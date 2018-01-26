# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:34 01/26/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39610 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 38810 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 36403 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [expressjs/express](https://github.com/expressjs/express) | 36284 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28584 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23227 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 20386 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 17897 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 17400 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17349 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15431 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14627 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13714 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12825 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12495 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11966 | `mocha` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 11945 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11868 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11631 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11526 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 10977 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10756 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10461 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 10209 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9840 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9474 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9291 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 9239 | `mocha --harmony` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9124 | `mocha test/index.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9111 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9005 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 8882 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8815 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8482 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8284 | `mocha test/*-test.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8176 | `mocha` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8123 | `mocha --check-leaks -R dot` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8071 | `mocha test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7701 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7699 | `./node_modules/.bin/mocha test/src` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7696 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7651 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7620 | `mocha --compilers js:babel-register test/test.js` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7436 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 7419 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7411 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7278 | `npm run eslint && npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7263 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 7206 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7107 | `npm run build && istanbul cover _mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7105 | `mocha tests/*.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7045 | `./node_modules/.bin/mocha test` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6707 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6674 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6517 | `mocha $HARMONY_OPTS` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6461 | `mocha --require babel-core/register ./packages/*/test/index.js` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6427 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6371 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6265 | `mocha --opts mocha.opts` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6250 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [almende/vis](https://github.com/almende/vis) | 6170 | `mocha --compilers js:babel-core/register` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6137 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6136 | `nyc mocha test/**/* -r ./test/before` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6049 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 5938 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5923 | `mocha` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5876 | `npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5770 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5722 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5612 | `npm run jshint && mocha test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5588 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5460 | `mocha tests/node.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5383 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5345 | `mocha test --recursive` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5321 | `mocha && eslint lib/**` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5312 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5263 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5221 | `mocha test/test.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5164 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5133 | `mocha src/**/*Tests.js --harmony` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5074 | `mocha --timeout 10000 && npm run lint` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 4950 | `mocha --compilers js:babel-core/register` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4916 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4915 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4755 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4709 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4649 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4613 | `mocha test` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4594 | `mocha --reporter spec -t 8000` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4591 | `mocha -R spec 'tests/app'` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4545 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4528 | `mocha ./test/runner.js` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4485 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4398 | `gulp build; mocha;` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4382 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4331 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4331 | `standard && mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4327 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4318 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4296 | `./node_modules/.bin/mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4222 | `mocha -R spec ./test --recursive` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4193 | `mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4191 | `mocha` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 4184 | `npm run build-cli && mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4167 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4162 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4096 | `mocha test` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 4035 | `mocha && ./bin/shipit staging test` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 3995 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3975 | `nyc mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3887 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3843 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3819 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3800 | `mocha --recursive && make test` | 
| [muicss/mui](https://github.com/muicss/mui) | 3791 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3756 | `mocha --require should --reporter spec` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3746 | `NODE_ENV=test mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3742 | `mocha --require test/babel-hook test/*.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3682 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3648 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3639 | `npm run jshint && npm run mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3589 | `nyc mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 3588 | `mocha; jshint *.js lib` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3580 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3545 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3542 | `standard && mocha --timeout 60000 test/test.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3530 | `npm run lint ; mocha && mocha test/individual` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3520 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3437 | `mocha --reporter spec --timeout 3000` | 
| [primus/primus](https://github.com/primus/primus) | 3426 | `npm run build && mocha test/*.test.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3426 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3405 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3389 | `mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3389 | `node_modules/.bin/mocha test/lib/` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3373 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3326 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3235 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3227 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3216 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3198 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3151 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3145 | `mocha --check-leaks --reporter spec --bail` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3092 | `mocha` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3089 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3069 | `npm run lint && npm run mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3068 | `mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3054 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3054 | `./node_modules/.bin/mocha test/test.*.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3021 | `yarn run build:cjs && mocha --require babel-core/register ./test/index.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3000 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 2997 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 2996 | `node_modules/.bin/mocha test/tests.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2960 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2914 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2913 | `mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2910 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2895 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2840 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2806 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2778 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2761 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2757 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2757 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2755 | `mocha --require should --reporter spec` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2732 | `mocha -R spec --recursive src/test` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 2718 | `NODE_ENV=test mocha test/**/*.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2711 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2703 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2703 | `istanbul cover _mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2687 | `mocha test/index.js && npm run demo` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2666 | `nyc mocha && tsc` | 
| [tj/should.js](https://github.com/tj/should.js) | 2659 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2644 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2644 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [github-tools/github](https://github.com/github-tools/github) | 2643 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2623 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2614 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2610 | `mocha` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2598 | `xo && mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2594 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2589 | `mocha --timeout 100000` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2580 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2572 | `mocha-phantomjs ./test/index.html` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2572 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2563 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2561 | `mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2561 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2550 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2548 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2545 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2542 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2541 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2528 | `mocha --opts mocha.opts` | 
| [css/csso](https://github.com/css/csso) | 2525 | `mocha --reporter dot` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2518 | `npm run mocha && npm run lint` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2507 | `export TESTING=true; mocha --reporter list` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2503 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2491 | `npm run compile && mocha --require babel-core/register` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2490 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2487 | `mocha --recursive --watch` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2484 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2471 | `mocha --compilers js:babel-register --recursive spec` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2427 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2413 | `mocha --reporter=spec test/*-test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2412 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2393 | `mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2391 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2390 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2363 | `node node_modules/mocha/bin/_mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2340 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2333 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2328 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2322 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2317 | `grunt jshint && mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2307 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2305 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2285 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2273 | `NODE_ENV=test mocha` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2273 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2267 | `mocha test/src/**/*.unit.js` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2260 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2258 | `node_modules/.bin/mocha --reporter spec` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2249 | `npm run build && cd test && mocha . --reporter dot` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2245 | `nyc mocha 'test/**/*-test.js'` | 
| [mozilla/send](https://github.com/mozilla/send) | 2234 | `mocha test/unit` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2220 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2216 | `mocha test test/unit/**/*_test.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 2215 | `mocha ./test/*.spec.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2208 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [json5/json5](https://github.com/json5/json5) | 2192 | `mocha --ui exports --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2191 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2185 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2179 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2153 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2152 | `mocha test/unit --require mochahook` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2143 | `npm run lint && npm run build && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2137 | `mocha -R spec` | 
| [gajus/swing](https://github.com/gajus/swing) | 2122 | `mocha --compilers js:babel-register` | 
| [mde/ejs](https://github.com/mde/ejs) | 2101 | `mocha --require should --reporter spec` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2095 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2094 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1886 | `mocha test.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1879 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1873 | `mocha test/index.js --reporter dot` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1866 | `mocha -c test/index.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1859 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1854 | `mocha -R landing test/index` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1844 | `mocha` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1832 | `mocha tests.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1826 | `mocha --require ./test/common --growl test/expect.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1819 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1809 | `mocha --reporter spec --timeout 5000` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1806 | `mocha --timeout 5000` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1785 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1933 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1931 | `mocha && eslint .` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1921 | `mocha --require=test/test_helper.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1898 | `mocha --bail --reporter spec --check-leaks test/` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1886 | `mocha test.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1879 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1877 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1873 | `mocha test/index.js --reporter dot` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1872 | `mocha test && npm run lint` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1866 | `mocha -c test/index.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1859 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1854 | `mocha -R landing test/index` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1844 | `mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 1839 | `mocha` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1832 | `mocha tests.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1826 | `mocha --require ./test/common --growl test/expect.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1819 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1809 | `mocha --reporter spec --timeout 5000` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1806 | `mocha --timeout 5000` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1797 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1790 | `mocha --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1785 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1775 | `cross-env NODE_ENV=test mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1770 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1761 | `mocha test/runner.js --reporter spec` | 
| [then/promise](https://github.com/then/promise) | 1753 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1752 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1743 | `mocha test` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1738 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1732 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1732 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1731 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1727 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1725 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1720 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1718 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1711 | `mocha test/*.test.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1699 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1696 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1693 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1691 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1687 | `mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1685 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1682 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1680 | `npm run lint && mocha --reporter spec test/*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1669 | `mocha && eslint *.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1668 | `xo && mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 1663 | `./node_modules/.bin/mocha && npm run jshint` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1661 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1656 | `./node_modules/.bin/mocha` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1648 | `npm run lint && mocha -R dot && npm run cover` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1648 | `npm run lint && mocha --recursive --exit` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1639 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1638 | `./node_modules/mocha/bin/mocha -R spec` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1635 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1635 | `mocha -R spec spec spec/reporters` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1635 | `mocha --reporter spec && npm run test-typescript` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1611 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1607 | `mocha tests/test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1606 | `npm run mocha && npm run karma` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1605 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1602 | `mocha --expose-gc --slow 300` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1569 | `mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1568 | `mocha && npm run lint` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1564 | `mocha test/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1538 | `mocha --reporter spec --grep .` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1537 | `mocha` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1533 | `npm run mocha && npm run lint` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1533 | `mocha tests --compilers js:babel-core/register` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1513 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1511 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1510 | `mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1505 | `mocha test/` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1503 | `mocha test -u bdd -R spec` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1503 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1502 | `mocha spec/` | 
| [pahen/madge](https://github.com/pahen/madge) | 1499 | `npm run lint && npm run mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1499 | `mocha ./test/basic.js -t 5000` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1495 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1494 | `mocha test/* --reporter spec` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1473 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1468 | `./node_modules/mocha/bin/mocha -R spec` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1467 | `npm run test:lint && npm run test:mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1467 | `mocha -R spec` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1466 | `mocha --reporter spec test/*.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1461 | `npm run lint && npm run mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1460 | `mocha -u tdd` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1457 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1447 | `node_modules/.bin/mocha --recursive` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1436 | `mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1432 | `mocha --reporter spec` | 
| [samccone/drool](https://github.com/samccone/drool) | 1430 | `mocha test/tests.js --timeout=10000` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1447 | `node_modules/.bin/mocha --recursive` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1436 | `mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1432 | `mocha --reporter spec` | 
| [samccone/drool](https://github.com/samccone/drool) | 1430 | `mocha test/tests.js --timeout=10000` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1411 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1405 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1402 | `mocha test.js` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1391 | `standard "src/*.js" && npm run build && mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1382 | `mocha --compilers js:babel-register` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1379 | `mocha test --timeout 600000` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1373 | `nyc mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1368 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1366 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1359 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1358 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1357 | `mocha --check-leaks -R dot` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1356 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1355 | `eslint --cache . && tsc && mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1352 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1346 | `standard "./src/*.js" && mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1346 | `./node_modules/mocha/bin/mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1344 | `mocha test.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1324 | `cross-env NODE_ENV=test nyc mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1322 | `mocha --recursive` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1317 | `mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1307 | `istanbul cover _mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1293 | `mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1292 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1284 | `mocha-phantomjs tests/index.html` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1231 | `mocha spec/exec.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1228 | `mocha test/setup.js test/spec/*.js` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1224 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1223 | `mocha compiled_tests/` | 
| [electron/devtron](https://github.com/electron/devtron) | 1218 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1212 | `npm run lint && npm run mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1211 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [reddit/reddit-mobile](https://github.com/reddit/reddit-mobile) | 1206 | `mocha test/index.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1200 | `mocha tests` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1200 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1200 | `mocha test/test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1199 | `mocha test/*.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1197 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1196 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1195 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1185 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1185 | `istanbul cover _mocha test -- --timeout 20000` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1231 | `mocha spec/exec.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1228 | `mocha test/setup.js test/spec/*.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1227 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1224 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1223 | `mocha compiled_tests/` | 
| [electron/devtron](https://github.com/electron/devtron) | 1218 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1212 | `npm run lint && npm run mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1211 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1209 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [reddit/reddit-mobile](https://github.com/reddit/reddit-mobile) | 1206 | `mocha test/index.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1200 | `mocha tests` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1200 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1200 | `mocha test/test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1199 | `mocha test/*.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1197 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1196 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1195 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1185 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1185 | `istanbul cover _mocha test -- --timeout 20000` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1182 | `mocha test/**/*Spec.js` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1182 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1177 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1175 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1169 | `mocha test` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1168 | `mocha` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1166 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1165 | `mocha --recursive` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1160 | `mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1158 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1157 | `eslint . && mocha -t 5000` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1156 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1145 | `node ./node_modules/mocha/bin/mocha tests` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1145 | `mocha --opts test/opts/mocha.opts` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1143 | `eslint lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1143 | `mocha --check-leaks --require @babel/register` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1139 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1134 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1128 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1127 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1111 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1098 | `npm run lint && npm run mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1097 | `mocha --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1096 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1094 | `mocha` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1093 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1091 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1091 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1091 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1088 | `node_modules/.bin/mocha && npm run lint` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1086 | `mocha src/test.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1083 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1077 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1077 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1071 | `standard && istanbul cover _mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1070 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1068 | `mocha --reporter dot` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1067 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1064 | `mocha --compilers js:babel-register` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1064 | `node_modules/.bin/mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1057 | `mocha test/unit` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1054 | `eslint src && mocha && karma start --single-run` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1052 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1049 | `mocha --reporter spec --timeout 3000` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1047 | `mocha $(find test -name '*.test.js')` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1045 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1039 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1036 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1034 | `xo && mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1029 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1028 | `istanbul test _mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1022 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1018 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 995 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 992 | `istanbul cover _mocha test/*.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 991 | `mocha test/tests.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 988 | `mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 984 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 984 | `mocha test` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 983 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 981 | `mocha --colors ./test/*.spec.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 981 | `mocha tests/test-*` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 980 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 978 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 974 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 974 | `mocha` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 981 | `mocha --colors ./test/*.spec.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 981 | `mocha tests/test-*` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 980 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 978 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 974 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 974 | `mocha` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 962 | `mocha --recursive --bail --reporter spec test` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 960 | `mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 957 | `npm run rollup-cjs && mocha test/test.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 957 | `mocha --timeout 5000` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 953 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 952 | ` NODE_ENV=test mocha --compilers js:babel-register` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 952 | `standard && mocha` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 951 | `mocha -R list` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 949 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 948 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 947 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 944 | `mocha $(find test -name '*.test.js')` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 941 | `mocha --recursive test/unit/` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 938 | `npm run prepublish && mocha test/test.js` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 937 | `mocha --async-only` | 
| [router5/router5](https://github.com/router5/router5) | 933 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 931 | `mocha --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 931 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 926 | `mocha test` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 925 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 924 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 923 | `mocha -t 120000 test/*.test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 918 | `mocha` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 915 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 913 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 912 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 910 | `standard && mocha -b` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 908 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 906 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 903 | `mocha spec/*.spec.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 901 | `webpack && mocha test/unit` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 899 | `mocha --recursive test` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 892 | `./node_modules/.bin/mocha --globals angular,require` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 889 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 889 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 889 | `nyc mocha --timeout=20000 test.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 889 | `mocha --reporter spec --bail --check-leaks test/` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 882 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 880 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 880 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [electron/asar](https://github.com/electron/asar) | 878 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 877 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 875 | `mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 875 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 874 | `mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 873 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 873 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 872 | `mocha --reporter spec --bail --check-leaks test/` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 867 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 865 | `mocha --reporter list` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 861 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 860 | `mocha "client.test" --compilers js:babel-register` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 858 | `mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 857 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 855 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 853 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [electron/spectron](https://github.com/electron/spectron) | 850 | `mocha && standard` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 850 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 848 | `mocha --compilers js:babel-register test/*.js` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 846 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 841 | `node_modules/.bin/mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 838 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 838 | `nyc mocha --require babel-register` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 836 | `eslint test && mocha --compilers js:babel/register` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 834 | `npm run lint && mocha -R spec` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 830 | `mocha --reporter spec --bail --check-leaks test/` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 830 | `npm run lint && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 826 | `mocha --timeout 200000` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 826 | `mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 824 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 824 | `mocha ./test/test*.js --reporter spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 824 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 823 | `npm run convertto:es5 && npm run mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 823 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 821 | `mocha tests` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 819 | `node_modules/.bin/mocha test/spec` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 817 | `mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 816 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 816 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 814 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 814 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 813 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 813 | `mocha --reporter spec` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 812 | `mocha && ember test` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 811 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 810 | `mocha ./test -R spec` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 807 | `mocha -R spec ./test/unit/**` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 804 | `npm run lint && mocha --compilers js:babel-register` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 798 | `mocha --check-leaks -t 20000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 793 | `mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 792 | `mocha -u tdd` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 791 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 791 | `mocha tests/*.js` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 790 | `mocha -R spec tests/` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 790 | `mocha --require babel-register` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 789 | `istanbul cover _mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 788 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 787 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 785 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 785 | `mocha -t 5000` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 782 | `standard && standard ./bin/* && mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 781 | `mocha --reporter spec --bail --check-leaks test/` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 781 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 779 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 778 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 774 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 774 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 774 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 770 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 768 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [edsu/anon](https://github.com/edsu/anon) | 766 | `mocha --colors --reporter spec test.js` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 765 | `mocha -R spec` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 765 | `istanbul cover -- _mocha --reporter spec` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 764 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 764 | `mocha test --compilers js:babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 763 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 763 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 761 | `mocha -t 600000` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 760 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 760 | `npm run lint && mocha` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 760 | `NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 758 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 756 | `nyc mocha specs` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 756 | `mocha --async-only` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 756 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 755 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 752 | `xo && mocha -R spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 751 | `mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 751 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 743 | `mocha --ui tdd --require ./test/__setup` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 740 | `./node_modules/.bin/mocha -R spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 739 | `mocha --reporter list` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 739 | `mocha spec/*.js` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 735 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require babel-register --no-timeouts` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 733 | `mocha -R spec src/**/*_test.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 732 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 728 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 727 | `mocha --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 723 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 719 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 718 | `npm run mocha:istanbul` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 718 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 715 | `mocha test.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 712 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 708 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 707 | `cross-env NODE_ENV=test nyc mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 706 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 702 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [contra/gulp-concat](https://github.com/contra/gulp-concat) | 700 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 698 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 698 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 695 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 695 | `npm run bundle && mocha` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 693 | `npm run mocha-test test/integration` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 693 | `eslint src test && mocha --compilers babel-register` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 693 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [bitpay/insight](https://github.com/bitpay/insight) | 691 | `mocha test` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 689 | `mocha tests/*.mocha.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 685 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 685 | `mocha test` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 655 | `mocha --no-timeouts` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 654 | `./bin/selenium-standalone install && mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 653 | `mocha` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 652 | `mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 651 | `npm run lint && npm run mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 650 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 647 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 645 | `npm run-script jshint && npm run-script mocha` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 644 | `mocha` | 