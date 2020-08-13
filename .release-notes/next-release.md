## Use `XDG_DATA_HOME` for install prefix in init script when set

The `ponyup_init.sh` script will now set the default install prefix to the `XDG_DATA_HOME` environment variable if the variable is set.

## Select uses latest version if none is specified

The select command will now link the latest installed version of a given package by default. For example, if `ponyc-release-0.36.0-x86_64-linux-gnu` is the latest release version of ponyc installed then it can now be selected with the command `ponyup select ponyc release` or the command `ponyup select ponyc release-latest`.