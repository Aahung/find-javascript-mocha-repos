# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:19 02/22/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45255 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42515 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42292 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30932 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 26091 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25852 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25353 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25251 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 21612 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20213 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18661 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18141 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18028 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17677 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15426 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15105 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14747 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14072 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13775 | `mocha --globals document test` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13775 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13354 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13056 | `mocha 'test/**/*.spec.js'` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12849 | `istanbul cover _mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12842 | `mocha --reporter spec test/*-test.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12636 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12592 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12385 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12370 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11676 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11387 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11259 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10970 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10915 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10467 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9924 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9837 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9737 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9611 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9506 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9467 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9365 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9173 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8977 | `mocha test/src` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 8845 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8715 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8631 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8595 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8486 | `grunt clean:test && mocha --exit` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8926 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 8845 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8715 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8631 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8595 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8486 | `grunt clean:test && mocha --exit` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8458 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8308 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8283 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8269 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8087 | `npm run eslint && npm run mocha` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8080 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8065 | `./node_modules/.bin/mocha test` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8040 | `mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7994 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7919 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7617 | `npm run build && istanbul cover _mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7610 | `mocha --compilers js:babel-core/register` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7606 | `mocha --exit --require @babel/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7598 | `mocha; jshint *.js lib` | 
| [dthree/cash](https://github.com/dthree/cash) | 7587 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7584 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7451 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7373 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7228 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7143 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7096 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7057 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6974 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6613 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6423 | `npm run test:mocha:src` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6364 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6352 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6306 | `mocha tests/node.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6263 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6242 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6196 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6136 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6118 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6104 | `standard && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6068 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4391 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4317 | `npm run lint ; mocha && mocha test/individual` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4235 | `npm run build && cd test && mocha . --reporter dot` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4192 | `mocha -R spec ./test --recursive` | 
| [muicss/mui](https://github.com/muicss/mui) | 4145 | `mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4115 | `nyc mocha "test/**/*.test.js"` | 
| [tj/ejs](https://github.com/tj/ejs) | 4100 | `mocha --require should --reporter spec` | 
| [expressjs/session](https://github.com/expressjs/session) | 4053 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4041 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3980 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3960 | `NODE_ENV=test mocha test/**/*.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5385 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5219 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5209 | `mocha src/**/*Tests.js --harmony` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5136 | `gulp lint && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5129 | `mocha --color` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5117 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5084 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5035 | `nyc mocha --exit` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4983 | `gulp build; mocha;` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4979 | `nyc mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4938 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4927 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4905 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4878 | `mocha -R spec 'tests/app'` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4870 | `mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4860 | `mocha test` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4763 | `NODE_ENV=test mocha --exit` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4756 | `mocha --reporter spec -t 8000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4732 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4673 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4587 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4568 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4487 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4485 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4458 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4418 | `mocha --check-leaks --reporter spec --bail` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4410 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4363 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4317 | `npm run lint ; mocha && mocha test/individual` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4235 | `npm run build && cd test && mocha . --reporter dot` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4192 | `mocha -R spec ./test --recursive` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4146 | `mocha --require test/babel-hook test/*.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4145 | `mocha` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4109 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4100 | `mocha --require should --reporter spec` | 
| [expressjs/session](https://github.com/expressjs/session) | 4053 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4041 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3980 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3960 | `NODE_ENV=test mocha test/**/*.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3861 | `mocha && tsc -p ./test/types` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3858 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3834 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3796 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3788 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3746 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3741 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3681 | `standard && mocha --timeout 60000 test/test.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3681 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3679 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3670 | `npm run jshint && npm run mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3604 | `mocha tests/javascript` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3580 | `nyc mocha && tsc` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3528 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3681 | `standard && mocha --timeout 60000 test/test.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3681 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3679 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3605 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3604 | `mocha tests/javascript` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3598 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3580 | `nyc mocha && tsc` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3562 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3528 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3523 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3501 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3495 | `node_modules/.bin/mocha test/lib/` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3486 | `mocha` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3465 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3274 | `mocha test/*.js` | 
| [mde/ejs](https://github.com/mde/ejs) | 3256 | `mocha --require should --reporter spec` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3253 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3232 | `mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3222 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3193 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3189 | `./node_modules/.bin/mocha test/test.*.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3181 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3176 | `mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3128 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3111 | `nyc mocha --recursive` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3103 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3095 | `npm run mocha && npm run lint` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3066 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3051 | `node_modules/.bin/mocha --reporter spec` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3040 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3274 | `mocha test/*.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3258 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3256 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [mde/ejs](https://github.com/mde/ejs) | 3256 | `mocha --require should --reporter spec` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3253 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3232 | `mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3222 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3193 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3189 | `./node_modules/.bin/mocha test/test.*.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3181 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3176 | `mocha` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3111 | `nyc mocha --recursive` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3103 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3085 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3066 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3051 | `node_modules/.bin/mocha --reporter spec` | 
| [pahen/madge](https://github.com/pahen/madge) | 2345 | `npm run lint && npm run mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2323 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [gajus/swing](https://github.com/gajus/swing) | 2322 | `mocha --compilers js:babel-register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2320 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2308 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2289 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2244 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [share/sharedb](https://github.com/share/sharedb) | 2226 | `./node_modules/.bin/mocha && npm run jshint` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2192 | `cross-env BABEL_ENV=test mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2174 | `mocha --compilers js:babel-register` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2164 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2147 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2134 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2636 | `mocha-phantomjs ./test/index.html` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2622 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2595 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2590 | `mocha test --exit && npm run lint` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2581 | `TEST=all mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2577 | `mocha && eslint .` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2574 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2571 | `mocha test/src/**/*.unit.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2558 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2549 | `nyc --reporter=html --reporter=text mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2546 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2532 | `export TESTING=true; mocha --reporter list` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2529 | `mocha --reporter=spec test/*-test.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2510 | `mocha` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2399 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2387 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2366 | `node node_modules/mocha/bin/_mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 2345 | `npm run lint && npm run mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2323 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [gajus/swing](https://github.com/gajus/swing) | 2322 | `mocha --compilers js:babel-register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2320 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2316 | `mocha test/**/*.coffee` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2308 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2147 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2134 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2124 | `mocha test` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2098 | `mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 2091 | `mocha test/*.test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2083 | `npm run mocha && npm run karma` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2073 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2057 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2057 | `mocha tests --require @babel/register` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2056 | `npm run lint && mocha -R dot && npm run cover` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2053 | `mocha && npm run lint` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2039 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2027 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2016 | `mocha --require=test/test_helper.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1757 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1750 | `mocha test/*.js` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1742 | `./node_modules/.bin/mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1741 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1739 | `mocha --check-leaks --reporter spec --bail` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1731 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1726 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1724 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1723 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1715 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1696 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1690 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1686 | `mocha && size-limit` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1671 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1671 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1669 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1667 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1665 | `mocha spec` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1652 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1642 | `mocha tests/test.js` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1632 | `mocha --reporter spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1626 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1625 | `mocha --recursive` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1621 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1621 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1614 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1612 | `mocha -R spec ./test/unit/**` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1605 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1598 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1551 | `npm run lint && npm run mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1549 | `npm run test:lint && npm run test:mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1546 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1537 | `npm run lint && mocha && karma start --single-run` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1536 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1531 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1531 | `mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1526 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1518 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1516 | `mocha --timeout 10000 ./tests/lib.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1514 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1500 | `standard && istanbul cover _mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1499 | `npm run prepublishOnly && mocha test/test.js` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1485 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1484 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [samccone/drool](https://github.com/samccone/drool) | 1463 | `mocha test/tests.js --timeout=10000` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1461 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1546 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1542 | `mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1537 | `npm run lint && mocha && karma start --single-run` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1536 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1531 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1531 | `mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1526 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1524 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1518 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1516 | `mocha --timeout 10000 ./tests/lib.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1514 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1512 | `mocha test/**/*.spec.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1506 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1502 | `mocha --recursive test` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1500 | `standard && istanbul cover _mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1499 | `npm run prepublishOnly && mocha test/test.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1415 | `istanbul cover _mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1406 | `mocha --check-leaks --reporter spec --bail test/` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1404 | `npm run mocha:istanbul` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1398 | `mocha --recursive` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1388 | `./node_modules/mocha/bin/mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1387 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1384 | `NODE_PATH=. mocha **/*.spec.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1380 | `./node_modules/.bin/mocha test` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1379 | `mocha --compilers js:babel-core/register` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1372 | `cross-env NODE_ENV=test nyc mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1367 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1362 | `npm run lint && mocha --require @babel/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1347 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1425 | `webpack && npm run lint && npm run mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1424 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [electron/devtron](https://github.com/electron/devtron) | 1422 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1415 | `istanbul cover _mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1415 | `mocha --recursive test/bin` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1406 | `mocha --check-leaks --reporter spec --bail test/` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1404 | `npm run mocha:istanbul` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1398 | `mocha --recursive` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1391 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1390 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1388 | `./node_modules/mocha/bin/mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1387 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1384 | `NODE_PATH=. mocha **/*.spec.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1380 | `./node_modules/.bin/mocha test` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1379 | `mocha --compilers js:babel-core/register` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1377 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1388 | `./node_modules/mocha/bin/mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1384 | `NODE_PATH=. mocha **/*.spec.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1380 | `./node_modules/.bin/mocha test` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1379 | `mocha --compilers js:babel-core/register` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1377 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1372 | `cross-env NODE_ENV=test nyc mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1367 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1362 | `npm run lint && mocha --require @babel/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1347 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1344 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1341 | `mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1322 | `mocha-phantomjs tests/index.html` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1320 | `mocha src/test.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1320 | `mocha --timeout 30000 --recursive ./tests` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1319 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1317 | `mocha --timeout 20000` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1316 | `mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1310 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1307 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1305 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1301 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1297 | `istanbul test _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1296 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1293 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1292 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1248 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [electron/asar](https://github.com/electron/asar) | 1239 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1237 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1230 | `node ./node_modules/mocha/bin/mocha tests` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1223 | `mocha test` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1213 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1207 | `mocha test/test.js` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1205 | `mocha --recursive -r tests/setup tests` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1203 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1203 | `mocha --reporter spec --bail --check-leaks test/` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 996 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 993 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 987 | `mocha "client.test" --compilers js:babel-register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 983 | `mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 983 | `mocha --reporter spec` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 979 | `npm run rollup-cjs && mocha test/test.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 978 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 976 | `mocha -t 600000 --exit` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 973 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 967 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 964 | `nyc mocha specs` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 963 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 963 | `./node_modules/.bin/mocha --reporter spec` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 962 | `mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 956 | `./node_modules/.bin/mocha test/**/*` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 839 | `mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 837 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 831 | `mocha && ember test` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 821 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 808 | `mocha index.test.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 808 | `mocha test` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 806 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 798 | `eslint . && mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 795 | `nyc mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 792 | `mocha --recursive -s 15 test/` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 792 | `mocha --recursive -s 15 test/` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 792 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 783 | `mocha tests --timeout 10000` | 
| [koajs/static](https://github.com/koajs/static) | 782 | `mocha --harmony --reporter spec --exit` | 
| [fivdi/onoff](https://github.com/fivdi/onoff) | 778 | `nyc mocha` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 770 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [susam/texme](https://github.com/susam/texme) | 769 | `standard && mocha` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 769 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 768 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 764 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 762 | `./bin/selenium-standalone install && mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 761 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 759 | `mocha 'test/**/*.tests.js'` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 761 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 761 | `./node_modules/.bin/mocha tests/*.js` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 759 | `mocha 'test/**/*.tests.js'` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 758 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 751 | `mocha tests/*.mocha.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 747 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 746 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [electron/apps](https://github.com/electron/apps) | 745 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 742 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 741 | `npm run bundle && mocha` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 740 | `mocha` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 739 | `mocha ./test/test.js --timeout 1000000` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 739 | `mocha --compilers js:babel-core/register` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 737 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 737 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 737 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 736 | `mocha $(find test -name '*.test.js')` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 735 | `mocha --reporter spec test/` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 734 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 733 | `mocha` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 731 | `mocha` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 721 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 721 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 714 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 713 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 713 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 707 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 706 | `mocha` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 714 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 713 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 713 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 707 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 707 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [typicode/katon](https://github.com/typicode/katon) | 705 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 702 | `mocha --reporter spec` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 700 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 699 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 698 | `jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 697 | `./node_modules/.bin/mocha` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 694 | `_mocha -u bdd --colors test/` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 694 | `mocha` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 694 | `npm -s run mocha && npm run -s lint` | 
| [Kagami/ffmpeg.js](https://github.com/Kagami/ffmpeg.js) | 693 | `mocha test/test.js` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 690 | `npm run lint && mocha test` | 
| [afc163/fanyi](https://github.com/afc163/fanyi) | 686 | `npm run lint && mocha tests/index.js --timeout 0` | 
| [Savjee/SavjeeCoin](https://github.com/Savjee/SavjeeCoin) | 684 | `mocha tests/*.test.js` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 684 | `mocha --require babel-register src/**/*.spec.js src/*.spec.js` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 683 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 683 | `mocha --compilers js:babel-register` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 683 | `mocha --bail test/` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 682 | `mocha -R spec` | 
| [shime/livedown](https://github.com/shime/livedown) | 676 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 683 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 683 | `mocha --compilers js:babel-register` | 
| [apollographql/eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) | 683 | `tav --ci && mocha test/index.js` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 683 | `mocha --bail test/` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 682 | `mocha -R spec` | 
| [shime/livedown](https://github.com/shime/livedown) | 676 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [mtth/avsc](https://github.com/mtth/avsc) | 676 | `mocha` | 
| [expressjs/cookie-session](https://github.com/expressjs/cookie-session) | 675 | `mocha --check-leaks --reporter spec --bail test/` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 673 | `mocha --require babel-register` | 
| [klokantech/tileserver-gl](https://github.com/klokantech/tileserver-gl) | 672 | `mocha test/**.js --timeout 10000` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 671 | `mocha -b -R spec test/*` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 671 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [godaddy/terminus](https://github.com/godaddy/terminus) | 671 | `mocha index.spec.js lib/**/*.spec.js && npm run test-typings` | 
| [puleos/object-hash](https://github.com/puleos/object-hash) | 624 | `node ./node_modules/.bin/mocha test` | 
| [amasad/debug_utils](https://github.com/amasad/debug_utils) | 624 | `mocha ./test --bail` | 
| [manavsehgal/reactspeedcoding](https://github.com/manavsehgal/reactspeedcoding) | 623 | `NODE_ENV=test npm run elint && npm run slint && npm run test:mocha` | 
| [adamgruber/mochawesome](https://github.com/adamgruber/mochawesome) | 623 | `npm run lint && cross-env NODE_ENV=test nyc mocha` | 
| [robrich/gulp-if](https://github.com/robrich/gulp-if) | 622 | `mocha && jshint .` | 
| [webpack/memory-fs](https://github.com/webpack/memory-fs) | 619 | `mocha` | 
| [duaraghav8/Ethlint](https://github.com/duaraghav8/Ethlint) | 618 | `nyc --reporter=text --reporter=html mocha --require should --reporter spec --recursive` | 
| [gameclosure/devkit](https://github.com/gameclosure/devkit) | 617 | `mocha --reporter spec --recursive -C ./tests` | 
| [macbre/analyze-css](https://github.com/macbre/analyze-css) | 617 | `mocha -R spec` | 
| [danielbayerlein/dashboard](https://github.com/danielbayerlein/dashboard) | 611 | `export TESTING=true; mocha --reporter list` | 
| [mattyork/fuzzy](https://github.com/mattyork/fuzzy) | 610 | `./node_modules/.bin/mocha` | 
| [mattyork/fuzzy](https://github.com/mattyork/fuzzy) | 610 | `./node_modules/.bin/mocha` | 
| [webdriverio-boneyard/webdrivercss](https://github.com/webdriverio-boneyard/webdrivercss) | 609 | `./node_modules/.bin/mocha` | 
| [wclimb/Koa2-blog](https://github.com/wclimb/Koa2-blog) | 609 | `./node_modules/mocha/bin/mocha --harmony test` | 
| [desmondmorris/node-tesseract](https://github.com/desmondmorris/node-tesseract) | 609 | `mocha` | 
| [shinnn/gulp-gh-pages](https://github.com/shinnn/gulp-gh-pages) | 607 | `nyc mocha test.js --timeout 50000 --full-trace` | 
| [cgross/generator-cg-angular](https://github.com/cgross/generator-cg-angular) | 606 | `mocha` | 
| [victorb/autochecker](https://github.com/victorb/autochecker) | 605 | `mocha` | 
| [echenley/react-news](https://github.com/echenley/react-news) | 604 | `./node_modules/.bin/karma start ./test/karma.conf.js --reporters mocha,coverage` | 
| [Charca/bootbot](https://github.com/Charca/bootbot) | 602 | `mocha --recursive test/*` | 
| [filamentgroup/glyphhanger](https://github.com/filamentgroup/glyphhanger) | 600 | `mocha` | 
| [ipfs-shipyard/ipfs-desktop](https://github.com/ipfs-shipyard/ipfs-desktop) | 600 | `cross-env NODE_ENV=test mocha` | 
| [rofrischmann/react-look](https://github.com/rofrischmann/react-look) | 599 | `npm run lint && mocha --recursive --compilers js:babel/register` | 
| [opencomponents/oc](https://github.com/opencomponents/oc) | 599 | `npm run build && node tasks/mochaTest.js` | 
| [times/cardkit](https://github.com/times/cardkit) | 599 | `./node_modules/.bin/istanbul cover --dir test/coverage ./node_modules/.bin/_mocha -- --compilers js:babel-core/register --require ignore-styles` | 
| [times/cardkit](https://github.com/times/cardkit) | 599 | `./node_modules/.bin/istanbul cover --dir test/coverage ./node_modules/.bin/_mocha -- --compilers js:babel-core/register --require ignore-styles` | 
| [putaoshu/jdf](https://github.com/putaoshu/jdf) | 598 | `mocha test/index.js` | 
| [ck86/main-bower-files](https://github.com/ck86/main-bower-files) | 597 | `mocha` | 
| [SGrondin/bottleneck](https://github.com/SGrondin/bottleneck) | 597 | `mocha test` | 
| [matthewmueller/graph.ql](https://github.com/matthewmueller/graph.ql) | 597 | `./node_modules/.bin/mocha` | 
| [SamyPesse/gitkit-js](https://github.com/SamyPesse/gitkit-js) | 596 | `./node_modules/.bin/mocha ./testing/setup.js ./lib/**/*/__tests__/*.js --bail --reporter=list` | 
| [newsdev/ai2html](https://github.com/newsdev/ai2html) | 596 | `mocha --check-leaks` | 
| [GoogleChromeLabs/pwacompat](https://github.com/GoogleChromeLabs/pwacompat) | 595 | `mocha-headless-server suite.html` | 
| [justinfagnani/mixwith.js](https://github.com/justinfagnani/mixwith.js) | 595 | `mocha build/test` | 
| [teropa/redux-voting-server](https://github.com/teropa/redux-voting-server) | 593 | `mocha --compilers js:babel-core/register  --require ./test/test_helper.js  --recursive` | 
| [mbasso/react-decoration](https://github.com/mbasso/react-decoration) | 592 | `cross-env BABEL_ENV=commonjs nyc --require babel-register --require ./test/setup.js mocha --recursive` | 
| [node-opcua/node-opcua](https://github.com/node-opcua/node-opcua) | 592 | `cd packages && node --expose-gc --max-old-space-size=512 run_all_mocha_tests.js` | 
| [bitovi/documentjs](https://github.com/bitovi/documentjs) | 592 | `mocha test/test.js --reporter spec` | 
| [dleitee/valid.js](https://github.com/dleitee/valid.js) | 592 | `mocha --compilers js:babel-register` | 
| [jimpick/lambda-comments](https://github.com/jimpick/lambda-comments) | 591 | `mocha --compilers js:./babel-register` | 
| [mhart/kinesalite](https://github.com/mhart/kinesalite) | 589 | `mocha --require should --reporter spec -t $([ $REMOTE ] && echo 30s || echo 4s)` | 
| [avgjs/avg-core](https://github.com/avgjs/avg-core) | 588 | `mocha --compilers js:babel-core/register` | 
| [CharlesStover/reactn](https://github.com/CharlesStover/reactn) | 583 | `mocha -r chai/register-expect -r @babel/register -r ts-node/register "tests/**/*.spec.ts?(x)"` | 
| [mathiasbynens/emoji-regex](https://github.com/mathiasbynens/emoji-regex) | 580 | `mocha` | 
| [zpratt/react-tdd-guide](https://github.com/zpratt/react-tdd-guide) | 579 | `npm run lint && mocha */test` | 
| [orliesaurus/nodemailer-mailgun-transport](https://github.com/orliesaurus/nodemailer-mailgun-transport) | 579 | `mocha` | 
| [ziyasal/scientist.js](https://github.com/ziyasal/scientist.js) | 578 | `node ./node_modules/babel-cli/bin/babel-node.js ./node_modules/mocha/bin/_mocha --timeout 20000 tests/**/*.spec.js` | 
| [screwdriver-cd/screwdriver](https://github.com/screwdriver-cd/screwdriver) | 578 | `jenkins-mocha --recursive --timeout 3000 --exit` | 
| [nicksp/redux-webpack-es6-boilerplate](https://github.com/nicksp/redux-webpack-es6-boilerplate) | 578 | `mocha --compilers js:babel-core/register,css:./test/unit/cssNullCompiler.js --require ./test/unit/testHelper.js --recursive ./test/unit` | 
| [Spreadsheets/WickedGrid](https://github.com/Spreadsheets/WickedGrid) | 577 | `./node_modules/.bin/mocha --reporter spec` | 
| [jmreidy/grunt-browserify](https://github.com/jmreidy/grunt-browserify) | 577 | `mocha -R spec --timeout 5000` | 
| [sindresorhus/jshint-stylish](https://github.com/sindresorhus/jshint-stylish) | 575 | `xo && mocha` | 
| [mike-marcacci/node-redlock](https://github.com/mike-marcacci/node-redlock) | 572 | `istanbul cover mocha` | 
| [scrollback/scrollback](https://github.com/scrollback/scrollback) | 571 | `node_modules/.bin/mocha test/test.js` | 
| [sindresorhus/jshint-stylish](https://github.com/sindresorhus/jshint-stylish) | 575 | `xo && mocha` | 
| [mike-marcacci/node-redlock](https://github.com/mike-marcacci/node-redlock) | 572 | `istanbul cover mocha` | 
| [scrollback/scrollback](https://github.com/scrollback/scrollback) | 571 | `node_modules/.bin/mocha test/test.js` | 
| [queckezz/koa-views](https://github.com/queckezz/koa-views) | 570 | `mocha --reporter dot --bail --exit` | 
| [javivelasco/react-css-themr](https://github.com/javivelasco/react-css-themr) | 569 | `mocha --compilers js:babel-core/register --recursive --reporter spec --require ./test/setup.js` | 
| [matthewmueller/socrates](https://github.com/matthewmueller/socrates) | 569 | `devtool node_modules/mocha/bin/_mocha -qc -- ./test/` | 
| [tj/node-ratelimiter](https://github.com/tj/node-ratelimiter) | 568 | `mocha --exit` | 
| [tschaub/mock-fs](https://github.com/tschaub/mock-fs) | 567 | `mocha --recursive test` | 
| [scniro/gulp-clean-css](https://github.com/scniro/gulp-clean-css) | 567 | `./node_modules/.bin/mocha ./index.spec.js` | 
| [azproduction/autopolyfiller](https://github.com/azproduction/autopolyfiller) | 566 | `npm run lint && mocha -R spec` | 
| [talpor/django-dashing](https://github.com/talpor/django-dashing) | 565 | `mocha -t 10000` | 
| [website-scraper/node-website-scraper](https://github.com/website-scraper/node-website-scraper) | 561 | `nyc --reporter=html --reporter=text mocha --recursive --timeout 7000 ./test/unit/ ./test/functional && npm run eslint` | 
| [imgly/imgly-sdk-html5](https://github.com/imgly/imgly-sdk-html5) | 561 | `NODE_ENV=test node_modules/.bin/mocha --harmony --require should --require babel/register --reporter spec test/*.test.js test/**/*.test.js` | 
| [hiproxy/hiproxy](https://github.com/hiproxy/hiproxy) | 561 | `cross-env NPM_TEST=true nyc mocha test/**/*.test.js test/**/**/*.test.js --timeout 10000 && nyc report --reporter=lcov --reporter=html` | 
| [jsantell/poet](https://github.com/jsantell/poet) | 560 | `./node_modules/.bin/mocha --reporter spec --ui bdd` | 
| [ember-cli-deploy/ember-cli-deploy](https://github.com/ember-cli-deploy/ember-cli-deploy) | 560 | `node node_modules/mocha/bin/mocha "node-tests/**/*-test.js"` | 
| [mozilla/webextension-polyfill](https://github.com/mozilla/webextension-polyfill) | 559 | `mocha` | 
| [t1msh/node-oauth20-provider](https://github.com/t1msh/node-oauth20-provider) | 559 | `node_modules/.bin/mocha --reporter spec` | 
| [moshen/node-googlemaps](https://github.com/moshen/node-googlemaps) | 559 | `./node_modules/.bin/mocha test/unit` | 
| [pushtell/react-ab-test](https://github.com/pushtell/react-ab-test) | 557 | `./node_modules/karma/bin/karma start test/browser/karma.conf.js; mocha --require babel-core/register --require babel-polyfill test/isomorphic/*.jsx` | 
| [gulp-community/gulp-less](https://github.com/gulp-community/gulp-less) | 557 | `jshint index.js && node_modules/.bin/mocha` | 
| [nijikokun/generate-schema](https://github.com/nijikokun/generate-schema) | 556 | `node_modules/mocha/bin/mocha` | 
| [jmar777/suspend](https://github.com/jmar777/suspend) | 556 | `node ./node_modules/mocha/bin/mocha --harmony --reporter list` | 
| [haoxins/gulp-file-include](https://github.com/haoxins/gulp-file-include) | 542 | `mocha -R spec -t 200 test/*.js` | 
| [chaijs/chai-http](https://github.com/chaijs/chai-http) | 542 | `istanbul cover --report lcovonly _mocha` | 
| [Tom-Alexander/regression-js](https://github.com/Tom-Alexander/regression-js) | 541 | `npm run lint && ./node_modules/.bin/nyc --reporter=lcov ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [euforic/banking.js](https://github.com/euforic/banking.js) | 541 | `mocha --require should --reporter spec --globals i` | 
| [mikejihbe/metrics](https://github.com/mikejihbe/metrics) | 541 | `tsc index.d.ts && ./node_modules/.bin/mocha test/unit` | 
| [Rabrennie/anything.js](https://github.com/Rabrennie/anything.js) | 541 | `node_modules/.bin/mocha` | 
| [fireyy/react-antd-admin](https://github.com/fireyy/react-antd-admin) | 539 | `NODE_ENV=test mocha --require babel-register tests/.setup.js tests/**/*-test.js --compilers css:mocha-compiler.js` | 
| [expressjs/vhost](https://github.com/expressjs/vhost) | 539 | `mocha --reporter spec --bail --check-leaks test/` | 
| [rollup/rollup-plugin-babel](https://github.com/rollup/rollup-plugin-babel) | 537 | `mocha` | 
| [peerigon/phridge](https://github.com/peerigon/phridge) | 537 | `mocha -R spec` | 
| [mixu/electroshot](https://github.com/mixu/electroshot) | 537 | `mocha -R spec --bail ./test/*.test.js` | 
| [englue/meteor-publish-composite](https://github.com/englue/meteor-publish-composite) | 536 | `meteor test-packages ./ --driver-package cultofcoders:mocha` | 
| [pwnall/node-open](https://github.com/pwnall/node-open) | 535 | `node_modules/mocha/bin/mocha` | 
| [ethjs/ethjs](https://github.com/ethjs/ethjs) | 535 | `mocha ./src/tests/**/*.js -R spec --timeout 2000000` | 
| [miickel/gulp-angular-templatecache](https://github.com/miickel/gulp-angular-templatecache) | 534 | `mocha` | 
| [Rich-Harris/magic-string](https://github.com/Rich-Harris/magic-string) | 534 | `mocha` | 
| [kriasoft/babel-starter-kit](https://github.com/kriasoft/babel-starter-kit) | 534 | `mocha --require @babel/register` | 
| [igrigorik/node-spdyproxy](https://github.com/igrigorik/node-spdyproxy) | 533 | `mocha --reporter spec` | 
| [mariusandra/insights](https://github.com/mariusandra/insights) | 533 | `npm run eslint && npm run mocha` | 
| [raineorshine/solgraph](https://github.com/raineorshine/solgraph) | 532 | `mocha --require @babel/register` | 
| [zeromq/zeromq.js](https://github.com/zeromq/zeromq.js) | 532 | `mocha --expose-gc --slow 300` | 
| [pwnall/node-open](https://github.com/pwnall/node-open) | 535 | `node_modules/mocha/bin/mocha` | 
| [ethjs/ethjs](https://github.com/ethjs/ethjs) | 535 | `mocha ./src/tests/**/*.js -R spec --timeout 2000000` | 
| [miickel/gulp-angular-templatecache](https://github.com/miickel/gulp-angular-templatecache) | 534 | `mocha` | 
| [kriasoft/babel-starter-kit](https://github.com/kriasoft/babel-starter-kit) | 534 | `mocha --require @babel/register` | 
| [igrigorik/node-spdyproxy](https://github.com/igrigorik/node-spdyproxy) | 533 | `mocha --reporter spec` | 
| [OnetapInc/chromy](https://github.com/OnetapInc/chromy) | 533 | `WITH_BABEL=1 mocha dist_test --compilers js:babel-core/register --require babel-polyfill` | 
| [mariusandra/insights](https://github.com/mariusandra/insights) | 533 | `npm run eslint && npm run mocha` | 
| [raineorshine/solgraph](https://github.com/raineorshine/solgraph) | 532 | `mocha --require @babel/register` | 
| [zeromq/zeromq.js](https://github.com/zeromq/zeromq.js) | 532 | `mocha --expose-gc --slow 300` | 
| [node-pinus/pinus](https://github.com/node-pinus/pinus) | 532 | `mocha` | 
| [chrisveness/geodesy](https://github.com/chrisveness/geodesy) | 532 | `mocha test/*.js` | 
| [rafaelhz/react-material-admin-template](https://github.com/rafaelhz/react-material-admin-template) | 530 | `mocha tools/testSetup.js "src/**/*.spec.js" --reporter progress` | 
| [sintaxi/dbox](https://github.com/sintaxi/dbox) | 529 | `./node_modules/.bin/mocha -t 120000 test/all.js -R spec` | 
| [flywheelsports/hydra](https://github.com/flywheelsports/hydra) | 528 | `mocha specs --reporter spec` | 
| [zapty/forever-service](https://github.com/zapty/forever-service) | 527 | `mocha test/*.js` | 
| [styled-components/vue-styled-components](https://github.com/styled-components/vue-styled-components) | 527 | `mocha "./src/**/*.test.js" --require babel-core/register --require ./mocha-bootstrap --timeout 5000` | 
| [bitpay/insight-api](https://github.com/bitpay/insight-api) | 543 | `NODE_ENV=test mocha -R spec --recursive` | 
| [haoxins/gulp-file-include](https://github.com/haoxins/gulp-file-include) | 542 | `mocha -R spec -t 200 test/*.js` | 
| [chaijs/chai-http](https://github.com/chaijs/chai-http) | 542 | `istanbul cover --report lcovonly _mocha` | 
| [Tom-Alexander/regression-js](https://github.com/Tom-Alexander/regression-js) | 541 | `npm run lint && ./node_modules/.bin/nyc --reporter=lcov ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [euforic/banking.js](https://github.com/euforic/banking.js) | 541 | `mocha --require should --reporter spec --globals i` | 
| [mikejihbe/metrics](https://github.com/mikejihbe/metrics) | 541 | `tsc index.d.ts && ./node_modules/.bin/mocha test/unit` | 
| [Rabrennie/anything.js](https://github.com/Rabrennie/anything.js) | 541 | `node_modules/.bin/mocha` | 
| [adametry/gulp-eslint](https://github.com/adametry/gulp-eslint) | 540 | `mocha` | 
| [fireyy/react-antd-admin](https://github.com/fireyy/react-antd-admin) | 539 | `NODE_ENV=test mocha --require babel-register tests/.setup.js tests/**/*-test.js --compilers css:mocha-compiler.js` | 
| [expressjs/vhost](https://github.com/expressjs/vhost) | 539 | `mocha --reporter spec --bail --check-leaks test/` | 
| [rollup/rollup-plugin-babel](https://github.com/rollup/rollup-plugin-babel) | 537 | `mocha` | 
| [mapbox/carto](https://github.com/mapbox/carto) | 537 | `mocha -R spec --timeout 50000 -i -f jslint` | 
| [peerigon/phridge](https://github.com/peerigon/phridge) | 537 | `mocha -R spec` | 
| [mixu/electroshot](https://github.com/mixu/electroshot) | 537 | `mocha -R spec --bail ./test/*.test.js` | 
| [englue/meteor-publish-composite](https://github.com/englue/meteor-publish-composite) | 536 | `meteor test-packages ./ --driver-package cultofcoders:mocha` | 
| [pwnall/node-open](https://github.com/pwnall/node-open) | 535 | `node_modules/mocha/bin/mocha` | 
| [ethjs/ethjs](https://github.com/ethjs/ethjs) | 535 | `mocha ./src/tests/**/*.js -R spec --timeout 2000000` | 
| [miickel/gulp-angular-templatecache](https://github.com/miickel/gulp-angular-templatecache) | 534 | `mocha` | 
| [Rich-Harris/magic-string](https://github.com/Rich-Harris/magic-string) | 534 | `mocha` | 
| [mallocator/Elasticsearch-Exporter](https://github.com/mallocator/Elasticsearch-Exporter) | 534 | `istanbul cover _mocha -- --recursive` | 
| [kriasoft/babel-starter-kit](https://github.com/kriasoft/babel-starter-kit) | 534 | `mocha --require @babel/register` | 
| [igrigorik/node-spdyproxy](https://github.com/igrigorik/node-spdyproxy) | 533 | `mocha --reporter spec` | 
| [OnetapInc/chromy](https://github.com/OnetapInc/chromy) | 533 | `WITH_BABEL=1 mocha dist_test --compilers js:babel-core/register --require babel-polyfill` | 
| [mariusandra/insights](https://github.com/mariusandra/insights) | 533 | `npm run eslint && npm run mocha` | 
| [raineorshine/solgraph](https://github.com/raineorshine/solgraph) | 532 | `mocha --require @babel/register` | 
| [zeromq/zeromq.js](https://github.com/zeromq/zeromq.js) | 532 | `mocha --expose-gc --slow 300` | 
| [node-pinus/pinus](https://github.com/node-pinus/pinus) | 532 | `mocha` | 
| [chrisveness/geodesy](https://github.com/chrisveness/geodesy) | 532 | `mocha test/*.js` | 
| [adorableio/avatars-api-middleware](https://github.com/adorableio/avatars-api-middleware) | 531 | `mocha --exit` | 
| [rafaelhz/react-material-admin-template](https://github.com/rafaelhz/react-material-admin-template) | 530 | `mocha tools/testSetup.js "src/**/*.spec.js" --reporter progress` | 
| [sintaxi/dbox](https://github.com/sintaxi/dbox) | 529 | `./node_modules/.bin/mocha -t 120000 test/all.js -R spec` | 
| [flywheelsports/hydra](https://github.com/flywheelsports/hydra) | 528 | `mocha specs --reporter spec` | 
| [fgnass/domino](https://github.com/fgnass/domino) | 492 | `npm run lint && npm run mocha` | 
| [Yomguithereal/talisman](https://github.com/Yomguithereal/talisman) | 490 | `mocha --compilers js:babel-core/register -R spec ./test/endpoint.js` | 
| [sindresorhus/gulp-ruby-sass](https://github.com/sindresorhus/gulp-ruby-sass) | 489 | `xo && cd test && mocha test.js` | 
| [lexich/redux-api](https://github.com/lexich/redux-api) | 488 | `npm run eslint && npm run mocha && npm run yaspeller` | 
| [Kinto/formbuilder](https://github.com/Kinto/formbuilder) | 488 | `SERVER_URL=http://localhost:8888/v1 NODE_ENV=test mocha --compilers js:babel/register --recursive --require ./test/setup-jsdom.js $(find test -name '*_test.js')` | 
| [hokaccha/js-flipsnap](https://github.com/hokaccha/js-flipsnap) | 488 | `phantomjs test/lib/mocha-phantomjs.coffee test/index.html` | 
| [suguru03/neo-async](https://github.com/suguru03/neo-async) | 486 | `istanbul cover ./node_modules/.bin/_mocha --report lcovonly -- -R spec ./test --recursive` | 
| [markdalgleish/redux-analytics](https://github.com/markdalgleish/redux-analytics) | 486 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [mherkender/lua.js](https://github.com/mherkender/lua.js) | 486 | `make test && ./node_modules/mocha/bin/mocha test.js` | 
| [jriecken/sat-js](https://github.com/jriecken/sat-js) | 484 | `mocha` | 
| [pboyer/verb](https://github.com/pboyer/verb) | 484 | `grunt -v mocha` | 