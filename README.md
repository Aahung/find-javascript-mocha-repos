# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:56:52 03/17/19 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45546 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42887 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42465 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30991 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 26388 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 26049 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25648 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25328 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 21933 | `npm-run-all lint build --parallel test:mocha test:karma test:ts` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20343 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18910 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18351 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18196 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 18003 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15667 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15254 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14806 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 14161 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13961 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13555 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13100 | `mocha 'test/**/*.spec.js'` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12994 | `istanbul cover _mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12901 | `mocha --reporter spec test/*-test.js` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12814 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12759 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12485 | `nyc grunt mocha-and-karma` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12381 | `mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11804 | `mocha test/index.js` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11614 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11389 | `set NODE_ENV=test && mocha` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 11083 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [websockets/ws](https://github.com/websockets/ws) | 10834 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10797 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10515 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 10078 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9920 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9772 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9680 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9612 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9509 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9411 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9359 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 9091 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 9087 | `mocha test/*/**` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 9035 | `mocha test/src` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8749 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8682 | `mocha --compilers js:babel-register test/test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8628 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8598 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8521 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8423 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8316 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8298 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8260 | `mocha` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8190 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8125 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8120 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8119 | `./node_modules/.bin/mocha test` | 
| [aui/art-template](https://github.com/aui/art-template) | 7985 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7746 | `mocha --exit --require @babel/register` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7735 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [almende/vis](https://github.com/almende/vis) | 7698 | `mocha --compilers js:babel-core/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7688 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7673 | `mocha; jshint *.js lib` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7639 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7453 | `mocha` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7376 | `mocha` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7233 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7169 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7151 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 7094 | `mocha test/test.js` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6651 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6449 | `npm run test:mocha:src` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6449 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6373 | `mocha` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6354 | `mocha tests/node.js` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 6305 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6273 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6270 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 6216 | `standard && mocha` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6165 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 6120 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6069 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 6012 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5957 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5935 | `mocha && eslint lib/**` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5923 | `mocha` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5889 | `npm run lint && mocha tests/**/*.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5852 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5779 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5741 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5636 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5558 | `mocha test` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5525 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5508 | `mocha -r esm` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5449 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5436 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5397 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5212 | `mocha src/**/*Tests.js --harmony` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5186 | `mocha --recursive` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 5165 | `npm run lint && npm run mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5151 | `gulp lint && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5126 | `mocha --color` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 5115 | `nyc mocha --exit` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 5095 | `NODE_ENV=test mocha --exit` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 5081 | `nyc mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 5008 | `gulp build; mocha;` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4992 | `./node_modules/.bin/mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4933 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4921 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3469 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3468 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3457 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3446 | `mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3420 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3406 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3377 | `mocha test/index.js && npm run demo` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3314 | `mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3300 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3294 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3197 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3191 | `./node_modules/.bin/mocha test/test.*.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3181 | `mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3161 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3159 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3153 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3134 | `nyc mocha --recursive` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3120 | `npm run mocha && npm run lint` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3090 | `node_modules/.bin/mocha --reporter spec` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3075 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 3067 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3065 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3061 | `mocha test-node` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 3055 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 3040 | `mocha --require @babel/register --recursive spec` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3031 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 3028 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2996 | `mocha -R spec --recursive src/test` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2988 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2988 | `mocha` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2980 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2929 | `mocha -R spec spec spec/reporters` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2922 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2892 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2851 | `istanbul cover _mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2846 | `mocha "./test/**/*-test.js"` | 
| [css/csso](https://github.com/css/csso) | 2838 | `mocha --reporter dot` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2805 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2788 | `mocha --require should --reporter spec` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2775 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2774 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [nosqlclient/nosqlclient](https://github.com/nosqlclient/nosqlclient) | 2761 | `cross-env TEST_BROWSER_DRIVER=chrome BABEL_ENV=coverage COVERAGE=1 COVERAGE_OUT_LCOVONLY=1 COVERAGE_APP_FOLDER=$PWD/ meteor test --once --driver-package meteortesting:mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2759 | `nyc mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2745 | `nyc mocha --timeout=10000` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2736 | `mocha test/unit --require mochahook` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2655 | `mocha-phantomjs ./test/index.html` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2646 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2622 | `mocha test --exit && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2613 | `mocha && eslint .` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2608 | `mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2597 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2557 | `mocha test/index.js --reporter dot` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2535 | `export TESTING=true; mocha --reporter list` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2532 | `nyc --require babel-register npm run _mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2519 | `mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2483 | `mocha -R spec` | 
| [noble/noble](https://github.com/noble/noble) | 2471 | `mocha -R spec test/*.js` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2483 | `mocha -R spec` | 
| [noble/noble](https://github.com/noble/noble) | 2471 | `mocha -R spec test/*.js` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2456 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2420 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [pahen/madge](https://github.com/pahen/madge) | 2396 | `npm run lint && npm run mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2392 | `grunt jshint && mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2373 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2347 | `mocha test/**/*.coffee` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2334 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2068 | `npm run lint && mocha -R dot && npm run cover` | 
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 2062 | `mocha --recursive` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2031 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1993 | `mocha --reporter spec && npm run test-typescript` | 
| [slate/slate](https://github.com/slate/slate) | 1993 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1982 | `mocha --require ./test/common --growl test/expect.js` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1977 | `bmocha --reporter spec test/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1974 | `mocha --bail --reporter spec --check-leaks test/` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1973 | `npm run lint && mocha --reporter spec test/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1965 | `mocha -c test/index.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1959 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1955 | `mocha --reporter spec --grep .` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1951 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1948 | `mocha test -u bdd -R spec` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1947 | `mocha test` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1917 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1886 | `mocha ./test/test*.js --reporter spec` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1885 | `mocha tests.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2373 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2347 | `mocha test/**/*.coffee` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2345 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2334 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [gajus/swing](https://github.com/gajus/swing) | 2334 | `mocha --compilers js:babel-register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2323 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2320 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2295 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2287 | `standard && mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 2281 | `./node_modules/.bin/mocha && npm run jshint` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2265 | `mocha` | 
| [benoitvallon/computer-science-in-javascript](https://github.com/benoitvallon/computer-science-in-javascript) | 2257 | `npm run lint && mocha tests/**/*.js` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1656 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1646 | `mocha --expose-gc --slow 300` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1646 | `mocha --recursive` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1631 | `mocha test.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1630 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1625 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1624 | `mocha tests/test-*` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1616 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1579 | `npm run lint && npm run mocha` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1563 | `mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1563 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1560 | `node_modules/.bin/mocha --recursive` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1557 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1550 | `npm run test:lint && npm run test:mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1549 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1547 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1547 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1542 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2068 | `npm run lint && mocha -R dot && npm run cover` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2065 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2058 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2055 | `mocha --reporter spec --timeout 5000` | 
| [then/promise](https://github.com/then/promise) | 2029 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2020 | `mocha --require=test/test_helper.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 2012 | `mocha test/**/*.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1998 | `nyc mocha --timeout=20000 test.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1993 | `mocha --reporter spec && npm run test-typescript` | 
| [slate/slate](https://github.com/slate/slate) | 1993 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1982 | `mocha --require ./test/common --growl test/expect.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1315 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1305 | `istanbul test _mocha` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1302 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1300 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1265 | `mocha tests` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1251 | `mocha test` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1241 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1223 | `mocha --recursive -r tests/setup tests` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1221 | `mocha --reporter spec test --recursive` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1218 | `mocha --reporter spec --bail --check-leaks test/` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1351 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1351 | `mocha --timeout 60000 test/` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1342 | `mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1339 | `mocha test/*.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1338 | `mocha spec/exec.js` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1330 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1322 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1321 | `mocha-phantomjs tests/index.html` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1305 | `istanbul test _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1304 | `mocha` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1300 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [variety/variety](https://github.com/variety/variety) | 1293 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1282 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [normalize/mz](https://github.com/normalize/mz) | 1267 | `mocha --reporter spec` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1258 | `mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1256 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1255 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1251 | `mocha test` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1241 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1232 | `node ./node_modules/mocha/bin/mocha tests` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1227 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1224 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1223 | `mocha --recursive -r tests/setup tests` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1222 | `mocha --reporter spec --bail --check-leaks test/` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1221 | `mocha --reporter spec test --recursive` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1227 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1224 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1223 | `mocha --recursive -r tests/setup tests` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1222 | `mocha --reporter spec --bail --check-leaks test/` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1221 | `mocha --reporter spec test --recursive` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1218 | `mocha --reporter spec --bail --check-leaks test/` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1216 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1214 | `mocha test` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1213 | `npm-run-all test:jest test:server:mocha` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1209 | `mocha test/test.js` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1202 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1196 | `xo && mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1159 | `mocha && standard` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1158 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1136 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1128 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1120 | `mocha` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1117 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1114 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1111 | `mocha --recursive --bail --reporter spec test` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [odota/core](https://github.com/odota/core) | 1078 | `NODE_ENV=test mocha --exit` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1075 | `mocha --async-only` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1059 | `mocha $(find test -name '*.test.js')` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 1058 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1044 | `mocha --recursive test/unit/` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1039 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1036 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1031 | `./node_modules/.bin/mocha -R spec` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1075 | `mocha --async-only` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 1058 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1053 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1044 | `mocha --recursive test/unit/` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1040 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1040 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1039 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1036 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1032 | `mocha --reporter spec --bail --check-leaks test/` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1031 | `npm run lint && mocha -R spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 1031 | `./node_modules/.bin/mocha -R spec` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1031 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1031 | `mocha spec/*.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1029 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1025 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 1025 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1024 | `mocha --reporter spec --timeout 3000` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 1022 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1020 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 1013 | `mocha --compilers js:babel-register test/*.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1009 | `mocha -R list` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 875 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 873 | `istanbul cover _mocha` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 868 | `mocha -r babel-register --check-leaks test/index.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 868 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 867 | `mocha --reporter spec` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 865 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 864 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 862 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 860 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 857 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 854 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 853 | `mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 851 | `mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 845 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 845 | `mocha test` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 841 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 939 | `mocha test/index.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 937 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 936 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 936 | `mocha --timeout 5000` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 931 | `mocha` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 926 | `mocha -r should --exit test/*.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 925 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 920 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 915 | `npm run lint && npm run mocha:no-functional` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 871 | `mocha` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 868 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 867 | `mocha --reporter spec` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 867 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 865 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 865 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 864 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 862 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [ebradyjobory/finance.js](https://github.com/ebradyjobory/finance.js) | 860 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 857 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 857 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 856 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 854 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 853 | `mocha` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 852 | `mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 851 | `mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 845 | `mocha test` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 844 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 967 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 964 | `mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 962 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 954 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 953 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 952 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 952 | `istanbul cover -- _mocha --reporter spec` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 951 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 939 | `mocha test/index.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 937 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 936 | `mocha` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 936 | `mocha --timeout 5000` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 931 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 927 | `mocha -t 5000` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 926 | `mocha -r should --exit test/*.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 924 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 925 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 924 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 920 | `mocha spec/*.spec.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 920 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 919 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 919 | `mocha test` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 915 | `npm run lint && npm run mocha:no-functional` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 914 | `mocha --harmony tests/**` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 913 | `mocha` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 909 | `mocha ./test/index.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 906 | `npm run build && istanbul test _mocha test/test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 905 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [nimiq-network/core](https://github.com/nimiq-network/core) | 904 | `NODE_ENV=test mocha --exit` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 899 | `mocha --harmony --full-trace --check-leaks` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 898 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 898 | `mocha --timeout 200000` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 897 | `mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 893 | `node_modules/.bin/mocha test/spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 892 | `mocha --reporter list` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 881 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 875 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 875 | `mocha --reporter list` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 874 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 857 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 856 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 854 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 853 | `mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 851 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 845 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 845 | `mocha test` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 844 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 843 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 841 | `mocha` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 837 | `mocha test/mocha.js test/crc/index.js` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 836 | `npm run mocha-test test/integration` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 836 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 836 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 832 | `_mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 832 | `mocha && ember test` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 807 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 801 | `nyc mocha` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 797 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 797 | `mocha tests --timeout 10000` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 796 | `npm run lint && npm run mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 795 | `mocha --recursive -s 15 test/` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [fivdi/onoff](https://github.com/fivdi/onoff) | 793 | `nyc mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [fivdi/onoff](https://github.com/fivdi/onoff) | 793 | `nyc mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 790 | `mocha -u tdd` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 787 | `mocha` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 786 | `npm run lint&&mocha tests/*.js` | 
| [koajs/static](https://github.com/koajs/static) | 786 | `mocha --harmony --reporter spec --exit` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 783 | `mocha` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 780 | `babel-node node_modules/.bin/_mocha -- test` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 778 | `mocha 'test/**/*.tests.js'` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 776 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 774 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 772 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 807 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 805 | `jenkins-mocha ./tests/*.js` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 801 | `nyc mocha` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 800 | `mocha --no-timeouts` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 799 | `xo && mocha -R spec` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 797 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 797 | `mocha tests --timeout 10000` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 796 | `npm run lint && npm run mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 795 | `mocha --recursive -s 15 test/` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [fivdi/onoff](https://github.com/fivdi/onoff) | 793 | `nyc mocha` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 771 | `./bin/selenium-standalone install && mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 770 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 770 | `mocha --ui tdd --require ./test/__setup` | 
| [susam/texme](https://github.com/susam/texme) | 769 | `standard && mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 767 | `mocha --reporter spec build/test/index.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 763 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [electron/apps](https://github.com/electron/apps) | 763 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 757 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 753 | `npm run test-mocha && npm run test-karma` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 783 | `npm run-script jshint && npm run-script mocha` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 780 | `babel-node node_modules/.bin/_mocha -- test` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 780 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 778 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 776 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 775 | `mocha -R spec src/**/*_test.js` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 775 | `mocha ./test/serializer/ --compilers js:@babel/register` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 774 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 772 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 772 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 771 | `./bin/selenium-standalone install && mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 770 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 770 | `mocha --ui tdd --require ./test/__setup` | 
| [susam/texme](https://github.com/susam/texme) | 769 | `standard && mocha` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 767 | `mocha --reporter spec build/test/index.js` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 740 | `mocha` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 739 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 738 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 737 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 737 | `mocha --reporter spec test/` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 733 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [CharlesStover/reactn](https://github.com/CharlesStover/reactn) | 733 | `mocha -r chai/register-expect -r @babel/register -r ts-node/register "tests/**/*.spec.ts?(x)"` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 731 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 730 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 730 | `mocha` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 728 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 726 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 720 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 710 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 707 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 705 | `mocha --reporter spec` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 702 | `./node_modules/.bin/mocha` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 702 | `./node_modules/.bin/mocha` | 
| [apollographql/eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) | 700 | `tav --ci && mocha test/index.js` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 698 | `npm run lint && nyc --reporter=html --reporter=text mocha test/ --recursive -R dot --check-leaks` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 694 | `mocha` | 
| [afc163/fanyi](https://github.com/afc163/fanyi) | 694 | `npm run lint && mocha tests/index.js --timeout 0` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 690 | `mocha --require babel-register src/**/*.spec.js src/*.spec.js` | 
| [klokantech/tileserver-gl](https://github.com/klokantech/tileserver-gl) | 689 | `mocha test/**.js --timeout 10000` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 689 | `npm run lint && mocha test` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 688 | `mocha -R spec` | 
| [godaddy/terminus](https://github.com/godaddy/terminus) | 687 | `mocha index.spec.js lib/**/*.spec.js && npm run test-typings` | 
| [gtanner/qrcode-terminal](https://github.com/gtanner/qrcode-terminal) | 687 | `./node_modules/jshint/bin/jshint lib vendor && node example/basic.js && ./node_modules/mocha/bin/mocha -R nyan` | 
| [fin-hypergrid/core](https://github.com/fin-hypergrid/core) | 686 | `NODE_ENV=test mocha --exit` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 686 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 686 | `mocha --compilers js:babel-register` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 678 | `mocha --require babel-register` | 
| [shelljs/shx](https://github.com/shelljs/shx) | 677 | `nyc --reporter=text --reporter=lcov mocha` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 676 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [stevenvachon/broken-link-checker](https://github.com/stevenvachon/broken-link-checker) | 674 | `mocha test/ --reporter spec --check-leaks --bail` | 
| [IjzerenHein/autolayout.js](https://github.com/IjzerenHein/autolayout.js) | 672 | `mocha` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 671 | `mocha -b -R spec test/*` | 
| [coinbase/gdax-node](https://github.com/coinbase/gdax-node) | 668 | `mocha --full-trace --ui tdd --bail --reporter spec tests/*.js` | 
| [catamphetamine/universal-webpack](https://github.com/catamphetamine/universal-webpack) | 667 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 667 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [joaonuno/tree-model-js](https://github.com/joaonuno/tree-model-js) | 667 | `istanbul cover _mocha` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 667 | `mocha` | 
| [maxkueng/victor](https://github.com/maxkueng/victor) | 667 | `mocha --ui bdd --reporter spec` | 
| [LouisBarranqueiro/reapop](https://github.com/LouisBarranqueiro/reapop) | 666 | `babel-node ./node_modules/karma/bin/karma start ./build/karma.conf.js --reporters mocha` | 
| [substance/data](https://github.com/substance/data) | 665 | `mocha -R spec tests/run.js` | 
| [Ivshti/linvodb3](https://github.com/Ivshti/linvodb3) | 663 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [docpress/docpress](https://github.com/docpress/docpress) | 663 | `nyc mocha` | 
| [mtth/avsc](https://github.com/mtth/avsc) | 681 | `mocha` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 678 | `mocha --require babel-register` | 
| [omnidan/node-emoji](https://github.com/omnidan/node-emoji) | 678 | `./node_modules/.bin/mocha --require should --bail --reporter spec test/*` | 
| [shelljs/shx](https://github.com/shelljs/shx) | 677 | `nyc --reporter=text --reporter=lcov mocha` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 676 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [stevenvachon/broken-link-checker](https://github.com/stevenvachon/broken-link-checker) | 674 | `mocha test/ --reporter spec --check-leaks --bail` | 
| [calmm-js/partial.lenses](https://github.com/calmm-js/partial.lenses) | 672 | `nyc mocha && nyc report -r html mocha` | 
| [IjzerenHein/autolayout.js](https://github.com/IjzerenHein/autolayout.js) | 672 | `mocha` | 
| [theoephraim/node-google-spreadsheet](https://github.com/theoephraim/node-google-spreadsheet) | 671 | `node_modules/.bin/mocha` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 671 | `mocha -b -R spec test/*` | 
| [kwhitley/apicache](https://github.com/kwhitley/apicache) | 669 | `nyc mocha $(find test -name '*.test.js') --recursive` | 
| [coinbase/gdax-node](https://github.com/coinbase/gdax-node) | 668 | `mocha --full-trace --ui tdd --bail --reporter spec tests/*.js` | 
| [catamphetamine/universal-webpack](https://github.com/catamphetamine/universal-webpack) | 667 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [catamphetamine/universal-webpack](https://github.com/catamphetamine/universal-webpack) | 667 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 667 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 667 | `mocha` | 
| [joaonuno/tree-model-js](https://github.com/joaonuno/tree-model-js) | 667 | `istanbul cover _mocha` | 
| [maxkueng/victor](https://github.com/maxkueng/victor) | 667 | `mocha --ui bdd --reporter spec` | 
| [LouisBarranqueiro/reapop](https://github.com/LouisBarranqueiro/reapop) | 666 | `babel-node ./node_modules/karma/bin/karma start ./build/karma.conf.js --reporters mocha` | 
| [substance/data](https://github.com/substance/data) | 665 | `mocha -R spec tests/run.js` | 
| [anandanand84/technicalindicators](https://github.com/anandanand84/technicalindicators) | 664 | `mocha --compilers js:babel-register --require babel-polyfill` | 
| [dtschust/redux-bug-reporter](https://github.com/dtschust/redux-bug-reporter) | 663 | `standard && mocha --compilers js:babel-register --recursive --require test/setup.js` | 
| [Ivshti/linvodb3](https://github.com/Ivshti/linvodb3) | 663 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [docpress/docpress](https://github.com/docpress/docpress) | 663 | `nyc mocha` | 
| [aaronshaf/react-toggle](https://github.com/aaronshaf/react-toggle) | 662 | `nyc mocha --require babel-register --require spec/setup.js spec/**/*.spec.js` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 660 | `mocha --recursive --compilers js:babel-core/register` | 
| [jbrooksuk/node-summary](https://github.com/jbrooksuk/node-summary) | 658 | `mocha --compilers js:babel-core/register --require should --reporter spec` | 
| [chao/RESTClient](https://github.com/chao/RESTClient) | 658 | `mocha` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 658 | `mocha` | 
| [jbrooksuk/node-summary](https://github.com/jbrooksuk/node-summary) | 658 | `mocha --compilers js:babel-core/register --require should --reporter spec` | 
| [chao/RESTClient](https://github.com/chao/RESTClient) | 658 | `mocha` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 658 | `mocha` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 657 | `mocha --reporter spec` | 
| [pburtchaell/react-notification](https://github.com/pburtchaell/react-notification) | 656 | `node_modules/.bin/mocha --compilers js:babel-core/register --reporter spec --recursive --timeout 5000 test/setup.js test/**/*.js` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 656 | `mocha` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 654 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [spirit/spirit](https://github.com/spirit/spirit) | 653 | `BABEL_ENV=modules NODE_ENV=test mocha -r babel-register -r babel-polyfill -r ./test/bootstrap.js --timeout 5000` | 
| [rkusa/koa-passport](https://github.com/rkusa/koa-passport) | 653 | `mocha` | 
| [azmenak/react-stripe-checkout](https://github.com/azmenak/react-stripe-checkout) | 652 | `mocha --require babel-register --require .test-setup.js -R spec ./spec.js` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 652 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [ideal-postcodes/postcodes.io](https://github.com/ideal-postcodes/postcodes.io) | 650 | `NODE_ENV=test npm run test:create && npm run nyc_mocha && NODE_ENV=test npm run test:clear && npm run lint` | 
| [danielstjules/buddy.js](https://github.com/danielstjules/buddy.js) | 650 | `mocha -R spec spec/unit spec/integration` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 650 | `./node_modules/.bin/mocha --bail` | 
| [gauntface/simple-push-demo](https://github.com/gauntface/simple-push-demo) | 649 | `gulp && npm run lint && node ./test/helpers/download-browsers.js && mocha` | 
| [postcss/gulp-postcss](https://github.com/postcss/gulp-postcss) | 649 | `nyc mocha test.js` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 648 | `./node_modules/.bin/mocha test/integration` | 
| [vault-development/react-native-svg-uri](https://github.com/vault-development/react-native-svg-uri) | 648 | `./node_modules/mocha/bin/mocha --compilers js:babel-core/register` | 
| [w0rm/gulp-svgstore](https://github.com/w0rm/gulp-svgstore) | 618 | `gulp build && mocha test.js` | 
| [gameclosure/devkit](https://github.com/gameclosure/devkit) | 617 | `mocha --reporter spec --recursive -C ./tests` | 
| [mattyork/fuzzy](https://github.com/mattyork/fuzzy) | 616 | `./node_modules/.bin/mocha` | 
| [macbre/analyze-css](https://github.com/macbre/analyze-css) | 616 | `mocha -R spec` | 
| [adamjmcgrath/react-native-simple-auth](https://github.com/adamjmcgrath/react-native-simple-auth) | 615 | `mocha lib/**/*.test.js --require babel-register` | 
| [opencomponents/oc](https://github.com/opencomponents/oc) | 614 | `npm run build && node tasks/mochaTest.js` | 
| [Charca/bootbot](https://github.com/Charca/bootbot) | 614 | `mocha --recursive test/*` | 
| [desmondmorris/node-tesseract](https://github.com/desmondmorris/node-tesseract) | 611 | `mocha` | 
| [koala-interactive/frenchkiss.js](https://github.com/koala-interactive/frenchkiss.js) | 610 | `mocha --require @babel/register --recursive test` | 
| [filamentgroup/glyphhanger](https://github.com/filamentgroup/glyphhanger) | 609 | `mocha` | 
| [mathiasbynens/emoji-regex](https://github.com/mathiasbynens/emoji-regex) | 608 | `mocha` | 
| [node-opcua/node-opcua](https://github.com/node-opcua/node-opcua) | 607 | `cd packages && node --expose-gc --max-old-space-size=512 run_all_mocha_tests.js` | 
| [shinnn/gulp-gh-pages](https://github.com/shinnn/gulp-gh-pages) | 606 | `nyc mocha test.js --timeout 50000 --full-trace` | 
| [cgross/generator-cg-angular](https://github.com/cgross/generator-cg-angular) | 606 | `mocha` | 
| [victorb/autochecker](https://github.com/victorb/autochecker) | 604 | `mocha` | 
| [adamgruber/mochawesome](https://github.com/adamgruber/mochawesome) | 632 | `npm run lint && cross-env NODE_ENV=test nyc mocha` | 
| [blueberryapps/react-bluekit](https://github.com/blueberryapps/react-bluekit) | 631 | `mocha --compilers js:babel/register --recursive` | 
| [danielbayerlein/dashboard](https://github.com/danielbayerlein/dashboard) | 630 | `export TESTING=true; mocha --reporter list` | 
| [tj/node-blocked](https://github.com/tj/node-blocked) | 630 | `./node_modules/mocha/bin/mocha` | 
| [hemerajs/hemera](https://github.com/hemerajs/hemera) | 630 | `nyc mocha -b -r "./test/hemera/bootstrap" -t 5000 --exit "./test/**/*.spec.js" && yarn run typescript` | 
| [susielu/d3-legend](https://github.com/susielu/d3-legend) | 629 | `mocha` | 
| [M6Web/websocket-bench](https://github.com/M6Web/websocket-bench) | 628 | `gulp mocha` | 
| [duaraghav8/Ethlint](https://github.com/duaraghav8/Ethlint) | 626 | `nyc --reporter=text --reporter=html mocha --require should --reporter spec --recursive` | 
| [wclimb/Koa2-blog](https://github.com/wclimb/Koa2-blog) | 625 | `./node_modules/mocha/bin/mocha --harmony test` | 
| [mysamai/mysam](https://github.com/mysamai/mysam) | 625 | `npm run lint && npm run mocha` | 
| [amasad/debug_utils](https://github.com/amasad/debug_utils) | 624 | `mocha ./test --bail` | 
| [robrich/gulp-if](https://github.com/robrich/gulp-if) | 623 | `mocha && jshint .` | 
| [JoshKaufman/ursa](https://github.com/JoshKaufman/ursa) | 583 | `mocha --recursive --reporter spec` | 
| [queckezz/koa-views](https://github.com/queckezz/koa-views) | 580 | `mocha --reporter dot --bail --exit` | 
| [felixge/node-dirty](https://github.com/felixge/node-dirty) | 580 | `mocha test/test-*.js -R list` | 
| [nicksp/redux-webpack-es6-boilerplate](https://github.com/nicksp/redux-webpack-es6-boilerplate) | 578 | `mocha --compilers js:babel-core/register,css:./test/unit/cssNullCompiler.js --require ./test/unit/testHelper.js --recursive ./test/unit` | 
| [jmreidy/grunt-browserify](https://github.com/jmreidy/grunt-browserify) | 578 | `mocha -R spec --timeout 5000` | 
| [Spreadsheets/WickedGrid](https://github.com/Spreadsheets/WickedGrid) | 578 | `./node_modules/.bin/mocha --reporter spec` | 
| [mozilla/webextension-polyfill](https://github.com/mozilla/webextension-polyfill) | 577 | `mocha` | 
| [sindresorhus/jshint-stylish](https://github.com/sindresorhus/jshint-stylish) | 575 | `xo && mocha` | 
| [hunterloftis/throng](https://github.com/hunterloftis/throng) | 575 | `mocha` | 
| [website-scraper/node-website-scraper](https://github.com/website-scraper/node-website-scraper) | 573 | `nyc --reporter=html --reporter=text mocha --recursive --timeout 7000 ./test/unit/ ./test/functional && npm run eslint` | 
| [GoogleChrome/proxy-polyfill](https://github.com/GoogleChrome/proxy-polyfill) | 573 | `mocha` | 
| [talpor/django-dashing](https://github.com/talpor/django-dashing) | 573 | `mocha -t 10000` | 
| [rofrischmann/react-look](https://github.com/rofrischmann/react-look) | 600 | `npm run lint && mocha --recursive --compilers js:babel/register` | 
| [newsdev/ai2html](https://github.com/newsdev/ai2html) | 600 | `mocha --check-leaks` | 
| [justinfagnani/mixwith.js](https://github.com/justinfagnani/mixwith.js) | 599 | `mocha build/test` | 
| [ivolo/disposable-email-domains](https://github.com/ivolo/disposable-email-domains) | 599 | `node ./node_modules/mocha/bin/_mocha` | 
| [putaoshu/jdf](https://github.com/putaoshu/jdf) | 598 | `mocha test/index.js` | 
| [csstree/csstree](https://github.com/csstree/csstree) | 598 | `mocha --reporter progress` | 
| [matthewmueller/graph.ql](https://github.com/matthewmueller/graph.ql) | 597 | `./node_modules/.bin/mocha` | 
| [SamyPesse/gitkit-js](https://github.com/SamyPesse/gitkit-js) | 596 | `./node_modules/.bin/mocha ./testing/setup.js ./lib/**/*/__tests__/*.js --bail --reporter=list` | 
| [ck86/main-bower-files](https://github.com/ck86/main-bower-files) | 596 | `mocha` | 
| [jkphl/gulp-svg-sprite](https://github.com/jkphl/gulp-svg-sprite) | 596 | `gulp && istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [mhart/kinesalite](https://github.com/mhart/kinesalite) | 595 | `mocha --require should --reporter spec -t $([ $REMOTE ] && echo 30s || echo 4s)` | 
| [jimpick/lambda-comments](https://github.com/jimpick/lambda-comments) | 594 | `mocha --compilers js:./babel-register` | 
| [bitovi/documentjs](https://github.com/bitovi/documentjs) | 594 | `mocha test/test.js --reporter spec` | 
| [mbasso/react-decoration](https://github.com/mbasso/react-decoration) | 593 | `cross-env BABEL_ENV=commonjs nyc --require babel-register --require ./test/setup.js mocha --recursive` | 
| [dleitee/valid.js](https://github.com/dleitee/valid.js) | 593 | `mocha --compilers js:babel-register` | 
| [pvorb/node-md5](https://github.com/pvorb/node-md5) | 592 | `mocha` | 
| [teropa/redux-voting-server](https://github.com/teropa/redux-voting-server) | 592 | `mocha --compilers js:babel-core/register  --require ./test/test_helper.js  --recursive` | 