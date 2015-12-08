# cordova-blockapps-js

blockapps-js polyfill for Cordova/PhoneGap


# How to use

Configure your plugin's plugin.xml by adding this dependency:

```
<dependency
  id="cordova-blockapps-js"
  url="https://github.com/kejace/cordova-blockapps-js.git">
</dependency>
```

Cordova CLI takes care to install cordova-blockapps-js automatically:

```
$ cordova plugins add {yourPlugin}

> Installing "{yourPlugin}" for {platform}
> Installing "cordova-blockapps-js" for {platform}
```

This is all. ```window.bajs``` is available for use in your plugin.
