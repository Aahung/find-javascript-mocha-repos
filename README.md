# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:14 01/01/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39415 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 38201 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 35849 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 35407 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28293 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23021 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 19890 | `mocha test/index.js` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17106 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [developit/preact](https://github.com/developit/preact) | 16962 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15249 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14366 | `mocha test/*.test.js test/**/*.test.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 13987 | `cross-env NODE_ENV=test mocha` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13626 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12476 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12325 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11919 | `mocha` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 11736 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11677 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11547 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11371 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 10616 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10492 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10326 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 9920 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9632 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9297 | `mocha --reporter spec` | 
| [tj/co](https://github.com/tj/co) | 9149 | `mocha --harmony` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9103 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 8968 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tmpvar/jsdom](https://github.com/tmpvar/jsdom) | 8946 | `mocha test/index.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 8885 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 8734 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8734 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8406 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8190 | `mocha test/*-test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8108 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8033 | `grunt clean:test && mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8009 | `mocha test/test.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 7969 | `mocha` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7657 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7617 | `./node_modules/.bin/mocha test/src` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7569 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7428 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7411 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7372 | `mocha --compilers js:babel-register test/test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7371 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7200 | `npm run eslint && npm run mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 7133 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7072 | `npm run build && istanbul cover _mocha` | 
| [amark/gun](https://github.com/amark/gun) | 7004 | `mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 6972 | `./node_modules/.bin/mocha test` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 6959 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 6940 | `mocha tests/*.js` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6500 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6464 | `mocha $HARMONY_OPTS` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6449 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6339 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6249 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6231 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6133 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [almende/vis](https://github.com/almende/vis) | 6064 | `mocha --compilers js:babel-core/register` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6008 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5928 | `mocha` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 5907 | `nyc mocha test/** -r ./test/before` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 5895 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5773 | `npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 5745 | `mocha --opts mocha.opts` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5705 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 5654 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5622 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5491 | `npm run jshint && mocha test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5434 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5387 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5384 | `mocha tests/node.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5282 | `mocha && eslint lib/**` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5264 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5261 | `mocha test --recursive` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5189 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5163 | `mocha --color` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5117 | `mocha test/test.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5116 | `mocha src/**/*Tests.js --harmony` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 4997 | `mocha --timeout 10000 && npm run lint` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4835 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4813 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4736 | `gulp lint && mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 4730 | `mocha --compilers js:babel-core/register` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4684 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4607 | `mocha test` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4591 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4569 | `mocha --reporter spec -t 8000` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4568 | `mocha -R spec 'tests/app'` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4514 | `mocha ./test/runner.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4389 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4368 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4367 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4359 | `gulp build; mocha;` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4304 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4280 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4261 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4247 | `./node_modules/.bin/mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4224 | `mocha -R spec ./test --recursive` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4219 | `standard && mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4120 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4119 | `mocha` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4085 | `mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4006 | `mocha test` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 3995 | `mocha && ./bin/shipit staging test` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 3976 | `mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3951 | `nyc mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3891 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 3879 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3831 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3811 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [muicss/mui](https://github.com/muicss/mui) | 3751 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3716 | `mocha --require should --reporter spec` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3699 | `mocha --recursive && make test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3647 | `NODE_ENV=test mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3633 | `npm run jshint && npm run mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3602 | `mocha --require test/babel-hook test/*.js` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 3591 | `npm run build-cli && mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3555 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3554 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3543 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3537 | `standard && mocha --timeout 60000 test/test.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3533 | `npm run lint && npm run mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3504 | `mocha tests/javascript` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3463 | `npm run lint ; mocha && mocha test/individual` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3417 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3417 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [primus/primus](https://github.com/primus/primus) | 3409 | `npm run build && mocha test/*.test.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3409 | `nyc mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3379 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3377 | `mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3344 | `node_modules/.bin/mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3337 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3287 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [easy-mock/easy-mock](https://github.com/easy-mock/easy-mock) | 3159 | `cross-env NODE_ENV=test istanbul cover _mocha test/*` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3096 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3078 | `mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3077 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3068 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3067 | `mocha --check-leaks --reporter spec --bail` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3059 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3042 | `./node_modules/.bin/mocha test/test.*.js` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3041 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 3028 | `mocha; jshint *.js lib` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3026 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3003 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 2972 | `node_modules/.bin/mocha test/tests.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 2964 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2943 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [expressjs/session](https://github.com/expressjs/session) | 2927 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 2906 | `nyc mocha "test/**/*.test.js"` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 2901 | `npm run lint && npm run mocha` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2894 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2882 | `mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2837 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2836 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2786 | `mocha test/*.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 2772 | `yarn run build:cjs && mocha --require babel-core/register ./test/index.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2769 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2753 | `mocha --require should --reporter spec` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2741 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2736 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2709 | `mocha -R spec --recursive src/test` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2690 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2689 | `istanbul cover _mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2681 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2664 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2644 | `mocha test/index.js && npm run demo` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2622 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2616 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2600 | `nyc mocha && tsc` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2593 | `mocha` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2587 | `xo && mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2584 | `mocha --timeout 100000` | 
| [github-tools/github](https://github.com/github-tools/github) | 2571 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2567 | `mocha-phantomjs ./test/index.html` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2560 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2555 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2554 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2549 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2529 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2525 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2517 | `mocha` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2510 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [css/csso](https://github.com/css/csso) | 2504 | `mocha --reporter dot` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2502 | `export TESTING=true; mocha --reporter list` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2499 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2497 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2497 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2480 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2475 | `npm run mocha && npm run lint` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2465 | `mocha --recursive --watch` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2464 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2451 | `mocha --opts mocha.opts` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2448 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2435 | `mocha --compilers js:babel-register --recursive spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2424 | `mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2411 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2403 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2401 | `mocha --reporter=spec test/*-test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2385 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2384 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2365 | `node node_modules/mocha/bin/_mocha` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2351 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2342 | `npm run compile && mocha --compilers js:babel-core/register` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2337 | `mocha` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2330 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2319 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2312 | `grunt jshint && mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2306 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2303 | `mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2287 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2251 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2246 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2241 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2238 | `mocha test` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2237 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2235 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2220 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2208 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2203 | `mocha test test/unit/**/*_test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2201 | `gulp && cd test && mocha . --reporter dot` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2195 | `NODE_ENV=test mocha` | 
| [octokit/node-github](https://github.com/octokit/node-github) | 2191 | `nyc mocha test/**/*-test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2180 | `node_modules/.bin/mocha --reporter spec` | 
| [mozilla/send](https://github.com/mozilla/send) | 2147 | `mocha test/unit` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2137 | `mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2128 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2123 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2120 | `npm run lint && npm run build && npm run mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2108 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2107 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [gajus/swing](https://github.com/gajus/swing) | 2104 | `mocha --compilers js:babel-register` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2098 | `mocha -R spec` | 
| [json5/json5](https://github.com/json5/json5) | 2090 | `mocha --ui exports --reporter spec` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2075 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2051 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2035 | `mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2022 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2020 | `mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2018 | `mocha --require should --reporter spec` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2012 | `cross-env BABEL_ENV=test mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 1973 | `nyc --reporter=html --reporter=text mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 1961 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1916 | `mocha -R spec test/*.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1913 | `mocha --require=test/test_helper.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1899 | `mocha --bail --reporter spec --check-leaks test/` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1876 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1871 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1852 | `mocha test/index.js --reporter dot` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1852 | `mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1851 | `mocha` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 1850 | `mocha ./test/*.spec.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 1840 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1835 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 1829 | `export TESTING=true; mocha --reporter list` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1821 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1818 | `mocha tests.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1816 | `mocha test && npm run lint` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1813 | `mocha --require ./test/common --growl test/expect.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1813 | `mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1813 | `mocha -c test/index.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1809 | `mocha --timeout 5000` | 
| [Qix-/color](https://github.com/Qix-/color) | 1798 | `mocha` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1794 | `mocha --reporter spec --timeout 5000` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1781 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1781 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1780 | `mocha test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1763 | `mocha -R landing test/index` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1761 | `cross-env NODE_ENV=test mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1739 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1738 | `mocha test` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1736 | `mocha test/**/*_test.js --bail` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1728 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [then/promise](https://github.com/then/promise) | 1727 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1723 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1722 | `mocha --compilers js:babel-register` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1721 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1721 | `mocha test/runner.js --reporter spec` | 
| [verdaccio/verdaccio](https://github.com/verdaccio/verdaccio) | 1704 | `mocha ./test/functional ./test/unit --reporter=spec --full-trace` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1703 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1696 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1694 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1691 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1687 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1686 | `mocha --compilers js:babel-core/register __tests__` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1683 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1680 | `mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1672 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1671 | `xo && mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1670 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1658 | `npm run lint && npm run compile && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1658 | `mocha test` | 
| [Hardmath123/nearley](https://github.com/Hardmath123/nearley) | 1658 | `mocha test/*.test.js` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1656 | `mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1647 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1647 | `./node_modules/.bin/mocha` | 
| [KunalKapadia/express-mongoose-es6-rest-api](https://github.com/KunalKapadia/express-mongoose-es6-rest-api) | 1640 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1637 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1629 | `mocha && eslint *.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1620 | `mocha -R spec spec spec/reporters` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1614 | `mocha --reporter spec && npm run test-typescript` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1612 | `npm run lint && npm run mocha` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1611 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1611 | `lint && mocha --recursive` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1605 | `mocha tests/test.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1601 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1601 | `mocha --expose-gc --slow 300` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1593 | `./node_modules/mocha/bin/mocha -R spec` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1580 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1575 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1574 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1562 | `npm run lint && mocha -R dot && npm run cover` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1558 | `npm run mocha && npm run karma` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1554 | `mocha test/*.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1554 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1544 | `./node_modules/.bin/mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1532 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1529 | `mocha && npm run lint` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1527 | `npm run lint && mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1518 | `mocha --reporter spec --grep .` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1508 | `nyc npm run _mocha` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1504 | `npm run mocha && npm run lint` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1503 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1489 | `mocha tests --compilers js:babel-core/register` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1489 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1488 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1486 | `mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1473 | `mocha test/` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1471 | `mocha test -u bdd -R spec` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1467 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1466 | `mocha spec/` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1466 | `mocha ./test/basic.js -t 5000` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1465 | `mocha test/* --reporter spec` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1463 | `mocha -R spec` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1461 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1458 | `./node_modules/mocha/bin/mocha -R spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1454 | `mocha -u tdd` | 
| [pahen/madge](https://github.com/pahen/madge) | 1450 | `npm run lint && npm run mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1447 | `npm run lint && npm run mocha` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1445 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1440 | `node_modules/.bin/mocha --recursive` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1437 | `mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1436 | `npm run test:lint && npm run test:mocha && npm run site` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1431 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1427 | `mocha test/tests.js --timeout=10000` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1411 | `mocha --reporter spec` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1402 | `mocha test.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1397 | `mocha --reporter spec test/*.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1397 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1384 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1382 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1358 | `nyc mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1358 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1358 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [share/sharedb](https://github.com/share/sharedb) | 1355 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1348 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1342 | `./node_modules/mocha/bin/mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1334 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1334 | `eslint --rulesdir=dev-tools/eslint --cache . && tsc && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1332 | `mocha --check-leaks -R dot` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1331 | `standard "./src/*.js" && mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1331 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1329 | `mocha --compilers js:babel-register` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1316 | `mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1315 | `cross-env NODE_ENV=test nyc mocha` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1314 | `standard "src/*.js" && npm run build && mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1300 | `mocha test.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1299 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1299 | `mocha --recursive` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1295 | `istanbul cover _mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1259 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1258 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1256 | `npm run build && mocha -r should` | 
| [sandeepmistry/bleno](https://github.com/sandeepmistry/bleno) | 1236 | `mocha -R spec test/*.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1234 | `mocha --timeout 10000 ./tests/lib.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1230 | `mocha --check-leaks --reporter spec --bail` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1227 | `./node_modules/.bin/mocha test` | 
| [zeit/ms](https://github.com/zeit/ms) | 1224 | `mocha tests.js` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1220 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1219 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1214 | `mocha-phantomjs tests/index.html` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1213 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1209 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1208 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1208 | `mocha test/setup.js test/spec/*.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1207 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1207 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1198 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1196 | `mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1193 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1192 | `mocha test --timeout 600000` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1191 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [reddit/reddit-mobile](https://github.com/reddit/reddit-mobile) | 1190 | `mocha test/index.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1190 | `mocha test/test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1183 | `mocha test/*.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1179 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1177 | `mocha test/**/*Spec.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1176 | `npm run lint && npm run mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1176 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1175 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1174 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1172 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1169 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1168 | `mocha compiled_tests/` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1167 | `istanbul cover _mocha test -- --timeout 20000` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1165 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1163 | `mocha test` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1154 | `mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1154 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1151 | `mocha --recursive` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1147 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [sorrycc/roadhog](https://github.com/sorrycc/roadhog) | 1146 | `npm run lint && npm run build && cross-env NODE_ENV=test nyc mocha --no-timeouts test/**/*-test.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1146 | `./node_modules/.bin/mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1145 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1138 | `node ./node_modules/mocha/bin/mocha tests` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1137 | `mocha --opts test/opts/mocha.opts` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1130 | `eslint lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1128 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1120 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1119 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1112 | `mocha --check-leaks --require @babel/register` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1111 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1105 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1094 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1090 | `npm run lint && npm run mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1090 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1087 | `node_modules/.bin/mocha && npm run lint` | 
| [normalize/mz](https://github.com/normalize/mz) | 1084 | `mocha --reporter spec` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [variety/variety](https://github.com/variety/variety) | 1078 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1077 | `mocha` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1070 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1070 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1069 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1066 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1062 | `mocha` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1058 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1055 | `mocha --compilers js:babel-register` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1054 | `mocha src/test.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1052 | `mocha test/*` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1050 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1050 | `mocha --reporter spec --timeout 3000` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1049 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1043 | `node_modules/.bin/mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1037 | `mocha $(find test -name '*.test.js')` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1036 | `standard && istanbul cover _mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1032 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1031 | `mocha --reporter dot` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1031 | `eslint . && mocha -t 5000` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1029 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1027 | `xo && mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1026 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1024 | `istanbul test _mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1021 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [jas/playground](https://github.com/jas/playground) | 1021 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1017 | `mocha --check-leaks -R dot` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1016 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1010 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1007 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1007 | `eslint src && mocha && karma start --single-run` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1005 | `mocha test/unit` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1004 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 999 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 999 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 998 | `NODE_PATH=. mocha **/*.spec.js` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 995 | `mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 988 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 987 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 982 | `mocha test/tests.js` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 981 | `mocha --colors ./test/*.spec.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 980 | `mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 977 | `istanbul cover _mocha test/*.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 977 | `mocha --check-leaks --reporter spec --bail test/` | 
| [googlevr/webvr-polyfill](https://github.com/googlevr/webvr-polyfill) | 976 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 973 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 967 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 960 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 959 | `mocha --timeout 5000` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 957 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 956 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 950 | `mocha --recursive --bail --reporter spec test` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 950 | `mocha -R list` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 946 | `mocha tests/test-*` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 945 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 945 | `npm run rollup-cjs && mocha test/test.js` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 938 | `standard && mocha` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 938 | `mocha $(find test -name '*.test.js')` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 937 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 936 | `mocha --recursive test/unit/` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 935 | `mocha` | 
| [dabeng/OrgChart](https://github.com/dabeng/OrgChart) | 928 | `mocha ./test/**/*-tests.js` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 926 | `mocha --async-only` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 926 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 924 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 923 | `mocha --reporter spec` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 921 | ` NODE_ENV=test mocha --compilers js:babel-register` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 918 | `mocha test` | 
| [tomas/needle](https://github.com/tomas/needle) | 916 | `mocha test` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 914 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [router5/router5](https://github.com/router5/router5) | 914 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 910 | `npm run prepublish && mocha test/test.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 908 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 903 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 901 | `mocha spec/*.spec.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 900 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 898 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 895 | `mocha -t 120000 test/*.test.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 894 | `standard && mocha -b` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 892 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 892 | `./node_modules/.bin/mocha --globals angular,require` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 884 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 883 | `webpack && mocha test/unit` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 878 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 878 | `mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 878 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 876 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [teambit/bit](https://github.com/teambit/bit) | 876 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 874 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 874 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 874 | `mocha --reporter spec --bail --check-leaks test/` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 869 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [electron/asar](https://github.com/electron/asar) | 869 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 868 | `mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 866 | `mocha --reporter list` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 863 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 859 | `mocha --recursive test` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 858 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 858 | `mocha` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 858 | `mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 854 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 854 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 851 | `mocha "client.test" --compilers js:babel-register` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 847 | `mocha --reporter spec --bail --check-leaks test/` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 846 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 843 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 842 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 840 | `node_modules/.bin/mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 838 | `nyc mocha --timeout=20000 test.js` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 835 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 833 | `mocha --compilers js:babel-register test/*.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 833 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [electron/spectron](https://github.com/electron/spectron) | 833 | `mocha && standard` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 831 | `eslint test && mocha --compilers js:babel/register` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 828 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 826 | `npm run lint && mocha -R spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 825 | `mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 822 | `mocha --timeout 200000` | 
| [MaxCDN/bootstrap-cdn](https://github.com/MaxCDN/bootstrap-cdn) | 821 | `npm run lint && npm run mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 821 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 819 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 819 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 816 | `mocha --reporter spec --bail --check-leaks test/` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 815 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 814 | `node_modules/.bin/mocha test/spec` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 811 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 811 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 810 | `mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 810 | `mocha --reporter spec` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 807 | `mocha && ember test` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 806 | `mocha tests/*.test.js --reporter spec` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 806 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 804 | `mocha` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 801 | `nyc mocha --require babel-register` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 800 | `mocha tests` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 795 | `npm run convertto:es5 && npm run mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 793 | `mocha --check-leaks -t 20000` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 793 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 789 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 786 | `mocha -u tdd` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 786 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 784 | `mocha --require babel-register` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 784 | `mocha ./test -R spec` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 781 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 781 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 781 | `mocha ./test/test*.js --reporter spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 781 | `istanbul cover _mocha` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 780 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 777 | `cake build && mocha ./test/mocha/*.coffee` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 776 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 776 | `mocha -t 5000` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 774 | `mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 774 | `standard && standard ./bin/* && mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 774 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 773 | `mocha --reporter spec --bail --check-leaks test/` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 772 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 771 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 767 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 764 | `mocha --colors --reporter spec test.js` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 764 | `mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 758 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 758 | `mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 757 | `npm run lint && mocha --compilers js:babel-register` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 755 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 755 | `istanbul cover -- _mocha --reporter spec` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 753 | `mocha test --compilers js:babel-register` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 749 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 748 | `TEST_MODE=unit NODE_ENV=test jest && TEST_MODE=unit NODE_ENV=test mocha -R ${MOCHA_REPORTER:-spec}` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 747 | `npm run lint && mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 747 | `mocha -R spec ./test/unit/**` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 747 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 747 | `mocha` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 745 | `mocha -R spec` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 744 | `nyc mocha specs` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 744 | `xo && mocha -R spec` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 744 | `mocha --async-only` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 740 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 739 | `mocha -t 600000` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 739 | `mocha` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 737 | `mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 736 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 732 | `mocha -R spec src/**/*_test.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 729 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 728 | `mocha --ui tdd --require ./test/__setup` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 728 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 727 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 725 | `mocha --reporter spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 724 | `mocha --reporter list` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 723 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 721 | `mocha spec/*.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 720 | `./node_modules/.bin/mocha -R spec` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 718 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 713 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 712 | `mocha tests/*.js` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 711 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 708 | `mocha test.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 705 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 705 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [contra/gulp-concat](https://github.com/contra/gulp-concat) | 699 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 696 | `cross-env NODE_ENV=test nyc mocha` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 693 | `npm run bundle && mocha` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 691 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require babel-register --no-timeouts` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 690 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 684 | `mocha tests/*.mocha.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 683 | `npm run mocha-test test/integration` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 683 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 681 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 680 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 679 | `npm run lint && mocha test` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 677 | `mocha ./test/index.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 677 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 675 | `npm run build && istanbul test _mocha test/test.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 673 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 673 | `eslint src test && mocha --compilers babel-register` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 673 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 672 | `mocha test` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 670 | `mocha -b -R spec test/*` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 669 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 668 | `mocha test` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 666 | `mocha --reporter spec` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 663 | `mocha --reporter spec` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 663 | `mocha` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 662 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 661 | `mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 661 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 660 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 659 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 658 | `mocha` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 653 | `./node_modules/.bin/mocha test/integration` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 653 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 652 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [developit/decko](https://github.com/developit/decko) | 651 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 651 | `mocha` | 