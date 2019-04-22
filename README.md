# MerakiDashboardAPILib

This API SDK was automatically generated by [APIMATIC Code Generator](https://apimatic.io/).

## Installation

The SDK relies on [Node Package Manager](https://www.npmjs.com/) (NPM) being available to resolve dependencies.
Once published you will need copy the folder `merakidashboardapilib` in to your `node_modules` folder.

## Usage

The following shows how import and use the controller:

1. Import the module:

    ```js
    var merakidashboardapilib = require('merakidashboardapilib');
    ```

2. Configure any authentication parameters. For example:

    ```js
    var config = merakidashboardapilib.configuration;
    config.apikey = a_secret_key;
    ```

3. Access various controllers by:

    ```js
    var controller = merakidashboardapilib.XYZ;
    controller.getItems(id, callback);
    ```
