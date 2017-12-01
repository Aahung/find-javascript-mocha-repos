# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:17 12/01/17 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39160 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 37541 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 35336 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 34406 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28066 | `mocha --reporter spec` | 
| [caolan/async](https://github.com/caolan/async) | 22797 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 19410 | `mocha test/index.js` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 16868 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [developit/preact](https://github.com/developit/preact) | 16435 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15064 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14093 | `mocha test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13539 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12196 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12114 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11867 | `mocha` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 11591 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11450 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11438 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11171 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 10211 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10190 | `nyc grunt mocha-and-karma` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10186 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 9593 | `NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9390 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9090 | `mocha --reporter spec` | 
| [tj/co](https://github.com/tj/co) | 9049 | `mocha --harmony` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 8898 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 8823 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tmpvar/jsdom](https://github.com/tmpvar/jsdom) | 8788 | `mocha test/index.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 8761 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8654 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [svg/svgo](https://github.com/svg/svgo) | 8512 | `set NODE_ENV=test && mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8311 | `grunt mocha` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8083 | `mocha --check-leaks -R dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8041 | `mocha test/*-test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 7992 | `grunt clean:test && mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 7952 | `mocha test/test.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 7688 | `mocha` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7607 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7491 | `./node_modules/.bin/mocha test/src` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7428 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7419 | `mocha` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7299 | `mocha --compilers js:babel-register test/test.js` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7135 | `npm run eslint && npm run mocha` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7077 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7018 | `npm run build && istanbul cover _mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 6881 | `./node_modules/.bin/mocha test` | 
| [websockets/ws](https://github.com/websockets/ws) | 6849 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [amark/gun](https://github.com/amark/gun) | 6819 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 6745 | `mocha tests/*.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 6734 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6402 | `mocha $HARMONY_OPTS` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6272 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6237 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6180 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6090 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6067 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 5992 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [almende/vis](https://github.com/almende/vis) | 5944 | `mocha --compilers js:babel-core/register` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5930 | `mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 5877 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 5706 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5603 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5598 | `npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 5578 | `nyc mocha test/** -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 5523 | `mocha --opts mocha.opts` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5468 | `npm run test:mocha:src` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5388 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5378 | `npm run jshint && mocha test/` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 5335 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5327 | `mocha tests/node.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5278 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5242 | `mocha && eslint lib/**` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5224 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5163 | `mocha --color` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5123 | `mocha test --recursive` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5104 | `mocha src/**/*Tests.js --harmony` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5095 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5010 | `mocha test/test.js` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 4892 | `mocha --timeout 10000 && npm run lint` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4769 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4711 | `gulp lint && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4703 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4652 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4604 | `mocha test` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4551 | `mocha --reporter spec -t 8000` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4547 | `mocha -R spec 'tests/app'` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4515 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4503 | `mocha ./test/runner.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 4497 | `mocha --compilers js:babel-core/register` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4354 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4315 | `gulp build; mocha;` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4295 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4245 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4222 | `mocha -R spec ./test --recursive` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4213 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4195 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4162 | `./node_modules/.bin/mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4148 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4089 | `standard && mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4071 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4060 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 3969 | `mocha` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 3950 | `mocha && ./bin/shipit staging test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3911 | `nyc mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 3910 | `mocha test` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3891 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [erming/shout](https://github.com/erming/shout) | 3813 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3810 | `export TESTING=true; mocha --reporter list` | 
| [botpress/botpress](https://github.com/botpress/botpress) | 3800 | `BABEL_ENV=tests mocha --compilers js:babel-core/register --require tests/index.js tests/** extensions/**/tests/**` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 3762 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 3745 | `mocha` | 
| [muicss/mui](https://github.com/muicss/mui) | 3708 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3674 | `mocha --require should --reporter spec` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3627 | `npm run jshint && npm run mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3589 | `mocha && make test` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3541 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3531 | `NODE_ENV=test mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3522 | `standard && mocha --timeout 60000 test/test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3517 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3492 | `mocha tests/javascript` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3468 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3453 | `mocha --require test/babel-hook test/*.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3452 | `npm run lint && npm run mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3398 | `mocha --reporter spec --timeout 3000` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3398 | `npm run lint ; mocha && mocha test/individual` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3396 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [primus/primus](https://github.com/primus/primus) | 3371 | `npm run build && mocha test/*.test.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3370 | `mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3368 | `node_modules/.bin/mocha test/lib/` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3334 | `nyc mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3315 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3258 | `npm run lint && mocha && EIO_WS_ENGINE=ws mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3223 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3070 | `mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3051 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3048 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3038 | `./node_modules/.bin/mocha test/test.*.js` | 
| [easy-mock/easy-mock](https://github.com/easy-mock/easy-mock) | 3010 | `cross-env NODE_ENV=test istanbul cover _mocha test/*` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 3009 | `npm run build-cli && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 2983 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 2973 | `mocha --check-leaks --reporter spec --bail` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 2970 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 2961 | `node_modules/.bin/mocha test/tests.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 2944 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2938 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2878 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 2876 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 2850 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2848 | `mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 2840 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 2826 | `nyc mocha "test/**/*.test.js"` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2783 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2757 | `mocha test/*.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2751 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2749 | `mocha --require should --reporter spec` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 2741 | `npm run lint && npm run mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 2728 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2719 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2718 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2691 | `mocha -R spec --recursive src/test` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2671 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2662 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2661 | `istanbul cover _mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2597 | `mocha test/index.js && npm run demo` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2592 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2584 | `xo && mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2576 | `mocha --timeout 100000` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2569 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2566 | `mocha-phantomjs ./test/index.html` | 
| [github-tools/github](https://github.com/github-tools/github) | 2539 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2520 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2511 | `nyc mocha && tsc` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2505 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2484 | `NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [css/csso](https://github.com/css/csso) | 2477 | `mocha --reporter dot` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 2469 | `mocha; jshint *.js lib` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2462 | `mocha -R spec --compilers js:babel-register ./test/endpoint.js` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2461 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2457 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2456 | `mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2454 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2452 | `mocha --recursive --watch` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2450 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2449 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2442 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2436 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2435 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2431 | `npm run mocha && npm run lint` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2413 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2400 | `mocha --compilers js:babel-register --recursive spec` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2388 | `mocha --reporter=spec test/*-test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2388 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2382 | `mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2374 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2363 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2360 | `node node_modules/mocha/bin/_mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2349 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2310 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2307 | `grunt jshint && mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2289 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2284 | `mocha --opts mocha.opts` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2281 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2280 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2275 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2270 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2254 | `mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2248 | `mocha` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2241 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2241 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2219 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2216 | `mocha test/src/**/*.unit.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2209 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2197 | `mocha test test/unit/**/*_test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2190 | `mocha test` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2184 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2171 | `npm run compile && mocha --compilers js:babel-core/register` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2166 | `gulp && cd test && mocha . --reporter dot` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2150 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2145 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [octokit/node-github](https://github.com/octokit/node-github) | 2140 | `nyc mocha test/**/*-test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2113 | `node_modules/.bin/mocha --reporter spec` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2108 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2093 | `NODE_ENV=test mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2088 | `npm run lint && npm run build && npm run mocha` | 
| [mozilla/send](https://github.com/mozilla/send) | 2083 | `mocha test/unit` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2080 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2072 | `mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2070 | `mocha --compilers js:babel-register` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2069 | `mocha -R spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2049 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2043 | `mocha test/unit --require mochahook` | 
| [json5/json5](https://github.com/json5/json5) | 2027 | `mocha --ui exports --reporter spec` | 
| [slate/slate](https://github.com/slate/slate) | 2023 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2013 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 1997 | `cross-env BABEL_ENV=test mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 1991 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 1984 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 1940 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 1928 | `nyc --reporter=html --reporter=text mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 1913 | `mocha --require should --reporter spec` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1911 | `mocha --require=test/test_helper.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1892 | `mocha --bail --reporter spec --check-leaks test/` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1869 | `mocha -R spec test/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1866 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1832 | `mocha test/index.js --reporter dot` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1831 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1830 | `mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1824 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1819 | `mocha tests.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 1816 | `mocha ./test/*.spec.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1812 | `mocha --timeout 5000` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1810 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [punkave/apostrophe](https://github.com/punkave/apostrophe) | 1807 | `mocha` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1795 | `mocha --require ./test/common --growl test/expect.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1775 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 1773 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1765 | `mocha --reporter spec --timeout 5000` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1759 | `mocha test && npm run lint` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1757 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [Qix-/color](https://github.com/Qix-/color) | 1756 | `mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1747 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1744 | `cross-env NODE_ENV=test mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1737 | `mocha test/**/*_test.js --bail` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1731 | `mocha test` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1714 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1702 | `mocha test.js` | 
| [then/promise](https://github.com/then/promise) | 1697 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1696 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1696 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1695 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1695 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1688 | `mocha test/runner.js --reporter spec` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1678 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1673 | `xo && mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1663 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1656 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1655 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1650 | `mocha --compilers js:babel-register` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1647 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1646 | `mocha --compilers js:babel-core/register __tests__` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1646 | `mocha test` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1645 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1644 | `mocha -R landing test/index` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1639 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1638 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1637 | `./node_modules/.bin/mocha` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1637 | `npm run lint && npm run compile && mocha --reporter spec test/*.js` | 
| [Hardmath123/nearley](https://github.com/Hardmath123/nearley) | 1633 | `mocha test/*.test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1632 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1604 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1604 | `mocha tests/test.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1603 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1602 | `mocha --reporter spec && npm run test-typescript` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1601 | `mocha -R spec spec spec/reporters` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1597 | `lint && mocha --recursive` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1595 | `npm run lint && npm run mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1593 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [KunalKapadia/express-mongoose-es6-rest-api](https://github.com/KunalKapadia/express-mongoose-es6-rest-api) | 1593 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1591 | `mocha --expose-gc --slow 300` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1588 | `mocha && eslint *.js` | 
| [verdaccio/verdaccio](https://github.com/verdaccio/verdaccio) | 1575 | `mocha ./test/functional ./test/unit --reporter=spec --full-trace` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1575 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1572 | `mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1569 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1568 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1563 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1561 | `./node_modules/mocha/bin/mocha -R spec` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1560 | `mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1546 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1536 | `./node_modules/.bin/mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1534 | `mocha test/*.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1515 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1504 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1503 | `npm run lint && mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1495 | `mocha && npm run lint` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1488 | `mocha --reporter spec --grep .` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1487 | `npm run mocha && npm run karma` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1486 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1482 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1470 | `npm run mocha && npm run lint` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1460 | `mocha -R spec` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1457 | `mocha` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1455 | `mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1450 | `nyc npm run _mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1450 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1448 | `mocha tests --compilers js:babel-core/register` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1446 | `mocha spec/` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1445 | `./node_modules/mocha/bin/mocha -R spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1444 | `mocha -u tdd` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1440 | `mocha ./test/basic.js -t 5000` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1439 | `mocha test/* --reporter spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1437 | `mocha test/` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1435 | `mocha test -u bdd -R spec` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1433 | `node_modules/.bin/mocha --recursive` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1432 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1430 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1426 | `mocha test/tests.js --timeout=10000` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1420 | `npm run lint && mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1414 | `npm run test:lint && npm run test:mocha && npm run site` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1400 | `mocha test.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 1396 | `npm run lint && npm run mocha` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1388 | `mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1387 | `mocha test/**/*.spec.js` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1385 | `mocha --reporter spec` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1368 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1352 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1344 | `nyc mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1343 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1339 | `./node_modules/mocha/bin/mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1329 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1318 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1312 | `mocha --check-leaks -R dot` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1310 | `cross-env NODE_ENV=test nyc mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1309 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1307 | `standard "./src/*.js" && mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 1304 | `./node_modules/.bin/mocha && npm run jshint` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1301 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1301 | `eslint --rulesdir=dev-tools/eslint --cache . && tsc && mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1298 | `mocha --reporter spec test/*.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1283 | `istanbul cover _mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1280 | `mocha --recursive` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1269 | `mocha --compilers js:babel-register` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1262 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1258 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1257 | `mocha test.js` | 
| [trufflesuite/ganache-cli](https://github.com/trufflesuite/ganache-cli) | 1244 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1241 | `npm run build && mocha -r should` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1228 | `mocha` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1220 | `standard "src/*.js" && npm run build && mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1218 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1216 | `./node_modules/.bin/mocha test` | 
| [sandeepmistry/bleno](https://github.com/sandeepmistry/bleno) | 1216 | `mocha -R spec test/*.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1213 | `mocha-phantomjs tests/index.html` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1209 | `mocha --timeout 10000 ./tests/lib.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1205 | `mocha spec/exec.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1204 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1195 | `mocha tests` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1193 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1192 | `mocha --check-leaks --reporter spec --bail` | 
| [zeit/ms](https://github.com/zeit/ms) | 1190 | `mocha tests.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1190 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1189 | `mocha test/test.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1185 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1181 | `mocha test/setup.js test/spec/*.js` | 
| [reddit/reddit-mobile](https://github.com/reddit/reddit-mobile) | 1177 | `mocha test/index.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1177 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1173 | `mocha test/**/*Spec.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1172 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1172 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1171 | `mocha test/*.js` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1168 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1167 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1162 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1161 | `mocha test` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1155 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1154 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1147 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1147 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1147 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1143 | `istanbul cover _mocha test -- --timeout 20000` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1141 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1140 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1137 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1136 | `node ./node_modules/mocha/bin/mocha tests` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1134 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1132 | `mocha --full-trace --check-leaks` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1132 | `mocha --full-trace --check-leaks` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1130 | `./node_modules/.bin/mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1130 | `mocha --recursive` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1128 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1127 | `eslint lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1125 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1118 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1107 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1105 | `mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1103 | `mocha --opts test/opts/mocha.opts` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1095 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1094 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1094 | `mocha compiled_tests/` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1091 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1089 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1087 | `node_modules/.bin/mocha && npm run lint` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1076 | `npm run lint && npm run mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1073 | `mocha --reporter spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1068 | `mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1066 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1065 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1062 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1058 | `mocha --check-leaks --require @babel/register` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1054 | `mocha --check-leaks -t 20000` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1054 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1052 | `mocha --reporter spec --timeout 3000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1051 | `mocha --compilers js:babel-register` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1046 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1045 | `mocha test/*` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1041 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1034 | `node_modules/.bin/mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1031 | `mocha $(find test -name '*.test.js')` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1027 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1027 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1026 | `mocha src/test.js` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1026 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [jas/playground](https://github.com/jas/playground) | 1023 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1020 | `istanbul test _mocha` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1020 | `mocha --check-leaks -R dot` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1018 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1016 | `xo && mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1013 | `standard && istanbul cover _mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1000 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1000 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [sorrycc/roadhog](https://github.com/sorrycc/roadhog) | 997 | `npm run lint && npm run build && cross-env NODE_ENV=test nyc mocha --no-timeouts test/**/*-test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 996 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 991 | `mocha --reporter dot` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 986 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 985 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 985 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 983 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 980 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 979 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 979 | `mocha --colors ./test/*.spec.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 977 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 976 | `mocha test/tests.js` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 972 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 972 | `eslint src && mocha && karma start --single-run` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 969 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 968 | `mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 962 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 960 | `mocha test/unit` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 960 | `mocha --timeout 5000` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 958 | `mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 957 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 954 | `istanbul cover _mocha test/*.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 953 | `npm run lint && mocha -R dot && npm run cover` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 949 | `mocha --check-leaks --reporter spec --bail test/` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 944 | `npm run rollup-cjs && mocha test/test.js` | 
| [googlevr/webvr-polyfill](https://github.com/googlevr/webvr-polyfill) | 942 | `mocha` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 942 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 941 | `mocha test --timeout 600000` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 940 | `mocha --recursive --bail --reporter spec test` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 940 | `mocha -R list` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 934 | `mocha --recursive test/unit/` | 
| [motdotla/node-lambda](https://github.com/motdotla/node-lambda) | 933 | `standard && standard bin/node-lambda && mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 931 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 930 | `mocha test/.setup.js 'test/**/*.spec.js'` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 925 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 924 | `mocha $(find test -name '*.test.js')` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 922 | `standard && mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 920 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 915 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 915 | `mocha --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 912 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 911 | `mocha --async-only` | 
| [watson-developer-cloud/node-sdk](https://github.com/watson-developer-cloud/node-sdk) | 911 | `npm run lint && mocha test/unit test/integration` | 
| [tomas/needle](https://github.com/tomas/needle) | 908 | `mocha test` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 908 | `NODE_PATH=. mocha **/*.spec.js` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 904 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 902 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 901 | `mocha spec/*.spec.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 900 | `eslint . && mocha -t 5000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 894 | `./node_modules/.bin/mocha --globals angular,require` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 894 | `mocha tests/test-*` | 
| [router5/router5](https://github.com/router5/router5) | 894 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 891 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [dabeng/OrgChart](https://github.com/dabeng/OrgChart) | 889 | `mocha ./test/**/*-tests.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 883 | ` NODE_ENV=test mocha --compilers js:babel-register` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 879 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 877 | `standard && mocha -b` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 876 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 876 | `mocha` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 876 | `mocha -t 120000 test/*.test.js` | 
| [alizain/ulid](https://github.com/alizain/ulid) | 876 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha -- -R spec` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 872 | `mocha test/test.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 872 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 868 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 864 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 864 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 864 | `mocha --reporter list` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 860 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 860 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 860 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 855 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 853 | `mocha test` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 852 | `webpack && mocha test/unit` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 851 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 851 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 847 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [electron/asar](https://github.com/electron/asar) | 844 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 842 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 839 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 838 | `mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 838 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 835 | `mocha "client.test" --compilers js:babel-register` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 835 | `mocha --reporter spec --bail --check-leaks test/` | 
| [teambit/bit](https://github.com/teambit/bit) | 833 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 832 | `node_modules/.bin/mocha` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 832 | `mocha --recursive test` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 832 | `eslint test && mocha --compilers js:babel/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 830 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 829 | `mocha --reporter spec --bail --check-leaks test/` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 825 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 824 | `mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 823 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 819 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 817 | `npm run lint && mocha -R spec` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 815 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 813 | `mocha --compilers js:babel-register test/*.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 811 | `mocha --timeout 200000` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 809 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 808 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 807 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 806 | `mocha && ember test` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 805 | `mocha tests/*.test.js --reporter spec` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 804 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 804 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 803 | `mocha --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 802 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [electron/spectron](https://github.com/electron/spectron) | 797 | `mocha && standard` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 796 | `node_modules/.bin/mocha test/spec` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 794 | `mocha --reporter spec --bail --check-leaks test/` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 792 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 791 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 790 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 790 | `mocha tests` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 788 | `mocha -R spec tests/` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 786 | `mocha --check-leaks -t 20000` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 785 | `mocha -u tdd` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 782 | `mocha --require babel-register` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 779 | `npm run convertto:es5 && npm run mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 777 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 776 | `nyc mocha --timeout=20000 test.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 773 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 769 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 769 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 768 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 768 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 767 | `mocha --reporter spec --bail --check-leaks test/` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 767 | `istanbul cover _mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 767 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 767 | `nyc mocha --require babel-register` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 760 | `mocha` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 758 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [edsu/anon](https://github.com/edsu/anon) | 758 | `mocha --colors --reporter spec test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 758 | `mocha -t 5000` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 757 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 757 | `mocha ./test -R spec` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 756 | `standard && standard ./bin/* && mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 752 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 750 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 747 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 746 | `npm run lint && mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 745 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 744 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 742 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 741 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 740 | `mocha test --compilers js:babel-register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 739 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 736 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 736 | `istanbul cover -- _mocha --reporter spec` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 732 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 732 | `xo && mocha -R spec` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 730 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 727 | `mocha -R spec src/**/*_test.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 726 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 726 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 725 | `nyc mocha specs` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 725 | `mocha --reporter spec` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 725 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 724 | `mocha --async-only` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 723 | `mocha ./test/test*.js --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 720 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 719 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 717 | `mocha --ui tdd --require ./test/__setup` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 716 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [typicode/katon](https://github.com/typicode/katon) | 715 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 714 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 714 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 712 | `mocha -t 600000` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 712 | `mocha -R spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 711 | `mocha --reporter list` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 710 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 705 | `mocha spec/*.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 704 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 704 | `mocha test.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 698 | `./node_modules/.bin/mocha -R spec` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 694 | `npm run lint && mocha --compilers js:babel-register` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 693 | `npm run bundle && mocha` | 
| [contra/gulp-concat](https://github.com/contra/gulp-concat) | 691 | `mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 690 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 680 | `npm run lint && mocha test` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 680 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 678 | `mocha tests/*.mocha.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 676 | `mocha ./test/index.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 674 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 671 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 671 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 670 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 670 | `npm run mocha-test test/integration` | 
| [sindresorhus/gulp-changed](https://github.com/sindresorhus/gulp-changed) | 669 | `xo && mocha` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 669 | `mocha -b -R spec test/*` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 668 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 667 | `mocha -R spec --compilers js:babel-core/register ./tests/setup.js ./tests/** --recursive` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 667 | `cross-env NODE_ENV=test nyc mocha` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 664 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 663 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 663 | `npm run lint && nyc mocha test/**` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 663 | `mocha` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 662 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 662 | `mocha --reporter spec` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 662 | `mocha --reporter spec` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 661 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 661 | `mocha test` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 658 | `mocha tests/*.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 658 | `npm run build && istanbul test _mocha test/test.js` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 657 | `mocha` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 657 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 654 | `mocha test` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 653 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 652 | `./node_modules/.bin/mocha test/integration` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 651 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 650 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 647 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 645 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 641 | `npm run lint && mocha ./test/test.js --timeout 1000000` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 641 | `mocha` | 