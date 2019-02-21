# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:37 02/21/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45242 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42501 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42286 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30929 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25842 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25336 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25248 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 21603 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20206 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18648 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18132 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18021 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17655 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15420 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15095 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14745 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14069 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13771 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13338 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13053 | `mocha 'test/**/*.spec.js'` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12842 | `istanbul cover _mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12841 | `mocha --reporter spec test/*-test.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12621 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12580 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12379 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12367 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11668 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11377 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11257 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10963 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10908 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10717 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10634 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10463 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9915 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9832 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9736 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9607 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9506 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9464 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9365 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9159 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8974 | `mocha test/src` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8919 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 8835 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8713 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8627 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8594 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8487 | `grunt clean:test && mocha --exit` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8449 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8310 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8281 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8260 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8085 | `npm run eslint && npm run mocha` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8076 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8062 | `./node_modules/.bin/mocha test` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8027 | `mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7989 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7915 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7616 | `npm run build && istanbul cover _mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7607 | `mocha --compilers js:babel-core/register` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7598 | `mocha --exit --require @babel/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7593 | `mocha; jshint *.js lib` | 
| [dthree/cash](https://github.com/dthree/cash) | 7586 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7553 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7450 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7351 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7227 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7136 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7094 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7052 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6968 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6611 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6422 | `npm run test:mocha:src` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6359 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6350 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6305 | `mocha tests/node.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6261 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6239 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6190 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6131 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6094 | `standard && mocha` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6094 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6067 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5906 | `mocha && eslint lib/**` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5861 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5857 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5808 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [teambit/bit](https://github.com/teambit/bit) | 5780 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5733 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5670 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5638 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5604 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5443 | `mocha -r esm` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5400 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5386 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5382 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5386 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5382 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5211 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5210 | `mocha src/**/*Tests.js --harmony` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5135 | `gulp lint && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5129 | `mocha --color` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5115 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5082 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5027 | `nyc mocha --exit` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4981 | `gulp build; mocha;` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4975 | `nyc mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4936 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4927 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4905 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4877 | `mocha -R spec 'tests/app'` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4869 | `mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4859 | `mocha test` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4756 | `mocha --reporter spec -t 8000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4729 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4670 | `mocha -R spec src` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4661 | `NODE_ENV=test mocha --exit` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4587 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4568 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4487 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4481 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4455 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4414 | `mocha --check-leaks --reporter spec --bail` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4405 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4405 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4394 | `node_modules/.bin/mocha test/tests.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4389 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4361 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4311 | `npm run lint ; mocha && mocha test/individual` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4244 | `nyc mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4232 | `npm run build && cd test && mocha . --reporter dot` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4192 | `mocha -R spec ./test --recursive` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4145 | `mocha --require test/babel-hook test/*.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4145 | `mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4113 | `nyc mocha "test/**/*.test.js"` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4109 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3833 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3832 | `npm run build && mocha test/*.test.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3814 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3791 | `eslint . && mocha -t 5000` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3738 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3722 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3670 | `npm run jshint && npm run mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3643 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3596 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3575 | `nyc mocha && tsc` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3524 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3499 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3481 | `mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3791 | `eslint . && mocha -t 5000` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3787 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3745 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3738 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3722 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3681 | `standard && mocha --timeout 60000 test/test.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3679 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3677 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3670 | `npm run jshint && npm run mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3643 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3604 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3604 | `mocha tests/javascript` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3596 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3575 | `nyc mocha && tsc` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3562 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3126 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3093 | `npm run mocha && npm run lint` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3081 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3066 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3049 | `node_modules/.bin/mocha --reporter spec` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3039 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3024 | `mocha test-node` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2995 | `mocha --require @babel/register --recursive spec` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2978 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2970 | `mocha -R spec --recursive src/test` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2965 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2921 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2898 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [retejs/rete](https://github.com/retejs/rete) | 2878 | `BABEL_ENV=test mocha --compilers js:@babel/register` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2857 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2850 | `istanbul cover _mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2921 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2916 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2915 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2913 | `mocha -R spec spec spec/reporters` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2898 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [retejs/rete](https://github.com/retejs/rete) | 2878 | `BABEL_ENV=test mocha --compilers js:@babel/register` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2857 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2850 | `istanbul cover _mocha` | 
| [css/csso](https://github.com/css/csso) | 2826 | `mocha --reporter dot` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2804 | `mocha "./test/**/*-test.js"` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2786 | `mocha --require should --reporter spec` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2783 | `mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2768 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2766 | `xo && mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2731 | `nyc mocha --timeout=10000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2728 | `nyc mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2720 | `mocha --recursive --watch` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3023 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3001 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2995 | `mocha --require @babel/register --recursive spec` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2978 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2970 | `mocha -R spec --recursive src/test` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2969 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2921 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2916 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2915 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2913 | `mocha -R spec spec spec/reporters` | 
| [retejs/rete](https://github.com/retejs/rete) | 2878 | `BABEL_ENV=test mocha --compilers js:@babel/register` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2857 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2850 | `istanbul cover _mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2786 | `mocha --require should --reporter spec` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2783 | `mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2768 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2766 | `xo && mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2731 | `nyc mocha --timeout=10000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2728 | `nyc mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2720 | `mocha --recursive --watch` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2700 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2696 | `mocha test/unit --require mochahook` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2695 | `mocha --timeout 100000` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2671 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2621 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2451 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2416 | `npm run build && mocha --require babel-register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2387 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2366 | `node node_modules/mocha/bin/_mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2323 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [gajus/swing](https://github.com/gajus/swing) | 2321 | `mocha --compilers js:babel-register` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2303 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2300 | `mocha test/**/*.coffee` | 
| [pahen/madge](https://github.com/pahen/madge) | 2341 | `npm run lint && npm run mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2323 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [gajus/swing](https://github.com/gajus/swing) | 2321 | `mocha --compilers js:babel-register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2320 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2309 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2303 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2300 | `mocha test/**/*.coffee` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2293 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2289 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2244 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2238 | `mocha && eslint *.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2289 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2272 | `standard && mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2244 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2242 | `npm run lint && mocha tests/**/*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2238 | `mocha && eslint *.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 2224 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2212 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2206 | `mocha --timeout 15000 --bail --exit test/*-test.js test/security/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2204 | `mocha test/runner.js --reporter spec` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2192 | `cross-env BABEL_ENV=test mocha` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2180 | `mocha test/test-*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2172 | `mocha --compilers js:babel-register` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2164 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2156 | `mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2147 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2144 | `mocha --compilers js:babel-core/register __tests__` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2136 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2134 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2119 | `mocha test` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2098 | `mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 2091 | `mocha test/*.test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2079 | `npm run mocha && npm run karma` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2070 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2054 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2054 | `mocha tests --require @babel/register` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2053 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2052 | `mocha && npm run lint` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2039 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2027 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 2018 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2016 | `mocha --require=test/test_helper.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 2005 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [slate/slate](https://github.com/slate/slate) | 1994 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1979 | `mocha --require ./test/common --growl test/expect.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1979 | `mocha test/**/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1965 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1953 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1918 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1907 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1894 | `mocha ./test/basic.js -t 5000` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1882 | `mocha tests.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1865 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1857 | `eslint --cache . && tsc && mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1854 | `npm run lint && npm run mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1840 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1814 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1865 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1857 | `eslint --cache . && tsc && mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1854 | `npm run lint && npm run mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1846 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1840 | `npm run lint && npm run mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1826 | `mocha test/setup.js test/spec/*.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1820 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1814 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1808 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1624 | `mocha --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1616 | `mocha test/unit` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1601 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1586 | `mocha tests/test-*` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1584 | `nyc mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1574 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1560 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1554 | `node_modules/.bin/mocha --recursive` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1549 | `npm run lint && npm run mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1549 | `npm run test:lint && npm run test:mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1544 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1536 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1531 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1586 | `mocha tests/test-*` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1574 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1554 | `node_modules/.bin/mocha --recursive` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1549 | `npm run lint && npm run mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1549 | `npm run test:lint && npm run test:mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1544 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1541 | `mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1539 | `mocha -u tdd` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1536 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1536 | `npm run lint && mocha && karma start --single-run` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1531 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1531 | `mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1526 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1517 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1516 | `mocha --timeout 10000 ./tests/lib.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1511 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [noble/bleno](https://github.com/noble/bleno) | 1509 | `mocha -R spec test/*.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1620 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1614 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1608 | `mocha -R spec ./test/unit/**` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1586 | `mocha tests/test-*` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1584 | `nyc mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1574 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1563 | `mocha --check-leaks --require @babel/register` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1560 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1554 | `node_modules/.bin/mocha --recursive` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1549 | `npm run lint && npm run mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1549 | `npm run test:lint && npm run test:mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1463 | `mocha test/tests.js --timeout=10000` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1460 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1442 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1439 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1434 | `npm run build && mocha -r should` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1433 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [electron/devtron](https://github.com/electron/devtron) | 1422 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1420 | `webpack && npm run lint && npm run mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1414 | `istanbul cover _mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1407 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1404 | `mocha --check-leaks --reporter spec --bail test/` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1391 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1390 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1389 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1386 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1378 | `NODE_PATH=. mocha **/*.spec.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1377 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1372 | `cross-env NODE_ENV=test nyc mocha` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1347 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1345 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1263 | `mocha tests` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1260 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1259 | `mocha --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1247 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1246 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [electron/asar](https://github.com/electron/asar) | 1239 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1230 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1220 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1210 | `mocha test` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1202 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1198 | `mocha --reporter spec --bail --check-leaks test/` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1196 | `npm-run-all test:jest test:server:mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1191 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1190 | `xo && mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1186 | `mocha --reporter spec test --recursive` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1177 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1176 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1176 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1172 | `mocha $(find test -name '*.test.js') --exit` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1168 | `mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1168 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1168 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1153 | `webpack && mocha test/unit` | 
| [electron/spectron](https://github.com/electron/spectron) | 1147 | `mocha && standard` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1134 | `standard && mocha -b` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1131 | `mocha test/*` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1129 | `eslint src test && mocha --compilers babel-register` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1116 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [tomas/needle](https://github.com/tomas/needle) | 1076 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1070 | `mocha --async-only` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1061 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1050 | `mocha test/*.test.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1049 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1049 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1039 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1036 | `mocha --recursive test/unit/` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1033 | `mocha --reporter spec --bail --check-leaks test/` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1081 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 1076 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1070 | `mocha --async-only` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1061 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1054 | `mocha $(find test -name '*.test.js')` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1050 | `mocha test/*.test.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1049 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 1048 | `mocha --recursive ./test/*_spec.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1006 | `mocha --check-leaks -R dot` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 1005 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1005 | `mocha -R list` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 1002 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 996 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 987 | `mocha "client.test" --compilers js:babel-register` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 983 | `mocha --reporter spec` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 979 | `npm run rollup-cjs && mocha test/test.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 978 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 976 | `mocha -t 600000 --exit` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 976 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 975 | `mocha tests` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 975 | `mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 947 | `mocha` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 943 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 939 | `istanbul cover -- _mocha --reporter spec` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 937 | `mocha --timeout 5000` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 920 | `mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 919 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 916 | `mocha test/index.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 916 | `mocha -t 5000` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 914 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 913 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 916 | `mocha -t 5000` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 914 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 914 | `mocha test` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 910 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 906 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 899 | `node_modules/.bin/mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 896 | `mocha --timeout 200000` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 892 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 885 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 964 | `nyc mocha specs` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 963 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 963 | `./node_modules/.bin/mocha --reporter spec` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 962 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 962 | `mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 954 | `./node_modules/.bin/mocha test/**/*` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 951 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 948 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 948 | `standard && standard ./bin/* && mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 947 | `mocha` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 947 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 951 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 948 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 948 | `standard && standard ./bin/* && mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 947 | `mocha` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 947 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 943 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 942 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 939 | `mocha test` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 939 | `istanbul cover -- _mocha --reporter spec` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 937 | `mocha --timeout 5000` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [susam/texme](https://github.com/susam/texme) | 768 | `standard && mocha` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 768 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 764 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 761 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 759 | `./node_modules/.bin/mocha tests/*.js` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 758 | `mocha 'test/**/*.tests.js'` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 752 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 751 | `mocha tests/*.mocha.js` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 748 | `npm run test-mocha && npm run test-karma` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [electron/apps](https://github.com/electron/apps) | 743 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 740 | `mocha` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 738 | `mocha ./test/test.js --timeout 1000000` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 736 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 736 | `mocha $(find test -name '*.test.js')` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 735 | `mocha --reporter spec test/` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 733 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 733 | `mocha` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 731 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 730 | `mocha` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 736 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 736 | `mocha $(find test -name '*.test.js')` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 736 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 735 | `mocha --reporter spec test/` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 733 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 733 | `mocha` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 731 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 730 | `mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 729 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 727 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 726 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 726 | `mocha --reporter spec` | 
| [formio/formio](https://github.com/formio/formio) | 725 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 723 | `mocha ./test/index.js` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 711 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 707 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 706 | `mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 705 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 699 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 698 | `jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 694 | `_mocha -u bdd --colors test/` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 694 | `mocha` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 694 | `npm -s run mocha && npm run -s lint` | 
| [afc163/fanyi](https://github.com/afc163/fanyi) | 685 | `npm run lint && mocha tests/index.js --timeout 0` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 684 | `mocha --require babel-register src/**/*.spec.js src/*.spec.js` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 683 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 683 | `mocha --compilers js:babel-register` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 683 | `mocha --bail test/` | 
| [apollographql/eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) | 682 | `tav --ci && mocha test/index.js` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 681 | `mocha -R spec` | 
| [shime/livedown](https://github.com/shime/livedown) | 676 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 673 | `mocha --require babel-register` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 671 | `mocha -b -R spec test/*` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 671 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [godaddy/terminus](https://github.com/godaddy/terminus) | 670 | `mocha index.spec.js lib/**/*.spec.js && npm run test-typings` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 694 | `npm -s run mocha && npm run -s lint` | 
| [Kagami/ffmpeg.js](https://github.com/Kagami/ffmpeg.js) | 690 | `mocha test/test.js` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 690 | `npm run lint && mocha test` | 
| [afc163/fanyi](https://github.com/afc163/fanyi) | 685 | `npm run lint && mocha tests/index.js --timeout 0` | 
| [Savjee/SavjeeCoin](https://github.com/Savjee/SavjeeCoin) | 684 | `mocha tests/*.test.js` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 684 | `mocha --require babel-register src/**/*.spec.js src/*.spec.js` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 683 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 683 | `mocha --compilers js:babel-register` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 683 | `mocha --bail test/` | 
| [apollographql/eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) | 682 | `tav --ci && mocha test/index.js` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 681 | `mocha -R spec` | 
| [theoephraim/node-google-spreadsheet](https://github.com/theoephraim/node-google-spreadsheet) | 661 | `node_modules/.bin/mocha` | 
| [joaonuno/tree-model-js](https://github.com/joaonuno/tree-model-js) | 661 | `istanbul cover _mocha` | 
| [dtschust/redux-bug-reporter](https://github.com/dtschust/redux-bug-reporter) | 660 | `standard && mocha --compilers js:babel-register --recursive --require test/setup.js` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 660 | `mocha --recursive --compilers js:babel-core/register` | 
| [esnext/esnext](https://github.com/esnext/esnext) | 659 | `mocha` | 
| [Ivshti/linvodb3](https://github.com/Ivshti/linvodb3) | 659 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [Munter/subfont](https://github.com/Munter/subfont) | 659 | `npm run lint && mocha` | 
| [gtanner/qrcode-terminal](https://github.com/gtanner/qrcode-terminal) | 659 | `./node_modules/jshint/bin/jshint lib vendor && node example/basic.js && ./node_modules/mocha/bin/mocha -R nyan` | 
| [maxkueng/victor](https://github.com/maxkueng/victor) | 659 | `mocha --ui bdd --reporter spec` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 658 | `mocha --reporter spec` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 658 | `mocha` | 
| [anandanand84/technicalindicators](https://github.com/anandanand84/technicalindicators) | 657 | `mocha --compilers js:babel-register --require babel-polyfill` | 
| [pburtchaell/react-notification](https://github.com/pburtchaell/react-notification) | 657 | `node_modules/.bin/mocha --compilers js:babel-core/register --reporter spec --recursive --timeout 5000 test/setup.js test/**/*.js` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 657 | `mocha` | 
| [LouisBarranqueiro/reapop](https://github.com/LouisBarranqueiro/reapop) | 656 | `babel-node ./node_modules/karma/bin/karma start ./build/karma.conf.js --reporters mocha` | 
| [kwhitley/apicache](https://github.com/kwhitley/apicache) | 656 | `nyc mocha $(find test -name '*.test.js') --recursive` | 
| [jbrooksuk/node-summary](https://github.com/jbrooksuk/node-summary) | 655 | `mocha --compilers js:babel-core/register --require should --reporter spec` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 654 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 651 | `./node_modules/.bin/mocha test/integration` | 
| [docpress/docpress](https://github.com/docpress/docpress) | 649 | `nyc mocha` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 649 | `./node_modules/.bin/mocha --bail` | 
| [pocketjoso/specificity-graph](https://github.com/pocketjoso/specificity-graph) | 636 | `node_modules/.bin/mocha test` | 
| [fent/node-ytdl](https://github.com/fent/node-ytdl) | 634 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [vault-development/react-native-svg-uri](https://github.com/vault-development/react-native-svg-uri) | 634 | `./node_modules/mocha/bin/mocha --compilers js:babel-core/register` | 
| [werk85/node-html-to-text](https://github.com/werk85/node-html-to-text) | 633 | `istanbul cover _mocha && eslint .` | 
| [jaredhanson/passport-google-oauth](https://github.com/jaredhanson/passport-google-oauth) | 630 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [blueberryapps/react-bluekit](https://github.com/blueberryapps/react-bluekit) | 627 | `mocha --compilers js:babel/register --recursive` | 
| [DEgITx/rats-search](https://github.com/DEgITx/rats-search) | 626 | `mocha temp/tests.js --require @babel/core/lib --require source-map-support/register` | 
| [susielu/d3-legend](https://github.com/susielu/d3-legend) | 625 | `mocha` | 
| [mysamai/mysam](https://github.com/mysamai/mysam) | 625 | `npm run lint && npm run mocha` | 
| [M6Web/websocket-bench](https://github.com/M6Web/websocket-bench) | 624 | `gulp mocha` | 
| [duaraghav8/Ethlint](https://github.com/duaraghav8/Ethlint) | 619 | `nyc --reporter=text --reporter=html mocha --require should --reporter spec --recursive` | 
| [gameclosure/devkit](https://github.com/gameclosure/devkit) | 617 | `mocha --reporter spec --recursive -C ./tests` | 
| [w0rm/gulp-svgstore](https://github.com/w0rm/gulp-svgstore) | 617 | `gulp build && mocha test.js` | 
| [adamjmcgrath/react-native-simple-auth](https://github.com/adamjmcgrath/react-native-simple-auth) | 615 | `mocha lib/**/*.test.js --require babel-register` | 
| [omnidan/node-emoji](https://github.com/omnidan/node-emoji) | 611 | `./node_modules/.bin/mocha --require should --bail --reporter spec test/*` | 
| [koajs/session](https://github.com/koajs/session) | 611 | `npm run lint && NODE_ENV=test mocha --exit --require should --reporter spec test/*.test.js` | 
| [mattyork/fuzzy](https://github.com/mattyork/fuzzy) | 610 | `./node_modules/.bin/mocha` | 
| [webdriverio-boneyard/webdrivercss](https://github.com/webdriverio-boneyard/webdrivercss) | 609 | `./node_modules/.bin/mocha` | 
| [desmondmorris/node-tesseract](https://github.com/desmondmorris/node-tesseract) | 609 | `mocha` | 
| [shinnn/gulp-gh-pages](https://github.com/shinnn/gulp-gh-pages) | 607 | `nyc mocha test.js --timeout 50000 --full-trace` | 
| [gauntface/simple-push-demo](https://github.com/gauntface/simple-push-demo) | 641 | `gulp && npm run lint && node ./test/helpers/download-browsers.js && mocha` | 
| [tonyhb/redux-ui](https://github.com/tonyhb/redux-ui) | 640 | `$(npm bin)/mocha  --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [phodal/sherlock](https://github.com/phodal/sherlock) | 640 | `mocha --reporter spec` | 
| [ideal-postcodes/postcodes.io](https://github.com/ideal-postcodes/postcodes.io) | 638 | `NODE_ENV=test npm run test:create && npm run nyc_mocha && NODE_ENV=test npm run test:clear && npm run lint` | 
| [floatdrop/gulp-watch](https://github.com/floatdrop/gulp-watch) | 637 | `xo && mocha -r test/util/set-default-options -t 5000 -R spec test/test-*` | 
| [aliyun-UED/aliyun-sdk-js](https://github.com/aliyun-UED/aliyun-sdk-js) | 637 | `mocha test` | 
| [pocketjoso/specificity-graph](https://github.com/pocketjoso/specificity-graph) | 636 | `node_modules/.bin/mocha test` | 
| [edankwan/penis.js](https://github.com/edankwan/penis.js) | 636 | `mocha --ui bdd --reporter spec test/` | 
| [danawoodman/react-fontawesome](https://github.com/danawoodman/react-fontawesome) | 635 | `mocha` | 
| [fent/node-ytdl](https://github.com/fent/node-ytdl) | 634 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [vault-development/react-native-svg-uri](https://github.com/vault-development/react-native-svg-uri) | 634 | `./node_modules/mocha/bin/mocha --compilers js:babel-core/register` | 
| [werk85/node-html-to-text](https://github.com/werk85/node-html-to-text) | 633 | `istanbul cover _mocha && eslint .` | 
| [jaredhanson/passport-google-oauth](https://github.com/jaredhanson/passport-google-oauth) | 630 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [tj/node-blocked](https://github.com/tj/node-blocked) | 630 | `./node_modules/mocha/bin/mocha` | 
| [webdriverio-boneyard/webdrivercss](https://github.com/webdriverio-boneyard/webdrivercss) | 609 | `./node_modules/.bin/mocha` | 
| [desmondmorris/node-tesseract](https://github.com/desmondmorris/node-tesseract) | 609 | `mocha` | 
| [shinnn/gulp-gh-pages](https://github.com/shinnn/gulp-gh-pages) | 607 | `nyc mocha test.js --timeout 50000 --full-trace` | 
| [cgross/generator-cg-angular](https://github.com/cgross/generator-cg-angular) | 606 | `mocha` | 
| [victorb/autochecker](https://github.com/victorb/autochecker) | 605 | `mocha` | 
| [ipfs-shipyard/ipfs-desktop](https://github.com/ipfs-shipyard/ipfs-desktop) | 600 | `cross-env NODE_ENV=test mocha` | 
| [Charca/bootbot](https://github.com/Charca/bootbot) | 600 | `mocha --recursive test/*` | 
| [rofrischmann/react-look](https://github.com/rofrischmann/react-look) | 599 | `npm run lint && mocha --recursive --compilers js:babel/register` | 
| [filamentgroup/glyphhanger](https://github.com/filamentgroup/glyphhanger) | 599 | `mocha` | 
| [opencomponents/oc](https://github.com/opencomponents/oc) | 599 | `npm run build && node tasks/mochaTest.js` | 
| [putaoshu/jdf](https://github.com/putaoshu/jdf) | 598 | `mocha test/index.js` | 
| [ck86/main-bower-files](https://github.com/ck86/main-bower-files) | 597 | `mocha` | 
| [matthewmueller/graph.ql](https://github.com/matthewmueller/graph.ql) | 597 | `./node_modules/.bin/mocha` | 
| [SamyPesse/gitkit-js](https://github.com/SamyPesse/gitkit-js) | 596 | `./node_modules/.bin/mocha ./testing/setup.js ./lib/**/*/__tests__/*.js --bail --reporter=list` | 