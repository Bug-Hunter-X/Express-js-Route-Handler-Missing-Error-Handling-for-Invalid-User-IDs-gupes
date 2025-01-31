# Express.js Route Handler Missing Error Handling for Invalid User IDs

This repository demonstrates a common error in Express.js route handlers: the lack of proper error handling for invalid input.  The `bug.js` file shows a route that attempts to parse a user ID as an integer without checking for potential errors. This can lead to crashes or unexpected behavior if the ID is not a number.

The `bugSolution.js` file provides a corrected version with proper error handling, showcasing best practices for handling such scenarios.