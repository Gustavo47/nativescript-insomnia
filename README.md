# NativeScript Insomnia

A plugin to make the screen not dim (and eventually lock the device).

## Installation
Run the following command from the root of your project:

```
tns plugin add nativescript-insomnia
```

## Usage

To use this plugin you must first require() it:

```js
var insomnia = require("nativescript-insomnia");
```

### keepAwake

```js
  insomnia.keepAwake().then(function() {
      console.log("Insomnia is active");
  })
```

### allowSleepAgain

```js
  insomnia.allowSleepAgain().then(function() {
      console.log("Insomnia is inactive, good night!");
  })
```