# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:44 05/06/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 41201 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40429 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38137 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29377 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23891 | `npm run lint && npm run mocha-node-test` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 22020 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 21937 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 18620 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18194 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16113 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15601 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14055 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14047 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13256 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12578 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12350 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12154 | `./node_modules/.bin/mocha test/` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12115 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11963 | `mocha --reporter spec test/*-test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11938 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11484 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10983 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10733 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10300 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10179 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9775 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9610 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9609 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9529 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9500 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9091 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8761 | `grunt mocha` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 8685 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8677 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 8458 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8279 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8262 | `mocha --check-leaks -R dot` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8210 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8184 | `grunt clean:test && mocha --exit` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8181 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8104 | `mocha test/src` | 
| [amark/gun](https://github.com/amark/gun) | 7999 | `mocha` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7961 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7890 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7803 | `mocha tests/*.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7695 | `npm run eslint && npm run mocha` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6419 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6196 | `npm run lint -s && npm run mocha -s` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6037 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6018 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5932 | `mocha` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 5776 | `npm run build-cli && mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5774 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5751 | `mocha test --recursive` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5695 | `mocha test/test.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5664 | `mocha tests/node.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5642 | `mocha --exit --require babel-core/register` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5556 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5533 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5423 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5403 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6419 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6196 | `npm run lint -s && npm run mocha -s` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6056 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6037 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6036 | `npm run jshint && mocha test/` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6018 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5932 | `mocha` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 5776 | `npm run build-cli && mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5774 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5751 | `mocha test --recursive` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5695 | `mocha test/test.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5664 | `mocha tests/node.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5642 | `mocha --exit --require babel-core/register` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5556 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5533 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5423 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5403 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5272 | `mocha; jshint *.js lib` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5263 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5241 | `mocha --timeout 10000 && npm run lint` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5161 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5152 | `mocha src/**/*Tests.js --harmony` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5095 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5029 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4880 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4867 | `gulp lint && mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 4845 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4823 | `standard && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4794 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4720 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [santinic/how2](https://github.com/santinic/how2) | 4702 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4673 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4656 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4604 | `gulp build; mocha;` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4557 | `mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4548 | `mocha ./test/runner.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4541 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4476 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4452 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4412 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4390 | `mocha test` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4317 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4311 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4294 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4223 | `mocha -R spec ./test --recursive` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4135 | `mocha --recursive && make test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4094 | `NODE_ENV=test mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4072 | `nyc mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4037 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4010 | `npm run lint && npm run mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4006 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3957 | `mocha --require test/babel-hook test/*.js` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3957 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3888 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3869 | `nyc mocha` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3862 | `export TESTING=true; mocha --reporter list` | 
| [tj/ejs](https://github.com/tj/ejs) | 3860 | `mocha --require should --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3858 | `mocha -R spec ./test` | 
| [erming/shout](https://github.com/erming/shout) | 3807 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3792 | `npm run lint ; mocha && mocha test/individual` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3734 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3708 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3696 | `npm run lint && npm run mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3694 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3678 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3658 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3614 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3561 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [primus/primus](https://github.com/primus/primus) | 3560 | `npm run build && mocha test/*.test.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3555 | `mocha tests/javascript` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3499 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3493 | `mocha --check-leaks --reporter spec --bail` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3486 | `mocha --reporter spec --timeout 3000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3457 | `node_modules/.bin/mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3445 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3346 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3343 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3309 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3304 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3299 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3219 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3188 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3105 | `mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3105 | `node_modules/.bin/mocha test/tests.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3104 | `./node_modules/.bin/mocha test/test.*.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3098 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3105 | `mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3105 | `node_modules/.bin/mocha test/tests.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3104 | `./node_modules/.bin/mocha test/test.*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3099 | `mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3098 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3075 | `NODE_ENV=test mocha test/**/*.js` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3053 | `mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3015 | `nyc mocha && tsc` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2997 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 2991 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2970 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2952 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2949 | `mocha test/*.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2949 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2941 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2919 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2871 | `mocha test/index.js && npm run demo` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2941 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2919 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2871 | `mocha test/index.js && npm run demo` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2852 | `NODE_ENV=test mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2850 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2849 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2832 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2823 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2820 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2814 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2813 | `mocha -R spec --recursive src/test` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2800 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2799 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2786 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2775 | `istanbul cover _mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2771 | `mocha --require should --reporter spec` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2767 | `mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2683 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2676 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2668 | `xo && mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2657 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2656 | `mocha` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2653 | `npm run mocha && npm run lint` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2648 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [css/csso](https://github.com/css/csso) | 2646 | `mocha --reporter dot` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2642 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2634 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2624 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2619 | `mocha --require babel-register --recursive spec` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2614 | `mocha --timeout 100000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2596 | `mocha-phantomjs ./test/index.html` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2569 | `mocha --recursive --watch` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2560 | `export TESTING=true; mocha --reporter list` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2537 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2527 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2526 | `export TESTING=true; mocha --reporter list` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2519 | `node_modules/.bin/mocha --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2503 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2473 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2458 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2454 | `mocha --reporter=spec test/*-test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2433 | `npm run build && cd test && mocha . --reporter dot` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2422 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2410 | `nyc mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2399 | `mocha -R landing test/index` | 
| [json5/json5](https://github.com/json5/json5) | 2390 | `nyc --reporter=html --reporter=text mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2387 | `mocha --require should --reporter spec` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2433 | `npm run build && cd test && mocha . --reporter dot` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2422 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2410 | `nyc mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2399 | `mocha -R landing test/index` | 
| [json5/json5](https://github.com/json5/json5) | 2390 | `nyc --reporter=html --reporter=text mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2387 | `mocha --require should --reporter spec` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2374 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2370 | `mocha test/src/**/*.unit.js` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2360 | `mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2347 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2345 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2344 | `mocha "test/**/*-test.js"` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2339 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2339 | `grunt jshint && mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2299 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2297 | `mocha test/unit --require mochahook` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2234 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2227 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2222 | `mocha -R spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2178 | `nyc --reporter=html --reporter=text mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2107 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2107 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2106 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2103 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2102 | `mocha test && npm run lint` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2098 | `cross-env BABEL_ENV=test mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2092 | `mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2090 | `mocha -R spec test/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2074 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2072 | `mocha` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1943 | `mocha --require=test/test_helper.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1943 | `mocha test/runner.js --reporter spec` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1942 | `eslint . && mocha -t 5000` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1927 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1918 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1915 | `mocha test/index.js --reporter dot` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1911 | `mocha --bail --reporter spec --check-leaks test/` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1910 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1908 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1900 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1886 | `mocha --reporter spec --timeout 5000` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1883 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1882 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1874 | `mocha --require ./test/common --growl test/expect.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1867 | `mocha --compilers js:babel-core/register __tests__` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1863 | `mocha tests.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1853 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1847 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1847 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [then/promise](https://github.com/then/promise) | 1830 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [share/sharedb](https://github.com/share/sharedb) | 1823 | `./node_modules/.bin/mocha && npm run jshint` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1820 | `mocha && eslint *.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1815 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1813 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [kach/nearley](https://github.com/kach/nearley) | 1812 | `mocha test/*.test.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1810 | `npm run lint && mocha -R dot && npm run cover` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1808 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1801 | `mocha --timeout 5000` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1798 | `nyc npm run _mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1795 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1781 | `mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1773 | `mocha test` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1771 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1770 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1770 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1756 | `npm run lint && mocha --reporter spec test/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1753 | `mocha --reporter spec && npm run test-typescript` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1743 | `mocha -R spec spec spec/reporters` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1743 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1742 | `mocha` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1740 | `mocha test` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1739 | `npm run mocha && npm run karma` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1736 | `mocha test/**/*_test.js --bail` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1725 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1715 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1712 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1700 | `mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 1696 | `npm run lint && npm run mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 1695 | `mocha --compilers js:babel-core/register './specs/**/*.spec.js'` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1692 | `npm run jshint && mocha --recursive` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1690 | `npm run lint && npm run mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1685 | `./node_modules/.bin/mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1685 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1683 | `mocha && npm run lint` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1679 | `mocha` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1676 | `standard "src/*.js" && npm run build && mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1674 | `xo && mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1671 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1668 | `mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1659 | `mocha --reporter spec test/*.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1658 | `mocha tests --compilers js:babel-core/register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1646 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1631 | `mocha test -u bdd -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1628 | `mocha test/**/*.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1625 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1623 | `mocha --expose-gc --slow 300` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1622 | `mocha ./test/basic.js -t 5000` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1620 | `mocha test/*.js` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1617 | `mocha tests/test.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1607 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1607 | `npm run lint && mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1604 | `mocha test --timeout 600000` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1603 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1595 | `mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1583 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1578 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1569 | `mocha spec` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1563 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1560 | `npm run lint && npm run mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1550 | `mocha --compilers js:babel-register` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1534 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1521 | `./node_modules/mocha/bin/mocha -R spec` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1512 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [samccone/drool](https://github.com/samccone/drool) | 1447 | `mocha test/tests.js --timeout=10000` | 
| [zeit/ms](https://github.com/zeit/ms) | 1446 | `mocha tests.js` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1443 | `nyc mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1441 | `standard "./src/*.js" && mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1441 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1441 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1438 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1437 | `mocha` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1436 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [AlloyTeam/omi](https://github.com/AlloyTeam/omi) | 1431 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1416 | `mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1415 | `mocha test.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1406 | `mocha --check-leaks --reporter spec --bail` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1394 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1453 | `mocha --check-leaks -R dot` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1448 | `mocha test/**/*.spec.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1447 | `mocha test/tests.js --timeout=10000` | 
| [zeit/ms](https://github.com/zeit/ms) | 1446 | `mocha tests.js` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1446 | `mocha compiled_tests/` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1443 | `nyc mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1441 | `standard "./src/*.js" && mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1441 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1441 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1438 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1437 | `mocha` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1436 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [AlloyTeam/omi](https://github.com/AlloyTeam/omi) | 1431 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1427 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1416 | `mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1415 | `mocha test.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1411 | `mocha test/setup.js test/spec/*.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1406 | `mocha --check-leaks --reporter spec --bail` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1404 | `mocha --recursive` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1394 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1389 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1385 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1385 | `nyc npm run mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1376 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1360 | `./node_modules/mocha/bin/mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1344 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1341 | `cross-env NODE_ENV=test nyc mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1338 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1336 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1331 | `mocha -R spec test/*.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1325 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1317 | `npm run build && mocha -r should` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1298 | `mocha-phantomjs tests/index.html` | 
| [electron/devtron](https://github.com/electron/devtron) | 1296 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1294 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1290 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1290 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1281 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1276 | `./node_modules/.bin/mocha test` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1272 | `mocha spec/exec.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1266 | `mocha test` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1264 | `istanbul cover _mocha test -- --timeout 20000` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1264 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1262 | `mocha --check-leaks --require @babel/register` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1259 | `mocha --recursive` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1258 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1255 | `mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1243 | `mocha --opts test/opts/mocha.opts` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1233 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1233 | `mocha test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1229 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1229 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1228 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1226 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1224 | `mocha tests` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1223 | `mocha test/unit` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1213 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1213 | `mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1212 | `mocha test/test.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1206 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1205 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1205 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1204 | `eslint src && mocha && karma start --single-run` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1203 | `nyc mocha --timeout=20000 test.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1204 | `eslint src && mocha && karma start --single-run` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1203 | `nyc mocha --timeout=20000 test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1201 | `standard && istanbul cover _mocha` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1200 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1199 | `mocha test/**/*Spec.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1194 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1193 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1192 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1192 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1189 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1188 | `mocha --reporter dot` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1184 | `node ./node_modules/mocha/bin/mocha tests` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1180 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1178 | `mocha test` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1175 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1171 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1168 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1157 | `mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1156 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1155 | `mocha tests/test-*` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1154 | `mocha src/test.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1152 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [normalize/mz](https://github.com/normalize/mz) | 1152 | `mocha --reporter spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1147 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [variety/variety](https://github.com/variety/variety) | 1145 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1138 | `npm run lint && npm run mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1136 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1132 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1129 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1128 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1125 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1122 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1119 | `mocha --check-leaks --reporter spec --bail test/` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1118 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1111 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1105 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1102 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1099 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1097 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1094 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1085 | `xo && mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1083 | `mocha $(find test -name '*.test.js')` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1082 | `mocha test/*` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1082 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1080 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1079 | `mocha -R spec ./test/unit/**` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1077 | `nodeunit test; mocha test` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1076 | `npm run prepublishOnly && mocha test/test.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1073 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1071 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1070 | `mocha --compilers js:babel-register` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1069 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1067 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1067 | `mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1067 | `NODE_PATH=. mocha **/*.spec.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1059 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1059 | `istanbul cover _mocha test/*.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1053 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1048 | `mocha --recursive test` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1044 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1042 | `mocha ./test/test*.js --reporter spec` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1041 | `istanbul test _mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1040 | `mocha tests/*.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1040 | `mocha --reporter spec --timeout 3000` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1038 | `npm run lint && npm run mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1036 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1030 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1029 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1028 | `mocha test/tests.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1025 | `mocha --compilers js:babel-core/register` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1024 | `mocha` | 
| [jas/playground](https://github.com/jas/playground) | 1022 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1021 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1020 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1020 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1018 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1014 | `mocha --check-leaks -R dot` | 
| [router5/router5](https://github.com/router5/router5) | 1011 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1009 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1007 | `webpack && npm run lint && npm run mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1007 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1006 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1004 | `mocha --recursive --bail --reporter spec test` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1001 | `standard && mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1000 | `TEST=all mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 998 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 997 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 997 | `mocha --colors ./test/*.spec.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 989 | `webpack && mocha test/unit` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 989 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 988 | `mocha $(find test -name '*.test.js')` | 
| [electron/asar](https://github.com/electron/asar) | 986 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 984 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 980 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 979 | `mocha -t 120000 test/*.test.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 977 | `mocha` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 974 | `mocha --recursive test/unit/` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 974 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 974 | `mocha test` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 973 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 973 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 968 | `mocha --async-only` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 967 | `standard && mocha -b` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 966 | `mocha --reporter spec --bail --check-leaks test/` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 965 | `mocha -R list` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 964 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 958 | `mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 957 | `mocha --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 955 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 954 | `mocha && standard` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 953 | `eslint src test && mocha --compilers babel-register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 949 | `mocha --timeout 5000` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 947 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 944 | `npm run lint && mocha --require @babel/register` | 
| [odota/core](https://github.com/odota/core) | 940 | `NODE_ENV=test mocha --exit` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 930 | `mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 930 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 928 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 921 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 914 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 911 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 911 | `mocha "client.test" --compilers js:babel-register` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 906 | `mocha` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 905 | `mocha ./test -R spec` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 904 | `mocha --timeout 20000` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 902 | `npm run convertto:es5 && npm run mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 902 | `npm run convertto:es5 && npm run mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 898 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 897 | `mocha --compilers js:babel-register test/*.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 894 | `mocha --reporter spec --bail --check-leaks test/` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 894 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 890 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 890 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 890 | `npm-run-all test:jest test:server:mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 885 | `npm run mocha:istanbul` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 883 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 883 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 881 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 881 | `npm run lint && mocha -R spec` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 874 | `mocha -R spec` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 874 | `mocha -R spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 870 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 870 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 868 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 864 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 864 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 862 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 861 | `node_modules/.bin/mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 859 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 855 | `npm run lint && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 851 | `mocha --timeout 200000` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 850 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 849 | `mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 848 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 848 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 847 | `node_modules/.bin/mocha test/spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 846 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 844 | `eslint test && mocha --compilers js:babel/register` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 841 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 839 | `mocha -t 600000` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 839 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 833 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 825 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 825 | `mocha -t 5000` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 825 | `mocha --check-leaks -t 20000` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 824 | `standard && standard ./bin/* && mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 822 | `istanbul cover _mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 820 | `mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 819 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 819 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 819 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [nimiq-network/core](https://github.com/nimiq-network/core) | 815 | `NODE_ENV=test mocha --exit` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 814 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 812 | `nyc mocha specs` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 812 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 812 | `mocha test --compilers js:babel-register` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 812 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 809 | `mocha spec/*.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 807 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 809 | `mocha spec/*.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 807 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 807 | `istanbul cover -- _mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 806 | `./node_modules/.bin/mocha -R spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 801 | `mocha --require babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 800 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 796 | `mocha --reporter spec --bail --check-leaks test/` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 792 | `mocha --reporter list` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 792 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 791 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 790 | `cake build && mocha ./test/mocha/*.coffee` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 790 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 788 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 781 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 780 | `mocha --async-only` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 780 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 779 | `mocha --colors --reporter spec test.js` | 
| [radi-js/radi](https://github.com/radi-js/radi) | 776 | `nyc mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 774 | `npm run lint && mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 771 | `xo && mocha -R spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 770 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 770 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 769 | `mocha` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 767 | `mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 765 | `mocha test --compilers js:babel-core/register` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 764 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 762 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 753 | `mocha -R spec src/**/*_test.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 750 | `npm run mocha-test test/integration` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 750 | `mocha test` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 748 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 747 | `./node_modules/.bin/mocha --reporter spec` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 746 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 743 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 743 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 738 | `mocha --harmony --full-trace --check-leaks` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 738 | `npm run build && istanbul test _mocha test/test.js` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 736 | `mocha --recursive -s 15 test/` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 735 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 735 | `mocha test` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 735 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 735 | `mocha` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 735 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 738 | `mocha --harmony --full-trace --check-leaks` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 738 | `npm run build && istanbul test _mocha test/test.js` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 736 | `mocha --recursive -s 15 test/` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 735 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 735 | `mocha test` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 735 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 735 | `mocha` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 735 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 734 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 733 | `nyc --check-coverage mocha test/*.test.js` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 733 | `mocha` | 
| [developit/decko](https://github.com/developit/decko) | 732 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 731 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 730 | `mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 729 | `mocha --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 728 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 727 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 726 | `mocha test.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 725 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 720 | `mocha --recursive ./test/*_spec.js` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 719 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 718 | `mocha test` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 717 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 716 | `mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 715 | `mocha tests/*.mocha.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 715 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [typicode/katon](https://github.com/typicode/katon) | 712 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 711 | `npm run bundle && mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 708 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 706 | `mocha --no-timeouts` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 706 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 706 | `npm run lint && npm run mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 704 | `mocha test/index.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 703 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 