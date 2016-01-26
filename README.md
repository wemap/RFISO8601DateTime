# RFISO8601DateTime

[![CI Status](http://img.shields.io/travis/readefries/RFISO8601DateTime.svg?style=flat)](https://travis-ci.org/readefries/RFISO8601DateTime)
[![Version](https://img.shields.io/cocoapods/v/RFISO8601DateTime.svg?style=flat)](http://cocoapods.org/pods/RFISO8601DateTime)
[![License](https://img.shields.io/cocoapods/l/RFISO8601DateTime.svg?style=flat)](http://cocoapods.org/pods/RFISO8601DateTime)
[![Platform](https://img.shields.io/cocoapods/p/RFISO8601DateTime.svg?style=flat)](http://cocoapods.org/pods/RFISO8601DateTime)

## Usage

Using is very easy, to parse an RFC3339 date/time string, just do the following.

```
let rfc3339DateTime = "1985-04-12T23:20:50.52Z"
let parsedDateTime = NSDate.parseDateString(rfc3339DateTime)
```

## Requirements

## Installation

RFISO8601DateTime is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "RFISO8601DateTime"
```

## Author

Hindrik Bruinsma, de@readefries.nl

## License

RFISO8601DateTime is available under the MIT license. See the LICENSE file for more info.
