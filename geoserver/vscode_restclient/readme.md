# GeoServer helper files for REST client extension of VS Code

The files provided in this folder are meant to be used with the REST client extension (https://github.com/Huachao/vscode-restclient).

Files are organized by main endpoint categories.

Each file defined on top several variables which are used in the different requests. There are always at least two variables:
- The `geoserver_url` variable must point to the root URL of the REST API (before the `/rest`)
- The `credential` variable must provide the credentials of the account to authenticate against. The files uses a Basic Auth so the variable must follow the syntax `login:password`

By default, their valu.e is retrieved from variables defined in the extension environments (to configure in the settings.json file of VS Code)