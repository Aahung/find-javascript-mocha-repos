# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:07 03/08/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39941 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 39729 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 37033 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28913 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23490 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 22369 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 20983 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 20133 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 17950 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17664 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15672 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15042 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13871 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 13308 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12780 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12197 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12140 | `mocha 'test/**/*.spec.js'` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12032 | `mocha` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11792 | `./node_modules/.bin/mocha test/` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11741 | `mocha --reporter spec test/*-test.js` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 11522 | `cross-env BABEL_ENV=test NODE_ENV=test mocha --recursive --require babel-register --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11220 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 10700 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10683 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10162 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9786 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9669 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 9383 | `mocha --harmony` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9383 | `mocha test/index.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9342 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9205 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9145 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8927 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8602 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8449 | `mocha test/*-test.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8432 | `mocha` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8174 | `mocha --check-leaks -R dot` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8162 | `mocha test/test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 8109 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8100 | `grunt clean:test && mocha --exit` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7911 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7873 | `./node_modules/.bin/mocha test/src` | 
| [websockets/ws](https://github.com/websockets/ws) | 7862 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7787 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7757 | `mocha --compilers js:babel-register test/test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7602 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [amark/gun](https://github.com/amark/gun) | 7594 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7455 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7437 | `mocha` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7385 | `npm run eslint && npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7355 | `mocha tests/*.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7194 | `npm run build && istanbul cover _mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7182 | `./node_modules/.bin/mocha test` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7011 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6980 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6778 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6579 | `mocha $HARMONY_OPTS` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6546 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6499 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6464 | `mocha --opts mocha.opts` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6460 | `nyc mocha test/**/* -r ./test/before` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6449 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6372 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6360 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [almende/vis](https://github.com/almende/vis) | 6341 | `mocha --compilers js:babel-core/register` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5985 | `npm run jshint -s && npm run mocha -s` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5925 | `mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5876 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5860 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5845 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5754 | `npm run jshint && mocha test/` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5599 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5517 | `mocha tests/node.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5508 | `mocha test --recursive` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5422 | `mocha && eslint lib/**` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5395 | `mocha test/test.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5390 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5384 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5231 | `mocha --exit --require babel-core/register` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5164 | `mocha --color` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5152 | `mocha --timeout 10000 && npm run lint` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5138 | `mocha src/**/*Tests.js --harmony` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5038 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5026 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 4934 | `npm run build-cli && mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4785 | `gulp lint && mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4784 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4752 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4740 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [redux-utilities/redux-actions](https://github.com/redux-utilities/redux-actions) | 4649 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4639 | `mocha test` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4620 | `mocha --reporter spec -t 8000` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4618 | `mocha -R spec 'tests/app'` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4540 | `standard && mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4532 | `mocha ./test/runner.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4514 | `gulp build; mocha;` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4460 | `mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4438 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4414 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4395 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 4371 | `mocha; jshint *.js lib` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4360 | `./node_modules/.bin/mocha` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4347 | `mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4312 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4223 | `mocha -R spec ./test --recursive` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4221 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4217 | `mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4213 | `mocha test` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4202 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 4094 | `mocha && ./bin/shipit staging test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4013 | `nyc mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3931 | `mocha --recursive && make test` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3907 | `mocha --require test/babel-hook test/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3896 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [muicss/mui](https://github.com/muicss/mui) | 3867 | `mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3864 | `NODE_ENV=test mocha` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3852 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3808 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [tj/ejs](https://github.com/tj/ejs) | 3804 | `mocha --require should --reporter spec` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3799 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3783 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3674 | `nyc mocha` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3638 | `npm run lint ; mocha && mocha test/individual` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3638 | `npm run jshint && npm run mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3619 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3590 | `mocha ./test/*.spec.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3558 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3549 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3545 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3541 | `mocha tests/javascript` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3517 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3508 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [primus/primus](https://github.com/primus/primus) | 3486 | `npm run build && mocha test/*.test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3458 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3438 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3403 | `node_modules/.bin/mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3402 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3399 | `mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3378 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3361 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3347 | `npm run lint && npm run mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3331 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3288 | `mocha --check-leaks --reporter spec --bail` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3222 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3180 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3175 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3154 | `nyc mocha "test/**/*.test.js"` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3118 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 3114 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3100 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3073 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3066 | `./node_modules/.bin/mocha test/test.*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3054 | `node_modules/.bin/mocha test/tests.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3011 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2978 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2975 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2974 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2972 | `mocha` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2933 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2925 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2893 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2853 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 2850 | `NODE_ENV=test mocha test/**/*.js` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2800 | `nyc mocha && tsc` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2794 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2786 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2777 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2775 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2768 | `mocha -R spec --recursive src/test` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2762 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2758 | `mocha --require should --reporter spec` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2754 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2751 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2746 | `mocha test/index.js && npm run demo` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2737 | `istanbul cover _mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2735 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2733 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2725 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2693 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2683 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2679 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2672 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2672 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2654 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2640 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2638 | `mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2635 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2631 | `xo && mocha` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2612 | `mocha --opts mocha.opts` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2609 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2609 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2597 | `mocha --timeout 100000` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2594 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [css/csso](https://github.com/css/csso) | 2584 | `mocha --reporter dot` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2583 | `mocha-phantomjs ./test/index.html` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2570 | `npm run mocha && npm run lint` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2541 | `mocha` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2538 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2524 | `mocha --recursive --watch` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2519 | `mocha --compilers js:babel-register --recursive spec` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2507 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2502 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2497 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2481 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2458 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2452 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2432 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2430 | `mocha --reporter=spec test/*-test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2403 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2397 | `NODE_ENV=test mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2385 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2368 | `node_modules/.bin/mocha --reporter spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2367 | `node node_modules/mocha/bin/_mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2353 | `nyc mocha test/mocha-node-setup.js 'test/**/*-test.js'` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2353 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2344 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2331 | `mocha --no-colors --reporter spec` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2330 | `nyc mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2329 | `grunt jshint && mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2329 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2324 | `npm run build && cd test && mocha . --reporter dot` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2322 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2311 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2304 | `mocha test` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2261 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [json5/json5](https://github.com/json5/json5) | 2260 | `mocha --ui exports --reporter spec` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2223 | `mocha test test/unit/**/*_test.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2221 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2217 | `mocha "test/**/*-test.js"` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2216 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2215 | `mocha test/unit --require mochahook` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 2215 | `npm run lint && mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2215 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mde/ejs](https://github.com/mde/ejs) | 2214 | `mocha --require should --reporter spec` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2203 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2201 | `npm run lint && npm run build && npm run mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2197 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2193 | `mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2172 | `mocha -R spec` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2161 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [gajus/swing](https://github.com/gajus/swing) | 2139 | `mocha --compilers js:babel-register` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2084 | `nyc --reporter=html --reporter=text mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2082 | `mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2080 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2065 | `cross-env BABEL_ENV=test mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2056 | `mocha test.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2043 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2043 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [slate/slate](https://github.com/slate/slate) | 2014 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2013 | `mocha -R landing test/index` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2012 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2011 | `mocha -R spec test/*.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2006 | `mocha && eslint .` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1958 | `mocha test && npm run lint` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1932 | `mocha --require=test/test_helper.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1927 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1924 | `standard && mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1907 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1901 | `mocha --bail --reporter spec --check-leaks test/` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1897 | `mocha test/index.js --reporter dot` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1892 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [Qix-/color](https://github.com/Qix-/color) | 1887 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1886 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1882 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1868 | `mocha --compilers js:babel-register` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1855 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1854 | `mocha --require ./test/common --growl test/expect.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1849 | `mocha tests.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1842 | `mocha --reporter spec --timeout 5000` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1822 | `mocha test/runner.js --reporter spec` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1819 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1814 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1807 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1794 | `cross-env NODE_ENV=test mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1790 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [then/promise](https://github.com/then/promise) | 1784 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1782 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1777 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1771 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1771 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1770 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1767 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1752 | `mocha test` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1748 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [kach/nearley](https://github.com/kach/nearley) | 1747 | `mocha test/*.test.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1742 | `mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1739 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1735 | `mocha test/**/*_test.js --bail` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1729 | `npm run lint && mocha -R dot && npm run cover` | 
| [share/sharedb](https://github.com/share/sharedb) | 1726 | `./node_modules/.bin/mocha && npm run jshint` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1721 | `npm run lint && mocha --reporter spec test/*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1720 | `mocha && eslint *.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1714 | `mocha test` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1714 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1706 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1706 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1698 | `mocha -R spec spec spec/reporters` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1696 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1690 | `mocha` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1687 | `npm run mocha && npm run karma` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1687 | `npm run jshint && mocha --recursive` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1687 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1686 | `mocha --reporter spec && npm run test-typescript` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1685 | `npm run lint && mocha server/test --recursive --exit` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1678 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1674 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1668 | `./node_modules/.bin/mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1667 | `nyc npm run _mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1666 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1656 | `npm run lint && npm run mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1642 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1620 | `mocha && npm run lint` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1613 | `mocha tests/test.js` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1612 | `mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1605 | `mocha --expose-gc --slow 300` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1603 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1603 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1597 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1592 | `mocha --reporter spec --grep .` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1589 | `npm run mocha && npm run lint` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1583 | `mocha test/*.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1578 | `npm run lint && mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 1575 | `npm run lint && npm run mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1574 | `mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1573 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1571 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1570 | `mocha tests --compilers js:babel-core/register` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1562 | `mocha test -u bdd -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1561 | `mocha test/**/*.js` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1548 | `mocha ./test/basic.js -t 5000` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1537 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1535 | `mocha spec` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1535 | `mocha --reporter spec test/*.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1535 | `mocha test/* --reporter spec` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1524 | `mocha test --timeout 600000` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1516 | `standard "src/*.js" && npm run build && mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1503 | `mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1501 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1501 | `npm run lint && npm run mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1496 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1489 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1481 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1479 | `npm run test:lint && npm run test:mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1471 | `mocha -R spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1471 | `mocha -u tdd` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1457 | `node_modules/.bin/mocha --recursive` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1453 | `mocha --reporter spec` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1446 | `mocha --compilers js:babel-register` | 
| [samccone/drool](https://github.com/samccone/drool) | 1438 | `mocha test/tests.js --timeout=10000` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1430 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1421 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1412 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1408 | `mocha test.js` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1401 | `nyc mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1400 | `eslint --cache . && tsc && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1399 | `mocha --check-leaks -R dot` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1397 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1396 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1394 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1391 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1384 | `mocha test.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1380 | `standard "./src/*.js" && mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1367 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1366 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1353 | `mocha --recursive` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1351 | `./node_modules/mocha/bin/mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1350 | `mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1347 | `eslint . && mocha -t 5000` | 
| [zeit/ms](https://github.com/zeit/ms) | 1345 | `mocha tests.js` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1337 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1331 | `mocha --check-leaks --reporter spec --bail` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1328 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1327 | `cross-env NODE_ENV=test nyc mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1326 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1322 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1311 | `mocha compiled_tests/` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1310 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1300 | `mocha test/setup.js test/spec/*.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1295 | `mocha-phantomjs tests/index.html` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1293 | `nyc npm run mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1290 | `mocha --timeout 10000 ./tests/lib.js` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1290 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1284 | `npm run build && mocha -r should` | 
| [noble/bleno](https://github.com/noble/bleno) | 1284 | `mocha -R spec test/*.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1261 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1258 | `./node_modules/.bin/mocha test` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1248 | `mocha spec/exec.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1247 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1247 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1243 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1241 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1239 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1233 | `istanbul cover _mocha test -- --timeout 20000` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1220 | `mocha test/*.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1216 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1213 | `mocha tests` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1209 | `mocha --check-leaks --require @babel/register` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1208 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1207 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1206 | `mocha test/test.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1205 | `mocha --recursive` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1199 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1195 | `mocha` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1194 | `mocha test/**/*Spec.js` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1189 | `mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1187 | `mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1187 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1185 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1185 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1184 | `mocha --opts test/opts/mocha.opts` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1184 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1172 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1171 | `mocha test` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1170 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1165 | `node ./node_modules/mocha/bin/mocha tests` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1159 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1149 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1146 | `mocha` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1145 | `mocha` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1142 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1129 | `mocha test/unit` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1126 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1125 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1124 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1124 | `standard && istanbul cover _mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1122 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1116 | `mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1115 | `mocha --reporter dot` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1115 | `npm run lint && npm run mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1114 | `mocha --reporter spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1112 | `mocha src/test.js` | 
| [variety/variety](https://github.com/variety/variety) | 1111 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1110 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1109 | `node_modules/.bin/mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 1109 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1107 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1105 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1102 | `mocha test` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1100 | `eslint src && mocha && karma start --single-run` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1099 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1098 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1096 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1089 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1089 | `node_modules/.bin/mocha && npm run lint` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1087 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1083 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1080 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1080 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1078 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1070 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1070 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1068 | `mocha --compilers js:babel-register` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1066 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1066 | `mocha test/*` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1063 | `mocha $(find test -name '*.test.js')` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1059 | `xo && mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1058 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1055 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1047 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1047 | `mocha --check-leaks --reporter spec --bail test/` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1044 | `mocha --reporter spec --timeout 3000` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1043 | `nyc mocha --timeout=20000 test.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1041 | `mocha tests/test-*` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1035 | `istanbul test _mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1026 | `NODE_PATH=. mocha **/*.spec.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1023 | `istanbul cover _mocha test/*.js` | 
| [jas/playground](https://github.com/jas/playground) | 1022 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1021 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1017 | `mocha --check-leaks -R dot` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1016 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1015 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1015 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1014 | `mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1007 | `mocha test/tests.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1002 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 996 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 996 | `mocha --colors ./test/*.spec.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 993 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 989 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 988 | `mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 987 | `npm run prepublishOnly && mocha test/test.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 984 | `mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 982 | `standard && mocha` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 976 | `mocha --recursive --bail --reporter spec test` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 974 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 972 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 968 | `npm run rollup-cjs && mocha test/test.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 967 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 963 | `mocha --recursive test` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 962 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 960 | `mocha` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 957 | `mocha --recursive test/unit/` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 957 | `mocha -R list` | 
| [router5/router5](https://github.com/router5/router5) | 957 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 955 | `mocha --compilers js:babel-core/register` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 955 | `mocha $(find test -name '*.test.js')` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 955 | `mocha --timeout 5000` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 951 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 950 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 949 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 948 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [tomas/needle](https://github.com/tomas/needle) | 945 | `mocha test` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 944 | `mocha --reporter spec` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 942 | `mocha -t 120000 test/*.test.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 938 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 937 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 937 | `standard && mocha -b` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 935 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 935 | `webpack && mocha test/unit` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 932 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 930 | `mocha -R spec ./test/unit/**` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 924 | `mocha ./test/test*.js --reporter spec` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 923 | `mocha --reporter spec --bail --check-leaks test/` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 920 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 919 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 917 | `mocha tests/*.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 912 | `mocha && standard` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 910 | `mocha` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 907 | `mocha ./test/index.js` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 906 | `eslint src test && mocha --compilers babel-register` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 906 | `mocha --reporter spec --bail --check-leaks test/` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 903 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 897 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 894 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 892 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 889 | `npm run lint && npm run mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 889 | `./node_modules/.bin/mocha --globals angular,require` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 887 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 886 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 886 | `mocha "client.test" --compilers js:babel-register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 884 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 883 | `mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 881 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 873 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 872 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 872 | `mocha --compilers js:babel-register test/*.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 871 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 866 | `mocha --reporter list` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 862 | `mocha --reporter spec --bail --check-leaks test/` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 861 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 860 | `mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 859 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 858 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 857 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 852 | `node_modules/.bin/mocha` | 
| [reactivestack/cookies](https://github.com/reactivestack/cookies) | 852 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 851 | `npm run convertto:es5 && npm run mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 850 | `npm run lint && mocha --require @babel/register` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 849 | `mocha ./test -R spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 848 | `mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 846 | `npm run lint && mocha -R spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 845 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 839 | `npm run lint && npm run mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 837 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 837 | `mocha tests` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 837 | `mocha --timeout 200000` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 836 | `eslint test && mocha --compilers js:babel/register` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 834 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 834 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 829 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 829 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 828 | `node_modules/.bin/mocha test/spec` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 820 | `mocha` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 820 | `mocha -R spec` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 818 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 818 | `mocha && ember test` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 815 | `mocha --reporter spec` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 814 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 813 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 810 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 805 | `mocha --check-leaks -t 20000` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 803 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 803 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 801 | `mocha -t 600000` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 801 | `istanbul cover _mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 801 | `standard && standard ./bin/* && mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 796 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 795 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 794 | `mocha --require babel-register` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 794 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 793 | `mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 791 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 790 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 790 | `mocha test --compilers js:babel-register` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 789 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 788 | `mocha -t 5000` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 787 | `mocha --reporter spec --bail --check-leaks test/` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 785 | `cake build && mocha ./test/mocha/*.coffee` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 782 | `mocha` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 781 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 781 | `istanbul cover -- _mocha --reporter spec` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 780 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 780 | `nyc mocha specs` | 
| [edsu/anon](https://github.com/edsu/anon) | 776 | `mocha --colors --reporter spec test.js` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 776 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 773 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 771 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 771 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 769 | `mocha --reporter list` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 765 | `npm run lint && mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 765 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 764 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 764 | `mocha spec/*.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 764 | `mocha --async-only` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 763 | `./node_modules/.bin/mocha -R spec` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 761 | `xo && mocha -R spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 761 | `mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 760 | `npm run mocha:istanbul` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 753 | `mocha --ui tdd --require ./test/__setup` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 751 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 751 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 748 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 741 | `mocha -R spec src/**/*_test.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 739 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [bitpay/insight](https://github.com/bitpay/insight) | 737 | `mocha test` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 733 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 729 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 729 | `mocha --reporter spec` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 728 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 728 | `mocha --recursive -s 15 test/` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 726 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 725 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 725 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 724 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 722 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 721 | `mocha test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 719 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 714 | `npm run mocha-test test/integration` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 713 | `mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 712 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 709 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [3Dparallax/insight](https://github.com/3Dparallax/insight) | 709 | `mocha test` | 
| [developit/decko](https://github.com/developit/decko) | 707 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 704 | `mocha test` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 704 | `mocha tests/*.mocha.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 704 | `npm run build && istanbul test _mocha test/test.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 703 | `mocha` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 703 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 702 | `npm run bundle && mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 699 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 699 | `mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 697 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 695 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 694 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 693 | `mocha test` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 693 | `mocha` | 