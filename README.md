# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:29 01/15/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44890 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41966 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41924 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30808 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 25721 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25503 | `nyc mocha --timeout=10000 --exit` | 
| [caolan/async](https://github.com/caolan/async) | 25137 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24904 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21280 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20035 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18355 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17919 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17738 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17077 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15111 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14854 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14668 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13891 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12981 | `mocha 'test/**/*.spec.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12906 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12734 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12728 | `istanbul cover _mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12356 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12353 | `mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12299 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12221 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11422 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11077 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11003 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10831 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10735 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10563 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10403 | `mocha --harmony` | 
| [websockets/ws](https://github.com/websockets/ws) | 10364 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9702 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9687 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9661 | `mocha tests/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 9469 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9417 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9352 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9276 | `grunt mocha` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8867 | `mocha test/src` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8790 | `mocha --opts mocha.opts` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8677 | `mocha test/test.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8626 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8552 | `mocha --check-leaks -R dot` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8545 | `mocha --compilers js:babel-register test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8442 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8346 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8241 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8081 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8035 | `npm run eslint && npm run mocha` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7999 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7985 | `./node_modules/.bin/mocha test` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7862 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7832 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7825 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7667 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7583 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7583 | `npm run build && istanbul cover _mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7486 | `mocha --compilers js:babel-core/register` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7457 | `mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7435 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7419 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7388 | `mocha --exit --require @babel/register` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7124 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7102 | `mocha $HARMONY_OPTS` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7016 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6977 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6792 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6755 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6537 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6383 | `npm run test:mocha:src` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6257 | `mocha tests/node.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6240 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6195 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6170 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6166 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6090 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6079 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5933 | `mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5930 | `standard && mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 5293 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5232 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5209 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5135 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5116 | `gulp lint && mocha` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 5018 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5014 | `mocha --recursive` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4959 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4934 | `gulp build; mocha;` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4912 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4896 | `nyc mocha --exit` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4859 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4848 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4840 | `mocha test` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4838 | `npm run lint && npm run mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4821 | `mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4777 | `nyc mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4744 | `mocha --reporter spec -t 8000` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5232 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5209 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5135 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5116 | `gulp lint && mocha` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 5018 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5014 | `mocha --recursive` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4959 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4934 | `gulp build; mocha;` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4912 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4896 | `nyc mocha --exit` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4880 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4865 | `./node_modules/.bin/mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4859 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4848 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4840 | `mocha test` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4838 | `npm run lint && npm run mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4821 | `mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4777 | `nyc mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4744 | `mocha --reporter spec -t 8000` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4580 | `mocha ./test/runner.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4575 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4540 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4537 | `mocha -R spec src` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4476 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4408 | `mocha --timeout=15000 tests/*.test.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4371 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4339 | `node_modules/.bin/mocha test/tests.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4338 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4315 | `mocha --check-leaks --reporter spec --bail` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4290 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4276 | `NODE_ENV=test mocha --exit` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4257 | `npm run lint ; mocha && mocha test/individual` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4232 | `nyc mocha` | 
| [muicss/mui](https://github.com/muicss/mui) | 4130 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4105 | `mocha --require test/babel-hook test/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4088 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4081 | `mocha --require should --reporter spec` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4030 | `nyc mocha "test/**/*.test.js"` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3967 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [expressjs/session](https://github.com/expressjs/session) | 3953 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3930 | `export TESTING=true; mocha --reporter list` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3904 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3864 | `NODE_ENV=test mocha test/**/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3859 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3821 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3805 | `npm run build && mocha test/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3795 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3742 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3725 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3707 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3702 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3702 | `mocha && tsc -p ./test/types` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3655 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3646 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3642 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3634 | `eslint . && mocha -t 5000` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3605 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3589 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3583 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3568 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3561 | `npm run mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3559 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3517 | `nyc mocha && tsc` | 
| [tensorspace-team/tensorspace](https://github.com/tensorspace-team/tensorspace) | 3508 | `mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3488 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3450 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3431 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3424 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3450 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3431 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3424 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3419 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3400 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3390 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3372 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3369 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 3343 | `npm run build && cd test && mocha . --reporter dot` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3336 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3328 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3328 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3321 | `mocha -R landing test/index --exit` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3298 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3278 | `mocha test/index.js && npm run demo` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2622 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2589 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2551 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2533 | `mocha test --exit && npm run lint` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2530 | `mocha test/src/**/*.unit.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2525 | `nyc --reporter=html --reporter=text mocha` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2518 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2514 | `mocha --reporter=spec test/*-test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2493 | `mocha && eslint .` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2481 | `mocha test/index.js --reporter dot` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2475 | `TEST=all mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2449 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2441 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2441 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2440 | `mocha -R spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2872 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2858 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2843 | `istanbul cover _mocha` | 
| [css/csso](https://github.com/css/csso) | 2810 | `mocha --reporter dot` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2805 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2786 | `mocha --require should --reporter spec` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2783 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2762 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [retejs/rete](https://github.com/retejs/rete) | 2757 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2755 | `xo && mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2739 | `mocha "./test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2733 | `mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2702 | `nyc mocha --timeout=10000` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2872 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2858 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2843 | `istanbul cover _mocha` | 
| [css/csso](https://github.com/css/csso) | 2810 | `mocha --reporter dot` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2805 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2786 | `mocha --require should --reporter spec` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2783 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2762 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [retejs/rete](https://github.com/retejs/rete) | 2757 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2755 | `xo && mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2744 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2739 | `mocha "./test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2733 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2706 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2702 | `nyc mocha --timeout=10000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2689 | `nyc mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2686 | `mocha --timeout 100000` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2659 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2654 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2637 | `mocha-phantomjs ./test/index.html` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2622 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2589 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2580 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2198 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2183 | `mocha && eslint *.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2183 | `cross-env BABEL_ENV=test mocha` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2176 | `mocha test/**/*.coffee` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2172 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2166 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2145 | `mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 2138 | `./node_modules/.bin/mocha && npm run jshint` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2138 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2128 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2123 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2116 | `mocha --compilers js:babel-register` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2404 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2400 | `nyc --require babel-register npm run _mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2394 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2381 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2379 | `grunt jshint && mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2379 | `npm run build && mocha --require babel-register` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2331 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2319 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2305 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [gajus/swing](https://github.com/gajus/swing) | 2305 | `mocha --compilers js:babel-register` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2243 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2239 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2231 | `standard && mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2198 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2183 | `mocha && eslint *.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2179 | `mocha test/runner.js --reporter spec` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2176 | `mocha test/**/*.coffee` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2172 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2166 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2145 | `mocha` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2166 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2145 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2138 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2128 | `mocha --compilers js:babel-core/register __tests__` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2116 | `mocha --compilers js:babel-register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2096 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2076 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [kach/nearley](https://github.com/kach/nearley) | 2047 | `mocha test/*.test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2042 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2035 | `npm run lint && mocha -R dot && npm run cover` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2030 | `npm run mocha && npm run karma` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2019 | `mocha tests --require @babel/register` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2016 | `mocha --reporter spec --timeout 5000` | 
| [then/promise](https://github.com/then/promise) | 2007 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2004 | `mocha && npm run lint` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1975 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1968 | `mocha test` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1689 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1671 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1661 | `mocha spec` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1658 | `mocha ./test/test*.js --reporter spec` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1641 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1640 | `mocha --recursive` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1639 | `mocha tests/test.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1620 | `mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1610 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1607 | `./node_modules/mocha/bin/mocha -R spec` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1596 | `mocha --recursive` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1568 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1689 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1685 | `mocha --check-leaks --reporter spec --bail` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1681 | `mocha && size-limit` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1669 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1661 | `mocha spec` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1658 | `mocha ./test/test*.js --reporter spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1644 | `mocha --expose-gc --slow 300` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1641 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1640 | `mocha --recursive` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1639 | `mocha tests/test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1633 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1621 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1620 | `mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1615 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1610 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1610 | `NODE_ENV=test mocha tests/*.js` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1610 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1607 | `./node_modules/mocha/bin/mocha -R spec` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1714 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1712 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1704 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1689 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1685 | `mocha --check-leaks --reporter spec --bail` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1681 | `mocha && size-limit` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1671 | `mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1669 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1661 | `mocha spec` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1658 | `mocha ./test/test*.js --reporter spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1644 | `mocha --expose-gc --slow 300` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1714 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1712 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1704 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1703 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1700 | `mocha test/test-*.js` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1695 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1685 | `mocha --check-leaks --reporter spec --bail` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1681 | `mocha && size-limit` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1671 | `mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1669 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1658 | `mocha ./test/test*.js --reporter spec` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1610 | `NODE_ENV=test mocha tests/*.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1605 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1601 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1596 | `mocha --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1572 | `mocha test/unit` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1570 | `nyc mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1568 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1557 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1548 | `mocha -R spec ./test/unit/**` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1544 | `mocha tests/test-*` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1449 | `mocha --opts test/opts/mocha.opts` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1448 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1446 | `npm run prepublishOnly && mocha test/test.js` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1440 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1421 | `npm run build && mocha -r should` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1414 | `mocha test --compilers js:babel-core/register` | 
| [electron/devtron](https://github.com/electron/devtron) | 1405 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1403 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1395 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1392 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1392 | `mocha --recursive` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1544 | `mocha tests/test-*` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1542 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require babel-core/register --recursive --exit` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1542 | `node_modules/.bin/mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1538 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1537 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1534 | `mocha --check-leaks --require @babel/register` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1529 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1519 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1519 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1505 | `npm run lint && npm run mocha` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1505 | `mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1505 | `mocha test/**/*.spec.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1505 | `npm run lint && mocha && karma start --single-run` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1500 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1499 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1496 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1493 | `mocha -R spec test/*.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1490 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1485 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1465 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [samccone/drool](https://github.com/samccone/drool) | 1460 | `mocha test/tests.js --timeout=10000` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1459 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1457 | `mocha --reporter dot` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1455 | `standard && istanbul cover _mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1453 | `mocha test.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1449 | `mocha --opts test/opts/mocha.opts` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1448 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1446 | `npm run prepublishOnly && mocha test/test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1444 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1440 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1431 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1422 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1421 | `npm run build && mocha -r should` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1414 | `mocha test --compilers js:babel-core/register` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1406 | `istanbul cover _mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1405 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1405 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1403 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1397 | `mocha --recursive test/bin` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1395 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1392 | `mocha --recursive` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1388 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1316 | `mocha spec/exec.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1314 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1311 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1310 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1308 | `mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1306 | `mocha tests/` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1298 | `npm run lint && npm run mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1288 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1284 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1282 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1282 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [variety/variety](https://github.com/variety/variety) | 1266 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1257 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1252 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1246 | `mocha --reporter spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1244 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1240 | `mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1351 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1350 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1350 | `mocha --compilers js:babel-core/register` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1348 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1345 | `webpack && npm run lint && npm run mocha` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1343 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1341 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1339 | `npm run mocha:istanbul` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1336 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1328 | `npm run lint && mocha --require @babel/register` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1327 | `lerna run test && mocha` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1324 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1322 | `mocha-phantomjs tests/index.html` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1318 | `mocha test/*.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1316 | `mocha --timeout 60000 test/` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1316 | `mocha spec/exec.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1315 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1314 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1311 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1311 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1282 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1282 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [variety/variety](https://github.com/variety/variety) | 1266 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1257 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1252 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1246 | `mocha --reporter spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1244 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1240 | `mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 919 | `./node_modules/.bin/mocha test/**/*` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 898 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 896 | `node_modules/.bin/mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 870 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1124 | `mocha test` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1123 | `mocha --reporter spec test --recursive` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1116 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1115 | `npm run convertto:es5 && npm run mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1114 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1103 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1099 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1097 | `mocha --recursive --bail --reporter spec test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1096 | `eslint src test && mocha --compilers babel-register` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1095 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1089 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1083 | `mocha test/tests.js` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1089 | `mocha --compilers js:babel-register` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1084 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1083 | `mocha test/tests.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1073 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [tomas/needle](https://github.com/tomas/needle) | 1066 | `mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1062 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1059 | `mocha --async-only` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1097 | `mocha --recursive --bail --reporter spec test` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1097 | `mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1097 | `node_modules/.bin/mocha && npm run lint` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1096 | `eslint src test && mocha --compilers babel-register` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1095 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1089 | `mocha --compilers js:babel-register` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1084 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1083 | `mocha test/tests.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1073 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1114 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1113 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1103 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1099 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1097 | `mocha --recursive --bail --reporter spec test` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1097 | `mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1097 | `node_modules/.bin/mocha && npm run lint` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1096 | `eslint src test && mocha --compilers babel-register` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1095 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1089 | `mocha --compilers js:babel-register` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1084 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1083 | `mocha test/tests.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1073 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [tomas/needle](https://github.com/tomas/needle) | 1066 | `mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1062 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1059 | `mocha --async-only` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1050 | `mocha $(find test -name '*.test.js')` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1049 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1044 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1039 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1030 | `mocha --recursive test/unit/` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1030 | `mocha --reporter spec --timeout 3000` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1020 | `mocha --reporter spec --bail --check-leaks test/` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1020 | `npm run lint && npm run mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1015 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1012 | `mocha test/*.test.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1009 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1008 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1007 | `mocha --check-leaks -R dot` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1004 | `mocha -R list` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 999 | `mocha --recursive ./test/*_spec.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 995 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 994 | `mocha spec/*.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 993 | `npm run lint && mocha -R spec` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 991 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 989 | `mocha --compilers js:babel-register test/*.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 989 | `./node_modules/.bin/mocha -R spec` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 986 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 953 | `mocha` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 952 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 945 | `nyc mocha specs` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 945 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 943 | `mocha test --compilers js:babel-register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 943 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 940 | `mocha --timeout 5000` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 939 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 935 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 931 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 917 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 916 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 916 | `mocha -t 5000` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 912 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 904 | `mocha test` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 904 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 898 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 896 | `node_modules/.bin/mocha` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 895 | `mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 892 | `mocha --timeout 200000` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 935 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 935 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 931 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 929 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 927 | `istanbul cover -- _mocha --reporter spec` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 924 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 921 | `standard && standard ./bin/* && mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 919 | `./node_modules/.bin/mocha test/**/*` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 917 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 916 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 916 | `mocha -t 5000` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 912 | `mocha spec/*.spec.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 896 | `node_modules/.bin/mocha` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 895 | `mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 884 | `node_modules/.bin/mocha test/spec` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 884 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 880 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 878 | `mocha -r should --exit test/*.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 877 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 877 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 877 | `mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 876 | `npm run build && istanbul test _mocha test/test.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 884 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 880 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 877 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 877 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 877 | `mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 876 | `npm run build && istanbul test _mocha test/test.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 871 | `mocha --reporter list` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 871 | `mocha --harmony --full-trace --check-leaks` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 871 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 870 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 822 | `npm run lint && mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 817 | `npm run mocha-test test/integration` | 
| [edsu/anon](https://github.com/edsu/anon) | 815 | `mocha --colors --reporter spec test.js` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 815 | `cake build && mocha ./test/mocha/*.coffee` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 815 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 811 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 809 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 808 | `mocha` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 808 | `_mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 849 | `npm run lint && mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 847 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 847 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 846 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 845 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 843 | `mocha --harmony tests/**` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 843 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 842 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 841 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 841 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 839 | `mocha --async-only` | 
| [developit/decko](https://github.com/developit/decko) | 836 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 836 | `mocha -r babel-register --check-leaks test/index.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 836 | `mocha` | 