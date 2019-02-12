# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:42 02/12/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45164 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42354 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42196 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30896 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25767 | `nyc mocha --timeout=10000 --exit` | 
| [caolan/async](https://github.com/caolan/async) | 25220 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25202 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21501 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20157 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18563 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18086 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17938 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17521 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15349 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15027 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14720 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14011 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13722 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13260 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13039 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12808 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12801 | `istanbul cover _mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12543 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12518 | `mocha --require @babel/register --reporter dot` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12357 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12343 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11610 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11285 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11211 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10930 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [websockets/ws](https://github.com/websockets/ws) | 10576 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10442 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9848 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9800 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9714 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9575 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9455 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9453 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9338 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9073 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8936 | `mocha test/src` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8826 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8707 | `mocha test/test.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8826 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8707 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8608 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8582 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8472 | `grunt clean:test && mocha --exit` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8380 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8318 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8276 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8187 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8063 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8042 | `./node_modules/.bin/mocha test` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8023 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7959 | `mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7951 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7886 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7615 | `npm run build && istanbul cover _mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7588 | `mocha --compilers js:babel-core/register` | 
| [dthree/cash](https://github.com/dthree/cash) | 7583 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7547 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7536 | `mocha --exit --require @babel/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7525 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7451 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7249 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7203 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7123 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7064 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6973 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6906 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6594 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6412 | `npm run test:mocha:src` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6320 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6299 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6284 | `mocha tests/node.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6242 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6225 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6168 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6113 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6044 | `standard && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5933 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5895 | `mocha && eslint lib/**` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 5888 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5800 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5789 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5789 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5716 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5654 | `npm run lint && mocha tests/**/*.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 5653 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5608 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5583 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5427 | `mocha test` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5414 | `mocha -r esm` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5406 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5361 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5354 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5211 | `mocha src/**/*Tests.js --harmony` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5134 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5132 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5128 | `gulp lint && mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5084 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5038 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4975 | `nyc mocha --exit` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4974 | `gulp build; mocha;` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4923 | `nyc mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4920 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4909 | `./node_modules/.bin/mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4891 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4867 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4857 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4844 | `mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4752 | `mocha --reporter spec -t 8000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4685 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4640 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4585 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4562 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4485 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4456 | `mocha --timeout=15000 tests/*.test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4431 | `NODE_ENV=test mocha --exit` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4427 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4394 | `mocha --check-leaks --reporter spec --bail` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4387 | `node_modules/.bin/mocha test/tests.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4387 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4343 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4288 | `npm run lint ; mocha && mocha test/individual` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4247 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4238 | `nyc mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4201 | `npm run build && cd test && mocha . --reporter dot` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4193 | `mocha -R spec ./test --recursive` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4135 | `mocha --require test/babel-hook test/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4100 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4098 | `mocha --require should --reporter spec` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4089 | `nyc mocha "test/**/*.test.js"` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4089 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 4026 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4015 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3957 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3936 | `export TESTING=true; mocha --reporter list` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3929 | `NODE_ENV=test mocha test/**/*.js` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3863 | `npm run mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3859 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3830 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3826 | `npm run build && mocha test/*.test.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3800 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [erming/shout](https://github.com/erming/shout) | 3796 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3783 | `mocha && tsc -p ./test/types` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3767 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3744 | `mocha test/* --reporter spec` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3738 | `eslint . && mocha -t 5000` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3736 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3701 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3684 | `standard && mocha --timeout 60000 test/test.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3676 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3675 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 3644 | `./node_modules/mocha/bin/mocha --require babel-core/register test/*` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3626 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3604 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3599 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3586 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3559 | `nyc mocha && tsc` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3440 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3431 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3407 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3402 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3387 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3378 | `mocha -R landing test/index --exit` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3337 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3332 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3315 | `mocha test/index.js && npm run demo` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3265 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3242 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3235 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3233 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3230 | `mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 3226 | `mocha --require should --reporter spec` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3315 | `mocha test/index.js && npm run demo` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3265 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3242 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3235 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3233 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3230 | `mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 3226 | `mocha --require should --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3188 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3186 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3175 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3168 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3166 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3118 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3103 | `nyc mocha --recursive` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2844 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [retejs/rete](https://github.com/retejs/rete) | 2843 | `BABEL_ENV=test mocha --compilers js:@babel/register` | 
| [css/csso](https://github.com/css/csso) | 2824 | `mocha --reporter dot` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2785 | `mocha "./test/**/*-test.js"` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2765 | `xo && mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2762 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2720 | `nyc mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2720 | `nyc mocha --timeout=10000` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2692 | `mocha --timeout 100000` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2687 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2679 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2660 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2634 | `mocha-phantomjs ./test/index.html` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2785 | `mocha "./test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2768 | `mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2767 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2765 | `xo && mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2762 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2720 | `nyc mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2720 | `nyc mocha --timeout=10000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2716 | `mocha --recursive --watch` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2692 | `mocha --timeout 100000` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2687 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2679 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2660 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2634 | `mocha-phantomjs ./test/index.html` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2037 | `mocha test/test-*.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2026 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1976 | `mocha --require ./test/common --growl test/expect.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1966 | `mocha -c test/index.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1963 | `mocha --reporter spec && npm run test-typescript` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1963 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1953 | `mocha` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1944 | `npm run lint && mocha --reporter spec test/*.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1935 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1924 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1922 | `mocha test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1911 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1909 | `mocha compiled_tests/` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1895 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1889 | `nyc mocha --timeout=20000 test.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1879 | `mocha tests.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2526 | `mocha --reporter=spec test/*-test.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2514 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2510 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2510 | `mocha test/index.js --reporter dot` | 
| [Qix-/color](https://github.com/Qix-/color) | 2470 | `mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2462 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2462 | `mocha -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2459 | `nyc --require babel-register npm run _mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2458 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2450 | `mocha --no-colors --reporter spec` | 
| [noble/noble](https://github.com/noble/noble) | 2427 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2399 | `npm run build && mocha --require babel-register` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2228 | `mocha && eslint *.js` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2211 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2198 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2194 | `mocha --timeout 10000 --bail --exit test/*-test.js test/security/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2188 | `cross-env BABEL_ENV=test mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2160 | `mocha --compilers js:babel-register` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2153 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2139 | `mocha --compilers js:babel-core/register __tests__` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2135 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2120 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2098 | `mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2083 | `mocha test` | 
| [kach/nearley](https://github.com/kach/nearley) | 2082 | `mocha test/*.test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2069 | `npm run mocha && npm run karma` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2058 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2054 | `npm run lint && mocha -R dot && npm run cover` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2052 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2049 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2042 | `mocha && npm run lint` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2037 | `mocha test/test-*.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2032 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2026 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2008 | `mocha --require=test/test_helper.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1999 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1972 | `mocha test/**/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1966 | `mocha -c test/index.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1963 | `mocha --reporter spec && npm run test-typescript` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1963 | `mocha --bail --reporter spec --check-leaks test/` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1955 | `bmocha --reporter spec test/*.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1953 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1953 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1944 | `npm run lint && mocha --reporter spec test/*.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1935 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1924 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1922 | `mocha test` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1909 | `mocha compiled_tests/` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1838 | `eslint --cache . && tsc && mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1831 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1825 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1820 | `mocha test` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1817 | `mocha test/setup.js test/spec/*.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1796 | `mocha --timeout 5000` | 
| [zeit/ms](https://github.com/zeit/ms) | 1778 | `mocha tests.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1831 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1825 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1820 | `mocha test` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1817 | `mocha test/setup.js test/spec/*.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1813 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1796 | `mocha --timeout 5000` | 
| [zeit/ms](https://github.com/zeit/ms) | 1778 | `mocha tests.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1767 | `npm run lint && mocha && npm run typescript` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1766 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1541 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1538 | `mocha -u tdd` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1533 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1529 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1527 | `npm run lint && mocha && karma start --single-run` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1523 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1517 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1513 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1511 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1504 | `mocha -R spec test/*.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1498 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1496 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1488 | `mocha --recursive test` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1486 | `standard && istanbul cover _mocha` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1475 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1460 | `mocha test/tests.js --timeout=10000` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1458 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1454 | `mocha test.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1673 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1672 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1667 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1665 | `mocha spec` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1659 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1652 | `NODE_ENV=test mocha tests/*.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1650 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1645 | `mocha --expose-gc --slow 300` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1640 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1630 | `mocha --reporter spec` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1628 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1625 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1620 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1363 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1346 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1340 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1335 | `lerna run test && mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1333 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1325 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1322 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1313 | `npm run lint && npm run mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1306 | `mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1303 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1300 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1299 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1293 | `mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1550 | `mocha --check-leaks --require @babel/register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1550 | `npm run test:lint && npm run test:mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1547 | `node_modules/.bin/mocha --recursive` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1538 | `npm run lint && npm run mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1538 | `mocha -u tdd` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1533 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1529 | `mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1528 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1527 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1527 | `npm run lint && mocha && karma start --single-run` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1523 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1517 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1511 | `mocha --timeout 10000 ./tests/lib.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1510 | `mocha test/**/*.spec.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1506 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [noble/bleno](https://github.com/noble/bleno) | 1504 | `mocha -R spec test/*.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1498 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1430 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1429 | `npm run build && mocha -r should` | 
| [electron/devtron](https://github.com/electron/devtron) | 1417 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1410 | `webpack && npm run lint && npm run mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1409 | `istanbul cover _mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1407 | `mocha --recursive test/bin` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1400 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1397 | `mocha --check-leaks --reporter spec --bail test/` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1392 | `npm run mocha:istanbul` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1391 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1384 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1378 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1375 | `./node_modules/.bin/mocha test` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1370 | `NODE_PATH=. mocha **/*.spec.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1369 | `mocha --compilers js:babel-core/register` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1369 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1303 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1300 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1299 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1294 | `istanbul test _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1293 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1287 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1273 | `mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1268 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1268 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1254 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1241 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1241 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1236 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [electron/asar](https://github.com/electron/asar) | 1235 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1228 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1219 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1212 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1207 | `mocha test/test.js` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1206 | `mocha test` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1206 | `mocha test` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1201 | `mocha --recursive -r tests/setup tests` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1192 | `npm-run-all test:jest test:server:mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1190 | `mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1190 | `mocha --reporter spec --bail --check-leaks test/` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1189 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1189 | `mocha --reporter spec --bail --check-leaks test/` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1186 | `xo && mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1173 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1173 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1171 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1170 | `mocha $(find test -name '*.test.js') --exit` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1169 | `mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1169 | `mocha --reporter spec test --recursive` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1131 | `mocha test/*` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1130 | `standard && mocha -b` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1128 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1115 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1114 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1110 | `eslint src test && mocha --compilers babel-register` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1105 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1104 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1103 | `mocha --recursive --bail --reporter spec test` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1098 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1098 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1098 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1096 | `mocha --check-leaks -t 20000` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1094 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1091 | `mocha --compilers js:babel-register` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1111 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1110 | `eslint src test && mocha --compilers babel-register` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1104 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1103 | `mocha --recursive --bail --reporter spec test` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1098 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1098 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1098 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1096 | `mocha --check-leaks -t 20000` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1094 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1091 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1088 | `mocha test/tests.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1076 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 1073 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1070 | `mocha --async-only` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1070 | `npm run lint && npm run mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1057 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1050 | `mocha $(find test -name '*.test.js')` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1046 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1050 | `mocha $(find test -name '*.test.js')` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1046 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1039 | `mocha test/*.test.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 1038 | `mocha --recursive ./test/*_spec.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1035 | `mocha --recursive test/unit/` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1031 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1030 | `mocha --reporter spec --bail --check-leaks test/` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1025 | `mocha --reporter spec --timeout 3000` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1024 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1006 | `npm run lint && mocha -R spec` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1006 | `mocha --check-leaks -R dot` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1005 | `mocha -R list` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1003 | `mocha --compilers js:babel-register test/*.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1003 | `./node_modules/.bin/mocha -R spec` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 1000 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 996 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 993 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 991 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 986 | `mocha "client.test" --compilers js:babel-register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 983 | `mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 983 | `mocha --reporter spec` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 981 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 983 | `mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 983 | `mocha --reporter spec` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 981 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 976 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 976 | `npm run rollup-cjs && mocha test/test.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 974 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 973 | `mocha -t 600000` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 972 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 969 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 968 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 968 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 966 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 963 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 963 | `./node_modules/.bin/mocha --reporter spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 961 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 961 | `nyc mocha specs` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 809 | `mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 807 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 803 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 796 | `mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 796 | `mocha --no-timeouts` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 795 | `mocha test` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 792 | `nyc mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 789 | `eslint . && mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 950 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 946 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 946 | `./node_modules/.bin/mocha test/**/*` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 941 | `standard && standard ./bin/* && mocha` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 940 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 940 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 938 | `mocha test` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 937 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 937 | `mocha --timeout 5000` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 934 | `mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 934 | `istanbul cover -- _mocha --reporter spec` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 929 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 918 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 918 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 916 | `mocha -t 5000` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 916 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 915 | `mocha test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 913 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 911 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 910 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 904 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 902 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 897 | `node_modules/.bin/mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 894 | `mocha --timeout 200000` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 891 | `mocha -r should --exit test/*.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 889 | `node_modules/.bin/mocha test/spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 889 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 882 | `mocha --reporter list` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 878 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 868 | `mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 868 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 866 | `mocha --harmony tests/**` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 865 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 863 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 862 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 861 | `mocha --reporter spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 858 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 857 | `npm run lint && mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 855 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 855 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 854 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 854 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 853 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 852 | `mocha` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 851 | `mocha -r babel-register --check-leaks test/index.js` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 851 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 851 | `mocha --check-leaks -t 20000` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 846 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 844 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 844 | `mocha --opts mocha.opts` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 851 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 851 | `mocha --check-leaks -t 20000` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 846 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 845 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 840 | `nyc mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 840 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 839 | `mocha --async-only` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 836 | `mocha test` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 833 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 831 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 826 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 840 | `nyc mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 840 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 839 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 839 | `mocha --async-only` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 836 | `mocha test` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 833 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 831 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 830 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 828 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 826 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 825 | `mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 824 | `npm run mocha-test test/integration` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 823 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 808 | `mocha index.test.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 805 | `mocha test` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 804 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 803 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 801 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 800 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 796 | `mocha` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 796 | `mocha` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 795 | `mocha test` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 793 | `npm run lint && npm run mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 792 | `nyc mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 789 | `jenkins-mocha ./tests/*.js` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 801 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 800 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 796 | `mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 796 | `mocha --no-timeouts` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 796 | `mocha` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 795 | `mocha test` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 792 | `nyc mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 789 | `jenkins-mocha ./tests/*.js` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 789 | `eslint . && mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 787 | `mocha --recursive -s 15 test/` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 789 | `eslint . && mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 787 | `mocha --recursive -s 15 test/` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 783 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [ebradyjobory/finance.js](https://github.com/ebradyjobory/finance.js) | 779 | `mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 778 | `mocha tests --timeout 10000` | 
| [koajs/static](https://github.com/koajs/static) | 776 | `mocha --harmony --reporter spec --exit` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 775 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 775 | `babel-node node_modules/.bin/_mocha -- test` | 
| [fivdi/onoff](https://github.com/fivdi/onoff) | 775 | `mocha ./unittest` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 775 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 707 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 706 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 704 | `mocha` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 703 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 702 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 699 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 697 | `jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 692 | `./node_modules/.bin/mocha` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 734 | `mocha ./test/test.js --timeout 1000000` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 733 | `mocha --reporter spec --bail --check-leaks test/` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 733 | `mocha` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 732 | `mocha $(find test -name '*.test.js')` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 732 | `mocha --reporter spec test/` | 
| [electron/apps](https://github.com/electron/apps) | 730 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 730 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 727 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 725 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 723 | `mocha ./test/index.js` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 723 | `mocha` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 723 | `mocha --reporter spec` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 721 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 720 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 