# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:22 12/22/17 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39362 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 38027 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 35716 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 35157 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28234 | `mocha --reporter spec` | 
| [caolan/async](https://github.com/caolan/async) | 22958 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 19756 | `mocha test/index.js` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17031 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [developit/preact](https://github.com/developit/preact) | 16829 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15195 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14272 | `mocha test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13604 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12392 | `node_modules/.bin/mocha test/*.*.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 12361 | `cross-env NODE_ENV=test mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12282 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11912 | `mocha` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 11697 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11627 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11522 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11311 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 10507 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10415 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10295 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 9848 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9568 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9253 | `mocha --reporter spec` | 
| [tj/co](https://github.com/tj/co) | 9122 | `mocha --harmony` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9057 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 8931 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tmpvar/jsdom](https://github.com/tmpvar/jsdom) | 8910 | `mocha test/index.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 8852 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8709 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [svg/svgo](https://github.com/svg/svgo) | 8678 | `set NODE_ENV=test && mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8381 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8146 | `mocha test/*-test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8102 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8029 | `grunt clean:test && mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 7990 | `mocha test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7641 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7588 | `./node_modules/.bin/mocha test/src` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7538 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7426 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7406 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7330 | `mocha --compilers js:babel-register test/test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7295 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7185 | `npm run eslint && npm run mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 7063 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7058 | `npm run build && istanbul cover _mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 6949 | `./node_modules/.bin/mocha test` | 
| [amark/gun](https://github.com/amark/gun) | 6943 | `mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 6897 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 6882 | `mocha tests/*.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6452 | `mocha $HARMONY_OPTS` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6415 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6393 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6313 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6215 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6194 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6099 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [almende/vis](https://github.com/almende/vis) | 6031 | `mocha --compilers js:babel-core/register` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 5967 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5933 | `mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 5845 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 5839 | `nyc mocha test/** -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 5689 | `mocha --opts mocha.opts` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5674 | `npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5673 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 5576 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5569 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5464 | `npm run jshint && mocha test/` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5389 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5389 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5374 | `mocha tests/node.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5270 | `mocha && eslint lib/**` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5257 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5224 | `mocha test --recursive` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5165 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5162 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5116 | `mocha src/**/*Tests.js --harmony` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5086 | `mocha test/test.js` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 4972 | `mocha --timeout 10000 && npm run lint` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4814 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4780 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4727 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4680 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 4659 | `mocha --compilers js:babel-core/register` | 
| [santinic/how2](https://github.com/santinic/how2) | 4606 | `mocha test` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4568 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4568 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4565 | `mocha --reporter spec -t 8000` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4510 | `mocha ./test/runner.js` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4366 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4352 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4348 | `gulp build; mocha;` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4330 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4299 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4258 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4246 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4228 | `./node_modules/.bin/mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4224 | `mocha -R spec ./test --recursive` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4179 | `standard && mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4104 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4084 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4050 | `mocha` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 3989 | `mocha && ./bin/shipit staging test` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 3984 | `mocha test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3940 | `nyc mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 3909 | `mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3892 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 3852 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3826 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3812 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [tj/ejs](https://github.com/tj/ejs) | 3701 | `mocha --require should --reporter spec` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3663 | `mocha --recursive && make test` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3632 | `npm run jshint && npm run mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3614 | `NODE_ENV=test mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3551 | `mocha --require test/babel-hook test/*.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3545 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3545 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3537 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3532 | `standard && mocha --timeout 60000 test/test.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3515 | `npm run lint && npm run mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3499 | `mocha tests/javascript` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 3439 | `npm run build-cli && mocha` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3437 | `npm run lint ; mocha && mocha test/individual` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3414 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3414 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [primus/primus](https://github.com/primus/primus) | 3398 | `npm run build && mocha test/*.test.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3382 | `nyc mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3379 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3376 | `mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3337 | `node_modules/.bin/mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3303 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3282 | `npm run lint && mocha && EIO_WS_ENGINE=ws mocha` | 
| [easy-mock/easy-mock](https://github.com/easy-mock/easy-mock) | 3126 | `cross-env NODE_ENV=test istanbul cover _mocha test/*` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3085 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3079 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3057 | `mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3050 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3041 | `mocha --check-leaks --reporter spec --bail` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3041 | `./node_modules/.bin/mocha test/test.*.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3036 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3014 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3002 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 2967 | `node_modules/.bin/mocha test/tests.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2944 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 2942 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 2919 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [expressjs/session](https://github.com/expressjs/session) | 2901 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2893 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 2884 | `nyc mocha "test/**/*.test.js"` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2875 | `mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 2854 | `npm run lint && npm run mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 2833 | `mocha; jshint *.js lib` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2824 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2813 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2777 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2752 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2752 | `mocha --require should --reporter spec` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2734 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2733 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2705 | `mocha -R spec --recursive src/test` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2688 | `mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 2688 | `yarn run build:cjs && mocha --require babel-core/register ./test/index.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2681 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2680 | `istanbul cover _mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2635 | `mocha test/index.js && npm run demo` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2629 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2611 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2588 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2585 | `xo && mocha` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2584 | `mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2581 | `mocha --timeout 100000` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2576 | `nyc mocha && tsc` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2567 | `mocha-phantomjs ./test/index.html` | 
| [github-tools/github](https://github.com/github-tools/github) | 2563 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2540 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2520 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2518 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2517 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2516 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2510 | `mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2502 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [css/csso](https://github.com/css/csso) | 2496 | `mocha --reporter dot` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2490 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2482 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2478 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2472 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2462 | `mocha --recursive --watch` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2461 | `npm run mocha && npm run lint` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2459 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2453 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2424 | `mocha --opts mocha.opts` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2421 | `mocha --compilers js:babel-register --recursive spec` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2421 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2415 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2397 | `mocha --reporter=spec test/*-test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2382 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2380 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2379 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2366 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2363 | `node node_modules/mocha/bin/_mocha` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2331 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2322 | `mocha --no-colors --reporter spec` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2314 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2312 | `grunt jshint && mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2308 | `mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2296 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2293 | `npm run compile && mocha --compilers js:babel-core/register` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2292 | `mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2283 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2248 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2237 | `mocha test/src/**/*.unit.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2231 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2220 | `mocha test` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2218 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2217 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2211 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2207 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2200 | `mocha test test/unit/**/*_test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2192 | `gulp && cd test && mocha . --reporter dot` | 
| [octokit/node-github](https://github.com/octokit/node-github) | 2172 | `nyc mocha test/**/*-test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2169 | `NODE_ENV=test mocha` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2149 | `node_modules/.bin/mocha --reporter spec` | 
| [mozilla/send](https://github.com/mozilla/send) | 2130 | `mocha test/unit` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2121 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2111 | `npm run lint && npm run build && npm run mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2108 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2098 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [gajus/swing](https://github.com/gajus/swing) | 2096 | `mocha --compilers js:babel-register` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2095 | `mocha -R spec` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2092 | `mocha test/unit --require mochahook` | 
| [json5/json5](https://github.com/json5/json5) | 2079 | `mocha --ui exports --reporter spec` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2072 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2033 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [slate/slate](https://github.com/slate/slate) | 2024 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2019 | `mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2019 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2008 | `cross-env BABEL_ENV=test mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 1992 | `mocha --require should --reporter spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 1960 | `nyc --reporter=html --reporter=text mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 1949 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1915 | `mocha --require=test/test_helper.js` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1909 | `mocha -R spec test/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1897 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1867 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1864 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1848 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1848 | `mocha test/index.js --reporter dot` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1842 | `mocha` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 1833 | `mocha ./test/*.spec.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1830 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1821 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1820 | `mocha tests.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 1817 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1809 | `mocha --timeout 5000` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1807 | `mocha --require ./test/common --growl test/expect.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1802 | `mocha test && npm run lint` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1791 | `mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 1791 | `mocha` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1787 | `mocha --reporter spec --timeout 5000` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1782 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1778 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1773 | `mocha -c test/index.js` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1761 | `cross-env NODE_ENV=test mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1759 | `mocha test.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1750 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1737 | `mocha test/**/*_test.js --bail` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1736 | `mocha test` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1729 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1724 | `mocha -R landing test/index` | 
| [then/promise](https://github.com/then/promise) | 1718 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1715 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1714 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1712 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1706 | `mocha test/runner.js --reporter spec` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1702 | `mocha --compilers js:babel-register` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1695 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1694 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1679 | `mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1679 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1677 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1676 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1673 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1672 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1671 | `xo && mocha` | 
| [verdaccio/verdaccio](https://github.com/verdaccio/verdaccio) | 1666 | `mocha ./test/functional ./test/unit --reporter=spec --full-trace` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1657 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1656 | `mocha test` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1654 | `mocha` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1652 | `npm run lint && npm run compile && mocha --reporter spec test/*.js` | 
| [Hardmath123/nearley](https://github.com/Hardmath123/nearley) | 1652 | `mocha test/*.test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1651 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1647 | `./node_modules/.bin/mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1636 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1629 | `mocha` | 
| [KunalKapadia/express-mongoose-es6-rest-api](https://github.com/KunalKapadia/express-mongoose-es6-rest-api) | 1628 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1619 | `mocha && eslint *.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1613 | `mocha -R spec spec spec/reporters` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1611 | `mocha --reporter spec && npm run test-typescript` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1607 | `lint && mocha --recursive` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1605 | `npm run lint && npm run mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1603 | `mocha tests/test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1599 | `mocha --expose-gc --slow 300` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1599 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1591 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1578 | `./node_modules/mocha/bin/mocha -R spec` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1574 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1574 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1555 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1553 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1548 | `mocha test/*.js` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1543 | `./node_modules/.bin/mocha` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1537 | `npm run mocha && npm run karma` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1523 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1522 | `npm run lint && mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1521 | `mocha && npm run lint` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1512 | `mocha --reporter spec --grep .` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1495 | `npm run lint && mocha -R dot && npm run cover` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1495 | `nyc npm run _mocha` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1492 | `mocha` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1489 | `npm run mocha && npm run lint` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1489 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1487 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1483 | `mocha tests --compilers js:babel-core/register` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1479 | `mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1463 | `mocha -R spec` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1462 | `mocha test -u bdd -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1460 | `mocha test/` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1460 | `mocha ./test/basic.js -t 5000` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1459 | `mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1459 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1456 | `mocha spec/` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1455 | `mocha test/* --reporter spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1454 | `mocha -u tdd` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1454 | `./node_modules/mocha/bin/mocha -R spec` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1446 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1440 | `node_modules/.bin/mocha --recursive` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1440 | `npm run lint && npm run mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 1438 | `npm run lint && npm run mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1434 | `npm run test:lint && npm run test:mocha && npm run site` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1431 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1428 | `mocha test/tests.js --timeout=10000` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1422 | `mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1405 | `mocha --reporter spec` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1401 | `mocha test.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1394 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1379 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1362 | `mocha --reporter spec test/*.js` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1359 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1357 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1353 | `nyc mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1352 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1347 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [share/sharedb](https://github.com/share/sharedb) | 1342 | `./node_modules/.bin/mocha && npm run jshint` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1340 | `./node_modules/mocha/bin/mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1329 | `mocha --check-leaks -R dot` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1326 | `standard "./src/*.js" && mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1325 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1325 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1322 | `eslint --rulesdir=dev-tools/eslint --cache . && tsc && mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1317 | `mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1314 | `cross-env NODE_ENV=test nyc mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1313 | `mocha --compilers js:babel-register` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1295 | `istanbul cover _mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1295 | `mocha test.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1294 | `mocha --recursive` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1285 | `standard "src/*.js" && npm run build && mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1275 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1259 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1253 | `npm run build && mocha -r should` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1247 | `mocha` | 
| [sandeepmistry/bleno](https://github.com/sandeepmistry/bleno) | 1231 | `mocha -R spec test/*.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1229 | `mocha --timeout 10000 ./tests/lib.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1226 | `./node_modules/.bin/mocha test` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1218 | `mocha --check-leaks --reporter spec --bail` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1217 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1215 | `mocha-phantomjs tests/index.html` | 
| [zeit/ms](https://github.com/zeit/ms) | 1210 | `mocha tests.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1209 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1209 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1206 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1201 | `mocha test/setup.js test/spec/*.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1196 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1196 | `mocha tests` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1195 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1193 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [reddit/reddit-mobile](https://github.com/reddit/reddit-mobile) | 1191 | `mocha test/index.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1189 | `mocha test/test.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1186 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1186 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1185 | `mocha` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1180 | `mocha test/*.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1177 | `mocha test/**/*Spec.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1173 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1170 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1168 | `mocha` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1167 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1166 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1165 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1163 | `mocha test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1163 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1161 | `istanbul cover _mocha test -- --timeout 20000` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1160 | `npm run lint && npm run mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1151 | `mocha compiled_tests/` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1150 | `mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1150 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1148 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1146 | `mocha --recursive` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1144 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1139 | `./node_modules/.bin/mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1137 | `mocha test --timeout 600000` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1136 | `node ./node_modules/mocha/bin/mocha tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1128 | `eslint lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1127 | `mocha --opts test/opts/mocha.opts` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1127 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1117 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1114 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [sorrycc/roadhog](https://github.com/sorrycc/roadhog) | 1113 | `npm run lint && npm run build && cross-env NODE_ENV=test nyc mocha --no-timeouts test/**/*-test.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1106 | `mocha --check-leaks --require @babel/register` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1106 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1100 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1092 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1091 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1088 | `node_modules/.bin/mocha && npm run lint` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1084 | `npm run lint && npm run mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1084 | `mocha --reporter spec` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [variety/variety](https://github.com/variety/variety) | 1077 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1072 | `mocha` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1069 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1066 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1065 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1058 | `mocha --check-leaks -t 20000` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1056 | `mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1055 | `mocha --compilers js:babel-register` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1052 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1051 | `mocha test/*` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1050 | `mocha --reporter spec --timeout 3000` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1044 | `mocha src/test.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1042 | `node_modules/.bin/mocha` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1042 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1039 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1035 | `mocha $(find test -name '*.test.js')` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1034 | `standard && istanbul cover _mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1025 | `xo && mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1023 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1022 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1022 | `istanbul test _mocha` | 
| [jas/playground](https://github.com/jas/playground) | 1021 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1020 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1018 | `mocha --reporter dot` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1018 | `mocha --check-leaks -R dot` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1015 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1015 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1005 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1003 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1000 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 999 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 995 | `eslint src && mocha && karma start --single-run` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 994 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 992 | `mocha test/unit` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 990 | `mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 982 | `mocha test/tests.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 981 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 981 | `mocha --colors ./test/*.spec.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 981 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 979 | `NODE_PATH=. mocha **/*.spec.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 974 | `mocha` | 
| [googlevr/webvr-polyfill](https://github.com/googlevr/webvr-polyfill) | 973 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 972 | `eslint . && mocha -t 5000` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 972 | `istanbul cover _mocha test/*.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 969 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 969 | `mocha --check-leaks --reporter spec --bail test/` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 963 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 959 | `mocha --timeout 5000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 951 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 946 | `mocha --recursive --bail --reporter spec test` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 946 | `mocha -R list` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 946 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 945 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 945 | `npm run rollup-cjs && mocha test/test.js` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 937 | `standard && mocha` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 937 | `mocha tests/test-*` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 936 | `mocha --recursive test/unit/` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 936 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 935 | `mocha $(find test -name '*.test.js')` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 931 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 928 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 922 | `mocha --async-only` | 
| [dabeng/OrgChart](https://github.com/dabeng/OrgChart) | 922 | `mocha ./test/**/*-tests.js` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 921 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 920 | `mocha --reporter spec` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 916 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 914 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [tomas/needle](https://github.com/tomas/needle) | 912 | `mocha test` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 904 | `mocha ./test/index.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 904 | ` NODE_ENV=test mocha --compilers js:babel-register` | 
| [router5/router5](https://github.com/router5/router5) | 904 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 902 | `mocha spec/*.spec.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 899 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 898 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 897 | `npm run prepublish && mocha test/test.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 894 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 893 | `mocha test` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 892 | `./node_modules/.bin/mocha --globals angular,require` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 888 | `mocha -t 120000 test/*.test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 887 | `mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 887 | `standard && mocha -b` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 878 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 874 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 874 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 874 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 873 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 872 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 871 | `webpack && mocha test/unit` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 867 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 867 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 866 | `mocha --reporter list` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 866 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 864 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 863 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 862 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 858 | `mocha --reporter spec --bail --check-leaks test/` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 857 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 856 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 852 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 851 | `mocha` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 850 | `mocha --recursive test` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 850 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 847 | `mocha "client.test" --compilers js:babel-register` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 842 | `mocha --reporter spec --bail --check-leaks test/` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 841 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 839 | `node_modules/.bin/mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 835 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 833 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 832 | `mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 831 | `mocha --compilers js:babel-register test/*.js` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 831 | `eslint test && mocha --compilers js:babel/register` | 
| [electron/spectron](https://github.com/electron/spectron) | 827 | `mocha && standard` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 826 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 825 | `mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 824 | `npm run lint && mocha -R spec` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 822 | `nyc mocha --timeout=20000 test.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 822 | `nyc mocha --timeout=20000 test.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 821 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [MaxCDN/bootstrap-cdn](https://github.com/MaxCDN/bootstrap-cdn) | 820 | `npm run lint && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 819 | `mocha --timeout 200000` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 819 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 817 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 815 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 812 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 811 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 811 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 809 | `mocha --reporter spec --bail --check-leaks test/` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 808 | `mocha --reporter spec` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 808 | `mocha && ember test` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 807 | `node_modules/.bin/mocha test/spec` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 806 | `mocha tests/*.test.js --reporter spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 804 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 803 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 800 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 797 | `mocha tests` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 791 | `nyc mocha --require babel-register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 790 | `mocha -R spec tests/` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 790 | `mocha --check-leaks -t 20000` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 789 | `npm run convertto:es5 && npm run mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 787 | `mocha -u tdd` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 784 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 784 | `mocha --require babel-register` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 783 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 779 | `istanbul cover _mocha` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 778 | `mocha ./test -R spec` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 776 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 775 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 772 | `mocha` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 771 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 771 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 771 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 770 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 770 | `mocha --reporter spec --bail --check-leaks test/` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 770 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 770 | `mocha ./test/test*.js --reporter spec` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 770 | `standard && standard ./bin/* && mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 767 | `mocha -t 5000` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 764 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [edsu/anon](https://github.com/edsu/anon) | 761 | `mocha --colors --reporter spec test.js` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 761 | `mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 756 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 755 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 755 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 753 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 750 | `mocha test --compilers js:babel-register` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 748 | `npm run lint && mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 748 | `istanbul cover -- _mocha --reporter spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 744 | `mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 743 | `TEST_MODE=unit NODE_ENV=test jest && TEST_MODE=unit NODE_ENV=test mocha -R ${MOCHA_REPORTER:-spec}` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 742 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 742 | `xo && mocha -R spec` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 741 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 740 | `nyc mocha specs` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 739 | `mocha --async-only` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 738 | `npm run lint && mocha --compilers js:babel-register` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 736 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 735 | `mocha -t 600000` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 734 | `mocha -R spec` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 732 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 732 | `mocha -R spec --compilers js:babel-core/register ./tests/setup.js ./tests/** --recursive` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 732 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 732 | `mocha -R spec src/**/*_test.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 731 | `mocha` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 727 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 726 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 726 | `mocha --reporter spec` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 723 | `mocha --ui tdd --require ./test/__setup` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 722 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 719 | `mocha --reporter list` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 718 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 717 | `mocha spec/*.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 712 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 709 | `./node_modules/.bin/mocha -R spec` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 708 | `mocha test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 708 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 705 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 702 | `mocha tests/*.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 699 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [contra/gulp-concat](https://github.com/contra/gulp-concat) | 699 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 696 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 693 | `npm run bundle && mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 693 | `cross-env NODE_ENV=test nyc mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 687 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 682 | `mocha tests/*.mocha.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 681 | `npm run mocha-test test/integration` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 679 | `npm run lint && mocha test` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 678 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require babel-register --no-timeouts` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 677 | `mocha ./test/index.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 676 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 676 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 675 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 673 | `npm run build && istanbul test _mocha test/test.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 671 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 670 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 670 | `mocha -b -R spec test/*` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 668 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 668 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 666 | `mocha test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 666 | `eslint src test && mocha --compilers babel-register` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 666 | `mocha test` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 665 | `mocha --reporter spec` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 663 | `mocha --reporter spec` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 663 | `mocha` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 662 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 659 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 658 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 657 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 655 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 653 | `mocha` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 653 | `mocha` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 652 | `./node_modules/.bin/mocha test/integration` | 