# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:22 12/21/17 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39358 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 38009 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 35701 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 35125 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28228 | `mocha --reporter spec` | 
| [caolan/async](https://github.com/caolan/async) | 22951 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 21328 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 19740 | `mocha test/index.js` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17024 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [developit/preact](https://github.com/developit/preact) | 16810 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15189 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14260 | `mocha test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13600 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12383 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12278 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 12053 | `cross-env NODE_ENV=test mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11911 | `mocha` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 11693 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11616 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11516 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11309 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 10492 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10405 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10292 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 9830 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9557 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9241 | `mocha --reporter spec` | 
| [tj/co](https://github.com/tj/co) | 9111 | `mocha --harmony` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9050 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 8926 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tmpvar/jsdom](https://github.com/tmpvar/jsdom) | 8907 | `mocha test/index.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 8847 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8707 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [svg/svgo](https://github.com/svg/svgo) | 8674 | `set NODE_ENV=test && mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8378 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8137 | `mocha test/*-test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8103 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8032 | `grunt clean:test && mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 7991 | `mocha test/test.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 7905 | `mocha` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7640 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7585 | `./node_modules/.bin/mocha test/src` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7532 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7423 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7408 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7328 | `mocha --compilers js:babel-register test/test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7276 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7187 | `npm run eslint && npm run mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7057 | `npm run build && istanbul cover _mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 7054 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 6948 | `./node_modules/.bin/mocha test` | 
| [amark/gun](https://github.com/amark/gun) | 6944 | `mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 6887 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 6872 | `mocha tests/*.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6449 | `mocha $HARMONY_OPTS` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6408 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6393 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6315 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6208 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6192 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6094 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [almende/vis](https://github.com/almende/vis) | 6025 | `mocha --compilers js:babel-core/register` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 5963 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5933 | `mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 5840 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 5830 | `nyc mocha test/** -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 5689 | `mocha --opts mocha.opts` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5670 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5668 | `npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 5568 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5567 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5461 | `npm run jshint && mocha test/` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5388 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5385 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5373 | `mocha tests/node.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5270 | `mocha && eslint lib/**` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5258 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5216 | `mocha test --recursive` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5164 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5161 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5115 | `mocha src/**/*Tests.js --harmony` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5083 | `mocha test/test.js` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 4972 | `mocha --timeout 10000 && npm run lint` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4810 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4777 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4727 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4680 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 4654 | `mocha --compilers js:babel-core/register` | 
| [santinic/how2](https://github.com/santinic/how2) | 4608 | `mocha test` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4567 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4565 | `mocha --reporter spec -t 8000` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4561 | `mocha -R spec 'tests/app'` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4513 | `mocha ./test/runner.js` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4365 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4349 | `gulp build; mocha;` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4348 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4321 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4299 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4258 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4242 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4226 | `mocha -R spec ./test --recursive` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4226 | `./node_modules/.bin/mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4177 | `standard && mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4105 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4086 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4043 | `mocha` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 3986 | `mocha && ./bin/shipit staging test` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 3979 | `mocha test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3939 | `nyc mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 3898 | `mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3891 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 3846 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3825 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3812 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [muicss/mui](https://github.com/muicss/mui) | 3745 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3701 | `mocha --require should --reporter spec` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3663 | `mocha --recursive && make test` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3633 | `npm run jshint && npm run mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3610 | `NODE_ENV=test mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3547 | `mocha --require test/babel-hook test/*.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3546 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3545 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3534 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3534 | `standard && mocha --timeout 60000 test/test.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3512 | `npm run lint && npm run mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3500 | `mocha tests/javascript` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3435 | `npm run lint ; mocha && mocha test/individual` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 3425 | `npm run build-cli && mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3414 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3413 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [primus/primus](https://github.com/primus/primus) | 3394 | `npm run build && mocha test/*.test.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3380 | `nyc mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3379 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3376 | `mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3336 | `node_modules/.bin/mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3300 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3279 | `npm run lint && mocha && EIO_WS_ENGINE=ws mocha` | 
| [easy-mock/easy-mock](https://github.com/easy-mock/easy-mock) | 3127 | `cross-env NODE_ENV=test istanbul cover _mocha test/*` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3083 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3077 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3058 | `mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3049 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3042 | `./node_modules/.bin/mocha test/test.*.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3038 | `mocha --check-leaks --reporter spec --bail` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3037 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3008 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 2993 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 2968 | `node_modules/.bin/mocha test/tests.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2945 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 2939 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 2916 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [expressjs/session](https://github.com/expressjs/session) | 2893 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2892 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 2883 | `nyc mocha "test/**/*.test.js"` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2877 | `mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 2844 | `npm run lint && npm run mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 2817 | `mocha; jshint *.js lib` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2817 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2811 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2778 | `mocha test/*.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2752 | `mocha --require should --reporter spec` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2749 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2735 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2734 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2703 | `mocha -R spec --recursive src/test` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2686 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2681 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2679 | `istanbul cover _mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 2668 | `yarn run build:cjs && mocha --require babel-core/register ./test/index.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2633 | `mocha test/index.js && npm run demo` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2621 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2610 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2586 | `xo && mocha` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2583 | `mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2581 | `mocha --timeout 100000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2577 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2572 | `nyc mocha && tsc` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2568 | `mocha-phantomjs ./test/index.html` | 
| [github-tools/github](https://github.com/github-tools/github) | 2562 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2540 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2521 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2514 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2513 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2511 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2510 | `mocha` | 
| [css/csso](https://github.com/css/csso) | 2496 | `mocha --reporter dot` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2488 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2480 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2479 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2476 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2471 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2464 | `mocha --recursive --watch` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2461 | `npm run mocha && npm run lint` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2459 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2451 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2420 | `mocha --compilers js:babel-register --recursive spec` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2418 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2416 | `mocha` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2414 | `mocha --opts mocha.opts` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2396 | `mocha --reporter=spec test/*-test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2382 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2380 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2375 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2364 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2364 | `node node_modules/mocha/bin/_mocha` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2327 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2321 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2314 | `grunt jshint && mocha` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2312 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2307 | `mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2294 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2292 | `mocha` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2288 | `npm run compile && mocha --compilers js:babel-core/register` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2283 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2247 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2237 | `mocha test/src/**/*.unit.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2229 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2219 | `mocha test` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2218 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2214 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2211 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2208 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2203 | `mocha test test/unit/**/*_test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2192 | `gulp && cd test && mocha . --reporter dot` | 
| [octokit/node-github](https://github.com/octokit/node-github) | 2169 | `nyc mocha test/**/*-test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2165 | `NODE_ENV=test mocha` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2147 | `node_modules/.bin/mocha --reporter spec` | 
| [mozilla/send](https://github.com/mozilla/send) | 2131 | `mocha test/unit` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2123 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2110 | `npm run lint && npm run build && npm run mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2107 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2097 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [gajus/swing](https://github.com/gajus/swing) | 2096 | `mocha --compilers js:babel-register` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2093 | `mocha -R spec` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2090 | `mocha test/unit --require mochahook` | 
| [json5/json5](https://github.com/json5/json5) | 2074 | `mocha --ui exports --reporter spec` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2073 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2032 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [slate/slate](https://github.com/slate/slate) | 2024 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2019 | `mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2019 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2008 | `cross-env BABEL_ENV=test mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 1988 | `mocha --require should --reporter spec` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 1947 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 1938 | `nyc --reporter=html --reporter=text mocha` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1916 | `mocha --require=test/test_helper.js` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1909 | `mocha -R spec test/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1896 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1869 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1863 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1849 | `mocha test/index.js --reporter dot` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1848 | `mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1841 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1829 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 1828 | `mocha ./test/*.spec.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1823 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1821 | `mocha tests.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 1817 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1809 | `mocha --timeout 5000` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1807 | `mocha --require ./test/common --growl test/expect.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1803 | `mocha test && npm run lint` | 
| [Qix-/color](https://github.com/Qix-/color) | 1791 | `mocha` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1790 | `mocha` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1786 | `mocha --reporter spec --timeout 5000` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1783 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1778 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1772 | `mocha -c test/index.js` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1762 | `cross-env NODE_ENV=test mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1757 | `mocha test.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1738 | `mocha test/**/*_test.js --bail` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1735 | `mocha test` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1725 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1722 | `mocha -R landing test/index` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1722 | `mocha -R landing test/index` | 
| [then/promise](https://github.com/then/promise) | 1717 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1716 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1714 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1709 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1706 | `mocha test/runner.js --reporter spec` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1700 | `mocha --compilers js:babel-register` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1697 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1696 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1679 | `mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1678 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1675 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1675 | `mocha --compilers js:babel-core/register __tests__` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1675 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1672 | `xo && mocha` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1670 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [verdaccio/verdaccio](https://github.com/verdaccio/verdaccio) | 1662 | `mocha ./test/functional ./test/unit --reporter=spec --full-trace` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1658 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1655 | `mocha test` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1653 | `mocha` | 
| [Hardmath123/nearley](https://github.com/Hardmath123/nearley) | 1653 | `mocha test/*.test.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1652 | `npm run lint && npm run compile && mocha --reporter spec test/*.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1648 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1647 | `./node_modules/.bin/mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1636 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [KunalKapadia/express-mongoose-es6-rest-api](https://github.com/KunalKapadia/express-mongoose-es6-rest-api) | 1628 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1627 | `mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1616 | `mocha && eslint *.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1613 | `mocha -R spec spec spec/reporters` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1610 | `mocha --reporter spec && npm run test-typescript` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1606 | `lint && mocha --recursive` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1605 | `mocha tests/test.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1605 | `npm run lint && npm run mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1599 | `mocha --expose-gc --slow 300` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1599 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1590 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1578 | `./node_modules/mocha/bin/mocha -R spec` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1576 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1573 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1554 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1554 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1548 | `mocha test/*.js` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1542 | `./node_modules/.bin/mocha` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1533 | `npm run mocha && npm run karma` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1523 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1521 | `npm run lint && mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1518 | `mocha && npm run lint` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1512 | `mocha --reporter spec --grep .` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1493 | `nyc npm run _mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1491 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1490 | `mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1487 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1486 | `npm run mocha && npm run lint` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1485 | `npm run lint && mocha -R dot && npm run cover` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1479 | `mocha tests --compilers js:babel-core/register` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1478 | `mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1463 | `mocha -R spec` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1461 | `mocha test -u bdd -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1460 | `mocha test/` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1459 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1458 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1457 | `mocha spec/` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1457 | `mocha ./test/basic.js -t 5000` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1455 | `mocha test/* --reporter spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1454 | `mocha -u tdd` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1454 | `./node_modules/mocha/bin/mocha -R spec` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1447 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1442 | `node_modules/.bin/mocha --recursive` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1439 | `npm run lint && npm run mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1436 | `npm run test:lint && npm run test:mocha && npm run site` | 
| [pahen/madge](https://github.com/pahen/madge) | 1434 | `npm run lint && npm run mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1431 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1429 | `mocha test/tests.js --timeout=10000` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1422 | `mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1402 | `mocha --reporter spec` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1402 | `mocha test.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1394 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1379 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1362 | `mocha --reporter spec test/*.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1356 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1353 | `nyc mocha` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1353 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1350 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1348 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1342 | `./node_modules/mocha/bin/mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 1340 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1329 | `mocha --check-leaks -R dot` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1326 | `standard "./src/*.js" && mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1325 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1321 | `eslint --rulesdir=dev-tools/eslint --cache . && tsc && mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1321 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1319 | `mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1316 | `cross-env NODE_ENV=test nyc mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1310 | `mocha --compilers js:babel-register` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1295 | `istanbul cover _mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1292 | `mocha --recursive` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1292 | `mocha test.js` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1283 | `standard "src/*.js" && npm run build && mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1275 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1259 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1253 | `npm run build && mocha -r should` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1244 | `mocha` | 
| [sandeepmistry/bleno](https://github.com/sandeepmistry/bleno) | 1231 | `mocha -R spec test/*.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1228 | `mocha --timeout 10000 ./tests/lib.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1226 | `./node_modules/.bin/mocha test` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1218 | `mocha spec/exec.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1215 | `mocha --check-leaks --reporter spec --bail` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1214 | `mocha-phantomjs tests/index.html` | 
| [zeit/ms](https://github.com/zeit/ms) | 1210 | `mocha tests.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1209 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1209 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1203 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1201 | `mocha test/setup.js test/spec/*.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1197 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1196 | `mocha tests` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1195 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [reddit/reddit-mobile](https://github.com/reddit/reddit-mobile) | 1191 | `mocha test/index.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1191 | `mocha test/test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1191 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1185 | `mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1185 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1183 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1181 | `mocha test/*.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1177 | `mocha test/**/*Spec.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1175 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1170 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1168 | `mocha` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1166 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1166 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1165 | `mocha test` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1164 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1162 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1159 | `npm run lint && npm run mocha` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1159 | `istanbul cover _mocha test -- --timeout 20000` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1150 | `mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1149 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1148 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1146 | `mocha --recursive` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1145 | `mocha compiled_tests/` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1143 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1138 | `./node_modules/.bin/mocha` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1137 | `node ./node_modules/mocha/bin/mocha tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1129 | `eslint lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1127 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1126 | `mocha --opts test/opts/mocha.opts` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1126 | `mocha test --timeout 600000` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1116 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1114 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [sorrycc/roadhog](https://github.com/sorrycc/roadhog) | 1108 | `npm run lint && npm run build && cross-env NODE_ENV=test nyc mocha --no-timeouts test/**/*-test.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1106 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1105 | `mocha --check-leaks --require @babel/register` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1099 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1093 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1092 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1088 | `node_modules/.bin/mocha && npm run lint` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1084 | `npm run lint && npm run mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1084 | `mocha --reporter spec` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1082 | `nodeunit test; mocha test` | 
| [variety/variety](https://github.com/variety/variety) | 1075 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1073 | `mocha` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1069 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1068 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1064 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1058 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1055 | `mocha --compilers js:babel-register` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1055 | `mocha` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1052 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1050 | `mocha test/*` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1050 | `mocha --reporter spec --timeout 3000` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1044 | `mocha src/test.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1042 | `node_modules/.bin/mocha` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1041 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1040 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1035 | `mocha $(find test -name '*.test.js')` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1033 | `standard && istanbul cover _mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1023 | `xo && mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1022 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1022 | `istanbul test _mocha` | 
| [jas/playground](https://github.com/jas/playground) | 1021 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1021 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1020 | `mocha --check-leaks -R dot` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1015 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1015 | `mocha --reporter dot` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1014 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1005 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1002 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1000 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 998 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 993 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 992 | `eslint src && mocha && karma start --single-run` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 990 | `mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 989 | `mocha test/unit` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 983 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 982 | `mocha --colors ./test/*.spec.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 982 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 982 | `mocha test/tests.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 981 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 974 | `mocha` | 
| [googlevr/webvr-polyfill](https://github.com/googlevr/webvr-polyfill) | 973 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 972 | `istanbul cover _mocha test/*.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 968 | `eslint . && mocha -t 5000` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 968 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 967 | `mocha --check-leaks --reporter spec --bail test/` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 963 | `NODE_PATH=. mocha **/*.spec.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 962 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 959 | `mocha --timeout 5000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 950 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 946 | `mocha -R list` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 946 | `npm run rollup-cjs && mocha test/test.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 945 | `mocha --recursive --bail --reporter spec test` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 945 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 944 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 939 | `mocha --recursive test/unit/` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 937 | `standard && mocha` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 936 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 935 | `mocha $(find test -name '*.test.js')` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 934 | `mocha tests/test-*` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 930 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 927 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 922 | `mocha --async-only` | 
| [dabeng/OrgChart](https://github.com/dabeng/OrgChart) | 921 | `mocha ./test/**/*-tests.js` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 921 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 920 | `mocha --reporter spec` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 916 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 914 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [tomas/needle](https://github.com/tomas/needle) | 912 | `mocha test` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 906 | ` NODE_ENV=test mocha --compilers js:babel-register` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 904 | `mocha ./test/index.js` | 
| [router5/router5](https://github.com/router5/router5) | 903 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 902 | `mocha spec/*.spec.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 898 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 896 | `npm run prepublish && mocha test/test.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 894 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 892 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 892 | `./node_modules/.bin/mocha --globals angular,require` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 890 | `mocha test` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 888 | `mocha` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 888 | `mocha -t 120000 test/*.test.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 887 | `standard && mocha -b` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 874 | `mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 874 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 873 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 872 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 872 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 871 | `webpack && mocha test/unit` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 867 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 867 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 867 | `mocha --reporter list` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 865 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 864 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 863 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 862 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 857 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 857 | `nyc mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 856 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 854 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 850 | `mocha --recursive test` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 850 | `mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 850 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 848 | `mocha "client.test" --compilers js:babel-register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 843 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 842 | `mocha --reporter spec --bail --check-leaks test/` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 839 | `node_modules/.bin/mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 835 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 832 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 832 | `eslint test && mocha --compilers js:babel/register` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 831 | `mocha --compilers js:babel-register test/*.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 828 | `mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 828 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 827 | `mocha && standard` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 827 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 824 | `npm run lint && mocha -R spec` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 821 | `nyc mocha --timeout=20000 test.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 820 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [MaxCDN/bootstrap-cdn](https://github.com/MaxCDN/bootstrap-cdn) | 820 | `npm run lint && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 819 | `mocha --timeout 200000` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 818 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 816 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 815 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 812 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 811 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 809 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 808 | `mocha --reporter spec` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 808 | `mocha && ember test` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 807 | `mocha --reporter spec --bail --check-leaks test/` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 807 | `node_modules/.bin/mocha test/spec` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 807 | `mocha tests/*.test.js --reporter spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 804 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 803 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 800 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 797 | `mocha tests` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 790 | `mocha -R spec tests/` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 790 | `mocha --check-leaks -t 20000` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 790 | `nyc mocha --require babel-register` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 789 | `npm run convertto:es5 && npm run mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 787 | `mocha -u tdd` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 784 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 784 | `mocha --require babel-register` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 779 | `istanbul cover _mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 779 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 777 | `mocha ./test -R spec` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 776 | `cake build && mocha ./test/mocha/*.coffee` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 775 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 773 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 772 | `mocha` | 
| [reactivestack/cookies](https://github.com/reactivestack/cookies) | 772 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 771 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 770 | `nyc mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 769 | `standard && standard ./bin/* && mocha` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 768 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 768 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 768 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 768 | `mocha ./test/test*.js --reporter spec` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 767 | `mocha -t 5000` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 763 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [edsu/anon](https://github.com/edsu/anon) | 762 | `mocha --colors --reporter spec test.js` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 761 | `mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 758 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 755 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 754 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 753 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 750 | `mocha test --compilers js:babel-register` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 749 | `istanbul cover -- _mocha --reporter spec` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 748 | `npm run lint && mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 744 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 742 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 742 | `xo && mocha -R spec` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 742 | `TEST_MODE=unit NODE_ENV=test jest && TEST_MODE=unit NODE_ENV=test mocha -R ${MOCHA_REPORTER:-spec}` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 739 | `nyc mocha specs` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 739 | `mocha --async-only` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 737 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 737 | `npm run lint && mocha --compilers js:babel-register` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 736 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 735 | `mocha -t 600000` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 734 | `mocha -R spec` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 732 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 732 | `mocha -R spec src/**/*_test.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 730 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 729 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 728 | `mocha -R spec --compilers js:babel-core/register ./tests/setup.js ./tests/** --recursive` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 728 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 726 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 726 | `mocha --reporter spec` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 723 | `mocha --ui tdd --require ./test/__setup` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 722 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 719 | `mocha --reporter list` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 716 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 716 | `mocha spec/*.js` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 714 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 708 | `./node_modules/.bin/mocha -R spec` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 708 | `mocha test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 707 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 705 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 701 | `mocha tests/*.js` | 
| [contra/gulp-concat](https://github.com/contra/gulp-concat) | 699 | `mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 698 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 695 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 693 | `npm run bundle && mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 693 | `cross-env NODE_ENV=test nyc mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 687 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 683 | `mocha tests/*.mocha.js` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 681 | `npm run lint && mocha test` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 678 | `mocha ./test/index.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 678 | `npm run mocha-test test/integration` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 677 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require babel-register --no-timeouts` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 676 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 676 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 675 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 674 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 672 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 672 | `npm run build && istanbul test _mocha test/test.js` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 670 | `mocha -b -R spec test/*` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 670 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 670 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 668 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 666 | `mocha test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 666 | `eslint src test && mocha --compilers babel-register` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 665 | `mocha test` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 665 | `mocha --reporter spec` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 663 | `mocha --reporter spec` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 663 | `mocha` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 662 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 659 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 658 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 656 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 655 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 653 | `mocha` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 652 | `./node_modules/.bin/mocha test/integration` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 652 | `mocha` | 