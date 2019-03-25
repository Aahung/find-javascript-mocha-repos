# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:44 03/25/19 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45664 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 43000 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42514 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 31018 | `nyc mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 26478 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 26123 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25764 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25354 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 22019 | `npm-run-all lint build --parallel test:mocha test:karma test:ts` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20396 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 19016 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18438 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18237 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 18114 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15747 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15309 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14815 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14203 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 14015 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13623 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13116 | `mocha 'test/**/*.spec.js'` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 13044 | `istanbul cover _mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12919 | `mocha --reporter spec test/*-test.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12878 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12815 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12506 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12386 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11860 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11683 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11449 | `set NODE_ENV=test && mocha` | 
| [tj/co](https://github.com/tj/co) | 10540 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 10135 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9934 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9794 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9658 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9522 | `mocha -b -r esm` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9424 | `mocha --opts mocha.opts` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9422 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 9185 | `mocha test/*/**` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 9147 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9063 | `mocha test/src` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8224 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8147 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8127 | `./node_modules/.bin/mocha test` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7822 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7788 | `mocha --exit --require @babel/register` | 
| [almende/vis](https://github.com/almende/vis) | 7735 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7729 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7722 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7649 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7603 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7452 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7302 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7822 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7788 | `mocha --exit --require @babel/register` | 
| [almende/vis](https://github.com/almende/vis) | 7735 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7729 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7722 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7649 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7603 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7452 | `mocha` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7446 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7302 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7179 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7171 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 7124 | `mocha test/test.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6486 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6455 | `npm run test:mocha:src` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6396 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6365 | `mocha tests/node.js` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6339 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6306 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6283 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6251 | `standard && mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 6249 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6175 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6068 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 6067 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 6005 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5950 | `mocha && eslint lib/**` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5921 | `mocha` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5916 | `npm run lint && mocha tests/**/*.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5861 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5398 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5236 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5186 | `npm run lint && npm run mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 5159 | `NODE_ENV=test mocha --exit` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5157 | `gulp lint && mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5156 | `nyc mocha --exit` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5124 | `mocha --color` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5113 | `nyc mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 5008 | `./node_modules/.bin/mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4927 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4896 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4885 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4872 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4770 | `mocha --reporter spec -t 8000` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5443 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5398 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5236 | `mocha --recursive` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5212 | `mocha src/**/*Tests.js --harmony` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5186 | `npm run lint && npm run mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 5159 | `NODE_ENV=test mocha --exit` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5157 | `gulp lint && mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5156 | `nyc mocha --exit` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5124 | `mocha --color` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5113 | `nyc mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 5020 | `gulp build; mocha;` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 5008 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4938 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4927 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4904 | `mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4896 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4885 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4872 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4770 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4756 | `mocha -R spec src` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 4692 | `./node_modules/mocha/bin/mocha --require @babel/register test/*` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4608 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4594 | `mocha ./test/runner.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4590 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4558 | `mocha --timeout=15000 tests/*.test.js` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 4550 | `npm run mocha` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4534 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4515 | `mocha --check-leaks --reporter spec --bail` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4497 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4457 | `mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4437 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4409 | `npm run lint && mocha && mocha test/individual && if [ "$TRAVIS_PULL_REQUEST" = "false" ]; then snyk test; fi` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4400 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4252 | `nyc mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4188 | `mocha --require test/babel-hook test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4187 | `mocha -R spec ./test --recursive` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4182 | `nyc mocha "test/**/*.test.js"` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4180 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4171 | `mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 4156 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [tj/ejs](https://github.com/tj/ejs) | 4136 | `mocha --require should --reporter spec` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3988 | `eslint . && mocha -t 5000` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3940 | `export TESTING=true; mocha --reporter list` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3857 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3852 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [primus/primus](https://github.com/primus/primus) | 3851 | `npm run build && mocha test/*.test.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3844 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3842 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [antvis/g6](https://github.com/antvis/g6) | 3820 | `torch --compile --renderer --opts test/mocha.opts --recursive ./test/unit` | 
| [erming/shout](https://github.com/erming/shout) | 3797 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3789 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3776 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3715 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3789 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3776 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3767 | `mocha test/* --reporter spec` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3715 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3680 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3674 | `npm run jshint && npm run mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3639 | `nyc mocha && tsc` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3631 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3623 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3615 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3615 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3608 | `mocha tests/javascript` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3586 | `mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3565 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3551 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3549 | `node ./test/import-test.js && mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3536 | `mocha -R landing test/index --exit` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3210 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3202 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3195 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3187 | `mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3184 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3174 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3146 | `nyc mocha --recursive` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 3088 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 3086 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3076 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3076 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3042 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3039 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 3017 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2994 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2991 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2931 | `mocha -R spec spec spec/reporters` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2926 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3386 | `mocha test/index.js && npm run demo` | 
| [mde/ejs](https://github.com/mde/ejs) | 3355 | `mocha --require should --reporter spec` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3325 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3316 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3303 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3298 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3246 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3210 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3202 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3195 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3187 | `mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3184 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3174 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3168 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 3088 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 3086 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3076 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3076 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3070 | `mocha test-node` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 3052 | `mocha --require @babel/register --recursive spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3042 | `mocha` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 3017 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2999 | `mocha -R spec --recursive src/test` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2994 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2991 | `mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2965 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2931 | `mocha -R spec spec spec/reporters` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2926 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2926 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2965 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2931 | `mocha -R spec spec spec/reporters` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2926 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2926 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2904 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2861 | `mocha "./test/**/*-test.js"` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2853 | `istanbul cover _mocha` | 
| [css/csso](https://github.com/css/csso) | 2845 | `mocha --reporter dot` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2811 | `mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2795 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2428 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [pahen/madge](https://github.com/pahen/madge) | 2427 | `npm run lint && npm run mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2394 | `grunt jshint && mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2391 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2370 | `node node_modules/mocha/bin/_mocha` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2358 | `mocha test/**/*.coffee` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2350 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2339 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [gajus/swing](https://github.com/gajus/swing) | 2337 | `mocha --compilers js:babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2326 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2322 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1962 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1961 | `mocha test -u bdd -R spec` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1941 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1887 | `mocha tests.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1886 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1875 | `npm run lint && npm run mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1868 | `npm run lint && npm run mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1868 | `mocha test/setup.js test/spec/*.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1826 | `mocha test` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2245 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2230 | `mocha --compilers js:babel-register` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2229 | `mocha --timeout 15000 --bail --exit test/*-test.js test/security/*.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2224 | `mocha test` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2194 | `cross-env BABEL_ENV=test mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2175 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2175 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2173 | `mocha --compilers js:babel-core/register __tests__` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2166 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2133 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2125 | `mocha tests --require @babel/register` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2121 | `npm run mocha && npm run karma` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2105 | `mocha && npm run lint` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 2101 | `mocha --recursive` | 
| [htmlhint/HTMLHint](https://github.com/htmlhint/HTMLHint) | 2081 | `mocha` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2074 | `npm run lint && mocha -R dot && npm run cover` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2067 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2056 | `mocha --reporter spec --timeout 5000` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 2032 | `nyc mocha --timeout=20000 test.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2032 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 2020 | `mocha test/**/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 2004 | `mocha --reporter spec && npm run test-typescript` | 
| [zeit/ms](https://github.com/zeit/ms) | 1996 | `mocha tests.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1981 | `bmocha --reporter spec test/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1979 | `mocha --bail --reporter spec --check-leaks test/` | 
| [then/promise](https://github.com/then/promise) | 2034 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 2032 | `nyc mocha --timeout=20000 test.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2032 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2023 | `mocha --require=test/test_helper.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 2020 | `mocha test/**/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 2004 | `mocha --reporter spec && npm run test-typescript` | 
| [zeit/ms](https://github.com/zeit/ms) | 1996 | `mocha tests.js` | 
| [slate/slate](https://github.com/slate/slate) | 1993 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1986 | `mocha --require ./test/common --growl test/expect.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1981 | `bmocha --reporter spec test/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1979 | `mocha --bail --reporter spec --check-leaks test/` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1975 | `npm run lint && mocha --reporter spec test/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1962 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1961 | `mocha test -u bdd -R spec` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1960 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1953 | `mocha test` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1822 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1817 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1814 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1801 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1797 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1794 | `mocha --timeout 5000` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1783 | `npm run lint && mocha && npm run typescript` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1782 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1776 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1752 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1749 | `./node_modules/.bin/mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1741 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1741 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1741 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1730 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1726 | `mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1801 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1797 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1794 | `mocha --timeout 5000` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1783 | `npm run lint && mocha && npm run typescript` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1782 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1778 | `mocha --check-leaks --reporter spec --bail` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1776 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1776 | `mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1771 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1752 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1749 | `./node_modules/.bin/mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1741 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1741 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1739 | `mocha test --timeout 600000` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1730 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1730 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1730 | `mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1724 | `mocha` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1797 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1794 | `mocha --timeout 5000` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1783 | `npm run lint && mocha && npm run typescript` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1782 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1778 | `mocha --check-leaks --reporter spec --bail` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1776 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1776 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1771 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1771 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1752 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1749 | `./node_modules/.bin/mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1741 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1741 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1741 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1739 | `mocha test --timeout 600000` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1735 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1644 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1641 | `mocha tests/test.js` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1634 | `mocha test.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1633 | `mocha tests/test-*` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1625 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1620 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1593 | `npm run lint && npm run mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1577 | `mocha --check-leaks --require @babel/register` | 
| [fbeline/design-patterns-JS](https://github.com/fbeline/design-patterns-JS) | 1575 | `mocha test --compilers js:babel-core/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1573 | `mocha` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1572 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1367 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1361 | `mocha` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1352 | `mocha` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1351 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1346 | `lerna run test && mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1343 | `npm run lint && npm run mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1342 | `mocha test/*.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1341 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1341 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1340 | `mocha src/test.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1321 | `mocha-phantomjs tests/index.html` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1318 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1305 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1305 | `istanbul test _mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1305 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1111 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1100 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1099 | `mocha --check-leaks -t 20000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1079 | `mocha --async-only` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1071 | `mocha test/*.test.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1067 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1052 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1044 | `mocha --recursive test/unit/` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1042 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1040 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1234 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1224 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1219 | `mocha --reporter spec --bail --check-leaks test/` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1214 | `mocha test` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1208 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1188 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1185 | `mocha $(find test -name '*.test.js') --exit` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1448 | `npm run build && mocha -r should` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1448 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1447 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1438 | `mocha --recursive test/bin` | 
| [electron/devtron](https://github.com/electron/devtron) | 1431 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1430 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1427 | `istanbul cover _mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1427 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1418 | `mocha --compilers js:babel-core/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1416 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1409 | `mocha --recursive` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1408 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1406 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1401 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1396 | `NODE_PATH=. mocha **/*.spec.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1390 | `./node_modules/mocha/bin/mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1385 | `mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1378 | `cross-env NODE_ENV=test nyc mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1367 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1367 | `mocha --timeout 20000` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1361 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1355 | `mocha --timeout 60000 test/` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1352 | `mocha` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1351 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1342 | `mocha test/*.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1341 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1341 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1340 | `mocha src/test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1352 | `mocha` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1351 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1342 | `mocha test/*.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1341 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1341 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1340 | `mocha src/test.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1340 | `mocha` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1339 | `mocha spec/exec.js` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1332 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1331 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1326 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1321 | `mocha-phantomjs tests/index.html` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1318 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1317 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1309 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [variety/variety](https://github.com/variety/variety) | 1293 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1275 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1273 | `mocha --reporter spec` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1269 | `mocha test` | 
| [electron/asar](https://github.com/electron/asar) | 1269 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1268 | `mocha tests` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1259 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1258 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1243 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1240 | `mocha --reporter spec test --recursive` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1234 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1233 | `node ./node_modules/mocha/bin/mocha tests` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1227 | `mocha --recursive -r tests/setup tests` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1227 | `mocha --reporter spec --bail --check-leaks test/` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1224 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1217 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1217 | `npm-run-all test:jest test:server:mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1214 | `mocha test` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1210 | `mocha test/test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1208 | `mocha` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1204 | `npm run lint && npm run mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1234 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1233 | `node ./node_modules/mocha/bin/mocha tests` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1227 | `mocha --recursive -r tests/setup tests` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1227 | `mocha --reporter spec --bail --check-leaks test/` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1224 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1219 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1217 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1217 | `npm-run-all test:jest test:server:mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1214 | `mocha test` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1210 | `mocha test/test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1208 | `mocha` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1204 | `npm run lint && npm run mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1198 | `xo && mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1135 | `mocha test/*` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1123 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1117 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1111 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1108 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1101 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1100 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1100 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1099 | `mocha --check-leaks -t 20000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1094 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1092 | `mocha test/tests.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1101 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1100 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1100 | `node_modules/.bin/mocha && npm run lint` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [tomas/needle](https://github.com/tomas/needle) | 1085 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1079 | `mocha --async-only` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 1075 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1067 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1111 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1108 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1101 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1100 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1100 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1099 | `mocha --check-leaks -t 20000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1094 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1092 | `mocha test/tests.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1079 | `mocha --async-only` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1067 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1061 | `mocha $(find test -name '*.test.js')` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1052 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1044 | `mocha --recursive test/unit/` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1042 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1041 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1040 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1037 | `npm run lint && mocha -R spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1035 | `./node_modules/.bin/mocha -R spec` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 1035 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 975 | `mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 971 | `standard && standard ./bin/* && mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 966 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 962 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 958 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 957 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 955 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 951 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 936 | `mocha --timeout 5000` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 931 | `mocha -r should --exit test/*.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 929 | `mocha -t 5000` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 928 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 924 | `mocha test` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 921 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 918 | `npm run lint && npm run mocha:no-functional` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 924 | `mocha test` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 922 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 922 | `mocha --harmony tests/**` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 921 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 918 | `npm run lint && npm run mocha:no-functional` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 914 | `mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 912 | `mocha` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 911 | `npm run lint && mocha` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 909 | `npm run build && istanbul test _mocha test/test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 905 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 904 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 904 | `mocha --harmony --full-trace --check-leaks` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 899 | `node_modules/.bin/mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 899 | `mocha --timeout 200000` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 897 | `mocha --reporter list` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 892 | `node_modules/.bin/mocha test/spec` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 884 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 883 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 878 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 878 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 877 | `istanbul cover _mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 875 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 875 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 874 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [developit/decko](https://github.com/developit/decko) | 873 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 871 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 870 | `mocha --reporter spec` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 869 | `nyc mocha` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 850 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 845 | `mocha test` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 844 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 843 | `mocha test/mocha.js test/crc/index.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 842 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 842 | `mocha --async-only` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 838 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 836 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 833 | `mocha && ember test` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 832 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 830 | `eslint . && mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 829 | `cake build && mocha ./test/mocha/*.coffee` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 824 | `mocha` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 846 | `ts-mocha test/` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 845 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 845 | `mocha test` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 844 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 843 | `mocha test/mocha.js test/crc/index.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 842 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 842 | `mocha --async-only` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 840 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 838 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 836 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 835 | `npm run mocha-test test/integration` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 835 | `mocha` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 833 | `_mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 833 | `mocha && ember test` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 832 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 846 | `ts-mocha test/` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 845 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 845 | `mocha test` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 844 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 843 | `mocha test/mocha.js test/crc/index.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 842 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 842 | `mocha --async-only` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 840 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 838 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 838 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 836 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 835 | `npm run mocha-test test/integration` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 835 | `mocha` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 833 | `_mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 833 | `mocha && ember test` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 832 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 830 | `eslint . && mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 829 | `cake build && mocha ./test/mocha/*.coffee` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 790 | `mocha -u tdd` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 786 | `mocha 'test/**/*.tests.js'` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 781 | `babel-node node_modules/.bin/_mocha -- test` | 
| [susam/texme](https://github.com/susam/texme) | 780 | `standard && mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 777 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 776 | `mocha -R spec src/**/*_test.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 774 | `./bin/selenium-standalone install && mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 773 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 795 | `mocha tests --timeout 10000` | 
| [koajs/static](https://github.com/koajs/static) | 794 | `mocha --harmony --reporter spec --exit` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 791 | `npm run lint&&mocha tests/*.js` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 790 | `mocha -u tdd` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 786 | `mocha 'test/**/*.tests.js'` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 785 | `mocha ./test/serializer/ --compilers js:@babel/register` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 784 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 783 | `npm run-script jshint && npm run-script mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 773 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 771 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 771 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 770 | `mocha --ui tdd --require ./test/__setup` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 768 | `mocha --reporter spec build/test/index.js` | 
| [electron/apps](https://github.com/electron/apps) | 766 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 763 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 761 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 759 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 712 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 712 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 708 | `mocha` | 
| [Savjee/SavjeeCoin](https://github.com/Savjee/SavjeeCoin) | 708 | `mocha tests/*.test.js` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 705 | `mocha -t 5000 -b -R spec test/index && npm run legacy-test` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 705 | `mocha --reporter spec` | 
| [apollographql/eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) | 703 | `tav --ci && mocha test/index.js` | 