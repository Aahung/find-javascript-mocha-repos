# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:35 01/17/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39530 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 38588 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 36131 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 35976 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28484 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23137 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 20195 | `mocha test/index.js` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17283 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [developit/preact](https://github.com/developit/preact) | 17226 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 16512 | `cross-env NODE_ENV=test mocha` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15358 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14526 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13674 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12716 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12434 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11950 | `mocha` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 11854 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11792 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11595 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11455 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 10827 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10661 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10416 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 10091 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9766 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9401 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9214 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 9210 | `mocha --harmony` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9058 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tmpvar/jsdom](https://github.com/tmpvar/jsdom) | 9047 | `mocha test/index.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 8958 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 8825 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8787 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8452 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8243 | `mocha test/*-test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8117 | `mocha --check-leaks -R dot` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8095 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8048 | `mocha test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8040 | `grunt clean:test && mocha` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7686 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7666 | `./node_modules/.bin/mocha test/src` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7650 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7560 | `mocha --compilers js:babel-register test/test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7521 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7436 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7408 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [websockets/ws](https://github.com/websockets/ws) | 7299 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7222 | `npm run eslint && npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7170 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 7134 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7096 | `npm run build && istanbul cover _mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7032 | `mocha tests/*.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7015 | `./node_modules/.bin/mocha test` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6627 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6587 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6503 | `mocha $HARMONY_OPTS` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6417 | `mocha --require babel-core/register ./packages/*/test/index.js` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6398 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6330 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6209 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6193 | `mocha --opts mocha.opts` | 
| [almende/vis](https://github.com/almende/vis) | 6130 | `mocha --compilers js:babel-core/register` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6091 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6060 | `nyc mocha test/** -r ./test/before` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 5996 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5926 | `mocha` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 5843 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5839 | `npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5748 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5692 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5553 | `npm run jshint && mocha test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5526 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5433 | `mocha tests/node.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5383 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5303 | `mocha && eslint lib/**` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5302 | `mocha test --recursive` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5292 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5232 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5173 | `mocha test/test.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5167 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5130 | `mocha src/**/*Tests.js --harmony` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5033 | `mocha --timeout 10000 && npm run lint` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4880 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4876 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 4876 | `mocha --compilers js:babel-core/register` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4747 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4699 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4623 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4611 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4584 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4577 | `mocha --reporter spec -t 8000` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4524 | `mocha ./test/runner.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4490 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4429 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4381 | `gulp build; mocha;` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4375 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4318 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4313 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4309 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4280 | `./node_modules/.bin/mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4270 | `standard && mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4226 | `mocha -R spec ./test --recursive` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4150 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4143 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4143 | `mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4112 | `mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4061 | `mocha test` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 4021 | `mocha && ./bin/shipit staging test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3974 | `nyc mocha` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 3960 | `npm run build-cli && mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 3948 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3886 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3839 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3816 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [muicss/mui](https://github.com/muicss/mui) | 3773 | `mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3759 | `mocha --recursive && make test` | 
| [tj/ejs](https://github.com/tj/ejs) | 3736 | `mocha --require should --reporter spec` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3713 | `NODE_ENV=test mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3689 | `mocha --require test/babel-hook test/*.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3639 | `npm run jshint && npm run mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3637 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3607 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3571 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3553 | `nyc mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3545 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3540 | `standard && mocha --timeout 60000 test/test.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3513 | `mocha tests/javascript` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3496 | `npm run lint ; mocha && mocha test/individual` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3432 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3420 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [primus/primus](https://github.com/primus/primus) | 3419 | `npm run build && mocha test/*.test.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 3402 | `mocha; jshint *.js lib` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3386 | `mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3383 | `node_modules/.bin/mocha test/lib/` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3374 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3359 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3310 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3173 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3144 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3135 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3132 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3130 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3101 | `mocha --check-leaks --reporter spec --bail` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3084 | `mocha` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3069 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3066 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3048 | `./node_modules/.bin/mocha test/test.*.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3018 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3008 | `npm run lint && npm run mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 2986 | `node_modules/.bin/mocha test/tests.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 2978 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 2964 | `nyc mocha "test/**/*.test.js"` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 2964 | `yarn run build:cjs && mocha --require babel-core/register ./test/index.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2956 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2907 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2896 | `mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2886 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2877 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2803 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2795 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2759 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2754 | `mocha --require should --reporter spec` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2752 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2722 | `mocha -R spec --recursive src/test` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2720 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2697 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2695 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2694 | `istanbul cover _mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2692 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2669 | `mocha test/index.js && npm run demo` | 
| [tj/should.js](https://github.com/tj/should.js) | 2657 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2645 | `nyc mocha && tsc` | 
| [github-tools/github](https://github.com/github-tools/github) | 2639 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2623 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2618 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2607 | `mocha` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2602 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2591 | `xo && mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2587 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2586 | `mocha --timeout 100000` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2579 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2571 | `mocha-phantomjs ./test/index.html` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2563 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2552 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2538 | `mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2532 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2528 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2527 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2524 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2521 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2519 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [css/csso](https://github.com/css/csso) | 2518 | `mocha --reporter dot` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2512 | `mocha --opts mocha.opts` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2507 | `export TESTING=true; mocha --reporter list` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2502 | `npm run mocha && npm run lint` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2478 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2478 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2474 | `mocha --recursive --watch` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2469 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2463 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2461 | `mocha --compilers js:babel-register --recursive spec` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2436 | `npm run compile && mocha --require babel-core/register` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2406 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2404 | `mocha --reporter=spec test/*-test.js` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2394 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2390 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2366 | `node node_modules/mocha/bin/_mocha` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2363 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2362 | `mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2328 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2322 | `mocha --no-colors --reporter spec` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2320 | `mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2315 | `grunt jshint && mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2297 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2290 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2283 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2274 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2258 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2257 | `mocha test/src/**/*.unit.js` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2256 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2245 | `NODE_ENV=test mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2242 | `gulp && cd test && mocha . --reporter dot` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2227 | `node_modules/.bin/mocha --reporter spec` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2220 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2164 | `mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2163 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2131 | `npm run lint && npm run build && npm run mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2131 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2123 | `mocha -R spec` | 
| [gajus/swing](https://github.com/gajus/swing) | 2115 | `mocha --compilers js:babel-register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2079 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2078 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [mde/ejs](https://github.com/mde/ejs) | 2072 | `mocha --require should --reporter spec` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2069 | `mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2028 | `mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2022 | `mocha --require babel-core/register ./packages/*/test/index.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2021 | `cross-env BABEL_ENV=test mocha` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1943 | `mocha -R spec test/*.js` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 1927 | `export TESTING=true; mocha --reporter list` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1919 | `mocha --require=test/test_helper.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1917 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 1911 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1889 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1876 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 1873 | `mocha ./test/*.spec.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1867 | `mocha test/index.js --reporter dot` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 1927 | `export TESTING=true; mocha --reporter list` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1919 | `mocha --require=test/test_helper.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1917 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 1911 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1900 | `mocha --bail --reporter spec --check-leaks test/` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1889 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1876 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 1873 | `mocha ./test/*.spec.js` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1868 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1867 | `mocha test/index.js --reporter dot` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1855 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1849 | `mocha -c test/index.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1849 | `mocha test && npm run lint` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1843 | `mocha test.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1836 | `mocha` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1829 | `mocha tests.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1824 | `mocha -R landing test/index` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1822 | `mocha --require ./test/common --growl test/expect.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 1814 | `mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1807 | `mocha --timeout 5000` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1807 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1802 | `mocha --reporter spec --timeout 5000` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1783 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1768 | `mocha --compilers js:babel-register` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1767 | `cross-env NODE_ENV=test mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1763 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1757 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1757 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1750 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [then/promise](https://github.com/then/promise) | 1746 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1745 | `mocha test/runner.js --reporter spec` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1743 | `mocha test` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1735 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1729 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1724 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1711 | `mocha --compilers js:babel-core/register __tests__` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1710 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1707 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1705 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1705 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1695 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [Hardmath123/nearley](https://github.com/Hardmath123/nearley) | 1695 | `mocha test/*.test.js` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1694 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1689 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1683 | `mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1676 | `mocha` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1675 | `mocha test` | 
| [KunalKapadia/express-mongoose-es6-rest-api](https://github.com/KunalKapadia/express-mongoose-es6-rest-api) | 1673 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1672 | `npm run lint && mocha --reporter spec test/*.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1660 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1656 | `./node_modules/.bin/mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1656 | `mocha && eslint *.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1641 | `./node_modules/.bin/mocha && npm run jshint` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1636 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1633 | `npm run lint && mocha --recursive` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1629 | `mocha --reporter spec && npm run test-typescript` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1625 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1624 | `mocha -R spec spec spec/reporters` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1623 | `npm run lint && npm run mocha` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1622 | `npm run lint && mocha -R dot && npm run cover` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1617 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1616 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1616 | `./node_modules/mocha/bin/mocha -R spec` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1608 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1606 | `mocha tests/test.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1603 | `mocha --expose-gc --slow 300` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1594 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1592 | `npm run mocha && npm run karma` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1586 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1568 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1567 | `mocha test/*.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1552 | `mocha && npm run lint` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1545 | `./node_modules/.bin/mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1543 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1537 | `nyc npm run _mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1534 | `npm run lint && mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1528 | `mocha --reporter spec --grep .` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1524 | `mocha` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1523 | `npm run mocha && npm run lint` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1519 | `mocha tests --compilers js:babel-core/register` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1500 | `mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1494 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1492 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1492 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1491 | `mocha test -u bdd -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1490 | `mocha test/` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1489 | `mocha spec/` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1489 | `mocha ./test/basic.js -t 5000` | 
| [pahen/madge](https://github.com/pahen/madge) | 1486 | `npm run lint && npm run mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1485 | `mocha test/* --reporter spec` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1476 | `mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1470 | `mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1467 | `npm run test:lint && npm run test:mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1467 | `mocha -R spec` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1465 | `./node_modules/mocha/bin/mocha -R spec` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1461 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1456 | `mocha -u tdd` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1455 | `npm run lint && npm run mocha` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1453 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1445 | `mocha --reporter spec test/*.js` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1444 | `node_modules/.bin/mocha --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1367 | `nyc mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1362 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1359 | `standard "src/*.js" && npm run build && mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1359 | `mocha --compilers js:babel-register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1356 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1354 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1348 | `eslint --rulesdir=dev-tools/eslint --cache . && tsc && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1346 | `mocha --check-leaks -R dot` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1345 | `./node_modules/mocha/bin/mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1343 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1341 | `standard "./src/*.js" && mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1336 | `mocha test --timeout 600000` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1332 | `mocha test.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1329 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1359 | `mocha --compilers js:babel-register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1356 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1354 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1354 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1348 | `eslint --rulesdir=dev-tools/eslint --cache . && tsc && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1346 | `mocha --check-leaks -R dot` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1345 | `./node_modules/mocha/bin/mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1341 | `standard "./src/*.js" && mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1336 | `mocha test --timeout 600000` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1332 | `mocha test.js` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1329 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1321 | `cross-env NODE_ENV=test nyc mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1317 | `mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1316 | `mocha --recursive` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1321 | `cross-env NODE_ENV=test nyc mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1317 | `mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1316 | `mocha --recursive` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1300 | `istanbul cover _mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1282 | `mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1279 | `mocha-phantomjs tests/index.html` | 
| [electron/devtron](https://github.com/electron/devtron) | 1213 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1213 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1210 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1203 | `mocha compiled_tests/` | 
| [reddit/reddit-mobile](https://github.com/reddit/reddit-mobile) | 1200 | `mocha test/index.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1200 | `mocha tests` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1200 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1198 | `npm run lint && npm run mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1196 | `mocha test/test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1192 | `mocha test/*.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1188 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1188 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1185 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1179 | `mocha test/**/*Spec.js` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1178 | `mocha` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1177 | `istanbul cover _mocha test -- --timeout 20000` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1176 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1169 | `mocha test` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1223 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1222 | `mocha test/setup.js test/spec/*.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1213 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1213 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1210 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1203 | `mocha compiled_tests/` | 
| [reddit/reddit-mobile](https://github.com/reddit/reddit-mobile) | 1200 | `mocha test/index.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1200 | `mocha tests` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1200 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1198 | `npm run lint && npm run mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1196 | `mocha test/test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1195 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1192 | `mocha test/*.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1188 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1188 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1185 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1184 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1179 | `mocha test/**/*Spec.js` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1179 | `mocha test/**/*Spec.js` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1178 | `mocha` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1177 | `istanbul cover _mocha test -- --timeout 20000` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1176 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1169 | `mocha test` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1167 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1165 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1162 | `mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1161 | `mocha --recursive` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1157 | `./node_modules/.bin/mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1153 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1151 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1141 | `mocha --opts test/opts/mocha.opts` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1140 | `node ./node_modules/mocha/bin/mocha tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1140 | `eslint lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1128 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1123 | `mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1097 | `eslint . && mocha -t 5000` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1095 | `npm run lint && npm run mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1093 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1092 | `mocha --reporter spec` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1091 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [variety/variety](https://github.com/variety/variety) | 1091 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1088 | `node_modules/.bin/mocha && npm run lint` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1087 | `mocha` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1080 | `mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1088 | `node_modules/.bin/mocha && npm run lint` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1087 | `mocha` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1082 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1080 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1077 | `mocha src/test.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1077 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1075 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1067 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1066 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1061 | `mocha --check-leaks -t 20000` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1060 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1060 | `mocha --compilers js:babel-register` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1059 | `standard && istanbul cover _mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1057 | `mocha test/*` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1057 | `node_modules/.bin/mocha` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1056 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1053 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1049 | `mocha --reporter spec --timeout 3000` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1047 | `mocha $(find test -name '*.test.js')` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1046 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1043 | `mocha --reporter dot` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1038 | `eslint src && mocha && karma start --single-run` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1037 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1036 | `mocha test/unit` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1031 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1029 | `xo && mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1027 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1026 | `istanbul test _mocha` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1026 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1022 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [jas/playground](https://github.com/jas/playground) | 1020 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1018 | `mocha --check-leaks -R dot` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1008 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1006 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1006 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1004 | `NODE_PATH=. mocha **/*.spec.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1001 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 996 | `mocha --check-leaks --reporter spec --bail test/` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 986 | `mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 985 | `mocha test/tests.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 984 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 982 | `istanbul cover _mocha test/*.js` | 
| [googlevr/webvr-polyfill](https://github.com/googlevr/webvr-polyfill) | 981 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 980 | `mocha --colors ./test/*.spec.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 977 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 975 | `mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 975 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 967 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 966 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 962 | `mocha tests/test-*` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 960 | `mocha --timeout 5000` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 958 | `mocha --recursive --bail --reporter spec test` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 954 | `npm run rollup-cjs && mocha test/test.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 954 | `mocha test` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 952 | `mocha -R list` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 950 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 948 | `mocha` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 945 | `standard && mocha` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 943 | ` NODE_ENV=test mocha --compilers js:babel-register` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 943 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 941 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 941 | `mocha $(find test -name '*.test.js')` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 938 | `mocha --recursive test/unit/` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 935 | `mocha --async-only` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 931 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 929 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 927 | `mocha --reporter spec` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 926 | `npm run prepublish && mocha test/test.js` | 
| [router5/router5](https://github.com/router5/router5) | 923 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [tomas/needle](https://github.com/tomas/needle) | 922 | `mocha test` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 915 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 912 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 910 | `mocha -t 120000 test/*.test.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 909 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 909 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 909 | `standard && mocha -b` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 905 | `mocha ./test/index.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 905 | `mocha` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 902 | `mocha spec/*.spec.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 897 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 895 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 892 | `./node_modules/.bin/mocha --globals angular,require` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 890 | `webpack && mocha test/unit` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 886 | `mocha` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 884 | `mocha --recursive test` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 883 | `mocha --reporter spec --bail --check-leaks test/` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 881 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 879 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 877 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [electron/asar](https://github.com/electron/asar) | 875 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 874 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 874 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 873 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 871 | `nyc mocha --timeout=20000 test.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 870 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 865 | `mocha --reporter list` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 864 | `mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 864 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 863 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 860 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 858 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 856 | `mocha "client.test" --compilers js:babel-register` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 856 | `mocha --reporter spec --bail --check-leaks test/` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 855 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 850 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 848 | `mocha && standard` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 845 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 844 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 844 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 841 | `mocha --compilers js:babel-register test/*.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 841 | `node_modules/.bin/mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 837 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 835 | `eslint test && mocha --compilers js:babel/register` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 832 | `npm run lint && mocha -R spec` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 831 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 827 | `npm run lint && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 826 | `mocha --timeout 200000` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 826 | `mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 823 | `mocha --reporter spec --bail --check-leaks test/` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 822 | `nyc mocha --require babel-register` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 821 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 819 | `mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 819 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 816 | `node_modules/.bin/mocha test/spec` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 815 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 814 | `mocha --reporter spec` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 814 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 812 | `mocha tests` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 811 | `npm run convertto:es5 && npm run mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 811 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 811 | `mocha && ember test` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 811 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 810 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 807 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 807 | `mocha tests/*.test.js --reporter spec` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 806 | `mocha ./test/test*.js --reporter spec` | 
| [reactivestack/cookies](https://github.com/reactivestack/cookies) | 802 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 801 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 800 | `mocha ./test -R spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 794 | `mocha --check-leaks -t 20000` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 792 | `mocha -u tdd` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 791 | `mocha -R spec ./test/unit/**` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 791 | `mocha -R spec tests/` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 791 | `mocha` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 789 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 787 | `istanbul cover _mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 787 | `npm run lint && mocha --compilers js:babel-register` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 787 | `mocha --require babel-register` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 785 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 781 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 781 | `standard && standard ./bin/* && mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 780 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 778 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 777 | `cake build && mocha ./test/mocha/*.coffee` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 777 | `mocha -t 5000` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 777 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 775 | `mocha --reporter spec --bail --check-leaks test/` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 774 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 768 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 764 | `mocha --colors --reporter spec test.js` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 764 | `mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 762 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 761 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 761 | `mocha test --compilers js:babel-register` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 761 | `istanbul cover -- _mocha --reporter spec` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 760 | `npm run lint && mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 759 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 758 | `mocha -R spec` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 756 | `mocha` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 754 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 754 | `mocha -t 600000` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 753 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 753 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 753 | `mocha --async-only` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 751 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 750 | `nyc mocha specs` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 750 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 749 | `xo && mocha -R spec` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 745 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 743 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 741 | `mocha --ui tdd --require ./test/__setup` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 734 | `mocha tests/*.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 734 | `mocha -R spec src/**/*_test.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 732 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 731 | `mocha --reporter list` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 731 | `mocha spec/*.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 728 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 728 | `mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 726 | `./node_modules/.bin/mocha -R spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 722 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 720 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 714 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 712 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 712 | `mocha test.js` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 708 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require babel-register --no-timeouts` | 
| [3Dparallax/insight](https://github.com/3Dparallax/insight) | 708 | `mocha test` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 706 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 701 | `cross-env NODE_ENV=test nyc mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 699 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [contra/gulp-concat](https://github.com/contra/gulp-concat) | 699 | `mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 696 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 695 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 694 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 693 | `npm run bundle && mocha` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 690 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 689 | `npm run mocha-test test/integration` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 689 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 686 | `mocha tests/*.mocha.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 684 | `npm run mocha:istanbul` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 684 | `mocha test` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 680 | `npm run lint && mocha test` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 680 | `npm run build && istanbul test _mocha test/test.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 679 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 679 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 679 | `eslint src test && mocha --compilers babel-register` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 679 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 678 | `mocha ./test/index.js` | 
| [bitpay/insight](https://github.com/bitpay/insight) | 677 | `mocha test` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 673 | `mocha test` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 671 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 670 | `mocha -b -R spec test/*` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 669 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 669 | `mocha --reporter spec` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 667 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 667 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 667 | `mocha` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 665 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 664 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 663 | `mocha --reporter spec` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 663 | `mocha` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 663 | `mocha` | 