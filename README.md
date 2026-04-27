# LOGZ InfoCommands

LOGZ InfoCommands is a CounterStrikeSharp / CS2 plugin that adds public information commands for LOGZ Romania servers.

## Current Version

```txt
1.2.0
```

## Commands

```txt
!forum
!fondator
!fondatorul
!admins
!ts
!discord
!admin
css_logzinfo_version
css_logzinfo_info
css_logzinfo_license
```

## New in v1.2.0

- added LOGZ proprietary license header
- added `LICENSE.md`
- added `version.txt`
- added `WebsiteUrl`
- added `GithubUrl`
- added `VersionUrl`
- added `LicenseName`
- added version/info/license commands
- removed `PlayerConnectedState.PlayerConnected` check for better API compatibility

## version.txt

Recommended format:

```txt
1.2.0
https://github.com/MartyCSGO/LOGZ_InfoCommands
```

Config raw URL:

```json
"VersionUrl": "https://raw.githubusercontent.com/MartyCSGO/LOGZ_InfoCommands/main/version.txt"
```

If your GitHub branch is `master`, use:

```json
"VersionUrl": "https://raw.githubusercontent.com/MartyCSGO/LOGZ_InfoCommands/master/version.txt"
```

## Important

`css_admins` may conflict with `LOGZ_Admin` if both plugins register the same command.

Recommended setup:

- keep `!admins` in `LOGZ_Admin`, or
- keep `!admins` in `LOGZ_InfoCommands`, but remove/disable the duplicate from `LOGZ_Admin`

Do not keep duplicate command registration if your server shows command conflicts.

## License

This project is licensed under the LOGZ Romania Proprietary License.

See `LICENSE.md`.
