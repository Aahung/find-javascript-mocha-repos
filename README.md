# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:31 12/28/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44728 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41886 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41663 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30750 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 25076 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24697 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21146 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19928 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18213 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17794 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17639 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16796 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14932 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14745 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14630 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13801 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13481 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12947 | `mocha 'test/**/*.spec.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12711 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12700 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12662 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12346 | `mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12219 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12161 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12157 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11332 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10987 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10847 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10760 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10625 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10514 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10371 | `mocha --harmony` | 
| [websockets/ws](https://github.com/websockets/ws) | 10258 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9648 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9629 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9545 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 9395 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9395 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9269 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9239 | `grunt mocha` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8817 | `mocha test/src` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8687 | `mocha --opts mocha.opts` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8647 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8542 | `mocha --check-leaks -R dot` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8503 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8453 | `mocha --compilers js:babel-register test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8429 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8363 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8217 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8010 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7945 | `./node_modules/.bin/mocha test` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7893 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7878 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7777 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [aui/art-template](https://github.com/aui/art-template) | 7761 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7761 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7567 | `npm run build && istanbul cover _mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7498 | `mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7459 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7429 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7374 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7349 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7292 | `mocha --exit --require @babel/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7088 | `mocha $HARMONY_OPTS` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7061 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6920 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6739 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6669 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6501 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6465 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6361 | `npm run test:mocha:src` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6231 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6187 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6159 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6117 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6085 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6072 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6060 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6050 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5939 | `mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5868 | `standard && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5852 | `mocha && eslint lib/**` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5674 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5641 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5579 | `npm run lint && mocha tests/**/*.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5576 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5500 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5449 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5439 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5409 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5302 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5290 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5248 | `mocha test` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5203 | `mocha src/**/*Tests.js --harmony` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5152 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5135 | `mocha --color` | 
| [teambit/bit](https://github.com/teambit/bit) | 5104 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5099 | `gulp lint && mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4955 | `mocha --recursive` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4914 | `gulp build; mocha;` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4906 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4860 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4844 | `./node_modules/.bin/mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4837 | `nyc mocha --exit` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4835 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4832 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4804 | `mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4784 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4781 | `npm run lint && npm run mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4777 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4732 | `mocha --reporter spec -t 8000` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4724 | `nyc mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4573 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4536 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4503 | `mocha -R spec src` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4503 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4477 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 4376 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4360 | `mocha --timeout=15000 tests/*.test.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4360 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4308 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4260 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4245 | `mocha --check-leaks --reporter spec --bail` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4230 | `nyc mocha` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4217 | `npm run lint ; mocha && mocha test/individual` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4201 | `NODE_ENV=test mocha --exit` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4200 | `mocha -R spec ./test --recursive` | 
| [muicss/mui](https://github.com/muicss/mui) | 4120 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4096 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4074 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4059 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3999 | `nyc mocha "test/**/*.test.js"` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3704 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3683 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3680 | `standard && mocha --timeout 60000 test/test.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3671 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3637 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3629 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3581 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3579 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3559 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3483 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3458 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3458 | `mocha && tsc -p ./test/types` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3452 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3414 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3375 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3368 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3281 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3274 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3680 | `standard && mocha --timeout 60000 test/test.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3671 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3669 | `npm run jshint && npm run mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3637 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3629 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3602 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3598 | `mocha tests/javascript` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3581 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3579 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3559 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3535 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3534 | `eslint . && mocha -t 5000` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3494 | `nyc mocha && tsc` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3483 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3458 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3458 | `mocha && tsc -p ./test/types` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3452 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3375 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3344 | `npm run mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3343 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3334 | `mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3317 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3303 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3281 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3280 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3274 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3270 | `mocha -R landing test/index --exit` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3252 | `mocha test/index.js && npm run demo` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3231 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3224 | `mocha test/*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3203 | `mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3231 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3224 | `mocha test/*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3203 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3180 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3176 | `./node_modules/.bin/mocha test/test.*.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3175 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3172 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3161 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3139 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3133 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 3082 | `mocha --require should --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3077 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3060 | `eslint . && nyc mocha --recursive` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3054 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3049 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3007 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2993 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2969 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2969 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2964 | `node_modules/.bin/mocha --reporter spec` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2946 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2946 | `mocha` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2940 | `mocha test-node` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2936 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2935 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2929 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2926 | `mocha --require @babel/register --recursive spec` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2926 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2906 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2885 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2875 | `mocha -R spec spec spec/reporters` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2864 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2533 | `export TESTING=true; mocha --reporter list` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2532 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2522 | `mocha test/src/**/*.unit.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2505 | `mocha test --exit && npm run lint` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2492 | `mocha` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2478 | `mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2473 | `mocha && eslint .` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2452 | `mocha test/index.js --reporter dot` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2445 | `mocha --no-colors --reporter spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2439 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2424 | `mocha -R spec` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2380 | `TEST=all mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2374 | `grunt jshint && mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2372 | `mocha -R spec test/*.js` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2372 | `node node_modules/mocha/bin/_mocha` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1943 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1936 | `mocha --reporter spec && npm run test-typescript` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1935 | `mocha test` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1920 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1900 | `npm run lint && mocha --reporter spec test/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1889 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1881 | `mocha test` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1880 | `mocha tests.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1868 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1853 | `mocha compiled_tests/` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1835 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1794 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2301 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2297 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2289 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [gajus/swing](https://github.com/gajus/swing) | 2289 | `mocha --compilers js:babel-register` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2254 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2240 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2220 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2218 | `standard && mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2218 | `mocha test test/unit/**/*_test.js` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2211 | `npm run lint && mocha tests/**/*.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2156 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2139 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2138 | `mocha` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2131 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2116 | `mocha --compilers js:babel-core/register __tests__` | 
| [share/sharedb](https://github.com/share/sharedb) | 2110 | `./node_modules/.bin/mocha && npm run jshint` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2096 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2093 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2079 | `mocha --compilers js:babel-register` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2058 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2034 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [kach/nearley](https://github.com/kach/nearley) | 2022 | `mocha test/*.test.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2017 | `npm run lint && mocha -R dot && npm run cover` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2010 | `npm run mocha && npm run karma` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2008 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2007 | `mocha --reporter spec --timeout 5000` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2003 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2000 | `mocha tests --require @babel/register` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1998 | `mocha --require=test/test_helper.js` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [then/promise](https://github.com/then/promise) | 1993 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1975 | `mocha && npm run lint` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1966 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1958 | `mocha --require ./test/common --growl test/expect.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1956 | `mocha --bail --reporter spec --check-leaks test/` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1930 | `mocha test/**/*.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1927 | `bmocha --reporter spec test/*.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1920 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1900 | `npm run lint && mocha --reporter spec test/*.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1880 | `mocha tests.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1868 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1868 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1853 | `mocha compiled_tests/` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1852 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1843 | `mocha ./test/basic.js -t 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1835 | `npm run lint && npm run mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1814 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1798 | `mocha --timeout 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1794 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1780 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1780 | `npm run lint && npm run mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1770 | `mocha test/setup.js test/spec/*.js` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1767 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1761 | `eslint --cache . && tsc && mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1755 | `nyc mocha --timeout=20000 test.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1737 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1734 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1733 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1732 | `npm run lint && mocha && npm run typescript` | 
| [zeit/ms](https://github.com/zeit/ms) | 1729 | `mocha tests.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1732 | `npm run lint && mocha && npm run typescript` | 
| [zeit/ms](https://github.com/zeit/ms) | 1729 | `mocha tests.js` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1725 | `mocha test/*.js` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1723 | `mocha test --timeout 600000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1721 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1714 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1712 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1707 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1699 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1698 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1678 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1674 | `mocha && size-limit` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1668 | `mocha --check-leaks --reporter spec --bail` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1676 | `standard "./src/*.js" && mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1675 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1674 | `mocha && size-limit` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1670 | `mocha test/test-*.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1668 | `mocha --check-leaks --reporter spec --bail` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1667 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1664 | `xo && mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1658 | `mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1644 | `mocha --expose-gc --slow 300` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1616 | `mocha --reporter spec` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1639 | `mocha tests/test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1616 | `mocha --reporter spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1616 | `mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1605 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1602 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1602 | `./node_modules/mocha/bin/mocha -R spec` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1600 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1598 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1596 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1596 | `mocha ./test/test*.js --reporter spec` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1583 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1582 | `NODE_ENV=test mocha tests/*.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1581 | `mocha --recursive` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1602 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1602 | `./node_modules/mocha/bin/mocha -R spec` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1600 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1598 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1596 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1596 | `mocha ./test/test*.js --reporter spec` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1583 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1582 | `NODE_ENV=test mocha tests/*.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1581 | `mocha --recursive` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1569 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1563 | `nyc mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1557 | `mocha test/unit` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1557 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1556 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1538 | `node_modules/.bin/mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1535 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1530 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1519 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive --exit` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1519 | `mocha --check-leaks --require @babel/register` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1514 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1513 | `mocha -R spec ./test/unit/**` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1511 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1506 | `mocha tests/test-*` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1505 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1505 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1501 | `mocha test/**/*.spec.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1332 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1328 | `lerna run test && mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1323 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1322 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1321 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1320 | `npm run mocha:istanbul` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1312 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1311 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1311 | `webpack && npm run lint && npm run mocha` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1308 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1305 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1299 | `mocha src/test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1299 | `npm run lint && mocha --require @babel/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1298 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1290 | `npm run lint && npm run mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1286 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1286 | `mocha tests/` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1283 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1278 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1396 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1394 | `mocha --recursive test` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1391 | `mocha --recursive test/bin` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1385 | `mocha --recursive` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1382 | `./node_modules/mocha/bin/mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1377 | `mocha test --compilers js:babel-core/register` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1370 | `cross-env NODE_ENV=test nyc mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1368 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1367 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1366 | `./node_modules/.bin/mocha test` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1361 | `NODE_PATH=. mocha **/*.spec.js` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1358 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1349 | `mocha --check-leaks --reporter spec --bail test/` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1349 | `mocha --check-leaks --reporter spec --bail test/` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1344 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1343 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1340 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1340 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1336 | `mocha --compilers js:babel-core/register` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1332 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1328 | `lerna run test && mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1323 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1322 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1321 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1316 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1315 | `mocha-phantomjs tests/index.html` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1314 | `mocha test/*.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1312 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1311 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1311 | `webpack && npm run lint && npm run mocha` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1308 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1308 | `mocha --timeout 60000 test/` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1305 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1302 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1300 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1299 | `mocha src/test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1299 | `npm run lint && mocha --require @babel/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1298 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1290 | `npm run lint && npm run mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1286 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1286 | `mocha tests/` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1283 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1279 | `istanbul test _mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1278 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1276 | `mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1267 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1267 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1265 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1239 | `mocha` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1238 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1235 | `mocha --reporter spec` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1232 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1221 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1220 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1218 | `node ./node_modules/mocha/bin/mocha tests` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1218 | `mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1209 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1209 | `mocha test/test.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1202 | `mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1160 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1158 | `npm-run-all test:jest test:server:mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1158 | `mocha --reporter spec --bail --check-leaks test/` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1157 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1155 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1148 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1148 | `mocha --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1140 | `mocha` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1137 | `webpack && mocha test/unit` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1125 | `mocha test/*` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1115 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [electron/spectron](https://github.com/electron/spectron) | 1114 | `mocha && standard` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1114 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1112 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1112 | `mocha --reporter spec test --recursive` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1169 | `xo && mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1168 | `mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1167 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1167 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1164 | `mocha $(find test -name '*.test.js') --exit` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1160 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1158 | `npm-run-all test:jest test:server:mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1158 | `mocha --reporter spec --bail --check-leaks test/` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1157 | `mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1149 | `istanbul cover _mocha test/*.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1148 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1148 | `mocha --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1140 | `mocha` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1137 | `webpack && mocha test/unit` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1140 | `mocha` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1137 | `webpack && mocha test/unit` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1127 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1127 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1125 | `mocha test/*` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1115 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [electron/spectron](https://github.com/electron/spectron) | 1114 | `mocha && standard` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1114 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1112 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1112 | `mocha --reporter spec test --recursive` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1112 | `standard && mocha -b` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1111 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1099 | `mocha test` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1096 | `mocha --check-leaks -t 20000` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1095 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1095 | `node_modules/.bin/mocha && npm run lint` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1090 | `mocha --recursive --bail --reporter spec test` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1090 | `npm run convertto:es5 && npm run mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1088 | `eslint src test && mocha --compilers babel-register` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1085 | `mocha --compilers js:babel-register` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1084 | `mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1083 | `mocha test/tests.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1082 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1042 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1039 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1030 | `mocha --reporter spec --timeout 3000` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1028 | `mocha --recursive test/unit/` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1019 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1018 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1002 | `mocha -R list` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1000 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 994 | `mocha test/*.test.js` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 991 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 988 | `npm run lint && mocha -R spec` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 987 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 987 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 982 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 980 | `mocha --compilers js:babel-register test/*.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 979 | `mocha --reporter spec` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 979 | `mocha spec/*.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 977 | `mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 975 | `npm run rollup-cjs && mocha test/test.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 975 | `mocha "client.test" --compilers js:babel-register` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 974 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 974 | `mocha --recursive ./test/*_spec.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 973 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 973 | `npm run lint && npm run mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 972 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 884 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 873 | `mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 871 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 869 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 865 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 861 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 860 | `istanbul cover _mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 860 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 858 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 857 | `mocha --reporter spec` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 857 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 855 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 855 | `mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 855 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 853 | `mocha --check-leaks -t 20000` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 851 | `mocha -r should --exit test/*.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 850 | `mocha --reporter spec --bail --check-leaks test/` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 847 | `npm run lint && mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 844 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 843 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 843 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 840 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 840 | `mocha --opts mocha.opts` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 838 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 831 | `mocha -r babel-register --check-leaks test/index.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 828 | `mocha --harmony tests/**` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 828 | `mocha test` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 828 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 827 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 826 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 825 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 822 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 821 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 818 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 814 | `npm run mocha-test test/integration` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 814 | `mocha` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 814 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [edsu/anon](https://github.com/edsu/anon) | 812 | `mocha --colors --reporter spec test.js` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 812 | `npm run lint && mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 785 | `npm run lint && npm run mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 784 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 784 | `mocha test` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 781 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 779 | `nyc mocha` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 779 | `mocha index.test.js` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 778 | `mocha --recursive -s 15 test/` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 794 | `mocha --no-timeouts` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 794 | `xo && mocha -R spec` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 792 | `_mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 791 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 785 | `npm run lint && npm run mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 784 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 784 | `mocha test` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 781 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 785 | `npm run lint && npm run mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 784 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 784 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 784 | `mocha test` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 781 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 779 | `nyc mocha` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 779 | `mocha index.test.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 778 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 778 | `mocha --recursive -s 15 test/` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 777 | `mocha test/mocha.js` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 776 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 773 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 772 | `mocha` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 772 | `mocha -R spec src/**/*_test.js` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 770 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 768 | `babel-node node_modules/.bin/_mocha -- test` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 766 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 762 | `jenkins-mocha ./tests/*.js` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 762 | `npm run-script jshint && npm run-script mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 762 | `mocha tests --timeout 10000` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 761 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 761 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 760 | `mocha` | 
| [susam/texme](https://github.com/susam/texme) | 759 | `standard && mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 733 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 733 | `mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 728 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 727 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 726 | `mocha $(find test -name '*.test.js')` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 721 | `mocha ./test/test.js --timeout 1000000` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 721 | `mocha 'test/**/*.tests.js'` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 721 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 720 | `mocha --compilers js:babel-core/register` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 718 | `mocha --reporter spec test/` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 742 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 742 | `mocha test.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 741 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 741 | `eslint . && mocha` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 738 | `npm run bundle && mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 735 | `npm run test-mocha && npm run test-karma` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 735 | `mocha` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 734 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 734 | `mocha` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 671 | `mocha -b -R spec test/*` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 671 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 669 | `mocha --require babel-register src/**/*.spec.js src/*.spec.js` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 668 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 667 | `mocha --require babel-register` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 664 | `mocha` | 
| [shime/livedown](https://github.com/shime/livedown) | 662 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 662 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 661 | `mocha --recursive --compilers js:babel-core/register` | 
| [coinbase/gdax-node](https://github.com/coinbase/gdax-node) | 659 | `mocha --full-trace --ui tdd --bail --reporter spec tests/*.js` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 658 | `mocha --reporter spec` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 657 | `mocha` | 
| [pburtchaell/react-notification](https://github.com/pburtchaell/react-notification) | 655 | `node_modules/.bin/mocha --compilers js:babel-core/register --reporter spec --recursive --timeout 5000 test/setup.js test/**/*.js` | 
| [mtth/avsc](https://github.com/mtth/avsc) | 655 | `mocha` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 655 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 718 | `mocha --reporter spec test/` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 713 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 712 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 710 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [typicode/katon](https://github.com/typicode/katon) | 707 | `mocha --reporter list test/cli/index test/daemon/index` | 