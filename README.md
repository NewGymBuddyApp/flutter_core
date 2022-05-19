[![TEST](https://github.com/NewGymBuddyApp/flutter_core/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/NewGymBuddyApp/flutter_core/actions/workflows/test.yml)

# flutter-core
_Package containing core elements of all apps developed within
the company. Designed for internal use only._

## Prerequisites
```yaml
environment:
  sdk: ">=2.17.0 <3.0.0"
  flutter: ">=1.17.0"
```

## Installation

Add the following snippet to your `pubspec.yaml` file:
```yaml
  flutter_core:
    git:
      url: https://github.com/NewGymBuddyApp/flutter_core.git
```


## Usage
- Following the documentation:
  - `DataModel` - an abstract class used to standardise models used within the application
  - `ListStore` - A facade over lists allowing more advanced operations to be handled internally without the need for lists to clutter their containing models.
