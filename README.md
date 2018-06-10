# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:47 06/10/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 42037 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40692 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38688 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29649 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24101 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23437 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 22992 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22403 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19039 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18455 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16326 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15938 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14430 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14153 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13499 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12759 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12499 | `mocha 'test/**/*.spec.js'` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 12447 | `mocha --reporter spec` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12343 | `./node_modules/.bin/mocha test/` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12153 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12104 | `mocha --reporter spec test/*-test.js` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11917 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11164 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11061 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10605 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10464 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10011 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9738 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9733 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9718 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9698 | `set NODE_ENV=test && mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9441 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8053 | `mocha tests/*.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8027 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7949 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7788 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7749 | `npm run eslint && npm run mocha` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7597 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7516 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7512 | `./node_modules/.bin/mocha test` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7440 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7340 | `npm run build && istanbul cover _mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7086 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7080 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 6897 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6893 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6892 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6832 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6785 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6726 | `mocha --compilers js:babel-core/register` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7605 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7597 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7516 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7512 | `./node_modules/.bin/mocha test` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7440 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7340 | `npm run build && istanbul cover _mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7086 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7080 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 6897 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6893 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6892 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6832 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6785 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6726 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6630 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6630 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6317 | `npm run lint -s && npm run mocha -s` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 6191 | `mocha test node-test --recursive` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6174 | `npm run jshint && mocha test/` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 6168 | `npm run build-cli && mocha` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6137 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6112 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6030 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5935 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5893 | `mocha --exit --require babel-core/register` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5850 | `mocha test/test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5848 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5733 | `mocha; jshint *.js lib` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5731 | `mocha tests/node.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5634 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5604 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5535 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5407 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5391 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5367 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5285 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5279 | `mocha --timeout 10000 && npm run lint` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5162 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5153 | `mocha --color` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5117 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4978 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4972 | `standard && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4936 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4896 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4820 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4716 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4696 | `mocha -R spec 'tests/app'` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4695 | `mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4671 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4658 | `gulp build; mocha;` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4641 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4605 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4582 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4556 | `mocha ./test/runner.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4513 | `mocha test` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4500 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4419 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4366 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4340 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4321 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4240 | `NODE_ENV=test mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4223 | `mocha --recursive && make test` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4219 | `mocha -R spec ./test --recursive` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4191 | `nyc mocha --exit` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4125 | `npm run lint && npm run mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4104 | `nyc mocha` | 
| [muicss/mui](https://github.com/muicss/mui) | 3971 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3969 | `mocha --require test/babel-hook test/*.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3954 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3935 | `mocha -R spec ./test` | 
| [tj/ejs](https://github.com/tj/ejs) | 3907 | `mocha --require should --reporter spec` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3883 | `npm run lint && npm run mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3883 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3875 | `export TESTING=true; mocha --reporter list` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3871 | `npm run lint ; mocha && mocha test/individual` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3814 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [erming/shout](https://github.com/erming/shout) | 3802 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3800 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3694 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3661 | `npm run jshint && npm run mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3621 | `mocha --check-leaks --reporter spec --bail` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3612 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3561 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3499 | `mocha --reporter spec --timeout 3000` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3498 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3484 | `node_modules/.bin/mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3499 | `mocha --reporter spec --timeout 3000` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3498 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3484 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3466 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3466 | `nyc mocha "test/**/*.test.js"` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3448 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 3447 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3441 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3431 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3425 | `mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3412 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3411 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3372 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3367 | `node_modules/.bin/mocha test/tests.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3365 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3337 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3291 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3095 | `nyc mocha && tsc` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3055 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3025 | `NODE_ENV=test mocha --exit` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3005 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2995 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2979 | `mocha test/*.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2959 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2958 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2947 | `mocha test/index.js && npm run demo` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2908 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2906 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2889 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2875 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2870 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2848 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2843 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2837 | `mocha -R spec --recursive src/test` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2626 | `mocha --timeout 100000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2589 | `mocha --recursive --watch` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2562 | `mocha -R landing test/index` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2547 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2540 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2527 | `export TESTING=true; mocha --reporter list` | 
| [mde/ejs](https://github.com/mde/ejs) | 2494 | `mocha --require should --reporter spec` | 
| [json5/json5](https://github.com/json5/json5) | 2463 | `nyc --reporter=html --reporter=text mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2424 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2420 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2419 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2418 | `mocha test` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2411 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2388 | `mocha test/src/**/*.unit.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2374 | `mocha` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2814 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2791 | `istanbul cover _mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2778 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2777 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2776 | `mocha --require should --reporter spec` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2771 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2770 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2763 | `mocha --opts mocha.opts` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2756 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2756 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2751 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2741 | `export TESTING=true; mocha --reporter list` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2739 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2736 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2725 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2704 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2701 | `npm run mocha && npm run lint` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2682 | `xo && mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2676 | `mocha --require babel-register --recursive spec` | 
| [css/csso](https://github.com/css/csso) | 2673 | `mocha --reporter dot` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2668 | `mocha` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2527 | `export TESTING=true; mocha --reporter list` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2510 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2495 | `npm run build && cd test && mocha . --reporter dot` | 
| [mde/ejs](https://github.com/mde/ejs) | 2494 | `mocha --require should --reporter spec` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2459 | `mocha --reporter=spec test/*-test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2450 | `nyc mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2424 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2420 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2419 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2418 | `mocha test` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2411 | `mocha "test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2411 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2388 | `mocha test/src/**/*.unit.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2374 | `mocha` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2258 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2256 | `mocha -R spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2246 | `nyc --reporter=html --reporter=text mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2233 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2225 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [gajus/swing](https://github.com/gajus/swing) | 2196 | `mocha --compilers js:babel-register` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2184 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2182 | `mocha test && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2167 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2159 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2126 | `mocha -R spec test/*.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2246 | `nyc --reporter=html --reporter=text mocha` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2244 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2233 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2225 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2213 | `eslint . && mocha -t 5000` | 
| [gajus/swing](https://github.com/gajus/swing) | 2196 | `mocha --compilers js:babel-register` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2184 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2182 | `mocha test && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2167 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2159 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2126 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2159 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2126 | `mocha -R spec test/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2110 | `cross-env BABEL_ENV=test mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2090 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2085 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2073 | `mocha --compilers js:babel-register` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2045 | `mocha test/index.js --reporter dot` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2042 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1544 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1525 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1517 | `mocha --reporter spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1514 | `mocha compiled_tests/` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1504 | `npm run test:lint && npm run test:mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1490 | `standard "./src/*.js" && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1479 | `mocha tests.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1474 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1468 | `nyc mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1461 | `mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1461 | `mocha` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1460 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1453 | `mocha --check-leaks --reporter spec --bail` | 
| [samccone/drool](https://github.com/samccone/drool) | 1449 | `mocha test/tests.js --timeout=10000` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1444 | `mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1439 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1438 | `nyc npm run mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1435 | `mocha test.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1431 | `mocha --recursive` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1396 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1396 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1386 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1370 | `./node_modules/mocha/bin/mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1370 | `mocha --timeout 10000 ./tests/lib.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1369 | `mocha test` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1364 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1361 | `mocha -R spec test/*.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1360 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1351 | `cross-env NODE_ENV=test nyc mocha` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1320 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1317 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1310 | `nyc mocha --timeout=20000 test.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1303 | `mocha --check-leaks --require @babel/register` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1298 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1294 | `mocha-phantomjs tests/index.html` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1291 | `./node_modules/.bin/mocha test` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1286 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1286 | `mocha --recursive` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1282 | `mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1282 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1280 | `mocha spec/exec.js` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1272 | `mocha test/unit` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1280 | `mocha spec/exec.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1273 | `mocha --opts test/opts/mocha.opts` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1272 | `mocha test/unit` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1262 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1256 | `eslint src && mocha && karma start --single-run` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1255 | `mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1254 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1250 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1243 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1242 | `mocha --timeout 60000 test/` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1240 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1239 | `mocha test/*.js` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1232 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1232 | `standard && istanbul cover _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1228 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1225 | `mocha tests` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1224 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1243 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1242 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1242 | `mocha --timeout 60000 test/` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1240 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1239 | `mocha test/*.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1236 | `mocha --reporter dot` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1235 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1232 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1232 | `standard && istanbul cover _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1228 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1225 | `mocha tests` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1224 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1224 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1222 | `mocha tests/test-*` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1215 | `mocha test/test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1214 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1211 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1207 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1202 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1207 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1202 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1197 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1194 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1190 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1189 | `node ./node_modules/mocha/bin/mocha tests` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1188 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1187 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1187 | `mocha test` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1186 | `mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1185 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1182 | `mocha src/test.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1180 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1172 | `mocha --reporter spec` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1171 | `mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1170 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1145 | `mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1142 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1139 | `mocha -R spec ./test/unit/**` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1139 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1136 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1131 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1128 | `mocha ./test/test*.js --reporter spec` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1127 | `NODE_ENV=test mocha tests/*.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1123 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1121 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1118 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1116 | `npm run prepublishOnly && mocha test/test.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1113 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1113 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1111 | `mocha --recursive test` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1061 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1058 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1054 | `istanbul test _mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1053 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1050 | `mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1050 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1048 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1048 | `mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1047 | `webpack && npm run lint && npm run mocha` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1041 | `standard && mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1040 | `mocha --reporter spec --timeout 3000` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1040 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1039 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1037 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1061 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1058 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1054 | `istanbul test _mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1053 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1050 | `mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1050 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1048 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1048 | `mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1047 | `webpack && npm run lint && npm run mocha` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1041 | `standard && mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1040 | `mocha --reporter spec --timeout 3000` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1040 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1039 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1037 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1041 | `standard && mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1040 | `mocha --reporter spec --timeout 3000` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1040 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1039 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1037 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1036 | `mocha test/tests.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1031 | `mocha --recursive --bail --reporter spec test` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1026 | `mocha` | 
| [jas/playground](https://github.com/jas/playground) | 1023 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1023 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1018 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [electron/asar](https://github.com/electron/asar) | 1016 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1014 | `webpack && mocha test/unit` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1013 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1006 | `npm run lint && mocha --require @babel/register` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1006 | `mocha` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1004 | `mocha $(find test -name '*.test.js')` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1002 | `mocha --reporter spec --bail --check-leaks test/` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1000 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 998 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 994 | `mocha --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 993 | `mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 991 | `mocha test` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 988 | `mocha --recursive test/unit/` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 987 | `standard && mocha -b` | 
| [electron/spectron](https://github.com/electron/spectron) | 986 | `mocha && standard` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 983 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 979 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 978 | `mocha --async-only` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 975 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 973 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 972 | `eslint src test && mocha --compilers babel-register` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 971 | `mocha -R list` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 970 | `npm run mocha:istanbul` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 968 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 963 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 963 | `mocha --timeout 20000` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 961 | `mocha --reporter spec` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 953 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 953 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 947 | `mocha --timeout 5000` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 941 | `mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 891 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 890 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 886 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 874 | `mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 867 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 861 | `mocha --timeout 200000` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 861 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 860 | `mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 853 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 852 | `eslint test && mocha --compilers js:babel/register` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 907 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 902 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 902 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 900 | `mocha -R spec` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 890 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 891 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 890 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 886 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 883 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 874 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 871 | `node_modules/.bin/mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 870 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 861 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 861 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 861 | `mocha --timeout 200000` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 861 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 860 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 859 | `npm run lint && npm run mocha:no-functional` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 858 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 853 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 852 | `eslint test && mocha --compilers js:babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 849 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 849 | `mocha spec/*.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 841 | `mocha` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 839 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 839 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [edsu/anon](https://github.com/edsu/anon) | 781 | `mocha --colors --reporter spec test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 779 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 775 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 773 | `mocha` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 770 | `nyc --check-coverage mocha test/*.test.js` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 770 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 769 | `xo && mocha -R spec` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 767 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 766 | `npm run mocha-test test/integration` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 766 | `mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 764 | `mocha --recursive ./test/*_spec.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 762 | `mocha --harmony --full-trace --check-leaks` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 761 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 760 | `mocha --ui tdd --require ./test/__setup` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 760 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 825 | `istanbul cover -- _mocha --reporter spec` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 823 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 822 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 822 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 820 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 815 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 814 | `npm run lint && mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 814 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 809 | `mocha --reporter spec --bail --check-leaks test/` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 808 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 705 | `mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 705 | `mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 703 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 702 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 701 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 699 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 694 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 693 | `./node_modules/.bin/mocha -t 60000` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 692 | `./bin/selenium-standalone install && mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 692 | `mocha --reporter spec build/test/index.js` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 691 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 687 | `mocha --reporter spec` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 687 | `npm run-script jshint && npm run-script mocha` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 681 | `mocha` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 696 | `babel-node node_modules/.bin/_mocha -- test` | 
| [scality/S3](https://github.com/scality/S3) | 695 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 694 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 692 | `./bin/selenium-standalone install && mocha` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 691 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 687 | `mocha --reporter spec` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 687 | `npm run-script jshint && npm run-script mocha` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 681 | `mocha ./test/test.js --timeout 1000000` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 681 | `mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 675 | `./node_modules/.bin/mocha test/**/*` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 674 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 672 | `mocha -b -R spec test/*` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 671 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 671 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 664 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 662 | `mocha --compilers js:babel-core/register` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 661 | `mocha` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 659 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 656 | `jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 662 | `mocha --compilers js:babel-core/register` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 661 | `mocha` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 660 | `npm run test-mocha && npm run test-karma` | 
| [koajs/static](https://github.com/koajs/static) | 659 | `mocha --harmony --reporter spec --exit` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 659 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 658 | `mocha --reporter spec` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 656 | `jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 655 | `./node_modules/.bin/mocha test/integration` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 654 | `mocha -R spec` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 654 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 654 | `mocha` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 653 | `mocha` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 645 | `mocha --compilers js:babel-register` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 645 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 644 | `./node_modules/.bin/mocha` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 644 | `mocha --compilers js:babel-register src/**/*.spec.js src/*.spec.js` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 643 | `./node_modules/.bin/mocha --bail` | 
| [shime/livedown](https://github.com/shime/livedown) | 639 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 635 | `mocha --reporter spec --bail --check-leaks test/` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 632 | `mocha --reporter spec` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 632 | `mocha --reporter spec` | 
| [tonyhb/redux-ui](https://github.com/tonyhb/redux-ui) | 628 | `$(npm bin)/mocha  --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 626 | `npm run lint && mocha` | 
| [manavsehgal/reactspeedcoding](https://github.com/manavsehgal/reactspeedcoding) | 625 | `NODE_ENV=test npm run elint && npm run slint && npm run test:mocha` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 624 | `mocha --require babel-register` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 623 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [robwierzbowski/generator-jekyllrb](https://github.com/robwierzbowski/generator-jekyllrb) | 623 | `mocha` | 
| [jbrooksuk/node-summary](https://github.com/jbrooksuk/node-summary) | 622 | `mocha --compilers js:babel-core/register --require should --reporter spec` | 
| [amasad/debug_utils](https://github.com/amasad/debug_utils) | 622 | `mocha ./test --bail` | 
| [danielstjules/buddy.js](https://github.com/danielstjules/buddy.js) | 609 | `mocha -R spec spec/unit spec/integration` | 
| [cgross/generator-cg-angular](https://github.com/cgross/generator-cg-angular) | 608 | `mocha` | 
| [VictorBjelkholm/autochecker](https://github.com/VictorBjelkholm/autochecker) | 607 | `mocha` | 
| [hparra/gulp-rename](https://github.com/hparra/gulp-rename) | 605 | `mocha` | 
| [maxkueng/victor](https://github.com/maxkueng/victor) | 605 | `mocha --ui bdd --reporter spec` | 
| [danawoodman/react-fontawesome](https://github.com/danawoodman/react-fontawesome) | 604 | `mocha` | 
| [phodal/sherlock](https://github.com/phodal/sherlock) | 603 | `mocha --reporter spec` | 
| [Ivshti/linvodb3](https://github.com/Ivshti/linvodb3) | 602 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [joaonuno/tree-model-js](https://github.com/joaonuno/tree-model-js) | 600 | `istanbul cover _mocha` | 
| [tj/node-blocked](https://github.com/tj/node-blocked) | 598 | `./node_modules/mocha/bin/mocha` | 
| [pillarjs/send](https://github.com/pillarjs/send) | 522 | `mocha --check-leaks --reporter spec --bail` | 
| [mixu/electroshot](https://github.com/mixu/electroshot) | 522 | `mocha -R spec --bail ./test/*.test.js` | 
| [pazguille/viewport](https://github.com/pazguille/viewport) | 519 | `npm run build && NODE_ENV=test istanbul cover _mocha -- ./test/*.spec.js` | 
| [adametry/gulp-eslint](https://github.com/adametry/gulp-eslint) | 519 | `mocha` | 
| [FGRibreau/match-when](https://github.com/FGRibreau/match-when) | 518 | `mocha {**,*/**}.test.js` | 
| [mikejihbe/metrics](https://github.com/mikejihbe/metrics) | 515 | `tsc index.d.ts && ./node_modules/.bin/mocha test/unit` | 
| [mapbox/carto](https://github.com/mapbox/carto) | 514 | `mocha -R spec --timeout 50000 -i -f jslint` | 
| [sebpiq/WebPd](https://github.com/sebpiq/WebPd) | 514 | `mocha --reporter list --recursive test/lib` | 
| [hunterloftis/throng](https://github.com/hunterloftis/throng) | 514 | `mocha` | 
| [marionettejs/backbone.syphon](https://github.com/marionettejs/backbone.syphon) | 512 | `grunt test --mocha-reporter=dot` | 
| [mateogianolio/vectorious](https://github.com/mateogianolio/vectorious) | 508 | `mocha` | 
| [bard/mozrepl](https://github.com/bard/mozrepl) | 507 | `mocha test` | 
| [nitrotasks/nitro](https://github.com/nitrotasks/nitro) | 506 | `cross-env NODE_ENV=test nyc mocha nitro.sdk.test/index.js && npm run build` | 
| [thysultan/dio.js](https://github.com/thysultan/dio.js) | 504 | `nyc mocha --harmony --recursive --require script/test` | 
| [mhart/kinesalite](https://github.com/mhart/kinesalite) | 504 | `mocha --require should --reporter spec -t $([ $REMOTE ] && echo 30s || echo 4s)` | 
| [storybook-eol/react-native-storybook](https://github.com/storybook-eol/react-native-storybook) | 502 | `mocha -r babel-register -r babel-polyfill src/**/__tests__/**/*.js` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 501 | `mocha test` | 
| [nemtsov/json-mask](https://github.com/nemtsov/json-mask) | 499 | `npm run lint && mocha` | 
| [rkusa/koa-passport](https://github.com/rkusa/koa-passport) | 561 | `mocha` | 
| [imgly/imgly-sdk-html5](https://github.com/imgly/imgly-sdk-html5) | 559 | `NODE_ENV=test node_modules/.bin/mocha --harmony --require should --require babel/register --reporter spec test/*.test.js test/**/*.test.js` | 
| [werk85/node-html-to-text](https://github.com/werk85/node-html-to-text) | 559 | `istanbul cover _mocha && eslint .` | 
| [jmar777/suspend](https://github.com/jmar777/suspend) | 558 | `node ./node_modules/mocha/bin/mocha --harmony --reporter list` | 
| [matthewmueller/socrates](https://github.com/matthewmueller/socrates) | 557 | `devtool node_modules/mocha/bin/_mocha -qc -- ./test/` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 557 | `npm -s run mocha && npm run -s lint` | 
| [merencia/node-cron](https://github.com/merencia/node-cron) | 556 | `./node_modules/mocha/bin/mocha --recursive` | 
| [GianlucaGuarini/icaro](https://github.com/GianlucaGuarini/icaro) | 554 | `npm run lint && mocha test` | 
| [paulogr/dstatuspage](https://github.com/paulogr/dstatuspage) | 549 | `standard && nyc mocha --exit` | 
| [mbasso/react-decoration](https://github.com/mbasso/react-decoration) | 547 | `cross-env BABEL_ENV=commonjs nyc --require babel-register --require ./test/setup.js mocha --recursive` | 
| [SamyPesse/gitkit-js](https://github.com/SamyPesse/gitkit-js) | 585 | `./node_modules/.bin/mocha ./testing/setup.js ./lib/**/*/__tests__/*.js --bail --reporter=list` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 585 | `mocha` | 
| [dleitee/valid.js](https://github.com/dleitee/valid.js) | 585 | `mocha --compilers js:babel-register` | 
| [teropa/redux-voting-server](https://github.com/teropa/redux-voting-server) | 584 | `mocha --compilers js:babel-core/register  --require ./test/test_helper.js  --recursive` | 
| [LouisBarranqueiro/reapop](https://github.com/LouisBarranqueiro/reapop) | 584 | `babel-node ./node_modules/karma/bin/karma start ./build/karma.conf.js --reporters mocha` | 
| [jeremyckahn/rekapi](https://github.com/jeremyckahn/rekapi) | 584 | `mocha -r jsdom-global/register ./node_modules/babel-core/register.js test/index.js` | 
| [nexus-js/ui](https://github.com/nexus-js/ui) | 584 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 583 | `_mocha -u bdd --colors test/` | 
| [jimpick/lambda-comments](https://github.com/jimpick/lambda-comments) | 583 | `mocha --compilers js:./babel-register` | 
| [docpress/docpress](https://github.com/docpress/docpress) | 583 | `nyc mocha` | 
| [jaredhanson/passport-google-oauth](https://github.com/jaredhanson/passport-google-oauth) | 583 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [macbre/analyze-css](https://github.com/macbre/analyze-css) | 582 | `mocha -R spec` | 
| [bitovi/documentjs](https://github.com/bitovi/documentjs) | 582 | `mocha test.js --reporter spec` | 
| [webdriverio/webdrivercss](https://github.com/webdriverio/webdrivercss) | 580 | `./node_modules/.bin/mocha` | 
| [esnext/esnext](https://github.com/esnext/esnext) | 580 | `mocha` | 
| [blueberryapps/react-bluekit](https://github.com/blueberryapps/react-bluekit) | 580 | `mocha --compilers js:babel/register --recursive` | 
| [zpratt/react-tdd-guide](https://github.com/zpratt/react-tdd-guide) | 579 | `npm run lint && mocha */test` | 
| [nicksp/redux-webpack-es6-boilerplate](https://github.com/nicksp/redux-webpack-es6-boilerplate) | 579 | `mocha --compilers js:babel-core/register,css:./test/unit/cssNullCompiler.js --require ./test/unit/testHelper.js --recursive ./test/unit` | 
| [bbc/VideoContext](https://github.com/bbc/VideoContext) | 579 | `node ./node_modules/mocha/bin/mocha --compilers js:babel-core/register` | 
| [aliyun-UED/aliyun-sdk-js](https://github.com/aliyun-UED/aliyun-sdk-js) | 579 | `mocha test` | 
| [jmreidy/grunt-browserify](https://github.com/jmreidy/grunt-browserify) | 578 | `mocha -R spec --timeout 5000` | 
| [formio/formio](https://github.com/formio/formio) | 577 | `npm run version && env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 577 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [mikaelbr/gulp-notify](https://github.com/mikaelbr/gulp-notify) | 577 | `mocha -R spec` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 577 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 577 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 575 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [scrollback/scrollback](https://github.com/scrollback/scrollback) | 574 | `node_modules/.bin/mocha test/test.js` | 
| [ziyasal/scientist.js](https://github.com/ziyasal/scientist.js) | 573 | `node ./node_modules/babel-cli/bin/babel-node.js ./node_modules/mocha/bin/_mocha --timeout 20000 tests/**/*.spec.js` | 
| [sindresorhus/jshint-stylish](https://github.com/sindresorhus/jshint-stylish) | 573 | `xo && mocha` | 
| [theoephraim/node-google-spreadsheet](https://github.com/theoephraim/node-google-spreadsheet) | 572 | `node_modules/.bin/mocha` | 
| [times/cardkit](https://github.com/times/cardkit) | 571 | `./node_modules/.bin/istanbul cover --dir test/coverage ./node_modules/.bin/_mocha -- --compilers js:babel-core/register --require ignore-styles` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 570 | `mocha` | 
| [edankwan/penis.js](https://github.com/edankwan/penis.js) | 570 | `mocha --ui bdd --reporter spec test/` | 
| [felixge/node-dirty](https://github.com/felixge/node-dirty) | 568 | `mocha test/test-*.js -R list` | 
| [gauntface/simple-push-demo](https://github.com/gauntface/simple-push-demo) | 568 | `gulp && npm run lint && node ./test/helpers/download-browsers.js && mocha` | 
| [dtschust/redux-bug-reporter](https://github.com/dtschust/redux-bug-reporter) | 567 | `standard && mocha --compilers js:babel-register --recursive --require test/setup.js` | 
| [Spreadsheets/WickedGrid](https://github.com/Spreadsheets/WickedGrid) | 567 | `./node_modules/.bin/mocha --reporter spec` | 
| [times/cardkit](https://github.com/times/cardkit) | 571 | `./node_modules/.bin/istanbul cover --dir test/coverage ./node_modules/.bin/_mocha -- --compilers js:babel-core/register --require ignore-styles` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 570 | `mocha` | 
| [edankwan/penis.js](https://github.com/edankwan/penis.js) | 570 | `mocha --ui bdd --reporter spec test/` | 
| [felixge/node-dirty](https://github.com/felixge/node-dirty) | 568 | `mocha test/test-*.js -R list` | 
| [gauntface/simple-push-demo](https://github.com/gauntface/simple-push-demo) | 568 | `gulp && npm run lint && node ./test/helpers/download-browsers.js && mocha` | 
| [dtschust/redux-bug-reporter](https://github.com/dtschust/redux-bug-reporter) | 567 | `standard && mocha --compilers js:babel-register --recursive --require test/setup.js` | 
| [Spreadsheets/WickedGrid](https://github.com/Spreadsheets/WickedGrid) | 567 | `./node_modules/.bin/mocha --reporter spec` | 
| [M6Web/websocket-bench](https://github.com/M6Web/websocket-bench) | 566 | `gulp mocha` | 
| [ideal-postcodes/postcodes.io](https://github.com/ideal-postcodes/postcodes.io) | 565 | `NODE_ENV=test npm run test:create && npm run mocha && NODE_ENV=test npm run test:clear && npm run lint` | 
| [jkphl/gulp-svg-sprite](https://github.com/jkphl/gulp-svg-sprite) | 565 | `gulp && istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [azproduction/autopolyfiller](https://github.com/azproduction/autopolyfiller) | 563 | `npm run lint && mocha -R spec` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 563 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [expressjs/cookie-session](https://github.com/expressjs/cookie-session) | 563 | `mocha --check-leaks --reporter spec --bail test/` | 
| [mtth/avsc](https://github.com/mtth/avsc) | 562 | `mocha` | 