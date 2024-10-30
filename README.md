<!-- # [ zrfisaac ] -->

<!-- # [ about ] -->
<!-- # - author : Isaac Caires -->
<!-- # . - email : zrfisaac@gmail.com -->
<!-- # . - site : zrfisaac.github.io -->

<!-- # [ markdown ] -->
# LkJSON 1.3.0

- **Original Author:** Leonid Koninin
- **Current Maintainer:** Isaac Caires
- **License:** Freeware
- **Original Project Link:** LkJSON on SourceForge

## Overview

**LkJSON** is a Delphi library developed by Leonid Koninin for parsing and managing JSON data structures. This library provides a lightweight, efficient way to handle JSON objects, making it easier for developers to work with JSON within Delphi applications.

## Key Features
- **Lightweight JSON Handling:** Built for efficiency and ease of use.
- **Simple API:** Minimal learning curve, easy to integrate into existing Delphi projects.
- **Full JSON Support:** Supports reading, writing, and manipulating JSON data structures, making it ideal for REST API responses, configuration files, and more.
- **Source Code Available:** The library includes full source code, making it easy to customize and extend for specific use cases.

## Compatibility

LkJSON is compatible with various Delphi versions, though specific compatibility details may vary based on the project configuration and Delphi edition.

## Installation
- **Download the Library:** The original version of LkJSON can be found on [SourceForge](https://sourceforge.net/projects/lkjson/files/lkJSON/).
- Add to Delphi Project:
  - In Delphi, go to **Tools > Options > Delphi Options > Library**.
  - Add the LkJSON source directory to the Library Path.
- **Compile and Use:** Open the LkJSON package file in Delphi, compile the units, and add them to your project as needed.

## Basic Usage

To get started with LkJSON, follow these basic steps to parse and create JSON objects.

- **Parse JSON:**
```delphi
var
  JSON: TlkJSONobject;
begin
  JSON := TlkJSON.ParseText('{ "key": "value" }') as TlkJSONobject;
  // Access values using JSON object properties
end;
```

- **Create JSON:**
```delphi
var
  JSON: TlkJSONobject;
begin
  JSON := TlkJSONobject.Create;
  JSON.Add('key', TlkJSONstring.Create('value'));
end;
```

For a more comprehensive guide, refer to the examples in the source code and sample projects.

## Additional Information

This repository is now maintained by Isaac Caires, who started working from the original [SourceForge](https://sourceforge.net/projects/lkjson/files/lkJSON/) project. Future updates will enhance performance, compatibility, and extend the functionality of LkJSON to meet evolving project needs.
