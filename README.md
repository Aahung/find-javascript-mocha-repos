# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:50 10/14/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 43866 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41483 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 40553 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30437 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 27260 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24721 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 24710 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 23849 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 20347 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19381 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 17566 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17176 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17111 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 15748 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14428 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14290 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14105 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13459 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13081 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12759 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12497 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12268 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12251 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11768 | `nyc grunt mocha-and-karma` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 11641 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 11595 | `mocha --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10832 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10505 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10390 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10365 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10181 | `mocha --harmony` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10178 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 10147 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [websockets/ws](https://github.com/websockets/ws) | 9738 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 9522 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9485 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 9328 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9325 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9271 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9102 | `grunt mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9015 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 8951 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8929 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8641 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8567 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8485 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8374 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8307 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8259 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8126 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7950 | `npm run eslint && npm run mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7946 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7790 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7562 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7485 | `npm run build && istanbul cover _mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7470 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7462 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [aui/art-template](https://github.com/aui/art-template) | 7444 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7443 | `mocha` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7393 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7346 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [almende/vis](https://github.com/almende/vis) | 7194 | `mocha --compilers js:babel-core/register` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 7146 | `xo && mocha test/*.js --timeout 100000` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7021 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6989 | `mocha $HARMONY_OPTS` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6903 | `mocha; jshint *.js lib` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 6845 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6744 | `mocha --exit --require @babel/register` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 6711 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6612 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6413 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6368 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6293 | `npm run test:mocha:src` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6147 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6077 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6055 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6035 | `mocha tests/node.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5936 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5903 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5853 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5840 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5824 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 5815 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5784 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5553 | `standard && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5527 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5506 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5416 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5294 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5259 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5192 | `mocha src/**/*Tests.js --harmony` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5184 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5182 | `mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5153 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5050 | `gulp lint && mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4952 | `mocha test` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4878 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4824 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4821 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4797 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [santinic/how2](https://github.com/santinic/how2) | 4772 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4767 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4705 | `mocha --reporter spec -t 8000` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4693 | `./node_modules/.bin/mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4666 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4586 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4584 | `nyc mocha --exit` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4570 | `mocha ./test/runner.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4552 | `mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4464 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4459 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4458 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4438 | `nyc mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4346 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4299 | `mocha -R spec src` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 4214 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4205 | `mocha -R spec ./test --recursive` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4201 | `node_modules/.bin/mocha test/tests.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 4197 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4195 | `nyc mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4171 | `mocha --timeout=15000 tests/*.test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4148 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4111 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4099 | `npm run lint ; mocha && mocha test/individual` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4067 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4062 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4022 | `mocha --require should --reporter spec` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4004 | `mocha --check-leaks --reporter spec --bail` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3957 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3905 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3869 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3830 | `nyc mocha "test/**/*.test.js"` | 
| [erming/shout](https://github.com/erming/shout) | 3797 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3779 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3766 | `NODE_ENV=test mocha --exit` | 
| [expressjs/session](https://github.com/expressjs/session) | 3749 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3741 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [primus/primus](https://github.com/primus/primus) | 3691 | `npm run build && mocha test/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3677 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3667 | `npm run jshint && npm run mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3647 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3614 | `NODE_ENV=test mocha test/**/*.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3605 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3583 | `mocha tests/javascript` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3578 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3576 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3566 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3554 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3553 | `mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3531 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3492 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3470 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3461 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3444 | `mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3398 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3379 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3335 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3323 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3091 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3076 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3058 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3035 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2998 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2994 | `mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2966 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2931 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2921 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2907 | `mocha -R spec --recursive src/test` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2905 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2897 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2895 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2882 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3058 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3035 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3027 | `eslint . && mocha -t 5000` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3002 | `mocha -R landing test/index` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2998 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2994 | `mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2966 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2931 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2921 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2907 | `mocha -R spec --recursive src/test` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2905 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2897 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2895 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2882 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 2864 | `mocha --require should --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2860 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2837 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2835 | `mocha --require babel-register --recursive spec` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2831 | `mocha -R spec spec spec/reporters` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2831 | `istanbul cover _mocha` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2830 | `mocha test-node` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2826 | `node_modules/.bin/mocha --reporter spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2825 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2809 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2809 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2795 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2784 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2773 | `mocha --require should --reporter spec` | 
| [css/csso](https://github.com/css/csso) | 2752 | `mocha --reporter dot` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2743 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2728 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2713 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2695 | `npm run build && cd test && mocha . --reporter dot` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2683 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2679 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2675 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2658 | `mocha --timeout 100000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2650 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2630 | `nyc mocha --timeout=10000` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2624 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2618 | `mocha-phantomjs ./test/index.html` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2598 | `nyc mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2575 | `mocha "test/**/*-test.js"` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2574 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2535 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2529 | `mocha test/unit --require mochahook` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2528 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2524 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2510 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2487 | `mocha test` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2482 | `mocha --reporter=spec test/*-test.js` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2482 | `mocha test/src/**/*.unit.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2477 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2454 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2423 | `nyc --reporter=html --reporter=text mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2420 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2403 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2314 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2303 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2296 | `mocha -R spec test/*.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2285 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2284 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [retejs/rete](https://github.com/retejs/rete) | 2278 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2247 | `mocha --compilers js:babel-register` | 
| [gajus/swing](https://github.com/gajus/swing) | 2245 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 2237 | `mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2229 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2222 | `mocha test test/unit/**/*_test.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2020 | `mocha --compilers js:babel-core/register __tests__` | 
| [slate/slate](https://github.com/slate/slate) | 1998 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1996 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1990 | `./node_modules/.bin/mocha && npm run jshint` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1975 | `mocha --reporter spec --timeout 5000` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1962 | `mocha -c test/index.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1952 | `mocha test/*.test.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1949 | `npm run lint && mocha -R dot && npm run cover` | 
| [then/promise](https://github.com/then/promise) | 1944 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1936 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1936 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1926 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1919 | `npm run mocha && npm run karma` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1917 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1908 | `mocha --compilers js:babel-register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1893 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1885 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1877 | `mocha tests.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1877 | `mocha --reporter spec && npm run test-typescript` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1860 | `mocha && npm run lint` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1844 | `mocha` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1842 | `npm run lint && mocha --reporter spec test/*.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1819 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1817 | `mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1816 | `mocha test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1813 | `mocha test -u bdd -R spec` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1811 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1808 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1792 | `npm run lint && npm run mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1764 | `mocha ./test/basic.js -t 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1761 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1745 | `mocha test` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1734 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1745 | `mocha test` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1734 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1733 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1728 | `mocha test/**/*_test.js --bail` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1728 | `mocha compiled_tests/` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1724 | `npm run lint && npm run mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1722 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1721 | `./node_modules/.bin/mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1716 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1709 | `mocha test --timeout 600000` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1706 | `mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1700 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1700 | `mocha test/* --reporter spec` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1692 | `mocha test/*.js` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1687 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1663 | `xo && mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1655 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1649 | `eslint --cache . && tsc && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1645 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1645 | `mocha && size-limit` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1638 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1634 | `mocha tests/test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1633 | `mocha --expose-gc --slow 300` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1631 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [zeit/ms](https://github.com/zeit/ms) | 1630 | `mocha tests.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1624 | `mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1617 | `standard "./src/*.js" && mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1616 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1608 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1607 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1631 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [zeit/ms](https://github.com/zeit/ms) | 1630 | `mocha tests.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1624 | `mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1617 | `standard "./src/*.js" && mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1616 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1608 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1607 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1594 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1589 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1588 | `./node_modules/mocha/bin/mocha -R spec` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1585 | `mocha --check-leaks --reporter spec --bail` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1579 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1577 | `mocha --reporter spec` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1535 | `TEST=all mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1535 | `mocha --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1532 | `nyc mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1524 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1521 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1516 | `mocha -u tdd` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1489 | `mocha test/**/*.spec.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1466 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1458 | `mocha test/unit` | 
| [samccone/drool](https://github.com/samccone/drool) | 1454 | `mocha test/tests.js --timeout=10000` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1451 | `NODE_ENV=test mocha tests/*.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1451 | `mocha --check-leaks --require @babel/register` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1447 | `mocha test.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1443 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1441 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1436 | `mocha -R spec test/*.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1429 | `mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1426 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1422 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1419 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1412 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1408 | `mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1407 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1405 | `mocha -R spec ./test/unit/**` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1403 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1395 | `mocha ./test/test*.js --reporter spec` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1393 | `istanbul cover _mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1387 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1387 | `npm run build && mocha -r should` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1387 | `mocha tests/test-*` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1377 | `mocha --opts test/opts/mocha.opts` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1377 | `standard && istanbul cover _mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1372 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1368 | `mocha --reporter dot` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1361 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1359 | `cross-env NODE_ENV=test nyc mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1359 | `npm run lint && npm run mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1354 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1412 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1408 | `mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1407 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1405 | `mocha -R spec ./test/unit/**` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1403 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1395 | `mocha ./test/test*.js --reporter spec` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1393 | `istanbul cover _mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1387 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1387 | `npm run build && mocha -r should` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1387 | `mocha tests/test-*` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1377 | `mocha --opts test/opts/mocha.opts` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1377 | `standard && istanbul cover _mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1372 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1368 | `mocha --reporter dot` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1361 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1291 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1289 | `mocha --recursive test` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1282 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1276 | `mocha test/*.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1271 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1266 | `mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1265 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1259 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1256 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1252 | `mocha tests` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1251 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1249 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1248 | `mocha src/test.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1247 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1242 | `npm run lint && npm run mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1238 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1237 | `istanbul test _mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1236 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1233 | `mocha --compilers js:babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1232 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1229 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1223 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1216 | `webpack && npm run lint && npm run mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1214 | `mocha test/test.js` | 
| [variety/variety](https://github.com/variety/variety) | 1214 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [normalize/mz](https://github.com/normalize/mz) | 1213 | `mocha --reporter spec` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1211 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1209 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1204 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1203 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1202 | `npm run lint && mocha --require @babel/register` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1204 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1203 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1202 | `npm run lint && mocha --require @babel/register` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1199 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1198 | `mocha test` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1192 | `npm run mocha:istanbul` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1189 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1184 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1183 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1180 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1174 | `mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1173 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1158 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1154 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1143 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1138 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1136 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1135 | `istanbul cover _mocha test/*.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1135 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1134 | `mocha $(find test -name '*.test.js') --exit` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1134 | `xo && mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1133 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1130 | `mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1091 | `npm-run-all test:jest test:server:mocha` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1089 | `mocha --check-leaks -t 20000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1088 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1088 | `mocha --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1086 | `mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1080 | `mocha --compilers js:babel-register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1073 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1072 | `mocha --recursive --bail --reporter spec test` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1072 | `standard && mocha -b` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1058 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1057 | `mocha && standard` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1072 | `mocha --recursive --bail --reporter spec test` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1072 | `standard && mocha -b` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1071 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1066 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1063 | `mocha test/tests.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1058 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1057 | `mocha && standard` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1053 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1053 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1045 | `eslint src test && mocha --compilers babel-register` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [tomas/needle](https://github.com/tomas/needle) | 1042 | `mocha test` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1038 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1035 | `npm run convertto:es5 && npm run mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1034 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1034 | `mocha --reporter spec --timeout 3000` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1033 | `mocha --recursive -r tests/setup tests` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1033 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1027 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1026 | `mocha --async-only` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1024 | `mocha $(find test -name '*.test.js')` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1023 | `mocha --reporter spec test --recursive` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1021 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1010 | `mocha --recursive test/unit/` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1008 | `mocha --colors ./test/*.spec.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1008 | `mocha --check-leaks -R dot` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 994 | `mocha -R list` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 994 | `mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 992 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 991 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 988 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 985 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 984 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 974 | `npm run rollup-cjs && mocha test/test.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 973 | `mocha --reporter spec` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 972 | `mocha test` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 970 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 967 | `mocha --reporter spec --bail --check-leaks test/` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 963 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 961 | `mocha "client.test" --compilers js:babel-register` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 960 | `mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 958 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 921 | `mocha -t 600000` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 921 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 918 | `mocha test` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 917 | `./node_modules/.bin/mocha --reporter spec` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 907 | `nyc --check-coverage mocha test/*.test.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 906 | `mocha` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 905 | `./node_modules/.bin/mocha -R spec` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 905 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 905 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 903 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 903 | `nyc mocha specs` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 903 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 902 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 931 | `mocha spec/*.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 930 | `mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 929 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 929 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 926 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 921 | `mocha -t 600000` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 921 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 918 | `mocha test` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 917 | `./node_modules/.bin/mocha --reporter spec` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 911 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 907 | `nyc --check-coverage mocha test/*.test.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 906 | `mocha` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 905 | `./node_modules/.bin/mocha -R spec` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 905 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 903 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 903 | `nyc mocha specs` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 902 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 900 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 898 | `mocha --recursive ./test/*_spec.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 895 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 893 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 891 | `mocha` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 890 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 889 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 887 | `node_modules/.bin/mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 887 | `mocha test --compilers js:babel-register` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 887 | `node_modules/.bin/mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 887 | `mocha test --compilers js:babel-register` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 886 | `./node_modules/.bin/mocha --globals angular,require` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 883 | `istanbul cover -- _mocha --reporter spec` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 880 | `npm run lint && npm run mocha:no-functional` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 880 | `standard && standard ./bin/* && mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 878 | `mocha -t 5000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 875 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 874 | `mocha --timeout 200000` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 870 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 870 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 869 | `node_modules/.bin/mocha test/spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 866 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 866 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 858 | `mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 858 | `eslint test && mocha --compilers js:babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 855 | `mocha test/index.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 855 | `mocha --reporter list` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 855 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 855 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 850 | `istanbul cover _mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 850 | `mocha --reporter spec` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 849 | `mocha test` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 847 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 835 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 832 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 832 | `mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 831 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 831 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 831 | `mocha` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 828 | `mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 826 | `mocha && ember test` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 823 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 823 | `./node_modules/.bin/mocha test/**/*` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 821 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 820 | `npm run build && istanbul test _mocha test/test.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 817 | `mocha --async-only` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 816 | `mocha --harmony --full-trace --check-leaks` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 816 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 821 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 820 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 820 | `npm run build && istanbul test _mocha test/test.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 817 | `mocha --async-only` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 816 | `mocha --harmony --full-trace --check-leaks` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 816 | `mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 816 | `mocha --opts mocha.opts` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 815 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 815 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 815 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 814 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 811 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 808 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 808 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 807 | `mocha --colors --reporter spec test.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 807 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 806 | `mocha` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 808 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 808 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 807 | `mocha --colors --reporter spec test.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 807 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 806 | `mocha` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 804 | `mocha` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 802 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 799 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 798 | `npm run mocha-test test/integration` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 797 | `mocha -R spec tests/` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 796 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 796 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 794 | `mocha -r should --reporter spec test/*.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 794 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 793 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 784 | `xo && mocha -R spec` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 784 | `mocha --recursive` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 783 | `mocha test` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 781 | `mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 779 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 777 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 776 | `mocha` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 774 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 772 | `nyc mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 770 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 769 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 768 | `mocha --recursive -s 15 test/` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 753 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 753 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 749 | `mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 749 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 747 | `babel-node node_modules/.bin/_mocha -- test` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 747 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 746 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 746 | `npm run lint && npm run mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 744 | `nyc mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 753 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 753 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 749 | `mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 749 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 747 | `babel-node node_modules/.bin/_mocha -- test` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 747 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 746 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 746 | `npm run lint && npm run mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 744 | `nyc mocha` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 744 | `mocha test/mocha.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 742 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 742 | `mocha --harmony tests/**` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 740 | `mocha tests/*.mocha.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 739 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 739 | `npm run-script jshint && npm run-script mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 738 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 737 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 735 | `mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 733 | `npm run bundle && mocha` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 733 | `npm run lint && mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 732 | `mocha --reporter spec build/test/index.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 