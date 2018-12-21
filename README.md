# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:43 12/21/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44659 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 41845 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 41582 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30712 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 25044 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 24606 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21092 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 19871 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18154 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17751 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17588 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 16734 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 14875 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14707 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14616 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13783 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13461 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12935 | `mocha 'test/**/*.spec.js'` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12692 | `mocha --reporter spec test/*-test.js` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 12630 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12612 | `istanbul cover _mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12337 | `mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12178 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12126 | `nyc grunt mocha-and-karma` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12116 | `mocha --require @babel/register --reporter dot` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11282 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 10953 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 10795 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10726 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 10499 | `mocha` | 
| [tj/co](https://github.com/tj/co) | 10354 | `mocha --harmony` | 
| [websockets/ws](https://github.com/websockets/ws) | 10234 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9638 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9610 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9496 | `mocha tests/*.js` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9391 | `mocha -b -r esm` | 
| [amark/gun](https://github.com/amark/gun) | 9238 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9234 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9229 | `grunt mocha` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8802 | `mocha test/src` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8651 | `mocha --opts mocha.opts` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8643 | `mocha test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8538 | `mocha --check-leaks -R dot` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8471 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8418 | `grunt clean:test && mocha --exit` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8405 | `mocha --compilers js:babel-register test/test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8364 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8205 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8008 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7931 | `./node_modules/.bin/mocha test` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 7848 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 7840 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 7751 | `eslint lib/**/*.js test/**/*.js index.js && nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 7741 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7735 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [dthree/cash](https://github.com/dthree/cash) | 7583 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7558 | `npm run build && istanbul cover _mocha` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7457 | `mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7423 | `mocha` | 
| [almende/vis](https://github.com/almende/vis) | 7410 | `mocha --compilers js:babel-core/register` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7352 | `mocha; jshint *.js lib` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7318 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7251 | `mocha --exit --require @babel/register` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7077 | `mocha $HARMONY_OPTS` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7045 | `mocha` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6893 | `npm run jshint && mocha test/` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6703 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6639 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6495 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 6417 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6351 | `npm run test:mocha:src` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6219 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6182 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6136 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6100 | `mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6071 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6063 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6050 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6040 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5936 | `mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5846 | `mocha && eslint lib/**` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 5845 | `standard && mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5651 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5636 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5565 | `npm run lint && mocha tests/*/*/*.js` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5556 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5434 | `mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5430 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5428 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5412 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5292 | `mocha -r esm` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5279 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5230 | `mocha test` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5202 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5136 | `mocha --color` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5126 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5094 | `gulp lint && mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 5024 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4940 | `mocha --recursive` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4908 | `gulp build; mocha;` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4903 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4854 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4831 | `mocha -R spec 'tests/app'` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4831 | `./node_modules/.bin/mocha` | 
| [santinic/how2](https://github.com/santinic/how2) | 4823 | `mocha test` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4817 | `nyc mocha --exit` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4796 | `mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4768 | `npm run lint && npm run mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 4739 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4739 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3280 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3274 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3262 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3243 | `mocha test/index.js && npm run demo` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3227 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3215 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3180 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3174 | `./node_modules/.bin/mocha test/test.*.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3169 | `mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3158 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3134 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3068 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3051 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3044 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2997 | `npm run mocha && npm run lint` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2986 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2956 | `node_modules/.bin/mocha --reporter spec` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2953 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2944 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2942 | `mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2926 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2926 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2925 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2921 | `mocha --require @babel/register --recursive spec` | 
| [521dimensions/amplitudejs](https://github.com/521dimensions/amplitudejs) | 2914 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2904 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2877 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2870 | `mocha -R spec spec spec/reporters` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2851 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2837 | `istanbul cover _mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2818 | `npm run build && cd test && mocha . --reporter dot` | 
| [css/csso](https://github.com/css/csso) | 2798 | `mocha --reporter dot` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2781 | `mocha --require should --reporter spec` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2779 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2763 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2751 | `xo && mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2743 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2721 | `mocha "./test/**/*-test.js"` | 
| [retejs/rete](https://github.com/retejs/rete) | 2718 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2714 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2707 | `mocha` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2693 | `nyc mocha --timeout=10000` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2689 | `mocha --recursive --watch` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2681 | `mocha --timeout 100000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2669 | `nyc mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2562 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2546 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2532 | `export TESTING=true; mocha --reporter list` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2528 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2521 | `mocha test/src/**/*.unit.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2506 | `mocha --reporter=spec test/*-test.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2498 | `nyc --reporter=html --reporter=text mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2495 | `mocha test --exit && npm run lint` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2489 | `mocha` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2464 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2445 | `mocha --no-colors --reporter spec` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2434 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2425 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [Qix-/color](https://github.com/Qix-/color) | 2399 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2506 | `mocha --reporter=spec test/*-test.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2498 | `nyc --reporter=html --reporter=text mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2495 | `mocha test --exit && npm run lint` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2489 | `mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2470 | `mocha && eslint .` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2464 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2445 | `mocha --no-colors --reporter spec` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2445 | `mocha test/index.js --reporter dot` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2434 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2425 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2421 | `mocha -R spec` | 
| [Qix-/color](https://github.com/Qix-/color) | 2399 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2175 | `cross-env BABEL_ENV=test mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2162 | `mocha test/runner.js --reporter spec` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2142 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2139 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2128 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [share/sharedb](https://github.com/share/sharedb) | 2101 | `./node_modules/.bin/mocha && npm run jshint` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2093 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2092 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2061 | `mocha --compilers js:babel-register` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2036 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2128 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [share/sharedb](https://github.com/share/sharedb) | 2101 | `./node_modules/.bin/mocha && npm run jshint` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2093 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2092 | `mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2061 | `mocha --compilers js:babel-register` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2049 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2036 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2033 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2016 | `npm run lint && mocha -R dot && npm run cover` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1960 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1955 | `mocha --require ./test/common --growl test/expect.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1955 | `mocha --bail --reporter spec --check-leaks test/` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1925 | `mocha test/**/*.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1925 | `mocha test` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1922 | `bmocha --reporter spec test/*.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1914 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1881 | `mocha tests.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1881 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1878 | `mocha test` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1867 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1698 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1696 | `mocha` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1695 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1688 | `npm run jshint && mocha --recursive` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1674 | `mocha && size-limit` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1669 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1666 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1659 | `mocha --check-leaks --reporter spec --bail` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1659 | `mocha spec` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1656 | `mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1644 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1637 | `mocha tests/test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1635 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1626 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1894 | `npm run lint && mocha --reporter spec test/*.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1881 | `mocha tests.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1881 | `mocha --reporter spec --grep .` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1878 | `mocha test` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1861 | `mocha test -u bdd -R spec` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1848 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1842 | `mocha compiled_tests/` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1834 | `mocha ./test/basic.js -t 5000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1832 | `npm run lint && npm run mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1820 | `mocha test` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1775 | `npm run lint && npm run mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1766 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1755 | `eslint --cache . && tsc && mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1739 | `nyc mocha --timeout=20000 test.js` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1733 | `./node_modules/.bin/mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1733 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1732 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1732 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1728 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1725 | `mocha test/**/*_test.js --bail` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1723 | `TEST=all mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1723 | `mocha test/*.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1722 | `mocha tests.js` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1721 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1720 | `mocha test --timeout 600000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1717 | `mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1711 | `mocha` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1698 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1696 | `mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1696 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1695 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1688 | `npm run jshint && mocha --recursive` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1674 | `mocha && size-limit` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1672 | `standard "./src/*.js" && mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1669 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1666 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1665 | `xo && mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1661 | `mocha` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 1660 | `mocha test/test-*.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1659 | `mocha --check-leaks --reporter spec --bail` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1659 | `mocha spec` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1656 | `mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1644 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1637 | `mocha tests/test.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1635 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1626 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1615 | `mocha` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1613 | `mocha --reporter spec` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1612 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1604 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1598 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1598 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1596 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1576 | `NODE_ENV=test mocha tests/*.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1573 | `mocha --recursive` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1562 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1560 | `mocha ./test/test*.js --reporter spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1556 | `./node_modules/.bin/mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1547 | `npm run test:lint && npm run test:mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1546 | `mocha test/unit` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1537 | `node_modules/.bin/mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1534 | `mocha -u tdd` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1529 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1516 | `mocha --check-leaks --require @babel/register` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1506 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1505 | `mocha -R spec ./test/unit/**` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1502 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1501 | `mocha test/**/*.spec.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1487 | `mocha --timeout 10000 ./tests/lib.js` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1485 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1483 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1476 | `mocha -R spec` | 
| [noble/bleno](https://github.com/noble/bleno) | 1476 | `mocha -R spec test/*.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1474 | `mocha` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1466 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1463 | `npm run lint && mocha && karma start --single-run` | 
| [samccone/drool](https://github.com/samccone/drool) | 1457 | `mocha test/tests.js --timeout=10000` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1420 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1402 | `istanbul cover _mocha` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1396 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [electron/devtron](https://github.com/electron/devtron) | 1394 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1391 | `npm run lint && nyc mocha test test/plugins && nyc report --reporter=lcov` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1388 | `mocha --recursive test/bin` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1383 | `./node_modules/mocha/bin/mocha` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1383 | `mocha --recursive test` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1383 | `mocha --recursive` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1372 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1372 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1371 | `mocha test --compilers js:babel-core/register` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1371 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1368 | `cross-env NODE_ENV=test nyc mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1367 | `./node_modules/.bin/mocha test` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1363 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1360 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1358 | `NODE_PATH=. mocha **/*.spec.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1345 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1343 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1342 | `mocha --check-leaks --reporter spec --bail test/` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1341 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1340 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1339 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1285 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1285 | `npm run lint && npm run mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1278 | `mocha tests/` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1276 | `istanbul test _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1275 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1261 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1260 | `mocha tests` | 
| [variety/variety](https://github.com/variety/variety) | 1255 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1248 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1244 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1244 | `mocha --timeout 20000` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1239 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1234 | `mocha --reporter spec` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1160 | `mocha $(find test -name '*.test.js') --exit` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1159 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1157 | `mocha --reporter spec --bail --check-leaks test/` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1149 | `istanbul cover _mocha test/*.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1149 | `npm-run-all test:jest test:server:mocha` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1147 | `mocha` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1147 | `mocha --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1135 | `mocha` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1124 | `mocha test/*` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1122 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1116 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [electron/spectron](https://github.com/electron/spectron) | 1113 | `mocha && standard` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1112 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1110 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1109 | `standard && mocha -b` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 1306 | `npm run mocha:istanbul` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1296 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1296 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1296 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1289 | `mocha src/test.js` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1287 | `mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1285 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1285 | `npm run lint && npm run mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1283 | `npm run lint && mocha --require @babel/register` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1282 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1278 | `mocha tests/` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1276 | `istanbul test _mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1275 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1272 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1137 | `webpack && mocha test/unit` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1125 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1124 | `mocha test/*` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1122 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1116 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [electron/spectron](https://github.com/electron/spectron) | 1113 | `mocha && standard` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1112 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1111 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1110 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1109 | `standard && mocha -b` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1102 | `mocha --reporter spec test --recursive` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1100 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1095 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1095 | `node_modules/.bin/mocha && npm run lint` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1090 | `mocha --recursive --bail --reporter spec test` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1090 | `mocha --recursive --bail --reporter spec test` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1086 | `npm run convertto:es5 && npm run mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1085 | `eslint src test && mocha --compilers babel-register` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1084 | `mocha --compilers js:babel-register` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1082 | `mocha` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1081 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1080 | `mocha test/tests.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 1060 | `mocha test` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1018 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1007 | `mocha --check-leaks -R dot` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1003 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1002 | `mocha -R list` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 989 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 987 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 984 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 984 | `npm run lint && mocha -R spec` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 981 | `mocha --reporter spec` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 980 | `mocha --compilers js:babel-register test/*.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 976 | `mocha` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 970 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 969 | `mocha --recursive ./test/*_spec.js` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 965 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 989 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 987 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 986 | `mocha test/*.test.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 984 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 984 | `npm run lint && mocha -R spec` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 981 | `mocha --reporter spec` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 980 | `mocha --compilers js:babel-register test/*.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 976 | `mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 975 | `npm run rollup-cjs && mocha test/test.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 975 | `mocha "client.test" --compilers js:babel-register` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 972 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 970 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 969 | `mocha --recursive ./test/*_spec.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 967 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 965 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 989 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 987 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 986 | `mocha test/*.test.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 984 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 984 | `npm run lint && mocha -R spec` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 981 | `mocha --reporter spec` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 980 | `mocha --compilers js:babel-register test/*.js` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 978 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 976 | `mocha` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 975 | `npm run rollup-cjs && mocha test/test.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 975 | `mocha "client.test" --compilers js:babel-register` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 975 | `mocha spec/*.js` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 972 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 971 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 970 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 969 | `mocha --recursive ./test/*_spec.js` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 956 | `npm run lint && npm run mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 955 | `./node_modules/.bin/mocha --reporter spec` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 953 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 953 | `./node_modules/.bin/mocha -R spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 953 | `mocha` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 951 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 951 | `mocha tests` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 950 | `mocha -t 600000` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 941 | `mocha --timeout 5000` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 939 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 935 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 935 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 934 | `nyc mocha specs` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 933 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 941 | `mocha --timeout 5000` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 939 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 935 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 935 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 934 | `nyc mocha specs` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 933 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 933 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 932 | `mocha test --compilers js:babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 926 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 921 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 921 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 920 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 921 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 921 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 920 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 917 | `istanbul cover -- _mocha --reporter spec` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 915 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 913 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 912 | `mocha -t 5000` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 911 | `mocha spec/*.spec.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 910 | `standard && standard ./bin/* && mocha` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 909 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 901 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 900 | `npm run lint && npm run mocha:no-functional` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 897 | `mocha test` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 897 | `./node_modules/.bin/mocha test/**/*` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 896 | `mocha test/index.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 893 | `node_modules/.bin/mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 887 | `mocha --timeout 200000` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 882 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 882 | `./node_modules/.bin/mocha --globals angular,require` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 878 | `node_modules/.bin/mocha test/spec` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 878 | `mocha` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 857 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 855 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 854 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 852 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 852 | `mocha --check-leaks -t 20000` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 848 | `mocha --reporter spec --bail --check-leaks test/` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 847 | `npm run lint && mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 842 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 841 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 841 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 840 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 840 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [SavjeeTutorials/SavjeeCoin](https://github.com/SavjeeTutorials/SavjeeCoin) | 652 | `mocha tests/*.test.js` | 
| [mtth/avsc](https://github.com/mtth/avsc) | 652 | `mocha` | 
| [pburtchaell/react-notification](https://github.com/pburtchaell/react-notification) | 651 | `node_modules/.bin/mocha --compilers js:babel-core/register --reporter spec --recursive --timeout 5000 test/setup.js test/**/*.js` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 651 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [chao/RESTClient](https://github.com/chao/RESTClient) | 650 | `mocha` | 
| [jbrooksuk/node-summary](https://github.com/jbrooksuk/node-summary) | 649 | `mocha --compilers js:babel-core/register --require should --reporter spec` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 648 | `./node_modules/.bin/mocha --bail` | 
| [dtschust/redux-bug-reporter](https://github.com/dtschust/redux-bug-reporter) | 647 | `standard && mocha --compilers js:babel-register --recursive --require test/setup.js` | 
| [maxkueng/victor](https://github.com/maxkueng/victor) | 647 | `mocha --ui bdd --reporter spec` | 
| [IjzerenHein/autolayout.js](https://github.com/IjzerenHein/autolayout.js) | 646 | `mocha` | 
| [esnext/esnext](https://github.com/esnext/esnext) | 640 | `mocha` | 
| [stevenvachon/broken-link-checker](https://github.com/stevenvachon/broken-link-checker) | 636 | `mocha test/ --reporter spec --check-leaks --bail` | 
| [danawoodman/react-fontawesome](https://github.com/danawoodman/react-fontawesome) | 633 | `mocha` | 
| [docpress/docpress](https://github.com/docpress/docpress) | 632 | `nyc mocha` | 
| [pocketjoso/specificity-graph](https://github.com/pocketjoso/specificity-graph) | 631 | `node_modules/.bin/mocha test` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 630 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [electron/apps](https://github.com/electron/apps) | 628 | `mocha --reporter min test/human-data.js test/colors-spec.js && standard --fix` | 
| [postcss/gulp-postcss](https://github.com/postcss/gulp-postcss) | 628 | `nyc mocha test.js` | 
| [hparra/gulp-rename](https://github.com/hparra/gulp-rename) | 625 | `mocha` | 
| [edankwan/penis.js](https://github.com/edankwan/penis.js) | 625 | `mocha --ui bdd --reporter spec test/` | 
| [manavsehgal/reactspeedcoding](https://github.com/manavsehgal/reactspeedcoding) | 625 | `NODE_ENV=test npm run elint && npm run slint && npm run test:mocha` | 
| [amasad/debug_utils](https://github.com/amasad/debug_utils) | 624 | `mocha ./test --bail` | 
| [mysamai/mysam](https://github.com/mysamai/mysam) | 623 | `npm run lint && npm run mocha` | 
| [susielu/d3-legend](https://github.com/susielu/d3-legend) | 621 | `mocha` | 
| [shelljs/shx](https://github.com/shelljs/shx) | 621 | `nyc --reporter=text --reporter=lcov mocha` | 
| [gauntface/simple-push-demo](https://github.com/gauntface/simple-push-demo) | 620 | `gulp && npm run lint && node ./test/helpers/download-browsers.js && mocha` | 
| [aliyun-UED/aliyun-sdk-js](https://github.com/aliyun-UED/aliyun-sdk-js) | 620 | `mocha test` | 
| [robwierzbowski/generator-jekyllrb](https://github.com/robwierzbowski/generator-jekyllrb) | 619 | `mocha` | 
| [gameclosure/devkit](https://github.com/gameclosure/devkit) | 619 | `mocha --reporter spec --recursive -C ./tests` | 
| [Munter/subfont](https://github.com/Munter/subfont) | 619 | `npm run lint && mocha` | 
| [tj/node-blocked](https://github.com/tj/node-blocked) | 619 | `./node_modules/mocha/bin/mocha` | 
| [blueberryapps/react-bluekit](https://github.com/blueberryapps/react-bluekit) | 619 | `mocha --compilers js:babel/register --recursive` | 
| [azmenak/react-stripe-checkout](https://github.com/azmenak/react-stripe-checkout) | 616 | `mocha --require babel-register --require .test-setup.js -R spec ./spec.js` | 
| [robrich/gulp-if](https://github.com/robrich/gulp-if) | 615 | `mocha && jshint .` | 
| [Kagami/ffmpeg.js](https://github.com/Kagami/ffmpeg.js) | 614 | `mocha test/test.js` | 
| [w0rm/gulp-svgstore](https://github.com/w0rm/gulp-svgstore) | 614 | `gulp build && mocha test.js` | 
| [anandanand84/technicalindicators](https://github.com/anandanand84/technicalindicators) | 612 | `mocha --compilers js:babel-register --require babel-polyfill` | 
| [jshttp/http-errors](https://github.com/jshttp/http-errors) | 611 | `mocha --reporter spec --bail` | 
| [fent/node-ytdl](https://github.com/fent/node-ytdl) | 610 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [jfromaniello/passport.socketio](https://github.com/jfromaniello/passport.socketio) | 609 | `mocha` | 
| [cgross/generator-cg-angular](https://github.com/cgross/generator-cg-angular) | 608 | `mocha` | 
| [atom/github](https://github.com/atom/github) | 607 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [duaraghav8/Ethlint](https://github.com/duaraghav8/Ethlint) | 606 | `nyc --reporter=text --reporter=html mocha --require should --reporter spec --recursive` | 
| [klokantech/tileserver-gl](https://github.com/klokantech/tileserver-gl) | 605 | `mocha test/**.js --timeout 10000` | 
| [webdriverio-boneyard/webdrivercss](https://github.com/webdriverio-boneyard/webdrivercss) | 603 | `./node_modules/.bin/mocha` | 
| [desmondmorris/node-tesseract](https://github.com/desmondmorris/node-tesseract) | 603 | `mocha` | 
| [hemerajs/hemera](https://github.com/hemerajs/hemera) | 603 | `nyc mocha -b -r "./test/hemera/bootstrap" -t 5000 --exit "./test/**/*.spec.js" "./packages/hemera-zipkin/test/**/*.js" && npm run typescript` | 
| [desmondmorris/node-tesseract](https://github.com/desmondmorris/node-tesseract) | 603 | `mocha` | 
| [adamjmcgrath/react-native-simple-auth](https://github.com/adamjmcgrath/react-native-simple-auth) | 603 | `mocha lib/**/*.test.js --require babel-register` | 
| [vault-development/react-native-svg-uri](https://github.com/vault-development/react-native-svg-uri) | 600 | `./node_modules/mocha/bin/mocha --compilers js:babel-core/register` | 
| [adamgruber/mochawesome](https://github.com/adamgruber/mochawesome) | 600 | `npm run lint && cross-env NODE_ENV=test nyc mocha` | 
| [rofrischmann/react-look](https://github.com/rofrischmann/react-look) | 599 | `npm run lint && mocha --recursive --compilers js:babel/register` | 
| [JustClear/blurify](https://github.com/JustClear/blurify) | 599 | `mocha test/index.js` | 
| [matthewmueller/graph.ql](https://github.com/matthewmueller/graph.ql) | 599 | `./node_modules/.bin/mocha` | 
| [ck86/main-bower-files](https://github.com/ck86/main-bower-files) | 598 | `mocha` | 
| [mattyork/fuzzy](https://github.com/mattyork/fuzzy) | 597 | `./node_modules/.bin/mocha` | 
| [putaoshu/jdf](https://github.com/putaoshu/jdf) | 596 | `mocha test/index.js` | 
| [times/cardkit](https://github.com/times/cardkit) | 596 | `./node_modules/.bin/istanbul cover --dir test/coverage ./node_modules/.bin/_mocha -- --compilers js:babel-core/register --require ignore-styles` | 
| [SamyPesse/gitkit-js](https://github.com/SamyPesse/gitkit-js) | 592 | `./node_modules/.bin/mocha ./testing/setup.js ./lib/**/*/__tests__/*.js --bail --reporter=list` | 
| [teropa/redux-voting-server](https://github.com/teropa/redux-voting-server) | 592 | `mocha --compilers js:babel-core/register  --require ./test/test_helper.js  --recursive` | 
| [bitovi/documentjs](https://github.com/bitovi/documentjs) | 591 | `mocha test/test.js --reporter spec` | 
| [jkphl/gulp-svg-sprite](https://github.com/jkphl/gulp-svg-sprite) | 588 | `gulp && istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [gridcontrol/gridcontrol](https://github.com/gridcontrol/gridcontrol) | 587 | `NODE_ENV='test' DEBUG='gc:*' ./node_modules/.bin/mocha test/*.mocha.js -b` | 
| [jimpick/lambda-comments](https://github.com/jimpick/lambda-comments) | 587 | `mocha --compilers js:./babel-register` | 
| [jeremyckahn/rekapi](https://github.com/jeremyckahn/rekapi) | 587 | `mocha -r jsdom-global/register ./node_modules/babel-core/register.js test/index.js` | 
| [mbasso/react-decoration](https://github.com/mbasso/react-decoration) | 586 | `cross-env BABEL_ENV=commonjs nyc --require babel-register --require ./test/setup.js mocha --recursive` | 
| [koajs/session](https://github.com/koajs/session) | 584 | `npm run lint && NODE_ENV=test mocha --exit --require should --reporter spec test/*.test.js` | 
| [mikaelbr/gulp-notify](https://github.com/mikaelbr/gulp-notify) | 582 | `mocha -R spec` | 
| [puleos/object-hash](https://github.com/puleos/object-hash) | 581 | `node ./node_modules/.bin/mocha test` | 
| [newsdev/ai2html](https://github.com/newsdev/ai2html) | 580 | `mocha --check-leaks` | 
| [omnidan/node-emoji](https://github.com/omnidan/node-emoji) | 579 | `./node_modules/.bin/mocha --require should --bail --reporter spec test/*` | 
| [zpratt/react-tdd-guide](https://github.com/zpratt/react-tdd-guide) | 578 | `npm run lint && mocha */test` | 
| [ziyasal/scientist.js](https://github.com/ziyasal/scientist.js) | 573 | `node ./node_modules/babel-cli/bin/babel-node.js ./node_modules/mocha/bin/_mocha --timeout 20000 tests/**/*.spec.js` | 
| [scrollback/scrollback](https://github.com/scrollback/scrollback) | 572 | `node_modules/.bin/mocha test/test.js` | 
| [justinfagnani/mixwith.js](https://github.com/justinfagnani/mixwith.js) | 571 | `mocha build/test` | 
| [opencomponents/oc](https://github.com/opencomponents/oc) | 571 | `npm run build && node tasks/mochaTest.js` | 
| [JoshKaufman/ursa](https://github.com/JoshKaufman/ursa) | 571 | `mocha --recursive --reporter spec` | 
| [mhart/kinesalite](https://github.com/mhart/kinesalite) | 570 | `mocha --require should --reporter spec -t $([ $REMOTE ] && echo 30s || echo 4s)` | 
| [avgjs/avg-core](https://github.com/avgjs/avg-core) | 567 | `mocha --compilers js:babel-core/register` | 
| [javivelasco/react-css-themr](https://github.com/javivelasco/react-css-themr) | 567 | `mocha --compilers js:babel-core/register --recursive --reporter spec --require ./test/setup.js` | 
| [afc163/fanyi](https://github.com/afc163/fanyi) | 566 | `npm run lint && mocha tests/index.js --timeout 0` | 
| [azproduction/autopolyfiller](https://github.com/azproduction/autopolyfiller) | 565 | `npm run lint && mocha -R spec` | 
| [matthewmueller/socrates](https://github.com/matthewmueller/socrates) | 565 | `devtool node_modules/mocha/bin/_mocha -qc -- ./test/` | 
| [wclimb/Koa2-blog](https://github.com/wclimb/Koa2-blog) | 562 | `./node_modules/mocha/bin/mocha --harmony test` | 
| [screwdriver-cd/screwdriver](https://github.com/screwdriver-cd/screwdriver) | 561 | `jenkins-mocha --recursive --timeout 3000 --exit` | 
| [nicksp/redux-webpack-es6-boilerplate](https://github.com/nicksp/redux-webpack-es6-boilerplate) | 578 | `mocha --compilers js:babel-core/register,css:./test/unit/cssNullCompiler.js --require ./test/unit/testHelper.js --recursive ./test/unit` | 
| [Charca/bootbot](https://github.com/Charca/bootbot) | 578 | `mocha --recursive test/*` | 
| [felixge/node-dirty](https://github.com/felixge/node-dirty) | 577 | `mocha test/test-*.js -R list` | 
| [sindresorhus/jshint-stylish](https://github.com/sindresorhus/jshint-stylish) | 577 | `xo && mocha` | 
| [jmreidy/grunt-browserify](https://github.com/jmreidy/grunt-browserify) | 576 | `mocha -R spec --timeout 5000` | 
| [webpack/memory-fs](https://github.com/webpack/memory-fs) | 576 | `mocha` | 
| [Spreadsheets/WickedGrid](https://github.com/Spreadsheets/WickedGrid) | 575 | `./node_modules/.bin/mocha --reporter spec` | 
| [ziyasal/scientist.js](https://github.com/ziyasal/scientist.js) | 573 | `node ./node_modules/babel-cli/bin/babel-node.js ./node_modules/mocha/bin/_mocha --timeout 20000 tests/**/*.spec.js` | 
| [filamentgroup/glyphhanger](https://github.com/filamentgroup/glyphhanger) | 573 | `mocha` | 
| [scrollback/scrollback](https://github.com/scrollback/scrollback) | 572 | `node_modules/.bin/mocha test/test.js` | 
| [justinfagnani/mixwith.js](https://github.com/justinfagnani/mixwith.js) | 571 | `mocha build/test` | 
| [opencomponents/oc](https://github.com/opencomponents/oc) | 571 | `npm run build && node tasks/mochaTest.js` | 
| [JoshKaufman/ursa](https://github.com/JoshKaufman/ursa) | 571 | `mocha --recursive --reporter spec` | 
| [mhart/kinesalite](https://github.com/mhart/kinesalite) | 570 | `mocha --require should --reporter spec -t $([ $REMOTE ] && echo 30s || echo 4s)` | 
| [afc163/fanyi](https://github.com/afc163/fanyi) | 566 | `npm run lint && mocha tests/index.js --timeout 0` | 
| [azproduction/autopolyfiller](https://github.com/azproduction/autopolyfiller) | 565 | `npm run lint && mocha -R spec` | 
| [matthewmueller/socrates](https://github.com/matthewmueller/socrates) | 565 | `devtool node_modules/mocha/bin/_mocha -qc -- ./test/` | 
| [wclimb/Koa2-blog](https://github.com/wclimb/Koa2-blog) | 562 | `./node_modules/mocha/bin/mocha --harmony test` | 
| [screwdriver-cd/screwdriver](https://github.com/screwdriver-cd/screwdriver) | 561 | `jenkins-mocha --recursive --timeout 3000 --exit` | 
| [node-opcua/node-opcua](https://github.com/node-opcua/node-opcua) | 561 | `cd packages && node --expose-gc --max-old-space-size=512 run_all_mocha_tests.js` | 
| [ivolo/disposable-email-domains](https://github.com/ivolo/disposable-email-domains) | 560 | `node ./node_modules/mocha/bin/_mocha` | 
| [imgly/imgly-sdk-html5](https://github.com/imgly/imgly-sdk-html5) | 559 | `NODE_ENV=test node_modules/.bin/mocha --harmony --require should --require babel/register --reporter spec test/*.test.js test/**/*.test.js` | 
| [moshen/node-googlemaps](https://github.com/moshen/node-googlemaps) | 559 | `./node_modules/.bin/mocha test/unit` | 
| [jsantell/poet](https://github.com/jsantell/poet) | 559 | `./node_modules/.bin/mocha --reporter spec --ui bdd` | 
| [hiproxy/hiproxy](https://github.com/hiproxy/hiproxy) | 559 | `cross-env NPM_TEST=true nyc mocha test/**/*.test.js test/**/**/*.test.js --timeout 10000 && nyc report --reporter=lcov --reporter=html` | 
| [jmar777/suspend](https://github.com/jmar777/suspend) | 558 | `node ./node_modules/mocha/bin/mocha --harmony --reporter list` | 
| [hunterloftis/throng](https://github.com/hunterloftis/throng) | 558 | `mocha` | 
| [LearnBoost/up](https://github.com/LearnBoost/up) | 558 | `./node_modules/mocha/bin/mocha test/*.test.js` | 
| [gulp-community/gulp-less](https://github.com/gulp-community/gulp-less) | 558 | `jshint index.js && node_modules/.bin/mocha` | 
| [gsuitedevs/apps-script-oauth2](https://github.com/gsuitedevs/apps-script-oauth2) | 557 | `mocha` | 
| [jmar777/suspend](https://github.com/jmar777/suspend) | 558 | `node ./node_modules/mocha/bin/mocha --harmony --reporter list` | 
| [hunterloftis/throng](https://github.com/hunterloftis/throng) | 558 | `mocha` | 
| [LearnBoost/up](https://github.com/LearnBoost/up) | 558 | `./node_modules/mocha/bin/mocha test/*.test.js` | 
| [gulp-community/gulp-less](https://github.com/gulp-community/gulp-less) | 558 | `jshint index.js && node_modules/.bin/mocha` | 
| [gsuitedevs/apps-script-oauth2](https://github.com/gsuitedevs/apps-script-oauth2) | 557 | `mocha` | 
| [t1msh/node-oauth20-provider](https://github.com/t1msh/node-oauth20-provider) | 556 | `node_modules/.bin/mocha --reporter spec` | 
| [GianlucaGuarini/icaro](https://github.com/GianlucaGuarini/icaro) | 555 | `npm run lint && mocha test` | 
| [paulogr/dstatuspage](https://github.com/paulogr/dstatuspage) | 554 | `standard && nyc mocha --exit` | 
| [scniro/gulp-clean-css](https://github.com/scniro/gulp-clean-css) | 552 | `./node_modules/.bin/mocha ./index.spec.js` | 
| [tschaub/mock-fs](https://github.com/tschaub/mock-fs) | 551 | `mocha --recursive test` | 
| [GoogleChromeLabs/pwacompat](https://github.com/GoogleChromeLabs/pwacompat) | 550 | `mocha-headless-server suite.html` | 
| [orliesaurus/nodemailer-mailgun-transport](https://github.com/orliesaurus/nodemailer-mailgun-transport) | 550 | `mocha` | 
| [jshttp/basic-auth](https://github.com/jshttp/basic-auth) | 550 | `mocha --check-leaks --reporter spec --bail` | 
| [csstree/csstree](https://github.com/csstree/csstree) | 550 | `mocha --reporter progress` | 
| [tj/node-ratelimiter](https://github.com/tj/node-ratelimiter) | 549 | `mocha --exit` | 
| [mapbox/carto](https://github.com/mapbox/carto) | 533 | `mocha -R spec --timeout 50000 -i -f jslint` | 
| [mixu/electroshot](https://github.com/mixu/electroshot) | 533 | `mocha -R spec --bail ./test/*.test.js` | 
| [krasimir/stent](https://github.com/krasimir/stent) | 532 | `./node_modules/.bin/mocha --require babel-register --require babel-polyfill --require test/setup.js --require jsdom-global/register --reporter spec --slow 100 './src/**/**.spec.{js,jsx}'` | 
| [bithavoc/express-winston](https://github.com/bithavoc/express-winston) | 531 | `node_modules/.bin/mocha --reporter spec` | 
| [sintaxi/dbox](https://github.com/sintaxi/dbox) | 531 | `./node_modules/.bin/mocha -t 120000 test/all.js -R spec` | 
| [ethjs/ethjs](https://github.com/ethjs/ethjs) | 531 | `mocha ./src/tests/**/*.js -R spec --timeout 2000000` | 
| [mallocator/Elasticsearch-Exporter](https://github.com/mallocator/Elasticsearch-Exporter) | 530 | `istanbul cover _mocha -- --recursive` | 
| [pushtell/react-ab-test](https://github.com/pushtell/react-ab-test) | 529 | `./node_modules/karma/bin/karma start test/browser/karma.conf.js; mocha --require babel-core/register --require babel-polyfill test/isomorphic/*.jsx` | 
| [chaijs/chai-http](https://github.com/chaijs/chai-http) | 529 | `istanbul cover --report lcovonly _mocha` | 
| [mathiasbynens/emoji-regex](https://github.com/mathiasbynens/emoji-regex) | 528 | `mocha` | 
| [raineorshine/solgraph](https://github.com/raineorshine/solgraph) | 527 | `mocha --require @babel/register` | 
| [kriasoft/babel-starter-kit](https://github.com/kriasoft/babel-starter-kit) | 527 | `mocha --require @babel/register` | 
| [pushtell/react-ab-test](https://github.com/pushtell/react-ab-test) | 529 | `./node_modules/karma/bin/karma start test/browser/karma.conf.js; mocha --require babel-core/register --require babel-polyfill test/isomorphic/*.jsx` | 
| [chaijs/chai-http](https://github.com/chaijs/chai-http) | 529 | `istanbul cover --report lcovonly _mocha` | 
| [mathiasbynens/emoji-regex](https://github.com/mathiasbynens/emoji-regex) | 528 | `mocha` | 
| [raineorshine/solgraph](https://github.com/raineorshine/solgraph) | 527 | `mocha --require @babel/register` | 
| [kriasoft/babel-starter-kit](https://github.com/kriasoft/babel-starter-kit) | 527 | `mocha --require @babel/register` | 
| [stephen-hardy/xlsx.js](https://github.com/stephen-hardy/xlsx.js) | 524 | `mocha -R spec` | 
| [techlayer/espresso.js](https://github.com/techlayer/espresso.js) | 523 | `mocha` | 
| [OnetapInc/chromy](https://github.com/OnetapInc/chromy) | 523 | `WITH_BABEL=1 mocha dist_test --compilers js:babel-core/register --require babel-polyfill` | 
| [website-scraper/node-website-scraper](https://github.com/website-scraper/node-website-scraper) | 522 | `nyc --reporter=html --reporter=text mocha --recursive --timeout 7000 ./test/unit/ ./test/functional && npm run eslint` | 
| [nemtsov/json-mask](https://github.com/nemtsov/json-mask) | 522 | `npm run lint && mocha` | 