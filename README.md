# Find Repos in JavaScript Tested using Mocha

The list was updated at 01:01:22 03/23/19 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45643 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42971 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42498 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 31016 | `nyc mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 26100 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25742 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25351 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 22001 | `npm-run-all lint build --parallel test:mocha test:karma test:ts` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20378 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 19001 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18426 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18230 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 18093 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15728 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15298 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14815 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14192 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11843 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11434 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 11112 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10817 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10534 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 10125 | `mocha tests/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9784 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9716 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9653 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9417 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9416 | `mocha --opts mocha.opts` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 11112 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [websockets/ws](https://github.com/websockets/ws) | 10894 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10817 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10534 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 10125 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9930 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9784 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9716 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9653 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9520 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9417 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9416 | `mocha --opts mocha.opts` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 9165 | `mocha test/*/**` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 9139 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9058 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8760 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8689 | `mocha --compilers js:babel-register test/test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8669 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8601 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8528 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8472 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8321 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8312 | `mocha` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8293 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8221 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8143 | `npm run eslint && npm run mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8141 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8124 | `./node_modules/.bin/mocha test` | 
| [aui/art-template](https://github.com/aui/art-template) | 8001 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7804 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7781 | `mocha --exit --require @babel/register` | 
| [almende/vis](https://github.com/almende/vis) | 7729 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7721 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7714 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7647 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7602 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7452 | `mocha` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7437 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7289 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7179 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7167 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 7118 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6670 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6480 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6454 | `npm run test:mocha:src` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6391 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6361 | `mocha tests/node.js` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6330 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6295 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6281 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6243 | `standard && mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 6230 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6173 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 6060 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 6001 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5948 | `mocha && eslint lib/**` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5921 | `mocha` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5915 | `npm run lint && mocha tests/**/*.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5859 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5790 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5786 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5648 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5591 | `mocha test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5546 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5527 | `mocha -r esm` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5518 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5442 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5398 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5229 | `mocha --recursive` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5212 | `mocha src/**/*Tests.js --harmony` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5180 | `npm run lint && npm run mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5156 | `gulp lint && mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 5150 | `NODE_ENV=test mocha --exit` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5150 | `nyc mocha --exit` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5124 | `mocha --color` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5107 | `nyc mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 5018 | `gulp build; mocha;` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 5003 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4935 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4927 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4902 | `mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4894 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4881 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4864 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4767 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4738 | `mocha -R spec src` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 4683 | `./node_modules/mocha/bin/mocha --require @babel/register test/*` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4607 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4594 | `mocha ./test/runner.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4587 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4555 | `mocha --timeout=15000 tests/*.test.js` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4532 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 4512 | `npm run mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4508 | `mocha --check-leaks --reporter spec --bail` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4496 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4450 | `mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4431 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4408 | `npm run lint && mocha && mocha test/individual && if [ "$TRAVIS_PULL_REQUEST" = "false" ]; then snyk test; fi` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4400 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4301 | `npm run build && cd test && mocha . --reporter dot` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4188 | `mocha --require test/babel-hook test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4187 | `mocha -R spec ./test --recursive` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4179 | `nyc mocha "test/**/*.test.js"` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4178 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4132 | `mocha --require should --reporter spec` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 4069 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 4069 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 4023 | `NODE_ENV=test mocha test/**/*.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3999 | `mocha && tsc -p ./test/types` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3979 | `eslint . && mocha -t 5000` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3941 | `export TESTING=true; mocha --reporter list` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3856 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3852 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [primus/primus](https://github.com/primus/primus) | 3849 | `npm run build && mocha test/*.test.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3841 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [antvis/g6](https://github.com/antvis/g6) | 3810 | `torch --compile --renderer --opts test/mocha.opts --recursive ./test/unit` | 
| [erming/shout](https://github.com/erming/shout) | 3798 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3785 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3774 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3764 | `mocha test/* --reporter spec` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3322 | `mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3301 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3300 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3202 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3194 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3187 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3172 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 3081 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3074 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 3013 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 3000 | `mocha -R spec --recursive src/test` | 
| [github-tools/github](https://github.com/github-tools/github) | 2927 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2925 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2903 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3430 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3414 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3386 | `mocha test/index.js && npm run demo` | 
| [mde/ejs](https://github.com/mde/ejs) | 3349 | `mocha --require should --reporter spec` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3311 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3301 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3300 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3245 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3208 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3202 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3180 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3172 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3168 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3039 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3038 | `mocha` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 3013 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2993 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2991 | `mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2964 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2929 | `mocha -R spec spec spec/reporters` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2925 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2857 | `mocha "./test/**/*-test.js"` | 
| [css/csso](https://github.com/css/csso) | 2845 | `mocha --reporter dot` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2812 | `mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2794 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2067 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2064 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2056 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2031 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2023 | `mocha --require=test/test_helper.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 2019 | `mocha test/**/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 2004 | `mocha --reporter spec && npm run test-typescript` | 
| [zeit/ms](https://github.com/zeit/ms) | 1989 | `mocha tests.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1975 | `npm run lint && mocha --reporter spec test/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1943 | `mocha ./test/basic.js -t 5000` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1929 | `eslint --cache . && tslint --project . && node build && mocha && tsc` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2567 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2564 | `mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2561 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2547 | `nyc --require babel-register npm run _mocha` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2536 | `export TESTING=true; mocha --reporter list` | 
| [Qix-/color](https://github.com/Qix-/color) | 2528 | `mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2476 | `mocha -R spec test/*.js` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2461 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2458 | `npm run build && mocha --require babel-register` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2455 | `mocha --no-colors --reporter spec` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2428 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [pahen/madge](https://github.com/pahen/madge) | 2421 | `npm run lint && npm run mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2735 | `mocha --recursive --watch` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2728 | `mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2713 | `mocha --timeout 100000` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2712 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2658 | `mocha-phantomjs ./test/index.html` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2654 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2639 | `mocha test --exit && npm run lint` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2628 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2620 | `mocha && eslint .` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2618 | `mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2599 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2245 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2229 | `mocha --timeout 15000 --bail --exit test/*-test.js test/security/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2222 | `mocha test/runner.js --reporter spec` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2218 | `mocha test` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2217 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2183 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2174 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2172 | `mocha --compilers js:babel-core/register __tests__` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2166 | `mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2145 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2132 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 2126 | `mocha test/*.test.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1964 | `mocha -c test/index.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1962 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1960 | `mocha --reporter spec --grep .` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1958 | `mocha test -u bdd -R spec` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1950 | `mocha test` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1941 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1929 | `eslint --cache . && tslint --project . && node build && mocha && tsc` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1905 | `mocha ./test/test*.js --reporter spec` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1887 | `mocha tests.js` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1873 | `npm run lint && npm run mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1865 | `npm run lint && npm run mocha` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1862 | `mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1829 | `mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1828 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1826 | `mocha test` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1822 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1799 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1794 | `mocha --timeout 5000` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1782 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1781 | `npm run lint && mocha && npm run typescript` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1776 | `mocha --check-leaks --reporter spec --bail` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1774 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1772 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1767 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1767 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1742 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1741 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1737 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1730 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1726 | `mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1723 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1710 | `NODE_ENV=test mocha tests/*.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1698 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1697 | `mocha && size-limit` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1695 | `npm run jshint && mocha --recursive` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1689 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1676 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1670 | `mocha spec` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1668 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1666 | `xo && mocha` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1665 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1656 | `mocha -R spec ./test/unit/**` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1655 | `mocha --recursive` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1649 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1648 | `mocha test/unit` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1647 | `mocha --reporter spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1646 | `mocha --expose-gc --slow 300` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1641 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1633 | `mocha test.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1631 | `mocha tests/test-*` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1625 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1618 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1618 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1594 | `nyc mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1590 | `npm run lint && npm run mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1576 | `mocha --check-leaks --require @babel/register` | 
| [fbeline/design-patterns-JS](https://github.com/fbeline/design-patterns-JS) | 1572 | `mocha test --compilers js:babel-core/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1572 | `mocha` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1569 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1564 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1563 | `mocha --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1561 | `node_modules/.bin/mocha --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1559 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1551 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1545 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1539 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1536 | `npm run prepublishOnly && mocha test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1533 | `mocha -R spec test/*.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1532 | `mocha --timeout 10000 ./tests/lib.js` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1530 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1530 | `mocha test/**/*.spec.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1529 | `standard && nyc _mocha --exit` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1521 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1496 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1495 | `mocha --opts test/opts/mocha.opts` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1487 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1536 | `npm run prepublishOnly && mocha test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1533 | `mocha -R spec test/*.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1532 | `mocha --timeout 10000 ./tests/lib.js` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1530 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1530 | `mocha test/**/*.spec.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1529 | `standard && nyc _mocha --exit` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1521 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1516 | `mocha --reporter dot` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1512 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [trufflesuite/ganache](https://github.com/trufflesuite/ganache) | 1505 | `npm run test-mocha && npm run test-jest` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1503 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1496 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1495 | `mocha --opts test/opts/mocha.opts` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1487 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [electron/devtron](https://github.com/electron/devtron) | 1429 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1428 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1426 | `istanbul cover _mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1424 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1416 | `mocha --compilers js:babel-core/register` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1416 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1407 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1406 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1400 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1398 | `mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1395 | `NODE_PATH=. mocha **/*.spec.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1392 | `./node_modules/.bin/mocha test` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1387 | `npm run lint && mocha --require @babel/register` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1384 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1379 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1379 | `mocha tests/` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1185 | `mocha $(find test -name '*.test.js') --exit` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1179 | `mocha` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1171 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1165 | `istanbul cover _mocha test/*.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 1163 | `mocha && standard` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1158 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1140 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1140 | `eslint src test && mocha --compilers babel-register` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1135 | `mocha test/*` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1358 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1355 | `mocha --timeout 60000 test/` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1354 | `mocha --timeout 30000 --recursive ./tests` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1351 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1349 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1345 | `lerna run test && mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1343 | `npm run lint && npm run mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1342 | `mocha test/*.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1341 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1340 | `mocha` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1340 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1339 | `mocha src/test.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1338 | `mocha spec/exec.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1330 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1329 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1326 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1321 | `mocha-phantomjs tests/index.html` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1318 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1267 | `mocha tests` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1267 | `mocha test` | 
| [electron/asar](https://github.com/electron/asar) | 1267 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1258 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1258 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1242 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1233 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1233 | `node ./node_modules/mocha/bin/mocha tests` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1225 | `mocha --recursive -r tests/setup tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1224 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1218 | `mocha --reporter spec --bail --check-leaks test/` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1214 | `mocha test` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1207 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1198 | `xo && mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1190 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1185 | `mocha $(find test -name '*.test.js') --exit` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1184 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1179 | `npm run convertto:es5 && npm run mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1179 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1158 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1140 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1140 | `eslint src test && mocha --compilers babel-register` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1136 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1135 | `mocha test/*` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1123 | `mocha` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1119 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1118 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1117 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1113 | `mocha --recursive --bail --reporter spec test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1100 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1108 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1100 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1100 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1099 | `mocha --check-leaks -t 20000` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1096 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1091 | `mocha test/tests.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 1085 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1080 | `mocha --async-only` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1070 | `mocha test/*.test.js` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1108 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1103 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1100 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1100 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1099 | `mocha --check-leaks -t 20000` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1096 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1094 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1091 | `mocha test/tests.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 1085 | `mocha test` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1080 | `mocha --async-only` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1052 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1044 | `mocha --recursive test/unit/` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1042 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1040 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1039 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1035 | `npm run lint && mocha -R spec` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1034 | `mocha spec/*.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1033 | `mocha --reporter spec --bail --check-leaks test/` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1032 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1032 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1032 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1031 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 1027 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1024 | `mocha --reporter spec --timeout 3000` | 
| [gulp-sourcemaps/gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) | 1022 | `mocha --async-only` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1020 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 978 | `./node_modules/.bin/mocha --reporter spec` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 977 | `mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 975 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 967 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 967 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 966 | `mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 962 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 958 | `istanbul cover -- _mocha --reporter spec` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 957 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 955 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 952 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 971 | `standard && standard ./bin/* && mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 967 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 967 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 958 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 955 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 712 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 705 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 703 | `./node_modules/.bin/mocha` | 
| [apollographql/eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) | 703 | `tav --ci && mocha test/index.js` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 700 | `_mocha -u bdd --colors test/` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 698 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 689 | `mocha -R spec` | 
| [Munter/subfont](https://github.com/Munter/subfont) | 689 | `npm run lint && mocha` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 686 | `mocha --compilers js:babel-register` | 
| [shime/livedown](https://github.com/shime/livedown) | 682 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 681 | `mocha --require babel-register` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 743 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 740 | `mocha ./test/test.js --timeout 1000000` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 740 | `mocha --reporter spec test/` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 731 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [Kagami/ffmpeg.js](https://github.com/Kagami/ffmpeg.js) | 731 | `mocha test/test.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 730 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 727 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 905 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 903 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 903 | `mocha --harmony --full-trace --check-leaks` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 899 | `mocha --timeout 200000` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 895 | `mocha --reporter list` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 892 | `node_modules/.bin/mocha test/spec` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 883 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 878 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 878 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 877 | `istanbul cover _mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 874 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 873 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 871 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 870 | `mocha --reporter spec` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 869 | `nyc mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 869 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 868 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 867 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 867 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 867 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [ebradyjobory/finance.js](https://github.com/ebradyjobory/finance.js) | 861 | `mocha` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 860 | `mocha test` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 860 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 860 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 860 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [ebradyjobory/finance.js](https://github.com/ebradyjobory/finance.js) | 861 | `mocha` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 860 | `mocha test` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 860 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 860 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 859 | `mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 858 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 854 | `mocha` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 854 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 853 | `mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 852 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 851 | `mocha --check-leaks -t 20000` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 848 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 846 | `ts-mocha test/` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 846 | `mocha test` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 845 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 844 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 844 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 843 | `mocha test/mocha.js test/crc/index.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 842 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 842 | `mocha --async-only` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 840 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 838 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 836 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 835 | `npm run mocha-test test/integration` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 833 | `mocha` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 833 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 833 | `mocha && ember test` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 832 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 831 | `_mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 829 | `cake build && mocha ./test/mocha/*.coffee` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 829 | `eslint . && mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 827 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 827 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 822 | `mocha index.test.js` | 
| [edsu/anon](https://github.com/edsu/anon) | 820 | `mocha --colors --reporter spec test.js` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 820 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 819 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 814 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 811 | `mocha test` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 810 | `jenkins-mocha ./tests/*.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 807 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 810 | `jenkins-mocha ./tests/*.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 807 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [CharlesStover/reactn](https://github.com/CharlesStover/reactn) | 805 | `mocha -r chai/register-expect -r @babel/register -r ts-node/register "tests/**/*.spec.ts?(x)"` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 803 | `nyc mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 799 | `mocha --no-timeouts` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [fivdi/onoff](https://github.com/fivdi/onoff) | 798 | `nyc mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 798 | `npm run lint && npm run mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 796 | `mocha --recursive -s 15 test/` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 761 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 759 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 755 | `npm run test-mocha && npm run test-karma` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 752 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [formio/formio](https://github.com/formio/formio) | 750 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 748 | `mocha test.js` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 747 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 746 | `mocha --compilers js:babel-core/register` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 745 | `mocha $(find test -name '*.test.js')` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 744 | `mocha` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 744 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 743 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 742 | `npm run bundle && mocha` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 739 | `mocha --reporter spec` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 738 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 735 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 730 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 730 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 729 | `mocha` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 727 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 723 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 746 | `mocha --compilers js:babel-core/register` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 744 | `mocha` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 744 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 744 | `mocha` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 743 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 743 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 742 | `npm run bundle && mocha` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 740 | `mocha ./test/test.js --timeout 1000000` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 740 | `mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 740 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 739 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 739 | `mocha --reporter spec` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 731 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 690 | `mocha --require babel-register src/**/*.spec.js src/*.spec.js` | 
| [mtth/avsc](https://github.com/mtth/avsc) | 689 | `mocha` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 689 | `npm run lint && mocha test` | 
| [Munter/subfont](https://github.com/Munter/subfont) | 689 | `npm run lint && mocha` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 686 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 686 | `mocha --bail test/` | 
| [shelljs/shx](https://github.com/shelljs/shx) | 684 | `nyc --reporter=text --reporter=lcov mocha` | 
| [omnidan/node-emoji](https://github.com/omnidan/node-emoji) | 681 | `./node_modules/.bin/mocha --require should --bail --reporter spec test/*` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 676 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [stevenvachon/broken-link-checker](https://github.com/stevenvachon/broken-link-checker) | 676 | `mocha test/ --reporter spec --check-leaks --bail` | 
| [IjzerenHein/autolayout.js](https://github.com/IjzerenHein/autolayout.js) | 674 | `mocha` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 727 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 723 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 712 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 712 | `npm -s run mocha && npm run -s lint` | 