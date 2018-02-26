# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:03 02/26/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39862 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 39484 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 37667 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation` | 
| [expressjs/express](https://github.com/expressjs/express) | 36821 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28846 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23432 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 22253 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 20803 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 19619 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 17829 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17570 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15615 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14934 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13821 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 13171 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12709 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12121 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12106 | `mocha 'test/**/*.spec.js'` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12012 | `mocha` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11728 | `./node_modules/.bin/mocha test/` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11715 | `mocha --reporter spec test/*-test.js` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 11380 | `cross-env BABEL_ENV=test NODE_ENV=test mocha --recursive --require babel-register --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11089 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10630 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 10563 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10010 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9705 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9561 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 9329 | `mocha --harmony` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9315 | `mocha test/index.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9282 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9145 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9077 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8896 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8561 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8402 | `mocha test/*-test.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8333 | `mocha` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8156 | `mocha --check-leaks -R dot` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8142 | `mocha test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8085 | `grunt clean:test && mocha --exit` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7988 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7862 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7826 | `./node_modules/.bin/mocha test/src` | 
| [websockets/ws](https://github.com/websockets/ws) | 7757 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7755 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7717 | `mocha --compilers js:babel-register test/test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7517 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7446 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [amark/gun](https://github.com/amark/gun) | 7443 | `mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7438 | `mocha` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7360 | `npm run eslint && npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7290 | `mocha tests/*.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7172 | `npm run build && istanbul cover _mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7136 | `./node_modules/.bin/mocha test` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6936 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6904 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6666 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6559 | `mocha $HARMONY_OPTS` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6511 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6446 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6397 | `mocha --opts mocha.opts` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6384 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6377 | `nyc mocha test/**/* -r ./test/before` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6306 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [almende/vis](https://github.com/almende/vis) | 6288 | `mocha --compilers js:babel-core/register` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6285 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 6224 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5956 | `npm run jshint -s && npm run mocha -s` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5924 | `mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5848 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5816 | `npm run test:mocha:src` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5790 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5712 | `npm run jshint && mocha test/` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5559 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5499 | `mocha tests/node.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5469 | `mocha test --recursive` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5388 | `mocha && eslint lib/**` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5387 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5357 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5348 | `mocha test/test.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5159 | `mocha --color` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5141 | `mocha --exit --require babel-core/register` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5137 | `mocha src/**/*Tests.js --harmony` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5129 | `mocha --timeout 10000 && npm run lint` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4997 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 4852 | `mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4779 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4741 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4724 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4718 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 4716 | `npm run build-cli && mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4626 | `mocha test` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4617 | `mocha --reporter spec -t 8000` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4609 | `mocha -R spec 'tests/app'` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4605 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4536 | `mocha ./test/runner.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4489 | `gulp build; mocha;` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4480 | `standard && mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4415 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4399 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4391 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4366 | `mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4346 | `./node_modules/.bin/mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4314 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4296 | `mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4222 | `mocha -R spec ./test --recursive` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4214 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4204 | `mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4177 | `mocha test` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4155 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 4145 | `mocha; jshint *.js lib` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 4079 | `mocha && ./bin/shipit staging test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4008 | `nyc mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3906 | `mocha --require test/babel-hook test/*.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3902 | `mocha --recursive && make test` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3895 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3848 | `export TESTING=true; mocha --reporter list` | 
| [muicss/mui](https://github.com/muicss/mui) | 3846 | `mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3829 | `NODE_ENV=test mocha` | 
| [erming/shout](https://github.com/erming/shout) | 3808 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [tj/ejs](https://github.com/tj/ejs) | 3792 | `mocha --require should --reporter spec` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3771 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3752 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3652 | `nyc mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3641 | `npm run jshint && npm run mocha` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3612 | `npm run lint ; mocha && mocha test/individual` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3612 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3557 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3549 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3534 | `mocha tests/javascript` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3527 | `mocha ./test/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3484 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3484 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [primus/primus](https://github.com/primus/primus) | 3468 | `npm run build && mocha test/*.test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3453 | `mocha --reporter spec --timeout 3000` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3438 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3433 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3398 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3396 | `mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3394 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3355 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3317 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3313 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3257 | `mocha --check-leaks --reporter spec --bail` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3252 | `npm run lint && npm run mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3209 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3148 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3147 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3113 | `nyc mocha "test/**/*.test.js"` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3099 | `mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3094 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 3087 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3072 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3064 | `./node_modules/.bin/mocha test/test.*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3020 | `node_modules/.bin/mocha test/tests.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2984 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2972 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2957 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2956 | `mocha` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2926 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2923 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2880 | `mocha test/*.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2880 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2839 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 2818 | `NODE_ENV=test mocha test/**/*.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2785 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2775 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2765 | `nyc mocha && tsc` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2757 | `mocha --require should --reporter spec` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2756 | `mocha -R spec --recursive src/test` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2753 | `mocha` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2733 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2730 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2726 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2725 | `istanbul cover _mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2722 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2721 | `mocha test/index.js && npm run demo` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2704 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2695 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2682 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2660 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2659 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2659 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2655 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2641 | `mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2625 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2621 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2618 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2617 | `xo && mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2614 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2597 | `mocha --timeout 100000` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2595 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2588 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2586 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2583 | `mocha --opts mocha.opts` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2579 | `mocha-phantomjs ./test/index.html` | 
| [css/csso](https://github.com/css/csso) | 2570 | `mocha --reporter dot` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2559 | `npm run mocha && npm run lint` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2526 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2517 | `mocha --recursive --watch` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2515 | `export TESTING=true; mocha --reporter list` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2508 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2503 | `mocha --compilers js:babel-register --recursive spec` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2503 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2488 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2470 | `mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2445 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2443 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2424 | `mocha --reporter=spec test/*-test.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2404 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2399 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2379 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2367 | `node node_modules/mocha/bin/_mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2365 | `NODE_ENV=test mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2337 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2336 | `mocha` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2335 | `node_modules/.bin/mocha --reporter spec` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2333 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2329 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2328 | `grunt jshint && mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2320 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2319 | `nyc mocha test/mocha-node-setup.js 'test/**/*-test.js'` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2312 | `nyc mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2301 | `mocha test/src/**/*.unit.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2301 | `npm run build && cd test && mocha . --reporter dot` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2295 | `mocha test` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2292 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2259 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [json5/json5](https://github.com/json5/json5) | 2244 | `mocha --ui exports --reporter spec` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2220 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2216 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2212 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2206 | `mocha` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2200 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2199 | `mocha test/unit --require mochahook` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2196 | `mocha "test/**/*-test.js"` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2187 | `npm run lint && npm run build && npm run mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2184 | `mocha --require should --reporter spec` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2180 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2162 | `mocha -R spec` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2157 | `mocha` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2151 | `export TESTING=true; mocha --reporter list` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2146 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [gajus/swing](https://github.com/gajus/swing) | 2136 | `mocha --compilers js:babel-register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2081 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2060 | `cross-env BABEL_ENV=test mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2058 | `nyc --reporter=html --reporter=text mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2053 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2041 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2032 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [slate/slate](https://github.com/slate/slate) | 2016 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2011 | `mocha test.js` | 
| [noble/noble](https://github.com/noble/noble) | 1999 | `mocha -R spec test/*.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1988 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1982 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1968 | `mocha -R landing test/index` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1936 | `mocha test && npm run lint` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1928 | `mocha --require=test/test_helper.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1916 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1913 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1900 | `mocha --bail --reporter spec --check-leaks test/` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1896 | `mocha -c test/index.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1890 | `mocha test/index.js --reporter dot` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1884 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Qix-/color](https://github.com/Qix-/color) | 1876 | `mocha` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1866 | `mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1866 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1849 | `mocha --require ./test/common --growl test/expect.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1845 | `mocha --compilers js:babel-register` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1844 | `mocha tests.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1843 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1840 | `mocha --reporter spec --timeout 5000` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1819 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1803 | `mocha --timeout 5000` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1802 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1798 | `mocha test/runner.js --reporter spec` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1789 | `cross-env NODE_ENV=test mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1787 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1787 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 1771 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1769 | `mocha --compilers js:babel-core/register __tests__` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1763 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1761 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1758 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1757 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1750 | `mocha test` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1747 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1738 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1738 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 1737 | `npm run lint && mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 1737 | `mocha test/*.test.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1724 | `mocha` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1712 | `npm run lint && mocha --reporter spec test/*.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1712 | `npm run lint && mocha -R dot && npm run cover` | 
| [share/sharedb](https://github.com/share/sharedb) | 1711 | `./node_modules/.bin/mocha && npm run jshint` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1708 | `mocha && eslint *.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1708 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1707 | `mocha test` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1705 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1703 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1688 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1687 | `npm run jshint && mocha --recursive` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1681 | `npm run mocha && npm run karma` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1679 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1677 | `npm run lint && mocha server/test --recursive --exit` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1674 | `mocha --reporter spec && npm run test-typescript` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1671 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1671 | `mocha -R spec spec spec/reporters` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1665 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1665 | `mocha` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1658 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1650 | `npm run lint && npm run mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1644 | `nyc npm run _mocha` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1641 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1637 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1610 | `mocha tests/test.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1603 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1603 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1602 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1602 | `mocha --expose-gc --slow 300` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1597 | `mocha && npm run lint` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1580 | `mocha` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1576 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1576 | `mocha --reporter spec --grep .` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1576 | `mocha test/*.js` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1573 | `npm run mocha && npm run lint` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1572 | `mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1570 | `npm run lint && mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1564 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1562 | `mocha tests --compilers js:babel-core/register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1562 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [pahen/madge](https://github.com/pahen/madge) | 1554 | `npm run lint && npm run mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1546 | `./node_modules/.bin/mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1543 | `mocha test -u bdd -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1538 | `mocha test/**/*.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1531 | `mocha ./test/basic.js -t 5000` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1529 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1526 | `mocha spec` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1523 | `mocha test/* --reporter spec` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1514 | `mocha --reporter spec test/*.js` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1507 | `mocha test --timeout 600000` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1498 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1498 | `mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1495 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1488 | `standard "src/*.js" && npm run build && mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1487 | `npm run lint && npm run mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1480 | `./node_modules/mocha/bin/mocha -R spec` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1479 | `npm run test:lint && npm run test:mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1475 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1470 | `mocha -R spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1467 | `mocha -u tdd` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1455 | `node_modules/.bin/mocha --recursive` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1446 | `mocha --reporter spec` | 
| [samccone/drool](https://github.com/samccone/drool) | 1435 | `mocha test/tests.js --timeout=10000` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1426 | `mocha test/**/*.spec.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1421 | `mocha --compilers js:babel-register` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1415 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1404 | `mocha test.js` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1392 | `nyc mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1391 | `eslint --cache . && tsc && mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1390 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1389 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1389 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1387 | `mocha --check-leaks -R dot` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1385 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1377 | `mocha test.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1366 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1365 | `standard "./src/*.js" && mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1365 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1364 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1352 | `mocha --recursive` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1348 | `./node_modules/mocha/bin/mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1335 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1328 | `mocha tests.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1326 | `cross-env NODE_ENV=test nyc mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1325 | `istanbul cover _mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1320 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1318 | `mocha --check-leaks --reporter spec --bail` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1317 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1308 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1301 | `eslint . && mocha -t 5000` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1294 | `mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1292 | `mocha-phantomjs tests/index.html` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1286 | `mocha --timeout 10000 ./tests/lib.js` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1285 | `mocha compiled_tests/` | 
| [noble/bleno](https://github.com/noble/bleno) | 1281 | `mocha -R spec test/*.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1277 | `npm run build && mocha -r should` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1274 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1270 | `mocha test/setup.js test/spec/*.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1262 | `npm run lint && npm run mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1261 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1255 | `./node_modules/.bin/mocha test` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1243 | `mocha spec/exec.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1241 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1239 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1234 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1233 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1230 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1224 | `istanbul cover _mocha test -- --timeout 20000` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1217 | `mocha test/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1213 | `mocha tests` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1213 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1207 | `mocha test/test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1204 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1197 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1195 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1194 | `mocha --check-leaks --require @babel/register` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1192 | `mocha test/**/*Spec.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1191 | `mocha --recursive` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1188 | `mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1188 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1185 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1185 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1183 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1181 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1173 | `mocha --opts test/opts/mocha.opts` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1170 | `mocha test` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1164 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1160 | `node ./node_modules/mocha/bin/mocha tests` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1156 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1151 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1148 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1140 | `mocha` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1137 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1132 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1126 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1123 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1113 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1113 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1113 | `npm run lint && npm run mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1112 | `mocha test/unit` | 
| [normalize/mz](https://github.com/normalize/mz) | 1111 | `mocha --reporter spec` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1109 | `standard && istanbul cover _mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1107 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1105 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1103 | `mocha --reporter dot` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1103 | `mocha src/test.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1102 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [variety/variety](https://github.com/variety/variety) | 1100 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1099 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1097 | `mocha` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1097 | `node_modules/.bin/mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1096 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1094 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1089 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1089 | `node_modules/.bin/mocha && npm run lint` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1086 | `eslint src && mocha && karma start --single-run` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1083 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1074 | `mocha test` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1074 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1073 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1069 | `mocha --check-leaks -t 20000` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1067 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1067 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1066 | `mocha --compilers js:babel-register` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1066 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1065 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1063 | `mocha test/*` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1061 | `mocha $(find test -name '*.test.js')` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1060 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1056 | `xo && mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 1046 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1045 | `mocha --reporter spec --timeout 3000` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1042 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1037 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1036 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1036 | `mocha --check-leaks --reporter spec --bail test/` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1033 | `istanbul test _mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1025 | `mocha tests/test-*` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1024 | `NODE_PATH=. mocha **/*.spec.js` | 
| [jas/playground](https://github.com/jas/playground) | 1020 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1018 | `istanbul cover _mocha test/*.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1017 | `mocha --check-leaks -R dot` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1013 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1012 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1008 | `nyc mocha --timeout=20000 test.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1007 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1007 | `mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1003 | `mocha test/tests.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 995 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 994 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 989 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 986 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 985 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 983 | `mocha --colors ./test/*.spec.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 983 | `mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 978 | `mocha` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 978 | `standard && mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 975 | `npm run prepublishOnly && mocha test/test.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 973 | `mocha --recursive --bail --reporter spec test` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 970 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 965 | `npm run rollup-cjs && mocha test/test.js` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 965 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 963 | `rollup -c --environment test && mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 958 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 956 | `mocha --timeout 5000` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 954 | `mocha --recursive test/unit/` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 954 | `mocha -R list` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 952 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 951 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 951 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 950 | `mocha $(find test -name '*.test.js')` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 949 | `mocha --recursive test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 946 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 941 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 939 | `mocha --reporter spec` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 938 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 937 | `mocha --compilers js:babel-core/register` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 937 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [tomas/needle](https://github.com/tomas/needle) | 937 | `mocha test` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 934 | `mocha -t 120000 test/*.test.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 933 | `standard && mocha -b` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 926 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 925 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 922 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 921 | `webpack && mocha test/unit` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 920 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 913 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 912 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 910 | `mocha --reporter spec --bail --check-leaks test/` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 909 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [electron/asar](https://github.com/electron/asar) | 906 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 906 | `mocha --reporter spec --bail --check-leaks test/` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 901 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 900 | `mocha && standard` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 897 | `nyc mocha --require @babel/register` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 896 | `mocha -R spec ./test/unit/**` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 895 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 894 | `mocha ./test/test*.js --reporter spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 890 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 886 | `mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 884 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 883 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 882 | `mocha tests/*.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 882 | `mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 881 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 880 | `mocha "client.test" --compilers js:babel-register` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 873 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 871 | `mocha --compilers js:babel-register test/*.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 871 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 870 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 866 | `mocha --reporter list` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 863 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 862 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 860 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 859 | `mocha` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 859 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 858 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 851 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 851 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 850 | `node_modules/.bin/mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 847 | `mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 846 | `mocha --reporter spec --bail --check-leaks test/` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 846 | `npm run convertto:es5 && npm run mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 846 | `npm run lint && npm run mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 845 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 844 | `npm run lint && mocha -R spec` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 844 | `mocha ./test -R spec` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 838 | `npm run lint && npm run mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 836 | `eslint test && mocha --compilers js:babel/register` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 834 | `mocha --timeout 200000` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 832 | `mocha tests` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 831 | `npm run lint && mocha --compilers js:babel-register` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 830 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 829 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 826 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 826 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 822 | `node_modules/.bin/mocha test/spec` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 819 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 818 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 818 | `mocha && ember test` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 816 | `eslint src test && mocha --compilers babel-register` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 814 | `mocha --reporter spec` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 813 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 811 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 807 | `mocha -R spec` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 804 | `mocha` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 803 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 802 | `mocha --check-leaks -t 20000` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 801 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 798 | `istanbul cover _mocha` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 795 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 795 | `standard && standard ./bin/* && mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 794 | `mocha --require babel-register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 791 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 790 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 788 | `mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 787 | `mocha --reporter spec --bail --check-leaks test/` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 787 | `mocha test --compilers js:babel-register` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 787 | `mocha -t 5000` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 786 | `mocha -t 600000` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 785 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 785 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 781 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 780 | `mocha` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 780 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 776 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 775 | `mocha --colors --reporter spec test.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 775 | `nyc mocha specs` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 773 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 773 | `istanbul cover -- _mocha --reporter spec` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 769 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 769 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 767 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 765 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 765 | `npm run lint && mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 765 | `mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 764 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 763 | `mocha --async-only` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 759 | `./node_modules/.bin/mocha -R spec` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 759 | `xo && mocha -R spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 759 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 759 | `mocha spec/*.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 757 | `mocha --reporter list` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 751 | `mocha --ui tdd --require ./test/__setup` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 747 | `npm run mocha:istanbul` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 747 | `mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 744 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 740 | `mocha -R spec src/**/*_test.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 738 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 738 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 733 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 730 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [bitpay/insight](https://github.com/bitpay/insight) | 730 | `mocha test` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 728 | `mocha --reporter spec` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 725 | `cross-env NODE_ENV=test nyc mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 723 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 723 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 723 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 720 | `mocha --recursive -s 15 test/` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 720 | `mocha test.js` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 719 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 715 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 712 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 711 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 711 | `npm run mocha-test test/integration` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 711 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 709 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 708 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 707 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 702 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 701 | `npm run bundle && mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 701 | `mocha test` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 701 | `mocha tests/*.mocha.js` | 
| [developit/decko](https://github.com/developit/decko) | 699 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 695 | `npm run build && istanbul test _mocha test/test.js` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 695 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 693 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 693 | `mocha` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 691 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 690 | `mocha test` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 689 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 684 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 684 | `mocha` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 682 | `mocha ./test/index.js` | 