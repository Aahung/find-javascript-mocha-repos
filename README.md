# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:52 03/31/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 40322 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40077 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 37427 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29086 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23659 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 22670 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 21358 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 20925 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 18220 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17874 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15847 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15271 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13938 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 13590 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12974 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12369 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12225 | `mocha 'test/**/*.spec.js'` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12071 | `mocha` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11932 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 11872 | `cross-env BABEL_ENV=test NODE_ENV=test mocha --recursive --require babel-register --require ./test/setup.js` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11824 | `mocha --reporter spec test/*-test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11516 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11037 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10783 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10414 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9972 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9866 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9536 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9479 | `mocha --harmony` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9456 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9331 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9307 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8994 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8677 | `grunt mocha` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8637 | `mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8534 | `mocha test/*-test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 8350 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8219 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8214 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8133 | `grunt clean:test && mocha --exit` | 
| [websockets/ws](https://github.com/websockets/ws) | 8123 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8029 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7977 | `./node_modules/.bin/mocha test/src` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7856 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7838 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7827 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [amark/gun](https://github.com/amark/gun) | 7823 | `mocha` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7616 | `npm run eslint && npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7519 | `mocha tests/*.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7475 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7441 | `mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7274 | `./node_modules/.bin/mocha test` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7238 | `npm run build && istanbul cover _mocha` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7184 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7150 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6980 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6681 | `nyc mocha test/**/* -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6669 | `mocha --opts mocha.opts` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6621 | `mocha $HARMONY_OPTS` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6620 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6590 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6552 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6543 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6524 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [almende/vis](https://github.com/almende/vis) | 6437 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6126 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6045 | `npm run lint -s && npm run mocha -s` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6008 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5968 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5945 | `npm run test:mocha:src` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5924 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5855 | `npm run jshint && mocha test/` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5684 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5605 | `mocha test --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5573 | `mocha tests/node.js` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5509 | `mocha test/test.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5486 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5450 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5396 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5393 | `mocha --exit --require babel-core/register` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 5333 | `npm run build-cli && mocha` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5261 | `mocha` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5194 | `mocha --timeout 10000 && npm run lint` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5164 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5145 | `mocha src/**/*Tests.js --harmony` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5121 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4906 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4806 | `gulp lint && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4794 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 4764 | `mocha; jshint *.js lib` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4756 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [redux-utilities/redux-actions](https://github.com/redux-utilities/redux-actions) | 4739 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4685 | `mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4667 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4646 | `mocha -R spec 'tests/app'` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4641 | `standard && mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4639 | `mocha --reporter spec -t 8000` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 4570 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4547 | `gulp build; mocha;` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4537 | `mocha ./test/runner.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4533 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4464 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4443 | `mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4402 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4399 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4314 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4306 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4280 | `mocha test` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4253 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4253 | `mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4224 | `mocha -R spec ./test --recursive` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4035 | `nyc mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4030 | `mocha --recursive && make test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3947 | `NODE_ENV=test mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3932 | `mocha --require test/babel-hook test/*.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 3902 | `mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3891 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3886 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3875 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3857 | `export TESTING=true; mocha --reporter list` | 
| [tj/ejs](https://github.com/tj/ejs) | 3822 | `mocha --require should --reporter spec` | 
| [erming/shout](https://github.com/erming/shout) | 3814 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3751 | `mocha -R spec ./test` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3726 | `nyc mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3714 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3710 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3705 | `npm run lint ; mocha && mocha test/individual` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3648 | `mocha ./test/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3648 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3647 | `npm run jshint && npm run mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3596 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3574 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3552 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3547 | `mocha tests/javascript` | 
| [primus/primus](https://github.com/primus/primus) | 3506 | `npm run build && mocha test/*.test.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3500 | `npm run lint && npm run mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3498 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3474 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3443 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3432 | `node_modules/.bin/mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3411 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3407 | `mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3398 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3389 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3380 | `mocha --check-leaks --reporter spec --bail` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3273 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3253 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3236 | `nyc mocha "test/**/*.test.js"` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3224 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 3207 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3179 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3102 | `mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3093 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3088 | `node_modules/.bin/mocha test/tests.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3087 | `./node_modules/.bin/mocha test/test.*.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3086 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3082 | `mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3041 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3016 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3015 | `mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2982 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2942 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 2936 | `NODE_ENV=test mocha test/**/*.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2922 | `mocha test/*.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2915 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2888 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2887 | `nyc mocha && tsc` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2862 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2826 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2818 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2810 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2808 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2796 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2795 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2790 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2784 | `mocha -R spec --recursive src/test` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2782 | `mocha test/index.js && npm run demo` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2763 | `mocha --require should --reporter spec` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2762 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2758 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2750 | `istanbul cover _mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2739 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2728 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2713 | `mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2712 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2707 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2705 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2700 | `mocha` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2683 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [tj/should.js](https://github.com/tj/should.js) | 2677 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2669 | `mocha --opts mocha.opts` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2669 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2648 | `xo && mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2638 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2626 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2609 | `npm run mocha && npm run lint` | 
| [css/csso](https://github.com/css/csso) | 2604 | `mocha --reporter dot` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2600 | `mocha --timeout 100000` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2595 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 2592 | `yarn tsc && yarn lint && mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2591 | `mocha-phantomjs ./test/index.html` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2572 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2561 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2560 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2542 | `mocha --compilers js:babel-register --recursive spec` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2538 | `mocha --recursive --watch` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2537 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2530 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2522 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2512 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2486 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2468 | `NODE_ENV=test mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2436 | `mocha --reporter=spec test/*-test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2429 | `node_modules/.bin/mocha --reporter spec` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2420 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2418 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2406 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2405 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2392 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2373 | `npm run build && cd test && mocha . --reporter dot` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2371 | `nyc mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2370 | `node node_modules/mocha/bin/_mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2349 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2337 | `mocha test/src/**/*.unit.js` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2335 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2335 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2334 | `grunt jshint && mocha` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2323 | `mocha test` | 
| [json5/json5](https://github.com/json5/json5) | 2306 | `nyc --reporter=html --reporter=text mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2273 | `mocha --require should --reporter spec` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2271 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2263 | `mocha "test/**/*-test.js"` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2261 | `mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2253 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2252 | `mocha test/unit --require mochahook` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2232 | `npm run lint && npm run build && npm run mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2230 | `mocha test test/unit/**/*_test.js` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2229 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2221 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2218 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2211 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2197 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2196 | `mocha -R spec` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2165 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2154 | `mocha test.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2152 | `mocha --compilers js:babel-register` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2113 | `nyc --reporter=html --reporter=text mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2108 | `mocha -R landing test/index` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2087 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2074 | `cross-env BABEL_ENV=test mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2057 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2055 | `mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2048 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2045 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2044 | `mocha && eslint .` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2022 | `mocha test && npm run lint` | 
| [slate/slate](https://github.com/slate/slate) | 2011 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1985 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1971 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1953 | `standard && mocha` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1933 | `mocha --require=test/test_helper.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1928 | `mocha -c test/index.js` | 
| [Qix-/color](https://github.com/Qix-/color) | 1923 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1921 | `mocha --compilers js:babel-register` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1906 | `mocha test/index.js --reporter dot` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1902 | `mocha` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1902 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1892 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1886 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1872 | `mocha test/runner.js --reporter spec` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1863 | `mocha --require ./test/common --growl test/expect.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1863 | `mocha --reporter spec --timeout 5000` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1850 | `mocha tests.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1842 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1840 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1833 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1819 | `mocha --compilers js:babel-core/register __tests__` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1819 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [then/promise](https://github.com/then/promise) | 1815 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1807 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1803 | `mocha --timeout 5000` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1792 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1791 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1789 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1786 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [kach/nearley](https://github.com/kach/nearley) | 1772 | `mocha test/*.test.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1764 | `mocha && eslint *.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1761 | `npm run lint && mocha -R dot && npm run cover` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1761 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1761 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1760 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1758 | `mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 1757 | `./node_modules/.bin/mocha && npm run jshint` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1738 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1733 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1727 | `mocha test` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1726 | `mocha --reporter spec && npm run test-typescript` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1726 | `nyc npm run _mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1723 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1721 | `mocha -R spec spec spec/reporters` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1720 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1713 | `npm run mocha && npm run karma` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1710 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1709 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1708 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1702 | `npm run lint && mocha server/test --timeout 10000 --recursive --exit` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1692 | `npm run jshint && mocha --recursive` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1691 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1674 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1672 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1671 | `npm run lint && npm run mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1671 | `xo && mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1661 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1657 | `mocha` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1648 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1647 | `mocha && npm run lint` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1635 | `mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 1623 | `npm run lint && npm run mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1621 | `mocha --reporter spec --grep .` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1619 | `mocha tests/test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1618 | `mocha --expose-gc --slow 300` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1610 | `mocha tests --compilers js:babel-core/register` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1609 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1606 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1604 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1600 | `mocha test/*.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1597 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1594 | `npm run lint && mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1589 | `mocha test/**/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1585 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1583 | `mocha test -u bdd -R spec` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1581 | `mocha --reporter spec test/*.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1578 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1576 | `mocha test --timeout 600000` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1568 | `mocha ./test/basic.js -t 5000` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1564 | `standard "src/*.js" && npm run build && mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1562 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1550 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1549 | `mocha spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1520 | `npm run lint && npm run mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1513 | `mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1503 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1503 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1501 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1498 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1498 | `mocha --compilers js:babel-register` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1493 | `eslint . && mocha -t 5000` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1486 | `npm run test:lint && npm run test:mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1479 | `mocha -u tdd` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1474 | `mocha --reporter spec` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1469 | `mocha -R spec` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1459 | `node_modules/.bin/mocha --recursive` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1452 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1448 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [samccone/drool](https://github.com/samccone/drool) | 1443 | `mocha test/tests.js --timeout=10000` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1442 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1442 | `mocha test/**/*.spec.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1437 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1426 | `eslint --cache . && tsc && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1420 | `mocha --check-leaks -R dot` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1416 | `nyc mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1416 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1413 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1412 | `mocha test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1411 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1403 | `standard "./src/*.js" && mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1399 | `mocha test.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1386 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1383 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1380 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1375 | `mocha compiled_tests/` | 
| [zeit/ms](https://github.com/zeit/ms) | 1373 | `mocha tests.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1372 | `mocha --recursive` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1372 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1370 | `mocha --check-leaks --reporter spec --bail` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1368 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1356 | `./node_modules/mocha/bin/mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 1346 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1337 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1337 | `mocha test/setup.js test/spec/*.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1335 | `cross-env NODE_ENV=test nyc mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1334 | `istanbul cover _mocha` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1334 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1331 | `nyc npm run mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1326 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1312 | `mocha --timeout 10000 ./tests/lib.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1299 | `npm run build && mocha -r should` | 
| [noble/bleno](https://github.com/noble/bleno) | 1299 | `mocha -R spec test/*.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1293 | `mocha-phantomjs tests/index.html` | 
| [electron/devtron](https://github.com/electron/devtron) | 1270 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1268 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1266 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1265 | `./node_modules/.bin/mocha test` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1264 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1260 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1259 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1259 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1255 | `mocha spec/exec.js` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1249 | `istanbul cover _mocha test -- --timeout 20000` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1235 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1231 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1228 | `mocha --check-leaks --require @babel/register` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1224 | `mocha test/*.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1219 | `mocha --recursive` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1218 | `mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1216 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1214 | `mocha tests` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1211 | `mocha --opts test/opts/mocha.opts` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1203 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1198 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1197 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1195 | `mocha` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1194 | `mocha test/**/*Spec.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1191 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1187 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1184 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1178 | `mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1177 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1176 | `node ./node_modules/mocha/bin/mocha tests` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1175 | `mocha test` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1169 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1163 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1163 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1163 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1163 | `mocha test` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1162 | `standard && istanbul cover _mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1160 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1157 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1157 | `mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1156 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1156 | `mocha test/unit` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1153 | `eslint src && mocha && karma start --single-run` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1152 | `mocha --reporter dot` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1142 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1135 | `node_modules/.bin/mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1133 | `mocha --reporter spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1131 | `mocha src/test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1130 | `mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1128 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1127 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1125 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [variety/variety](https://github.com/variety/variety) | 1123 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1121 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1121 | `npm run lint && npm run mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1116 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1113 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1109 | `nyc mocha --timeout=20000 test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1102 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1100 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1099 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1096 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1093 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1092 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1091 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1080 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1079 | `mocha tests/test-*` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1075 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1073 | `mocha --check-leaks --reporter spec --bail test/` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1072 | `mocha test/*` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1071 | `mocha --check-leaks -t 20000` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1069 | `mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1069 | `mocha --compilers js:babel-register` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1068 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1068 | `mocha $(find test -name '*.test.js')` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1066 | `xo && mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1058 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1052 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1042 | `mocha --reporter spec --timeout 3000` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1040 | `istanbul test _mocha` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1040 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1038 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1037 | `NODE_PATH=. mocha **/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1035 | `istanbul cover _mocha test/*.js` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1031 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1029 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1023 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1023 | `npm run prepublishOnly && mocha test/test.js` | 
| [jas/playground](https://github.com/jas/playground) | 1023 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1022 | `mocha` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1015 | `mocha --check-leaks -R dot` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1013 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1013 | `mocha test/tests.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1006 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1003 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1002 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1001 | `mocha` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 996 | `mocha --colors ./test/*.spec.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 994 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 991 | `mocha --recursive --bail --reporter spec test` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 990 | `standard && mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 987 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 986 | `mocha --compilers js:babel-core/register` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 985 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 983 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 982 | `mocha -R spec ./test/unit/**` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 982 | `mocha --recursive test` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 980 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [router5/router5](https://github.com/router5/router5) | 978 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 976 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 975 | `mocha` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 974 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 972 | `npm run rollup-cjs && mocha test/test.js` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 969 | `mocha $(find test -name '*.test.js')` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 967 | `mocha tests/*.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 965 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 963 | `mocha --recursive test/unit/` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 962 | `mocha -R list` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 961 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 961 | `mocha ./test/test*.js --reporter spec` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 961 | `webpack && mocha test/unit` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 960 | `mocha -t 120000 test/*.test.js` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 957 | `mocha --async-only` | 
| [tomas/needle](https://github.com/tomas/needle) | 955 | `mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 955 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [electron/asar](https://github.com/electron/asar) | 954 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 954 | `mocha --timeout 5000` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 951 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 945 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 945 | `mocha --reporter spec` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 945 | `standard && mocha -b` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 943 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 940 | `nyc mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 935 | `mocha && standard` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 931 | `mocha --reporter spec --bail --check-leaks test/` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 929 | `npm run lint && npm run mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 925 | `eslint src test && mocha --compilers babel-register` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 921 | `mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 921 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 920 | `mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 912 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 911 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 909 | `mocha spec/*.spec.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 899 | `mocha "client.test" --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 898 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 898 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 897 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 896 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 892 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 891 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 889 | `./node_modules/.bin/mocha --globals angular,require` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 887 | `npm run lint && mocha --require @babel/register` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 882 | `mocha --compilers js:babel-register test/*.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 879 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 878 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 877 | `mocha ./test -R spec` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 875 | `mocha --reporter spec --bail --check-leaks test/` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 874 | `npm run convertto:es5 && npm run mocha` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 874 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 872 | `mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 871 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 871 | `TEST=all mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 870 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 869 | `mocha --reporter list` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 863 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 859 | `npm run lint && mocha -R spec` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 858 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 853 | `node_modules/.bin/mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 852 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 851 | `mocha tests` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 846 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 845 | `mocha -R spec` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 844 | `npm run lint && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 844 | `mocha --timeout 200000` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 842 | `mocha` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 842 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 841 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 839 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 838 | `eslint test && mocha --compilers js:babel/register` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 834 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 833 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 833 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 831 | `mocha --timeout 20000` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 829 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 822 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 820 | `mocha && ember test` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 819 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 817 | `mocha --reporter spec` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 816 | `mocha -t 600000` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 816 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 814 | `mocha --check-leaks -t 20000` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 812 | `standard && standard ./bin/* && mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 810 | `istanbul cover _mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 807 | `mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 805 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 805 | `mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 801 | `mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 800 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 800 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 800 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 799 | `npm run mocha:istanbul` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 799 | `mocha test --compilers js:babel-register` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 798 | `mocha --require babel-register` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 795 | `mocha -t 5000` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 793 | `nyc mocha specs` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 792 | `nyc mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 792 | `mocha -u tdd` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 789 | `cake build && mocha ./test/mocha/*.coffee` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 787 | `istanbul cover -- _mocha --reporter spec` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 786 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 785 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 784 | `mocha spec/*.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 782 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 779 | `./node_modules/.bin/mocha -R spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 777 | `mocha --reporter list` | 
| [edsu/anon](https://github.com/edsu/anon) | 777 | `mocha --colors --reporter spec test.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 776 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 776 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 771 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 769 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 769 | `mocha --async-only` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 767 | `npm run lint && mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 767 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 766 | `xo && mocha -R spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 765 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 764 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 758 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 756 | `mocha --ui tdd --require ./test/__setup` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 755 | `mocha` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 748 | `mocha -R spec src/**/*_test.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 745 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 743 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 739 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 738 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 735 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 735 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 734 | `mocha --recursive -s 15 test/` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 733 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 731 | `mocha` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 730 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 730 | `mocha --reporter spec` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 729 | `npm run mocha-test test/integration` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 729 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 729 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 726 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 722 | `mocha test.js` | 
| [developit/decko](https://github.com/developit/decko) | 714 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 714 | `mocha` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 713 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 713 | `mocha test` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 713 | `npm run build && istanbul test _mocha test/test.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 713 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 712 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 712 | `mocha` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 712 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 710 | `mocha test --compilers js:babel-core/register` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 709 | `mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 708 | `mocha tests/*.mocha.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 708 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 708 | `mocha test` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 706 | `mocha --harmony --full-trace --check-leaks` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 705 | `npm run bundle && mocha` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 705 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 704 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 703 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 703 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 702 | `mocha test` | 