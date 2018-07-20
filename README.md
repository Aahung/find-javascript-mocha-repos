# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:02 07/20/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 42816 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40986 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39287 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29906 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 24918 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24330 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23917 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22855 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19455 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18758 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16622 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16328 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14892 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14268 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13778 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13149 | `mocha --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12990 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12588 | `mocha 'test/**/*.spec.js'` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12563 | `./node_modules/.bin/mocha test/` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 12560 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12228 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12215 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11579 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11371 | `nyc grunt mocha-and-karma` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10914 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10893 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10261 | `mocha test/index.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9960 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 9947 | `mocha --harmony` | 
| [svg/svgo](https://github.com/svg/svgo) | 9946 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9941 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9871 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9497 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9351 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9295 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7933 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7856 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7627 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7540 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7438 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7389 | `npm run build && istanbul cover _mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7093 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6945 | `xo && mocha test/*.js --timeout 100000` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6889 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [almende/vis](https://github.com/almende/vis) | 6883 | `mocha --compilers js:babel-core/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6845 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6621 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7933 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7856 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7816 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7627 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7540 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7529 | `mocha --opts mocha.opts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7438 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7389 | `npm run build && istanbul cover _mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7383 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 7136 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7093 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7069 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6945 | `xo && mocha test/*.js --timeout 100000` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6889 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [almende/vis](https://github.com/almende/vis) | 6883 | `mocha --compilers js:babel-core/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6845 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6621 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6371 | `npm run jshint && mocha test/` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6187 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6184 | `npm run test:mocha:src` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6168 | `mocha --exit --require babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6143 | `mocha; jshint *.js lib` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6052 | `mocha test/test.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6045 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5939 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5931 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5826 | `mocha tests/node.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5820 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5735 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5685 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5648 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5517 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5500 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5408 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5374 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5371 | `mocha --timeout 10000 && npm run lint` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5226 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5172 | `mocha src/**/*Tests.js --harmony` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5166 | `standard && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5155 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5035 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4930 | `gulp lint && mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4868 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4860 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4837 | `mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4836 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4725 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4725 | `mocha test` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4713 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4695 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4687 | `mocha --reporter spec -t 8000` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4677 | `mocha test` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4569 | `mocha ./test/runner.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4558 | `./node_modules/.bin/mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4440 | `mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4429 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4414 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4380 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4335 | `nyc mocha --exit` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4330 | `mocha --recursive && make test` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4323 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4309 | `npm run lint && npm run mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4132 | `nyc mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4075 | `npm run lint && npm run mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4066 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4039 | `nyc mocha` | 
| [muicss/mui](https://github.com/muicss/mui) | 3998 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3989 | `mocha --require test/babel-hook test/*.js` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3966 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3961 | `node_modules/.bin/mocha test/tests.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3948 | `npm run lint ; mocha && mocha test/individual` | 
| [tj/ejs](https://github.com/tj/ejs) | 3948 | `mocha --require should --reporter spec` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3923 | `mocha --timeout=15000 tests/*.test.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3890 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3882 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3812 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [erming/shout](https://github.com/erming/shout) | 3804 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3747 | `mocha --check-leaks --reporter spec --bail` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3737 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3726 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3676 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3669 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3650 | `standard && mocha --timeout 60000 test/test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3644 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [primus/primus](https://github.com/primus/primus) | 3624 | `npm run build && mocha test/*.test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3613 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3595 | `nyc mocha "test/**/*.test.js"` | 
| [teambit/bit](https://github.com/teambit/bit) | 3576 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3573 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3563 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [expressjs/session](https://github.com/expressjs/session) | 3555 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3532 | `mocha --reporter spec --timeout 3000` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3530 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3527 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3501 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3481 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3456 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3448 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3434 | `mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3431 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3422 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3370 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3359 | `NODE_ENV=test mocha test/**/*.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3264 | `NODE_ENV=test mocha --exit` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3255 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3191 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3184 | `nyc mocha && tsc` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3174 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3171 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3000 | `mocha test/index.js && npm run demo` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2992 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2983 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2979 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2973 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2943 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2909 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2884 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2876 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2871 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2867 | `mocha -R spec --recursive src/test` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2863 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2856 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2909 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2884 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2876 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2871 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2869 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2867 | `mocha -R spec --recursive src/test` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2863 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2856 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2835 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2826 | `mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2823 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2821 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2818 | `istanbul cover _mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2804 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2800 | `mocha --opts mocha.opts` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2796 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [github-tools/github](https://github.com/github-tools/github) | 2791 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2773 | `npm run mocha && npm run lint` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2772 | `mocha --require should --reporter spec` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2753 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2726 | `mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2723 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2721 | `mocha --require babel-register --recursive spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2719 | `mocha test-node` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2707 | `mocha -R landing test/index` | 
| [css/csso](https://github.com/css/csso) | 2701 | `mocha --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2696 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2693 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2688 | `node_modules/.bin/mocha --reporter spec` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2638 | `mocha --timeout 100000` | 
| [mde/ejs](https://github.com/mde/ejs) | 2634 | `mocha --require should --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2629 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2620 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2608 | `mocha-phantomjs ./test/index.html` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2606 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2605 | `mocha --recursive --watch` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2345 | `nyc --reporter=html --reporter=text mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2344 | `grunt jshint && mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2341 | `mocha --no-colors --reporter spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2328 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2301 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2296 | `mocha -R spec` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2269 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2269 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2264 | `mocha test && npm run lint` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2230 | `mocha test test/unit/**/*_test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2230 | `mocha && eslint .` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2225 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2217 | `mocha test/index.js --reporter dot` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2345 | `nyc --reporter=html --reporter=text mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2344 | `grunt jshint && mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2341 | `mocha --no-colors --reporter spec` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2301 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2296 | `mocha -R spec` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2273 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2269 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2269 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2264 | `mocha test && npm run lint` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2273 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2269 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2269 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2264 | `mocha test && npm run lint` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2230 | `mocha test test/unit/**/*_test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2230 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2227 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2225 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2217 | `mocha test/index.js --reporter dot` | 
| [gajus/swing](https://github.com/gajus/swing) | 2214 | `mocha --compilers js:babel-register` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2028 | `mocha test/runner.js --reporter spec` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2012 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2011 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [slate/slate](https://github.com/slate/slate) | 2006 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1992 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1983 | `nyc npm run _mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1969 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1958 | `mocha --require=test/test_helper.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1951 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1946 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1946 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1934 | `mocha --reporter spec --timeout 5000` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1930 | `mocha` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1925 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1925 | `mocha --bail --reporter spec --check-leaks test/` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1925 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1922 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1919 | `mocha && eslint *.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1906 | `./node_modules/.bin/mocha && npm run jshint` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1902 | `mocha --require ./test/common --growl test/expect.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1897 | `npm run lint && mocha -R dot && npm run cover` | 
| [then/promise](https://github.com/then/promise) | 1897 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1886 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1875 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1873 | `mocha tests.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1848 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1832 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1821 | `mocha --reporter spec && npm run test-typescript` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1810 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1803 | `mocha --timeout 5000` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1802 | `npm run mocha && npm run karma` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1790 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1789 | `mocha -R spec spec spec/reporters` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1788 | `npm run lint && mocha --reporter spec test/*.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1776 | `mocha && npm run lint` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1775 | `mocha test` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1774 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1769 | `mocha --reporter spec test/*.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1768 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1712 | `mocha test -u bdd -R spec` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1696 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1683 | `npm run lint && mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1673 | `xo && mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1672 | `mocha ./test/basic.js -t 5000` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1668 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1662 | `mocha test/*.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1650 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1645 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1629 | `mocha --expose-gc --slow 300` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1627 | `mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1623 | `mocha && size-limit` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1683 | `npm run lint && mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1675 | `mocha test --timeout 600000` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1673 | `xo && mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1672 | `mocha ./test/basic.js -t 5000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1665 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1662 | `mocha test/*.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1650 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1648 | `npm run lint && npm run mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1645 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1642 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1633 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1632 | `mocha spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1629 | `mocha --expose-gc --slow 300` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1587 | `mocha compiled_tests/` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1577 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1564 | `./node_modules/mocha/bin/mocha -R spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1546 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1545 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1543 | `mocha test/setup.js test/spec/*.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1542 | `eslint --cache . && tsc && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1539 | `mocha tests.js` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1539 | `npm run test:lint && npm run test:mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1530 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1578 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1577 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1564 | `./node_modules/mocha/bin/mocha -R spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1546 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1545 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1543 | `mocha test/setup.js test/spec/*.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1542 | `eslint --cache . && tsc && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1539 | `mocha tests.js` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1539 | `npm run test:lint && npm run test:mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1537 | `mocha --reporter spec` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1531 | `standard "./src/*.js" && mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1530 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1518 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1510 | `mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1509 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1500 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1499 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1499 | `mocha test` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1497 | `mocha --check-leaks --reporter spec --bail` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1495 | `mocha -u tdd` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1492 | `mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1490 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1487 | `nyc mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1487 | `node_modules/.bin/mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1481 | `mocha -R spec` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1479 | `nyc npm run mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1467 | `mocha test/**/*.spec.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1463 | `mocha --recursive` | 
| [samccone/drool](https://github.com/samccone/drool) | 1453 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1448 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1438 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1409 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1409 | `mocha --timeout 10000 ./tests/lib.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1335 | `mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1333 | `mocha test/unit` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1319 | `mocha` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1316 | `istanbul cover _mocha test -- --timeout 20000` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1315 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1315 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1314 | `mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1314 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1311 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1310 | `./node_modules/.bin/mocha test` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1307 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1306 | `mocha-phantomjs tests/index.html` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1305 | `mocha --recursive` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1301 | `eslint src && mocha && karma start --single-run` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1293 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1293 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1306 | `mocha-phantomjs tests/index.html` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1305 | `mocha --recursive` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1301 | `eslint src && mocha && karma start --single-run` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1298 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1294 | `TEST=all mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1293 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1293 | `mocha spec/exec.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1279 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1278 | `mocha --reporter dot` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1271 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1263 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1263 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1262 | `mocha --timeout 60000 test/` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1254 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1250 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1245 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1242 | `mocha test/*.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1240 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1239 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1238 | `mocha tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1236 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1229 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1225 | `NODE_ENV=test mocha tests/*.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1219 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1212 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1210 | `mocha src/test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1207 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1207 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1206 | `mocha -R spec ./test/unit/**` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1203 | `mocha ./test/test*.js --reporter spec` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1203 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1203 | `mocha ./test/test*.js --reporter spec` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1203 | `mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1201 | `mocha --check-leaks --reporter spec --bail test/` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1200 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1198 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1196 | `node ./node_modules/mocha/bin/mocha tests` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1193 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1190 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [normalize/mz](https://github.com/normalize/mz) | 1190 | `mocha --reporter spec` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1190 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1188 | `mocha --recursive test/bin` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1187 | `npm run lint && npm run mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1186 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1181 | `istanbul test _mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1179 | `npm run prepublishOnly && mocha test/test.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1175 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1171 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1169 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1165 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1164 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1164 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [variety/variety](https://github.com/variety/variety) | 1171 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1169 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1168 | `mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1165 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1164 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1164 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1162 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1160 | `mocha --recursive test` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1151 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1150 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1146 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1145 | `mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1142 | `NODE_PATH=. mocha **/*.spec.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1140 | `mocha --compilers js:babel-core/register` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1135 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1122 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1120 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1117 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1117 | `mocha $(find test -name '*.test.js')` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1115 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1110 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1108 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1107 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1105 | `istanbul cover _mocha test/*.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1104 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1103 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1099 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1099 | `mocha test/*` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1094 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1094 | `node_modules/.bin/mocha && npm run lint` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1090 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1089 | `mocha --check-leaks -t 20000` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1085 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [router5/router5](https://github.com/router5/router5) | 1085 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1084 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1082 | `mocha` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1079 | `mocha --compilers js:babel-register` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1079 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1076 | `webpack && npm run lint && npm run mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1076 | `npm run lint && mocha --require @babel/register` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1074 | `standard && mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1072 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1068 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [electron/asar](https://github.com/electron/asar) | 1057 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1056 | `npm run mocha:istanbul` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1055 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1049 | `mocha --recursive --bail --reporter spec test` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1047 | `mocha test/tests.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1047 | `webpack && mocha test/unit` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1042 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1040 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1039 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1037 | `mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1037 | `mocha --reporter spec --timeout 3000` | 
| [electron/spectron](https://github.com/electron/spectron) | 1012 | `mocha && standard` | 
| [tomas/needle](https://github.com/tomas/needle) | 1011 | `mocha test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1011 | `eslint src test && mocha --compilers babel-register` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1009 | `mocha $(find test -name '*.test.js')` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1001 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1000 | `mocha --recursive test/unit/` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 993 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 992 | `mocha --async-only` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 990 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 983 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 981 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 993 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 992 | `mocha --async-only` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 990 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 983 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 981 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 977 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 974 | `mocha -R list` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 973 | `npm run rollup-cjs && mocha test/test.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 972 | `mocha --timeout 30000 --recursive ./tests` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 941 | `mocha "client.test" --compilers js:babel-register` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 939 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit/**/*-test.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 934 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 931 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 931 | `mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 928 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 928 | `mocha --compilers js:babel-register test/*.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 918 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 918 | `npm run lint && mocha -R spec` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 856 | `node_modules/.bin/mocha test/spec` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 855 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 855 | `eslint test && mocha --compilers js:babel/register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 854 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 853 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 853 | `mocha -t 5000` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 849 | `./node_modules/.bin/mocha -R spec` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 849 | `mocha test --compilers js:babel-register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 848 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 848 | `istanbul cover -- _mocha --reporter spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 847 | `./node_modules/.bin/mocha --reporter spec` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 842 | `mocha test` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 836 | `mocha --check-leaks -t 20000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 834 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 833 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 825 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 825 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 824 | `mocha --reporter list` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 824 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 823 | `mocha && ember test` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 821 | `nyc mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 819 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 816 | `nyc --check-coverage mocha test/*.test.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 815 | `npm run lint && mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 815 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 814 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 812 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 812 | `mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 811 | `mocha --recursive ./test/*_spec.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 808 | `mocha test/index.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 807 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 807 | `mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 807 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 806 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 805 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 804 | `mocha --require babel-register` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 804 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 803 | `cake build && mocha ./test/mocha/*.coffee` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 803 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 801 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 799 | `mocha --async-only` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 798 | `mocha test` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 796 | `mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 795 | `mocha -u tdd` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 795 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 788 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 788 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 785 | `mocha --colors --reporter spec test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 784 | `mocha --harmony --full-trace --check-leaks` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 782 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 780 | `npm run build && istanbul test _mocha test/test.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 777 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 777 | `npm run mocha-test test/integration` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 777 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 776 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 776 | `xo && mocha -R spec` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 776 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 775 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 772 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 772 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 770 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 768 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [developit/decko](https://github.com/developit/decko) | 767 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 767 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 766 | `mocha --ui tdd --require ./test/__setup` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 764 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 764 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 762 | `mocha -R spec src/**/*_test.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 756 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 755 | `mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 753 | `mocha --recursive -s 15 test/` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 753 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 753 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 753 | `mocha test` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 752 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 752 | `mocha --no-timeouts` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 751 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 743 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 738 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 736 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 735 | `mocha -r should --reporter spec test/*.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 735 | `mocha test` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 735 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 735 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 733 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 732 | `npm run lint && npm run mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 730 | `mocha tests/*.mocha.js` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 730 | `mocha test.js` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 729 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 726 | `mocha` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 726 | `mocha` | 
| [scality/S3](https://github.com/scality/S3) | 724 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 723 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 722 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 726 | `mocha` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 726 | `mocha` | 
| [scality/S3](https://github.com/scality/S3) | 724 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 723 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 722 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 722 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 722 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 722 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 722 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 719 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 719 | `babel-node node_modules/.bin/_mocha -- test` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 719 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 717 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 716 | `npm run bundle && mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 715 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [typicode/katon](https://github.com/typicode/katon) | 710 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 706 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 706 | `mocha --reporter spec build/test/index.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 703 | `mocha ./test/index.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 703 | `./bin/selenium-standalone install && mocha` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 702 | `npm run-script jshint && npm run-script mocha` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 698 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 698 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 696 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 680 | `mocha` | 
| [koajs/static](https://github.com/koajs/static) | 680 | `mocha --harmony --reporter spec --exit` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 679 | `npm run lint && mocha test` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 675 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 674 | `mocha` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 673 | `jenkins-mocha ./tests/*.js` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 673 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 672 | `mocha --compilers js:babel-core/register` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 672 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 671 | `mocha -b -R spec test/*` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 660 | `mocha -R spec` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 660 | `mocha --harmony tests/**` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 660 | `mocha --reporter spec --bail --check-leaks test/` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 658 | `mocha --reporter spec` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 658 | `mocha` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 657 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 656 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 655 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 654 | `./node_modules/.bin/mocha test/integration` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 653 | `mocha` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 651 | `mocha --compilers js:babel-register` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 649 | `./node_modules/.bin/mocha` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 649 | `mocha --recursive --compilers js:babel-core/register` | 
| [shime/livedown](https://github.com/shime/livedown) | 648 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 648 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 