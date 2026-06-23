# # String Compression-C

This is a C program that performs basic run-length encoding on a string. 
It compresses consecutive duplicate characters into the character followed by its count.

## Example
* **Input:** `"abbcccdddd"`
* **Output:** `a1b2c3d4`

## Concepts Used
* Array traversal with single loops
* Look-ahead logic (`array[i] == array[i+1]`)
* Conditional tracking
