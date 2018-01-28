# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:23 01/28/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39628 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 38848 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 36464 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [expressjs/express](https://github.com/expressjs/express) | 36323 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28596 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23236 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 20409 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 18005 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 17436 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17356 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15440 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14644 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13718 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12852 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12509 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11970 | `mocha` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 11961 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11876 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11635 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11542 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 11003 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10774 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10472 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 10220 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9848 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9483 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9312 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 9242 | `mocha --harmony` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9129 | `mocha test/index.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9128 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9011 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 8891 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8823 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8489 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8287 | `mocha test/*-test.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8182 | `mocha` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8127 | `mocha --check-leaks -R dot` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8072 | `mocha test/test.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7707 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7706 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7704 | `./node_modules/.bin/mocha test/src` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7666 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7620 | `mocha --compilers js:babel-register test/test.js` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7436 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 7433 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7416 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7287 | `npm run eslint && npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7283 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 7214 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7117 | `mocha tests/*.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7109 | `npm run build && istanbul cover _mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7048 | `./node_modules/.bin/mocha test` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6726 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6686 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6523 | `mocha $HARMONY_OPTS` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6468 | `BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6429 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6378 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6279 | `mocha --opts mocha.opts` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6258 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [almende/vis](https://github.com/almende/vis) | 6178 | `mocha --compilers js:babel-core/register` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6153 | `nyc mocha test/**/* -r ./test/before` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6142 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6062 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 5951 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5922 | `mocha` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5881 | `npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5777 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5728 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5620 | `npm run jshint && mocha test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5593 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5460 | `mocha tests/node.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5383 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5349 | `mocha test --recursive` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5327 | `mocha && eslint lib/**` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5320 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5269 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5231 | `mocha test/test.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5164 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5133 | `mocha src/**/*Tests.js --harmony` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5080 | `mocha --timeout 10000 && npm run lint` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 4963 | `mocha --compilers js:babel-core/register` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4922 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4922 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4756 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4713 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4653 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4613 | `mocha test` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4595 | `mocha --reporter spec -t 8000` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4591 | `mocha -R spec 'tests/app'` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4551 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4529 | `mocha ./test/runner.js` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4490 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4401 | `gulp build; mocha;` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4382 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4339 | `standard && mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4337 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4330 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4317 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4299 | `./node_modules/.bin/mocha` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 4224 | `npm run build-cli && mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4222 | `mocha -R spec ./test --recursive` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4201 | `mocha` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4197 | `mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4170 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4163 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4099 | `mocha test` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 4038 | `mocha && ./bin/shipit staging test` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4003 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3977 | `nyc mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3887 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3842 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3820 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3807 | `mocha --recursive && make test` | 
| [muicss/mui](https://github.com/muicss/mui) | 3795 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3756 | `mocha --require should --reporter spec` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3754 | `mocha --require test/babel-hook test/*.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3747 | `NODE_ENV=test mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3687 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3653 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3638 | `npm run jshint && npm run mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 3620 | `mocha; jshint *.js lib` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3592 | `nyc mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3583 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3546 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3543 | `standard && mocha --timeout 60000 test/test.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3537 | `npm run lint ; mocha && mocha test/individual` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3524 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3438 | `mocha --reporter spec --timeout 3000` | 
| [primus/primus](https://github.com/primus/primus) | 3430 | `npm run build && mocha test/*.test.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3426 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3409 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3389 | `mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3389 | `node_modules/.bin/mocha test/lib/` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3373 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3328 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3248 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3243 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3220 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3208 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3157 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3148 | `mocha --check-leaks --reporter spec --bail` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3094 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3093 | `mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3078 | `npm run lint && npm run mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3068 | `mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3057 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3055 | `./node_modules/.bin/mocha test/test.*.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3028 | `yarn run build:cjs && mocha --require babel-core/register ./test/index.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3005 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 3002 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3001 | `node_modules/.bin/mocha test/tests.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2960 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2916 | `mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2914 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2914 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2896 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2846 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2806 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2784 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2761 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2760 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2757 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2755 | `mocha --require should --reporter spec` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2732 | `mocha -R spec --recursive src/test` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 2722 | `NODE_ENV=test mocha test/**/*.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2712 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2703 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2703 | `istanbul cover _mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2687 | `mocha test/index.js && npm run demo` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2672 | `nyc mocha && tsc` | 
| [tj/should.js](https://github.com/tj/should.js) | 2660 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2649 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2646 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [github-tools/github](https://github.com/github-tools/github) | 2644 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2624 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2623 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2614 | `mocha` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2599 | `xo && mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2597 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2588 | `mocha --timeout 100000` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2583 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2576 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2571 | `mocha-phantomjs ./test/index.html` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2566 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2564 | `mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2562 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2553 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2551 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2550 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 2549 | `mocha ./test/*.spec.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2547 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2545 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2429 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2412 | `mocha --reporter=spec test/*-test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2412 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2396 | `mocha` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2395 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2391 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2363 | `node node_modules/mocha/bin/_mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2341 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2330 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2320 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2318 | `grunt jshint && mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2309 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2306 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2286 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2276 | `NODE_ENV=test mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2363 | `node node_modules/mocha/bin/_mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2341 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2340 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2330 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2320 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2318 | `grunt jshint && mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2309 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2306 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2286 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2276 | `NODE_ENV=test mocha` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2273 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2269 | `mocha test/src/**/*.unit.js` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2261 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2259 | `node_modules/.bin/mocha --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2252 | `nyc mocha 'test/**/*-test.js'` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2252 | `npm run build && cd test && mocha . --reporter dot` | 
| [mozilla/send](https://github.com/mozilla/send) | 2247 | `mocha test/unit` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2220 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2217 | `mocha test test/unit/**/*_test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2208 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2199 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [json5/json5](https://github.com/json5/json5) | 2196 | `mocha --ui exports --reporter spec` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2187 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2178 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2156 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2154 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2145 | `npm run lint && npm run build && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2139 | `mocha -R spec` | 
| [gajus/swing](https://github.com/gajus/swing) | 2124 | `mocha --compilers js:babel-register` | 
| [mde/ejs](https://github.com/mde/ejs) | 2102 | `mocha --require should --reporter spec` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2097 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2096 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2080 | `mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2035 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2034 | `cross-env BABEL_ENV=test mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2031 | `nyc --reporter=html --reporter=text mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2021 | `BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 1993 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1959 | `mocha -R spec test/*.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 1956 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1934 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1933 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1924 | `mocha --require=test/test_helper.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1897 | `mocha --bail --reporter spec --check-leaks test/` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1893 | `mocha test.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1880 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1877 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1874 | `mocha test && npm run lint` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1872 | `mocha test/index.js --reporter dot` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1868 | `mocha -c test/index.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1862 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1857 | `mocha -R landing test/index` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1844 | `mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 1841 | `mocha` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1832 | `mocha tests.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1827 | `mocha --require ./test/common --growl test/expect.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1820 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1811 | `mocha --reporter spec --timeout 5000` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1805 | `mocha --timeout 5000` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1799 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1793 | `mocha --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1785 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1775 | `cross-env NODE_ENV=test mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1773 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1765 | `mocha test/runner.js --reporter spec` | 
| [then/promise](https://github.com/then/promise) | 1756 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1752 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1743 | `mocha test` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1739 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1739 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1735 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1733 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1730 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1729 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1722 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1719 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1714 | `mocha test/*.test.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1699 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1697 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1692 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1690 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1688 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1687 | `mocha` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1684 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1683 | `mocha test` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1671 | `mocha && eslint *.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1669 | `xo && mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 1664 | `./node_modules/.bin/mocha && npm run jshint` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1662 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1656 | `./node_modules/.bin/mocha` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1653 | `npm run lint && mocha -R dot && npm run cover` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1650 | `npm run lint && mocha --recursive --exit` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1641 | `./node_modules/mocha/bin/mocha -R spec` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1641 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1636 | `mocha -R spec spec spec/reporters` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1636 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1634 | `mocha --reporter spec && npm run test-typescript` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1633 | `npm run lint && npm run mocha` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1629 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1614 | `npm run mocha && npm run karma` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1612 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1607 | `mocha tests/test.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1607 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1602 | `mocha --expose-gc --slow 300` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1600 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1592 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1571 | `mocha && npm run lint` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1569 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1566 | `mocha test/*.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1559 | `nyc npm run _mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1546 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1545 | `./node_modules/.bin/mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1543 | `npm run lint && mocha` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1538 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1538 | `mocha --reporter spec --grep .` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1534 | `npm run mocha && npm run lint` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1534 | `mocha tests --compilers js:babel-core/register` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1520 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1515 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1509 | `mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1507 | `mocha test/` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1506 | `mocha spec/` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1505 | `mocha test -u bdd -R spec` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1505 | `mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 1500 | `npm run lint && npm run mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1498 | `mocha ./test/basic.js -t 5000` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1496 | `mocha test/* --reporter spec` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1495 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1495 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1475 | `mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1470 | `mocha --reporter spec test/*.js` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1468 | `npm run test:lint && npm run test:mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1468 | `./node_modules/mocha/bin/mocha -R spec` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1466 | `mocha -R spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1463 | `npm run lint && npm run mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1462 | `mocha -u tdd` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1456 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1447 | `node_modules/.bin/mocha --recursive` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1436 | `mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1433 | `mocha --reporter spec` | 
| [samccone/drool](https://github.com/samccone/drool) | 1430 | `mocha test/tests.js --timeout=10000` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1412 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1406 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1402 | `mocha test.js` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1395 | `mocha test --timeout 600000` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1394 | `standard "src/*.js" && npm run build && mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1384 | `mocha --compilers js:babel-register` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1373 | `nyc mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1369 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1368 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1361 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1358 | `eslint --cache . && tsc && mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1358 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1358 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1358 | `mocha --check-leaks -R dot` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1356 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1346 | `standard "./src/*.js" && mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1346 | `./node_modules/mocha/bin/mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1345 | `mocha test.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1326 | `mocha --recursive` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1325 | `cross-env NODE_ENV=test nyc mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1317 | `mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1308 | `istanbul cover _mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1297 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1296 | `mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1283 | `mocha-phantomjs tests/index.html` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1273 | `mocha --check-leaks --reporter spec --bail` | 
| [zeit/ms](https://github.com/zeit/ms) | 1267 | `mocha tests.js` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1267 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1265 | `mocha --timeout 10000 ./tests/lib.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1263 | `npm run build && mocha -r should` | 
| [sandeepmistry/bleno](https://github.com/sandeepmistry/bleno) | 1262 | `mocha -R spec test/*.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1261 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1252 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1249 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1241 | `./node_modules/.bin/mocha test` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1231 | `mocha spec/exec.js` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1230 | `mocha compiled_tests/` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1229 | `mocha test/setup.js test/spec/*.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1227 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1226 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1221 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1212 | `npm run lint && npm run mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1210 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1209 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [reddit/reddit-mobile](https://github.com/reddit/reddit-mobile) | 1206 | `mocha test/index.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1202 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1202 | `mocha test/*.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1201 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1199 | `mocha test/test.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1198 | `mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1196 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1196 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1187 | `istanbul cover _mocha test -- --timeout 20000` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1185 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1184 | `mocha` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1182 | `mocha test/**/*Spec.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1177 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1176 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1171 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1169 | `mocha test` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1168 | `mocha --recursive` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1165 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1162 | `mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1161 | `eslint . && mocha -t 5000` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1159 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1157 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1146 | `mocha --check-leaks --require @babel/register` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1145 | `node ./node_modules/mocha/bin/mocha tests` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1144 | `mocha --opts test/opts/mocha.opts` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1143 | `eslint lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1143 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1128 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1128 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1111 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1098 | `npm run lint && npm run mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1098 | `mocha --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1096 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1094 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1094 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1091 | `mocha src/test.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1091 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1091 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1090 | `mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1088 | `node_modules/.bin/mocha && npm run lint` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1083 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [variety/variety](https://github.com/variety/variety) | 1096 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1094 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1094 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1091 | `mocha src/test.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1091 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1091 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1090 | `mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1088 | `node_modules/.bin/mocha && npm run lint` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1083 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1077 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1077 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1073 | `standard && istanbul cover _mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1072 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1069 | `mocha --reporter dot` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1067 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1064 | `mocha --compilers js:babel-register` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1064 | `node_modules/.bin/mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1063 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1061 | `mocha --check-leaks -t 20000` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1061 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1060 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1060 | `mocha test/unit` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1059 | `mocha test/*` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1055 | `eslint src && mocha && karma start --single-run` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1053 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1049 | `mocha --reporter spec --timeout 3000` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1048 | `mocha $(find test -name '*.test.js')` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1042 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1037 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1036 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1035 | `xo && mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1030 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1028 | `istanbul test _mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1022 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1020 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1018 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1017 | `mocha --check-leaks -R dot` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1013 | `mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1013 | `mocha --check-leaks --reporter spec --bail test/` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1012 | `NODE_PATH=. mocha **/*.spec.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1011 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1007 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1001 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 994 | `mocha test` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 993 | `istanbul cover _mocha test/*.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 991 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 990 | `mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 990 | `mocha test/tests.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 985 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 984 | `mocha tests/test-*` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 980 | `mocha --colors ./test/*.spec.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 980 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 979 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 977 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 976 | `mocha` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 965 | `mocha --recursive --bail --reporter spec test` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 961 | `mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 957 | `npm run rollup-cjs && mocha test/test.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 957 | `mocha --timeout 5000` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 954 | ` NODE_ENV=test mocha --compilers js:babel-register` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 954 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 953 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 952 | `standard && mocha` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 951 | `mocha -R list` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 951 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 947 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 945 | `mocha $(find test -name '*.test.js')` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 941 | `mocha --recursive test/unit/` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 939 | `npm run prepublish && mocha test/test.js` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 937 | `mocha --async-only` | 
| [router5/router5](https://github.com/router5/router5) | 936 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 931 | `mocha --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 930 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 926 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 926 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 926 | `mocha test` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 923 | `mocha -t 120000 test/*.test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 920 | `mocha` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 918 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 915 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 912 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 911 | `standard && mocha -b` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 908 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 906 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 903 | `mocha spec/*.spec.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 902 | `mocha --recursive test` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 902 | `webpack && mocha test/unit` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 893 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 893 | `nyc mocha --timeout=20000 test.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 892 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 891 | `mocha --reporter spec --bail --check-leaks test/` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 891 | `./node_modules/.bin/mocha --globals angular,require` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 889 | `mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 881 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 880 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 880 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 880 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [electron/asar](https://github.com/electron/asar) | 879 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 876 | `mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 875 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 874 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 874 | `mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 874 | `mocha --reporter spec --bail --check-leaks test/` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 873 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 867 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 865 | `mocha --reporter list` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 862 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 861 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 860 | `mocha "client.test" --compilers js:babel-register` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 859 | `mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 857 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 856 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 851 | `mocha --compilers js:babel-register test/*.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 851 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 850 | `mocha && standard` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 846 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 843 | `node_modules/.bin/mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 840 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 838 | `nyc mocha --require @babel/register` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 836 | `eslint test && mocha --compilers js:babel/register` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 835 | `npm run lint && mocha -R spec` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 831 | `npm run lint && npm run mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 830 | `mocha --reporter spec --bail --check-leaks test/` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 828 | `mocha ./test/test*.js --reporter spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 827 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 826 | `npm run convertto:es5 && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 826 | `mocha --timeout 200000` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 826 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 825 | `mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 823 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 821 | `mocha tests` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 819 | `node_modules/.bin/mocha test/spec` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 818 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 818 | `mocha` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 817 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 816 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 815 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 814 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 813 | `mocha --reporter spec` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 812 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 812 | `mocha && ember test` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 811 | `mocha ./test -R spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 810 | `mocha -R spec ./test/unit/**` | 
| [reactivestack/cookies](https://github.com/reactivestack/cookies) | 810 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 805 | `npm run lint && mocha --compilers js:babel-register` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 800 | `mocha tests/*.js` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 798 | `mocha --check-leaks -t 20000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 795 | `mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 792 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 790 | `mocha -R spec tests/` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 790 | `istanbul cover _mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 790 | `mocha --require babel-register` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 787 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 787 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 785 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 784 | `mocha -t 5000` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 782 | `mocha --reporter spec --bail --check-leaks test/` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 782 | `standard && standard ./bin/* && mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 781 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 779 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 778 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 777 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 775 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 774 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 770 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 769 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [edsu/anon](https://github.com/edsu/anon) | 766 | `mocha --colors --reporter spec test.js` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 766 | `mocha -R spec` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 765 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 765 | `mocha test --compilers js:babel-register` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 765 | `istanbul cover -- _mocha --reporter spec` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 764 | `mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 764 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 762 | `NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 761 | `mocha -t 600000` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 760 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 760 | `npm run lint && mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 758 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 757 | `mocha --async-only` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 757 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 756 | `nyc mocha specs` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 756 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 753 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 752 | `xo && mocha -R spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 751 | `mocha` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 734 | `mocha -R spec src/**/*_test.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 728 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 726 | `mocha --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 723 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 721 | `npm run mocha:istanbul` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 721 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 718 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 728 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 726 | `mocha --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 723 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 721 | `npm run mocha:istanbul` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 721 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 718 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 715 | `mocha test.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 712 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 708 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 707 | `cross-env NODE_ENV=test nyc mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 706 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 705 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 702 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 700 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [contra/gulp-concat](https://github.com/contra/gulp-concat) | 700 | `mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 699 | `eslint src test && mocha --compilers babel-register` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 698 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 697 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 696 | `npm run bundle && mocha` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 693 | `npm run mocha-test test/integration` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 693 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [bitpay/insight](https://github.com/bitpay/insight) | 692 | `mocha test` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 690 | `mocha tests/*.mocha.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 687 | `mocha test` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 685 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 673 | `mocha --reporter spec` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 672 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 671 | `mocha` | 
| [developit/decko](https://github.com/developit/decko) | 670 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 670 | `mocha -b -R spec test/*` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 666 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 663 | `mocha --reporter spec` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 663 | `mocha` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 663 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 663 | `mocha` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 661 | `mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 660 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 658 | `mocha --harmony --full-trace --check-leaks` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 658 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 657 | `npm run lint && mocha ./test/test.js --timeout 1000000` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 656 | `mocha --no-timeouts` | 