# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:40 02/05/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45099 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42229 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42072 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30872 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 25936 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25675 | `nyc mocha --timeout=10000 --exit` | 
| [caolan/async](https://github.com/caolan/async) | 25199 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25146 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21435 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20131 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18514 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18051 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17899 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17437 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14991 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14712 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13984 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13690 | `mocha --globals document test` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13690 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13198 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13020 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12792 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12789 | `istanbul cover _mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12497 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12480 | `mocha --require @babel/register --reporter dot` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12355 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12308 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11556 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11214 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11182 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10912 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10659 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10531 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10430 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9798 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9784 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9710 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9544 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9444 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9421 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9328 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9001 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8917 | `mocha test/src` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8576 | `mocha --check-leaks -R dot` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8324 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8299 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8269 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8134 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8056 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8026 | `./node_modules/.bin/mocha test` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7997 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7936 | `mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7922 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7880 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7609 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7584 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [almende/vis](https://github.com/almende/vis) | 7563 | `mocha --compilers js:babel-core/register` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7508 | `mocha --exit --require @babel/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7506 | `mocha; jshint *.js lib` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7609 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7584 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [almende/vis](https://github.com/almende/vis) | 7563 | `mocha --compilers js:babel-core/register` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7508 | `mocha --exit --require @babel/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7506 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7505 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7449 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7220 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7186 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7112 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7047 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6919 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6888 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6582 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6403 | `npm run test:mocha:src` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6300 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6280 | `mocha tests/node.js` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6266 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6226 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6215 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6144 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6106 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6023 | `standard && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5931 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5891 | `mocha && eslint lib/**` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 5791 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5775 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5772 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5744 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5706 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5637 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5579 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5576 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 5573 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5414 | `mocha test` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5404 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5399 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5348 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5322 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5209 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5135 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5125 | `gulp lint && mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5098 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5067 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5008 | `npm run lint && npm run mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4964 | `gulp build; mocha;` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4962 | `nyc mocha --exit` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4961 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4918 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4899 | `./node_modules/.bin/mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4888 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4861 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4853 | `mocha test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4847 | `nyc mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4840 | `mocha` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4284 | `npm run lint ; mocha && mocha test/individual` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4238 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4192 | `mocha -R spec ./test --recursive` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4169 | `npm run build && cd test && mocha . --reporter dot` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4132 | `mocha --require test/babel-hook test/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4096 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4095 | `mocha --require should --reporter spec` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4076 | `nyc mocha "test/**/*.test.js"` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4066 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [expressjs/session](https://github.com/expressjs/session) | 4009 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4006 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3948 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3932 | `export TESTING=true; mocha --reporter list` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3911 | `NODE_ENV=test mocha test/**/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3858 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3831 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3821 | `npm run build && mocha test/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3794 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3789 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3789 | `npm run mocha` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3761 | `mocha && tsc -p ./test/types` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3756 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3739 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3730 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3727 | `eslint . && mocha -t 5000` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3690 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3684 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3671 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3670 | `node_modules/.bin/mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3667 | `npm run jshint && npm run mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3613 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3595 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3586 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3553 | `nyc mocha && tsc` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3491 | `node_modules/.bin/mocha test/lib/` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3488 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3485 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3465 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3447 | `mocha` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3442 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3431 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3425 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3397 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3391 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3397 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3391 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3377 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3375 | `mocha -R landing test/index --exit` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3369 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3329 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3316 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3308 | `mocha test/index.js && npm run demo` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3259 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3236 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 3236 | `./node_modules/mocha/bin/mocha --require babel-core/register test/*` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3229 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3226 | `mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3217 | `mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 3214 | `mocha --require should --reporter spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2998 | `mocha test-node` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2981 | `mocha --require @babel/register --recursive spec` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2967 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2965 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2946 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2918 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2909 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2908 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2900 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2898 | `mocha -R spec spec spec/reporters` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2847 | `istanbul cover _mocha` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2845 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2839 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [retejs/rete](https://github.com/retejs/rete) | 2828 | `BABEL_ENV=test mocha --compilers js:@babel/register` | 
| [css/csso](https://github.com/css/csso) | 2822 | `mocha --reporter dot` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2787 | `mocha --require should --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2787 | `mocha --require should --reporter spec` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2770 | `mocha "./test/**/*-test.js"` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2765 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2764 | `xo && mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2764 | `mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2720 | `nyc mocha --timeout=10000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2716 | `nyc mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2715 | `mocha --recursive --watch` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2688 | `mocha --timeout 100000` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2680 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2674 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2654 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2321 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 2299 | `npm run lint && npm run mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2292 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2287 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2267 | `mocha test/**/*.coffee` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2251 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2229 | `npm run lint && mocha tests/**/*.js` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2207 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2197 | `mocha test/runner.js --reporter spec` | 
| [share/sharedb](https://github.com/share/sharedb) | 2191 | `./node_modules/.bin/mocha && npm run jshint` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2186 | `cross-env BABEL_ENV=test mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1966 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1963 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1959 | `mocha --reporter spec && npm run test-typescript` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1952 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1951 | `mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1951 | `bmocha --reporter spec test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1935 | `npm run lint && mocha --reporter spec test/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1918 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1918 | `mocha test` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1892 | `mocha` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1879 | `mocha tests.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1845 | `npm run lint && npm run mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1820 | `eslint --cache . && tsc && mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1816 | `npm run lint && npm run mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2111 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2060 | `npm run mocha && npm run karma` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2049 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2047 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2034 | `mocha && npm run lint` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2023 | `mocha --reporter spec --timeout 5000` | 
| [then/promise](https://github.com/then/promise) | 2013 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2004 | `mocha --require=test/test_helper.js` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2383 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2367 | `node node_modules/mocha/bin/_mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2321 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2313 | `mocha --compilers js:babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2308 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [pahen/madge](https://github.com/pahen/madge) | 2299 | `npm run lint && npm run mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2292 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2287 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2267 | `mocha test/**/*.coffee` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2254 | `standard && mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2251 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2251 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2243 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2229 | `npm run lint && mocha tests/**/*.js` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2211 | `mocha && eslint *.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2207 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2197 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2191 | `mocha --timeout 10000 --bail --exit test/*-test.js test/security/*.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 2191 | `./node_modules/.bin/mocha && npm run jshint` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2186 | `cross-env BABEL_ENV=test mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2160 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2151 | `mocha --compilers js:babel-register` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2150 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2136 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2136 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2136 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2111 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 2079 | `mocha test/*.test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2060 | `npm run mocha && npm run karma` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2053 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2049 | `npm run lint && mocha -R dot && npm run cover` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2049 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2060 | `npm run mocha && npm run karma` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2053 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2049 | `npm run lint && mocha -R dot && npm run cover` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2049 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2047 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2044 | `mocha tests --require @babel/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2034 | `mocha && npm run lint` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2026 | `mocha test` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2023 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2023 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 2013 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2004 | `mocha --require=test/test_helper.js` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1992 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1934 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1906 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1901 | `mocha compiled_tests/` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1892 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1881 | `mocha ./test/basic.js -t 5000` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1864 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1864 | `nyc mocha --timeout=20000 test.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1845 | `npm run lint && npm run mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1802 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1797 | `mocha --timeout 5000` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1795 | `mocha --recursive` | 
| [zeit/ms](https://github.com/zeit/ms) | 1771 | `mocha tests.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1762 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1762 | `npm run lint && mocha && npm run typescript` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1749 | `mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1749 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1743 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1742 | `mocha test/*.js` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1739 | `./node_modules/.bin/mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1734 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1728 | `mocha test --timeout 600000` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1726 | `mocha ./test/test*.js --reporter spec` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1724 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1719 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1716 | `mocha --check-leaks --reporter spec --bail` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1716 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1810 | `mocha test/setup.js test/spec/*.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1802 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1797 | `mocha --timeout 5000` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1795 | `mocha --recursive` | 
| [zeit/ms](https://github.com/zeit/ms) | 1771 | `mocha tests.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1762 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1762 | `npm run lint && mocha && npm run typescript` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1749 | `mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1749 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1743 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1742 | `mocha test/*.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1561 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1558 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1547 | `mocha --check-leaks --require @babel/register` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1542 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1539 | `mocha -u tdd` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1529 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1525 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1513 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1508 | `mocha --timeout 10000 ./tests/lib.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1508 | `mocha test/**/*.spec.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1502 | `mocha -R spec test/*.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1494 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1627 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1625 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1624 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1620 | `mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1616 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1615 | `./node_modules/mocha/bin/mocha -R spec` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1613 | `mocha --recursive` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1611 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1607 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1588 | `mocha test/unit` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1582 | `mocha -R spec ./test/unit/**` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1578 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1588 | `mocha test/unit` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1582 | `mocha -R spec ./test/unit/**` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1578 | `nyc mocha` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1578 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1567 | `mocha tests/test-*` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1558 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1549 | `npm run test:lint && npm run test:mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1547 | `mocha --check-leaks --require @babel/register` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1543 | `node_modules/.bin/mocha --recursive` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1542 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1397 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1395 | `webpack && npm run lint && npm run mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1395 | `mocha --recursive` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1391 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1386 | `./node_modules/mocha/bin/mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1382 | `npm run mocha:istanbul` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1375 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1374 | `./node_modules/.bin/mocha test` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1371 | `cross-env NODE_ENV=test nyc mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1371 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1366 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1365 | `mocha --compilers js:babel-core/register` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1360 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1356 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1350 | `npm run lint && mocha --require @babel/register` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1483 | `mocha --recursive test` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1475 | `npm run prepublishOnly && mocha test/test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1475 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1474 | `mocha --reporter dot` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1471 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1471 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1470 | `mocha --opts test/opts/mocha.opts` | 
| [samccone/drool](https://github.com/samccone/drool) | 1460 | `mocha test/tests.js --timeout=10000` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1458 | `mocha test --compilers js:babel-core/register` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1454 | `mocha test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1446 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1440 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1428 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1424 | `npm run build && mocha -r should` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1424 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1421 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [electron/devtron](https://github.com/electron/devtron) | 1416 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1407 | `istanbul cover _mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1406 | `mocha --recursive test/bin` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1397 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1395 | `webpack && npm run lint && npm run mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1395 | `mocha --check-leaks --reporter spec --bail test/` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1391 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1382 | `npm run mocha:istanbul` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1375 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1371 | `cross-env NODE_ENV=test nyc mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1371 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1370 | `NODE_PATH=. mocha **/*.spec.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1365 | `mocha --compilers js:babel-core/register` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1360 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1356 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1346 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1335 | `lerna run test && mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1310 | `npm run lint && npm run mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1309 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1305 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1301 | `mocha --timeout 30000 --recursive ./tests` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1299 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1297 | `mocha --timeout 20000` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1295 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1293 | `mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1275 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1268 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1265 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1242 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1242 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1239 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1230 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1227 | `node ./node_modules/mocha/bin/mocha tests` | 
| [poooi/poi](https://github.com/poooi/poi) | 1225 | `mocha --recursive --harmony --require ./test/babelhook` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1219 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1189 | `mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1183 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1183 | `xo && mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1182 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1212 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1199 | `mocha --recursive -r tests/setup tests` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1189 | `npm-run-all test:jest test:server:mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1183 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1183 | `xo && mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1183 | `mocha --reporter spec --bail --check-leaks test/` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1182 | `mocha test` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1182 | `mocha --reporter spec --bail --check-leaks test/` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1171 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1169 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1167 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1166 | `mocha --reporter spec test --recursive` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1160 | `mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1183 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1183 | `xo && mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1183 | `mocha --reporter spec --bail --check-leaks test/` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1182 | `mocha test` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1182 | `mocha --reporter spec --bail --check-leaks test/` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1171 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1169 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1167 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1166 | `mocha --reporter spec test --recursive` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1160 | `mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1156 | `istanbul cover _mocha test/*.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1147 | `webpack && mocha test/unit` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1067 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1067 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1065 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1057 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1067 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1065 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1057 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1049 | `mocha $(find test -name '*.test.js')` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1034 | `mocha --recursive test/unit/` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 1029 | `mocha --recursive ./test/*_spec.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1022 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1016 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 966 | `mocha` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 966 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 966 | `mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 964 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 963 | `./node_modules/.bin/mocha --reporter spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 961 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 959 | `nyc mocha specs` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 952 | `mocha test --compilers js:babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 951 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 950 | `mocha` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 947 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 939 | `mocha --timeout 5000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 938 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 951 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 950 | `mocha` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 948 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 946 | `./node_modules/.bin/mocha test/**/*` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 939 | `mocha --timeout 5000` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 933 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 933 | `standard && standard ./bin/* && mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 919 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 918 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 916 | `mocha -t 5000` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 913 | `mocha test/index.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 911 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 910 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 897 | `node_modules/.bin/mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 897 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 899 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 897 | `node_modules/.bin/mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 897 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 894 | `mocha --timeout 200000` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 887 | `npm run build && istanbul test _mocha test/test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 886 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 862 | `mocha --reporter spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 862 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 861 | `mocha` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 860 | `mocha --harmony tests/**` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 859 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 857 | `mocha --reporter spec --bail --check-leaks test/` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 856 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 856 | `mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 855 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 853 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 851 | `npm run lint && mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 851 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 848 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [developit/decko](https://github.com/developit/decko) | 847 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 843 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 842 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 839 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 839 | `mocha --async-only` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 835 | `mocha test` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 834 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 851 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 850 | `npm run lint && mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 849 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 849 | `mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 848 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [developit/decko](https://github.com/developit/decko) | 847 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 845 | `mocha --opts mocha.opts` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 843 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 842 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 839 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 839 | `mocha --async-only` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 835 | `mocha test` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 839 | `mocha --async-only` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 835 | `nyc mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 835 | `mocha test` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 834 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 829 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 829 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 826 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 825 | `mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 824 | `npm run mocha-test test/integration` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 821 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 825 | `mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 824 | `npm run mocha-test test/integration` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 821 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 818 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 818 | `mocha --colors --reporter spec test.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 818 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 817 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 813 | `cake build && mocha ./test/mocha/*.coffee` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 812 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 811 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 810 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 809 | `mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 807 | `mocha index.test.js` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 806 | `mocha test/mocha.js` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 804 | `_mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 803 | `mocha test` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 800 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 800 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 799 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 798 | `xo && mocha -R spec` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 797 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 796 | `mocha --no-timeouts` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 796 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 795 | `mocha` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 795 | `mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 767 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 767 | `npm run-script jshint && npm run-script mocha` | 
| [susam/texme](https://github.com/susam/texme) | 764 | `standard && mocha` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 763 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 762 | `mocha --reporter spec build/test/index.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 761 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 761 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 760 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 751 | `mocha tests/*.mocha.js` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 778 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 775 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 775 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 774 | `babel-node node_modules/.bin/_mocha -- test` | 
| [koajs/static](https://github.com/koajs/static) | 773 | `mocha --harmony --reporter spec --exit` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 773 | `mocha tests --timeout 10000` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 767 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 767 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 767 | `npm run-script jshint && npm run-script mocha` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 668 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [expressjs/cookie-session](https://github.com/expressjs/cookie-session) | 666 | `mocha --check-leaks --reporter spec --bail test/` | 
| [coinbase/gdax-node](https://github.com/coinbase/gdax-node) | 663 | `mocha --full-trace --ui tdd --bail --reporter spec tests/*.js` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 663 | `mocha` | 
| [godaddy/terminus](https://github.com/godaddy/terminus) | 661 | `mocha index.spec.js lib/**/*.spec.js && npm run test-typings` | 
| [joaonuno/tree-model-js](https://github.com/joaonuno/tree-model-js) | 660 | `istanbul cover _mocha` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 659 | `mocha --reporter spec` | 
| [shelljs/shx](https://github.com/shelljs/shx) | 658 | `nyc --reporter=text --reporter=lcov mocha` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 658 | `mocha` | 
| [maxkueng/victor](https://github.com/maxkueng/victor) | 658 | `mocha --ui bdd --reporter spec` | 
| [theoephraim/node-google-spreadsheet](https://github.com/theoephraim/node-google-spreadsheet) | 657 | `node_modules/.bin/mocha` | 
| [catamphetamine/universal-webpack](https://github.com/catamphetamine/universal-webpack) | 656 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 656 | `mocha` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 654 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [calmm-js/partial.lenses](https://github.com/calmm-js/partial.lenses) | 653 | `nyc mocha && nyc report -r html mocha` | 
| [chao/RESTClient](https://github.com/chao/RESTClient) | 653 | `mocha` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 653 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [gtanner/qrcode-terminal](https://github.com/gtanner/qrcode-terminal) | 653 | `./node_modules/jshint/bin/jshint lib vendor && node example/basic.js && ./node_modules/mocha/bin/mocha -R nyan` | 
| [LouisBarranqueiro/reapop](https://github.com/LouisBarranqueiro/reapop) | 652 | `babel-node ./node_modules/karma/bin/karma start ./build/karma.conf.js --reporters mocha` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 651 | `./node_modules/.bin/mocha test/integration` | 