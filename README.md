# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:07 02/08/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39700 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 39150 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 36910 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [expressjs/express](https://github.com/expressjs/express) | 36537 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28718 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23329 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 22054 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 20596 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 18790 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 17591 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17453 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15516 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14765 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13762 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12972 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12607 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12010 | `mocha 'test/**/*.spec.js'` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11986 | `mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11984 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11665 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11624 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 11160 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10895 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10532 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 10369 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9930 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9578 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9421 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 9287 | `mocha --harmony` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9206 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9200 | `mocha test/index.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9074 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 8968 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8858 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8512 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8334 | `mocha test/*-test.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8261 | `mocha` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8135 | `mocha --check-leaks -R dot` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8110 | `mocha test/test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7810 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7779 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7758 | `./node_modules/.bin/mocha test/src` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7728 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7663 | `mocha --compilers js:babel-register test/test.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 7585 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7439 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7427 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7374 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7319 | `npm run eslint && npm run mocha` | 
| [amark/gun](https://github.com/amark/gun) | 7319 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7194 | `mocha tests/*.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7137 | `npm run build && istanbul cover _mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7085 | `./node_modules/.bin/mocha test` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6824 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6757 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6558 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6542 | `mocha $HARMONY_OPTS` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6466 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6419 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6322 | `mocha --opts mocha.opts` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6313 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6256 | `nyc mocha test/**/* -r ./test/before` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6224 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [almende/vis](https://github.com/almende/vis) | 6223 | `mocha --compilers js:babel-core/register` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6146 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 6071 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5926 | `mocha` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5911 | `npm run jshint -s && npm run mocha -s` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5812 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5763 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5662 | `npm run jshint && mocha test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5659 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5476 | `mocha tests/node.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5424 | `mocha test --recursive` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5387 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5348 | `mocha && eslint lib/**` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5345 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5309 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5293 | `mocha test/test.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5164 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5138 | `mocha src/**/*Tests.js --harmony` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5099 | `mocha --timeout 10000 && npm run lint` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5038 | `mocha --exit --require babel-core/register` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4959 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4953 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4762 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4730 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4670 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4624 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [santinic/how2](https://github.com/santinic/how2) | 4617 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4607 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4602 | `mocha --reporter spec -t 8000` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4536 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4530 | `mocha ./test/runner.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4439 | `gulp build; mocha;` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 4412 | `npm run build-cli && mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4399 | `standard && mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4386 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4370 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4358 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4320 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4317 | `./node_modules/.bin/mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4292 | `mocha` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4240 | `mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4222 | `mocha -R spec ./test --recursive` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4183 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4173 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4140 | `mocha test` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4060 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 4053 | `mocha && ./bin/shipit staging test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3989 | `nyc mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3889 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3846 | `export TESTING=true; mocha --reporter list` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3827 | `mocha --require test/babel-hook test/*.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 3821 | `mocha; jshint *.js lib` | 
| [erming/shout](https://github.com/erming/shout) | 3817 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [muicss/mui](https://github.com/muicss/mui) | 3810 | `mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3783 | `NODE_ENV=test mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3773 | `mocha --require should --reporter spec` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3721 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3699 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3640 | `npm run jshint && npm run mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3617 | `nyc mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3592 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3582 | `npm run lint ; mocha && mocha test/individual` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3550 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3543 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3530 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3449 | `mocha --reporter spec --timeout 3000` | 
| [primus/primus](https://github.com/primus/primus) | 3448 | `npm run build && mocha test/*.test.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3435 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3427 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3394 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3391 | `mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3382 | `node_modules/.bin/mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3344 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3339 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3335 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3265 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3247 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3186 | `mocha --check-leaks --reporter spec --bail` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3178 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3159 | `npm run lint && npm run mocha` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3112 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3100 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3099 | `mocha ./test/*.spec.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3094 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3070 | `mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3060 | `yarn run build:cjs && mocha --require babel-core/register ./test/index.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3058 | `./node_modules/.bin/mocha test/test.*.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3051 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 3041 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 3038 | `mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3016 | `node_modules/.bin/mocha test/tests.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2963 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2955 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2923 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2921 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2921 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2854 | `mocha test/*.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2839 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2820 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2819 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2770 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2766 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 2762 | `NODE_ENV=test mocha test/**/*.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2758 | `mocha --require should --reporter spec` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2738 | `mocha -R spec --recursive src/test` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2734 | `mocha` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2718 | `nyc mocha && tsc` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2716 | `istanbul cover _mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2713 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2709 | `mocha test/index.js && npm run demo` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2686 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2679 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [tj/should.js](https://github.com/tj/should.js) | 2668 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2663 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2661 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2640 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2639 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2638 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2632 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2622 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2622 | `mocha` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2606 | `xo && mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2593 | `mocha --timeout 100000` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2591 | `mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2591 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2587 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2583 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2576 | `mocha-phantomjs ./test/index.html` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2575 | `npm run compile && mocha --require babel-core/register` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2568 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2566 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2563 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2548 | `mocha --opts mocha.opts` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2547 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [css/csso](https://github.com/css/csso) | 2538 | `mocha --reporter dot` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2535 | `npm run mocha && npm run lint` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2513 | `export TESTING=true; mocha --reporter list` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2507 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2504 | `mocha --recursive --watch` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2493 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2478 | `mocha --compilers js:babel-register --recursive spec` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2458 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2437 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2427 | `mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2427 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2423 | `mocha --reporter=spec test/*-test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2394 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2382 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2356 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2344 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2333 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2324 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2323 | `grunt jshint && mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2314 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2312 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2308 | `NODE_ENV=test mocha` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2292 | `node_modules/.bin/mocha --reporter spec` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2287 | `mocha test/src/**/*.unit.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2283 | `nyc mocha 'test/**/*-test.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2283 | `mocha test` | 
| [mozilla/send](https://github.com/mozilla/send) | 2273 | `mocha test/unit` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2263 | `npm run build && cd test && mocha . --reporter dot` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2262 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2237 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [json5/json5](https://github.com/json5/json5) | 2227 | `mocha --ui exports --reporter spec` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2218 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2218 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2209 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2192 | `mocha` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2190 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2177 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2168 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2163 | `npm run lint && npm run build && npm run mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2159 | `mocha "test/**/*-test.js"` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2147 | `mocha -R spec` | 
| [mde/ejs](https://github.com/mde/ejs) | 2139 | `mocha --require should --reporter spec` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2127 | `mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2127 | `mocha --compilers js:babel-register` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2119 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2080 | `mocha` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2067 | `export TESTING=true; mocha --reporter list` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2046 | `cross-env BABEL_ENV=test mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2036 | `nyc --reporter=html --reporter=text mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2036 | `mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2018 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2016 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2000 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1978 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1964 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1959 | `mocha && eslint .` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1940 | `mocha test.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1926 | `mocha --require=test/test_helper.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1925 | `mocha -R landing test/index` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1903 | `mocha test && npm run lint` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1899 | `mocha --bail --reporter spec --check-leaks test/` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1895 | `mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1884 | `mocha -c test/index.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1880 | `mocha test/index.js --reporter dot` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1880 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1876 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [Qix-/color](https://github.com/Qix-/color) | 1859 | `mocha` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1858 | `mocha` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1837 | `mocha --require ./test/common --growl test/expect.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1835 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1832 | `mocha tests.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1825 | `mocha --reporter spec --timeout 5000` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1822 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1821 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1816 | `mocha --compilers js:babel-register` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1805 | `mocha --timeout 5000` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1790 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1782 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1780 | `cross-env NODE_ENV=test mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1779 | `mocha test/runner.js --reporter spec` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1775 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [then/promise](https://github.com/then/promise) | 1764 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1759 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1750 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1748 | `mocha test` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1746 | `mocha --compilers js:babel-core/register __tests__` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1742 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1740 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1737 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1736 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [kach/nearley](https://github.com/kach/nearley) | 1721 | `mocha test/*.test.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1717 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1701 | `mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1701 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1700 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1697 | `mocha test` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1697 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1692 | `npm run lint && mocha --reporter spec test/*.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1691 | `./node_modules/.bin/mocha && npm run jshint` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1686 | `mocha` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1685 | `npm run lint && mocha -R dot && npm run cover` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1684 | `mocha && eslint *.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1664 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1658 | `./node_modules/.bin/mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1658 | `npm run lint && mocha --recursive --exit` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1656 | `./node_modules/mocha/bin/mocha -R spec` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1651 | `mocha --reporter spec && npm run test-typescript` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1651 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1648 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1645 | `npm run mocha && npm run karma` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1644 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1639 | `mocha -R spec spec spec/reporters` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1638 | `npm run lint && npm run mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1636 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1624 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1618 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1609 | `mocha tests/test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1605 | `mocha --expose-gc --slow 300` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1604 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1598 | `nyc npm run _mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1597 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1586 | `mocha && npm run lint` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1571 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1569 | `mocha test/*.js` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1567 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1557 | `mocha --reporter spec --grep .` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1556 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1552 | `npm run mocha && npm run lint` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1552 | `npm run lint && mocha` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1551 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1548 | `mocha tests --compilers js:babel-core/register` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1546 | `./node_modules/.bin/mocha` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1539 | `mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1536 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [pahen/madge](https://github.com/pahen/madge) | 1526 | `npm run lint && npm run mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1525 | `mocha test/` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1524 | `mocha test -u bdd -R spec` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1519 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1515 | `mocha spec/` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1514 | `mocha ./test/basic.js -t 5000` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1509 | `mocha test/* --reporter spec` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1499 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1497 | `mocha --reporter spec test/*.js` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1497 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1487 | `mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1473 | `npm run test:lint && npm run test:mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1473 | `./node_modules/mocha/bin/mocha -R spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1472 | `npm run lint && npm run mocha` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1468 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1465 | `mocha -R spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1462 | `mocha -u tdd` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1452 | `mocha test --timeout 600000` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1448 | `node_modules/.bin/mocha --recursive` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1440 | `mocha --reporter spec` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1432 | `standard "src/*.js" && npm run build && mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1431 | `mocha test/tests.js --timeout=10000` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1417 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1408 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1404 | `mocha --compilers js:babel-register` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1403 | `mocha test.js` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1379 | `nyc mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1379 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1375 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1374 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1372 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1372 | `mocha --check-leaks -R dot` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1368 | `eslint --cache . && tsc && mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1362 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1361 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1361 | `mocha test.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1353 | `standard "./src/*.js" && mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1348 | `./node_modules/mocha/bin/mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1335 | `mocha --recursive` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1333 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1326 | `cross-env NODE_ENV=test nyc mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1317 | `mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1316 | `istanbul cover _mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1312 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1305 | `mocha tests.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1291 | `mocha --check-leaks --reporter spec --bail` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1291 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1283 | `mocha-phantomjs tests/index.html` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1279 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [sandeepmistry/bleno](https://github.com/sandeepmistry/bleno) | 1273 | `mocha -R spec test/*.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1273 | `mocha --timeout 10000 ./tests/lib.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1270 | `npm run build && mocha -r should` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1265 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1261 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1254 | `mocha compiled_tests/` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1249 | `./node_modules/.bin/mocha test` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1246 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1242 | `mocha test/setup.js test/spec/*.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1238 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1237 | `mocha spec/exec.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1229 | `eslint . && mocha -t 5000` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1227 | `npm run lint && npm run mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1226 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1217 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1217 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1213 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1212 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1210 | `mocha tests` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1207 | `istanbul cover _mocha test -- --timeout 20000` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1206 | `mocha test/*.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1204 | `mocha test/test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1201 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1197 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1192 | `mocha test/**/*Spec.js` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1190 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1187 | `mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1186 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1178 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1178 | `mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1175 | `mocha --recursive` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1171 | `mocha test` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1170 | `mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1167 | `mocha --check-leaks --require @babel/register` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1165 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1163 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1161 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1159 | `mocha --opts test/opts/mocha.opts` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1153 | `node ./node_modules/mocha/bin/mocha tests` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1145 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1143 | `eslint lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1139 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1134 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1125 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1113 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1111 | `mocha` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1107 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1107 | `mocha --reporter spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1106 | `npm run lint && npm run mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1102 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1099 | `mocha src/test.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1097 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1093 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1093 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1092 | `mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1089 | `node_modules/.bin/mocha && npm run lint` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1086 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1084 | `mocha --reporter dot` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1083 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1082 | `mocha test/unit` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1080 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1079 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1077 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1077 | `node_modules/.bin/mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1074 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1071 | `eslint src && mocha && karma start --single-run` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1069 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1069 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1066 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1066 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1066 | `mocha --compilers js:babel-register` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1062 | `mocha test/*` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1060 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1053 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1053 | `mocha $(find test -name '*.test.js')` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1050 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1047 | `mocha --reporter spec --timeout 3000` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1044 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1042 | `xo && mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1032 | `istanbul test _mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1030 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1026 | `mocha --check-leaks --reporter spec --bail test/` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1023 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1021 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [jas/playground](https://github.com/jas/playground) | 1020 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1020 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1018 | `mocha test` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1016 | `mocha --check-leaks -R dot` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1015 | `NODE_PATH=. mocha **/*.spec.js` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1011 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1004 | `istanbul cover _mocha test/*.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 996 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 995 | `mocha tests/test-*` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 994 | `mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 994 | `mocha test/tests.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 992 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 987 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 987 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 986 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 982 | `mocha --colors ./test/*.spec.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 977 | `mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 972 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 971 | `mocha` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 970 | ` NODE_ENV=test mocha --compilers js:babel-register` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 969 | `mocha --recursive --bail --reporter spec test` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 965 | `standard && mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 961 | `npm run rollup-cjs && mocha test/test.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 960 | `npm run prepublish && mocha test/test.js` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 957 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 955 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 955 | `mocha --timeout 5000` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 954 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [teambit/bit](https://github.com/teambit/bit) | 953 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 952 | `mocha -R list` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 949 | `mocha $(find test -name '*.test.js')` | 
| [router5/router5](https://github.com/router5/router5) | 944 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 943 | `mocha --recursive test/unit/` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 940 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 940 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 939 | `mocha --async-only` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 936 | `mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 936 | `mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 936 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 933 | `mocha --reporter spec` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 932 | `mocha -t 120000 test/*.test.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 924 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 923 | `mocha --recursive test` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 920 | `standard && mocha -b` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 919 | `mocha --compilers js:babel-core/register` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 918 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 915 | `nyc mocha --timeout=20000 test.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 914 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 908 | `mocha spec/*.spec.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 907 | `webpack && mocha test/unit` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 906 | `mocha ./test/index.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 904 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 903 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 899 | `mocha --reporter spec --bail --check-leaks test/` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 895 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 894 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 891 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 887 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 885 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 885 | `mocha --reporter spec --bail --check-leaks test/` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 881 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 881 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 881 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 877 | `mocha` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 877 | `nyc mocha --require @babel/register` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 874 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 871 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 871 | `mocha "client.test" --compilers js:babel-register` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 870 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 865 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 865 | `mocha --reporter list` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 862 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 859 | `mocha --compilers js:babel-register test/*.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 857 | `mocha && standard` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 856 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 855 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 848 | `mocha ./test/test*.js --reporter spec` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 846 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 846 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 845 | `node_modules/.bin/mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 843 | `mocha tests/*.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 843 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 841 | `mocha -R spec ./test/unit/**` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 840 | `mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 839 | `mocha --reporter spec --bail --check-leaks test/` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 838 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 837 | `npm run lint && mocha -R spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 837 | `eslint test && mocha --compilers js:babel/register` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 835 | `npm run convertto:es5 && npm run mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 834 | `npm run lint && npm run mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 833 | `mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 833 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 829 | `mocha --timeout 200000` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 828 | `mocha tests` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 827 | `mocha ./test -R spec` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 824 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 823 | `mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 821 | `npm run lint && mocha --compilers js:babel-register` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 821 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 820 | `node_modules/.bin/mocha test/spec` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 817 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 815 | `mocha && ember test` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 814 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 813 | `mocha --reporter spec` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 812 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 802 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 802 | `mocha --check-leaks -t 20000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 801 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 798 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 796 | `istanbul cover _mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 793 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 792 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 792 | `mocha --require babel-register` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 791 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 790 | `mocha -R spec tests/` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 789 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 788 | `standard && standard ./bin/* && mocha` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 785 | `mocha -R spec` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 785 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 783 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 783 | `mocha --reporter spec --bail --check-leaks test/` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 783 | `mocha -t 5000` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 780 | `cake build && mocha ./test/mocha/*.coffee` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 779 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 778 | `mocha` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 777 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 776 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 775 | `mocha -t 600000` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 775 | `mocha test --compilers js:babel-register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 772 | `NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [edsu/anon](https://github.com/edsu/anon) | 769 | `mocha --colors --reporter spec test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 769 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 768 | `istanbul cover -- _mocha --reporter spec` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 765 | `mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 765 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 764 | `npm run lint && mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 764 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 763 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 761 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 760 | `nyc mocha specs` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 760 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 758 | `mocha --async-only` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 755 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require babel-register --no-timeouts` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 754 | `mocha spec/*.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 752 | `xo && mocha -R spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 752 | `mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 747 | `mocha --reporter list` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 745 | `./node_modules/.bin/mocha -R spec` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 744 | `mocha --ui tdd --require ./test/__setup` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 737 | `mocha -R spec src/**/*_test.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 735 | `npm run mocha:istanbul` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 733 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 733 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 727 | `mocha --reporter spec` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 726 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 726 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 723 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 722 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 720 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 716 | `mocha --recursive -s 15 test/` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 716 | `mocha test.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 714 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [bitpay/insight](https://github.com/bitpay/insight) | 714 | `mocha test` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 712 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 711 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 711 | `cross-env NODE_ENV=test nyc mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 707 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [3Dparallax/insight](https://github.com/3Dparallax/insight) | 707 | `mocha test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 703 | `eslint src test && mocha --compilers babel-register` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 703 | `mocha` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 702 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 702 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 699 | `npm run bundle && mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 697 | `npm run mocha-test test/integration` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 697 | `mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 694 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 694 | `mocha tests/*.mocha.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 694 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 693 | `mocha test` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 687 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 687 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 685 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 685 | `npm run build && istanbul test _mocha test/test.js` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 683 | `mocha test` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 679 | `mocha ./test/index.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 679 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 679 | `npm run lint && mocha test` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 679 | `mocha` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 678 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [developit/decko](https://github.com/developit/decko) | 677 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 674 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 673 | `mocha --reporter spec` | 