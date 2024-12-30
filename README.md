# Next.js 15 App Router Unexpected Token '<' Error

This repository demonstrates a bug in Next.js 15's App Router where a simple component throws an unexpected token error. The error occurs when using the app directory structure and a basic component that doesn't involve any dynamic features.

## Bug Description

When using the `app` directory structure in Next.js 15 and rendering a simple component like the one shown in `bug.js`, an error is thrown:

> Error: Unexpected token '<'

This error is unexpected, as the component is basic and should render without issues.  The error suggests the router isn't correctly handling the component's JSX.

## Solution

The solution might involve ensuring the proper configuration of Next.js and its dependencies, or it could be a bug that needs to be reported to the Next.js team. The provided solution in `bugSolution.js` is a placeholder, and actual fix might need additional investigation.