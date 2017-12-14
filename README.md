Get the things. You know, that thing that I put in that place that time? Yeah, that one.

## Usage

### Modifiable Variables
- `TARGET_BIN` The name of the binary to be checked.
- `TARGET_INSTALL_PATH` The local path to install the binary to (defaults to `/usr/local/bin`)
- `TARGET_PROJECT` The GitHub user/repo to download from.

Pass any modified variables to the command and run it.
E.G.:

```shell
TARGET_BIN=ksync TARGET_PROJECT=vapor-ware/ksync gimme.sh
```

These variables may also be exported.
