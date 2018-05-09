# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:03 05/09/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 41288 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40470 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38185 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29404 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23910 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23103 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 22101 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 21992 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 18661 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18218 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16129 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15631 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14081 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14051 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13272 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12599 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12356 | `mocha 'test/**/*.spec.js'` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12173 | `./node_modules/.bin/mocha test/` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12120 | `mocha` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11977 | `mocha --reporter spec` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11977 | `mocha --reporter spec test/*-test.js` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11526 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10996 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10768 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10329 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10205 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9794 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9624 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9619 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9547 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9511 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9101 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8769 | `grunt mocha` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 8720 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8685 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 8485 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8281 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8267 | `mocha --check-leaks -R dot` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8213 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8199 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8188 | `grunt clean:test && mocha --exit` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8116 | `mocha test/src` | 
| [amark/gun](https://github.com/amark/gun) | 8011 | `mocha` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7967 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7893 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7830 | `mocha tests/*.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7699 | `npm run eslint && npm run mocha` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7538 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [dthree/cash](https://github.com/dthree/cash) | 7501 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7435 | `mocha` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7427 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7413 | `./node_modules/.bin/mocha test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7323 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7302 | `npm run build && istanbul cover _mocha` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6956 | `nyc mocha test/**/* -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6945 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6852 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 6754 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6754 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6743 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6711 | `mocha $HARMONY_OPTS` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6704 | `xo && mocha test/*.js --timeout 100000` | 
| [almende/vis](https://github.com/almende/vis) | 6590 | `mocha --compilers js:babel-core/register` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5934 | `mocha` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 5805 | `npm run build-cli && mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5782 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5765 | `mocha test --recursive` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5713 | `mocha test/test.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5651 | `mocha --exit --require babel-core/register` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5562 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5535 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5403 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5308 | `mocha; jshint *.js lib` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5275 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5248 | `mocha --timeout 10000 && npm run lint` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5160 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5152 | `mocha src/**/*Tests.js --harmony` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5112 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5562 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5535 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5445 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5403 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5308 | `mocha; jshint *.js lib` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5275 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5248 | `mocha --timeout 10000 && npm run lint` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5160 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5152 | `mocha src/**/*Tests.js --harmony` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5112 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5067 | `mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4885 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4870 | `gulp lint && mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 4862 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha ./infra/testing/auto-stub-logger.mjs` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4841 | `standard && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4794 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4731 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [santinic/how2](https://github.com/santinic/how2) | 4703 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4677 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4659 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4611 | `gulp build; mocha;` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4575 | `mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4548 | `mocha ./test/runner.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4546 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4489 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4456 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4413 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4401 | `mocha test` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4318 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4312 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4296 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4223 | `mocha -R spec ./test --recursive` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4147 | `mocha --recursive && make test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4113 | `NODE_ENV=test mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4074 | `nyc mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4056 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4022 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4016 | `npm run lint && npm run mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3976 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3961 | `mocha --require test/babel-hook test/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3889 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3881 | `nyc mocha` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3865 | `export TESTING=true; mocha --reporter list` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3864 | `mocha -R spec ./test` | 
| [tj/ejs](https://github.com/tj/ejs) | 3863 | `mocha --require should --reporter spec` | 
| [erming/shout](https://github.com/erming/shout) | 3807 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3806 | `npm run lint ; mocha && mocha test/individual` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3737 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3717 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3717 | `npm run lint && npm run mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3705 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3679 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3657 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3616 | `standard && mocha --timeout 60000 test/test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3562 | `npm run build && mocha test/*.test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3562 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3556 | `mocha tests/javascript` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3507 | `mocha --check-leaks --reporter spec --bail` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3506 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3488 | `mocha --reporter spec --timeout 3000` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3457 | `node_modules/.bin/mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3448 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3435 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3424 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3413 | `mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3370 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3358 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3351 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3338 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3324 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3310 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3304 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3244 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3125 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3106 | `mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3106 | `node_modules/.bin/mocha test/tests.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3104 | `./node_modules/.bin/mocha test/test.*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3098 | `mocha` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3088 | `NODE_ENV=test mocha test/**/*.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3075 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3056 | `mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3022 | `nyc mocha && tsc` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 3002 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2999 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2972 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2961 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2959 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2954 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2951 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2924 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2951 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2924 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2874 | `mocha test/index.js && npm run demo` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2869 | `NODE_ENV=test mocha` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2869 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2853 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2851 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2832 | `mocha` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2829 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2825 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2824 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2814 | `mocha -R spec --recursive src/test` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2805 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2805 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2796 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2776 | `istanbul cover _mocha` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2773 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2771 | `mocha --require should --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2753 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2751 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2729 | `mocha --opts mocha.opts` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2722 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2685 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2684 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2673 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2670 | `xo && mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2666 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2660 | `mocha` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2658 | `npm run mocha && npm run lint` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2657 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [css/csso](https://github.com/css/csso) | 2648 | `mocha --reporter dot` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2646 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2638 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2625 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2622 | `mocha --require babel-register --recursive spec` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2615 | `mocha --timeout 100000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2597 | `mocha-phantomjs ./test/index.html` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2569 | `mocha --recursive --watch` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2537 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2528 | `node_modules/.bin/mocha --reporter spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2528 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2512 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2490 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2478 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2463 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2456 | `mocha --reporter=spec test/*-test.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2437 | `npm run build && cd test && mocha . --reporter dot` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2422 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2414 | `mocha -R landing test/index` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2412 | `nyc mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 2402 | `mocha --require should --reporter spec` | 
| [json5/json5](https://github.com/json5/json5) | 2402 | `nyc --reporter=html --reporter=text mocha` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2380 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2371 | `mocha test/src/**/*.unit.js` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2361 | `mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2350 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2349 | `mocha "test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2349 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2340 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2339 | `grunt jshint && mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2315 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2309 | `mocha test/unit --require mochahook` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2304 | `mocha test.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2302 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2294 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2279 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2274 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2265 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2239 | `mocha test test/unit/**/*_test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2235 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2227 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2224 | `mocha -R spec` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2224 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2186 | `nyc --reporter=html --reporter=text mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2177 | `mocha --compilers js:babel-register` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2112 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2112 | `mocha test && npm run lint` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2108 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2107 | `mocha && eslint .` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2098 | `cross-env BABEL_ENV=test mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2094 | `mocha -R spec test/*.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2093 | `mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2077 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2074 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2014 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [slate/slate](https://github.com/slate/slate) | 2010 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2004 | `mocha --compilers js:babel-register` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1988 | `standard && mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 1975 | `mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1953 | `mocha -c test/index.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1948 | `mocha test/runner.js --reporter spec` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1943 | `mocha --require=test/test_helper.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1933 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1919 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1919 | `mocha test/index.js --reporter dot` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1915 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1910 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1908 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1904 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1899 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1890 | `mocha --reporter spec --timeout 5000` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1887 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1876 | `mocha --require ./test/common --growl test/expect.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1870 | `mocha --compilers js:babel-core/register __tests__` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1862 | `mocha tests.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1857 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1851 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1848 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [then/promise](https://github.com/then/promise) | 1833 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [share/sharedb](https://github.com/share/sharedb) | 1824 | `./node_modules/.bin/mocha && npm run jshint` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1822 | `mocha && eslint *.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1821 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1816 | `npm run lint && mocha -R dot && npm run cover` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1813 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [kach/nearley](https://github.com/kach/nearley) | 1812 | `mocha test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1810 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1808 | `nyc npm run _mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1801 | `mocha --timeout 5000` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1796 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1785 | `mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1775 | `mocha test` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1775 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1771 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1770 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1758 | `npm run lint && mocha --reporter spec test/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1755 | `mocha --reporter spec && npm run test-typescript` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1750 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1746 | `mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1745 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1743 | `mocha -R spec spec spec/reporters` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1741 | `mocha test` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1740 | `npm run mocha && npm run karma` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1736 | `mocha test/**/*_test.js --bail` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1725 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 1725 | `mocha --compilers js:babel-core/register './specs/**/*.spec.js'` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1717 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1713 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [pahen/madge](https://github.com/pahen/madge) | 1700 | `npm run lint && npm run mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1700 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1692 | `npm run jshint && mocha --recursive` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1691 | `npm run lint && npm run mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1687 | `./node_modules/.bin/mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1687 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1685 | `mocha && npm run lint` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1630 | `mocha test/**/*.js` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1617 | `mocha tests/test.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1610 | `npm run lint && mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1609 | `mocha test --timeout 600000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1609 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1604 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1599 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1585 | `mocha spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1584 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1583 | `mocha test/* --reporter spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1564 | `npm run lint && npm run mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1563 | `mocha --compilers js:babel-register` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1599 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1585 | `mocha spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1584 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1583 | `mocha test/* --reporter spec` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1571 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1564 | `npm run lint && npm run mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1563 | `mocha --compilers js:babel-register` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1535 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1535 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1521 | `./node_modules/mocha/bin/mocha -R spec` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1515 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1513 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1511 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1508 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1507 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1498 | `mocha --reporter spec` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1494 | `npm run test:lint && npm run test:mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1450 | `mocha test/**/*.spec.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1448 | `mocha tests.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1447 | `mocha test/tests.js --timeout=10000` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1446 | `nyc mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1443 | `standard "./src/*.js" && mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1443 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1439 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [AlloyTeam/omi](https://github.com/AlloyTeam/omi) | 1437 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1428 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1420 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1419 | `mocha test/setup.js test/spec/*.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1415 | `mocha test.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1412 | `mocha --check-leaks --reporter spec --bail` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1406 | `mocha --recursive` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1401 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1420 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1419 | `mocha test/setup.js test/spec/*.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1415 | `mocha test.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1412 | `mocha --check-leaks --reporter spec --bail` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1406 | `mocha --recursive` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1392 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1392 | `nyc npm run mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1389 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1389 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1376 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1360 | `./node_modules/mocha/bin/mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1344 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1342 | `cross-env NODE_ENV=test nyc mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1339 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1339 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1333 | `mocha -R spec test/*.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1291 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1291 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1283 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1278 | `./node_modules/.bin/mocha test` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1272 | `mocha test` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1272 | `mocha spec/exec.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1266 | `mocha --check-leaks --require @babel/register` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1265 | `istanbul cover _mocha test -- --timeout 20000` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1265 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1264 | `mocha --recursive` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1263 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1260 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1247 | `mocha --opts test/opts/mocha.opts` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1235 | `mocha test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1234 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1233 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1232 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1227 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1225 | `mocha tests` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1225 | `mocha test/unit` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1221 | `nyc mocha --timeout=20000 test.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1216 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1215 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1212 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1210 | `mocha test/test.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1210 | `eslint src && mocha && karma start --single-run` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1209 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1207 | `standard && istanbul cover _mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1206 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1205 | `mocha` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1198 | `mocha test/**/*Spec.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1196 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1196 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1195 | `mocha --reporter dot` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1193 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1192 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1185 | `node ./node_modules/mocha/bin/mocha tests` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1181 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1179 | `mocha test` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1175 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1171 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1169 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1162 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1160 | `mocha tests/test-*` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1158 | `mocha src/test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1157 | `mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1154 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1153 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1152 | `mocha --reporter spec` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1147 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [variety/variety](https://github.com/variety/variety) | 1147 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1160 | `mocha tests/test-*` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1158 | `mocha src/test.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1157 | `mocha` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1154 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1153 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1152 | `mocha --reporter spec` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1147 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [variety/variety](https://github.com/variety/variety) | 1147 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1140 | `npm run lint && npm run mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1138 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1131 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1131 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1128 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1122 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1120 | `mocha --check-leaks --reporter spec --bail test/` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1118 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1115 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1108 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1103 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1101 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1098 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1095 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1091 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1087 | `mocha -R spec ./test/unit/**` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1086 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1085 | `mocha $(find test -name '*.test.js')` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1085 | `xo && mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1082 | `mocha test/*` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1080 | `npm run prepublishOnly && mocha test/test.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1077 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1077 | `nodeunit test; mocha test` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1076 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1071 | `mocha --check-leaks -t 20000` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1070 | `mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1070 | `mocha --compilers js:babel-register` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1069 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1069 | `NODE_PATH=. mocha **/*.spec.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1065 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1064 | `istanbul cover _mocha test/*.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1061 | `mocha --recursive test` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1053 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1052 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1050 | `mocha ./test/test*.js --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1044 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1043 | `mocha tests/*.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1040 | `istanbul test _mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1040 | `mocha --reporter spec --timeout 3000` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1039 | `npm run lint && npm run mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1031 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1029 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1029 | `mocha test/tests.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1027 | `mocha --compilers js:babel-core/register` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1027 | `mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1025 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1022 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [jas/playground](https://github.com/jas/playground) | 1022 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1021 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1020 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1019 | `TEST=all mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1015 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1001 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 997 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 997 | `mocha --colors ./test/*.spec.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 994 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 992 | `mocha $(find test -name '*.test.js')` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 991 | `webpack && mocha test/unit` | 
| [electron/asar](https://github.com/electron/asar) | 988 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 980 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 980 | `mocha -t 120000 test/*.test.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 979 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 976 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 976 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [tomas/needle](https://github.com/tomas/needle) | 975 | `mocha test` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 974 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 970 | `standard && mocha -b` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 979 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 976 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 976 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 975 | `mocha --recursive test/unit/` | 
| [tomas/needle](https://github.com/tomas/needle) | 975 | `mocha test` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 974 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 970 | `mocha --async-only` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 970 | `standard && mocha -b` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 968 | `mocha --reporter spec --bail --check-leaks test/` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 967 | `mocha -R list` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 967 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 960 | `mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 958 | `mocha --reporter spec` | 
| [electron/spectron](https://github.com/electron/spectron) | 954 | `mocha && standard` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 954 | `eslint src test && mocha --compilers babel-register` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 954 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 951 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 950 | `npm run lint && mocha --require @babel/register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 949 | `mocha --timeout 5000` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 933 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 931 | `mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 929 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 884 | `mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 882 | `npm run lint && mocha -R spec` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 881 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 874 | `mocha -R spec` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 870 | `mocha --reporter list` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 867 | `mocha` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 865 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 864 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 864 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 862 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 861 | `node_modules/.bin/mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 859 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 855 | `npm run lint && npm run mocha && npm run cov` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 852 | `mocha --timeout 200000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 852 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 851 | `mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 849 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 848 | `node_modules/.bin/mocha test/spec` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 846 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 846 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 844 | `eslint test && mocha --compilers js:babel/register` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 841 | `mocha -t 600000` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 827 | `mocha` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 825 | `mocha --reporter spec` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 825 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 825 | `mocha -t 5000` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 825 | `mocha --check-leaks -t 20000` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 824 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 824 | `istanbul cover _mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 824 | `standard && standard ./bin/* && mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 822 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 821 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 819 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 816 | `nyc mocha specs` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 814 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 814 | `mocha test --compilers js:babel-register` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 816 | `nyc mocha specs` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 814 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 814 | `mocha test --compilers js:babel-register` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 813 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 812 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 811 | `mocha spec/*.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 809 | `istanbul cover -- _mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 808 | `./node_modules/.bin/mocha -R spec` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 806 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 801 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 801 | `mocha --require babel-register` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 798 | `mocha --reporter spec --bail --check-leaks test/` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 794 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 794 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 793 | `mocha --reporter list` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 790 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 790 | `cake build && mocha ./test/mocha/*.coffee` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 790 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 782 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [edsu/anon](https://github.com/edsu/anon) | 781 | `mocha --colors --reporter spec test.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 781 | `mocha --async-only` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 781 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 779 | `mocha` | 
| [radi-js/radi](https://github.com/radi-js/radi) | 778 | `nyc mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 776 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 773 | `npm run lint && mocha` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 773 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 771 | `xo && mocha -R spec` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 770 | `mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 770 | `mocha test --compilers js:babel-core/register` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 770 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 766 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 756 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 756 | `./node_modules/.bin/mocha --reporter spec` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 754 | `mocha --ui tdd --require ./test/__setup` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 754 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 754 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 753 | `mocha -R spec src/**/*_test.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 751 | `npm run mocha-test test/integration` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 751 | `mocha test` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 749 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 747 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 746 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 744 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 741 | `mocha --harmony --full-trace --check-leaks` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 741 | `mocha test` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 739 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 739 | `npm run build && istanbul test _mocha test/test.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 747 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 746 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 744 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 741 | `mocha --harmony --full-trace --check-leaks` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 741 | `mocha test` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 739 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 739 | `mocha --recursive -s 15 test/` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 739 | `npm run build && istanbul test _mocha test/test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 737 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 737 | `mocha` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 736 | `mocha` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 735 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [developit/decko](https://github.com/developit/decko) | 734 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 734 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 733 | `nyc --check-coverage mocha test/*.test.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 733 | `mocha` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 731 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 730 | `mocha --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 729 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 729 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 729 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 729 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 726 | `mocha test/index.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 725 | `mocha --recursive ./test/*_spec.js` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 725 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 724 | `mocha test` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 722 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 721 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 721 | `mocha test` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 720 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 719 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 716 | `mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 715 | `mocha tests/*.mocha.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 703 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 702 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 696 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 696 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 694 | `mocha ./test/index.js` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 693 | `mocha -r should --reporter spec test/*.js` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 692 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 692 | `./node_modules/.bin/mocha -t 60000` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 681 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 681 | `./bin/selenium-standalone install && mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 681 | `mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 680 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 679 | `npm run lint && mocha test` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 677 | `mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 676 | `mocha --reporter spec build/test/index.js` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 675 | `mocha ./test/test.js --timeout 1000000` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 674 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [scality/S3](https://github.com/scality/S3) | 673 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 673 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 671 | `mocha -b -R spec test/*` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 671 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 670 | `npm run-script jshint && npm run-script mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 669 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 669 | `./node_modules/.bin/mocha test/**/*` | 