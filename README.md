# tools-aquaproj

Tools - aquaproj/aqua - Repository gestion de configuration des registries aqua pour différents profils

## What's aqua?

aqua is a Declarative CLI Version Manager written in Go.

https://aquaproj.github.io/

## GitHub Access Token is required

Please set your GitHub Access Token as the environment variable `GITHUB_TOKEN` or `AQUA_GITHUB_TOKEN`.

### Use as Global Configuration

About Global Configuration, please see the document.

- https://aquaproj.github.io/docs/tutorial/global-config
- https://aquaproj.github.io/docs/guides/team-config

Checkout this repository and set the environment variable `AQUA_GLOBAL_CONFIG`.

```console
$ git checkout https://github.com/<REPO_OWNER>/<REPO_NAME>
## Pour l'ensemble des collaborateurs :
$ export AQUA_GLOBAL_CONFIG=$PWD/<REPO_NAME>/aqua-all.yaml:$AQUA_GLOBAL_CONFIG
```

## LICENSE

[MIT](LICENSE)
