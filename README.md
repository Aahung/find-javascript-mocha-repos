# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:31 12/20/17 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39349 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 37980 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 35673 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 35090 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28214 | `mocha --reporter spec` | 
| [caolan/async](https://github.com/caolan/async) | 22945 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 19724 | `mocha test/index.js` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17015 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [developit/preact](https://github.com/developit/preact) | 16797 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15176 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14252 | `mocha test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13598 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12374 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12260 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11908 | `mocha` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 11742 | `cross-env NODE_ENV=test mocha` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 11690 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11613 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11515 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11302 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 10479 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10384 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10286 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 9822 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9551 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9232 | `mocha --reporter spec` | 
| [tj/co](https://github.com/tj/co) | 9108 | `mocha --harmony` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9044 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 8922 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tmpvar/jsdom](https://github.com/tmpvar/jsdom) | 8901 | `mocha test/index.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 8845 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8704 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [svg/svgo](https://github.com/svg/svgo) | 8671 | `set NODE_ENV=test && mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8373 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8128 | `mocha test/*-test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8103 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8021 | `grunt clean:test && mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 7990 | `mocha test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7636 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7577 | `./node_modules/.bin/mocha test/src` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7528 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7422 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7405 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7324 | `mocha --compilers js:babel-register test/test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7265 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7186 | `npm run eslint && npm run mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7052 | `npm run build && istanbul cover _mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 7046 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 6942 | `./node_modules/.bin/mocha test` | 
| [amark/gun](https://github.com/amark/gun) | 6940 | `mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 6879 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 6861 | `mocha tests/*.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6446 | `mocha $HARMONY_OPTS` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6397 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6377 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6308 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6204 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6187 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6089 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [almende/vis](https://github.com/almende/vis) | 6016 | `mocha --compilers js:babel-core/register` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 5958 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5934 | `mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 5832 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 5824 | `nyc mocha test/** -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 5675 | `mocha --opts mocha.opts` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5666 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5666 | `npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5557 | `npm run test:mocha:src` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 5554 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5460 | `npm run jshint && mocha test/` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5388 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5380 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5373 | `mocha tests/node.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5270 | `mocha && eslint lib/**` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5255 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5210 | `mocha test --recursive` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5161 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5161 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5114 | `mocha src/**/*Tests.js --harmony` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5080 | `mocha test/test.js` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 4972 | `mocha --timeout 10000 && npm run lint` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4809 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4774 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4726 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4676 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 4641 | `mocha --compilers js:babel-core/register` | 
| [santinic/how2](https://github.com/santinic/how2) | 4608 | `mocha test` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4563 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4563 | `mocha --reporter spec -t 8000` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4561 | `mocha -R spec 'tests/app'` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4514 | `mocha ./test/runner.js` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4366 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4346 | `gulp build; mocha;` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4343 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4321 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4298 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4258 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4239 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4226 | `mocha -R spec ./test --recursive` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4225 | `./node_modules/.bin/mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4174 | `standard && mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4103 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4083 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4039 | `mocha` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 3985 | `mocha && ./bin/shipit staging test` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 3975 | `mocha test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3938 | `nyc mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3891 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 3888 | `mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 3841 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3823 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3812 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [tj/ejs](https://github.com/tj/ejs) | 3699 | `mocha --require should --reporter spec` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3659 | `mocha --recursive && make test` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3632 | `npm run jshint && npm run mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3608 | `NODE_ENV=test mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3546 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3544 | `mocha --require test/babel-hook test/*.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3543 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3532 | `standard && mocha --timeout 60000 test/test.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3528 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3511 | `npm run lint && npm run mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3498 | `mocha tests/javascript` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3434 | `npm run lint ; mocha && mocha test/individual` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3414 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3411 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 3408 | `npm run build-cli && mocha` | 
| [primus/primus](https://github.com/primus/primus) | 3392 | `npm run build && mocha test/*.test.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3379 | `node_modules/.bin/mocha test/lib/` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3377 | `nyc mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3376 | `mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3333 | `node_modules/.bin/mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3295 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3279 | `npm run lint && mocha && EIO_WS_ENGINE=ws mocha` | 
| [easy-mock/easy-mock](https://github.com/easy-mock/easy-mock) | 3119 | `cross-env NODE_ENV=test istanbul cover _mocha test/*` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3080 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3076 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3058 | `mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3047 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3041 | `./node_modules/.bin/mocha test/test.*.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3033 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3033 | `mocha --check-leaks --reporter spec --bail` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3004 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 2989 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 2968 | `node_modules/.bin/mocha test/tests.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2943 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 2935 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 2902 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2892 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [expressjs/session](https://github.com/expressjs/session) | 2891 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 2880 | `nyc mocha "test/**/*.test.js"` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2876 | `mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 2833 | `npm run lint && npm run mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2814 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2809 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 2802 | `mocha; jshint *.js lib` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2778 | `mocha test/*.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2751 | `mocha --require should --reporter spec` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2745 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2734 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2734 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2703 | `mocha -R spec --recursive src/test` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2684 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2681 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2679 | `istanbul cover _mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 2641 | `yarn run build:cjs && mocha --require babel-core/register ./test/index.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2632 | `mocha test/index.js && npm run demo` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2613 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2610 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2586 | `xo && mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2582 | `mocha --timeout 100000` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2582 | `mocha` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2570 | `nyc mocha && tsc` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2568 | `mocha-phantomjs ./test/index.html` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2567 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [github-tools/github](https://github.com/github-tools/github) | 2562 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2538 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2519 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2511 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2511 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2508 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2505 | `mocha` | 
| [css/csso](https://github.com/css/csso) | 2496 | `mocha --reporter dot` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2486 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2477 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2476 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2475 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2465 | `mocha --recursive --watch` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2463 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2460 | `npm run mocha && npm run lint` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2457 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2447 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2417 | `mocha --compilers js:babel-register --recursive spec` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2415 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2415 | `mocha` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2403 | `mocha --opts mocha.opts` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2395 | `mocha --reporter=spec test/*-test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2382 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2378 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2372 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2363 | `node node_modules/mocha/bin/_mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2358 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2326 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2319 | `mocha --no-colors --reporter spec` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2313 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2313 | `grunt jshint && mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2301 | `mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2291 | `mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2291 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2283 | `npm run compile && mocha --compilers js:babel-core/register` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2283 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2246 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2235 | `mocha test/src/**/*.unit.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2228 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2219 | `mocha test` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2218 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2211 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2211 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2208 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2202 | `mocha test test/unit/**/*_test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2188 | `gulp && cd test && mocha . --reporter dot` | 
| [octokit/node-github](https://github.com/octokit/node-github) | 2167 | `nyc mocha test/**/*-test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2163 | `NODE_ENV=test mocha` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2145 | `node_modules/.bin/mocha --reporter spec` | 
| [mozilla/send](https://github.com/mozilla/send) | 2127 | `mocha test/unit` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2124 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2108 | `npm run lint && npm run build && npm run mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2103 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2098 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [gajus/swing](https://github.com/gajus/swing) | 2095 | `mocha --compilers js:babel-register` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2091 | `mocha -R spec` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2086 | `mocha test/unit --require mochahook` | 
| [json5/json5](https://github.com/json5/json5) | 2074 | `mocha --ui exports --reporter spec` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2073 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2031 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [slate/slate](https://github.com/slate/slate) | 2023 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2019 | `mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2017 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2007 | `cross-env BABEL_ENV=test mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 1983 | `mocha --require should --reporter spec` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 1945 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 1937 | `nyc --reporter=html --reporter=text mocha` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1915 | `mocha --require=test/test_helper.js` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1908 | `mocha -R spec test/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1896 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1869 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1864 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1849 | `mocha test/index.js --reporter dot` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1848 | `mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1841 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1827 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 1826 | `mocha ./test/*.spec.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1823 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1821 | `mocha tests.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 1812 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1809 | `mocha --timeout 5000` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1805 | `mocha --require ./test/common --growl test/expect.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1803 | `mocha test && npm run lint` | 
| [Qix-/color](https://github.com/Qix-/color) | 1790 | `mocha` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1789 | `mocha` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1783 | `mocha --reporter spec --timeout 5000` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1783 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1777 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1767 | `mocha -c test/index.js` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1762 | `cross-env NODE_ENV=test mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1755 | `mocha test.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1750 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1738 | `mocha test/**/*_test.js --bail` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1734 | `mocha test` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1725 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1717 | `mocha -R landing test/index` | 
| [then/promise](https://github.com/then/promise) | 1717 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1715 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1714 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1704 | `mocha test/runner.js --reporter spec` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1703 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1698 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1698 | `mocha --compilers js:babel-register` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1696 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1678 | `mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1677 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1674 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1674 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1672 | `mocha --compilers js:babel-core/register __tests__` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1672 | `xo && mocha` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1668 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [verdaccio/verdaccio](https://github.com/verdaccio/verdaccio) | 1659 | `mocha ./test/functional ./test/unit --reporter=spec --full-trace` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1658 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1655 | `mocha test` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1653 | `mocha` | 
| [Hardmath123/nearley](https://github.com/Hardmath123/nearley) | 1651 | `mocha test/*.test.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1650 | `npm run lint && npm run compile && mocha --reporter spec test/*.js` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1646 | `./node_modules/.bin/mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1646 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1635 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [KunalKapadia/express-mongoose-es6-rest-api](https://github.com/KunalKapadia/express-mongoose-es6-rest-api) | 1627 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1624 | `mocha` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1613 | `mocha -R spec spec spec/reporters` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1612 | `mocha && eslint *.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1610 | `mocha --reporter spec && npm run test-typescript` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1605 | `npm run lint && npm run mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1604 | `mocha tests/test.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1604 | `lint && mocha --recursive` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1599 | `mocha --expose-gc --slow 300` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1599 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1595 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1589 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1576 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1576 | `./node_modules/mocha/bin/mocha -R spec` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1573 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1553 | `mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1550 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1547 | `mocha test/*.js` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1542 | `./node_modules/.bin/mocha` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1531 | `npm run mocha && npm run karma` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1520 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1520 | `npm run lint && mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1518 | `mocha && npm run lint` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1510 | `mocha --reporter spec --grep .` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1491 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1491 | `nyc npm run _mocha` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1489 | `mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1487 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1486 | `npm run mocha && npm run lint` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1478 | `mocha tests --compilers js:babel-core/register` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1475 | `mocha` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1467 | `npm run lint && mocha -R dot && npm run cover` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1464 | `mocha -R spec` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1460 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1459 | `mocha test -u bdd -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1458 | `mocha test/` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1458 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1456 | `mocha spec/` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1455 | `mocha ./test/basic.js -t 5000` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1455 | `mocha test/* --reporter spec` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1454 | `./node_modules/mocha/bin/mocha -R spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1453 | `mocha -u tdd` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1447 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1443 | `node_modules/.bin/mocha --recursive` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1438 | `npm run lint && npm run mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1435 | `npm run test:lint && npm run test:mocha && npm run site` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1430 | `mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 1429 | `npm run lint && npm run mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1429 | `mocha test/tests.js --timeout=10000` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1420 | `mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1402 | `mocha --reporter spec` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1402 | `mocha test.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1393 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1378 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1361 | `mocha --reporter spec test/*.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1355 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1354 | `nyc mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1350 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1348 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1347 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1342 | `./node_modules/mocha/bin/mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 1335 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1328 | `mocha --check-leaks -R dot` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1326 | `standard "./src/*.js" && mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1324 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1322 | `eslint --rulesdir=dev-tools/eslint --cache . && tsc && mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1320 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1319 | `mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1315 | `cross-env NODE_ENV=test nyc mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1309 | `mocha --compilers js:babel-register` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1293 | `istanbul cover _mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1292 | `mocha --recursive` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1289 | `mocha test.js` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1281 | `standard "src/*.js" && npm run build && mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1269 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1259 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1252 | `npm run build && mocha -r should` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1242 | `mocha` | 
| [sandeepmistry/bleno](https://github.com/sandeepmistry/bleno) | 1231 | `mocha -R spec test/*.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1225 | `./node_modules/.bin/mocha test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1225 | `mocha --timeout 10000 ./tests/lib.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1217 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1214 | `mocha-phantomjs tests/index.html` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1213 | `mocha --check-leaks --reporter spec --bail` | 
| [zeit/ms](https://github.com/zeit/ms) | 1209 | `mocha tests.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1209 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1207 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1200 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1197 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1195 | `mocha tests` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1195 | `mocha test/setup.js test/spec/*.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1193 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1191 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [reddit/reddit-mobile](https://github.com/reddit/reddit-mobile) | 1190 | `mocha test/index.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1190 | `mocha test/test.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1186 | `mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1185 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1181 | `mocha test/*.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1177 | `mocha test/**/*Spec.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1174 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1173 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1169 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1167 | `mocha` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1166 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1166 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1165 | `mocha test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1163 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1161 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1159 | `npm run lint && npm run mocha` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1154 | `istanbul cover _mocha test -- --timeout 20000` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1149 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1149 | `mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1147 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1146 | `mocha --recursive` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1143 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1141 | `mocha compiled_tests/` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1138 | `./node_modules/.bin/mocha` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1136 | `node ./node_modules/mocha/bin/mocha tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1129 | `eslint lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1127 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1126 | `mocha --opts test/opts/mocha.opts` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1117 | `mocha test --timeout 600000` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1114 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1113 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1106 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [sorrycc/roadhog](https://github.com/sorrycc/roadhog) | 1103 | `npm run lint && npm run build && cross-env NODE_ENV=test nyc mocha --no-timeouts test/**/*-test.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1101 | `mocha --check-leaks --require @babel/register` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1099 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1093 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1092 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1088 | `node_modules/.bin/mocha && npm run lint` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1083 | `npm run lint && npm run mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1083 | `mocha --reporter spec` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1082 | `nodeunit test; mocha test` | 
| [variety/variety](https://github.com/variety/variety) | 1075 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1072 | `mocha` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1069 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1068 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1064 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1058 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1055 | `mocha --compilers js:babel-register` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1055 | `mocha` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1052 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1050 | `mocha --reporter spec --timeout 3000` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1049 | `mocha test/*` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1044 | `mocha src/test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1043 | `node_modules/.bin/mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1040 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1040 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1035 | `mocha $(find test -name '*.test.js')` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1031 | `standard && istanbul cover _mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1022 | `istanbul test _mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1022 | `xo && mocha` | 
| [jas/playground](https://github.com/jas/playground) | 1021 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1020 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1020 | `mocha --check-leaks -R dot` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1019 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1014 | `mocha --reporter dot` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1013 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1012 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1005 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1002 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 999 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 994 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 992 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 991 | `eslint src && mocha && karma start --single-run` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 988 | `mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 988 | `mocha test/unit` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 983 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 982 | `mocha --colors ./test/*.spec.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 982 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 982 | `mocha test/tests.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 981 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 974 | `mocha` | 
| [googlevr/webvr-polyfill](https://github.com/googlevr/webvr-polyfill) | 971 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 970 | `istanbul cover _mocha test/*.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 968 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 966 | `mocha --check-leaks --reporter spec --bail test/` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 963 | `eslint . && mocha -t 5000` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 962 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 959 | `mocha --timeout 5000` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 958 | `NODE_PATH=. mocha **/*.spec.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 949 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 946 | `mocha -R list` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 945 | `mocha --recursive --bail --reporter spec test` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 945 | `npm run rollup-cjs && mocha test/test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 945 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 944 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 938 | `mocha --recursive test/unit/` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 936 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 935 | `standard && mocha` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 935 | `mocha $(find test -name '*.test.js')` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 932 | `mocha tests/test-*` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 930 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 924 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 921 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 921 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [dabeng/OrgChart](https://github.com/dabeng/OrgChart) | 920 | `mocha ./test/**/*-tests.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 920 | `mocha --reporter spec` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 916 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 914 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [tomas/needle](https://github.com/tomas/needle) | 911 | `mocha test` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 905 | ` NODE_ENV=test mocha --compilers js:babel-register` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 904 | `mocha ./test/index.js` | 
| [router5/router5](https://github.com/router5/router5) | 903 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 902 | `mocha spec/*.spec.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 897 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 895 | `npm run prepublish && mocha test/test.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 892 | `./node_modules/.bin/mocha --globals angular,require` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 892 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 890 | `mocha test` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 889 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 889 | `mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 887 | `standard && mocha -b` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 885 | `mocha -t 120000 test/*.test.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 874 | `mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 874 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 872 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 871 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 871 | `webpack && mocha test/unit` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 870 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 867 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 867 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 867 | `mocha --reporter list` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 863 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 863 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 862 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 860 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 857 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 856 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 855 | `mocha --reporter spec --bail --check-leaks test/` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 854 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 850 | `mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 850 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 849 | `mocha --recursive test` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 846 | `mocha "client.test" --compilers js:babel-register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 843 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 842 | `mocha --reporter spec --bail --check-leaks test/` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 838 | `node_modules/.bin/mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 835 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 832 | `eslint test && mocha --compilers js:babel/register` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 831 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 828 | `mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 827 | `mocha --compilers js:babel-register test/*.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 827 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 827 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 826 | `mocha && standard` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 824 | `npm run lint && mocha -R spec` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 819 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 819 | `nyc mocha --timeout=20000 test.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 819 | `mocha --timeout 200000` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 818 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 816 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 815 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 812 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 812 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 808 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 808 | `mocha && ember test` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 807 | `mocha tests/*.test.js --reporter spec` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 806 | `node_modules/.bin/mocha test/spec` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 806 | `mocha --reporter spec` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 805 | `mocha --reporter spec --bail --check-leaks test/` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 803 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 802 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 800 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 795 | `mocha tests` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 790 | `mocha -R spec tests/` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 790 | `mocha --check-leaks -t 20000` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 788 | `npm run convertto:es5 && npm run mocha` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 787 | `nyc mocha --require babel-register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 786 | `mocha -u tdd` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 784 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 784 | `mocha --require babel-register` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 779 | `istanbul cover _mocha` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 776 | `mocha ./test -R spec` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 775 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 775 | `cake build && mocha ./test/mocha/*.coffee` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 773 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 773 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 772 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 771 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 770 | `mocha --reporter spec --bail --check-leaks test/` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 768 | `standard && standard ./bin/* && mocha` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 767 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 767 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 767 | `mocha -t 5000` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 766 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 764 | `mocha ./test/test*.js --reporter spec` | 
| [edsu/anon](https://github.com/edsu/anon) | 763 | `mocha --colors --reporter spec test.js` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 763 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 761 | `mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 758 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 755 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 751 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 751 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 750 | `mocha test --compilers js:babel-register` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 748 | `npm run lint && mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 748 | `istanbul cover -- _mocha --reporter spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 745 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 742 | `xo && mocha -R spec` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 741 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 739 | `TEST_MODE=unit NODE_ENV=test jest && TEST_MODE=unit NODE_ENV=test mocha -R ${MOCHA_REPORTER:-spec}` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 739 | `mocha --async-only` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 737 | `nyc mocha specs` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 736 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 736 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 734 | `mocha -t 600000` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 734 | `npm run lint && mocha --compilers js:babel-register` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 732 | `mocha -R spec` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 732 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 731 | `mocha -R spec src/**/*_test.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 728 | `mocha` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 728 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 727 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 726 | `mocha --reporter spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 723 | `mocha -R spec --compilers js:babel-core/register ./tests/setup.js ./tests/** --recursive` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 722 | `mocha --ui tdd --require ./test/__setup` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 722 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 722 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 718 | `mocha --reporter list` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 716 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 715 | `mocha spec/*.js` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 714 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 708 | `mocha test.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 707 | `./node_modules/.bin/mocha -R spec` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 705 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 703 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [contra/gulp-concat](https://github.com/contra/gulp-concat) | 699 | `mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 697 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 696 | `mocha tests/*.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 695 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 693 | `npm run bundle && mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 693 | `cross-env NODE_ENV=test nyc mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 687 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 681 | `mocha tests/*.mocha.js` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 681 | `npm run lint && mocha test` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 678 | `mocha ./test/index.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 676 | `npm run mocha-test test/integration` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 676 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 676 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 675 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 674 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require babel-register --no-timeouts` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 672 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 671 | `npm run build && istanbul test _mocha test/test.js` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 670 | `mocha -b -R spec test/*` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 670 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 670 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 667 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 666 | `eslint src test && mocha --compilers babel-register` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 665 | `mocha --reporter spec` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 664 | `mocha test` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 664 | `mocha test` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 663 | `mocha --reporter spec` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 663 | `mocha` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 662 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 658 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 658 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 656 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 656 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 653 | `mocha` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 652 | `./node_modules/.bin/mocha test/integration` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 652 | `mocha` | 