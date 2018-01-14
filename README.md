# :sparkles: favorite-modules :sparkles:

My favorite node modules with a very brief explanation of the intent or use case.

#### [`after`](https://github.com/Raynos/after#readme)

Invoke callback after n calls.

#### [`async`](https://github.com/caolan/async)

Async swiss army knife for node and the browser.

#### [`chalk`](https://github.com/chalk/chalk#readme)

Colors and styling for the terminal.

#### [`commander`](https://github.com/tj/commander.js#readme)

CLI interfaces maded easy.

#### [`faucet`](https://github.com/substack/faucet) :white_check_mark:

Human readable `TAP` summarizer. Pipe output from e.g. `tape` to make the output purdier. Also useful if you have a gazillion tiny tests and you want a smaller more digestable test output.

#### [`hyperquest`](https://github.com/substack/hyperquest)

Streaming http request the right way. Much less bloated than `request`. Clean streaming interface.

#### [`jsonist`](https://github.com/rvagg/jsonist)

Perfect when you are using a `REST` api with `JSON` output. Uses `hyperquest` under the hood.

#### [`monotonic-timestamp`](https://github.com/dominictarr/monotonic-timestamp)

Monotonically increasing timestamps. Use instead of `Date.now()` to avoid getting identical timestamps on the same tick.

#### [`nodemon`](https://github.com/remy/nodemon) :wrench:

Monitor changes and restart processes. Use in place of `node`. Poor mans tdd: `alias tdd=nodemon -x npm test`

#### [`prebuild`](https://github.com/prebuild/prebuild) :wrench:

Creates prebuilt native modules and uploads to github.

#### [`prebuild-ci`](https://github.com/prebuild/prebuild-ci) :wrench:

Runs `prebuild` in your ci environment whenever a module has updated its version.

#### [`prebuild-install`](https://github.com/prebuild/prebuild-install) :wrench:

Downloads prebuilt binaries for native modules.

#### [`rc`](https://github.com/dominictarr/rc)

Dominic has solved the configuration problem once and for all. Provide default values for your config and override using command line arguments and/or configuration files and/or environment variables. Support for `.json` and `.ini` formats.

#### [`rimraf`](https://github.com/isaacs/rimraf#readme) :white_check_mark:

`rm -rf` for node. Extremely useful in many different contexts.

#### [`safe-buffer`](https://github.com/feross/safe-buffer)

A safer node.js Buffer API. Works in the browser.

#### [`sinon`](https://github.com/sinonjs/sinon) :white_check_mark:

Spies, stubs and mocks for JavaScript. Very advanced. I'm only using it for spies and stubs. Also just a module so easy to use as a complement to [`tape`](https://github.com/substack/tape).

#### [`sodium-universal`](https://github.com/sodium-friends/sodium-universal)

Need crypto? Want it to work in both node and in the browser? For the node case, there are prebuilt binaries for all major OS. If prebuilt fails, then falls back to pure js. Backed by [f`libsodium`](https://github.com/jedisct1/libsodium).

#### [`standard`](https://github.com/feross/standard) :wrench: :white_check_mark:

A JavaScript coding style. Just embrace it, get rid of all bike shedding and move on to more important stuff.

#### [`tape`](https://github.com/substack/tape) :white_check_mark:

Simple and minimalistic test module. Since it's just a function it can be composed endlessly. Produces `TAP` (Test Anything Protocol) output which in turn can be formatted to your liking.
