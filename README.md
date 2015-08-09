RGCaseErrorDetect
============

RGCaseErrorDetect helps you spot mispelled asset names while you're still running in the simulator.

iOS and Android are case sensitive while OS X and Windows are not.  Often  (new and old) users will accidentaly get the case of a file name wrong.  The misnamed resource will be found on the simulator, but when you build and run on a device you get a mysterious crash or error.

This utility will print warnings in the console, and you (optionally) promote warnings to errors, a dialog will pop up too.

NOTE: The library comes with a sample for you to run and fix based on the warnings you will get


Basic Usage
-------------------------

##### Require the code
```lua
local ced = require "RGCaseErrorDetect"
```

##### Optionally Promote Warnings To Errors
```lua
ced.promoteToError()
```
