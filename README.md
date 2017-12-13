# gimme-that-shiz
Get the things. You know, that thing that I put in that place that time? Yeah, that one.

## Usage

### Modifiable Variables
- `TARGET_BIN` The name of the binary to be checked.
- `TARGET_INSTALL_PATH` The local path to install the binary to (defaults to `/usr/local/bin`)
- `TARGET_GITHUB_USER` The GitHub user of the target repo
- `TARGET_GITHUB_REPO` The GitHub repo name of the target repo

Pass any modified variables to the command and run it.
E.G.:

```shell
TARGET_BIN=confd TARGET_GITHUB_USER=kelseyhightower TARGET_GITHUB_REPO=confd gimme.sh
```

These variables may also be exported.
