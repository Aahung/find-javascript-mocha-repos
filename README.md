# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:05 03/16/19 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45535 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42883 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42455 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30990 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 26381 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 26043 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25631 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25325 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 21929 | `npm-run-all lint build --parallel test:mocha test:karma test:ts` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20336 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18899 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18346 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18192 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17994 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15659 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15248 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14805 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14159 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13956 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13547 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13097 | `mocha 'test/**/*.spec.js'` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12992 | `istanbul cover _mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12901 | `mocha --reporter spec test/*-test.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12811 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12754 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12479 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12381 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11802 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11606 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11384 | `set NODE_ENV=test && mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10795 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10514 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 10070 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9918 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9770 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9679 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9608 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9508 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9410 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9354 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 9088 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 9078 | `mocha test/*/**` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9034 | `mocha test/src` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 9078 | `mocha test/*/**` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9034 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8748 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8680 | `mocha --compilers js:babel-register test/test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8615 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8598 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8521 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8417 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8316 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8298 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8257 | `mocha` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8187 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8123 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8119 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8117 | `./node_modules/.bin/mocha test` | 
| [aui/art-template](https://github.com/aui/art-template) | 7985 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7742 | `mocha --exit --require @babel/register` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7725 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [almende/vis](https://github.com/almende/vis) | 7695 | `mocha --compilers js:babel-core/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7687 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7667 | `mocha; jshint *.js lib` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7638 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7453 | `mocha` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7376 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7216 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7168 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7151 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 7092 | `mocha test/test.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6449 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6446 | `npm run test:mocha:src` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6370 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6354 | `mocha tests/node.js` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6303 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6269 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6269 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6215 | `standard && mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6164 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 6108 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6068 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 6009 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5954 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5933 | `mocha && eslint lib/**` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5923 | `mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6068 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 6009 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5954 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5933 | `mocha && eslint lib/**` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5923 | `mocha` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5884 | `npm run lint && mocha tests/**/*.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5850 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5778 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5739 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5636 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5557 | `mocha test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5525 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5507 | `mocha -r esm` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5446 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5125 | `mocha --color` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5110 | `nyc mocha --exit` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 5087 | `NODE_ENV=test mocha --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5078 | `nyc mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 5009 | `gulp build; mocha;` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4989 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4933 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4920 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4897 | `mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4888 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4873 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4829 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4766 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4710 | `mocha -R spec src` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4279 | `npm run build && cd test && mocha . --reporter dot` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4251 | `nyc mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4187 | `mocha -R spec ./test --recursive` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4184 | `mocha --require test/babel-hook test/*.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4168 | `mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4163 | `nyc mocha "test/**/*.test.js"` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4160 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4125 | `mocha --require should --reporter spec` | 
| [expressjs/session](https://github.com/expressjs/session) | 4124 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4087 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 4043 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 4004 | `NODE_ENV=test mocha test/**/*.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3974 | `mocha && tsc -p ./test/types` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3940 | `export TESTING=true; mocha --reporter list` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3935 | `eslint . && mocha -t 5000` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3851 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3847 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [primus/primus](https://github.com/primus/primus) | 3844 | `npm run build && mocha test/*.test.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3837 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3824 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3794 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3760 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3757 | `mocha test/* --reporter spec` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3681 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3671 | `npm run jshint && npm run mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3626 | `nyc mocha && tsc` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3614 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3608 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3592 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3555 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3537 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3501 | `node_modules/.bin/mocha test/lib/` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3490 | `node ./test/import-test.js && mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3464 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3459 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3455 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3454 | `mocha -R landing test/index --exit` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3446 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2851 | `istanbul cover _mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2846 | `mocha "./test/**/*-test.js"` | 
| [css/csso](https://github.com/css/csso) | 2838 | `mocha --reporter dot` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2804 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2788 | `mocha --require should --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2774 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2758 | `nyc mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2745 | `nyc mocha --timeout=10000` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2735 | `mocha test/unit --require mochahook` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2733 | `mocha --recursive --watch` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2703 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2622 | `mocha test --exit && npm run lint` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2607 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2606 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2597 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2566 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2561 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2553 | `mocha test/index.js --reporter dot` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2545 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2537 | `mocha --reporter=spec test/*-test.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3240 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3202 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3197 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3191 | `./node_modules/.bin/mocha test/test.*.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3161 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3157 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3153 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3133 | `nyc mocha --recursive` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3120 | `npm run mocha && npm run lint` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3089 | `node_modules/.bin/mocha --reporter spec` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3074 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3063 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3061 | `mocha test-node` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 3061 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 3053 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3074 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3063 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3061 | `mocha test-node` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 3061 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 3053 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 3038 | `mocha --require @babel/register --recursive spec` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3030 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3027 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2996 | `mocha -R spec --recursive src/test` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2988 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2988 | `mocha` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2976 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2951 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2928 | `mocha -R spec spec spec/reporters` | 
| [github-tools/github](https://github.com/github-tools/github) | 2924 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2922 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2629 | `TEST=all mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2613 | `mocha && eslint .` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2607 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2606 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2598 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2574 | `mocha test` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2561 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2553 | `mocha test/index.js --reporter dot` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2537 | `mocha --reporter=spec test/*-test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2534 | `export TESTING=true; mocha --reporter list` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2528 | `nyc --require babel-register npm run _mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2483 | `mocha -R spec` | 
| [noble/noble](https://github.com/noble/noble) | 2470 | `mocha -R spec test/*.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2606 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2598 | `mocha test/src/**/*.unit.js` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2597 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2566 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2561 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2553 | `mocha test/index.js --reporter dot` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2545 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2537 | `mocha --reporter=spec test/*-test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2534 | `export TESTING=true; mocha --reporter list` | 
| [Qix-/color](https://github.com/Qix-/color) | 2518 | `mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2483 | `mocha -R spec` | 
| [noble/noble](https://github.com/noble/noble) | 2470 | `mocha -R spec test/*.js` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2456 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2455 | `mocha --no-colors --reporter spec` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2218 | `mocha test/runner.js --reporter spec` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2215 | `mocha --compilers js:babel-register` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2192 | `cross-env BABEL_ENV=test mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2189 | `mocha test` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2177 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2174 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2169 | `mocha --compilers js:babel-core/register __tests__` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2135 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2132 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 2115 | `mocha test/*.test.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2108 | `mocha tests --require @babel/register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2101 | `mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2088 | `mocha && npm run lint` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2227 | `mocha --timeout 15000 --bail --exit test/*-test.js test/security/*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2215 | `mocha --compilers js:babel-register` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2192 | `cross-env BABEL_ENV=test mocha` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2189 | `mocha test` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2177 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2174 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2172 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2169 | `mocha --compilers js:babel-core/register __tests__` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2163 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2132 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2120 | `npm run mocha && npm run karma` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2169 | `mocha --compilers js:babel-core/register __tests__` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2163 | `mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2135 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2132 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2120 | `npm run mocha && npm run karma` | 
| [kach/nearley](https://github.com/kach/nearley) | 2115 | `mocha test/*.test.js` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2108 | `mocha tests --require @babel/register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2101 | `mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2088 | `mocha && npm run lint` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2068 | `npm run lint && mocha -R dot && npm run cover` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 2060 | `mocha --recursive` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2058 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2052 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2031 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 2029 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2020 | `mocha --require=test/test_helper.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 2012 | `mocha test/**/*.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1997 | `nyc mocha --timeout=20000 test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1982 | `mocha --require ./test/common --growl test/expect.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1974 | `mocha --bail --reporter spec --check-leaks test/` | 
| [zeit/ms](https://github.com/zeit/ms) | 1960 | `mocha tests.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1959 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1955 | `mocha --reporter spec --grep .` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1881 | `mocha ./test/test*.js --reporter spec` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1874 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1856 | `mocha test/setup.js test/spec/*.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1827 | `mocha test` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1796 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1794 | `mocha --timeout 5000` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1783 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1780 | `npm run lint && mocha && npm run typescript` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1770 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1763 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1750 | `./node_modules/.bin/mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1868 | `npm run lint && npm run mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1863 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1856 | `mocha test/setup.js test/spec/*.js` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1853 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1828 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1824 | `mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1821 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1817 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1797 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1796 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1794 | `mocha --timeout 5000` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1783 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1780 | `npm run lint && mocha && npm run typescript` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1450 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1446 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1421 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1406 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1403 | `mocha --recursive` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1399 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1391 | `./node_modules/mocha/bin/mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1376 | `cross-env NODE_ENV=test nyc mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1375 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1351 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1348 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1341 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1340 | `mocha` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1592 | `nyc mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1574 | `mocha --check-leaks --require @babel/register` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1563 | `npm run lint && mocha && karma start --single-run` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1560 | `node_modules/.bin/mocha --recursive` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1559 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1554 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1552 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1549 | `mocha -u tdd` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1549 | `mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1547 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1547 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1546 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1545 | `mocha --recursive test` | 
| [fbeline/design-patterns-JS](https://github.com/fbeline/design-patterns-JS) | 1543 | `mocha test --compilers js:babel-core/register` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1530 | `mocha --timeout 10000 ./tests/lib.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1528 | `npm run prepublishOnly && mocha test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1528 | `mocha -R spec test/*.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1453 | `npm run mocha:istanbul` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1450 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1449 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1446 | `npm run build && mocha -r should` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1446 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1430 | `mocha --check-leaks --reporter spec --bail test/` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1428 | `mocha --recursive test/bin` | 
| [electron/devtron](https://github.com/electron/devtron) | 1426 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1421 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1406 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1406 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1403 | `mocha --recursive` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1399 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1394 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1393 | `NODE_PATH=. mocha **/*.spec.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1574 | `mocha --check-leaks --require @babel/register` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1563 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1563 | `npm run lint && mocha && karma start --single-run` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1560 | `node_modules/.bin/mocha --recursive` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1559 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1554 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1552 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1550 | `npm run test:lint && npm run test:mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1549 | `mocha -u tdd` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1549 | `mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1547 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1547 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1546 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1545 | `mocha --recursive test` | 
| [fbeline/design-patterns-JS](https://github.com/fbeline/design-patterns-JS) | 1543 | `mocha test --compilers js:babel-core/register` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1530 | `mocha --timeout 10000 ./tests/lib.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1528 | `npm run prepublishOnly && mocha test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1528 | `mocha -R spec test/*.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1525 | `mocha test/**/*.spec.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1450 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1449 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1448 | `webpack && npm run lint && npm run mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1446 | `npm run build && mocha -r should` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1430 | `mocha --check-leaks --reporter spec --bail test/` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1428 | `mocha --recursive test/bin` | 
| [electron/devtron](https://github.com/electron/devtron) | 1426 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1421 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1413 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1406 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1406 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1399 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1394 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1393 | `NODE_PATH=. mocha **/*.spec.js` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1428 | `mocha --recursive test/bin` | 
| [electron/devtron](https://github.com/electron/devtron) | 1426 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1426 | `istanbul cover _mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1413 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1408 | `mocha --compilers js:babel-core/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1406 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1399 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1394 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1393 | `NODE_PATH=. mocha **/*.spec.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1391 | `./node_modules/mocha/bin/mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1389 | `./node_modules/.bin/mocha test` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1380 | `npm run lint && mocha --require @babel/register` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1379 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1375 | `mocha` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1372 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1196 | `xo && mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1185 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1183 | `mocha $(find test -name '*.test.js') --exit` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1177 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1171 | `npm run convertto:es5 && npm run mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1170 | `mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1163 | `istanbul cover _mocha test/*.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 1159 | `mocha && standard` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1158 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1140 | `standard && mocha -b` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1139 | `eslint src test && mocha --compilers babel-register` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1136 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1135 | `mocha test/*` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1128 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1117 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1116 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1114 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1111 | `mocha --recursive --bail --reporter spec test` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1109 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1099 | `mocha --check-leaks -t 20000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1099 | `node_modules/.bin/mocha && npm run lint` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1094 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 1086 | `mocha test` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1084 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1075 | `mocha --async-only` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1075 | `mocha --async-only` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1067 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1066 | `mocha test/*.test.js` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1059 | `mocha $(find test -name '*.test.js')` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 1056 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1052 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1044 | `mocha --recursive test/unit/` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1040 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1039 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1044 | `mocha --recursive test/unit/` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1040 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1039 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1036 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1032 | `mocha --reporter spec --bail --check-leaks test/` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1031 | `mocha spec/*.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1030 | `./node_modules/.bin/mocha -R spec` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1030 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1029 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1027 | `npm run lint && mocha -R spec` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1027 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1024 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1024 | `mocha --reporter spec --timeout 3000` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 1022 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [gulp-sourcemaps/gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) | 1022 | `mocha --async-only` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 1021 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1020 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 987 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 986 | `mocha -t 600000 --exit` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 986 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 985 | `mocha tests` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 985 | `mocha --reporter spec` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 984 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 984 | `mocha` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 982 | `mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 981 | `npm run rollup-cjs && mocha test/test.js` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 975 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 975 | `./node_modules/.bin/mocha --reporter spec` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 973 | `mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 970 | `./node_modules/.bin/mocha test/**/*` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 970 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 968 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 968 | `standard && standard ./bin/* && mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 967 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 964 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 901 | `npm run lint && mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 900 | `node_modules/.bin/mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 898 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 897 | `mocha --timeout 200000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 893 | `node_modules/.bin/mocha test/spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 891 | `mocha --reporter list` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 881 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 875 | `mocha --reporter list` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 874 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 874 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 871 | `mocha` | 
| [developit/decko](https://github.com/developit/decko) | 867 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 867 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 931 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 927 | `mocha -t 5000` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 925 | `mocha -r should --exit test/*.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 925 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 924 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 920 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 920 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 919 | `mocha test` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 918 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 913 | `mocha --harmony tests/**` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 913 | `mocha` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 906 | `npm run build && istanbul test _mocha test/test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 905 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 900 | `node_modules/.bin/mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 898 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 898 | `mocha --harmony --full-trace --check-leaks` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 897 | `mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 893 | `node_modules/.bin/mocha test/spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 891 | `mocha --reporter list` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 721 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [typicode/katon](https://github.com/typicode/katon) | 705 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 702 | `./node_modules/.bin/mocha` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 690 | `mocha --require babel-register src/**/*.spec.js src/*.spec.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 836 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 835 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 832 | `mocha && ember test` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 831 | `_mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 826 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 825 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 824 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 820 | `mocha --colors --reporter spec test.js` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 820 | `eslint . && mocha` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 819 | `mocha index.test.js` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 815 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 815 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 813 | `mocha test` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 807 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 805 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 804 | `jenkins-mocha ./tests/*.js` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 801 | `nyc mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 800 | `mocha --no-timeouts` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [node-cron/node-cron](https://github.com/node-cron/node-cron) | 793 | `nyc --reporter=html --reporter=text mocha --recursive` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 782 | `npm run-script jshint && npm run-script mocha` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 780 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 778 | `mocha 'test/**/*.tests.js'` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 778 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 776 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 782 | `npm run-script jshint && npm run-script mocha` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 780 | `babel-node node_modules/.bin/_mocha -- test` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 780 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 778 | `mocha 'test/**/*.tests.js'` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 778 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 776 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 775 | `mocha -R spec src/**/*_test.js` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 775 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 774 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 772 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 772 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 771 | `./bin/selenium-standalone install && mocha` | 
| [susam/texme](https://github.com/susam/texme) | 769 | `standard && mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 767 | `mocha --reporter spec build/test/index.js` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 739 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 739 | `mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 738 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 737 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 737 | `mocha --reporter spec test/` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 732 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 730 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 730 | `mocha` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 728 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [CharlesStover/reactn](https://github.com/CharlesStover/reactn) | 728 | `mocha -r chai/register-expect -r @babel/register -r ts-node/register "tests/**/*.spec.ts?(x)"` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 721 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 752 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 750 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 746 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 745 | `mocha --compilers js:babel-core/register` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 743 | `npm run bundle && mocha` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 743 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [formio/formio](https://github.com/formio/formio) | 743 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 743 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 743 | `mocha` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 742 | `mocha` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 742 | `mocha $(find test -name '*.test.js')` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 740 | `mocha ./test/test.js --timeout 1000000` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 705 | `mocha --reporter spec` | 
| [typicode/katon](https://github.com/typicode/katon) | 705 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 705 | `npm -s run mocha && npm run -s lint` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 703 | `mocha -t 5000 -b -R spec test/index && npm run legacy-test` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 698 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 697 | `_mocha -u bdd --colors test/` | 
| [apollographql/eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) | 697 | `tav --ci && mocha test/index.js` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 694 | `mocha` | 
| [afc163/fanyi](https://github.com/afc163/fanyi) | 694 | `npm run lint && mocha tests/index.js --timeout 0` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [klokantech/tileserver-gl](https://github.com/klokantech/tileserver-gl) | 689 | `mocha test/**.js --timeout 10000` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 689 | `npm run lint && mocha test` | 
| [godaddy/terminus](https://github.com/godaddy/terminus) | 687 | `mocha index.spec.js lib/**/*.spec.js && npm run test-typings` | 
| [gtanner/qrcode-terminal](https://github.com/gtanner/qrcode-terminal) | 687 | `./node_modules/jshint/bin/jshint lib vendor && node example/basic.js && ./node_modules/mocha/bin/mocha -R nyan` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 686 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 686 | `mocha --compilers js:babel-register` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 708 | `mocha` | 
| [Savjee/SavjeeCoin](https://github.com/Savjee/SavjeeCoin) | 705 | `mocha tests/*.test.js` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 705 | `mocha --reporter spec` | 
| [typicode/katon](https://github.com/typicode/katon) | 705 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 705 | `npm -s run mocha && npm run -s lint` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 702 | `./node_modules/.bin/mocha` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 698 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [apollographql/eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) | 697 | `tav --ci && mocha test/index.js` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 694 | `mocha` | 
| [afc163/fanyi](https://github.com/afc163/fanyi) | 694 | `npm run lint && mocha tests/index.js --timeout 0` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 710 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 708 | `mocha` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 707 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [Savjee/SavjeeCoin](https://github.com/Savjee/SavjeeCoin) | 705 | `mocha tests/*.test.js` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 705 | `mocha --reporter spec` | 
| [typicode/katon](https://github.com/typicode/katon) | 705 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 705 | `npm -s run mocha && npm run -s lint` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 703 | `mocha -t 5000 -b -R spec test/index && npm run legacy-test` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 702 | `./node_modules/.bin/mocha` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 698 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 697 | `_mocha -u bdd --colors test/` | 
| [apollographql/eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) | 697 | `tav --ci && mocha test/index.js` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 698 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 697 | `_mocha -u bdd --colors test/` | 
| [apollographql/eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) | 697 | `tav --ci && mocha test/index.js` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 694 | `mocha` | 
| [afc163/fanyi](https://github.com/afc163/fanyi) | 694 | `npm run lint && mocha tests/index.js --timeout 0` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 690 | `mocha --require babel-register src/**/*.spec.js src/*.spec.js` | 
| [klokantech/tileserver-gl](https://github.com/klokantech/tileserver-gl) | 689 | `mocha test/**.js --timeout 10000` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 689 | `npm run lint && mocha test` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 688 | `mocha -R spec` | 
| [godaddy/terminus](https://github.com/godaddy/terminus) | 687 | `mocha index.spec.js lib/**/*.spec.js && npm run test-typings` | 
| [gtanner/qrcode-terminal](https://github.com/gtanner/qrcode-terminal) | 687 | `./node_modules/jshint/bin/jshint lib vendor && node example/basic.js && ./node_modules/mocha/bin/mocha -R nyan` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 686 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 686 | `mocha --compilers js:babel-register` | 
| [Munter/subfont](https://github.com/Munter/subfont) | 684 | `npm run lint && mocha` | 
| [expressjs/cookie-session](https://github.com/expressjs/cookie-session) | 683 | `mocha --check-leaks --reporter spec --bail test/` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 683 | `mocha --bail test/` | 
| [mtth/avsc](https://github.com/mtth/avsc) | 681 | `mocha` | 
| [shime/livedown](https://github.com/shime/livedown) | 680 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 678 | `mocha --require babel-register` | 