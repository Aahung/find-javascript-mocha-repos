# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:15 11/30/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44434 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41722 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41284 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30620 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24955 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24362 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20877 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19749 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17990 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17584 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17443 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16354 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14626 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14557 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14555 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13692 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12893 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12623 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12507 | `istanbul cover _mocha` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12893 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12623 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12507 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12316 | `mocha` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12150 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12034 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12014 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11954 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11155 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10824 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10639 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10621 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10462 | `mocha` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10398 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10301 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10289 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [websockets/ws](https://github.com/websockets/ws) | 10092 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9582 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9519 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9361 | `mocha -b -r esm` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9334 | `mocha tests/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9194 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 9152 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9124 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8751 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8615 | `mocha test/test.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7651 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [dthree/cash](https://github.com/dthree/cash) | 7578 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7536 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7452 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7354 | `mocha --compilers js:babel-core/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7245 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7232 | `mocha; jshint *.js lib` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7184 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7082 | `mocha --exit --require @babel/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7054 | `mocha $HARMONY_OPTS` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6992 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6812 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6628 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6454 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7452 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7354 | `mocha --compilers js:babel-core/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7245 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7232 | `mocha; jshint *.js lib` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7184 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7082 | `mocha --exit --require @babel/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7054 | `mocha $HARMONY_OPTS` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6992 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6812 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6628 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6530 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6454 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6332 | `npm run test:mocha:src` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6258 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6157 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6156 | `mocha tests/node.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6063 | `mocha` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6054 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6005 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5988 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5978 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5937 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5821 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5760 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5609 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5598 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5469 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5416 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5399 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5359 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5249 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5193 | `mocha src/**/*Tests.js --harmony` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5143 | `mocha test` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5138 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5081 | `gulp lint && mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5047 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4899 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4889 | `gulp build; mocha;` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4846 | `mocha --recursive` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4839 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4812 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4807 | `mocha test` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4787 | `./node_modules/.bin/mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4769 | `mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4763 | `nyc mocha --exit` | 
| [teambit/bit](https://github.com/teambit/bit) | 4753 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4725 | `mocha --reporter spec -t 8000` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4711 | `npm run lint && npm run mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4657 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4621 | `nyc mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4567 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4506 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4471 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4470 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4433 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4427 | `mocha -R spec src` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4353 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4329 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4295 | `mocha --timeout=15000 tests/*.test.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4256 | `node_modules/.bin/mocha test/tests.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4218 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4204 | `mocha -R spec ./test --recursive` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4195 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4171 | `mocha --check-leaks --reporter spec --bail` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4167 | `npm run lint ; mocha && mocha test/individual` | 
| [muicss/mui](https://github.com/muicss/mui) | 4099 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4088 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4053 | `mocha --require should --reporter spec` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4048 | `NODE_ENV=test mocha --exit` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4029 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3956 | `nyc mocha "test/**/*.test.js"` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3917 | `export TESTING=true; mocha --reporter list` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3673 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3646 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3628 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3612 | `node_modules/.bin/mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3593 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3571 | `mocha --reporter spec --timeout 3000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3553 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3518 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3480 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3479 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3453 | `mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3449 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3404 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3390 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3354 | `eslint . && mocha -t 5000` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3294 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3289 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3276 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3253 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3252 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3251 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3190 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3171 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3153 | `mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3151 | `mocha -R landing test/index --exit` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3151 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3139 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3122 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3112 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3080 | `mocha && tsc -p ./test/types` | 
| [tensorspace-team/tensorspace](https://github.com/tensorspace-team/tensorspace) | 3063 | `mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3046 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3033 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3122 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3080 | `mocha && tsc -p ./test/types` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3046 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3033 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3029 | `eslint . && nyc mocha --recursive` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3010 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 3009 | `mocha --require should --reporter spec` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2972 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2954 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2945 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2931 | `mocha test.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2927 | `mocha` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2914 | `node_modules/.bin/mocha --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2908 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2906 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2898 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2896 | `mocha test-node` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3173 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3171 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3153 | `mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3151 | `mocha -R landing test/index --exit` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3151 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3139 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3137 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3122 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3112 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3080 | `mocha && tsc -p ./test/types` | 
| [tensorspace-team/tensorspace](https://github.com/tensorspace-team/tensorspace) | 3063 | `mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3046 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3033 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3029 | `eslint . && nyc mocha --recursive` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3010 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 3009 | `mocha --require should --reporter spec` | 
| [github-tools/github](https://github.com/github-tools/github) | 2863 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2862 | `mocha -R spec spec spec/reporters` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2832 | `istanbul cover _mocha` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2808 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [css/csso](https://github.com/css/csso) | 2788 | `mocha --reporter dot` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2778 | `mocha --require should --reporter spec` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2769 | `npm run build && cd test && mocha . --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2750 | `xo && mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2745 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2739 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [tj/should.js](https://github.com/tj/should.js) | 2728 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2727 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2718 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2679 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2675 | `mocha --recursive --watch` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2808 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [css/csso](https://github.com/css/csso) | 2788 | `mocha --reporter dot` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2778 | `mocha --require should --reporter spec` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2769 | `npm run build && cd test && mocha . --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2750 | `xo && mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2745 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2739 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [tj/should.js](https://github.com/tj/should.js) | 2728 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2727 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2718 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2679 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2675 | `mocha --recursive --watch` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2674 | `mocha --timeout 100000` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2674 | `nyc mocha --timeout=10000` | 
| [retejs/rete](https://github.com/retejs/rete) | 2673 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2669 | `mocha "./test/**/*-test.js"` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2651 | `nyc mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2167 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2148 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2140 | `npm run lint && npm run mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2139 | `mocha && eslint *.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2132 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2132 | `mocha` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2121 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2095 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2087 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2076 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [share/sharedb](https://github.com/share/sharedb) | 2070 | `./node_modules/.bin/mocha && npm run jshint` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2198 | `standard && mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2196 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2173 | `cross-env BABEL_ENV=test mocha` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2148 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2140 | `npm run lint && npm run mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2140 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2140 | `mocha test/runner.js --reporter spec` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2139 | `mocha && eslint *.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2132 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2132 | `mocha` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2121 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2108 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2095 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2087 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2076 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [share/sharedb](https://github.com/share/sharedb) | 2070 | `./node_modules/.bin/mocha && npm run jshint` | 
| [pahen/madge](https://github.com/pahen/madge) | 2140 | `npm run lint && npm run mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2140 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2139 | `mocha && eslint *.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2132 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2132 | `mocha` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2121 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2108 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2095 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2087 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2076 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [share/sharedb](https://github.com/share/sharedb) | 2070 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2033 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2027 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2020 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2006 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2004 | `mocha --compilers js:babel-register` | 
| [kach/nearley](https://github.com/kach/nearley) | 2004 | `mocha test/*.test.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2002 | `npm run lint && mocha -R dot && npm run cover` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1997 | `mocha --reporter spec --timeout 5000` | 
| [slate/slate](https://github.com/slate/slate) | 1996 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1991 | `mocha --require=test/test_helper.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1986 | `npm run mocha && npm run karma` | 
| [then/promise](https://github.com/then/promise) | 1972 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1964 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1963 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1952 | `mocha --bail --reporter spec --check-leaks test/` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1949 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1938 | `mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1937 | `mocha && npm run lint` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1929 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1926 | `mocha tests --require @babel/register` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1900 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1877 | `mocha tests.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1877 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1869 | `mocha test` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1868 | `mocha test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1863 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1857 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1843 | `mocha test -u bdd -R spec` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1821 | `mocha test` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1819 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1819 | `npm run lint && npm run mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1818 | `mocha ./test/basic.js -t 5000` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1812 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1792 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1764 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1737 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1736 | `mocha test/setup.js test/spec/*.js` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1732 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1731 | `npm run lint && mocha && npm run typescript` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1729 | `./node_modules/.bin/mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1726 | `mocha test/**/*_test.js --bail` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1712 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1710 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1699 | `mocha tests.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1690 | `mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1743 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1737 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1736 | `mocha test/setup.js test/spec/*.js` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1732 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1729 | `./node_modules/.bin/mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1726 | `mocha test/**/*_test.js --bail` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1723 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1722 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1719 | `mocha test/*.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1718 | `eslint --cache . && tsc && mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1716 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1713 | `mocha test --timeout 600000` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1712 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1710 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1693 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1692 | `npm run jshint && mocha --recursive` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1690 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1699 | `mocha tests.js` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1693 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1692 | `npm run jshint && mocha --recursive` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1690 | `mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1684 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1680 | `nyc mocha --timeout=20000 test.js` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1672 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1667 | `mocha && size-limit` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1664 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1660 | `TEST=all mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1654 | `mocha spec` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1649 | `standard "./src/*.js" && mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1646 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1643 | `mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1642 | `mocha --expose-gc --slow 300` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1558 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1554 | `nyc mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1550 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1549 | `NODE_ENV=test mocha tests/*.js` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1531 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1528 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1527 | `mocha -u tdd` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1520 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1511 | `mocha ./test/test*.js --reporter spec` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1498 | `mocha --check-leaks --require @babel/register` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1497 | `mocha test/**/*.spec.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1498 | `mocha --check-leaks --require @babel/register` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1498 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1486 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1484 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1476 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive --exit` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1476 | `mocha -R spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1475 | `mocha -R spec ./test/unit/**` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1471 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1471 | `mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1469 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1467 | `mocha tests/test-*` | 
| [noble/bleno](https://github.com/noble/bleno) | 1464 | `mocha -R spec test/*.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1462 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1456 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1455 | `mocha test/tests.js --timeout=10000` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1454 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1451 | `mocha test.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1449 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1449 | `npm run lint && mocha && karma start --single-run` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1511 | `mocha ./test/test*.js --reporter spec` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1498 | `mocha --check-leaks --require @babel/register` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1498 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1497 | `mocha test/**/*.spec.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1486 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1484 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1476 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive --exit` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1476 | `mocha -R spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1475 | `mocha -R spec ./test/unit/**` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1471 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1471 | `mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1469 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1467 | `mocha tests/test-*` | 
| [noble/bleno](https://github.com/noble/bleno) | 1464 | `mocha -R spec test/*.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1462 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1471 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1471 | `mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1469 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1467 | `mocha tests/test-*` | 
| [noble/bleno](https://github.com/noble/bleno) | 1464 | `mocha -R spec test/*.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1462 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1456 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1455 | `mocha test/tests.js --timeout=10000` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1454 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1451 | `mocha test.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1449 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1449 | `npm run lint && mocha && karma start --single-run` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1439 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1429 | `npm run lint && npm run mocha` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1426 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1391 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1382 | `./node_modules/mocha/bin/mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1379 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1376 | `mocha --recursive` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1367 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1366 | `npm run prepublishOnly && mocha test/test.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1363 | `cross-env NODE_ENV=test nyc mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1361 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1360 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1359 | `./node_modules/.bin/mocha test` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1356 | `mocha --recursive test` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1347 | `NODE_PATH=. mocha **/*.spec.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1347 | `NODE_PATH=. mocha **/*.spec.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1342 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1342 | `mocha test --compilers js:babel-core/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1340 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1340 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1336 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1329 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1325 | `mocha --check-leaks --reporter spec --bail test/` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1322 | `mocha` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1319 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1313 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1311 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1309 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1306 | `mocha --compilers js:babel-core/register` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1303 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1302 | `mocha test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1301 | `mocha --timeout 60000 test/` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1298 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1294 | `webpack && npm run lint && npm run mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1291 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1290 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1284 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1279 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1275 | `npm run mocha:istanbul` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1274 | `mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1273 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1272 | `npm run lint && npm run mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1265 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1264 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1257 | `mocha tests` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1257 | `npm run lint && mocha --require @babel/register` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1256 | `mocha tests/` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1261 | `istanbul test _mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1257 | `mocha tests` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1257 | `npm run lint && mocha --require @babel/register` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1256 | `mocha tests/` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1253 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1252 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [router5/router5](https://github.com/router5/router5) | 1245 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1243 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1242 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1241 | `mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1238 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1238 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1229 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 1226 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1226 | `mocha --reporter spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1218 | `node ./node_modules/mocha/bin/mocha tests` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1215 | `mocha test/test.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1206 | `mocha --timeout 20000` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1205 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1204 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [poooi/poi](https://github.com/poooi/poi) | 1176 | `mocha --recursive --harmony --require ./test/babelhook` | 
| [electron/asar](https://github.com/electron/asar) | 1175 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [poooi/poi](https://github.com/poooi/poi) | 1176 | `mocha --recursive --harmony --require ./test/babelhook` | 
| [electron/asar](https://github.com/electron/asar) | 1175 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1164 | `mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1164 | `mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1161 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1160 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1159 | `mocha --recursive -r tests/setup tests` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1158 | `mocha $(find test -name '*.test.js') --exit` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1153 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1151 | `istanbul cover _mocha test/*.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1148 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1146 | `mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1144 | `mocha --reporter spec --bail --check-leaks test/` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1143 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1140 | `npm-run-all test:jest test:server:mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1059 | `mocha test` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1055 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [tomas/needle](https://github.com/tomas/needle) | 1053 | `mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1050 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1039 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1023 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1094 | `mocha --check-leaks -t 20000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1089 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1088 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1086 | `mocha --recursive --bail --reporter spec test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1084 | `mocha --compilers js:babel-register` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1080 | `mocha --reporter spec test --recursive` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1075 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1075 | `eslint src test && mocha --compilers babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1074 | `mocha test/tests.js` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1070 | `npm run convertto:es5 && npm run mocha` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1075 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1075 | `eslint src test && mocha --compilers babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1074 | `mocha test/tests.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1073 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1070 | `npm run convertto:es5 && npm run mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1059 | `mocha test` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1055 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [tomas/needle](https://github.com/tomas/needle) | 1053 | `mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1050 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1046 | `mocha --async-only` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 958 | `mocha --recursive ./test/*_spec.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 954 | `mocha spec/*.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 949 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 948 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 948 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 946 | `./node_modules/.bin/mocha --reporter spec` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 944 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 941 | `mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 941 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 939 | `mocha -t 600000` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 936 | `./node_modules/.bin/mocha -R spec` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 931 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 989 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 987 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 980 | `mocha --reporter spec` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 979 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 978 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 975 | `npm run lint && mocha -R spec` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 974 | `npm run rollup-cjs && mocha test/test.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 972 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 970 | `mocha "client.test" --compilers js:babel-register` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 969 | `mocha --compilers js:babel-register test/*.js` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 967 | `mocha test/*.test.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 967 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 965 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 965 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 964 | `mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 958 | `mocha --recursive ./test/*_spec.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 949 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 948 | `mocha` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 947 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 946 | `./node_modules/.bin/mocha --reporter spec` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 945 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 944 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 941 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 941 | `mocha --timeout 5000` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 939 | `mocha -t 600000` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 936 | `./node_modules/.bin/mocha -R spec` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 933 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 927 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 927 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 925 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 921 | `mocha test --compilers js:babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 920 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 919 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 916 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 913 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 911 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 910 | `mocha -t 5000` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 905 | `standard && standard ./bin/* && mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 894 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 893 | `node_modules/.bin/mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 893 | `npm run lint && npm run mocha:no-functional` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 888 | `mocha test` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 884 | `mocha test/index.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 884 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 882 | `mocha --timeout 200000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 877 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 877 | `node_modules/.bin/mocha test/spec` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 875 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 884 | `mocha test/index.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 884 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 877 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 877 | `node_modules/.bin/mocha test/spec` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 875 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 868 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 865 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 864 | `mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 862 | `eslint test && mocha --compilers js:babel/register` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 860 | `./node_modules/.bin/mocha test/**/*` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 859 | `mocha --reporter list` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 859 | `mocha --reporter spec` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 859 | `mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 868 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 865 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 864 | `mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 862 | `eslint test && mocha --compilers js:babel/register` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 860 | `./node_modules/.bin/mocha test/**/*` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 859 | `mocha --reporter list` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 859 | `mocha --reporter spec` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 859 | `mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 858 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 857 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 856 | `istanbul cover _mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 855 | `mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 850 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 847 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 846 | `npm run lint && mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 845 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 844 | `nyc mocha` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 842 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 841 | `mocha` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 840 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 837 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 836 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 834 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 834 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 833 | `mocha --opts mocha.opts` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 832 | `mocha -r should --exit test/*.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 830 | `mocha --async-only` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 795 | `mocha -R spec tests/` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 795 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 792 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 790 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 790 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 787 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 778 | `_mocha` | 
| [fossasia/labyrinth](https://github.com/fossasia/labyrinth) | 778 | `./node_modules/.bin/mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 778 | `mocha test` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 777 | `mocha --recursive -s 15 test/` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 800 | `mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 795 | `mocha -R spec tests/` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 795 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 793 | `xo && mocha -R spec` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 792 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 790 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 790 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 787 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 795 | `mocha -R spec tests/` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 795 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 793 | `xo && mocha -R spec` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 792 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 790 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 790 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 787 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 780 | `npm run lint && mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 778 | `mocha` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 778 | `_mocha` | 
| [fossasia/labyrinth](https://github.com/fossasia/labyrinth) | 778 | `./node_modules/.bin/mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 778 | `mocha test` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 777 | `mocha --recursive -s 15 test/` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 772 | `mocha --harmony tests/**` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 771 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 770 | `mocha -R spec src/**/*_test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 767 | `mocha --ui tdd --require ./test/__setup` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 767 | `npm run lint && npm run mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 765 | `nyc mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 765 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 