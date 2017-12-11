# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:28 12/11/17 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39254 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 37764 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 35516 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 34779 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28155 | `mocha --reporter spec` | 
| [caolan/async](https://github.com/caolan/async) | 22870 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 19557 | `mocha test/index.js` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 16948 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [developit/preact](https://github.com/developit/preact) | 16622 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15126 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14180 | `mocha test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13577 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12273 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12180 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11895 | `mocha` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 11654 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11514 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11480 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11239 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 10353 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10276 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10237 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 9715 | `NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9472 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9157 | `mocha --reporter spec` | 
| [tj/co](https://github.com/tj/co) | 9078 | `mocha --harmony` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 8982 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 8875 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tmpvar/jsdom](https://github.com/tmpvar/jsdom) | 8843 | `mocha test/index.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 8791 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8680 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [svg/svgo](https://github.com/svg/svgo) | 8604 | `set NODE_ENV=test && mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8345 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8091 | `mocha test/*-test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8090 | `mocha --check-leaks -R dot` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 8073 | `cross-env NODE_ENV=test mocha` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8009 | `grunt clean:test && mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 7975 | `mocha test/test.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 7792 | `mocha` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7619 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7538 | `./node_modules/.bin/mocha test/src` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7480 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7424 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7395 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7315 | `mocha --compilers js:babel-register test/test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7172 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7171 | `npm run eslint && npm run mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7032 | `npm run build && istanbul cover _mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 6944 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 6911 | `./node_modules/.bin/mocha test` | 
| [amark/gun](https://github.com/amark/gun) | 6873 | `mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 6815 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 6799 | `mocha tests/*.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6431 | `mocha $HARMONY_OPTS` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6340 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6305 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6260 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6141 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6130 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6032 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [almende/vis](https://github.com/almende/vis) | 5982 | `mocha --compilers js:babel-core/register` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5931 | `mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 5920 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 5771 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 5737 | `nyc mocha test/** -r ./test/before` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5632 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5631 | `npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 5578 | `mocha --opts mocha.opts` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5513 | `npm run test:mocha:src` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 5454 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5417 | `npm run jshint && mocha test/` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5387 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5350 | `mocha tests/node.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5341 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5257 | `mocha && eslint lib/**` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5243 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5160 | `mocha --color` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5160 | `mocha test --recursive` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5133 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5110 | `mocha src/**/*Tests.js --harmony` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5043 | `mocha test/test.js` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 4917 | `mocha --timeout 10000 && npm run lint` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4791 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4731 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4717 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4661 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4606 | `mocha test` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 4574 | `mocha --compilers js:babel-core/register` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4557 | `mocha --reporter spec -t 8000` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4549 | `mocha -R spec 'tests/app'` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4543 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4506 | `mocha ./test/runner.js` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4361 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4332 | `gulp build; mocha;` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4295 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4283 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4276 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4236 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4221 | `mocha -R spec ./test --recursive` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4206 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4202 | `./node_modules/.bin/mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4134 | `standard && mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4090 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4075 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4000 | `mocha` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 3965 | `mocha && ./bin/shipit staging test` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 3941 | `mocha test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3924 | `nyc mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3892 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3819 | `export TESTING=true; mocha --reporter list` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 3814 | `mocha` | 
| [erming/shout](https://github.com/erming/shout) | 3811 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 3801 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [muicss/mui](https://github.com/muicss/mui) | 3729 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3687 | `mocha --require should --reporter spec` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3634 | `mocha && make test` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3630 | `npm run jshint && npm run mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3571 | `NODE_ENV=test mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3543 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3529 | `standard && mocha --timeout 60000 test/test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3528 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3496 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3493 | `mocha tests/javascript` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3486 | `mocha --require test/babel-hook test/*.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3481 | `npm run lint && npm run mocha` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3420 | `npm run lint ; mocha && mocha test/individual` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3409 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3402 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [primus/primus](https://github.com/primus/primus) | 3385 | `npm run build && mocha test/*.test.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3376 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3373 | `mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3356 | `nyc mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3327 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3269 | `npm run lint && mocha && EIO_WS_ENGINE=ws mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3260 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 3145 | `npm run build-cli && mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3077 | `mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3066 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [easy-mock/easy-mock](https://github.com/easy-mock/easy-mock) | 3063 | `cross-env NODE_ENV=test istanbul cover _mocha test/*` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3053 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3041 | `./node_modules/.bin/mocha test/test.*.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3009 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3009 | `mocha --check-leaks --reporter spec --bail` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3007 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 2981 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 2964 | `node_modules/.bin/mocha test/tests.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2943 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 2921 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 2902 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2889 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [expressjs/session](https://github.com/expressjs/session) | 2869 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2867 | `mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 2849 | `nyc mocha "test/**/*.test.js"` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 2840 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2802 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 2790 | `npm run lint && npm run mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2781 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2764 | `mocha test/*.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2750 | `mocha --require should --reporter spec` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2736 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2732 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2729 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2700 | `mocha -R spec --recursive src/test` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2679 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2676 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2669 | `istanbul cover _mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2616 | `mocha test/index.js && npm run demo` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 2616 | `mocha; jshint *.js lib` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2601 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2585 | `xo && mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2580 | `mocha --timeout 100000` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2577 | `mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2572 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2568 | `mocha-phantomjs ./test/index.html` | 
| [github-tools/github](https://github.com/github-tools/github) | 2555 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2547 | `nyc mocha && tsc` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2523 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2518 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2499 | `export TESTING=true; mocha --reporter list` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2499 | `NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2489 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [css/csso](https://github.com/css/csso) | 2486 | `mocha --reporter dot` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2484 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2478 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2474 | `mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2470 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2468 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2466 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2462 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2461 | `mocha --recursive --watch` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 2456 | `yarn run build:cjs && mocha --require babel-core/register ./test/index.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2455 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2448 | `npm run mocha && npm run lint` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2439 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2423 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2412 | `mocha --compilers js:babel-register --recursive spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2399 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2391 | `mocha --reporter=spec test/*-test.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2382 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2375 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2371 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2360 | `node node_modules/mocha/bin/_mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2339 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2319 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2311 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2310 | `grunt jshint && mocha` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2307 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2292 | `mocha --opts mocha.opts` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2283 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2282 | `mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2280 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2273 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2269 | `mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2246 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2233 | `npm run compile && mocha --compilers js:babel-core/register` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2227 | `mocha test/src/**/*.unit.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2218 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2208 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2205 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2202 | `mocha test` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2200 | `mocha test test/unit/**/*_test.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2181 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2181 | `gulp && cd test && mocha . --reporter dot` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2178 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [octokit/node-github](https://github.com/octokit/node-github) | 2152 | `nyc mocha test/**/*-test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2132 | `node_modules/.bin/mocha --reporter spec` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2118 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2116 | `NODE_ENV=test mocha` | 
| [mozilla/send](https://github.com/mozilla/send) | 2106 | `mocha test/unit` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2096 | `npm run lint && npm run build && npm run mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2089 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [gajus/swing](https://github.com/gajus/swing) | 2087 | `mocha --compilers js:babel-register` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2081 | `mocha -R spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2075 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2073 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2066 | `mocha test/unit --require mochahook` | 
| [json5/json5](https://github.com/json5/json5) | 2050 | `mocha --ui exports --reporter spec` | 
| [slate/slate](https://github.com/slate/slate) | 2023 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2017 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2016 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2005 | `cross-env BABEL_ENV=test mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2002 | `mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 1962 | `mocha --require should --reporter spec` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 1944 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 1936 | `nyc --reporter=html --reporter=text mocha` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1912 | `mocha --require=test/test_helper.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1895 | `mocha --bail --reporter spec --check-leaks test/` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1889 | `mocha -R spec test/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1865 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1850 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1842 | `mocha test/index.js --reporter dot` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1837 | `mocha` | 
| [punkave/apostrophe](https://github.com/punkave/apostrophe) | 1824 | `mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1823 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 1821 | `mocha ./test/*.spec.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1820 | `mocha tests.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1816 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1810 | `mocha --timeout 5000` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1800 | `mocha --require ./test/common --growl test/expect.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 1793 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1782 | `mocha test && npm run lint` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1781 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [Qix-/color](https://github.com/Qix-/color) | 1778 | `mocha` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1771 | `mocha --reporter spec --timeout 5000` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1770 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1755 | `mocha` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1754 | `cross-env NODE_ENV=test mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1750 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1737 | `mocha test/**/*_test.js --bail` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1735 | `mocha test.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1734 | `mocha test` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 1728 | `export TESTING=true; mocha --reporter list` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1721 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1713 | `mocha -c test/index.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1709 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [then/promise](https://github.com/then/promise) | 1708 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1706 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1696 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1696 | `mocha test/runner.js --reporter spec` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1694 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1681 | `mocha -R landing test/index` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1681 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1678 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1673 | `xo && mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1666 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1666 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1665 | `mocha --compilers js:babel-register` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1664 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1662 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1656 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1653 | `mocha test` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1651 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1650 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1642 | `./node_modules/.bin/mocha` | 
| [Hardmath123/nearley](https://github.com/Hardmath123/nearley) | 1642 | `mocha test/*.test.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1641 | `npm run lint && npm run compile && mocha --reporter spec test/*.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1631 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1627 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [KunalKapadia/express-mongoose-es6-rest-api](https://github.com/KunalKapadia/express-mongoose-es6-rest-api) | 1609 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1606 | `mocha -R spec spec spec/reporters` | 
| [verdaccio/verdaccio](https://github.com/verdaccio/verdaccio) | 1606 | `mocha ./test/functional ./test/unit --reporter=spec --full-trace` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1605 | `mocha tests/test.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1604 | `npm run lint && npm run mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1602 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1602 | `mocha --reporter spec && npm run test-typescript` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1601 | `lint && mocha --recursive` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1600 | `mocha && eslint *.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1596 | `mocha --expose-gc --slow 300` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1595 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1585 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1581 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1575 | `mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1572 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1569 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1569 | `./node_modules/mocha/bin/mocha -R spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1550 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1541 | `mocha test/*.js` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1540 | `./node_modules/.bin/mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1531 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1515 | `npm run lint && mocha` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1511 | `npm run mocha && npm run karma` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1511 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1508 | `mocha && npm run lint` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1501 | `mocha --reporter spec --grep .` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1489 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1485 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1481 | `npm run mocha && npm run lint` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1477 | `mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1477 | `nyc npm run _mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1466 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1463 | `mocha tests --compilers js:babel-core/register` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1462 | `mocha -R spec` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1458 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1452 | `mocha spec/` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1451 | `mocha ./test/basic.js -t 5000` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1449 | `mocha -u tdd` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1448 | `mocha test/` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1448 | `./node_modules/mocha/bin/mocha -R spec` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1447 | `mocha test -u bdd -R spec` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1447 | `mocha test/* --reporter spec` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1443 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1442 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1440 | `node_modules/.bin/mocha --recursive` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1430 | `mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1430 | `npm run lint && mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1428 | `mocha test/tests.js --timeout=10000` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1422 | `npm run test:lint && npm run test:mocha && npm run site` | 
| [pahen/madge](https://github.com/pahen/madge) | 1415 | `npm run lint && npm run mocha` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1403 | `mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1402 | `mocha test.js` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1396 | `mocha --reporter spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1390 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1371 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1355 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1350 | `nyc mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1344 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1339 | `./node_modules/mocha/bin/mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1332 | `mocha --reporter spec test/*.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1329 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1320 | `mocha --check-leaks -R dot` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1319 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1318 | `mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 1317 | `./node_modules/.bin/mocha && npm run jshint` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1315 | `cross-env NODE_ENV=test nyc mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1314 | `standard "./src/*.js" && mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1314 | `eslint --rulesdir=dev-tools/eslint --cache . && tsc && mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1311 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [trufflesuite/ganache-cli](https://github.com/trufflesuite/ganache-cli) | 1299 | `mocha` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1297 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1293 | `mocha --compilers js:babel-register` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1289 | `istanbul cover _mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1287 | `mocha --recursive` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1268 | `mocha test.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1258 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1245 | `npm run build && mocha -r should` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1243 | `standard "src/*.js" && npm run build && mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1242 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1238 | `mocha` | 
| [sandeepmistry/bleno](https://github.com/sandeepmistry/bleno) | 1227 | `mocha -R spec test/*.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1221 | `./node_modules/.bin/mocha test` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1214 | `mocha-phantomjs tests/index.html` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1213 | `mocha --timeout 10000 ./tests/lib.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1208 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1208 | `mocha spec/exec.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1204 | `mocha --check-leaks --reporter spec --bail` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1200 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [zeit/ms](https://github.com/zeit/ms) | 1199 | `mocha tests.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1195 | `mocha tests` | 
| [electron/devtron](https://github.com/electron/devtron) | 1192 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1190 | `mocha test/test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1189 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1187 | `mocha test/setup.js test/spec/*.js` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1186 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [reddit/reddit-mobile](https://github.com/reddit/reddit-mobile) | 1183 | `mocha test/index.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1181 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1178 | `mocha test/*.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1178 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1176 | `mocha test/**/*Spec.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1172 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1170 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1166 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1165 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1165 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1163 | `mocha test` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1162 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1155 | `mocha` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1153 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1149 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1149 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1148 | `istanbul cover _mocha test -- --timeout 20000` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1147 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1146 | `mocha --full-trace --check-leaks` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1144 | `mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1142 | `mocha --recursive` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1139 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1139 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1136 | `./node_modules/.bin/mocha` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1134 | `node ./node_modules/mocha/bin/mocha tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1128 | `eslint lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1126 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1121 | `mocha compiled_tests/` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1114 | `mocha --opts test/opts/mocha.opts` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1111 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1110 | `mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1099 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1098 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1094 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1089 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1088 | `node_modules/.bin/mocha && npm run lint` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1079 | `mocha --check-leaks --require @babel/register` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1079 | `npm run lint && npm run mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1076 | `mocha --reporter spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1070 | `mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1070 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1067 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1066 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1060 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1059 | `mocha --check-leaks -t 20000` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1057 | `npm run lint && mocha -R dot && npm run cover` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1055 | `mocha --compilers js:babel-register` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1051 | `mocha --reporter spec --timeout 3000` | 
| [sorrycc/roadhog](https://github.com/sorrycc/roadhog) | 1050 | `npm run lint && npm run build && cross-env NODE_ENV=test nyc mocha --no-timeouts test/**/*-test.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1049 | `mocha test/*` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1047 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1040 | `node_modules/.bin/mocha` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1039 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1036 | `mocha src/test.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1034 | `mocha $(find test -name '*.test.js')` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1033 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1032 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1028 | `standard && istanbul cover _mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1021 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1021 | `istanbul test _mocha` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1020 | `mocha --check-leaks -R dot` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1019 | `xo && mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1011 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1007 | `mocha --reporter dot` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1007 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1007 | `mocha test --timeout 600000` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1005 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1000 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 998 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 997 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 988 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 986 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 985 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 984 | `mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 982 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 982 | `mocha test/tests.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 982 | `eslint src && mocha && karma start --single-run` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 980 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 980 | `mocha --colors ./test/*.spec.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 978 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 975 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 975 | `mocha test/unit` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 974 | `mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 962 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 960 | `istanbul cover _mocha test/*.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 959 | `mocha --timeout 5000` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 958 | `mocha` | 
| [googlevr/webvr-polyfill](https://github.com/googlevr/webvr-polyfill) | 957 | `mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 955 | `mocha --check-leaks --reporter spec --bail test/` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 946 | `NODE_PATH=. mocha **/*.spec.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 944 | `mocha --recursive --bail --reporter spec test` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 944 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 944 | `npm run rollup-cjs && mocha test/test.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 942 | `mocha -R list` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 942 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 938 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 934 | `mocha --recursive test/unit/` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 933 | `eslint . && mocha -t 5000` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 933 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 933 | `mocha $(find test -name '*.test.js')` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 929 | `standard && mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 922 | `mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 918 | `mocha --async-only` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 917 | `mocha --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 917 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 915 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 913 | `mocha tests/test-*` | 
| [tomas/needle](https://github.com/tomas/needle) | 910 | `mocha test` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 910 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 903 | `mocha ./test/index.js` | 
| [dabeng/OrgChart](https://github.com/dabeng/OrgChart) | 903 | `mocha ./test/**/*-tests.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 901 | `mocha spec/*.spec.js` | 
| [router5/router5](https://github.com/router5/router5) | 898 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 896 | ` NODE_ENV=test mocha --compilers js:babel-register` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 895 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 892 | `./node_modules/.bin/mocha --globals angular,require` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 886 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 884 | `mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 884 | `mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 883 | `standard && mocha -b` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 879 | `mocha -t 120000 test/*.test.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 878 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 878 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 874 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 874 | `mocha test` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 871 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 870 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 868 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 867 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 866 | `webpack && mocha test/unit` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 865 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 865 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 864 | `mocha --reporter list` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 860 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 856 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 855 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 852 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 851 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 847 | `nyc mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 844 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 844 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [teambit/bit](https://github.com/teambit/bit) | 844 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 843 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 842 | `mocha --recursive test` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 842 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 840 | `mocha "client.test" --compilers js:babel-register` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 837 | `node_modules/.bin/mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 836 | `mocha --reporter spec --bail --check-leaks test/` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 832 | `eslint test && mocha --compilers js:babel/register` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 827 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 825 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 825 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 824 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 823 | `mocha --compilers js:babel-register test/*.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 821 | `npm run lint && mocha -R spec` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 821 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 820 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 819 | `mocha && standard` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 818 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 816 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 816 | `mocha --timeout 200000` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 815 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 811 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 809 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 809 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 807 | `mocha && ember test` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 804 | `mocha tests/*.test.js --reporter spec` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 803 | `mocha --reporter spec` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 802 | `node_modules/.bin/mocha test/spec` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 802 | `nyc mocha --timeout=20000 test.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 800 | `mocha --reporter spec --bail --check-leaks test/` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 797 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 796 | `mocha` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 796 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 793 | `mocha tests` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 792 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 789 | `mocha --check-leaks -t 20000` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 788 | `mocha -R spec tests/` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 785 | `npm run convertto:es5 && npm run mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 783 | `mocha -u tdd` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 782 | `mocha --require babel-register` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 778 | `istanbul cover _mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 777 | `mocha` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 776 | `nyc mocha --require babel-register` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 775 | `cake build && mocha ./test/mocha/*.coffee` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 771 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 770 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 770 | `mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 769 | `nyc mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 769 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 768 | `mocha ./test -R spec` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 763 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 762 | `standard && standard ./bin/* && mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 760 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 759 | `mocha --colors --reporter spec test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 759 | `mocha -t 5000` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 758 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 758 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 755 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 754 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 754 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 752 | `mocha` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 751 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 749 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 748 | `npm run lint && mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 745 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 745 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 742 | `mocha ./test/test*.js --reporter spec` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 742 | `mocha test --compilers js:babel-register` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 739 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 738 | `xo && mocha -R spec` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 738 | `istanbul cover -- _mocha --reporter spec` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 735 | `mocha --async-only` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 732 | `nyc mocha specs` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 731 | `mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 730 | `mocha -R spec src/**/*_test.js` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 728 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 728 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 727 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 727 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 725 | `mocha --reporter spec` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 722 | `mocha -t 600000` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 721 | `mocha -R spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 721 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 719 | `mocha --ui tdd --require ./test/__setup` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 718 | `mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 716 | `mocha --reporter list` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 716 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 715 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 715 | `npm run lint && mocha --compilers js:babel-register` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 713 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 710 | `mocha spec/*.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 709 | `TEST_MODE=unit NODE_ENV=test jest && TEST_MODE=unit NODE_ENV=test mocha -R ${MOCHA_REPORTER:-spec}` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 707 | `mocha test.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 704 | `mocha -R spec --compilers js:babel-core/register ./tests/setup.js ./tests/** --recursive` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 704 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 702 | `./node_modules/.bin/mocha -R spec` | 
| [contra/gulp-concat](https://github.com/contra/gulp-concat) | 696 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 695 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 694 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 693 | `npm run bundle && mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 684 | `cross-env NODE_ENV=test nyc mocha` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 681 | `npm run lint && mocha test` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 680 | `mocha tests/*.mocha.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 679 | `npm run lint && nyc mocha test/**` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 679 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 678 | `mocha ./test/index.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 674 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 674 | `npm run mocha-test test/integration` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 672 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 672 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 670 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 670 | `mocha -b -R spec test/*` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 670 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 666 | `mocha tests/*.js` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 664 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 664 | `npm run build && istanbul test _mocha test/test.js` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 663 | `mocha --reporter spec` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 663 | `mocha test` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 663 | `mocha --reporter spec` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 662 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 662 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 662 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 660 | `mocha test` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 655 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 653 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 653 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 653 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require babel-register --no-timeouts` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 651 | `./node_modules/.bin/mocha test/integration` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 648 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 648 | `eslint src test && mocha --compilers babel-register` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 645 | `npm run lint && mocha ./test/test.js --timeout 1000000` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 644 | `mocha` | 