Installs the latest github CLI [gh](https://github.com/cli/cli) for github actions
runners.  This is usually only helpful for self hosted runners which may not
have the CLI installed already.

# Usage

Add a step like this
```
      - name: Install github CLI
        uses: cresta/action-setup-github-cli
```
