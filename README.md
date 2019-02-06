# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:45 02/06/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45109 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42248 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42075 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30880 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 25946 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25690 | `nyc mocha --timeout=10000 --exit` | 
| [caolan/async](https://github.com/caolan/async) | 25201 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25151 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21443 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20137 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18055 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17908 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17448 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15312 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14714 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13986 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13698 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13207 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13022 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12799 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12790 | `istanbul cover _mocha` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13698 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13207 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13022 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12799 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12790 | `istanbul cover _mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12506 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12487 | `mocha --require @babel/register --reporter dot` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12355 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12317 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11563 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11222 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11189 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10913 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9806 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9786 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9711 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9544 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9445 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9427 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9329 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9015 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8924 | `mocha test/src` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8787 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8699 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8602 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8579 | `mocha --check-leaks -R dot` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6926 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6893 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6583 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6271 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6225 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6151 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6106 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5931 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7613 | `npm run build && istanbul cover _mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7566 | `mocha --compilers js:babel-core/register` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7510 | `mocha --exit --require @babel/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7508 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7507 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7449 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7221 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7187 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7115 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7049 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6926 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6893 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6583 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6405 | `npm run test:mocha:src` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6304 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6281 | `mocha tests/node.js` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6271 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6225 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6216 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6151 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6106 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6028 | `standard && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5931 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5891 | `mocha && eslint lib/**` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 5802 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5780 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5774 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5745 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5708 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5639 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5584 | `mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 5579 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5577 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5415 | `mocha test` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5404 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5399 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5348 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5327 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5210 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5135 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5124 | `gulp lint && mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5101 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5069 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5017 | `npm run lint && npm run mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4968 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4966 | `gulp build; mocha;` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4963 | `nyc mocha --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4919 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4899 | `./node_modules/.bin/mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4889 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4862 | `mocha -R spec 'tests/app'` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4856 | `nyc mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4854 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4839 | `mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4749 | `mocha --reporter spec -t 8000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4665 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4600 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4583 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4556 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4485 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4448 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4399 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4391 | `NODE_ENV=test mocha --exit` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4383 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4377 | `mocha --check-leaks --reporter spec --bail` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4377 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4331 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4285 | `npm run lint ; mocha && mocha test/individual` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4238 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4192 | `mocha -R spec ./test --recursive` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4178 | `npm run build && cd test && mocha . --reporter dot` | 
| [muicss/mui](https://github.com/muicss/mui) | 4141 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4131 | `mocha --require test/babel-hook test/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4098 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4095 | `mocha --require should --reporter spec` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4080 | `nyc mocha "test/**/*.test.js"` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4075 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [expressjs/session](https://github.com/expressjs/session) | 4014 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4007 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3950 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3932 | `export TESTING=true; mocha --reporter list` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3913 | `NODE_ENV=test mocha test/**/*.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3831 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3821 | `npm run build && mocha test/*.test.js` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3801 | `npm run mocha` | 
| [erming/shout](https://github.com/erming/shout) | 3793 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3789 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3761 | `mocha && tsc -p ./test/types` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3739 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3731 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3728 | `eslint . && mocha -t 5000` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3398 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 3295 | `./node_modules/mocha/bin/mocha --require babel-core/register test/*` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3239 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3230 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3221 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3185 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3172 | `mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3172 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3162 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3099 | `nyc mocha --recursive` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3061 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3059 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3047 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3185 | `./node_modules/.bin/mocha test/test.*.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3172 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3165 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3162 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3099 | `nyc mocha --recursive` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3061 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3059 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3047 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3019 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3005 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2998 | `mocha test-node` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2989 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2968 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2967 | `mocha` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2961 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2949 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2968 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2967 | `mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2911 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2908 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2901 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2898 | `mocha -R spec spec spec/reporters` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2849 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2839 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [retejs/rete](https://github.com/retejs/rete) | 2831 | `BABEL_ENV=test mocha --compilers js:@babel/register` | 
| [css/csso](https://github.com/css/csso) | 2822 | `mocha --reporter dot` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2788 | `mocha --require should --reporter spec` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2771 | `mocha "./test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2765 | `mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2765 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2764 | `xo && mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2758 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3005 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2998 | `mocha test-node` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2989 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2981 | `mocha --require @babel/register --recursive spec` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2968 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2967 | `mocha` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2961 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2949 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2918 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2911 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2908 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2901 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2898 | `mocha -R spec spec spec/reporters` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2849 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2847 | `istanbul cover _mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2604 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2592 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2557 | `mocha test --exit && npm run lint` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2556 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2556 | `mocha test/src/**/*.unit.js` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2554 | `mocha` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2548 | `mocha test` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2546 | `TEST=all mocha` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2532 | `export TESTING=true; mocha --reporter list` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2510 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2502 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [Qix-/color](https://github.com/Qix-/color) | 2462 | `mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2460 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2450 | `mocha --no-colors --reporter spec` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2557 | `mocha test --exit && npm run lint` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2554 | `mocha` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2548 | `mocha test` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2546 | `mocha && eslint .` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2539 | `nyc --reporter=html --reporter=text mocha` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2532 | `export TESTING=true; mocha --reporter list` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2525 | `mocha --reporter=spec test/*-test.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2502 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2501 | `mocha test/index.js --reporter dot` | 
| [Qix-/color](https://github.com/Qix-/color) | 2462 | `mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2456 | `mocha -R spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2450 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2446 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2443 | `nyc --require babel-register npm run _mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2395 | `npm run build && mocha --require babel-register` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2392 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2383 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2367 | `node node_modules/mocha/bin/_mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2321 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [gajus/swing](https://github.com/gajus/swing) | 2313 | `mocha --compilers js:babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2309 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [pahen/madge](https://github.com/pahen/madge) | 2302 | `npm run lint && npm run mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2313 | `mocha --compilers js:babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2309 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [pahen/madge](https://github.com/pahen/madge) | 2302 | `npm run lint && npm run mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2292 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2287 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2266 | `mocha test/**/*.coffee` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2254 | `standard && mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2252 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2252 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2244 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2230 | `npm run lint && mocha tests/**/*.js` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2207 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2192 | `mocha --timeout 10000 --bail --exit test/*-test.js test/security/*.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 2192 | `./node_modules/.bin/mocha && npm run jshint` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2186 | `cross-env BABEL_ENV=test mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2161 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2151 | `mocha --compilers js:babel-register` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2137 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2136 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2098 | `mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 2079 | `mocha test/*.test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2061 | `npm run mocha && npm run karma` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2053 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2049 | `npm run lint && mocha -R dot && npm run cover` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2049 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2053 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2049 | `npm run lint && mocha -R dot && npm run cover` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2047 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2034 | `mocha && npm run lint` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2023 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2023 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 2013 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2005 | `mocha test/test-*.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1994 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1974 | `mocha --require ./test/common --growl test/expect.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1967 | `mocha -c test/index.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1966 | `mocha test/**/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1963 | `mocha --bail --reporter spec --check-leaks test/` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1959 | `mocha --reporter spec && npm run test-typescript` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1935 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1919 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1918 | `mocha test` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1881 | `mocha ./test/basic.js -t 5000` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1880 | `mocha tests.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1865 | `nyc mocha --timeout=20000 test.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1864 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1845 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1816 | `npm run lint && npm run mocha` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1892 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1881 | `mocha ./test/basic.js -t 5000` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1880 | `mocha tests.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1865 | `nyc mocha --timeout=20000 test.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1864 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1845 | `npm run lint && npm run mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1829 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1823 | `eslint --cache . && tsc && mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1816 | `npm run lint && npm run mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1812 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1810 | `mocha test/setup.js test/spec/*.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1749 | `mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1749 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1742 | `mocha test/*.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1742 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1739 | `./node_modules/.bin/mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1731 | `mocha ./test/test*.js --reporter spec` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1728 | `mocha test --timeout 600000` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1724 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1720 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1719 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1718 | `mocha --check-leaks --reporter spec --bail` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1716 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1715 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1709 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1707 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1692 | `npm run jshint && mocha --recursive` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1639 | `mocha tests/test.js` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1629 | `mocha --reporter spec` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1628 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1620 | `mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1614 | `mocha --recursive` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1614 | `./node_modules/mocha/bin/mocha -R spec` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1589 | `mocha test/unit` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1580 | `nyc mocha` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1570 | `mocha tests/test-*` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1509 | `mocha --timeout 10000 ./tests/lib.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1508 | `mocha test/**/*.spec.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1504 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [noble/bleno](https://github.com/noble/bleno) | 1502 | `mocha -R spec test/*.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1489 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1478 | `npm run prepublishOnly && mocha test/test.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1472 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1462 | `mocha test --compilers js:babel-core/register` | 
| [samccone/drool](https://github.com/samccone/drool) | 1460 | `mocha test/tests.js --timeout=10000` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1446 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1616 | `mocha test.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1614 | `mocha --recursive` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1614 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1611 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1589 | `mocha test/unit` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1580 | `nyc mocha` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1580 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1570 | `mocha tests/test-*` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1562 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1584 | `mocha -R spec ./test/unit/**` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1580 | `nyc mocha` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1580 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1570 | `mocha tests/test-*` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1562 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1558 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1549 | `npm run test:lint && npm run test:mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1547 | `mocha --check-leaks --require @babel/register` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1544 | `node_modules/.bin/mocha --recursive` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1542 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1539 | `mocha -u tdd` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1530 | `npm run lint && npm run mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1350 | `npm run lint && mocha --require @babel/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1346 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1338 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1334 | `lerna run test && mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1331 | `mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1330 | `mocha --timeout 60000 test/` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1328 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1327 | `mocha spec/exec.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1325 | `mocha test/*.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1324 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1322 | `mocha-phantomjs tests/index.html` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1321 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1321 | `mocha` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1319 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1310 | `npm run lint && npm run mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1302 | `mocha --timeout 30000 --recursive ./tests` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1298 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1297 | `mocha --timeout 20000` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1293 | `istanbul test _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1293 | `mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1275 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1267 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1266 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1264 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1262 | `mocha tests` | 
| [normalize/mz](https://github.com/normalize/mz) | 1255 | `mocha --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1249 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1242 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1239 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1230 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [normalize/mz](https://github.com/normalize/mz) | 1255 | `mocha --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1249 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1242 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1242 | `mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1239 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1236 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [electron/asar](https://github.com/electron/asar) | 1230 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1227 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1219 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1212 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1138 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 1136 | `mocha && standard` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1131 | `mocha test/*` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1128 | `standard && mocha -b` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1114 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1105 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1103 | `mocha --recursive --bail --reporter spec test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1103 | `eslint src test && mocha --compilers babel-register` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1099 | `node_modules/.bin/mocha && npm run lint` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1097 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1091 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1090 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1087 | `mocha test/tests.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1138 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 1136 | `mocha && standard` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1131 | `mocha test/*` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1128 | `standard && mocha -b` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1127 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1115 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1114 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1111 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1105 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1103 | `mocha --recursive --bail --reporter spec test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1103 | `eslint src test && mocha --compilers babel-register` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1115 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1114 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1105 | `mocha` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1103 | `mocha --recursive --bail --reporter spec test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1103 | `eslint src test && mocha --compilers babel-register` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1099 | `node_modules/.bin/mocha && npm run lint` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1097 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1091 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1090 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1087 | `mocha test/tests.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1091 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1090 | `mocha --compilers js:babel-register` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [tomas/needle](https://github.com/tomas/needle) | 1070 | `mocha test` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1069 | `npm run lint && npm run mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1068 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1068 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1067 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 991 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 989 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 988 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 987 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 983 | `mocha --reporter spec` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 976 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 976 | `npm run rollup-cjs && mocha test/test.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 973 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 970 | `mocha -t 600000` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 966 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 966 | `mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 966 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 965 | `mocha tests` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 965 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 966 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 966 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 965 | `mocha tests` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 965 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 964 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 961 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 959 | `nyc mocha specs` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 953 | `mocha test --compilers js:babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 952 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 951 | `mocha` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 947 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 939 | `mocha --timeout 5000` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 972 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 970 | `mocha -t 600000` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 966 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 966 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 965 | `mocha tests` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 964 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 963 | `./node_modules/.bin/mocha --reporter spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 961 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 959 | `nyc mocha specs` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 953 | `mocha test --compilers js:babel-register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 951 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 959 | `nyc mocha specs` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 953 | `mocha test --compilers js:babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 952 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 951 | `mocha` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 948 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 947 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 947 | `./node_modules/.bin/mocha test/**/*` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 939 | `mocha --timeout 5000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 938 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 937 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 937 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 936 | `standard && standard ./bin/* && mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 928 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 919 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 918 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 916 | `mocha -t 5000` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 913 | `mocha test/index.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 911 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 910 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 899 | `mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 894 | `mocha --timeout 200000` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 916 | `mocha -t 5000` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 913 | `mocha test/index.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 913 | `mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 911 | `mocha test` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 910 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 909 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 907 | `npm run lint && npm run mocha:no-functional` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 899 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 899 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 897 | `node_modules/.bin/mocha` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 891 | `mocha -r should --exit test/*.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 888 | `node_modules/.bin/mocha test/spec` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 888 | `npm run build && istanbul test _mocha test/test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 886 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 886 | `mocha --harmony --full-trace --check-leaks` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 878 | `mocha --reporter list` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 877 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 877 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 877 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 870 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 853 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 851 | `npm run lint && mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 851 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 849 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 849 | `mocha` | 
| [developit/decko](https://github.com/developit/decko) | 848 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 847 | `mocha -r babel-register --check-leaks test/index.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 841 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 835 | `nyc mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 835 | `mocha test` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 829 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 824 | `npm run mocha-test test/integration` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 824 | `mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 821 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 820 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 818 | `mocha --colors --reporter spec test.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 818 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 818 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 814 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 813 | `cake build && mocha ./test/mocha/*.coffee` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 811 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 809 | `mocha` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 809 | `mocha index.test.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 830 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 830 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 829 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 826 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 824 | `npm run mocha-test test/integration` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 824 | `mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 821 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 820 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 818 | `mocha --colors --reporter spec test.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 818 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 818 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 790 | `nyc mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 790 | `npm run lint && npm run mocha` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 789 | `mocha test` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 785 | `mocha --recursive -s 15 test/` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 785 | `eslint . && mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 778 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 775 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 775 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [koajs/static](https://github.com/koajs/static) | 774 | `mocha --harmony --reporter spec --exit` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 742 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 742 | `./node_modules/.bin/mocha tests/*.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 739 | `mocha` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 737 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 737 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 737 | `mocha --compilers js:babel-core/register` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 734 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 731 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 730 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 728 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 727 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 689 | `npm run lint && mocha test` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 688 | `_mocha -u bdd --colors test/` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 688 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 683 | `mocha --require babel-register src/**/*.spec.js src/*.spec.js` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 672 | `mocha --require babel-register` | 
| [shime/livedown](https://github.com/shime/livedown) | 671 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 751 | `mocha tests/*.mocha.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 751 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 750 | `mocha 'test/**/*.tests.js'` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 750 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 745 | `npm run test-mocha && npm run test-karma` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 744 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 744 | `mocha test.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 742 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 742 | `./node_modules/.bin/mocha tests/*.js` | 