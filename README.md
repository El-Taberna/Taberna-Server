# Taberna Server

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/5c4a9e46064942f68a68574aa98d56fa)](https://app.codacy.com/gh/El-Taberna/Taberna-Server?utm_source=github.com&utm_medium=referral&utm_content=El-Taberna/Taberna-Server&utm_campaign=Badge_Grade_Settings)

Taberna server is the package of Taberna Modpack compiled in server file ready to start them.
He can be use to create your own private or public server with the Taberna Launcher.

## Requirement 

-   The server required `3Go` of Ram
-   Java `8` or Newer
-   The last update of the server package

## Installation

Download the [last update](https://github.com/El-Taberna/Taberna-Server/archive/v5.3.1.zip) to start the server.

## Usage

### On Windows

-   Unzip your file
-   start run.bat

### On Linux

-   In `Root` write in your bash :

```bash
sudo apt update && upgrade
```

```bash
sudo apt install openjdk-8-jre-headless screen
```

```bash
sudo adduser minecraft
```

-   Now you need to connect on minecraft

```bash
su minecraft
```

-   Upload last update of server files in `/home/minecraft/`
-   Create `Run.sh` and paste this inside `/home/minecraft/`

```bash
#!/bin/sh

java -Xms1024M -Xmx3072M -jar minecraft_server.jar -o true
```

-   Make `Run.sh` executable

```bash
chmod +x /home/minecraft/run.sh
```

-   To start your server :

``` bash
screen /home/minecraft/run.sh
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
