# Server-Side Rendering for React
Based on: https://flaviocopes.com/react-server-side-rendering/

## Requirements
All the Node.js code needs to be transpiled by Babel, as server-side Node.js code does not know anything about JSX, nor ES Modules (which we use for the include statements).

Install these 3 packages:

npm install @babel/register @babel/preset-env @babel/preset-react ignore-styles express

ignore-styles is a Babel utility that will tell it to ignore CSS files imported using the import syntax.

