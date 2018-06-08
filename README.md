# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:01 06/08/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 42006 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40684 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38662 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 22920 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22380 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19020 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16316 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15920 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16316 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15920 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14421 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14148 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13494 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12753 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12499 | `mocha 'test/**/*.spec.js'` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 12402 | `mocha --reporter spec` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12336 | `./node_modules/.bin/mocha test/` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12153 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12099 | `mocha --reporter spec test/*-test.js` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11904 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11158 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11050 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10593 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10453 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10005 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9732 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9723 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9706 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9686 | `set NODE_ENV=test && mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9401 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7336 | `npm run build && istanbul cover _mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7076 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7067 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6893 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6830 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6779 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6722 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6622 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6170 | `npm run jshint && mocha test/` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 6157 | `mocha test node-test --recursive` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6135 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6111 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7076 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7067 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 6895 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6893 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6881 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6830 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6779 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6722 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6622 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6309 | `npm run lint -s && npm run mocha -s` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6170 | `npm run jshint && mocha test/` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 6157 | `mocha test node-test --recursive` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 6150 | `npm run build-cli && mocha` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6135 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6111 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6622 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6309 | `npm run lint -s && npm run mocha -s` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6170 | `npm run jshint && mocha test/` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 6157 | `mocha test node-test --recursive` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 6150 | `npm run build-cli && mocha` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6135 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6111 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6029 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5935 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5887 | `mocha --exit --require babel-core/register` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5848 | `mocha test/test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5846 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5730 | `mocha tests/node.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5713 | `mocha; jshint *.js lib` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5628 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5602 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5530 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5405 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5389 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5362 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5280 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5276 | `mocha --timeout 10000 && npm run lint` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5162 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5153 | `mocha --color` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5105 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4967 | `standard && mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4948 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4934 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4896 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4818 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4715 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4696 | `mocha -R spec 'tests/app'` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4692 | `mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4670 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4658 | `gulp build; mocha;` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4631 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4601 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4571 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4555 | `mocha ./test/runner.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4508 | `mocha test` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4500 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4416 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4363 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4335 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4321 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4230 | `NODE_ENV=test mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4219 | `mocha -R spec ./test --recursive` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4217 | `mocha --recursive && make test` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4188 | `nyc mocha --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4114 | `npm run lint && npm run mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4102 | `nyc mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3969 | `mocha --require test/babel-hook test/*.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 3968 | `mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3950 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3920 | `mocha -R spec ./test` | 
| [tj/ejs](https://github.com/tj/ejs) | 3903 | `mocha --require should --reporter spec` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3882 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3880 | `npm run lint && npm run mocha` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3875 | `export TESTING=true; mocha --reporter list` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3868 | `npm run lint ; mocha && mocha test/individual` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3811 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [erming/shout](https://github.com/erming/shout) | 3803 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3794 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3769 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3696 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3662 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3619 | `standard && mocha --timeout 60000 test/test.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3617 | `mocha --check-leaks --reporter spec --bail` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3609 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [primus/primus](https://github.com/primus/primus) | 3592 | `npm run build && mocha test/*.test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3500 | `mocha --reporter spec --timeout 3000` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3493 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3484 | `node_modules/.bin/mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3493 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3484 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3466 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3462 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 3440 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3437 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3430 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3423 | `mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3409 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3406 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3366 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3365 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3343 | `node_modules/.bin/mocha test/tests.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3336 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3286 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3210 | `NODE_ENV=test mocha test/**/*.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3121 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3115 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3114 | `./node_modules/.bin/mocha test/test.*.js` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 3094 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3092 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3089 | `nyc mocha && tsc` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3078 | `mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3050 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3045 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3017 | `NODE_ENV=test mocha --exit` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3008 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3017 | `NODE_ENV=test mocha --exit` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3008 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2990 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2977 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2955 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2953 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2946 | `mocha test/index.js && npm run demo` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2906 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2902 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2883 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2875 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2866 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2846 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2841 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2841 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2837 | `mocha -R spec --recursive src/test` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2774 | `mocha --require should --reporter spec` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2772 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2769 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2768 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2761 | `mocha --opts mocha.opts` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2754 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2749 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2747 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2733 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2722 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2704 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2698 | `npm run mocha && npm run lint` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2681 | `xo && mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2675 | `mocha --require babel-register --recursive spec` | 
| [css/csso](https://github.com/css/csso) | 2671 | `mocha --reporter dot` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2666 | `mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2660 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2603 | `mocha-phantomjs ./test/index.html` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2594 | `node_modules/.bin/mocha --reporter spec` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2590 | `mocha --recursive --watch` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2559 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2557 | `mocha -R landing test/index` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2546 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2545 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2538 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2510 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2494 | `npm run build && cd test && mocha . --reporter dot` | 
| [mde/ejs](https://github.com/mde/ejs) | 2490 | `mocha --require should --reporter spec` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2459 | `mocha --reporter=spec test/*-test.js` | 
| [json5/json5](https://github.com/json5/json5) | 2459 | `nyc --reporter=html --reporter=text mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2449 | `nyc mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2494 | `npm run build && cd test && mocha . --reporter dot` | 
| [mde/ejs](https://github.com/mde/ejs) | 2490 | `mocha --require should --reporter spec` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2459 | `mocha --reporter=spec test/*-test.js` | 
| [json5/json5](https://github.com/json5/json5) | 2459 | `nyc --reporter=html --reporter=text mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2449 | `nyc mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2424 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2419 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2417 | `mocha test` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2415 | `mocha test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2411 | `mocha "test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2407 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2388 | `mocha test/src/**/*.unit.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2374 | `mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2301 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2295 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2288 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2258 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2256 | `mocha -R spec` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2244 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2233 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2224 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [gajus/swing](https://github.com/gajus/swing) | 2196 | `mocha --compilers js:babel-register` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2192 | `eslint . && mocha -t 5000` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2181 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2180 | `mocha test && npm run lint` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2041 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2028 | `mocha test/index.js --reporter dot` | 
| [Qix-/color](https://github.com/Qix-/color) | 2022 | `mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2016 | `standard && mocha` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2010 | `mocha test/ --no-timeouts` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1980 | `mocha test/runner.js --reporter spec` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1969 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [teambit/bit](https://github.com/teambit/bit) | 1964 | `mocha --require babel-core/register './specs/**/*.spec.js'` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1959 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1949 | `mocha --require=test/test_helper.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2089 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2084 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2070 | `mocha --compilers js:babel-register` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2041 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2028 | `mocha test/index.js --reporter dot` | 
| [Qix-/color](https://github.com/Qix-/color) | 2022 | `mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2016 | `standard && mocha` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2010 | `mocha test/ --no-timeouts` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1980 | `mocha test/runner.js --reporter spec` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1969 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1967 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 1964 | `mocha --require babel-core/register './specs/**/*.spec.js'` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1959 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1949 | `mocha --require=test/test_helper.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1924 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1921 | `mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1918 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1916 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1913 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1909 | `mocha --compilers js:babel-core/register __tests__` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1908 | `mocha --reporter spec --timeout 5000` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1906 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1899 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1885 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1881 | `mocha --require ./test/common --growl test/expect.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1880 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1877 | `nyc npm run _mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1871 | `mocha && eslint *.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1867 | `mocha tests.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1859 | `./node_modules/.bin/mocha && npm run jshint` | 
| [then/promise](https://github.com/then/promise) | 1857 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1850 | `npm run lint && mocha -R dot && npm run cover` | 
| [kach/nearley](https://github.com/kach/nearley) | 1839 | `mocha test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1829 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1820 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1815 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1754 | `mocha test` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1752 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [pahen/madge](https://github.com/pahen/madge) | 1741 | `npm run lint && npm run mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1727 | `mocha && npm run lint` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1719 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1719 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1711 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1711 | `npm run lint && npm run mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1708 | `mocha --reporter spec --grep .` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1705 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1703 | `mocha tests --compilers js:babel-core/register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1703 | `npm run lint && mocha test/unit --recursive && mocha test/runner --recursive` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1701 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1692 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1690 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1618 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1612 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1611 | `mocha && size-limit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1592 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1587 | `mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1548 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1542 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1526 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1518 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1552 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1526 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1517 | `mocha --reporter spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1513 | `mocha compiled_tests/` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1509 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1505 | `npm run test:lint && npm run test:mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1490 | `standard "./src/*.js" && mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1482 | `node_modules/.bin/mocha --recursive` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1601 | `npm run lint && npm run mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1599 | `mocha test/* --reporter spec` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1592 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1587 | `mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1552 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1548 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1542 | `./node_modules/mocha/bin/mocha -R spec` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1439 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1437 | `mocha test.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1431 | `mocha --recursive` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1384 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1369 | `mocha --timeout 10000 ./tests/lib.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1364 | `mocha test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1482 | `node_modules/.bin/mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1481 | `mocha -u tdd` | 
| [zeit/ms](https://github.com/zeit/ms) | 1478 | `mocha tests.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1475 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1473 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1473 | `mocha test/setup.js test/spec/*.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1472 | `mocha -R spec` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1471 | `mocha test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1470 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1468 | `nyc mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1461 | `mocha` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1459 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1457 | `mocha test/**/*.spec.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1452 | `mocha --check-leaks --reporter spec --bail` | 
| [samccone/drool](https://github.com/samccone/drool) | 1449 | `mocha test/tests.js --timeout=10000` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1444 | `mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1396 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1384 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1369 | `./node_modules/mocha/bin/mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1369 | `mocha --timeout 10000 ./tests/lib.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1364 | `mocha test` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1363 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1359 | `mocha -R spec test/*.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1358 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1350 | `cross-env NODE_ENV=test nyc mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [electron/asar](https://github.com/electron/asar) | 1015 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1014 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1005 | `mocha $(find test -name '*.test.js')` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1003 | `npm run lint && mocha --require @babel/register` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1001 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 993 | `mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 990 | `mocha test` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 988 | `mocha --recursive test/unit/` | 
| [electron/spectron](https://github.com/electron/spectron) | 984 | `mocha && standard` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 977 | `mocha --async-only` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 975 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 971 | `mocha -R list` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 967 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 963 | `npm run mocha:istanbul` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 962 | `mocha --timeout 20000` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 961 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 961 | `mocha --reporter spec` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 952 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 951 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 947 | `mocha --timeout 5000` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 941 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 929 | `npm run convertto:es5 && npm run mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 927 | `mocha "client.test" --compilers js:babel-register` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 927 | `npm-run-all test:jest test:server:mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 927 | `mocha "client.test" --compilers js:babel-register` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 927 | `npm-run-all test:jest test:server:mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 917 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 912 | `mocha --compilers js:babel-register test/*.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 912 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 911 | `mocha ./test/index.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 910 | `mocha --reporter spec --bail --check-leaks test/` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 904 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 902 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 901 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 898 | `mocha -R spec` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 861 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 860 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 860 | `npm run lint && npm run mocha:no-functional` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 859 | `mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 853 | `node_modules/.bin/mocha test/spec` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 839 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 839 | `mocha spec/*.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 836 | `mocha -t 5000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 831 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 828 | `mocha test --compilers js:babel-register` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 827 | `mocha test --compilers js:babel-core/register` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 826 | `./node_modules/.bin/mocha -R spec` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 824 | `istanbul cover -- _mocha --reporter spec` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 881 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 873 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 871 | `node_modules/.bin/mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 869 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 866 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 865 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 865 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 864 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 863 | `mocha -t 600000` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 862 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 861 | `mocha --timeout 200000` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 815 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 814 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 813 | `npm run lint && mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 800 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 800 | `./node_modules/.bin/mocha --reporter spec` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 797 | `mocha --timeout 30000 --recursive ./tests` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 796 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 794 | `mocha -u tdd` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 793 | `mocha test` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 788 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 786 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 836 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 836 | `mocha -t 5000` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 834 | `mocha --check-leaks -t 20000` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 833 | `mocha --reporter spec` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 831 | `nyc mocha specs` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 831 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 830 | `istanbul cover _mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 830 | `standard && standard ./bin/* && mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 829 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 828 | `mocha test --compilers js:babel-register` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 827 | `mocha test --compilers js:babel-core/register` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 826 | `./node_modules/.bin/mocha -R spec` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 824 | `istanbul cover -- _mocha --reporter spec` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 822 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 821 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 821 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 732 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 729 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 729 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 725 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 725 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 722 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 721 | `mocha tests/*.mocha.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 720 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 714 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [typicode/katon](https://github.com/typicode/katon) | 711 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 708 | `mocha -r should --reporter spec test/*.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 708 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 707 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 786 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 782 | `mocha --colors --reporter spec test.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 782 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 779 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 775 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 773 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 771 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 770 | `mocha test/index.js` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 770 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 769 | `xo && mocha -R spec` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 767 | `nyc --check-coverage mocha test/*.test.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 782 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 779 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 775 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 773 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 771 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 770 | `mocha test/index.js` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 770 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 769 | `xo && mocha -R spec` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 767 | `nyc --check-coverage mocha test/*.test.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 766 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 766 | `mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 765 | `npm run mocha-test test/integration` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 743 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [developit/decko](https://github.com/developit/decko) | 742 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 736 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 733 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 733 | `mocha test` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 733 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 732 | `mocha test` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 732 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 731 | `mocha --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 729 | `mocha --no-timeouts` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 729 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 725 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 724 | `mocha test.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 722 | `mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 721 | `mocha tests/*.mocha.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 720 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 720 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 719 | `npm run lint && npm run mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 718 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 715 | `npm run bundle && mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 710 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 708 | `mocha -r should --reporter spec test/*.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 708 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 707 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 706 | `mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 704 | `mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 704 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 704 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 702 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 698 | `mocha ./test/index.js` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 697 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 696 | `babel-node node_modules/.bin/_mocha -- test` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 694 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 693 | `./node_modules/.bin/mocha -t 60000` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 693 | `mocha --reporter spec build/test/index.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 691 | `./bin/selenium-standalone install && mocha` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 687 | `mocha --reporter spec` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 687 | `npm run-script jshint && npm run-script mocha` | 
| [scality/S3](https://github.com/scality/S3) | 693 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 693 | `./node_modules/.bin/mocha -t 60000` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 693 | `mocha --reporter spec build/test/index.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 691 | `./bin/selenium-standalone install && mocha` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 690 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 687 | `mocha --reporter spec` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 687 | `npm run-script jshint && npm run-script mocha` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 681 | `mocha ./test/test.js --timeout 1000000` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 681 | `mocha` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 679 | `npm run lint && mocha test` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 664 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 661 | `mocha --compilers js:babel-core/register` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 661 | `mocha` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 660 | `npm run test-mocha && npm run test-karma` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 660 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 656 | `jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 655 | `./node_modules/.bin/mocha test/integration` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 654 | `mocha -R spec` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 654 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 652 | `mocha` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 650 | `mocha` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 649 | `mocha --bail test/` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 648 | `mocha --recursive --compilers js:babel-core/register` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 648 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 648 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 645 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 644 | `./node_modules/.bin/mocha` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 644 | `mocha --compilers js:babel-register` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 643 | `./node_modules/.bin/mocha --bail` | 
| [shime/livedown](https://github.com/shime/livedown) | 638 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 635 | `jenkins-mocha ./tests/*.js` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 654 | `mocha` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 652 | `mocha` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 650 | `mocha` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 649 | `mocha --bail test/` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 648 | `mocha --recursive --compilers js:babel-core/register` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 648 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 648 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 645 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 644 | `./node_modules/.bin/mocha` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 644 | `mocha --compilers js:babel-register` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 644 | `mocha --compilers js:babel-register src/**/*.spec.js src/*.spec.js` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 643 | `./node_modules/.bin/mocha --bail` | 
| [shime/livedown](https://github.com/shime/livedown) | 638 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 635 | `jenkins-mocha ./tests/*.js` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 635 | `mocha --reporter spec --bail --check-leaks test/` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 631 | `mocha --reporter spec` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 630 | `mocha --reporter spec` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 597 | `mocha` | 
| [w0rm/gulp-svgstore](https://github.com/w0rm/gulp-svgstore) | 597 | `gulp build && mocha test.js` | 
| [jfromaniello/passport.socketio](https://github.com/jfromaniello/passport.socketio) | 596 | `mocha` | 
| [echenley/react-news](https://github.com/echenley/react-news) | 596 | `./node_modules/.bin/karma start ./test/karma.conf.js --reporters mocha,coverage` | 
| [IjzerenHein/autolayout.js](https://github.com/IjzerenHein/autolayout.js) | 594 | `mocha` | 
| [shinnn/gulp-gh-pages](https://github.com/shinnn/gulp-gh-pages) | 594 | `mocha test.js --timeout 50000 --full-trace` | 
| [postcss/gulp-postcss](https://github.com/postcss/gulp-postcss) | 593 | `nyc mocha test.js` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 593 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [robrich/gulp-if](https://github.com/robrich/gulp-if) | 592 | `mocha && jshint .` | 
| [gridcontrol/gridcontrol](https://github.com/gridcontrol/gridcontrol) | 588 | `NODE_ENV='test' DEBUG='gc:*' ./node_modules/.bin/mocha test/*.mocha.js -b` | 
| [aaronshaf/react-toggle](https://github.com/aaronshaf/react-toggle) | 588 | `nyc mocha --require babel-register --require spec/setup.js spec/**/*.spec.js` | 
| [matthewmueller/graph.ql](https://github.com/matthewmueller/graph.ql) | 588 | `./node_modules/.bin/mocha` | 
| [JustClear/blurify](https://github.com/JustClear/blurify) | 587 | `mocha test/index.js` | 
| [putaoshu/jdf](https://github.com/putaoshu/jdf) | 586 | `mocha test/index.js` | 
| [SamyPesse/gitkit-js](https://github.com/SamyPesse/gitkit-js) | 586 | `./node_modules/.bin/mocha ./testing/setup.js ./lib/**/*/__tests__/*.js --bail --reporter=list` | 
| [GitbookIO/gitbook-cli](https://github.com/GitbookIO/gitbook-cli) | 344 | `mocha --reporter spec --recursive --bail` | 
| [forward/sql-parser](https://github.com/forward/sql-parser) | 344 | `./node_modules/.bin/cake build && ./node_modules/.bin/mocha --require should --compilers coffee:coffee-script/register` | 
| [goatslacker/iso](https://github.com/goatslacker/iso) | 340 | `babel-node node_modules/.bin/_mocha -u exports test/*-test.js` | 
| [banderson/generator-flux-react](https://github.com/banderson/generator-flux-react) | 339 | `mocha` | 
| [UnsignedInt8/LightSword](https://github.com/UnsignedInt8/LightSword) | 338 | `mocha --timeout 60000 test/**/*.js test/*.js build/test/*.js` | 
| [Justin-lu/react-redux-antd](https://github.com/Justin-lu/react-redux-antd) | 337 | `mocha tools/testSetup.js "src/**/*.spec.js"` | 
| [derek-watson/jsUri](https://github.com/derek-watson/jsUri) | 333 | `./node_modules/.bin/mocha` | 
| [istanbuljs/babel-plugin-istanbul](https://github.com/istanbuljs/babel-plugin-istanbul) | 333 | `cross-env NODE_ENV=test nyc --reporter=lcov --reporter=text mocha test/*.js` | 
| [danielstjules/pjs](https://github.com/danielstjules/pjs) | 333 | `mocha --recursive -R spec spec` | 
| [vesparny/marky](https://github.com/vesparny/marky) | 331 | `npm run rollup-cjs && mocha test/test.js` | 
| [phodal/sherlock](https://github.com/phodal/sherlock) | 603 | `mocha --reporter spec` | 
| [Ivshti/linvodb3](https://github.com/Ivshti/linvodb3) | 602 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [rofrischmann/react-look](https://github.com/rofrischmann/react-look) | 601 | `npm run lint && mocha --recursive --compilers js:babel/register` | 
| [danawoodman/react-fontawesome](https://github.com/danawoodman/react-fontawesome) | 601 | `mocha` | 
| [tj/node-blocked](https://github.com/tj/node-blocked) | 598 | `./node_modules/mocha/bin/mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 597 | `mocha` | 
| [w0rm/gulp-svgstore](https://github.com/w0rm/gulp-svgstore) | 597 | `gulp build && mocha test.js` | 
| [joaonuno/tree-model-js](https://github.com/joaonuno/tree-model-js) | 597 | `istanbul cover _mocha` | 
| [jfromaniello/passport.socketio](https://github.com/jfromaniello/passport.socketio) | 596 | `mocha` | 
| [ck86/main-bower-files](https://github.com/ck86/main-bower-files) | 596 | `mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 596 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require babel-register` | 
| [echenley/react-news](https://github.com/echenley/react-news) | 596 | `./node_modules/.bin/karma start ./test/karma.conf.js --reporters mocha,coverage` | 