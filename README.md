# Testing
Project was initialized with `npm init next-app`. Polyfills were added according to the [with-polyfills](https://github.com/zeit/next.js/tree/canary/examples/with-polyfills) example. Attempting to render an non-existent component (`<NonExistentComponent />` in `pages/index.js`) throws error `SCRIPT438: Object doesn't support property or method 'repeat'` on client render.
