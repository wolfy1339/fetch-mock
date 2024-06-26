---
title: Versions
position: 1
content_markdown: |-
  Note that the documentation below refers to **version 9** of the library.

  Version 10 is a significant rewrite and should just work in any environment where `fetch` is available natively. It's relatively untested, so if it doesn't work for you please raise an issue, then downgrade to version 9 and follow the usage documentation below. 

  - [Node.js](https://Node.js.org/) 8+ for full feature operation
  - [Node.js](https://Node.js.org/) 0.12+ with [limitations](http://www.wheresrhys.co.uk/fetch-mock/installation)
  - [npm](https://www.npmjs.com/package/npm) (normally comes with Node.js)
  - Either
    - [node-fetch](https://www.npmjs.com/package/node-fetch) when testing in Node.js. To allow users a choice over which version to use, `node-fetch` is not included as a dependency of `fetch-mock`.
    - A browser that supports the `fetch` API either natively or via a [polyfill/ponyfill](https://ponyfoo.com/articles/polyfills-or-ponyfills)

  Check out the new [cheatsheet](https://github.com/wheresrhys/fetch-mock/blob/master/docs/cheatsheet.md)
  {: .info}
---
