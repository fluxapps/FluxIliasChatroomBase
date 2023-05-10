# flux-ilias-chatroom-base

ILIAS base chatroom docker image

First look at [flux-ilias](https://github.com/fluxfw/flux-ilias)

The follow environment variables are available

| Variable | Description | Default value |
| -------- | ----------- | ------------- |
| ILIAS_COMMON_CLIENT_ID | Client name | default |
| ILIAS_FILESYSTEM_DATA_DIR | Path to data directory<br>This is a volume | /var/iliasdata |
| ILIAS_WEB_DIR | Path to ILIAS source code | /var/www/html |
| ILIAS_CHATROOM_CLIENT_CONFIG_FILE | Path to client config file | *%ILIAS_FILESYSTEM_DATA_DIR%*/*%ILIAS_COMMON_CLIENT_ID%*/chatroom/client.cfg |
| ILIAS_CHATROOM_SERVER_CONFIG_FILE | Path to server config file | *%ILIAS_FILESYSTEM_DATA_DIR%*/*%ILIAS_COMMON_CLIENT_ID%*/chatroom/server.cfg |

Minimal variables required to set are **bold**
