# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:18 05/29/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 41758 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40602 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38511 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29554 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24046 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23293 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 22575 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22259 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 18887 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18361 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16269 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15834 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14306 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14115 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13430 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12711 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12452 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12275 | `./node_modules/.bin/mocha test/` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 12163 | `mocha --reporter spec` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12142 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12068 | `mocha --reporter spec test/*-test.js` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11766 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11104 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10946 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10484 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10355 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9942 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9690 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9689 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9652 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9626 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9149 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 8885 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8829 | `grunt mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 8764 | `mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8754 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 8682 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8367 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8361 | `mocha test/test.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8311 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8293 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8216 | `grunt clean:test && mocha --exit` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8193 | `mocha test/src` | 
| [amark/gun](https://github.com/amark/gun) | 8137 | `mocha` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8010 | `mocha --compilers js:babel-register test/test.js` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7964 | `mocha tests/*.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7926 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7735 | `npm run eslint && npm run mocha` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7686 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7575 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7536 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7514 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7477 | `./node_modules/.bin/mocha test` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7437 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7327 | `npm run build && istanbul cover _mocha` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 7131 | `nyc mocha test/**/* -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7041 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6982 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6852 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 6838 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6829 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6774 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6762 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6675 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6552 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6264 | `npm run lint -s && npm run mocha -s` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6122 | `npm run jshint && mocha test/` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6112 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6100 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 6036 | `npm run build-cli && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6028 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5937 | `mocha` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5841 | `mocha test node-test --recursive` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5824 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5822 | `mocha --exit --require babel-core/register` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5808 | `mocha test/test.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5711 | `mocha tests/node.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5591 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5585 | `mocha && eslint lib/**` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5585 | `mocha; jshint *.js lib` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5504 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5406 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5357 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5285 | `mocha` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5273 | `mocha --timeout 10000 && npm run lint` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5218 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5154 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5154 | `mocha src/**/*Tests.js --harmony` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5040 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4925 | `standard && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4917 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4893 | `gulp lint && mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4865 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4814 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4719 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4693 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4674 | `mocha --reporter spec -t 8000` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4655 | `mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4643 | `gulp build; mocha;` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4582 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4580 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4554 | `mocha ./test/runner.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4489 | `./node_modules/.bin/mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4475 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4470 | `mocha test` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4414 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4347 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4321 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4320 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4220 | `mocha -R spec ./test --recursive` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4193 | `NODE_ENV=test mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4189 | `mocha --recursive && make test` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3889 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3872 | `export TESTING=true; mocha --reporter list` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3855 | `npm run lint ; mocha && mocha test/individual` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3822 | `npm run lint && npm run mocha` | 
| [erming/shout](https://github.com/erming/shout) | 3802 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3779 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3766 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3762 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3694 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3661 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3617 | `standard && mocha --timeout 60000 test/test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3581 | `npm run build && mocha test/*.test.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3581 | `mocha --check-leaks --reporter spec --bail` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3559 | `mocha tests/javascript` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3533 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3499 | `mocha --reporter spec --timeout 3000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3478 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3461 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3432 | `nyc mocha "test/**/*.test.js"` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3428 | `node_modules/.bin/mocha test/lib/` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3423 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3419 | `mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3414 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3383 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3348 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3329 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3309 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3254 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3254 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3125 | `node_modules/.bin/mocha test/tests.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3114 | `mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3111 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3108 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3073 | `mocha` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 3071 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3066 | `nyc mocha && tsc` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3031 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3015 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3014 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3031 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3015 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3014 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3003 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2985 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2978 | `NODE_ENV=test mocha --exit` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2974 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2949 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2925 | `mocha test/index.js && npm run demo` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2915 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2914 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2884 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2882 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2864 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2853 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2842 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2841 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2835 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2835 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2832 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2801 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2789 | `istanbul cover _mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2776 | `mocha --require should --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2767 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2760 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2753 | `mocha --opts mocha.opts` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2749 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2735 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2726 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2722 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2720 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2717 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2709 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2695 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [tj/should.js](https://github.com/tj/should.js) | 2693 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2689 | `npm run mocha && npm run lint` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2677 | `xo && mocha` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2676 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2668 | `export TESTING=true; mocha --reporter list` | 
| [css/csso](https://github.com/css/csso) | 2667 | `mocha --reporter dot` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2658 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2648 | `mocha --require babel-register --recursive spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2647 | `mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2621 | `mocha --timeout 100000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2602 | `mocha-phantomjs ./test/index.html` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2588 | `mocha --recursive --watch` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2579 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2576 | `node_modules/.bin/mocha --reporter spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2552 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2539 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2529 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2527 | `export TESTING=true; mocha --reporter list` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2525 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2518 | `mocha -R landing test/index` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2497 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2477 | `npm run build && cd test && mocha . --reporter dot` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2457 | `mocha --reporter=spec test/*-test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2440 | `nyc mocha` | 
| [json5/json5](https://github.com/json5/json5) | 2439 | `nyc --reporter=html --reporter=text mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2426 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2402 | `mocha test` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2396 | `mocha "test/**/*-test.js"` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2386 | `mocha test/src/**/*.unit.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2382 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2375 | `mocha test.js` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2340 | `mocha --no-colors --reporter spec` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2339 | `mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2338 | `grunt jshint && mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2319 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2291 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2287 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2282 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2255 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2246 | `mocha -R spec` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2242 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2237 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2224 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2207 | `nyc --reporter=html --reporter=text mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2237 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2224 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2207 | `nyc --reporter=html --reporter=text mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2190 | `mocha --compilers js:babel-register` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2165 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2150 | `mocha test && npm run lint` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2142 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2139 | `mocha && eslint .` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1971 | `mocha test/ --no-timeouts` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1957 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1955 | `mocha -c test/index.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1951 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1949 | `mocha --require=test/test_helper.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1929 | `mocha test/index.js --reporter dot` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1920 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1914 | `mocha --bail --reporter spec --check-leaks test/` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1912 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1911 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1972 | `mocha test/runner.js --reporter spec` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1971 | `mocha test/ --no-timeouts` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1957 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1955 | `mocha -c test/index.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1951 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1949 | `mocha --require=test/test_helper.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1929 | `mocha test/index.js --reporter dot` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1920 | `mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1916 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1914 | `mocha --bail --reporter spec --check-leaks test/` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1912 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1911 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1903 | `mocha --reporter spec --timeout 5000` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1898 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1888 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1883 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1880 | `mocha --require ./test/common --growl test/expect.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1870 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [teambit/bit](https://github.com/teambit/bit) | 1870 | `mocha --require babel-core/register './specs/**/*.spec.js'` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1868 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1866 | `mocha tests.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1859 | `nyc npm run _mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1854 | `mocha && eslint *.js` | 
| [then/promise](https://github.com/then/promise) | 1850 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [share/sharedb](https://github.com/share/sharedb) | 1846 | `./node_modules/.bin/mocha && npm run jshint` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1842 | `npm run lint && mocha -R dot && npm run cover` | 
| [kach/nearley](https://github.com/kach/nearley) | 1833 | `mocha test/*.test.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1752 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1719 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1716 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1714 | `mocha && npm run lint` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1701 | `mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1698 | `mocha --reporter spec test/*.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1691 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1684 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1675 | `xo && mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1660 | `mocha test/**/*.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1650 | `mocha test -u bdd -R spec` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1645 | `npm run lint && mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1644 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1635 | `mocha test --timeout 600000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1629 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1620 | `mocha tests/test.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1619 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [pahen/madge](https://github.com/pahen/madge) | 1729 | `npm run lint && npm run mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1719 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1719 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1716 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1714 | `mocha && npm run lint` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1701 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1701 | `npm run lint && npm run mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1701 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1698 | `mocha --reporter spec test/*.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1697 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1694 | `mocha --reporter spec --grep .` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1693 | `mocha tests --compilers js:babel-core/register` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1691 | `./node_modules/.bin/mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1691 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1686 | `mocha` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1684 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1635 | `mocha test --timeout 600000` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1634 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1633 | `mocha ./test/basic.js -t 5000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1629 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1627 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1620 | `mocha tests/test.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1619 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1613 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1609 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1608 | `mocha && size-limit` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1600 | `mocha --compilers js:babel-register` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1589 | `mocha test/* --reporter spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1588 | `mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1586 | `npm run lint && npm run mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1608 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1608 | `mocha && size-limit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1600 | `mocha --compilers js:babel-register` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1589 | `mocha test/* --reporter spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1588 | `mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1586 | `npm run lint && npm run mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1564 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1551 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1511 | `mocha --reporter spec` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1511 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1500 | `npm run test:lint && npm run test:mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1493 | `eslint --cache . && tsc && mocha` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1487 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1482 | `mocha -u tdd` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1478 | `node_modules/.bin/mocha --recursive` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1478 | `mocha --check-leaks -R dot` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1473 | `standard "./src/*.js" && mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1471 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1470 | `mocha -R spec` | 
| [zeit/ms](https://github.com/zeit/ms) | 1469 | `mocha tests.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1462 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1461 | `nyc mocha` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1487 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1482 | `mocha -u tdd` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1478 | `node_modules/.bin/mocha --recursive` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1478 | `mocha --check-leaks -R dot` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1473 | `standard "./src/*.js" && mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1471 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1470 | `mocha -R spec` | 
| [zeit/ms](https://github.com/zeit/ms) | 1469 | `mocha tests.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1462 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1461 | `nyc mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1459 | `mocha test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1457 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1457 | `mocha test/setup.js test/spec/*.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1457 | `mocha test/**/*.spec.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1450 | `mocha test/tests.js --timeout=10000` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1444 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1439 | `mocha --check-leaks --reporter spec --bail` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1436 | `mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1434 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1432 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1426 | `mocha --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1421 | `nyc npm run mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1416 | `mocha test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1395 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1384 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1358 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1353 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1351 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1348 | `cross-env NODE_ENV=test nyc mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1343 | `mocha -R spec test/*.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1334 | `mocha test` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1326 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1324 | `npm run build && mocha -r should` | 
| [electron/devtron](https://github.com/electron/devtron) | 1317 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [electron/devtron](https://github.com/electron/devtron) | 1317 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1308 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1307 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1298 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1298 | `mocha-phantomjs tests/index.html` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1295 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1285 | `./node_modules/.bin/mocha test` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1283 | `mocha --check-leaks --require @babel/register` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1280 | `istanbul cover _mocha test -- --timeout 20000` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1279 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1277 | `nyc mocha --timeout=20000 test.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1276 | `mocha --recursive` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1275 | `mocha spec/exec.js` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1273 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1264 | `mocha --opts test/opts/mocha.opts` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1261 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1259 | `mocha test/unit` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1258 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1248 | `mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1244 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1243 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1240 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1239 | `mocha test/*.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1239 | `eslint src && mocha && karma start --single-run` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1235 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1232 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1228 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1227 | `mocha tests` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1222 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1221 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1221 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1221 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1219 | `mocha --reporter dot` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1218 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1216 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1210 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1207 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1205 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1201 | `mocha test/**/*Spec.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1198 | `mocha tests/test-*` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1188 | `node ./node_modules/mocha/bin/mocha tests` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1187 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1187 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1186 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1185 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1185 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1183 | `mocha test` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1179 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1176 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1175 | `mocha src/test.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1169 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1166 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1166 | `mocha --reporter spec` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1160 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [variety/variety](https://github.com/variety/variety) | 1158 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1157 | `npm run lint && npm run mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1153 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1149 | `mocha --check-leaks --reporter spec --bail test/` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1143 | `mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1139 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1135 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1134 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1130 | `mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1130 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1124 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1123 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1121 | `mocha -R spec ./test/unit/**` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1109 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1104 | `npm run prepublishOnly && mocha test/test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1103 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1101 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1101 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1100 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1099 | `NODE_ENV=test mocha tests/*.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1099 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1097 | `mocha $(find test -name '*.test.js')` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1096 | `TEST=all mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1095 | `mocha ./test/test*.js --reporter spec` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1095 | `mocha --recursive test` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1095 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1094 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1091 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1086 | `xo && mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1085 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1084 | `mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1084 | `mocha test/*` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1080 | `mocha --check-leaks -t 20000` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1079 | `nodeunit test; mocha test` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1079 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1078 | `NODE_PATH=. mocha **/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1076 | `istanbul cover _mocha test/*.js` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1074 | `npm run lint && npm run mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1072 | `mocha --compilers js:babel-register` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1070 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1068 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1064 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1054 | `mocha --compilers js:babel-core/register` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1052 | `istanbul test _mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1048 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1046 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1045 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1043 | `mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1041 | `mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1040 | `mocha --reporter spec --timeout 3000` | 
| [router5/router5](https://github.com/router5/router5) | 1040 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1036 | `webpack && npm run lint && npm run mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1034 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1033 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1032 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1031 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1031 | `mocha test/tests.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1028 | `mocha` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1025 | `standard && mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1025 | `mocha --recursive test/bin` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1021 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1021 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1020 | `mocha --recursive --bail --reporter spec test` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1018 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1014 | `mocha --check-leaks -R dot` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1010 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 987 | `mocha --recursive test/unit/` | 
| [tomas/needle](https://github.com/tomas/needle) | 984 | `mocha test` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 983 | `mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 983 | `standard && mocha -b` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 983 | `mocha --reporter spec --bail --check-leaks test/` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 979 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 976 | `mocha --async-only` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 976 | `npm run lint && mocha --require @babel/register` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 975 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 973 | `mocha && standard` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 968 | `mocha -R list` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 962 | `eslint src test && mocha --compilers babel-register` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 960 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 960 | `mocha --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 958 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 976 | `mocha --async-only` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 976 | `npm run lint && mocha --require @babel/register` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 975 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 973 | `mocha && standard` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 968 | `mocha -R list` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 962 | `eslint src test && mocha --compilers babel-register` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 960 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 960 | `mocha --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 958 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 952 | `mocha --timeout 20000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 951 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 951 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 923 | `mocha "client.test" --compilers js:babel-register` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 921 | `npm run convertto:es5 && npm run mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 917 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 915 | `mocha` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 911 | `npm-run-all test:jest test:server:mocha` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 908 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 906 | `mocha --compilers js:babel-register test/*.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 901 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 898 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 891 | `mocha -R spec` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 891 | `./node_modules/.bin/mocha --globals angular,require` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 888 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 884 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 879 | `mocha tests` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 879 | `mocha tests` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 868 | `node_modules/.bin/mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 868 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 866 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 864 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 862 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 861 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 859 | `npm run lint && npm run mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 859 | `mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 858 | `mocha --timeout 200000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 858 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 857 | `mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 856 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 855 | `mocha -t 600000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 850 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 850 | `eslint test && mocha --compilers js:babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 849 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 844 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 838 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 835 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 834 | `mocha -t 5000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 833 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 833 | `mocha --check-leaks -t 20000` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 830 | `mocha --reporter spec` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 830 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 830 | `standard && standard ./bin/* && mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 828 | `istanbul cover _mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 827 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 826 | `mocha spec/*.js` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 825 | `mocha test --compilers js:babel-register` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 824 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 823 | `nyc mocha specs` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 822 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 821 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 821 | `mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 820 | `istanbul cover -- _mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 819 | `./node_modules/.bin/mocha -R spec` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 818 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 815 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 813 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 807 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 806 | `mocha test --compilers js:babel-core/register` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 805 | `nyc mocha` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 804 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 803 | `mocha --reporter list` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 801 | `mocha --require babel-register` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 800 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 799 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 797 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 795 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 793 | `cake build && mocha ./test/mocha/*.coffee` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 789 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 788 | `./node_modules/.bin/mocha --reporter spec` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 787 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 785 | `mocha --async-only` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 783 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 781 | `mocha --colors --reporter spec test.js` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 765 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 763 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 763 | `mocha --timeout 30000 --recursive ./tests` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 761 | `npm run mocha-test test/integration` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 758 | `mocha --ui tdd --require ./test/__setup` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 757 | `nyc --check-coverage mocha test/*.test.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 757 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 756 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 756 | `mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 756 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 755 | `mocha test` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 754 | `mocha -R spec src/**/*_test.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 753 | `mocha --harmony --full-trace --check-leaks` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 752 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 749 | `mocha --recursive ./test/*_spec.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 748 | `npm run build && istanbul test _mocha test/test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 748 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 761 | `npm run mocha-test test/integration` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 759 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 758 | `mocha --ui tdd --require ./test/__setup` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 757 | `nyc --check-coverage mocha test/*.test.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 757 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 756 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 756 | `mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 756 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 755 | `mocha test` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 754 | `mocha -R spec src/**/*_test.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 753 | `mocha --harmony --full-trace --check-leaks` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 752 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 749 | `mocha --recursive ./test/*_spec.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 748 | `npm run build && istanbul test _mocha test/test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 748 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 748 | `mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 747 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 744 | `mocha --recursive -s 15 test/` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 744 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 743 | `mocha test/index.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 741 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 740 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [developit/decko](https://github.com/developit/decko) | 738 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 738 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 736 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 735 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 733 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 731 | `mocha test` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 731 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 731 | `mocha --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 730 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 729 | `mocha test` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 725 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 724 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 724 | `mocha test.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 724 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 722 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 720 | `mocha tests/*.mocha.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 720 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 717 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 713 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 713 | `npm run lint && npm run mocha` | 