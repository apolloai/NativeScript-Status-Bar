# Apollo.ai NativeScript StatusBar plugin

A fork of https://github.com/PeterStaev simple NativeScript plugin for controlling status bar visibility.

## Installation

Run the following command from the root of your project:

`tns plugin add apolloai-nativescript-status-bar`

This command automatically installs the necessary files, as well as stores apolloai-nativescript-status-bar as a dependency in your project's package.json file.

## API

```TypeScript
// Get reference to the Status Bar plugin module
import statusBar = require("apolloai-nativescript-status-bar");
```

For Angular:
```TypeScript
// Get reference to the Status Bar plugin module
import * as statusBar from 'apolloai-nativescript-status-bar'
```

* **show()**  
Shows the status bar.

* **hide()**  
Hides the status bar.
