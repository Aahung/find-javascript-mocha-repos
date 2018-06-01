# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:57 06/01/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 41846 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40637 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38568 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29589 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24066 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23332 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 22651 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22302 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 18933 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18386 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16287 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15874 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14350 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14121 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13454 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12723 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12467 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12298 | `./node_modules/.bin/mocha test/` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 12226 | `mocha --reporter spec` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12149 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12079 | `mocha --reporter spec test/*-test.js` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11820 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11126 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10982 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10523 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10395 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9963 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9707 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9703 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9672 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9646 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 8914 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8831 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8769 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8428 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8365 | `mocha test/test.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8322 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8298 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8220 | `grunt clean:test && mocha --exit` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8203 | `mocha test/src` | 
| [amark/gun](https://github.com/amark/gun) | 8154 | `mocha` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8015 | `mocha --compilers js:babel-register test/test.js` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8000 | `mocha tests/*.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7932 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7744 | `npm run eslint && npm run mocha` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7724 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7586 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7555 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7515 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7490 | `./node_modules/.bin/mocha test` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7744 | `npm run eslint && npm run mocha` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7724 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7586 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7555 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7515 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7490 | `./node_modules/.bin/mocha test` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7436 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7333 | `npm run build && istanbul cover _mocha` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 7165 | `nyc mocha test/**/* -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7056 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7009 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6865 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 6859 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6844 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6793 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6771 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6684 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6579 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6276 | `npm run lint -s && npm run mocha -s` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6131 | `npm run jshint && mocha test/` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6117 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6106 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 6067 | `npm run build-cli && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6030 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5940 | `mocha` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5883 | `mocha test node-test --recursive` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5845 | `mocha --exit --require babel-core/register` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5828 | `mocha test/test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5828 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5716 | `mocha tests/node.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5625 | `mocha; jshint *.js lib` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5609 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5593 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5512 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5406 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5374 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5308 | `mocha` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5278 | `mocha --timeout 10000 && npm run lint` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5228 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5162 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5154 | `mocha --color` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5059 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4939 | `standard && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4928 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4902 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4897 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4815 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4720 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4694 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4674 | `mocha --reporter spec -t 8000` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4667 | `mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4649 | `gulp build; mocha;` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4596 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4588 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4555 | `mocha ./test/runner.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4510 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4493 | `./node_modules/.bin/mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4482 | `mocha test` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4416 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4352 | `mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4323 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4321 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4221 | `mocha -R spec ./test --recursive` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4206 | `NODE_ENV=test mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4202 | `mocha --recursive && make test` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4161 | `nyc mocha --exit` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4095 | `nyc mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4084 | `npm run lint && npm run mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3968 | `mocha --require test/babel-hook test/*.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 3961 | `mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3928 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3908 | `mocha -R spec ./test` | 
| [tj/ejs](https://github.com/tj/ejs) | 3898 | `mocha --require should --reporter spec` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3887 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3875 | `export TESTING=true; mocha --reporter list` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3859 | `npm run lint ; mocha && mocha test/individual` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3842 | `npm run lint && npm run mocha` | 
| [erming/shout](https://github.com/erming/shout) | 3803 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3790 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3764 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3699 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3661 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3620 | `standard && mocha --timeout 60000 test/test.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3593 | `mocha --check-leaks --reporter spec --bail` | 
| [primus/primus](https://github.com/primus/primus) | 3582 | `npm run build && mocha test/*.test.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3561 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3499 | `mocha --reporter spec --timeout 3000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3481 | `node_modules/.bin/mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3451 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3449 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3446 | `nyc mocha "test/**/*.test.js"` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3463 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3451 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3449 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3446 | `nyc mocha "test/**/*.test.js"` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3430 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3420 | `mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3420 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3410 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3394 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3362 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3342 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3338 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3332 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3266 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3183 | `NODE_ENV=test mocha test/**/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3171 | `node_modules/.bin/mocha test/tests.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3120 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3115 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3114 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3113 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 3076 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3075 | `mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3075 | `nyc mocha && tsc` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3053 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3033 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3025 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2869 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2859 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2848 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2838 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2836 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2835 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2807 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2776 | `mocha --require should --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2770 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2761 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2758 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2756 | `mocha --opts mocha.opts` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2747 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2736 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2733 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2729 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2726 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2718 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2702 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2690 | `npm run mocha && npm run lint` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2685 | `export TESTING=true; mocha --reporter list` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2683 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2758 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2756 | `mocha --opts mocha.opts` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2747 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2733 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2729 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2726 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2718 | `mocha` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2690 | `npm run mocha && npm run lint` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2685 | `export TESTING=true; mocha --reporter list` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2683 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2678 | `xo && mocha` | 
| [css/csso](https://github.com/css/csso) | 2671 | `mocha --reporter dot` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2659 | `mocha --require babel-register --recursive spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2659 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2653 | `mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2623 | `mocha --timeout 100000` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2653 | `mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2623 | `mocha --timeout 100000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2603 | `mocha-phantomjs ./test/index.html` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2590 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2589 | `mocha --recursive --watch` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2582 | `node_modules/.bin/mocha --reporter spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2555 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2540 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2534 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2531 | `mocha -R landing test/index` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2528 | `export TESTING=true; mocha --reporter list` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2527 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2355 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2348 | `mocha test/unit --require mochahook` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2341 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2338 | `grunt jshint && mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2322 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2295 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2295 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2257 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2252 | `mocha -R spec` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2242 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2237 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2224 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2284 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2257 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2252 | `mocha -R spec` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2242 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2237 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2224 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2217 | `nyc --reporter=html --reporter=text mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2168 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2164 | `mocha test && npm run lint` | 
| [gajus/swing](https://github.com/gajus/swing) | 2193 | `mocha --compilers js:babel-register` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2168 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2164 | `mocha test && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2147 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2143 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2135 | `eslint . && mocha -t 5000` | 
| [noble/noble](https://github.com/noble/noble) | 2112 | `mocha -R spec test/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2106 | `cross-env BABEL_ENV=test mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2084 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2083 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2055 | `mocha --compilers js:babel-register` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2033 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [Qix-/color](https://github.com/Qix-/color) | 2015 | `mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2013 | `standard && mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2009 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1979 | `mocha test/ --no-timeouts` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1975 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1961 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1961 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1957 | `mocha -c test/index.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1948 | `mocha --require=test/test_helper.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1946 | `mocha test/index.js --reporter dot` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1921 | `mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1917 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1916 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1913 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1892 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1871 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1867 | `mocha tests.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1864 | `nyc npm run _mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 1854 | `./node_modules/.bin/mocha && npm run jshint` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1845 | `npm run lint && mocha -R dot && npm run cover` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1825 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1889 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1881 | `mocha --require ./test/common --growl test/expect.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1876 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1871 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1867 | `mocha tests.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1864 | `nyc npm run _mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1859 | `mocha && eslint *.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1854 | `./node_modules/.bin/mocha && npm run jshint` | 
| [then/promise](https://github.com/then/promise) | 1853 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1845 | `npm run lint && mocha -R dot && npm run cover` | 
| [kach/nearley](https://github.com/kach/nearley) | 1832 | `mocha test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1825 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1815 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1807 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1783 | `mocha test` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1778 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1775 | `mocha --reporter spec && npm run test-typescript` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1772 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1766 | `npm run lint && mocha --reporter spec test/*.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1763 | `npm run mocha && npm run karma` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1762 | `mocha -R spec spec spec/reporters` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1754 | `mocha test` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1752 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [pahen/madge](https://github.com/pahen/madge) | 1734 | `npm run lint && npm run mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1722 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1718 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1716 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1715 | `mocha && npm run lint` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1705 | `npm run lint && npm run mocha` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1703 | `mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1703 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1701 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1699 | `mocha --reporter spec --grep .` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1696 | `mocha tests --compilers js:babel-core/register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1693 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1692 | `./node_modules/.bin/mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1687 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1675 | `xo && mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1663 | `mocha test/**/*.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1652 | `mocha test -u bdd -R spec` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1649 | `npm run lint && mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1652 | `mocha test -u bdd -R spec` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1649 | `npm run lint && mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1643 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1640 | `mocha test --timeout 600000` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1638 | `mocha test/*.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1636 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1636 | `mocha ./test/basic.js -t 5000` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1635 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1631 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1627 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1619 | `mocha tests/test.js` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1615 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1613 | `mocha spec` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1613 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1610 | `mocha --compilers js:babel-register` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1608 | `mocha && size-limit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1592 | `mocha test/* --reporter spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1591 | `npm run lint && npm run mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1587 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1570 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1551 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1541 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1539 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1527 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1384 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1368 | `./node_modules/mocha/bin/mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1362 | `mocha --timeout 10000 ./tests/lib.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1348 | `cross-env NODE_ENV=test nyc mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1344 | `mocha test` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1328 | `npm run build && mocha -r should` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1327 | `mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1317 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1311 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1311 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1384 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1368 | `./node_modules/mocha/bin/mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1362 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1357 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1354 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1348 | `cross-env NODE_ENV=test nyc mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1344 | `mocha -R spec test/*.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1344 | `mocha test` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1328 | `npm run build && mocha -r should` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1327 | `mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1327 | `mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1317 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1311 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1311 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1302 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1299 | `mocha-phantomjs tests/index.html` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1297 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1293 | `mocha --check-leaks --require @babel/register` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1288 | `./node_modules/.bin/mocha test` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1288 | `nyc mocha --timeout=20000 test.js` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1283 | `istanbul cover _mocha test -- --timeout 20000` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1277 | `mocha --recursive` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1368 | `./node_modules/mocha/bin/mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1362 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1357 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1354 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1348 | `cross-env NODE_ENV=test nyc mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1344 | `mocha -R spec test/*.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1344 | `mocha test` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1328 | `npm run build && mocha -r should` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1327 | `mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1317 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1311 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1311 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1297 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1293 | `mocha --check-leaks --require @babel/register` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1288 | `./node_modules/.bin/mocha test` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1288 | `nyc mocha --timeout=20000 test.js` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1283 | `istanbul cover _mocha test -- --timeout 20000` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1280 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1264 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1262 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1262 | `mocha test/unit` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1269 | `mocha --opts test/opts/mocha.opts` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1264 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1262 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1262 | `mocha test/unit` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1250 | `mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1247 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1247 | `eslint src && mocha && karma start --single-run` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1245 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1239 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1239 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1237 | `mocha test/*.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1236 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1229 | `mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1228 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1227 | `mocha tests` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1226 | `standard && istanbul cover _mocha` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1225 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1224 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1223 | `mocha --reporter dot` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1221 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1219 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1217 | `mocha test/test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1213 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1210 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1209 | `mocha tests/test-*` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1205 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1202 | `mocha test/**/*Spec.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1188 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1188 | `node ./node_modules/mocha/bin/mocha tests` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1188 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1186 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1186 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1186 | `mocha` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1184 | `mocha test` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1161 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1158 | `npm run lint && npm run mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1158 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1153 | `mocha --check-leaks --reporter spec --bail test/` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1148 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1144 | `mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1137 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1136 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1133 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1131 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1127 | `mocha -R spec ./test/unit/**` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1127 | `mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1137 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1136 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1133 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1131 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1127 | `mocha -R spec ./test/unit/**` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1127 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1124 | `TEST=all mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1123 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1112 | `NODE_ENV=test mocha tests/*.js` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1109 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1108 | `mocha ./test/test*.js --reporter spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1107 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1106 | `npm run prepublishOnly && mocha test/test.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1036 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1034 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1031 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1024 | `mocha --recursive --bail --reporter spec test` | 
| [jas/playground](https://github.com/jas/playground) | 1021 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1021 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1020 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1014 | `mocha --check-leaks -R dot` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1011 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1001 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1000 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 999 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 998 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 993 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 989 | `mocha --reporter spec --bail --check-leaks test/` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 988 | `mocha --recursive test/unit/` | 
| [tomas/needle](https://github.com/tomas/needle) | 988 | `mocha test` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1001 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1000 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 999 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 998 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 993 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 989 | `mocha --reporter spec --bail --check-leaks test/` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 988 | `mocha --recursive test/unit/` | 
| [tomas/needle](https://github.com/tomas/needle) | 988 | `mocha test` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 985 | `standard && mocha -b` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 980 | `npm run lint && mocha --require @babel/register` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 979 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [electron/spectron](https://github.com/electron/spectron) | 977 | `mocha && standard` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 976 | `mocha --async-only` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1014 | `mocha --check-leaks -R dot` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1011 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [electron/asar](https://github.com/electron/asar) | 1010 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1008 | `webpack && mocha test/unit` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1003 | `mocha $(find test -name '*.test.js')` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1001 | `mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 998 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 993 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 989 | `mocha --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 988 | `mocha` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 985 | `standard && mocha -b` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 980 | `npm run lint && mocha --require @babel/register` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 969 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 968 | `mocha -R list` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 964 | `eslint src test && mocha --compilers babel-register` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 960 | `mocha --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 958 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 956 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 956 | `mocha --timeout 20000` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 953 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 950 | `npm run mocha:istanbul` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 948 | `mocha --timeout 5000` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 948 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 946 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 940 | `mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 969 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 968 | `mocha -R list` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 964 | `eslint src test && mocha --compilers babel-register` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 960 | `mocha --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 958 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 956 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 956 | `mocha --timeout 20000` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 953 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 950 | `npm run mocha:istanbul` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 948 | `mocha --timeout 5000` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 948 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 946 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 940 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 923 | `mocha "client.test" --compilers js:babel-register` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 922 | `npm run convertto:es5 && npm run mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 919 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [jvalen/pixel-art-react](https://github.com/jvalen/pixel-art-react) | 918 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js 'test/**/*.@(js|jsx)'` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 917 | `mocha` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 915 | `npm-run-all test:jest test:server:mocha` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 913 | `mocha spec/*.spec.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 908 | `mocha --reporter spec --bail --check-leaks test/` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 907 | `mocha --compilers js:babel-register test/*.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 902 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 901 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 901 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 893 | `npm run lint && mocha -R spec` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 892 | `mocha -R spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 891 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 888 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 884 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 880 | `mocha tests` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 870 | `node_modules/.bin/mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 870 | `mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 866 | `mocha` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 857 | `mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 850 | `eslint test && mocha --compilers js:babel/register` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 849 | `node_modules/.bin/mocha test/spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 849 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 845 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 838 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 835 | `mocha -t 5000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 835 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 788 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 788 | `mocha --async-only` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 783 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 781 | `mocha test` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 774 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 770 | `xo && mocha -R spec` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 760 | `nyc --check-coverage mocha test/*.test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 758 | `mocha --ui tdd --require ./test/__setup` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 757 | `mocha --harmony --full-trace --check-leaks` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 757 | `mocha test` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 757 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 821 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 821 | `istanbul cover -- _mocha --reporter spec` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 819 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 815 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 813 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 811 | `mocha test --compilers js:babel-core/register` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 810 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 807 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 806 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 791 | `./node_modules/.bin/mocha --reporter spec` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 790 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 788 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 788 | `mocha --async-only` | 
| [edsu/anon](https://github.com/edsu/anon) | 782 | `mocha --colors --reporter spec test.js` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 781 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 779 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 777 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 777 | `mocha --timeout 30000 --recursive ./tests` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 776 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 774 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 771 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 783 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 782 | `mocha --colors --reporter spec test.js` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 781 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 779 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 777 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 777 | `mocha --timeout 30000 --recursive ./tests` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 776 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 774 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 771 | `mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 771 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 770 | `xo && mocha -R spec` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 766 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 762 | `npm run mocha-test test/integration` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 762 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 761 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 760 | `nyc --check-coverage mocha test/*.test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 758 | `mocha --ui tdd --require ./test/__setup` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 757 | `mocha --harmony --full-trace --check-leaks` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 757 | `mocha test` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 757 | `mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 757 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 756 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 755 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 755 | `mocha -R spec src/**/*_test.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 755 | `mocha --recursive ./test/*_spec.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 743 | `mocha test/index.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 743 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 742 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [developit/decko](https://github.com/developit/decko) | 739 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 739 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 738 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 737 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 736 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 732 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 731 | `mocha test` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 731 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 731 | `mocha --reporter spec` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 731 | `mocha test` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 730 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 728 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 