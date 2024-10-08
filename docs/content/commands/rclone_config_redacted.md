---
title: "rclone config redacted"
description: "Print redacted (decrypted) config file, or the redacted config for a single remote."
versionIntroduced: v1.64
# autogenerated - DO NOT EDIT, instead edit the source code in cmd/config/redacted/ and as part of making a release run "make commanddocs"
---
# rclone config redacted

Print redacted (decrypted) config file, or the redacted config for a single remote.

## Synopsis

This prints a redacted copy of the config file, either the
whole config file or for a given remote.

The config file will be redacted by replacing all passwords and other
sensitive info with XXX.

This makes the config file suitable for posting online for support.

It should be double checked before posting as the redaction may not be perfect.



```
rclone config redacted [<remote>] [flags]
```

## Options

```
  -h, --help   help for redacted
```

See the [global flags page](/flags/) for global options not listed here.

## See Also

* [rclone config](/commands/rclone_config/)	 - Enter an interactive configuration session.

