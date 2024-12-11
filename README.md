# Tailwind CSS SSR Error: Directives/Classes Not Applied

This repository demonstrates a common error encountered when using Tailwind CSS with server-side rendering (SSR) frameworks like Next.js or Nuxt.js.  The issue arises when Tailwind's directives or classes fail to apply correctly during the server-side rendering process, resulting in missing styles or runtime errors in the browser.

## Problem
The `bug.js` file shows an example of a Next.js component where Tailwind classes are not properly applied due to an improper Tailwind CSS setup for SSR. This leads to styling issues on the client-side.

## Solution
The `bugSolution.js` file presents the corrected component with the necessary adjustments to ensure Tailwind's directives and classes are correctly applied during SSR.  This involves appropriate configuration and potentially using `@apply` directives where necessary.

## How to Reproduce
1. Clone this repository.
2. Run `npm install` to install dependencies (if needed).
3. Run the project (according to the framework's instructions).  Observe the styling issues in the browser. 
4. Compare `bug.js` and `bugSolution.js` to understand the solution.

This example demonstrates a common pitfall of SSR with Tailwind CSS and highlights the importance of correctly configuring Tailwind for this purpose.