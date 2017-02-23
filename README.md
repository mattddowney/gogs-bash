gogs-bash
=========

Interact with the [GOGS](https://gogs.io/) API from bash.

Create repositories and manage webooks.

Setup:
------

Set the following environment variables:

* GOGS_ROOT_URL - The url of the GOGS server (IE: http://try.gogs.io)
* GOGS_TOKEN - Access token obtained from GOGS (http://try.gogs.io/user/settings/applications)

Usage:
------

```
$ ./gogs
./gogs is a tool for interacting with the GOGS API.

Usage:
    ./gogs command [arguments]

The commands are:

    create-repo     create a repository
    create-webhook  create a webhook
    delete-webhook  delete a webhook
    env             print environment information
    get-webhooks    get a list of webhooks for a repo

Use "./gogs help [command]" for more information about a command.
```
