# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:03 07/24/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 42885 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41005 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39351 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29935 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 25086 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24345 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23956 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22910 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19482 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18781 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16637 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16369 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14938 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14277 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13799 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13172 | `mocha --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13008 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12592 | `mocha 'test/**/*.spec.js'` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12587 | `./node_modules/.bin/mocha test/` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12236 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12218 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11599 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11386 | `nyc grunt mocha-and-karma` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10941 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10928 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10277 | `mocha test/index.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9976 | `mocha` | 
| [svg/svgo](https://github.com/svg/svgo) | 9976 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9967 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [tj/co](https://github.com/tj/co) | 9954 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9878 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9526 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9391 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9299 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 9171 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8992 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8922 | `grunt mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8871 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8592 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [amark/gun](https://github.com/amark/gun) | 8503 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8450 | `mocha test/test.js` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8450 | `mocha tests/*.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8409 | `mocha --check-leaks -R dot` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8376 | `mocha test/src` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8275 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8130 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8028 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7997 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7869 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7817 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7643 | `./node_modules/.bin/mocha test` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7566 | `mocha --opts mocha.opts` | 
| [dthree/cash](https://github.com/dthree/cash) | 7545 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7437 | `mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7409 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7391 | `npm run build && istanbul cover _mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7147 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7105 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7084 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6957 | `xo && mocha test/*.js --timeout 100000` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6909 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [almende/vis](https://github.com/almende/vis) | 6898 | `mocha --compilers js:babel-core/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6847 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6639 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6379 | `npm run jshint && mocha test/` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6192 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6191 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6190 | `mocha --exit --require babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6188 | `mocha; jshint *.js lib` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6074 | `mocha test/test.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6043 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5942 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5935 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5855 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5837 | `mocha tests/node.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5741 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5689 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5657 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5533 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5515 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5406 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5397 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5375 | `mocha --timeout 10000 && npm run lint` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5242 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5186 | `standard && mocha` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5171 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5154 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5042 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4931 | `gulp lint && mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4898 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4881 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4849 | `mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4836 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4442 | `mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4439 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4428 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4379 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4347 | `nyc mocha --exit` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4341 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4327 | `npm run lint && npm run mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4323 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4132 | `nyc mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4085 | `npm run lint && npm run mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4132 | `nyc mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4085 | `npm run lint && npm run mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4077 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4044 | `nyc mocha` | 
| [muicss/mui](https://github.com/muicss/mui) | 4001 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3991 | `mocha --require test/babel-hook test/*.js` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3972 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3972 | `node_modules/.bin/mocha test/tests.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3952 | `npm run lint ; mocha && mocha test/individual` | 
| [tj/ejs](https://github.com/tj/ejs) | 3951 | `mocha --require should --reporter spec` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3934 | `mocha --timeout=15000 tests/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3805 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3768 | `mocha --check-leaks --reporter spec --bail` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3750 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3727 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3679 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3671 | `npm run jshint && npm run mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3657 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3633 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3606 | `nyc mocha "test/**/*.test.js"` | 
| [teambit/bit](https://github.com/teambit/bit) | 3605 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3633 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [primus/primus](https://github.com/primus/primus) | 3629 | `npm run build && mocha test/*.test.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3606 | `nyc mocha "test/**/*.test.js"` | 
| [teambit/bit](https://github.com/teambit/bit) | 3605 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3574 | `mocha tests/javascript` | 
| [expressjs/session](https://github.com/expressjs/session) | 3572 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3563 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3538 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3534 | `mocha --reporter spec --timeout 3000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3528 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3504 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3491 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3456 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3449 | `node_modules/.bin/mocha test/lib/` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3442 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3435 | `mocha` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3427 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3371 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3369 | `NODE_ENV=test mocha test/**/*.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3293 | `NODE_ENV=test mocha --exit` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3264 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3198 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3197 | `nyc mocha && tsc` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3183 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3180 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3064 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3048 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3022 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3014 | `mocha test/*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3010 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3002 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2999 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2987 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2984 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2977 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2946 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2921 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2894 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2883 | `mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2877 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2864 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2840 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2831 | `mocha` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2830 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2829 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2819 | `istanbul cover _mocha` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2803 | `mocha --opts mocha.opts` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2801 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [github-tools/github](https://github.com/github-tools/github) | 2793 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2778 | `npm run mocha && npm run lint` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2770 | `mocha --require should --reporter spec` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2762 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2734 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2728 | `mocha --require babel-register --recursive spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2726 | `mocha` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2723 | `mocha test-node` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2720 | `mocha -R landing test/index` | 
| [css/csso](https://github.com/css/csso) | 2701 | `mocha --reporter dot` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2762 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2734 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2728 | `mocha --require babel-register --recursive spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2726 | `mocha` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2723 | `mocha test-node` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2720 | `mocha -R landing test/index` | 
| [css/csso](https://github.com/css/csso) | 2701 | `mocha --reporter dot` | 
| [tj/should.js](https://github.com/tj/should.js) | 2698 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2697 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2693 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2691 | `node_modules/.bin/mocha --reporter spec` | 
| [mde/ejs](https://github.com/mde/ejs) | 2643 | `mocha --require should --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2641 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2640 | `mocha --timeout 100000` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2621 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2609 | `mocha --recursive --watch` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2608 | `mocha-phantomjs ./test/index.html` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2607 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2598 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [json5/json5](https://github.com/json5/json5) | 2598 | `nyc --reporter=html --reporter=text mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2592 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2568 | `nyc mocha --timeout=10000` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2562 | `mocha test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2560 | `npm run build && cd test && mocha . --reporter dot` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2560 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2555 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2498 | `nyc mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2480 | `eslint . && mocha -t 5000` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2480 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2479 | `mocha "test/**/*-test.js"` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2467 | `mocha --reporter=spec test/*-test.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2457 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2441 | `mocha test` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2435 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2424 | `mocha test/src/**/*.unit.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2415 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2410 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2407 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2403 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2391 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2372 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2353 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2349 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2345 | `grunt jshint && mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2326 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2303 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2297 | `mocha -R spec` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2280 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2273 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2272 | `mocha test && npm run lint` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2269 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2235 | `mocha && eslint .` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2230 | `mocha test test/unit/**/*_test.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2228 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2227 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2226 | `mocha test/index.js --reporter dot` | 
| [gajus/swing](https://github.com/gajus/swing) | 2216 | `mocha --compilers js:babel-register` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2012 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [slate/slate](https://github.com/slate/slate) | 2005 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1996 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1991 | `nyc npm run _mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1971 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1958 | `mocha --require=test/test_helper.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1956 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1948 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1939 | `mocha` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1937 | `mocha --reporter spec --timeout 5000` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1927 | `mocha && eslint *.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1927 | `mocha --bail --reporter spec --check-leaks test/` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1926 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1926 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1925 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1922 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [share/sharedb](https://github.com/share/sharedb) | 1912 | `./node_modules/.bin/mocha && npm run jshint` | 
| [then/promise](https://github.com/then/promise) | 1908 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1903 | `mocha --require ./test/common --growl test/expect.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1900 | `npm run lint && mocha -R dot && npm run cover` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1893 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1879 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1872 | `mocha tests.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 1871 | `npm run lint && npm run mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 1869 | `mocha test/*.test.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1854 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1854 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1810 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1790 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1790 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1787 | `npm run lint && mocha --reporter spec test/*.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1778 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1777 | `mocha test` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1776 | `mocha && npm run lint` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1765 | `mocha tests --compilers js:babel-core/register` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1759 | `mocha --reporter spec --grep .` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1747 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1745 | `npm run lint && npm run mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1726 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1725 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1723 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1722 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1714 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1730 | `mocha --compilers js:babel-register` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1726 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1725 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1723 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1722 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1716 | `mocha test -u bdd -R spec` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1714 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1707 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1699 | `./node_modules/.bin/mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1684 | `npm run lint && mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1677 | `mocha ./test/basic.js -t 5000` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1675 | `mocha test --timeout 600000` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1671 | `xo && mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1670 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1666 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1664 | `mocha test/*.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1650 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1650 | `npm run lint && npm run mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1684 | `npm run lint && mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1677 | `mocha ./test/basic.js -t 5000` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1675 | `mocha test --timeout 600000` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1671 | `xo && mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1670 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1666 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1664 | `mocha test/*.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1650 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1650 | `npm run lint && npm run mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1646 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1645 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1636 | `mocha test/* --reporter spec` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1633 | `mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1631 | `mocha spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1629 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1624 | `mocha tests/test.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1623 | `mocha && size-limit` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1604 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1602 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1597 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1593 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1593 | `mocha compiled_tests/` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1586 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1579 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1565 | `./node_modules/mocha/bin/mocha -R spec` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1496 | `mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1494 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1490 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1488 | `nyc mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1487 | `node_modules/.bin/mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1480 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1469 | `mocha test/**/*.spec.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1465 | `mocha --recursive` | 
| [samccone/drool](https://github.com/samccone/drool) | 1453 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1447 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1440 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1504 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1503 | `mocha --check-leaks --reporter spec --bail` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1500 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1496 | `mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1494 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1490 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1488 | `nyc mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1487 | `node_modules/.bin/mocha --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1486 | `nyc npm run mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1480 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1469 | `mocha test/**/*.spec.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1465 | `mocha --recursive` | 
| [samccone/drool](https://github.com/samccone/drool) | 1453 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1447 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1415 | `nyc mocha --timeout=20000 test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1410 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1409 | `mocha --timeout 10000 ./tests/lib.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1263 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1263 | `mocha --timeout 60000 test/` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1257 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1256 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1247 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1247 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1243 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1242 | `mocha` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1242 | `mocha test/*.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1240 | `NODE_PATH=. mocha **/*.spec.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1239 | `mocha tests` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1238 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1237 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1233 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1228 | `NODE_ENV=test mocha tests/*.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1226 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1217 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1212 | `mocha src/test.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1288 | `mocha tests/test-*` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1283 | `mocha --reporter dot` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1282 | `standard && istanbul cover _mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1281 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1273 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1263 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1263 | `mocha --timeout 60000 test/` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1257 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1256 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1247 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1247 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1243 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1242 | `mocha` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1242 | `mocha test/*.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1240 | `NODE_PATH=. mocha **/*.spec.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1239 | `mocha tests` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1238 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1237 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1233 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1228 | `NODE_ENV=test mocha tests/*.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1226 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1217 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1214 | `mocha -R spec ./test/unit/**` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1212 | `mocha src/test.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1208 | `mocha ./test/test*.js --reporter spec` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1207 | `mocha --check-leaks --reporter spec --bail test/` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1207 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1207 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1206 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1202 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1199 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1198 | `istanbul test _mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1198 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1197 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1197 | `node ./node_modules/mocha/bin/mocha tests` | 
| [variety/variety](https://github.com/variety/variety) | 1174 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1171 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1167 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1165 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1164 | `mocha --recursive test` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1162 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1153 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1152 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1149 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1137 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1153 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1152 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1149 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1145 | `mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1143 | `mocha --compilers js:babel-core/register` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1137 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1125 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1117 | `mocha $(find test -name '*.test.js')` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1114 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1111 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1109 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1106 | `istanbul cover _mocha test/*.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1104 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1104 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1104 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1099 | `mocha test/*` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1098 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1097 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1097 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1092 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1088 | `mocha --check-leaks -t 20000` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1087 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [router5/router5](https://github.com/router5/router5) | 1085 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1083 | `mocha` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1083 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1081 | `npm run lint && mocha --require @babel/register` | 
| [router5/router5](https://github.com/router5/router5) | 1085 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1083 | `mocha` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1083 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1081 | `npm run lint && mocha --require @babel/register` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1080 | `webpack && npm run lint && npm run mocha` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1079 | `mocha --compilers js:babel-register` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1078 | `standard && mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1072 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1071 | `npm run mocha:istanbul` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1068 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [electron/asar](https://github.com/electron/asar) | 1061 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1057 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 992 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 984 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 982 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 978 | `mocha --timeout 30000 --recursive ./tests` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 977 | `mocha -R list` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 975 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1017 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [electron/spectron](https://github.com/electron/spectron) | 1016 | `mocha && standard` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1012 | `eslint src test && mocha --compilers babel-register` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1012 | `mocha --check-leaks -R dot` | 
| [tomas/needle](https://github.com/tomas/needle) | 1011 | `mocha test` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1010 | `mocha $(find test -name '*.test.js')` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1000 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 999 | `mocha --recursive test/unit/` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 993 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 992 | `mocha --async-only` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 992 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 984 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 982 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 978 | `mocha --timeout 30000 --recursive ./tests` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 977 | `mocha -R list` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 975 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 972 | `npm run rollup-cjs && mocha test/test.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 970 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 967 | `mocha --reporter spec` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 966 | `npm run convertto:es5 && npm run mocha` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 966 | `npm run lint && npm run flow && NODE_ENV=test nyc mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 959 | `npm-run-all test:jest test:server:mocha` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 933 | `mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 930 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 929 | `mocha --compilers js:babel-register test/*.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 922 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 920 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 920 | `mocha` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 916 | `mocha ./test/index.js` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 916 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 908 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 870 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 868 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 864 | `npm run lint && npm run mocha:no-functional` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 864 | `mocha --timeout 200000` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 864 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 863 | `mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 863 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 856 | `eslint test && mocha --compilers js:babel/register` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 855 | `mocha -t 5000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 854 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 851 | `./node_modules/.bin/mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 850 | `./node_modules/.bin/mocha -R spec` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 849 | `mocha test` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 849 | `mocha test --compilers js:babel-register` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 849 | `istanbul cover -- _mocha --reporter spec` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 848 | `standard && standard ./bin/* && mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 847 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 838 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 836 | `istanbul cover _mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 835 | `mocha --check-leaks -t 20000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 834 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 834 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 826 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 826 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 825 | `mocha --reporter list` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 823 | `mocha && ember test` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 821 | `npm run lint && mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 825 | `mocha --reporter list` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 823 | `mocha && ember test` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 821 | `npm run lint && mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 821 | `nyc --check-coverage mocha test/*.test.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 820 | `nyc mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 820 | `mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 819 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 819 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 815 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 815 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 814 | `mocha --recursive ./test/*_spec.js` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 813 | `mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 812 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 809 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 809 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 808 | `mocha test/index.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 808 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 807 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 807 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 805 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 805 | `mocha --require babel-register` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 803 | `cake build && mocha ./test/mocha/*.coffee` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 802 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 799 | `mocha test` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 798 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 798 | `mocha --async-only` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 795 | `mocha -u tdd` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 794 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [edsu/anon](https://github.com/edsu/anon) | 785 | `mocha --colors --reporter spec test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 785 | `mocha --harmony --full-trace --check-leaks` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 782 | `mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 780 | `npm run build && istanbul test _mocha test/test.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 779 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 778 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 778 | `npm run mocha-test test/integration` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 776 | `xo && mocha -R spec` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 776 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 775 | `mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 775 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 772 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 771 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 771 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 770 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 758 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 754 | `mocha test` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 753 | `mocha --recursive -s 15 test/` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 753 | `mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 752 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 744 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 742 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 754 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 754 | `mocha test` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 753 | `mocha --recursive -s 15 test/` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 753 | `mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 752 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 752 | `mocha --no-timeouts` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 749 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 744 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 742 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 734 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 734 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 733 | `npm run lint && npm run mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 731 | `mocha tests/*.mocha.js` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 728 | `mocha` | 
| [scality/S3](https://github.com/scality/S3) | 727 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 726 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 725 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 724 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 722 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 722 | `mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 721 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 721 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 721 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 722 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 722 | `mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 721 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 721 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 721 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 720 | `babel-node node_modules/.bin/_mocha -- test` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 719 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 719 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 718 | `mocha` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 717 | `npm run bundle && mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 716 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 716 | `nyc mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 710 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 710 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 691 | `mocha --reporter spec` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 685 | `mocha $(find test -name '*.test.js')` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 685 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 683 | `npm run test-mocha && npm run test-karma` | 
| [koajs/static](https://github.com/koajs/static) | 683 | `mocha --harmony --reporter spec --exit` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 682 | `mocha --exit --use_strict src/*.test.js` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 681 | `mocha` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 693 | `mocha` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 691 | `mocha --reporter spec` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 686 | `./node_modules/.bin/mocha test/**/*` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 685 | `mocha $(find test -name '*.test.js')` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 685 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 683 | `npm run test-mocha && npm run test-karma` | 
| [koajs/static](https://github.com/koajs/static) | 683 | `mocha --harmony --reporter spec --exit` | 
| [EOSIO/eosjs](https://github.com/EOSIO/eosjs) | 682 | `mocha --exit --use_strict src/*.test.js` | 