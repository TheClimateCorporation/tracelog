# TraceLog

[![CI Status](http://img.shields.io/travis/tonystone/TraceLog.svg?style=flat)](https://travis-ci.org/tonystone/TraceLog)
[![Version](https://img.shields.io/cocoapods/v/TraceLog.svg?style=flat)](http://cocoadocs.org/docsets/TraceLog)
[![License](https://img.shields.io/cocoapods/l/TraceLog.svg?style=flat)](http://cocoadocs.org/docsets/TraceLog)
[![Platform](https://img.shields.io/cocoapods/p/TraceLog.svg?style=flat)](http://cocoadocs.org/docsets/TraceLog)


## Introduction
    
TraceLog is a runtime configurable debug logging system.  It allows flexible
configuration via environment variables at run time which allows each developer
to configure log output per session based on the debugging needs of that session.

When compiled in a RELEASE build, TraceLog is compiled out and has no overhead at
all in the application.

Log output can be configured globally using the `LOG_ALL` environment variable,
by CLASS name using the `LOG_CLASS_<CLASSNAME>` environment variable pattern,
and/or by a CLASS group by using the `CLASS_PREFIX_<CLASSPREFIX>` environment
variable pattern.

## Installation

TraceLog is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "TraceLog"
```

See the ["Using CocoaPods"](https://guides.cocoapods.org/using/using-cocoapods.html) guide for more information.

## Author

Tony Stone ([https://github.com/tonystone] (https://github.com/tonystone))

## License

TraceLog is released under the [Apache License, Version 2.0] (http://www.apache.org/licenses/LICENSE-2.0.html)

