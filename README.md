# CastleDB Unity Importer
Define all your data in the external CastleDB software and enjoy macro-like intellisense for your data inside your code editor

## How it works

* When you update the CastleDB file, the types will be reimported and everything in your path will be deleted.

## Implementation

## Limitations
* Currently there is no validation of column names, so column names in CastleDB need to be valid field names in C#. I.E. don't use spaces in your column names, weird characters, etc.
* All sheets need to have some sort of GUID column that defines the name of a row. This defaults to "id" with a string type.


## TODO
* Add in Color support
* Figure out a better guide for adding CastleDB Custom Trypes
* Document way to add in your own CustomType to match with a predefined Type in Unity
* Rebuilt DLL doesn't have new columns
* Unclear how references are supposed to work in CastleDB

## Custom Types