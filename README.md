# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:15 05/30/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 41788 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40619 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38528 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29573 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24052 | `npm run lint && npm run mocha-node-test` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 22607 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22275 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 18906 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18369 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16274 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15846 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14321 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14119 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13438 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12714 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12459 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12283 | `./node_modules/.bin/mocha test/` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 12177 | `mocha --reporter spec` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12144 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12071 | `mocha --reporter spec test/*-test.js` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11791 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11111 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10959 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10498 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10377 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9948 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9694 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9690 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9662 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9632 | `set NODE_ENV=test && mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7328 | `npm run build && istanbul cover _mocha` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 7142 | `nyc mocha test/**/* -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7044 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6988 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6855 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6780 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6765 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6677 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6560 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6123 | `npm run jshint && mocha test/` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6113 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6104 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6030 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5847 | `mocha test node-test --recursive` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5824 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5814 | `mocha test/test.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5599 | `mocha; jshint *.js lib` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5598 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5589 | `mocha && eslint lib/**` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5297 | `mocha` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5274 | `mocha --timeout 10000 && npm run lint` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5219 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5159 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5154 | `mocha --color` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5045 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6560 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6267 | `npm run lint -s && npm run mocha -s` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6123 | `npm run jshint && mocha test/` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6113 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6104 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 6045 | `npm run build-cli && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6030 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5937 | `mocha` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5847 | `mocha test node-test --recursive` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5831 | `mocha --exit --require babel-core/register` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5824 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5814 | `mocha test/test.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5712 | `mocha tests/node.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5599 | `mocha; jshint *.js lib` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5598 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5589 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5510 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5407 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5364 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5297 | `mocha` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5274 | `mocha --timeout 10000 && npm run lint` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5219 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5159 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5154 | `mocha --color` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5045 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4930 | `standard && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4920 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4893 | `gulp lint && mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4875 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4814 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4719 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4693 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4675 | `mocha --reporter spec -t 8000` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4660 | `mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4645 | `gulp build; mocha;` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4585 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4584 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4554 | `mocha ./test/runner.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4492 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4491 | `./node_modules/.bin/mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4473 | `mocha test` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4416 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4351 | `mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4322 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4321 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4220 | `mocha -R spec ./test --recursive` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4197 | `NODE_ENV=test mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4193 | `mocha --recursive && make test` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4155 | `nyc mocha --exit` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 4095 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4091 | `nyc mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4078 | `npm run lint && npm run mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3969 | `mocha --require test/babel-hook test/*.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 3957 | `mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3920 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3903 | `mocha -R spec ./test` | 
| [tj/ejs](https://github.com/tj/ejs) | 3897 | `mocha --require should --reporter spec` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3887 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3875 | `export TESTING=true; mocha --reporter list` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3857 | `npm run lint ; mocha && mocha test/individual` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3828 | `npm run lint && npm run mocha` | 
| [erming/shout](https://github.com/erming/shout) | 3802 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3783 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3770 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3763 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3695 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3661 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3618 | `standard && mocha --timeout 60000 test/test.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3585 | `mocha --check-leaks --reporter spec --bail` | 
| [primus/primus](https://github.com/primus/primus) | 3582 | `npm run build && mocha test/*.test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3560 | `mocha tests/javascript` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3534 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3499 | `mocha --reporter spec --timeout 3000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3480 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3461 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3449 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3434 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3434 | `nyc mocha "test/**/*.test.js"` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3428 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3419 | `mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3415 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3400 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3385 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3353 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3338 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3330 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3322 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3258 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3180 | `NODE_ENV=test mocha test/**/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3125 | `node_modules/.bin/mocha test/tests.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3119 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3115 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3111 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3109 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 3075 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3074 | `mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3071 | `nyc mocha && tsc` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3039 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3023 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3019 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2889 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2885 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2867 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2857 | `mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2841 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2836 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2835 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2834 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2801 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2788 | `istanbul cover _mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2776 | `mocha --require should --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2769 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2761 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2754 | `mocha --opts mocha.opts` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2750 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2730 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2727 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2722 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2719 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2730 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2727 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2722 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2719 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2713 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2697 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2689 | `npm run mocha && npm run lint` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2677 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2677 | `xo && mocha` | 
| [css/csso](https://github.com/css/csso) | 2667 | `mocha --reporter dot` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2658 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2650 | `mocha --require babel-register --recursive spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2648 | `mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2621 | `mocha --timeout 100000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2603 | `mocha-phantomjs ./test/index.html` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2583 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2650 | `mocha --require babel-register --recursive spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2648 | `mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2621 | `mocha --timeout 100000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2603 | `mocha-phantomjs ./test/index.html` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2588 | `mocha --recursive --watch` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2583 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2578 | `node_modules/.bin/mocha --reporter spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2552 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2539 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2532 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2526 | `mocha -R landing test/index` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2526 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2498 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2483 | `npm run build && cd test && mocha . --reporter dot` | 
| [mde/ejs](https://github.com/mde/ejs) | 2466 | `mocha --require should --reporter spec` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2457 | `mocha --reporter=spec test/*-test.js` | 
| [json5/json5](https://github.com/json5/json5) | 2444 | `nyc --reporter=html --reporter=text mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2440 | `nyc mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2426 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2406 | `mocha test` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2397 | `mocha "test/**/*-test.js"` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2386 | `mocha test/src/**/*.unit.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2384 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2380 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2373 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2372 | `mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2353 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2344 | `mocha test/unit --require mochahook` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2340 | `mocha --no-colors --reporter spec` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2340 | `mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2338 | `grunt jshint && mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2320 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2293 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2290 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2282 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2256 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2246 | `mocha -R spec` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2242 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2237 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2224 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2212 | `nyc --reporter=html --reporter=text mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2165 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2155 | `mocha test && npm run lint` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2143 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2141 | `mocha && eslint .` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2117 | `eslint . && mocha -t 5000` | 
| [noble/noble](https://github.com/noble/noble) | 2109 | `mocha -R spec test/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2105 | `cross-env BABEL_ENV=test mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2093 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2084 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2079 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2050 | `mocha --compilers js:babel-register` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1856 | `mocha && eslint *.js` | 
| [then/promise](https://github.com/then/promise) | 1850 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [share/sharedb](https://github.com/share/sharedb) | 1849 | `./node_modules/.bin/mocha && npm run jshint` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1842 | `npm run lint && mocha -R dot && npm run cover` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1824 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1816 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1803 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1797 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1796 | `mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1782 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1776 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1772 | `mocha --reporter spec && npm run test-typescript` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1769 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1766 | `npm run lint && mocha --reporter spec test/*.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1759 | `mocha -R spec spec spec/reporters` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1718 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1718 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1699 | `mocha --reporter spec test/*.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1695 | `mocha tests --compilers js:babel-core/register` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1691 | `./node_modules/.bin/mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1691 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1675 | `xo && mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1651 | `mocha test -u bdd -R spec` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1647 | `npm run lint && mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1638 | `mocha test/*.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1627 | `mocha --expose-gc --slow 300` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1623 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1675 | `xo && mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1663 | `mocha test/**/*.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1651 | `mocha test -u bdd -R spec` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1647 | `npm run lint && mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1644 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1638 | `mocha test/*.js` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1636 | `mocha test --timeout 600000` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1635 | `mocha ./test/basic.js -t 5000` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1634 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1629 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1627 | `mocha --expose-gc --slow 300` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1623 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1620 | `mocha tests/test.js` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1614 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1611 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1609 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1608 | `mocha && size-limit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1604 | `mocha --compilers js:babel-register` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1590 | `mocha test/* --reporter spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1588 | `npm run lint && npm run mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1588 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1565 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1551 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1539 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1535 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1526 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1514 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1511 | `mocha --reporter spec` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1511 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1500 | `npm run test:lint && npm run test:mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1499 | `mocha compiled_tests/` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1464 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1461 | `nyc mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1460 | `mocha test.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1458 | `mocha test/setup.js test/spec/*.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1457 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1457 | `mocha test/**/*.spec.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1450 | `mocha test/tests.js --timeout=10000` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1441 | `mocha --check-leaks --reporter spec --bail` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1437 | `mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1436 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1426 | `mocha --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1422 | `nyc npm run mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1416 | `mocha test.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1445 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1441 | `mocha --check-leaks --reporter spec --bail` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1437 | `mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1436 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1436 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1426 | `mocha --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1422 | `nyc npm run mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1416 | `mocha test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1395 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1384 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1368 | `./node_modules/mocha/bin/mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1360 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1354 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1351 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1348 | `cross-env NODE_ENV=test nyc mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1343 | `mocha -R spec test/*.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1335 | `mocha test` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1326 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1326 | `npm run build && mocha -r should` | 
| [electron/devtron](https://github.com/electron/devtron) | 1317 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1308 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1308 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1298 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1298 | `mocha-phantomjs tests/index.html` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1296 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1289 | `mocha --check-leaks --require @babel/register` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1287 | `./node_modules/.bin/mocha test` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1109 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1104 | `NODE_ENV=test mocha tests/*.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1102 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1101 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1101 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1100 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1098 | `mocha ./test/test*.js --reporter spec` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1097 | `mocha $(find test -name '*.test.js')` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1095 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1087 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1087 | `xo && mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1084 | `mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1084 | `mocha test/*` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1078 | `NODE_PATH=. mocha **/*.spec.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1076 | `npm run lint && npm run mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1072 | `mocha --compilers js:babel-register` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1070 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1069 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1228 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1227 | `mocha tests` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1224 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1223 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1223 | `standard && istanbul cover _mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1222 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1221 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1220 | `mocha --reporter dot` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1217 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1217 | `mocha test/test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1211 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1208 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1205 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1202 | `mocha test/**/*Spec.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1202 | `mocha tests/test-*` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1188 | `node ./node_modules/mocha/bin/mocha tests` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1187 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1187 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1186 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1186 | `mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1185 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1183 | `mocha test` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1179 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1176 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1175 | `mocha src/test.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1169 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1166 | `mocha --reporter spec` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1166 | `mocha` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1161 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1158 | `npm run lint && npm run mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1158 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1153 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1117 | `TEST=all mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1105 | `npm run prepublishOnly && mocha test/test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1103 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1096 | `mocha --recursive test` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1091 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1087 | `xo && mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1084 | `mocha test/*` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1080 | `mocha --check-leaks -t 20000` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1080 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1078 | `NODE_PATH=. mocha **/*.spec.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1076 | `npm run lint && npm run mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1075 | `istanbul cover _mocha test/*.js` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1072 | `mocha --compilers js:babel-register` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1070 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1069 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1065 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1105 | `npm run prepublishOnly && mocha test/test.js` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1104 | `NODE_ENV=test mocha tests/*.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1103 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1102 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1101 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1100 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1098 | `mocha ./test/test*.js --reporter spec` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1097 | `mocha $(find test -name '*.test.js')` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1096 | `mocha --recursive test` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1095 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1091 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1087 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1084 | `mocha` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1080 | `mocha --check-leaks -t 20000` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1080 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1075 | `istanbul cover _mocha test/*.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1070 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1069 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1080 | `mocha --check-leaks -t 20000` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1080 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1078 | `NODE_PATH=. mocha **/*.spec.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1076 | `npm run lint && npm run mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1075 | `istanbul cover _mocha test/*.js` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1072 | `mocha --compilers js:babel-register` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1070 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1069 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1065 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1055 | `mocha --compilers js:babel-core/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1052 | `istanbul test _mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1049 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1047 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1046 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1044 | `mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1041 | `mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1040 | `mocha --reporter spec --timeout 3000` | 
| [router5/router5](https://github.com/router5/router5) | 1040 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1039 | `webpack && npm run lint && npm run mocha` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1038 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1034 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1033 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1032 | `mocha test/tests.js` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1032 | `mocha --recursive test/bin` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1031 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1028 | `mocha` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1027 | `standard && mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1023 | `mocha --recursive --bail --reporter spec test` | 
| [jas/playground](https://github.com/jas/playground) | 1021 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1020 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1019 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1011 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [electron/asar](https://github.com/electron/asar) | 1010 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1007 | `webpack && mocha test/unit` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1003 | `mocha $(find test -name '*.test.js')` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1000 | `mocha` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 998 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 998 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 992 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 992 | `mocha --reporter spec --bail --check-leaks test/` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 987 | `mocha --recursive test/unit/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 986 | `mocha --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 985 | `mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 984 | `mocha test` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 983 | `standard && mocha -b` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 979 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 978 | `npm run lint && mocha --require @babel/register` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 976 | `mocha --async-only` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 976 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 975 | `mocha && standard` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 968 | `mocha -R list` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 962 | `eslint src test && mocha --compilers babel-register` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 962 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 960 | `mocha --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 958 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 954 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 952 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 952 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 948 | `mocha --timeout 5000` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 947 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 943 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 943 | `npm run mocha:istanbul` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 939 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 924 | `mocha "client.test" --compilers js:babel-register` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 921 | `npm run convertto:es5 && npm run mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 918 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 916 | `mocha` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 913 | `npm-run-all test:jest test:server:mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 908 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 906 | `mocha --compilers js:babel-register test/*.js` | 
| [jvalen/pixel-art-react](https://github.com/jvalen/pixel-art-react) | 903 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js 'test/**/*.@(js|jsx)'` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 902 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 901 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 899 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 892 | `npm run lint && mocha -R spec` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 891 | `mocha -R spec` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 891 | `./node_modules/.bin/mocha --globals angular,require` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 890 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 888 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 884 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 879 | `mocha tests` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 869 | `node_modules/.bin/mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 869 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 866 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 864 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 862 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 861 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 861 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 859 | `npm run lint && npm run mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 859 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 858 | `mocha --timeout 200000` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 857 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 856 | `mocha -t 600000` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 856 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 850 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 850 | `eslint test && mocha --compilers js:babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 849 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 845 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 838 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 837 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 834 | `mocha -t 5000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 834 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 833 | `mocha --check-leaks -t 20000` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 830 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 830 | `istanbul cover _mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 830 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 830 | `standard && standard ./bin/* && mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 827 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 826 | `mocha spec/*.js` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 825 | `mocha test --compilers js:babel-register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 824 | `nyc mocha specs` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 824 | `mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 824 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 822 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 821 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 821 | `istanbul cover -- _mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 820 | `./node_modules/.bin/mocha -R spec` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 819 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 816 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 813 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 808 | `mocha test --compilers js:babel-core/register` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 807 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 807 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 805 | `mocha --reporter spec --bail --check-leaks test/` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 803 | `mocha --reporter list` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 802 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 801 | `mocha --require babel-register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 800 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 797 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 796 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 793 | `cake build && mocha ./test/mocha/*.coffee` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 789 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 788 | `./node_modules/.bin/mocha --reporter spec` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 787 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 786 | `mocha --async-only` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 783 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 781 | `mocha --colors --reporter spec test.js` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 780 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 779 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 777 | `npm run lint && mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 776 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 776 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 762 | `npm run mocha-test test/integration` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 761 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 758 | `mocha --ui tdd --require ./test/__setup` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 758 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 757 | `nyc --check-coverage mocha test/*.test.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 757 | `mocha` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 756 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 756 | `mocha test` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 756 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 754 | `mocha --harmony --full-trace --check-leaks` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 754 | `mocha -R spec src/**/*_test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 753 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 752 | `mocha --recursive ./test/*_spec.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 749 | `npm run build && istanbul test _mocha test/test.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 749 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 748 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 747 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 756 | `mocha test` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 756 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 754 | `mocha --harmony --full-trace --check-leaks` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 754 | `mocha -R spec src/**/*_test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 753 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 752 | `mocha --recursive ./test/*_spec.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 749 | `npm run build && istanbul test _mocha test/test.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 749 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 748 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 747 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 744 | `mocha --recursive -s 15 test/` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 744 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 743 | `mocha test/index.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 741 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 741 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [developit/decko](https://github.com/developit/decko) | 738 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 738 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 736 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 736 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 734 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 732 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 731 | `mocha test` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 731 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 731 | `mocha --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 730 | `mocha test` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 730 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 728 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 725 | `mocha --no-timeouts` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 724 | `mocha test.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 724 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 723 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 711 | `npm run bundle && mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 711 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 710 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 710 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 708 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 707 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 703 | `mocha -r should --reporter spec test/*.js` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 701 | `mocha` | 
| [webpack-contrib/webpack-serve](https://github.com/webpack-contrib/webpack-serve) | 700 | `nyc npm run mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 699 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 697 | `mocha ./test/index.js` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 696 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 696 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 696 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 696 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 691 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 691 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 691 | `babel-node node_modules/.bin/_mocha -- test` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 691 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 691 | `./node_modules/.bin/mocha -t 60000` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 688 | `./bin/selenium-standalone install && mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 688 | `mocha` | 
| [scality/S3](https://github.com/scality/S3) | 687 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 687 | `mocha --reporter spec` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 685 | `mocha --reporter spec build/test/index.js` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 682 | `mocha ./test/test.js --timeout 1000000` | 