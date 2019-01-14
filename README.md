# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:21 01/14/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44876 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41962 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41905 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30799 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 25709 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25496 | `nyc mocha --timeout=10000 --exit` | 
| [caolan/async](https://github.com/caolan/async) | 25131 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24892 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21264 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20026 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15101 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14851 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14668 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13883 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13574 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12890 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12732 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12721 | `istanbul cover _mocha` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13574 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12981 | `mocha 'test/**/*.spec.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12890 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12732 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12721 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12351 | `mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12349 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12294 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12217 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11420 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11072 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10994 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10829 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10723 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10562 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10401 | `mocha --harmony` | 
| [websockets/ws](https://github.com/websockets/ws) | 10353 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9695 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9687 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9657 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 9466 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9413 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9346 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9268 | `grunt mocha` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8867 | `mocha test/src` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8784 | `mocha --opts mocha.opts` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8060 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8035 | `npm run eslint && npm run mocha` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7991 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7980 | `./node_modules/.bin/mocha test` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7830 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7820 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [dthree/cash](https://github.com/dthree/cash) | 7583 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7583 | `npm run build && istanbul cover _mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7484 | `mocha --compilers js:babel-core/register` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7456 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7429 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7412 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7380 | `mocha --exit --require @babel/register` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7119 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7100 | `mocha $HARMONY_OPTS` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7649 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7583 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7583 | `npm run build && istanbul cover _mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7484 | `mocha --compilers js:babel-core/register` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7456 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7429 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7412 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7380 | `mocha --exit --require @babel/register` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7119 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7100 | `mocha $HARMONY_OPTS` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7002 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6975 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6783 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6750 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6535 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6383 | `npm run test:mocha:src` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6256 | `mocha tests/node.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6233 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6194 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6162 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6162 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6087 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6076 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5933 | `mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5926 | `standard && mocha` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5510 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5462 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5408 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5350 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5320 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5317 | `mocha test` | 
| [teambit/bit](https://github.com/teambit/bit) | 5277 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5228 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5207 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5135 | `mocha --color` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4570 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4539 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4536 | `mocha -R spec src` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4476 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4403 | `mocha --timeout=15000 tests/*.test.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4371 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4340 | `node_modules/.bin/mocha test/tests.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4334 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4313 | `mocha --check-leaks --reporter spec --bail` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4288 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4270 | `NODE_ENV=test mocha --exit` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4371 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4340 | `node_modules/.bin/mocha test/tests.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4334 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4313 | `mocha --check-leaks --reporter spec --bail` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4288 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4255 | `npm run lint ; mocha && mocha test/individual` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4232 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4197 | `mocha -R spec ./test --recursive` | 
| [muicss/mui](https://github.com/muicss/mui) | 4128 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4104 | `mocha --require test/babel-hook test/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4089 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4081 | `mocha --require should --reporter spec` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4026 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4005 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3949 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3904 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3860 | `NODE_ENV=test mocha test/**/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3859 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3821 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3795 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3724 | `mocha test/* --reporter spec` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3740 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3724 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3702 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3696 | `mocha && tsc -p ./test/types` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3684 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3670 | `npm run jshint && npm run mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3655 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3643 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3638 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3626 | `eslint . && mocha -t 5000` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3605 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3587 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3583 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3566 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3558 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3547 | `npm run mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3517 | `nyc mocha && tsc` | 
| [tensorspace-team/tensorspace](https://github.com/tensorspace-team/tensorspace) | 3505 | `mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3487 | `node_modules/.bin/mocha test/lib/` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3487 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3450 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3432 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3419 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3418 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3396 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3385 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3367 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3366 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3330 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3327 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3321 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3319 | `mocha -R landing test/index --exit` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3266 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3239 | `mocha test/*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3212 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3210 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3202 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3189 | `mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3164 | `mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 3150 | `mocha --require should --reporter spec` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3147 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3141 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3112 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3082 | `nyc mocha --recursive` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3070 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2937 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2911 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2907 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [github-tools/github](https://github.com/github-tools/github) | 2899 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2885 | `mocha -R spec spec spec/reporters` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2870 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2859 | `npm run build && cd test && mocha . --reporter dot` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2853 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2843 | `istanbul cover _mocha` | 
| [css/csso](https://github.com/css/csso) | 2809 | `mocha --reporter dot` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2802 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2786 | `mocha --require should --reporter spec` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2780 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2762 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2754 | `xo && mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 2750 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2734 | `mocha "./test/**/*-test.js"` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2853 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2843 | `istanbul cover _mocha` | 
| [css/csso](https://github.com/css/csso) | 2809 | `mocha --reporter dot` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2802 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2786 | `mocha --require should --reporter spec` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2780 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2762 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2754 | `xo && mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 2750 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2744 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2734 | `mocha "./test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2730 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2706 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2699 | `nyc mocha --timeout=10000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2688 | `nyc mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2686 | `mocha --timeout 100000` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2551 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2534 | `export TESTING=true; mocha --reporter list` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2532 | `mocha test --exit && npm run lint` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2530 | `mocha test/src/**/*.unit.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2525 | `nyc --reporter=html --reporter=text mocha` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2515 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2512 | `mocha --reporter=spec test/*-test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2500 | `mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2491 | `mocha && eslint .` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2480 | `mocha test/index.js --reporter dot` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2472 | `TEST=all mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2448 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2446 | `mocha --no-colors --reporter spec` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2440 | `mocha -R spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2440 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2437 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2525 | `nyc --reporter=html --reporter=text mocha` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2515 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2512 | `mocha --reporter=spec test/*-test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2500 | `mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2491 | `mocha && eslint .` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2472 | `TEST=all mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2448 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2446 | `mocha --no-colors --reporter spec` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2440 | `mocha -R spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2440 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2437 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [Qix-/color](https://github.com/Qix-/color) | 2425 | `mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2400 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [noble/noble](https://github.com/noble/noble) | 2394 | `mocha -R spec test/*.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2394 | `nyc --require babel-register npm run _mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2380 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [kach/nearley](https://github.com/kach/nearley) | 2047 | `mocha test/*.test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2042 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2035 | `npm run lint && mocha -R dot && npm run cover` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2017 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2011 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 2006 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2002 | `mocha && npm run lint` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1965 | `mocha --require ./test/common --growl test/expect.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1964 | `mocha test` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1961 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1958 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1946 | `mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 2047 | `mocha test/*.test.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2046 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2042 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2035 | `npm run lint && mocha -R dot && npm run cover` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2019 | `mocha tests --require @babel/register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2017 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2015 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2011 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 2006 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2002 | `mocha && npm run lint` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1998 | `mocha --require=test/test_helper.js` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1973 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1964 | `mocha test` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1961 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1958 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1946 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1941 | `mocha --reporter spec && npm run test-typescript` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1940 | `mocha test/**/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1939 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1935 | `bmocha --reporter spec test/*.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1924 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1917 | `npm run lint && mocha --reporter spec test/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1903 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1894 | `mocha test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1883 | `mocha test -u bdd -R spec` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1878 | `mocha tests.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1871 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1871 | `mocha compiled_tests/` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1859 | `mocha ./test/basic.js -t 5000` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1857 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1838 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1824 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1814 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1806 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1801 | `nyc mocha --timeout=20000 test.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1798 | `mocha --timeout 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1798 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1797 | `npm run lint && npm run mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1789 | `mocha test/setup.js test/spec/*.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1778 | `eslint --cache . && tsc && mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1714 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1709 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1704 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1687 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1685 | `mocha --check-leaks --reporter spec --bail` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1680 | `mocha && size-limit` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1671 | `mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1670 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1663 | `mocha spec` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1654 | `mocha ./test/test*.js --reporter spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1644 | `mocha --expose-gc --slow 300` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1640 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1692 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1687 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1685 | `mocha --check-leaks --reporter spec --bail` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1671 | `mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1670 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1663 | `mocha spec` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1654 | `mocha ./test/test*.js --reporter spec` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1640 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1633 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1632 | `mocha --recursive` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1625 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1622 | `mocha --reporter spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1619 | `mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1616 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1614 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1610 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1610 | `mocha test.js` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1608 | `NODE_ENV=test mocha tests/*.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1607 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1601 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1601 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1571 | `mocha test/unit` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1567 | `nyc mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1565 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1571 | `mocha test/unit` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1567 | `nyc mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1565 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1557 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1547 | `mocha -R spec ./test/unit/**` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1542 | `node_modules/.bin/mocha --recursive` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1542 | `mocha tests/test-*` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1538 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require babel-core/register --recursive --exit` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1538 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1537 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1547 | `mocha -R spec ./test/unit/**` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1542 | `node_modules/.bin/mocha --recursive` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1542 | `mocha tests/test-*` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1538 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require babel-core/register --recursive --exit` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1538 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1537 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1533 | `mocha --check-leaks --require @babel/register` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1528 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1519 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1519 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1505 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1505 | `npm run lint && mocha && karma start --single-run` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1504 | `mocha test/**/*.spec.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1502 | `npm run lint && npm run mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1497 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1495 | `mocha --timeout 10000 ./tests/lib.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1495 | `mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1493 | `mocha -R spec test/*.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1490 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1482 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1463 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [samccone/drool](https://github.com/samccone/drool) | 1459 | `mocha test/tests.js --timeout=10000` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1458 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1455 | `mocha --reporter dot` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1454 | `standard && istanbul cover _mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1453 | `mocha test.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1450 | `mocha --opts test/opts/mocha.opts` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1446 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1444 | `npm run prepublishOnly && mocha test/test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1444 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1440 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1427 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1422 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1421 | `mocha --recursive test` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1420 | `npm run build && mocha -r should` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1413 | `mocha test --compilers js:babel-core/register` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1406 | `istanbul cover _mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1405 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1404 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1402 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1397 | `mocha --recursive test/bin` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1391 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1391 | `mocha --recursive` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1388 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1387 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1384 | `./node_modules/mocha/bin/mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1384 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1371 | `./node_modules/.bin/mocha test` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1370 | `cross-env NODE_ENV=test nyc mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1364 | `mocha --check-leaks --reporter spec --bail test/` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1361 | `NODE_PATH=. mocha **/*.spec.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1349 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1347 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1342 | `webpack && npm run lint && npm run mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1341 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1337 | `npm run mocha:istanbul` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1335 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1327 | `npm run lint && mocha --require @babel/register` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1327 | `lerna run test && mocha` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1324 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1322 | `mocha-phantomjs tests/index.html` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1318 | `mocha test/*.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1316 | `mocha spec/exec.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1315 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1313 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1313 | `mocha --timeout 60000 test/` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1309 | `mocha` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1308 | `mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1306 | `mocha tests/` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1302 | `mocha src/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1295 | `npm run lint && npm run mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1290 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1289 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1289 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1288 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1288 | `istanbul test _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1286 | `mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1283 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1282 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1281 | `mocha --timeout 20000` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [variety/variety](https://github.com/variety/variety) | 1265 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [variety/variety](https://github.com/variety/variety) | 1265 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1259 | `mocha tests` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1257 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1253 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1250 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1244 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [normalize/mz](https://github.com/normalize/mz) | 1244 | `mocha --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1240 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1234 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1234 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1229 | `mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1225 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1214 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1211 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1209 | `mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1206 | `mocha test` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1189 | `mocha --recursive -r tests/setup tests` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1182 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1176 | `mocha` | 
| [x-tag/core](https://github.com/x-tag/core) | 1175 | `NODE_ENV=test mocha --exit` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1173 | `xo && mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1171 | `mocha --reporter spec --bail --check-leaks test/` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1169 | `mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1144 | `mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1141 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1141 | `webpack && mocha test/unit` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1129 | `mocha test/*` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1127 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1124 | `mocha test` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1122 | `mocha --reporter spec test --recursive` | 
| [electron/spectron](https://github.com/electron/spectron) | 1119 | `mocha && standard` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1116 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1115 | `npm run convertto:es5 && npm run mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1114 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1113 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1101 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1100 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1127 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1124 | `mocha test` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1122 | `mocha --reporter spec test --recursive` | 
| [electron/spectron](https://github.com/electron/spectron) | 1119 | `mocha && standard` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1117 | `standard && mocha -b` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1116 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1116 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1115 | `npm run convertto:es5 && npm run mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1114 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1113 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1113 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1101 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1099 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1097 | `mocha --recursive --bail --reporter spec test` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1096 | `mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1096 | `eslint src test && mocha --compilers babel-register` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1096 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1095 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1089 | `mocha --compilers js:babel-register` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1084 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1083 | `mocha test/tests.js` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1059 | `mocha --async-only` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1048 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1036 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1030 | `mocha --recursive test/unit/` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1030 | `mocha --reporter spec --timeout 3000` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1019 | `mocha --reporter spec --bail --check-leaks test/` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1050 | `mocha $(find test -name '*.test.js')` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1048 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [odota/core](https://github.com/odota/core) | 1045 | `NODE_ENV=test mocha --exit` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1044 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1036 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1030 | `mocha --recursive test/unit/` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1030 | `mocha --reporter spec --timeout 3000` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1019 | `mocha --reporter spec --bail --check-leaks test/` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1017 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1015 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1014 | `npm run lint && npm run mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1013 | `mocha test/*.test.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1008 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1006 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1004 | `mocha -R list` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 997 | `mocha --recursive ./test/*_spec.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 993 | `npm run lint && mocha -R spec` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 993 | `mocha spec/*.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 992 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 991 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 990 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 989 | `mocha --compilers js:babel-register test/*.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 988 | `./node_modules/.bin/mocha -R spec` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 986 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 982 | `mocha --reporter spec` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 981 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 979 | `mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 977 | `npm run rollup-cjs && mocha test/test.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 976 | `mocha "client.test" --compilers js:babel-register` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 974 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 970 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 968 | `mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 967 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 963 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 962 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 960 | `./node_modules/.bin/mocha --reporter spec` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 959 | `mocha tests` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 959 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 959 | `mocha tests` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 958 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 957 | `mocha -t 600000` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 957 | `mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 952 | `mocha` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 950 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 945 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 943 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 942 | `mocha test --compilers js:babel-register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 940 | `nyc mocha specs` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 912 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 904 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 903 | `mocha test/index.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 896 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 894 | `mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 883 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 876 | `npm run build && istanbul test _mocha test/test.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [nimiq-network/core](https://github.com/nimiq-network/core) | 896 | `NODE_ENV=test mocha --exit` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 896 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 894 | `mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 883 | `node_modules/.bin/mocha test/spec` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 883 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 880 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 877 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 876 | `npm run build && istanbul test _mocha test/test.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 875 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 875 | `mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 883 | `node_modules/.bin/mocha test/spec` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 883 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 880 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 877 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 876 | `npm run build && istanbul test _mocha test/test.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 875 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 874 | `mocha -r should --exit test/*.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 871 | `mocha --reporter list` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 871 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 870 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 862 | `istanbul cover _mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 862 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 860 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 860 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 859 | `mocha --reporter spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 858 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 857 | `mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 856 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 852 | `nyc mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 852 | `mocha --check-leaks -t 20000` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 849 | `npm run lint && mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 847 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 846 | `mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 845 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 845 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 843 | `mocha --harmony tests/**` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 842 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 826 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 826 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 825 | `nyc mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 818 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 817 | `npm run mocha-test test/integration` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 815 | `cake build && mocha ./test/mocha/*.coffee` | 
| [edsu/anon](https://github.com/edsu/anon) | 814 | `mocha --colors --reporter spec test.js` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 814 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 811 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 809 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 808 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 799 | `mocha test` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 799 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 795 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 793 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 791 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 791 | `mocha index.test.js` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 788 | `mocha` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 787 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 786 | `npm run lint && npm run mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 784 | `nyc mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 784 | `mocha` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 782 | `mocha` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 791 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 791 | `mocha index.test.js` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 788 | `mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 786 | `npm run lint && npm run mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 785 | `mocha test/mocha.js` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 784 | `nyc mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 784 | `mocha` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 782 | `mocha` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 780 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 775 | `mocha tests --timeout 10000` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 793 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 792 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 791 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 791 | `mocha index.test.js` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 788 | `mocha` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 787 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 786 | `npm run lint && npm run mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 785 | `mocha test/mocha.js` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 784 | `nyc mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 784 | `mocha` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 782 | `mocha` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 780 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 779 | `mocha --recursive -s 15 test/` | 