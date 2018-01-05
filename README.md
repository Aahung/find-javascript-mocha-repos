# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:26 01/05/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39447 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 38292 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 35914 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 35552 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28340 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23060 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 19995 | `mocha test/index.js` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17148 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [developit/preact](https://github.com/developit/preact) | 17019 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15271 | `mocha` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 14581 | `cross-env NODE_ENV=test mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14401 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13639 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12530 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12359 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11930 | `mocha` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 11758 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11705 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11551 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11394 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 10665 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10539 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10353 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 9955 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9678 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9316 | `mocha --reporter spec` | 
| [tj/co](https://github.com/tj/co) | 9166 | `mocha --harmony` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9134 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 8993 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tmpvar/jsdom](https://github.com/tmpvar/jsdom) | 8964 | `mocha test/index.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 8903 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 8756 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8752 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8414 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8199 | `mocha test/*-test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8111 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8033 | `grunt clean:test && mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8029 | `mocha test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7668 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7627 | `./node_modules/.bin/mocha test/src` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7588 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7435 | `mocha --compilers js:babel-register test/test.js` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7428 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7412 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7408 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7203 | `npm run eslint && npm run mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 7178 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7078 | `npm run build && istanbul cover _mocha` | 
| [amark/gun](https://github.com/amark/gun) | 7043 | `mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7009 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 6982 | `./node_modules/.bin/mocha test` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 6972 | `mocha tests/*.js` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6539 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6476 | `mocha $HARMONY_OPTS` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6475 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6353 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6276 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6259 | `mocha --require babel-core/register ./packages/*/test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6159 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [almende/vis](https://github.com/almende/vis) | 6089 | `mocha --compilers js:babel-core/register` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6075 | `mocha --opts mocha.opts` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6026 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 5950 | `nyc mocha test/** -r ./test/before` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5927 | `mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 5917 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5783 | `npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5714 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 5702 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5644 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5509 | `npm run jshint && mocha test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5456 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5392 | `mocha tests/node.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5385 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5287 | `mocha && eslint lib/**` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5267 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5266 | `mocha test --recursive` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5197 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5163 | `mocha --color` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5130 | `mocha test/test.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5120 | `mocha src/**/*Tests.js --harmony` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5013 | `mocha --timeout 10000 && npm run lint` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4848 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4827 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 4783 | `mocha --compilers js:babel-core/register` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4738 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4687 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4610 | `mocha test` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4601 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4575 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4570 | `mocha --reporter spec -t 8000` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4517 | `mocha ./test/runner.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4408 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4383 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4370 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4367 | `gulp build; mocha;` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4305 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4282 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4274 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4257 | `./node_modules/.bin/mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4235 | `standard && mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4224 | `mocha -R spec ./test --recursive` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4126 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4125 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4107 | `mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4021 | `mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4015 | `mocha test` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 3997 | `mocha && ./bin/shipit staging test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3959 | `nyc mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 3899 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3889 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3832 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3813 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [tj/ejs](https://github.com/tj/ejs) | 3722 | `mocha --require should --reporter spec` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3713 | `mocha --recursive && make test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3661 | `NODE_ENV=test mocha` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 3645 | `npm run build-cli && mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3634 | `npm run jshint && npm run mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3626 | `mocha --require test/babel-hook test/*.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3564 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3558 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3556 | `npm run lint && npm run mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3543 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3540 | `standard && mocha --timeout 60000 test/test.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3508 | `mocha tests/javascript` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3468 | `npm run lint ; mocha && mocha test/individual` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3422 | `nyc mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3418 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3416 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [primus/primus](https://github.com/primus/primus) | 3410 | `npm run build && mocha test/*.test.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3381 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3376 | `mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3349 | `node_modules/.bin/mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3345 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3292 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [easy-mock/easy-mock](https://github.com/easy-mock/easy-mock) | 3177 | `cross-env NODE_ENV=test istanbul cover _mocha test/*` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3115 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3108 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3096 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 3093 | `mocha; jshint *.js lib` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3077 | `mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3074 | `mocha --check-leaks --reporter spec --bail` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3062 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3061 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3044 | `./node_modules/.bin/mocha test/test.*.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3042 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3037 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 2978 | `node_modules/.bin/mocha test/tests.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 2977 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2948 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [expressjs/session](https://github.com/expressjs/session) | 2942 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 2928 | `npm run lint && npm run mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 2925 | `nyc mocha "test/**/*.test.js"` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2896 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2886 | `mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2854 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2844 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 2790 | `yarn run build:cjs && mocha --require babel-core/register ./test/index.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2788 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2775 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2754 | `mocha --require should --reporter spec` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2745 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2743 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2708 | `mocha -R spec --recursive src/test` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2693 | `istanbul cover _mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2688 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2681 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2677 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2651 | `mocha test/index.js && npm run demo` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2641 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2616 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2609 | `nyc mocha && tsc` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2599 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2591 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2587 | `xo && mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2586 | `mocha --timeout 100000` | 
| [github-tools/github](https://github.com/github-tools/github) | 2575 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2569 | `mocha-phantomjs ./test/index.html` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2564 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2560 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2560 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2543 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2532 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2523 | `mocha` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2516 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2508 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2507 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2505 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2503 | `export TESTING=true; mocha --reporter list` | 
| [css/csso](https://github.com/css/csso) | 2503 | `mocha --reporter dot` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2488 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2483 | `npm run mocha && npm run lint` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2479 | `mocha --opts mocha.opts` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2468 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2466 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2465 | `mocha --recursive --watch` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2438 | `mocha --compilers js:babel-register --recursive spec` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2432 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2427 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2426 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2401 | `mocha --reporter=spec test/*-test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2391 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2386 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2368 | `npm run compile && mocha --require babel-core/register` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2366 | `node node_modules/mocha/bin/_mocha` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2361 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2341 | `mocha` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2338 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2319 | `mocha --no-colors --reporter spec` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2314 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2310 | `mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2310 | `grunt jshint && mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2288 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2254 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2252 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2249 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2249 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2244 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2241 | `mocha test` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2220 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2215 | `gulp && cd test && mocha . --reporter dot` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2210 | `NODE_ENV=test mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2208 | `mocha test test/unit/**/*_test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2208 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [octokit/node-github](https://github.com/octokit/node-github) | 2200 | `nyc mocha test/**/*-test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2194 | `node_modules/.bin/mocha --reporter spec` | 
| [mozilla/send](https://github.com/mozilla/send) | 2162 | `mocha test/unit` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2146 | `mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2139 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2131 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2121 | `npm run lint && npm run build && npm run mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2110 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2110 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [gajus/swing](https://github.com/gajus/swing) | 2106 | `mocha --compilers js:babel-register` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2105 | `mocha -R spec` | 
| [json5/json5](https://github.com/json5/json5) | 2095 | `mocha --ui exports --reporter spec` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2075 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2056 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2042 | `mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2029 | `mocha --require should --reporter spec` | 
| [slate/slate](https://github.com/slate/slate) | 2022 | `mocha --require babel-core/register ./packages/*/test/index.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2021 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2013 | `cross-env BABEL_ENV=test mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 1980 | `nyc --reporter=html --reporter=text mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 1966 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1917 | `mocha -R spec test/*.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1916 | `mocha --require=test/test_helper.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1899 | `mocha --bail --reporter spec --check-leaks test/` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1885 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1871 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 1863 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1861 | `mocha test/index.js --reporter dot` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 1858 | `mocha ./test/*.spec.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1857 | `mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1856 | `mocha` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 1845 | `export TESTING=true; mocha --reporter list` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1839 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1824 | `mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1821 | `mocha test && npm run lint` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1817 | `mocha tests.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1814 | `mocha --require ./test/common --growl test/expect.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1814 | `mocha -c test/index.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1809 | `mocha --timeout 5000` | 
| [Qix-/color](https://github.com/Qix-/color) | 1800 | `mocha` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1796 | `mocha --reporter spec --timeout 5000` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1792 | `mocha test.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1784 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1783 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1776 | `mocha -R landing test/index` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1763 | `cross-env NODE_ENV=test mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1742 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1737 | `mocha test` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1736 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1735 | `mocha test/**/*_test.js --bail` | 
| [then/promise](https://github.com/then/promise) | 1734 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1730 | `mocha --compilers js:babel-register` | 
| [verdaccio/verdaccio](https://github.com/verdaccio/verdaccio) | 1728 | `mocha ./test/functional ./test/unit --reporter=spec --full-trace` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1727 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1724 | `mocha test/runner.js --reporter spec` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1723 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1713 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1695 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1695 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1693 | `mocha --compilers js:babel-core/register __tests__` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1693 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1690 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1684 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1682 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1680 | `mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1677 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1671 | `xo && mocha` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1662 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1661 | `npm run lint && npm run compile && mocha --reporter spec test/*.js` | 
| [Hardmath123/nearley](https://github.com/Hardmath123/nearley) | 1659 | `mocha test/*.test.js` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1656 | `mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1655 | `mocha` | 
| [KunalKapadia/express-mongoose-es6-rest-api](https://github.com/KunalKapadia/express-mongoose-es6-rest-api) | 1650 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1649 | `./node_modules/.bin/mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1637 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1634 | `mocha && eslint *.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1622 | `mocha --reporter spec && npm run test-typescript` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1620 | `mocha -R spec spec spec/reporters` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1617 | `npm run lint && npm run mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1616 | `lint && mocha --recursive` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1614 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1608 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1605 | `mocha tests/test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1600 | `mocha --expose-gc --slow 300` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1597 | `./node_modules/mocha/bin/mocha -R spec` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1587 | `npm run lint && mocha -R dot && npm run cover` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1585 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1579 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1579 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1566 | `npm run mocha && npm run karma` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1556 | `mocha test/*.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1556 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1546 | `./node_modules/.bin/mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1535 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1534 | `mocha && npm run lint` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1530 | `npm run lint && mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1520 | `mocha --reporter spec --grep .` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1515 | `nyc npm run _mocha` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1509 | `mocha` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1509 | `npm run mocha && npm run lint` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1498 | `mocha tests --compilers js:babel-core/register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1489 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1489 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1488 | `mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1477 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1475 | `mocha test -u bdd -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1475 | `mocha test/` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1473 | `mocha ./test/basic.js -t 5000` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1470 | `mocha spec/` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1467 | `mocha test/* --reporter spec` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1464 | `mocha -R spec` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1463 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1463 | `./node_modules/mocha/bin/mocha -R spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1454 | `mocha -u tdd` | 
| [pahen/madge](https://github.com/pahen/madge) | 1452 | `npm run lint && npm run mocha` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1446 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1446 | `npm run lint && npm run mocha` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1444 | `mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1441 | `node_modules/.bin/mocha --recursive` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1436 | `npm run test:lint && npm run test:mocha && npm run site` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1432 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1427 | `mocha test/tests.js --timeout=10000` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1414 | `mocha --reporter spec` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1409 | `mocha --reporter spec test/*.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1402 | `mocha test.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1399 | `mocha test/**/*.spec.js` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1395 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1386 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [share/sharedb](https://github.com/share/sharedb) | 1362 | `./node_modules/.bin/mocha && npm run jshint` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1361 | `nyc mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1361 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1356 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1350 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1343 | `./node_modules/mocha/bin/mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1341 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1340 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1337 | `eslint --rulesdir=dev-tools/eslint --cache . && tsc && mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1336 | `standard "./src/*.js" && mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1334 | `mocha --compilers js:babel-register` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1334 | `mocha --check-leaks -R dot` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1321 | `standard "src/*.js" && npm run build && mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1316 | `cross-env NODE_ENV=test nyc mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1316 | `mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1312 | `mocha test.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1308 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1302 | `mocha --recursive` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1295 | `istanbul cover _mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1264 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1260 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1256 | `npm run build && mocha -r should` | 
| [sandeepmistry/bleno](https://github.com/sandeepmistry/bleno) | 1238 | `mocha -R spec test/*.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1237 | `mocha --timeout 10000 ./tests/lib.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1235 | `mocha --check-leaks --reporter spec --bail` | 
| [zeit/ms](https://github.com/zeit/ms) | 1232 | `mocha tests.js` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1230 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1228 | `./node_modules/.bin/mocha test` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1224 | `mocha test --timeout 600000` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1219 | `mocha spec/exec.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1218 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1214 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1214 | `mocha-phantomjs tests/index.html` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1213 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1210 | `mocha test/setup.js test/spec/*.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1209 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1208 | `mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1205 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1197 | `mocha tests` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1195 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [reddit/reddit-mobile](https://github.com/reddit/reddit-mobile) | 1193 | `mocha test/index.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1193 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1192 | `mocha test/test.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1185 | `npm run lint && npm run mocha` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1185 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1184 | `mocha test/*.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1182 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1179 | `mocha test/**/*Spec.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1178 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1177 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1177 | `mocha compiled_tests/` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1176 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1175 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1173 | `mocha` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1167 | `istanbul cover _mocha test -- --timeout 20000` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1165 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1164 | `mocha test` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1156 | `mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1155 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1152 | `mocha --recursive` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1148 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1147 | `./node_modules/.bin/mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1146 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1138 | `node ./node_modules/mocha/bin/mocha tests` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1138 | `mocha --opts test/opts/mocha.opts` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1133 | `eslint lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1129 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1121 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1120 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1117 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1114 | `mocha --check-leaks --require @babel/register` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1105 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1094 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1091 | `npm run lint && npm run mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1091 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1087 | `node_modules/.bin/mocha && npm run lint` | 
| [normalize/mz](https://github.com/normalize/mz) | 1085 | `mocha --reporter spec` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [variety/variety](https://github.com/variety/variety) | 1081 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1079 | `mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1071 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1070 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1069 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1067 | `mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1066 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1060 | `mocha --check-leaks -t 20000` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1059 | `mocha src/test.js` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1058 | `mocha --compilers js:babel-register` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1054 | `mocha test/*` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1053 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1051 | `eslint . && mocha -t 5000` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1051 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1050 | `mocha --reporter spec --timeout 3000` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1046 | `node_modules/.bin/mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1038 | `standard && istanbul cover _mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1037 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1037 | `mocha $(find test -name '*.test.js')` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1036 | `mocha --reporter dot` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1033 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1033 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1028 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1028 | `xo && mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1024 | `istanbul test _mocha` | 
| [jas/playground](https://github.com/jas/playground) | 1022 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1021 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1017 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1017 | `mocha --check-leaks -R dot` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1016 | `mocha test/unit` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1014 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1014 | `eslint src && mocha && karma start --single-run` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1008 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1005 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1002 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 998 | `mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 998 | `NODE_PATH=. mocha **/*.spec.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 989 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 989 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 982 | `mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 982 | `mocha test/tests.js` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 981 | `mocha --colors ./test/*.spec.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 981 | `mocha --check-leaks --reporter spec --bail test/` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 978 | `istanbul cover _mocha test/*.js` | 
| [googlevr/webvr-polyfill](https://github.com/googlevr/webvr-polyfill) | 976 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 974 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 969 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 962 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 959 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 959 | `mocha --timeout 5000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 957 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 953 | `mocha --recursive --bail --reporter spec test` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 952 | `mocha tests/test-*` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 950 | `mocha -R list` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 946 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 946 | `npm run rollup-cjs && mocha test/test.js` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 941 | `standard && mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 939 | `mocha` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 938 | `mocha --recursive test/unit/` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 938 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 938 | `mocha $(find test -name '*.test.js')` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 930 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 927 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 926 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 925 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 924 | ` NODE_ENV=test mocha --compilers js:babel-register` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 923 | `mocha --reporter spec` | 
| [tomas/needle](https://github.com/tomas/needle) | 917 | `mocha test` | 
| [router5/router5](https://github.com/router5/router5) | 917 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 915 | `npm run prepublish && mocha test/test.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 914 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 913 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 903 | `mocha ./test/index.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 903 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 902 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 901 | `mocha spec/*.spec.js` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 900 | `mocha -t 120000 test/*.test.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 900 | `standard && mocha -b` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 895 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 892 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 892 | `./node_modules/.bin/mocha --globals angular,require` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 884 | `webpack && mocha test/unit` | 
| [teambit/bit](https://github.com/teambit/bit) | 883 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 881 | `mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 879 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 878 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 878 | `nyc mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 876 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 875 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 874 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [electron/asar](https://github.com/electron/asar) | 871 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 871 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 870 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 867 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 866 | `mocha --recursive test` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 865 | `mocha --reporter list` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 859 | `mocha` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 859 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 858 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 855 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 854 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 851 | `mocha "client.test" --compilers js:babel-register` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 850 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 850 | `mocha --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 845 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 845 | `nyc mocha --timeout=20000 test.js` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 842 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 841 | `node_modules/.bin/mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 839 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 838 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 835 | `mocha --compilers js:babel-register test/*.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 834 | `mocha && standard` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 832 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 831 | `eslint test && mocha --compilers js:babel/register` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 828 | `npm run lint && mocha -R spec` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 824 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 824 | `mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 823 | `mocha --timeout 200000` | 
| [MaxCDN/bootstrap-cdn](https://github.com/MaxCDN/bootstrap-cdn) | 822 | `npm run lint && npm run mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 821 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 821 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 820 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 818 | `mocha --reporter spec --bail --check-leaks test/` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 816 | `node_modules/.bin/mocha test/spec` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 815 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 812 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 811 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 811 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 810 | `mocha --reporter spec` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 807 | `mocha tests/*.test.js --reporter spec` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 807 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 807 | `mocha && ember test` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 805 | `nyc mocha --require babel-register` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 804 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 803 | `mocha tests` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 796 | `npm run convertto:es5 && npm run mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 796 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 795 | `mocha --check-leaks -t 20000` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 790 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 789 | `mocha -R spec tests/` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 788 | `mocha ./test -R spec` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 787 | `mocha ./test/test*.js --reporter spec` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 787 | `mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 786 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 786 | `mocha -u tdd` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 785 | `mocha --require babel-register` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 783 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 783 | `istanbul cover _mocha` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 782 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 777 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 777 | `cake build && mocha ./test/mocha/*.coffee` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 777 | `mocha -t 5000` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 776 | `standard && standard ./bin/* && mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 775 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 774 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 773 | `nyc mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 773 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 770 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 766 | `npm run lint && mocha --compilers js:babel-register` | 
| [edsu/anon](https://github.com/edsu/anon) | 764 | `mocha --colors --reporter spec test.js` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 764 | `mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 761 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 759 | `mocha -R spec ./test/unit/**` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 759 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 756 | `mocha test --compilers js:babel-register` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 756 | `istanbul cover -- _mocha --reporter spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 754 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 752 | `TEST_MODE=unit NODE_ENV=test jest && TEST_MODE=unit NODE_ENV=test mocha -R ${MOCHA_REPORTER:-spec}` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 750 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 748 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 748 | `npm run lint && mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 748 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 747 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 746 | `nyc mocha specs` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 746 | `mocha -R spec` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 745 | `mocha --async-only` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 744 | `xo && mocha -R spec` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 743 | `mocha -t 600000` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 741 | `mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 740 | `mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 738 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 733 | `mocha -R spec src/**/*_test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 733 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 729 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 728 | `mocha --ui tdd --require ./test/__setup` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 728 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 726 | `mocha --reporter spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 725 | `mocha --reporter list` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 725 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 725 | `mocha spec/*.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 722 | `./node_modules/.bin/mocha -R spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 722 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 719 | `mocha tests/*.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 718 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 711 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 708 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 708 | `mocha test.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 705 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 699 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require babel-register --no-timeouts` | 
| [contra/gulp-concat](https://github.com/contra/gulp-concat) | 699 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 696 | `cross-env NODE_ENV=test nyc mocha` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 695 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 692 | `npm run bundle && mocha` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 686 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 686 | `npm run mocha-test test/integration` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 684 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 684 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 682 | `mocha tests/*.mocha.js` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 679 | `npm run lint && mocha test` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 677 | `mocha ./test/index.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 676 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 676 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 676 | `npm run build && istanbul test _mocha test/test.js` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 675 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 673 | `mocha test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 673 | `eslint src test && mocha --compilers babel-register` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 672 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 670 | `mocha -b -R spec test/*` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 670 | `mocha test` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 669 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 666 | `mocha --reporter spec` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 663 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 663 | `mocha --reporter spec` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 663 | `mocha` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 662 | `mocha` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 662 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 660 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 660 | `mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 657 | `npm run mocha:istanbul` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 654 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 653 | `./node_modules/.bin/mocha test/integration` | 