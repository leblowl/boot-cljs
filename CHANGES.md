## 0.0-3269-0 (17.5.2015)

- **Probably breaks stuff**: Updated to latest ClojureScript compiler
- **Might break stuff**: Uses shim created by cljs compiler
- **Breaking**: Removed \*.inc.js, \*.ext.js, \*.lib.js handling
  - Most of use cases are covered by [cljsjs](http://cljsjs.github.io/)
  - If you still need to add local js files to the build, you can add deps.cljs
  file to your local project
