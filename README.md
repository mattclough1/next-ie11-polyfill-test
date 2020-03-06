# Testing
1. Project was initialized with `npm init next-app`.
2. Polyfills were added according to the [with-polyfills](https://github.com/zeit/next.js/tree/canary/examples/with-polyfills) example.
3. Added an undefined component (`<NonExistentComponent />` in `pages/index.js`) to jsx.
4. Note that in Chrome, we see the usual `ReferenceError: NonExistentComponent is not defined` error.
5. Note that in IE11, we see the server-rendered error, but on client render the screen goes white, and the console reads `SCRIPT438: Object doesn't support property or method 'repeat'`
