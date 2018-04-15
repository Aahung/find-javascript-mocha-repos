# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:55 04/15/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 40695 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40219 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 39867 | `npm run mocha` | 
| [expressjs/express](https://github.com/expressjs/express) | 37665 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29199 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23760 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 22839 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 21591 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 21381 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 18399 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18001 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15951 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15415 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13980 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 13792 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13098 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12467 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12274 | `mocha 'test/**/*.spec.js'` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12086 | `mocha` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12018 | `./node_modules/.bin/mocha test/` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11879 | `mocha --reporter spec test/*-test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11690 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11214 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10859 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10549 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10131 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10008 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9630 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9540 | `mocha --harmony` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9529 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9415 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9395 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9031 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8763 | `mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8710 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8582 | `mocha test/*-test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 8489 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8256 | `mocha test/test.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 8251 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8236 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8155 | `grunt clean:test && mocha --exit` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8121 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8035 | `./node_modules/.bin/mocha test/src` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8008 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7896 | `mocha --compilers js:babel-register test/test.js` | 
| [amark/gun](https://github.com/amark/gun) | 7893 | `mocha` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7846 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7642 | `npm run eslint && npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7621 | `mocha tests/*.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7482 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7435 | `mocha` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7330 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7329 | `./node_modules/.bin/mocha test` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7268 | `npm run build && istanbul cover _mocha` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7228 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7121 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6798 | `mocha --opts mocha.opts` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6774 | `nyc mocha test/**/* -r ./test/before` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 6706 | `npm run mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6687 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6664 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6650 | `mocha $HARMONY_OPTS` | 
| [aui/art-template](https://github.com/aui/art-template) | 6649 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6628 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6624 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [almende/vis](https://github.com/almende/vis) | 6499 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6251 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6077 | `npm run lint -s && npm run mocha -s` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6012 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6009 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5996 | `npm run test:mocha:src` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5935 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5918 | `npm run jshint && mocha test/` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5727 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5658 | `mocha test --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5618 | `mocha tests/node.js` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5569 | `mocha test/test.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5519 | `mocha && eslint lib/**` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 5505 | `npm run build-cli && mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5488 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5484 | `mocha --exit --require babel-core/register` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5399 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5336 | `mocha` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5211 | `mocha --timeout 10000 && npm run lint` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5182 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5161 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5150 | `mocha src/**/*Tests.js --harmony` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4990 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 4947 | `mocha; jshint *.js lib` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4831 | `gulp lint && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4823 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4807 | `mocha` | 
| [redux-utilities/redux-actions](https://github.com/redux-utilities/redux-actions) | 4784 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4771 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4707 | `standard && mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 4687 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [santinic/how2](https://github.com/santinic/how2) | 4680 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4661 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4646 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4574 | `gulp build; mocha;` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4573 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4546 | `mocha ./test/runner.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4500 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4491 | `mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4425 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4399 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4368 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4333 | `mocha test` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4311 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4283 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4267 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4224 | `mocha -R spec ./test --recursive` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4077 | `mocha --recursive && make test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4054 | `nyc mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4018 | `NODE_ENV=test mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3936 | `npm run lint && npm run mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3934 | `mocha --require test/babel-hook test/*.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3929 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [muicss/mui](https://github.com/muicss/mui) | 3919 | `mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3891 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3861 | `export TESTING=true; mocha --reporter list` | 
| [tj/ejs](https://github.com/tj/ejs) | 3835 | `mocha --require should --reporter spec` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3834 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3818 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [erming/shout](https://github.com/erming/shout) | 3814 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3788 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3781 | `nyc mocha` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3734 | `npm run lint ; mocha && mocha test/individual` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3687 | `mocha ./test/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3658 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3652 | `npm run jshint && npm run mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3631 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3597 | `standard && mocha --timeout 60000 test/test.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3584 | `npm run lint && npm run mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3563 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3557 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3552 | `mocha tests/javascript` | 
| [primus/primus](https://github.com/primus/primus) | 3530 | `npm run build && mocha test/*.test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3480 | `mocha --reporter spec --timeout 3000` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3450 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3442 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3437 | `node_modules/.bin/mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3430 | `mocha --check-leaks --reporter spec --bail` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3420 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3409 | `mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3406 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3305 | `nyc mocha "test/**/*.test.js"` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3299 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3294 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3271 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3248 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3213 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3185 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3133 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3118 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3102 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3095 | `./node_modules/.bin/mocha test/test.*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3094 | `node_modules/.bin/mocha test/tests.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3085 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3043 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3030 | `mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2988 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 2986 | `NODE_ENV=test mocha test/**/*.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2979 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2954 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2941 | `nyc mocha && tsc` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2931 | `mocha test/*.js` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2919 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2903 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2879 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2862 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 2852 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2847 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2823 | `mocha test/index.js && npm run demo` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2820 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2812 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2810 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2809 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2807 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2806 | `mocha -R spec --recursive src/test` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2783 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2765 | `mocha --require should --reporter spec` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2761 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2761 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2760 | `NODE_ENV=test mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2759 | `istanbul cover _mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2754 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2738 | `mocha` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2734 | `mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2726 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2725 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2712 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2697 | `mocha --opts mocha.opts` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2686 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [tj/should.js](https://github.com/tj/should.js) | 2684 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2657 | `xo && mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2657 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2630 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2626 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [css/csso](https://github.com/css/csso) | 2622 | `mocha --reporter dot` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2619 | `npm run mocha && npm run lint` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2608 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2605 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2604 | `mocha --timeout 100000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2595 | `mocha-phantomjs ./test/index.html` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2591 | `mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2587 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2587 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2586 | `mocha --compilers js:babel-register --recursive spec` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2576 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2551 | `mocha --recursive --watch` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2527 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2523 | `export TESTING=true; mocha --reporter list` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2503 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2470 | `node_modules/.bin/mocha --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2452 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2444 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2441 | `mocha --reporter=spec test/*-test.js` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2441 | `export TESTING=true; mocha --reporter list` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2431 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2421 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2420 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2395 | `npm run build && cd test && mocha . --reporter dot` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2387 | `nyc mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2370 | `node node_modules/mocha/bin/_mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2361 | `mocha` | 
| [json5/json5](https://github.com/json5/json5) | 2351 | `nyc --reporter=html --reporter=text mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2350 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2340 | `mocha test` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2337 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2335 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2334 | `grunt jshint && mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2326 | `mocha --require should --reporter spec` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2311 | `mocha "test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2295 | `mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2278 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2273 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2270 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2256 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2254 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2235 | `mocha test test/unit/**/*_test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2233 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2229 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2221 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2221 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2219 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2208 | `mocha -R spec` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2207 | `mocha test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2206 | `mocha -R landing test/index` | 
| [gajus/swing](https://github.com/gajus/swing) | 2162 | `mocha --compilers js:babel-register` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2146 | `nyc --reporter=html --reporter=text mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2093 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2087 | `cross-env BABEL_ENV=test mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2072 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2072 | `mocha && eslint .` | 
| [noble/noble](https://github.com/noble/noble) | 2070 | `mocha -R spec test/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2067 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2059 | `mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2048 | `mocha test && npm run lint` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2036 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [slate/slate](https://github.com/slate/slate) | 2010 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1994 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1967 | `standard && mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1953 | `mocha --compilers js:babel-register` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1943 | `mocha -c test/index.js` | 
| [Qix-/color](https://github.com/Qix-/color) | 1939 | `mocha` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1937 | `mocha --require=test/test_helper.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1910 | `mocha test/index.js --reporter dot` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1906 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1905 | `mocha --bail --reporter spec --check-leaks test/` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1903 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1902 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1901 | `mocha test/runner.js --reporter spec` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1876 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1869 | `mocha --require ./test/common --growl test/expect.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1867 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1866 | `mocha --reporter spec --timeout 5000` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1860 | `mocha tests.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1859 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1833 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1830 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1821 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [then/promise](https://github.com/then/promise) | 1821 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1815 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1812 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1798 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1798 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1794 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1792 | `mocha && eslint *.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1782 | `npm run lint && mocha -R dot && npm run cover` | 
| [share/sharedb](https://github.com/share/sharedb) | 1782 | `./node_modules/.bin/mocha && npm run jshint` | 
| [kach/nearley](https://github.com/kach/nearley) | 1782 | `mocha test/*.test.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1769 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1766 | `mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1765 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1765 | `mocha test` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1752 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1751 | `nyc npm run _mocha` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1749 | `npm run lint && mocha --reporter spec test/*.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1744 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1742 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1739 | `mocha --reporter spec && npm run test-typescript` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1735 | `mocha test/**/*_test.js --bail` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1730 | `mocha test` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1728 | `mocha -R spec spec spec/reporters` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1726 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1723 | `rm -rf ./dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1722 | `npm run mocha && npm run karma` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1712 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1709 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1697 | `mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1695 | `eslint . && mocha -t 5000` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1695 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1678 | `npm run lint && npm run mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1677 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1676 | `mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1673 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1673 | `xo && mocha` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1662 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1661 | `mocha && npm run lint` | 
| [pahen/madge](https://github.com/pahen/madge) | 1657 | `npm run lint && npm run mocha` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1649 | `mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1640 | `mocha --reporter spec --grep .` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1637 | `mocha tests --compilers js:babel-core/register` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1621 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1618 | `mocha tests/test.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1615 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1612 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1610 | `mocha test/*.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1610 | `mocha --reporter spec test/*.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1608 | `mocha test -u bdd -R spec` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1608 | `standard "src/*.js" && npm run build && mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1605 | `mocha test/**/*.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1603 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1602 | `npm run lint && mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1591 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1586 | `mocha test --timeout 600000` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1585 | `mocha ./test/basic.js -t 5000` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1581 | `mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1581 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1569 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1559 | `mocha spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1539 | `npm run lint && npm run mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1528 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1522 | `mocha --compilers js:babel-register` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1513 | `./node_modules/mocha/bin/mocha -R spec` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1507 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1504 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1504 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1493 | `npm run test:lint && npm run test:mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1488 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1485 | `mocha --reporter spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1479 | `mocha -u tdd` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1471 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1469 | `mocha -R spec` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1463 | `node_modules/.bin/mocha --recursive` | 
| [teambit/bit](https://github.com/teambit/bit) | 1459 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1449 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1448 | `eslint --cache . && tsc && mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1444 | `mocha test/tests.js --timeout=10000` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1444 | `mocha test/**/*.spec.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1437 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1434 | `mocha --check-leaks -R dot` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1429 | `nyc mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1429 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1429 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1424 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1417 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1415 | `standard "./src/*.js" && mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1414 | `mocha test.js` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1414 | `mocha test.js` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1411 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1405 | `mocha tests.js` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1404 | `mocha compiled_tests/` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1392 | `mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1390 | `mocha --recursive` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1384 | `mocha --check-leaks --reporter spec --bail` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1382 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1376 | `mocha test/setup.js test/spec/*.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1368 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1360 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1357 | `./node_modules/mocha/bin/mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1353 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1352 | `nyc npm run mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1339 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1334 | `cross-env NODE_ENV=test nyc mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1325 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1321 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1318 | `mocha -R spec test/*.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1307 | `npm run build && mocha -r should` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1292 | `mocha-phantomjs tests/index.html` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1286 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1281 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1281 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1279 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1277 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1269 | `./node_modules/.bin/mocha test` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1268 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1260 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1260 | `mocha spec/exec.js` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1254 | `istanbul cover _mocha test -- --timeout 20000` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1248 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1238 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1238 | `mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1235 | `mocha --recursive` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1233 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1231 | `mocha test/*.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1226 | `mocha --opts test/opts/mocha.opts` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1222 | `mocha tests` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1222 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1205 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1204 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1203 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1203 | `mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1201 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1200 | `mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1199 | `mocha test` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1193 | `mocha test/**/*Spec.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1193 | `mocha test/unit` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1187 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1184 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1183 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1182 | `node ./node_modules/mocha/bin/mocha tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1180 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1179 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1178 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1178 | `standard && istanbul cover _mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1178 | `eslint src && mocha && karma start --single-run` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1177 | `mocha test` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1176 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1173 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1168 | `mocha --reporter dot` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1166 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1166 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1163 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1162 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1150 | `nyc mocha --timeout=20000 test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1145 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1143 | `node_modules/.bin/mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1141 | `mocha --reporter spec` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1140 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1137 | `mocha src/test.js` | 
| [variety/variety](https://github.com/variety/variety) | 1133 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1132 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1132 | `npm run lint && npm run mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1131 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1124 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1123 | `mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1119 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1114 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1112 | `mocha tests/test-*` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1112 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1103 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1098 | `mocha --check-leaks --reporter spec --bail test/` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1096 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1096 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1096 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1094 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1092 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1089 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1081 | `mocha test/*` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1080 | `mocha $(find test -name '*.test.js')` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1078 | `mocha` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1077 | `nodeunit test; mocha test` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1075 | `xo && mocha` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1072 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1069 | `mocha --compilers js:babel-register` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1068 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1063 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1059 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1049 | `npm run prepublishOnly && mocha test/test.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1048 | `NODE_PATH=. mocha **/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1045 | `istanbul cover _mocha test/*.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1041 | `mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1041 | `mocha --reporter spec --timeout 3000` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1040 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1040 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1039 | `istanbul test _mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1037 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1029 | `mocha -R spec ./test/unit/**` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1028 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1026 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1023 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [jas/playground](https://github.com/jas/playground) | 1023 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1022 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1021 | `mocha test/tests.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1018 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1015 | `mocha --check-leaks -R dot` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1014 | `mocha --recursive test` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1011 | `mocha` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1007 | `mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1007 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1006 | `npm run lint && npm run mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1004 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1004 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1001 | `mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1000 | `mocha --compilers js:babel-core/register` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 997 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 996 | `mocha tests/*.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 995 | `mocha --recursive --bail --reporter spec test` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 995 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 994 | `standard && mocha` | 
| [router5/router5](https://github.com/router5/router5) | 992 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 988 | `mocha ./test/test*.js --reporter spec` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 987 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 979 | `mocha $(find test -name '*.test.js')` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 978 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 977 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 975 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 971 | `webpack && mocha test/unit` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 970 | `npm run rollup-cjs && mocha test/test.js` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 970 | `mocha -t 120000 test/*.test.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 967 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [electron/asar](https://github.com/electron/asar) | 967 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 964 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 963 | `mocha --recursive test/unit/` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 962 | `mocha -R list` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 961 | `mocha --async-only` | 
| [tomas/needle](https://github.com/tomas/needle) | 961 | `mocha test` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 960 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 955 | `mocha --reporter spec --bail --check-leaks test/` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 955 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 953 | `standard && mocha -b` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 951 | `mocha --reporter spec --bail --check-leaks test/` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 949 | `mocha --timeout 5000` | 
| [electron/spectron](https://github.com/electron/spectron) | 948 | `mocha && standard` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 948 | `mocha --reporter spec` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 946 | `npm run lint && npm run mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 943 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 938 | `eslint src test && mocha --compilers babel-register` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 936 | `mocha` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 925 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 924 | `TEST=all mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 923 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 922 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 919 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 917 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 911 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 909 | `npm run lint && mocha --require @babel/register` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 906 | `mocha "client.test" --compilers js:babel-register` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 905 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 905 | `mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 893 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 889 | `mocha ./test -R spec` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 886 | `mocha --compilers js:babel-register test/*.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 885 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 884 | `mocha --reporter spec --bail --check-leaks test/` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 881 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 881 | `npm run convertto:es5 && npm run mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 879 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 877 | `mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 872 | `npm run lint && mocha -R spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 870 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 870 | `mocha --reporter list` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 869 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 867 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 867 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 864 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 859 | `mocha -R spec` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 859 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 858 | `mocha tests` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 858 | `mocha --timeout 20000` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 857 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 855 | `node_modules/.bin/mocha` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 851 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 849 | `npm run lint && npm run mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 847 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 845 | `mocha --timeout 200000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 845 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 845 | `mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 844 | `node_modules/.bin/mocha test/spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 843 | `npm run mocha:istanbul` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 843 | `eslint test && mocha --compilers js:babel/register` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 834 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 832 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 824 | `mocha -t 600000` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 822 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 819 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 819 | `istanbul cover _mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 819 | `mocha --check-leaks -t 20000` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 817 | `mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 816 | `standard && standard ./bin/* && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 815 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 815 | `mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 814 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 810 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 807 | `nyc mocha specs` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 807 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 806 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 805 | `mocha -t 5000` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 804 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 799 | `mocha test --compilers js:babel-register` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 798 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 798 | `mocha --require babel-register` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 795 | `mocha --reporter spec --bail --check-leaks test/` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 795 | `istanbul cover -- _mocha --reporter spec` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 792 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 791 | `./node_modules/.bin/mocha -R spec` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 790 | `mocha spec/*.js` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 789 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 788 | `cake build && mocha ./test/mocha/*.coffee` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 786 | `mocha --reporter list` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 785 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 783 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [edsu/anon](https://github.com/edsu/anon) | 778 | `mocha --colors --reporter spec test.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 777 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 777 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 776 | `mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 772 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 772 | `mocha --async-only` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 770 | `xo && mocha -R spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 768 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 768 | `npm run lint && mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 768 | `mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 762 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 760 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 756 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 753 | `mocha --ui tdd --require ./test/__setup` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 753 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 751 | `mocha -R spec src/**/*_test.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 747 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 745 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 743 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [radi-js/radi](https://github.com/radi-js/radi) | 743 | `nyc mocha` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 742 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 739 | `npm run mocha-test test/integration` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 736 | `mocha --recursive -s 15 test/` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 735 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 734 | `mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 734 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 732 | `mocha test` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 731 | `mocha --reporter spec` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 730 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 730 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 728 | `mocha test --compilers js:babel-core/register` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 727 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 726 | `mocha test.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 723 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 721 | `mocha test` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 721 | `npm run build && istanbul test _mocha test/test.js` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 720 | `nyc --check-coverage mocha test/*.test.js` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 720 | `mocha` | 
| [developit/decko](https://github.com/developit/decko) | 719 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 719 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 717 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 717 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 717 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 714 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 714 | `mocha tests/*.mocha.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 714 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 714 | `mocha --harmony --full-trace --check-leaks` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 714 | `mocha test` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 714 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 714 | `./node_modules/.bin/mocha --reporter spec` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 713 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 713 | `mocha` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 712 | `npm run bundle && mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 712 | `mocha --reporter list test/cli/index test/daemon/index` | 