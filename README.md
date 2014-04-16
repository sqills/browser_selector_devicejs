browser_selector_devicejs
=========================

Integrated Device.js and CSS browser selector in a Bower package.

## Usage

- Run `bower install` to install the dependencies
- Add the dependencies to the HEAD of your HTML with the following snippet:


    <script src="static/libs/css_browser_selector/css_browser_selector_dev.js"></script>
    <script src="static/libs/device-js/lib/device.js"></script>


## Configuration

You can overwrite settings by putting a variable in your HTML __before__ the particular library is loaded. See `test.html` for an example.

### Configure CSS browser selector

    var CSS_BROWSER_SELECTOR_CONFIG = {
        'showScreenSize': true
    };

#### Possible config variables:

- showScreenSize: add classes for screen size

### Configure Device.js

    var DEVICEJS_CONFIG = {
        'showOrientation': true
    };

#### Possible config variables:

- showOrientation: add classes for portrait or landscape


## Usage in new project (with Bower)

If you want to add this package in a new project you can use the following command to install it:

    bower install https://github.com/sq-template/browser_selector_devicejs.git

You can also add it as a dependency in the bower.json for the project:

    "dependencies": {
        "browser_selector_devicejs": "https://github.com/sq-template/browser_selector_devicejs.git"
    }

After you run `bower install` the package is installed in your project.