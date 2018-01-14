# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:18 01/14/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39506 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 38518 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 36064 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 35832 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28449 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23116 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 21634 | `mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 20143 | `mocha test/index.js` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17251 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [developit/preact](https://github.com/developit/preact) | 17168 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 15875 | `cross-env NODE_ENV=test mocha` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15328 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14483 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13668 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12685 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12408 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11943 | `mocha` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 11804 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11770 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11580 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11438 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 10784 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10629 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10402 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 10052 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9743 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9366 | `mocha --reporter spec` | 
| [tj/co](https://github.com/tj/co) | 9195 | `mocha --harmony` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9194 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9037 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tmpvar/jsdom](https://github.com/tmpvar/jsdom) | 9022 | `mocha test/index.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 8944 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 8804 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8779 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8441 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8235 | `mocha test/*-test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8116 | `mocha --check-leaks -R dot` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8070 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8044 | `mocha test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8037 | `grunt clean:test && mocha` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7677 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7648 | `./node_modules/.bin/mocha test/src` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7631 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7512 | `mocha --compilers js:babel-register test/test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7495 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7433 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7409 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [websockets/ws](https://github.com/websockets/ws) | 7263 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7218 | `npm run eslint && npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7148 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 7107 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7092 | `npm run build && istanbul cover _mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7008 | `mocha tests/*.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7004 | `./node_modules/.bin/mocha test` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6605 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6546 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6494 | `mocha $HARMONY_OPTS` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6387 | `mocha --require babel-core/register ./packages/*/test/index.js` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6386 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6311 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6189 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6168 | `mocha --opts mocha.opts` | 
| [almende/vis](https://github.com/almende/vis) | 6119 | `mocha --compilers js:babel-core/register` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6072 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6035 | `nyc mocha test/** -r ./test/before` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 5973 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5927 | `mocha` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5823 | `npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 5803 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5739 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5680 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5544 | `npm run jshint && mocha test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5499 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5422 | `mocha tests/node.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5384 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5294 | `mocha && eslint lib/**` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5294 | `mocha test --recursive` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5279 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5220 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5166 | `mocha --color` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5156 | `mocha test/test.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5127 | `mocha src/**/*Tests.js --harmony` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5024 | `mocha --timeout 10000 && npm run lint` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4869 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4865 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 4849 | `mocha --compilers js:babel-core/register` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4746 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4696 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4614 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4612 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4582 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4577 | `mocha --reporter spec -t 8000` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4524 | `mocha ./test/runner.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4461 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4408 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4376 | `gulp build; mocha;` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4373 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4316 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4304 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4297 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4276 | `./node_modules/.bin/mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4258 | `standard && mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4226 | `mocha -R spec ./test --recursive` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4138 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4138 | `mocha` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4136 | `mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4084 | `mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4047 | `mocha test` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 4016 | `mocha && ./bin/shipit staging test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3969 | `nyc mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 3935 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3886 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 3872 | `npm run build-cli && mocha` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3838 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3815 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [muicss/mui](https://github.com/muicss/mui) | 3767 | `mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3739 | `mocha --recursive && make test` | 
| [tj/ejs](https://github.com/tj/ejs) | 3730 | `mocha --require should --reporter spec` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3703 | `NODE_ENV=test mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3674 | `mocha --require test/babel-hook test/*.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3636 | `npm run jshint && npm run mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3620 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3597 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3568 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3544 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3540 | `standard && mocha --timeout 60000 test/test.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3534 | `nyc mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3512 | `mocha tests/javascript` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3491 | `npm run lint ; mocha && mocha test/individual` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3431 | `mocha --reporter spec --timeout 3000` | 
| [primus/primus](https://github.com/primus/primus) | 3419 | `npm run build && mocha test/*.test.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3419 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3383 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3382 | `mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3361 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3356 | `node_modules/.bin/mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 3317 | `mocha; jshint *.js lib` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3308 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [easy-mock/easy-mock](https://github.com/easy-mock/easy-mock) | 3209 | `cross-env NODE_ENV=test istanbul cover _mocha test/*` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3167 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3131 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3128 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3110 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3105 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3091 | `mocha --check-leaks --reporter spec --bail` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3080 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3064 | `mocha` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3060 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3047 | `./node_modules/.bin/mocha test/test.*.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3007 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 2983 | `npm run lint && npm run mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 2982 | `node_modules/.bin/mocha test/tests.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 2968 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2953 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 2951 | `nyc mocha "test/**/*.test.js"` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 2949 | `yarn run build:cjs && mocha --require babel-core/register ./test/index.js` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2905 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2895 | `mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2878 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2863 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2798 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2789 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2755 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2754 | `mocha --require should --reporter spec` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2749 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2720 | `mocha -R spec --recursive src/test` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2711 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2697 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2693 | `istanbul cover _mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2688 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2682 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2667 | `mocha test/index.js && npm run demo` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2634 | `nyc mocha && tsc` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2620 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2616 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2605 | `mocha` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2590 | `xo && mocha` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2587 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2585 | `mocha --timeout 100000` | 
| [github-tools/github](https://github.com/github-tools/github) | 2585 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2583 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2572 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2570 | `mocha-phantomjs ./test/index.html` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2560 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2547 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2534 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2526 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2523 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2520 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2516 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2515 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [css/csso](https://github.com/css/csso) | 2514 | `mocha --reporter dot` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2508 | `mocha --opts mocha.opts` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2505 | `export TESTING=true; mocha --reporter list` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2501 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2499 | `npm run mocha && npm run lint` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2476 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2473 | `mocha --recursive --watch` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2464 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2458 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2458 | `mocha --compilers js:babel-register --recursive spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2450 | `mocha` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2416 | `npm run compile && mocha --require babel-core/register` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2405 | `mocha --reporter=spec test/*-test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2401 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2390 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2386 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2365 | `node node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2360 | `mocha` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2351 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2325 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2321 | `mocha --no-colors --reporter spec` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2320 | `mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2312 | `grunt jshint && mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2294 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2275 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2270 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2269 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2255 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2254 | `mocha test/src/**/*.unit.js` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2254 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2237 | `gulp && cd test && mocha . --reporter dot` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2236 | `NODE_ENV=test mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2221 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2214 | `node_modules/.bin/mocha --reporter spec` | 
| [octokit/node-github](https://github.com/octokit/node-github) | 2210 | `nyc mocha 'test/**/*-test.js'` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2210 | `mocha test test/unit/**/*_test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2208 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mozilla/send](https://github.com/mozilla/send) | 2174 | `mocha test/unit` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2170 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2160 | `mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2158 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [json5/json5](https://github.com/json5/json5) | 2146 | `mocha --ui exports --reporter spec` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2130 | `mocha test/unit --require mochahook` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2128 | `npm run lint && npm run build && npm run mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2128 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2118 | `mocha -R spec` | 
| [gajus/swing](https://github.com/gajus/swing) | 2114 | `mocha --compilers js:babel-register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2077 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2071 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [mde/ejs](https://github.com/mde/ejs) | 2064 | `mocha --require should --reporter spec` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2062 | `mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2024 | `mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2021 | `mocha --require babel-core/register ./packages/*/test/index.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2017 | `cross-env BABEL_ENV=test mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2012 | `nyc --reporter=html --reporter=text mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 1974 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1938 | `mocha -R spec test/*.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1783 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1765 | `cross-env NODE_ENV=test mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1757 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1756 | `mocha --compilers js:babel-register` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1752 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1750 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [then/promise](https://github.com/then/promise) | 1746 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1741 | `mocha test` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1740 | `mocha test/runner.js --reporter spec` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1734 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1728 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1722 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1707 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1698 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1698 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1697 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1696 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1694 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1825 | `mocha test.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1824 | `mocha tests.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1823 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1820 | `mocha --require ./test/common --growl test/expect.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1813 | `mocha -R landing test/index` | 
| [Qix-/color](https://github.com/Qix-/color) | 1809 | `mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1807 | `mocha --timeout 5000` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1800 | `mocha --reporter spec --timeout 5000` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1800 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1783 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1765 | `cross-env NODE_ENV=test mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1757 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1756 | `mocha --compilers js:babel-register` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1752 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1750 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [then/promise](https://github.com/then/promise) | 1746 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1741 | `mocha test` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1740 | `mocha test/runner.js --reporter spec` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1734 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1728 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1722 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1707 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1705 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1698 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1698 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1697 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1696 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1694 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Hardmath123/nearley](https://github.com/Hardmath123/nearley) | 1691 | `mocha test/*.test.js` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1684 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1669 | `npm run lint && mocha --reporter spec test/*.js` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1659 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1655 | `./node_modules/.bin/mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1648 | `mocha && eslint *.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1637 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [share/sharedb](https://github.com/share/sharedb) | 1632 | `./node_modules/.bin/mocha && npm run jshint` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1627 | `mocha --reporter spec && npm run test-typescript` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1623 | `mocha -R spec spec spec/reporters` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1623 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1622 | `npm run lint && npm run mocha` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1617 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1613 | `npm run lint && mocha -R dot && npm run cover` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1612 | `./node_modules/mocha/bin/mocha -R spec` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1608 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1605 | `mocha tests/test.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1602 | `mocha --expose-gc --slow 300` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1600 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1593 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1587 | `npm run mocha && npm run karma` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1585 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1565 | `mocha test/*.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1563 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1545 | `./node_modules/.bin/mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1525 | `mocha --reporter spec --grep .` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1539 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1533 | `npm run lint && mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1532 | `nyc npm run _mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1525 | `mocha --reporter spec --grep .` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1521 | `npm run mocha && npm run lint` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1520 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1515 | `mocha tests --compilers js:babel-core/register` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1494 | `mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1491 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1490 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1490 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1488 | `mocha test -u bdd -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1488 | `mocha test/` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1485 | `mocha spec/` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1483 | `mocha ./test/basic.js -t 5000` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1481 | `mocha test/* --reporter spec` | 
| [pahen/madge](https://github.com/pahen/madge) | 1474 | `npm run lint && npm run mocha` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1467 | `mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1467 | `mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1466 | `npm run test:lint && npm run test:mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1466 | `mocha -R spec` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1463 | `./node_modules/mocha/bin/mocha -R spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1455 | `mocha -u tdd` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1454 | `npm run lint && npm run mocha` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1453 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1443 | `node_modules/.bin/mocha --recursive` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1434 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1433 | `mocha --reporter spec test/*.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1432 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1427 | `mocha test/tests.js --timeout=10000` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1418 | `mocha --reporter spec` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1403 | `mocha test.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1403 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1397 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1364 | `nyc mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1361 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1355 | `mocha --compilers js:babel-register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1355 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1352 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1352 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1350 | `standard "src/*.js" && npm run build && mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1345 | `./node_modules/mocha/bin/mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1344 | `eslint --rulesdir=dev-tools/eslint --cache . && tsc && mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1342 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1341 | `standard "./src/*.js" && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1341 | `mocha --check-leaks -R dot` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1325 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1324 | `mocha test.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1319 | `cross-env NODE_ENV=test nyc mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1317 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1317 | `mocha test --timeout 600000` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1313 | `mocha --recursive` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1299 | `istanbul cover _mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1279 | `mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1271 | `mocha-phantomjs tests/index.html` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1259 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1258 | `npm run build && mocha -r should` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1253 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1249 | `mocha --check-leaks --reporter spec --bail` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1249 | `mocha --timeout 10000 ./tests/lib.js` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1247 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [sandeepmistry/bleno](https://github.com/sandeepmistry/bleno) | 1244 | `mocha -R spec test/*.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1241 | `mocha tests.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1235 | `./node_modules/.bin/mocha test` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1226 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1224 | `mocha spec/exec.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1220 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1220 | `mocha test/setup.js test/spec/*.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1219 | `mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1212 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1209 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1202 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1200 | `mocha tests` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1199 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [reddit/reddit-mobile](https://github.com/reddit/reddit-mobile) | 1194 | `mocha test/index.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1194 | `npm run lint && npm run mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1194 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1193 | `mocha test/test.js` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1193 | `mocha compiled_tests/` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1190 | `mocha test/*.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1187 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1185 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1185 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1184 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1178 | `mocha test/**/*Spec.js` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1176 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1175 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1173 | `istanbul cover _mocha test -- --timeout 20000` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1168 | `mocha test` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1165 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1164 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1160 | `mocha --recursive` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1159 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1153 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1153 | `./node_modules/.bin/mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1151 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1139 | `node ./node_modules/mocha/bin/mocha tests` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1139 | `mocha --opts test/opts/mocha.opts` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1138 | `eslint lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1128 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1127 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1125 | `mocha --check-leaks --require @babel/register` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1122 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1122 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1108 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1094 | `npm run lint && npm run mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1093 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1091 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [normalize/mz](https://github.com/normalize/mz) | 1089 | `mocha --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1088 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1088 | `node_modules/.bin/mocha && npm run lint` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1086 | `eslint . && mocha -t 5000` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1086 | `mocha` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1079 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1076 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1074 | `mocha src/test.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1073 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1073 | `mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1066 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1060 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1060 | `mocha --compilers js:babel-register` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1059 | `mocha --check-leaks -t 20000` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1056 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1055 | `mocha test/*` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1055 | `standard && istanbul cover _mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1053 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1052 | `node_modules/.bin/mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1051 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1049 | `mocha --reporter spec --timeout 3000` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1042 | `mocha $(find test -name '*.test.js')` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1041 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1038 | `mocha --reporter dot` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1033 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1031 | `eslint src && mocha && karma start --single-run` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1030 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1030 | `xo && mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1027 | `mocha test/unit` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1026 | `istanbul test _mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1024 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1023 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1020 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1018 | `mocha --check-leaks -R dot` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1015 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1007 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1006 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1004 | `mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1002 | `NODE_PATH=. mocha **/*.spec.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 997 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 991 | `mocha --check-leaks --reporter spec --bail test/` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 989 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 985 | `mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 984 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 983 | `mocha test/tests.js` | 
| [googlevr/webvr-polyfill](https://github.com/googlevr/webvr-polyfill) | 980 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 980 | `istanbul cover _mocha test/*.js` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 980 | `mocha --colors ./test/*.spec.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 976 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 974 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 972 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 965 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 964 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 960 | `mocha --timeout 5000` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 958 | `mocha tests/test-*` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 957 | `mocha --recursive --bail --reporter spec test` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 951 | `mocha -R list` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 948 | `mocha test` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 947 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 946 | `npm run rollup-cjs && mocha test/test.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 945 | `mocha` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 943 | `standard && mocha` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 940 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 940 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 939 | ` NODE_ENV=test mocha --compilers js:babel-register` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 939 | `mocha --recursive test/unit/` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 939 | `mocha $(find test -name '*.test.js')` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 932 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 929 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 927 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 927 | `mocha --reporter spec` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 924 | `npm run prepublish && mocha test/test.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 921 | `mocha test` | 
| [router5/router5](https://github.com/router5/router5) | 920 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 913 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 910 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 909 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 906 | `mocha -t 120000 test/*.test.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 905 | `mocha ./test/index.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 903 | `standard && mocha -b` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 902 | `mocha spec/*.spec.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 901 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 900 | `mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 893 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 892 | `./node_modules/.bin/mocha --globals angular,require` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 890 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 887 | `webpack && mocha test/unit` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 885 | `mocha` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 881 | `mocha --recursive test` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 880 | `mocha --reporter spec --bail --check-leaks test/` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 879 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 878 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 876 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 874 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [electron/asar](https://github.com/electron/asar) | 874 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 873 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 871 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 870 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 865 | `mocha --reporter list` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 863 | `nyc mocha --timeout=20000 test.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 862 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 861 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 861 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 860 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 854 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 854 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 854 | `mocha --reporter spec --bail --check-leaks test/` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 853 | `mocha "client.test" --compilers js:babel-register` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 850 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 847 | `mocha && standard` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 845 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 844 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 842 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 841 | `mocha --compilers js:babel-register test/*.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 840 | `node_modules/.bin/mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 833 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 833 | `eslint test && mocha --compilers js:babel/register` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 831 | `npm run lint && mocha -R spec` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 827 | `npm run lint && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 826 | `mocha --timeout 200000` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 826 | `mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 823 | `mocha --reporter spec --bail --check-leaks test/` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 820 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 818 | `nyc mocha --require babel-register` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 816 | `node_modules/.bin/mocha test/spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 816 | `mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 815 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 814 | `mocha --reporter spec` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 815 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 814 | `mocha --reporter spec` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 814 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 810 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 810 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 809 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 808 | `npm run convertto:es5 && npm run mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 808 | `mocha && ember test` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 807 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 807 | `mocha tests` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 807 | `mocha tests/*.test.js --reporter spec` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 807 | `mocha` | 
| [reactivestack/cookies](https://github.com/reactivestack/cookies) | 799 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 799 | `mocha ./test/test*.js --reporter spec` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 798 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 797 | `mocha ./test -R spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 795 | `mocha --check-leaks -t 20000` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 791 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 790 | `mocha -u tdd` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 788 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 788 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 786 | `mocha --require babel-register` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 784 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 784 | `istanbul cover _mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 783 | `npm run lint && mocha --compilers js:babel-register` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 782 | `mocha -R spec ./test/unit/**` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 780 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 780 | `standard && standard ./bin/* && mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 778 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 778 | `cake build && mocha ./test/mocha/*.coffee` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 778 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 777 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 776 | `mocha -t 5000` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 774 | `mocha --reporter spec --bail --check-leaks test/` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 774 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 766 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 764 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 763 | `mocha --colors --reporter spec test.js` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 761 | `mocha test --compilers js:babel-register` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 760 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 760 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 760 | `istanbul cover -- _mocha --reporter spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 757 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 757 | `npm run lint && mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 753 | `mocha -t 600000` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 753 | `mocha -R spec` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 753 | `mocha` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 752 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 751 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 751 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 751 | `mocha --async-only` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 750 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 748 | `nyc mocha specs` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 748 | `xo && mocha -R spec` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 745 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 742 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 740 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 738 | `mocha --ui tdd --require ./test/__setup` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 734 | `mocha -R spec src/**/*_test.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 733 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 730 | `mocha tests/*.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 730 | `mocha spec/*.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 730 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 728 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 727 | `mocha --reporter list` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 726 | `mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 725 | `./node_modules/.bin/mocha -R spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 722 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 720 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 712 | `mocha test.js` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 711 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 711 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 707 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 706 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require babel-register --no-timeouts` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 701 | `cross-env NODE_ENV=test nyc mocha` | 
| [contra/gulp-concat](https://github.com/contra/gulp-concat) | 699 | `mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 696 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 695 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 693 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 693 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 692 | `npm run bundle && mocha` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 690 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 689 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 688 | `npm run mocha-test test/integration` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 686 | `mocha tests/*.mocha.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 681 | `mocha test` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 680 | `npm run lint && mocha test` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 680 | `npm run build && istanbul test _mocha test/test.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 679 | `npm run mocha:istanbul` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 678 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 678 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 677 | `mocha ./test/index.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 677 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 676 | `eslint src test && mocha --compilers babel-register` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 673 | `mocha test` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 671 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 670 | `mocha -b -R spec test/*` | 
| [bitpay/insight](https://github.com/bitpay/insight) | 670 | `mocha test` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 669 | `mocha --reporter spec` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 666 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 665 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 664 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 664 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 663 | `mocha` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 663 | `mocha --reporter spec` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 663 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 661 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 661 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 