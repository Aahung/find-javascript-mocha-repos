# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:49 03/02/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45342 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42637 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42361 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30965 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25920 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25444 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25282 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 21678 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20274 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18740 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18240 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18097 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17801 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15509 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15161 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14763 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14103 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13077 | `mocha 'test/**/*.spec.js'` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12904 | `istanbul cover _mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12866 | `mocha --reporter spec test/*-test.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12716 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12646 | `mocha --require @babel/register --reporter dot` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12376 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11725 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11470 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11301 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 11003 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10760 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10703 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10760 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10703 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10481 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9969 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9865 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9744 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9630 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9546 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9485 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9380 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9248 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9002 | `mocha test/src` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8969 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 8944 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8724 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8643 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8592 | `mocha --check-leaks -R dot` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8514 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8498 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8318 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8303 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8287 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8141 | `mocha` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8115 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8097 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8083 | `./node_modules/.bin/mocha test` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8039 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7944 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7649 | `mocha --exit --require @babel/register` | 
| [almende/vis](https://github.com/almende/vis) | 7645 | `mocha --compilers js:babel-core/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7644 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7619 | `npm run build && istanbul cover _mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7617 | `mocha; jshint *.js lib` | 
| [dthree/cash](https://github.com/dthree/cash) | 7589 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7555 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7451 | `mocha` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7323 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7153 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7119 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7111 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 7016 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6626 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6430 | `npm run test:mocha:src` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6401 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6400 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6319 | `mocha tests/node.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6273 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6260 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6216 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6168 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6145 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6145 | `standard && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6067 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5926 | `mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5924 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5919 | `mocha && eslint lib/**` | 
| [teambit/bit](https://github.com/teambit/bit) | 5909 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5901 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5823 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5747 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5684 | `mocha` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5679 | `npm run lint && mocha tests/**/*.js` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5624 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5501 | `mocha test` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5474 | `mocha -r esm` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5432 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5408 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5400 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5319 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5210 | `mocha src/**/*Tests.js --harmony` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5138 | `gulp lint && mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5134 | `mocha --recursive` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5128 | `mocha --color` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5119 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5070 | `nyc mocha --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5016 | `nyc mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4995 | `gulp build; mocha;` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4957 | `./node_modules/.bin/mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4952 | `NODE_ENV=test mocha --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4930 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4909 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4880 | `mocha -R spec 'tests/app'` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4880 | `mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4864 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4770 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4756 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4685 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4589 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4572 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4508 | `mocha --timeout=15000 tests/*.test.js` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4488 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4481 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4474 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4443 | `mocha --check-leaks --reporter spec --bail` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4407 | `node_modules/.bin/mocha test/tests.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4392 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4381 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4336 | `npm run lint ; mocha && mocha test/individual` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4257 | `npm run build && cd test && mocha . --reporter dot` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4248 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4191 | `mocha -R spec ./test --recursive` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4147 | `mocha --require test/babel-hook test/*.js` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 4143 | `./node_modules/mocha/bin/mocha --require @babel/register test/*` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4131 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4109 | `mocha --require should --reporter spec` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 4003 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3932 | `mocha && tsc -p ./test/types` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3854 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3835 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3802 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3796 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3749 | `mocha test/* --reporter spec` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3683 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3683 | `node_modules/.bin/mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3682 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3674 | `npm run jshint && npm run mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3665 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3606 | `mocha tests/javascript` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3602 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3597 | `nyc mocha && tsc` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3469 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3460 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3449 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3447 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3428 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3421 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3420 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3384 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3375 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3344 | `mocha test/index.js && npm run demo` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3287 | `mocha test/*.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 3281 | `mocha --require should --reporter spec` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2822 | `mocha "./test/**/*-test.js"` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2786 | `mocha --require should --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2769 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2740 | `nyc mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2740 | `nyc mocha --timeout=10000` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2712 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2682 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2588 | `mocha && eslint .` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2567 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2557 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2552 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2850 | `istanbul cover _mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2793 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2786 | `mocha --require should --reporter spec` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2775 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2769 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2740 | `nyc mocha --timeout=10000` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2712 | `mocha test/unit --require mochahook` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2700 | `mocha --timeout 100000` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2822 | `mocha "./test/**/*-test.js"` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2765 | `xo && mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2740 | `nyc mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2740 | `nyc mocha --timeout=10000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2720 | `mocha --recursive --watch` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2712 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2710 | `mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2700 | `mocha --timeout 100000` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2682 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2628 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2594 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2592 | `TEST=all mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2720 | `mocha --recursive --watch` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2710 | `mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2700 | `mocha --timeout 100000` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2682 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2637 | `mocha-phantomjs ./test/index.html` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2603 | `mocha test --exit && npm run lint` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2594 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2592 | `TEST=all mocha` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2581 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2574 | `mocha test/src/**/*.unit.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2567 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2567 | `mocha test` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2557 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2552 | `mocha` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2534 | `export TESTING=true; mocha --reporter list` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2028 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 2016 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2015 | `mocha --require=test/test_helper.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1989 | `mocha test/**/*.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1980 | `mocha --require ./test/common --growl test/expect.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1980 | `mocha --reporter spec && npm run test-typescript` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1971 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1969 | `mocha --recursive` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1968 | `bmocha --reporter spec test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1965 | `npm run lint && mocha --reporter spec test/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1960 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1953 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1950 | `nyc mocha --timeout=20000 test.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1939 | `mocha --reporter spec --grep .` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1939 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1933 | `mocha test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1932 | `mocha test -u bdd -R spec` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2290 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2279 | `standard && mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2246 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2212 | `mocha --timeout 15000 --bail --exit test/*-test.js test/security/*.js` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2204 | `mocha test/test-*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2192 | `cross-env BABEL_ENV=test mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2184 | `mocha --compilers js:babel-register` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2165 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2160 | `mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2218 | `mocha test test/unit/**/*_test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2212 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2209 | `mocha test/runner.js --reporter spec` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2192 | `cross-env BABEL_ENV=test mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2184 | `mocha --compilers js:babel-register` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2165 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2159 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2155 | `mocha --compilers js:babel-core/register __tests__` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2151 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2149 | `mocha test` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2134 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2108 | `npm run mocha && npm run karma` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2100 | `mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 2099 | `mocha test/*.test.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2094 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2068 | `mocha tests --require @babel/register` | 
| [htmlhint/HTMLHint](https://github.com/htmlhint/HTMLHint) | 2066 | `mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2066 | `mocha && npm run lint` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2060 | `npm run lint && mocha -R dot && npm run cover` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2056 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2056 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2045 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2028 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 2020 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 2016 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2015 | `mocha --require=test/test_helper.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1989 | `mocha test/**/*.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1980 | `mocha --require ./test/common --growl test/expect.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1980 | `mocha --reporter spec && npm run test-typescript` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1971 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1969 | `mocha --recursive` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1968 | `bmocha --reporter spec test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1965 | `npm run lint && mocha --reporter spec test/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1960 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1953 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1950 | `nyc mocha --timeout=20000 test.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1939 | `mocha --reporter spec --grep .` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1939 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1933 | `mocha test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1932 | `mocha test -u bdd -R spec` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1858 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1843 | `npm run lint && npm run mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1835 | `mocha test/setup.js test/spec/*.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1829 | `mocha ./test/test*.js --reporter spec` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1822 | `mocha test` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1813 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1773 | `npm run lint && mocha && npm run typescript` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1759 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1755 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1753 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1750 | `mocha --check-leaks --reporter spec --bail` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1745 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1733 | `mocha test --timeout 600000` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1732 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1731 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1727 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1725 | `mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1724 | `mocha test/**/*_test.js --bail` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1720 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1717 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1714 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1692 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1689 | `mocha && size-limit` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1686 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1676 | `NODE_ENV=test mocha tests/*.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1671 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1661 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1645 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1637 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1634 | `mocha --reporter spec` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1634 | `mocha --recursive` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1645 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1637 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1634 | `mocha --reporter spec` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1634 | `mocha --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1625 | `mocha test/unit` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1625 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1625 | `./node_modules/mocha/bin/mocha -R spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1624 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1624 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1622 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1621 | `mocha -R spec ./test/unit/**` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1614 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1614 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1603 | `mocha tests/test-*` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1599 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1625 | `mocha test/unit` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1625 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1625 | `./node_modules/mocha/bin/mocha -R spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1624 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1624 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1622 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1621 | `mocha -R spec ./test/unit/**` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1614 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1614 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1603 | `mocha tests/test-*` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1599 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1588 | `nyc mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1569 | `mocha --check-leaks --require @babel/register` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1560 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1558 | `npm run lint && npm run mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1557 | `node_modules/.bin/mocha --recursive` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1549 | `npm run test:lint && npm run test:mocha` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1549 | `mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1546 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1544 | `mocha -u tdd` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1543 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1518 | `mocha -R spec test/*.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1516 | `mocha test/**/*.spec.js` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1515 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1511 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1509 | `npm run prepublishOnly && mocha test/test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1509 | `standard && istanbul cover _mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1504 | `mocha test --compilers js:babel-core/register` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1493 | `mocha --reporter dot` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1490 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1487 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1485 | `mocha --opts test/opts/mocha.opts` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1478 | `mocha -R spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1470 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [samccone/drool](https://github.com/samccone/drool) | 1463 | `mocha test/tests.js --timeout=10000` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1302 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1302 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1297 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [variety/variety](https://github.com/variety/variety) | 1287 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1277 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1272 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1264 | `mocha tests` | 
| [normalize/mz](https://github.com/normalize/mz) | 1261 | `mocha --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1250 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1246 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1239 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1231 | `node ./node_modules/mocha/bin/mocha tests` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1230 | `mocha test` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1214 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1213 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1211 | `mocha --recursive -r tests/setup tests` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1210 | `mocha --reporter spec --bail --check-leaks test/` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1207 | `mocha test/test.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1207 | `mocha --reporter spec --bail --check-leaks test/` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1205 | `npm-run-all test:jest test:server:mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1204 | `mocha --reporter spec test --recursive` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1194 | `mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1182 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1179 | `mocha $(find test -name '*.test.js') --exit` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1178 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1176 | `mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1170 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1168 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1168 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1161 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1160 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1157 | `istanbul cover _mocha test/*.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1155 | `webpack && mocha test/unit` | 
| [electron/spectron](https://github.com/electron/spectron) | 1149 | `mocha && standard` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1135 | `standard && mocha -b` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1133 | `mocha test/*` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1131 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1130 | `eslint src test && mocha --compilers babel-register` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1128 | `npm run lint && npm run mocha` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1102 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1102 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1098 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1097 | `node_modules/.bin/mocha && npm run lint` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1093 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1088 | `mocha test/tests.js` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1083 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 1082 | `mocha test` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1071 | `mocha --async-only` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1064 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [gulp-sourcemaps/gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) | 1018 | `mocha --async-only` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 1009 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1007 | `mocha -R list` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1007 | `mocha --check-leaks -R dot` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 997 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 989 | `mocha "client.test" --compilers js:babel-register` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 983 | `mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 983 | `mocha --reporter spec` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 982 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 981 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 979 | `mocha -t 600000 --exit` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 979 | `mocha` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 979 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 1055 | `mocha --recursive ./test/*_spec.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1051 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1039 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1038 | `mocha --recursive test/unit/` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1033 | `mocha --reporter spec --bail --check-leaks test/` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 1032 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1030 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1027 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1027 | `mocha spec/*.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1026 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1024 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1024 | `mocha --reporter spec --timeout 3000` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1022 | `npm run lint && mocha -R spec` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1030 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1027 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1027 | `mocha spec/*.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1026 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1024 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1024 | `mocha --reporter spec --timeout 3000` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1022 | `npm run lint && mocha -R spec` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1018 | `./node_modules/.bin/mocha -R spec` | 
| [gulp-sourcemaps/gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) | 1018 | `mocha --async-only` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1017 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1010 | `mocha --compilers js:babel-register test/*.js` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 1009 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1007 | `mocha -R list` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 1007 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1007 | `mocha --check-leaks -R dot` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1006 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 920 | `mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 919 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 914 | `mocha test` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 908 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 900 | `node_modules/.bin/mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 898 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 897 | `mocha --timeout 200000` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 887 | `mocha --harmony tests/**` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 883 | `mocha` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 883 | `npm run lint && mocha` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 943 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 943 | `istanbul cover -- _mocha --reporter spec` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 937 | `mocha --timeout 5000` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 931 | `mocha test/index.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 929 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 926 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 923 | `mocha -t 5000` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 922 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 914 | `mocha test` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 913 | `mocha` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 911 | `mocha -r should --exit test/*.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 908 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 908 | `npm run lint && npm run mocha:no-functional` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 901 | `npm run build && istanbul test _mocha test/test.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 900 | `node_modules/.bin/mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 898 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 897 | `mocha --timeout 200000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 892 | `node_modules/.bin/mocha test/spec` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 892 | `mocha --harmony --full-trace --check-leaks` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 889 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 887 | `mocha --reporter list` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 887 | `mocha --harmony tests/**` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 885 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 883 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 878 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 874 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 870 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 867 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 863 | `mocha --reporter spec --bail --check-leaks test/` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 859 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 857 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 855 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 855 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 853 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 844 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 842 | `mocha test` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 841 | `mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 839 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 837 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 835 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 833 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 832 | `mocha && ember test` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 847 | `mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 844 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 842 | `mocha test` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 841 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 841 | `mocha --async-only` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 839 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 837 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [ebradyjobory/finance.js](https://github.com/ebradyjobory/finance.js) | 837 | `mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 835 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 835 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 833 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 832 | `mocha test` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 832 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 832 | `mocha && ember test` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 831 | `npm run mocha-test test/integration` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 830 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 828 | `_mocha` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 828 | `mocha test/mocha.js test/crc/index.js` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 825 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 823 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 822 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 819 | `mocha --colors --reporter spec test.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 818 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 813 | `mocha` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 811 | `mocha index.test.js` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 810 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 809 | `mocha test` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 807 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 805 | `eslint . && mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 817 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 813 | `mocha` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 811 | `mocha index.test.js` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 810 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 809 | `mocha test` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 807 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 805 | `eslint . && mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 803 | `mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 803 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 802 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 800 | `jenkins-mocha ./tests/*.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 798 | `mocha --no-timeouts` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 798 | `xo && mocha -R spec` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 797 | `npm run lint && npm run mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 796 | `nyc mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 793 | `mocha tests --timeout 10000` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 792 | `mocha --recursive -s 15 test/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 718 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 709 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 707 | `mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 705 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 700 | `mocha -t 5000 -b -R spec test/index` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 700 | `npm -s run mocha && npm run -s lint` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 699 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 698 | `./node_modules/.bin/mocha` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 767 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 766 | `./bin/selenium-standalone install && mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 765 | `mocha --reporter spec build/test/index.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 762 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 756 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 746 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 745 | `mocha test.js` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 744 | `mocha --compilers js:babel-core/register` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 743 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 743 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 742 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 742 | `mocha --reporter spec --bail --check-leaks test/` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 742 | `mocha` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 741 | `npm run bundle && mocha` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 739 | `mocha ./test/test.js --timeout 1000000` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 739 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 738 | `mocha $(find test -name '*.test.js')` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 738 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 737 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 737 | `mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 737 | `mocha` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 735 | `mocha --reporter spec test/` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 718 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 717 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 716 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 715 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 709 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 707 | `mocha` | 