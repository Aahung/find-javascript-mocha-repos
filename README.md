# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:18 12/26/17 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39377 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 38091 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 35765 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 35243 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28258 | `mocha --reporter spec` | 
| [caolan/async](https://github.com/caolan/async) | 22982 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 19812 | `mocha test/index.js` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17059 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [developit/preact](https://github.com/developit/preact) | 16868 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15220 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14305 | `mocha test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13610 | `nyc --reporter=html --reporter=text mocha` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 13034 | `cross-env NODE_ENV=test mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12416 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12301 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11913 | `mocha` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 11716 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11650 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11528 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11336 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 10557 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10436 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10303 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 9874 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9593 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9265 | `mocha --reporter spec` | 
| [tj/co](https://github.com/tj/co) | 9132 | `mocha --harmony` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9075 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 8946 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tmpvar/jsdom](https://github.com/tmpvar/jsdom) | 8922 | `mocha test/index.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 8866 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8716 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [svg/svgo](https://github.com/svg/svgo) | 8705 | `set NODE_ENV=test && mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8391 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8167 | `mocha test/*-test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8106 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8031 | `grunt clean:test && mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 7998 | `mocha test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7644 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7601 | `./node_modules/.bin/mocha test/src` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7548 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7427 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7409 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7356 | `mocha --compilers js:babel-register test/test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7332 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7194 | `npm run eslint && npm run mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 7084 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7061 | `npm run build && istanbul cover _mocha` | 
| [amark/gun](https://github.com/amark/gun) | 6975 | `mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 6956 | `./node_modules/.bin/mocha test` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 6923 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 6905 | `mocha tests/*.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6455 | `mocha $HARMONY_OPTS` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6443 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6410 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6319 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6231 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6206 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6113 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [almende/vis](https://github.com/almende/vis) | 6047 | `mocha --compilers js:babel-core/register` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 5980 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5931 | `mocha` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 5866 | `nyc mocha test/** -r ./test/before` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 5866 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5755 | `npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 5716 | `mocha --opts mocha.opts` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5684 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 5608 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5590 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5477 | `npm run jshint && mocha test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5402 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5388 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5374 | `mocha tests/node.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5270 | `mocha && eslint lib/**` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5262 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5236 | `mocha test --recursive` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5176 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5163 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5117 | `mocha src/**/*Tests.js --harmony` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5103 | `mocha test/test.js` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 4985 | `mocha --timeout 10000 && npm run lint` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4823 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4793 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4730 | `gulp lint && mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 4681 | `mocha --compilers js:babel-core/register` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4680 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4605 | `mocha test` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4578 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4568 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4568 | `mocha --reporter spec -t 8000` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4510 | `mocha ./test/runner.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4370 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4367 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4350 | `gulp build; mocha;` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4342 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4303 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4269 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4250 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4234 | `./node_modules/.bin/mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4225 | `mocha -R spec ./test --recursive` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4195 | `standard && mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4110 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4107 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4062 | `mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 3995 | `mocha test` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 3992 | `mocha && ./bin/shipit staging test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3945 | `nyc mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 3928 | `mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3892 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 3868 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3830 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3812 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [tj/ejs](https://github.com/tj/ejs) | 3708 | `mocha --require should --reporter spec` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3673 | `mocha --recursive && make test` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3633 | `npm run jshint && npm run mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3630 | `NODE_ENV=test mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3569 | `mocha --require test/babel-hook test/*.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3546 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3544 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3542 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3534 | `standard && mocha --timeout 60000 test/test.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3523 | `npm run lint && npm run mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3503 | `mocha tests/javascript` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 3493 | `npm run build-cli && mocha` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3449 | `npm run lint ; mocha && mocha test/individual` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3416 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3415 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [primus/primus](https://github.com/primus/primus) | 3398 | `npm run build && mocha test/*.test.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3393 | `nyc mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3380 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3376 | `mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3338 | `node_modules/.bin/mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3320 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3285 | `npm run lint && mocha && EIO_WS_ENGINE=ws mocha` | 
| [easy-mock/easy-mock](https://github.com/easy-mock/easy-mock) | 3142 | `cross-env NODE_ENV=test istanbul cover _mocha test/*` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3087 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3079 | `mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3062 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3059 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3057 | `mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3054 | `mocha --check-leaks --reporter spec --bail` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3041 | `./node_modules/.bin/mocha test/test.*.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3018 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3014 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 2970 | `node_modules/.bin/mocha test/tests.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 2949 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2942 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 2939 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [expressjs/session](https://github.com/expressjs/session) | 2910 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 2909 | `mocha; jshint *.js lib` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 2893 | `nyc mocha "test/**/*.test.js"` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2893 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 2885 | `npm run lint && npm run mocha` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2878 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2828 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2823 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2781 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2757 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2752 | `mocha --require should --reporter spec` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2739 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2734 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 2717 | `yarn run build:cjs && mocha --require babel-core/register ./test/index.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2708 | `mocha -R spec --recursive src/test` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2688 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2687 | `istanbul cover _mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2682 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2642 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2638 | `mocha test/index.js && npm run demo` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2613 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2604 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2588 | `mocha` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2586 | `xo && mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2583 | `mocha --timeout 100000` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2582 | `nyc mocha && tsc` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2568 | `mocha-phantomjs ./test/index.html` | 
| [github-tools/github](https://github.com/github-tools/github) | 2566 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2546 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2543 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2528 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2526 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2519 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2517 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2511 | `mocha` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2502 | `export TESTING=true; mocha --reporter list` | 
| [css/csso](https://github.com/css/csso) | 2500 | `mocha --reporter dot` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2494 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2494 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2486 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2483 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2464 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2464 | `mocha --recursive --watch` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2463 | `npm run mocha && npm run lint` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2460 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2436 | `mocha --opts mocha.opts` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2429 | `mocha --compilers js:babel-register --recursive spec` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2428 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2419 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2398 | `mocha --reporter=spec test/*-test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2393 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2382 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2381 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2379 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2366 | `node node_modules/mocha/bin/_mocha` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2338 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2321 | `mocha --no-colors --reporter spec` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2319 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2319 | `mocha` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2314 | `npm run compile && mocha --compilers js:babel-core/register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2312 | `grunt jshint && mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2301 | `mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2299 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2285 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2249 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2237 | `mocha test/src/**/*.unit.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2236 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2229 | `mocha test` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2226 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2219 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2218 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2208 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2203 | `mocha test test/unit/**/*_test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2196 | `gulp && cd test && mocha . --reporter dot` | 
| [octokit/node-github](https://github.com/octokit/node-github) | 2181 | `nyc mocha test/**/*-test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2176 | `NODE_ENV=test mocha` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2161 | `node_modules/.bin/mocha --reporter spec` | 
| [mozilla/send](https://github.com/mozilla/send) | 2139 | `mocha test/unit` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2122 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2115 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2111 | `npm run lint && npm run build && npm run mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2100 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2099 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [gajus/swing](https://github.com/gajus/swing) | 2098 | `mocha --compilers js:babel-register` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2095 | `mocha -R spec` | 
| [json5/json5](https://github.com/json5/json5) | 2081 | `mocha --ui exports --reporter spec` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2074 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2037 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2027 | `mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2023 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2020 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2011 | `cross-env BABEL_ENV=test mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2001 | `mocha --require should --reporter spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 1968 | `nyc --reporter=html --reporter=text mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 1950 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1914 | `mocha --require=test/test_helper.js` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1910 | `mocha -R spec test/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1897 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1871 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1868 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1849 | `mocha test/index.js --reporter dot` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1848 | `mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1843 | `mocha` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 1838 | `mocha ./test/*.spec.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1831 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 1826 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1821 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1819 | `mocha tests.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1809 | `mocha --require ./test/common --growl test/expect.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1809 | `mocha --timeout 5000` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 1809 | `export TESTING=true; mocha --reporter list` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1806 | `mocha test && npm run lint` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1801 | `mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 1793 | `mocha` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1789 | `mocha --reporter spec --timeout 5000` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1785 | `mocha -c test/index.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1783 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1780 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1762 | `mocha test.js` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1761 | `cross-env NODE_ENV=test mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1739 | `mocha -R landing test/index` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1737 | `mocha test/**/*_test.js --bail` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1736 | `mocha test` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1732 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [then/promise](https://github.com/then/promise) | 1720 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1718 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1718 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1717 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1711 | `mocha test/runner.js --reporter spec` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1710 | `mocha --compilers js:babel-register` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1696 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1695 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1692 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1681 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1680 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1679 | `mocha --compilers js:babel-core/register __tests__` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1678 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1677 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [verdaccio/verdaccio](https://github.com/verdaccio/verdaccio) | 1674 | `mocha ./test/functional ./test/unit --reporter=spec --full-trace` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1672 | `xo && mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1663 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1661 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1657 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1655 | `npm run lint && npm run compile && mocha --reporter spec test/*.js` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1655 | `mocha` | 
| [Hardmath123/nearley](https://github.com/Hardmath123/nearley) | 1654 | `mocha test/*.test.js` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1647 | `./node_modules/.bin/mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1637 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1636 | `mocha` | 
| [KunalKapadia/express-mongoose-es6-rest-api](https://github.com/KunalKapadia/express-mongoose-es6-rest-api) | 1631 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1625 | `mocha && eslint *.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1614 | `mocha -R spec spec spec/reporters` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1613 | `mocha --reporter spec && npm run test-typescript` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1608 | `npm run lint && npm run mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1608 | `lint && mocha --recursive` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1603 | `mocha tests/test.js` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1603 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1600 | `mocha --expose-gc --slow 300` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1595 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1589 | `./node_modules/mocha/bin/mocha -R spec` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1576 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1575 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1563 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1554 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1549 | `mocha test/*.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1545 | `npm run mocha && npm run karma` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1544 | `./node_modules/.bin/mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1526 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1525 | `npm run lint && mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1523 | `mocha && npm run lint` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1522 | `npm run lint && mocha -R dot && npm run cover` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1515 | `mocha --reporter spec --grep .` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1497 | `nyc npm run _mocha` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1496 | `mocha` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1493 | `npm run mocha && npm run lint` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1489 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1488 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1484 | `mocha tests --compilers js:babel-core/register` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1482 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1466 | `mocha test -u bdd -R spec` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1463 | `mocha -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1462 | `mocha test/` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1462 | `mocha ./test/basic.js -t 5000` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1461 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1460 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1459 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1458 | `mocha spec/` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1456 | `./node_modules/mocha/bin/mocha -R spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1454 | `mocha -u tdd` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1447 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1444 | `npm run lint && npm run mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 1442 | `npm run lint && npm run mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1440 | `node_modules/.bin/mocha --recursive` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1435 | `npm run test:lint && npm run test:mocha && npm run site` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1432 | `mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1432 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1428 | `mocha test/tests.js --timeout=10000` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1409 | `mocha --reporter spec` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1402 | `mocha test.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1394 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1381 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1374 | `mocha --reporter spec test/*.js` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1362 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1357 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1354 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1353 | `nyc mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 1351 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1346 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1340 | `./node_modules/mocha/bin/mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1331 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1330 | `mocha --check-leaks -R dot` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1329 | `standard "./src/*.js" && mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1329 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1324 | `eslint --rulesdir=dev-tools/eslint --cache . && tsc && mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1319 | `mocha --compilers js:babel-register` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1317 | `mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1314 | `cross-env NODE_ENV=test nyc mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1299 | `mocha test.js` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1295 | `standard "src/*.js" && npm run build && mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1295 | `istanbul cover _mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1295 | `mocha --recursive` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1282 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1259 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1255 | `npm run build && mocha -r should` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1253 | `mocha` | 
| [sandeepmistry/bleno](https://github.com/sandeepmistry/bleno) | 1234 | `mocha -R spec test/*.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1230 | `mocha --timeout 10000 ./tests/lib.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1226 | `./node_modules/.bin/mocha test` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1223 | `mocha --check-leaks --reporter spec --bail` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1219 | `mocha spec/exec.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1217 | `mocha tests.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1214 | `mocha-phantomjs tests/index.html` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1212 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1209 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1209 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1204 | `mocha test/setup.js test/spec/*.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1201 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1199 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1196 | `mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1195 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1194 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [reddit/reddit-mobile](https://github.com/reddit/reddit-mobile) | 1192 | `mocha test/index.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1191 | `mocha test/test.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1188 | `mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1186 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1180 | `mocha test/*.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1179 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1177 | `mocha test/**/*Spec.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1174 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1174 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1171 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1169 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1168 | `npm run lint && npm run mocha` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1168 | `mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1167 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1166 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1164 | `istanbul cover _mocha test -- --timeout 20000` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1163 | `mocha test` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1156 | `mocha compiled_tests/` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1156 | `mocha compiled_tests/` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1156 | `mocha test --timeout 600000` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1153 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1151 | `mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1148 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1147 | `mocha --recursive` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1145 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1141 | `./node_modules/.bin/mocha` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1136 | `node ./node_modules/mocha/bin/mocha tests` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1131 | `mocha --opts test/opts/mocha.opts` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1128 | `eslint lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1128 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [sorrycc/roadhog](https://github.com/sorrycc/roadhog) | 1126 | `npm run lint && npm run build && cross-env NODE_ENV=test nyc mocha --no-timeouts test/**/*-test.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1119 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1116 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1108 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1107 | `mocha --check-leaks --require @babel/register` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1101 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1093 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1090 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1087 | `npm run lint && npm run mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1087 | `node_modules/.bin/mocha && npm run lint` | 
| [normalize/mz](https://github.com/normalize/mz) | 1084 | `mocha --reporter spec` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [variety/variety](https://github.com/variety/variety) | 1077 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1074 | `mocha` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1069 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1067 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1066 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1062 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1058 | `mocha --check-leaks -t 20000` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1057 | `mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1055 | `mocha --compilers js:babel-register` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1051 | `mocha test/*` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1050 | `mocha --reporter spec --timeout 3000` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1046 | `mocha src/test.js` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1044 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1042 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1042 | `node_modules/.bin/mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1036 | `mocha $(find test -name '*.test.js')` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1034 | `standard && istanbul cover _mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1027 | `xo && mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1025 | `mocha --reporter dot` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1025 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1024 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1024 | `istanbul test _mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1023 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1021 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1019 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1018 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1017 | `mocha --check-leaks -R dot` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1016 | `eslint . && mocha -t 5000` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1013 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1004 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1003 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1002 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1002 | `eslint src && mocha && karma start --single-run` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1001 | `mocha test/unit` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 997 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 991 | `mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 989 | `NODE_PATH=. mocha **/*.spec.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 985 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 984 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 982 | `mocha test/tests.js` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 981 | `mocha --colors ./test/*.spec.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 977 | `mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 976 | `istanbul cover _mocha test/*.js` | 
| [googlevr/webvr-polyfill](https://github.com/googlevr/webvr-polyfill) | 975 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 973 | `mocha --check-leaks --reporter spec --bail test/` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 972 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 964 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 959 | `mocha --timeout 5000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 953 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 950 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 947 | `mocha --recursive --bail --reporter spec test` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 946 | `mocha -R list` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 945 | `npm run rollup-cjs && mocha test/test.js` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 944 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 943 | `mocha tests/test-*` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 937 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 936 | `mocha --recursive test/unit/` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 936 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 936 | `standard && mocha` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 936 | `mocha $(find test -name '*.test.js')` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 933 | `mocha` | 
| [dabeng/OrgChart](https://github.com/dabeng/OrgChart) | 927 | `mocha ./test/**/*-tests.js` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 925 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 922 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 920 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 920 | `mocha --reporter spec` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 914 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [tomas/needle](https://github.com/tomas/needle) | 913 | `mocha test` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 912 | ` NODE_ENV=test mocha --compilers js:babel-register` | 
| [router5/router5](https://github.com/router5/router5) | 910 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 904 | `mocha ./test/index.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 903 | `npm run prepublish && mocha test/test.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 902 | `mocha spec/*.spec.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 901 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 900 | `mocha test` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 898 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 895 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 892 | `./node_modules/.bin/mocha --globals angular,require` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 891 | `mocha -t 120000 test/*.test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 890 | `mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 887 | `standard && mocha -b` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 878 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 878 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 877 | `mocha` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 877 | `webpack && mocha test/unit` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 875 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 874 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 873 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 872 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 869 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 868 | `nyc mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 867 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 867 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 866 | `mocha --reporter list` | 
| [electron/asar](https://github.com/electron/asar) | 864 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 864 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 858 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 857 | `mocha` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 854 | `mocha --recursive test` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 853 | `mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 853 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 852 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 849 | `mocha "client.test" --compilers js:babel-register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 842 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 842 | `mocha --reporter spec --bail --check-leaks test/` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 839 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 839 | `node_modules/.bin/mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 835 | `mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 833 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 832 | `mocha --compilers js:babel-register test/*.js` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 831 | `eslint test && mocha --compilers js:babel/register` | 
| [electron/spectron](https://github.com/electron/spectron) | 829 | `mocha && standard` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 828 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 828 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 825 | `nyc mocha --timeout=20000 test.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 825 | `mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 824 | `npm run lint && mocha -R spec` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 824 | `npm run lint && mocha -R spec` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [MaxCDN/bootstrap-cdn](https://github.com/MaxCDN/bootstrap-cdn) | 821 | `npm run lint && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 820 | `mocha --timeout 200000` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 820 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 817 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 815 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 814 | `mocha --reporter spec --bail --check-leaks test/` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 814 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 812 | `node_modules/.bin/mocha test/spec` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 812 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 811 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 809 | `mocha --reporter spec` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 808 | `mocha && ember test` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 806 | `mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 806 | `mocha tests/*.test.js --reporter spec` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 804 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 801 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 798 | `mocha tests` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 797 | `nyc mocha --require babel-register` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 792 | `mocha --check-leaks -t 20000` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 789 | `npm run convertto:es5 && npm run mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 789 | `mocha -R spec tests/` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 789 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 787 | `mocha -u tdd` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 785 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 784 | `mocha --require babel-register` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 781 | `mocha ./test -R spec` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 780 | `istanbul cover _mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 777 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 777 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [reactivestack/cookies](https://github.com/reactivestack/cookies) | 776 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 776 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 773 | `mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 772 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 772 | `standard && standard ./bin/* && mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 772 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 772 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 771 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 771 | `mocha ./test/test*.js --reporter spec` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 771 | `mocha -t 5000` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 770 | `nyc mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 767 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [edsu/anon](https://github.com/edsu/anon) | 762 | `mocha --colors --reporter spec test.js` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 762 | `mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 759 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 756 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 755 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 754 | `mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 753 | `istanbul cover -- _mocha --reporter spec` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 750 | `mocha test --compilers js:babel-register` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 748 | `npm run lint && mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 746 | `npm run lint && mocha --compilers js:babel-register` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 745 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 745 | `TEST_MODE=unit NODE_ENV=test jest && TEST_MODE=unit NODE_ENV=test mocha -R ${MOCHA_REPORTER:-spec}` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 744 | `mocha` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 743 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 742 | `nyc mocha specs` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 742 | `xo && mocha -R spec` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 741 | `mocha --async-only` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 740 | `mocha -R spec --compilers js:babel-core/register ./tests/setup.js ./tests/** --recursive` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 739 | `mocha -R spec` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 738 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 737 | `mocha -t 600000` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 734 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 733 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 732 | `mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 731 | `mocha -R spec src/**/*_test.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 727 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 726 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 726 | `mocha --ui tdd --require ./test/__setup` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 726 | `mocha --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 723 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 719 | `mocha --reporter list` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 718 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 718 | `mocha spec/*.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 712 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 712 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 710 | `./node_modules/.bin/mocha -R spec` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 709 | `mocha tests/*.js` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 708 | `mocha test.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 705 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 702 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 700 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [contra/gulp-concat](https://github.com/contra/gulp-concat) | 699 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 695 | `cross-env NODE_ENV=test nyc mocha` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 693 | `npm run bundle && mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 688 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 683 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require babel-register --no-timeouts` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 682 | `mocha tests/*.mocha.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 681 | `npm run mocha-test test/integration` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 680 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 679 | `npm run lint && mocha test` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 677 | `mocha ./test/index.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 677 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 677 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 676 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 676 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 673 | `npm run build && istanbul test _mocha test/test.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 672 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 670 | `eslint src test && mocha --compilers babel-register` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 670 | `mocha -b -R spec test/*` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 669 | `mocha test` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 668 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 668 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 667 | `mocha test` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 665 | `mocha --reporter spec` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 663 | `mocha --reporter spec` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 663 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 663 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 659 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 659 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 657 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 657 | `mocha` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 655 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 653 | `mocha` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 652 | `./node_modules/.bin/mocha test/integration` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 652 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 