# Kanata-Service
A macOS launchctl wrapper to run [kanata-tray](https://github.com/rszyma/kanata-tray) on startup as a daemon.

This service was previously (see commit [6a5bdb2](https://github.com/jussapaavo/kanata-service/tree/6a5bdb22f8d2ccff183c7619f19e06eb7f267151)) used to install [kanata](https://github.com/jtroo/kanata) directly instead.

## Manual
```sh
$ kanata-service help
```
```
Usage:
    Installation: kanata-service install <kanata_binary>
    Other: kanata-service <command>

Available commands:
    1. install - installs the launchd plist file & and adds kanata-tray to sudoers.d
    2. uninstall - deletes the launchd plist file & removes the kanata-tray sudoers.d
    3. start - starts the service
    4. stop - stops the service
    5. restart - restarts the service
    6. info - prints properties of the launchd service
    7. debug - concatenates the stderr.log to stdout"
```
