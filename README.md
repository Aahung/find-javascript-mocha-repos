# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:10 01/27/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45006 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42083 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42033 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30851 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25597 | `nyc mocha --timeout=10000 --exit` | 
| [caolan/async](https://github.com/caolan/async) | 25176 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25054 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21374 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20109 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18456 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18008 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17839 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17289 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15222 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14939 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14696 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13946 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13652 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13082 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13009 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12777 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12770 | `istanbul cover _mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12450 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12394 | `mocha --require @babel/register --reporter dot` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12359 | `mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12273 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11505 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11146 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11121 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10883 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10802 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10597 | `mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 10455 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10421 | `mocha --harmony` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9752 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9739 | `mocha tests/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9702 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9524 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9438 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9389 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9312 | `grunt mocha` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8906 | `mocha test/src` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8865 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8718 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8690 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8584 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8568 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8448 | `grunt clean:test && mocha --exit` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8335 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8258 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8223 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8073 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8055 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8022 | `./node_modules/.bin/mocha test` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7952 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7888 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7865 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7855 | `mocha` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7159 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7134 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7110 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7026 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6856 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6855 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6564 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6564 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6396 | `npm run test:mocha:src` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6271 | `mocha tests/node.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6269 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6238 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6213 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6213 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6122 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6095 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6071 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5984 | `standard && mocha` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5932 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5885 | `mocha && eslint lib/**` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5751 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5718 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5706 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5698 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5618 | `npm run lint && mocha tests/**/*.js` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 5577 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5556 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5531 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 5463 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5405 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5376 | `mocha -r esm` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5376 | `mocha test` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5338 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5279 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5208 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5136 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5124 | `gulp lint && mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5045 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5045 | `mocha --recursive` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4951 | `gulp build; mocha;` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4938 | `nyc mocha --exit` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4925 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4916 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4889 | `./node_modules/.bin/mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4888 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4878 | `npm run lint && npm run mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4857 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4839 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4834 | `mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4816 | `nyc mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4482 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4431 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4378 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4375 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4363 | `node_modules/.bin/mocha test/tests.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4346 | `mocha --check-leaks --reporter spec --bail` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4336 | `NODE_ENV=test mocha --exit` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4307 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4271 | `npm run lint ; mocha && mocha test/individual` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4236 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4195 | `mocha -R spec ./test --recursive` | 
| [muicss/mui](https://github.com/muicss/mui) | 4139 | `mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4098 | `npm run build && cd test && mocha . --reporter dot` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4058 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 3984 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3983 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3929 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3884 | `NODE_ENV=test mocha test/**/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3858 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3831 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3738 | `mocha && tsc -p ./test/types` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3737 | `mocha test/* --reporter spec` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3730 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3774 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3730 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3718 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3703 | `eslint . && mocha -t 5000` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3692 | `npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3685 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3670 | `npm run jshint && npm run mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3668 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3663 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3660 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3604 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3581 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3530 | `nyc mocha && tsc` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3490 | `node_modules/.bin/mocha test/lib/` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3320 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3297 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3249 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3228 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3219 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3208 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3183 | `./node_modules/.bin/mocha test/test.*.js` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3091 | `nyc mocha --recursive` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3060 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3032 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3249 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3228 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3225 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3219 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3208 | `mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3171 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3155 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3154 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3148 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3091 | `nyc mocha --recursive` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3090 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2847 | `istanbul cover _mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2828 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2827 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [css/csso](https://github.com/css/csso) | 2819 | `mocha --reporter dot` | 
| [retejs/rete](https://github.com/retejs/rete) | 2802 | `BABEL_ENV=test mocha --compilers js:@babel/register` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2786 | `mocha --require should --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2767 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2760 | `mocha "./test/**/*-test.js"` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2752 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2751 | `mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2713 | `nyc mocha --timeout=10000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2705 | `nyc mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2688 | `mocha --timeout 100000` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2669 | `mocha test/unit --require mochahook` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2828 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2827 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [css/csso](https://github.com/css/csso) | 2819 | `mocha --reporter dot` | 
| [retejs/rete](https://github.com/retejs/rete) | 2802 | `BABEL_ENV=test mocha --compilers js:@babel/register` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2786 | `mocha --require should --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2767 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2761 | `xo && mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2760 | `mocha "./test/**/*-test.js"` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2752 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2751 | `mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2713 | `nyc mocha --timeout=10000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2712 | `mocha --recursive --watch` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2705 | `nyc mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2688 | `mocha --timeout 100000` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2669 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2668 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2633 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2596 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2592 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2555 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2550 | `mocha test --exit && npm run lint` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2549 | `mocha test` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2539 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2537 | `mocha test/src/**/*.unit.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2531 | `nyc --reporter=html --reporter=text mocha` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2531 | `export TESTING=true; mocha --reporter list` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2519 | `mocha --reporter=spec test/*-test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2519 | `mocha && eslint .` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2507 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2507 | `TEST=all mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2482 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2454 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2449 | `mocha --no-colors --reporter spec` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2447 | `mocha -R spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2442 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [Qix-/color](https://github.com/Qix-/color) | 2441 | `mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2433 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2426 | `nyc --require babel-register npm run _mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2409 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2388 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2388 | `npm run build && mocha --require babel-register` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 2065 | `mocha test/*.test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2049 | `npm run mocha && npm run karma` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2048 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2047 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2040 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2034 | `mocha tests --require @babel/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2027 | `mocha && npm run lint` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2020 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2020 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 2013 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2007 | `mocha test` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2004 | `mocha --require=test/test_helper.js` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1987 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1971 | `mocha --require ./test/common --growl test/expect.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1959 | `mocha test/**/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1951 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1949 | `bmocha --reporter spec test/*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2143 | `mocha --compilers js:babel-register` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2138 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2132 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2130 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2101 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2097 | `mocha` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2049 | `npm run mocha && npm run karma` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2048 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2047 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2040 | `npm run lint && mocha -R dot && npm run cover` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2034 | `mocha tests --require @babel/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2027 | `mocha && npm run lint` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2020 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2020 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 2013 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2007 | `mocha test` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2004 | `mocha --require=test/test_helper.js` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1987 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1971 | `mocha --require ./test/common --growl test/expect.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1965 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1960 | `mocha --bail --reporter spec --check-leaks test/` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1959 | `mocha test/**/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1952 | `mocha --reporter spec && npm run test-typescript` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1951 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1949 | `mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1949 | `bmocha --reporter spec test/*.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1897 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1891 | `mocha compiled_tests/` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1862 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1843 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1823 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1821 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1813 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1810 | `npm run lint && npm run mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1802 | `mocha test/setup.js test/spec/*.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1800 | `eslint --cache . && tsc && mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1844 | `nyc mocha --timeout=20000 test.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1843 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1823 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1821 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1813 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1810 | `npm run lint && npm run mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1802 | `mocha test/setup.js test/spec/*.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1800 | `eslint --cache . && tsc && mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1800 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1798 | `mocha --timeout 5000` | 
| [zeit/ms](https://github.com/zeit/ms) | 1763 | `mocha tests.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1760 | `npm run lint && mocha && npm run typescript` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1753 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1745 | `mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1743 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1743 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1738 | `mocha test/*.js` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1737 | `./node_modules/.bin/mocha` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1736 | `mocha test/test-*.js` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1735 | `mocha --recursive` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1733 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1728 | `mocha test --timeout 600000` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1723 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1715 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1714 | `mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1710 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1710 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1644 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1637 | `mocha tests/test.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1628 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1626 | `mocha --reporter spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1618 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1613 | `./node_modules/mocha/bin/mocha -R spec` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1609 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1605 | `mocha --recursive` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1601 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1575 | `nyc mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1568 | `mocha -R spec ./test/unit/**` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1648 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1644 | `mocha --expose-gc --slow 300` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1639 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1637 | `mocha tests/test.js` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1632 | `NODE_ENV=test mocha tests/*.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1628 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1626 | `mocha --reporter spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1625 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1625 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1618 | `mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1613 | `./node_modules/mocha/bin/mocha -R spec` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1612 | `mocha test.js` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1609 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1609 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1582 | `mocha test/unit` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1575 | `nyc mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1568 | `mocha -R spec ./test/unit/**` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1560 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1557 | `mocha tests/test-*` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1557 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1549 | `npm run test:lint && npm run test:mocha` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1547 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1542 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1542 | `node_modules/.bin/mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1539 | `mocha -u tdd` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1538 | `mocha --check-leaks --require @babel/register` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1404 | `mocha --recursive test/bin` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1396 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1388 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1384 | `./node_modules/mocha/bin/mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1375 | `./node_modules/.bin/mocha test` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1375 | `webpack && npm run lint && npm run mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1371 | `cross-env NODE_ENV=test nyc mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1365 | `NODE_PATH=. mocha **/*.spec.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1360 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1359 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1358 | `mocha --compilers js:babel-core/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1346 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1341 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1340 | `npm run lint && mocha --require @babel/register` | 
| [electron/devtron](https://github.com/electron/devtron) | 1411 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1410 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1408 | `istanbul cover _mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1404 | `mocha --recursive test/bin` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1396 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1388 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1384 | `mocha --check-leaks --reporter spec --bail test/` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1375 | `./node_modules/.bin/mocha test` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1375 | `webpack && npm run lint && npm run mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1365 | `NODE_PATH=. mocha **/*.spec.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1364 | `npm run mocha:istanbul` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1360 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1360 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1359 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1358 | `mocha --compilers js:babel-core/register` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1304 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1297 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1297 | `mocha --timeout 30000 --recursive ./tests` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1297 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1292 | `istanbul test _mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1292 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1290 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1275 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1262 | `mocha tests` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1261 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1260 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1256 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1253 | `mocha --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1241 | `mocha` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1241 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1235 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1235 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1233 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1227 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1224 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1219 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1213 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1207 | `mocha test` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1198 | `mocha --recursive -r tests/setup tests` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1182 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1181 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1180 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1180 | `mocha --reporter spec --bail --check-leaks test/` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1179 | `npm-run-all test:jest test:server:mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1178 | `xo && mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1166 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1166 | `mocha $(find test -name '*.test.js') --exit` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1166 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1156 | `istanbul cover _mocha test/*.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1153 | `mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1147 | `mocha test` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1145 | `webpack && mocha test/unit` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1130 | `npm run convertto:es5 && npm run mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1128 | `mocha test/*` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1128 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [electron/spectron](https://github.com/electron/spectron) | 1127 | `mocha && standard` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1125 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1130 | `npm run convertto:es5 && npm run mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1128 | `mocha test/*` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1128 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [electron/spectron](https://github.com/electron/spectron) | 1127 | `mocha && standard` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1125 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1120 | `standard && mocha -b` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1116 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1114 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1113 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1105 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1086 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1084 | `mocha test/tests.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1065 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1064 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1054 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1030 | `mocha --recursive test/unit/` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1028 | `mocha test/*.test.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1024 | `mocha --reporter spec --bail --check-leaks test/` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 1019 | `mocha --recursive ./test/*_spec.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1018 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1018 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1015 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1013 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1013 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1007 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1006 | `mocha --check-leaks -R dot` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1005 | `mocha -R list` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1003 | `mocha spec/*.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 999 | `mocha --compilers js:babel-register test/*.js` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 999 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 996 | `npm run lint && mocha -R spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 996 | `./node_modules/.bin/mocha -R spec` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 987 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 983 | `mocha --reporter spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 982 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 981 | `mocha "client.test" --compilers js:babel-register` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 977 | `npm run rollup-cjs && mocha test/test.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 974 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 971 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 966 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 966 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 964 | `mocha -t 600000` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 964 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 963 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 963 | `mocha tests` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 960 | `./node_modules/.bin/mocha --reporter spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 958 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 939 | `mocha test` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 936 | `./node_modules/.bin/mocha test/**/*` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 933 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 932 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 927 | `standard && standard ./bin/* && mocha` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 925 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 925 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 918 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 918 | `mocha -t 5000` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 917 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 950 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 950 | `mocha test --compilers js:babel-register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 945 | `mocha` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 942 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 942 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 939 | `mocha test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 939 | `mocha --timeout 5000` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 936 | `./node_modules/.bin/mocha test/**/*` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 933 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 932 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 927 | `standard && standard ./bin/* && mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 927 | `istanbul cover -- _mocha --reporter spec` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 925 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 910 | `mocha test/index.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 908 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 906 | `npm run lint && npm run mocha:no-functional` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 905 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 901 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 896 | `node_modules/.bin/mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 890 | `mocha` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 888 | `mocha -r should --exit test/*.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 887 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 886 | `node_modules/.bin/mocha test/spec` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 885 | `npm run build && istanbul test _mocha test/test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 881 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 880 | `mocha --harmony --full-trace --check-leaks` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 877 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 876 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 873 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 869 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 865 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 865 | `istanbul cover _mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 862 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 858 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 858 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 858 | `mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 857 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 856 | `mocha --reporter spec --bail --check-leaks test/` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 856 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 856 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 855 | `mocha --harmony tests/**` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 853 | `mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 852 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 851 | `npm run lint && mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 849 | `mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 849 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 848 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 846 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 846 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 845 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 844 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 844 | `mocha --opts mocha.opts` | 
| [developit/decko](https://github.com/developit/decko) | 842 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 844 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 844 | `mocha --opts mocha.opts` | 
| [developit/decko](https://github.com/developit/decko) | 842 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 840 | `mocha --async-only` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 839 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 839 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 837 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 835 | `mocha test` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 835 | `npm run lint && mocha` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 834 | `nyc mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 830 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 829 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 827 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 826 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 826 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 826 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 826 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 821 | `npm run mocha-test test/integration` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 820 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 820 | `mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 819 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [edsu/anon](https://github.com/edsu/anon) | 815 | `mocha --colors --reporter spec test.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 814 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 813 | `_mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 813 | `cake build && mocha ./test/mocha/*.coffee` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 810 | `mocha` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 784 | `mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 781 | `mocha tests --timeout 10000` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 780 | `mocha test` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 775 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 775 | `eslint . && mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 774 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 774 | `mocha -R spec src/**/*_test.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 771 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [koajs/static](https://github.com/koajs/static) | 768 | `mocha --harmony --reporter spec --exit` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 766 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 789 | `nyc mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 788 | `npm run lint && npm run mocha` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 787 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 784 | `mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 782 | `mocha --recursive -s 15 test/` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 781 | `mocha tests --timeout 10000` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 780 | `mocha test` | 
| [typicode/katon](https://github.com/typicode/katon) | 707 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 703 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [formio/formio](https://github.com/formio/formio) | 701 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 699 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 699 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 696 | `jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 695 | `mocha` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 692 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 690 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [sass-eyeglass/eyeglass](https://github.com/sass-eyeglass/eyeglass) | 690 | `mocha test/**/test_*.js` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 688 | `npm run lint && mocha test` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 685 | `_mocha -u bdd --colors test/` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 761 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 761 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 759 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 758 | `./bin/selenium-standalone install && mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 752 | `mocha tests/*.mocha.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 751 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 747 | `mocha 'test/**/*.tests.js'` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 752 | `mocha tests/*.mocha.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 751 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 747 | `mocha 'test/**/*.tests.js'` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 744 | `npm run test-mocha && npm run test-karma` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 744 | `mocha test.js` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 744 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 743 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 742 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 708 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [typicode/katon](https://github.com/typicode/katon) | 707 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 703 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 703 | `mocha` | 
| [formio/formio](https://github.com/formio/formio) | 701 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 699 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 699 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 698 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 696 | `jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 695 | `mocha` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 