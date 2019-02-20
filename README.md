# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:37 02/20/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45234 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42482 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42266 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30918 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25827 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25313 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25244 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 21592 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20199 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18636 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18125 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18009 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17638 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15409 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15089 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14741 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14061 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13761 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13328 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13051 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12838 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12834 | `istanbul cover _mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12610 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12574 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12373 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12364 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11663 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11367 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11254 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10959 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [amark/gun](https://github.com/amark/gun) | 9600 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9462 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9361 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9144 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8970 | `mocha test/src` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8913 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 8825 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8712 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8593 | `mocha --check-leaks -R dot` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8435 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8312 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8279 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8255 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8082 | `npm run eslint && npm run mocha` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8071 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8058 | `./node_modules/.bin/mocha test` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8017 | `mocha` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8626 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8593 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8485 | `grunt clean:test && mocha --exit` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8435 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8312 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8279 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8255 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8082 | `npm run eslint && npm run mocha` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8071 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8058 | `./node_modules/.bin/mocha test` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8017 | `mocha` | 
| [aui/art-template](https://github.com/aui/art-template) | 7911 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7615 | `npm run build && istanbul cover _mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7604 | `mocha --compilers js:babel-core/register` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7592 | `mocha --exit --require @babel/register` | 
| [dthree/cash](https://github.com/dthree/cash) | 7587 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7584 | `mocha; jshint *.js lib` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7615 | `npm run build && istanbul cover _mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7604 | `mocha --compilers js:babel-core/register` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7592 | `mocha --exit --require @babel/register` | 
| [dthree/cash](https://github.com/dthree/cash) | 7587 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7584 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7550 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7450 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7340 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7226 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7134 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7092 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7046 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6957 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6608 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6421 | `npm run test:mocha:src` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6348 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6345 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6300 | `mocha tests/node.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6260 | `mocha` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6235 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6189 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6129 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6087 | `standard && mocha` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6067 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6066 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5668 | `npm run lint && mocha tests/**/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5632 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5600 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5463 | `mocha test` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5440 | `mocha -r esm` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5399 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5382 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5380 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5210 | `mocha src/**/*Tests.js --harmony` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5208 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5134 | `gulp lint && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5129 | `mocha --color` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5113 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5080 | `npm run lint && npm run mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5382 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5380 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5210 | `mocha src/**/*Tests.js --harmony` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5208 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5134 | `gulp lint && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5129 | `mocha --color` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5113 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5080 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5022 | `nyc mocha --exit` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4981 | `gulp build; mocha;` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4973 | `nyc mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4932 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4927 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4903 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4876 | `mocha -R spec 'tests/app'` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4866 | `mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4856 | `mocha test` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4755 | `mocha --reporter spec -t 8000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4720 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4664 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4585 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4567 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4499 | `NODE_ENV=test mocha --exit` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4487 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4477 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4453 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4411 | `mocha --check-leaks --reporter spec --bail` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4393 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4393 | `node_modules/.bin/mocha test/tests.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4388 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4358 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4310 | `npm run lint ; mocha && mocha test/individual` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4244 | `nyc mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4225 | `npm run build && cd test && mocha . --reporter dot` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4191 | `mocha -R spec ./test --recursive` | 
| [muicss/mui](https://github.com/muicss/mui) | 4145 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4143 | `mocha --require test/babel-hook test/*.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4110 | `nyc mocha "test/**/*.test.js"` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4109 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 4041 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4036 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 3992 | `npm run mocha` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3950 | `NODE_ENV=test mocha test/**/*.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3940 | `export TESTING=true; mocha --reporter list` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 3935 | `./node_modules/mocha/bin/mocha --require babel-core/register test/*` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3858 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3845 | `mocha && tsc -p ./test/types` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3833 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [primus/primus](https://github.com/primus/primus) | 3831 | `npm run build && mocha test/*.test.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3812 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3787 | `eslint . && mocha -t 5000` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3787 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3746 | `mocha test/* --reporter spec` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3738 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3722 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 3412 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3402 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3400 | `mocha -R landing test/index --exit` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3360 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3353 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3271 | `mocha test/*.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3251 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3232 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3188 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3105 | `nyc mocha --recursive` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3097 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3049 | `node_modules/.bin/mocha --reporter spec` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3020 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3001 | `mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3448 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3442 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3438 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3433 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3408 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 3402 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3400 | `mocha -R landing test/index --exit` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3360 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3353 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3323 | `mocha test/index.js && npm run demo` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3271 | `mocha test/*.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3254 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3251 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3251 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3232 | `mocha` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3105 | `nyc mocha --recursive` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3097 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3076 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3066 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3039 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3021 | `mocha test-node` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3020 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3001 | `mocha` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2989 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2977 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2970 | `mocha -R spec --recursive src/test` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2967 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2960 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1964 | `mocha --bail --reporter spec --check-leaks test/` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1929 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1926 | `mocha test` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1899 | `mocha --recursive` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1893 | `mocha ./test/basic.js -t 5000` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1864 | `mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1857 | `eslint --cache . && tsc && mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1822 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1814 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1795 | `mocha --timeout 5000` | 
| [zeit/ms](https://github.com/zeit/ms) | 1792 | `mocha tests.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1791 | `mocha ./test/test*.js --reporter spec` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1778 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2802 | `mocha "./test/**/*-test.js"` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2767 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2766 | `xo && mocha` | 
| [tj/should.js](https://github.com/tj/should.js) | 2731 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2730 | `nyc mocha --timeout=10000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2728 | `nyc mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2720 | `mocha --recursive --watch` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2699 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2694 | `mocha test/unit --require mochahook` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2694 | `mocha --timeout 100000` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2669 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2636 | `mocha-phantomjs ./test/index.html` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2621 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2621 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2595 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2587 | `mocha test --exit && npm run lint` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2581 | `TEST=all mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2576 | `mocha && eslint .` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2571 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2569 | `mocha test/src/**/*.unit.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2558 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2556 | `mocha test` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2532 | `export TESTING=true; mocha --reporter list` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2516 | `mocha test/index.js --reporter dot` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2511 | `mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2480 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2480 | `nyc --require babel-register npm run _mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2478 | `mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2469 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1962 | `bmocha --reporter spec test/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1953 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1939 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1926 | `nyc mocha --timeout=20000 test.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1918 | `mocha test -u bdd -R spec` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1857 | `eslint --cache . && tsc && mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1842 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1838 | `npm run lint && npm run mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2469 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2468 | `mocha -R spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2454 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2451 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [noble/noble](https://github.com/noble/noble) | 2433 | `mocha -R spec test/*.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2413 | `npm run build && mocha --require babel-register` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2399 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2387 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2366 | `node node_modules/mocha/bin/_mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 2336 | `npm run lint && npm run mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2321 | `mocha --compilers js:babel-register` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2320 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2320 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2303 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2289 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2269 | `standard && mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2244 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2237 | `mocha && eslint *.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2202 | `mocha test/runner.js --reporter spec` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2192 | `cross-env BABEL_ENV=test mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2244 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2242 | `npm run lint && mocha tests/**/*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2237 | `mocha && eslint *.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 2221 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2211 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2203 | `mocha --timeout 15000 --bail --exit test/*-test.js test/security/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2202 | `mocha test/runner.js --reporter spec` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2192 | `cross-env BABEL_ENV=test mocha` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2177 | `mocha test/test-*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2169 | `mocha --compilers js:babel-register` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2163 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2155 | `mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2146 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2143 | `mocha --compilers js:babel-core/register __tests__` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2078 | `npm run mocha && npm run karma` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2069 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2056 | `npm run lint && mocha -R dot && npm run cover` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2054 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2053 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2050 | `mocha && npm run lint` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2038 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2027 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 2016 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2015 | `mocha --require=test/test_helper.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 2004 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [slate/slate](https://github.com/slate/slate) | 1994 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [then/promise](https://github.com/then/promise) | 2016 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2015 | `mocha --require=test/test_helper.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 2004 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [slate/slate](https://github.com/slate/slate) | 1994 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1979 | `mocha --require ./test/common --growl test/expect.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1978 | `mocha test/**/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1970 | `mocha --reporter spec && npm run test-typescript` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1965 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1964 | `mocha --bail --reporter spec --check-leaks test/` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1962 | `bmocha --reporter spec test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1955 | `npm run lint && mocha --reporter spec test/*.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1953 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1952 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1929 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1926 | `mocha test` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1926 | `nyc mocha --timeout=20000 test.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1918 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1904 | `mocha` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1899 | `mocha --recursive` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1893 | `mocha ./test/basic.js -t 5000` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1882 | `mocha tests.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1857 | `eslint --cache . && tsc && mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1854 | `npm run lint && npm run mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1842 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1814 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1808 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1795 | `mocha --timeout 5000` | 
| [zeit/ms](https://github.com/zeit/ms) | 1792 | `mocha tests.js` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1784 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1778 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1771 | `npm run lint && mocha && npm run typescript` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1756 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1755 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1750 | `mocha test/*.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1741 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1737 | `mocha --check-leaks --reporter spec --bail` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1737 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [zeit/ms](https://github.com/zeit/ms) | 1792 | `mocha tests.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1791 | `mocha ./test/test*.js --reporter spec` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1784 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1778 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1771 | `npm run lint && mocha && npm run typescript` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1756 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1755 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1750 | `mocha test/*.js` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1741 | `./node_modules/.bin/mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1741 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1737 | `mocha --check-leaks --reporter spec --bail` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1737 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1735 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1733 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1733 | `mocha test --timeout 600000` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1730 | `mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1729 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1726 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1724 | `mocha test/**/*_test.js --bail` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1724 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1721 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1719 | `mocha` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1715 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1714 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1688 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1688 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1686 | `mocha && size-limit` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1389 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1388 | `./node_modules/mocha/bin/mocha` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1387 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1376 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1373 | `NODE_PATH=. mocha **/*.spec.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1363 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1346 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1337 | `lerna run test && mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1334 | `mocha tests/` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1329 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1328 | `mocha spec/exec.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1327 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1326 | `npm run lint && npm run mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1325 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1300 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1297 | `mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1290 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1287 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [variety/variety](https://github.com/variety/variety) | 1282 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1273 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1263 | `mocha tests` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1259 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1259 | `mocha --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1247 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1246 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [electron/asar](https://github.com/electron/asar) | 1239 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1237 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1230 | `node ./node_modules/mocha/bin/mocha tests` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1217 | `mocha test` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1213 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1207 | `mocha test/test.js` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1203 | `mocha --recursive -r tests/setup tests` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1201 | `mocha --reporter spec --bail --check-leaks test/` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1200 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1196 | `mocha --reporter spec --bail --check-leaks test/` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1194 | `npm-run-all test:jest test:server:mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1189 | `xo && mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1185 | `mocha --reporter spec test --recursive` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1194 | `npm-run-all test:jest test:server:mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1191 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1189 | `xo && mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1185 | `mocha --reporter spec test --recursive` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1181 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1176 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1176 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1175 | `mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1172 | `mocha $(find test -name '*.test.js') --exit` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1168 | `mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1168 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1167 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1161 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1157 | `istanbul cover _mocha test/*.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1088 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [tomas/needle](https://github.com/tomas/needle) | 1075 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1070 | `mocha --async-only` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1058 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1036 | `mocha --recursive test/unit/` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1025 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1022 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1020 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1007 | `mocha --compilers js:babel-register test/*.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1006 | `mocha --check-leaks -R dot` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 1004 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 989 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 983 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 972 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 971 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 963 | `nyc mocha specs` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 963 | `./node_modules/.bin/mocha --reporter spec` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 961 | `mocha` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1093 | `npm run lint && npm run mocha` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1092 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1089 | `mocha test/tests.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1088 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1081 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 1075 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1070 | `mocha --async-only` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1047 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 1046 | `mocha --recursive ./test/*_spec.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1039 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1036 | `mocha --recursive test/unit/` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1032 | `mocha --reporter spec --bail --check-leaks test/` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1025 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1023 | `mocha --reporter spec --timeout 3000` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1022 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1022 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1020 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1020 | `mocha spec/*.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1018 | `mocha --colors ./test/*.spec.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 1014 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 989 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 987 | `mocha "client.test" --compilers js:babel-register` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 983 | `mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 983 | `mocha --reporter spec` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 979 | `npm run rollup-cjs && mocha test/test.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 975 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 972 | `mocha tests` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 971 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 961 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 961 | `mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 953 | `./node_modules/.bin/mocha test/**/*` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 947 | `mocha` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 947 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 946 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 942 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 942 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 938 | `mocha test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 937 | `mocha --timeout 5000` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 709 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 706 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 702 | `mocha --reporter spec` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 699 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 698 | `jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 693 | `_mocha -u bdd --colors test/` | 
| [afc163/fanyi](https://github.com/afc163/fanyi) | 684 | `npm run lint && mocha tests/index.js --timeout 0` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 947 | `mocha` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 947 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 947 | `standard && standard ./bin/* && mocha` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 946 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 942 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 942 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 939 | `istanbul cover -- _mocha --reporter spec` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 938 | `mocha test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 937 | `mocha --timeout 5000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 928 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 918 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 916 | `mocha -t 5000` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 914 | `mocha test` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 910 | `mocha ./test/index.js` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 909 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 898 | `node_modules/.bin/mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 896 | `mocha --timeout 200000` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 898 | `node_modules/.bin/mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 893 | `node_modules/.bin/mocha test/spec` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 893 | `npm run build && istanbul test _mocha test/test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 892 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 887 | `mocha --harmony --full-trace --check-leaks` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 885 | `mocha --reporter list` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 879 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 878 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 876 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 875 | `mocha --harmony tests/**` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 874 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 873 | `mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 871 | `istanbul cover _mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 831 | `mocha && ember test` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 822 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 819 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 808 | `mocha index.test.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 808 | `mocha test` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 806 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 797 | `eslint . && mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 795 | `npm run lint && npm run mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 794 | `nyc mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 858 | `mocha --reporter spec --bail --check-leaks test/` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [developit/decko](https://github.com/developit/decko) | 856 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 856 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 855 | `mocha -r babel-register --check-leaks test/index.js` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 855 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 854 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 854 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 852 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 852 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 852 | `mocha --check-leaks -t 20000` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 851 | `nyc mocha` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 848 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 844 | `mocha --opts mocha.opts` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 843 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 841 | `mocha test` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 840 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 839 | `mocha` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 826 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [ebradyjobory/finance.js](https://github.com/ebradyjobory/finance.js) | 826 | `mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 825 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 825 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 822 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 820 | `cake build && mocha ./test/mocha/*.coffee` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 820 | `mocha test/mocha.js test/crc/index.js` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 819 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 818 | `mocha --colors --reporter spec test.js` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 813 | `mocha test` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 811 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 808 | `mocha index.test.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 808 | `mocha test` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 808 | `mocha` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 808 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 806 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 802 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 802 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 798 | `mocha --no-timeouts` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 797 | `mocha` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 797 | `eslint . && mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 795 | `npm run lint && npm run mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 794 | `nyc mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 811 | `mocha` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 811 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 808 | `mocha index.test.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 808 | `mocha test` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 808 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 807 | `mocha --require babel-register` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 806 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 802 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 802 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 798 | `mocha --no-timeouts` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 797 | `mocha` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 797 | `eslint . && mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 769 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 769 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 768 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [susam/texme](https://github.com/susam/texme) | 768 | `standard && mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 767 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 764 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 763 | `mocha --reporter spec build/test/index.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 762 | `./bin/selenium-standalone install && mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 761 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 763 | `mocha --reporter spec build/test/index.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 762 | `./bin/selenium-standalone install && mocha` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 757 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 755 | `./node_modules/.bin/mocha tests/*.js` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 755 | `mocha 'test/**/*.tests.js'` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 751 | `mocha tests/*.mocha.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 751 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 748 | `npm run test-mocha && npm run test-karma` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 763 | `mocha --reporter spec build/test/index.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 762 | `./bin/selenium-standalone install && mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 761 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 755 | `./node_modules/.bin/mocha tests/*.js` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 755 | `mocha 'test/**/*.tests.js'` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 751 | `mocha tests/*.mocha.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 751 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 