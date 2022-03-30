# File sysynchronization service in windows

1. run syncthing as a server
2. checkout https://github.com/syncthing/syncthing/releases
3. checkout https://github.com/winsw/winsw


# Usage

1. Clone the proejct into c:/

```shell
git clone https://github.com/chet-cloud/win-syncthing-service.git c:/syncthing
```

2.  generate config

```shell
syncthing.exe generate --home c:\syncthing\config
```

3. Install, start, stop, status, and restart the service

    - open cmd.exe and switch to the directory - c:/syncthing

    - input the following commands

```shell
    syncthing-service install
    syncthing-service start
    syncthing-service stop
    syncthing-service status
    syncthing-service restart
```

or You can open the Services (win+run>services.msc) and operate on syncthing service after install the service