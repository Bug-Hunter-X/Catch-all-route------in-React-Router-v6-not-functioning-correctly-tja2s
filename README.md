# React Router v6 Catch-all Route Issue

This repository demonstrates a problem with the catch-all route (`/*`) in React Router v6.  The catch-all route is intended to handle any unmatched routes, but in this case, it's incorrectly intercepting all routes, including those explicitly defined.

The problem occurs when placing the catch-all route after other routes in the `Routes` component. The solution demonstrates how to correctly implement a catch-all route in React Router v6.