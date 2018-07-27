# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:03 07/27/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 42958 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41027 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39406 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29961 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 25194 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24377 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23990 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22948 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19517 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18808 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16663 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16403 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14971 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14286 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13827 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13229 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13033 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12601 | `mocha 'test/**/*.spec.js'` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12598 | `./node_modules/.bin/mocha test/` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12256 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12225 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11631 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11406 | `nyc grunt mocha-and-karma` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10981 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10975 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10301 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10001 | `set NODE_ENV=test && mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9998 | `mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9989 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [tj/co](https://github.com/tj/co) | 9967 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9888 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9543 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9429 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9309 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 9210 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9004 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8945 | `grunt mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8892 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8607 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [amark/gun](https://github.com/amark/gun) | 8525 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8478 | `mocha tests/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8456 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8417 | `mocha --check-leaks -R dot` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8388 | `mocha test/src` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8278 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8137 | `mocha --compilers js:babel-register test/test.js` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8037 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8036 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7882 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7818 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7646 | `./node_modules/.bin/mocha test` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7585 | `mocha --opts mocha.opts` | 
| [dthree/cash](https://github.com/dthree/cash) | 7549 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7437 | `mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7435 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7398 | `npm run build && istanbul cover _mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7157 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7121 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7113 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6973 | `xo && mocha test/*.js --timeout 100000` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6923 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [almende/vis](https://github.com/almende/vis) | 6909 | `mocha --compilers js:babel-core/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6861 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6677 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6393 | `npm run jshint && mocha test/` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6227 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6218 | `mocha --exit --require babel-core/register` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6199 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6194 | `npm run test:mocha:src` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6093 | `mocha test/test.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6042 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5944 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5941 | `mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5934 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5847 | `mocha tests/node.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5752 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5691 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5668 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5541 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5531 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5461 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5408 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5378 | `mocha --timeout 10000 && npm run lint` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5047 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4947 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4943 | `gulp lint && mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4906 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4868 | `mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4837 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4720 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4701 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4690 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4570 | `./node_modules/.bin/mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4725 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4725 | `mocha test` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4720 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4701 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4696 | `mocha test` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4690 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4570 | `./node_modules/.bin/mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4567 | `mocha ./test/runner.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4460 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4448 | `mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4428 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4388 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4363 | `nyc mocha --exit` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4356 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4340 | `npm run lint && npm run mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4325 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4214 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4136 | `nyc mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4104 | `npm run lint && npm run mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4091 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4054 | `nyc mocha` | 
| [muicss/mui](https://github.com/muicss/mui) | 4002 | `mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4001 | `node_modules/.bin/mocha test/tests.js` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3995 | `mocha --require test/babel-hook test/*.js` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3982 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3959 | `npm run lint ; mocha && mocha test/individual` | 
| [tj/ejs](https://github.com/tj/ejs) | 3959 | `mocha --require should --reporter spec` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3941 | `mocha --timeout=15000 tests/*.test.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3891 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3880 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3819 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [erming/shout](https://github.com/erming/shout) | 3805 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3778 | `mocha --check-leaks --reporter spec --bail` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3771 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3732 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3683 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3676 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3671 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3655 | `standard && mocha --timeout 60000 test/test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3653 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 3646 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [expressjs/session](https://github.com/expressjs/session) | 3581 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3575 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3563 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3545 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3534 | `mocha --reporter spec --timeout 3000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3533 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3508 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3461 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3455 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3449 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3436 | `mocha` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3430 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3383 | `NODE_ENV=test mocha test/**/*.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3374 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3274 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3204 | `nyc mocha && tsc` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3202 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3196 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3188 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3151 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3140 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3136 | `./node_modules/.bin/mocha test/test.*.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3130 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3124 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3053 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3029 | `mocha test/*.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3023 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3013 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3012 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3151 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3140 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3136 | `./node_modules/.bin/mocha test/test.*.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3130 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3124 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3121 | `mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3089 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3053 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3029 | `mocha test/*.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3023 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3013 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3012 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3004 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 3000 | `export TESTING=true; mocha --reporter list` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2998 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2989 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2981 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2955 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2926 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2909 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2892 | `mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2879 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2874 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2869 | `mocha -R spec --recursive src/test` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2865 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2859 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2848 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2839 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2834 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2834 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2820 | `istanbul cover _mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2810 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2806 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2805 | `mocha --opts mocha.opts` | 
| [github-tools/github](https://github.com/github-tools/github) | 2794 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2783 | `npm run mocha && npm run lint` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2778 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2768 | `mocha --require should --reporter spec` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2530 | `export TESTING=true; mocha --reporter list` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2500 | `eslint . && mocha -t 5000` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2468 | `mocha --reporter=spec test/*-test.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2463 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2443 | `mocha test` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2437 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2428 | `mocha test/src/**/*.unit.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2422 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2414 | `mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2405 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2390 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2373 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2367 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2361 | `mocha --no-colors --reporter spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2609 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2608 | `mocha-phantomjs ./test/index.html` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2607 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2596 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2577 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2571 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2568 | `nyc mocha --timeout=10000` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2567 | `npm run build && cd test && mocha . --reporter dot` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2562 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2530 | `export TESTING=true; mocha --reporter list` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2505 | `nyc mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2500 | `eslint . && mocha -t 5000` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2489 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2485 | `mocha "test/**/*-test.js"` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2468 | `mocha --reporter=spec test/*-test.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2463 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2443 | `mocha test` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2437 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2428 | `mocha test/src/**/*.unit.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2422 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2414 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2414 | `mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2405 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2390 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2373 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2367 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2361 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2346 | `grunt jshint && mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2330 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2304 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2299 | `mocha -R spec` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2295 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2283 | `mocha test && npm run lint` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2273 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2270 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2254 | `mocha test/index.js --reporter dot` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2244 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2230 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2230 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2228 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [gajus/swing](https://github.com/gajus/swing) | 2217 | `mocha --compilers js:babel-register` | 
| [noble/noble](https://github.com/noble/noble) | 2173 | `mocha -R spec test/*.js` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2153 | `mocha test/ --no-timeouts` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2151 | `mocha --compilers js:babel-register` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2136 | `cross-env BABEL_ENV=test mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2106 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2102 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2093 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2092 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [Qix-/color](https://github.com/Qix-/color) | 2089 | `mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2082 | `standard && mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2063 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2038 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2036 | `mocha test/runner.js --reporter spec` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2023 | `mocha -R spec spec spec/reporters` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2019 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [slate/slate](https://github.com/slate/slate) | 2005 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1999 | `nyc npm run _mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1998 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1974 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1965 | `mocha -c test/index.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1952 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1948 | `mocha` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1938 | `mocha --reporter spec --timeout 5000` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1930 | `mocha && eslint *.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1927 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1925 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1922 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [share/sharedb](https://github.com/share/sharedb) | 1918 | `./node_modules/.bin/mocha && npm run jshint` | 
| [then/promise](https://github.com/then/promise) | 1913 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1903 | `npm run lint && mocha -R dot && npm run cover` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1896 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1888 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1857 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1822 | `mocha --reporter spec && npm run test-typescript` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1813 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1791 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1791 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1789 | `npm run lint && mocha --reporter spec test/*.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1785 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1781 | `mocha test` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1779 | `mocha && npm run lint` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1774 | `mocha --reporter spec test/*.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1769 | `mocha tests --compilers js:babel-core/register` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1789 | `npm run lint && mocha --reporter spec test/*.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1785 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1781 | `mocha test` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1779 | `mocha && npm run lint` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1774 | `mocha --reporter spec test/*.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1771 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1769 | `mocha tests --compilers js:babel-core/register` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1766 | `mocha --reporter spec --grep .` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1757 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1752 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1747 | `npm run lint && npm run mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1739 | `mocha test/**/*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1739 | `mocha --compilers js:babel-register` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1732 | `mocha test/**/*_test.js --bail` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1727 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1727 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1724 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1723 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1708 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1700 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1699 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1684 | `npm run lint && mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1675 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1674 | `mocha test --timeout 600000` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1666 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1666 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1651 | `npm run lint && npm run mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1647 | `mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1645 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1583 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1567 | `./node_modules/mocha/bin/mocha -R spec` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1557 | `mocha test/setup.js test/spec/*.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1554 | `eslint --cache . && tsc && mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1551 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1550 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [zeit/ms](https://github.com/zeit/ms) | 1544 | `mocha tests.js` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1537 | `mocha --reporter spec` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1537 | `standard "./src/*.js" && mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1529 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1525 | `mocha test` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1520 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1594 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1590 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1583 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1567 | `./node_modules/mocha/bin/mocha -R spec` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1557 | `mocha test/setup.js test/spec/*.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1554 | `eslint --cache . && tsc && mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1551 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1550 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [zeit/ms](https://github.com/zeit/ms) | 1544 | `mocha tests.js` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1544 | `npm run test:lint && npm run test:mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1249 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1245 | `mocha tests` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1243 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1240 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1238 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1236 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1235 | `NODE_ENV=test mocha tests/*.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1219 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1216 | `mocha --check-leaks --reporter spec --bail test/` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1214 | `mocha src/test.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1211 | `npm run lint && npm run mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1210 | `mocha ./test/test*.js --reporter spec` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1207 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1204 | `istanbul test _mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1203 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1200 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1198 | `mocha test` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1191 | `npm run lint && npm run mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1480 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1469 | `mocha test/**/*.spec.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1467 | `mocha --recursive` | 
| [samccone/drool](https://github.com/samccone/drool) | 1453 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1448 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1441 | `mocha test.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1216 | `mocha --check-leaks --reporter spec --bail test/` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1211 | `npm run lint && npm run mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1210 | `mocha ./test/test*.js --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1208 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1204 | `istanbul test _mocha` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1204 | `mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1203 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1200 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1199 | `node ./node_modules/mocha/bin/mocha tests` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1198 | `mocha test` | 
| [normalize/mz](https://github.com/normalize/mz) | 1193 | `mocha --reporter spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1191 | `npm run lint && npm run mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1187 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1180 | `npm run prepublishOnly && mocha test/test.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1178 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1177 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1173 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1172 | `mocha` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1168 | `mocha --recursive test` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1168 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1168 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1168 | `mocha --recursive test` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1163 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1158 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1154 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1150 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1149 | `mocha --compilers js:babel-core/register` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1145 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1141 | `mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1130 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1129 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1123 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1121 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1119 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1119 | `mocha $(find test -name '*.test.js')` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1114 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1111 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1111 | `xo && mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1108 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1106 | `istanbul cover _mocha test/*.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1104 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1104 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1102 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1102 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1098 | `mocha test/*` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1088 | `mocha --check-leaks -t 20000` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1087 | `npm run lint && mocha --require @babel/register` | 
| [router5/router5](https://github.com/router5/router5) | 1087 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1084 | `webpack && npm run lint && npm run mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1082 | `mocha` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1081 | `standard && mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1079 | `mocha --compilers js:babel-register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1078 | `npm run mocha:istanbul` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1072 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1069 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [electron/asar](https://github.com/electron/asar) | 1062 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1057 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1038 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1038 | `mocha --timeout 20000` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1037 | `mocha --reporter spec --timeout 3000` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1035 | `nyc mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1034 | `mocha --reporter spec --bail --check-leaks test/` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1028 | `standard && mocha -b` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1024 | `mocha` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1023 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1022 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1017 | `eslint src test && mocha --compilers babel-register` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1017 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [tomas/needle](https://github.com/tomas/needle) | 1014 | `mocha test` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1012 | `mocha $(find test -name '*.test.js')` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1012 | `mocha --check-leaks -R dot` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1002 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1000 | `mocha --recursive test/unit/` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 997 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1023 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1022 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [electron/spectron](https://github.com/electron/spectron) | 1017 | `mocha && standard` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1017 | `eslint src test && mocha --compilers babel-register` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1017 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [tomas/needle](https://github.com/tomas/needle) | 1014 | `mocha test` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1012 | `mocha $(find test -name '*.test.js')` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1012 | `mocha --check-leaks -R dot` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1002 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1000 | `mocha --recursive test/unit/` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 997 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 994 | `mocha --async-only` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 993 | `mocha --timeout 30000 --recursive ./tests` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 992 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 950 | `mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 950 | `mocha test --compilers js:babel-core/register` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 944 | `mocha "client.test" --compilers js:babel-register` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 943 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 939 | `mocha -R spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 936 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 932 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 930 | `mocha --compilers js:babel-register test/*.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 930 | `mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 923 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 923 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 921 | `npm run lint && mocha -R spec` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 964 | `npm-run-all test:jest test:server:mocha` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 950 | `mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 950 | `mocha test --compilers js:babel-core/register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 944 | `mocha "client.test" --compilers js:babel-register` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 943 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 939 | `mocha -R spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 936 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 893 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 887 | `mocha -t 600000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 882 | `node_modules/.bin/mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 880 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 879 | `mocha --recursive -r tests/setup tests` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 879 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 870 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 869 | `nyc mocha specs` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 865 | `npm run lint && npm run mocha:no-functional` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 864 | `mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 908 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 907 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 907 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 905 | `mocha tests` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 903 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 898 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 896 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 895 | `mocha spec/*.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 893 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 887 | `mocha -t 600000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 882 | `node_modules/.bin/mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 881 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 880 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 879 | `mocha --recursive -r tests/setup tests` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 879 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 877 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 870 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 869 | `nyc mocha specs` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 868 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 865 | `npm run lint && npm run mocha:no-functional` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 864 | `mocha --timeout 200000` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 864 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 863 | `mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 863 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 858 | `node_modules/.bin/mocha test/spec` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 858 | `mocha -t 5000` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 857 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 857 | `eslint test && mocha --compilers js:babel/register` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 856 | `mocha test` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 856 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 854 | `./node_modules/.bin/mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 852 | `./node_modules/.bin/mocha -R spec` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 852 | `istanbul cover -- _mocha --reporter spec` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 849 | `mocha test --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 848 | `standard && standard ./bin/* && mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 847 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 845 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 838 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 836 | `istanbul cover _mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 835 | `mocha --check-leaks -t 20000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 834 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 834 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 833 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 830 | `npm run lint && mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 829 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 828 | `mocha --reporter list` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 827 | `nyc --check-coverage mocha test/*.test.js` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 826 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 826 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 825 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 823 | `mocha && ember test` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 821 | `nyc mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 815 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 814 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 813 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 812 | `mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 808 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 807 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 805 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 805 | `mocha --require babel-register` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 803 | `cake build && mocha ./test/mocha/*.coffee` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 803 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 801 | `mocha test` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 801 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 799 | `mocha --async-only` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 796 | `mocha -u tdd` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 794 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 791 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 790 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 785 | `mocha --colors --reporter spec test.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 785 | `mocha --harmony --full-trace --check-leaks` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 783 | `npm run mocha-test test/integration` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 781 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 781 | `npm run build && istanbul test _mocha test/test.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 779 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 777 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 776 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 776 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 776 | `xo && mocha -R spec` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 776 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 775 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 773 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 773 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 770 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [developit/decko](https://github.com/developit/decko) | 769 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 768 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 766 | `mocha --ui tdd --require ./test/__setup` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 765 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 768 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 766 | `mocha --ui tdd --require ./test/__setup` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 765 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 762 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 761 | `mocha -R spec src/**/*_test.js` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 758 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 757 | `mocha test` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 754 | `mocha --recursive -s 15 test/` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 754 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 753 | `mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 752 | `mocha --no-timeouts` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 731 | `mocha tests/*.mocha.js` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 730 | `mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 725 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 725 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 723 | `mocha` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 722 | `nyc mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 722 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 722 | `npm run bundle && mocha` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 722 | `babel-node node_modules/.bin/_mocha -- test` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 722 | `mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 721 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 719 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 719 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 718 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 725 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 725 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 723 | `mocha` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 722 | `nyc mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 722 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 722 | `npm run bundle && mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 722 | `mocha` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 722 | `babel-node node_modules/.bin/_mocha -- test` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 721 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 721 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 719 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 719 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 718 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 719 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 719 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 718 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 710 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [typicode/katon](https://github.com/typicode/katon) | 710 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 708 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 708 | `mocha --reporter spec build/test/index.js` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 705 | `mocha` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 704 | `mocha ./test/index.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 704 | `./bin/selenium-standalone install && mocha` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 687 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [koajs/static](https://github.com/koajs/static) | 686 | `mocha --harmony --reporter spec --exit` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 685 | `mocha $(find test -name '*.test.js')` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 685 | `npm run test-mocha && npm run test-karma` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 681 | `mocha` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 676 | `jenkins-mocha ./tests/*.js` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 676 | `mocha --harmony tests/**` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 675 | `mocha` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 674 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 