# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:53 02/01/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39660 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 38980 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 36642 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [expressjs/express](https://github.com/expressjs/express) | 36407 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28645 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23268 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 21959 | `BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 20489 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 18365 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 17490 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17401 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15470 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14691 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13731 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12908 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12551 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 11983 | `mocha 'test/**/*.spec.js'` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11976 | `mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11915 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11646 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11571 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 11054 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10813 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10501 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 10280 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9890 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9513 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9363 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 9257 | `mocha --harmony` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9159 | `mocha test/index.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9156 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9032 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 8924 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8837 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8496 | `grunt mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7439 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7421 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7314 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7300 | `npm run eslint && npm run mocha` | 
| [amark/gun](https://github.com/amark/gun) | 7253 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7147 | `mocha tests/*.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7123 | `npm run build && istanbul cover _mocha` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6771 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6712 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6531 | `mocha $HARMONY_OPTS` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6506 | `BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 6399 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6294 | `mocha --opts mocha.opts` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6279 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [almende/vis](https://github.com/almende/vis) | 6192 | `mocha --compilers js:babel-core/register` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6190 | `nyc mocha test/**/* -r ./test/before` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7123 | `npm run build && istanbul cover _mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7067 | `./node_modules/.bin/mocha test` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6771 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6712 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6531 | `mocha $HARMONY_OPTS` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6506 | `BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6448 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6399 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6294 | `mocha --opts mocha.opts` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6279 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [almende/vis](https://github.com/almende/vis) | 6192 | `mocha --compilers js:babel-core/register` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6190 | `nyc mocha test/**/* -r ./test/before` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6172 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6098 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 5991 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5922 | `mocha` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5890 | `npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5791 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5746 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5639 | `npm run jshint && mocha test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5612 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5465 | `mocha tests/node.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5393 | `mocha test --recursive` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5385 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5332 | `mocha && eslint lib/**` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5324 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5284 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5252 | `mocha test/test.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5163 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5135 | `mocha src/**/*Tests.js --harmony` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5092 | `mocha --timeout 10000 && npm run lint` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 4991 | `mocha --compilers js:babel-core/register` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4936 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4931 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4760 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4719 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4662 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4615 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4599 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4594 | `mocha --reporter spec -t 8000` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4582 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4527 | `mocha ./test/runner.js` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4502 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4410 | `gulp build; mocha;` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4384 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4360 | `standard && mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4352 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4340 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4318 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4306 | `./node_modules/.bin/mocha` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 4296 | `npm run build-cli && mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4242 | `mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4221 | `mocha -R spec ./test --recursive` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4211 | `mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4177 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4167 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4115 | `mocha test` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 4044 | `mocha && ./bin/shipit staging test` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4032 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3977 | `nyc mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3886 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3844 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3818 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3814 | `mocha --recursive && make test` | 
| [muicss/mui](https://github.com/muicss/mui) | 3800 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3779 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 3761 | `mocha --require should --reporter spec` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3756 | `NODE_ENV=test mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 3716 | `mocha; jshint *.js lib` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3699 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3682 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3639 | `npm run jshint && npm run mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3600 | `nyc mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3590 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3557 | `npm run lint ; mocha && mocha test/individual` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3550 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3544 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3530 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3445 | `mocha --reporter spec --timeout 3000` | 
| [primus/primus](https://github.com/primus/primus) | 3439 | `npm run build && mocha test/*.test.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3426 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3419 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3389 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3388 | `mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3379 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3333 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3280 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3271 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3238 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3226 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3169 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3164 | `mocha --check-leaks --reporter spec --bail` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3108 | `npm run lint && npm run mocha` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3100 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3095 | `mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3073 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3068 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3054 | `./node_modules/.bin/mocha test/test.*.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3043 | `yarn run build:cjs && mocha --require babel-core/register ./test/index.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3036 | `mocha ./test/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3029 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 3014 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3010 | `node_modules/.bin/mocha test/tests.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2962 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2933 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2918 | `mocha` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2914 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2902 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2849 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2812 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2802 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2784 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2761 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2757 | `mocha --require should --reporter spec` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 2738 | `NODE_ENV=test mocha test/**/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2736 | `mocha -R spec --recursive src/test` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2722 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2706 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2706 | `istanbul cover _mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2696 | `mocha test/index.js && npm run demo` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2691 | `nyc mocha && tsc` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2667 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [tj/should.js](https://github.com/tj/should.js) | 2661 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2654 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [github-tools/github](https://github.com/github-tools/github) | 2652 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2637 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2628 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2616 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2607 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2602 | `xo && mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2601 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2598 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2593 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2590 | `mocha --timeout 100000` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2581 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2574 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2573 | `mocha-phantomjs ./test/index.html` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2568 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2563 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2562 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2558 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2555 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2539 | `npm run compile && mocha --require babel-core/register` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2537 | `mocha --opts mocha.opts` | 
| [css/csso](https://github.com/css/csso) | 2530 | `mocha --reporter dot` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2526 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2524 | `npm run mocha && npm run lint` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2503 | `mocha --recursive --watch` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2496 | `mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2488 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2474 | `mocha --compilers js:babel-register --recursive spec` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2441 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2420 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2415 | `mocha --reporter=spec test/*-test.js` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2412 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2408 | `mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2393 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2366 | `node node_modules/mocha/bin/_mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2355 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2346 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2333 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2331 | `mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2322 | `grunt jshint && mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2321 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2311 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2297 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2292 | `NODE_ENV=test mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2279 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2278 | `mocha test` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2270 | `node_modules/.bin/mocha --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2269 | `nyc mocha 'test/**/*-test.js'` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2262 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [mozilla/send](https://github.com/mozilla/send) | 2258 | `mocha test/unit` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2257 | `npm run build && cd test && mocha . --reporter dot` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2190 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2186 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2163 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2161 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2151 | `npm run lint && npm run build && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2142 | `mocha -R spec` | 
| [gajus/swing](https://github.com/gajus/swing) | 2123 | `mocha --compilers js:babel-register` | 
| [mde/ejs](https://github.com/mde/ejs) | 2122 | `mocha --require should --reporter spec` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2105 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2104 | `mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2081 | `mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2081 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2041 | `cross-env BABEL_ENV=test mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2035 | `nyc --reporter=html --reporter=text mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2035 | `mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2020 | `BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2003 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 1973 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1967 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1948 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1944 | `mocha && eslint .` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1924 | `mocha --require=test/test_helper.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1915 | `mocha test.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1898 | `mocha --bail --reporter spec --check-leaks test/` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1894 | `mocha -R landing test/index` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1886 | `mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1885 | `mocha test && npm run lint` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1879 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1877 | `mocha test/index.js --reporter dot` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1873 | `mocha -c test/index.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1863 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1853 | `mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 1847 | `mocha` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1831 | `mocha --require ./test/common --growl test/expect.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1831 | `mocha tests.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1825 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1819 | `mocha --reporter spec --timeout 5000` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1805 | `mocha --timeout 5000` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1803 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1795 | `mocha --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1787 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1778 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1776 | `cross-env NODE_ENV=test mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1769 | `mocha test/runner.js --reporter spec` | 
| [then/promise](https://github.com/then/promise) | 1762 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1752 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1747 | `mocha test` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1747 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1742 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1734 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1733 | `mocha --compilers js:babel-core/register __tests__` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1733 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1729 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1728 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1718 | `mocha test/*.test.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1701 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1700 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1697 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1695 | `mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1693 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1687 | `mocha test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1686 | `npm run lint && mocha --reporter spec test/*.js` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1686 | `mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1674 | `mocha && eslint *.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1671 | `./node_modules/.bin/mocha && npm run jshint` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1662 | `mocha` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1662 | `npm run lint && mocha -R dot && npm run cover` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1659 | `./node_modules/.bin/mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1652 | `npm run lint && mocha --recursive --exit` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1647 | `./node_modules/mocha/bin/mocha -R spec` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1644 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1642 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1641 | `mocha --reporter spec && npm run test-typescript` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1638 | `mocha -R spec spec spec/reporters` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1637 | `npm run lint && npm run mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1632 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1630 | `npm run mocha && npm run karma` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1613 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1610 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1608 | `mocha tests/test.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1602 | `mocha --expose-gc --slow 300` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1600 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1592 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1580 | `nyc npm run _mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1576 | `mocha && npm run lint` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1570 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1567 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1551 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1548 | `npm run lint && mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1546 | `./node_modules/.bin/mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1545 | `mocha --reporter spec --grep .` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1542 | `mocha` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1541 | `npm run mocha && npm run lint` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1539 | `mocha tests --compilers js:babel-core/register` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1532 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1521 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1517 | `mocha test/` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1517 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1515 | `mocha test -u bdd -R spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1514 | `mocha spec/` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1512 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1507 | `mocha ./test/basic.js -t 5000` | 
| [pahen/madge](https://github.com/pahen/madge) | 1506 | `npm run lint && npm run mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1503 | `mocha test/* --reporter spec` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1497 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1496 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1480 | `mocha --reporter spec test/*.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1478 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1470 | `./node_modules/mocha/bin/mocha -R spec` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1469 | `npm run test:lint && npm run test:mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1467 | `npm run lint && npm run mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1466 | `mocha -R spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1462 | `mocha -u tdd` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1458 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1447 | `node_modules/.bin/mocha --recursive` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1437 | `mocha --reporter spec` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1434 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1430 | `mocha test/tests.js --timeout=10000` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1417 | `mocha test --timeout 600000` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1414 | `mocha test/**/*.spec.js` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1413 | `standard "src/*.js" && npm run build && mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1406 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1403 | `mocha test.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1391 | `mocha --compilers js:babel-register` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1378 | `nyc mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1374 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1371 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1364 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1364 | `eslint --cache . && tsc && mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1362 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1362 | `mocha --check-leaks -R dot` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1361 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1358 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1349 | `mocha test.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1347 | `standard "./src/*.js" && mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1346 | `./node_modules/mocha/bin/mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1332 | `mocha --recursive` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1327 | `cross-env NODE_ENV=test nyc mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1316 | `mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1315 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1311 | `istanbul cover _mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1298 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1285 | `mocha tests.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1283 | `mocha-phantomjs tests/index.html` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1281 | `mocha --check-leaks --reporter spec --bail` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1270 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1270 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1268 | `mocha --timeout 10000 ./tests/lib.js` | 
| [sandeepmistry/bleno](https://github.com/sandeepmistry/bleno) | 1267 | `mocha -R spec test/*.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1266 | `npm run build && mocha -r should` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1261 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1255 | `mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1245 | `./node_modules/.bin/mocha test` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1238 | `mocha test/setup.js test/spec/*.js` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1237 | `mocha compiled_tests/` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1236 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1235 | `mocha spec/exec.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1233 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [electron/devtron](https://github.com/electron/devtron) | 1224 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1217 | `npm run lint && npm run mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1212 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1209 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1208 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1207 | `mocha tests` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1204 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1203 | `mocha test/*.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1200 | `mocha test/test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1197 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1197 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1193 | `eslint . && mocha -t 5000` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1192 | `istanbul cover _mocha test -- --timeout 20000` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1187 | `mocha test/**/*Spec.js` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1186 | `mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1185 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1183 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1178 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1173 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1170 | `mocha test` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1170 | `mocha --recursive` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1166 | `mocha` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1165 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1158 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1157 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1157 | `mocha --check-leaks --require @babel/register` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1149 | `node ./node_modules/mocha/bin/mocha tests` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1147 | `mocha --opts test/opts/mocha.opts` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1144 | `eslint lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1144 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1138 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1132 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1126 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1111 | `mocha` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1103 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1103 | `mocha --reporter spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1102 | `npm run lint && npm run mocha` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1101 | `mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1098 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1093 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1092 | `mocha src/test.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1092 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1090 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1090 | `mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1088 | `node_modules/.bin/mocha && npm run lint` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1078 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1077 | `standard && istanbul cover _mocha` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1076 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1075 | `mocha --reporter dot` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1075 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1070 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1069 | `mocha test/unit` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1068 | `node_modules/.bin/mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1066 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1066 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1065 | `mocha --compilers js:babel-register` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1061 | `mocha test/*` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1060 | `eslint src && mocha && karma start --single-run` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1050 | `mocha $(find test -name '*.test.js')` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1050 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1048 | `mocha --reporter spec --timeout 3000` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1045 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1040 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1038 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1038 | `xo && mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1028 | `istanbul test _mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1023 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1023 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1022 | `mocha --check-leaks --reporter spec --bail test/` | 
| [jas/playground](https://github.com/jas/playground) | 1020 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1023 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1023 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1022 | `mocha --check-leaks --reporter spec --bail test/` | 
| [jas/playground](https://github.com/jas/playground) | 1020 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1018 | `mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1014 | `NODE_PATH=. mocha **/*.spec.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1014 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1008 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1005 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1001 | `mocha test` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 995 | `istanbul cover _mocha test/*.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 992 | `mocha test/tests.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 991 | `mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 989 | `mocha tests/test-*` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 987 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 985 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 983 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 982 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 981 | `mocha --colors ./test/*.spec.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 976 | `mocha` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 967 | `mocha --recursive --bail --reporter spec test` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 967 | `mocha` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 961 | ` NODE_ENV=test mocha --compilers js:babel-register` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 959 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 958 | `npm run rollup-cjs && mocha test/test.js` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 957 | `standard && mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 957 | `mocha --timeout 5000` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 954 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 952 | `mocha -R list` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 951 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 949 | `npm run prepublish && mocha test/test.js` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 948 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 948 | `mocha $(find test -name '*.test.js')` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 942 | `mocha --recursive test/unit/` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 939 | `mocha --async-only` | 
| [router5/router5](https://github.com/router5/router5) | 939 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [tomas/needle](https://github.com/tomas/needle) | 932 | `mocha test` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 932 | `mocha --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 932 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 931 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 931 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 928 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 928 | `mocha -t 120000 test/*.test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 927 | `mocha` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 920 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 914 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 913 | `standard && mocha -b` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 909 | `mocha --recursive test` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 906 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 904 | `mocha spec/*.spec.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 903 | `webpack && mocha test/unit` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 901 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 900 | `nyc mocha --timeout=20000 test.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 899 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 894 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 893 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 893 | `mocha --reporter spec --bail --check-leaks test/` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 891 | `./node_modules/.bin/mocha --globals angular,require` | 
| [electron/asar](https://github.com/electron/asar) | 882 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 881 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 881 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 881 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 879 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 877 | `mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 877 | `mocha --reporter spec --bail --check-leaks test/` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 876 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 874 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 874 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 873 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 867 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 867 | `mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 864 | `mocha --reporter list` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 863 | `mocha "client.test" --compilers js:babel-register` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 862 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 858 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 857 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 853 | `mocha --compilers js:babel-register test/*.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 852 | `mocha && standard` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 852 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 846 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 845 | `nyc mocha --require @babel/register` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 843 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 842 | `node_modules/.bin/mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 836 | `eslint test && mocha --compilers js:babel/register` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 835 | `npm run lint && mocha -R spec` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 834 | `mocha --reporter spec --bail --check-leaks test/` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 833 | `mocha ./test/test*.js --reporter spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 833 | `mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 833 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 832 | `npm run convertto:es5 && npm run mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 832 | `npm run lint && npm run mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 828 | `mocha` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 827 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 820 | `mocha -R spec ./test/unit/**` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 820 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 817 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 817 | `mocha ./test -R spec` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 816 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 814 | `mocha --reporter spec` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 812 | `mocha && ember test` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 810 | `npm run lint && mocha --compilers js:babel-register` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 800 | `mocha --check-leaks -t 20000` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 796 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 800 | `mocha --check-leaks -t 20000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 798 | `mocha` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 796 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 793 | `istanbul cover _mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 790 | `mocha -R spec tests/` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 790 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 790 | `mocha --require babel-register` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 789 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 788 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 785 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 783 | `mocha --reporter spec --bail --check-leaks test/` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 783 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 783 | `mocha -t 5000` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 783 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 782 | `standard && standard ./bin/* && mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 780 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 778 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 776 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 775 | `mocha` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 774 | `mocha -R spec` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 773 | `mocha` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 771 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 769 | `mocha -t 600000` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 768 | `mocha test --compilers js:babel-register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 767 | `NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 767 | `istanbul cover -- _mocha --reporter spec` | 
| [edsu/anon](https://github.com/edsu/anon) | 766 | `mocha --colors --reporter spec test.js` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 761 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 760 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 759 | `nyc mocha specs` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 759 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 758 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 757 | `mocha --async-only` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 756 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 752 | `xo && mocha -R spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 752 | `mocha` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 747 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require babel-register --no-timeouts` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 747 | `mocha spec/*.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 743 | `mocha --ui tdd --require ./test/__setup` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 743 | `mocha --reporter list` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 747 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require babel-register --no-timeouts` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 747 | `mocha spec/*.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 743 | `mocha --ui tdd --require ./test/__setup` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 743 | `mocha --reporter list` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 742 | `./node_modules/.bin/mocha -R spec` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 736 | `mocha -R spec src/**/*_test.js` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 722 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 720 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 716 | `mocha test.js` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 714 | `mocha --recursive -s 15 test/` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 713 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 711 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 711 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 708 | `cross-env NODE_ENV=test nyc mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 713 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 711 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 711 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 709 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 708 | `cross-env NODE_ENV=test nyc mocha` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 707 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 706 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 703 | `mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 702 | `eslint src test && mocha --compilers babel-register` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 703 | `mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 702 | `eslint src test && mocha --compilers babel-register` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 699 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [bitpay/insight](https://github.com/bitpay/insight) | 699 | `mocha test` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 697 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 697 | `npm run bundle && mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 696 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 693 | `npm run mocha-test test/integration` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 691 | `mocha tests/*.mocha.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 690 | `mocha test` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 685 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 685 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 685 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 683 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 682 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 682 | `npm run build && istanbul test _mocha test/test.js` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 680 | `npm run lint && mocha test` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 680 | `mocha test` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 679 | `mocha ./test/index.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 678 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 677 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 677 | `mocha` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 674 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 673 | `mocha --reporter spec` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 672 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [developit/decko](https://github.com/developit/decko) | 671 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 670 | `mocha -b -R spec test/*` | 