# py_javahome

A python utility to emulate java_home util from macOS on linux

Current behavior

- with no arguments, prints the current default Java home
- with a `--version` argument, it tries to select a matching version. If none exists, uses the default one (failfast unimplemented).
- with the `--exec` argument, it runs the command after it.