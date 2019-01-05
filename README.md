# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:06 01/05/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44785 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41926 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41750 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30768 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 25628 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25094 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24791 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21200 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19967 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18288 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17841 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17667 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16898 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15015 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14799 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14645 | `nyc --reporter=html --reporter=text mocha` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13517 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12963 | `mocha 'test/**/*.spec.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12784 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12714 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12687 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12352 | `mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12277 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12222 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12182 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11373 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11027 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10910 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10794 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10661 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10531 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10395 | `mocha --harmony` | 
| [websockets/ws](https://github.com/websockets/ws) | 10300 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9665 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9657 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9590 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 9432 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9399 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9289 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9251 | `grunt mocha` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8841 | `mocha test/src` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8740 | `mocha --opts mocha.opts` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8659 | `mocha test/test.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8549 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8545 | `mocha --check-leaks -R dot` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8519 | `mocha --compilers js:babel-register test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8434 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8356 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8229 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8019 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7966 | `./node_modules/.bin/mocha test` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7949 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7943 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7808 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7792 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7777 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [dthree/cash](https://github.com/dthree/cash) | 7585 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7576 | `npm run build && istanbul cover _mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7545 | `mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7458 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7450 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7393 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7375 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7340 | `mocha --exit --require @babel/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7090 | `mocha $HARMONY_OPTS` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7081 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6946 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6758 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6708 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6538 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6524 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6373 | `npm run test:mocha:src` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6244 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6193 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6181 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6142 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6121 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6073 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6066 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6065 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5939 | `mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5896 | `standard && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5859 | `mocha && eslint lib/**` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5687 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5648 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5606 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5588 | `npm run lint && mocha tests/**/*.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5537 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5475 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5451 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5409 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5318 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5308 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5274 | `mocha test` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4871 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4868 | `nyc mocha --exit` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4862 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4858 | `./node_modules/.bin/mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4838 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4834 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4815 | `mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4806 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4803 | `npm run lint && npm run mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4744 | `nyc mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4739 | `mocha --reporter spec -t 8000` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 4648 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4577 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4540 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4523 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4519 | `mocha -R spec src` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4475 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4381 | `mocha --timeout=15000 tests/*.test.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4367 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4326 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4270 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4269 | `mocha --check-leaks --reporter spec --bail` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4234 | `NODE_ENV=test mocha --exit` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4231 | `npm run lint ; mocha && mocha test/individual` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4227 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4199 | `mocha -R spec ./test --recursive` | 
| [muicss/mui](https://github.com/muicss/mui) | 4124 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4097 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4075 | `mocha --require should --reporter spec` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4015 | `nyc mocha "test/**/*.test.js"` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3873 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3861 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3831 | `NODE_ENV=test mocha test/**/*.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3812 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3792 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3712 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3692 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3686 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3682 | `standard && mocha --timeout 60000 test/test.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3487 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3451 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3417 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3400 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3382 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3312 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3272 | `mocha test/index.js && npm run demo` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3194 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3179 | `mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3162 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3140 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [tensorspace-team/tensorspace](https://github.com/tensorspace-team/tensorspace) | 3473 | `mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3464 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3451 | `mocha` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3430 | `npm run mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3421 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3417 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3400 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3382 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3357 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3353 | `mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3348 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3312 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3312 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3298 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3288 | `mocha -R landing test/index --exit` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3287 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2825 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [css/csso](https://github.com/css/csso) | 2806 | `mocha --reporter dot` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2785 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2783 | `mocha --require should --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2756 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2755 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2754 | `xo && mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 2735 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2726 | `mocha "./test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2716 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2701 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2698 | `nyc mocha --timeout=10000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2683 | `nyc mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2682 | `mocha --timeout 100000` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2647 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2645 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2608 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2585 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3074 | `nyc mocha --recursive` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3064 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3055 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3016 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2998 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2981 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2976 | `node_modules/.bin/mocha --reporter spec` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2970 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2955 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2953 | `mocha test-node` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2953 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2949 | `mocha -R spec --recursive src/test` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2949 | `mocha` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2944 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2936 | `mocha --require @babel/register --recursive spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2931 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2908 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2551 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2537 | `mocha test` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2534 | `export TESTING=true; mocha --reporter list` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2517 | `mocha test --exit && npm run lint` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2502 | `mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2494 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2470 | `mocha test/index.js --reporter dot` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2445 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2438 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [Qix-/color](https://github.com/Qix-/color) | 2416 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2394 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [noble/noble](https://github.com/noble/noble) | 2381 | `mocha -R spec test/*.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2378 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2377 | `nyc --require babel-register npm run _mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2375 | `grunt jshint && mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2371 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2370 | `npm run build && mocha --require babel-register` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2167 | `mocha test/**/*.coffee` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2162 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2141 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2139 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2122 | `mocha --compilers js:babel-core/register __tests__` | 
| [share/sharedb](https://github.com/share/sharedb) | 2121 | `./node_modules/.bin/mocha && npm run jshint` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2096 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2065 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2037 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [then/promise](https://github.com/then/promise) | 2000 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2437 | `TEST=all mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2430 | `mocha -R spec` | 
| [Qix-/color](https://github.com/Qix-/color) | 2416 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2394 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [noble/noble](https://github.com/noble/noble) | 2381 | `mocha -R spec test/*.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2378 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2375 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2372 | `node node_modules/mocha/bin/_mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2371 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2370 | `npm run build && mocha --require babel-register` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2315 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2303 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [gajus/swing](https://github.com/gajus/swing) | 2298 | `mocha --compilers js:babel-register` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2146 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2141 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2139 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2122 | `mocha --compilers js:babel-core/register __tests__` | 
| [share/sharedb](https://github.com/share/sharedb) | 2121 | `./node_modules/.bin/mocha && npm run jshint` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2108 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2096 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2065 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2046 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2037 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2017 | `npm run mocha && npm run karma` | 
| [then/promise](https://github.com/then/promise) | 2000 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1999 | `mocha --require=test/test_helper.js` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1986 | `mocha && npm run lint` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1969 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1961 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1957 | `mocha --bail --reporter spec --check-leaks test/` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1947 | `mocha test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1945 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1939 | `mocha --reporter spec && npm run test-typescript` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1936 | `mocha test/**/*.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1934 | `bmocha --reporter spec test/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1931 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1906 | `npm run lint && mocha --reporter spec test/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1894 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1890 | `mocha test` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1880 | `mocha tests.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1876 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1872 | `mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1855 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1850 | `mocha ./test/basic.js -t 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1838 | `npm run lint && npm run mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1815 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1796 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1792 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1775 | `mocha test/setup.js test/spec/*.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1774 | `nyc mocha --timeout=20000 test.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1769 | `eslint --cache . && tsc && mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1746 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1739 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1736 | `./node_modules/.bin/mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1734 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1734 | `npm run lint && mocha && npm run typescript` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1728 | `mocha test/*.js` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1727 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1691 | `mocha test/test-*.js` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1683 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1679 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1669 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1663 | `mocha spec` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1661 | `mocha` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1633 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1627 | `mocha ./test/test*.js --reporter spec` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1619 | `mocha --reporter spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1619 | `mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1612 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1611 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1607 | `mocha test.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1619 | `mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1612 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1611 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1609 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1605 | `./node_modules/mocha/bin/mocha -R spec` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1598 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1595 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1592 | `NODE_ENV=test mocha tests/*.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1587 | `mocha --recursive` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1580 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1562 | `mocha test/unit` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1557 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1552 | `mocha --recursive` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1619 | `mocha --reporter spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1619 | `mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1612 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1611 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1609 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1607 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1605 | `./node_modules/mocha/bin/mocha -R spec` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1598 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1595 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1592 | `NODE_ENV=test mocha tests/*.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1587 | `mocha --recursive` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1580 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1565 | `nyc mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1562 | `mocha test/unit` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1557 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1552 | `mocha --recursive` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1540 | `node_modules/.bin/mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1537 | `mocha -u tdd` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1533 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1531 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1529 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require babel-core/register --recursive --exit` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1526 | `mocha -R spec ./test/unit/**` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1525 | `mocha --check-leaks --require @babel/register` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1316 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1315 | `mocha-phantomjs tests/index.html` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1314 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1314 | `mocha test/*.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1312 | `npm run lint && mocha --require @babel/register` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1312 | `mocha --timeout 60000 test/` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1305 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1303 | `mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1301 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1282 | `istanbul test _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1281 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1271 | `mocha --timeout 30000 --recursive ./tests` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1270 | `mocha --timeout 20000` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1266 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [variety/variety](https://github.com/variety/variety) | 1263 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1260 | `mocha tests` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1419 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1417 | `npm run build && mocha -r should` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1404 | `istanbul cover _mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1400 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1399 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1392 | `mocha test --compilers js:babel-core/register` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1390 | `mocha --recursive test/bin` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1386 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1386 | `mocha --recursive` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1382 | `./node_modules/mocha/bin/mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1381 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1378 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1373 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1409 | `mocha --recursive test` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1404 | `istanbul cover _mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1400 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1399 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1392 | `mocha test --compilers js:babel-core/register` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1390 | `mocha --recursive test/bin` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1386 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1386 | `mocha --recursive` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1381 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1378 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1373 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1370 | `cross-env NODE_ENV=test nyc mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1367 | `./node_modules/.bin/mocha test` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1373 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1370 | `cross-env NODE_ENV=test nyc mocha` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1370 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1367 | `./node_modules/.bin/mocha test` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1360 | `NODE_PATH=. mocha **/*.spec.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1355 | `mocha --check-leaks --reporter spec --bail test/` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1344 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1344 | `mocha --compilers js:babel-core/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1344 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1340 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1340 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1335 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1333 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1333 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1316 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1315 | `mocha-phantomjs tests/index.html` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1314 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1314 | `mocha test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1312 | `mocha --timeout 60000 test/` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1309 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1308 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1305 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1303 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1301 | `mocha src/test.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1295 | `mocha tests/` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1287 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1287 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1284 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1282 | `istanbul test _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1281 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1290 | `npm run lint && npm run mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1287 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1287 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1284 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1282 | `istanbul test _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1281 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1272 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1271 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1271 | `mocha --timeout 30000 --recursive ./tests` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1270 | `mocha --timeout 20000` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1266 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [variety/variety](https://github.com/variety/variety) | 1263 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1260 | `mocha tests` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1254 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1175 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1170 | `xo && mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1167 | `mocha $(find test -name '*.test.js') --exit` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1159 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1158 | `mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1152 | `istanbul cover _mocha test/*.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1150 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1207 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1206 | `mocha test` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1186 | `mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1180 | `mocha --recursive -r tests/setup tests` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1175 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1170 | `xo && mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1169 | `mocha` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1116 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1116 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [electron/spectron](https://github.com/electron/spectron) | 1114 | `mocha && standard` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1114 | `standard && mocha -b` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1112 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1112 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1110 | `mocha test` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1101 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1096 | `node_modules/.bin/mocha && npm run lint` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1095 | `mocha --recursive --bail --reporter spec test` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1083 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1116 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1116 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [electron/spectron](https://github.com/electron/spectron) | 1114 | `mocha && standard` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1114 | `standard && mocha -b` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1112 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1112 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1110 | `mocha test` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1103 | `npm run convertto:es5 && npm run mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1101 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1101 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1099 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1096 | `node_modules/.bin/mocha && npm run lint` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1095 | `mocha --recursive --bail --reporter spec test` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1095 | `mocha --check-leaks -t 20000` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1093 | `eslint src test && mocha --compilers babel-register` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1088 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1084 | `mocha test/tests.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1083 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1047 | `mocha $(find test -name '*.test.js')` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1045 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1029 | `mocha --recursive test/unit/` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1025 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1017 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1015 | `mocha --colors ./test/*.spec.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1014 | `mocha --reporter spec --bail --check-leaks test/` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 902 | `mocha test` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 899 | `mocha test/index.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 895 | `node_modules/.bin/mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 891 | `mocha --timeout 200000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 883 | `node_modules/.bin/mocha test/spec` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 882 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 875 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 941 | `mocha --timeout 5000` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 939 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 938 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 936 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 935 | `nyc mocha specs` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 923 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 923 | `istanbul cover -- _mocha --reporter spec` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 920 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 918 | `standard && standard ./bin/* && mocha` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 991 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 990 | `npm run lint && mocha -R spec` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 987 | `mocha --recursive ./test/*_spec.js` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 987 | `npm run lint && npm run mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 983 | `mocha --compilers js:babel-register test/*.js` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 983 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 983 | `mocha spec/*.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 982 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 980 | `mocha --reporter spec` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 979 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 979 | `./node_modules/.bin/mocha -R spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 978 | `mocha` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 976 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 976 | `mocha "client.test" --compilers js:babel-register` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 975 | `npm run rollup-cjs && mocha test/test.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 972 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 967 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 960 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 958 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 958 | `./node_modules/.bin/mocha --reporter spec` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 955 | `mocha -t 600000` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 954 | `mocha tests` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 951 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 942 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 942 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 941 | `mocha --timeout 5000` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 942 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 942 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 941 | `mocha --timeout 5000` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 939 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 938 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 936 | `mocha test --compilers js:babel-register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 936 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 935 | `nyc mocha specs` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 935 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 929 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 927 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 923 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 923 | `istanbul cover -- _mocha --reporter spec` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 920 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 918 | `standard && standard ./bin/* && mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 915 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 914 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 914 | `mocha -t 5000` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 912 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 906 | `npm run lint && npm run mocha:no-functional` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 906 | `./node_modules/.bin/mocha test/**/*` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 895 | `node_modules/.bin/mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 893 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 891 | `mocha --timeout 200000` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 888 | `mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 883 | `node_modules/.bin/mocha test/spec` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 882 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 875 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 873 | `npm run build && istanbul test _mocha test/test.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 872 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 872 | `mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 870 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 879 | `mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 875 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 873 | `npm run build && istanbul test _mocha test/test.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 872 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 872 | `mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 870 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 867 | `mocha --reporter list` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 866 | `eslint test && mocha --compilers js:babel/register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 865 | `mocha --harmony --full-trace --check-leaks` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 865 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 863 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 827 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 827 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 825 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 822 | `nyc mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 819 | `mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 818 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 812 | `cake build && mocha ./test/mocha/*.coffee` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 808 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 809 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 808 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 799 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 794 | `xo && mocha -R spec` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 792 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 772 | `mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 771 | `mocha tests --timeout 10000` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 769 | `babel-node node_modules/.bin/_mocha -- test` | 
| [susam/texme](https://github.com/susam/texme) | 763 | `standard && mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 762 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 808 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 807 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 801 | `_mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 799 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 794 | `mocha --no-timeouts` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 794 | `mocha test` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 794 | `xo && mocha -R spec` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 792 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 786 | `npm run lint && npm run mocha` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 786 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 784 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 784 | `mocha` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 782 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 781 | `mocha test/mocha.js` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 780 | `nyc mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 779 | `mocha --recursive -s 15 test/` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 775 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 773 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 773 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 772 | `mocha` | 