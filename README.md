# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:35 03/07/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45401 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42734 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42398 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30976 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 26219 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25963 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25526 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25302 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 21816 | `npm-run-all lint build --parallel test:mocha test:karma test:ts` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20297 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15560 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15189 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14781 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14129 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13890 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13458 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12942 | `istanbul cover _mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12879 | `mocha --reporter spec test/*-test.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12751 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12457 | `nyc grunt mocha-and-karma` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11519 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13458 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13084 | `mocha 'test/**/*.spec.js'` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12942 | `istanbul cover _mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12879 | `mocha --reporter spec test/*-test.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12751 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12695 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12457 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12378 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11748 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11519 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11333 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 11033 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [tj/co](https://github.com/tj/co) | 10490 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 10009 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9886 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9751 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9645 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9563 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9490 | `mocha -b -r esm` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9283 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9010 | `mocha test/src` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 9008 | `mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 9002 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8729 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8594 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8505 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8343 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8296 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8293 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8202 | `mocha` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8142 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8101 | `npm run eslint && npm run mocha` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8065 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7964 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7680 | `mocha --exit --require @babel/register` | 
| [almende/vis](https://github.com/almende/vis) | 7662 | `mocha --compilers js:babel-core/register` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7625 | `npm run build && istanbul cover _mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7603 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [dthree/cash](https://github.com/dthree/cash) | 7589 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7680 | `mocha --exit --require @babel/register` | 
| [almende/vis](https://github.com/almende/vis) | 7662 | `mocha --compilers js:babel-core/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7659 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7640 | `mocha; jshint *.js lib` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7625 | `npm run build && istanbul cover _mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7603 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [dthree/cash](https://github.com/dthree/cash) | 7589 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7453 | `mocha` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7346 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7155 | `mocha $HARMONY_OPTS` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7155 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7126 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 7040 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6632 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6437 | `npm run test:mocha:src` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6418 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6417 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6337 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6332 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6263 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6240 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6226 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6174 | `standard && mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6151 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5830 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5756 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5699 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5629 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5525 | `mocha test` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5486 | `mocha -r esm` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5470 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5415 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5398 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5357 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5210 | `mocha src/**/*Tests.js --harmony` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5398 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5357 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5210 | `mocha src/**/*Tests.js --harmony` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5156 | `mocha --recursive` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5144 | `gulp lint && mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5136 | `npm run lint && npm run mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5128 | `mocha --color` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5075 | `nyc mocha --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5046 | `nyc mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 5001 | `gulp build; mocha;` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4993 | `NODE_ENV=test mocha --exit` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4972 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4932 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4913 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4885 | `mocha -R spec 'tests/app'` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4884 | `mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4867 | `mocha test` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4792 | `mocha --recursive --colors` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4763 | `mocha --reporter spec -t 8000` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4699 | `mocha -R spec src` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4590 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4573 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4518 | `mocha --timeout=15000 tests/*.test.js` | 
| [hackmdio/codimd](https://github.com/hackmdio/codimd) | 4500 | `npm run-script eslint && npm run-script jsonlint && mocha` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4494 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4487 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4458 | `mocha --check-leaks --reporter spec --bail` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4416 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4383 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr) | 4258 | `npm run mocha` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4248 | `nyc mocha` | 
| [myliang/x-spreadsheet](https://github.com/myliang/x-spreadsheet) | 4185 | `./node_modules/mocha/bin/mocha --require @babel/register test/*` | 
| [muicss/mui](https://github.com/muicss/mui) | 4159 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4149 | `mocha --require test/babel-hook test/*.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 4139 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 4096 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3982 | `NODE_ENV=test mocha test/**/*.js` | 
| [enquirer/enquirer](https://github.com/enquirer/enquirer) | 3943 | `mocha && tsc -p ./test/types` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3835 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3834 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3753 | `mocha test/* --reporter spec` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3673 | `npm run jshint && npm run mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3852 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3834 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3811 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [erming/shout](https://github.com/erming/shout) | 3795 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3746 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3688 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3682 | `standard && mocha --timeout 60000 test/test.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3682 | `node_modules/.bin/mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3673 | `npm run jshint && npm run mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3611 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3607 | `nyc mocha && tsc` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3606 | `mocha tests/javascript` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3574 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3564 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3564 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3688 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3682 | `standard && mocha --timeout 60000 test/test.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3682 | `node_modules/.bin/mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3673 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3673 | `npm run jshint && npm run mocha` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3611 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3607 | `nyc mocha && tsc` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3607 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3606 | `mocha tests/javascript` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 3574 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests --exclude "tests/unit/relations/files/**"` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3564 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 3527 | `mocha` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 3524 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3300 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3274 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3270 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3236 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3195 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3189 | `./node_modules/.bin/mocha test/test.*.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3189 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3178 | `mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3139 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3138 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3124 | `nyc mocha --recursive` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3073 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3071 | `node_modules/.bin/mocha --reporter spec` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3052 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3045 | `mocha test-node` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3144 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3139 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3124 | `nyc mocha --recursive` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3113 | `npm run mocha && npm run lint` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3073 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3071 | `node_modules/.bin/mocha --reporter spec` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3045 | `mocha test-node` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 3037 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3025 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 3025 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 3024 | `mocha --require @babel/register --recursive spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3014 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2992 | `mocha -R spec --recursive src/test` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2982 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2944 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2943 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2925 | `mocha -R spec spec spec/reporters` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2390 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2367 | `node node_modules/mocha/bin/_mocha` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2335 | `mocha test/**/*.coffee` | 
| [gajus/swing](https://github.com/gajus/swing) | 2332 | `mocha --compilers js:babel-register` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2315 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2253 | `mocha && eslint *.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2246 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [share/sharedb](https://github.com/share/sharedb) | 2244 | `./node_modules/.bin/mocha && npm run jshint` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2217 | `mocha --timeout 15000 --bail --exit test/*-test.js test/security/*.js` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2211 | `mocha test/test-*.js` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2590 | `mocha test/src/**/*.unit.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2582 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2558 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2557 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2538 | `mocha test/index.js --reporter dot` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2536 | `mocha --reporter=spec test/*-test.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2527 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2507 | `nyc --require babel-register npm run _mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2477 | `mocha -R spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2454 | `mocha --no-colors --reporter spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2453 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2605 | `mocha test --exit && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2601 | `mocha && eslint .` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2594 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2593 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2582 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2570 | `mocha test` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2558 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2557 | `mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2538 | `mocha test/index.js --reporter dot` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2536 | `mocha --reporter=spec test/*-test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2534 | `export TESTING=true; mocha --reporter list` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2527 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2507 | `nyc --require babel-register npm run _mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2496 | `mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2477 | `mocha -R spec` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2132 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2117 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2112 | `npm run mocha && npm run karma` | 
| [kach/nearley](https://github.com/kach/nearley) | 2108 | `mocha test/*.test.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2101 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2080 | `mocha tests --require @babel/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2078 | `mocha && npm run lint` | 
| [htmlhint/HTMLHint](https://github.com/htmlhint/HTMLHint) | 2066 | `mocha` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2065 | `npm run lint && mocha -R dot && npm run cover` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2057 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2047 | `mocha --reporter spec --timeout 5000` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 2033 | `mocha --recursive` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2029 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 2024 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [then/promise](https://github.com/then/promise) | 2024 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2016 | `mocha --require=test/test_helper.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2253 | `mocha && eslint *.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2246 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [share/sharedb](https://github.com/share/sharedb) | 2244 | `./node_modules/.bin/mocha && npm run jshint` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2217 | `mocha --timeout 15000 --bail --exit test/*-test.js test/security/*.js` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2211 | `mocha test/test-*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2210 | `mocha test/runner.js --reporter spec` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2194 | `mocha --compilers js:babel-register` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2192 | `cross-env BABEL_ENV=test mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2166 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2163 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2162 | `mocha --compilers js:babel-core/register __tests__` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2161 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2156 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2132 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2117 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2112 | `npm run mocha && npm run karma` | 
| [kach/nearley](https://github.com/kach/nearley) | 2108 | `mocha test/*.test.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2101 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2080 | `mocha tests --require @babel/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2078 | `mocha && npm run lint` | 
| [htmlhint/HTMLHint](https://github.com/htmlhint/HTMLHint) | 2066 | `mocha` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2065 | `npm run lint && mocha -R dot && npm run cover` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2060 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2057 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 2033 | `mocha --recursive` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2029 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 2024 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [then/promise](https://github.com/then/promise) | 2024 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1998 | `mocha test/**/*.js` | 
| [slate/slate](https://github.com/slate/slate) | 1993 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1984 | `mocha --reporter spec && npm run test-typescript` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1980 | `mocha --require ./test/common --growl test/expect.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1971 | `mocha --bail --reporter spec --check-leaks test/` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1971 | `bmocha --reporter spec test/*.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1970 | `npm run lint && mocha --reporter spec test/*.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1969 | `nyc mocha --timeout=20000 test.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1963 | `mocha -c test/index.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1959 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1892 | `eslint --cache . && tslint --project . && node build && mocha && tsc` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1885 | `mocha tests.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1863 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1854 | `mocha ./test/test*.js --reporter spec` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1835 | `mocha test/setup.js test/spec/*.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1824 | `mocha test` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1815 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1794 | `mocha --timeout 5000` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1790 | `mocha` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1790 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1775 | `npm run lint && mocha && npm run typescript` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1644 | `mocha --expose-gc --slow 300` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1640 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1634 | `mocha test/unit` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1630 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1629 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1627 | `./node_modules/mocha/bin/mocha -R spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1624 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1624 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1623 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1615 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1614 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1558 | `node_modules/.bin/mocha --recursive` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1556 | `npm run lint && mocha && karma start --single-run` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1552 | `mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1546 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1545 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1545 | `mocha -u tdd` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1782 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1775 | `npm run lint && mocha && npm run typescript` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1762 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1762 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1758 | `mocha test/*.js` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1757 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1750 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1747 | `./node_modules/.bin/mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1741 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1735 | `mocha test --timeout 600000` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1734 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1734 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1732 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1728 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1726 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1725 | `mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1724 | `mocha test/**/*_test.js --bail` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1722 | `mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1569 | `mocha --check-leaks --require @babel/register` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1561 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1558 | `node_modules/.bin/mocha --recursive` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1552 | `mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1546 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1545 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1545 | `mocha -u tdd` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1535 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1532 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1532 | `mocha --recursive test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1523 | `mocha --timeout 10000 ./tests/lib.js` | 
| [fbeline/design-patterns-JS](https://github.com/fbeline/design-patterns-JS) | 1522 | `mocha test --compilers js:babel-core/register` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1522 | `mocha test/**/*.spec.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1521 | `mocha -R spec test/*.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1510 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1630 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1627 | `mocha -R spec ./test/unit/**` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1627 | `./node_modules/mocha/bin/mocha -R spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1624 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1623 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1615 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1614 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1610 | `mocha tests/test-*` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1589 | `nyc mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1569 | `mocha --check-leaks --require @babel/register` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1457 | `mocha test.js` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1450 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1443 | `npm run build && mocha -r should` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1440 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1437 | `mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1436 | `webpack && npm run lint && npm run mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1425 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1417 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1415 | `npm run mocha:istanbul` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1405 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1402 | `mocha --recursive` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1400 | `mocha --compilers js:babel-core/register` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1436 | `webpack && npm run lint && npm run mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1425 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1422 | `mocha --check-leaks --reporter spec --bail test/` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1421 | `mocha --recursive test/bin` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1417 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1405 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1402 | `mocha --recursive` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1398 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1397 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1389 | `./node_modules/mocha/bin/mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1387 | `./node_modules/.bin/mocha test` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1387 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1374 | `cross-env NODE_ENV=test nyc mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1374 | `npm run lint && mocha --require @babel/register` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1450 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1448 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1443 | `npm run build && mocha -r should` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1440 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1437 | `mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1436 | `webpack && npm run lint && npm run mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1425 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1422 | `mocha --check-leaks --reporter spec --bail test/` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1421 | `istanbul cover _mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1421 | `mocha --recursive test/bin` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1417 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1415 | `npm run mocha:istanbul` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1405 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1402 | `mocha --recursive` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1400 | `mocha --compilers js:babel-core/register` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1397 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1397 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1392 | `NODE_PATH=. mocha **/*.spec.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1389 | `./node_modules/mocha/bin/mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1387 | `./node_modules/.bin/mocha test` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1374 | `cross-env NODE_ENV=test nyc mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1374 | `npm run lint && mocha --require @babel/register` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1356 | `mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1351 | `mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1351 | `mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1351 | `mocha tests/` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1349 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1348 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1346 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1346 | `mocha --timeout 60000 test/` | 
| [localtunnel/server](https://github.com/localtunnel/server) | 1344 | `mocha --check-leaks --require esm './**/*.test.js'` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1343 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1342 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1339 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1337 | `mocha --timeout 20000` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1337 | `mocha test/*.js` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1335 | `mocha` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1334 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1334 | `mocha --timeout 30000 --recursive ./tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1333 | `eslint --fix lib/ test/ module/ && mocha test/*.js module/**/test/*.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1331 | `mocha src/test.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1330 | `mocha spec/exec.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1329 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1326 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1323 | `mocha-phantomjs tests/index.html` | 
| [variety/variety](https://github.com/variety/variety) | 1288 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1280 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1274 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1264 | `mocha tests` | 
| [normalize/mz](https://github.com/normalize/mz) | 1262 | `mocha --reporter spec` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1252 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1252 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1250 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1242 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1240 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1274 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [normalize/mz](https://github.com/normalize/mz) | 1262 | `mocha --reporter spec` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1252 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1252 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1250 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1242 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1240 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1220 | `mocha --recursive -r tests/setup tests` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1215 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1213 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1213 | `mocha --reporter spec --bail --check-leaks test/` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1211 | `mocha --reporter spec test --recursive` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1211 | `mocha test` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1208 | `mocha test/test.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1206 | `npm-run-all test:jest test:server:mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1195 | `xo && mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1183 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1180 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1116 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1113 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1112 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1110 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1102 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1101 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1097 | `mocha --check-leaks -t 20000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1097 | `node_modules/.bin/mocha && npm run lint` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1093 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1087 | `mocha test/tests.js` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1087 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 944 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 937 | `mocha --timeout 5000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 933 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 925 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 924 | `mocha -t 5000` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 922 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 920 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 915 | `mocha test` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1097 | `node_modules/.bin/mocha && npm run lint` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1096 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1087 | `mocha test/tests.js` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1087 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 1085 | `mocha test` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1074 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1073 | `mocha --async-only` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1065 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1062 | `mocha test/*.test.js` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1058 | `mocha $(find test -name '*.test.js')` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1058 | `mocha $(find test -name '*.test.js')` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1052 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 1042 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1040 | `mocha --recursive test/unit/` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1039 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1032 | `mocha --reporter spec --bail --check-leaks test/` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1032 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1028 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1028 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1027 | `mocha spec/*.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1026 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1025 | `npm run lint && mocha -R spec` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 996 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 989 | `mocha "client.test" --compilers js:babel-register` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 986 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 985 | `mocha --reporter spec` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 983 | `mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 983 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 982 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 979 | `mocha -t 600000 --exit` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 979 | `npm run rollup-cjs && mocha test/test.js` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 970 | `./node_modules/.bin/mocha --reporter spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 969 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 969 | `mocha` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 968 | `mocha` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 965 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 964 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 963 | `mocha` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 963 | `./node_modules/.bin/mocha test/**/*` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 962 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 955 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 948 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 944 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 944 | `istanbul cover -- _mocha --reporter spec` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 937 | `mocha --timeout 5000` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 936 | `mocha test/index.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 933 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 928 | `mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 925 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 924 | `mocha -t 5000` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 923 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 922 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 901 | `npm run build && istanbul test _mocha test/test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 899 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 895 | `mocha --harmony tests/**` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 895 | `mocha --harmony --full-trace --check-leaks` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 892 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 890 | `npm run lint && mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 888 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 887 | `mocha --reporter list` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 886 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 875 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 874 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 874 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 871 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 867 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 865 | `mocha --reporter spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 863 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 861 | `mocha -r babel-register --check-leaks test/index.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 861 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 858 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 857 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 856 | `mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 854 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 853 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 844 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 844 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 842 | `mocha test` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 856 | `mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 856 | `mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 854 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 853 | `mocha` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 850 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 844 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 844 | `mocha` | 
| [ebradyjobory/finance.js](https://github.com/ebradyjobory/finance.js) | 844 | `mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 842 | `mocha test` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 841 | `mocha --async-only` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 840 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 839 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 837 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 837 | `mocha test` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 836 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 850 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 844 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 844 | `mocha` | 
| [ebradyjobory/finance.js](https://github.com/ebradyjobory/finance.js) | 844 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 842 | `mocha test` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 841 | `mocha --async-only` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 840 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 837 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 837 | `mocha test` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 836 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 833 | `npm run mocha-test test/integration` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 833 | `mocha test/mocha.js test/crc/index.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 832 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 832 | `_mocha` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 832 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 740 | `mocha $(find test -name '*.test.js')` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 738 | `mocha ./test/test.js --timeout 1000000` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 737 | `mocha` | 
| [formio/formio](https://github.com/formio/formio) | 736 | `env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 736 | `mocha --reporter spec test/` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 730 | `mocha --reporter spec` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 727 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 726 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 719 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 717 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 797 | `mocha tests --timeout 10000` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 793 | `mocha --recursive -s 15 test/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [fivdi/onoff](https://github.com/fivdi/onoff) | 787 | `nyc mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 786 | `mocha` | 
| [koajs/static](https://github.com/koajs/static) | 783 | `mocha --harmony --reporter spec --exit` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 779 | `babel-node node_modules/.bin/_mocha -- test` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 779 | `npm run-script jshint && npm run-script mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 798 | `mocha --no-timeouts` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 797 | `mocha tests --timeout 10000` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 796 | `npm run lint && npm run mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 793 | `mocha --recursive -s 15 test/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [fivdi/onoff](https://github.com/fivdi/onoff) | 787 | `nyc mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 786 | `mocha` | 
| [pburtchaell/react-notification](https://github.com/pburtchaell/react-notification) | 657 | `node_modules/.bin/mocha --compilers js:babel-core/register --reporter spec --recursive --timeout 5000 test/setup.js test/**/*.js` | 
| [omnidan/node-emoji](https://github.com/omnidan/node-emoji) | 657 | `./node_modules/.bin/mocha --require should --bail --reporter spec test/*` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 657 | `mocha` | 
| [jbrooksuk/node-summary](https://github.com/jbrooksuk/node-summary) | 656 | `mocha --compilers js:babel-core/register --require should --reporter spec` | 
| [spirit/spirit](https://github.com/spirit/spirit) | 654 | `BABEL_ENV=modules NODE_ENV=test mocha -r babel-register -r babel-polyfill -r ./test/bootstrap.js --timeout 5000` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 650 | `./node_modules/.bin/mocha test/integration` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 650 | `./node_modules/.bin/mocha --bail` | 
| [azmenak/react-stripe-checkout](https://github.com/azmenak/react-stripe-checkout) | 649 | `mocha --require babel-register --require .test-setup.js -R spec ./spec.js` | 
| [postcss/gulp-postcss](https://github.com/postcss/gulp-postcss) | 647 | `nyc mocha test.js` | 
| [vault-development/react-native-svg-uri](https://github.com/vault-development/react-native-svg-uri) | 646 | `./node_modules/mocha/bin/mocha --compilers js:babel-core/register` | 
| [gauntface/simple-push-demo](https://github.com/gauntface/simple-push-demo) | 646 | `gulp && npm run lint && node ./test/helpers/download-browsers.js && mocha` | 
| [jshttp/http-errors](https://github.com/jshttp/http-errors) | 644 | `mocha --reporter spec --bail` | 
| [edankwan/penis.js](https://github.com/edankwan/penis.js) | 640 | `mocha --ui bdd --reporter spec test/` | 
| [fent/node-ytdl](https://github.com/fent/node-ytdl) | 638 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [hparra/gulp-rename](https://github.com/hparra/gulp-rename) | 638 | `mocha` | 