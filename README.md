# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:28:15 11/30/17 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39151 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 37519 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 35310 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 34357 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28058 | `mocha --reporter spec` | 
| [caolan/async](https://github.com/caolan/async) | 22787 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 21039 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 19398 | `mocha test/index.js` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 16855 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [developit/preact](https://github.com/developit/preact) | 16421 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15049 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14084 | `mocha test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13535 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12187 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12106 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11862 | `mocha` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 11581 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11437 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11434 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11165 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 10197 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10183 | `nyc grunt mocha-and-karma` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10181 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 9583 | `NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9379 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9084 | `mocha --reporter spec` | 
| [tj/co](https://github.com/tj/co) | 9044 | `mocha --harmony` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 8885 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 8818 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tmpvar/jsdom](https://github.com/tmpvar/jsdom) | 8778 | `mocha test/index.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 8755 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8645 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [svg/svgo](https://github.com/svg/svgo) | 8503 | `set NODE_ENV=test && mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8297 | `grunt mocha` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8081 | `mocha --check-leaks -R dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8037 | `mocha test/*-test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 7989 | `grunt clean:test && mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 7951 | `mocha test/test.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 7683 | `mocha` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7606 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7482 | `./node_modules/.bin/mocha test/src` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7421 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7418 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7385 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7297 | `mocha --compilers js:babel-register test/test.js` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7131 | `npm run eslint && npm run mocha` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7063 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7016 | `npm run build && istanbul cover _mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 6876 | `./node_modules/.bin/mocha test` | 
| [websockets/ws](https://github.com/websockets/ws) | 6837 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [amark/gun](https://github.com/amark/gun) | 6809 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 6736 | `mocha tests/*.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 6722 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6401 | `mocha $HARMONY_OPTS` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6261 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6227 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6167 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6085 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6058 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 5986 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [almende/vis](https://github.com/almende/vis) | 5938 | `mocha --compilers js:babel-core/register` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5931 | `mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 5868 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 5698 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5599 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5597 | `npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 5566 | `nyc mocha test/** -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 5519 | `mocha --opts mocha.opts` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5465 | `npm run test:mocha:src` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5387 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5373 | `npm run jshint && mocha test/` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5326 | `mocha tests/node.js` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 5317 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5273 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5240 | `mocha && eslint lib/**` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5225 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5164 | `mocha --color` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5116 | `mocha test --recursive` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5103 | `mocha src/**/*Tests.js --harmony` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5092 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5005 | `mocha test/test.js` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 4890 | `mocha --timeout 10000 && npm run lint` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4765 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4710 | `gulp lint && mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4699 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4651 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4604 | `mocha test` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4551 | `mocha --reporter spec -t 8000` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4547 | `mocha -R spec 'tests/app'` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4511 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4503 | `mocha ./test/runner.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 4483 | `mocha --compilers js:babel-core/register` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4354 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4313 | `gulp build; mocha;` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4295 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4240 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4223 | `mocha -R spec ./test --recursive` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4210 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4187 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4161 | `./node_modules/.bin/mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4143 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4086 | `standard && mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4070 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4056 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 3965 | `mocha` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 3948 | `mocha && ./bin/shipit staging test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3911 | `nyc mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 3910 | `mocha test` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3891 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [erming/shout](https://github.com/erming/shout) | 3813 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3812 | `export TESTING=true; mocha --reporter list` | 
| [botpress/botpress](https://github.com/botpress/botpress) | 3796 | `BABEL_ENV=tests mocha --compilers js:babel-core/register --require tests/index.js tests/** extensions/**/tests/**` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 3759 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 3736 | `mocha` | 
| [muicss/mui](https://github.com/muicss/mui) | 3708 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3669 | `mocha --require should --reporter spec` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3627 | `npm run jshint && npm run mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3585 | `mocha && make test` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3541 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3527 | `NODE_ENV=test mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3521 | `standard && mocha --timeout 60000 test/test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3515 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3488 | `mocha tests/javascript` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3463 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3450 | `mocha --require test/babel-hook test/*.js` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3448 | `npm run lint && npm run mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3396 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3396 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3392 | `npm run lint ; mocha && mocha test/individual` | 
| [primus/primus](https://github.com/primus/primus) | 3368 | `npm run build && mocha test/*.test.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3368 | `mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3368 | `node_modules/.bin/mocha test/lib/` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3332 | `nyc mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3315 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3257 | `npm run lint && mocha && EIO_WS_ENGINE=ws mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3219 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3070 | `mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3051 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3048 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3037 | `./node_modules/.bin/mocha test/test.*.js` | 
| [easy-mock/easy-mock](https://github.com/easy-mock/easy-mock) | 2998 | `cross-env NODE_ENV=test istanbul cover _mocha test/*` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 2995 | `npm run build-cli && mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 2977 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 2973 | `mocha --check-leaks --reporter spec --bail` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 2963 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 2961 | `node_modules/.bin/mocha test/tests.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2936 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 2936 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2878 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 2871 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2848 | `mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 2843 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 2834 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 2824 | `nyc mocha "test/**/*.test.js"` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2781 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2757 | `mocha test/*.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2749 | `mocha --require should --reporter spec` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2748 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 2735 | `npm run lint && npm run mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2732 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2719 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2717 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 2709 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2691 | `mocha -R spec --recursive src/test` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2670 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2660 | `istanbul cover _mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2660 | `mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2595 | `mocha test/index.js && npm run demo` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2588 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2584 | `xo && mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2574 | `mocha --timeout 100000` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2569 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2566 | `mocha-phantomjs ./test/index.html` | 
| [github-tools/github](https://github.com/github-tools/github) | 2539 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2509 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2507 | `nyc mocha && tsc` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2501 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2481 | `NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [css/csso](https://github.com/css/csso) | 2476 | `mocha --reporter dot` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2460 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2459 | `mocha -R spec --compilers js:babel-register ./test/endpoint.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 2458 | `mocha; jshint *.js lib` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2457 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2453 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2452 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2452 | `mocha --recursive --watch` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2447 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2444 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2440 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2431 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2428 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2425 | `npm run mocha && npm run lint` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2409 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2398 | `mocha --compilers js:babel-register --recursive spec` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2387 | `mocha --reporter=spec test/*-test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2385 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2381 | `mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2372 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2362 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2360 | `node node_modules/mocha/bin/_mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2346 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2310 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2302 | `grunt jshint && mocha` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2282 | `mocha --opts mocha.opts` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2280 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2278 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2278 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2275 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2269 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2254 | `mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2248 | `mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2241 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2239 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2219 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2215 | `mocha test/src/**/*.unit.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2209 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2196 | `mocha test test/unit/**/*_test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2188 | `mocha test` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2182 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2163 | `gulp && cd test && mocha . --reporter dot` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2163 | `npm run compile && mocha --compilers js:babel-core/register` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2143 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2143 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [octokit/node-github](https://github.com/octokit/node-github) | 2140 | `nyc mocha test/**/*-test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2111 | `node_modules/.bin/mocha --reporter spec` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2108 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2091 | `NODE_ENV=test mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2087 | `npm run lint && npm run build && npm run mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2078 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [mozilla/send](https://github.com/mozilla/send) | 2077 | `mocha test/unit` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2072 | `mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2070 | `mocha --compilers js:babel-register` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2067 | `mocha -R spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2044 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2042 | `mocha test/unit --require mochahook` | 
| [slate/slate](https://github.com/slate/slate) | 2023 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [json5/json5](https://github.com/json5/json5) | 2016 | `mocha --ui exports --reporter spec` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2013 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 1997 | `cross-env BABEL_ENV=test mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 1990 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 1981 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 1936 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 1927 | `nyc --reporter=html --reporter=text mocha` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1910 | `mocha --require=test/test_helper.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 1909 | `mocha --require should --reporter spec` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1891 | `mocha --bail --reporter spec --check-leaks test/` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1869 | `mocha -R spec test/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1866 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1832 | `mocha test/index.js --reporter dot` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1830 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1828 | `mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1823 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1819 | `mocha tests.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 1815 | `mocha ./test/*.spec.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1812 | `mocha --timeout 5000` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1809 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [punkave/apostrophe](https://github.com/punkave/apostrophe) | 1807 | `mocha` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1795 | `mocha --require ./test/common --growl test/expect.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1774 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 1768 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1765 | `mocha --reporter spec --timeout 5000` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1757 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1757 | `mocha test && npm run lint` | 
| [Qix-/color](https://github.com/Qix-/color) | 1755 | `mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1747 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1744 | `cross-env NODE_ENV=test mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1737 | `mocha test/**/*_test.js --bail` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1730 | `mocha test` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1714 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1699 | `mocha test.js` | 
| [then/promise](https://github.com/then/promise) | 1697 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1696 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1696 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1694 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1693 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1686 | `mocha test/runner.js --reporter spec` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1678 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1673 | `xo && mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1663 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1654 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1652 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1647 | `mocha` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1646 | `mocha test` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1646 | `mocha --compilers js:babel-register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1645 | `mocha --compilers js:babel-core/register __tests__` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1640 | `mocha -R landing test/index` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1640 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1637 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1637 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1635 | `./node_modules/.bin/mocha` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1635 | `npm run lint && npm run compile && mocha --reporter spec test/*.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1632 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [Hardmath123/nearley](https://github.com/Hardmath123/nearley) | 1631 | `mocha test/*.test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1604 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1604 | `mocha tests/test.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1603 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1600 | `mocha -R spec spec spec/reporters` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1600 | `mocha --reporter spec && npm run test-typescript` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1595 | `npm run lint && npm run mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1595 | `lint && mocha --recursive` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1593 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [KunalKapadia/express-mongoose-es6-rest-api](https://github.com/KunalKapadia/express-mongoose-es6-rest-api) | 1592 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1591 | `mocha --expose-gc --slow 300` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1585 | `mocha && eslint *.js` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1574 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1572 | `mocha` | 
| [verdaccio/verdaccio](https://github.com/verdaccio/verdaccio) | 1569 | `mocha ./test/functional ./test/unit --reporter=spec --full-trace` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1569 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1568 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1563 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1561 | `./node_modules/mocha/bin/mocha -R spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1545 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1536 | `./node_modules/.bin/mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1532 | `mocha test/*.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1509 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1503 | `npm run lint && mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1502 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1495 | `mocha && npm run lint` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1487 | `mocha --reporter spec --grep .` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1485 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1483 | `npm run mocha && npm run karma` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1482 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1469 | `npm run mocha && npm run lint` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1460 | `mocha -R spec` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1457 | `mocha` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1453 | `mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1448 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1447 | `mocha tests --compilers js:babel-core/register` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1446 | `mocha spec/` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1446 | `nyc npm run _mocha` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1445 | `mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1444 | `mocha -u tdd` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1444 | `./node_modules/mocha/bin/mocha -R spec` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1438 | `mocha ./test/basic.js -t 5000` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1436 | `mocha test/` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1436 | `mocha test/* --reporter spec` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1433 | `mocha test -u bdd -R spec` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1433 | `node_modules/.bin/mocha --recursive` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1432 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1430 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1426 | `mocha test/tests.js --timeout=10000` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1419 | `npm run lint && mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1414 | `npm run test:lint && npm run test:mocha && npm run site` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1400 | `mocha test.js` | 
| [pahen/madge](https://github.com/pahen/madge) | 1395 | `npm run lint && npm run mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1386 | `mocha --reporter spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1386 | `mocha test/**/*.spec.js` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1384 | `mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1368 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1351 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1343 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1342 | `nyc mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1339 | `./node_modules/mocha/bin/mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1329 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1318 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1312 | `mocha --check-leaks -R dot` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1310 | `cross-env NODE_ENV=test nyc mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1308 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1305 | `standard "./src/*.js" && mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 1304 | `./node_modules/.bin/mocha && npm run jshint` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1300 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1298 | `eslint --rulesdir=dev-tools/eslint --cache . && tsc && mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1296 | `mocha --reporter spec test/*.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1281 | `istanbul cover _mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1279 | `mocha --recursive` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1267 | `mocha --compilers js:babel-register` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1261 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1258 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1253 | `mocha test.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1241 | `npm run build && mocha -r should` | 
| [trufflesuite/ganache-cli](https://github.com/trufflesuite/ganache-cli) | 1240 | `mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1228 | `mocha` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1218 | `standard "src/*.js" && npm run build && mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1216 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1216 | `./node_modules/.bin/mocha test` | 
| [sandeepmistry/bleno](https://github.com/sandeepmistry/bleno) | 1216 | `mocha -R spec test/*.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1213 | `mocha-phantomjs tests/index.html` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1209 | `mocha --timeout 10000 ./tests/lib.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1205 | `mocha spec/exec.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1202 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1195 | `mocha tests` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1192 | `mocha --check-leaks --reporter spec --bail` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1192 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1190 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [zeit/ms](https://github.com/zeit/ms) | 1189 | `mocha tests.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1189 | `mocha test/test.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1184 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1179 | `mocha test/setup.js test/spec/*.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1177 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [reddit/reddit-mobile](https://github.com/reddit/reddit-mobile) | 1175 | `mocha test/index.js` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1173 | `mocha test/**/*Spec.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1171 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1171 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1171 | `mocha test/*.js` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1167 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1167 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1161 | `mocha test` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1161 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1154 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1154 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1147 | `mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1146 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1144 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1143 | `istanbul cover _mocha test -- --timeout 20000` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1141 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1138 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1137 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1135 | `node ./node_modules/mocha/bin/mocha tests` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1134 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1131 | `mocha --full-trace --check-leaks` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1131 | `mocha --full-trace --check-leaks` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1130 | `./node_modules/.bin/mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1130 | `mocha --recursive` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1127 | `eslint lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1127 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1125 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1112 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1107 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1105 | `mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1102 | `mocha --opts test/opts/mocha.opts` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1095 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1094 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1094 | `mocha compiled_tests/` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1091 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1088 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1087 | `node_modules/.bin/mocha && npm run lint` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1076 | `npm run lint && npm run mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1071 | `mocha --reporter spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1068 | `mocha` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1063 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [variety/variety](https://github.com/variety/variety) | 1063 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1062 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1058 | `mocha --check-leaks --require @babel/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1053 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1052 | `mocha --check-leaks -t 20000` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1052 | `mocha --reporter spec --timeout 3000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1051 | `mocha --compilers js:babel-register` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1047 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1045 | `mocha test/*` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1041 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1034 | `node_modules/.bin/mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1031 | `mocha $(find test -name '*.test.js')` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1027 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1025 | `mocha src/test.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1025 | `mocha` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1024 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [jas/playground](https://github.com/jas/playground) | 1023 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1020 | `istanbul test _mocha` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1020 | `mocha --check-leaks -R dot` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1016 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1014 | `xo && mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1012 | `standard && istanbul cover _mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1000 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1000 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 995 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [sorrycc/roadhog](https://github.com/sorrycc/roadhog) | 993 | `npm run lint && npm run build && cross-env NODE_ENV=test nyc mocha --no-timeouts test/**/*-test.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 990 | `mocha --reporter dot` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 985 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 984 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 983 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 982 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 979 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 978 | `mocha --colors ./test/*.spec.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 977 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 977 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 976 | `mocha test/tests.js` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 972 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 970 | `eslint src && mocha && karma start --single-run` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 967 | `mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 967 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 961 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 960 | `mocha test/unit` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 960 | `mocha --timeout 5000` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 958 | `mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 957 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 953 | `istanbul cover _mocha test/*.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 953 | `npm run lint && mocha -R dot && npm run cover` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 948 | `mocha --check-leaks --reporter spec --bail test/` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 943 | `npm run rollup-cjs && mocha test/test.js` | 
| [googlevr/webvr-polyfill](https://github.com/googlevr/webvr-polyfill) | 942 | `mocha` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 942 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 940 | `mocha --recursive --bail --reporter spec test` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 940 | `mocha -R list` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 934 | `mocha --recursive test/unit/` | 
| [motdotla/node-lambda](https://github.com/motdotla/node-lambda) | 933 | `standard && standard bin/node-lambda && mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 930 | `mocha test/.setup.js 'test/**/*.spec.js'` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 930 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 926 | `mocha test --timeout 600000` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 924 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 924 | `mocha $(find test -name '*.test.js')` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 921 | `standard && mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 918 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 915 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 915 | `mocha --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 912 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [watson-developer-cloud/node-sdk](https://github.com/watson-developer-cloud/node-sdk) | 911 | `npm run lint && mocha test/unit test/integration` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 909 | `mocha --async-only` | 
| [tomas/needle](https://github.com/tomas/needle) | 908 | `mocha test` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 904 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 902 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 901 | `mocha spec/*.spec.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 896 | `NODE_PATH=. mocha **/*.spec.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 894 | `eslint . && mocha -t 5000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 894 | `./node_modules/.bin/mocha --globals angular,require` | 
| [router5/router5](https://github.com/router5/router5) | 893 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 891 | `mocha tests/test-*` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 890 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [dabeng/OrgChart](https://github.com/dabeng/OrgChart) | 888 | `mocha ./test/**/*-tests.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 880 | ` NODE_ENV=test mocha --compilers js:babel-register` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 879 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 876 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 876 | `standard && mocha -b` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 875 | `mocha` | 
| [alizain/ulid](https://github.com/alizain/ulid) | 875 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha -- -R spec` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 874 | `mocha -t 120000 test/*.test.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 872 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 871 | `mocha test/test.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 868 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 864 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 864 | `mocha --reporter list` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 863 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 859 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 859 | `mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 857 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 855 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 853 | `mocha test` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 852 | `webpack && mocha test/unit` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 851 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 850 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 847 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [electron/asar](https://github.com/electron/asar) | 841 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 839 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 839 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 838 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 836 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 835 | `mocha "client.test" --compilers js:babel-register` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 834 | `mocha --reporter spec --bail --check-leaks test/` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 832 | `node_modules/.bin/mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 832 | `eslint test && mocha --compilers js:babel/register` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 831 | `mocha --recursive test` | 
| [teambit/bit](https://github.com/teambit/bit) | 831 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 829 | `mocha --reporter spec --bail --check-leaks test/` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 827 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 825 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 824 | `mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 822 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 818 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 817 | `npm run lint && mocha -R spec` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 814 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 813 | `mocha --compilers js:babel-register test/*.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 810 | `mocha --timeout 200000` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 809 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 808 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 806 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 806 | `mocha && ember test` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 805 | `mocha tests/*.test.js --reporter spec` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 803 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 802 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 802 | `mocha --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 799 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 796 | `node_modules/.bin/mocha test/spec` | 
| [electron/spectron](https://github.com/electron/spectron) | 796 | `mocha && standard` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 794 | `mocha --reporter spec --bail --check-leaks test/` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 792 | `mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 790 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 790 | `mocha tests` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 789 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 788 | `mocha -R spec tests/` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 786 | `mocha --check-leaks -t 20000` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 785 | `mocha -u tdd` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 782 | `mocha --require babel-register` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 779 | `npm run convertto:es5 && npm run mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 777 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 773 | `cake build && mocha ./test/mocha/*.coffee` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 772 | `nyc mocha --timeout=20000 test.js` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 769 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 769 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 768 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 767 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 766 | `mocha --reporter spec --bail --check-leaks test/` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 766 | `istanbul cover _mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 765 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 764 | `nyc mocha --require babel-register` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 759 | `mocha` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 758 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [edsu/anon](https://github.com/edsu/anon) | 758 | `mocha --colors --reporter spec test.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 757 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 756 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 755 | `mocha -t 5000` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 754 | `mocha ./test -R spec` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 752 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 750 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 746 | `npm run lint && mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 746 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 745 | `mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 742 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 741 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 740 | `mocha test --compilers js:babel-register` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 739 | `mocha` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 738 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 735 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 735 | `istanbul cover -- _mocha --reporter spec` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 732 | `xo && mocha -R spec` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 731 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 727 | `mocha -R spec src/**/*_test.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 725 | `nyc mocha specs` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 725 | `mocha --reporter spec` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 725 | `mocha` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 725 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 724 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 724 | `mocha --async-only` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 723 | `mocha ./test/test*.js --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 720 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 718 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 717 | `mocha --ui tdd --require ./test/__setup` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 716 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [typicode/katon](https://github.com/typicode/katon) | 715 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 714 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 713 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 711 | `mocha -t 600000` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 711 | `mocha -R spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 710 | `mocha --reporter list` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 707 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 705 | `mocha spec/*.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 704 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 704 | `mocha test.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 698 | `./node_modules/.bin/mocha -R spec` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 693 | `npm run bundle && mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 692 | `npm run lint && mocha --compilers js:babel-register` | 
| [contra/gulp-concat](https://github.com/contra/gulp-concat) | 690 | `mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 689 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 680 | `npm run lint && mocha test` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 680 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 678 | `mocha tests/*.mocha.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 675 | `mocha ./test/index.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 673 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 671 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 671 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 670 | `npm run mocha-test test/integration` | 
| [sindresorhus/gulp-changed](https://github.com/sindresorhus/gulp-changed) | 669 | `xo && mocha` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 669 | `mocha -b -R spec test/*` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 667 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 667 | `cross-env NODE_ENV=test nyc mocha` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 665 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 664 | `mocha -R spec --compilers js:babel-core/register ./tests/setup.js ./tests/** --recursive` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 663 | `npm run lint && nyc mocha test/**` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 663 | `mocha` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 662 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 662 | `mocha --reporter spec` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 661 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 661 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 661 | `mocha test` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 661 | `mocha --reporter spec` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 660 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 657 | `mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 657 | `npm run build && istanbul test _mocha test/test.js` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 656 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 655 | `mocha tests/*.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 654 | `mocha test` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 653 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 652 | `./node_modules/.bin/mocha test/integration` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 651 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 648 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 647 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 644 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 641 | `npm run lint && mocha ./test/test.js --timeout 1000000` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 641 | `mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 640 | `eslint src test && mocha --compilers babel-register` | 