# Karma-jasmine-imagediff

## by Chris Finch

> Dirty adapter for using [js-imagediff](https://github.com/HumbleSoftware/js-imagediff) with [Karma and require.js](https://npmjs.org/package/karma-requirejs)

See here for getting Karma running with Require: https://github.com/karma-runner/karma-requirejs

If you are using require and they try to include the imagediff files in the test runner browsers you will see that the node require calls in the imagediff code conflict with the Require.js require calls in the testing code. This adapter allows you to import the imagediff api in to karma/jasmine without coflicts.

Requires [lib cairo](https://github.com/LearnBoost/node-canvas/wiki/_pages) to be installed for the  node package to work. `brew install cairo` works well. You may also need dependancies of cairo `brew install fontconfig`...

If anything fails read the wiki here to instructions for your OS: https://github.com/LearnBoost/node-canvas/wiki/_pages

### License - MIT

Copyright (C) 2013 Chris Finch

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
