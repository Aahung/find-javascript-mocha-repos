# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:02 05/10/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 41307 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40473 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38197 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29407 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23914 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23114 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 22126 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22007 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 18686 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18229 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16132 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15641 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14094 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14056 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13285 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12610 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12356 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12175 | `./node_modules/.bin/mocha test/` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12121 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11985 | `mocha --reporter spec test/*-test.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11984 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11537 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11003 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10783 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10340 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10212 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9801 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9627 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9624 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9554 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9516 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9104 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8774 | `grunt mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 8724 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8689 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 8492 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8284 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8268 | `mocha --check-leaks -R dot` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8217 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8213 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8190 | `grunt clean:test && mocha --exit` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8121 | `mocha test/src` | 
| [amark/gun](https://github.com/amark/gun) | 8018 | `mocha` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7969 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7894 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7835 | `mocha tests/*.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7702 | `npm run eslint && npm run mocha` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7543 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [dthree/cash](https://github.com/dthree/cash) | 7501 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7435 | `mocha` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7433 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7417 | `./node_modules/.bin/mocha test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7331 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7306 | `npm run build && istanbul cover _mocha` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6969 | `nyc mocha test/**/* -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6952 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6866 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 6763 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6761 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6744 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6713 | `mocha $HARMONY_OPTS` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6707 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 6597 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6438 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6215 | `npm run lint -s && npm run mocha -s` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6070 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6057 | `npm run jshint && mocha test/` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6049 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6020 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5934 | `mocha` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 5820 | `npm run build-cli && mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5786 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5766 | `mocha test --recursive` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5717 | `mocha test/test.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5671 | `mocha tests/node.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5657 | `mocha --exit --require babel-core/register` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5563 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5538 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5447 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5403 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5330 | `mocha; jshint *.js lib` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5277 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5248 | `mocha --timeout 10000 && npm run lint` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5160 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5153 | `mocha src/**/*Tests.js --harmony` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5119 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5083 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 4889 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4887 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4871 | `gulp lint && mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4848 | `standard && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4795 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4736 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [santinic/how2](https://github.com/santinic/how2) | 4704 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4678 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4659 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4611 | `gulp build; mocha;` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4581 | `mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4548 | `mocha ./test/runner.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4546 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4494 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4457 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4413 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4404 | `mocha test` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4321 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4314 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4297 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4221 | `mocha -R spec ./test --recursive` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4147 | `mocha --recursive && make test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4118 | `NODE_ENV=test mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4074 | `nyc mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4062 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4041 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4020 | `npm run lint && npm run mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3981 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3960 | `mocha --require test/babel-hook test/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3889 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3886 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3865 | `mocha -R spec ./test` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3864 | `export TESTING=true; mocha --reporter list` | 
| [tj/ejs](https://github.com/tj/ejs) | 3864 | `mocha --require should --reporter spec` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3807 | `npm run lint ; mocha && mocha test/individual` | 
| [erming/shout](https://github.com/erming/shout) | 3807 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3738 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3725 | `npm run lint && npm run mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3718 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3708 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3680 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3658 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3617 | `standard && mocha --timeout 60000 test/test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3563 | `npm run build && mocha test/*.test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3562 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3556 | `mocha tests/javascript` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3515 | `mocha --check-leaks --reporter spec --bail` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3507 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3487 | `mocha --reporter spec --timeout 3000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3458 | `node_modules/.bin/mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3447 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3363 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3355 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3340 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3326 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3310 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3305 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3259 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3146 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3106 | `node_modules/.bin/mocha test/tests.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3194 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3146 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3107 | `mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3106 | `node_modules/.bin/mocha test/tests.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3104 | `./node_modules/.bin/mocha test/test.*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3099 | `mocha` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3092 | `NODE_ENV=test mocha test/**/*.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3079 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3058 | `mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3026 | `nyc mocha && tsc` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 3007 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2999 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2973 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2968 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2966 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2958 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2951 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2924 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2890 | `mocha test/index.js && npm run demo` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2874 | `NODE_ENV=test mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2872 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2854 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2854 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2833 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2833 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2826 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2824 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2815 | `mocha -R spec --recursive src/test` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2809 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2807 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2796 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2777 | `istanbul cover _mocha` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2775 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2771 | `mocha --require should --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2753 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2751 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2731 | `mocha --opts mocha.opts` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2723 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2687 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2685 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2678 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2671 | `xo && mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2671 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2664 | `mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2659 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2658 | `npm run mocha && npm run lint` | 
| [css/csso](https://github.com/css/csso) | 2648 | `mocha --reporter dot` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2646 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2640 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2626 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2622 | `mocha --require babel-register --recursive spec` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2615 | `mocha --timeout 100000` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2463 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2456 | `mocha --reporter=spec test/*-test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2441 | `npm run build && cd test && mocha . --reporter dot` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2423 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2420 | `mocha -R landing test/index` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2412 | `nyc mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2406 | `mocha --require should --reporter spec` | 
| [json5/json5](https://github.com/json5/json5) | 2403 | `nyc --reporter=html --reporter=text mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2371 | `mocha test/src/**/*.unit.js` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2361 | `mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2353 | `mocha "test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2351 | `mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2350 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2341 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2338 | `grunt jshint && mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2311 | `mocha test/unit --require mochahook` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2307 | `mocha test.js` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2239 | `mocha test test/unit/**/*_test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2235 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2228 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2226 | `mocha -R spec` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2224 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2191 | `nyc --reporter=html --reporter=text mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2177 | `mocha --compilers js:babel-register` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2302 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2299 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2279 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2274 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2265 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2239 | `mocha test test/unit/**/*_test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2235 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2228 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2226 | `mocha -R spec` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2224 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2191 | `nyc --reporter=html --reporter=text mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2177 | `mocha --compilers js:babel-register` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2097 | `cross-env BABEL_ENV=test mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2094 | `mocha -R spec test/*.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2092 | `mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2077 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2075 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2016 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [slate/slate](https://github.com/slate/slate) | 2010 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2005 | `mocha --compilers js:babel-register` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1988 | `standard && mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 1978 | `mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1970 | `eslint . && mocha -t 5000` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1907 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1904 | `mocha test/ --no-timeouts` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1904 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1876 | `mocha --require ./test/common --growl test/expect.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1871 | `mocha --compilers js:babel-core/register __tests__` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1863 | `mocha tests.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1857 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1854 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1848 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [then/promise](https://github.com/then/promise) | 1832 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1827 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [share/sharedb](https://github.com/share/sharedb) | 1825 | `./node_modules/.bin/mocha && npm run jshint` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1824 | `mocha && eslint *.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1817 | `npm run lint && mocha -R dot && npm run cover` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [kach/nearley](https://github.com/kach/nearley) | 1814 | `mocha test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1810 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1807 | `nyc npm run _mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1801 | `mocha --timeout 5000` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1797 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1789 | `mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1775 | `mocha test` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1775 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1772 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1772 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1759 | `npm run lint && mocha --reporter spec test/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1756 | `mocha --reporter spec && npm run test-typescript` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1750 | `mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1750 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1747 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1744 | `mocha -R spec spec spec/reporters` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1741 | `mocha test` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1740 | `npm run mocha && npm run karma` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1736 | `mocha test/**/*_test.js --bail` | 
| [teambit/bit](https://github.com/teambit/bit) | 1734 | `mocha --compilers js:babel-core/register './specs/**/*.spec.js'` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1725 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1717 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1713 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [pahen/madge](https://github.com/pahen/madge) | 1702 | `npm run lint && npm run mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1700 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1692 | `npm run jshint && mocha --recursive` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1691 | `npm run lint && npm run mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1688 | `./node_modules/.bin/mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1687 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1686 | `standard "src/*.js" && npm run build && mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1686 | `mocha && npm run lint` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1683 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1675 | `mocha --reporter spec --grep .` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1674 | `xo && mocha` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1671 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1667 | `mocha tests --compilers js:babel-core/register` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1662 | `mocha --reporter spec test/*.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1659 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1634 | `mocha test -u bdd -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1631 | `mocha test/**/*.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1628 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1624 | `mocha --expose-gc --slow 300` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1624 | `mocha test/*.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1624 | `mocha ./test/basic.js -t 5000` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1624 | `npm run lint && mocha` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1618 | `mocha tests/test.js` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1612 | `mocha test --timeout 600000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1611 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1606 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1603 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1599 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1587 | `mocha spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1584 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1583 | `mocha test/* --reporter spec` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1575 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1564 | `mocha --compilers js:babel-register` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1564 | `npm run lint && npm run mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1536 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1521 | `./node_modules/mocha/bin/mocha -R spec` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1516 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1514 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1511 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1510 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1508 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1498 | `mocha --reporter spec` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1495 | `npm run test:lint && npm run test:mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1463 | `node_modules/.bin/mocha --recursive` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1456 | `mocha --check-leaks -R dot` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1454 | `mocha compiled_tests/` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1452 | `mocha test/**/*.spec.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1449 | `mocha tests.js` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1447 | `nyc mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1447 | `mocha test/tests.js --timeout=10000` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1446 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1445 | `standard "./src/*.js" && mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1440 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [AlloyTeam/omi](https://github.com/AlloyTeam/omi) | 1438 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1429 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1422 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1420 | `mocha test/setup.js test/spec/*.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1415 | `mocha test.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1414 | `mocha --check-leaks --reporter spec --bail` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1360 | `./node_modules/mocha/bin/mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1344 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1343 | `cross-env NODE_ENV=test nyc mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1340 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1339 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1333 | `mocha -R spec test/*.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1325 | `mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1299 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1298 | `mocha-phantomjs tests/index.html` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1376 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1360 | `./node_modules/mocha/bin/mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1344 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1343 | `cross-env NODE_ENV=test nyc mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1340 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1339 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1333 | `mocha -R spec test/*.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1325 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1319 | `npm run build && mocha -r should` | 
| [electron/devtron](https://github.com/electron/devtron) | 1299 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1298 | `mocha-phantomjs tests/index.html` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1297 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1293 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1291 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1284 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1280 | `./node_modules/.bin/mocha test` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1277 | `mocha test` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1273 | `mocha spec/exec.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1267 | `mocha --check-leaks --require @babel/register` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1267 | `istanbul cover _mocha test -- --timeout 20000` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1265 | `mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1265 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1264 | `mocha --recursive` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1259 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1248 | `mocha --opts test/opts/mocha.opts` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1235 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1235 | `mocha test/*.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1234 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1234 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1232 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1228 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1227 | `mocha test/unit` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1227 | `nyc mocha --timeout=20000 test.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1225 | `mocha tests` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1218 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1215 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1212 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1211 | `mocha test/test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1210 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1210 | `eslint src && mocha && karma start --single-run` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1209 | `standard && istanbul cover _mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1206 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1205 | `mocha` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1199 | `mocha test/**/*Spec.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1198 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1198 | `mocha --reporter dot` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1196 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1194 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1194 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1189 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1189 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1186 | `node ./node_modules/mocha/bin/mocha tests` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1181 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1180 | `mocha test` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1176 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1171 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1169 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1162 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1161 | `mocha tests/test-*` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1160 | `mocha src/test.js` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1157 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1157 | `mocha` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1154 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1153 | `mocha --reporter spec` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1150 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [variety/variety](https://github.com/variety/variety) | 1148 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1131 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1128 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1123 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1122 | `mocha --check-leaks --reporter spec --bail test/` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1120 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1118 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1109 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1104 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1102 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1098 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1096 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1094 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1102 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1098 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1096 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1094 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1093 | `node_modules/.bin/mocha && npm run lint` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1088 | `mocha -R spec ./test/unit/**` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1086 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1084 | `mocha $(find test -name '*.test.js')` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1084 | `xo && mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1081 | `npm run prepublishOnly && mocha test/test.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1081 | `mocha test/*` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1077 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1076 | `nodeunit test; mocha test` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1076 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1073 | `mocha` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1072 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1070 | `mocha --compilers js:babel-register` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1069 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1069 | `NODE_PATH=. mocha **/*.spec.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1067 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1064 | `istanbul cover _mocha test/*.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1064 | `mocha --recursive test` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1055 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1054 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1053 | `mocha ./test/test*.js --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1045 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1044 | `mocha tests/*.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1040 | `istanbul test _mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1040 | `mocha --reporter spec --timeout 3000` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1039 | `npm run lint && npm run mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1022 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1022 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [jas/playground](https://github.com/jas/playground) | 1022 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1022 | `TEST=all mocha` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1022 | `mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1016 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1015 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1013 | `mocha --check-leaks -R dot` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1011 | `webpack && npm run lint && npm run mocha` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1008 | `mocha --recursive --bail --reporter spec test` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1008 | `standard && mocha` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1005 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1002 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 997 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 997 | `mocha --colors ./test/*.spec.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 996 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 994 | `mocha $(find test -name '*.test.js')` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 991 | `webpack && mocha test/unit` | 
| [electron/asar](https://github.com/electron/asar) | 989 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 988 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1002 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 997 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 997 | `mocha --colors ./test/*.spec.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 996 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 994 | `mocha $(find test -name '*.test.js')` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 991 | `webpack && mocha test/unit` | 
| [electron/asar](https://github.com/electron/asar) | 989 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 988 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 981 | `mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 980 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 980 | `mocha -t 120000 test/*.test.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 978 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 977 | `mocha --reporter spec --bail --check-leaks test/` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 975 | `mocha --recursive test/unit/` | 
| [tomas/needle](https://github.com/tomas/needle) | 975 | `mocha test` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 974 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 971 | `standard && mocha -b` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 970 | `mocha --async-only` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 970 | `mocha --reporter spec --bail --check-leaks test/` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 969 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 967 | `mocha -R list` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 961 | `mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 958 | `mocha --reporter spec` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 955 | `eslint src test && mocha --compilers babel-register` | 
| [electron/spectron](https://github.com/electron/spectron) | 954 | `mocha && standard` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 954 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 951 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 950 | `npm run lint && mocha --require @babel/register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 949 | `mocha --timeout 5000` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 933 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 932 | `mocha` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 929 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 929 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 924 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 911 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 911 | `mocha "client.test" --compilers js:babel-register` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 910 | `mocha --timeout 20000` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 909 | `mocha ./test -R spec` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 908 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 907 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 905 | `npm run convertto:es5 && npm run mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 900 | `mocha --compilers js:babel-register test/*.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 896 | `mocha --reporter spec --bail --check-leaks test/` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 896 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 896 | `npm-run-all test:jest test:server:mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 892 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 891 | `npm run mocha:istanbul` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 891 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 884 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 884 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 882 | `npm run lint && mocha -R spec` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 875 | `mocha -R spec` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 870 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 870 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 867 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 864 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 864 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 862 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 861 | `node_modules/.bin/mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 859 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 856 | `npm run lint && npm run mocha && npm run cov` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 852 | `mocha --timeout 200000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 852 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 851 | `mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 850 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 848 | `node_modules/.bin/mocha test/spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 847 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 846 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 844 | `eslint test && mocha --compilers js:babel/register` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 843 | `mocha -t 600000` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 839 | `mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 837 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 827 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 827 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 827 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 826 | `mocha -t 5000` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 825 | `mocha --reporter spec` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 825 | `standard && standard ./bin/* && mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 825 | `mocha --check-leaks -t 20000` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 824 | `istanbul cover _mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 823 | `mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 822 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 820 | `mocha && ember test` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 819 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 816 | `nyc mocha specs` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 815 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 815 | `mocha test --compilers js:babel-register` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 812 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 812 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 811 | `mocha spec/*.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 810 | `istanbul cover -- _mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 809 | `./node_modules/.bin/mocha -R spec` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 806 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 798 | `mocha --reporter spec --bail --check-leaks test/` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 794 | `mocha --reporter list` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 794 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 794 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 791 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 790 | `cake build && mocha ./test/mocha/*.coffee` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 783 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [edsu/anon](https://github.com/edsu/anon) | 781 | `mocha --colors --reporter spec test.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 781 | `mocha --async-only` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 781 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 779 | `mocha` | 
| [radi-js/radi](https://github.com/radi-js/radi) | 778 | `nyc mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 776 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 773 | `npm run lint && mocha` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 773 | `mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 772 | `mocha test --compilers js:babel-core/register` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 771 | `xo && mocha -R spec` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 770 | `mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 770 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 750 | `npm run mocha-test test/integration` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 747 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 746 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 745 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 741 | `mocha --recursive -s 15 test/` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 741 | `mocha --harmony --full-trace --check-leaks` | 
| [jvalen/pixel-art-react](https://github.com/jvalen/pixel-art-react) | 740 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js 'test/**/*.@(js|jsx)'` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 740 | `npm run build && istanbul test _mocha test/test.js` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 739 | `mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 738 | `nyc --check-coverage mocha test/*.test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 738 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 736 | `mocha` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 735 | `mocha` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 735 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 734 | `mocha test/index.js` | 
| [developit/decko](https://github.com/developit/decko) | 734 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 750 | `npm run mocha-test test/integration` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 747 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 746 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 745 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 743 | `mocha test` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 741 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 741 | `mocha --recursive -s 15 test/` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 741 | `mocha --harmony --full-trace --check-leaks` | 
| [jvalen/pixel-art-react](https://github.com/jvalen/pixel-art-react) | 740 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js 'test/**/*.@(js|jsx)'` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 740 | `npm run build && istanbul test _mocha test/test.js` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 739 | `mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 738 | `nyc --check-coverage mocha test/*.test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 738 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 736 | `mocha` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 735 | `mocha` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 735 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 734 | `mocha test/index.js` | 
| [developit/decko](https://github.com/developit/decko) | 734 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 734 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 720 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 717 | `mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 715 | `mocha tests/*.mocha.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 715 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [typicode/katon](https://github.com/typicode/katon) | 712 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 711 | `npm run bundle && mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 711 | `mocha --no-timeouts` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 709 | `npm run lint && npm run mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 708 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 707 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 703 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 702 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 683 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 683 | `mocha --reporter spec` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 682 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 682 | `mocha` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 681 | `./bin/selenium-standalone install && mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 680 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 679 | `babel-node node_modules/.bin/_mocha -- test` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 679 | `npm run lint && mocha test` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 676 | `mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 676 | `mocha --reporter spec build/test/index.js` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 676 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 675 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 675 | `mocha ./test/test.js --timeout 1000000` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 671 | `mocha -b -R spec test/*` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 670 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 