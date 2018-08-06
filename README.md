# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:04 08/06/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43067 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41072 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39555 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30024 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 25507 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24416 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23068 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19602 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18884 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16738 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16477 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15048 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14308 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13887 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13352 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13078 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12645 | `./node_modules/.bin/mocha test/` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12610 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12280 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12235 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11705 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11437 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11059 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11058 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10385 | `mocha test/index.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10068 | `mocha` | 
| [svg/svgo](https://github.com/svg/svgo) | 10054 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10053 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [tj/co](https://github.com/tj/co) | 9994 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9914 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9591 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9510 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9332 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 9279 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9040 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8969 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8961 | `grunt mocha` | 
| [amark/gun](https://github.com/amark/gun) | 8648 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8646 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8557 | `mocha tests/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8471 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8420 | `mocha --check-leaks -R dot` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8417 | `mocha test/src` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8294 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8156 | `mocha --compilers js:babel-register test/test.js` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 8149 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8046 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7933 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7874 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7669 | `./node_modules/.bin/mocha test` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7653 | `mocha --opts mocha.opts` | 
| [dthree/cash](https://github.com/dthree/cash) | 7550 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7518 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7438 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7409 | `npm run build && istanbul cover _mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7197 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7179 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7149 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7008 | `xo && mocha test/*.js --timeout 100000` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6972 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [almende/vis](https://github.com/almende/vis) | 6946 | `mocha --compilers js:babel-core/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6869 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6753 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6425 | `npm run jshint && mocha test/` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6329 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6277 | `mocha --exit --require babel-core/register` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6231 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6207 | `npm run test:mocha:src` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6141 | `mocha test/test.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6045 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6019 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5947 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5943 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5875 | `mocha tests/node.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5784 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5712 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5679 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5573 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5569 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5517 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5408 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5289 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5237 | `standard && mocha` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5174 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5152 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5068 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5062 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4942 | `gulp lint && mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4941 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4912 | `mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4838 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4506 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4458 | `mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4430 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4397 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4389 | `nyc mocha --exit` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4386 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4367 | `npm run lint && npm run mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4325 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4325 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4143 | `npm run lint && npm run mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4130 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4120 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4071 | `nyc mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4036 | `node_modules/.bin/mocha test/tests.js` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 4008 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4007 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4003 | `mocha --require test/babel-hook test/*.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3973 | `npm run lint ; mocha && mocha test/individual` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3968 | `mocha --timeout=15000 tests/*.test.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 3965 | `mocha --require should --reporter spec` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3890 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3880 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3828 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3815 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3806 | `mocha --check-leaks --reporter spec --bail` | 
| [erming/shout](https://github.com/erming/shout) | 3803 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3739 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3727 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3723 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [teambit/bit](https://github.com/teambit/bit) | 3715 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3695 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3672 | `npm run jshint && npm run mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3563 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3563 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3541 | `node_modules/.bin/mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3534 | `mocha --reporter spec --timeout 3000` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3521 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3517 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3485 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3455 | `node_modules/.bin/mocha test/lib/` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3437 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3435 | `mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3386 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3360 | `NODE_ENV=test mocha --exit` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3386 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3360 | `NODE_ENV=test mocha --exit` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3307 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3226 | `nyc mocha && tsc` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3215 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3214 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3213 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2975 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2951 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2937 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2907 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2875 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2873 | `mocha -R spec --recursive src/test` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2861 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2848 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2839 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2822 | `istanbul cover _mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2817 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2813 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2803 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2795 | `npm run mocha && npm run lint` | 
| [github-tools/github](https://github.com/github-tools/github) | 2792 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2951 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2937 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2907 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2883 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2875 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2875 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2873 | `mocha -R spec --recursive src/test` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2861 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2859 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2848 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2839 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2822 | `istanbul cover _mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2817 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2813 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2803 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2795 | `npm run mocha && npm run lint` | 
| [github-tools/github](https://github.com/github-tools/github) | 2792 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2771 | `mocha --require should --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2769 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2756 | `mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2752 | `mocha -R landing test/index` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2745 | `mocha --require babel-register --recursive spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2740 | `mocha test-node` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2714 | `node_modules/.bin/mocha --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2713 | `mocha --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2704 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2700 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [mde/ejs](https://github.com/mde/ejs) | 2676 | `mocha --require should --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2666 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2644 | `mocha --timeout 100000` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2640 | `mocha -R spec spec spec/reporters` | 
| [json5/json5](https://github.com/json5/json5) | 2640 | `nyc --reporter=html --reporter=text mocha` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2633 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2497 | `mocha "test/**/*-test.js"` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2468 | `mocha --reporter=spec test/*-test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2448 | `mocha test` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2441 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2437 | `mocha test/src/**/*.unit.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2432 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2427 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2409 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2403 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2397 | `mocha --no-colors --reporter spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2373 | `nyc --reporter=html --reporter=text mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2348 | `grunt jshint && mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2335 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2325 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2309 | `mocha -R spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2377 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2373 | `nyc --reporter=html --reporter=text mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2348 | `grunt jshint && mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2335 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2325 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2309 | `mocha -R spec` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2306 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2296 | `mocha test && npm run lint` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2279 | `mocha test/index.js --reporter dot` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2278 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2274 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2255 | `mocha && eslint .` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2325 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2309 | `mocha -R spec` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2306 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2296 | `mocha test && npm run lint` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2279 | `mocha test/index.js --reporter dot` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2278 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2274 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2255 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2241 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2231 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2228 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [gajus/swing](https://github.com/gajus/swing) | 2217 | `mocha --compilers js:babel-register` | 
| [noble/noble](https://github.com/noble/noble) | 2187 | `mocha -R spec test/*.js` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2186 | `mocha test/ --no-timeouts` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2164 | `mocha --compilers js:babel-register` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2141 | `cross-env BABEL_ENV=test mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2126 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2107 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2106 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2097 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2093 | `mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2090 | `standard && mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2076 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2056 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2043 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2034 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2030 | `nyc npm run _mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2008 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [slate/slate](https://github.com/slate/slate) | 2005 | `cross-env BABEL_ENV=test FORBID_DEPRECATIONS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1980 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1969 | `mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1966 | `mocha -c test/index.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1965 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1961 | `mocha --compilers js:babel-core/register __tests__` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1960 | `mocha --require=test/test_helper.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1949 | `mocha && eslint *.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1948 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1942 | `mocha --reporter spec --timeout 5000` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1929 | `mocha --bail --reporter spec --check-leaks test/` | 
| [share/sharedb](https://github.com/share/sharedb) | 1928 | `./node_modules/.bin/mocha && npm run jshint` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1925 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1920 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [then/promise](https://github.com/then/promise) | 1915 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1908 | `mocha --require ./test/common --growl test/expect.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1908 | `npm run lint && mocha -R dot && npm run cover` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1904 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1903 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1862 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1837 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1829 | `mocha --reporter spec && npm run test-typescript` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1828 | `npm run mocha && npm run karma` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1811 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1806 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1799 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1797 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1793 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1793 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1790 | `mocha && npm run lint` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1789 | `npm run lint && mocha --reporter spec test/*.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1789 | `mocha --reporter spec test/*.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1780 | `mocha tests --compilers js:babel-core/register` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1775 | `mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1799 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1797 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1793 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1793 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1790 | `mocha && npm run lint` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1789 | `npm run lint && mocha --reporter spec test/*.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1789 | `mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1784 | `mocha test` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1780 | `mocha tests --compilers js:babel-core/register` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1777 | `mocha --reporter spec --grep .` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1775 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1765 | `mocha --compilers js:babel-register` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1753 | `npm run lint && npm run mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1753 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1748 | `mocha test/**/*.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1737 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1737 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1732 | `mocha test/**/*_test.js --bail` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1727 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1727 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1725 | `mocha test -u bdd -R spec` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1724 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1709 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1702 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1698 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1693 | `mocha ./test/basic.js -t 5000` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1689 | `npm run lint && mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1682 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1681 | `mocha test --timeout 600000` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1673 | `mocha test/*.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1669 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1584 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1575 | `mocha test/setup.js test/spec/*.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1568 | `./node_modules/mocha/bin/mocha -R spec` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1559 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1558 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [zeit/ms](https://github.com/zeit/ms) | 1557 | `mocha tests.js` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1547 | `standard "./src/*.js" && mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1547 | `mocha test` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1542 | `mocha --reporter spec` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1530 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1528 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1547 | `standard "./src/*.js" && mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1547 | `mocha test` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1544 | `npm run test:lint && npm run test:mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1542 | `mocha --reporter spec` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1530 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1528 | `mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1520 | `node_modules/.bin/mocha --recursive` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1518 | `mocha test.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1514 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1513 | `mocha --check-leaks --reporter spec --bail` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1509 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1501 | `mocha -u tdd` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1547 | `mocha test` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1544 | `npm run test:lint && npm run test:mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1542 | `mocha --reporter spec` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1530 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1528 | `mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1520 | `node_modules/.bin/mocha --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1520 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1518 | `mocha test.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1514 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1513 | `mocha --check-leaks --reporter spec --bail` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1510 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1509 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1503 | `nyc npm run mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1501 | `mocha -u tdd` | 
| [noble/bleno](https://github.com/noble/bleno) | 1403 | `mocha -R spec test/*.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1401 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1379 | `./node_modules/mocha/bin/mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1374 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1372 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1370 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1366 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1362 | `mocha test/unit` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1360 | `cross-env NODE_ENV=test nyc mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1360 | `npm run build && mocha -r should` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1349 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [electron/devtron](https://github.com/electron/devtron) | 1346 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1341 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1439 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1434 | `nyc mocha --timeout=20000 test.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1415 | `mocha --timeout 10000 ./tests/lib.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1411 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [noble/bleno](https://github.com/noble/bleno) | 1403 | `mocha -R spec test/*.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1401 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1400 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1387 | `istanbul cover _mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1379 | `./node_modules/mocha/bin/mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1374 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1372 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1370 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1366 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1362 | `mocha test/unit` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1360 | `cross-env NODE_ENV=test nyc mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1360 | `npm run build && mocha -r should` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1349 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [electron/devtron](https://github.com/electron/devtron) | 1346 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1341 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1338 | `mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1337 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1335 | `npm run lint && mocha && karma start --single-run` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1332 | `TEST=all mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1330 | `mocha --opts test/opts/mocha.opts` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1327 | `istanbul cover _mocha test -- --timeout 20000` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1326 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1322 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1321 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1318 | `./node_modules/.bin/mocha test` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1317 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1315 | `mocha --recursive` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1314 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1309 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1306 | `mocha tests/test-*` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1306 | `mocha-phantomjs tests/index.html` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1300 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1296 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1295 | `mocha spec/exec.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1295 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1294 | `mocha --reporter dot` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1268 | `mocha --timeout 60000 test/` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1267 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1263 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1260 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1255 | `NODE_ENV=test mocha tests/*.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1250 | `mocha ./test/test*.js --reporter spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1250 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1250 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1248 | `mocha tests` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1248 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1246 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1246 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1243 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1240 | `mocha -R spec ./test/unit/**` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1233 | `npm run lint && npm run mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1229 | `mocha --check-leaks --reporter spec --bail test/` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1224 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1240 | `mocha -R spec ./test/unit/**` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1233 | `npm run lint && npm run mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1229 | `mocha --check-leaks --reporter spec --bail test/` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1224 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1218 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1218 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1217 | `mocha src/test.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1214 | `mocha test/test.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1213 | `istanbul test _mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1212 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1211 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1211 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1208 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1207 | `npm run prepublishOnly && mocha test/test.js` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1205 | `mocha --recursive test/bin` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1202 | `mocha test` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1200 | `node ./node_modules/mocha/bin/mocha tests` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1200 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1198 | `npm run lint && npm run mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1197 | `mocha --reporter spec` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1192 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1185 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1184 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1184 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1183 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1181 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1177 | `mocha` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1177 | `mocha --recursive test` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1175 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1168 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1149 | `mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1146 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1144 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1144 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1130 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1130 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1123 | `mocha $(find test -name '*.test.js')` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1121 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1120 | `mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1119 | `webpack && npm run lint && npm run mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1117 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1117 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1114 | `xo && mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1113 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1130 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1130 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1123 | `mocha $(find test -name '*.test.js')` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1121 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1120 | `mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1119 | `webpack && npm run lint && npm run mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1117 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1117 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1114 | `xo && mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1113 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1111 | `istanbul cover _mocha test/*.js` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1107 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1105 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1105 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1105 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1103 | `npm run lint && mocha --require @babel/register` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1101 | `mocha test/*` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1100 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1098 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1097 | `npm run mocha:istanbul` | 
| [router5/router5](https://github.com/router5/router5) | 1094 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1090 | `mocha` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1089 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1081 | `mocha --compilers js:babel-register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1074 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [electron/asar](https://github.com/electron/asar) | 1073 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1071 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1070 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1064 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1062 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1062 | `webpack && mocha test/unit` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 983 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 979 | `mocha -R list` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 976 | `npm run convertto:es5 && npm run mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 975 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 973 | `npm run rollup-cjs && mocha test/test.js` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 971 | `npm run lint && npm run flow && NODE_ENV=test nyc mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 971 | `mocha --reporter spec` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 967 | `mocha test --compilers js:babel-core/register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 951 | `mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 951 | `mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 970 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 951 | `mocha` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 948 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 938 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 937 | `mocha --compilers js:babel-register test/*.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 936 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 934 | `mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 931 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 927 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 926 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 923 | `mocha --recursive -r tests/setup tests` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 922 | `npm run lint && mocha -R spec` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 916 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 914 | `mocha spec/*.spec.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 913 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 912 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 912 | `mocha tests` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 909 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 907 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 906 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 904 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 901 | `mocha spec/*.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 895 | `mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 894 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 889 | `mocha -t 600000` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 884 | `node_modules/.bin/mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 884 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 883 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 875 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 874 | `nyc mocha specs` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 872 | `mocha test` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 871 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 868 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 865 | `npm run lint && npm run mocha:no-functional` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 865 | `mocha --timeout 200000` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 864 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 864 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 863 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 862 | `./node_modules/.bin/mocha --reporter spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 859 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 859 | `mocha -t 5000` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 857 | `./node_modules/.bin/mocha -R spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 857 | `eslint test && mocha --compilers js:babel/register` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 855 | `istanbul cover -- _mocha --reporter spec` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 853 | `mocha test --compilers js:babel-register` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 857 | `./node_modules/.bin/mocha -R spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 857 | `eslint test && mocha --compilers js:babel/register` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 855 | `istanbul cover -- _mocha --reporter spec` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 853 | `mocha test --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 852 | `standard && standard ./bin/* && mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 848 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 848 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 846 | `mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 843 | `nyc --check-coverage mocha test/*.test.js` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 839 | `mocha --reporter spec` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 839 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 839 | `mocha --check-leaks -t 20000` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 837 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 836 | `istanbul cover _mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 835 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 835 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 835 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 835 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 834 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 833 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 830 | `npm run lint && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 828 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 827 | `nyc mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 827 | `mocha --recursive ./test/*_spec.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 827 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 823 | `mocha && ember test` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 817 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 816 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 815 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 814 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 812 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 812 | `mocha test/index.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 812 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 810 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 806 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 805 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 805 | `cake build && mocha ./test/mocha/*.coffee` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 805 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 805 | `mocha --require babel-register` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 804 | `mocha test` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 803 | `mocha --async-only` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 799 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 797 | `mocha -u tdd` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 795 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 793 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 790 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 789 | `mocha --harmony --full-trace --check-leaks` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 788 | `mocha` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 787 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [developit/decko](https://github.com/developit/decko) | 769 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 765 | `mocha --ui tdd --require ./test/__setup` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 765 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 764 | `mocha test` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 762 | `mocha --no-timeouts` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 762 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 755 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 753 | `mocha --recursive -s 15 test/` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 751 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 751 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 751 | `mocha` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 749 | `mocha -r should --reporter spec test/*.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 747 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 747 | `mocha` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 739 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 738 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 738 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 737 | `mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 737 | `mocha --reporter spec` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 737 | `npm run lint && npm run mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 736 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 735 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 734 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 732 | `mocha tests/*.mocha.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 728 | `mocha` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 727 | `nyc mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 727 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 726 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 724 | `npm run bundle && mocha` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 723 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 723 | `mocha` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 722 | `babel-node node_modules/.bin/_mocha -- test` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 722 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 721 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 720 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 719 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 718 | `./node_modules/.bin/mocha test/**/*` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 715 | `mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 714 | `mocha --reporter spec build/test/index.js` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 714 | `mocha --exit --use_strict src/*.test.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 713 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 