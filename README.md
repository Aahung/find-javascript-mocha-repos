# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:31 01/19/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39550 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 38652 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 36165 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 36086 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28505 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23165 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 20237 | `mocha test/index.js` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17298 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [developit/preact](https://github.com/developit/preact) | 17258 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 16807 | `cross-env NODE_ENV=test mocha` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15379 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14551 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13684 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12744 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12445 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11953 | `mocha` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 11874 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11807 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11606 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11467 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 10870 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10687 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10428 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 10118 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9774 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9412 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9229 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 9218 | `mocha --harmony` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9069 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tmpvar/jsdom](https://github.com/tmpvar/jsdom) | 9058 | `mocha test/index.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 8965 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 8838 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8794 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8460 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8256 | `mocha test/*-test.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8121 | `mocha` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8118 | `mocha --check-leaks -R dot` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8053 | `mocha test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8047 | `grunt clean:test && mocha` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7690 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7681 | `./node_modules/.bin/mocha test/src` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7661 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7580 | `mocha --compilers js:babel-register test/test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7551 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7437 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7410 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [websockets/ws](https://github.com/websockets/ws) | 7331 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7232 | `npm run eslint && npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7190 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 7147 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7097 | `npm run build && istanbul cover _mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7044 | `mocha tests/*.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7022 | `./node_modules/.bin/mocha test` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6651 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6621 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6510 | `mocha $HARMONY_OPTS` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6433 | `mocha --require babel-core/register ./packages/*/test/index.js` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6407 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6339 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6223 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6201 | `mocha --opts mocha.opts` | 
| [almende/vis](https://github.com/almende/vis) | 6134 | `mocha --compilers js:babel-core/register` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6101 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6078 | `nyc mocha test/** -r ./test/before` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6015 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5927 | `mocha` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 5865 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5849 | `npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5752 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5698 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5558 | `npm run jshint && mocha test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5544 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5437 | `mocha tests/node.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5382 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5309 | `mocha test --recursive` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5308 | `mocha && eslint lib/**` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5299 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5243 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5187 | `mocha test/test.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5166 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5130 | `mocha src/**/*Tests.js --harmony` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5040 | `mocha --timeout 10000 && npm run lint` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 4901 | `mocha --compilers js:babel-core/register` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4892 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4886 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4750 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4702 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4627 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4612 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4584 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4582 | `mocha --reporter spec -t 8000` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4524 | `mocha ./test/runner.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4509 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4441 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4387 | `gulp build; mocha;` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4376 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4318 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4317 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4311 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4285 | `standard && mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4282 | `./node_modules/.bin/mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4225 | `mocha -R spec ./test --recursive` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4160 | `mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4149 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4147 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4140 | `mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4072 | `mocha test` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 4024 | `mocha && ./bin/shipit staging test` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 4013 | `npm run build-cli && mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3976 | `nyc mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 3961 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3887 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3840 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3818 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3777 | `mocha --recursive && make test` | 
| [muicss/mui](https://github.com/muicss/mui) | 3777 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3737 | `mocha --require should --reporter spec` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3722 | `NODE_ENV=test mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3700 | `mocha --require test/babel-hook test/*.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3645 | `npm run lint && npm run mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3638 | `npm run jshint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3621 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3576 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3564 | `nyc mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3545 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3540 | `standard && mocha --timeout 60000 test/test.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3517 | `mocha tests/javascript` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3504 | `npm run lint ; mocha && mocha test/individual` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 3456 | `mocha; jshint *.js lib` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3431 | `mocha --reporter spec --timeout 3000` | 
| [primus/primus](https://github.com/primus/primus) | 3422 | `npm run build && mocha test/*.test.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3422 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3386 | `mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3385 | `node_modules/.bin/mocha test/lib/` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3380 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3361 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3313 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3187 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3165 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3157 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3147 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3134 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3106 | `mocha --check-leaks --reporter spec --bail` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3084 | `mocha` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3074 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3066 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3048 | `./node_modules/.bin/mocha test/test.*.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3031 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3031 | `npm run lint && npm run mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 2989 | `yarn run build:cjs && mocha --require babel-core/register ./test/index.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 2987 | `node_modules/.bin/mocha test/tests.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 2982 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 2975 | `nyc mocha "test/**/*.test.js"` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2957 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2907 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2900 | `mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2893 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2880 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2805 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2799 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2760 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2754 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2754 | `mocha --require should --reporter spec` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2736 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2724 | `mocha -R spec --recursive src/test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2711 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2700 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2696 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2696 | `istanbul cover _mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2673 | `mocha test/index.js && npm run demo` | 
| [tj/should.js](https://github.com/tj/should.js) | 2657 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2647 | `nyc mocha && tsc` | 
| [github-tools/github](https://github.com/github-tools/github) | 2641 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2634 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2621 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2607 | `mocha` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2603 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2592 | `xo && mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2591 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2587 | `mocha --timeout 100000` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2580 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2572 | `mocha-phantomjs ./test/index.html` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2566 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2555 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2545 | `mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2543 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2533 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2529 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2529 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2528 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2525 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2520 | `mocha --opts mocha.opts` | 
| [css/csso](https://github.com/css/csso) | 2517 | `mocha --reporter dot` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2507 | `npm run mocha && npm run lint` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2483 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2480 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2479 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2477 | `mocha --recursive --watch` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2471 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2466 | `mocha --compilers js:babel-register --recursive spec` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2442 | `npm run compile && mocha --require babel-core/register` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2408 | `mocha --reporter=spec test/*-test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2408 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2406 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2391 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2371 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2370 | `mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2365 | `node node_modules/mocha/bin/_mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2330 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2322 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2322 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2317 | `grunt jshint && mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2302 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2298 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2290 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2277 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2264 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2260 | `mocha test/src/**/*.unit.js` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2260 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2252 | `NODE_ENV=test mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2243 | `gulp && cd test && mocha . --reporter dot` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2236 | `node_modules/.bin/mocha --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2225 | `nyc mocha 'test/**/*-test.js'` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2220 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mozilla/send](https://github.com/mozilla/send) | 2219 | `mocha test/unit` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2214 | `mocha test test/unit/**/*_test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2209 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2178 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2172 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [json5/json5](https://github.com/json5/json5) | 2168 | `mocha --ui exports --reporter spec` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2167 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2137 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2135 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2134 | `npm run lint && npm run build && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2126 | `mocha -R spec` | 
| [gajus/swing](https://github.com/gajus/swing) | 2116 | `mocha --compilers js:babel-register` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2084 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2079 | `mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2076 | `mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2075 | `mocha --require should --reporter spec` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2032 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2026 | `cross-env BABEL_ENV=test mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2021 | `mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2020 | `nyc --reporter=html --reporter=text mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 1981 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1948 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1925 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 1923 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1920 | `mocha --require=test/test_helper.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1905 | `mocha && eslint .` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1900 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1876 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 1875 | `mocha ./test/*.spec.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1875 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1867 | `mocha test/index.js --reporter dot` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1858 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1856 | `mocha -c test/index.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1854 | `mocha test && npm run lint` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1848 | `mocha test.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1840 | `mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1833 | `mocha -R landing test/index` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1829 | `mocha tests.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1823 | `mocha --require ./test/common --growl test/expect.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 1817 | `mocha` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1812 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1807 | `mocha --timeout 5000` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1804 | `mocha --reporter spec --timeout 5000` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1783 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1772 | `mocha --compilers js:babel-register` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1770 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1767 | `cross-env NODE_ENV=test mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1760 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1760 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1750 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [then/promise](https://github.com/then/promise) | 1747 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1747 | `mocha test/runner.js --reporter spec` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1736 | `mocha test/**/*_test.js --bail` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1729 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1724 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1714 | `mocha --compilers js:babel-core/register __tests__` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1714 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1709 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1708 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1696 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [Hardmath123/nearley](https://github.com/Hardmath123/nearley) | 1695 | `mocha test/*.test.js` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1694 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1690 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1688 | `npm run jshint && mocha --recursive` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1684 | `mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1683 | `mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1694 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1690 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1688 | `npm run jshint && mocha --recursive` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1684 | `mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1683 | `mocha` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1678 | `mocha test` | 
| [KunalKapadia/express-mongoose-es6-rest-api](https://github.com/KunalKapadia/express-mongoose-es6-rest-api) | 1676 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1673 | `npm run lint && mocha --reporter spec test/*.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1660 | `mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1659 | `mocha && eslint *.js` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1656 | `./node_modules/.bin/mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 1646 | `./node_modules/.bin/mocha && npm run jshint` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1639 | `npm run lint && mocha --recursive` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1635 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1631 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1630 | `mocha --reporter spec && npm run test-typescript` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1628 | `npm run lint && mocha -R dot && npm run cover` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1627 | `npm run lint && npm run mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1626 | `mocha -R spec spec spec/reporters` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1623 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1621 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1618 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1609 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1606 | `mocha tests/test.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1603 | `mocha --expose-gc --slow 300` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1595 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1594 | `npm run mocha && npm run karma` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1588 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1567 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1565 | `mocha test/*.js` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1527 | `mocha` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1525 | `npm run mocha && npm run lint` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1523 | `mocha tests --compilers js:babel-core/register` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1504 | `mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1496 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1494 | `mocha test -u bdd -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1493 | `mocha test/` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1492 | `mocha ./test/basic.js -t 5000` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1492 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1490 | `mocha spec/` | 
| [pahen/madge](https://github.com/pahen/madge) | 1490 | `npm run lint && npm run mocha` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1485 | `mocha` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1478 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1471 | `mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1467 | `npm run test:lint && npm run test:mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1466 | `./node_modules/mocha/bin/mocha -R spec` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1496 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1494 | `mocha test -u bdd -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1493 | `mocha test/` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1492 | `mocha ./test/basic.js -t 5000` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1492 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1492 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1490 | `mocha spec/` | 
| [pahen/madge](https://github.com/pahen/madge) | 1490 | `npm run lint && npm run mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1488 | `mocha test/* --reporter spec` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1485 | `mocha` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1478 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1471 | `mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1468 | `mocha -R spec` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1467 | `npm run test:lint && npm run test:mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1466 | `./node_modules/mocha/bin/mocha -R spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1456 | `npm run lint && npm run mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1456 | `mocha -u tdd` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1454 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1451 | `mocha --reporter spec test/*.js` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1444 | `node_modules/.bin/mocha --recursive` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1433 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1427 | `mocha test/tests.js --timeout=10000` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1425 | `mocha --reporter spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1407 | `mocha test/**/*.spec.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1402 | `mocha test.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1400 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1368 | `standard "src/*.js" && npm run build && mocha` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1367 | `nyc mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1364 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1360 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1360 | `mocha --compilers js:babel-register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1358 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1354 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1352 | `eslint --rulesdir=dev-tools/eslint --cache . && tsc && mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1347 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1347 | `mocha --check-leaks -R dot` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1346 | `mocha test --timeout 600000` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1345 | `./node_modules/mocha/bin/mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1342 | `standard "./src/*.js" && mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1339 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1333 | `mocha test.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1323 | `cross-env NODE_ENV=test nyc mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1317 | `mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1317 | `mocha --recursive` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1302 | `istanbul cover _mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1288 | `mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1279 | `mocha-phantomjs tests/index.html` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1272 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1259 | `mocha --check-leaks --reporter spec --bail` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1259 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1259 | `npm run build && mocha -r should` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1254 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1253 | `mocha --timeout 10000 ./tests/lib.js` | 
| [sandeepmistry/bleno](https://github.com/sandeepmistry/bleno) | 1252 | `mocha -R spec test/*.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1250 | `mocha tests.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1236 | `./node_modules/.bin/mocha test` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1231 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1231 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1226 | `mocha spec/exec.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1224 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1223 | `mocha test/setup.js test/spec/*.js` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1216 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1215 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1213 | `mocha compiled_tests/` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1211 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [reddit/reddit-mobile](https://github.com/reddit/reddit-mobile) | 1202 | `mocha test/index.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1201 | `npm run lint && npm run mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1200 | `mocha tests` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1200 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1197 | `mocha test/test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1195 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1193 | `mocha test/*.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1190 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1190 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1186 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1185 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1180 | `mocha test/**/*Spec.js` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1178 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1178 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1177 | `istanbul cover _mocha test -- --timeout 20000` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1169 | `mocha test` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1169 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1165 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1163 | `mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1162 | `mocha --recursive` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1159 | `mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1155 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1153 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1142 | `node ./node_modules/mocha/bin/mocha tests` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1142 | `mocha --opts test/opts/mocha.opts` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1140 | `eslint lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1132 | `mocha --check-leaks --require @babel/register` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1131 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1128 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1128 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1124 | `mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1111 | `eslint . && mocha -t 5000` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1110 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1095 | `npm run lint && npm run mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1093 | `mocha --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1092 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1091 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1091 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1088 | `node_modules/.bin/mocha && npm run lint` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1087 | `mocha` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1084 | `mocha` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1083 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1081 | `mocha src/test.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1077 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1076 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1069 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1066 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1062 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1062 | `standard && istanbul cover _mocha` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1061 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1060 | `mocha --compilers js:babel-register` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1059 | `node_modules/.bin/mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1057 | `mocha test/*` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1056 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1053 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1049 | `mocha --reporter dot` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1049 | `mocha --reporter spec --timeout 3000` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1047 | `mocha $(find test -name '*.test.js')` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1047 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1043 | `eslint src && mocha && karma start --single-run` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1041 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1039 | `mocha test/unit` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1031 | `xo && mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1030 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1027 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1027 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1026 | `istanbul test _mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1023 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1023 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [jas/playground](https://github.com/jas/playground) | 1019 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1018 | `mocha --check-leaks -R dot` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1008 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1008 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1007 | `mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1004 | `NODE_PATH=. mocha **/*.spec.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1004 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1003 | `mocha --check-leaks --reporter spec --bail test/` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 987 | `mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 986 | `mocha test/tests.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 984 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 983 | `istanbul cover _mocha test/*.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 982 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 982 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 980 | `mocha --colors ./test/*.spec.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 978 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 975 | `mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 968 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 968 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 965 | `mocha tests/test-*` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 961 | `mocha test` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 960 | `mocha --recursive --bail --reporter spec test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 960 | `mocha --timeout 5000` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 956 | `npm run rollup-cjs && mocha test/test.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 953 | `mocha -R list` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 952 | `mocha` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 951 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 947 | `standard && mocha` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 945 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 943 | ` NODE_ENV=test mocha --compilers js:babel-register` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 943 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 941 | `mocha $(find test -name '*.test.js')` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 938 | `mocha --recursive test/unit/` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 935 | `mocha --async-only` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 935 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 931 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 928 | `npm run prepublish && mocha test/test.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 928 | `mocha --reporter spec` | 
| [router5/router5](https://github.com/router5/router5) | 924 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [tomas/needle](https://github.com/tomas/needle) | 923 | `mocha test` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 919 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 912 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 911 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 911 | `mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 910 | `standard && mocha -b` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 909 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 909 | `mocha -t 120000 test/*.test.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 905 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 903 | `mocha spec/*.spec.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 900 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 899 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 893 | `webpack && mocha test/unit` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 892 | `./node_modules/.bin/mocha --globals angular,require` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 888 | `mocha` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 885 | `mocha --recursive test` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 883 | `nyc mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 880 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 880 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 877 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 877 | `nyc mocha --timeout=20000 test.js` | 
| [electron/asar](https://github.com/electron/asar) | 875 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 874 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 873 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 871 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 867 | `mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 867 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 865 | `mocha --reporter list` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 864 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 862 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 860 | `mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 858 | `mocha --reporter spec --bail --check-leaks test/` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 857 | `mocha "client.test" --compilers js:babel-register` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 855 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 851 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 848 | `mocha && standard` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 847 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 846 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 844 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 843 | `mocha --compilers js:babel-register test/*.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 842 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 842 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 841 | `node_modules/.bin/mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 835 | `eslint test && mocha --compilers js:babel/register` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 833 | `npm run lint && mocha -R spec` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 832 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 828 | `npm run lint && npm run mocha` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 827 | `nyc mocha --require babel-register` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 826 | `mocha --timeout 200000` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 825 | `mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 824 | `mocha --reporter spec --bail --check-leaks test/` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 821 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 820 | `mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 820 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 816 | `node_modules/.bin/mocha test/spec` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 815 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 814 | `mocha --reporter spec` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 814 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 813 | `npm run convertto:es5 && npm run mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 813 | `mocha tests` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 812 | `mocha && ember test` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 812 | `mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 811 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 811 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 810 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 808 | `mocha ./test/test*.js --reporter spec` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 807 | `mocha tests/*.test.js --reporter spec` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 804 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 802 | `mocha ./test -R spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 794 | `mocha --check-leaks -t 20000` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 792 | `mocha -u tdd` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 791 | `mocha -R spec tests/` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 790 | `npm run lint && mocha --compilers js:babel-register` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 790 | `mocha` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 789 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 787 | `istanbul cover _mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 786 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 781 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 781 | `standard && standard ./bin/* && mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 780 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 778 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 777 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 777 | `cake build && mocha ./test/mocha/*.coffee` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 775 | `nyc mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 774 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 778 | `mocha -t 5000` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 778 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 777 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 777 | `cake build && mocha ./test/mocha/*.coffee` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 775 | `nyc mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 774 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 771 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 765 | `mocha --colors --reporter spec test.js` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 764 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 763 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 762 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 762 | `mocha test --compilers js:babel-register` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 761 | `istanbul cover -- _mocha --reporter spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 760 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 760 | `npm run lint && mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 759 | `mocha -t 600000` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 759 | `mocha` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 759 | `mocha -R spec` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 758 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 755 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 754 | `mocha --async-only` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 753 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 752 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 751 | `nyc mocha specs` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 751 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 748 | `xo && mocha -R spec` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 746 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 744 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 743 | `mocha --ui tdd --require ./test/__setup` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 742 | `mocha tests/*.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 734 | `mocha spec/*.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 733 | `mocha --reporter list` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 733 | `mocha -R spec src/**/*_test.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 732 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 730 | `./node_modules/.bin/mocha -R spec` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 728 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 727 | `mocha --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 722 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 720 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 717 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require babel-register --no-timeouts` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 715 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 713 | `mocha test.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 712 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 706 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 701 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 701 | `cross-env NODE_ENV=test nyc mocha` | 
| [contra/gulp-concat](https://github.com/contra/gulp-concat) | 699 | `mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 696 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 694 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 693 | `npm run bundle && mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 693 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 692 | `npm run mocha:istanbul` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 691 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 690 | `npm run mocha-test test/integration` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 687 | `mocha tests/*.mocha.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 684 | `mocha test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 682 | `eslint src test && mocha --compilers babel-register` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 681 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 681 | `npm run build && istanbul test _mocha test/test.js` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 680 | `npm run lint && mocha test` | 
| [bitpay/insight](https://github.com/bitpay/insight) | 680 | `mocha test` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 679 | `mocha ./test/index.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 679 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 679 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [developit/workerize-loader](https://github.com/developit/workerize-loader) | 678 | `npm run build && webpack --config test/webpack.config.js && npm run -s mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 675 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 673 | `mocha test` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 671 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 670 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 670 | `mocha -b -R spec test/*` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 669 | `mocha --reporter spec` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 668 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 668 | `mocha` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 665 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 664 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 