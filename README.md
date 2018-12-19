# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:54 12/19/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44644 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41839 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41546 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30708 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 25035 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24581 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21067 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19855 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18140 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17732 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17581 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16708 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14837 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14687 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14611 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13778 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13447 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12932 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12680 | `mocha --reporter spec test/*-test.js` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12608 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12606 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12332 | `mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12157 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12115 | `nyc grunt mocha-and-karma` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12098 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11269 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10944 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10786 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10719 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 10531 | `mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10498 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10342 | `mocha --harmony` | 
| [websockets/ws](https://github.com/websockets/ws) | 10221 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9635 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9595 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9480 | `mocha tests/*.js` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9387 | `mocha -b -r esm` | 
| [amark/gun](https://github.com/amark/gun) | 9233 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9221 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9221 | `grunt mocha` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8790 | `mocha test/src` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8639 | `mocha --opts mocha.opts` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8637 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8537 | `mocha --check-leaks -R dot` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8461 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8417 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8400 | `mocha --compilers js:babel-register test/test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8363 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8200 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8008 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7928 | `./node_modules/.bin/mocha test` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7830 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7827 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7744 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7733 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7725 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6694 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6623 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6400 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6347 | `npm run test:mocha:src` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6211 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6179 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6123 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6097 | `mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6070 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6048 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6034 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6486 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6400 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6347 | `npm run test:mocha:src` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6211 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6179 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6123 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6097 | `mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6070 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6057 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6048 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6034 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5936 | `mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4477 | `mocha -R spec src` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4476 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4461 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4360 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4338 | `mocha --timeout=15000 tests/*.test.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4288 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4244 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4228 | `nyc mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4226 | `mocha --check-leaks --reporter spec --bail` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4199 | `npm run lint ; mocha && mocha test/individual` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4175 | `NODE_ENV=test mocha --exit` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5135 | `mocha --color` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5118 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5091 | `gulp lint && mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 4997 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4931 | `mocha --recursive` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4907 | `gulp build; mocha;` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4904 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4851 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4830 | `mocha -R spec 'tests/app'` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4827 | `./node_modules/.bin/mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4822 | `mocha test` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4812 | `nyc mocha --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4794 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4765 | `npm run lint && npm run mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4729 | `mocha --reporter spec -t 8000` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4728 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4718 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4695 | `nyc mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4570 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4526 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 4477 | `mocha -R spec src` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4476 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 4461 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4360 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4338 | `mocha --timeout=15000 tests/*.test.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 4288 | `node_modules/.bin/mocha test/tests.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4244 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4228 | `nyc mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 4226 | `mocha --check-leaks --reporter spec --bail` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4201 | `mocha -R spec ./test --recursive` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4199 | `npm run lint ; mocha && mocha test/individual` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 4175 | `NODE_ENV=test mocha --exit` | 
| [muicss/mui](https://github.com/muicss/mui) | 4111 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 4093 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 4070 | `mocha --require should --reporter spec` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 4050 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3983 | `nyc mocha "test/**/*.test.js"` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3863 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3810 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3790 | `NODE_ENV=test mocha test/**/*.js` | 
| [primus/primus](https://github.com/primus/primus) | 3776 | `npm run build && mocha test/*.test.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3714 | `nyc --reporter=html --reporter=text --reporter lcovonly mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 3688 | `mocha test/* --reporter spec` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3680 | `standard && mocha --timeout 60000 test/test.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3676 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3653 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3597 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3575 | `mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3573 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3571 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3556 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3668 | `npm run jshint && npm run mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3653 | `cross-env BABEL_ENV=test mocha --require babel-register test/test.js` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 3638 | `npm run build && mocha test/bootstrap.js --recursive test` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3631 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3628 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3597 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3575 | `mocha --reporter spec --timeout 3000` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3573 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3571 | `npm run lint && nyc --reporter=html --reporter=text mocha --require test/support/env` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3556 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3524 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3481 | `nyc mocha && tsc` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3479 | `node_modules/.bin/mocha test/lib/` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 3473 | `eslint . && mocha -t 5000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3458 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3451 | `mocha` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3273 | `mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3233 | `mocha test/index.js && npm run demo` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3230 | `mocha -R landing test/index --exit` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3200 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3174 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3165 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3162 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3158 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3133 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3126 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3065 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3065 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [mde/ejs](https://github.com/mde/ejs) | 3060 | `mocha --require should --reporter spec` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3052 | `eslint . && nyc mocha --recursive` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3051 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3038 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2992 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2981 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2957 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2948 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2943 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2939 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2924 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2922 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2921 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2911 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2904 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2874 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2869 | `mocha -R spec spec spec/reporters` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2421 | `mocha -R spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2373 | `node node_modules/mocha/bin/_mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2365 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2359 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2335 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2289 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [gajus/swing](https://github.com/gajus/swing) | 2285 | `mocha --compilers js:babel-register` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2246 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2234 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2218 | `mocha test test/unit/**/*_test.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2750 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2741 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2728 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2714 | `mocha "./test/**/*-test.js"` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2707 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2701 | `mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 2700 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2691 | `nyc mocha --timeout=10000` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2679 | `mocha --timeout 100000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2668 | `nyc mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2628 | `mocha-phantomjs ./test/index.html` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2626 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2623 | `mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2595 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2588 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2424 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2421 | `mocha -R spec` | 
| [Qix-/color](https://github.com/Qix-/color) | 2393 | `mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2375 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2373 | `node node_modules/mocha/bin/_mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2365 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2359 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2335 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2334 | `nyc --require babel-register npm run _mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2330 | `npm run build && mocha --require babel-register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2314 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2289 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [gajus/swing](https://github.com/gajus/swing) | 2285 | `mocha --compilers js:babel-register` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 2282 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1571 | `mocha --recursive` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1556 | `./node_modules/.bin/mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1551 | `mocha ./test/test*.js --reporter spec` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1526 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1507 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1501 | `mocha -R spec ./test/unit/**` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1501 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --compilers js:babel-core/register --recursive --exit` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1499 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1494 | `mocha tests/test-*` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1486 | `mocha --timeout 10000 ./tests/lib.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1485 | `mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1476 | `mocha -R spec` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1472 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1472 | `mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2234 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2218 | `mocha test test/unit/**/*_test.js` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2216 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2212 | `standard && mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 2194 | `npm run lint && npm run mocha` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2187 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2175 | `cross-env BABEL_ENV=test mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2160 | `mocha test/runner.js --reporter spec` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2154 | `mocha && eslint *.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2154 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2152 | `mocha test/**/*.coffee` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2139 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2137 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2105 | `mocha --compilers js:babel-core/register __tests__` | 
| [share/sharedb](https://github.com/share/sharedb) | 2097 | `./node_modules/.bin/mocha && npm run jshint` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2093 | `mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2091 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2049 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2036 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2031 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [kach/nearley](https://github.com/kach/nearley) | 2017 | `mocha test/*.test.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2014 | `npm run lint && mocha -R dot && npm run cover` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2009 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1996 | `mocha --require=test/test_helper.js` | 
| [slate/slate](https://github.com/slate/slate) | 1996 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1995 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1996 | `mocha --require=test/test_helper.js` | 
| [slate/slate](https://github.com/slate/slate) | 1996 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1995 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [then/promise](https://github.com/then/promise) | 1983 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1982 | `mocha tests --require @babel/register` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1963 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1955 | `mocha --bail --reporter spec --check-leaks test/` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1954 | `mocha && npm run lint` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1953 | `mocha --require ./test/common --growl test/expect.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1942 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1927 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1923 | `mocha --reporter spec && npm run test-typescript` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1832 | `mocha ./test/basic.js -t 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1830 | `npm run lint && npm run mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1820 | `mocha test` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1819 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1813 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1794 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1775 | `npm run lint && npm run mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1765 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1733 | `./node_modules/.bin/mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1733 | `nyc mocha --timeout=20000 test.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1730 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1729 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1819 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1813 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1798 | `mocha --timeout 5000` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1794 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1775 | `npm run lint && npm run mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1765 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1753 | `eslint --cache . && tsc && mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1747 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1733 | `./node_modules/.bin/mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1733 | `nyc mocha --timeout=20000 test.js` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1672 | `mocha && size-limit` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1666 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1665 | `xo && mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1658 | `mocha` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1656 | `mocha --check-leaks --reporter spec --bail` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1656 | `mocha` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1655 | `mocha test/test-*.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1644 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1637 | `mocha tests/test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1635 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1615 | `mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1602 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1600 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1596 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1596 | `./node_modules/mocha/bin/mocha -R spec` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1595 | `mocha test.js` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1593 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1575 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1573 | `NODE_ENV=test mocha tests/*.js` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1562 | `nyc mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1562 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1557 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1551 | `mocha ./test/test*.js --reporter spec` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1593 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1575 | `standard && cd frontend && ng lint && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1573 | `NODE_ENV=test mocha tests/*.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1571 | `mocha --recursive` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1562 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1557 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1556 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1536 | `node_modules/.bin/mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1532 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1530 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1420 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1413 | `npm run build && mocha -r should` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1402 | `npm run prepublishOnly && mocha test/test.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1402 | `istanbul cover _mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1393 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1389 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1385 | `mocha --recursive test/bin` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1383 | `mocha --recursive` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1372 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1370 | `mocha test --compilers js:babel-core/register` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1369 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1368 | `cross-env NODE_ENV=test nyc mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1367 | `./node_modules/.bin/mocha test` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1452 | `mocha test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1439 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1435 | `standard && istanbul cover _mocha` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1432 | `mocha --opts test/opts/mocha.opts` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 1431 | `mocha --recursive` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1427 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1413 | `npm run build && mocha -r should` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1402 | `npm run prepublishOnly && mocha test/test.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1402 | `istanbul cover _mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1393 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1389 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1320 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1316 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1316 | `mocha-phantomjs tests/index.html` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1313 | `mocha spec/exec.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1311 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1310 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1310 | `webpack && npm run lint && npm run mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1304 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1302 | `npm run mocha:istanbul` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1295 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1288 | `mocha src/test.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1285 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1284 | `npm run lint && npm run mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1283 | `mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1280 | `npm run lint && mocha --require @babel/register` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1274 | `mocha tests/` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1273 | `istanbul test _mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1263 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1261 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1258 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1258 | `mocha tests` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1249 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1247 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1245 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1242 | `mocha --timeout 30000 --recursive ./tests` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1238 | `mocha` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1236 | `mocha --timeout 20000` | 
| [normalize/mz](https://github.com/normalize/mz) | 1233 | `mocha --reporter spec` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1231 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1231 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1221 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1220 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1219 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1213 | `mocha test/test.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1212 | `mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1208 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1205 | `mocha test` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1204 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1192 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1185 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1176 | `mocha --recursive -r tests/setup tests` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1172 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1165 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1164 | `xo && mocha` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1162 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1154 | `mocha --reporter spec --bail --check-leaks test/` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1152 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1151 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1150 | `npm-run-all test:jest test:server:mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1149 | `istanbul cover _mocha test/*.js` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 1147 | `mocha` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1146 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1145 | `mocha --reporter spec --bail --check-leaks test/` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1084 | `mocha --compilers js:babel-register` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1084 | `eslint src test && mocha --compilers babel-register` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1083 | `npm run convertto:es5 && npm run mocha` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1080 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1079 | `mocha test/tests.js` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1054 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1053 | `mocha --async-only` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1084 | `mocha --compilers js:babel-register` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1084 | `eslint src test && mocha --compilers babel-register` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1083 | `npm run convertto:es5 && npm run mocha` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1081 | `mocha` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1080 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1079 | `mocha test/tests.js` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 1063 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [tomas/needle](https://github.com/tomas/needle) | 1058 | `mocha test` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1054 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1054 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1030 | `mocha --reporter spec --timeout 3000` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1029 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1028 | `mocha --recursive test/unit/` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1018 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1013 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1007 | `mocha --check-leaks -R dot` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1005 | `mocha --reporter spec --bail --check-leaks test/` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1002 | `mocha -R list` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1002 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 997 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1029 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1028 | `mocha --recursive test/unit/` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1014 | `mocha --colors ./test/*.spec.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1013 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1007 | `mocha --check-leaks -R dot` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1005 | `mocha --reporter spec --bail --check-leaks test/` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1002 | `mocha -R list` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1002 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 997 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 897 | `mocha test` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 895 | `./node_modules/.bin/mocha test/**/*` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 893 | `node_modules/.bin/mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 886 | `mocha --timeout 200000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 882 | `./node_modules/.bin/mocha --globals angular,require` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 881 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 879 | `node_modules/.bin/mocha test/spec` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 976 | `mocha` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 976 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 974 | `npm run rollup-cjs && mocha test/test.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 974 | `mocha "client.test" --compilers js:babel-register` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 973 | `mocha spec/*.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 971 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 970 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 968 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 967 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 966 | `mocha --recursive ./test/*_spec.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 965 | `mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 960 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 954 | `./node_modules/.bin/mocha --reporter spec` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 931 | `mocha test --compilers js:babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 924 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 921 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 920 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 920 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 914 | `istanbul cover -- _mocha --reporter spec` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 912 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 912 | `mocha -t 5000` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 910 | `standard && standard ./bin/* && mocha` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 909 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 900 | `npm run lint && npm run mocha:no-functional` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 900 | `mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 897 | `mocha test` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 895 | `./node_modules/.bin/mocha test/**/*` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 894 | `mocha test/index.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 886 | `mocha --timeout 200000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 882 | `./node_modules/.bin/mocha --globals angular,require` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 881 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 881 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 879 | `node_modules/.bin/mocha test/spec` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 876 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 876 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 874 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 869 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 868 | `mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 866 | `mocha --reporter list` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 865 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 863 | `npm run build && istanbul test _mocha test/test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 862 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 862 | `eslint test && mocha --compilers js:babel/register` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 861 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 859 | `istanbul cover _mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 858 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 858 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 857 | `mocha --reporter spec` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 852 | `mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 852 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 852 | `mocha --check-leaks -t 20000` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 848 | `mocha --reporter spec --bail --check-leaks test/` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 847 | `npm run lint && mocha` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 845 | `mocha -r should --exit test/*.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 842 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 841 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 841 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 839 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 838 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 838 | `mocha --opts mocha.opts` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 837 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 837 | `mocha --async-only` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 842 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 841 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 841 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 839 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 838 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 838 | `mocha --opts mocha.opts` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 837 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 837 | `mocha --async-only` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 835 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 832 | `mocha` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 829 | `mocha -r babel-register --check-leaks test/index.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 829 | `mocha && ember test` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 828 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [developit/decko](https://github.com/developit/decko) | 827 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 826 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 825 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 824 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 823 | `nyc mocha` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 821 | `mocha --harmony tests/**` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 821 | `mocha test` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 820 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 820 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 818 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 818 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 817 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 813 | `npm run mocha-test test/integration` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 813 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 812 | `cake build && mocha ./test/mocha/*.coffee` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 812 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [edsu/anon](https://github.com/edsu/anon) | 811 | `mocha --colors --reporter spec test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 801 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 798 | `npm run lint && mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 794 | `mocha -R spec tests/` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 794 | `xo && mocha -R spec` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 790 | `mocha --no-timeouts` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 790 | `mocha --no-timeouts` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 785 | `mocha` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 784 | `_mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 782 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 782 | `mocha test` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 781 | `mocha` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 781 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 781 | `npm run lint && npm run mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 778 | `nyc mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 778 | `mocha --recursive -s 15 test/` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 774 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 768 | `babel-node node_modules/.bin/_mocha -- test` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 764 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 762 | `jenkins-mocha ./tests/*.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 762 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 761 | `mocha` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 761 | `npm run-script jshint && npm run-script mocha` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 760 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [koajs/static](https://github.com/koajs/static) | 747 | `mocha --harmony --reporter spec --exit` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 746 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 743 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 742 | `mocha test.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 741 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 739 | `mocha test` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 739 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 736 | `npm run bundle && mocha` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 708 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 708 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [typicode/katon](https://github.com/typicode/katon) | 707 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 699 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 699 | `mocha --reporter spec` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 698 | `mocha` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 697 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 697 | `mocha --reporter spec` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 693 | `mocha` | 