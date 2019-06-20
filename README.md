# Truffle artifact error example

Running `truffle compile` with an empty artifact file in the `build/contracts`folder results in the following error:

```
SyntaxError: Unexpected end of JSON input
    at JSON.parse (<anonymous>)
    at async.map (truffle/build/webpack:/packages/truffle-compile/profiler.js:83:1)
    at truffle/build/webpack:/packages/truffle-compile/~/async/dist/async.js:1140:1
    at truffle/build/webpack:/packages/truffle-compile/~/async/dist/async.js:473:1
    at iteratorCallback (truffle/build/webpack:/packages/truffle-compile/~/async/dist/async.js:1064:1)
    at truffle/build/webpack:/packages/truffle-compile/~/async/dist/async.js:969:1
    at truffle/build/webpack:/packages/truffle-compile/~/async/dist/async.js:1137:1
    at fs.readFile (truffle/build/webpack:/packages/truffle-compile/profiler.js:74:1)
    at FSReqWrap.readFileAfterClose [as oncomplete] (internal/fs/read_file_context.js:53:3)
```
