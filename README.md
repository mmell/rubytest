## Setup
1. Clone this repository into a `public` repository in your github account
1. Follow the test instructions below.

## Instructions

 1. Create a new branch named **step_1**.
    - Create a simple String calculator with a method `add(numbers)` that takes a string.
    - The method can take 0, 1 or 2 numbers, and will return their sum (for an empty string it will 
    return 0) for example ```""``` or ```"1"``` or ```"1,2"```.
    - Start with the simplest test case of an empty string and move to 1 and two numbers.
    - Commit with the comment **Step 1** and push this branch.
    
 1. Create a new branch based on step_1 named **step_2**.
    - Allow the `add` method to handle an unknown amount of numbers. 
    - Commit with the comment **Step 2** and push this branch.
    
 1. Create a new branch based on step_2 named **step_3**.
    - Allow the `add` method to handle new lines between numbers (instead of commas).
    - the following input is ok: ```1\n2,3``` (will equal 6).
    - the following input is NOT ok: ```1,\n```.
    - Make sure you only test for correct inputs. There is no need to test for invalid inputs.
    - Commit with the comment **Step 3** and push this branch.

 1. Create a new branch based on step_3 named **step_4**.
    - Allow the `add` method to handle a different delimiter:
    - to change a delimiter, the beginning of the string will contain a separate line that looks like 
    this: ```//[delimiter]\n[numbers…]``` for example ```//;\n1;2``` should return three where the 
    default delimiter is ```;``` .
    - the first line is optional. all existing scenarios should still be supported
    - Commit with the comment **Step 4** and push this branch.
    
 1. Create a new branch based on step_4 named **step_5**.
    - Calling `add` with a negative number will throw an exception “negatives not allowed” – and 
    the negative that was passed. If there are multiple negatives, show all of them in the exception message. 
    - Commit with the comment **Step 5** and push this branch.
