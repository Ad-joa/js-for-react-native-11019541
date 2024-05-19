# js-for-react-native-11019541

11019541

## Task Summaries

**Task 1: arrayManipulation.js - processArray**

* Creates a function `processArray` that takes an array of numbers.
* The function iterates through the array and squares even numbers, triples odd numbers.
* It returns a new array containing the modified elements.

**Task 2: arrayManipulation.js - formatArrayStrings**

* Creates a function `formatArrayStrings` that takes two arrays.
  - The first array contains strings.
  - The second array contains numbers (presumably processed by `processArray`).
* The function checks if both arrays have the same length (to ensure correspondence).
* It iterates through both arrays, modifying the strings based on the corresponding numbers:
  - Capitalizes the entire string if the number is even.
  - Converts the string to lowercase if the number is odd.
* It returns a new array containing the formatted strings.

**Task 3: userInfo.js - createUserProfiles**

* Creates a function `createUserProfiles` that takes two arrays.
  - The first array contains original names.
  - The second array contains modified names (presumably from `formatArrayStrings`).
* The function checks if both arrays have the same length.
* It initializes an empty array to store user objects.
* It iterates through both arrays, creating user objects with the following properties:
  - `id`: An auto-incrementing ID starting from 1.
  - `originalName`: The original name from the input array.
  - `modifiedName`: The modified name from the second input array.
* It returns an array containing the user objects.
