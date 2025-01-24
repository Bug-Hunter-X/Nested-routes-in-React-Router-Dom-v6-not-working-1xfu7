# React Router Dom v6 Nested Routes Issue

This repository demonstrates a common issue encountered when working with nested routes in React Router Dom v6.  The problem involves nested routes failing to render correctly, even when seemingly defined appropriately.

## Problem Description

The provided `bug.js` file contains a simple React application utilizing React Router Dom v6. Despite the presence of nested routes, navigating to these routes doesn't render the expected components.  The issue is related to how nested routes are declared and handled in v6.

## Solution

The `bugSolution.js` demonstrates the corrected approach. Key changes involve ensuring that the nested `Routes` component is correctly placed and that the `path` values are correctly defined relative to the parent route.