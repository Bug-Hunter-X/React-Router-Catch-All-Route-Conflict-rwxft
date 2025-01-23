# React Router Catch-All Route Conflict

This repository demonstrates a common issue in React Router v6: conflicts between a catch-all route (`/*`) and other, more specific routes. The catch-all route unintentionally intercepts requests intended for other routes, leading to incorrect rendering or unexpected behavior.  The solution involves carefully ordering routes within the `Routes` component.