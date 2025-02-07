## [2.1.4+8] - August 9, 2022

* Automated dependency updates


## [2.1.4+7] - July 19, 2022

* Automated dependency updates


## [2.1.4+6] - July 12, 2022

* Automated dependency updates


## [2.1.4+5] - July 5, 2022

* Automated dependency updates


## [2.1.4+4] - June 28, 2022

* Automated dependency updates


## [2.1.4+3] - June 21, 2022

* Automated dependency updates


## [2.1.4+2] - June, 7, 2022

* Automated dependency updates


## [2.1.4+1] - May, 31, 2022

* Automated dependency updates


## [2.1.4] - May 9th, 2022

* Updated to restrict when to process when the content type explicitly tells us it is not JSON.


## [2.1.3] - April 25th, 2022

* Removed nullability from response values that should always have to be set.
* Fall back to returning the plain body when not proper JSON to allow the end user app to decide what to do.


## [2.1.2] - April 16th, 2022

* Disabled the isolate when running in debug mode due to a bug in the VS Code debugger that can cause the isolate to hang.
* Added the ability to disable the isolate to improve performance when it it is known that small responses will be encountered.


## [2.1.1] - March 27th, 2022

* Added `lookup` to `RequestMethod`.
* Renamed `language` to `accept-language`.
* Updated to remove empty headers.


## [2.1.0] - March 5th, 2022

* Switched authorizer to return a Future
* Added option to accept a binary response


## [2.0.1+7] - February 6th, 2022

* Dependency updates


## [2.0.1+6] - January 3rd, 2022

* Dart 2.15


## [2.0.1+5] - December 8th, 2021

* Dependency updates


## [2.0.1+4] - September 19th, 2021

* Dependency updates


## [2.0.1+3] - September 19th, 2021

* Dependency updates
* Flutter 2.5 analysis fixes


## [2.0.1+2] - May 29th, 2021

* Static analysis fixes


## [2.0.1+1] - April 11th, 2021

* Fix for issue #4
* Fix for issue #5


## [2.0.0] - March 7th, 2021

* Null Safety


## [1.0.6+2] - January 10th, 2021

* Dependency updates


## [1.0.6+1] - August 22nd, 2020

* Metadata


## [1.0.6] - August 22nd, 2020

* Rolling back to meta 1.1.8 due to `flutter_test` incompatiblities


## [1.0.5] - August 22nd, 2020

* Updated dependencies


## [1.0.4] - July 13th, 2020

* Updated dependencies


## [1.0.3] - June 11th, 2020

* Deprecated internal Jsonable class in favor of the [JsonClass](https://github.com/peiffer-innovations/json_class) package's version


## [1.0.2] - May 6th, 2020

* Minor fix to `parseDouble`


## [1.0.1] - April 16th, 2020

* Updated project metadata


## [1.0.0] - April 12th, 2020

* Initial release








