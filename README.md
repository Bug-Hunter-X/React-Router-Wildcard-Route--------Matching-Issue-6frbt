# React Router Wildcard Route Issue

This repository demonstrates a common issue encountered when using wildcard routes ('/*') in React Router.  The wildcard route unintentionally intercepts all other route matches, resulting in an unexpected 404 page display.

The `App.js` file shows the problematic code, while `AppSolution.js` provides the corrected version. The solution involves proper ordering of routes within `Routes`.