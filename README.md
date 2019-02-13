# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:41 02/13/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45169 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42367 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42208 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30897 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25775 | `nyc mocha --timeout=10000 --exit` | 
| [caolan/async](https://github.com/caolan/async) | 25229 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25218 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21517 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20158 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18575 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18094 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17947 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17538 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15359 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15034 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14724 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14015 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13726 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13269 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13039 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12814 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12800 | `istanbul cover _mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12553 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12525 | `mocha --require @babel/register --reporter dot` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12359 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12346 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11615 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11304 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11219 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10933 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10860 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10696 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10582 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10445 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9857 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9804 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9713 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9577 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9464 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9452 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9341 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9085 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8944 | `mocha test/src` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8859 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8707 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8611 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8585 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8475 | `grunt clean:test && mocha --exit` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8393 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8319 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8277 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8193 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8062 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8044 | `./node_modules/.bin/mocha test` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8025 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7966 | `mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7954 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7891 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7616 | `npm run build && istanbul cover _mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7589 | `mocha --compilers js:babel-core/register` | 
| [dthree/cash](https://github.com/dthree/cash) | 7583 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7559 | `mocha; jshint *.js lib` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7542 | `mocha --exit --require @babel/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7527 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7451 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7258 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7204 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7124 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7069 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6981 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6913 | `mocha test/test.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6047 | `standard && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5898 | `mocha && eslint lib/**` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5805 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5796 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5791 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5718 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5656 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5609 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5584 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5429 | `mocha test` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5417 | `mocha -r esm` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5405 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5365 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5356 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5933 | `mocha` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 5908 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5898 | `mocha && eslint lib/**` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5805 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5796 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5791 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5718 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [teambit/bit](https://github.com/teambit/bit) | 5667 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5656 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5609 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5584 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5429 | `mocha test` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5417 | `mocha -r esm` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5405 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5365 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5356 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5212 | `mocha src/**/*Tests.js --harmony` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5152 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5132 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5128 | `gulp lint && mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5083 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5054 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4981 | `nyc mocha --exit` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4975 | `gulp build; mocha;` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4930 | `nyc mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4920 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4913 | `./node_modules/.bin/mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4892 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4868 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4857 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4844 | `mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4752 | `mocha --reporter spec -t 8000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4689 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4646 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4586 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4561 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4486 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4458 | `mocha --timeout=15000 tests/*.test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4440 | `NODE_ENV=test mocha --exit` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4428 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4397 | `mocha --check-leaks --reporter spec --bail` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4389 | `node_modules/.bin/mocha test/tests.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4387 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4347 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4293 | `npm run lint ; mocha && mocha test/individual` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4272 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4238 | `nyc mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4204 | `npm run build && cd test && mocha . --reporter dot` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4193 | `mocha -R spec ./test --recursive` | 
| [muicss/mui](https://github.com/muicss/mui) | 4142 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4135 | `mocha --require test/babel-hook test/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4102 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4098 | `mocha --require should --reporter spec` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3932 | `NODE_ENV=test mocha test/**/*.js` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3883 | `npm run mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3858 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3832 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3826 | `npm run build && mocha test/*.test.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3799 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [erming/shout](https://github.com/erming/shout) | 3796 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3785 | `mocha && tsc -p ./test/types` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3770 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3744 | `mocha test/* --reporter spec` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3743 | `eslint . && mocha -t 5000` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3706 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 3703 | `./node_modules/mocha/bin/mocha --require babel-core/register test/*` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3684 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3677 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3675 | `node_modules/.bin/mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3629 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3603 | `mocha tests/javascript` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3560 | `nyc mocha && tsc` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3560 | `nyc mocha && tsc` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3507 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3500 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3494 | `node_modules/.bin/mocha test/lib/` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3493 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3466 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3458 | `mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3449 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3440 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3412 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3403 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3389 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3380 | `mocha -R landing test/index --exit` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3339 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3333 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3266 | `mocha test/*.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3240 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 3229 | `mocha --require should --reporter spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3191 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3187 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3176 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3166 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3119 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3103 | `nyc mocha --recursive` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3081 | `npm run mocha && npm run lint` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3075 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3062 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3034 | `node_modules/.bin/mocha --reporter spec` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3031 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3015 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3007 | `mocha test-node` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2991 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3065 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3062 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3031 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3015 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2991 | `mocha` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2973 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2970 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2970 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2962 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2933 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2917 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2908 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2869 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2847 | `istanbul cover _mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2847 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [tj/should.js](https://github.com/tj/should.js) | 2730 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2725 | `nyc mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2716 | `mocha --recursive --watch` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2692 | `mocha --timeout 100000` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2690 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2611 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2592 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2569 | `mocha test --exit && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2566 | `mocha && eslint .` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2564 | `mocha test/src/**/*.unit.js` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2563 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2559 | `TEST=all mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2558 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2553 | `mocha test` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2533 | `export TESTING=true; mocha --reporter list` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2634 | `mocha-phantomjs ./test/index.html` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2592 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2569 | `mocha test --exit && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2566 | `mocha && eslint .` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2564 | `mocha test/src/**/*.unit.js` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2563 | `mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2558 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2542 | `nyc --reporter=html --reporter=text mocha` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2533 | `export TESTING=true; mocha --reporter list` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2527 | `mocha --reporter=spec test/*-test.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2517 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2512 | `mocha test/index.js --reporter dot` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2510 | `mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2471 | `mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2464 | `nyc --require babel-register npm run _mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2463 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2462 | `mocha -R spec` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2461 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2055 | `npm run lint && mocha -R dot && npm run cover` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2051 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2043 | `mocha && npm run lint` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2033 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2027 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2010 | `mocha --require=test/test_helper.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1999 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1973 | `mocha test/**/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1966 | `mocha -c test/index.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1963 | `mocha --reporter spec && npm run test-typescript` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1963 | `mocha --bail --reporter spec --check-leaks test/` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1955 | `bmocha --reporter spec test/*.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1953 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1953 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1946 | `npm run lint && mocha --reporter spec test/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1925 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1922 | `mocha test` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2451 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2450 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [noble/noble](https://github.com/noble/noble) | 2428 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2403 | `npm run build && mocha --require babel-register` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2395 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2385 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2367 | `node node_modules/mocha/bin/_mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2295 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2289 | `mocha test/**/*.coffee` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2288 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2265 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2262 | `standard && mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2229 | `mocha && eslint *.js` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2211 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2199 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2195 | `mocha --timeout 10000 --bail --exit test/*-test.js test/security/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2188 | `cross-env BABEL_ENV=test mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2161 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2153 | `mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2143 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2135 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2120 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2098 | `mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2085 | `mocha test` | 
| [kach/nearley](https://github.com/kach/nearley) | 2082 | `mocha test/*.test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2070 | `npm run mocha && npm run karma` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2059 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2055 | `npm run lint && mocha -R dot && npm run cover` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2055 | `mocha test/test-*.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2050 | `mocha tests --require @babel/register` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2049 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2033 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2027 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2059 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2055 | `npm run lint && mocha -R dot && npm run cover` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2055 | `mocha test/test-*.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2051 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2050 | `mocha tests --require @babel/register` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2049 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2043 | `mocha && npm run lint` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2033 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2027 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 2016 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2010 | `mocha --require=test/test_helper.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1999 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1925 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1922 | `mocha test` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1896 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1888 | `mocha ./test/basic.js -t 5000` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1879 | `mocha tests.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1864 | `mocha` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1856 | `mocha --recursive` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1848 | `npm run lint && npm run mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1839 | `eslint --cache . && tsc && mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1832 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1829 | `npm run lint && npm run mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1864 | `mocha` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1856 | `mocha --recursive` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1848 | `npm run lint && npm run mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1832 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1829 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1820 | `mocha test` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1819 | `mocha test/setup.js test/spec/*.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1813 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1805 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1796 | `mocha --timeout 5000` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1820 | `mocha test` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1819 | `mocha test/setup.js test/spec/*.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1813 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1805 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1796 | `mocha --timeout 5000` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1781 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1778 | `mocha tests.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1767 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1767 | `npm run lint && mocha && npm run typescript` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1760 | `mocha ./test/test*.js --reporter spec` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1753 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1750 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1710 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1692 | `npm run jshint && mocha --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1687 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1685 | `mocha && size-limit` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1674 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1672 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1665 | `mocha spec` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1659 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1653 | `NODE_ENV=test mocha tests/*.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1652 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1617 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1617 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1613 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1598 | `mocha test/unit` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1597 | `mocha -R spec ./test/unit/**` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1587 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1582 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1581 | `nyc mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1560 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1550 | `mocha --check-leaks --require @babel/register` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1131 | `mocha test/*` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1119 | `eslint src test && mocha --compilers babel-register` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1115 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1105 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1102 | `mocha --recursive --bail --reporter spec test` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1096 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1091 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1088 | `mocha test/tests.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [tomas/needle](https://github.com/tomas/needle) | 1073 | `mocha test` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1012 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1005 | `mocha -R list` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 986 | `mocha "client.test" --compilers js:babel-register` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 983 | `mocha --reporter spec` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 968 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 968 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 968 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 968 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 964 | `./node_modules/.bin/mocha --reporter spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 961 | `mocha` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 950 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 947 | `./node_modules/.bin/mocha test/**/*` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 942 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 940 | `standard && standard ./bin/* && mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 928 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 918 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 918 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 916 | `mocha -t 5000` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 916 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 915 | `mocha test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 912 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 911 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 910 | `mocha` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 906 | `npm run lint && npm run mocha:no-functional` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 906 | `npm run lint && npm run mocha:no-functional` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 904 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 904 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 894 | `mocha --timeout 200000` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 893 | `mocha -r should --exit test/*.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 890 | `node_modules/.bin/mocha test/spec` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 890 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 890 | `npm run build && istanbul test _mocha test/test.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 886 | `mocha --harmony --full-trace --check-leaks` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 882 | `mocha --reporter list` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 863 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 861 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 861 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 858 | `nyc mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 855 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 855 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 854 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 854 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [developit/decko](https://github.com/developit/decko) | 853 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 852 | `mocha` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 848 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 844 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 844 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 841 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 840 | `nyc mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 839 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 839 | `mocha --async-only` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 836 | `mocha test` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 841 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 840 | `nyc mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 839 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 836 | `mocha test` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 833 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 832 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 831 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 826 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 826 | `mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 824 | `npm run mocha-test test/integration` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 823 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 822 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 821 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 826 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 826 | `mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 824 | `npm run mocha-test test/integration` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 823 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 822 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 821 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [edsu/anon](https://github.com/edsu/anon) | 818 | `mocha --colors --reporter spec test.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 818 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 817 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 815 | `cake build && mocha ./test/mocha/*.coffee` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 814 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [koajs/static](https://github.com/koajs/static) | 779 | `mocha --harmony --reporter spec --exit` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 778 | `mocha tests --timeout 10000` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 775 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 775 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 768 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 768 | `npm run-script jshint && npm run-script mocha` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 765 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 763 | `mocha --reporter spec build/test/index.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 761 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 801 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 800 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [ebradyjobory/finance.js](https://github.com/ebradyjobory/finance.js) | 800 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 797 | `mocha test` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 797 | `mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 796 | `mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 796 | `mocha --no-timeouts` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 793 | `npm run lint && npm run mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 792 | `nyc mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 790 | `eslint . && mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 787 | `mocha --recursive -s 15 test/` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 775 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 768 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 768 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 768 | `npm run-script jshint && npm run-script mocha` | 
| [susam/texme](https://github.com/susam/texme) | 768 | `standard && mocha` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 765 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 765 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 763 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 763 | `mocha --reporter spec build/test/index.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 761 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 765 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 763 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 761 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 761 | `./bin/selenium-standalone install && mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 752 | `mocha tests/*.mocha.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 752 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 751 | `mocha 'test/**/*.tests.js'` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [rkusa/koa-passport](https://github.com/rkusa/koa-passport) | 644 | `mocha` | 
| [danielstjules/buddy.js](https://github.com/danielstjules/buddy.js) | 643 | `mocha -R spec spec/unit spec/integration` | 
| [Munter/subfont](https://github.com/Munter/subfont) | 640 | `npm run lint && mocha` | 
| [ideal-postcodes/postcodes.io](https://github.com/ideal-postcodes/postcodes.io) | 638 | `NODE_ENV=test npm run test:create && npm run nyc_mocha && NODE_ENV=test npm run test:clear && npm run lint` | 
| [gauntface/simple-push-demo](https://github.com/gauntface/simple-push-demo) | 637 | `gulp && npm run lint && node ./test/helpers/download-browsers.js && mocha` | 
| [werk85/node-html-to-text](https://github.com/werk85/node-html-to-text) | 631 | `istanbul cover _mocha && eslint .` | 
| [jaredhanson/passport-google-oauth](https://github.com/jaredhanson/passport-google-oauth) | 629 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [vault-development/react-native-svg-uri](https://github.com/vault-development/react-native-svg-uri) | 628 | `./node_modules/mocha/bin/mocha --compilers js:babel-core/register` | 
| [susielu/d3-legend](https://github.com/susielu/d3-legend) | 625 | `mocha` | 
| [mysamai/mysam](https://github.com/mysamai/mysam) | 623 | `npm run lint && npm run mocha` | 
| [robrich/gulp-if](https://github.com/robrich/gulp-if) | 621 | `mocha && jshint .` | 
| [M6Web/websocket-bench](https://github.com/M6Web/websocket-bench) | 621 | `gulp mocha` | 
| [robrich/gulp-if](https://github.com/robrich/gulp-if) | 621 | `mocha && jshint .` | 
| [hemerajs/hemera](https://github.com/hemerajs/hemera) | 621 | `nyc mocha -b -r "./test/hemera/bootstrap" -t 5000 --exit "./test/**/*.spec.js" "./packages/hemera-zipkin/test/**/*.js" && npm run typescript` | 
| [adamgruber/mochawesome](https://github.com/adamgruber/mochawesome) | 620 | `npm run lint && cross-env NODE_ENV=test nyc mocha` | 
| [duaraghav8/Ethlint](https://github.com/duaraghav8/Ethlint) | 619 | `nyc --reporter=text --reporter=html mocha --require should --reporter spec --recursive` | 
| [gameclosure/devkit](https://github.com/gameclosure/devkit) | 617 | `mocha --reporter spec --recursive -C ./tests` | 
| [w0rm/gulp-svgstore](https://github.com/w0rm/gulp-svgstore) | 617 | `gulp build && mocha test.js` | 
| [webpack/memory-fs](https://github.com/webpack/memory-fs) | 613 | `mocha` | 
| [desmondmorris/node-tesseract](https://github.com/desmondmorris/node-tesseract) | 609 | `mocha` | 
| [desmondmorris/node-tesseract](https://github.com/desmondmorris/node-tesseract) | 609 | `mocha` | 
| [webdriverio-boneyard/webdrivercss](https://github.com/webdriverio-boneyard/webdrivercss) | 607 | `./node_modules/.bin/mocha` | 
| [koajs/session](https://github.com/koajs/session) | 607 | `npm run lint && NODE_ENV=test mocha --exit --require should --reporter spec test/*.test.js` | 
| [shinnn/gulp-gh-pages](https://github.com/shinnn/gulp-gh-pages) | 607 | `nyc mocha test.js --timeout 50000 --full-trace` | 
| [mattyork/fuzzy](https://github.com/mattyork/fuzzy) | 606 | `./node_modules/.bin/mocha` | 
| [cgross/generator-cg-angular](https://github.com/cgross/generator-cg-angular) | 606 | `mocha` | 
| [omnidan/node-emoji](https://github.com/omnidan/node-emoji) | 605 | `./node_modules/.bin/mocha --require should --bail --reporter spec test/*` | 
| [victorb/autochecker](https://github.com/victorb/autochecker) | 605 | `mocha` | 
| [echenley/react-news](https://github.com/echenley/react-news) | 604 | `./node_modules/.bin/karma start ./test/karma.conf.js --reporters mocha,coverage` | 
| [danielbayerlein/dashboard](https://github.com/danielbayerlein/dashboard) | 602 | `export TESTING=true; mocha --reporter list` | 
| [rofrischmann/react-look](https://github.com/rofrischmann/react-look) | 599 | `npm run lint && mocha --recursive --compilers js:babel/register` | 
| [putaoshu/jdf](https://github.com/putaoshu/jdf) | 598 | `mocha test/index.js` | 
| [times/cardkit](https://github.com/times/cardkit) | 598 | `./node_modules/.bin/istanbul cover --dir test/coverage ./node_modules/.bin/_mocha -- --compilers js:babel-core/register --require ignore-styles` | 
| [matthewmueller/graph.ql](https://github.com/matthewmueller/graph.ql) | 598 | `./node_modules/.bin/mocha` | 
| [ck86/main-bower-files](https://github.com/ck86/main-bower-files) | 597 | `mocha` | 
| [filamentgroup/glyphhanger](https://github.com/filamentgroup/glyphhanger) | 596 | `mocha` | 
| [ipfs-shipyard/ipfs-desktop](https://github.com/ipfs-shipyard/ipfs-desktop) | 596 | `cross-env NODE_ENV=test mocha` | 
| [Charca/bootbot](https://github.com/Charca/bootbot) | 596 | `mocha --recursive test/*` | 
| [SamyPesse/gitkit-js](https://github.com/SamyPesse/gitkit-js) | 594 | `./node_modules/.bin/mocha ./testing/setup.js ./lib/**/*/__tests__/*.js --bail --reporter=list` | 
| [SGrondin/bottleneck](https://github.com/SGrondin/bottleneck) | 594 | `mocha test` | 
| [teropa/redux-voting-server](https://github.com/teropa/redux-voting-server) | 593 | `mocha --compilers js:babel-core/register  --require ./test/test_helper.js  --recursive` | 
| [mbasso/react-decoration](https://github.com/mbasso/react-decoration) | 592 | `cross-env BABEL_ENV=commonjs nyc --require babel-register --require ./test/setup.js mocha --recursive` | 
| [jkphl/gulp-svg-sprite](https://github.com/jkphl/gulp-svg-sprite) | 592 | `gulp && istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [newsdev/ai2html](https://github.com/newsdev/ai2html) | 592 | `mocha --check-leaks` | 
| [dleitee/valid.js](https://github.com/dleitee/valid.js) | 592 | `mocha --compilers js:babel-register` | 
| [justinfagnani/mixwith.js](https://github.com/justinfagnani/mixwith.js) | 590 | `mocha build/test` | 
| [bitovi/documentjs](https://github.com/bitovi/documentjs) | 590 | `mocha test/test.js --reporter spec` | 
| [screwdriver-cd/screwdriver](https://github.com/screwdriver-cd/screwdriver) | 577 | `jenkins-mocha --recursive --timeout 3000 --exit` | 
| [Spreadsheets/WickedGrid](https://github.com/Spreadsheets/WickedGrid) | 577 | `./node_modules/.bin/mocha --reporter spec` | 
| [jmreidy/grunt-browserify](https://github.com/jmreidy/grunt-browserify) | 577 | `mocha -R spec --timeout 5000` | 
| [sindresorhus/jshint-stylish](https://github.com/sindresorhus/jshint-stylish) | 575 | `xo && mocha` | 
| [orliesaurus/nodemailer-mailgun-transport](https://github.com/orliesaurus/nodemailer-mailgun-transport) | 575 | `mocha` | 
| [scrollback/scrollback](https://github.com/scrollback/scrollback) | 571 | `node_modules/.bin/mocha test/test.js` | 
| [csstree/csstree](https://github.com/csstree/csstree) | 571 | `mocha --reporter progress` | 
| [javivelasco/react-css-themr](https://github.com/javivelasco/react-css-themr) | 569 | `mocha --compilers js:babel-core/register --recursive --reporter spec --require ./test/setup.js` | 
| [mike-marcacci/node-redlock](https://github.com/mike-marcacci/node-redlock) | 568 | `istanbul cover mocha` | 
| [queckezz/koa-views](https://github.com/queckezz/koa-views) | 567 | `mocha --reporter dot --bail --exit` | 
| [azproduction/autopolyfiller](https://github.com/azproduction/autopolyfiller) | 567 | `npm run lint && mocha -R spec` | 
| [tschaub/mock-fs](https://github.com/tschaub/mock-fs) | 566 | `mocha --recursive test` | 
| [scniro/gulp-clean-css](https://github.com/scniro/gulp-clean-css) | 566 | `./node_modules/.bin/mocha ./index.spec.js` | 
| [hunterloftis/throng](https://github.com/hunterloftis/throng) | 565 | `mocha` | 
| [JoshKaufman/ursa](https://github.com/JoshKaufman/ursa) | 581 | `mocha --recursive --reporter spec` | 
| [felixge/node-dirty](https://github.com/felixge/node-dirty) | 579 | `mocha test/test-*.js -R list` | 
| [zpratt/react-tdd-guide](https://github.com/zpratt/react-tdd-guide) | 579 | `npm run lint && mocha */test` | 
| [nicksp/redux-webpack-es6-boilerplate](https://github.com/nicksp/redux-webpack-es6-boilerplate) | 578 | `mocha --compilers js:babel-core/register,css:./test/unit/cssNullCompiler.js --require ./test/unit/testHelper.js --recursive ./test/unit` | 
| [ziyasal/scientist.js](https://github.com/ziyasal/scientist.js) | 577 | `node ./node_modules/babel-cli/bin/babel-node.js ./node_modules/mocha/bin/_mocha --timeout 20000 tests/**/*.spec.js` | 
| [screwdriver-cd/screwdriver](https://github.com/screwdriver-cd/screwdriver) | 577 | `jenkins-mocha --recursive --timeout 3000 --exit` | 
| [Spreadsheets/WickedGrid](https://github.com/Spreadsheets/WickedGrid) | 577 | `./node_modules/.bin/mocha --reporter spec` | 
| [jmreidy/grunt-browserify](https://github.com/jmreidy/grunt-browserify) | 577 | `mocha -R spec --timeout 5000` | 
| [sindresorhus/jshint-stylish](https://github.com/sindresorhus/jshint-stylish) | 575 | `xo && mocha` | 
| [orliesaurus/nodemailer-mailgun-transport](https://github.com/orliesaurus/nodemailer-mailgun-transport) | 575 | `mocha` | 
| [mathiasbynens/emoji-regex](https://github.com/mathiasbynens/emoji-regex) | 574 | `mocha` | 
| [gsuitedevs/apps-script-oauth2](https://github.com/gsuitedevs/apps-script-oauth2) | 572 | `mocha` | 
| [scniro/gulp-clean-css](https://github.com/scniro/gulp-clean-css) | 566 | `./node_modules/.bin/mocha ./index.spec.js` | 
| [hunterloftis/throng](https://github.com/hunterloftis/throng) | 565 | `mocha` | 
| [tj/node-ratelimiter](https://github.com/tj/node-ratelimiter) | 564 | `mocha --exit` | 
| [talpor/django-dashing](https://github.com/talpor/django-dashing) | 563 | `mocha -t 10000` | 
| [imgly/imgly-sdk-html5](https://github.com/imgly/imgly-sdk-html5) | 561 | `NODE_ENV=test node_modules/.bin/mocha --harmony --require should --require babel/register --reporter spec test/*.test.js test/**/*.test.js` | 
| [t1msh/node-oauth20-provider](https://github.com/t1msh/node-oauth20-provider) | 559 | `node_modules/.bin/mocha --reporter spec` | 
| [jsantell/poet](https://github.com/jsantell/poet) | 559 | `./node_modules/.bin/mocha --reporter spec --ui bdd` | 
| [ember-cli-deploy/ember-cli-deploy](https://github.com/ember-cli-deploy/ember-cli-deploy) | 559 | `node node_modules/mocha/bin/mocha "node-tests/**/*-test.js"` | 
| [moshen/node-googlemaps](https://github.com/moshen/node-googlemaps) | 558 | `./node_modules/.bin/mocha test/unit` | 
| [hiproxy/hiproxy](https://github.com/hiproxy/hiproxy) | 558 | `cross-env NPM_TEST=true nyc mocha test/**/*.test.js test/**/**/*.test.js --timeout 10000 && nyc report --reporter=lcov --reporter=html` | 
| [gulp-community/gulp-less](https://github.com/gulp-community/gulp-less) | 557 | `jshint index.js && node_modules/.bin/mocha` | 
| [website-scraper/node-website-scraper](https://github.com/website-scraper/node-website-scraper) | 549 | `nyc --reporter=html --reporter=text mocha --recursive --timeout 7000 ./test/unit/ ./test/functional && npm run eslint` | 
| [sebpiq/WebPd](https://github.com/sebpiq/WebPd) | 549 | `mocha --reporter list --recursive test/lib` | 
| [mozilla/webextension-polyfill](https://github.com/mozilla/webextension-polyfill) | 549 | `mocha` | 
| [jshttp/cookie](https://github.com/jshttp/cookie) | 548 | `mocha --reporter spec --bail --check-leaks test/` | 
| [mrsimonfletcher/react-progressive-web-app](https://github.com/mrsimonfletcher/react-progressive-web-app) | 547 | `mocha "src/**/*.spec.jsx"` | 
| [vbauer/manet](https://github.com/vbauer/manet) | 546 | `mocha --exit` | 
| [dlau/koa-body](https://github.com/dlau/koa-body) | 546 | `mocha` | 
| [bithavoc/express-winston](https://github.com/bithavoc/express-winston) | 545 | `node_modules/.bin/mocha --reporter spec` | 
| [thibauts/node-castv2-client](https://github.com/thibauts/node-castv2-client) | 545 | `node_modules/.bin/mocha` | 
| [mrsteele/dotenv-webpack](https://github.com/mrsteele/dotenv-webpack) | 544 | `nyc _mocha --compilers js:babel-register` | 
| [bitpay/insight-api](https://github.com/bitpay/insight-api) | 543 | `NODE_ENV=test mocha -R spec --recursive` | 
| [jsreport/jsreport](https://github.com/jsreport/jsreport) | 542 | `mocha test --timeout 35000 && standard` | 
| [Tom-Alexander/regression-js](https://github.com/Tom-Alexander/regression-js) | 542 | `npm run lint && ./node_modules/.bin/nyc --reporter=lcov ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mikejihbe/metrics](https://github.com/mikejihbe/metrics) | 541 | `tsc index.d.ts && ./node_modules/.bin/mocha test/unit` | 
| [euforic/banking.js](https://github.com/euforic/banking.js) | 540 | `mocha --require should --reporter spec --globals i` | 
| [Rabrennie/anything.js](https://github.com/Rabrennie/anything.js) | 540 | `node_modules/.bin/mocha` | 
| [larsonjj/generator-yeogurt](https://github.com/larsonjj/generator-yeogurt) | 522 | `istanbul cover _mocha -- test/app/*.test.js test/subgenerators/*.test.js --reporter list --timeout 100000 && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [Lucifier129/factor-network](https://github.com/Lucifier129/factor-network) | 522 | `mocha --require babel-polyfill --compilers babel-register` | 
| [unshiftio/url-parse](https://github.com/unshiftio/url-parse) | 521 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [techlayer/espresso.js](https://github.com/techlayer/espresso.js) | 521 | `mocha` | 
| [rafaelhz/react-material-admin-template](https://github.com/rafaelhz/react-material-admin-template) | 521 | `mocha tools/testSetup.js "src/**/*.spec.js" --reporter progress` | 
| [EvanHahn/HumanizeDuration.js](https://github.com/EvanHahn/HumanizeDuration.js) | 521 | `mocha` | 
| [FGRibreau/match-when](https://github.com/FGRibreau/match-when) | 521 | `mocha {**,*/**}.test.js` | 
| [markdalgleish/react-themeable](https://github.com/markdalgleish/react-themeable) | 518 | `babel-istanbul cover _mocha -- --compilers js:babel/register && babel-istanbul check-coverage --branches 100` | 
| [nitrotasks/nitro](https://github.com/nitrotasks/nitro) | 518 | `cross-env NODE_ENV=test nyc mocha nitro.sdk.test/index.js && npm run build` | 
| [sitegui/nodejs-websocket](https://github.com/sitegui/nodejs-websocket) | 515 | `mocha -R spec -b` | 
| [shootaroo/jit-grunt](https://github.com/shootaroo/jit-grunt) | 514 | `npm-run-all build -p lint mocha` | 
| [shakiba/svgexport](https://github.com/shakiba/svgexport) | 513 | `mocha` | 
| [bard/mozrepl](https://github.com/bard/mozrepl) | 513 | `mocha test` | 
| [asmcrypto/asmcrypto.js](https://github.com/asmcrypto/asmcrypto.js) | 512 | `node -r esm build.js && mocha -r esm test/*.js` | 
| [expressjs/vhost](https://github.com/expressjs/vhost) | 531 | `mocha --reporter spec --bail --check-leaks test/` | 
| [rollup/rollup-plugin-babel](https://github.com/rollup/rollup-plugin-babel) | 530 | `mocha` | 
| [chrisveness/geodesy](https://github.com/chrisveness/geodesy) | 530 | `mocha test/*.js` | 
| [sintaxi/dbox](https://github.com/sintaxi/dbox) | 529 | `./node_modules/.bin/mocha -t 120000 test/all.js -R spec` | 
| [kosmtik/kosmtik](https://github.com/kosmtik/kosmtik) | 526 | `mocha` | 
| [pazguille/viewport](https://github.com/pazguille/viewport) | 526 | `npm run build && NODE_ENV=test istanbul cover _mocha -- ./test/*.spec.js` | 
| [zapty/forever-service](https://github.com/zapty/forever-service) | 525 | `mocha test/*.js` | 
| [zeromq/zeromq.js](https://github.com/zeromq/zeromq.js) | 525 | `mocha --expose-gc --slow 300` | 
| [node-pinus/pinus](https://github.com/node-pinus/pinus) | 525 | `mocha` | 
| [stephen-hardy/xlsx.js](https://github.com/stephen-hardy/xlsx.js) | 525 | `mocha -R spec` | 
| [flywheelsports/hydra](https://github.com/flywheelsports/hydra) | 524 | `mocha specs --reporter spec` | 
| [dankogai/js-combinatorics](https://github.com/dankogai/js-combinatorics) | 524 | `mocha` | 
| [styled-components/vue-styled-components](https://github.com/styled-components/vue-styled-components) | 523 | `mocha "./src/**/*.test.js" --require babel-core/register --require ./mocha-bootstrap --timeout 5000` | 
| [expressjs/vhost](https://github.com/expressjs/vhost) | 531 | `mocha --reporter spec --bail --check-leaks test/` | 
| [rollup/rollup-plugin-babel](https://github.com/rollup/rollup-plugin-babel) | 530 | `mocha` | 
| [chrisveness/geodesy](https://github.com/chrisveness/geodesy) | 530 | `mocha test/*.js` | 
| [adorableio/avatars-api-middleware](https://github.com/adorableio/avatars-api-middleware) | 530 | `mocha --exit` | 
| [kosmtik/kosmtik](https://github.com/kosmtik/kosmtik) | 526 | `mocha` | 
| [pazguille/viewport](https://github.com/pazguille/viewport) | 526 | `npm run build && NODE_ENV=test istanbul cover _mocha -- ./test/*.spec.js` | 
| [zapty/forever-service](https://github.com/zapty/forever-service) | 525 | `mocha test/*.js` | 
| [zeromq/zeromq.js](https://github.com/zeromq/zeromq.js) | 525 | `mocha --expose-gc --slow 300` | 
| [node-pinus/pinus](https://github.com/node-pinus/pinus) | 525 | `mocha` | 
| [stephen-hardy/xlsx.js](https://github.com/stephen-hardy/xlsx.js) | 525 | `mocha -R spec` | 
| [flywheelsports/hydra](https://github.com/flywheelsports/hydra) | 524 | `mocha specs --reporter spec` | 
| [dankogai/js-combinatorics](https://github.com/dankogai/js-combinatorics) | 524 | `mocha` | 
| [styled-components/vue-styled-components](https://github.com/styled-components/vue-styled-components) | 523 | `mocha "./src/**/*.test.js" --require babel-core/register --require ./mocha-bootstrap --timeout 5000` | 
| [nemtsov/json-mask](https://github.com/nemtsov/json-mask) | 522 | `npm run lint && mocha` | 