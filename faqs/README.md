
# FAQs


## Que:1 Is it possible to pass some configuration parameters when installing an extension?

No, it's not. The users can either install the extension from the ui or using the cli. In any case there is no way to pass options when installing.
It is possible to chose the version of the extension in the CLI though: ```docker install foo/bar:0.0.1``` installs the version 0.0.1 of the extension.


## Que:2 Is it a best practice to expose pre-defined ports?

No, it is not recommended, as it could conflict with other installed extensions or apps running on the host. 
You should favor using sockets as it is done in the generated extension when using the ```docker extension init``` command.

## Que:3 Is there a way to list the container associated with the extension?

Yes, it's possible but you must filter containers by a known criteria.
For example, if you want to get the extension’s container, they have the same com.docker.compose.project label.

You can try the following from the command line, it will display extension containers if the setting is disabled:

```
docker container ls --filter "label=com.docker.compose.project=<your extension label>"
```

That means you can totally do the same with the sdk:

```
await ddClient.docker.cli.exec('container', ['ls', '--filter', 'label=com.docker.compose.project=<your extension label>']);
```

Please note that in order to find the value of the label, you can use docker inspect on your extension container.



