# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:47 04/21/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 40866 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40272 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 40110 | `npm run mocha` | 
| [expressjs/express](https://github.com/expressjs/express) | 37793 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29254 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23822 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 22921 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 21714 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 21572 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 18476 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18072 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15994 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15483 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13996 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 13870 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13151 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12507 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12300 | `mocha 'test/**/*.spec.js'` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12100 | `mocha` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12068 | `./node_modules/.bin/mocha test/` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11910 | `mocha --reporter spec test/*-test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11786 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11321 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10893 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10599 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10176 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10050 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9677 | `mocha test/index.js` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9569 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tj/co](https://github.com/tj/co) | 9564 | `mocha --harmony` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9460 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9428 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9059 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8813 | `mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8723 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8627 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 8566 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 8325 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8261 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8250 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8159 | `grunt clean:test && mocha --exit` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8143 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8068 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8058 | `./node_modules/.bin/mocha test/src` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7919 | `mocha --compilers js:babel-register test/test.js` | 
| [amark/gun](https://github.com/amark/gun) | 7917 | `mocha` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7864 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7677 | `mocha tests/*.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7667 | `npm run eslint && npm run mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7488 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7433 | `mocha` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7400 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7353 | `./node_modules/.bin/mocha test` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7293 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7274 | `npm run build && istanbul cover _mocha` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7209 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6836 | `mocha --opts mocha.opts` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6828 | `nyc mocha test/**/* -r ./test/before` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 6763 | `npm run mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6728 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 6675 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6675 | `xo && mocha test/*.js --timeout 100000` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6672 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6665 | `mocha $HARMONY_OPTS` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6662 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [almende/vis](https://github.com/almende/vis) | 6522 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6314 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6167 | `npm run lint -s && npm run mocha -s` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6017 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6015 | `npm run test:mocha:src` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6014 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5944 | `npm run jshint && mocha test/` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5933 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5734 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5683 | `mocha test --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5628 | `mocha tests/node.js` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5611 | `mocha test/test.js` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 5596 | `npm run build-cli && mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5542 | `mocha --exit --require babel-core/register` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5532 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5501 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5399 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5360 | `mocha` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5223 | `mocha --timeout 10000 && npm run lint` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5210 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5161 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5152 | `mocha src/**/*Tests.js --harmony` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5066 | `mocha; jshint *.js lib` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5023 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4880 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4857 | `gulp lint && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4839 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [redux-utilities/redux-actions](https://github.com/redux-utilities/redux-actions) | 4806 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4777 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4751 | `standard && mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 4748 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [santinic/how2](https://github.com/santinic/how2) | 4688 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4664 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4653 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4585 | `gulp build; mocha;` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4584 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4546 | `mocha ./test/runner.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4515 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4509 | `mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4432 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4406 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4396 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4356 | `mocha test` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4314 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4299 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4276 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4223 | `mocha -R spec ./test --recursive` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4097 | `mocha --recursive && make test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4057 | `nyc mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4049 | `NODE_ENV=test mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3959 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3958 | `npm run lint && npm run mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3944 | `mocha --require test/babel-hook test/*.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 3924 | `mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3889 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3881 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3867 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3861 | `export TESTING=true; mocha --reporter list` | 
| [tj/ejs](https://github.com/tj/ejs) | 3843 | `mocha --require should --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3815 | `mocha -R spec ./test` | 
| [erming/shout](https://github.com/erming/shout) | 3813 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3808 | `nyc mocha` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3751 | `npm run lint ; mocha && mocha test/individual` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3698 | `mocha ./test/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3666 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3655 | `npm run jshint && npm run mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3653 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3622 | `npm run lint && npm run mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3606 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3604 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3556 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3553 | `mocha tests/javascript` | 
| [primus/primus](https://github.com/primus/primus) | 3542 | `npm run build && mocha test/*.test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3485 | `mocha --reporter spec --timeout 3000` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3472 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3447 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3444 | `mocha --check-leaks --reporter spec --bail` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3442 | `node_modules/.bin/mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3422 | `node_modules/.bin/mocha test/lib/` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3414 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3412 | `mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3321 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3313 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3309 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 3296 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3263 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3244 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3216 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3155 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3152 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3103 | `mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3102 | `node_modules/.bin/mocha test/tests.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3098 | `./node_modules/.bin/mocha test/test.*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3095 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3054 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3038 | `mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3012 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3011 | `NODE_ENV=test mocha test/**/*.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2988 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 2968 | `nyc mocha && tsc` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2957 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2948 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2936 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2911 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2895 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 2892 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2888 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2874 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2850 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2839 | `mocha test/index.js && npm run demo` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2824 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2822 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2812 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2812 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2806 | `mocha -R spec --recursive src/test` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2786 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2782 | `NODE_ENV=test mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2777 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2775 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2770 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2768 | `mocha --require should --reporter spec` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2767 | `istanbul cover _mocha` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2763 | `mocha` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2743 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2731 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2727 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2726 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2705 | `mocha --opts mocha.opts` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2690 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [tj/should.js](https://github.com/tj/should.js) | 2688 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2665 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2659 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2639 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2636 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2629 | `npm run mocha && npm run lint` | 
| [css/csso](https://github.com/css/csso) | 2626 | `mocha --reporter dot` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2621 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2618 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2612 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2609 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2606 | `mocha --timeout 100000` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2600 | `mocha` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2596 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2595 | `mocha-phantomjs ./test/index.html` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2595 | `mocha --compilers js:babel-register --recursive spec` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2554 | `mocha --recursive --watch` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2532 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2524 | `export TESTING=true; mocha --reporter list` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2510 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2488 | `node_modules/.bin/mocha --reporter spec` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2486 | `export TESTING=true; mocha --reporter list` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2476 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2456 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2444 | `mocha --reporter=spec test/*-test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2439 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2434 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2421 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2408 | `npm run build && cd test && mocha . --reporter dot` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2391 | `nyc mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2363 | `mocha` | 
| [json5/json5](https://github.com/json5/json5) | 2363 | `nyc --reporter=html --reporter=text mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2359 | `mocha test/src/**/*.unit.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 2354 | `mocha --require should --reporter spec` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2350 | `mocha test` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2338 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2336 | `grunt jshint && mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2336 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2330 | `mocha -R landing test/index` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2320 | `mocha "test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2308 | `mocha` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2282 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2280 | `mocha test/unit --require mochahook` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2280 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2266 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2258 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2251 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2238 | `mocha test test/unit/**/*_test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2236 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2235 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2232 | `mocha test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2222 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2221 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2214 | `mocha -R spec` | 
| [gajus/swing](https://github.com/gajus/swing) | 2168 | `mocha --compilers js:babel-register` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2162 | `nyc --reporter=html --reporter=text mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2088 | `cross-env BABEL_ENV=test mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2085 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2083 | `mocha && eslint .` | 
| [noble/noble](https://github.com/noble/noble) | 2074 | `mocha -R spec test/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2071 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2068 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2063 | `mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2061 | `mocha test && npm run lint` | 
| [slate/slate](https://github.com/slate/slate) | 2011 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2002 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1975 | `standard && mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1961 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 1949 | `mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1945 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1941 | `mocha --require=test/test_helper.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1914 | `mocha test/runner.js --reporter spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1912 | `mocha test/index.js --reporter dot` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1912 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1909 | `mocha` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1909 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1908 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1904 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1886 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1881 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1875 | `mocha --reporter spec --timeout 5000` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1870 | `mocha --require ./test/common --growl test/expect.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1868 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1860 | `mocha tests.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1842 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1840 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1829 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1828 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1827 | `eslint . && mocha -t 5000` | 
| [then/promise](https://github.com/then/promise) | 1823 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1808 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1802 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1801 | `mocha && eslint *.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1797 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [kach/nearley](https://github.com/kach/nearley) | 1797 | `mocha test/*.test.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1796 | `./node_modules/.bin/mocha && npm run jshint` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1790 | `npm run lint && mocha -R dot && npm run cover` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1781 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1771 | `mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1769 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1767 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1762 | `nyc npm run _mocha` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1756 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1754 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1753 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1750 | `npm run lint && mocha --reporter spec test/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1744 | `mocha --reporter spec && npm run test-typescript` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1736 | `mocha test/**/*_test.js --bail` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1735 | `mocha -R spec spec spec/reporters` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1733 | `mocha test` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1732 | `npm run mocha && npm run karma` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1732 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1727 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1713 | `mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1712 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1710 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1697 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1683 | `npm run lint && npm run mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1679 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1678 | `mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1678 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [pahen/madge](https://github.com/pahen/madge) | 1675 | `npm run lint && npm run mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1673 | `xo && mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1669 | `mocha && npm run lint` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1664 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1655 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1651 | `mocha --reporter spec --grep .` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1649 | `mocha tests --compilers js:babel-core/register` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1632 | `standard "src/*.js" && npm run build && mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1625 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1623 | `mocha --expose-gc --slow 300` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1620 | `mocha test -u bdd -R spec` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1619 | `mocha tests/test.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1617 | `mocha --reporter spec test/*.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1616 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1614 | `mocha test/*.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1613 | `mocha test/**/*.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1604 | `mocha ./test/basic.js -t 5000` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1603 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1601 | `npm run lint && mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1595 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1590 | `mocha test --timeout 600000` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1588 | `mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1581 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1573 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1559 | `mocha spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1542 | `npm run lint && npm run mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1531 | `mocha --compilers js:babel-register` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1529 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1517 | `./node_modules/mocha/bin/mocha -R spec` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1512 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1511 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1505 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1505 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [teambit/bit](https://github.com/teambit/bit) | 1503 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1492 | `npm run test:lint && npm run test:mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1486 | `mocha --reporter spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1482 | `mocha -u tdd` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1481 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1470 | `mocha -R spec` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1464 | `node_modules/.bin/mocha --recursive` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1453 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1453 | `eslint --cache . && tsc && mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1451 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [samccone/drool](https://github.com/samccone/drool) | 1446 | `mocha test/tests.js --timeout=10000` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1446 | `mocha test/**/*.spec.js` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1438 | `mocha --check-leaks -R dot` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1436 | `mocha` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1433 | `nyc mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1432 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1428 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1424 | `mocha test.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1422 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1421 | `standard "./src/*.js" && mocha` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1419 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1416 | `mocha compiled_tests/` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1414 | `mocha test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1412 | `mocha tests.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1402 | `mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1395 | `mocha --recursive` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1393 | `mocha --check-leaks --reporter spec --bail` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1388 | `mocha test/setup.js test/spec/*.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1382 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1374 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1372 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1369 | `nyc npm run mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1364 | `mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1360 | `./node_modules/mocha/bin/mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1338 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1336 | `cross-env NODE_ENV=test nyc mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1325 | `mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1325 | `mocha -R spec test/*.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1324 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1323 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1310 | `npm run build && mocha -r should` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1296 | `mocha-phantomjs tests/index.html` | 
| [electron/devtron](https://github.com/electron/devtron) | 1286 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1285 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1282 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1280 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1274 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1270 | `./node_modules/.bin/mocha test` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1267 | `mocha spec/exec.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1259 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1257 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1255 | `istanbul cover _mocha test -- --timeout 20000` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1245 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1244 | `mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1242 | `mocha --recursive` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1233 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1233 | `mocha test` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1232 | `mocha --opts test/opts/mocha.opts` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1232 | `mocha test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1223 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1222 | `mocha tests` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1211 | `mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1209 | `mocha test/test.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1209 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1208 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1207 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1204 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1203 | `mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1200 | `mocha test/unit` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1199 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1196 | `mocha test/**/*Spec.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1188 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1188 | `eslint src && mocha && karma start --single-run` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1188 | `standard && istanbul cover _mocha` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1187 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1185 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1184 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1183 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1181 | `node ./node_modules/mocha/bin/mocha tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1181 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1179 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1177 | `mocha test` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1177 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1176 | `mocha --reporter dot` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1169 | `nyc mocha --timeout=20000 test.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1169 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1167 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1162 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1149 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1147 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1147 | `node_modules/.bin/mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1143 | `mocha src/test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1142 | `mocha --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1140 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1137 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1137 | `npm run lint && npm run mocha` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1133 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1131 | `mocha` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1126 | `mocha tests/test-*` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1124 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1123 | `mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1122 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1120 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1105 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1104 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1103 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1103 | `mocha --check-leaks --reporter spec --bail test/` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1103 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1097 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1096 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1093 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1085 | `mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1084 | `mocha test/*` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1079 | `mocha $(find test -name '*.test.js')` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1079 | `xo && mocha` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1077 | `nodeunit test; mocha test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1071 | `mocha --compilers js:babel-register` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1070 | `mocha --check-leaks -t 20000` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1068 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1067 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1065 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1057 | `npm run prepublishOnly && mocha test/test.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1053 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1052 | `NODE_PATH=. mocha **/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1049 | `istanbul cover _mocha test/*.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1048 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1047 | `mocha -R spec ./test/unit/**` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1042 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1041 | `mocha --reporter spec --timeout 3000` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1040 | `istanbul test _mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1039 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1035 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1027 | `mocha --recursive test` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1024 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [jas/playground](https://github.com/jas/playground) | 1023 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1023 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1021 | `mocha test/tests.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1015 | `mocha --check-leaks -R dot` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1013 | `mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1013 | `npm run lint && npm run mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1011 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1011 | `mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1010 | `mocha --compilers js:babel-core/register` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1010 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1010 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1007 | `mocha tests/*.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1007 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1001 | `mocha --recursive --bail --reporter spec test` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1001 | `mocha ./test/test*.js --reporter spec` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1001 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 999 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 999 | `mocha --colors ./test/*.spec.js` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 998 | `standard && mocha` | 
| [router5/router5](https://github.com/router5/router5) | 996 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 995 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 985 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 982 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 981 | `mocha $(find test -name '*.test.js')` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 978 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 977 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 976 | `webpack && mocha test/unit` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 975 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 975 | `webpack && npm run lint && npm run mocha` | 
| [electron/asar](https://github.com/electron/asar) | 973 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 972 | `npm run rollup-cjs && mocha test/test.js` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 972 | `mocha -t 120000 test/*.test.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 971 | `mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 971 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 964 | `mocha --recursive test/unit/` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 963 | `mocha --async-only` | 
| [tomas/needle](https://github.com/tomas/needle) | 963 | `mocha test` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 962 | `mocha -R list` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 959 | `nyc mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 956 | `mocha --reporter spec --bail --check-leaks test/` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 956 | `standard && mocha -b` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 954 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 952 | `TEST=all mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 950 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [electron/spectron](https://github.com/electron/spectron) | 949 | `mocha && standard` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 949 | `mocha --timeout 5000` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 948 | `mocha --reporter spec` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 943 | `mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 943 | `eslint src test && mocha --compilers babel-register` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 935 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 934 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 933 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 925 | `mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 923 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 920 | `npm run lint && mocha --require @babel/register` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 918 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 913 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 913 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 907 | `mocha "client.test" --compilers js:babel-register` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 906 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 906 | `mocha` | 
| [reactivestack/cookies](https://github.com/reactivestack/cookies) | 896 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 894 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 893 | `mocha ./test -R spec` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 891 | `./node_modules/.bin/mocha --globals angular,require` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 889 | `mocha --compilers js:babel-register test/*.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 888 | `mocha --reporter spec --bail --check-leaks test/` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 888 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 887 | `npm run convertto:es5 && npm run mocha` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 887 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 886 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 881 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 881 | `npm-run-all test:jest test:mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 880 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 879 | `mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 874 | `npm run lint && mocha -R spec` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 872 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 870 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 870 | `mocha --timeout 20000` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 868 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 862 | `mocha -R spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 861 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 859 | `mocha tests` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 859 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 858 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 856 | `node_modules/.bin/mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 854 | `npm run mocha:istanbul` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 852 | `npm run lint && npm run mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 847 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 847 | `mocha --timeout 200000` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 847 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 846 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 845 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 843 | `eslint test && mocha --compilers js:babel/register` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 835 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 834 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 830 | `mocha -t 600000` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 828 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 825 | `mocha --check-leaks -t 20000` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 822 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 822 | `mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 821 | `istanbul cover _mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 820 | `mocha --reporter spec` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 819 | `standard && standard ./bin/* && mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 816 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 816 | `mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 815 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 815 | `mocha -t 5000` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 812 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 811 | `nyc mocha specs` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 810 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 808 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 806 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 806 | `mocha test --compilers js:babel-register` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 802 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 800 | `istanbul cover -- _mocha --reporter spec` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 799 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 799 | `mocha --require babel-register` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 797 | `./node_modules/.bin/mocha -R spec` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 796 | `nyc mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 794 | `mocha spec/*.js` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 789 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 788 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 788 | `cake build && mocha ./test/mocha/*.coffee` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 788 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 785 | `mocha --reporter list` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 784 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 780 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 779 | `mocha --colors --reporter spec test.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 779 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 776 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 774 | `mocha --async-only` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 770 | `xo && mocha -R spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 769 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 769 | `npm run lint && mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 769 | `mocha` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 768 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [radi-js/radi](https://github.com/radi-js/radi) | 764 | `nyc mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 763 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 759 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 756 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 754 | `mocha --ui tdd --require ./test/__setup` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 751 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 751 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 751 | `mocha -R spec src/**/*_test.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 748 | `mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 745 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 744 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 743 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 741 | `npm run mocha-test test/integration` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 740 | `mocha test` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 736 | `mocha --recursive -s 15 test/` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 736 | `mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 734 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 734 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 733 | `mocha test --compilers js:babel-core/register` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 733 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 730 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 730 | `mocha --reporter spec` | 
| [developit/decko](https://github.com/developit/decko) | 728 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 727 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 727 | `mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 726 | `nyc --check-coverage mocha test/*.test.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 726 | `npm run build && istanbul test _mocha test/test.js` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 726 | `mocha test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 725 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 725 | `./node_modules/.bin/mocha --reporter spec` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 725 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 722 | `mocha test` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 721 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 720 | `mocha --harmony --full-trace --check-leaks` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 720 | `mocha test` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 720 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 720 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 717 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 