# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:59 04/04/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 40434 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40125 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 37496 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29109 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23688 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 22707 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 21421 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 21060 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 18261 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17905 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15866 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15312 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13941 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 13646 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13001 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12395 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12234 | `mocha 'test/**/*.spec.js'` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12074 | `mocha` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11955 | `./node_modules/.bin/mocha test/` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11839 | `mocha --reporter spec test/*-test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11556 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11081 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10806 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10450 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10032 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9910 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9557 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9494 | `mocha --harmony` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9470 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9352 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9335 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9002 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8680 | `grunt mocha` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8668 | `mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8547 | `mocha test/*-test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 8395 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8234 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8216 | `mocha --check-leaks -R dot` | 
| [websockets/ws](https://github.com/websockets/ws) | 8157 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8143 | `grunt clean:test && mocha --exit` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8054 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7990 | `./node_modules/.bin/mocha test/src` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7907 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7852 | `mocha --compilers js:babel-register test/test.js` | 
| [amark/gun](https://github.com/amark/gun) | 7834 | `mocha` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7831 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7625 | `npm run eslint && npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7550 | `mocha tests/*.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7472 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7439 | `mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7284 | `./node_modules/.bin/mocha test` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7246 | `npm run build && istanbul cover _mocha` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7218 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7169 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7022 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6705 | `nyc mocha test/**/* -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6701 | `mocha --opts mocha.opts` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6631 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6629 | `mocha $HARMONY_OPTS` | 
| [aui/art-template](https://github.com/aui/art-template) | 6610 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6570 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6564 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6560 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [almende/vis](https://github.com/almende/vis) | 6458 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6175 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6051 | `npm run lint -s && npm run mocha -s` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6011 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5974 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5968 | `npm run test:mocha:src` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5925 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5870 | `npm run jshint && mocha test/` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5699 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5618 | `mocha test --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5588 | `mocha tests/node.js` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5528 | `mocha test/test.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5494 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5463 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5412 | `mocha --exit --require babel-core/register` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5396 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 5382 | `npm run build-cli && mocha` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5284 | `mocha` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5196 | `mocha --timeout 10000 && npm run lint` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5164 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5147 | `mocha src/**/*Tests.js --harmony` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5134 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4931 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 4817 | `mocha; jshint *.js lib` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4809 | `gulp lint && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4800 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4762 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [redux-utilities/redux-actions](https://github.com/redux-utilities/redux-actions) | 4755 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4724 | `mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4666 | `mocha test` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4657 | `standard && mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4649 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4640 | `mocha --reporter spec -t 8000` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 4593 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4550 | `gulp build; mocha;` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4548 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4541 | `mocha ./test/runner.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4475 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4455 | `mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4409 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4401 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4324 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4313 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4293 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4259 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4257 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4224 | `mocha -R spec ./test --recursive` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4047 | `mocha --recursive && make test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4036 | `nyc mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3958 | `NODE_ENV=test mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3933 | `mocha --require test/babel-hook test/*.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 3906 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3902 | `npm run lint && npm run mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3891 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3887 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3857 | `export TESTING=true; mocha --reporter list` | 
| [tj/ejs](https://github.com/tj/ejs) | 3826 | `mocha --require should --reporter spec` | 
| [erming/shout](https://github.com/erming/shout) | 3814 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3766 | `mocha -R spec ./test` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3746 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3740 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3731 | `nyc mocha` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3711 | `npm run lint ; mocha && mocha test/individual` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3655 | `mocha ./test/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3651 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3647 | `npm run jshint && npm run mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3608 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3576 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3553 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3549 | `mocha tests/javascript` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3522 | `npm run lint && npm run mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3516 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [primus/primus](https://github.com/primus/primus) | 3511 | `npm run build && mocha test/*.test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3474 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3443 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3430 | `node_modules/.bin/mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3414 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3412 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3410 | `mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3401 | `mocha --check-leaks --reporter spec --bail` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3394 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3282 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3265 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3259 | `nyc mocha "test/**/*.test.js"` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3232 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 3229 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3196 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3109 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3103 | `mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3101 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3089 | `node_modules/.bin/mocha test/tests.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3089 | `./node_modules/.bin/mocha test/test.*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3083 | `mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3062 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3025 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3017 | `mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2983 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 2951 | `NODE_ENV=test mocha test/**/*.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2945 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2930 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2924 | `mocha test/*.js` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2908 | `nyc mocha && tsc` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2893 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2883 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2831 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2825 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2815 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2813 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2801 | `mocha test/index.js && npm run demo` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2801 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2798 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2797 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2790 | `mocha -R spec --recursive src/test` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2769 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2767 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2765 | `mocha --require should --reporter spec` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2756 | `istanbul cover _mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2744 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2732 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2719 | `mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2717 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2712 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2711 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2704 | `mocha` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2693 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [tj/should.js](https://github.com/tj/should.js) | 2679 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2677 | `mocha --opts mocha.opts` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2672 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2652 | `xo && mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2641 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2629 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 2621 | `yarn tsc && yarn lint && mocha` | 
| [css/csso](https://github.com/css/csso) | 2611 | `mocha --reporter dot` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2611 | `npm run mocha && npm run lint` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2603 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2601 | `mocha --timeout 100000` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2598 | `NODE_ENV=test mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2594 | `mocha-phantomjs ./test/index.html` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2577 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2573 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2567 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2554 | `mocha --compilers js:babel-register --recursive spec` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2546 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2543 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2540 | `mocha --recursive --watch` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2531 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2524 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2520 | `export TESTING=true; mocha --reporter list` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2489 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2440 | `mocha --reporter=spec test/*-test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2439 | `node_modules/.bin/mocha --reporter spec` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2427 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2425 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2419 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2409 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2402 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2376 | `npm run build && cd test && mocha . --reporter dot` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2371 | `nyc mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2370 | `node node_modules/mocha/bin/_mocha` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2366 | `export TESTING=true; mocha --reporter list` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2349 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2339 | `mocha test/src/**/*.unit.js` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2336 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2335 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2332 | `grunt jshint && mocha` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2332 | `mocha test` | 
| [json5/json5](https://github.com/json5/json5) | 2322 | `nyc --reporter=html --reporter=text mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2289 | `mocha --require should --reporter spec` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2280 | `mocha "test/**/*-test.js"` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2272 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2265 | `mocha` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2264 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2257 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2238 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2236 | `npm run lint && npm run build && npm run mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2232 | `mocha test test/unit/**/*_test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2222 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2217 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2213 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2201 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2198 | `mocha -R spec` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2178 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2166 | `mocha test.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2153 | `mocha --compilers js:babel-register` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2119 | `mocha -R landing test/index` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2117 | `nyc --reporter=html --reporter=text mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2086 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2076 | `cross-env BABEL_ENV=test mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2060 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [noble/noble](https://github.com/noble/noble) | 2057 | `mocha -R spec test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2056 | `mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2051 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2045 | `mocha && eslint .` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2030 | `mocha test && npm run lint` | 
| [slate/slate](https://github.com/slate/slate) | 2010 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2000 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1976 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1955 | `standard && mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1934 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1934 | `mocha --require=test/test_helper.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1929 | `mocha --compilers js:babel-register` | 
| [Qix-/color](https://github.com/Qix-/color) | 1927 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1906 | `mocha test/index.js --reporter dot` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1905 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1904 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1898 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1890 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1885 | `mocha test/runner.js --reporter spec` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1866 | `mocha --require ./test/common --growl test/expect.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1865 | `mocha --reporter spec --timeout 5000` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1852 | `mocha tests.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1849 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1845 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1840 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1824 | `mocha --compilers js:babel-core/register __tests__` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1818 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1817 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [then/promise](https://github.com/then/promise) | 1817 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1798 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1792 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1791 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1789 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [kach/nearley](https://github.com/kach/nearley) | 1772 | `mocha test/*.test.js` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1771 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1768 | `mocha && eslint *.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1765 | `npm run lint && mocha -R dot && npm run cover` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1761 | `mocha test` | 
| [share/sharedb](https://github.com/share/sharedb) | 1761 | `./node_modules/.bin/mocha && npm run jshint` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1760 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1759 | `mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1750 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1738 | `npm run lint && mocha --reporter spec test/*.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1731 | `nyc npm run _mocha` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1729 | `mocha test` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1728 | `mocha --reporter spec && npm run test-typescript` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1728 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1723 | `mocha -R spec spec spec/reporters` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1721 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1714 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1714 | `npm run mocha && npm run karma` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1709 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1707 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1705 | `rm -rf ./dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1693 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1675 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1674 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1673 | `npm run lint && npm run mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1673 | `xo && mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1663 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1662 | `mocha` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1651 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1647 | `mocha && npm run lint` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1638 | `mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 1634 | `npm run lint && npm run mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1624 | `mocha --reporter spec --grep .` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1620 | `mocha tests/test.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1620 | `mocha tests --compilers js:babel-core/register` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1618 | `mocha --expose-gc --slow 300` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1611 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1606 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1605 | `mocha test/*.js` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1604 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1601 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1597 | `npm run lint && mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1591 | `mocha test/**/*.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1589 | `mocha test -u bdd -R spec` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1588 | `mocha --reporter spec test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1588 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1578 | `mocha test --timeout 600000` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1578 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1574 | `mocha ./test/basic.js -t 5000` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1573 | `standard "src/*.js" && npm run build && mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1564 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1555 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1550 | `mocha spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1546 | `eslint . && mocha -t 5000` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1527 | `npm run lint && npm run mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1517 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1505 | `mocha --compilers js:babel-register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1503 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1503 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1500 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1499 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1492 | `npm run test:lint && npm run test:mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1480 | `mocha -u tdd` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1476 | `mocha --reporter spec` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1469 | `mocha -R spec` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1465 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1461 | `node_modules/.bin/mocha --recursive` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1455 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [samccone/drool](https://github.com/samccone/drool) | 1442 | `mocha test/tests.js --timeout=10000` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1441 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1440 | `mocha test/**/*.spec.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1437 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1430 | `eslint --cache . && tsc && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1424 | `mocha --check-leaks -R dot` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1420 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1417 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1416 | `nyc mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1413 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1412 | `mocha test.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1408 | `standard "./src/*.js" && mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1402 | `mocha test.js` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1396 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1394 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1384 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1381 | `mocha compiled_tests/` | 
| [zeit/ms](https://github.com/zeit/ms) | 1380 | `mocha tests.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1378 | `mocha --recursive` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1374 | `mocha --check-leaks --reporter spec --bail` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1374 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [teambit/bit](https://github.com/teambit/bit) | 1374 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1369 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1354 | `./node_modules/mocha/bin/mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1340 | `mocha test/setup.js test/spec/*.js` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1339 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1337 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1337 | `nyc npm run mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1335 | `cross-env NODE_ENV=test nyc mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1335 | `istanbul cover _mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1326 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1313 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1306 | `mocha -R spec test/*.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1301 | `npm run build && mocha -r should` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1293 | `mocha-phantomjs tests/index.html` | 
| [electron/devtron](https://github.com/electron/devtron) | 1273 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1273 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1270 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1268 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1265 | `./node_modules/.bin/mocha test` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1264 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1261 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1259 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1256 | `mocha spec/exec.js` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1250 | `istanbul cover _mocha test -- --timeout 20000` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1241 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1232 | `mocha --check-leaks --require @babel/register` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1232 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1227 | `mocha test/*.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1223 | `mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1223 | `mocha --recursive` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1219 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1217 | `mocha --opts test/opts/mocha.opts` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1217 | `mocha tests` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1209 | `mocha test/test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1203 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1201 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1197 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1196 | `mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1194 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1192 | `mocha test/**/*Spec.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1188 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1187 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1185 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1179 | `node ./node_modules/mocha/bin/mocha tests` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1177 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1175 | `mocha test` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1171 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1170 | `mocha test` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1168 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1166 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1162 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1162 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1162 | `standard && istanbul cover _mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1161 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1161 | `mocha test/unit` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1161 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1159 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1159 | `eslint src && mocha && karma start --single-run` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1156 | `mocha --reporter dot` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1149 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [normalize/mz](https://github.com/normalize/mz) | 1135 | `mocha --reporter spec` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1134 | `node_modules/.bin/mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1133 | `mocha src/test.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1132 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1130 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1129 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [variety/variety](https://github.com/variety/variety) | 1126 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1126 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1125 | `npm run lint && npm run mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1122 | `nyc mocha --timeout=20000 test.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1121 | `mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1119 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1114 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1109 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1104 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1102 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1101 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1096 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1094 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1093 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1092 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1087 | `mocha tests/test-*` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1083 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1078 | `nodeunit test; mocha test` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1078 | `mocha --check-leaks --reporter spec --bail test/` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1077 | `mocha test/*` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1073 | `mocha $(find test -name '*.test.js')` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1072 | `mocha --check-leaks -t 20000` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1071 | `mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1069 | `mocha --compilers js:babel-register` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1069 | `xo && mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1068 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1068 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1055 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1044 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1042 | `NODE_PATH=. mocha **/*.spec.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1042 | `mocha --reporter spec --timeout 3000` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1040 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1039 | `istanbul test _mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1038 | `istanbul cover _mocha test/*.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1035 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1033 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1032 | `npm run prepublishOnly && mocha test/test.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1026 | `mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1023 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1022 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1018 | `mocha test/tests.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1015 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1015 | `mocha --check-leaks -R dot` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1008 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1007 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1006 | `mocha -R spec ./test/unit/**` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1004 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1002 | `mocha` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 996 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 995 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 994 | `mocha --recursive test` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 992 | `mocha --compilers js:babel-core/register` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 991 | `mocha --recursive --bail --reporter spec test` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 990 | `standard && mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 988 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 986 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 986 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 983 | `mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [router5/router5](https://github.com/router5/router5) | 982 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 979 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 979 | `mocha tests/*.js` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 974 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 969 | `npm run rollup-cjs && mocha test/test.js` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 969 | `mocha $(find test -name '*.test.js')` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 968 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 965 | `mocha ./test/test*.js --reporter spec` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 965 | `webpack && mocha test/unit` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 962 | `mocha -R list` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 962 | `mocha -t 120000 test/*.test.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 961 | `mocha --recursive test/unit/` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 961 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 959 | `mocha --async-only` | 
| [tomas/needle](https://github.com/tomas/needle) | 958 | `mocha test` | 
| [electron/asar](https://github.com/electron/asar) | 956 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 955 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 955 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 952 | `mocha --timeout 5000` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 950 | `mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 949 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 946 | `standard && mocha -b` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 945 | `mocha --reporter spec` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 942 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron/spectron](https://github.com/electron/spectron) | 938 | `mocha && standard` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 933 | `npm run lint && npm run mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 933 | `mocha --reporter spec --bail --check-leaks test/` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 928 | `eslint src test && mocha --compilers babel-register` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 924 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 922 | `mocha` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 921 | `mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 914 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 913 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 901 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 901 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 900 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 900 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 900 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 900 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 900 | `mocha "client.test" --compilers js:babel-register` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 899 | `mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 894 | `npm run lint && mocha --require @babel/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 891 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 889 | `./node_modules/.bin/mocha --globals angular,require` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 884 | `mocha --compilers js:babel-register test/*.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 884 | `TEST=all mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 881 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 879 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 879 | `mocha ./test -R spec` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 877 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 876 | `mocha --reporter spec --bail --check-leaks test/` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 874 | `npm run convertto:es5 && npm run mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 873 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 873 | `mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 870 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 869 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 863 | `npm run lint && mocha -R spec` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 863 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 858 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 855 | `node_modules/.bin/mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 851 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 851 | `mocha` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 848 | `mocha -R spec` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 846 | `mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 846 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 844 | `npm run lint && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 844 | `mocha --timeout 200000` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 843 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 842 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 839 | `node_modules/.bin/mocha test/spec` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 838 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 838 | `eslint test && mocha --compilers js:babel/register` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 837 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 836 | `mocha --timeout 20000` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 833 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 833 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 822 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 820 | `mocha && ember test` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 819 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 818 | `mocha --reporter spec` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 816 | `mocha -t 600000` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 816 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 816 | `mocha --check-leaks -t 20000` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 812 | `standard && standard ./bin/* && mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 811 | `istanbul cover _mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 809 | `npm run mocha:istanbul` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 809 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 808 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 807 | `mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 806 | `mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 801 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 801 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 800 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 798 | `mocha --require babel-register` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 798 | `mocha -t 5000` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 798 | `mocha test --compilers js:babel-register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 797 | `nyc mocha specs` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 793 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 792 | `mocha --reporter spec --bail --check-leaks test/` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 789 | `cake build && mocha ./test/mocha/*.coffee` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 789 | `istanbul cover -- _mocha --reporter spec` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 786 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 785 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 785 | `mocha spec/*.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 783 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 781 | `./node_modules/.bin/mocha -R spec` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 780 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 779 | `mocha --reporter list` | 
| [edsu/anon](https://github.com/edsu/anon) | 777 | `mocha --colors --reporter spec test.js` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 776 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 773 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 771 | `mocha --async-only` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 770 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 769 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 768 | `xo && mocha -R spec` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 767 | `npm run lint && mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 767 | `mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 766 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 764 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 757 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 756 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 754 | `mocha --ui tdd --require ./test/__setup` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 748 | `mocha -R spec src/**/*_test.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 747 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 747 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 743 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 741 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 740 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 737 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 735 | `mocha --recursive -s 15 test/` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 735 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 733 | `mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 733 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 731 | `npm run mocha-test test/integration` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 730 | `mocha --reporter spec` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 730 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 729 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 727 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 721 | `mocha test.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 715 | `mocha test` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 715 | `mocha test` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 715 | `mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 714 | `mocha test --compilers js:babel-core/register` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 714 | `mocha` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 713 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [developit/decko](https://github.com/developit/decko) | 713 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 713 | `npm run build && istanbul test _mocha test/test.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 713 | `mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 713 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 712 | `mocha tests/*.mocha.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 712 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 712 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 712 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [radi-js/radi](https://github.com/radi-js/radi) | 709 | `nyc mocha` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 708 | `mocha --harmony --full-trace --check-leaks` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 708 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 707 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 707 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 706 | `npm run bundle && mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 705 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 704 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 