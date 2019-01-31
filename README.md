# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:28 01/31/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45063 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42155 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42053 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30868 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25618 | `nyc mocha --timeout=10000 --exit` | 
| [caolan/async](https://github.com/caolan/async) | 25192 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25114 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21409 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20115 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18488 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18030 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17873 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17352 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15257 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14970 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14705 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13958 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13675 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13152 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13014 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12786 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12783 | `istanbul cover _mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12476 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12441 | `mocha --require @babel/register --reporter dot` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12356 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12292 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11538 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11171 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11164 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10899 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9769 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9766 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9708 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9533 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9443 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9407 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9324 | `grunt mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8918 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8913 | `mocha test/src` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8746 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8688 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8594 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8573 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8457 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8330 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8264 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8262 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7599 | `npm run build && istanbul cover _mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7497 | `mocha --exit --require @babel/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7493 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7489 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7450 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7183 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7171 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7037 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6889 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6873 | `mocha test/test.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7599 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7584 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [almende/vis](https://github.com/almende/vis) | 7545 | `mocha --compilers js:babel-core/register` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7497 | `mocha --exit --require @babel/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7493 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7489 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7450 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7183 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7171 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7112 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7037 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6889 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6873 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6577 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6398 | `npm run test:mocha:src` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6281 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6277 | `mocha tests/node.js` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6248 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6218 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6211 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6134 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6101 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6068 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6007 | `standard && mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5300 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5208 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5136 | `mocha --color` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5074 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5056 | `mocha --recursive` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4953 | `nyc mocha --exit` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4938 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4894 | `./node_modules/.bin/mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4888 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4859 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4849 | `mocha test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4840 | `nyc mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4838 | `mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5300 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5208 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5136 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5124 | `gulp lint && mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5074 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5056 | `mocha --recursive` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4959 | `gulp build; mocha;` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4953 | `nyc mocha --exit` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4938 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4917 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4897 | `npm run lint && npm run mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4894 | `./node_modules/.bin/mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4888 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4859 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4849 | `mocha test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4840 | `nyc mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4838 | `mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4750 | `mocha --reporter spec -t 8000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4648 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4589 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4584 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4554 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4485 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4444 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4384 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4380 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4368 | `node_modules/.bin/mocha test/tests.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4362 | `mocha --check-leaks --reporter spec --bail` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4352 | `NODE_ENV=test mocha --exit` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4319 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4279 | `npm run lint ; mocha && mocha test/individual` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4235 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4194 | `mocha -R spec ./test --recursive` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4127 | `mocha --require test/babel-hook test/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4092 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3989 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3930 | `export TESTING=true; mocha --reporter list` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3942 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3930 | `export TESTING=true; mocha --reporter list` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3903 | `NODE_ENV=test mocha test/**/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3858 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3831 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3819 | `npm run build && mocha test/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3793 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3781 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3750 | `npm run mocha` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3750 | `mocha && tsc -p ./test/types` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3735 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3724 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3722 | `eslint . && mocha -t 5000` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 3713 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3670 | `npm run jshint && npm run mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3666 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3665 | `node_modules/.bin/mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3601 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3593 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3582 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3545 | `nyc mocha && tsc` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3490 | `node_modules/.bin/mocha test/lib/` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3473 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3469 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3448 | `mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3439 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3435 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3426 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3412 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3392 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3385 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3370 | `mocha -R landing test/index --exit` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3370 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [css/csso](https://github.com/css/csso) | 2822 | `mocha --reporter dot` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2787 | `mocha --require should --reporter spec` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2767 | `mocha "./test/**/*-test.js"` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2764 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2764 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2757 | `mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2714 | `nyc mocha --timeout=10000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2714 | `mocha --recursive --watch` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2710 | `nyc mocha` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2677 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2673 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2647 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2592 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2554 | `mocha test --exit && npm run lint` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2543 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2633 | `mocha-phantomjs ./test/index.html` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2601 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2556 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 2550 | `./node_modules/mocha/bin/mocha --require babel-core/register test/*` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2548 | `mocha test` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2533 | `mocha && eslint .` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2530 | `export TESTING=true; mocha --reporter list` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2507 | `mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2452 | `mocha -R spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2450 | `mocha --no-colors --reporter spec` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2438 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [noble/noble](https://github.com/noble/noble) | 2410 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2390 | `npm run build && mocha --require babel-register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2321 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2308 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2287 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2286 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2321 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2308 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2252 | `standard && mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2246 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1638 | `mocha tests/test.js` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1628 | `mocha --reporter spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1619 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1613 | `./node_modules/mocha/bin/mocha -R spec` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1608 | `mocha --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1576 | `nyc mocha` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1562 | `mocha tests/test-*` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1550 | `npm run test:lint && npm run test:mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1543 | `node_modules/.bin/mocha --recursive` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1542 | `mocha --check-leaks --require @babel/register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1525 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1521 | `npm run lint && npm run mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1519 | `npm run lint && mocha && karma start --single-run` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1516 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1513 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [gajus/swing](https://github.com/gajus/swing) | 2311 | `mocha --compilers js:babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2308 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [pahen/madge](https://github.com/pahen/madge) | 2288 | `npm run lint && npm run mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2287 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2286 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2252 | `standard && mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2246 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2242 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2311 | `mocha --compilers js:babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2308 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [pahen/madge](https://github.com/pahen/madge) | 2288 | `npm run lint && npm run mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2287 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2286 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2252 | `standard && mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2246 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2242 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2209 | `mocha && eslint *.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2207 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2191 | `mocha test/runner.js --reporter spec` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2186 | `mocha test/**/*.coffee` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2185 | `mocha --timeout 10000 --bail --exit test/*-test.js test/security/*.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2185 | `mocha --timeout 10000 --bail --exit test/*-test.js test/security/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2185 | `cross-env BABEL_ENV=test mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 2182 | `./node_modules/.bin/mocha && npm run jshint` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2156 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2150 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2146 | `mocha --compilers js:babel-register` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2137 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2133 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2133 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2109 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 2072 | `mocha test/*.test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2055 | `npm run mocha && npm run karma` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2049 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2048 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2046 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2038 | `mocha tests --require @babel/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2030 | `mocha && npm run lint` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2022 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2021 | `mocha --reporter spec --timeout 5000` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2014 | `mocha test` | 
| [then/promise](https://github.com/then/promise) | 2013 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2002 | `mocha --require=test/test_helper.js` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1988 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1965 | `mocha test/**/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1952 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1950 | `bmocha --reporter spec test/*.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1933 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1904 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1896 | `mocha compiled_tests/` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1885 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1879 | `mocha ./test/basic.js -t 5000` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1862 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1858 | `nyc mocha --timeout=20000 test.js` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1896 | `mocha compiled_tests/` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1885 | `mocha` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1880 | `mocha tests.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1879 | `mocha ./test/basic.js -t 5000` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1862 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1858 | `nyc mocha --timeout=20000 test.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1843 | `npm run lint && npm run mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1825 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1820 | `mocha test` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1812 | `npm run lint && npm run mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1811 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1825 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1820 | `mocha test` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1812 | `npm run lint && npm run mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1811 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1806 | `mocha test/setup.js test/spec/*.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1805 | `eslint --cache . && tsc && mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1801 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1798 | `mocha --timeout 5000` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1780 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1768 | `mocha --recursive` | 
| [zeit/ms](https://github.com/zeit/ms) | 1767 | `mocha tests.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1761 | `npm run lint && mocha && npm run typescript` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1758 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1717 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1714 | `mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1713 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1712 | `mocha --check-leaks --reporter spec --bail` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1711 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1708 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1704 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1692 | `npm run jshint && mocha --recursive` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1686 | `mocha && size-limit` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1680 | `mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1676 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1671 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1668 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1664 | `mocha spec` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1494 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1480 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1477 | `mocha --recursive test` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1472 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1470 | `mocha --reporter dot` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1470 | `standard && istanbul cover _mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1469 | `mocha --opts test/opts/mocha.opts` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1468 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1460 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1454 | `mocha test.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1635 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1628 | `mocha --reporter spec` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1626 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1625 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1619 | `mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1613 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1613 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1613 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1610 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1608 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1608 | `mocha --recursive` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1585 | `mocha test/unit` | 
| [electron/spectron](https://github.com/electron/spectron) | 1131 | `mocha && standard` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1129 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1125 | `standard && mocha -b` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1115 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1113 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1112 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1105 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1105 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1098 | `node_modules/.bin/mocha && npm run lint` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1095 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1470 | `mocha --reporter dot` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1469 | `mocha --opts test/opts/mocha.opts` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1468 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1468 | `npm run prepublishOnly && mocha test/test.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1460 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1454 | `mocha test.js` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1450 | `mocha test --compilers js:babel-core/register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1445 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1425 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1424 | `npm run build && mocha -r should` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1423 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1419 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [electron/devtron](https://github.com/electron/devtron) | 1413 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1409 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1408 | `istanbul cover _mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1405 | `mocha --recursive test/bin` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1396 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1395 | `mocha --recursive` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1388 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1385 | `./node_modules/mocha/bin/mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1384 | `webpack && npm run lint && npm run mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1376 | `./node_modules/.bin/mocha test` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1371 | `cross-env NODE_ENV=test nyc mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1370 | `npm run mocha:istanbul` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1365 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1362 | `mocha --compilers js:babel-core/register` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1361 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1360 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1358 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1353 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1349 | `npm run lint && mocha --require @babel/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1346 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1333 | `lerna run test && mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1330 | `mocha --timeout 60000 test/` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1326 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1324 | `mocha` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1323 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1323 | `mocha test/*.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1293 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1292 | `istanbul test _mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1289 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1273 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1265 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1265 | `mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1263 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [normalize/mz](https://github.com/normalize/mz) | 1254 | `mocha --reporter spec` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1250 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1241 | `mocha` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1241 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1262 | `mocha tests` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1250 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1242 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1241 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1235 | `mocha` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1224 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1219 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1213 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1236 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1235 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1230 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1224 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1219 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1213 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1206 | `mocha test` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1199 | `mocha --recursive -r tests/setup tests` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1134 | `npm run convertto:es5 && npm run mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1131 | `mocha && standard` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1129 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1129 | `mocha test/*` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1115 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1105 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1103 | `eslint src test && mocha --compilers babel-register` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1101 | `mocha --recursive --bail --reporter spec test` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1099 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1096 | `mocha --check-leaks -t 20000` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1095 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1128 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1125 | `standard && mocha -b` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1115 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1113 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1105 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1105 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1103 | `eslint src test && mocha --compilers babel-register` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1101 | `mocha --recursive --bail --reporter spec test` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1099 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1098 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1096 | `mocha --check-leaks -t 20000` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1095 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1090 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1090 | `mocha --compilers js:babel-register` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1115 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1113 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1112 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1105 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1105 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1103 | `eslint src test && mocha --compilers babel-register` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1101 | `mocha --recursive --bail --reporter spec test` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1099 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1098 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1096 | `mocha --check-leaks -t 20000` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1095 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1090 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1090 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1086 | `mocha test/tests.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1022 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1014 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1013 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1011 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1006 | `mocha --check-leaks -R dot` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1005 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1000 | `mocha --compilers js:babel-register test/*.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1000 | `npm run lint && mocha -R spec` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 987 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 987 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 983 | `mocha --reporter spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 982 | `mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 828 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 827 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 821 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 813 | `cake build && mocha ./test/mocha/*.coffee` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 810 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 805 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 805 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 803 | `mocha test` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 801 | `mocha test/mocha.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 800 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 799 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 799 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 796 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 796 | `mocha --no-timeouts` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 796 | `xo && mocha -R spec` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 794 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 793 | `mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 792 | `mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 790 | `nyc mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 789 | `mocha tests --timeout 10000` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 789 | `mocha tests --timeout 10000` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 782 | `mocha test` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 782 | `mocha --recursive -s 15 test/` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 781 | `eslint . && mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 775 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 774 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 767 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 766 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 765 | `npm run-script jshint && npm run-script mocha` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 762 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 761 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 759 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 759 | `./bin/selenium-standalone install && mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 758 | `mocha --reporter spec build/test/index.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 751 | `mocha tests/*.mocha.js` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 751 | `mocha 'test/**/*.tests.js'` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 751 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 746 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 744 | `npm run test-mocha && npm run test-karma` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 744 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 744 | `mocha test.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 742 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 740 | `npm run bundle && mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 737 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 736 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 734 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 734 | `mocha --compilers js:babel-core/register` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 732 | `mocha $(find test -name '*.test.js')` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 732 | `./node_modules/.bin/mocha tests/*.js` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 731 | `mocha --reporter spec --bail --check-leaks test/` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 730 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 728 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 727 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 726 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 726 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 723 | `mocha ./test/index.js` | 
| [ideal-postcodes/postcodes.io](https://github.com/ideal-postcodes/postcodes.io) | 630 | `NODE_ENV=test npm run test:create && npm run nyc_mocha && NODE_ENV=test npm run test:clear && npm run lint` | 
| [werk85/node-html-to-text](https://github.com/werk85/node-html-to-text) | 629 | `istanbul cover _mocha && eslint .` | 
| [jaredhanson/passport-google-oauth](https://github.com/jaredhanson/passport-google-oauth) | 624 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [blueberryapps/react-bluekit](https://github.com/blueberryapps/react-bluekit) | 624 | `mocha --compilers js:babel/register --recursive` | 
| [mysamai/mysam](https://github.com/mysamai/mysam) | 623 | `npm run lint && npm run mocha` | 
| [susielu/d3-legend](https://github.com/susielu/d3-legend) | 622 | `mocha` | 
| [robrich/gulp-if](https://github.com/robrich/gulp-if) | 620 | `mocha && jshint .` | 
| [w0rm/gulp-svgstore](https://github.com/w0rm/gulp-svgstore) | 617 | `gulp build && mocha test.js` | 
| [adamgruber/mochawesome](https://github.com/adamgruber/mochawesome) | 613 | `npm run lint && cross-env NODE_ENV=test nyc mocha` | 
| [webpack/memory-fs](https://github.com/webpack/memory-fs) | 611 | `mocha` | 
| [adamjmcgrath/react-native-simple-auth](https://github.com/adamjmcgrath/react-native-simple-auth) | 611 | `mocha lib/**/*.test.js --require babel-register` | 
| [macbre/analyze-css](https://github.com/macbre/analyze-css) | 608 | `mocha -R spec` | 
| [webdriverio-boneyard/webdrivercss](https://github.com/webdriverio-boneyard/webdrivercss) | 607 | `./node_modules/.bin/mocha` | 
| [desmondmorris/node-tesseract](https://github.com/desmondmorris/node-tesseract) | 607 | `mocha` | 
| [sass-eyeglass/eyeglass](https://github.com/sass-eyeglass/eyeglass) | 690 | `mocha test/**/test_*.js` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 689 | `npm run lint && mocha test` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 688 | `npm -s run mocha && npm run -s lint` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 685 | `./node_modules/.bin/mocha` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 683 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 682 | `mocha --bail test/` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 678 | `mocha -R spec` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 678 | `mocha --compilers js:babel-register` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 699 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 696 | `jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 694 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 694 | `mocha` | 
| [sass-eyeglass/eyeglass](https://github.com/sass-eyeglass/eyeglass) | 690 | `mocha test/**/test_*.js` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 689 | `npm run lint && mocha test` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 688 | `npm -s run mocha && npm run -s lint` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 685 | `./node_modules/.bin/mocha` | 
| [chao/RESTClient](https://github.com/chao/RESTClient) | 653 | `mocha` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 653 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [shelljs/shx](https://github.com/shelljs/shx) | 652 | `nyc --reporter=text --reporter=lcov mocha` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 651 | `./node_modules/.bin/mocha test/integration` | 
| [LouisBarranqueiro/reapop](https://github.com/LouisBarranqueiro/reapop) | 651 | `babel-node ./node_modules/karma/bin/karma start ./build/karma.conf.js --reporters mocha` | 
| [calmm-js/partial.lenses](https://github.com/calmm-js/partial.lenses) | 650 | `nyc mocha && nyc report -r html mocha` | 
| [stevenvachon/broken-link-checker](https://github.com/stevenvachon/broken-link-checker) | 649 | `mocha test/ --reporter spec --check-leaks --bail` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 649 | `./node_modules/.bin/mocha --bail` | 
| [aaronshaf/react-toggle](https://github.com/aaronshaf/react-toggle) | 648 | `nyc mocha --require babel-register --require spec/setup.js spec/**/*.spec.js` | 
| [kwhitley/apicache](https://github.com/kwhitley/apicache) | 647 | `nyc mocha $(find test -name '*.test.js') --recursive` | 
| [docpress/docpress](https://github.com/docpress/docpress) | 644 | `nyc mocha` | 
| [anandanand84/technicalindicators](https://github.com/anandanand84/technicalindicators) | 641 | `mocha --compilers js:babel-register --require babel-polyfill` | 
| [danielstjules/buddy.js](https://github.com/danielstjules/buddy.js) | 641 | `mocha -R spec spec/unit spec/integration` | 
| [postcss/gulp-postcss](https://github.com/postcss/gulp-postcss) | 639 | `nyc mocha test.js` | 
| [tonyhb/redux-ui](https://github.com/tonyhb/redux-ui) | 639 | `$(npm bin)/mocha  --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 680 | `mocha --require babel-register src/**/*.spec.js src/*.spec.js` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 678 | `mocha -R spec` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 678 | `mocha --compilers js:babel-register` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 675 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [afc163/fanyi](https://github.com/afc163/fanyi) | 674 | `npm run lint && mocha tests/index.js --timeout 0` | 
| [Savjee/SavjeeCoin](https://github.com/Savjee/SavjeeCoin) | 673 | `mocha tests/*.test.js` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 672 | `mocha --require babel-register` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 671 | `mocha -b -R spec test/*` | 
| [shime/livedown](https://github.com/shime/livedown) | 670 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 670 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [Kagami/ffmpeg.js](https://github.com/Kagami/ffmpeg.js) | 668 | `mocha test/test.js` | 