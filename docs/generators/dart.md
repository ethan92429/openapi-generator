---
title: Config Options for dart
sidebar_label: dart
---

| Option | Description | Values | Default |
| ------ | ----------- | ------ | ------- |
|sortParamsByRequiredFlag|Sort method arguments to place required parameters before optional parameters.| |true|
|sortModelPropertiesByRequiredFlag|Sort model properties to place required parameters before optional parameters.| |true|
|ensureUniqueParams|Whether to ensure parameter names are unique in an operation (rename parameters that are not).| |true|
|allowUnicodeIdentifiers|boolean, toggles whether unicode identifiers are allowed in names or not, default is false| |false|
|prependFormOrBodyParameters|Add form or body parameters to the beginning of the parameter list.| |false|
|browserClient|Is the client browser based (for Dart 1.x only)| |null|
|pubName|Name in generated pubspec| |null|
|pubVersion|Version in generated pubspec| |null|
|pubDescription|Description in generated pubspec| |null|
|pubAuthor|Author name in generated pubspec| |null|
|pubAuthorEmail|Email address of the author in generated pubspec| |null|
|pubHomepage|Homepage in generated pubspec| |null|
|useEnumExtension|Allow the 'x-enum-values' extension for enums| |null|
|sourceFolder|Source folder for generated code| |null|
|supportDart2|Support Dart 2.x (Dart 1.x support has been deprecated)| |true|
