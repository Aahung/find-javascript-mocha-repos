# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:59 05/04/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 41195 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40420 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38120 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29360 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23878 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23048 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 21974 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 21914 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 18608 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18185 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16101 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15587 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14039 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14039 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13240 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12572 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12346 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12144 | `./node_modules/.bin/mocha test/` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12116 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11953 | `mocha --reporter spec test/*-test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11918 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11468 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10973 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10719 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10280 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10170 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9768 | `mocha test/index.js` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9604 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tj/co](https://github.com/tj/co) | 9603 | `mocha --harmony` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9524 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9493 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9085 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8759 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8676 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 8669 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 8442 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8276 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8263 | `mocha --check-leaks -R dot` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8206 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8181 | `grunt clean:test && mocha --exit` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8163 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8101 | `mocha test/src` | 
| [amark/gun](https://github.com/amark/gun) | 7982 | `mocha` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7958 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7890 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7792 | `mocha tests/*.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7693 | `npm run eslint && npm run mocha` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7500 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [dthree/cash](https://github.com/dthree/cash) | 7495 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7436 | `mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7403 | `./node_modules/.bin/mocha test` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7395 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7297 | `npm run build && istanbul cover _mocha` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7292 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6931 | `mocha --opts mocha.opts` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6909 | `nyc mocha test/**/* -r ./test/before` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6831 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 6735 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6729 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6720 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6700 | `mocha $HARMONY_OPTS` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6697 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 6579 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6411 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6191 | `npm run lint -s && npm run mocha -s` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6055 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6032 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6025 | `npm run jshint && mocha test/` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6018 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5932 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5772 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 5758 | `npm run build-cli && mocha` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5745 | `mocha test --recursive` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5684 | `mocha test/test.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5662 | `mocha tests/node.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5622 | `mocha --exit --require babel-core/register` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5552 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5532 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5410 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5403 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5252 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5251 | `mocha; jshint *.js lib` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5238 | `mocha --timeout 10000 && npm run lint` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5161 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5152 | `mocha src/**/*Tests.js --harmony` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5089 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5021 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4877 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4866 | `gulp lint && mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 4834 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4814 | `standard && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4790 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4714 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [santinic/how2](https://github.com/santinic/how2) | 4696 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4673 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4655 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4602 | `gulp build; mocha;` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4551 | `mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4547 | `mocha ./test/runner.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4538 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4461 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4449 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4411 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4388 | `mocha test` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4317 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4308 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4294 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4223 | `mocha -R spec ./test --recursive` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4130 | `mocha --recursive && make test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4092 | `NODE_ENV=test mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4072 | `nyc mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4025 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4007 | `npm run lint && npm run mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3991 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3956 | `mocha --require test/babel-hook test/*.js` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3945 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3888 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3865 | `nyc mocha` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3862 | `export TESTING=true; mocha --reporter list` | 
| [tj/ejs](https://github.com/tj/ejs) | 3859 | `mocha --require should --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3854 | `mocha -R spec ./test` | 
| [erming/shout](https://github.com/erming/shout) | 3807 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3789 | `npm run lint ; mocha && mocha test/individual` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3732 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3687 | `npm run lint && npm run mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3685 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3678 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3658 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3612 | `standard && mocha --timeout 60000 test/test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3560 | `npm run build && mocha test/*.test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3554 | `mocha tests/javascript` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3485 | `mocha --check-leaks --reporter spec --bail` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3484 | `mocha --reporter spec --timeout 3000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3457 | `node_modules/.bin/mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3444 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3427 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3427 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3423 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3412 | `mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3358 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3344 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3338 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3330 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3298 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3295 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3295 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3214 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3186 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3105 | `node_modules/.bin/mocha test/tests.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3104 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3104 | `./node_modules/.bin/mocha test/test.*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3099 | `mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3091 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3070 | `NODE_ENV=test mocha test/**/*.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3068 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3052 | `mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3011 | `nyc mocha && tsc` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2996 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 2988 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2968 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2949 | `mocha test/*.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2946 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2945 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2936 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2918 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2869 | `mocha test/index.js && npm run demo` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2863 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2846 | `NODE_ENV=test mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2846 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2843 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2831 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2822 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2814 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2812 | `mocha -R spec --recursive src/test` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2809 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2797 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2797 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2784 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2775 | `istanbul cover _mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2771 | `mocha --require should --reporter spec` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2765 | `mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2747 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2745 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2724 | `mocha --opts mocha.opts` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2717 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2679 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2669 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2666 | `xo && mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2655 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2651 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2650 | `npm run mocha && npm run lint` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2647 | `mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2642 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [css/csso](https://github.com/css/csso) | 2641 | `mocha --reporter dot` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2641 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2630 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2622 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2617 | `mocha --require babel-register --recursive spec` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2613 | `mocha --timeout 100000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2596 | `mocha-phantomjs ./test/index.html` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2566 | `mocha --recursive --watch` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2536 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2526 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2518 | `node_modules/.bin/mocha --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2501 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2484 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2468 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2454 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2452 | `mocha --reporter=spec test/*-test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2234 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2227 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2224 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2221 | `mocha -R spec` | 
| [gajus/swing](https://github.com/gajus/swing) | 2174 | `mocha --compilers js:babel-register` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2103 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2103 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2102 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2098 | `cross-env BABEL_ENV=test mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2098 | `mocha test && npm run lint` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2093 | `mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2088 | `mocha -R spec test/*.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2177 | `nyc --reporter=html --reporter=text mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2174 | `mocha --compilers js:babel-register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2103 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2102 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2098 | `cross-env BABEL_ENV=test mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2093 | `mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2088 | `mocha -R spec test/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2074 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2072 | `mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2103 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2103 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2102 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2098 | `cross-env BABEL_ENV=test mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2098 | `mocha test && npm run lint` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2093 | `mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2088 | `mocha -R spec test/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2074 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2072 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2011 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [slate/slate](https://github.com/slate/slate) | 2010 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1987 | `mocha --compilers js:babel-register` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1986 | `standard && mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 1967 | `mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1952 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1943 | `mocha --require=test/test_helper.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1940 | `mocha test/runner.js --reporter spec` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1935 | `eslint . && mocha -t 5000` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1924 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1918 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1914 | `mocha test/index.js --reporter dot` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1911 | `mocha --bail --reporter spec --check-leaks test/` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1908 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1908 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1901 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1885 | `mocha --reporter spec --timeout 5000` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1881 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1874 | `mocha --require ./test/common --growl test/expect.js` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1864 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1863 | `mocha tests.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1863 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1850 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1847 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1846 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [then/promise](https://github.com/then/promise) | 1829 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [share/sharedb](https://github.com/share/sharedb) | 1824 | `./node_modules/.bin/mocha && npm run jshint` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1818 | `mocha && eslint *.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1813 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [kach/nearley](https://github.com/kach/nearley) | 1811 | `mocha test/*.test.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1809 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1808 | `npm run lint && mocha -R dot && npm run cover` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1795 | `nyc npm run _mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1795 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1780 | `mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1771 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1768 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1765 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1755 | `npm run lint && mocha --reporter spec test/*.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1765 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1755 | `npm run lint && mocha --reporter spec test/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1751 | `mocha --reporter spec && npm run test-typescript` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1743 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1741 | `mocha -R spec spec spec/reporters` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1740 | `mocha` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1740 | `mocha test` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1739 | `npm run mocha && npm run karma` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1736 | `mocha test/**/*_test.js --bail` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1726 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1715 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1712 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1699 | `mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 1696 | `npm run lint && npm run mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1646 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1628 | `mocha test -u bdd -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1626 | `mocha test/**/*.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1625 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1623 | `mocha --expose-gc --slow 300` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1622 | `mocha ./test/basic.js -t 5000` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1619 | `mocha test/*.js` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1616 | `mocha tests/test.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1603 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1595 | `mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1582 | `mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1625 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1623 | `mocha --expose-gc --slow 300` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1622 | `mocha ./test/basic.js -t 5000` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1619 | `mocha test/*.js` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1616 | `mocha tests/test.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1606 | `npm run lint && mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1605 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1603 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1600 | `mocha test --timeout 600000` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1595 | `mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1582 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1578 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1567 | `mocha spec` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1563 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1557 | `npm run lint && npm run mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1550 | `mocha --compilers js:babel-register` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1533 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1521 | `./node_modules/mocha/bin/mocha -R spec` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1512 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1509 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1509 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1505 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1497 | `mocha --reporter spec` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1497 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1492 | `npm run test:lint && npm run test:mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1481 | `mocha -u tdd` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1473 | `eslint --cache . && tsc && mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1470 | `mocha -R spec` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1463 | `node_modules/.bin/mocha --recursive` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1462 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1453 | `mocha --check-leaks -R dot` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1448 | `mocha test/**/*.spec.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1446 | `mocha test/tests.js --timeout=10000` | 
| [zeit/ms](https://github.com/zeit/ms) | 1444 | `mocha tests.js` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1441 | `nyc mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1441 | `mocha compiled_tests/` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1439 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1439 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1437 | `mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1436 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1435 | `standard "./src/*.js" && mocha` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1435 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [AlloyTeam/omi](https://github.com/AlloyTeam/omi) | 1429 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1427 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1415 | `mocha test.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1412 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1407 | `mocha test/setup.js test/spec/*.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1404 | `mocha --check-leaks --reporter spec --bail` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1401 | `mocha --recursive` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1376 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1360 | `./node_modules/mocha/bin/mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1344 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1340 | `cross-env NODE_ENV=test nyc mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1336 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1334 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1330 | `mocha -R spec test/*.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1324 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1316 | `npm run build && mocha -r should` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1297 | `mocha-phantomjs tests/index.html` | 
| [electron/devtron](https://github.com/electron/devtron) | 1295 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1293 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1290 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1289 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1280 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1276 | `./node_modules/.bin/mocha test` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1272 | `mocha spec/exec.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1263 | `mocha test` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1263 | `istanbul cover _mocha test -- --timeout 20000` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1263 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1258 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1258 | `mocha --check-leaks --require @babel/register` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1257 | `mocha --recursive` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1252 | `mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1243 | `mocha --opts test/opts/mocha.opts` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1233 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1233 | `mocha test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1229 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1226 | `mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1225 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1224 | `mocha tests` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1224 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1219 | `mocha test/unit` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1213 | `mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1212 | `mocha test/test.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1211 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1205 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1205 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1205 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1201 | `standard && istanbul cover _mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1201 | `eslint src && mocha && karma start --single-run` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1198 | `mocha test/**/*Spec.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1198 | `nyc mocha --timeout=20000 test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1194 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1193 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1192 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1191 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1191 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1189 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1188 | `mocha --reporter dot` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1184 | `node ./node_modules/mocha/bin/mocha tests` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1180 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1178 | `mocha test` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1174 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1170 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1168 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1156 | `mocha` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1153 | `mocha tests/test-*` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1153 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1151 | `mocha src/test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1151 | `mocha --reporter spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1150 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1146 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [variety/variety](https://github.com/variety/variety) | 1145 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1138 | `npm run lint && npm run mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1132 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1128 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1128 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1127 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1124 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1123 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1117 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1117 | `mocha --check-leaks --reporter spec --bail test/` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1109 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1104 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1102 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1098 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1097 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1094 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1077 | `nodeunit test; mocha test` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1076 | `mocha -R spec ./test/unit/**` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1076 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1074 | `npm run prepublishOnly && mocha test/test.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1072 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1070 | `mocha --compilers js:babel-register` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1069 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1067 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1066 | `NODE_PATH=. mocha **/*.spec.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1064 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1058 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1058 | `istanbul cover _mocha test/*.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1052 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1052 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1044 | `mocha --recursive test` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1041 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1040 | `istanbul test _mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1040 | `mocha --reporter spec --timeout 3000` | 
| [poooi/poi](https://github.com/poooi/poi) | 1039 | `mocha --recursive --harmony --require ./test/babelhook` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1038 | `npm run lint && npm run mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1037 | `mocha ./test/test*.js --reporter spec` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1037 | `mocha tests/*.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1034 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1030 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1028 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1027 | `mocha test/tests.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1025 | `mocha --compilers js:babel-core/register` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1023 | `mocha` | 
| [jas/playground](https://github.com/jas/playground) | 1022 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1020 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1019 | `mocha` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1019 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1017 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1014 | `mocha --check-leaks -R dot` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1008 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1007 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [router5/router5](https://github.com/router5/router5) | 1006 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1005 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1004 | `mocha --recursive --bail --reporter spec test` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1004 | `webpack && npm run lint && npm run mocha` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1000 | `standard && mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 997 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 997 | `mocha --colors ./test/*.spec.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 996 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 993 | `TEST=all mocha` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 989 | `mocha $(find test -name '*.test.js')` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 989 | `webpack && mocha test/unit` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 988 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [electron/asar](https://github.com/electron/asar) | 985 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 929 | `mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 928 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 927 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 921 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 909 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [electron/spectron](https://github.com/electron/spectron) | 955 | `mocha && standard` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 955 | `mocha --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 955 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 951 | `mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 951 | `eslint src test && mocha --compilers babel-register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 949 | `mocha --timeout 5000` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 947 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 944 | `npm run lint && mocha --require @babel/register` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 911 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 911 | `mocha "client.test" --compilers js:babel-register` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 909 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 907 | `mocha` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 903 | `mocha ./test -R spec` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 900 | `npm run convertto:es5 && npm run mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 900 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 896 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 895 | `mocha --compilers js:babel-register test/*.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 894 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 892 | `mocha --reporter spec --bail --check-leaks test/` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 890 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 890 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 890 | `npm-run-all test:jest test:server:mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 882 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 882 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 881 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 881 | `npm run lint && mocha -R spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 878 | `npm run mocha:istanbul` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 873 | `mocha -R spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 870 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 870 | `mocha --reporter list` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 868 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 864 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 863 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 862 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 861 | `node_modules/.bin/mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 859 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 854 | `npm run lint && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 851 | `mocha --timeout 200000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 848 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 848 | `mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 847 | `node_modules/.bin/mocha test/spec` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 847 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 846 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 843 | `eslint test && mocha --compilers js:babel/register` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 838 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 838 | `mocha -t 600000` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 838 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 837 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 831 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 826 | `mocha --check-leaks -t 20000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 825 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 825 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 824 | `mocha -t 5000` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 823 | `mocha --reporter spec` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 823 | `standard && standard ./bin/* && mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 822 | `istanbul cover _mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 820 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 819 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 818 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 818 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 814 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 812 | `nyc mocha specs` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 812 | `mocha test --compilers js:babel-register` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 811 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 811 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 807 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 807 | `istanbul cover -- _mocha --reporter spec` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 807 | `mocha spec/*.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 806 | `./node_modules/.bin/mocha -R spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 801 | `mocha --require babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 799 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 797 | `nyc mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 792 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 791 | `mocha --reporter list` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 790 | `cake build && mocha ./test/mocha/*.coffee` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 790 | `mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 789 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 788 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 760 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 756 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 754 | `mocha --ui tdd --require ./test/__setup` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 753 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 753 | `mocha -R spec src/**/*_test.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 749 | `npm run mocha-test test/integration` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 748 | `mocha test` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 746 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 745 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 744 | `./node_modules/.bin/mocha --reporter spec` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 749 | `npm run mocha-test test/integration` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 748 | `mocha test` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 746 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 745 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 744 | `./node_modules/.bin/mocha --reporter spec` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 743 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 741 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 736 | `mocha --recursive -s 15 test/` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 736 | `npm run build && istanbul test _mocha test/test.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 735 | `mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 734 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 734 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 733 | `nyc --check-coverage mocha test/*.test.js` | 
| [developit/decko](https://github.com/developit/decko) | 732 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [developit/decko](https://github.com/developit/decko) | 732 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 732 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 731 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 731 | `mocha test` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 729 | `mocha --reporter spec` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 727 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 725 | `mocha test` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 724 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 722 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 721 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 720 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 719 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 718 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 717 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 716 | `mocha test` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 716 | `mocha --recursive ./test/*_spec.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 716 | `mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 715 | `mocha tests/*.mocha.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 715 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 731 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 731 | `mocha test` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 729 | `mocha --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 727 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 727 | `mocha` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 726 | `mocha test.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 725 | `mocha test` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 724 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 724 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 722 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 721 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 720 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 719 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 718 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 717 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 716 | `mocha test` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 716 | `mocha --recursive ./test/*_spec.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 716 | `mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 715 | `mocha tests/*.mocha.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 715 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [typicode/katon](https://github.com/typicode/katon) | 712 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 711 | `npm run bundle && mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 708 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 706 | `npm run lint && npm run mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 705 | `mocha --no-timeouts` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 705 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 703 | `mocha test/index.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 702 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 702 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 