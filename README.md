# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:42 02/11/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39727 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 39215 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 36995 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [expressjs/express](https://github.com/expressjs/express) | 36575 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28748 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23350 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 20645 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 18919 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 17627 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17483 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15540 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14798 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13773 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 13002 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12630 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12021 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12007 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11991 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11676 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11635 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 11191 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10923 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10550 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 10393 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9947 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9607 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9443 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 9297 | `mocha --harmony` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9222 | `mocha test/index.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9219 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9095 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 8986 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8868 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8514 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8351 | `mocha test/*-test.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8279 | `mocha` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8141 | `mocha --check-leaks -R dot` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8124 | `mocha test/test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7845 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7795 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7768 | `./node_modules/.bin/mocha test/src` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7733 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7675 | `mocha --compilers js:babel-register test/test.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 7616 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7438 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7429 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7403 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 7340 | `mocha` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7329 | `npm run eslint && npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7209 | `mocha tests/*.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7144 | `npm run build && istanbul cover _mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7096 | `./node_modules/.bin/mocha test` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6849 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6773 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6576 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6546 | `mocha $HARMONY_OPTS` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6478 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6424 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6334 | `mocha --opts mocha.opts` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6322 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6279 | `nyc mocha test/**/* -r ./test/before` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6240 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [almende/vis](https://github.com/almende/vis) | 6229 | `mocha --compilers js:babel-core/register` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6162 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 6101 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5922 | `mocha` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5922 | `npm run jshint -s && npm run mocha -s` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5820 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5772 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5673 | `npm run jshint && mocha test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5670 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5484 | `mocha tests/node.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5431 | `mocha test --recursive` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5403 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5387 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5357 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5317 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5303 | `mocha test/test.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5163 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5137 | `mocha src/**/*Tests.js --harmony` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5104 | `mocha --timeout 10000 && npm run lint` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5056 | `mocha --exit --require babel-core/register` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4975 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4964 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4764 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4730 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4681 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4641 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [santinic/how2](https://github.com/santinic/how2) | 4616 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4608 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4606 | `mocha --reporter spec -t 8000` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4544 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4533 | `mocha ./test/runner.js` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 4466 | `npm run build-cli && mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4448 | `gulp build; mocha;` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4407 | `standard && mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4388 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4379 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4364 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4321 | `./node_modules/.bin/mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4319 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4315 | `mocha` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4248 | `mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4222 | `mocha -R spec ./test --recursive` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4186 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4179 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4142 | `mocha test` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4078 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 4059 | `mocha && ./bin/shipit staging test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3994 | `nyc mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3889 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 3862 | `mocha; jshint *.js lib` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3849 | `export TESTING=true; mocha --reporter list` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3838 | `mocha --require test/babel-hook test/*.js` | 
| [erming/shout](https://github.com/erming/shout) | 3817 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [muicss/mui](https://github.com/muicss/mui) | 3815 | `mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3796 | `NODE_ENV=test mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3779 | `mocha --require should --reporter spec` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3728 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3710 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3641 | `npm run jshint && npm run mocha` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 3636 | `mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3623 | `nyc mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3596 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3591 | `npm run lint ; mocha && mocha test/individual` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3550 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3543 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3529 | `mocha tests/javascript` | 
| [primus/primus](https://github.com/primus/primus) | 3455 | `npm run build && mocha test/*.test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3451 | `mocha --reporter spec --timeout 3000` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3443 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3426 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3397 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3392 | `mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3384 | `node_modules/.bin/mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3373 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3351 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3343 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3271 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3268 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3201 | `mocha --check-leaks --reporter spec --bail` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3186 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3175 | `npm run lint && npm run mocha` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3124 | `mocha ./test/*.spec.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3121 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3108 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3094 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3070 | `mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3066 | `yarn run build:cjs && mocha --require babel-core/register ./test/index.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3064 | `nyc mocha "test/**/*.test.js"` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3061 | `./node_modules/.bin/mocha test/test.*.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 3049 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3018 | `node_modules/.bin/mocha test/tests.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2964 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2958 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2931 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2926 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2922 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2860 | `mocha test/*.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2853 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2834 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2824 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 2774 | `NODE_ENV=test mocha test/**/*.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2771 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2768 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2757 | `mocha --require should --reporter spec` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2742 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2740 | `mocha -R spec --recursive src/test` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2724 | `nyc mocha && tsc` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2717 | `istanbul cover _mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2713 | `mocha test/index.js && npm run demo` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2713 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2699 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2691 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2679 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [tj/should.js](https://github.com/tj/should.js) | 2668 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2664 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2654 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2648 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2643 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2641 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2628 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2625 | `mocha` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2608 | `xo && mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2602 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2600 | `mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2596 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2593 | `mocha --timeout 100000` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2590 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2577 | `mocha-phantomjs ./test/index.html` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2571 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2570 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2570 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2561 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2552 | `mocha --opts mocha.opts` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2542 | `npm run mocha && npm run lint` | 
| [css/csso](https://github.com/css/csso) | 2540 | `mocha --reporter dot` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2515 | `export TESTING=true; mocha --reporter list` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2515 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2505 | `mocha --recursive --watch` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2495 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2479 | `mocha --compilers js:babel-register --recursive spec` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2469 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2446 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2433 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2432 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2422 | `mocha --reporter=spec test/*-test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2394 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2393 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2361 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2359 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2334 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2325 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2323 | `grunt jshint && mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2319 | `NODE_ENV=test mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2315 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2314 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2301 | `node_modules/.bin/mocha --reporter spec` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2289 | `mocha test/src/**/*.unit.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2287 | `nyc mocha 'test/**/*-test.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2286 | `mocha test` | 
| [mozilla/send](https://github.com/mozilla/send) | 2282 | `mocha test/unit` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2267 | `npm run build && cd test && mocha . --reporter dot` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2260 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2249 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [json5/json5](https://github.com/json5/json5) | 2234 | `mocha --ui exports --reporter spec` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2220 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2218 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2210 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2196 | `mocha` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2192 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2178 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2173 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2169 | `npm run lint && npm run build && npm run mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2163 | `mocha "test/**/*-test.js"` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2150 | `mocha -R spec` | 
| [mde/ejs](https://github.com/mde/ejs) | 2146 | `mocha --require should --reporter spec` | 
| [gajus/swing](https://github.com/gajus/swing) | 2131 | `mocha --compilers js:babel-register` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2130 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2125 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2081 | `export TESTING=true; mocha --reporter list` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2079 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2049 | `cross-env BABEL_ENV=test mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2039 | `nyc --reporter=html --reporter=text mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2036 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2019 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [slate/slate](https://github.com/slate/slate) | 2018 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2010 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1985 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1967 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1967 | `mocha && eslint .` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1954 | `mocha test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1939 | `mocha -R landing test/index` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1926 | `mocha --require=test/test_helper.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1909 | `mocha test && npm run lint` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1901 | `mocha --bail --reporter spec --check-leaks test/` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1900 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1895 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1885 | `mocha -c test/index.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1884 | `mocha test/index.js --reporter dot` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1880 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Qix-/color](https://github.com/Qix-/color) | 1863 | `mocha` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1858 | `mocha` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1839 | `mocha --require ./test/common --growl test/expect.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1836 | `mocha tests.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1836 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1826 | `mocha --reporter spec --timeout 5000` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1826 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1817 | `mocha --compilers js:babel-register` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1805 | `mocha --timeout 5000` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1790 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1790 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1783 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1783 | `mocha test/runner.js --reporter spec` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1782 | `cross-env NODE_ENV=test mocha` | 
| [then/promise](https://github.com/then/promise) | 1765 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1762 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1754 | `mocha --compilers js:babel-core/register __tests__` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1751 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1748 | `mocha test` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1746 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1743 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1742 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1737 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [kach/nearley](https://github.com/kach/nearley) | 1721 | `mocha test/*.test.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1717 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1703 | `mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1701 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1701 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1698 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1697 | `mocha test` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1693 | `npm run lint && mocha -R dot && npm run cover` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1692 | `npm run lint && mocha --reporter spec test/*.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1692 | `./node_modules/.bin/mocha && npm run jshint` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1691 | `mocha && eslint *.js` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1688 | `npm run jshint && mocha --recursive` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1686 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1664 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1662 | `./node_modules/mocha/bin/mocha -R spec` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1661 | `npm run lint && mocha server/test --recursive --exit` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1660 | `./node_modules/.bin/mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1655 | `mocha --reporter spec && npm run test-typescript` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1654 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1653 | `npm run mocha && npm run karma` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1652 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1645 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1642 | `mocha -R spec spec spec/reporters` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1642 | `npm run lint && npm run mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1635 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1623 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1618 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1610 | `mocha tests/test.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1606 | `nyc npm run _mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1605 | `mocha --expose-gc --slow 300` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1604 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1597 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1588 | `mocha && npm run lint` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1585 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1571 | `mocha test/*.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1569 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1560 | `mocha --reporter spec --grep .` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1558 | `npm run mocha && npm run lint` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1557 | `mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1556 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1554 | `npm run lint && mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1550 | `mocha tests --compilers js:babel-core/register` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1546 | `./node_modules/.bin/mocha` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1545 | `mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1539 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1530 | `mocha test -u bdd -R spec` | 
| [pahen/madge](https://github.com/pahen/madge) | 1530 | `npm run lint && npm run mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1527 | `mocha test/` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1521 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1516 | `mocha ./test/basic.js -t 5000` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1515 | `mocha spec/` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1510 | `mocha test/* --reporter spec` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1500 | `mocha --reporter spec test/*.js` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1498 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1496 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1487 | `mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1476 | `npm run test:lint && npm run test:mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1475 | `./node_modules/mocha/bin/mocha -R spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1474 | `npm run lint && npm run mocha` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1470 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1466 | `mocha -R spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1462 | `mocha -u tdd` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1456 | `mocha test --timeout 600000` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1447 | `node_modules/.bin/mocha --recursive` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1444 | `standard "src/*.js" && npm run build && mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1440 | `mocha --reporter spec` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1432 | `mocha test/tests.js --timeout=10000` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1419 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1410 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1407 | `mocha --compilers js:babel-register` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1403 | `mocha test.js` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1381 | `nyc mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1381 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1380 | `mocha --check-leaks -R dot` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1377 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1375 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1374 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1371 | `eslint --cache . && tsc && mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1365 | `mocha test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1362 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1362 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1354 | `standard "./src/*.js" && mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1348 | `./node_modules/mocha/bin/mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1340 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1335 | `mocha --recursive` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1325 | `cross-env NODE_ENV=test nyc mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1319 | `istanbul cover _mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1318 | `mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1318 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1308 | `mocha tests.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1298 | `mocha --check-leaks --reporter spec --bail` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1296 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1284 | `mocha-phantomjs tests/index.html` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1283 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1274 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1274 | `mocha --timeout 10000 ./tests/lib.js` | 
| [sandeepmistry/bleno](https://github.com/sandeepmistry/bleno) | 1273 | `mocha -R spec test/*.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1272 | `npm run build && mocha -r should` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1266 | `eslint . && mocha -t 5000` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1261 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1258 | `mocha compiled_tests/` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1251 | `./node_modules/.bin/mocha test` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1251 | `mocha test/setup.js test/spec/*.js` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1247 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1241 | `mocha spec/exec.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1238 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1234 | `npm run lint && npm run mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1226 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1224 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1219 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1216 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1212 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1210 | `istanbul cover _mocha test -- --timeout 20000` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1209 | `mocha tests` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1206 | `mocha test/test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1206 | `mocha test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1201 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1197 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1193 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1192 | `mocha test/**/*Spec.js` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1187 | `mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1186 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1180 | `mocha --recursive` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1179 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1178 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1172 | `mocha test` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1172 | `mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1170 | `mocha --check-leaks --require @babel/register` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1163 | `mocha --opts test/opts/mocha.opts` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1163 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1160 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1154 | `node ./node_modules/mocha/bin/mocha tests` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1148 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1144 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1141 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1136 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1125 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1116 | `mocha` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1113 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1110 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1109 | `npm run lint && npm run mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1108 | `mocha --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1101 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1099 | `mocha src/test.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1097 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1093 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1093 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1092 | `mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1090 | `mocha --reporter dot` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1089 | `node_modules/.bin/mocha && npm run lint` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1087 | `mocha test/unit` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1087 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1086 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1086 | `standard && istanbul cover _mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1080 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1080 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1079 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1079 | `node_modules/.bin/mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1075 | `eslint src && mocha && karma start --single-run` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1072 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1071 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1067 | `mocha --check-leaks -t 20000` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1066 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1065 | `mocha --compilers js:babel-register` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1063 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1061 | `mocha test/*` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1056 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1053 | `mocha $(find test -name '*.test.js')` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1051 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1048 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1047 | `mocha --reporter spec --timeout 3000` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1044 | `xo && mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1032 | `istanbul test _mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1031 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1029 | `mocha --check-leaks --reporter spec --bail test/` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1029 | `mocha test` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1028 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1027 | `mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1023 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [jas/playground](https://github.com/jas/playground) | 1020 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1015 | `NODE_PATH=. mocha **/*.spec.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1015 | `mocha --check-leaks -R dot` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1011 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1010 | `istanbul cover _mocha test/*.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1002 | `mocha tests/test-*` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 996 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 996 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 996 | `mocha test/tests.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 995 | `mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 990 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 987 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 984 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 982 | `mocha --colors ./test/*.spec.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 979 | `mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 975 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 972 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 972 | `mocha` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 970 | `mocha --recursive --bail --reporter spec test` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 967 | `npm run prepublish && mocha test/test.js` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 967 | `standard && mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 960 | `npm run rollup-cjs && mocha test/test.js` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 957 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [teambit/bit](https://github.com/teambit/bit) | 957 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 956 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 955 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 955 | `mocha --timeout 5000` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 952 | `mocha -R list` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 949 | `mocha $(find test -name '*.test.js')` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 945 | `mocha --recursive test/unit/` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 943 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [router5/router5](https://github.com/router5/router5) | 943 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 942 | `mocha --async-only` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 942 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 936 | `mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 936 | `mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 936 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 935 | `mocha --reporter spec` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 933 | `mocha -t 120000 test/*.test.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 928 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 927 | `mocha --recursive test` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 921 | `mocha --compilers js:babel-core/register` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 920 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 920 | `standard && mocha -b` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 918 | `nyc mocha --timeout=20000 test.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 917 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 909 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 909 | `webpack && mocha test/unit` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 908 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 907 | `mocha ./test/index.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 907 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 899 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron/asar](https://github.com/electron/asar) | 898 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 896 | `mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 894 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 892 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 888 | `mocha --reporter spec --bail --check-leaks test/` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 886 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 883 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 882 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 881 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 880 | `nyc mocha --require @babel/register` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 877 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 873 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 872 | `mocha "client.test" --compilers js:babel-register` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 871 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 870 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 868 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 865 | `mocha --reporter list` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 864 | `mocha --compilers js:babel-register test/*.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 861 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 860 | `mocha && standard` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 857 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 857 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 857 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 856 | `mocha ./test/test*.js --reporter spec` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 850 | `mocha tests/*.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 850 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 849 | `mocha -R spec ./test/unit/**` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 846 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 846 | `node_modules/.bin/mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 846 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 842 | `mocha --reporter spec --bail --check-leaks test/` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 840 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 840 | `mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 838 | `npm run lint && mocha -R spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 838 | `eslint test && mocha --compilers js:babel/register` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 837 | `npm run convertto:es5 && npm run mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 837 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 836 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 834 | `npm run lint && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 829 | `mocha --timeout 200000` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 827 | `mocha tests` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 827 | `mocha ./test -R spec` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 824 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 824 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 823 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 822 | `npm run lint && mocha --compilers js:babel-register` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 820 | `node_modules/.bin/mocha test/spec` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 818 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 815 | `mocha && ember test` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 814 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 813 | `mocha --reporter spec` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 812 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 809 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffeescript --recursive regression/node-helper.coffee regression/src` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 807 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 803 | `mocha --check-leaks -t 20000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 801 | `mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 797 | `istanbul cover _mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 797 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 795 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 794 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 792 | `mocha --require babel-register` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 790 | `mocha -R spec tests/` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 790 | `mocha -R spec` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 790 | `standard && standard ./bin/* && mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 788 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 785 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 785 | `mocha --reporter spec --bail --check-leaks test/` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 785 | `mocha -t 5000` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 785 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 783 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 780 | `cake build && mocha ./test/mocha/*.coffee` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 780 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 778 | `mocha -t 600000` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 777 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 776 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 775 | `mocha test --compilers js:babel-register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 774 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [edsu/anon](https://github.com/edsu/anon) | 771 | `mocha --colors --reporter spec test.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 771 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 771 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 770 | `istanbul cover -- _mocha --reporter spec` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 766 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 765 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 764 | `npm run lint && mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 764 | `nyc mocha specs` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 763 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 762 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 762 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 759 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require babel-register --no-timeouts` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 757 | `mocha --async-only` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 756 | `mocha spec/*.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 753 | `xo && mocha -R spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 753 | `mocha` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 747 | `./node_modules/.bin/mocha -R spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 746 | `mocha --reporter list` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 744 | `mocha --ui tdd --require ./test/__setup` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 738 | `mocha -R spec src/**/*_test.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 736 | `npm run mocha:istanbul` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 734 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 733 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 733 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 730 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 728 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 727 | `mocha --reporter spec` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 725 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 723 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 721 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [bitpay/insight](https://github.com/bitpay/insight) | 720 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 717 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 717 | `mocha --recursive -s 15 test/` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 716 | `mocha test.js` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 716 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 714 | `cross-env NODE_ENV=test nyc mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 712 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 708 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 707 | `mocha` | 
| [3Dparallax/insight](https://github.com/3Dparallax/insight) | 707 | `mocha test` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 705 | `mocha` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 704 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 704 | `eslint src test && mocha --compilers babel-register` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 703 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 701 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 700 | `npm run bundle && mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 698 | `npm run mocha-test test/integration` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 697 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 695 | `mocha tests/*.mocha.js` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 693 | `mocha test` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 692 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 688 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 687 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 687 | `npm run build && istanbul test _mocha test/test.js` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 683 | `mocha test` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 680 | `mocha` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 679 | `mocha ./test/index.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 679 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [developit/decko](https://github.com/developit/decko) | 679 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 679 | `npm run lint && mocha test` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 678 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 674 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 674 | `mocha --reporter spec` | 