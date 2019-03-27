# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:50 03/27/19 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45697 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 43034 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42520 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 31017 | `nyc mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 26507 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 26148 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25801 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25368 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 22048 | `npm-run-all lint build --parallel test:mocha test:karma test:ts` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20407 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 19040 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18454 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18251 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 18147 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15774 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15326 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14822 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14210 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 14022 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13649 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13117 | `mocha 'test/**/*.spec.js'` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 13057 | `istanbul cover _mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12928 | `mocha --reporter spec test/*-test.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12898 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12830 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12511 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12390 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11879 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11720 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11470 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 11138 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [websockets/ws](https://github.com/websockets/ws) | 10926 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10824 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10545 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 10151 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9941 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9806 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9734 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9671 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9524 | `mocha -b -r esm` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9439 | `mocha --opts mocha.opts` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9428 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 9207 | `mocha test/*/**` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 9164 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9076 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8765 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8701 | `mocha --compilers js:babel-register test/test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8685 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8603 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8530 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8496 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8350 | `mocha` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8329 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8290 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8236 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8196 | `npm run eslint && npm run mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8160 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8133 | `./node_modules/.bin/mocha test` | 
| [aui/art-template](https://github.com/aui/art-template) | 8012 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7842 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7800 | `mocha --exit --require @babel/register` | 
| [almende/vis](https://github.com/almende/vis) | 7744 | `mocha --compilers js:babel-core/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7736 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7735 | `mocha; jshint *.js lib` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7655 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7604 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7466 | `mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7453 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7313 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7187 | `npm run jshint && mocha test/` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7180 | `mocha $HARMONY_OPTS` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 7146 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6674 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6497 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6457 | `npm run test:mocha:src` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6398 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6370 | `mocha tests/node.js` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6346 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6313 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6287 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 6268 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6261 | `standard && mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6178 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 6083 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6068 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 6013 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5952 | `mocha && eslint lib/**` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5921 | `mocha` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5920 | `npm run lint && mocha tests/**/*.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5866 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5797 | `mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5794 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5653 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5598 | `mocha test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5572 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5548 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5537 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5446 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5397 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5244 | `mocha --recursive` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5211 | `mocha src/**/*Tests.js --harmony` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5196 | `npm run lint && npm run mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 5179 | `NODE_ENV=test mocha --exit` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5162 | `nyc mocha --exit` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5158 | `gulp lint && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5125 | `mocha --color` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5119 | `nyc mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 5022 | `gulp build; mocha;` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 5010 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4938 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 4583 | `npm run mocha` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4535 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4523 | `mocha --check-leaks --reporter spec --bail` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4497 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4461 | `mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4442 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4415 | `npm run lint && mocha && mocha test/individual && if [ "$TRAVIS_PULL_REQUEST" = "false" ]; then snyk test; fi` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4400 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4313 | `npm run build && cd test && mocha . --reporter dot` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4252 | `nyc mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4195 | `mocha --require test/babel-hook test/*.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4188 | `nyc mocha "test/**/*.test.js"` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4183 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4176 | `mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 4161 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4109 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 4080 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 4032 | `NODE_ENV=test mocha test/**/*.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 4014 | `mocha && tsc -p ./test/types` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 4001 | `eslint . && mocha -t 5000` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3940 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3799 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3794 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3777 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3772 | `mocha test/* --reporter spec` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3719 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3706 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3700 | `node_modules/.bin/mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3673 | `npm run jshint && npm run mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3642 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3641 | `nyc mocha && tsc` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3617 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3590 | `mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3574 | `mocha -R landing test/index --exit` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3557 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3471 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3471 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3464 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3450 | `mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3434 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3423 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3328 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3320 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3304 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3303 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3196 | `./node_modules/.bin/mocha test/test.*.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3188 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3450 | `mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3434 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3423 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3392 | `mocha test/index.js && npm run demo` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3328 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3320 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3304 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3303 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3249 | `mocha` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3109 | `node_modules/.bin/mocha --reporter spec` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 3098 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 3093 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3081 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3076 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3074 | `mocha test-node` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 3055 | `mocha --require @babel/register --recursive spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3049 | `mocha` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 3028 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 3001 | `mocha -R spec --recursive src/test` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2997 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2993 | `mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2967 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2932 | `mocha -R spec spec spec/reporters` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1752 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1750 | `./node_modules/.bin/mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1741 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1741 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1727 | `mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1698 | `mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1692 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1676 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1673 | `mocha spec` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1670 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1662 | `mocha -R spec ./test/unit/**` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1646 | `mocha --expose-gc --slow 300` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1645 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1641 | `mocha tests/test.js` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1636 | `mocha test.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1623 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1606 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2194 | `cross-env BABEL_ENV=test mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2176 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2176 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2132 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2128 | `mocha tests --require @babel/register` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2122 | `npm run mocha && npm run karma` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2108 | `mocha && npm run lint` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2101 | `mocha` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2065 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2057 | `mocha --reporter spec --timeout 5000` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2430 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2394 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2394 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2370 | `node node_modules/mocha/bin/_mocha` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2363 | `mocha test/**/*.coffee` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2353 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2340 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [gajus/swing](https://github.com/gajus/swing) | 2338 | `mocha --compilers js:babel-register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2323 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2299 | `standard && mocha` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2296 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [share/sharedb](https://github.com/share/sharedb) | 2295 | `./node_modules/.bin/mocha && npm run jshint` | 
| [pahen/madge](https://github.com/pahen/madge) | 2435 | `npm run lint && npm run mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2430 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2394 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2394 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2370 | `node node_modules/mocha/bin/_mocha` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2363 | `mocha test/**/*.coffee` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2353 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2340 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [gajus/swing](https://github.com/gajus/swing) | 2338 | `mocha --compilers js:babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2326 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2323 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2108 | `mocha && npm run lint` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 2107 | `mocha --recursive` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2101 | `mocha` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2068 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2065 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2057 | `mocha --reporter spec --timeout 5000` | 
| [then/promise](https://github.com/then/promise) | 2037 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 2035 | `nyc mocha --timeout=20000 test.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2035 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 2024 | `mocha test/**/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 2005 | `mocha --reporter spec && npm run test-typescript` | 
| [zeit/ms](https://github.com/zeit/ms) | 2001 | `mocha tests.js` | 
| [slate/slate](https://github.com/slate/slate) | 1993 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1983 | `bmocha --reporter spec test/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1979 | `mocha --bail --reporter spec --check-leaks test/` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1976 | `npm run lint && mocha --reporter spec test/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1963 | `mocha --reporter spec --grep .` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1963 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1955 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1955 | `eslint --cache . && tslint --project . && node build && mocha && tsc` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1954 | `mocha test` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1945 | `mocha ./test/basic.js -t 5000` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1926 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1923 | `mocha ./test/test*.js --reporter spec` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1887 | `mocha tests.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1876 | `npm run lint && npm run mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1872 | `mocha test/setup.js test/spec/*.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1863 | `mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1832 | `mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1828 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1826 | `mocha test` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1826 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1818 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1817 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1804 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1798 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1794 | `mocha --timeout 5000` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1784 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1784 | `npm run lint && mocha && npm run typescript` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1782 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1782 | `mocha --check-leaks --reporter spec --bail` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1633 | `./node_modules/mocha/bin/mocha -R spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1623 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1606 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1581 | `mocha --check-leaks --require @babel/register` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1576 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1574 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1571 | `npm run lint && mocha && karma start --single-run` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1565 | `mocha --recursive test` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1563 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1560 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1560 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1540 | `npm run prepublishOnly && mocha test/test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1534 | `standard && nyc _mocha --exit` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1533 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1522 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1581 | `mocha --check-leaks --require @babel/register` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1576 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1574 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1571 | `npm run lint && mocha && karma start --single-run` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1565 | `mocha --recursive test` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1564 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1563 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1560 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1560 | `mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1550 | `npm run test:lint && npm run test:mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1534 | `standard && nyc _mocha --exit` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1533 | `mocha --timeout 10000 ./tests/lib.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1531 | `mocha test/**/*.spec.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1522 | `mocha --reporter dot` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1522 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1519 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [trufflesuite/ganache](https://github.com/trufflesuite/ganache) | 1512 | `npm run test-mocha && npm run test-jest` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1506 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1676 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1673 | `mocha spec` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1670 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1665 | `xo && mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1662 | `mocha -R spec ./test/unit/**` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1658 | `mocha --recursive` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1653 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1652 | `mocha test/unit` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1648 | `mocha --reporter spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1646 | `mocha --expose-gc --slow 300` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1645 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1641 | `mocha tests/test.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1637 | `mocha tests/test-*` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1636 | `mocha test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1625 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1621 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1565 | `mocha --recursive test` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1564 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1563 | `node_modules/.bin/mocha --recursive` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1563 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1560 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1560 | `mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1559 | `mocha -u tdd` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1555 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1552 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1550 | `npm run test:lint && npm run test:mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1547 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1534 | `standard && nyc _mocha --exit` | 
| [noble/bleno](https://github.com/noble/bleno) | 1532 | `mocha -R spec test/*.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1531 | `mocha test/**/*.spec.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1522 | `mocha --reporter dot` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1522 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1500 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1472 | `npm run mocha:istanbul` | 
| [samccone/drool](https://github.com/samccone/drool) | 1463 | `mocha test/tests.js --timeout=10000` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1456 | `webpack && npm run lint && npm run mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1456 | `mocha test.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1453 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1449 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1448 | `npm run build && mocha -r should` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1447 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1443 | `mocha --recursive test/bin` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1441 | `mocha --check-leaks --reporter spec --bail test/` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1491 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1472 | `npm run mocha:istanbul` | 
| [samccone/drool](https://github.com/samccone/drool) | 1463 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1456 | `mocha test.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1453 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1449 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1448 | `npm run build && mocha -r should` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1447 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1437 | `mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1433 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1431 | `istanbul cover _mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1430 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1427 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1421 | `mocha --compilers js:babel-core/register` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1413 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1411 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1410 | `mocha --recursive` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1406 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1402 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1396 | `NODE_PATH=. mocha **/*.spec.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1395 | `npm run lint && mocha --require @babel/register` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1393 | `./node_modules/.bin/mocha test` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1390 | `./node_modules/mocha/bin/mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1390 | `mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 935 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 928 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 924 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 923 | `mocha --harmony tests/**` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 919 | `mocha spec/*.spec.js` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 918 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 917 | `npm run lint && npm run mocha:no-functional` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 908 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 908 | `mocha --harmony --full-trace --check-leaks` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 879 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 877 | `istanbul cover _mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 876 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 875 | `mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 875 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 875 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 874 | `mocha -r babel-register --check-leaks test/index.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 872 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 871 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 870 | `mocha --reporter spec` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 868 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 868 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 866 | `eslint test && mocha --compilers js:babel/register` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 876 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 876 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 875 | `mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 875 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 875 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [developit/decko](https://github.com/developit/decko) | 873 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 872 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 871 | `nyc mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 871 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 870 | `mocha --reporter spec` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 869 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 868 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 868 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 868 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 866 | `eslint test && mocha --compilers js:babel/register` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 864 | `mocha test` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 863 | `nyc mocha` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 861 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 860 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 860 | `mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 859 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 855 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 854 | `mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 854 | `mocha` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 853 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 849 | `ts-mocha test/` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 847 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 845 | `mocha test/mocha.js test/crc/index.js` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 845 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 845 | `mocha test` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 845 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 843 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 838 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 837 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 836 | `npm run mocha-test test/integration` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 835 | `eslint . && mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 832 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 832 | `mocha && ember test` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 831 | `_mocha` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 838 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 838 | `mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 837 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 836 | `npm run mocha-test test/integration` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 832 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 831 | `_mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 830 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 829 | `cake build && mocha ./test/mocha/*.coffee` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 827 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 826 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 825 | `mocha` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 824 | `mocha index.test.js` | 
| [CharlesStover/reactn](https://github.com/CharlesStover/reactn) | 824 | `mocha -r chai/register-expect -r @babel/register -r ts-node/register "tests/**/*.spec.ts?(x)"` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 822 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 821 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 818 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 814 | `mocha` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 812 | `jenkins-mocha ./tests/*.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 810 | `mocha test` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 808 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 790 | `mocha -u tdd` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 788 | `mocha 'test/**/*.tests.js'` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 786 | `mocha ./test/serializer/ --compilers js:@babel/register` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 784 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 784 | `npm run-script jshint && npm run-script mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 782 | `babel-node node_modules/.bin/_mocha -- test` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 780 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 777 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 776 | `mocha -R spec src/**/*_test.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 774 | `./bin/selenium-standalone install && mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 773 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 765 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 761 | `mocha --reporter spec --bail --check-leaks test/` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 759 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [formio/formio](https://github.com/formio/formio) | 756 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 756 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 752 | `mocha tests/*.mocha.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 752 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 748 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 747 | `mocha --compilers js:babel-core/register` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 747 | `mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 780 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 777 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 776 | `mocha -R spec src/**/*_test.js` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 774 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 774 | `./bin/selenium-standalone install && mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 773 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 772 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [electron/apps](https://github.com/electron/apps) | 771 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 771 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 770 | `mocha --ui tdd --require ./test/__setup` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 768 | `mocha --reporter spec build/test/index.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 752 | `mocha tests/*.mocha.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 752 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 748 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 748 | `mocha test.js` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 747 | `mocha --compilers js:babel-core/register` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 747 | `mocha` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 745 | `mocha $(find test -name '*.test.js')` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 745 | `mocha --reporter spec` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 743 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 743 | `mocha` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 742 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 741 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 740 | `mocha ./test/test.js --timeout 1000000` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 740 | `mocha --reporter spec test/` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 740 | `mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 740 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 738 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [Kagami/ffmpeg.js](https://github.com/Kagami/ffmpeg.js) | 736 | `mocha test/test.js` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 736 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 731 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 731 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 730 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 730 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 729 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 729 | `mocha` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 727 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 714 | `npm -s run mocha && npm run -s lint` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 713 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 712 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 708 | `mocha` | 
| [Savjee/SavjeeCoin](https://github.com/Savjee/SavjeeCoin) | 708 | `mocha tests/*.test.js` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 708 | `mocha` | 
| [Savjee/SavjeeCoin](https://github.com/Savjee/SavjeeCoin) | 708 | `mocha tests/*.test.js` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 705 | `mocha --reporter spec` | 
| [apollographql/eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) | 704 | `tav --ci && mocha test/index.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 704 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 703 | `./node_modules/.bin/mocha` | 
| [gtanner/qrcode-terminal](https://github.com/gtanner/qrcode-terminal) | 701 | `./node_modules/jshint/bin/jshint lib vendor && node example/basic.js && ./node_modules/mocha/bin/mocha -R nyan` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 700 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [afc163/fanyi](https://github.com/afc163/fanyi) | 698 | `npm run lint && mocha tests/index.js --timeout 0` | 
| [godaddy/terminus](https://github.com/godaddy/terminus) | 697 | `mocha index.spec.js lib/**/*.spec.js && npm run test-typings` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 695 | `mocha` | 
| [klokantech/tileserver-gl](https://github.com/klokantech/tileserver-gl) | 695 | `mocha test/**.js --timeout 10000` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 689 | `mocha -R spec` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 688 | `mocha --bail test/` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 687 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 686 | `mocha --compilers js:babel-register` | 
| [shelljs/shx](https://github.com/shelljs/shx) | 686 | `nyc --reporter=text --reporter=lcov mocha` | 
| [omnidan/node-emoji](https://github.com/omnidan/node-emoji) | 684 | `./node_modules/.bin/mocha --require should --bail --reporter spec test/*` | 
| [shime/livedown](https://github.com/shime/livedown) | 683 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 681 | `mocha --require babel-register` | 
| [theoephraim/node-google-spreadsheet](https://github.com/theoephraim/node-google-spreadsheet) | 677 | `node_modules/.bin/mocha` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 676 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [calmm-js/partial.lenses](https://github.com/calmm-js/partial.lenses) | 675 | `nyc mocha && nyc report -r html mocha` | 
| [anandanand84/technicalindicators](https://github.com/anandanand84/technicalindicators) | 668 | `mocha --compilers js:babel-register --require babel-polyfill` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 667 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [maxkueng/victor](https://github.com/maxkueng/victor) | 667 | `mocha --ui bdd --reporter spec` | 
| [substance/data](https://github.com/substance/data) | 666 | `mocha -R spec tests/run.js` | 
| [docpress/docpress](https://github.com/docpress/docpress) | 666 | `nyc mocha` | 
| [aaronshaf/react-toggle](https://github.com/aaronshaf/react-toggle) | 666 | `nyc mocha --require babel-register --require spec/setup.js spec/**/*.spec.js` | 
| [Ivshti/linvodb3](https://github.com/Ivshti/linvodb3) | 663 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [dtschust/redux-bug-reporter](https://github.com/dtschust/redux-bug-reporter) | 662 | `standard && mocha --compilers js:babel-register --recursive --require test/setup.js` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 662 | `mocha --recursive --compilers js:babel-core/register` | 
| [jbrooksuk/node-summary](https://github.com/jbrooksuk/node-summary) | 659 | `mocha --compilers js:babel-core/register --require should --reporter spec` | 
| [chao/RESTClient](https://github.com/chao/RESTClient) | 659 | `mocha` | 
| [pburtchaell/react-notification](https://github.com/pburtchaell/react-notification) | 656 | `node_modules/.bin/mocha --compilers js:babel-core/register --reporter spec --recursive --timeout 5000 test/setup.js test/**/*.js` | 
| [rkusa/koa-passport](https://github.com/rkusa/koa-passport) | 656 | `mocha` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 656 | `mocha` | 
| [pburtchaell/react-notification](https://github.com/pburtchaell/react-notification) | 656 | `node_modules/.bin/mocha --compilers js:babel-core/register --reporter spec --recursive --timeout 5000 test/setup.js test/**/*.js` | 
| [rkusa/koa-passport](https://github.com/rkusa/koa-passport) | 656 | `mocha` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 656 | `mocha` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 654 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [azmenak/react-stripe-checkout](https://github.com/azmenak/react-stripe-checkout) | 653 | `mocha --require babel-register --require .test-setup.js -R spec ./spec.js` | 
| [vault-development/react-native-svg-uri](https://github.com/vault-development/react-native-svg-uri) | 652 | `./node_modules/mocha/bin/mocha --compilers js:babel-core/register` | 
| [danielstjules/buddy.js](https://github.com/danielstjules/buddy.js) | 652 | `mocha -R spec spec/unit spec/integration` | 
| [ideal-postcodes/postcodes.io](https://github.com/ideal-postcodes/postcodes.io) | 651 | `NODE_ENV=test npm run test:create && npm run nyc_mocha && NODE_ENV=test npm run test:clear && npm run lint` | 
| [gauntface/simple-push-demo](https://github.com/gauntface/simple-push-demo) | 650 | `gulp && npm run lint && node ./test/helpers/download-browsers.js && mocha` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 650 | `./node_modules/.bin/mocha --bail` | 
| [postcss/gulp-postcss](https://github.com/postcss/gulp-postcss) | 649 | `nyc mocha test.js` | 
| [GoogleChromeLabs/pwacompat](https://github.com/GoogleChromeLabs/pwacompat) | 646 | `mocha-headless-server suite.html` | 
| [edankwan/penis.js](https://github.com/edankwan/penis.js) | 642 | `mocha --ui bdd --reporter spec test/` | 
| [screwdriver-cd/screwdriver](https://github.com/screwdriver-cd/screwdriver) | 641 | `jenkins-mocha --recursive --timeout 3000 --exit` | 
| [webpack/memory-fs](https://github.com/webpack/memory-fs) | 641 | `mocha` | 
| [werk85/node-html-to-text](https://github.com/werk85/node-html-to-text) | 640 | `istanbul cover _mocha && eslint .` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 648 | `./node_modules/.bin/mocha test/integration` | 
| [fent/node-ytdl](https://github.com/fent/node-ytdl) | 645 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [phodal/sherlock](https://github.com/phodal/sherlock) | 644 | `mocha --reporter spec` | 
| [aliyun-UED/aliyun-sdk-js](https://github.com/aliyun-UED/aliyun-sdk-js) | 643 | `mocha test` | 
| [edankwan/penis.js](https://github.com/edankwan/penis.js) | 642 | `mocha --ui bdd --reporter spec test/` | 
| [tonyhb/redux-ui](https://github.com/tonyhb/redux-ui) | 641 | `$(npm bin)/mocha  --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [webpack/memory-fs](https://github.com/webpack/memory-fs) | 641 | `mocha` | 
| [werk85/node-html-to-text](https://github.com/werk85/node-html-to-text) | 640 | `istanbul cover _mocha && eslint .` | 
| [floatdrop/gulp-watch](https://github.com/floatdrop/gulp-watch) | 640 | `xo && mocha -r test/util/set-default-options -t 5000 -R spec test/test-*` | 
| [hparra/gulp-rename](https://github.com/hparra/gulp-rename) | 638 | `mocha` | 
| [puleos/object-hash](https://github.com/puleos/object-hash) | 638 | `node ./node_modules/.bin/mocha test` | 
| [nexus-js/ui](https://github.com/nexus-js/ui) | 637 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [danawoodman/react-fontawesome](https://github.com/danawoodman/react-fontawesome) | 636 | `mocha` | 
| [adamgruber/mochawesome](https://github.com/adamgruber/mochawesome) | 636 | `npm run lint && cross-env NODE_ENV=test nyc mocha` | 
| [dleitee/valid.js](https://github.com/dleitee/valid.js) | 593 | `mocha --compilers js:babel-register` | 
| [gsuitedevs/apps-script-oauth2](https://github.com/gsuitedevs/apps-script-oauth2) | 592 | `mocha` | 
| [mozilla/webextension-polyfill](https://github.com/mozilla/webextension-polyfill) | 591 | `mocha` | 
| [gridcontrol/gridcontrol](https://github.com/gridcontrol/gridcontrol) | 587 | `NODE_ENV='test' DEBUG='gc:*' ./node_modules/.bin/mocha test/*.mocha.js -b` | 
| [JoshKaufman/ursa](https://github.com/JoshKaufman/ursa) | 583 | `mocha --recursive --reporter spec` | 
| [felixge/node-dirty](https://github.com/felixge/node-dirty) | 582 | `mocha test/test-*.js -R list` | 
| [ck86/main-bower-files](https://github.com/ck86/main-bower-files) | 596 | `mocha` | 
| [jimpick/lambda-comments](https://github.com/jimpick/lambda-comments) | 595 | `mocha --compilers js:./babel-register` | 
| [mike-marcacci/node-redlock](https://github.com/mike-marcacci/node-redlock) | 594 | `istanbul cover mocha` | 
| [bitovi/documentjs](https://github.com/bitovi/documentjs) | 594 | `mocha test/test.js --reporter spec` | 
| [mhart/dynalite](https://github.com/mhart/dynalite) | 593 | `mocha --require should --reporter spec -t $([ $REMOTE ] && echo 30s || echo 4s)` | 
| [teropa/redux-voting-server](https://github.com/teropa/redux-voting-server) | 592 | `mocha --compilers js:babel-core/register  --require ./test/test_helper.js  --recursive` | 
| [gsuitedevs/apps-script-oauth2](https://github.com/gsuitedevs/apps-script-oauth2) | 592 | `mocha` | 
| [mikaelbr/gulp-notify](https://github.com/mikaelbr/gulp-notify) | 591 | `mocha -R spec` | 
| [orliesaurus/nodemailer-mailgun-transport](https://github.com/orliesaurus/nodemailer-mailgun-transport) | 589 | `mocha` | 
| [gridcontrol/gridcontrol](https://github.com/gridcontrol/gridcontrol) | 587 | `NODE_ENV='test' DEBUG='gc:*' ./node_modules/.bin/mocha test/*.mocha.js -b` | 
| [jeremyckahn/rekapi](https://github.com/jeremyckahn/rekapi) | 587 | `mocha -r jsdom-global/register ./node_modules/babel-core/register.js test/index.js` | 
| [queckezz/koa-views](https://github.com/queckezz/koa-views) | 586 | `mocha --reporter dot --bail --exit` | 
| [mrsteele/dotenv-webpack](https://github.com/mrsteele/dotenv-webpack) | 585 | `nyc _mocha --compilers js:babel-register` | 
| [GoogleChrome/proxy-polyfill](https://github.com/GoogleChrome/proxy-polyfill) | 583 | `mocha` | 
| [cgross/generator-cg-angular](https://github.com/cgross/generator-cg-angular) | 606 | `mocha` | 
| [echenley/react-news](https://github.com/echenley/react-news) | 605 | `./node_modules/.bin/karma start ./test/karma.conf.js --reporters mocha,coverage` | 
| [victorb/autochecker](https://github.com/victorb/autochecker) | 603 | `mocha` | 
| [justinfagnani/mixwith.js](https://github.com/justinfagnani/mixwith.js) | 603 | `mocha build/test` | 
| [ivolo/disposable-email-domains](https://github.com/ivolo/disposable-email-domains) | 603 | `node ./node_modules/mocha/bin/_mocha` | 
| [times/cardkit](https://github.com/times/cardkit) | 601 | `./node_modules/.bin/istanbul cover --dir test/coverage ./node_modules/.bin/_mocha -- --compilers js:babel-core/register --require ignore-styles` | 
| [rofrischmann/react-look](https://github.com/rofrischmann/react-look) | 600 | `npm run lint && mocha --recursive --compilers js:babel/register` | 
| [matthewmueller/graph.ql](https://github.com/matthewmueller/graph.ql) | 599 | `./node_modules/.bin/mocha` | 
| [putaoshu/jdf](https://github.com/putaoshu/jdf) | 598 | `mocha test/index.js` | 
| [mhart/kinesalite](https://github.com/mhart/kinesalite) | 597 | `mocha --require should --reporter spec -t $([ $REMOTE ] && echo 30s || echo 4s)` | 
| [SamyPesse/gitkit-js](https://github.com/SamyPesse/gitkit-js) | 596 | `./node_modules/.bin/mocha ./testing/setup.js ./lib/**/*/__tests__/*.js --bail --reporter=list` | 
| [ck86/main-bower-files](https://github.com/ck86/main-bower-files) | 596 | `mocha` | 
| [jkphl/gulp-svg-sprite](https://github.com/jkphl/gulp-svg-sprite) | 596 | `gulp && istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [mbasso/react-decoration](https://github.com/mbasso/react-decoration) | 595 | `cross-env BABEL_ENV=commonjs nyc --require babel-register --require ./test/setup.js mocha --recursive` | 
| [pvorb/node-md5](https://github.com/pvorb/node-md5) | 595 | `mocha` | 
| [jimpick/lambda-comments](https://github.com/jimpick/lambda-comments) | 595 | `mocha --compilers js:./babel-register` | 
| [bitovi/documentjs](https://github.com/bitovi/documentjs) | 594 | `mocha test/test.js --reporter spec` | 
| [ivolo/disposable-email-domains](https://github.com/ivolo/disposable-email-domains) | 603 | `node ./node_modules/mocha/bin/_mocha` | 
| [newsdev/ai2html](https://github.com/newsdev/ai2html) | 602 | `mocha --check-leaks` | 
| [times/cardkit](https://github.com/times/cardkit) | 601 | `./node_modules/.bin/istanbul cover --dir test/coverage ./node_modules/.bin/_mocha -- --compilers js:babel-core/register --require ignore-styles` | 
| [rofrischmann/react-look](https://github.com/rofrischmann/react-look) | 600 | `npm run lint && mocha --recursive --compilers js:babel/register` | 
| [matthewmueller/graph.ql](https://github.com/matthewmueller/graph.ql) | 599 | `./node_modules/.bin/mocha` | 
| [putaoshu/jdf](https://github.com/putaoshu/jdf) | 598 | `mocha test/index.js` | 
| [mhart/kinesalite](https://github.com/mhart/kinesalite) | 597 | `mocha --require should --reporter spec -t $([ $REMOTE ] && echo 30s || echo 4s)` | 
| [SamyPesse/gitkit-js](https://github.com/SamyPesse/gitkit-js) | 596 | `./node_modules/.bin/mocha ./testing/setup.js ./lib/**/*/__tests__/*.js --bail --reporter=list` | 
| [ck86/main-bower-files](https://github.com/ck86/main-bower-files) | 596 | `mocha` | 
| [jkphl/gulp-svg-sprite](https://github.com/jkphl/gulp-svg-sprite) | 596 | `gulp && istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [mbasso/react-decoration](https://github.com/mbasso/react-decoration) | 595 | `cross-env BABEL_ENV=commonjs nyc --require babel-register --require ./test/setup.js mocha --recursive` | 
| [pvorb/node-md5](https://github.com/pvorb/node-md5) | 595 | `mocha` | 
| [jimpick/lambda-comments](https://github.com/jimpick/lambda-comments) | 595 | `mocha --compilers js:./babel-register` | 
| [bitovi/documentjs](https://github.com/bitovi/documentjs) | 594 | `mocha test/test.js --reporter spec` | 
| [mhart/dynalite](https://github.com/mhart/dynalite) | 593 | `mocha --require should --reporter spec -t $([ $REMOTE ] && echo 30s || echo 4s)` | 
| [dleitee/valid.js](https://github.com/dleitee/valid.js) | 593 | `mocha --compilers js:babel-register` | 