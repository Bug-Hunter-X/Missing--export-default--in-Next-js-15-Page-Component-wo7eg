# Missing `export default` in Next.js 15 Page Component

This repository demonstrates a common error in Next.js 15: forgetting to export the default component from a page file.

## Bug

The `pages/about.js` file is missing the `export default` statement, which causes Next.js to throw an error when trying to render the page.

## Solution

Adding the `export default` statement to the `pages/about.js` file fixes the error.

## How to reproduce

1. Clone this repository.
2. Run `npm install` to install the dependencies.
3. Run `npm run dev` to start the development server.
4. Navigate to `/about` in your browser. You should see an error.
5. Apply the fix in `bugSolution.js` and restart the development server. The error should be resolved, and you'll be able to view the about page.