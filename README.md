# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:56:50 03/22/19 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45631 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42956 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42492 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 31013 | `nyc mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 26458 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 26095 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25734 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25352 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 21993 | `npm-run-all lint build --parallel test:mocha test:karma test:ts` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20377 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18990 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18417 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18222 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 18079 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15725 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15287 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14815 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14189 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13998 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13605 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13111 | `mocha 'test/**/*.spec.js'` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 13032 | `istanbul cover _mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12914 | `mocha --reporter spec test/*-test.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12861 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12797 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12500 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12383 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11843 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11667 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11427 | `set NODE_ENV=test && mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9417 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9410 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 9135 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9054 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8758 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8683 | `mocha --compilers js:babel-register test/test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8664 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8601 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8527 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8464 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8305 | `mocha` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8221 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8139 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8136 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8124 | `./node_modules/.bin/mocha test` | 
| [aui/art-template](https://github.com/aui/art-template) | 7996 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9054 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8758 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8683 | `mocha --compilers js:babel-register test/test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8664 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8601 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8527 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8464 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8322 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8305 | `mocha` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8295 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8221 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8139 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8136 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8124 | `./node_modules/.bin/mocha test` | 
| [aui/art-template](https://github.com/aui/art-template) | 7996 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7796 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7778 | `mocha --exit --require @babel/register` | 
| [almende/vis](https://github.com/almende/vis) | 7724 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7715 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7710 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7646 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7600 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7452 | `mocha` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7430 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7283 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7179 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7163 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 7111 | `mocha test/test.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6474 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6453 | `npm run test:mocha:src` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6386 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6360 | `mocha tests/node.js` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6328 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6291 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6282 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6239 | `standard && mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 6218 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6172 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5995 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5947 | `mocha && eslint lib/**` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5921 | `mocha` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5911 | `npm run lint && mocha tests/**/*.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5856 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 6054 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5995 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5947 | `mocha && eslint lib/**` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5921 | `mocha` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5911 | `npm run lint && mocha tests/**/*.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5856 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5785 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5780 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5644 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5592 | `mocha test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5543 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5526 | `mocha -r esm` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5511 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5443 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5398 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5220 | `mocha --recursive` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5212 | `mocha src/**/*Tests.js --harmony` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5178 | `npm run lint && npm run mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5154 | `gulp lint && mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5147 | `nyc mocha --exit` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 5141 | `NODE_ENV=test mocha --exit` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5124 | `mocha --color` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5105 | `nyc mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 5018 | `gulp build; mocha;` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 5004 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4934 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4927 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4902 | `mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4893 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4878 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4862 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4765 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4729 | `mocha -R spec src` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 4679 | `./node_modules/mocha/bin/mocha --require @babel/register test/*` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4606 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4594 | `mocha ./test/runner.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4586 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4554 | `mocha --timeout=15000 tests/*.test.js` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4532 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4506 | `mocha --check-leaks --reporter spec --bail` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 4500 | `npm run mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4495 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4449 | `mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4430 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4406 | `npm run lint && mocha && mocha test/individual && if [ "$TRAVIS_PULL_REQUEST" = "false" ]; then snyk test; fi` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4400 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4300 | `npm run build && cd test && mocha . --reporter dot` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4249 | `nyc mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4187 | `mocha --require test/babel-hook test/*.js` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4187 | `mocha -R spec ./test --recursive` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4177 | `nyc mocha "test/**/*.test.js"` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4176 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 4169 | `mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 4149 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3852 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3835 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [antvis/g6](https://github.com/antvis/g6) | 3805 | `torch --compile --renderer --opts test/mocha.opts --recursive ./test/unit` | 
| [erming/shout](https://github.com/erming/shout) | 3797 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3784 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3763 | `mocha test/* --reporter spec` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3709 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3702 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3696 | `node_modules/.bin/mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3681 | `standard && mocha --timeout 60000 test/test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3620 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3612 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3612 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3608 | `mocha tests/javascript` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3564 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3540 | `node ./test/import-test.js && mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3504 | `node_modules/.bin/mocha test/lib/` | 
| [antvis/g6](https://github.com/antvis/g6) | 3805 | `torch --compile --renderer --opts test/mocha.opts --recursive ./test/unit` | 
| [erming/shout](https://github.com/erming/shout) | 3797 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3784 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3773 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3763 | `mocha test/* --reporter spec` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3709 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3702 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3696 | `node_modules/.bin/mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3681 | `standard && mocha --timeout 60000 test/test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3673 | `npm run jshint && npm run mocha` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3635 | `nyc mocha && tsc` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3628 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3620 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3612 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3612 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3608 | `mocha tests/javascript` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3580 | `mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3564 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3321 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3309 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3299 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3245 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3205 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3202 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3194 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3185 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3168 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3167 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3143 | `nyc mocha --recursive` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3125 | `npm run mocha && npm run lint` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3099 | `node_modules/.bin/mocha --reporter spec` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2991 | `mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2961 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2927 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2903 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2854 | `mocha "./test/**/*-test.js"` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2853 | `istanbul cover _mocha` | 
| [css/csso](https://github.com/css/csso) | 2845 | `mocha --reporter dot` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2811 | `mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2794 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2788 | `mocha --require should --reporter spec` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2653 | `TEST=all mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2638 | `mocha test --exit && npm run lint` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2624 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2621 | `mocha && eslint .` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2617 | `mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2599 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2599 | `mocha test/src/**/*.unit.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2566 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2565 | `mocha test/index.js --reporter dot` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2563 | `mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2557 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2546 | `nyc --require babel-register npm run _mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2538 | `mocha --reporter=spec test/*-test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2536 | `export TESTING=true; mocha --reporter list` | 
| [Qix-/color](https://github.com/Qix-/color) | 2528 | `mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2485 | `mocha -R spec` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1304 | `istanbul test _mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1285 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1229 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1218 | `mocha --reporter spec --bail --check-leaks test/` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1214 | `mocha test` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1170 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 1163 | `mocha && standard` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1158 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2228 | `mocha --compilers js:babel-register` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2222 | `mocha test/runner.js --reporter spec` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2214 | `mocha test` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2193 | `cross-env BABEL_ENV=test mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2181 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2175 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2171 | `mocha --compilers js:babel-core/register __tests__` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2142 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2132 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 2123 | `mocha test/*.test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2121 | `npm run mocha && npm run karma` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2121 | `mocha tests --require @babel/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2100 | `mocha && npm run lint` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 2088 | `mocha --recursive` | 
| [pahen/madge](https://github.com/pahen/madge) | 2417 | `npm run lint && npm run mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2394 | `grunt jshint && mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2388 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2370 | `node node_modules/mocha/bin/_mocha` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2356 | `mocha test/**/*.coffee` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2349 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2338 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [gajus/swing](https://github.com/gajus/swing) | 2336 | `mocha --compilers js:babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2326 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2323 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2296 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2293 | `standard && mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 2290 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2281 | `mocha test/test-*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2269 | `mocha` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2338 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [gajus/swing](https://github.com/gajus/swing) | 2336 | `mocha --compilers js:babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2326 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2323 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2296 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2293 | `standard && mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 2290 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2281 | `mocha test/test-*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2269 | `mocha` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2259 | `npm run lint && mocha tests/**/*.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2244 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2229 | `mocha --timeout 15000 --bail --exit test/*-test.js test/security/*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2228 | `mocha --compilers js:babel-register` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2222 | `mocha test/runner.js --reporter spec` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2217 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2214 | `mocha test` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2193 | `cross-env BABEL_ENV=test mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2181 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2175 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2173 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2171 | `mocha --compilers js:babel-core/register __tests__` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2166 | `mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2142 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2132 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 2123 | `mocha test/*.test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2121 | `npm run mocha && npm run karma` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2121 | `mocha tests --require @babel/register` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 2088 | `mocha --recursive` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2067 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2064 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2057 | `mocha --reporter spec --timeout 5000` | 
| [then/promise](https://github.com/then/promise) | 2033 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2031 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 2026 | `nyc mocha --timeout=20000 test.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2022 | `mocha --require=test/test_helper.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 2018 | `mocha test/**/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 2003 | `mocha --reporter spec && npm run test-typescript` | 
| [slate/slate](https://github.com/slate/slate) | 1993 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1988 | `mocha tests.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1986 | `mocha --require ./test/common --growl test/expect.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1829 | `mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1828 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1817 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1810 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1794 | `mocha --timeout 5000` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1773 | `mocha --check-leaks --reporter spec --bail` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1768 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1767 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1742 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1740 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1739 | `mocha test --timeout 600000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1730 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1730 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1726 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1723 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1749 | `./node_modules/.bin/mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1747 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1740 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1739 | `mocha test --timeout 600000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1730 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1730 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1726 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1718 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1708 | `NODE_ENV=test mocha tests/*.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1698 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1697 | `mocha && size-limit` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1695 | `npm run jshint && mocha --recursive` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1688 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1676 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1669 | `mocha spec` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1667 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1663 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1654 | `mocha --recursive` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1653 | `mocha -R spec ./test/unit/**` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1647 | `mocha --expose-gc --slow 300` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1676 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1669 | `mocha spec` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1667 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1654 | `mocha --recursive` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1653 | `mocha -R spec ./test/unit/**` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1647 | `mocha --reporter spec` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1647 | `mocha --expose-gc --slow 300` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1647 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1645 | `mocha test/unit` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1640 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1633 | `mocha test.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1631 | `mocha tests/test-*` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1625 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1617 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1617 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1594 | `nyc mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1590 | `npm run lint && npm run mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1576 | `mocha --check-leaks --require @babel/register` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1567 | `npm run lint && mocha && karma start --single-run` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1565 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1564 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1560 | `mocha --recursive test` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1559 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1555 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1555 | `mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1553 | `mocha -u tdd` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1550 | `npm run test:lint && npm run test:mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1545 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1539 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [noble/bleno](https://github.com/noble/bleno) | 1533 | `mocha -R spec test/*.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1532 | `mocha --timeout 10000 ./tests/lib.js` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1530 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1452 | `webpack && npm run lint && npm run mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1452 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1448 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1446 | `npm run build && mocha -r should` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1437 | `mocha --recursive test/bin` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1427 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1426 | `istanbul cover _mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1415 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1413 | `mocha --compilers js:babel-core/register` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1406 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1394 | `NODE_PATH=. mocha **/*.spec.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1392 | `./node_modules/.bin/mocha test` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1386 | `npm run lint && mocha --require @babel/register` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1383 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1379 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1378 | `cross-env NODE_ENV=test nyc mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1617 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1594 | `nyc mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1576 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1573 | `mocha` | 
| [fbeline/design-patterns-JS](https://github.com/fbeline/design-patterns-JS) | 1569 | `mocha test --compilers js:babel-core/register` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1565 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1564 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1561 | `node_modules/.bin/mocha --recursive` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1560 | `mocha --recursive test` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1559 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1515 | `mocha --reporter dot` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1510 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1502 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1495 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1478 | `mocha -R spec` | 
| [samccone/drool](https://github.com/samccone/drool) | 1464 | `mocha test/tests.js --timeout=10000` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1461 | `npm run mocha:istanbul` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1456 | `mocha test.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 995 | `mocha "client.test" --compilers js:babel-register` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 985 | `mocha --reporter spec` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 982 | `npm run rollup-cjs && mocha test/test.js` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 980 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 976 | `nyc mocha specs` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 962 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 957 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 957 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 953 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 952 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 944 | `mocha test/index.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 941 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 938 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 938 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 936 | `mocha --timeout 5000` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 931 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 928 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 928 | `mocha -t 5000` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 928 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 922 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 922 | `mocha test` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 921 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 920 | `mocha --harmony tests/**` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 917 | `npm run lint && npm run mocha:no-functional` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 914 | `mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 911 | `mocha` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 910 | `npm run lint && mocha` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 909 | `npm run build && istanbul test _mocha test/test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 905 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 903 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 902 | `mocha --harmony --full-trace --check-leaks` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 901 | `node_modules/.bin/mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 892 | `node_modules/.bin/mocha test/spec` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 882 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 878 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 875 | `istanbul cover _mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 875 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 875 | `mocha --reporter list` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 874 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 874 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [developit/decko](https://github.com/developit/decko) | 872 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 871 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 870 | `mocha --reporter spec` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 869 | `nyc mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 869 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 861 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 860 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 859 | `mocha test` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 859 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 854 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 853 | `mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 852 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 851 | `mocha --check-leaks -t 20000` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 846 | `mocha test` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 845 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 845 | `ts-mocha test/` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 841 | `mocha --async-only` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 840 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 837 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 836 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 836 | `npm run mocha-test test/integration` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 822 | `mocha` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 816 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 810 | `jenkins-mocha ./tests/*.js` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 796 | `mocha --recursive -s 15 test/` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 811 | `mocha test` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 803 | `nyc mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 796 | `mocha --recursive -s 15 test/` | 
| [CharlesStover/reactn](https://github.com/CharlesStover/reactn) | 796 | `mocha -r chai/register-expect -r @babel/register -r ts-node/register "tests/**/*.spec.ts?(x)"` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 796 | `npm run lint && npm run mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 794 | `mocha tests --timeout 10000` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [koajs/static](https://github.com/koajs/static) | 793 | `mocha --harmony --reporter spec --exit` | 
| [edsu/anon](https://github.com/edsu/anon) | 820 | `mocha --colors --reporter spec test.js` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 820 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 816 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 814 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 811 | `mocha test` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 810 | `jenkins-mocha ./tests/*.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 807 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 784 | `mocha 'test/**/*.tests.js'` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 784 | `mocha ./test/serializer/ --compilers js:@babel/register` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 783 | `npm run-script jshint && npm run-script mocha` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 783 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 781 | `babel-node node_modules/.bin/_mocha -- test` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 779 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 777 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [susam/texme](https://github.com/susam/texme) | 775 | `standard && mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 774 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 784 | `mocha 'test/**/*.tests.js'` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 784 | `mocha ./test/serializer/ --compilers js:@babel/register` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 783 | `npm run-script jshint && npm run-script mocha` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 783 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 781 | `babel-node node_modules/.bin/_mocha -- test` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 779 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 777 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 776 | `mocha -R spec src/**/*_test.js` | 
| [susam/texme](https://github.com/susam/texme) | 775 | `standard && mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 774 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 774 | `./bin/selenium-standalone install && mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 773 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 746 | `mocha $(find test -name '*.test.js')` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 744 | `mocha` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 743 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 743 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 740 | `mocha ./test/test.js --timeout 1000000` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 740 | `mocha --reporter spec test/` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 738 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 738 | `mocha --reporter spec` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 734 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 731 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [Kagami/ffmpeg.js](https://github.com/Kagami/ffmpeg.js) | 730 | `mocha test/test.js` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 730 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 730 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [Kagami/ffmpeg.js](https://github.com/Kagami/ffmpeg.js) | 730 | `mocha test/test.js` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 730 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 730 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 730 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 727 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 709 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 708 | `mocha` | 
| [Savjee/SavjeeCoin](https://github.com/Savjee/SavjeeCoin) | 708 | `mocha tests/*.test.js` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 705 | `mocha -t 5000 -b -R spec test/index && npm run legacy-test` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 703 | `./node_modules/.bin/mocha` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 700 | `_mocha -u bdd --colors test/` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 698 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [afc163/fanyi](https://github.com/afc163/fanyi) | 695 | `npm run lint && mocha tests/index.js --timeout 0` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 694 | `mocha` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [godaddy/terminus](https://github.com/godaddy/terminus) | 693 | `mocha index.spec.js lib/**/*.spec.js && npm run test-typings` | 
| [expressjs/cookie-session](https://github.com/expressjs/cookie-session) | 688 | `mocha --check-leaks --reporter spec --bail test/` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 686 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 686 | `mocha --compilers js:babel-register` | 
| [omnidan/node-emoji](https://github.com/omnidan/node-emoji) | 681 | `./node_modules/.bin/mocha --require should --bail --reporter spec test/*` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 676 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [stevenvachon/broken-link-checker](https://github.com/stevenvachon/broken-link-checker) | 676 | `mocha test/ --reporter spec --check-leaks --bail` | 
| [theoephraim/node-google-spreadsheet](https://github.com/theoephraim/node-google-spreadsheet) | 675 | `node_modules/.bin/mocha` | 
| [IjzerenHein/autolayout.js](https://github.com/IjzerenHein/autolayout.js) | 674 | `mocha` | 
| [calmm-js/partial.lenses](https://github.com/calmm-js/partial.lenses) | 673 | `nyc mocha && nyc report -r html mocha` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 671 | `mocha -b -R spec test/*` | 
| [joaonuno/tree-model-js](https://github.com/joaonuno/tree-model-js) | 670 | `istanbul cover _mocha` | 
| [Munter/subfont](https://github.com/Munter/subfont) | 689 | `npm run lint && mocha` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 688 | `mocha -R spec` | 
| [expressjs/cookie-session](https://github.com/expressjs/cookie-session) | 688 | `mocha --check-leaks --reporter spec --bail test/` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 686 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 686 | `mocha --compilers js:babel-register` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 684 | `mocha --bail test/` | 
| [shime/livedown](https://github.com/shime/livedown) | 682 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 
| [shelljs/shx](https://github.com/shelljs/shx) | 682 | `nyc --reporter=text --reporter=lcov mocha` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 681 | `mocha --require babel-register` | 
| [omnidan/node-emoji](https://github.com/omnidan/node-emoji) | 681 | `./node_modules/.bin/mocha --require should --bail --reporter spec test/*` | 
| [IjzerenHein/autolayout.js](https://github.com/IjzerenHein/autolayout.js) | 674 | `mocha` | 
| [calmm-js/partial.lenses](https://github.com/calmm-js/partial.lenses) | 673 | `nyc mocha && nyc report -r html mocha` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 671 | `mocha -b -R spec test/*` | 
| [kwhitley/apicache](https://github.com/kwhitley/apicache) | 669 | `nyc mocha $(find test -name '*.test.js') --recursive` | 
| [coinbase/gdax-node](https://github.com/coinbase/gdax-node) | 668 | `mocha --full-trace --ui tdd --bail --reporter spec tests/*.js` | 
| [catamphetamine/universal-webpack](https://github.com/catamphetamine/universal-webpack) | 668 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 667 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [maxkueng/victor](https://github.com/maxkueng/victor) | 667 | `mocha --ui bdd --reporter spec` | 
| [LouisBarranqueiro/reapop](https://github.com/LouisBarranqueiro/reapop) | 666 | `babel-node ./node_modules/karma/bin/karma start ./build/karma.conf.js --reporters mocha` | 
| [anandanand84/technicalindicators](https://github.com/anandanand84/technicalindicators) | 665 | `mocha --compilers js:babel-register --require babel-polyfill` | 
| [docpress/docpress](https://github.com/docpress/docpress) | 665 | `nyc mocha` | 
| [aaronshaf/react-toggle](https://github.com/aaronshaf/react-toggle) | 665 | `nyc mocha --require babel-register --require spec/setup.js spec/**/*.spec.js` | 
| [Ivshti/linvodb3](https://github.com/Ivshti/linvodb3) | 663 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [jshttp/http-errors](https://github.com/jshttp/http-errors) | 652 | `mocha --reporter spec --bail` | 
| [azmenak/react-stripe-checkout](https://github.com/azmenak/react-stripe-checkout) | 652 | `mocha --require babel-register --require .test-setup.js -R spec ./spec.js` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 652 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [vault-development/react-native-svg-uri](https://github.com/vault-development/react-native-svg-uri) | 651 | `./node_modules/mocha/bin/mocha --compilers js:babel-core/register` | 
| [gauntface/simple-push-demo](https://github.com/gauntface/simple-push-demo) | 650 | `gulp && npm run lint && node ./test/helpers/download-browsers.js && mocha` | 
| [danielstjules/buddy.js](https://github.com/danielstjules/buddy.js) | 650 | `mocha -R spec spec/unit spec/integration` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 650 | `./node_modules/.bin/mocha --bail` | 
| [postcss/gulp-postcss](https://github.com/postcss/gulp-postcss) | 649 | `nyc mocha test.js` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 648 | `./node_modules/.bin/mocha test/integration` | 
| [phodal/sherlock](https://github.com/phodal/sherlock) | 644 | `mocha --reporter spec` | 
| [fent/node-ytdl](https://github.com/fent/node-ytdl) | 642 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [edankwan/penis.js](https://github.com/edankwan/penis.js) | 642 | `mocha --ui bdd --reporter spec test/` | 
| [tonyhb/redux-ui](https://github.com/tonyhb/redux-ui) | 641 | `$(npm bin)/mocha  --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [aliyun-UED/aliyun-sdk-js](https://github.com/aliyun-UED/aliyun-sdk-js) | 641 | `mocha test` | 
| [screwdriver-cd/screwdriver](https://github.com/screwdriver-cd/screwdriver) | 640 | `jenkins-mocha --recursive --timeout 3000 --exit` | 
| [floatdrop/gulp-watch](https://github.com/floatdrop/gulp-watch) | 640 | `xo && mocha -r test/util/set-default-options -t 5000 -R spec test/test-*` | 
| [webpack/memory-fs](https://github.com/webpack/memory-fs) | 640 | `mocha` | 
| [susielu/d3-legend](https://github.com/susielu/d3-legend) | 630 | `mocha` | 
| [tj/node-blocked](https://github.com/tj/node-blocked) | 630 | `./node_modules/mocha/bin/mocha` | 
| [wclimb/Koa2-blog](https://github.com/wclimb/Koa2-blog) | 628 | `./node_modules/mocha/bin/mocha --harmony test` | 
| [duaraghav8/Ethlint](https://github.com/duaraghav8/Ethlint) | 627 | `nyc --reporter=text --reporter=html mocha --require should --reporter spec --recursive` | 
| [mysamai/mysam](https://github.com/mysamai/mysam) | 625 | `npm run lint && npm run mocha` | 
| [ipfs-shipyard/ipfs-desktop](https://github.com/ipfs-shipyard/ipfs-desktop) | 624 | `cross-env NODE_ENV=test mocha` | 
| [robrich/gulp-if](https://github.com/robrich/gulp-if) | 623 | `mocha && jshint .` | 
| [robwierzbowski/generator-jekyllrb](https://github.com/robwierzbowski/generator-jekyllrb) | 619 | `mocha` | 
| [macbre/analyze-css](https://github.com/macbre/analyze-css) | 616 | `mocha -R spec` | 
| [SGrondin/bottleneck](https://github.com/SGrondin/bottleneck) | 616 | `mocha test` | 
| [wclimb/Koa2-blog](https://github.com/wclimb/Koa2-blog) | 628 | `./node_modules/mocha/bin/mocha --harmony test` | 
| [duaraghav8/Ethlint](https://github.com/duaraghav8/Ethlint) | 627 | `nyc --reporter=text --reporter=html mocha --require should --reporter spec --recursive` | 
| [mysamai/mysam](https://github.com/mysamai/mysam) | 625 | `npm run lint && npm run mocha` | 
| [ipfs-shipyard/ipfs-desktop](https://github.com/ipfs-shipyard/ipfs-desktop) | 624 | `cross-env NODE_ENV=test mocha` | 
| [robrich/gulp-if](https://github.com/robrich/gulp-if) | 623 | `mocha && jshint .` | 
| [robwierzbowski/generator-jekyllrb](https://github.com/robwierzbowski/generator-jekyllrb) | 619 | `mocha` | 
| [gameclosure/devkit](https://github.com/gameclosure/devkit) | 617 | `mocha --reporter spec --recursive -C ./tests` | 
| [gameclosure/devkit](https://github.com/gameclosure/devkit) | 617 | `mocha --reporter spec --recursive -C ./tests` | 
| [mattyork/fuzzy](https://github.com/mattyork/fuzzy) | 616 | `./node_modules/.bin/mocha` | 
| [jfromaniello/passport.socketio](https://github.com/jfromaniello/passport.socketio) | 615 | `mocha` | 
| [opencomponents/oc](https://github.com/opencomponents/oc) | 615 | `npm run build && node tasks/mochaTest.js` | 
| [adamjmcgrath/react-native-simple-auth](https://github.com/adamjmcgrath/react-native-simple-auth) | 615 | `mocha lib/**/*.test.js --require babel-register` | 
| [Charca/bootbot](https://github.com/Charca/bootbot) | 615 | `mocha --recursive test/*` | 
| [filamentgroup/glyphhanger](https://github.com/filamentgroup/glyphhanger) | 612 | `mocha` | 
| [desmondmorris/node-tesseract](https://github.com/desmondmorris/node-tesseract) | 612 | `mocha` | 
| [mathiasbynens/emoji-regex](https://github.com/mathiasbynens/emoji-regex) | 612 | `mocha` | 
| [webdriverio-boneyard/webdrivercss](https://github.com/webdriverio-boneyard/webdrivercss) | 611 | `./node_modules/.bin/mocha` | 
| [node-opcua/node-opcua](https://github.com/node-opcua/node-opcua) | 608 | `cd packages && node --expose-gc --max-old-space-size=512 run_all_mocha_tests.js` | 
| [shinnn/gulp-gh-pages](https://github.com/shinnn/gulp-gh-pages) | 607 | `nyc mocha test.js --timeout 50000 --full-trace` | 
| [cgross/generator-cg-angular](https://github.com/cgross/generator-cg-angular) | 606 | `mocha` | 
| [csstree/csstree](https://github.com/csstree/csstree) | 604 | `mocha --reporter progress` | 
| [GianlucaGuarini/icaro](https://github.com/GianlucaGuarini/icaro) | 550 | `npm run lint && mocha test` | 
| [totorojs/totoro](https://github.com/totorojs/totoro) | 550 | `mocha tests/` | 
| [zeromq/zeromq.js](https://github.com/zeromq/zeromq.js) | 548 | `mocha --expose-gc --slow 300` | 
| [bitpay/bitcore-wallet-service](https://github.com/bitpay/bitcore-wallet-service) | 548 | `./node_modules/.bin/mocha --exit` | 
| [vbauer/manet](https://github.com/vbauer/manet) | 547 | `mocha --exit` | 
| [jaredhanson/electrolyte](https://github.com/jaredhanson/electrolyte) | 547 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [mrsimonfletcher/react-progressive-web-app](https://github.com/mrsimonfletcher/react-progressive-web-app) | 547 | `mocha "src/**/*.spec.jsx"` | 
| [rollup/rollup-plugin-babel](https://github.com/rollup/rollup-plugin-babel) | 546 | `mocha` | 
| [euforic/banking.js](https://github.com/euforic/banking.js) | 544 | `mocha --require should --reporter spec --globals i` | 
| [haoxins/gulp-file-include](https://github.com/haoxins/gulp-file-include) | 542 | `mocha -R spec -t 200 test/*.js` | 
| [chrisveness/geodesy](https://github.com/chrisveness/geodesy) | 541 | `mocha test/*.js` | 
| [mikejihbe/metrics](https://github.com/mikejihbe/metrics) | 541 | `tsc index.d.ts && ./node_modules/.bin/mocha test/unit` | 
| [adametry/gulp-eslint](https://github.com/adametry/gulp-eslint) | 541 | `mocha` | 
| [OnetapInc/chromy](https://github.com/OnetapInc/chromy) | 537 | `WITH_BABEL=1 mocha dist_test --compilers js:babel-core/register --require babel-polyfill` | 
| [EvanHahn/HumanizeDuration.js](https://github.com/EvanHahn/HumanizeDuration.js) | 537 | `mocha` | 
| [peerigon/phridge](https://github.com/peerigon/phridge) | 537 | `mocha -R spec` | 
| [raineorshine/solgraph](https://github.com/raineorshine/solgraph) | 536 | `mocha --require @babel/register` | 
| [englue/meteor-publish-composite](https://github.com/englue/meteor-publish-composite) | 536 | `meteor test-packages ./ --driver-package cultofcoders:mocha` | 