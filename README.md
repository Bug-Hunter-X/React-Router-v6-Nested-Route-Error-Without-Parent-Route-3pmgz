# React Router v6 Nested Route Error

This repository demonstrates a common error in React Router v6: attempting to define a nested route without a parent route.  The error occurs because React Router needs a parent route to correctly resolve nested routes. 

## To reproduce the error:

1. Clone this repository.
2. Run `npm install`
3. Run `npm start`

You'll observe an error in the browser's console related to React Router's inability to resolve the nested route. 

## Solution:

The solution involves ensuring that each nested route has a parent route. See `bugSolution.js` for the corrected code.
