# elm-dependabot-repro

One Elm application per compiler version, each with its own Dependabot job. The Build workflow compiles each folder with its own compiler.

| Folder | `elm-version` | 0.19.1-only package |
| --- | --- | --- |
| `elm-0.19.0` | 0.19.0 | no |
| `elm-0.19.1` | 0.19.1 | `obiloud/numeric-decimal` |
| `elm-0.19.2` | 0.19.2 | `obiloud/numeric-decimal` |
| `elm-0.19.3` | 0.19.3 | `obiloud/numeric-decimal` |

All pin `justinmimbs/date` at 4.0.1, so 4.1.0 is an available update.
