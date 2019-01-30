# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:51 01/30/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45048 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42135 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42048 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30860 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25618 | `nyc mocha --timeout=10000 --exit` | 
| [caolan/async](https://github.com/caolan/async) | 25189 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25098 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21402 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20115 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18480 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18020 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17868 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17333 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15249 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14963 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14705 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13948 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13670 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13143 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13012 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12782 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12779 | `istanbul cover _mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12466 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12422 | `mocha --require @babel/register --reporter dot` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12354 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12284 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11527 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11159 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11147 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10890 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10822 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10486 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10423 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9764 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9762 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9707 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9534 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9443 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9400 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9318 | `grunt mocha` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8911 | `mocha test/src` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8905 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8738 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8687 | `mocha test/test.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8738 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8687 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8589 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8571 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8458 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8332 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8261 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8254 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8101 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8053 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8022 | `./node_modules/.bin/mocha test` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7969 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7906 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7900 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7874 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7036 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6876 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6574 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6398 | `npm run test:mocha:src` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6279 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6277 | `mocha tests/node.js` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6244 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6217 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6214 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6100 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6068 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4917 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4890 | `npm run lint && npm run mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4858 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4846 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4837 | `mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4835 | `nyc mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4750 | `mocha --reporter spec -t 8000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4642 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4587 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4585 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4554 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4485 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4384 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4364 | `node_modules/.bin/mocha test/tests.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4357 | `mocha --check-leaks --reporter spec --bail` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4316 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5932 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5885 | `mocha && eslint lib/**` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5767 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5738 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5721 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 5708 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5703 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5619 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5566 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5548 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 5513 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5406 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5392 | `mocha test` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5383 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5341 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4956 | `gulp build; mocha;` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4946 | `nyc mocha --exit` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4935 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4917 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4895 | `./node_modules/.bin/mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4890 | `npm run lint && npm run mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4888 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4858 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4846 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4837 | `mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4835 | `nyc mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4750 | `mocha --reporter spec -t 8000` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4585 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4554 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4485 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4750 | `mocha --reporter spec -t 8000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4642 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4587 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4585 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4554 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4485 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4440 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4384 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4378 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4364 | `node_modules/.bin/mocha test/tests.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4357 | `mocha --check-leaks --reporter spec --bail` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4348 | `NODE_ENV=test mocha --exit` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4316 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4235 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4194 | `mocha -R spec ./test --recursive` | 
| [muicss/mui](https://github.com/muicss/mui) | 4139 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4127 | `mocha --require test/babel-hook test/*.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4113 | `npm run build && cd test && mocha . --reporter dot` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4093 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4091 | `mocha --require should --reporter spec` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4062 | `nyc mocha "test/**/*.test.js"` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3931 | `export TESTING=true; mocha --reporter list` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3892 | `NODE_ENV=test mocha test/**/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3858 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3832 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3815 | `npm run build && mocha test/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3793 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3779 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3750 | `mocha && tsc -p ./test/types` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3735 | `mocha test/* --reporter spec` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3734 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3728 | `npm run mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3723 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3716 | `eslint . && mocha -t 5000` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3685 | `standard && mocha --timeout 60000 test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3677 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3670 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3685 | `standard && mocha --timeout 60000 test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3677 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3670 | `npm run jshint && npm run mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3665 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3662 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 3629 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3609 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3601 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3593 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3581 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3540 | `nyc mocha && tsc` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3490 | `node_modules/.bin/mocha test/lib/` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3466 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3465 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3448 | `mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3490 | `node_modules/.bin/mocha test/lib/` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3466 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3465 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3448 | `mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3438 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3432 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3426 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3409 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3390 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3379 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3368 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3366 | `mocha -R landing test/index --exit` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3325 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3305 | `mocha test/index.js && npm run demo` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3305 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3253 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3233 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3226 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3221 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3212 | `mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 3199 | `mocha --require should --reporter spec` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3182 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3171 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3160 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3158 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3155 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3100 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3093 | `nyc mocha --recursive` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2787 | `mocha --require should --reporter spec` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2764 | `mocha "./test/**/*-test.js"` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2764 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2763 | `xo && mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2755 | `mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2714 | `nyc mocha --timeout=10000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2713 | `mocha --recursive --watch` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2707 | `nyc mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2687 | `mocha --timeout 100000` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2676 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2673 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2645 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2592 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2633 | `mocha-phantomjs ./test/index.html` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2599 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2555 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2553 | `mocha test --exit && npm run lint` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2548 | `mocha test` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2542 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2537 | `mocha test/src/**/*.unit.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2532 | `nyc --reporter=html --reporter=text mocha` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2530 | `export TESTING=true; mocha --reporter list` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2526 | `mocha && eslint .` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2524 | `TEST=all mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2520 | `mocha --reporter=spec test/*-test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2507 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2493 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2492 | `mocha test/index.js --reporter dot` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 2070 | `mocha test/*.test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2052 | `npm run mocha && npm run karma` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2048 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2045 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2042 | `npm run lint && mocha -R dot && npm run cover` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2035 | `mocha tests --require @babel/register` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2022 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2020 | `mocha --reporter spec --timeout 5000` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2012 | `mocha test` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2002 | `mocha --require=test/test_helper.js` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1988 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1965 | `mocha -c test/index.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1963 | `mocha test/**/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1961 | `mocha --bail --reporter spec --check-leaks test/` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2321 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2311 | `mocha --compilers js:babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2308 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2286 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2285 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [pahen/madge](https://github.com/pahen/madge) | 2283 | `npm run lint && npm run mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2249 | `standard && mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2243 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2236 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2052 | `npm run mocha && npm run karma` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2048 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2048 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2042 | `npm run lint && mocha -R dot && npm run cover` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2035 | `mocha tests --require @babel/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2029 | `mocha && npm run lint` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2020 | `mocha --reporter spec --timeout 5000` | 
| [then/promise](https://github.com/then/promise) | 2013 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2012 | `mocha test` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2002 | `mocha --require=test/test_helper.js` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1988 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1971 | `mocha --require ./test/common --growl test/expect.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1965 | `mocha -c test/index.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1963 | `mocha test/**/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1961 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1954 | `mocha --reporter spec && npm run test-typescript` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1950 | `mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1949 | `bmocha --reporter spec test/*.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1933 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1932 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1915 | `mocha test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1915 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1915 | `mocha test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1915 | `mocha --reporter spec --grep .` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1901 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1897 | `mocha compiled_tests/` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1884 | `mocha` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1880 | `mocha tests.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1877 | `mocha ./test/basic.js -t 5000` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1862 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1855 | `nyc mocha --timeout=20000 test.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1843 | `npm run lint && npm run mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1824 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1820 | `mocha test` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1812 | `npm run lint && npm run mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1811 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1805 | `eslint --cache . && tsc && mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1803 | `mocha test/setup.js test/spec/*.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1800 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1798 | `mocha --timeout 5000` | 
| [zeit/ms](https://github.com/zeit/ms) | 1766 | `mocha tests.js` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1762 | `mocha --recursive` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1761 | `npm run lint && mocha && npm run typescript` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1756 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1613 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1612 | `./node_modules/mocha/bin/mocha -R spec` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1610 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1609 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1607 | `mocha --recursive` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1585 | `mocha test/unit` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1574 | `mocha -R spec ./test/unit/**` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1569 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1562 | `mocha tests/test-*` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1554 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1543 | `node_modules/.bin/mocha --recursive` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1542 | `mocha --check-leaks --require @babel/register` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1539 | `mocha -u tdd` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1585 | `mocha test/unit` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1574 | `mocha -R spec ./test/unit/**` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1569 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1557 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1543 | `node_modules/.bin/mocha --recursive` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1542 | `mocha --check-leaks --require @babel/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1357 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1347 | `npm run lint && mocha --require @babel/register` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1331 | `lerna run test && mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1330 | `mocha --timeout 60000 test/` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1326 | `mocha spec/exec.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1323 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1323 | `mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1323 | `mocha-phantomjs tests/index.html` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1307 | `npm run lint && npm run mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1300 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1299 | `mocha --timeout 30000 --recursive ./tests` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1298 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1294 | `mocha --timeout 20000` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1292 | `istanbul test _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1291 | `mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1284 | `mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1524 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1521 | `mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1518 | `npm run lint && npm run mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1511 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1509 | `mocha --timeout 10000 ./tests/lib.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1507 | `mocha test/**/*.spec.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1501 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [noble/bleno](https://github.com/noble/bleno) | 1500 | `mocha -R spec test/*.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1495 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1473 | `mocha --recursive test` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1472 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1471 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1467 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1415 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1409 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1408 | `istanbul cover _mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1405 | `mocha --recursive test/bin` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1395 | `mocha --recursive` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1386 | `./node_modules/mocha/bin/mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1386 | `mocha --check-leaks --reporter spec --bail test/` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1382 | `webpack && npm run lint && npm run mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1375 | `./node_modules/.bin/mocha test` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1369 | `npm run mocha:istanbul` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1368 | `NODE_PATH=. mocha **/*.spec.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1362 | `mocha --compilers js:babel-core/register` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1361 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1360 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1357 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1313 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1310 | `mocha src/test.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1308 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1307 | `npm run lint && npm run mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1298 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1298 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1294 | `mocha --timeout 20000` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1293 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1292 | `istanbul test _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1291 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1289 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1284 | `mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1347 | `npm run lint && mocha --require @babel/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1346 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1331 | `lerna run test && mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1330 | `mocha --timeout 60000 test/` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1325 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1323 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1323 | `mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1323 | `mocha-phantomjs tests/index.html` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1322 | `mocha test/*.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1320 | `mocha tests/` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1319 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1317 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1313 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1310 | `mocha src/test.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1308 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1307 | `npm run lint && npm run mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1299 | `mocha --timeout 30000 --recursive ./tests` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1298 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1298 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1294 | `mocha --timeout 20000` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1293 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1292 | `istanbul test _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1291 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1289 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1284 | `mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1273 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1264 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1262 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1262 | `mocha tests` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1262 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1262 | `mocha tests` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1259 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1252 | `mocha --reporter spec` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1246 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1242 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1241 | `mocha` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1241 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1236 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1235 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1229 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1154 | `mocha --reporter spec test --recursive` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1154 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1128 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1125 | `standard && mocha -b` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1115 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1114 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1112 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1105 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1104 | `mocha` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1099 | `mocha --recursive --bail --reporter spec test` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1098 | `node_modules/.bin/mocha && npm run lint` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1172 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1170 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1169 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1167 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1167 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1156 | `istanbul cover _mocha test/*.js` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1155 | `mocha test` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1154 | `mocha --reporter spec test --recursive` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1154 | `mocha` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1146 | `webpack && mocha test/unit` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1133 | `npm run convertto:es5 && npm run mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1125 | `standard && mocha -b` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1115 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1114 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1105 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1104 | `mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1101 | `eslint src test && mocha --compilers babel-register` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1099 | `mocha --recursive --bail --reporter spec test` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1098 | `node_modules/.bin/mocha && npm run lint` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1095 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1090 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1090 | `mocha --compilers js:babel-register` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1098 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1096 | `mocha --check-leaks -t 20000` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1090 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1090 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1085 | `mocha test/tests.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [tomas/needle](https://github.com/tomas/needle) | 1068 | `mocha test` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1066 | `npm run lint && npm run mocha` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 747 | `mocha 'test/**/*.tests.js'` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 744 | `npm run test-mocha && npm run test-karma` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 744 | `mocha test.js` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 740 | `npm run bundle && mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 737 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 733 | `mocha --compilers js:babel-core/register` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 732 | `mocha $(find test -name '*.test.js')` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 723 | `mocha ./test/index.js` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 720 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 717 | `mocha` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1006 | `mocha --check-leaks -R dot` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1005 | `mocha -R list` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1002 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1000 | `mocha --compilers js:babel-register test/*.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1000 | `npm run lint && mocha -R spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 996 | `./node_modules/.bin/mocha -R spec` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 991 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 987 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 984 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 983 | `mocha --reporter spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 982 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 981 | `mocha "client.test" --compilers js:babel-register` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 979 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 977 | `npm run rollup-cjs && mocha test/test.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 974 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 935 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 932 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 930 | `istanbul cover -- _mocha --reporter spec` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 925 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 918 | `mocha -t 5000` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 917 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 911 | `mocha test/index.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 896 | `node_modules/.bin/mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 894 | `mocha` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 888 | `mocha -r should --exit test/*.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 888 | `node_modules/.bin/mocha test/spec` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 886 | `npm run build && istanbul test _mocha test/test.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 877 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 869 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 867 | `istanbul cover _mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 865 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 864 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 862 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 858 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 858 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 858 | `mocha --harmony tests/**` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 858 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 858 | `mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 856 | `nyc mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 856 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 855 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 853 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 853 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 853 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 851 | `npm run lint && mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 849 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 849 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 849 | `mocha` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 848 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 848 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 846 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 846 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [developit/decko](https://github.com/developit/decko) | 844 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 844 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 843 | `mocha --opts mocha.opts` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 842 | `npm run lint && mocha` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 840 | `mocha -r babel-register --check-leaks test/index.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 840 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 840 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 839 | `mocha --async-only` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 835 | `mocha test` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 834 | `nyc mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 830 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 829 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 828 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 823 | `mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 822 | `npm run mocha-test test/integration` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 820 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 818 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [edsu/anon](https://github.com/edsu/anon) | 816 | `mocha --colors --reporter spec test.js` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 816 | `_mocha` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 815 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 815 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 813 | `cake build && mocha ./test/mocha/*.coffee` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 810 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 809 | `mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 805 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 804 | `mocha index.test.js` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 802 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 801 | `mocha test` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 800 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 800 | `mocha test/mocha.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 799 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 799 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 796 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 796 | `mocha --no-timeouts` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 796 | `xo && mocha -R spec` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 793 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 751 | `mocha tests/*.mocha.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 746 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 744 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 742 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 739 | `mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 736 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 775 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 774 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 774 | `jenkins-mocha ./tests/*.js` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 773 | `babel-node node_modules/.bin/_mocha -- test` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [koajs/static](https://github.com/koajs/static) | 770 | `mocha --harmony --reporter spec --exit` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 765 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [susam/texme](https://github.com/susam/texme) | 764 | `standard && mocha` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 763 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 761 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 747 | `mocha 'test/**/*.tests.js'` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 746 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 744 | `npm run test-mocha && npm run test-karma` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 744 | `mocha test.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 742 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 740 | `npm run bundle && mocha` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 739 | `mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 737 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 736 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 751 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 747 | `mocha 'test/**/*.tests.js'` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 744 | `npm run test-mocha && npm run test-karma` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 744 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 744 | `mocha test.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 742 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 740 | `npm run bundle && mocha` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 739 | `mocha` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 711 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 707 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [typicode/katon](https://github.com/typicode/katon) | 707 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 705 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 704 | `mocha` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 703 | `mocha --reporter spec` | 
| [formio/formio](https://github.com/formio/formio) | 702 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 701 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 699 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [stevenvachon/broken-link-checker](https://github.com/stevenvachon/broken-link-checker) | 648 | `mocha test/ --reporter spec --check-leaks --bail` | 
| [kwhitley/apicache](https://github.com/kwhitley/apicache) | 647 | `nyc mocha $(find test -name '*.test.js') --recursive` | 
| [docpress/docpress](https://github.com/docpress/docpress) | 643 | `nyc mocha` | 
| [anandanand84/technicalindicators](https://github.com/anandanand84/technicalindicators) | 641 | `mocha --compilers js:babel-register --require babel-polyfill` | 
| [tonyhb/redux-ui](https://github.com/tonyhb/redux-ui) | 639 | `$(npm bin)/mocha  --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [danielstjules/buddy.js](https://github.com/danielstjules/buddy.js) | 639 | `mocha -R spec spec/unit spec/integration` | 
| [postcss/gulp-postcss](https://github.com/postcss/gulp-postcss) | 638 | `nyc mocha test.js` | 
| [floatdrop/gulp-watch](https://github.com/floatdrop/gulp-watch) | 636 | `xo && mocha -r test/util/set-default-options -t 5000 -R spec test/test-*` | 
| [pocketjoso/specificity-graph](https://github.com/pocketjoso/specificity-graph) | 634 | `node_modules/.bin/mocha test` | 
| [azmenak/react-stripe-checkout](https://github.com/azmenak/react-stripe-checkout) | 634 | `mocha --require babel-register --require .test-setup.js -R spec ./spec.js` | 
| [gauntface/simple-push-demo](https://github.com/gauntface/simple-push-demo) | 632 | `gulp && npm run lint && node ./test/helpers/download-browsers.js && mocha` | 
| [hparra/gulp-rename](https://github.com/hparra/gulp-rename) | 632 | `mocha` | 
| [Munter/subfont](https://github.com/Munter/subfont) | 632 | `npm run lint && mocha` | 
| [edankwan/penis.js](https://github.com/edankwan/penis.js) | 631 | `mocha --ui bdd --reporter spec test/` | 