# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:56:27 03/09/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [expressjs/express](https://github.com/expressjs/express) | 42761 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42413 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30975 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 26233 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25990 | `nyc mocha --timeout=10000 --exit` | 
| [caolan/async](https://github.com/caolan/async) | 25305 | `npm run lint && npm run mocha-node-test` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20306 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18820 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18302 | `mocha` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18820 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18302 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18144 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17905 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15579 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15202 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14791 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14137 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13903 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13478 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13080 | `mocha 'test/**/*.spec.js'` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12953 | `istanbul cover _mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12881 | `mocha --reporter spec test/*-test.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12769 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12713 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12465 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12377 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11760 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11536 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11342 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 11051 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [websockets/ws](https://github.com/websockets/ws) | 10760 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10776 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10760 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10498 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 10013 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9898 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9753 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9651 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9571 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9493 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9399 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9298 | `mocha --opts mocha.opts` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 9024 | `mocha test/*/**` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 9021 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9011 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8730 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8650 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8597 | `mocha --check-leaks -R dot` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8564 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8510 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8357 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8297 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8297 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8218 | `mocha` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8146 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8103 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8103 | `./node_modules/.bin/mocha test` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8071 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7968 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7689 | `mocha --exit --require @babel/register` | 
| [almende/vis](https://github.com/almende/vis) | 7668 | `mocha --compilers js:babel-core/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7668 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7649 | `mocha; jshint *.js lib` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7627 | `npm run build && istanbul cover _mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7625 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [dthree/cash](https://github.com/dthree/cash) | 7590 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7453 | `mocha` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7353 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7168 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7163 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7134 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 7056 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6638 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6442 | `npm run test:mocha:src` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6426 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6421 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6347 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6333 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6263 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6254 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6234 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6185 | `standard && mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6153 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 5995 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5970 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5933 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5930 | `mocha && eslint lib/**` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5922 | `mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5836 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5809 | `npm run lint && mocha tests/**/*.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5763 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5713 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5628 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5532 | `mocha test` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5489 | `mocha -r esm` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5477 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5420 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4796 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4763 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4700 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4592 | `mocha ./test/runner.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4519 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4512 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4503 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4489 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4465 | `mocha --check-leaks --reporter spec --bail` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4420 | `node_modules/.bin/mocha test/tests.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4397 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4395 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4887 | `mocha -R spec 'tests/app'` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4883 | `mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4868 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4796 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4763 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4700 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4592 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4581 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4519 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4512 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4503 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4489 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4465 | `mocha --check-leaks --reporter spec --bail` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4420 | `node_modules/.bin/mocha test/tests.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4397 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4395 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4357 | `npm run lint && snyk test && mocha && mocha test/individual` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 4356 | `./node_modules/mocha/bin/mocha --require @babel/register test/*` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 4280 | `npm run mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4269 | `npm run build && cd test && mocha . --reporter dot` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4248 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4190 | `mocha -R spec ./test --recursive` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4168 | `mocha --require test/babel-hook test/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4151 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4146 | `nyc mocha "test/**/*.test.js"` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 4023 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3985 | `NODE_ENV=test mocha test/**/*.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3950 | `mocha && tsc -p ./test/types` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3938 | `export TESTING=true; mocha --reporter list` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3893 | `eslint . && mocha -t 5000` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3852 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [primus/primus](https://github.com/primus/primus) | 3840 | `npm run build && mocha test/*.test.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3836 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3834 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3813 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3795 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3754 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3752 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [erming/shout](https://github.com/erming/shout) | 3795 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3754 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3752 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3751 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3691 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3683 | `node_modules/.bin/mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3681 | `standard && mocha --timeout 60000 test/test.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3678 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3674 | `npm run jshint && npm run mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3613 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3612 | `nyc mocha && tsc` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3606 | `mocha tests/javascript` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3606 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3579 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3567 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3564 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3277 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3191 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3190 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3181 | `mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3149 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3142 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3115 | `npm run mocha && npm run lint` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3076 | `node_modules/.bin/mocha --reporter spec` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3073 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3054 | `mocha test-node` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3053 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 3031 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 3027 | `mocha --require @babel/register --recursive spec` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2992 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2984 | `mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2606 | `mocha test --exit && npm run lint` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2598 | `mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2595 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2559 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2559 | `mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2528 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2511 | `nyc --require babel-register npm run _mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2454 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2454 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2391 | `grunt jshint && mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2992 | `mocha -R spec --recursive src/test` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2983 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2949 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2945 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2926 | `mocha -R spec spec spec/reporters` | 
| [github-tools/github](https://github.com/github-tools/github) | 2922 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2921 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2878 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2851 | `istanbul cover _mocha` | 
| [css/csso](https://github.com/css/csso) | 2836 | `mocha --reporter dot` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2835 | `mocha "./test/**/*-test.js"` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2926 | `mocha -R spec spec spec/reporters` | 
| [github-tools/github](https://github.com/github-tools/github) | 2922 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2921 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2878 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2851 | `istanbul cover _mocha` | 
| [css/csso](https://github.com/css/csso) | 2836 | `mocha --reporter dot` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2835 | `mocha "./test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2796 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2788 | `mocha --require should --reporter spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2783 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [htmlhint/HTMLHint](https://github.com/htmlhint/HTMLHint) | 2070 | `mocha` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2065 | `npm run lint && mocha -R dot && npm run cover` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2061 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2048 | `mocha --reporter spec --timeout 5000` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 2037 | `mocha --recursive` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2029 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 2025 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 2000 | `mocha test/**/*.js` | 
| [slate/slate](https://github.com/slate/slate) | 1993 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1986 | `mocha --reporter spec && npm run test-typescript` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1976 | `nyc mocha --timeout=20000 test.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1973 | `mocha --bail --reporter spec --check-leaks test/` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1971 | `npm run lint && mocha --reporter spec test/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1963 | `mocha -c test/index.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1945 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1939 | `mocha test` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1939 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [zeit/ms](https://github.com/zeit/ms) | 1932 | `mocha tests.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1815 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1810 | `mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1794 | `mocha --timeout 5000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1764 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1759 | `mocha test/*.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1757 | `mocha --check-leaks --reporter spec --bail` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1748 | `./node_modules/.bin/mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1742 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1736 | `mocha test --timeout 600000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1728 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1727 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1725 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1725 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1715 | `mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1732 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1728 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1727 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1722 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1715 | `mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1705 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1691 | `mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1675 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1669 | `mocha spec` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1645 | `mocha --expose-gc --slow 300` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1642 | `mocha --recursive` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1641 | `mocha --reporter spec` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1640 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1636 | `mocha test/unit` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1632 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1630 | `mocha test.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1627 | `mocha -R spec ./test/unit/**` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1627 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1627 | `./node_modules/mocha/bin/mocha -R spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1624 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1621 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1614 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1611 | `mocha tests/test-*` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1589 | `nyc mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1562 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1558 | `node_modules/.bin/mocha --recursive` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1556 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1556 | `npm run lint && mocha && karma start --single-run` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1547 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1547 | `mocha -u tdd` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1545 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1543 | `mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1536 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1535 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1534 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [fbeline/design-patterns-JS](https://github.com/fbeline/design-patterns-JS) | 1529 | `mocha test --compilers js:babel-core/register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1528 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1524 | `mocha --timeout 10000 ./tests/lib.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1523 | `mocha test/**/*.spec.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1522 | `mocha -R spec test/*.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1518 | `npm run prepublishOnly && mocha test/test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1515 | `standard && istanbul cover _mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1424 | `mocha --recursive test/bin` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1421 | `istanbul cover _mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1419 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1401 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1400 | `mocha --compilers js:babel-core/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1397 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1387 | `./node_modules/.bin/mocha test` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1375 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1375 | `npm run lint && mocha --require @babel/register` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1374 | `cross-env NODE_ENV=test nyc mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1353 | `mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1349 | `mocha --timeout 60000 test/` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1347 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1344 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1339 | `mocha --timeout 20000` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1339 | `mocha test/*.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1336 | `mocha --timeout 30000 --recursive ./tests` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1336 | `mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1452 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1449 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1443 | `npm run build && mocha -r should` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1443 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1429 | `npm run mocha:istanbul` | 
| [electron/devtron](https://github.com/electron/devtron) | 1425 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1424 | `mocha --recursive test/bin` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1422 | `mocha --check-leaks --reporter spec --bail test/` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1419 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1408 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1264 | `mocha tests` | 
| [normalize/mz](https://github.com/normalize/mz) | 1264 | `mocha --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1252 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1251 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1240 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1239 | `mocha test` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1222 | `mocha --recursive -r tests/setup tests` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1217 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1215 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1215 | `mocha --reporter spec test --recursive` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1207 | `npm-run-all test:jest test:server:mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1199 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1298 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1295 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [variety/variety](https://github.com/variety/variety) | 1289 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1281 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1275 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [normalize/mz](https://github.com/normalize/mz) | 1264 | `mocha --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1252 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1251 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1264 | `mocha tests` | 
| [normalize/mz](https://github.com/normalize/mz) | 1264 | `mocha --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1252 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1251 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1240 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1239 | `mocha test` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1223 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1223 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1222 | `mocha --recursive -r tests/setup tests` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1217 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1215 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1240 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1239 | `mocha test` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1233 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1223 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1222 | `mocha --recursive -r tests/setup tests` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1217 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1215 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1215 | `mocha --reporter spec test --recursive` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1214 | `mocha --reporter spec --bail --check-leaks test/` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1212 | `mocha test` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1207 | `npm-run-all test:jest test:server:mocha` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1222 | `mocha --recursive -r tests/setup tests` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1217 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1215 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1215 | `mocha --reporter spec test --recursive` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1214 | `mocha --reporter spec --bail --check-leaks test/` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1212 | `mocha test` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1207 | `npm-run-all test:jest test:server:mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1199 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1195 | `xo && mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1184 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1180 | `mocha $(find test -name '*.test.js') --exit` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1179 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 937 | `mocha --timeout 5000` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 928 | `mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 924 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 924 | `mocha -t 5000` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 922 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 920 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 915 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 915 | `mocha test` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 913 | `mocha` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 905 | `mocha --harmony tests/**` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 902 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 900 | `node_modules/.bin/mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 896 | `mocha --timeout 200000` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 895 | `mocha --harmony --full-trace --check-leaks` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 894 | `npm run lint && mocha` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 893 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 889 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 889 | `mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 888 | `mocha --reporter list` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 879 | `mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 873 | `istanbul cover _mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 871 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 868 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 867 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 866 | `mocha --reporter spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [developit/decko](https://github.com/developit/decko) | 864 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 863 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 863 | `mocha -r babel-register --check-leaks test/index.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 861 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 860 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 859 | `mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 858 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 857 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 856 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 854 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 846 | `mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 844 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 842 | `mocha test` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 841 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 841 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 841 | `mocha --async-only` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 840 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 839 | `mocha test` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 839 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 836 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 834 | `_mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 834 | `npm run mocha-test test/integration` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 833 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 833 | `mocha test/mocha.js test/crc/index.js` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 832 | `mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 832 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 832 | `mocha && ember test` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 751 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 750 | `mocha tests/*.mocha.js` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 748 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 744 | `mocha --compilers js:babel-core/register` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 744 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 743 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 738 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 737 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 737 | `mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 730 | `mocha` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 729 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 729 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 814 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 812 | `mocha test` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 807 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 806 | `mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 805 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 804 | `jenkins-mocha ./tests/*.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 799 | `mocha --no-timeouts` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 799 | `mocha tests --timeout 10000` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 798 | `nyc mocha` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 739 | `mocha` | 
| [formio/formio](https://github.com/formio/formio) | 739 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 738 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 737 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 737 | `mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 729 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 727 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 724 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 718 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 717 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [Kagami/ffmpeg.js](https://github.com/Kagami/ffmpeg.js) | 716 | `mocha test/test.js` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 773 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 771 | `mocha 'test/**/*.tests.js'` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 771 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [susam/texme](https://github.com/susam/texme) | 771 | `standard && mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 770 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 769 | `./bin/selenium-standalone install && mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 765 | `mocha --reporter spec build/test/index.js` | 
| [electron/apps](https://github.com/electron/apps) | 757 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [electron/apps](https://github.com/electron/apps) | 757 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 753 | `npm run test-mocha && npm run test-karma` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 753 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 751 | `mocha --reporter spec --bail --check-leaks test/` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 751 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 750 | `mocha tests/*.mocha.js` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 748 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 746 | `mocha test.js` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 744 | `mocha --compilers js:babel-core/register` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 743 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 730 | `mocha --reporter spec` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 730 | `mocha` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 729 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 728 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 727 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 726 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 724 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 720 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 718 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 737 | `mocha` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 736 | `mocha --reporter spec test/` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 730 | `mocha --reporter spec` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 730 | `mocha` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 729 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 728 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 727 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 726 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 724 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 708 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 706 | `mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 705 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 703 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 702 | `npm -s run mocha && npm run -s lint` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 700 | `mocha -t 5000 -b -R spec test/index` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 696 | `_mocha -u bdd --colors test/` | 
| [Savjee/SavjeeCoin](https://github.com/Savjee/SavjeeCoin) | 696 | `mocha tests/*.test.js` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 706 | `mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 705 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 704 | `mocha --reporter spec` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 703 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 702 | `npm -s run mocha && npm run -s lint` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 701 | `./node_modules/.bin/mocha` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 700 | `mocha -t 5000 -b -R spec test/index` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 699 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 696 | `_mocha -u bdd --colors test/` | 
| [Savjee/SavjeeCoin](https://github.com/Savjee/SavjeeCoin) | 696 | `mocha tests/*.test.js` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [apollographql/eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) | 694 | `tav --ci && mocha test/index.js` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 693 | `mocha` | 
| [CharlesStover/reactn](https://github.com/CharlesStover/reactn) | 693 | `mocha -r chai/register-expect -r @babel/register -r ts-node/register "tests/**/*.spec.ts?(x)"` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 688 | `mocha -R spec` | 
| [afc163/fanyi](https://github.com/afc163/fanyi) | 688 | `npm run lint && mocha tests/index.js --timeout 0` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 686 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [klokantech/tileserver-gl](https://github.com/klokantech/tileserver-gl) | 686 | `mocha test/**.js --timeout 10000` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 685 | `mocha --compilers js:babel-register` | 
| [godaddy/terminus](https://github.com/godaddy/terminus) | 683 | `mocha index.spec.js lib/**/*.spec.js && npm run test-typings` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 683 | `mocha --bail test/` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 678 | `mocha --require babel-register` | 
| [shime/livedown](https://github.com/shime/livedown) | 677 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [mtth/avsc](https://github.com/mtth/avsc) | 677 | `mocha` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 675 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 671 | `mocha -b -R spec test/*` | 
| [theoephraim/node-google-spreadsheet](https://github.com/theoephraim/node-google-spreadsheet) | 670 | `node_modules/.bin/mocha` | 
| [calmm-js/partial.lenses](https://github.com/calmm-js/partial.lenses) | 669 | `nyc mocha && nyc report -r html mocha` | 
| [coinbase/gdax-node](https://github.com/coinbase/gdax-node) | 667 | `mocha --full-trace --ui tdd --bail --reporter spec tests/*.js` | 
| [omnidan/node-emoji](https://github.com/omnidan/node-emoji) | 667 | `./node_modules/.bin/mocha --require should --bail --reporter spec test/*` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 667 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 667 | `mocha` | 
| [maxkueng/victor](https://github.com/maxkueng/victor) | 667 | `mocha --ui bdd --reporter spec` | 
| [catamphetamine/universal-webpack](https://github.com/catamphetamine/universal-webpack) | 666 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [kwhitley/apicache](https://github.com/kwhitley/apicache) | 665 | `nyc mocha $(find test -name '*.test.js') --recursive` | 
| [joaonuno/tree-model-js](https://github.com/joaonuno/tree-model-js) | 665 | `istanbul cover _mocha` | 
| [dtschust/redux-bug-reporter](https://github.com/dtschust/redux-bug-reporter) | 662 | `standard && mocha --compilers js:babel-register --recursive --require test/setup.js` | 
| [anandanand84/technicalindicators](https://github.com/anandanand84/technicalindicators) | 662 | `mocha --compilers js:babel-register --require babel-polyfill` | 
| [LouisBarranqueiro/reapop](https://github.com/LouisBarranqueiro/reapop) | 662 | `babel-node ./node_modules/karma/bin/karma start ./build/karma.conf.js --reporters mocha` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 660 | `mocha --recursive --compilers js:babel-core/register` | 
| [spirit/spirit](https://github.com/spirit/spirit) | 653 | `BABEL_ENV=modules NODE_ENV=test mocha -r babel-register -r babel-polyfill -r ./test/bootstrap.js --timeout 5000` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 653 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [atom/github](https://github.com/atom/github) | 652 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 650 | `./node_modules/.bin/mocha test/integration` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 650 | `./node_modules/.bin/mocha --bail` | 
| [azmenak/react-stripe-checkout](https://github.com/azmenak/react-stripe-checkout) | 649 | `mocha --require babel-register --require .test-setup.js -R spec ./spec.js` | 
| [postcss/gulp-postcss](https://github.com/postcss/gulp-postcss) | 647 | `nyc mocha test.js` | 
| [vault-development/react-native-svg-uri](https://github.com/vault-development/react-native-svg-uri) | 646 | `./node_modules/mocha/bin/mocha --compilers js:babel-core/register` | 
| [gauntface/simple-push-demo](https://github.com/gauntface/simple-push-demo) | 646 | `gulp && npm run lint && node ./test/helpers/download-browsers.js && mocha` | 
| [jshttp/http-errors](https://github.com/jshttp/http-errors) | 645 | `mocha --reporter spec --bail` | 
| [tonyhb/redux-ui](https://github.com/tonyhb/redux-ui) | 642 | `$(npm bin)/mocha  --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [phodal/sherlock](https://github.com/phodal/sherlock) | 640 | `mocha --reporter spec` | 
| [edankwan/penis.js](https://github.com/edankwan/penis.js) | 639 | `mocha --ui bdd --reporter spec test/` | 
| [floatdrop/gulp-watch](https://github.com/floatdrop/gulp-watch) | 639 | `xo && mocha -r test/util/set-default-options -t 5000 -R spec test/test-*` | 
| [fent/node-ytdl](https://github.com/fent/node-ytdl) | 638 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [hparra/gulp-rename](https://github.com/hparra/gulp-rename) | 638 | `mocha` | 
| [aliyun-UED/aliyun-sdk-js](https://github.com/aliyun-UED/aliyun-sdk-js) | 638 | `mocha test` | 
| [DEgITx/rats-search](https://github.com/DEgITx/rats-search) | 636 | `mocha temp/tests.js --require @babel/core/lib --require source-map-support/register` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 658 | `mocha` | 
| [pburtchaell/react-notification](https://github.com/pburtchaell/react-notification) | 657 | `node_modules/.bin/mocha --compilers js:babel-core/register --reporter spec --recursive --timeout 5000 test/setup.js test/**/*.js` | 
| [chao/RESTClient](https://github.com/chao/RESTClient) | 657 | `mocha` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 657 | `mocha` | 
| [jbrooksuk/node-summary](https://github.com/jbrooksuk/node-summary) | 656 | `mocha --compilers js:babel-core/register --require should --reporter spec` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 654 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [spirit/spirit](https://github.com/spirit/spirit) | 653 | `BABEL_ENV=modules NODE_ENV=test mocha -r babel-register -r babel-polyfill -r ./test/bootstrap.js --timeout 5000` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 653 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [atom/github](https://github.com/atom/github) | 652 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [rkusa/koa-passport](https://github.com/rkusa/koa-passport) | 651 | `mocha` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 650 | `./node_modules/.bin/mocha test/integration` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 650 | `./node_modules/.bin/mocha --bail` | 
| [azmenak/react-stripe-checkout](https://github.com/azmenak/react-stripe-checkout) | 649 | `mocha --require babel-register --require .test-setup.js -R spec ./spec.js` | 
| [danielstjules/buddy.js](https://github.com/danielstjules/buddy.js) | 648 | `mocha -R spec spec/unit spec/integration` | 
| [postcss/gulp-postcss](https://github.com/postcss/gulp-postcss) | 647 | `nyc mocha test.js` | 
| [danielstjules/buddy.js](https://github.com/danielstjules/buddy.js) | 648 | `mocha -R spec spec/unit spec/integration` | 
| [postcss/gulp-postcss](https://github.com/postcss/gulp-postcss) | 647 | `nyc mocha test.js` | 
| [vault-development/react-native-svg-uri](https://github.com/vault-development/react-native-svg-uri) | 646 | `./node_modules/mocha/bin/mocha --compilers js:babel-core/register` | 
| [gauntface/simple-push-demo](https://github.com/gauntface/simple-push-demo) | 646 | `gulp && npm run lint && node ./test/helpers/download-browsers.js && mocha` | 
| [ideal-postcodes/postcodes.io](https://github.com/ideal-postcodes/postcodes.io) | 646 | `NODE_ENV=test npm run test:create && npm run nyc_mocha && NODE_ENV=test npm run test:clear && npm run lint` | 
| [jshttp/http-errors](https://github.com/jshttp/http-errors) | 645 | `mocha --reporter spec --bail` | 
| [tonyhb/redux-ui](https://github.com/tonyhb/redux-ui) | 642 | `$(npm bin)/mocha  --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [phodal/sherlock](https://github.com/phodal/sherlock) | 640 | `mocha --reporter spec` | 
| [edankwan/penis.js](https://github.com/edankwan/penis.js) | 639 | `mocha --ui bdd --reporter spec test/` | 
| [floatdrop/gulp-watch](https://github.com/floatdrop/gulp-watch) | 639 | `xo && mocha -r test/util/set-default-options -t 5000 -R spec test/test-*` | 
| [fent/node-ytdl](https://github.com/fent/node-ytdl) | 638 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [hparra/gulp-rename](https://github.com/hparra/gulp-rename) | 638 | `mocha` | 
| [aliyun-UED/aliyun-sdk-js](https://github.com/aliyun-UED/aliyun-sdk-js) | 638 | `mocha test` | 
| [DEgITx/rats-search](https://github.com/DEgITx/rats-search) | 636 | `mocha temp/tests.js --require @babel/core/lib --require source-map-support/register` | 
| [desmondmorris/node-tesseract](https://github.com/desmondmorris/node-tesseract) | 610 | `mocha` | 
| [webdriverio-boneyard/webdrivercss](https://github.com/webdriverio-boneyard/webdrivercss) | 609 | `./node_modules/.bin/mocha` | 
| [ipfs-shipyard/ipfs-desktop](https://github.com/ipfs-shipyard/ipfs-desktop) | 608 | `cross-env NODE_ENV=test mocha` | 
| [GoogleChromeLabs/pwacompat](https://github.com/GoogleChromeLabs/pwacompat) | 607 | `mocha-headless-server suite.html` | 
| [SGrondin/bottleneck](https://github.com/SGrondin/bottleneck) | 607 | `mocha test` | 
| [shinnn/gulp-gh-pages](https://github.com/shinnn/gulp-gh-pages) | 606 | `nyc mocha test.js --timeout 50000 --full-trace` | 
| [cgross/generator-cg-angular](https://github.com/cgross/generator-cg-angular) | 606 | `mocha` | 
| [victorb/autochecker](https://github.com/victorb/autochecker) | 604 | `mocha` | 
| [echenley/react-news](https://github.com/echenley/react-news) | 603 | `./node_modules/.bin/karma start ./test/karma.conf.js --reporters mocha,coverage` | 
| [times/cardkit](https://github.com/times/cardkit) | 601 | `./node_modules/.bin/istanbul cover --dir test/coverage ./node_modules/.bin/_mocha -- --compilers js:babel-core/register --require ignore-styles` | 
| [newsdev/ai2html](https://github.com/newsdev/ai2html) | 599 | `mocha --check-leaks` | 
| [putaoshu/jdf](https://github.com/putaoshu/jdf) | 598 | `mocha test/index.js` | 
| [matthewmueller/graph.ql](https://github.com/matthewmueller/graph.ql) | 597 | `./node_modules/.bin/mocha` | 
| [SamyPesse/gitkit-js](https://github.com/SamyPesse/gitkit-js) | 596 | `./node_modules/.bin/mocha ./testing/setup.js ./lib/**/*/__tests__/*.js --bail --reporter=list` | 
| [screwdriver-cd/screwdriver](https://github.com/screwdriver-cd/screwdriver) | 596 | `jenkins-mocha --recursive --timeout 3000 --exit` | 
| [ck86/main-bower-files](https://github.com/ck86/main-bower-files) | 596 | `mocha` | 
| [mhart/kinesalite](https://github.com/mhart/kinesalite) | 595 | `mocha --require should --reporter spec -t $([ $REMOTE ] && echo 30s || echo 4s)` | 
| [desmondmorris/node-tesseract](https://github.com/desmondmorris/node-tesseract) | 610 | `mocha` | 
| [Charca/bootbot](https://github.com/Charca/bootbot) | 610 | `mocha --recursive test/*` | 
| [webdriverio-boneyard/webdrivercss](https://github.com/webdriverio-boneyard/webdrivercss) | 609 | `./node_modules/.bin/mocha` | 
| [ipfs-shipyard/ipfs-desktop](https://github.com/ipfs-shipyard/ipfs-desktop) | 608 | `cross-env NODE_ENV=test mocha` | 
| [GoogleChromeLabs/pwacompat](https://github.com/GoogleChromeLabs/pwacompat) | 607 | `mocha-headless-server suite.html` | 
| [SGrondin/bottleneck](https://github.com/SGrondin/bottleneck) | 607 | `mocha test` | 
| [shinnn/gulp-gh-pages](https://github.com/shinnn/gulp-gh-pages) | 606 | `nyc mocha test.js --timeout 50000 --full-trace` | 
| [cgross/generator-cg-angular](https://github.com/cgross/generator-cg-angular) | 606 | `mocha` | 
| [victorb/autochecker](https://github.com/victorb/autochecker) | 604 | `mocha` | 
| [echenley/react-news](https://github.com/echenley/react-news) | 603 | `./node_modules/.bin/karma start ./test/karma.conf.js --reporters mocha,coverage` | 
| [times/cardkit](https://github.com/times/cardkit) | 601 | `./node_modules/.bin/istanbul cover --dir test/coverage ./node_modules/.bin/_mocha -- --compilers js:babel-core/register --require ignore-styles` | 
| [newsdev/ai2html](https://github.com/newsdev/ai2html) | 599 | `mocha --check-leaks` | 
| [putaoshu/jdf](https://github.com/putaoshu/jdf) | 598 | `mocha test/index.js` | 
| [matthewmueller/graph.ql](https://github.com/matthewmueller/graph.ql) | 597 | `./node_modules/.bin/mocha` | 
| [SamyPesse/gitkit-js](https://github.com/SamyPesse/gitkit-js) | 596 | `./node_modules/.bin/mocha ./testing/setup.js ./lib/**/*/__tests__/*.js --bail --reporter=list` | 
| [screwdriver-cd/screwdriver](https://github.com/screwdriver-cd/screwdriver) | 596 | `jenkins-mocha --recursive --timeout 3000 --exit` | 
| [Paxa/postbird](https://github.com/Paxa/postbird) | 508 | `electron-mocha tests/` | 
| [storybook-eol/react-native-storybook](https://github.com/storybook-eol/react-native-storybook) | 503 | `mocha -r babel-register -r babel-polyfill src/**/__tests__/**/*.js` | 
| [fgnass/domino](https://github.com/fgnass/domino) | 502 | `npm run lint && npm run mocha` | 
| [digiaonline/react-foundation](https://github.com/digiaonline/react-foundation) | 502 | `NODE_ENV=test mocha --compilers js:babel-core/register --require test/index.js --recursive --colors` | 
| [steos/reactcards](https://github.com/steos/reactcards) | 501 | `mocha test/setup.js test/*test.js` | 
| [ebdrup/html2pdf.it](https://github.com/ebdrup/html2pdf.it) | 499 | `_mocha` | 
| [careercup/CtCI-6th-Edition-JavaScript-ES2015](https://github.com/careercup/CtCI-6th-Edition-JavaScript-ES2015) | 498 | `./node_modules/.bin/mocha` | 
| [santinic/pampy.js](https://github.com/santinic/pampy.js) | 495 | `mocha tests` | 
| [ohanhi/hyperscript-helpers](https://github.com/ohanhi/hyperscript-helpers) | 492 | `npm run lint && mocha` | 