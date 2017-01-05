# android-location-provider-states
An Android module for Titanium. Reports to the Javascript side the status of the GPS Provider and the Network Provider.

Use ```android.permission.ACCESS_FINE_LOCATION``` and ```android.permission.ACCESS_COARSE_LOCATION```, respectively.

Usage:
```
var androidisgpson = require("com.restadoapp.androidisgpson");

var gps_enabled = androidisgpson.getGPSState(); //boolean
var networks_allowed = androidisgpson.getNetworkProviderState(); //boolean
