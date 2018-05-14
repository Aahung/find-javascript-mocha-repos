# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:55 05/14/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 41388 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40500 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38251 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29429 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23938 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23160 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 22215 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22035 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 18728 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18253 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16159 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15670 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14137 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14064 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13327 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12622 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12371 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12191 | `./node_modules/.bin/mocha test/` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12125 | `mocha` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 12013 | `mocha --reporter spec` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12004 | `mocha --reporter spec test/*-test.js` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11580 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11024 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10808 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10372 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10236 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9823 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9639 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9638 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9578 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9538 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9113 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8996 | `mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8781 | `grunt mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 8747 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8699 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 8537 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8292 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8275 | `mocha --check-leaks -R dot` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8240 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8232 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8198 | `grunt clean:test && mocha --exit` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8133 | `mocha test/src` | 
| [amark/gun](https://github.com/amark/gun) | 8036 | `mocha` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7973 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7900 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7852 | `mocha tests/*.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7709 | `npm run eslint && npm run mocha` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7575 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [dthree/cash](https://github.com/dthree/cash) | 7502 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7462 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7437 | `mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7425 | `./node_modules/.bin/mocha test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7400 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7308 | `npm run build && istanbul cover _mocha` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 7000 | `nyc mocha test/**/* -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6960 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6880 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6780 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 6779 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6759 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6725 | `mocha $HARMONY_OPTS` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6719 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 6610 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6464 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6226 | `npm run lint -s && npm run mocha -s` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6075 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6069 | `npm run jshint && mocha test/` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6056 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6019 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5937 | `mocha` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 5865 | `npm run build-cli && mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5794 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5780 | `mocha test --recursive` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5733 | `mocha test/test.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5688 | `mocha --exit --require babel-core/register` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5683 | `mocha tests/node.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5570 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5550 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5457 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5405 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5367 | `mocha; jshint *.js lib` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5287 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5250 | `mocha --timeout 10000 && npm run lint` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5160 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5154 | `mocha src/**/*Tests.js --harmony` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5134 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5128 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 4924 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4899 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4879 | `gulp lint && mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4859 | `standard && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4801 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4753 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [santinic/how2](https://github.com/santinic/how2) | 4705 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4683 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4665 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4618 | `gulp build; mocha;` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4597 | `mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4551 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4547 | `mocha ./test/runner.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4507 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4460 | `./node_modules/.bin/mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4415 | `mocha test` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4413 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4322 | `mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4319 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4302 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4221 | `mocha -R spec ./test --recursive` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4160 | `mocha --recursive && make test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4125 | `NODE_ENV=test mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4120 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4082 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4074 | `nyc mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4030 | `npm run lint && npm run mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 4004 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3960 | `mocha --require test/babel-hook test/*.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 3943 | `mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3892 | `nyc mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3890 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3874 | `mocha -R spec ./test` | 
| [tj/ejs](https://github.com/tj/ejs) | 3873 | `mocha --require should --reporter spec` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3869 | `export TESTING=true; mocha --reporter list` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3814 | `npm run lint ; mocha && mocha test/individual` | 
| [erming/shout](https://github.com/erming/shout) | 3807 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3746 | `npm run lint && npm run mocha` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3742 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3728 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3722 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3685 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3658 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3617 | `standard && mocha --timeout 60000 test/test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3569 | `npm run build && mocha test/*.test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3561 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3560 | `mocha tests/javascript` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3531 | `mocha --check-leaks --reporter spec --bail` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3511 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3488 | `mocha --reporter spec --timeout 3000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3466 | `node_modules/.bin/mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3448 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3439 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3423 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3416 | `mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3379 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3369 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3366 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3345 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3340 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3310 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3308 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3278 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3208 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3109 | `node_modules/.bin/mocha test/tests.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3108 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3106 | `mocha` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3105 | `NODE_ENV=test mocha test/**/*.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3103 | `./node_modules/.bin/mocha test/test.*.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3085 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3062 | `mocha` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 3022 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3001 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2978 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2977 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2973 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2973 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2957 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2931 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2899 | `mocha test/index.js && npm run demo` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2886 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2884 | `NODE_ENV=test mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2865 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2857 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2839 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2836 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2826 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2818 | `mocha -R spec --recursive src/test` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2814 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2814 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2781 | `istanbul cover _mocha` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2777 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2773 | `mocha --require should --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2755 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2752 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2727 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2773 | `mocha --require should --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2755 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2752 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2736 | `mocha --opts mocha.opts` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2727 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2694 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2691 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2690 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2685 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2674 | `xo && mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2669 | `mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2668 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2667 | `npm run mocha && npm run lint` | 
| [css/csso](https://github.com/css/csso) | 2652 | `mocha --reporter dot` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2649 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2648 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2630 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2622 | `mocha --require babel-register --recursive spec` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2618 | `mocha --timeout 100000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2599 | `mocha-phantomjs ./test/index.html` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2571 | `mocha --recursive --watch` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2539 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2538 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2534 | `node_modules/.bin/mocha --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2527 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2503 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2492 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2469 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2457 | `mocha --reporter=spec test/*-test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2449 | `npm run build && cd test && mocha . --reporter dot` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2431 | `mocha -R landing test/index` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2424 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2415 | `nyc mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2415 | `mocha --require should --reporter spec` | 
| [json5/json5](https://github.com/json5/json5) | 2410 | `nyc --reporter=html --reporter=text mocha` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2387 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2373 | `mocha test/src/**/*.unit.js` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2364 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2361 | `mocha "test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2358 | `mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2350 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2341 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2338 | `grunt jshint && mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2326 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2321 | `mocha test.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2317 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2311 | `mocha` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2247 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2238 | `mocha test test/unit/**/*_test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2235 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2230 | `mocha -R spec` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2224 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2194 | `nyc --reporter=html --reporter=text mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2177 | `mocha --compilers js:babel-register` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2125 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2121 | `mocha test && npm run lint` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2119 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2125 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2121 | `mocha test && npm run lint` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2119 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2111 | `mocha && eslint .` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2099 | `cross-env BABEL_ENV=test mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2097 | `mocha -R spec test/*.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2092 | `mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2078 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2077 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2018 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2016 | `mocha --compilers js:babel-register` | 
| [slate/slate](https://github.com/slate/slate) | 2010 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1999 | `eslint . && mocha -t 5000` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1991 | `standard && mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 1983 | `mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1957 | `mocha test/runner.js --reporter spec` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1952 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1946 | `mocha --require=test/test_helper.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1937 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1929 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1922 | `mocha test/index.js --reporter dot` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1919 | `mocha` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1918 | `mocha test/ --no-timeouts` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1911 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1907 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1906 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1893 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1892 | `mocha --reporter spec --timeout 5000` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1878 | `mocha --compilers js:babel-core/register __tests__` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1877 | `mocha --require ./test/common --growl test/expect.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1866 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1863 | `mocha tests.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1855 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1851 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1843 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [then/promise](https://github.com/then/promise) | 1839 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [share/sharedb](https://github.com/share/sharedb) | 1830 | `./node_modules/.bin/mocha && npm run jshint` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1826 | `mocha && eslint *.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1821 | `mocha test/*.test.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1818 | `npm run lint && mocha -R dot && npm run cover` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1818 | `nyc npm run _mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1815 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1810 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1801 | `mocha --timeout 5000` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1797 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1791 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1780 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1778 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1775 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1773 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 1767 | `mocha --compilers js:babel-core/register './specs/**/*.spec.js'` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1760 | `mocha --reporter spec && npm run test-typescript` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1759 | `npm run lint && mocha --reporter spec test/*.js` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1759 | `mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1750 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1747 | `mocha -R spec spec spec/reporters` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1744 | `npm run mocha && npm run karma` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1742 | `mocha test` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1736 | `mocha test/**/*_test.js --bail` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1726 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1718 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1712 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [pahen/madge](https://github.com/pahen/madge) | 1705 | `npm run lint && npm run mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1701 | `mocha` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1694 | `standard "src/*.js" && npm run build && mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1694 | `mocha && npm run lint` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1694 | `npm run lint && npm run mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1689 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1687 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1683 | `mocha` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1677 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1677 | `mocha --reporter spec --grep .` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1674 | `xo && mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1673 | `mocha tests --compilers js:babel-core/register` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1665 | `mocha --reporter spec test/*.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1662 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1637 | `mocha test -u bdd -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1633 | `mocha test/**/*.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1631 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1631 | `npm run lint && mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1629 | `mocha test/*.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1625 | `mocha --expose-gc --slow 300` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1625 | `mocha ./test/basic.js -t 5000` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1618 | `mocha tests/test.js` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1618 | `mocha test --timeout 600000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1612 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1606 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1603 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1602 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1593 | `mocha spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1588 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1585 | `mocha test/* --reporter spec` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1584 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1512 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1507 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1499 | `mocha --reporter spec` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1496 | `npm run test:lint && npm run test:mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1482 | `eslint --cache . && tsc && mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1481 | `mocha -u tdd` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1470 | `node_modules/.bin/mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1470 | `mocha -R spec` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1466 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1460 | `mocha compiled_tests/` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1460 | `mocha compiled_tests/` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1459 | `mocha --check-leaks -R dot` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1455 | `standard "./src/*.js" && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1453 | `mocha tests.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1453 | `mocha test/**/*.spec.js` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1451 | `nyc mocha` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1451 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1450 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1447 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [samccone/drool](https://github.com/samccone/drool) | 1447 | `mocha test/tests.js --timeout=10000` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1446 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [AlloyTeam/omi](https://github.com/AlloyTeam/omi) | 1441 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1428 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1426 | `mocha test/setup.js test/spec/*.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1425 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1416 | `mocha --check-leaks --reporter spec --bail` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1415 | `mocha test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1453 | `mocha tests.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1453 | `mocha test/**/*.spec.js` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1451 | `nyc mocha` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1451 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1450 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1447 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [samccone/drool](https://github.com/samccone/drool) | 1447 | `mocha test/tests.js --timeout=10000` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1446 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [AlloyTeam/omi](https://github.com/AlloyTeam/omi) | 1441 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1428 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1426 | `mocha test/setup.js test/spec/*.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1425 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1416 | `mocha --check-leaks --reporter spec --bail` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1415 | `mocha test.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1409 | `mocha --recursive` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1345 | `istanbul cover _mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1338 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1335 | `mocha -R spec test/*.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1325 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1321 | `npm run build && mocha -r should` | 
| [electron/devtron](https://github.com/electron/devtron) | 1306 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1298 | `mocha-phantomjs tests/index.html` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1294 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1346 | `cross-env NODE_ENV=test nyc mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1345 | `istanbul cover _mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1342 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1338 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1335 | `mocha -R spec test/*.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1325 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1321 | `npm run build && mocha -r should` | 
| [electron/devtron](https://github.com/electron/devtron) | 1306 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1300 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1298 | `mocha-phantomjs tests/index.html` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1295 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1295 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1294 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1287 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1287 | `mocha test` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1281 | `./node_modules/.bin/mocha test` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1272 | `mocha spec/exec.js` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1271 | `istanbul cover _mocha test -- --timeout 20000` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1268 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1267 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1266 | `mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1265 | `mocha --recursive` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1260 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1253 | `mocha --opts test/opts/mocha.opts` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1239 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1239 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1234 | `nyc mocha --timeout=20000 test.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1234 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1234 | `mocha test/*.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1232 | `mocha test/unit` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1225 | `mocha tests` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1217 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1213 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1212 | `mocha test/test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1207 | `mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1202 | `mocha --reporter dot` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1201 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1199 | `mocha test/**/*Spec.js` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1199 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1198 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1194 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1199 | `mocha test/**/*Spec.js` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1199 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1198 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1194 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1189 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1186 | `node ./node_modules/mocha/bin/mocha tests` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1183 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1181 | `mocha test` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1178 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1176 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1173 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1172 | `mocha tests/test-*` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1168 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1163 | `mocha src/test.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1161 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1150 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1138 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1134 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1132 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1129 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1123 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1121 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1120 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1111 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1123 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1121 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1120 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1111 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1103 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1102 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1098 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1098 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1093 | `mocha -R spec ./test/unit/**` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1089 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1048 | `mocha tests/*.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1040 | `istanbul test _mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1040 | `mocha --reporter spec --timeout 3000` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1033 | `mocha --compilers js:babel-core/register` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1029 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1029 | `mocha test/tests.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1027 | `mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1026 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1025 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1023 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1020 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1019 | `webpack && npm run lint && npm run mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1051 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1048 | `mocha tests/*.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1046 | `npm run lint && npm run mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1040 | `istanbul test _mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1040 | `mocha --reporter spec --timeout 3000` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1035 | `TEST=all mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1034 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1033 | `mocha --compilers js:babel-core/register` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1030 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1029 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1029 | `mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1029 | `mocha test/tests.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1027 | `mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1026 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1025 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1023 | `mocha` | 
| [jas/playground](https://github.com/jas/playground) | 1021 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [router5/router5](https://github.com/router5/router5) | 1020 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1019 | `webpack && npm run lint && npm run mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1014 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1013 | `mocha --check-leaks -R dot` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1012 | `mocha --recursive --bail --reporter spec test` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1011 | `standard && mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1010 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1009 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1008 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1006 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 997 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 997 | `mocha --colors ./test/*.spec.js` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 995 | `mocha $(find test -name '*.test.js')` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 995 | `webpack && mocha test/unit` | 
| [electron/asar](https://github.com/electron/asar) | 992 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 991 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 984 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 984 | `mocha --reporter spec --bail --check-leaks test/` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 983 | `mocha -t 120000 test/*.test.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 980 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 978 | `mocha --recursive test/unit/` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 977 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [tomas/needle](https://github.com/tomas/needle) | 976 | `mocha test` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 974 | `standard && mocha -b` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 973 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 972 | `mocha --async-only` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 972 | `mocha --reporter spec --bail --check-leaks test/` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 967 | `mocha -R list` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 963 | `mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 959 | `mocha --reporter spec` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 958 | `npm run lint && mocha --require @babel/register` | 
| [electron/spectron](https://github.com/electron/spectron) | 955 | `mocha && standard` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 955 | `eslint src test && mocha --compilers babel-register` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 955 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 954 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 949 | `mocha --timeout 5000` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 935 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 933 | `mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 933 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 931 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 926 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 918 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 914 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 913 | `mocha "client.test" --compilers js:babel-register` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 913 | `mocha ./test -R spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 911 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 910 | `npm run convertto:es5 && npm run mocha` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 909 | `mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 905 | `npm-run-all test:jest test:server:mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 901 | `mocha --compilers js:babel-register test/*.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 899 | `npm run mocha:istanbul` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 898 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 897 | `mocha --reporter spec --bail --check-leaks test/` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 894 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 893 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 893 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 886 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 885 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 883 | `npm run lint && mocha -R spec` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 867 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 866 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 866 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 862 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 862 | `node_modules/.bin/mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 859 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 856 | `npm run lint && npm run mocha && npm run cov` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 852 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 851 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 850 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 850 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 852 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 851 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 850 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 850 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 850 | `eslint test && mocha --compilers js:babel/register` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 849 | `mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 848 | `node_modules/.bin/mocha test/spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 847 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 843 | `mocha -t 600000` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 837 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 834 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 806 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 805 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 801 | `mocha --require babel-register` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 800 | `mocha --reporter spec --bail --check-leaks test/` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 796 | `mocha --reporter list` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 795 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 791 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 790 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 789 | `mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 789 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 801 | `mocha --require babel-register` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 796 | `mocha --reporter list` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 795 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 795 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 793 | `mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 790 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 789 | `mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 789 | `mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 793 | `mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 791 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 790 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 789 | `mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 789 | `mocha` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 784 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 782 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 781 | `mocha --colors --reporter spec test.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 781 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 781 | `mocha --async-only` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 764 | `./node_modules/.bin/mocha --reporter spec` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 756 | `mocha test` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 756 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 754 | `mocha --ui tdd --require ./test/__setup` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 754 | `mocha -R spec src/**/*_test.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 752 | `npm run mocha-test test/integration` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 751 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 747 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 747 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 744 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 744 | `mocha --harmony --full-trace --check-leaks` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 744 | `mocha test` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 756 | `mocha test` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 756 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 754 | `mocha --ui tdd --require ./test/__setup` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 754 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 754 | `mocha -R spec src/**/*_test.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 752 | `npm run mocha-test test/integration` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 751 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 747 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 747 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 745 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 744 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 744 | `mocha --harmony --full-trace --check-leaks` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 744 | `mocha test` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 742 | `npm run build && istanbul test _mocha test/test.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 717 | `mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 716 | `mocha tests/*.mocha.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 715 | `mocha --no-timeouts` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 715 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 711 | `npm run bundle && mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 711 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 709 | `npm run lint && npm run mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 708 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 707 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 704 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 703 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 