### Pods Used:
* Alamofire
* MBProgressHUD

### Notes
Open Podfile using Xcode for editing ```open -a Xcode Podfile```

Add Pod to Podfile (again, remember to open using Xcode)

Install via terminal ```pod install```


Using installed pods and build project (⌘ + B) ```import Pod-name```

### Semantic Versioning used with all pods:
For Example,
```pod 'MBProgressHUD', '~> 1.0'```
* version 1.0.0 is the major, minor, patch numbers
* ~> 1.0 means to install version greater than or equal to 1.0 but less than 2.0
* this means, latest bug fixes and features will be included but we won't have to worry about backwards-incompatible changes

#### More
* major number are non-backwards compatible
* minor is new functionality and is back compatible
* patch are bug fixes with no new functionality or behaviour changes
* less than 1.0.0 is consider beta version, and minor number increases _may_ incl. backwards imcompatible changes
