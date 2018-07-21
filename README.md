# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:44 07/21/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 42828 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40994 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39304 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29919 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 24945 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24332 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23927 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22876 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19460 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18765 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16625 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16341 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14901 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14271 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13781 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13150 | `mocha --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12994 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12588 | `mocha 'test/**/*.spec.js'` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 12572 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12568 | `./node_modules/.bin/mocha test/` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12231 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12215 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11584 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11371 | `nyc grunt mocha-and-karma` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10918 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10897 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10267 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 9962 | `set NODE_ENV=test && mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9961 | `mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9951 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [tj/co](https://github.com/tj/co) | 9947 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9871 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9505 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9358 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9296 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 9137 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8980 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8917 | `grunt mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8840 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8563 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [amark/gun](https://github.com/amark/gun) | 8497 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8446 | `mocha test/test.js` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8429 | `mocha tests/*.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8408 | `mocha --check-leaks -R dot` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8366 | `mocha test/src` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8271 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8124 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8022 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7955 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7861 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7817 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7627 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7541 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7535 | `mocha --opts mocha.opts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7438 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7391 | `npm run build && istanbul cover _mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7390 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 7141 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7097 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7071 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6946 | `xo && mocha test/*.js --timeout 100000` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6896 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [almende/vis](https://github.com/almende/vis) | 6884 | `mocha --compilers js:babel-core/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6845 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6625 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6371 | `npm run jshint && mocha test/` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6191 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6187 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6170 | `mocha --exit --require babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6153 | `mocha; jshint *.js lib` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6053 | `mocha test/test.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6044 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5939 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5932 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5828 | `mocha tests/node.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5826 | `mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5738 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5689 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5652 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5520 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5506 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5408 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5377 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5371 | `mocha --timeout 10000 && npm run lint` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5230 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5173 | `mocha src/**/*Tests.js --harmony` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5167 | `standard && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5155 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5038 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4930 | `gulp lint && mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4871 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4861 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4839 | `mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4835 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4725 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4724 | `mocha test` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4714 | `gulp build; mocha;` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4696 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4686 | `mocha --reporter spec -t 8000` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4682 | `mocha test` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4568 | `mocha ./test/runner.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4561 | `./node_modules/.bin/mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4441 | `mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4428 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4418 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4380 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4336 | `nyc mocha --exit` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4331 | `mocha --recursive && make test` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4322 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4312 | `npm run lint && npm run mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4214 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4131 | `nyc mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4074 | `npm run lint && npm run mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4065 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4039 | `nyc mocha` | 
| [muicss/mui](https://github.com/muicss/mui) | 3998 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3990 | `mocha --require test/babel-hook test/*.js` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3968 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3964 | `node_modules/.bin/mocha test/tests.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3950 | `npm run lint ; mocha && mocha test/individual` | 
| [tj/ejs](https://github.com/tj/ejs) | 3950 | `mocha --require should --reporter spec` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3925 | `mocha --timeout=15000 tests/*.test.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3890 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3882 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3813 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [erming/shout](https://github.com/erming/shout) | 3805 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3756 | `mocha --check-leaks --reporter spec --bail` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3739 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3726 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3677 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3670 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3652 | `standard && mocha --timeout 60000 test/test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3644 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3484 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3456 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3448 | `node_modules/.bin/mocha test/lib/` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3434 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3433 | `mocha` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3423 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3361 | `NODE_ENV=test mocha test/**/*.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3259 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3193 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3275 | `NODE_ENV=test mocha --exit` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3259 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3193 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3188 | `nyc mocha && tsc` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3175 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3173 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3146 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3135 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3134 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3122 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3114 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3109 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3061 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3043 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3022 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3013 | `mocha test/*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3000 | `mocha test/index.js && npm run demo` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2997 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2995 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2983 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2979 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2974 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2943 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2912 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2885 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2879 | `mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2872 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2870 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2867 | `mocha -R spec --recursive src/test` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2864 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2855 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2835 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2828 | `mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2826 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2821 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2819 | `istanbul cover _mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2803 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2801 | `mocha --opts mocha.opts` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2798 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [github-tools/github](https://github.com/github-tools/github) | 2791 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2772 | `npm run mocha && npm run lint` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2771 | `mocha --require should --reporter spec` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2755 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2726 | `mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2724 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2721 | `mocha --require babel-register --recursive spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2720 | `mocha test-node` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2711 | `mocha -R landing test/index` | 
| [css/csso](https://github.com/css/csso) | 2700 | `mocha --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2696 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2693 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2690 | `node_modules/.bin/mocha --reporter spec` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2638 | `mocha --timeout 100000` | 
| [mde/ejs](https://github.com/mde/ejs) | 2634 | `mocha --require should --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2631 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2621 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2608 | `mocha-phantomjs ./test/index.html` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2606 | `mocha --recursive --watch` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2606 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2590 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2589 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [json5/json5](https://github.com/json5/json5) | 2581 | `nyc --reporter=html --reporter=text mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2568 | `nyc mocha --timeout=10000` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2558 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2557 | `npm run build && cd test && mocha . --reporter dot` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2556 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2546 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2494 | `nyc mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2477 | `mocha "test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2476 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2466 | `mocha --reporter=spec test/*-test.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2463 | `eslint . && mocha -t 5000` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2455 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2230 | `mocha test test/unit/**/*_test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2230 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2227 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2226 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [gajus/swing](https://github.com/gajus/swing) | 2214 | `mocha --compilers js:babel-register` | 
| [noble/noble](https://github.com/noble/noble) | 2163 | `mocha -R spec test/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2131 | `cross-env BABEL_ENV=test mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2105 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2099 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2273 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2272 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2269 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2264 | `mocha test && npm run lint` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2230 | `mocha test test/unit/**/*_test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2230 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2227 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2226 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2220 | `mocha test/index.js --reporter dot` | 
| [gajus/swing](https://github.com/gajus/swing) | 2214 | `mocha --compilers js:babel-register` | 
| [noble/noble](https://github.com/noble/noble) | 2163 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2142 | `mocha --compilers js:babel-register` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2131 | `cross-env BABEL_ENV=test mocha` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2130 | `mocha test/ --no-timeouts` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2105 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2099 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2093 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2090 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2076 | `standard && mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2069 | `mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2052 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2029 | `mocha test/runner.js --reporter spec` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2013 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2011 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [slate/slate](https://github.com/slate/slate) | 2006 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1994 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1986 | `nyc npm run _mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1970 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1965 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1958 | `mocha --require=test/test_helper.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1952 | `mocha --compilers js:babel-core/register __tests__` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1934 | `mocha --reporter spec --timeout 5000` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1930 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1926 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1925 | `mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1925 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1921 | `mocha && eslint *.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1905 | `./node_modules/.bin/mocha && npm run jshint` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1902 | `mocha --require ./test/common --growl test/expect.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1898 | `npm run lint && mocha -R dot && npm run cover` | 
| [then/promise](https://github.com/then/promise) | 1896 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1889 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1875 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1873 | `mocha tests.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 1867 | `npm run lint && npm run mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 1862 | `mocha test/*.test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1875 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1873 | `mocha tests.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 1867 | `npm run lint && npm run mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 1862 | `mocha test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1853 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1848 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1832 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1822 | `mocha --reporter spec && npm run test-typescript` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1810 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1803 | `mocha --timeout 5000` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1802 | `npm run mocha && npm run karma` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1794 | `mocha -R spec spec spec/reporters` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1791 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1790 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1787 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1776 | `mocha test` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1775 | `mocha && npm run lint` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1774 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1769 | `mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1769 | `mocha --reporter spec test/*.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1764 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1758 | `mocha tests --compilers js:babel-core/register` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1757 | `mocha --reporter spec --grep .` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1750 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1745 | `npm run lint && npm run mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1741 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1730 | `mocha test/**/*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1725 | `mocha --compilers js:babel-register` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1725 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1723 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1723 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1722 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1717 | `mocha test -u bdd -R spec` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1706 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1700 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1695 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1684 | `npm run lint && mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1676 | `mocha test --timeout 600000` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1675 | `mocha ./test/basic.js -t 5000` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1672 | `xo && mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1668 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1665 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1663 | `mocha test/*.js` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1624 | `mocha tests/test.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1623 | `mocha && size-limit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1602 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1602 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1596 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1594 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1591 | `mocha compiled_tests/` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1579 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1578 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1564 | `./node_modules/mocha/bin/mocha -R spec` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1579 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1578 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1564 | `./node_modules/mocha/bin/mocha -R spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1548 | `./node_modules/.bin/mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1547 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1544 | `mocha test/setup.js test/spec/*.js` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1544 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1542 | `eslint --cache . && tsc && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1539 | `mocha tests.js` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1539 | `npm run test:lint && npm run test:mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1537 | `mocha --reporter spec` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1532 | `standard "./src/*.js" && mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1511 | `mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1510 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1501 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1501 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1500 | `mocha test` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1499 | `mocha --check-leaks --reporter spec --bail` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1494 | `mocha -u tdd` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1493 | `mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1490 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1488 | `nyc mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1487 | `node_modules/.bin/mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1481 | `mocha -R spec` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1480 | `nyc npm run mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1468 | `mocha test/**/*.spec.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1465 | `mocha --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1480 | `nyc npm run mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1468 | `mocha test/**/*.spec.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1465 | `mocha --recursive` | 
| [samccone/drool](https://github.com/samccone/drool) | 1453 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1447 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1438 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1410 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1410 | `mocha --timeout 10000 ./tests/lib.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1408 | `nyc mocha --timeout=20000 test.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1394 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1391 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1389 | `mocha -R spec test/*.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1382 | `istanbul cover _mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 1378 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1374 | `./node_modules/mocha/bin/mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1374 | `./node_modules/mocha/bin/mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1358 | `cross-env NODE_ENV=test nyc mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1358 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1357 | `npm run build && mocha -r should` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1356 | `mocha --check-leaks --require @babel/register` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1354 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [electron/devtron](https://github.com/electron/devtron) | 1339 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1335 | `mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1335 | `mocha test/unit` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1321 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1320 | `mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1319 | `mocha --opts test/opts/mocha.opts` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1317 | `istanbul cover _mocha test -- --timeout 20000` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1316 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1315 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1315 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1314 | `mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1311 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1310 | `./node_modules/.bin/mocha test` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1308 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1306 | `mocha-phantomjs tests/index.html` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1304 | `mocha --recursive` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1303 | `eslint src && mocha && karma start --single-run` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1299 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1298 | `TEST=all mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1292 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1292 | `mocha spec/exec.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1283 | `mocha tests/test-*` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1280 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1279 | `mocha --reporter dot` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1246 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1246 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1243 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1238 | `mocha tests` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1238 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1236 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1230 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1224 | `NODE_ENV=test mocha tests/*.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1213 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1210 | `mocha src/test.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1204 | `mocha ./test/test*.js --reporter spec` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1203 | `mocha --check-leaks --reporter spec --bail test/` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1201 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1199 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1195 | `node ./node_modules/mocha/bin/mocha tests` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1195 | `mocha test` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1207 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1206 | `mocha -R spec ./test/unit/**` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1206 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1204 | `mocha ./test/test*.js --reporter spec` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1203 | `mocha --check-leaks --reporter spec --bail test/` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1202 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1201 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1199 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1195 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1195 | `mocha test` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1195 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [normalize/mz](https://github.com/normalize/mz) | 1190 | `mocha --reporter spec` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1189 | `mocha --recursive test/bin` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1188 | `npm run lint && npm run mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1186 | `istanbul test _mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1186 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1174 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1172 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1170 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1168 | `mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1190 | `npm run lint && npm run mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1190 | `mocha --reporter spec` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1189 | `mocha --recursive test/bin` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1188 | `npm run lint && npm run mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1186 | `istanbul test _mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1186 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1180 | `npm run prepublishOnly && mocha test/test.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1174 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1172 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1170 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1170 | `NODE_PATH=. mocha **/*.spec.js` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1168 | `mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1164 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1164 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1163 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1162 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1160 | `mocha --recursive test` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1096 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1091 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1089 | `mocha --check-leaks -t 20000` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1088 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1086 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [router5/router5](https://github.com/router5/router5) | 1084 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1082 | `mocha` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1081 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1077 | `npm run lint && mocha --require @babel/register` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1077 | `webpack && npm run lint && npm run mocha` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1074 | `standard && mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1068 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [electron/asar](https://github.com/electron/asar) | 1058 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1117 | `mocha $(find test -name '*.test.js')` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1115 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1111 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1108 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1107 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1104 | `istanbul cover _mocha test/*.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1104 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1103 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1099 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1099 | `mocha test/*` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1096 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1091 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1089 | `mocha --check-leaks -t 20000` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1088 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1086 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [router5/router5](https://github.com/router5/router5) | 1084 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1082 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1058 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1057 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1050 | `mocha --recursive --bail --reporter spec test` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1048 | `mocha test/tests.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1047 | `webpack && mocha test/unit` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1043 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1041 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1040 | `mocha` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1037 | `mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1037 | `mocha --reporter spec --timeout 3000` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1033 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1029 | `mocha --reporter spec --bail --check-leaks test/` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1027 | `mocha --timeout 20000` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1027 | `standard && mocha -b` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1022 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1048 | `mocha test/tests.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1047 | `webpack && mocha test/unit` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1043 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1041 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1040 | `mocha` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1037 | `mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1037 | `mocha --reporter spec --timeout 3000` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1033 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1029 | `mocha --reporter spec --bail --check-leaks test/` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1027 | `mocha --timeout 20000` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1027 | `standard && mocha -b` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1022 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1020 | `mocha` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1019 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1017 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [electron/spectron](https://github.com/electron/spectron) | 1013 | `mocha && standard` | 
| [tomas/needle](https://github.com/tomas/needle) | 1012 | `mocha test` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1012 | `mocha --check-leaks -R dot` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1011 | `eslint src test && mocha --compilers babel-register` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 967 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 966 | `npm run lint && npm run flow && NODE_ENV=test nyc mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 965 | `mocha --reporter spec` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 963 | `npm run convertto:es5 && npm run mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 957 | `npm-run-all test:jest test:server:mocha` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 949 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 941 | `mocha "client.test" --compilers js:babel-register` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 940 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit/**/*-test.js` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 938 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 935 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 935 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 934 | `mocha -R spec` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 933 | `mocha test --compilers js:babel-core/register` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 932 | `mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 928 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 928 | `mocha --compilers js:babel-register test/*.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 922 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 918 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 918 | `npm run lint && mocha -R spec` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 916 | `mocha ./test/index.js` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 913 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 912 | `mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 908 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 907 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 906 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 903 | `mocha tests` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 901 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 892 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 892 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 890 | `mocha spec/*.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 885 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 883 | `mocha -t 600000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 880 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 879 | `node_modules/.bin/mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 880 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 879 | `node_modules/.bin/mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 877 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 873 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 868 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 868 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 865 | `nyc mocha specs` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 864 | `npm run lint && npm run mocha:no-functional` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 864 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 863 | `mocha --timeout 200000` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 862 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 862 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 859 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 855 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 855 | `eslint test && mocha --compilers js:babel/register` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 854 | `mocha -t 5000` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 853 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 853 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 849 | `./node_modules/.bin/mocha -R spec` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 849 | `mocha test --compilers js:babel-register` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 849 | `istanbul cover -- _mocha --reporter spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 848 | `./node_modules/.bin/mocha --reporter spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 847 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 847 | `standard && standard ./bin/* && mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 844 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 843 | `mocha test` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 838 | `mocha --reporter spec` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 825 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 825 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 824 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 823 | `mocha && ember test` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 821 | `mocha --reporter spec --bail --check-leaks test/` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 819 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 817 | `nyc --check-coverage mocha test/*.test.js` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 815 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 815 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 814 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 812 | `mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 811 | `mocha --recursive ./test/*_spec.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 808 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 819 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 817 | `nyc --check-coverage mocha test/*.test.js` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 815 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 815 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 814 | `npm run lint && mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 814 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 812 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 812 | `mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 811 | `mocha --recursive ./test/*_spec.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 808 | `mocha test/index.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 808 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 808 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 807 | `mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 807 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 806 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 805 | `mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 805 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 804 | `mocha --require babel-register` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 788 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 787 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 785 | `mocha --colors --reporter spec test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 785 | `mocha --harmony --full-trace --check-leaks` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 783 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 781 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 780 | `npm run build && istanbul test _mocha test/test.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 778 | `mocha` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 777 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 777 | `npm run mocha-test test/integration` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 777 | `xo && mocha -R spec` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 776 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 774 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 772 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 772 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 758 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 755 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 753 | `mocha --recursive -s 15 test/` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 753 | `mocha test` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 752 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 750 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 743 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [developit/decko](https://github.com/developit/decko) | 767 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 767 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 766 | `mocha --ui tdd --require ./test/__setup` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 765 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 764 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 761 | `mocha -R spec src/**/*_test.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 758 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 755 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 753 | `mocha --recursive -s 15 test/` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 753 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 753 | `mocha test` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 752 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 752 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 743 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 742 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 738 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 736 | `mocha -r should --reporter spec test/*.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 736 | `mocha test` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 736 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 736 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 735 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 732 | `npm run lint && npm run mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 732 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 730 | `mocha tests/*.mocha.js` | 