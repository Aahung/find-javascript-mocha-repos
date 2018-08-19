# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:44 08/19/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43218 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41142 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39730 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30129 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 25839 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24487 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23208 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19773 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18977 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16803 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16576 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15203 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14329 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13970 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13504 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13146 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12721 | `./node_modules/.bin/mocha test/` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12643 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12321 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12238 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11814 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11491 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11189 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11157 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10459 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10140 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10115 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10109 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10030 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9960 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9678 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9638 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9383 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 9359 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9110 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9064 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8999 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8725 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8709 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8671 | `mocha tests/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8496 | `mocha test/test.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8468 | `mocha test/src` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8439 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8318 | `grunt clean:test && mocha --exit` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8286 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8171 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8065 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7993 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7897 | `npm run eslint && npm run mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7817 | `mocha --opts mocha.opts` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7709 | `./node_modules/.bin/mocha test` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7599 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [dthree/cash](https://github.com/dthree/cash) | 7554 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7438 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7427 | `npm run build && istanbul cover _mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7238 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7222 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7213 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7046 | `xo && mocha test/*.js --timeout 100000` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7046 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [almende/vis](https://github.com/almende/vis) | 6995 | `mocha --compilers js:babel-core/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6887 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6868 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6694 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6458 | `npm run jshint && mocha test/` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6457 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6373 | `mocha --exit --require babel-core/register` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6259 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6221 | `npm run test:mocha:src` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6216 | `mocha test/test.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6201 | `mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6051 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5970 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5933 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5912 | `mocha tests/node.js` | 
| [shipshapecode/shepherd](https://github.com/shipshapecode/shepherd) | 5824 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5813 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5722 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5703 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5642 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5635 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5620 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5412 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5336 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5299 | `standard && mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5217 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5178 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5148 | `mocha --color` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5108 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5086 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4992 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4969 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4965 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4841 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4328 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4188 | `npm run lint && npm run mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4155 | `mocha -R spec src` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4145 | `nyc mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4120 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4079 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4023 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4009 | `mocha --require test/babel-hook test/*.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4006 | `mocha --timeout=15000 tests/*.test.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 3977 | `mocha --require should --reporter spec` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4328 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4188 | `npm run lint && npm run mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4155 | `mocha -R spec src` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4145 | `nyc mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4120 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4079 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4023 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4018 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4009 | `mocha --require test/babel-hook test/*.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4008 | `npm run lint ; mocha && mocha test/individual` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4006 | `mocha --timeout=15000 tests/*.test.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 3977 | `mocha --require should --reporter spec` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3916 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3895 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3880 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3855 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3838 | `mocha --check-leaks --reporter spec --bail` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3808 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [teambit/bit](https://github.com/teambit/bit) | 3807 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3806 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [erming/shout](https://github.com/erming/shout) | 3805 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3752 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3673 | `nyc mocha "test/**/*.test.js"` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3669 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [primus/primus](https://github.com/primus/primus) | 3661 | `npm run build && mocha test/*.test.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 3625 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3616 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3577 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3562 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3552 | `node_modules/.bin/mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3544 | `mocha --reporter spec --timeout 3000` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3527 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3523 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3521 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3467 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3466 | `node_modules/.bin/mocha test/lib/` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3464 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3449 | `NODE_ENV=test mocha test/**/*.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3440 | `mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3430 | `NODE_ENV=test mocha --exit` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3398 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3356 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3248 | `nyc mocha && tsc` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3245 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3245 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3226 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3027 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3026 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3017 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2996 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2994 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2970 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2947 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2903 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2894 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2890 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2885 | `mocha -R spec --recursive src/test` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2879 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2867 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2864 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2853 | `mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2830 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2827 | `istanbul cover _mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2824 | `mocha -R landing test/index` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2824 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2903 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2894 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2894 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2890 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2885 | `mocha -R spec --recursive src/test` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2879 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2867 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2853 | `mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2830 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2827 | `istanbul cover _mocha` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2826 | `npm run mocha && npm run lint` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2824 | `mocha -R landing test/index` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2824 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2812 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2808 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2779 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2771 | `mocha --require should --reporter spec` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2768 | `mocha -R spec spec spec/reporters` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2763 | `mocha test-node` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2761 | `mocha --require babel-register --recursive spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2735 | `node_modules/.bin/mocha --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2724 | `mocha --reporter dot` | 
| [mde/ejs](https://github.com/mde/ejs) | 2715 | `mocha --require should --reporter spec` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2707 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2700 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2677 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2661 | `eslint . && mocha -t 5000` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2656 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2651 | `mocha --timeout 100000` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2643 | `mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2633 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2621 | `mocha --recursive --watch` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2620 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2616 | `npm run build && cd test && mocha . --reporter dot` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2616 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2608 | `mocha-phantomjs ./test/index.html` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2345 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2322 | `mocha -R spec` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2312 | `mocha test && npm run lint` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2309 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2306 | `mocha test/index.js --reporter dot` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2284 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2255 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2227 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2223 | `mocha test/ --no-timeouts` | 
| [gajus/swing](https://github.com/gajus/swing) | 2221 | `mocha --compilers js:babel-register` | 
| [noble/noble](https://github.com/noble/noble) | 2195 | `mocha -R spec test/*.js` | 
| [Qix-/color](https://github.com/Qix-/color) | 2152 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2126 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2109 | `standard && mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2109 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2106 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2083 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2056 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2051 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2270 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2255 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2233 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2227 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2223 | `mocha test/ --no-timeouts` | 
| [gajus/swing](https://github.com/gajus/swing) | 2221 | `mocha --compilers js:babel-register` | 
| [noble/noble](https://github.com/noble/noble) | 2195 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2191 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2152 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2146 | `cross-env BABEL_ENV=test mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2195 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2191 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2152 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2146 | `cross-env BABEL_ENV=test mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2126 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2109 | `standard && mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2109 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2106 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2095 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2083 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2056 | `nyc npm run _mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2056 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2051 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2020 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2010 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [slate/slate](https://github.com/slate/slate) | 2004 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1985 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1981 | `mocha && eslint *.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1980 | `mocha --compilers js:babel-core/register __tests__` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1981 | `mocha && eslint *.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1980 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1973 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1968 | `mocha -c test/index.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1967 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1964 | `mocha --require=test/test_helper.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 1960 | `npm run lint && npm run mocha` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1945 | `mocha --reporter spec --timeout 5000` | 
| [share/sharedb](https://github.com/share/sharedb) | 1938 | `./node_modules/.bin/mocha && npm run jshint` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1930 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1929 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1927 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1927 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [then/promise](https://github.com/then/promise) | 1921 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1917 | `npm run lint && mocha -R dot && npm run cover` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1917 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1913 | `mocha --require ./test/common --growl test/expect.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1849 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1834 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1814 | `mocha --reporter spec test/*.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1812 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1805 | `mocha && npm run lint` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1800 | `mocha test` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1799 | `mocha test` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1792 | `mocha --compilers js:babel-register` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1783 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1782 | `mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1753 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1727 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1725 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1712 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1707 | `mocha ./test/basic.js -t 5000` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1693 | `npm run lint && mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1690 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1688 | `mocha test --timeout 600000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1674 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1671 | `npm run lint && npm run mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [zeeshanu/dumper.js](https://github.com/zeeshanu/dumper.js) | 1668 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1666 | `mocha test/* --reporter spec` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1658 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1653 | `mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1634 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1632 | `mocha --expose-gc --slow 300` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1745 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1739 | `mocha test -u bdd -R spec` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1732 | `mocha test/**/*_test.js --bail` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1728 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1727 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1725 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1712 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1707 | `mocha ./test/basic.js -t 5000` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1706 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1698 | `mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1693 | `npm run lint && mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1690 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1688 | `mocha test --timeout 600000` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1687 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [zeeshanu/dumper.js](https://github.com/zeeshanu/dumper.js) | 1668 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1666 | `mocha test/* --reporter spec` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1658 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1653 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1651 | `mocha compiled_tests/` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1647 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1638 | `mocha spec` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1634 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1632 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1629 | `mocha tests/test.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1626 | `mocha && size-limit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1606 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1602 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1606 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1602 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1598 | `mocha test/setup.js test/spec/*.js` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1593 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1590 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1578 | `mocha tests.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1571 | `eslint --cache . && tsc && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1570 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1570 | `./node_modules/mocha/bin/mocha -R spec` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1562 | `standard "./src/*.js" && mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1562 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1533 | `nyc npm run mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1533 | `mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1533 | `mocha test.js` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1529 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1528 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1525 | `mocha --check-leaks --reporter spec --bail` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1525 | `node_modules/.bin/mocha --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1520 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1518 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1505 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1503 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1501 | `nyc mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 1491 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1401 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1395 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1384 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1383 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1381 | `./node_modules/mocha/bin/mocha` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1380 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1373 | `TEST=all mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1369 | `npm run build && mocha -r should` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1365 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1361 | `cross-env NODE_ENV=test nyc mocha` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1353 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1353 | `npm run lint && mocha && karma start --single-run` | 
| [electron/devtron](https://github.com/electron/devtron) | 1350 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [samccone/drool](https://github.com/samccone/drool) | 1455 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1454 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1439 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1424 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1412 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1411 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [noble/bleno](https://github.com/noble/bleno) | 1411 | `mocha -R spec test/*.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1401 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1387 | `istanbul cover _mocha` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1384 | `mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1381 | `./node_modules/mocha/bin/mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1381 | `mocha test/unit` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1369 | `npm run build && mocha -r should` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1365 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1361 | `cross-env NODE_ENV=test nyc mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1355 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1353 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1353 | `npm run lint && mocha && karma start --single-run` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1343 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1337 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1337 | `istanbul cover _mocha test -- --timeout 20000` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1337 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1337 | `istanbul cover _mocha test -- --timeout 20000` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1334 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1330 | `mocha tests/test-*` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1329 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1328 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1326 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1322 | `mocha --recursive` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1322 | `standard && istanbul cover _mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1307 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1305 | `mocha-phantomjs tests/index.html` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1302 | `mocha --reporter dot` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1296 | `mocha spec/exec.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1290 | `NODE_PATH=. mocha **/*.spec.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1296 | `mocha spec/exec.js` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1295 | `NODE_ENV=test mocha tests/*.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1290 | `NODE_PATH=. mocha **/*.spec.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1286 | `mocha` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1277 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1275 | `mocha --timeout 60000 test/` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1274 | `mocha ./test/test*.js --reporter spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1272 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1269 | `mocha -R spec ./test/unit/**` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1266 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1264 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1262 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1257 | `npm run lint && npm run mocha` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1256 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1256 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1252 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1252 | `mocha test/*.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1250 | `mocha --check-leaks --reporter spec --bail test/` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1249 | `mocha tests` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1248 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1246 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1239 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1235 | `mocha --recursive test/bin` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1232 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1224 | `npm run prepublishOnly && mocha test/test.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1222 | `mocha src/test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1222 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1222 | `mocha` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1221 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1217 | `istanbul test _mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1204 | `mocha --reporter spec` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1203 | `mocha test` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1201 | `node ./node_modules/mocha/bin/mocha tests` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1201 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1199 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1192 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1192 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1192 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1190 | `mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1190 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [variety/variety](https://github.com/variety/variety) | 1188 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1186 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1185 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1183 | `mocha --recursive test` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1181 | `mocha --compilers js:babel-core/register` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1173 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1170 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1173 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1170 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1160 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1158 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1152 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1149 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1146 | `mocha` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1146 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1141 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1140 | `webpack && npm run lint && npm run mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1136 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1136 | `mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1131 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1131 | `mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1128 | `npm run lint && mocha --require @babel/register` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1124 | `mocha $(find test -name '*.test.js')` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1124 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1122 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1120 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1118 | `xo && mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1116 | `npm run mocha:istanbul` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1116 | `istanbul cover _mocha test/*.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1115 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [router5/router5](https://github.com/router5/router5) | 1110 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1082 | `mocha --compilers js:babel-register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1080 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [electron/asar](https://github.com/electron/asar) | 1079 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1076 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1076 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1071 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1070 | `webpack && mocha test/unit` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1068 | `mocha --recursive --bail --reporter spec test` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1060 | `mocha test/tests.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1057 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1057 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 969 | `mocha` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 953 | `mocha --recursive -r tests/setup tests` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 945 | `mocha "client.test" --compilers js:babel-register` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 944 | `mocha --reporter spec --bail --check-leaks test/` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 943 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 941 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 940 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 939 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 932 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1003 | `mocha --async-only` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1003 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 999 | `mocha --colors ./test/*.spec.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 993 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 992 | `mocha test --compilers js:babel-core/register` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 987 | `npm run convertto:es5 && npm run mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 979 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 977 | `npm-run-all test:jest test:server:mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 975 | `npm run rollup-cjs && mocha test/test.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 975 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 974 | `mocha --reporter spec` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 971 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 969 | `mocha` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 954 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 953 | `mocha` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 953 | `mocha --recursive -r tests/setup tests` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 945 | `mocha "client.test" --compilers js:babel-register` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 944 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 943 | `mocha --compilers js:babel-register test/*.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 941 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 940 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 939 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 934 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 941 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 940 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 939 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 934 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 932 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 929 | `npm run lint && mocha -R spec` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 919 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 917 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 917 | `mocha tests` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 915 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 914 | `mocha spec/*.spec.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 913 | `mocha test` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 912 | `mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 907 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 906 | `mocha spec/*.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 902 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 897 | `mocha -t 600000` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 895 | `mocha test` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 871 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 871 | `./node_modules/.bin/mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 869 | `./node_modules/.bin/mocha -R spec` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 868 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 867 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 867 | `mocha --timeout 200000` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 865 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 864 | `npm run lint && npm run mocha:no-functional` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 864 | `mocha -t 5000` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 862 | `istanbul cover -- _mocha --reporter spec` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 861 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 858 | `standard && standard ./bin/* && mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 857 | `mocha test --compilers js:babel-register` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 857 | `eslint test && mocha --compilers js:babel/register` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 854 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 852 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 848 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 846 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 869 | `./node_modules/.bin/mocha -R spec` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 868 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 867 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 867 | `mocha --timeout 200000` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 865 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 864 | `npm run lint && npm run mocha:no-functional` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 864 | `mocha -t 5000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 862 | `node_modules/.bin/mocha test/spec` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 862 | `istanbul cover -- _mocha --reporter spec` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 861 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 858 | `standard && standard ./bin/* && mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 857 | `mocha test --compilers js:babel-register` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 857 | `eslint test && mocha --compilers js:babel/register` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 854 | `nyc --check-coverage mocha test/*.test.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 854 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 852 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 848 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 846 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 823 | `mocha && ember test` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 822 | `mocha test/index.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 819 | `mocha` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 818 | `mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 815 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 814 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 813 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 813 | `mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 810 | `mocha --async-only` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 806 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 806 | `cake build && mocha ./test/mocha/*.coffee` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 819 | `mocha` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 818 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 818 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 815 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 814 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 813 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 813 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 813 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 813 | `mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 806 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 806 | `cake build && mocha ./test/mocha/*.coffee` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 806 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 798 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 798 | `mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 797 | `mocha -u tdd` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 797 | `mocha --harmony --full-trace --check-leaks` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 797 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 791 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 790 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 790 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 789 | `npm run mocha-test test/integration` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 789 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 788 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 787 | `npm run build && istanbul test _mocha test/test.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 787 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 787 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 786 | `mocha --colors --reporter spec test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 786 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 785 | `mocha` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 784 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 784 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 791 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 790 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 790 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 789 | `npm run mocha-test test/integration` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 789 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 788 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 787 | `npm run build && istanbul test _mocha test/test.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 787 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 787 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 786 | `mocha --colors --reporter spec test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 786 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 785 | `mocha` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 784 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 784 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 782 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 777 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 777 | `xo && mocha -R spec` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 776 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 775 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [developit/decko](https://github.com/developit/decko) | 770 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 770 | `mocha test` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 766 | `mocha --no-timeouts` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 764 | `mocha --ui tdd --require ./test/__setup` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 762 | `mocha` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 761 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 761 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 760 | `./node_modules/.bin/mocha test/**/*` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 759 | `mocha --recursive -s 15 test/` | 