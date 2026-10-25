# tgshaders-updates

Public version file for [TG Shaders](https://threatjpn.gumroad.com/l/tgshaders).

KSM Editor reads `version.txt` from here (at most once a day) and, when it names a newer version than the one
installed, shows players a banner linking to the store.

```
version = 1.1.0
notes = one line shown in the banner
```

Update it only after the new release is on Gumroad. The source of truth is `release/version.txt` in the
main repo; `make-release.ps1` copies it to `dist\version.txt`.
