# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:34 01/24/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39592 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 38745 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 36287 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [expressjs/express](https://github.com/expressjs/express) | 36241 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28569 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23204 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 21788 | `mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 20328 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 17460 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 17359 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17329 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15422 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14608 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13708 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12807 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12476 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11963 | `mocha` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 11919 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11849 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11621 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11508 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 10945 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10736 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10451 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 10164 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9820 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9451 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9266 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 9232 | `mocha --harmony` | 
| [tmpvar/jsdom](https://github.com/tmpvar/jsdom) | 9105 | `mocha test/index.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9096 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 8992 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 8863 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8808 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8477 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8273 | `mocha test/*-test.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8158 | `mocha` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8122 | `mocha --check-leaks -R dot` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8068 | `mocha test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8050 | `grunt clean:test && mocha` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7695 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7691 | `./node_modules/.bin/mocha test/src` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7690 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7609 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7609 | `mocha --compilers js:babel-register test/test.js` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7437 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7411 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [websockets/ws](https://github.com/websockets/ws) | 7390 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7253 | `npm run eslint && npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7246 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 7194 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7105 | `npm run build && istanbul cover _mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7088 | `mocha tests/*.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7036 | `./node_modules/.bin/mocha test` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6691 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6659 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6511 | `mocha $HARMONY_OPTS` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6455 | `mocha --require babel-core/register ./packages/*/test/index.js` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6422 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6359 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6250 | `mocha --opts mocha.opts` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6236 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [almende/vis](https://github.com/almende/vis) | 6153 | `mocha --compilers js:babel-core/register` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6120 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6119 | `nyc mocha test/**/* -r ./test/before` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6039 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5925 | `mocha` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 5912 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5871 | `npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5766 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5717 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5597 | `npm run jshint && mocha test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5576 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5448 | `mocha tests/node.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5382 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5334 | `mocha test --recursive` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5318 | `mocha && eslint lib/**` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5309 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5252 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5208 | `mocha test/test.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5164 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5129 | `mocha src/**/*Tests.js --harmony` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5065 | `mocha --timeout 10000 && npm run lint` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 4932 | `mocha --compilers js:babel-core/register` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4910 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4905 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4754 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4709 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4642 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4612 | `mocha test` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4590 | `mocha --reporter spec -t 8000` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4589 | `mocha -R spec 'tests/app'` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4533 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4525 | `mocha ./test/runner.js` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4467 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4397 | `gulp build; mocha;` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4380 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4325 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4319 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4319 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4319 | `standard && mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4293 | `./node_modules/.bin/mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4222 | `mocha -R spec ./test --recursive` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4183 | `mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4172 | `mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4163 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4157 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 4143 | `npm run build-cli && mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4086 | `mocha test` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 4033 | `mocha && ./bin/shipit staging test` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 3986 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3973 | `nyc mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3887 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3842 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3817 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3795 | `mocha --recursive && make test` | 
| [muicss/mui](https://github.com/muicss/mui) | 3790 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3749 | `mocha --require should --reporter spec` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3740 | `NODE_ENV=test mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3725 | `mocha --require test/babel-hook test/*.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3674 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3643 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3638 | `npm run jshint && npm run mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3581 | `nyc mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3580 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 3548 | `mocha; jshint *.js lib` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3545 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3541 | `standard && mocha --timeout 60000 test/test.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3520 | `npm run lint ; mocha && mocha test/individual` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3520 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3435 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3425 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [primus/primus](https://github.com/primus/primus) | 3424 | `npm run build && mocha test/*.test.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3388 | `mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3388 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3388 | `mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3388 | `node_modules/.bin/mocha test/lib/` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3388 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3371 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3320 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3213 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3210 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3203 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3188 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3145 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3132 | `mocha --check-leaks --reporter spec --bail` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3092 | `mocha` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3082 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3067 | `mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3050 | `npm run lint && npm run mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3050 | `./node_modules/.bin/mocha test/test.*.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3049 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3011 | `yarn run build:cjs && mocha --require babel-core/register ./test/index.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 2992 | `node_modules/.bin/mocha test/tests.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 2991 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 2989 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2959 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2910 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2907 | `mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2904 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2892 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2817 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2805 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2762 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2760 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2757 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2736 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2730 | `mocha -R spec --recursive src/test` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2709 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2702 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2700 | `istanbul cover _mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2683 | `mocha test/index.js && npm run demo` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2661 | `nyc mocha && tsc` | 
| [github-tools/github](https://github.com/github-tools/github) | 2643 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2640 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2633 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2626 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2683 | `mocha test/index.js && npm run demo` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2661 | `nyc mocha && tsc` | 
| [github-tools/github](https://github.com/github-tools/github) | 2643 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2640 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2633 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2626 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2608 | `mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2607 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2596 | `xo && mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2589 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2588 | `mocha --timeout 100000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2572 | `mocha-phantomjs ./test/index.html` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2571 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2565 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2560 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2555 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2551 | `mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2548 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2543 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2543 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2535 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2528 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2523 | `mocha --opts mocha.opts` | 
| [css/csso](https://github.com/css/csso) | 2521 | `mocha --reporter dot` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2514 | `npm run mocha && npm run lint` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2493 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2484 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2484 | `mocha --recursive --watch` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2484 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2472 | `npm run compile && mocha --require babel-core/register` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2469 | `mocha --compilers js:babel-register --recursive spec` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2419 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2412 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2411 | `mocha --reporter=spec test/*-test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2392 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2388 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2386 | `mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2363 | `node node_modules/mocha/bin/_mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2338 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2327 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2322 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2321 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2317 | `grunt jshint && mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2304 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2304 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2282 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2272 | `mocha test` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2265 | `NODE_ENV=test mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2263 | `mocha test/src/**/*.unit.js` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2261 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2250 | `node_modules/.bin/mocha --reporter spec` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2247 | `npm run build && cd test && mocha . --reporter dot` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2239 | `nyc mocha 'test/**/*-test.js'` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2079 | `mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2034 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2032 | `cross-env BABEL_ENV=test mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2028 | `nyc --reporter=html --reporter=text mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2021 | `mocha --require babel-core/register ./packages/*/test/index.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 1987 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1955 | `mocha -R spec test/*.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 1942 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1931 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2079 | `mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2034 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2032 | `cross-env BABEL_ENV=test mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2028 | `nyc --reporter=html --reporter=text mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2021 | `mocha --require babel-core/register ./packages/*/test/index.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 1987 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1955 | `mocha -R spec test/*.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 1942 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1931 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1924 | `mocha && eslint .` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1921 | `mocha --require=test/test_helper.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1899 | `mocha --bail --reporter spec --check-leaks test/` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 1887 | `mocha ./test/*.spec.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1876 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1876 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1875 | `mocha test.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1872 | `mocha test/index.js --reporter dot` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1866 | `mocha test && npm run lint` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1865 | `mocha -c test/index.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1858 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1847 | `mocha -R landing test/index` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1843 | `mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 1833 | `mocha` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1832 | `mocha tests.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1825 | `mocha --require ./test/common --growl test/expect.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1821 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1818 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1807 | `mocha --timeout 5000` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1807 | `mocha --reporter spec --timeout 5000` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1789 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1784 | `mocha --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1783 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1771 | `cross-env NODE_ENV=test mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1768 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1755 | `mocha test/runner.js --reporter spec` | 
| [then/promise](https://github.com/then/promise) | 1752 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1752 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1742 | `mocha test` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1738 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1730 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1727 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1726 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1723 | `mocha --compilers js:babel-core/register __tests__` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1721 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1717 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1715 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1706 | `mocha test/*.test.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1679 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1677 | `npm run lint && mocha --reporter spec test/*.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1669 | `xo && mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1660 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1658 | `./node_modules/.bin/mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 1657 | `./node_modules/.bin/mocha && npm run jshint` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1646 | `npm run lint && mocha --recursive --exit` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1641 | `npm run lint && mocha -R dot && npm run cover` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1635 | `./node_modules/mocha/bin/mocha -R spec` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1635 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1632 | `mocha --reporter spec && npm run test-typescript` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1631 | `mocha -R spec spec spec/reporters` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1631 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1631 | `npm run lint && npm run mocha` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1628 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1631 | `npm run lint && npm run mocha` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1628 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1607 | `mocha tests/test.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1603 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1602 | `mocha --expose-gc --slow 300` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1600 | `npm run mocha && npm run karma` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1589 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1568 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1564 | `mocha test/*.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1564 | `mocha && npm run lint` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1550 | `nyc npm run _mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1544 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1543 | `./node_modules/.bin/mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1541 | `npm run lint && mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1537 | `mocha --reporter spec --grep .` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1533 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1530 | `mocha tests --compilers js:babel-core/register` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1529 | `npm run mocha && npm run lint` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1508 | `mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1503 | `mocha test/` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1503 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1500 | `mocha test -u bdd -R spec` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1500 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1499 | `mocha spec/` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1498 | `mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 1497 | `npm run lint && npm run mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1496 | `mocha ./test/basic.js -t 5000` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1494 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1493 | `mocha test/* --reporter spec` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1493 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1472 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1468 | `./node_modules/mocha/bin/mocha -R spec` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1467 | `npm run test:lint && npm run test:mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1466 | `mocha -R spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1462 | `npm run lint && npm run mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1460 | `mocha --reporter spec test/*.js` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1459 | `mocha -u tdd` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1456 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1429 | `mocha --reporter spec` | 
| [samccone/drool](https://github.com/samccone/drool) | 1428 | `mocha test/tests.js --timeout=10000` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1411 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1405 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1402 | `mocha test.js` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1384 | `standard "src/*.js" && npm run build && mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1370 | `mocha --compilers js:babel-register` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1369 | `nyc mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1365 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1365 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1359 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1357 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1354 | `mocha --check-leaks -R dot` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1353 | `eslint --cache . && tsc && mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1353 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1349 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1345 | `standard "./src/*.js" && mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1345 | `./node_modules/mocha/bin/mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1338 | `mocha test.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1324 | `cross-env NODE_ENV=test nyc mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1321 | `mocha --recursive` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1324 | `cross-env NODE_ENV=test nyc mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1321 | `mocha --recursive` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1317 | `mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1305 | `istanbul cover _mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1292 | `mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1283 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1282 | `mocha-phantomjs tests/index.html` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1265 | `mocha --check-leaks --reporter spec --bail` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1264 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1260 | `npm run build && mocha -r should` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1260 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [zeit/ms](https://github.com/zeit/ms) | 1259 | `mocha tests.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1259 | `mocha --timeout 10000 ./tests/lib.js` | 
| [sandeepmistry/bleno](https://github.com/sandeepmistry/bleno) | 1256 | `mocha -R spec test/*.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1244 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1242 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1239 | `./node_modules/.bin/mocha test` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1230 | `mocha spec/exec.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1227 | `mocha test/setup.js test/spec/*.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1226 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1221 | `mocha compiled_tests/` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1221 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1218 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1211 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1209 | `npm run lint && npm run mocha` | 
| [reddit/reddit-mobile](https://github.com/reddit/reddit-mobile) | 1206 | `mocha test/index.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1206 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1200 | `mocha tests` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1199 | `mocha test/test.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1196 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1196 | `mocha test/*.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1195 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1194 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1187 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1185 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1183 | `istanbul cover _mocha test -- --timeout 20000` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1182 | `mocha test/**/*Spec.js` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1181 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1178 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1172 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1169 | `mocha test` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1165 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1165 | `mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1162 | `mocha --recursive` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1160 | `mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1157 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1154 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1144 | `eslint . && mocha -t 5000` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1144 | `node ./node_modules/mocha/bin/mocha tests` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1143 | `mocha --opts test/opts/mocha.opts` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1142 | `eslint lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1138 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1135 | `mocha --check-leaks --require @babel/register` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1133 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1127 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1126 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1110 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1097 | `npm run lint && npm run mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1096 | `mocha --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1094 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1091 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1091 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1091 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1089 | `mocha` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1088 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1088 | `node_modules/.bin/mocha && npm run lint` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1082 | `mocha src/test.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1079 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1077 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1077 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1069 | `standard && istanbul cover _mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1067 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1066 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1062 | `mocha --compilers js:babel-register` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1062 | `node_modules/.bin/mocha` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1061 | `mocha --check-leaks -t 20000` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1060 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1059 | `mocha --reporter dot` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1059 | `mocha test/*` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1056 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1055 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1052 | `eslint src && mocha && karma start --single-run` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1051 | `mocha test/unit` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1049 | `mocha --reporter spec --timeout 3000` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1049 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1047 | `mocha $(find test -name '*.test.js')` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1045 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1034 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1034 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1032 | `xo && mocha` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1032 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1027 | `istanbul test _mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1025 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1020 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1018 | `mocha --check-leaks -R dot` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1015 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1009 | `mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1009 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1008 | `NODE_PATH=. mocha **/*.spec.js` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1007 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1007 | `mocha --check-leaks --reporter spec --bail test/` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 991 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 990 | `mocha test/tests.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 989 | `mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 988 | `istanbul cover _mocha test/*.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 984 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 983 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 981 | `mocha --colors ./test/*.spec.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 979 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 976 | `mocha tests/test-*` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 974 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 974 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 974 | `mocha test` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 973 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 962 | `mocha --recursive --bail --reporter spec test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 960 | `mocha --timeout 5000` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 957 | `npm run rollup-cjs && mocha test/test.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 956 | `mocha` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 952 | `mocha -R list` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 952 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 952 | `standard && mocha` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 950 | ` NODE_ENV=test mocha --compilers js:babel-register` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 948 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 947 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 946 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 943 | `mocha $(find test -name '*.test.js')` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 939 | `mocha --recursive test/unit/` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 936 | `mocha --async-only` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 933 | `npm run prepublish && mocha test/test.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 931 | `mocha --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 931 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [router5/router5](https://github.com/router5/router5) | 931 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [tomas/needle](https://github.com/tomas/needle) | 927 | `mocha test` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 910 | `standard && mocha -b` | 
| [teambit/bit](https://github.com/teambit/bit) | 907 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 906 | `mocha ./test/index.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 905 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 903 | `mocha spec/*.spec.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 897 | `webpack && mocha test/unit` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 892 | `./node_modules/.bin/mocha --globals angular,require` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 891 | `mocha --recursive test` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 889 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 887 | `mocha --reporter spec --bail --check-leaks test/` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 886 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 883 | `nyc mocha --timeout=20000 test.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 897 | `webpack && mocha test/unit` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 892 | `./node_modules/.bin/mocha --globals angular,require` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 891 | `mocha --recursive test` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 889 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 887 | `mocha --reporter spec --bail --check-leaks test/` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 886 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 883 | `nyc mocha --timeout=20000 test.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 880 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 879 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 877 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [electron/asar](https://github.com/electron/asar) | 875 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 874 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 873 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 872 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 872 | `mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 872 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 871 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 867 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 865 | `mocha --reporter list` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 865 | `mocha --reporter spec --bail --check-leaks test/` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 862 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 857 | `mocha "client.test" --compilers js:babel-register` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 855 | `mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 855 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 854 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [electron/spectron](https://github.com/electron/spectron) | 849 | `mocha && standard` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 849 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 849 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 845 | `mocha --compilers js:babel-register test/*.js` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 845 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 841 | `node_modules/.bin/mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 836 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 836 | `eslint test && mocha --compilers js:babel/register` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 833 | `npm run lint && mocha -R spec` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 832 | `nyc mocha --require babel-register` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 830 | `npm run lint && npm run mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 827 | `mocha --reporter spec --bail --check-leaks test/` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 826 | `mocha --timeout 200000` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 826 | `mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 823 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 822 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 822 | `npm run convertto:es5 && npm run mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 820 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 819 | `mocha ./test/test*.js --reporter spec` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 818 | `mocha tests` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 817 | `node_modules/.bin/mocha test/spec` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 815 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 815 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 815 | `mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 814 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 813 | `mocha --reporter spec` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 813 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 812 | `mocha && ember test` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 811 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 810 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [reactivestack/cookies](https://github.com/reactivestack/cookies) | 808 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 807 | `mocha tests/*.test.js --reporter spec` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 807 | `mocha ./test -R spec` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 793 | `mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 792 | `mocha -u tdd` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 790 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 790 | `mocha -R spec tests/` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 789 | `istanbul cover _mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 789 | `mocha --require babel-register` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 788 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 785 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 784 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 781 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 780 | `mocha -t 5000` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 778 | `mocha --reporter spec --bail --check-leaks test/` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 778 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 777 | `mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 781 | `standard && standard ./bin/* && mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 781 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 780 | `mocha -t 5000` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 778 | `mocha --reporter spec --bail --check-leaks test/` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 778 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 777 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 774 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 772 | `mocha tests/*.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 772 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 770 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [edsu/anon](https://github.com/edsu/anon) | 766 | `mocha --colors --reporter spec test.js` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 765 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 765 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 764 | `mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 763 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 763 | `mocha -R spec` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 763 | `istanbul cover -- _mocha --reporter spec` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 762 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 762 | `mocha test --compilers js:babel-register` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 761 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 760 | `npm run lint && mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 760 | `mocha -t 600000` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 758 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 754 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 754 | `mocha --async-only` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 753 | `nyc mocha specs` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 752 | `xo && mocha -R spec` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 752 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 751 | `mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 748 | `mocha` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 733 | `mocha -R spec src/**/*_test.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 730 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require babel-register --no-timeouts` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 728 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 727 | `mocha --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 723 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 718 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 716 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 715 | `mocha test.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 727 | `mocha --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 723 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [developit/workerize-loader](https://github.com/developit/workerize-loader) | 723 | `npm run build && webpack --config test/webpack.config.js && npm run -s mocha` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 718 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 716 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 715 | `mocha test.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 712 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 712 | `npm run mocha:istanbul` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 706 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 705 | `cross-env NODE_ENV=test nyc mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 705 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [contra/gulp-concat](https://github.com/contra/gulp-concat) | 700 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 699 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 698 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 697 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 694 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 694 | `npm run bundle && mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 693 | `npm run mocha-test test/integration` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 693 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 691 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 691 | `eslint src test && mocha --compilers babel-register` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 697 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 694 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 694 | `npm run bundle && mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 693 | `npm run mocha-test test/integration` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 693 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 691 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 691 | `eslint src test && mocha --compilers babel-register` | 
| [bitpay/insight](https://github.com/bitpay/insight) | 689 | `mocha test` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 688 | `mocha tests/*.mocha.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 686 | `mocha test` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 683 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 681 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 681 | `npm run build && istanbul test _mocha test/test.js` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 657 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 657 | `mocha --harmony --full-trace --check-leaks` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 657 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 657 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 656 | `mocha` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 656 | `npm run lint && mocha ./test/test.js --timeout 1000000` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 653 | `mocha --no-timeouts` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 652 | `./node_modules/.bin/mocha test/integration` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 652 | `./bin/selenium-standalone install && mocha` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 652 | `mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 650 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 650 | `mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 649 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 649 | `npm run lint && npm run mocha` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 647 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 