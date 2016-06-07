lie-pretransform
=====

[lie](https://github.com/calvinmetcalf/lie), but with its Browserify transforms
applied as a build step. So it doesn't assume you're using Browserify.

Benefits: even without Browserify, transforms will be applied to remove `process.browser`
switches and make Lie smaller where appropriate.

This builds both a Node-optimized version and a browser-optimized version. It chooses which
one to use based on the `"browser"` field.
