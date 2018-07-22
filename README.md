# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:43 07/22/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40996 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 39320 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29925 | `mocha --async-only` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 24971 | `cross-env NODE_ENV=test mocha` | 
| [caolan/async](https://github.com/caolan/async) | 24335 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23933 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22882 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19464 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18767 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16630 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16350 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16630 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 16350 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14909 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14272 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13786 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 13151 | `mocha --reporter spec` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13000 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12590 | `mocha 'test/**/*.spec.js'` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 12582 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 12576 | `./node_modules/.bin/mocha test/` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12232 | `mocha --reporter spec test/*-test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12217 | `mocha` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11587 | `istanbul cover _mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11373 | `nyc grunt mocha-and-karma` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10923 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10903 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10271 | `mocha test/index.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9967 | `mocha` | 
| [svg/svgo](https://github.com/svg/svgo) | 9965 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9954 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [tj/co](https://github.com/tj/co) | 9946 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9873 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9505 | `mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 9369 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9297 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 9146 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8983 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8918 | `grunt mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8848 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8567 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [amark/gun](https://github.com/amark/gun) | 8497 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8447 | `mocha test/test.js` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8434 | `mocha tests/*.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8410 | `mocha --check-leaks -R dot` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8368 | `mocha test/src` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8271 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8125 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8023 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7967 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7866 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7818 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7632 | `./node_modules/.bin/mocha test` | 
| [dthree/cash](https://github.com/dthree/cash) | 7542 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7541 | `mocha --opts mocha.opts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7438 | `mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7394 | `npm run pre_test && nyc mocha --exit --check-leaks -t 10000 -R spec test/index.js && npm run tape` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7391 | `npm run build && istanbul cover _mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7141 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7098 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7073 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6948 | `xo && mocha test/*.js --timeout 100000` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6901 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [almende/vis](https://github.com/almende/vis) | 6884 | `mocha --compilers js:babel-core/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6846 | `mocha $HARMONY_OPTS` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6628 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6372 | `npm run jshint && mocha test/` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6191 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6187 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 6172 | `mocha --exit --require babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 6157 | `mocha; jshint *.js lib` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6056 | `mocha test/test.js` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6042 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5940 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5933 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5832 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5830 | `mocha tests/node.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5739 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5689 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5653 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5524 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5506 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5408 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5382 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5372 | `mocha --timeout 10000 && npm run lint` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5232 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5172 | `mocha src/**/*Tests.js --harmony` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5171 | `standard && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5155 | `mocha --color` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5040 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4931 | `gulp lint && mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4874 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4865 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4842 | `mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4835 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4080 | `npm run lint && npm run mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4071 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4040 | `nyc mocha` | 
| [muicss/mui](https://github.com/muicss/mui) | 4000 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3990 | `mocha --require test/babel-hook test/*.js` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3969 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3965 | `node_modules/.bin/mocha test/tests.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3951 | `npm run lint ; mocha && mocha test/individual` | 
| [tj/ejs](https://github.com/tj/ejs) | 3951 | `mocha --require should --reporter spec` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3927 | `mocha --timeout=15000 tests/*.test.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3890 | `export TESTING=true; mocha --reporter list` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4215 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4131 | `nyc mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4080 | `npm run lint && npm run mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4071 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4040 | `nyc mocha` | 
| [muicss/mui](https://github.com/muicss/mui) | 4000 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3990 | `mocha --require test/babel-hook test/*.js` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3969 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3965 | `node_modules/.bin/mocha test/tests.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3951 | `npm run lint ; mocha && mocha test/individual` | 
| [tj/ejs](https://github.com/tj/ejs) | 3951 | `mocha --require should --reporter spec` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3927 | `mocha --timeout=15000 tests/*.test.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3890 | `export TESTING=true; mocha --reporter list` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3882 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3814 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [erming/shout](https://github.com/erming/shout) | 3805 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3758 | `mocha --check-leaks --reporter spec --bail` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3741 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3728 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3676 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3672 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3652 | `standard && mocha --timeout 60000 test/test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3647 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [primus/primus](https://github.com/primus/primus) | 3626 | `npm run build && mocha test/*.test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3619 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3601 | `nyc mocha "test/**/*.test.js"` | 
| [teambit/bit](https://github.com/teambit/bit) | 3587 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3573 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3563 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [expressjs/session](https://github.com/expressjs/session) | 3560 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3533 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3533 | `mocha --reporter spec --timeout 3000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3527 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3501 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3486 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3455 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3448 | `node_modules/.bin/mocha test/lib/` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3435 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3433 | `mocha` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3424 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3369 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3260 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3194 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3192 | `nyc mocha && tsc` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3177 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3176 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3147 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3137 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3134 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3122 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3118 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3112 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3061 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3045 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3023 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3013 | `mocha test/*.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2913 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2891 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2880 | `mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2872 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2871 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2855 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2839 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2828 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2824 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2819 | `istanbul cover _mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2804 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2801 | `mocha --opts mocha.opts` | 
| [github-tools/github](https://github.com/github-tools/github) | 2792 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2771 | `mocha --require should --reporter spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2726 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2722 | `mocha --require babel-register --recursive spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2721 | `mocha test-node` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2711 | `mocha -R landing test/index` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2722 | `mocha --require babel-register --recursive spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2721 | `mocha test-node` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2711 | `mocha -R landing test/index` | 
| [css/csso](https://github.com/css/csso) | 2700 | `mocha --reporter dot` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2696 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2693 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2690 | `node_modules/.bin/mocha --reporter spec` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2640 | `mocha --timeout 100000` | 
| [mde/ejs](https://github.com/mde/ejs) | 2634 | `mocha --require should --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2633 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2621 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2609 | `mocha --recursive --watch` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2608 | `mocha-phantomjs ./test/index.html` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2591 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [json5/json5](https://github.com/json5/json5) | 2583 | `nyc --reporter=html --reporter=text mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2569 | `nyc mocha --timeout=10000` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2558 | `npm run build && cd test && mocha . --reporter dot` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2558 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2557 | `mocha test.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2640 | `mocha --timeout 100000` | 
| [mde/ejs](https://github.com/mde/ejs) | 2634 | `mocha --require should --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2633 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2621 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2609 | `mocha --recursive --watch` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2608 | `mocha-phantomjs ./test/index.html` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2605 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2591 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [json5/json5](https://github.com/json5/json5) | 2583 | `nyc --reporter=html --reporter=text mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2558 | `npm run build && cd test && mocha . --reporter dot` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2558 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2557 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2547 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2530 | `export TESTING=true; mocha --reporter list` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2591 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2591 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [json5/json5](https://github.com/json5/json5) | 2583 | `nyc --reporter=html --reporter=text mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2569 | `nyc mocha --timeout=10000` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2558 | `npm run build && cd test && mocha . --reporter dot` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2558 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2557 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2547 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2530 | `export TESTING=true; mocha --reporter list` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2495 | `nyc mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2477 | `mocha "test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2477 | `mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2466 | `eslint . && mocha -t 5000` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2466 | `mocha --reporter=spec test/*-test.js` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2456 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2440 | `mocha test` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2435 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2422 | `mocha test/src/**/*.unit.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2414 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2410 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2404 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2403 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2384 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2373 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2348 | `nyc --reporter=html --reporter=text mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2345 | `grunt jshint && mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2343 | `mocha --no-colors --reporter spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2328 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2302 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2295 | `mocha -R spec` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2132 | `mocha test/ --no-timeouts` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2105 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2099 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2093 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2090 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2076 | `standard && mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2069 | `mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2030 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2011 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [slate/slate](https://github.com/slate/slate) | 2006 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2105 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2099 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2093 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2090 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2076 | `standard && mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2069 | `mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2053 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2030 | `mocha test/runner.js --reporter spec` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2014 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2011 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [slate/slate](https://github.com/slate/slate) | 2006 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1995 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1971 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1965 | `mocha -c test/index.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1953 | `mocha --compilers js:babel-core/register __tests__` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1934 | `mocha --reporter spec --timeout 5000` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1932 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1926 | `mocha --bail --reporter spec --check-leaks test/` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1925 | `mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1925 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1922 | `mocha && eslint *.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1906 | `./node_modules/.bin/mocha && npm run jshint` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1902 | `mocha --require ./test/common --growl test/expect.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1900 | `npm run lint && mocha -R dot && npm run cover` | 
| [then/promise](https://github.com/then/promise) | 1896 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [share/sharedb](https://github.com/share/sharedb) | 1906 | `./node_modules/.bin/mocha && npm run jshint` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1902 | `mocha --require ./test/common --growl test/expect.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1900 | `npm run lint && mocha -R dot && npm run cover` | 
| [then/promise](https://github.com/then/promise) | 1896 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1889 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1877 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1873 | `mocha tests.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 1867 | `npm run lint && npm run mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 1862 | `mocha test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1854 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1851 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1833 | `mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1810 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1809 | `mocha -R spec spec spec/reporters` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1804 | `npm run mocha && npm run karma` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1803 | `mocha --timeout 5000` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1790 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1790 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1787 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1776 | `mocha test` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1776 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1775 | `mocha && npm run lint` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1770 | `mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1763 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1759 | `mocha tests --compilers js:babel-core/register` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1757 | `mocha --reporter spec --grep .` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1745 | `npm run lint && npm run mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1742 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1672 | `xo && mocha` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1668 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1664 | `mocha test/*.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1645 | `mocha` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1631 | `mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1629 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1624 | `mocha tests/test.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1623 | `mocha && size-limit` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1602 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1597 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1593 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1591 | `mocha compiled_tests/` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1664 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1664 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1650 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1649 | `npm run lint && npm run mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1646 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1645 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1635 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1632 | `mocha spec` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 1631 | `mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1629 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1624 | `mocha tests/test.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1623 | `mocha && size-limit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1602 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1602 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1502 | `mocha test` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1501 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1499 | `mocha --check-leaks --reporter spec --bail` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1493 | `mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1489 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1488 | `nyc mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1487 | `node_modules/.bin/mocha --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1481 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1468 | `mocha test/**/*.spec.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1465 | `mocha --recursive` | 
| [samccone/drool](https://github.com/samccone/drool) | 1453 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1447 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1548 | `./node_modules/.bin/mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1547 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1545 | `mocha test/setup.js test/spec/*.js` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1545 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1543 | `eslint --cache . && tsc && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1540 | `mocha tests.js` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1540 | `npm run test:lint && npm run test:mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1537 | `mocha --reporter spec` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1533 | `standard "./src/*.js" && mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1529 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1518 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1514 | `mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1510 | `mocha test.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1502 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1502 | `mocha test` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1501 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1499 | `mocha --check-leaks --reporter spec --bail` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1494 | `mocha -u tdd` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1493 | `mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1489 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1488 | `nyc mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1487 | `node_modules/.bin/mocha --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1483 | `nyc npm run mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1481 | `mocha -R spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1468 | `mocha test/**/*.spec.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1465 | `mocha --recursive` | 
| [samccone/drool](https://github.com/samccone/drool) | 1453 | `mocha test/tests.js --timeout=10000` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1447 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1438 | `mocha test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1411 | `nyc mocha --timeout=20000 test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1410 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1410 | `mocha --timeout 10000 ./tests/lib.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1321 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1321 | `mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1319 | `mocha --opts test/opts/mocha.opts` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1318 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1318 | `istanbul cover _mocha test -- --timeout 20000` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1316 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1315 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1314 | `mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1312 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1310 | `./node_modules/.bin/mocha test` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1308 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1306 | `mocha-phantomjs tests/index.html` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1305 | `eslint src && mocha && karma start --single-run` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1304 | `mocha --recursive` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1299 | `TEST=all mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1293 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1293 | `mocha spec/exec.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1284 | `mocha tests/test-*` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1281 | `standard && istanbul cover _mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1277 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1266 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1263 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1262 | `mocha --timeout 60000 test/` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1256 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1254 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1247 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1246 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1243 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1242 | `mocha test/*.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1241 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1238 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1238 | `mocha tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1236 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1231 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1224 | `NODE_ENV=test mocha tests/*.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1220 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1214 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1211 | `mocha src/test.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1208 | `mocha -R spec ./test/unit/**` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1207 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1206 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1205 | `mocha ./test/test*.js --reporter spec` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1204 | `mocha --check-leaks --reporter spec --bail test/` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1202 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1201 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1199 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1196 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1196 | `node ./node_modules/mocha/bin/mocha tests` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1196 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1195 | `mocha test` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1190 | `istanbul test _mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1190 | `npm run lint && npm run mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1189 | `NODE_PATH=. mocha **/*.spec.js` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1189 | `mocha --recursive test/bin` | 
| [normalize/mz](https://github.com/normalize/mz) | 1189 | `mocha --reporter spec` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1188 | `npm run lint && npm run mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1186 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1180 | `npm run prepublishOnly && mocha test/test.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1174 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1172 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1172 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1169 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1163 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1162 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1161 | `mocha --recursive test` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1152 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1152 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1149 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1144 | `mocha` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1142 | `mocha --compilers js:babel-core/register` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1116 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1112 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1109 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1108 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1104 | `istanbul cover _mocha test/*.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1104 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1099 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1099 | `mocha test/*` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1096 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1091 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1089 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1087 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [router5/router5](https://github.com/router5/router5) | 1085 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1082 | `mocha` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1081 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1079 | `npm run lint && mocha --require @babel/register` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1079 | `mocha --compilers js:babel-register` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1077 | `webpack && npm run lint && npm run mocha` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1075 | `standard && mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1112 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1109 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1108 | `xo && mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1104 | `istanbul cover _mocha test/*.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1104 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1103 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1099 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1099 | `mocha test/*` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1096 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1091 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1089 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1088 | `mocha --check-leaks -t 20000` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1087 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [router5/router5](https://github.com/router5/router5) | 1085 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1082 | `mocha` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 1081 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1079 | `npm run lint && mocha --require @babel/register` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1079 | `mocha --compilers js:babel-register` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1077 | `webpack && npm run lint && npm run mocha` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1075 | `standard && mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1072 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1068 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1062 | `npm run mocha:istanbul` | 
| [electron/asar](https://github.com/electron/asar) | 1060 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1057 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1050 | `mocha --recursive --bail --reporter spec test` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1049 | `mocha test/tests.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1047 | `webpack && mocha test/unit` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1044 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1042 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1040 | `mocha` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1037 | `mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1037 | `mocha --reporter spec --timeout 3000` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1033 | `nyc mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1029 | `mocha --reporter spec --bail --check-leaks test/` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1027 | `mocha --timeout 20000` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1027 | `standard && mocha -b` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1022 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1021 | `mocha` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1020 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1017 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [electron/spectron](https://github.com/electron/spectron) | 1015 | `mocha && standard` | 
| [tomas/needle](https://github.com/tomas/needle) | 1012 | `mocha test` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1012 | `mocha --check-leaks -R dot` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1011 | `eslint src test && mocha --compilers babel-register` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1009 | `mocha $(find test -name '*.test.js')` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 967 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 966 | `npm run lint && npm run flow && NODE_ENV=test nyc mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 966 | `mocha --reporter spec` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 957 | `npm-run-all test:jest test:server:mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 941 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit/**/*-test.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 941 | `mocha "client.test" --compilers js:babel-register` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 940 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 935 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 934 | `mocha -R spec` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 974 | `mocha -R list` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 974 | `mocha --timeout 30000 --recursive ./tests` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 972 | `npm run rollup-cjs && mocha test/test.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 967 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 966 | `npm run lint && npm run flow && NODE_ENV=test nyc mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 966 | `mocha --reporter spec` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 965 | `npm run convertto:es5 && npm run mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 957 | `npm-run-all test:jest test:server:mocha` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 949 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 946 | `mocha --timeout 5000` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 941 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit/**/*-test.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 941 | `mocha "client.test" --compilers js:babel-register` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 940 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 935 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 934 | `mocha -R spec` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 933 | `mocha test --compilers js:babel-core/register` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 932 | `mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 929 | `mocha --compilers js:babel-register test/*.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 928 | `mocha --reporter spec --bail --check-leaks test/` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 922 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 920 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 918 | `npm run lint && mocha -R spec` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 916 | `mocha ./test/index.js` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 914 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 914 | `mocha` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 908 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 907 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 906 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 903 | `mocha tests` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 903 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 893 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 893 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 892 | `mocha spec/*.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 885 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 883 | `mocha -t 600000` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 880 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 879 | `node_modules/.bin/mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 878 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 873 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 869 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 868 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 865 | `nyc mocha specs` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 864 | `npm run lint && npm run mocha:no-functional` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 864 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 863 | `mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 863 | `mocha --timeout 200000` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 862 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 862 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 855 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 855 | `eslint test && mocha --compilers js:babel/register` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 854 | `mocha -t 5000` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 853 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 849 | `./node_modules/.bin/mocha -R spec` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 849 | `mocha test --compilers js:babel-register` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 849 | `./node_modules/.bin/mocha --reporter spec` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 848 | `istanbul cover -- _mocha --reporter spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 847 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 847 | `standard && standard ./bin/* && mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 846 | `mocha test` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 845 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 838 | `mocha --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 836 | `istanbul cover _mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 835 | `mocha --check-leaks -t 20000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 834 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 833 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 825 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 825 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 824 | `mocha --reporter list` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 824 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 823 | `mocha && ember test` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 821 | `nyc mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 819 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 818 | `nyc --check-coverage mocha test/*.test.js` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 815 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 815 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 814 | `npm run lint && mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 814 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 812 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 812 | `mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 811 | `mocha --recursive ./test/*_spec.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 796 | `mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 795 | `mocha -u tdd` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 794 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [edsu/anon](https://github.com/edsu/anon) | 785 | `mocha --colors --reporter spec test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 785 | `mocha --harmony --full-trace --check-leaks` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 783 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 780 | `npm run build && istanbul test _mocha test/test.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 779 | `mocha` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 778 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 778 | `npm run mocha-test test/integration` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 777 | `xo && mocha -R spec` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 794 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 789 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 788 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 785 | `mocha --colors --reporter spec test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 785 | `mocha --harmony --full-trace --check-leaks` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 783 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 781 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 780 | `npm run build && istanbul test _mocha test/test.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 779 | `mocha` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 778 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 778 | `npm run mocha-test test/integration` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 777 | `xo && mocha -R spec` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 764 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 761 | `mocha -R spec src/**/*_test.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 758 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 753 | `mocha --recursive -s 15 test/` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 753 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 752 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 752 | `mocha --no-timeouts` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 750 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 758 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 756 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 753 | `mocha --recursive -s 15 test/` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 753 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 753 | `mocha test` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 752 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 752 | `mocha --no-timeouts` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 750 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 743 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 742 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 732 | `npm run lint && npm run mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 732 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 731 | `mocha tests/*.mocha.js` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 730 | `mocha test.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 726 | `mocha` | 
| [scality/S3](https://github.com/scality/S3) | 725 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 723 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 723 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 722 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 722 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 722 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 721 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 720 | `babel-node node_modules/.bin/_mocha -- test` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 719 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 