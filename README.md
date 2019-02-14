# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:31 02/14/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45183 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42387 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42220 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30899 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 26018 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25779 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25234 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25234 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 21533 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20162 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18590 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18099 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17959 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17552 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15368 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15050 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14728 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14022 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13279 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13042 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12817 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12805 | `istanbul cover _mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12561 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12530 | `mocha --require @babel/register --reporter dot` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12359 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12349 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11622 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11311 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10938 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10863 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10701 | `mocha` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8203 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8068 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8046 | `./node_modules/.bin/mocha test` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8034 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7977 | `mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7956 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7895 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7561 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7549 | `mocha --exit --require @babel/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7532 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7451 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7266 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7205 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7130 | `mocha $HARMONY_OPTS` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6993 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6921 | `mocha test/test.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8945 | `mocha test/src` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8875 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8708 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8610 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8586 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8478 | `grunt clean:test && mocha --exit` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8400 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8318 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8277 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8203 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8068 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8046 | `./node_modules/.bin/mocha test` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8034 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7977 | `mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7956 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7895 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6602 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6413 | `npm run test:mocha:src` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6333 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6311 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6247 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6175 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6117 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6068 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6056 | `standard && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5931 | `mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6602 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6413 | `npm run test:mocha:src` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6333 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6311 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6284 | `mocha tests/node.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6247 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6228 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6175 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6117 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6068 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6056 | `standard && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5931 | `mocha` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 5930 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5902 | `mocha && eslint lib/**` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5815 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5806 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5795 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5719 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [teambit/bit](https://github.com/teambit/bit) | 5683 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5660 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5612 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5584 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5438 | `mocha test` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5421 | `mocha -r esm` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5401 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5374 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4983 | `nyc mocha --exit` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4974 | `gulp build; mocha;` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4939 | `nyc mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4920 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4918 | `./node_modules/.bin/mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4893 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4869 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4856 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4846 | `mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4752 | `mocha --reporter spec -t 8000` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4586 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4561 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4869 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4856 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4846 | `mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4752 | `mocha --reporter spec -t 8000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4695 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4651 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4586 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4561 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4487 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4460 | `mocha --timeout=15000 tests/*.test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4449 | `NODE_ENV=test mocha --exit` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4429 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4399 | `mocha --check-leaks --reporter spec --bail` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4296 | `npm run lint ; mocha && mocha test/individual` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4210 | `npm run build && cd test && mocha . --reporter dot` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4192 | `mocha -R spec ./test --recursive` | 
| [muicss/mui](https://github.com/muicss/mui) | 4144 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 4098 | `mocha --require should --reporter spec` | 
| [expressjs/session](https://github.com/expressjs/session) | 4031 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3959 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3935 | `NODE_ENV=test mocha test/**/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3858 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [erming/shout](https://github.com/erming/shout) | 3796 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3788 | `mocha && tsc -p ./test/types` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3772 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3938 | `export TESTING=true; mocha --reporter list` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3900 | `npm run mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3832 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3828 | `npm run build && mocha test/*.test.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3803 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [erming/shout](https://github.com/erming/shout) | 3796 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3750 | `eslint . && mocha -t 5000` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 3743 | `./node_modules/mocha/bin/mocha --require babel-core/register test/*` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3738 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3711 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3677 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3676 | `node_modules/.bin/mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3631 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3589 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3561 | `nyc mocha && tsc` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3503 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3495 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3466 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3459 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3432 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3414 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3405 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3393 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3382 | `mocha -R landing test/index --exit` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3343 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3335 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3266 | `mocha test/*.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3243 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3235 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3231 | `mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 3229 | `mocha --require should --reporter spec` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3187 | `./node_modules/.bin/mocha test/test.*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3171 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3102 | `nyc mocha --recursive` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3079 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3063 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3037 | `node_modules/.bin/mocha --reporter spec` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3017 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2991 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2985 | `mocha --require @babel/register --recursive spec` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2978 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2970 | `mocha -R spec --recursive src/test` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3067 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3063 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3037 | `node_modules/.bin/mocha --reporter spec` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3032 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2991 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2985 | `mocha --require @babel/register --recursive spec` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2978 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2971 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2970 | `mocha -R spec --recursive src/test` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2962 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2933 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2918 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2905 | `mocha -R spec spec spec/reporters` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2874 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2692 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2684 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2664 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2592 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2572 | `mocha test --exit && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2567 | `mocha && eslint .` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2565 | `mocha test/src/**/*.unit.js` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2563 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2559 | `TEST=all mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2558 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2554 | `mocha test` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2544 | `nyc --reporter=html --reporter=text mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2528 | `mocha --reporter=spec test/*-test.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2523 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2512 | `mocha test/index.js --reporter dot` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2510 | `mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2473 | `mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2722 | `nyc mocha --timeout=10000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2716 | `mocha --recursive --watch` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2692 | `mocha --timeout 100000` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2692 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2684 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2664 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2634 | `mocha-phantomjs ./test/index.html` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2616 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2592 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2567 | `mocha && eslint .` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2565 | `mocha test/src/**/*.unit.js` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2563 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2559 | `TEST=all mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2558 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2554 | `mocha test` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2367 | `node node_modules/mocha/bin/_mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 2323 | `npm run lint && npm run mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2322 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2297 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2291 | `mocha test/**/*.coffee` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2269 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2264 | `standard && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1779 | `mocha tests.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1767 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1754 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1750 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1747 | `mocha test/*.js` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1732 | `mocha test --timeout 600000` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1730 | `mocha --check-leaks --reporter spec --bail` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1729 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1724 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1717 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1716 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1711 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1692 | `npm run jshint && mocha --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1688 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1685 | `mocha && size-limit` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1676 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1672 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1692 | `npm run jshint && mocha --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1688 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1685 | `mocha && size-limit` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1676 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1659 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1654 | `NODE_ENV=test mocha tests/*.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1645 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1626 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1621 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1618 | `./node_modules/mocha/bin/mocha -R spec` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1617 | `mocha test.js` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1613 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1600 | `mocha -R spec ./test/unit/**` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1599 | `mocha test/unit` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1589 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1586 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1582 | `mocha tests/test-*` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1581 | `nyc mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1560 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1551 | `mocha --check-leaks --require @babel/register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1550 | `npm run test:lint && npm run test:mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1546 | `node_modules/.bin/mocha --recursive` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1542 | `npm run lint && npm run mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1538 | `mocha -u tdd` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1535 | `mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1542 | `npm run lint && npm run mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1541 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1538 | `mocha -u tdd` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1535 | `mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1534 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1530 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1530 | `npm run lint && mocha && karma start --single-run` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1528 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1527 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1525 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1519 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1512 | `mocha --timeout 10000 ./tests/lib.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1511 | `mocha test/**/*.spec.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1507 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [noble/bleno](https://github.com/noble/bleno) | 1506 | `mocha -R spec test/*.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1500 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1500 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1480 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1478 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1474 | `mocha test --compilers js:babel-core/register` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1473 | `mocha --reporter dot` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1473 | `mocha --opts test/opts/mocha.opts` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1467 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1461 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1454 | `mocha test.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1448 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1447 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1440 | `mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1433 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1431 | `npm run build && mocha -r should` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1431 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1411 | `webpack && npm run lint && npm run mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1407 | `mocha --recursive test/bin` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1403 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1397 | `mocha --check-leaks --reporter spec --bail test/` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1396 | `npm run mocha:istanbul` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1396 | `mocha --recursive` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1391 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1389 | `./node_modules/mocha/bin/mocha` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1386 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1380 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1376 | `./node_modules/.bin/mocha test` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1373 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1372 | `cross-env NODE_ENV=test nyc mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1371 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1335 | `lerna run test && mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1331 | `mocha --timeout 60000 test/` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1328 | `mocha tests/` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1326 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1326 | `mocha test/*.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1324 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1324 | `mocha` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1323 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1317 | `mocha src/test.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1317 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1313 | `npm run lint && npm run mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1310 | `mocha --timeout 30000 --recursive ./tests` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1308 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1306 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1306 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1302 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1299 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1299 | `mocha --timeout 20000` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1295 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1288 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1288 | `mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1353 | `npm run lint && mocha --require @babel/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1346 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1342 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1337 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1335 | `lerna run test && mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1332 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1331 | `mocha --timeout 60000 test/` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1328 | `mocha tests/` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1328 | `mocha spec/exec.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1326 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1326 | `mocha test/*.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1324 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1324 | `mocha` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1323 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1322 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1322 | `mocha-phantomjs tests/index.html` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1317 | `mocha src/test.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1317 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1313 | `npm run lint && npm run mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1299 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1299 | `mocha --timeout 20000` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1295 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1294 | `istanbul test _mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1288 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1288 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1279 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [variety/variety](https://github.com/variety/variety) | 1278 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1272 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1270 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1262 | `mocha tests` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1120 | `eslint src test && mocha --compilers babel-register` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1114 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1105 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1105 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1102 | `mocha --recursive --bail --reporter spec test` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1098 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1098 | `node_modules/.bin/mocha && npm run lint` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1097 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1091 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1088 | `mocha test/tests.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1078 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1076 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1070 | `mocha --async-only` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1152 | `webpack && mocha test/unit` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1149 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1145 | `npm run convertto:es5 && npm run mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1142 | `mocha && standard` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1131 | `standard && mocha -b` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1115 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1114 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1112 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1155 | `istanbul cover _mocha test/*.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1152 | `webpack && mocha test/unit` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1149 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 1142 | `mocha && standard` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1131 | `mocha test/*` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1131 | `standard && mocha -b` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1129 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1120 | `eslint src test && mocha --compilers babel-register` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1115 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1114 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1105 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1102 | `mocha --recursive --bail --reporter spec test` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1098 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1098 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1098 | `node_modules/.bin/mocha && npm run lint` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1097 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1096 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1091 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1088 | `mocha test/tests.js` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1091 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1088 | `mocha test/tests.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1078 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1076 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1074 | `npm run lint && npm run mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 1073 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1070 | `mocha --async-only` | 
| [odota/core](https://github.com/odota/core) | 1062 | `NODE_ENV=test mocha --exit` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1024 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1017 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1016 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1013 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1006 | `mocha --compilers js:babel-register test/*.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1006 | `mocha --check-leaks -R dot` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1005 | `mocha -R list` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 1005 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1005 | `./node_modules/.bin/mocha -R spec` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 996 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 994 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 986 | `mocha "client.test" --compilers js:babel-register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 983 | `mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 983 | `mocha --reporter spec` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 982 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 961 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 961 | `nyc mocha specs` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 955 | `mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 949 | `./node_modules/.bin/mocha test/**/*` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 946 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 938 | `mocha test` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 937 | `mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 937 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 937 | `mocha --timeout 5000` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 934 | `istanbul cover -- _mocha --reporter spec` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 955 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 954 | `mocha test --compilers js:babel-register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 950 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 949 | `./node_modules/.bin/mocha test/**/*` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 946 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 943 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 941 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 941 | `standard && standard ./bin/* && mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 938 | `mocha test` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 937 | `mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 937 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 937 | `mocha --timeout 5000` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 961 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 960 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 955 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 954 | `mocha test --compilers js:babel-register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 950 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 949 | `./node_modules/.bin/mocha test/**/*` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 946 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 943 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 941 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [nimiq-network/core](https://github.com/nimiq-network/core) | 899 | `NODE_ENV=test mocha --exit` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 897 | `node_modules/.bin/mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 894 | `mocha --timeout 200000` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 890 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 882 | `mocha --reporter list` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 878 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 878 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 872 | `mocha --harmony tests/**` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 894 | `mocha -r should --exit test/*.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 894 | `mocha --timeout 200000` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 892 | `npm run build && istanbul test _mocha test/test.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 890 | `node_modules/.bin/mocha test/spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 890 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 886 | `mocha --harmony --full-trace --check-leaks` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 882 | `mocha --reporter list` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 878 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 876 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 872 | `mocha --harmony tests/**` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 871 | `istanbul cover _mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 870 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 870 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 865 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 864 | `mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 861 | `mocha --reporter spec` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 861 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 860 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 860 | `npm run lint && mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 858 | `nyc mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 855 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 855 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [developit/decko](https://github.com/developit/decko) | 854 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 854 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 854 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 852 | `mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 852 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 848 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 848 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 845 | `mocha` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 844 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 844 | `mocha --opts mocha.opts` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 841 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 839 | `mocha --async-only` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 836 | `mocha test` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 833 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 832 | `mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 832 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 831 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 828 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 826 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [edsu/anon](https://github.com/edsu/anon) | 818 | `mocha --colors --reporter spec test.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 818 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 817 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 815 | `cake build && mocha ./test/mocha/*.coffee` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 814 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 810 | `mocha` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 810 | `_mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 808 | `mocha index.test.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 807 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 806 | `mocha test` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 805 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [ebradyjobory/finance.js](https://github.com/ebradyjobory/finance.js) | 805 | `mocha` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 804 | `mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 801 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 800 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 798 | `mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 796 | `mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 796 | `mocha --no-timeouts` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 792 | `eslint . && mocha` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 791 | `jenkins-mocha ./tests/*.js` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 787 | `mocha --recursive -s 15 test/` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 783 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 783 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [koajs/static](https://github.com/koajs/static) | 779 | `mocha --harmony --reporter spec --exit` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 778 | `mocha tests --timeout 10000` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 775 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 775 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 751 | `mocha tests/*.mocha.js` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 751 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 751 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 749 | `./node_modules/.bin/mocha tests/*.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 744 | `npm run test-mocha && npm run test-karma` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 744 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 742 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 740 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 739 | `mocha` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 738 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 737 | `mocha --compilers js:babel-core/register` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 727 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 725 | `mocha` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 723 | `mocha ./test/index.js` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 721 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 716 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 707 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 706 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 705 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 705 | `mocha` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 744 | `npm run test-mocha && npm run test-karma` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 744 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 744 | `mocha test.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 742 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 740 | `npm run bundle && mocha` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 740 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 739 | `mocha` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 738 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 737 | `mocha --compilers js:babel-core/register` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 736 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 736 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [electron/apps](https://github.com/electron/apps) | 735 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 735 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 734 | `mocha ./test/test.js --timeout 1000000` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 734 | `mocha --reporter spec --bail --check-leaks test/` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 729 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 727 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 727 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 725 | `mocha` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 723 | `mocha ./test/index.js` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 723 | `mocha --reporter spec` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 721 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 720 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [formio/formio](https://github.com/formio/formio) | 718 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 716 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 711 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 707 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 706 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 705 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 705 | `mocha` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 704 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 703 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [mtth/avsc](https://github.com/mtth/avsc) | 672 | `mocha` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 671 | `mocha -b -R spec test/*` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 671 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 669 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [expressjs/cookie-session](https://github.com/expressjs/cookie-session) | 669 | `mocha --check-leaks --reporter spec --bail test/` | 
| [godaddy/terminus](https://github.com/godaddy/terminus) | 667 | `mocha index.spec.js lib/**/*.spec.js && npm run test-typings` | 
| [IjzerenHein/autolayout.js](https://github.com/IjzerenHein/autolayout.js) | 666 | `mocha` | 
| [stevenvachon/broken-link-checker](https://github.com/stevenvachon/broken-link-checker) | 665 | `mocha test/ --reporter spec --check-leaks --bail` | 
| [coinbase/gdax-node](https://github.com/coinbase/gdax-node) | 663 | `mocha --full-trace --ui tdd --bail --reporter spec tests/*.js` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 663 | `mocha` | 
| [shelljs/shx](https://github.com/shelljs/shx) | 661 | `nyc --reporter=text --reporter=lcov mocha` | 
| [joaonuno/tree-model-js](https://github.com/joaonuno/tree-model-js) | 661 | `istanbul cover _mocha` | 
| [Ivshti/linvodb3](https://github.com/Ivshti/linvodb3) | 659 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [maxkueng/victor](https://github.com/maxkueng/victor) | 659 | `mocha --ui bdd --reporter spec` | 
| [theoephraim/node-google-spreadsheet](https://github.com/theoephraim/node-google-spreadsheet) | 658 | `node_modules/.bin/mocha` | 
| [calmm-js/partial.lenses](https://github.com/calmm-js/partial.lenses) | 658 | `nyc mocha && nyc report -r html mocha` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 658 | `mocha --reporter spec` | 
| [catamphetamine/universal-webpack](https://github.com/catamphetamine/universal-webpack) | 658 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 658 | `mocha` | 
| [mtth/avsc](https://github.com/mtth/avsc) | 672 | `mocha` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 671 | `mocha -b -R spec test/*` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 671 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [expressjs/cookie-session](https://github.com/expressjs/cookie-session) | 669 | `mocha --check-leaks --reporter spec --bail test/` | 
| [godaddy/terminus](https://github.com/godaddy/terminus) | 667 | `mocha index.spec.js lib/**/*.spec.js && npm run test-typings` | 
| [IjzerenHein/autolayout.js](https://github.com/IjzerenHein/autolayout.js) | 666 | `mocha` | 
| [stevenvachon/broken-link-checker](https://github.com/stevenvachon/broken-link-checker) | 665 | `mocha test/ --reporter spec --check-leaks --bail` | 
| [coinbase/gdax-node](https://github.com/coinbase/gdax-node) | 663 | `mocha --full-trace --ui tdd --bail --reporter spec tests/*.js` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 663 | `mocha` | 
| [joaonuno/tree-model-js](https://github.com/joaonuno/tree-model-js) | 661 | `istanbul cover _mocha` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 660 | `mocha --recursive --compilers js:babel-core/register` | 
| [Ivshti/linvodb3](https://github.com/Ivshti/linvodb3) | 659 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [maxkueng/victor](https://github.com/maxkueng/victor) | 659 | `mocha --ui bdd --reporter spec` | 
| [dtschust/redux-bug-reporter](https://github.com/dtschust/redux-bug-reporter) | 658 | `standard && mocha --compilers js:babel-register --recursive --require test/setup.js` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 658 | `mocha --reporter spec` | 
| [catamphetamine/universal-webpack](https://github.com/catamphetamine/universal-webpack) | 658 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 658 | `mocha` | 