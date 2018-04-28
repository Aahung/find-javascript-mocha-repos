# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:45 04/28/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 41061 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40324 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 40323 | `npm run mocha` | 
| [expressjs/express](https://github.com/expressjs/express) | 37927 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29320 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23859 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23000 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 21833 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 21830 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 18553 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18136 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16064 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15545 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14021 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 13972 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13206 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12542 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12329 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12115 | `./node_modules/.bin/mocha test/` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12111 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11939 | `mocha --reporter spec test/*-test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11865 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11414 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10942 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10675 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10231 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10116 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9725 | `mocha test/index.js` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9595 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tj/co](https://github.com/tj/co) | 9582 | `mocha --harmony` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9508 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9458 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9076 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8894 | `mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8749 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8656 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 8632 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 8400 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8269 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8260 | `mocha --check-leaks -R dot` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8179 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8170 | `grunt clean:test && mocha --exit` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8120 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8076 | `mocha test/src` | 
| [amark/gun](https://github.com/amark/gun) | 7961 | `mocha` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7940 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7879 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7739 | `mocha tests/*.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7682 | `npm run eslint && npm run mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7493 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7454 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7436 | `mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7381 | `./node_modules/.bin/mocha test` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7347 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7287 | `npm run build && istanbul cover _mocha` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7262 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6898 | `mocha --opts mocha.opts` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6871 | `nyc mocha test/**/* -r ./test/before` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 6848 | `npm run mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6787 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 6718 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6709 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6697 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6688 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6680 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6559 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6362 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6173 | `npm run lint -s && npm run mocha -s` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6035 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6025 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6017 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5998 | `npm run jshint && mocha test/` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5931 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5754 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5722 | `mocha test --recursive` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 5688 | `npm run build-cli && mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5652 | `mocha tests/node.js` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5648 | `mocha test/test.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5585 | `mocha --exit --require babel-core/register` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5549 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5525 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5402 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5393 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5241 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5234 | `mocha --timeout 10000 && npm run lint` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5173 | `mocha; jshint *.js lib` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5161 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5152 | `mocha src/**/*Tests.js --harmony` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5068 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4973 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4862 | `gulp lint && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4853 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 4803 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4781 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4778 | `standard && mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4691 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4674 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4656 | `mocha --reporter spec -t 8000` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4606 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4593 | `gulp build; mocha;` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4551 | `mocha ./test/runner.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4529 | `mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4526 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4441 | `./node_modules/.bin/mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4436 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4408 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4370 | `mocha test` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4316 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4305 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4285 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4224 | `mocha -R spec ./test --recursive` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4112 | `mocha --recursive && make test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4078 | `NODE_ENV=test mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4068 | `nyc mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3985 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3983 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3954 | `mocha --require test/babel-hook test/*.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3944 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [muicss/mui](https://github.com/muicss/mui) | 3929 | `mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3909 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3889 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3863 | `export TESTING=true; mocha --reporter list` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3853 | `nyc mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3850 | `mocha --require should --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3844 | `mocha -R spec ./test` | 
| [erming/shout](https://github.com/erming/shout) | 3808 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3768 | `npm run lint ; mocha && mocha test/individual` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3713 | `mocha ./test/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3676 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3673 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3660 | `npm run lint && npm run mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3657 | `npm run jshint && npm run mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3648 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3608 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3558 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3553 | `mocha tests/javascript` | 
| [primus/primus](https://github.com/primus/primus) | 3550 | `npm run build && mocha test/*.test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3483 | `mocha --reporter spec --timeout 3000` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3482 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3468 | `mocha --check-leaks --reporter spec --bail` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3453 | `node_modules/.bin/mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3445 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3423 | `node_modules/.bin/mocha test/lib/` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3422 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3340 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3327 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3322 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 3318 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3280 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3276 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3264 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3187 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3173 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3104 | `mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3102 | `node_modules/.bin/mocha test/tests.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3100 | `./node_modules/.bin/mocha test/test.*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3099 | `mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3059 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3059 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3052 | `NODE_ENV=test mocha test/**/*.js` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3047 | `mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2992 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 2989 | `nyc mocha && tsc` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2962 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 2955 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2945 | `mocha test/*.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2925 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2923 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2916 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2915 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2861 | `mocha test/index.js && npm run demo` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2855 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2840 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2837 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2827 | `NODE_ENV=test mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2821 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2816 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2806 | `mocha -R spec --recursive src/test` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2797 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2795 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2790 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2790 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2777 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2777 | `istanbul cover _mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2770 | `mocha --require should --reporter spec` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2757 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2737 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2733 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2714 | `mocha --opts mocha.opts` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2706 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2676 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2663 | `xo && mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2653 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2644 | `npm run mocha && npm run lint` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2643 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2643 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2636 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2635 | `mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2632 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [css/csso](https://github.com/css/csso) | 2630 | `mocha --reporter dot` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2617 | `mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2610 | `mocha --timeout 100000` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2609 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2607 | `mocha --require babel-register --recursive spec` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2595 | `mocha-phantomjs ./test/index.html` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2524 | `export TESTING=true; mocha --reporter list` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2520 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2508 | `node_modules/.bin/mocha --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2492 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2475 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2452 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2444 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2425 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2424 | `npm run build && cd test && mocha . --reporter dot` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2400 | `nyc mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2425 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2424 | `npm run build && cd test && mocha . --reporter dot` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2400 | `nyc mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2374 | `mocha -R landing test/index` | 
| [json5/json5](https://github.com/json5/json5) | 2373 | `nyc --reporter=html --reporter=text mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2371 | `mocha --require should --reporter spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2363 | `mocha test/src/**/*.unit.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2362 | `mocha` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2360 | `mocha test` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2344 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2339 | `grunt jshint && mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2338 | `mocha --no-colors --reporter spec` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2335 | `mocha "test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2329 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2290 | `mocha test/unit --require mochahook` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2098 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2094 | `cross-env BABEL_ENV=test mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2094 | `mocha && eslint .` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2086 | `mocha test && npm run lint` | 
| [noble/noble](https://github.com/noble/noble) | 2084 | `mocha -R spec test/*.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2084 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2074 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2065 | `mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2098 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2094 | `cross-env BABEL_ENV=test mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2094 | `mocha && eslint .` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2086 | `mocha test && npm run lint` | 
| [noble/noble](https://github.com/noble/noble) | 2084 | `mocha -R spec test/*.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2084 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2074 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2065 | `mocha` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1944 | `mocha --require=test/test_helper.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1929 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1921 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1916 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1915 | `mocha test/index.js --reporter dot` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1910 | `mocha --bail --reporter spec --check-leaks test/` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1909 | `eslint . && mocha -t 5000` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1906 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1900 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1897 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1879 | `mocha --reporter spec --timeout 5000` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1874 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1872 | `mocha --require ./test/common --growl test/expect.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1863 | `mocha tests.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1854 | `mocha --compilers js:babel-core/register __tests__` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1853 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1846 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1844 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1833 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [then/promise](https://github.com/then/promise) | 1829 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [share/sharedb](https://github.com/share/sharedb) | 1813 | `./node_modules/.bin/mocha && npm run jshint` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1811 | `mocha && eslint *.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1806 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [kach/nearley](https://github.com/kach/nearley) | 1803 | `mocha test/*.test.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1802 | `npm run lint && mocha -R dot && npm run cover` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1801 | `mocha --timeout 5000` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1799 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1798 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1785 | `nyc npm run _mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1779 | `mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1773 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1770 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1765 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1758 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1753 | `npm run lint && mocha --reporter spec test/*.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1752 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1749 | `mocha --reporter spec && npm run test-typescript` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1740 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1737 | `mocha -R spec spec spec/reporters` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1737 | `mocha test` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1736 | `mocha test/**/*_test.js --bail` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1736 | `npm run mocha && npm run karma` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1730 | `mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1730 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1714 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1712 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1699 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [pahen/madge](https://github.com/pahen/madge) | 1689 | `npm run lint && npm run mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1687 | `npm run lint && npm run mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1682 | `./node_modules/.bin/mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1682 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1679 | `mocha && npm run lint` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1677 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1673 | `xo && mocha` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1666 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1663 | `mocha --reporter spec --grep .` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1653 | `standard "src/*.js" && npm run build && mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1652 | `mocha tests --compilers js:babel-core/register` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1616 | `mocha test/*.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1613 | `mocha ./test/basic.js -t 5000` | 
| [teambit/bit](https://github.com/teambit/bit) | 1611 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1605 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1604 | `npm run lint && mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1603 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1600 | `mocha test --timeout 600000` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1591 | `mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1584 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1574 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1563 | `mocha spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1548 | `./node_modules/.bin/mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1548 | `npm run lint && npm run mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1546 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1563 | `mocha spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1548 | `./node_modules/.bin/mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1548 | `npm run lint && npm run mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1546 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1541 | `mocha --compilers js:babel-register` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1530 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1519 | `./node_modules/mocha/bin/mocha -R spec` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1513 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1508 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1507 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1501 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1519 | `./node_modules/mocha/bin/mocha -R spec` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1513 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1508 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1507 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1501 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1493 | `npm run test:lint && npm run test:mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1492 | `mocha --reporter spec` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1483 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1481 | `mocha -u tdd` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1471 | `mocha -R spec` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1464 | `node_modules/.bin/mocha --recursive` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1463 | `eslint --cache . && tsc && mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1456 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1449 | `mocha --check-leaks -R dot` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1448 | `mocha test/**/*.spec.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1447 | `mocha test/tests.js --timeout=10000` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1437 | `nyc mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1437 | `mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1437 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [zeit/ms](https://github.com/zeit/ms) | 1436 | `mocha tests.js` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1436 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1435 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1428 | `mocha compiled_tests/` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1428 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1427 | `standard "./src/*.js" && mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1426 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1413 | `mocha test.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1410 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1402 | `mocha --check-leaks --reporter spec --bail` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1400 | `mocha test/setup.js test/spec/*.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1397 | `mocha --recursive` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1383 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1383 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1376 | `nyc npm run mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1372 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1371 | `mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1361 | `./node_modules/mocha/bin/mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1341 | `cross-env NODE_ENV=test nyc mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1340 | `istanbul cover _mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1330 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1329 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1328 | `mocha -R spec test/*.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1326 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1311 | `npm run build && mocha -r should` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1298 | `mocha-phantomjs tests/index.html` | 
| [electron/devtron](https://github.com/electron/devtron) | 1293 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1291 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1285 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1285 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1277 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1273 | `./node_modules/.bin/mocha test` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1271 | `mocha spec/exec.js` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1260 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1258 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1258 | `istanbul cover _mocha test -- --timeout 20000` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1251 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1248 | `mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1247 | `mocha test` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1247 | `mocha --recursive` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1240 | `mocha --opts test/opts/mocha.opts` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1234 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1233 | `mocha test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1230 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1223 | `mocha tests` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1220 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1217 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1216 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1210 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1210 | `mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1209 | `mocha test/test.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1208 | `mocha test/unit` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1206 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1206 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1203 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1199 | `mocha test/**/*Spec.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1194 | `standard && istanbul cover _mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1194 | `eslint src && mocha && karma start --single-run` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1192 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1192 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1190 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1189 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1188 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1186 | `nyc mocha --timeout=20000 test.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1183 | `mocha --reporter dot` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1183 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [x-tag/core](https://github.com/x-tag/core) | 1183 | `NODE_ENV=test mocha --exit` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1182 | `node ./node_modules/mocha/bin/mocha tests` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1181 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1177 | `mocha test` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1172 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1168 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1167 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1161 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1153 | `node_modules/.bin/mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1151 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1148 | `mocha src/test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1146 | `mocha --reporter spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1145 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1144 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1142 | `mocha tests/test-*` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1139 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1137 | `npm run lint && npm run mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1131 | `mocha` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1094 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1094 | `mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1084 | `mocha test/*` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1083 | `xo && mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1081 | `mocha $(find test -name '*.test.js')` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1077 | `nodeunit test; mocha test` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1077 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1072 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1071 | `mocha --compilers js:babel-register` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1071 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1067 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1067 | `npm run prepublishOnly && mocha test/test.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1072 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1071 | `mocha --compilers js:babel-register` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1071 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1067 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1067 | `npm run prepublishOnly && mocha test/test.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1062 | `NODE_PATH=. mocha **/*.spec.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1061 | `mocha -R spec ./test/unit/**` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1060 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1057 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1056 | `mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1054 | `istanbul cover _mocha test/*.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1050 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1046 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1054 | `istanbul cover _mocha test/*.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1050 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1046 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1041 | `istanbul test _mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1041 | `mocha --reporter spec --timeout 3000` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1035 | `mocha --recursive test` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1029 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1027 | `npm run lint && npm run mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1026 | `mocha tests/*.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1026 | `mocha test/tests.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1025 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1024 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1023 | `mocha ./test/test*.js --reporter spec` | 
| [jas/playground](https://github.com/jas/playground) | 1022 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1021 | `mocha --compilers js:babel-core/register` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 977 | `mocha -t 120000 test/*.test.js` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 975 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 975 | `TEST=all mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 973 | `npm run rollup-cjs && mocha test/test.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 971 | `mocha test` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 967 | `mocha --reporter spec --bail --check-leaks test/` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 964 | `mocha -R list` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 962 | `standard && mocha -b` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 961 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 960 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 955 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 953 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 952 | `mocha --reporter spec` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 949 | `eslint src test && mocha --compilers babel-register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 949 | `mocha --timeout 5000` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 945 | `mocha` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 985 | `webpack && mocha test/unit` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 983 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 982 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [electron/asar](https://github.com/electron/asar) | 982 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 981 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 981 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 978 | `mocha` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 977 | `mocha -t 120000 test/*.test.js` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 975 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 975 | `TEST=all mocha` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 973 | `mocha --recursive test/unit/` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 973 | `npm run rollup-cjs && mocha test/test.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 971 | `mocha test` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 967 | `mocha --reporter spec --bail --check-leaks test/` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 965 | `mocha --async-only` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 964 | `mocha -R list` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 962 | `standard && mocha -b` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 961 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 960 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 955 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 953 | `mocha && standard` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 953 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 952 | `mocha --reporter spec` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 949 | `eslint src test && mocha --compilers babel-register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 949 | `mocha --timeout 5000` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 945 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 942 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 940 | `npm run lint && mocha --require @babel/register` | 
| [odota/core](https://github.com/odota/core) | 936 | `NODE_ENV=test mocha --exit` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 908 | `mocha "client.test" --compilers js:babel-register` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 907 | `mocha` | 
| [reactivestack/cookies](https://github.com/reactivestack/cookies) | 902 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 902 | `mocha ./test -R spec` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 901 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 896 | `npm run convertto:es5 && npm run mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 896 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 894 | `mocha --compilers js:babel-register test/*.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 891 | `./node_modules/.bin/mocha --globals angular,require` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 890 | `mocha --reporter spec --bail --check-leaks test/` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 889 | `mocha --timeout 20000` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 888 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 885 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 885 | `npm-run-all test:jest test:mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 881 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 881 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 880 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 876 | `npm run lint && mocha -R spec` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 870 | `./node_modules/.bin/mocha --bail` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 870 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 869 | `mocha -R spec` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 868 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 867 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 866 | `npm run mocha:istanbul` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 863 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 861 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 860 | `mocha tests` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 858 | `node_modules/.bin/mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 854 | `npm run lint && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 850 | `mocha --timeout 200000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 848 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 848 | `mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 847 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 845 | `node_modules/.bin/mocha test/spec` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 844 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 844 | `eslint test && mocha --compilers js:babel/register` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 826 | `mocha --check-leaks -t 20000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 825 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 824 | `mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 823 | `istanbul cover _mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 822 | `mocha --reporter spec` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 822 | `standard && standard ./bin/* && mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 822 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 819 | `mocha -t 5000` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 818 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 818 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 814 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 813 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 811 | `nyc mocha specs` | 
| [nimiq-network/core](https://github.com/nimiq-network/core) | 811 | `NODE_ENV=test mocha --exit` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 811 | `mocha test --compilers js:babel-register` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 811 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 814 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 813 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 811 | `nyc mocha specs` | 
| [nimiq-network/core](https://github.com/nimiq-network/core) | 811 | `NODE_ENV=test mocha --exit` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 811 | `mocha test --compilers js:babel-register` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 811 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 808 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 807 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 806 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 804 | `mocha spec/*.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 804 | `istanbul cover -- _mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 801 | `./node_modules/.bin/mocha -R spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 800 | `mocha --require babel-register` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 796 | `mocha --reporter spec --bail --check-leaks test/` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 795 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 792 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 790 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 788 | `mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 788 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 786 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 785 | `mocha --reporter list` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 780 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 779 | `mocha --colors --reporter spec test.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 779 | `mocha --async-only` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 777 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 776 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 780 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 779 | `mocha --colors --reporter spec test.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 779 | `mocha --async-only` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 777 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 776 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [radi-js/radi](https://github.com/radi-js/radi) | 773 | `nyc mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 772 | `npm run lint && mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 770 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 770 | `xo && mocha -R spec` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 769 | `mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 766 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 760 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 759 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 758 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 756 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 754 | `mocha --ui tdd --require ./test/__setup` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 754 | `mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 753 | `mocha test --compilers js:babel-core/register` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 753 | `mocha -R spec src/**/*_test.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 751 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 747 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 746 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 744 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 744 | `npm run mocha-test test/integration` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 744 | `mocha test` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 739 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 737 | `mocha --recursive -s 15 test/` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 735 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 734 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [developit/decko](https://github.com/developit/decko) | 732 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 732 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 732 | `./node_modules/.bin/mocha --reporter spec` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 732 | `mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 731 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 731 | `nyc --check-coverage mocha test/*.test.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 731 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 730 | `mocha --reporter spec` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 729 | `mocha --harmony --full-trace --check-leaks` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 729 | `npm run build && istanbul test _mocha test/test.js` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 729 | `mocha` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 728 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 728 | `mocha test` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 727 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 727 | `mocha test.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 723 | `mocha test` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 722 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 722 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 721 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 721 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 717 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 717 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 716 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 716 | `mocha` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 715 | `mocha` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 714 | `mocha test` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 714 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 713 | `mocha tests/*.mocha.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 712 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 711 | `npm run bundle && mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 709 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 709 | `mocha --recursive ./test/*_spec.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 705 | `mocha --no-timeouts` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 705 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 705 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 704 | `mocha test/index.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 703 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 703 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 703 | `npm run lint && npm run mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 701 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 