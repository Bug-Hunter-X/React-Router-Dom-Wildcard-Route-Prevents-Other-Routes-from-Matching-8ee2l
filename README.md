# React Router Dom Wildcard Route Issue

This repository demonstrates a common issue with React Router Dom's wildcard route (`/*`). When a wildcard route is placed after other routes, it matches all paths, effectively preventing any other routes from ever being matched.  This results in the wildcard component always rendering. 

The solution demonstrates how to correctly order routes to avoid this issue.  Place wildcard routes at the end of your route definitions to resolve this.

## Setup

1. Clone the repository
2. Run `npm install`
3. Run `npm start`