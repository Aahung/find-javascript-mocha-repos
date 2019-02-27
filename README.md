# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:26 02/27/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45305 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42599 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42335 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30951 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25901 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25421 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25268 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 21651 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20246 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18704 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18208 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18074 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17750 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15474 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15140 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14759 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14098 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12402 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12372 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11703 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11443 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11281 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10990 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10743 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10683 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10475 | `mocha --harmony` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9853 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9741 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10743 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10683 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10475 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9955 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9853 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9741 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9619 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9525 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9475 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9372 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9216 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8990 | `mocha test/src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6623 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6383 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6312 | `mocha tests/node.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6269 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6249 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6206 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6155 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5927 | `mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5908 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5892 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [teambit/bit](https://github.com/teambit/bit) | 5854 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5818 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5743 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5672 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7634 | `mocha --compilers js:babel-core/register` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7633 | `mocha --exit --require @babel/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7632 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7619 | `npm run build && istanbul cover _mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7606 | `mocha; jshint *.js lib` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7522 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7451 | `mocha` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7306 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7151 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7112 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7080 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6995 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6623 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6429 | `npm run test:mocha:src` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6391 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6383 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6312 | `mocha tests/node.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6269 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6249 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6206 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6155 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6140 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6126 | `standard && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6067 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5927 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5913 | `mocha && eslint lib/**` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5908 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5892 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [teambit/bit](https://github.com/teambit/bit) | 5854 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5818 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5743 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5676 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5672 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5619 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5488 | `mocha test` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5471 | `mocha -r esm` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5414 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5401 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5397 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5281 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5210 | `mocha src/**/*Tests.js --harmony` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5138 | `gulp lint && mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5132 | `mocha --recursive` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5128 | `mocha --color` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5108 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5052 | `nyc mocha --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4998 | `nyc mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4995 | `gulp build; mocha;` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4953 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4927 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4922 | `NODE_ENV=test mocha --exit` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4907 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4879 | `mocha -R spec 'tests/app'` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4876 | `mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4865 | `mocha test` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4756 | `mocha --reporter spec -t 8000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4752 | `mocha --recursive --colors` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4676 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4588 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4570 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4501 | `mocha --timeout=15000 tests/*.test.js` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4487 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4475 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4447 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4433 | `mocha --check-leaks --reporter spec --bail` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4403 | `node_modules/.bin/mocha test/tests.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4392 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4377 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4326 | `npm run lint ; mocha && mocha test/individual` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4249 | `npm run build && cd test && mocha . --reporter dot` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4247 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4191 | `mocha -R spec ./test --recursive` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4149 | `mocha --require test/babel-hook test/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4127 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4124 | `nyc mocha "test/**/*.test.js"` | 
| [tj/ejs](https://github.com/tj/ejs) | 4106 | `mocha --require should --reporter spec` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3796 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3750 | `mocha test/* --reporter spec` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3731 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3682 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3680 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3657 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3608 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3602 | `mocha tests/javascript` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3600 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3563 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3467 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3454 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3449 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3445 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3425 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3608 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3563 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3536 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3510 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3507 | `mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3496 | `node_modules/.bin/mocha test/lib/` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3454 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3448 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3445 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3416 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3410 | `mocha -R landing test/index --exit` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3373 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3367 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3467 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3454 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3449 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3448 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3445 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3425 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3373 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3367 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3336 | `mocha test/index.js && npm run demo` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3285 | `mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3283 | `mocha test/*.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 3271 | `mocha --require should --reporter spec` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3336 | `mocha test/index.js && npm run demo` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3285 | `mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3283 | `mocha test/*.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 3271 | `mocha --require should --reporter spec` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3260 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3260 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3235 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3196 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3189 | `./node_modules/.bin/mocha test/test.*.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3184 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3174 | `mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3133 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2738 | `nyc mocha --timeout=10000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2720 | `mocha --recursive --watch` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2706 | `mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2697 | `mocha --timeout 100000` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2677 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2627 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2597 | `mocha test --exit && npm run lint` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2594 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2586 | `TEST=all mocha` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2579 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2571 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2562 | `mocha test` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2557 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2550 | `mocha` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1908 | `mocha` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1884 | `mocha tests.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1861 | `npm run lint && npm run mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1841 | `npm run lint && npm run mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1820 | `mocha ./test/test*.js --reporter spec` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1758 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1743 | `./node_modules/.bin/mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1742 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1733 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1980 | `mocha --require ./test/common --growl test/expect.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1976 | `mocha --reporter spec && npm run test-typescript` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1966 | `mocha --bail --reporter spec --check-leaks test/` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1963 | `npm run lint && mocha --reporter spec test/*.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1954 | `mocha` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1939 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1937 | `nyc mocha --timeout=20000 test.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1935 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1931 | `mocha test` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1930 | `mocha --recursive` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1927 | `mocha test -u bdd -R spec` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1884 | `mocha tests.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1874 | `eslint --cache . && tslint --project . && node build && mocha && tsc` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1863 | `mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2597 | `mocha test --exit && npm run lint` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2594 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2586 | `TEST=all mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2584 | `mocha && eslint .` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2579 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2571 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2562 | `mocha test` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2557 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2557 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2551 | `nyc --reporter=html --reporter=text mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2550 | `mocha` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2534 | `export TESTING=true; mocha --reporter list` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2533 | `mocha --reporter=spec test/*-test.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2523 | `mocha test/index.js --reporter dot` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2498 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2497 | `nyc --require babel-register npm run _mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2488 | `mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2470 | `mocha -R spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2454 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2450 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [noble/noble](https://github.com/noble/noble) | 2445 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2425 | `npm run build && mocha --require babel-register` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2404 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2388 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2366 | `node node_modules/mocha/bin/_mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 2355 | `npm run lint && npm run mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2326 | `mocha --compilers js:babel-register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2320 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2315 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2313 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2277 | `standard && mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2244 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2218 | `mocha test test/unit/**/*_test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2212 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2211 | `mocha --timeout 15000 --bail --exit test/*-test.js test/security/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2208 | `mocha test/runner.js --reporter spec` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2199 | `mocha test/test-*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2180 | `mocha --compilers js:babel-register` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2165 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2155 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2144 | `mocha test` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2134 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2098 | `mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 2095 | `mocha test/*.test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2094 | `npm run mocha && npm run karma` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2087 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [htmlhint/HTMLHint](https://github.com/htmlhint/HTMLHint) | 2065 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2064 | `mocha tests --require @babel/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2060 | `mocha && npm run lint` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2058 | `npm run lint && mocha -R dot && npm run cover` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2058 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2043 | `mocha --reporter spec --timeout 5000` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2015 | `mocha --require=test/test_helper.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 2010 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1988 | `mocha test/**/*.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1980 | `mocha --require ./test/common --growl test/expect.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1976 | `mocha --reporter spec && npm run test-typescript` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1967 | `bmocha --reporter spec test/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1963 | `npm run lint && mocha --reporter spec test/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1958 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1954 | `mocha` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1939 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1937 | `nyc mocha --timeout=20000 test.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1927 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1908 | `mocha` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1963 | `npm run lint && mocha --reporter spec test/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1958 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1954 | `mocha` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1939 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1937 | `nyc mocha --timeout=20000 test.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1935 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1931 | `mocha test` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1930 | `mocha --recursive` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1927 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1908 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1899 | `mocha ./test/basic.js -t 5000` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1884 | `mocha tests.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1863 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1861 | `npm run lint && npm run mocha` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1939 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1935 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1931 | `mocha test` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1930 | `mocha --recursive` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1927 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1908 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1899 | `mocha ./test/basic.js -t 5000` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1884 | `mocha tests.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1874 | `eslint --cache . && tslint --project . && node build && mocha && tsc` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1863 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1861 | `npm run lint && npm run mocha` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1778 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1772 | `npm run lint && mocha && npm run typescript` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1758 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1750 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1748 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1743 | `./node_modules/.bin/mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1742 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1741 | `mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1733 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1733 | `mocha test --timeout 600000` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1731 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1727 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1727 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1725 | `mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1724 | `mocha test/**/*_test.js --bail` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1720 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1714 | `mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1772 | `npm run lint && mocha && npm run typescript` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1762 | `mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1758 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1752 | `mocha test/*.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1750 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1748 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1747 | `mocha --check-leaks --reporter spec --bail` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1743 | `./node_modules/.bin/mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1741 | `mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1733 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1733 | `mocha test --timeout 600000` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1731 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1727 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1727 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1725 | `mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1724 | `mocha test/**/*_test.js --bail` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1724 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1720 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1714 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1220 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1212 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1207 | `mocha test/test.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1207 | `mocha --reporter spec --bail --check-leaks test/` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1205 | `npm-run-all test:jest test:server:mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1199 | `mocha --reporter spec test --recursive` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1192 | `mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1180 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1177 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1177 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1177 | `mocha $(find test -name '*.test.js') --exit` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1168 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1168 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1347 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1343 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1340 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1339 | `lerna run test && mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1337 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1335 | `npm run lint && npm run mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1333 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1332 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1331 | `mocha test/*.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1326 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1324 | `mocha src/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1323 | `mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1319 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1309 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1306 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1302 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1294 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1418 | `istanbul cover _mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1418 | `mocha --recursive test/bin` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1410 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1409 | `mocha --check-leaks --reporter spec --bail test/` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1399 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1394 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1393 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1388 | `NODE_PATH=. mocha **/*.spec.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1384 | `./node_modules/.bin/mocha test` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1381 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1369 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1368 | `npm run lint && mocha --require @babel/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1347 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1347 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1344 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1343 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1342 | `mocha tests/` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1340 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1339 | `lerna run test && mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1337 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1335 | `npm run lint && npm run mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1333 | `mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1333 | `mocha --timeout 60000 test/` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1332 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1329 | `mocha --timeout 30000 --recursive ./tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1329 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1329 | `mocha spec/exec.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1328 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1327 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1324 | `mocha src/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1323 | `mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1322 | `mocha-phantomjs tests/index.html` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1321 | `mocha --timeout 20000` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1319 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1309 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1306 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1302 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1299 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1298 | `istanbul test _mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1297 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1294 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1288 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [variety/variety](https://github.com/variety/variety) | 1287 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1276 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [normalize/mz](https://github.com/normalize/mz) | 1260 | `mocha --reporter spec` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1250 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1250 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1244 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1239 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1230 | `node ./node_modules/mocha/bin/mocha tests` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1224 | `mocha test` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1212 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1209 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1209 | `mocha test` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1209 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1209 | `mocha test` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1207 | `mocha test/test.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1207 | `mocha --reporter spec --bail --check-leaks test/` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1206 | `mocha --recursive -r tests/setup tests` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1205 | `npm-run-all test:jest test:server:mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1204 | `mocha --reporter spec --bail --check-leaks test/` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1199 | `mocha --reporter spec test --recursive` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1193 | `xo && mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1192 | `mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1180 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1177 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1177 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1177 | `mocha $(find test -name '*.test.js') --exit` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1180 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1177 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1177 | `mocha $(find test -name '*.test.js') --exit` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1177 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1168 | `mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1168 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1168 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1161 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1159 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1157 | `istanbul cover _mocha test/*.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 750 | `mocha tests/*.mocha.js` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 749 | `npm run test-mocha && npm run test-karma` | 
| [electron/apps](https://github.com/electron/apps) | 748 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 742 | `mocha --compilers js:babel-core/register` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 739 | `mocha ./test/test.js --timeout 1000000` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 738 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 736 | `mocha $(find test -name '*.test.js')` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 735 | `mocha --reporter spec test/` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 721 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 710 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 706 | `mocha` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1082 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 1080 | `mocha test` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1071 | `mocha --async-only` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1062 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1061 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1050 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1039 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1038 | `mocha --recursive test/unit/` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1033 | `mocha --reporter spec --bail --check-leaks test/` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1029 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1028 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1027 | `mocha spec/*.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1024 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1024 | `mocha --reporter spec --timeout 3000` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1022 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1018 | `npm run lint && mocha -R spec` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [gulp-sourcemaps/gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) | 1016 | `mocha --async-only` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1015 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1010 | `mocha --compilers js:babel-register test/*.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 1009 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1006 | `mocha -R list` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1014 | `./node_modules/.bin/mocha -R spec` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1010 | `mocha --compilers js:babel-register test/*.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 1009 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 1007 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1006 | `mocha -R list` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1000 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 996 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 988 | `mocha "client.test" --compilers js:babel-register` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 967 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 965 | `./node_modules/.bin/mocha --reporter spec` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 964 | `nyc mocha specs` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 964 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 963 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 963 | `mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 961 | `./node_modules/.bin/mocha test/**/*` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 955 | `standard && standard ./bin/* && mocha` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 951 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 948 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 945 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 942 | `istanbul cover -- _mocha --reporter spec` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 928 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 926 | `mocha test/index.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 925 | `mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 919 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 918 | `mocha` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 914 | `mocha test` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 913 | `mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 917 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 914 | `mocha test` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 913 | `mocha` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 908 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 908 | `npm run lint && npm run mocha:no-functional` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 907 | `mocha -r should --exit test/*.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 901 | `node_modules/.bin/mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 900 | `npm run build && istanbul test _mocha test/test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 897 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 897 | `mocha --timeout 200000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 876 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 872 | `istanbul cover _mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 866 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 865 | `mocha --reporter spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 864 | `eslint test && mocha --compilers js:babel/register` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 862 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [developit/decko](https://github.com/developit/decko) | 861 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 861 | `mocha --reporter spec --bail --check-leaks test/` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 861 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 858 | `nyc mocha` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 858 | `mocha -r babel-register --check-leaks test/index.js` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 856 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 855 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 855 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 854 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 853 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 847 | `mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 846 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 844 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 841 | `mocha test` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 837 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 837 | `mocha` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 831 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 830 | `npm run mocha-test test/integration` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 829 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 826 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 824 | `_mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 822 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 821 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 819 | `mocha --colors --reporter spec test.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 832 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 832 | `mocha && ember test` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 830 | `npm run mocha-test test/integration` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 829 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 826 | `cake build && mocha ./test/mocha/*.coffee` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 826 | `mocha test/mocha.js test/crc/index.js` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 824 | `_mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 822 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 821 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 819 | `mocha --colors --reporter spec test.js` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 818 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 817 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 814 | `mocha` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 809 | `mocha index.test.js` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 808 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 808 | `mocha test` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 805 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 804 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 803 | `mocha` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 802 | `eslint . && mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 797 | `jenkins-mocha ./tests/*.js` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 796 | `nyc mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 796 | `npm run lint && npm run mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 792 | `mocha --recursive -s 15 test/` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 808 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 805 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 804 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 803 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 798 | `mocha --no-timeouts` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 797 | `jenkins-mocha ./tests/*.js` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 796 | `nyc mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 796 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 796 | `npm run lint && npm run mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [fivdi/onoff](https://github.com/fivdi/onoff) | 781 | `nyc mocha` | 
| [koajs/static](https://github.com/koajs/static) | 780 | `mocha --harmony --reporter spec --exit` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 777 | `babel-node node_modules/.bin/_mocha -- test` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 777 | `npm run-script jshint && npm run-script mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 776 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 775 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 773 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 773 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 716 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 716 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 715 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 710 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 709 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [Kagami/ffmpeg.js](https://github.com/Kagami/ffmpeg.js) | 705 | `mocha test/test.js` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 701 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 697 | `./node_modules/.bin/mocha` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 748 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 748 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 746 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 743 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 742 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 742 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 742 | `mocha --compilers js:babel-core/register` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 741 | `npm run bundle && mocha` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 741 | `mocha` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 740 | `mocha --reporter spec --bail --check-leaks test/` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 738 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 737 | `mocha` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 736 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 