# Silent Failure: Modifying innerHTML of Non-Existent Element

This repository demonstrates a common, yet often silent, bug in HTML/JavaScript. The bug involves attempting to modify the `innerHTML` property of a DOM element that doesn't exist. This usually results in a JavaScript error that may not be easily caught, making debugging challenging.

The `bug.html` file showcases the error. The `bugSolution.html` file provides a corrected version.

## Bug Description:
The script attempts to access an element with id "nonExistentDiv", which doesn't exist in the HTML structure.  This results in a runtime error that may not be explicitly displayed in some browsers.