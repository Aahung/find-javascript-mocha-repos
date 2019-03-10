# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:56:07 03/10/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45434 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42769 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42419 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30977 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25997 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25554 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25305 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 21854 | `npm-run-all lint build --parallel test:mocha test:karma test:ts` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20311 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18310 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18153 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17918 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15588 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15207 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14792 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14139 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13912 | `mocha --globals document test` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12721 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12470 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12378 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11763 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11543 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11344 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 11052 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 11013 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10778 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10766 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 10019 | `mocha tests/*.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 11013 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10778 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10766 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10497 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 10019 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9899 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9756 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9655 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9574 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9494 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9401 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9301 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 9030 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 9028 | `mocha test/*/**` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9013 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8730 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8651 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8597 | `mocha --check-leaks -R dot` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8570 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8512 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8366 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8296 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8296 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8218 | `mocha` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8150 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8107 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8104 | `./node_modules/.bin/mocha test` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8073 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7970 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7134 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 7060 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6640 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6442 | `npm run test:mocha:src` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6429 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6426 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6334 | `mocha tests/node.js` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6260 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6238 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6189 | `standard && mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6155 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6442 | `npm run test:mocha:src` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6429 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6426 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6350 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6334 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6265 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6260 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6238 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6189 | `standard && mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6155 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 6007 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5972 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5938 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5930 | `mocha && eslint lib/**` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5922 | `mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5836 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5820 | `npm run lint && mocha tests/**/*.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5482 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5424 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5397 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5371 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5211 | `mocha src/**/*Tests.js --harmony` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5165 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5152 | `npm run lint && npm run mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5145 | `gulp lint && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5127 | `mocha --color` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5082 | `nyc mocha --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5058 | `nyc mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 5017 | `NODE_ENV=test mocha --exit` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 5002 | `gulp build; mocha;` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4977 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4935 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4917 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4886 | `mocha -R spec 'tests/app'` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4885 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5397 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5371 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5211 | `mocha src/**/*Tests.js --harmony` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5165 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5152 | `npm run lint && npm run mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5145 | `gulp lint && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5127 | `mocha --color` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5082 | `nyc mocha --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5058 | `nyc mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 5017 | `NODE_ENV=test mocha --exit` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 5002 | `gulp build; mocha;` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4977 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4935 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4917 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4886 | `mocha -R spec 'tests/app'` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4885 | `mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4869 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4798 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4763 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4701 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4593 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4587 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4521 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4518 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4502 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4491 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4468 | `mocha --check-leaks --reporter spec --bail` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4397 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4359 | `npm run lint && snyk test && mocha && mocha test/individual` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4269 | `npm run build && cd test && mocha . --reporter dot` | 
| [muicss/mui](https://github.com/muicss/mui) | 4163 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 4119 | `mocha --require should --reporter spec` | 
| [expressjs/session](https://github.com/expressjs/session) | 4109 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 4025 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [erming/shout](https://github.com/erming/shout) | 3795 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3755 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3754 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3753 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3985 | `NODE_ENV=test mocha test/**/*.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3960 | `mocha && tsc -p ./test/types` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3939 | `export TESTING=true; mocha --reporter list` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3896 | `eslint . && mocha -t 5000` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3852 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [primus/primus](https://github.com/primus/primus) | 3840 | `npm run build && mocha test/*.test.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3834 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3814 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3795 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3755 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3754 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3753 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3691 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3683 | `node_modules/.bin/mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3681 | `standard && mocha --timeout 60000 test/test.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3678 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3755 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3754 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3753 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3691 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3683 | `node_modules/.bin/mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3681 | `standard && mocha --timeout 60000 test/test.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3678 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3674 | `npm run jshint && npm run mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3614 | `nyc mocha && tsc` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3613 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3605 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3586 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3569 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3564 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3536 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3530 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3536 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3530 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3497 | `node_modules/.bin/mocha test/lib/` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3477 | `node ./test/import-test.js && mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3470 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3456 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3452 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3445 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3444 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3437 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3432 | `mocha -R landing test/index --exit` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3400 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3393 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3360 | `mocha test/index.js && npm run demo` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3053 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 3034 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 3029 | `mocha --require @babel/register --recursive spec` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3026 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2993 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2985 | `mocha` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2950 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2945 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2926 | `mocha -R spec spec spec/reporters` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2878 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2851 | `istanbul cover _mocha` | 
| [css/csso](https://github.com/css/csso) | 2836 | `mocha --reporter dot` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3075 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3055 | `mocha test-node` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3053 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 3044 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 3034 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3026 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3016 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2993 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2985 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2984 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2950 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2945 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2926 | `mocha -R spec spec spec/reporters` | 
| [github-tools/github](https://github.com/github-tools/github) | 2922 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2921 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2513 | `nyc --require babel-register npm run _mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2477 | `mocha -R spec` | 
| [noble/noble](https://github.com/noble/noble) | 2465 | `mocha -R spec test/*.js` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2455 | `mocha --no-colors --reporter spec` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2415 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2391 | `grunt jshint && mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 2382 | `npm run lint && npm run mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2366 | `node node_modules/mocha/bin/_mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2341 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2434 | `npm run build && mocha --require babel-register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2391 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2366 | `node node_modules/mocha/bin/_mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2356 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2341 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2338 | `mocha test/**/*.coffee` | 
| [gajus/swing](https://github.com/gajus/swing) | 2333 | `mocha --compilers js:babel-register` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2323 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2321 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2317 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2294 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2166 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2165 | `mocha --compilers js:babel-core/register __tests__` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2162 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2123 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2116 | `npm run mocha && npm run karma` | 
| [kach/nearley](https://github.com/kach/nearley) | 2108 | `mocha test/*.test.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2101 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2092 | `mocha tests --require @babel/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2082 | `mocha && npm run lint` | 
| [htmlhint/HTMLHint](https://github.com/htmlhint/HTMLHint) | 2070 | `mocha` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2065 | `npm run lint && mocha -R dot && npm run cover` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2061 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2058 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2049 | `mocha --reporter spec --timeout 5000` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2132 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2123 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2116 | `npm run mocha && npm run karma` | 
| [kach/nearley](https://github.com/kach/nearley) | 2108 | `mocha test/*.test.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2101 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2092 | `mocha tests --require @babel/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2082 | `mocha && npm run lint` | 
| [htmlhint/HTMLHint](https://github.com/htmlhint/HTMLHint) | 2070 | `mocha` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2065 | `npm run lint && mocha -R dot && npm run cover` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2058 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2049 | `mocha --reporter spec --timeout 5000` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 2039 | `mocha --recursive` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2029 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 2025 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2017 | `mocha --require=test/test_helper.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 2002 | `mocha test/**/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1986 | `mocha --reporter spec && npm run test-typescript` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1974 | `bmocha --reporter spec test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1971 | `npm run lint && mocha --reporter spec test/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1963 | `mocha -c test/index.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1960 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1933 | `mocha tests.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1928 | `mocha ./test/basic.js -t 5000` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1896 | `eslint --cache . && tslint --project . && node build && mocha && tsc` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1885 | `mocha tests.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1913 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1896 | `eslint --cache . && tslint --project . && node build && mocha && tsc` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1885 | `mocha tests.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1867 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1865 | `npm run lint && npm run mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1863 | `mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1850 | `npm run lint && npm run mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1838 | `mocha test/setup.js test/spec/*.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1794 | `mocha --timeout 5000` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1793 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1778 | `npm run lint && mocha && npm run typescript` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1768 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1764 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1761 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1759 | `mocha test/*.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1757 | `mocha --check-leaks --reporter spec --bail` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1754 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1736 | `mocha test --timeout 600000` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1732 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1731 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1728 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1725 | `mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1724 | `mocha test/**/*_test.js --bail` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1715 | `mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1645 | `mocha --expose-gc --slow 300` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1644 | `mocha --recursive` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1640 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1637 | `mocha test/unit` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1633 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1631 | `mocha test.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1628 | `mocha -R spec ./test/unit/**` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1626 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1624 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1624 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1615 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1611 | `mocha tests/test-*` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1571 | `npm run lint && npm run mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1457 | `mocha test.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1452 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1449 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1443 | `npm run build && mocha -r should` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1443 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1441 | `webpack && npm run lint && npm run mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1425 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1424 | `mocha --recursive test/bin` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1420 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1401 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1401 | `mocha --recursive` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1400 | `mocha --compilers js:babel-core/register` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1397 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1387 | `./node_modules/.bin/mocha test` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1645 | `mocha --expose-gc --slow 300` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1644 | `mocha --recursive` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1640 | `mocha --reporter spec` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1640 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1637 | `mocha test/unit` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1633 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1631 | `mocha test.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1628 | `mocha -R spec ./test/unit/**` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1627 | `./node_modules/mocha/bin/mocha -R spec` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1626 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1624 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1624 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1624 | `mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1615 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1611 | `mocha tests/test-*` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1496 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1474 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [samccone/drool](https://github.com/samccone/drool) | 1464 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1457 | `mocha test.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1452 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1449 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1443 | `npm run build && mocha -r should` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1443 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1441 | `webpack && npm run lint && npm run mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1496 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1491 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1491 | `mocha --opts test/opts/mocha.opts` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1460 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1457 | `mocha test.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1452 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1449 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1433 | `npm run mocha:istanbul` | 
| [electron/devtron](https://github.com/electron/devtron) | 1425 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1424 | `mocha --recursive test/bin` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1423 | `mocha --check-leaks --reporter spec --bail test/` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1421 | `istanbul cover _mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1420 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1410 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1401 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1401 | `mocha --recursive` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1400 | `mocha --compilers js:babel-core/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1398 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1397 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1392 | `NODE_PATH=. mocha **/*.spec.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1390 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1389 | `./node_modules/mocha/bin/mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1387 | `./node_modules/.bin/mocha test` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1337 | `npm run lint && npm run mocha` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1336 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1333 | `mocha src/test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1333 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1332 | `mocha spec/exec.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1329 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1322 | `mocha-phantomjs tests/index.html` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1313 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1312 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1311 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1303 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1302 | `istanbul test _mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1298 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1295 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [variety/variety](https://github.com/variety/variety) | 1289 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1264 | `mocha tests` | 
| [normalize/mz](https://github.com/normalize/mz) | 1264 | `mocha --reporter spec` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1254 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1252 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1251 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1240 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1240 | `mocha test` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1240 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1240 | `mocha test` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1233 | `node ./node_modules/mocha/bin/mocha tests` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1223 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1223 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1222 | `mocha --recursive -r tests/setup tests` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1217 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1216 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1215 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1215 | `mocha --reporter spec test --recursive` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1212 | `mocha test` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1208 | `npm-run-all test:jest test:server:mocha` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1147 | `npm run lint && npm run mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1139 | `standard && mocha -b` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1134 | `mocha test/*` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1133 | `eslint src test && mocha --compilers babel-register` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1122 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1116 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1113 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1112 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1112 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1110 | `mocha --recursive --bail --reporter spec test` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1113 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1112 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1110 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1098 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1097 | `mocha --check-leaks -t 20000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1094 | `mocha --compilers js:babel-register` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1089 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1088 | `mocha test/tests.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1065 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1064 | `mocha test/*.test.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1052 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 1046 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1040 | `mocha --recursive test/unit/` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1039 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1032 | `mocha --reporter spec --bail --check-leaks test/` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1032 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1028 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1028 | `mocha spec/*.js` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1027 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1026 | `npm run lint && mocha -R spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1025 | `./node_modules/.bin/mocha -R spec` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1024 | `mocha --reporter spec --timeout 3000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1098 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1097 | `mocha --check-leaks -t 20000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1094 | `mocha --compilers js:babel-register` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1089 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1088 | `mocha test/tests.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 1085 | `mocha test` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1074 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1074 | `mocha --async-only` | 
| [odota/core](https://github.com/odota/core) | 1074 | `NODE_ENV=test mocha --exit` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1052 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 1046 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1040 | `mocha --recursive test/unit/` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1039 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1034 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1032 | `mocha --reporter spec --bail --check-leaks test/` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1032 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1028 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1028 | `mocha spec/*.js` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1027 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1026 | `npm run lint && mocha -R spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1025 | `./node_modules/.bin/mocha -R spec` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1024 | `mocha --reporter spec --timeout 3000` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1022 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [gulp-sourcemaps/gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) | 1021 | `mocha --async-only` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1020 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 937 | `mocha test/index.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 937 | `mocha --timeout 5000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 934 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 932 | `mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 926 | `mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 922 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 916 | `mocha -r should --exit test/*.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 913 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 911 | `npm run lint && npm run mocha:no-functional` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 937 | `mocha --timeout 5000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 934 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 932 | `mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 926 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 925 | `mocha -t 5000` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 924 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 922 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 963 | `standard && standard ./bin/* && mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 962 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 954 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 953 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 948 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 946 | `istanbul cover -- _mocha --reporter spec` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 945 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 937 | `mocha test/index.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 937 | `mocha --timeout 5000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 934 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 932 | `mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 926 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 925 | `mocha -t 5000` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 924 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 922 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 920 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 915 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 915 | `mocha test` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 913 | `mocha` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 906 | `mocha --harmony tests/**` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 904 | `npm run build && istanbul test _mocha test/test.js` | 
| [nimiq-network/core](https://github.com/nimiq-network/core) | 903 | `NODE_ENV=test mocha --exit` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 903 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 900 | `node_modules/.bin/mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 896 | `mocha --timeout 200000` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 894 | `npm run lint && mocha` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 893 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 891 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 895 | `mocha --harmony --full-trace --check-leaks` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 894 | `npm run lint && mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 893 | `node_modules/.bin/mocha test/spec` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 893 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 891 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 889 | `mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 888 | `mocha --reporter list` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 879 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 875 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 874 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 873 | `istanbul cover _mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 842 | `mocha test` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 841 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 839 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 839 | `mocha test` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 834 | `npm run mocha-test test/integration` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 834 | `mocha test/mocha.js test/crc/index.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 833 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 833 | `_mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 828 | `cake build && mocha ./test/mocha/*.coffee` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 826 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 826 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 823 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 819 | `mocha --colors --reporter spec test.js` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 817 | `mocha index.test.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 832 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 832 | `mocha && ember test` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 826 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 826 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 823 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 823 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 819 | `mocha --colors --reporter spec test.js` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 817 | `mocha index.test.js` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 815 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 814 | `mocha` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 812 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 812 | `mocha test` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 812 | `eslint . && mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 841 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 841 | `mocha --async-only` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 840 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 839 | `mocha test` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 839 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 837 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 834 | `npm run mocha-test test/integration` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 834 | `mocha test/mocha.js test/crc/index.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 833 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 833 | `_mocha` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 833 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 832 | `mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 832 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 832 | `mocha && ember test` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 828 | `cake build && mocha ./test/mocha/*.coffee` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 826 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 826 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [koajs/static](https://github.com/koajs/static) | 784 | `mocha --harmony --reporter spec --exit` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 780 | `npm run lint&&mocha tests/*.js` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 779 | `npm run-script jshint && npm run-script mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 777 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 777 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 775 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 775 | `mocha -R spec src/**/*_test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 807 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 806 | `mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 805 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 804 | `jenkins-mocha ./tests/*.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 799 | `mocha --no-timeouts` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 798 | `mocha tests --timeout 10000` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 797 | `nyc mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 796 | `npm run lint && npm run mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 794 | `mocha --recursive -s 15 test/` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 763 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [electron/apps](https://github.com/electron/apps) | 759 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 753 | `npm run test-mocha && npm run test-karma` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 753 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 751 | `mocha --reporter spec --bail --check-leaks test/` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 751 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 750 | `mocha tests/*.mocha.js` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 748 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 728 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 727 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 726 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 719 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 717 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [Kagami/ffmpeg.js](https://github.com/Kagami/ffmpeg.js) | 716 | `mocha test/test.js` | 