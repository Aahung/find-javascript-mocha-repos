# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:17 01/06/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39452 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 38316 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 35935 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 35581 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28357 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23061 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 20001 | `mocha test/index.js` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17163 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [developit/preact](https://github.com/developit/preact) | 17030 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15273 | `mocha` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 14685 | `cross-env NODE_ENV=test mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14414 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13643 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12544 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12363 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11930 | `mocha` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 11764 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11708 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11552 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11397 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 10679 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10544 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10358 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 9964 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9680 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9318 | `mocha --reporter spec` | 
| [tj/co](https://github.com/tj/co) | 9170 | `mocha --harmony` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9142 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9000 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tmpvar/jsdom](https://github.com/tmpvar/jsdom) | 8969 | `mocha test/index.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 8908 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 8763 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8754 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8417 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8204 | `mocha test/*-test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8112 | `mocha --check-leaks -R dot` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8032 | `mocha test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8032 | `grunt clean:test && mocha` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7668 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7628 | `./node_modules/.bin/mocha test/src` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7591 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7443 | `mocha --compilers js:babel-register test/test.js` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7430 | `mocha` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7416 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7410 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7205 | `npm run eslint && npm run mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 7185 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7080 | `npm run build && istanbul cover _mocha` | 
| [amark/gun](https://github.com/amark/gun) | 7046 | `mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7026 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 6983 | `./node_modules/.bin/mocha test` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 6973 | `mocha tests/*.js` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6545 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6478 | `mocha $HARMONY_OPTS` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6477 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6354 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6277 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6265 | `mocha --require babel-core/register ./packages/*/test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6159 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6094 | `mocha --opts mocha.opts` | 
| [almende/vis](https://github.com/almende/vis) | 6093 | `mocha --compilers js:babel-core/register` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6029 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 5958 | `nyc mocha test/** -r ./test/before` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5928 | `mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 5923 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5784 | `npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5718 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 5708 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5653 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5513 | `npm run jshint && mocha test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5458 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5395 | `mocha tests/node.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5384 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5290 | `mocha && eslint lib/**` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5269 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5268 | `mocha test --recursive` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5200 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5163 | `mocha --color` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5130 | `mocha test/test.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5120 | `mocha src/**/*Tests.js --harmony` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5013 | `mocha --timeout 10000 && npm run lint` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4850 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4830 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 4788 | `mocha --compilers js:babel-core/register` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4739 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4688 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4609 | `mocha test` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4604 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4575 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4571 | `mocha --reporter spec -t 8000` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4517 | `mocha ./test/runner.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4415 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4385 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4370 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4366 | `gulp build; mocha;` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4305 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4282 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4275 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4257 | `./node_modules/.bin/mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4236 | `standard && mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4224 | `mocha -R spec ./test --recursive` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4128 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4124 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4108 | `mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4024 | `mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4015 | `mocha test` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 3996 | `mocha && ./bin/shipit staging test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3960 | `nyc mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 3906 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3888 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3832 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3813 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [muicss/mui](https://github.com/muicss/mui) | 3759 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3721 | `mocha --require should --reporter spec` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3714 | `mocha --recursive && make test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3663 | `NODE_ENV=test mocha` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 3659 | `npm run build-cli && mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3634 | `npm run jshint && npm run mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3631 | `mocha --require test/babel-hook test/*.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3569 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3566 | `npm run lint && npm run mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3559 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3543 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3540 | `standard && mocha --timeout 60000 test/test.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3509 | `mocha tests/javascript` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3471 | `npm run lint ; mocha && mocha test/individual` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3426 | `nyc mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3421 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3416 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [primus/primus](https://github.com/primus/primus) | 3410 | `npm run build && mocha test/*.test.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3381 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3377 | `mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3350 | `node_modules/.bin/mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3346 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3292 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [easy-mock/easy-mock](https://github.com/easy-mock/easy-mock) | 3180 | `cross-env NODE_ENV=test istanbul cover _mocha test/*` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3119 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 3115 | `mocha; jshint *.js lib` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3110 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3099 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3077 | `mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3076 | `mocha --check-leaks --reporter spec --bail` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3065 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3061 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3046 | `./node_modules/.bin/mocha test/test.*.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3044 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3042 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 2981 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 2979 | `node_modules/.bin/mocha test/tests.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2948 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [expressjs/session](https://github.com/expressjs/session) | 2941 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 2930 | `npm run lint && npm run mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 2926 | `nyc mocha "test/**/*.test.js"` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2896 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2886 | `mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2857 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2843 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 2794 | `yarn run build:cjs && mocha --require babel-core/register ./test/index.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2789 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2775 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2754 | `mocha --require should --reporter spec` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2745 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2744 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2708 | `mocha -R spec --recursive src/test` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2693 | `istanbul cover _mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2690 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2682 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2681 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2650 | `mocha test/index.js && npm run demo` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2642 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2616 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2612 | `nyc mocha && tsc` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2599 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2594 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2587 | `xo && mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2586 | `mocha --timeout 100000` | 
| [github-tools/github](https://github.com/github-tools/github) | 2578 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2570 | `mocha-phantomjs ./test/index.html` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2564 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2563 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2562 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2543 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2533 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2524 | `mocha` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2517 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2508 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2508 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [css/csso](https://github.com/css/csso) | 2505 | `mocha --reporter dot` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2505 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2503 | `export TESTING=true; mocha --reporter list` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2492 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2488 | `mocha --opts mocha.opts` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2482 | `npm run mocha && npm run lint` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2470 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2468 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2466 | `mocha --recursive --watch` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2439 | `mocha --compilers js:babel-register --recursive spec` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2434 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2428 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2428 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2402 | `mocha --reporter=spec test/*-test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2393 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2386 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2373 | `npm run compile && mocha --require babel-core/register` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2366 | `node node_modules/mocha/bin/_mocha` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2363 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2342 | `mocha` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2338 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2319 | `mocha --no-colors --reporter spec` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2316 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2310 | `mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2310 | `grunt jshint && mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2289 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2254 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2252 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2251 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2251 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2245 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2241 | `mocha test` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2220 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2217 | `gulp && cd test && mocha . --reporter dot` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2211 | `NODE_ENV=test mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2208 | `mocha test test/unit/**/*_test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2208 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [octokit/node-github](https://github.com/octokit/node-github) | 2200 | `nyc mocha test/**/*-test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2198 | `node_modules/.bin/mocha --reporter spec` | 
| [mozilla/send](https://github.com/mozilla/send) | 2163 | `mocha test/unit` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2145 | `mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2141 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2136 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2122 | `npm run lint && npm run build && npm run mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2115 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2112 | `mocha test/unit --require mochahook` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2108 | `mocha -R spec` | 
| [gajus/swing](https://github.com/gajus/swing) | 2108 | `mocha --compilers js:babel-register` | 
| [json5/json5](https://github.com/json5/json5) | 2096 | `mocha --ui exports --reporter spec` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2075 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2057 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2043 | `mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2036 | `mocha --require should --reporter spec` | 
| [slate/slate](https://github.com/slate/slate) | 2022 | `mocha --require babel-core/register ./packages/*/test/index.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2021 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2013 | `cross-env BABEL_ENV=test mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 1986 | `nyc --reporter=html --reporter=text mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 1966 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1919 | `mocha -R spec test/*.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1916 | `mocha --require=test/test_helper.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1899 | `mocha --bail --reporter spec --check-leaks test/` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1886 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1871 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 1865 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1861 | `mocha test/index.js --reporter dot` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 1860 | `mocha ./test/*.spec.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1857 | `mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1857 | `mocha` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 1850 | `export TESTING=true; mocha --reporter list` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1839 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1824 | `mocha` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1824 | `mocha tests.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1823 | `mocha test && npm run lint` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1815 | `mocha --require ./test/common --growl test/expect.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1813 | `mocha -c test/index.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1809 | `mocha --timeout 5000` | 
| [Qix-/color](https://github.com/Qix-/color) | 1802 | `mocha` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1797 | `mocha --reporter spec --timeout 5000` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1793 | `mocha test.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1787 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1784 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1778 | `mocha -R landing test/index` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1763 | `cross-env NODE_ENV=test mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1742 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1740 | `mocha test` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1738 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1738 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [then/promise](https://github.com/then/promise) | 1736 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1735 | `mocha test/**/*_test.js --bail` | 
| [verdaccio/verdaccio](https://github.com/verdaccio/verdaccio) | 1733 | `mocha ./test/functional ./test/unit --reporter=spec --full-trace` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1732 | `mocha --compilers js:babel-register` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1727 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1725 | `mocha test/runner.js --reporter spec` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1723 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1715 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1697 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1696 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1695 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1694 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1690 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1684 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1683 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1681 | `mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1679 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1671 | `xo && mocha` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1665 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1662 | `npm run lint && npm run compile && mocha --reporter spec test/*.js` | 
| [Hardmath123/nearley](https://github.com/Hardmath123/nearley) | 1661 | `mocha test/*.test.js` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1656 | `mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1655 | `mocha` | 
| [KunalKapadia/express-mongoose-es6-rest-api](https://github.com/KunalKapadia/express-mongoose-es6-rest-api) | 1652 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1649 | `./node_modules/.bin/mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1637 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1635 | `mocha && eslint *.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1622 | `mocha --reporter spec && npm run test-typescript` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1621 | `mocha -R spec spec spec/reporters` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1617 | `npm run lint && npm run mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1616 | `lint && mocha --recursive` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1613 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1609 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1605 | `mocha tests/test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1600 | `mocha --expose-gc --slow 300` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1597 | `./node_modules/mocha/bin/mocha -R spec` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1588 | `npm run lint && mocha -R dot && npm run cover` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1586 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1581 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1580 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1571 | `npm run mocha && npm run karma` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1558 | `mocha test/*.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1556 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1545 | `./node_modules/.bin/mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1536 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1536 | `mocha && npm run lint` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1531 | `npm run lint && mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1520 | `mocha --reporter spec --grep .` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1516 | `nyc npm run _mocha` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1512 | `npm run mocha && npm run lint` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1510 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1501 | `mocha tests --compilers js:babel-core/register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1489 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1489 | `mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1489 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1479 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1475 | `mocha test/` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1474 | `mocha test -u bdd -R spec` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1474 | `mocha ./test/basic.js -t 5000` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1470 | `mocha spec/` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1468 | `mocha test/* --reporter spec` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1464 | `mocha -R spec` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1464 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1463 | `./node_modules/mocha/bin/mocha -R spec` | 
| [pahen/madge](https://github.com/pahen/madge) | 1454 | `npm run lint && npm run mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1454 | `mocha -u tdd` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1448 | `mocha` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1447 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1446 | `npm run lint && npm run mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1441 | `node_modules/.bin/mocha --recursive` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1437 | `npm run test:lint && npm run test:mocha && npm run site` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1432 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1427 | `mocha test/tests.js --timeout=10000` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1415 | `mocha --reporter spec` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1409 | `mocha --reporter spec test/*.js` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1403 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1402 | `mocha test.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1399 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1388 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1362 | `nyc mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 1362 | `./node_modules/.bin/mocha && npm run jshint` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1361 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1356 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1350 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1343 | `./node_modules/mocha/bin/mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1341 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1339 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1337 | `eslint --rulesdir=dev-tools/eslint --cache . && tsc && mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1336 | `standard "./src/*.js" && mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1335 | `mocha --compilers js:babel-register` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1333 | `mocha --check-leaks -R dot` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1323 | `standard "src/*.js" && npm run build && mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1316 | `cross-env NODE_ENV=test nyc mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1316 | `mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1314 | `mocha test.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1309 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1302 | `mocha --recursive` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1295 | `istanbul cover _mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1264 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1260 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1256 | `npm run build && mocha -r should` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1250 | `mocha-phantomjs tests/index.html` | 
| [sandeepmistry/bleno](https://github.com/sandeepmistry/bleno) | 1239 | `mocha -R spec test/*.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1237 | `mocha --timeout 10000 ./tests/lib.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1235 | `mocha --check-leaks --reporter spec --bail` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1235 | `mocha test --timeout 600000` | 
| [zeit/ms](https://github.com/zeit/ms) | 1232 | `mocha tests.js` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1230 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1228 | `./node_modules/.bin/mocha test` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1222 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1219 | `mocha spec/exec.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1215 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1214 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1211 | `mocha test/setup.js test/spec/*.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1210 | `mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1209 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [electron/devtron](https://github.com/electron/devtron) | 1205 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1197 | `mocha tests` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1195 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [reddit/reddit-mobile](https://github.com/reddit/reddit-mobile) | 1193 | `mocha test/index.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1193 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1192 | `mocha test/test.js` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1187 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1185 | `npm run lint && npm run mocha` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1185 | `mocha test/*.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1182 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1179 | `mocha test/**/*Spec.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1179 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1178 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1178 | `mocha compiled_tests/` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1176 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1176 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1173 | `mocha` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1168 | `istanbul cover _mocha test -- --timeout 20000` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1165 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1164 | `mocha test` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1157 | `mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1155 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1154 | `mocha --recursive` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1149 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1148 | `./node_modules/.bin/mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1147 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1139 | `node ./node_modules/mocha/bin/mocha tests` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1138 | `mocha --opts test/opts/mocha.opts` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1133 | `eslint lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1129 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1121 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1120 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1119 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1116 | `mocha --check-leaks --require @babel/register` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1105 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1093 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1091 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1090 | `npm run lint && npm run mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1087 | `node_modules/.bin/mocha && npm run lint` | 
| [normalize/mz](https://github.com/normalize/mz) | 1085 | `mocha --reporter spec` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [variety/variety](https://github.com/variety/variety) | 1081 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1079 | `mocha` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1072 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1071 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1069 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1067 | `mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1066 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1060 | `mocha --check-leaks -t 20000` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1059 | `mocha src/test.js` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1058 | `mocha --compilers js:babel-register` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1054 | `mocha test/*` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1053 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1052 | `eslint . && mocha -t 5000` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1052 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1050 | `mocha --reporter spec --timeout 3000` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1046 | `node_modules/.bin/mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1040 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1039 | `standard && istanbul cover _mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1038 | `mocha $(find test -name '*.test.js')` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1036 | `mocha --reporter dot` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1036 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1035 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1028 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1028 | `xo && mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1024 | `istanbul test _mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1024 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [jas/playground](https://github.com/jas/playground) | 1022 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1018 | `mocha test/unit` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1017 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1017 | `mocha --check-leaks -R dot` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1015 | `eslint src && mocha && karma start --single-run` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1014 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1009 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1005 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1003 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 999 | `mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 998 | `NODE_PATH=. mocha **/*.spec.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 989 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 989 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 982 | `mocha test/tests.js` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 981 | `mocha --colors ./test/*.spec.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 981 | `mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 980 | `mocha --check-leaks --reporter spec --bail test/` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 978 | `istanbul cover _mocha test/*.js` | 
| [googlevr/webvr-polyfill](https://github.com/googlevr/webvr-polyfill) | 977 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 973 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 969 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 964 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 959 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 959 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 959 | `mocha --timeout 5000` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 953 | `mocha --recursive --bail --reporter spec test` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 952 | `mocha tests/test-*` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 950 | `mocha -R list` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 946 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 946 | `npm run rollup-cjs && mocha test/test.js` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 942 | `standard && mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 940 | `mocha` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 939 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 938 | `mocha --recursive test/unit/` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 938 | `mocha $(find test -name '*.test.js')` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 933 | `mocha test` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 932 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 927 | ` NODE_ENV=test mocha --compilers js:babel-register` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 926 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 925 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 923 | `mocha --reporter spec` | 
| [tomas/needle](https://github.com/tomas/needle) | 918 | `mocha test` | 
| [router5/router5](https://github.com/router5/router5) | 917 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 915 | `npm run prepublish && mocha test/test.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 914 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 913 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 904 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 903 | `mocha ./test/index.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 902 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 902 | `mocha spec/*.spec.js` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 901 | `mocha -t 120000 test/*.test.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 900 | `standard && mocha -b` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 895 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 894 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 892 | `./node_modules/.bin/mocha --globals angular,require` | 
| [teambit/bit](https://github.com/teambit/bit) | 886 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 884 | `webpack && mocha test/unit` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 883 | `mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 879 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 878 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 876 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 876 | `nyc mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 875 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 874 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [electron/asar](https://github.com/electron/asar) | 871 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 871 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 870 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 869 | `mocha --recursive test` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 868 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 865 | `mocha --reporter list` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 860 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 859 | `mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 857 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 854 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 852 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 851 | `mocha "client.test" --compilers js:babel-register` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 850 | `mocha --reporter spec --bail --check-leaks test/` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 849 | `nyc mocha --timeout=20000 test.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 845 | `mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 843 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 841 | `node_modules/.bin/mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 839 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 838 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [electron/spectron](https://github.com/electron/spectron) | 836 | `mocha && standard` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 835 | `mocha --compilers js:babel-register test/*.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 832 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 831 | `eslint test && mocha --compilers js:babel/register` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 828 | `npm run lint && mocha -R spec` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 824 | `mocha --timeout 200000` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 824 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 824 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 824 | `mocha` | 
| [MaxCDN/bootstrap-cdn](https://github.com/MaxCDN/bootstrap-cdn) | 823 | `npm run lint && npm run mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 821 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 820 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 819 | `mocha --reporter spec --bail --check-leaks test/` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 816 | `node_modules/.bin/mocha test/spec` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 815 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 812 | `mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 811 | `mocha --reporter spec` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 811 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 810 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 807 | `mocha tests/*.test.js --reporter spec` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 807 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 807 | `mocha && ember test` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 806 | `nyc mocha --require babel-register` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 805 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 803 | `mocha tests` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 798 | `npm run convertto:es5 && npm run mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 796 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 795 | `mocha --check-leaks -t 20000` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 791 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 790 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 789 | `mocha -R spec tests/` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 789 | `mocha ./test/test*.js --reporter spec` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 788 | `mocha ./test -R spec` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 787 | `mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 786 | `mocha -u tdd` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 785 | `mocha --require babel-register` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 783 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 783 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 783 | `istanbul cover _mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 777 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 777 | `cake build && mocha ./test/mocha/*.coffee` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 777 | `mocha -t 5000` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 776 | `standard && standard ./bin/* && mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 775 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 774 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 773 | `nyc mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 773 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 770 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 767 | `npm run lint && mocha --compilers js:babel-register` | 
| [edsu/anon](https://github.com/edsu/anon) | 764 | `mocha --colors --reporter spec test.js` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 764 | `mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 762 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 761 | `mocha -R spec ./test/unit/**` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 759 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 759 | `mocha test --compilers js:babel-register` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 756 | `istanbul cover -- _mocha --reporter spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 754 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 752 | `TEST_MODE=unit NODE_ENV=test jest && TEST_MODE=unit NODE_ENV=test mocha -R ${MOCHA_REPORTER:-spec}` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 751 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 750 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 748 | `npm run lint && mocha` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 748 | `mocha -R spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 748 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 747 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 746 | `nyc mocha specs` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 745 | `mocha -t 600000` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 745 | `mocha --async-only` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 744 | `xo && mocha -R spec` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 743 | `mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 740 | `mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 739 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 733 | `mocha -R spec src/**/*_test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 733 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 729 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 728 | `mocha --ui tdd --require ./test/__setup` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 728 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 727 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 726 | `mocha --reporter spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 725 | `mocha --reporter list` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 725 | `mocha spec/*.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 723 | `./node_modules/.bin/mocha -R spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 722 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 721 | `mocha tests/*.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 718 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 711 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 708 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 708 | `mocha test.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 705 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 700 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require babel-register --no-timeouts` | 
| [contra/gulp-concat](https://github.com/contra/gulp-concat) | 699 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 696 | `cross-env NODE_ENV=test nyc mocha` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 695 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 692 | `npm run bundle && mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 687 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 686 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 686 | `npm run mocha-test test/integration` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 684 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 683 | `mocha tests/*.mocha.js` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 679 | `npm run lint && mocha test` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 677 | `mocha ./test/index.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 676 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 676 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 676 | `npm run build && istanbul test _mocha test/test.js` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 675 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 674 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 673 | `mocha test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 673 | `eslint src test && mocha --compilers babel-register` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 670 | `mocha -b -R spec test/*` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 670 | `mocha test` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 669 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 666 | `mocha --reporter spec` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 663 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 663 | `mocha --reporter spec` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 663 | `mocha` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 662 | `mocha` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 662 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 661 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 660 | `mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 658 | `npm run mocha:istanbul` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 654 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 