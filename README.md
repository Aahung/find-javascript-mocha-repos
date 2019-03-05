# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:41 03/05/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45375 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42682 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42377 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30968 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 26186 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25946 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25488 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25294 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 21727 | `npm-run-all lint build --parallel test:mocha test:karma test:ts` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20282 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18770 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18274 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18122 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17842 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15532 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15174 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14770 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14116 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13874 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13436 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13077 | `mocha 'test/**/*.spec.js'` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12927 | `istanbul cover _mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12873 | `mocha --reporter spec test/*-test.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12734 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12670 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12443 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12376 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11736 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11493 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11317 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 11018 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10974 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10763 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10717 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10486 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9990 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9875 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9750 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9636 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9551 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9488 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9387 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9263 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9006 | `mocha test/src` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8985 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 8969 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8728 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8643 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8593 | `mocha --check-leaks -R dot` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8532 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8504 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8334 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8298 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8287 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8166 | `mocha` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8129 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8099 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8087 | `./node_modules/.bin/mocha test` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8052 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7954 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7153 | `mocha $HARMONY_OPTS` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7130 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7124 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 7033 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6627 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6434 | `npm run test:mocha:src` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6411 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6403 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6330 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6325 | `mocha tests/node.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6220 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6200 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6160 | `standard && mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6627 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6434 | `npm run test:mocha:src` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6411 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6403 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6330 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6325 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6260 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6220 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6200 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6160 | `standard && mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6149 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6068 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5945 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 5943 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5926 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5920 | `mocha && eslint lib/**` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5913 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5825 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5751 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5719 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5692 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5626 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5512 | `mocha test` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5481 | `mocha -r esm` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5447 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5412 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5400 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5336 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5209 | `mocha src/**/*Tests.js --harmony` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5147 | `mocha --recursive` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5138 | `gulp lint && mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5130 | `npm run lint && npm run mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5128 | `mocha --color` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5072 | `nyc mocha --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5039 | `nyc mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4998 | `gulp build; mocha;` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4973 | `NODE_ENV=test mocha --exit` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4965 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4931 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4913 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4883 | `mocha -R spec 'tests/app'` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4882 | `mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4866 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4781 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4761 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4692 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4590 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4573 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4511 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4492 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4488 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4480 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4452 | `mocha --check-leaks --reporter spec --bail` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4393 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4383 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4344 | `npm run lint ; mocha && mocha test/individual` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4249 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4191 | `mocha -R spec ./test --recursive` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 4170 | `./node_modules/mocha/bin/mocha --require @babel/register test/*` | 
| [muicss/mui](https://github.com/muicss/mui) | 4155 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4148 | `mocha --require test/babel-hook test/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4133 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4063 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 4091 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4063 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 4008 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3978 | `NODE_ENV=test mocha test/**/*.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3939 | `export TESTING=true; mocha --reporter list` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3933 | `mocha && tsc -p ./test/types` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3871 | `eslint . && mocha -t 5000` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3854 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [primus/primus](https://github.com/primus/primus) | 3838 | `npm run build && mocha test/*.test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3835 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3830 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3809 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3796 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3297 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3269 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3265 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3195 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3187 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3178 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3139 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3122 | `nyc mocha --recursive` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3048 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3013 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2989 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2981 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2923 | `mocha -R spec spec spec/reporters` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2873 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3469 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3452 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3448 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3446 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3432 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3426 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3425 | `mocha -R landing test/index --exit` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3351 | `mocha test/index.js && npm run demo` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3297 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3026 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 3021 | `mocha --require @babel/register --recursive spec` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2981 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2979 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2936 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2923 | `mocha -R spec spec spec/reporters` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2918 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2873 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2849 | `istanbul cover _mocha` | 
| [css/csso](https://github.com/css/csso) | 2836 | `mocha --reporter dot` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2828 | `mocha "./test/**/*-test.js"` | 
| [tj/should.js](https://github.com/tj/should.js) | 2733 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2718 | `mocha test/unit --require mochahook` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2702 | `mocha --timeout 100000` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2683 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2651 | `mocha-phantomjs ./test/index.html` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2631 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2605 | `mocha test --exit && npm run lint` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2602 | `TEST=all mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2595 | `mocha && eslint .` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2589 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2587 | `mocha test/src/**/*.unit.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2577 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2569 | `mocha test` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2536 | `mocha --reporter=spec test/*-test.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2535 | `mocha test/index.js --reporter dot` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2534 | `export TESTING=true; mocha --reporter list` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2388 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2366 | `node node_modules/mocha/bin/_mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2345 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2336 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2332 | `mocha test/**/*.coffee` | 
| [gajus/swing](https://github.com/gajus/swing) | 2332 | `mocha --compilers js:babel-register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2320 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2314 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2290 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2252 | `mocha && eslint *.js` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2388 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2366 | `node node_modules/mocha/bin/_mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2345 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2336 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2332 | `mocha test/**/*.coffee` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2320 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2320 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2314 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2290 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1336 | `mocha --timeout 60000 test/` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1333 | `mocha --timeout 20000` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1331 | `mocha --timeout 30000 --recursive ./tests` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1329 | `mocha spec/exec.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1326 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1322 | `mocha-phantomjs tests/index.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1302 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1300 | `istanbul test _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1300 | `mocha` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1293 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1252 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1222 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [zeit/ms](https://github.com/zeit/ms) | 1914 | `mocha tests.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1907 | `mocha ./test/basic.js -t 5000` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1880 | `eslint --cache . && tslint --project . && node build && mocha && tsc` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1863 | `mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1847 | `npm run lint && npm run mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1835 | `mocha test/setup.js test/spec/*.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1825 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1824 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1815 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1794 | `mocha --timeout 5000` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1790 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1783 | `mocha` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1779 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1774 | `npm run lint && mocha && npm run typescript` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1760 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1758 | `mocha test/*.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1757 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1755 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1754 | `mocha --check-leaks --reporter spec --bail` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1747 | `./node_modules/.bin/mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1746 | `mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1741 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1734 | `mocha test --timeout 600000` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1732 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1732 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1731 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1715 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1692 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1691 | `mocha && size-limit` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1691 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1681 | `NODE_ENV=test mocha tests/*.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1672 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1630 | `mocha test/unit` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1627 | `./node_modules/mocha/bin/mocha -R spec` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1626 | `mocha test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1624 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1622 | `mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1618 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1614 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1608 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1589 | `nyc mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1569 | `mocha --check-leaks --require @babel/register` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1562 | `npm run lint && npm run mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1560 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1560 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1550 | `mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1546 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1545 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1545 | `mocha -u tdd` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1536 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1533 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1530 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1528 | `mocha --recursive test` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1523 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1521 | `mocha --timeout 10000 ./tests/lib.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1521 | `mocha test/**/*.spec.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1520 | `mocha -R spec test/*.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1510 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1509 | `npm run prepublishOnly && mocha test/test.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1350 | `mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1349 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1342 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1336 | `mocha --timeout 60000 test/` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1336 | `mocha test/*.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1333 | `mocha --timeout 20000` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1332 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1331 | `mocha --timeout 30000 --recursive ./tests` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1329 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1329 | `mocha spec/exec.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1326 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1322 | `mocha-phantomjs tests/index.html` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1304 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1302 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1300 | `istanbul test _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1300 | `mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1498 | `mocha --reporter dot` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1491 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1489 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1487 | `mocha --opts test/opts/mocha.opts` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1471 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [samccone/drool](https://github.com/samccone/drool) | 1463 | `mocha test/tests.js --timeout=10000` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1456 | `mocha test.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1455 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1450 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1448 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1337 | `npm run lint && npm run mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1333 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1333 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1333 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1331 | `mocha --timeout 30000 --recursive ./tests` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1329 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1329 | `mocha spec/exec.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1328 | `mocha src/test.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1326 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1322 | `mocha-phantomjs tests/index.html` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1310 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1309 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1304 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1300 | `istanbul test _mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1297 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1293 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1351 | `mocha tests/` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1350 | `mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1349 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1348 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1347 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1342 | `lerna run test && mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1342 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1342 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1339 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1337 | `npm run lint && npm run mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1336 | `mocha --timeout 60000 test/` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1336 | `mocha test/*.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1333 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1333 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1333 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1333 | `mocha --timeout 20000` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1332 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1331 | `mocha --timeout 30000 --recursive ./tests` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1264 | `mocha tests` | 
| [normalize/mz](https://github.com/normalize/mz) | 1261 | `mocha --reporter spec` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1252 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1252 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1249 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1240 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1232 | `mocha test` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1231 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1222 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1219 | `mocha --recursive -r tests/setup tests` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1216 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1213 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1213 | `mocha --reporter spec --bail --check-leaks test/` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1222 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1219 | `mocha --recursive -r tests/setup tests` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1216 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1213 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1213 | `mocha --reporter spec --bail --check-leaks test/` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1209 | `mocha --reporter spec test --recursive` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1209 | `mocha test` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1207 | `mocha test/test.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1205 | `npm-run-all test:jest test:server:mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1199 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1194 | `xo && mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1184 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1180 | `mocha $(find test -name '*.test.js') --exit` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1178 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1176 | `mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1174 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1168 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1168 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1161 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1160 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1159 | `npm run convertto:es5 && npm run mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1157 | `istanbul cover _mocha test/*.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 1152 | `mocha && standard` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1138 | `npm run lint && npm run mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1136 | `standard && mocha -b` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1138 | `npm run lint && npm run mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1134 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1133 | `mocha test/*` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1131 | `eslint src test && mocha --compilers babel-register` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1117 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1116 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1112 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1110 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1110 | `mocha` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1108 | `mocha --recursive --bail --reporter spec test` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1101 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1102 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1101 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1101 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1097 | `mocha --check-leaks -t 20000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1097 | `node_modules/.bin/mocha && npm run lint` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1093 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1087 | `mocha test/tests.js` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1086 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 1083 | `mocha test` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1072 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1072 | `mocha --async-only` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1065 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1060 | `mocha test/*.test.js` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1058 | `mocha $(find test -name '*.test.js')` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1051 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1039 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1038 | `mocha --recursive test/unit/` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 1038 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1031 | `mocha --reporter spec --bail --check-leaks test/` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1030 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1029 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 989 | `mocha "client.test" --compilers js:babel-register` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 983 | `mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 982 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 982 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 981 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 981 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 979 | `mocha -t 600000 --exit` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 979 | `npm run rollup-cjs && mocha test/test.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 977 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 969 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 968 | `nyc mocha specs` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 968 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 964 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 963 | `mocha` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 962 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 962 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 989 | `mocha "client.test" --compilers js:babel-register` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 984 | `mocha --reporter spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 983 | `mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 982 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 982 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 981 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 981 | `mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 981 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 979 | `mocha -t 600000 --exit` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 979 | `npm run rollup-cjs && mocha test/test.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 977 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 970 | `./node_modules/.bin/mocha --reporter spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 969 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 968 | `nyc mocha specs` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 968 | `mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 967 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 964 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 963 | `mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 963 | `./node_modules/.bin/mocha test/**/*` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 962 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 962 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 962 | `standard && standard ./bin/* && mocha` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 955 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 861 | `mocha -r babel-register --check-leaks test/index.js` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 860 | `nyc mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 858 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 856 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 855 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 844 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 841 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 839 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 838 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 837 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 834 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 834 | `mocha test` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 832 | `mocha test/mocha.js test/crc/index.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 832 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 832 | `mocha && ember test` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 888 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 886 | `mocha --reporter list` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 885 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 877 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 875 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 872 | `istanbul cover _mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 871 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 869 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 866 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 865 | `mocha --reporter spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 825 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 823 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 821 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 819 | `mocha --colors --reporter spec test.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 816 | `mocha index.test.js` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 813 | `mocha` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 810 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 810 | `mocha test` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 809 | `eslint . && mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 807 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 804 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 798 | `mocha --no-timeouts` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 798 | `xo && mocha -R spec` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 797 | `npm run lint && npm run mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 797 | `mocha tests --timeout 10000` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 792 | `mocha --recursive -s 15 test/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 786 | `mocha` | 
| [fivdi/onoff](https://github.com/fivdi/onoff) | 785 | `nyc mocha` | 
| [koajs/static](https://github.com/koajs/static) | 782 | `mocha --harmony --reporter spec --exit` | 
| [fivdi/onoff](https://github.com/fivdi/onoff) | 785 | `nyc mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 782 | `mocha` | 
| [koajs/static](https://github.com/koajs/static) | 782 | `mocha --harmony --reporter spec --exit` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 779 | `babel-node node_modules/.bin/_mocha -- test` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 777 | `npm run-script jshint && npm run-script mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 777 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 775 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 774 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 774 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 774 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 773 | `npm run lint&&mocha tests/*.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 771 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 771 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [electron/apps](https://github.com/electron/apps) | 751 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 751 | `npm run test-mocha && npm run test-karma` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 751 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 746 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 746 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 746 | `mocha test.js` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 744 | `mocha --compilers js:babel-core/register` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 743 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 742 | `mocha` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 742 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 741 | `npm run bundle && mocha` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 740 | `mocha $(find test -name '*.test.js')` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 738 | `mocha ./test/test.js --timeout 1000000` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 738 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 737 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 737 | `mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 737 | `mocha` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 735 | `mocha --reporter spec test/` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 731 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 729 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 727 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [formio/formio](https://github.com/formio/formio) | 732 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 731 | `mocha` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 730 | `mocha --reporter spec` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 729 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 727 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 727 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 726 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 722 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 721 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 722 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 721 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 718 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 717 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 716 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 708 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [Kagami/ffmpeg.js](https://github.com/Kagami/ffmpeg.js) | 707 | `mocha test/test.js` | 
| [afc163/fanyi](https://github.com/afc163/fanyi) | 687 | `npm run lint && mocha tests/index.js --timeout 0` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 687 | `mocha --require babel-register src/**/*.spec.js src/*.spec.js` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 685 | `mocha --compilers js:babel-register` | 
| [klokantech/tileserver-gl](https://github.com/klokantech/tileserver-gl) | 684 | `mocha test/**.js --timeout 10000` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 683 | `mocha --bail test/` | 
| [expressjs/cookie-session](https://github.com/expressjs/cookie-session) | 679 | `mocha --check-leaks --reporter spec --bail test/` | 
| [godaddy/terminus](https://github.com/godaddy/terminus) | 678 | `mocha index.spec.js lib/**/*.spec.js && npm run test-typings` | 
| [mtth/avsc](https://github.com/mtth/avsc) | 677 | `mocha` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 674 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [stevenvachon/broken-link-checker](https://github.com/stevenvachon/broken-link-checker) | 673 | `mocha test/ --reporter spec --check-leaks --bail` | 
| [gtanner/qrcode-terminal](https://github.com/gtanner/qrcode-terminal) | 673 | `./node_modules/jshint/bin/jshint lib vendor && node example/basic.js && ./node_modules/mocha/bin/mocha -R nyan` | 
| [expressjs/cookie-session](https://github.com/expressjs/cookie-session) | 679 | `mocha --check-leaks --reporter spec --bail test/` | 
| [godaddy/terminus](https://github.com/godaddy/terminus) | 678 | `mocha index.spec.js lib/**/*.spec.js && npm run test-typings` | 
| [shime/livedown](https://github.com/shime/livedown) | 677 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 676 | `mocha --require babel-register` | 
| [Munter/subfont](https://github.com/Munter/subfont) | 676 | `npm run lint && mocha` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 674 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [gtanner/qrcode-terminal](https://github.com/gtanner/qrcode-terminal) | 673 | `./node_modules/jshint/bin/jshint lib vendor && node example/basic.js && ./node_modules/mocha/bin/mocha -R nyan` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 671 | `mocha -b -R spec test/*` | 
| [shelljs/shx](https://github.com/shelljs/shx) | 670 | `nyc --reporter=text --reporter=lcov mocha` | 
| [calmm-js/partial.lenses](https://github.com/calmm-js/partial.lenses) | 668 | `nyc mocha && nyc report -r html mocha` | 
| [coinbase/gdax-node](https://github.com/coinbase/gdax-node) | 667 | `mocha --full-trace --ui tdd --bail --reporter spec tests/*.js` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 667 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 667 | `mocha` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 676 | `mocha --require babel-register` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 674 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [stevenvachon/broken-link-checker](https://github.com/stevenvachon/broken-link-checker) | 673 | `mocha test/ --reporter spec --check-leaks --bail` | 
| [gtanner/qrcode-terminal](https://github.com/gtanner/qrcode-terminal) | 673 | `./node_modules/jshint/bin/jshint lib vendor && node example/basic.js && ./node_modules/mocha/bin/mocha -R nyan` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 671 | `mocha -b -R spec test/*` | 
| [CharlesStover/reactn](https://github.com/CharlesStover/reactn) | 670 | `mocha -r chai/register-expect -r @babel/register -r ts-node/register "tests/**/*.spec.ts?(x)"` | 
| [calmm-js/partial.lenses](https://github.com/calmm-js/partial.lenses) | 668 | `nyc mocha && nyc report -r html mocha` | 
| [IjzerenHein/autolayout.js](https://github.com/IjzerenHein/autolayout.js) | 668 | `mocha` | 
| [coinbase/gdax-node](https://github.com/coinbase/gdax-node) | 667 | `mocha --full-trace --ui tdd --bail --reporter spec tests/*.js` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 667 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 667 | `mocha` | 
| [catamphetamine/universal-webpack](https://github.com/catamphetamine/universal-webpack) | 666 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [theoephraim/node-google-spreadsheet](https://github.com/theoephraim/node-google-spreadsheet) | 664 | `node_modules/.bin/mocha` | 
| [joaonuno/tree-model-js](https://github.com/joaonuno/tree-model-js) | 664 | `istanbul cover _mocha` | 
| [hparra/gulp-rename](https://github.com/hparra/gulp-rename) | 635 | `mocha` | 
| [werk85/node-html-to-text](https://github.com/werk85/node-html-to-text) | 635 | `istanbul cover _mocha && eslint .` | 
| [DEgITx/rats-search](https://github.com/DEgITx/rats-search) | 634 | `mocha temp/tests.js --require @babel/core/lib --require source-map-support/register` | 
| [nexus-js/ui](https://github.com/nexus-js/ui) | 634 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [jaredhanson/passport-google-oauth](https://github.com/jaredhanson/passport-google-oauth) | 632 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [puleos/object-hash](https://github.com/puleos/object-hash) | 630 | `node ./node_modules/.bin/mocha test` | 
| [tj/node-blocked](https://github.com/tj/node-blocked) | 630 | `./node_modules/mocha/bin/mocha` | 
| [backstrokeapp/server](https://github.com/backstrokeapp/server) | 629 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [susielu/d3-legend](https://github.com/susielu/d3-legend) | 628 | `mocha` | 
| [webpack/memory-fs](https://github.com/webpack/memory-fs) | 628 | `mocha` | 
| [M6Web/websocket-bench](https://github.com/M6Web/websocket-bench) | 625 | `gulp mocha` | 
| [mysamai/mysam](https://github.com/mysamai/mysam) | 625 | `npm run lint && npm run mocha` | 
| [adamgruber/mochawesome](https://github.com/adamgruber/mochawesome) | 625 | `npm run lint && cross-env NODE_ENV=test nyc mocha` | 
| [amasad/debug_utils](https://github.com/amasad/debug_utils) | 624 | `mocha ./test --bail` | 