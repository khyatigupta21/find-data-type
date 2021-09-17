# Find data type of input parameter

This repository contains a javascript code to find the data type of input parameter whether it is Number, String, Boolean, Function, Object, Array, Undefined or Null. Below is the algorithm to achieve the result.

## Algorithm

- Step 1: Enter parameter
- Step 2: If parameter is =="null"  Return "Null is not allowed"
- Step 3: If parameter is =="undefined" : Return "Please enter a value"
- Step 4: If parameter typeof is "String" : Return "String"
- Step 5: If parameter typeof is "Number" : Return "Number"
- Step 6: If parameter typeof is "Boolean" : Return "Boolean"
- Step 7: If parameter instanceOf is "Object" and instanceOf is "Array" :  Return "Array"
- Step 8: If parameter instanceOf is "Object" and Not instanceOf is "Array" : Return "Object"
- Step 9: If parameter typeof is "Function"  Return "Function"

