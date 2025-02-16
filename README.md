# Dart JSON Parsing - IndexOutOfBoundsException

This repository demonstrates a common error in Dart when parsing JSON data from an API:  an `IndexOutOfBoundsException` due to accessing an array index that's out of bounds. The `bug.dart` file contains the erroneous code, and `bugSolution.dart` provides the corrected version.

The problem arises when the code assumes a certain number of elements in the JSON response array without checking. If the server returns fewer elements than expected, an exception is thrown.

The solution involves adding error handling to check the length of the array before accessing any index, preventing the exception.

## How to run
1. Clone this repository
2. Run `bug.dart` to observe the error
3. Run `bugSolution.dart` to see the corrected code
