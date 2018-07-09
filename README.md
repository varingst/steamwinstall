```
steamwinstall: Download Windows steam games while on Linux
A convencience wrapper around steamcmd.sh

Usage: steamwinstall -u STEAMUSR -d STEAMDIR [-c STEAMCMD] APPID|GAME

APPID is the Steam app id
GAME is a search string to find the appid using steamdb.info

Options:
  -u, --user STEAMUSR           Steam username to log in as
  -d, --dir STEAMDIR            Windows steam library directory,
                                usually the Steam installation directory
  -c, --cmd STEAMCMD            Path of steamcmd.sh
  -h, --help                    Print this help text and exit

If not provided, STEAMCMD is assumed to be ~/.steam/steam/steamcmd.sh
```
