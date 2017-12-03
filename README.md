# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:02:29 12/03/17 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39177 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 37564 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 35365 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 34465 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28080 | `mocha --reporter spec` | 
| [caolan/async](https://github.com/caolan/async) | 22810 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 21078 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 19436 | `mocha test/index.js` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 16884 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [developit/preact](https://github.com/developit/preact) | 16458 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15071 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14105 | `mocha test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13543 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12205 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12127 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11870 | `mocha` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 11605 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11454 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11446 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11181 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 10230 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10202 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10200 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 9608 | `NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9399 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9100 | `mocha --reporter spec` | 
| [tj/co](https://github.com/tj/co) | 9055 | `mocha --harmony` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 8908 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 8830 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tmpvar/jsdom](https://github.com/tmpvar/jsdom) | 8794 | `mocha test/index.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 8771 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8661 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [svg/svgo](https://github.com/svg/svgo) | 8525 | `set NODE_ENV=test && mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8324 | `grunt mocha` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8082 | `mocha --check-leaks -R dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8050 | `mocha test/*-test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 7993 | `grunt clean:test && mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 7953 | `mocha test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7608 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7498 | `./node_modules/.bin/mocha test/src` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7436 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7422 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7388 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7301 | `mocha --compilers js:babel-register test/test.js` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7140 | `npm run eslint && npm run mocha` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7084 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7024 | `npm run build && istanbul cover _mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 6884 | `./node_modules/.bin/mocha test` | 
| [websockets/ws](https://github.com/websockets/ws) | 6866 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [amark/gun](https://github.com/amark/gun) | 6832 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 6753 | `mocha tests/*.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 6744 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6406 | `mocha $HARMONY_OPTS` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6281 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6245 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6190 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6097 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6080 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 5997 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [almende/vis](https://github.com/almende/vis) | 5952 | `mocha --compilers js:babel-core/register` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5929 | `mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 5884 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 5716 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5607 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5605 | `npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 5588 | `nyc mocha test/** -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 5535 | `mocha --opts mocha.opts` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5471 | `npm run test:mocha:src` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5388 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5380 | `npm run jshint && mocha test/` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 5355 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5331 | `mocha tests/node.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5291 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5244 | `mocha && eslint lib/**` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5226 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5163 | `mocha --color` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5128 | `mocha test --recursive` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5106 | `mocha src/**/*Tests.js --harmony` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5104 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5015 | `mocha test/test.js` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 4899 | `mocha --timeout 10000 && npm run lint` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4772 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4713 | `gulp lint && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4704 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4654 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4605 | `mocha test` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4554 | `mocha --reporter spec -t 8000` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4548 | `mocha -R spec 'tests/app'` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4519 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 4513 | `mocha --compilers js:babel-core/register` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4504 | `mocha ./test/runner.js` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4355 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4320 | `gulp build; mocha;` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4296 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4246 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4224 | `mocha -R spec ./test --recursive` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4215 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4211 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4163 | `./node_modules/.bin/mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4155 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4098 | `standard && mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4076 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4062 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 3973 | `mocha` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 3951 | `mocha && ./bin/shipit staging test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3913 | `nyc mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 3912 | `mocha test` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3891 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [erming/shout](https://github.com/erming/shout) | 3811 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3809 | `export TESTING=true; mocha --reporter list` | 
| [botpress/botpress](https://github.com/botpress/botpress) | 3805 | `BABEL_ENV=tests mocha --compilers js:babel-core/register --require tests/index.js tests/** extensions/**/tests/**` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 3768 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 3748 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3676 | `mocha --require should --reporter spec` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3627 | `npm run jshint && npm run mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3593 | `mocha && make test` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3541 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3536 | `NODE_ENV=test mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3523 | `standard && mocha --timeout 60000 test/test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3519 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3492 | `mocha tests/javascript` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3475 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3460 | `mocha --require test/babel-hook test/*.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3456 | `npm run lint && npm run mocha` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3402 | `npm run lint ; mocha && mocha test/individual` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3399 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3398 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [primus/primus](https://github.com/primus/primus) | 3372 | `npm run build && mocha test/*.test.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3371 | `mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3370 | `node_modules/.bin/mocha test/lib/` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3335 | `nyc mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3317 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3262 | `npm run lint && mocha && EIO_WS_ENGINE=ws mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3230 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3073 | `mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3055 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3049 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3038 | `./node_modules/.bin/mocha test/test.*.js` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 3034 | `npm run build-cli && mocha` | 
| [easy-mock/easy-mock](https://github.com/easy-mock/easy-mock) | 3015 | `cross-env NODE_ENV=test istanbul cover _mocha test/*` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 2987 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 2979 | `mocha --check-leaks --reporter spec --bail` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 2977 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 2962 | `node_modules/.bin/mocha test/tests.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 2953 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2940 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2882 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 2879 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 2858 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2852 | `mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 2842 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 2830 | `nyc mocha "test/**/*.test.js"` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2785 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2759 | `mocha test/*.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2752 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2749 | `mocha --require should --reporter spec` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 2746 | `npm run lint && npm run mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 2746 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2733 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2722 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2721 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2692 | `mocha -R spec --recursive src/test` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2675 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2667 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2660 | `istanbul cover _mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2601 | `mocha test/index.js && npm run demo` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2593 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2584 | `xo && mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2576 | `mocha --timeout 100000` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2571 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2567 | `mocha-phantomjs ./test/index.html` | 
| [github-tools/github](https://github.com/github-tools/github) | 2541 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2524 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2515 | `nyc mocha && tsc` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2507 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2499 | `export TESTING=true; mocha --reporter list` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2487 | `NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 2485 | `mocha; jshint *.js lib` | 
| [css/csso](https://github.com/css/csso) | 2477 | `mocha --reporter dot` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2465 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2465 | `mocha -R spec --compilers js:babel-register ./test/endpoint.js` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2458 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2456 | `mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2456 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2455 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2452 | `mocha --recursive --watch` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2450 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2443 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2442 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2440 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2432 | `npm run mocha && npm run lint` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2416 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2402 | `mocha --compilers js:babel-register --recursive spec` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2390 | `mocha --reporter=spec test/*-test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2390 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2384 | `mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2374 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2366 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2360 | `node node_modules/mocha/bin/_mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2353 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2310 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2307 | `grunt jshint && mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2302 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2290 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2285 | `mocha --opts mocha.opts` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2284 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2275 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2274 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2257 | `mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2248 | `mocha` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2244 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2243 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2219 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2218 | `mocha test/src/**/*.unit.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2209 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2199 | `mocha test test/unit/**/*_test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2192 | `mocha test` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2190 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2175 | `npm run compile && mocha --compilers js:babel-core/register` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2166 | `gulp && cd test && mocha . --reporter dot` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2158 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2150 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [octokit/node-github](https://github.com/octokit/node-github) | 2140 | `nyc mocha test/**/*-test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2117 | `node_modules/.bin/mocha --reporter spec` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2109 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2096 | `NODE_ENV=test mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2092 | `npm run lint && npm run build && npm run mocha` | 
| [mozilla/send](https://github.com/mozilla/send) | 2085 | `mocha test/unit` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2081 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [gajus/swing](https://github.com/gajus/swing) | 2077 | `mocha --compilers js:babel-register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2071 | `mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2071 | `mocha -R spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2054 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2048 | `mocha test/unit --require mochahook` | 
| [json5/json5](https://github.com/json5/json5) | 2032 | `mocha --ui exports --reporter spec` | 
| [slate/slate](https://github.com/slate/slate) | 2023 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2013 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 1998 | `cross-env BABEL_ENV=test mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 1996 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 1989 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 1942 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 1930 | `nyc --reporter=html --reporter=text mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 1918 | `mocha --require should --reporter spec` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1911 | `mocha --require=test/test_helper.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1892 | `mocha --bail --reporter spec --check-leaks test/` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1873 | `mocha -R spec test/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1866 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1833 | `mocha test/index.js --reporter dot` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1832 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1831 | `mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1824 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1819 | `mocha tests.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 1816 | `mocha ./test/*.spec.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1811 | `mocha --timeout 5000` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1810 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [punkave/apostrophe](https://github.com/punkave/apostrophe) | 1808 | `mocha` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1796 | `mocha --require ./test/common --growl test/expect.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 1778 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1775 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1767 | `mocha --reporter spec --timeout 5000` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1762 | `mocha test && npm run lint` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1757 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [Qix-/color](https://github.com/Qix-/color) | 1757 | `mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1745 | `cross-env NODE_ENV=test mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1737 | `mocha test/**/*_test.js --bail` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1731 | `mocha test` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1715 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1704 | `mocha test.js` | 
| [then/promise](https://github.com/then/promise) | 1700 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1697 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1697 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 1697 | `export TESTING=true; mocha --reporter list` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1696 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1695 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 