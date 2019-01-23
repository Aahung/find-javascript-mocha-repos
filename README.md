# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:29 01/23/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 44975 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42037 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42007 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30840 | `mocha --async-only` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25578 | `nyc mocha --timeout=10000 --exit` | 
| [caolan/async](https://github.com/caolan/async) | 25162 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25007 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 21348 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20091 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | 18430 | `jshint lib/ test/ && mocha --recursive --reporter dot` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 17980 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 17804 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17226 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15194 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 14905 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14684 | `nyc --reporter=html --reporter=text mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 13925 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13640 | `mocha --globals document test` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13003 | `mocha 'test/**/*.spec.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13001 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12765 | `mocha --reporter spec test/*-test.js` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 12752 | `istanbul cover _mocha` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 12426 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12360 | `mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 12360 | `mocha --require @babel/register --reporter dot` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 12263 | `nyc grunt mocha-and-karma` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 11474 | `mocha test/index.js` | 
| [svg/svgo](https://github.com/svg/svgo) | 11123 | `set NODE_ENV=test && mocha` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 11082 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 10868 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9717 | `mocha tests/*.js` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9693 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9509 | `mocha` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9431 | `mocha -b -r esm` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9377 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9305 | `grunt mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8845 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8688 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8577 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8557 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8447 | `grunt clean:test && mocha --exit` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8257 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8181 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 7825 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7588 | `npm run build && istanbul cover _mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7587 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [almende/vis](https://github.com/almende/vis) | 7515 | `mocha --compilers js:babel-core/register` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7455 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7446 | `mocha --exit --require @babel/register` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7145 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7110 | `mocha $HARMONY_OPTS` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7102 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7010 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6835 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 6836 | `mocha test/test.js` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 6835 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6555 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6392 | `npm run test:mocha:src` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 6267 | `mocha tests/node.js` | 
| [mholt/PapaParse](https://github.com/mholt/PapaParse) | 6259 | `npm run lint && npm run test-node && npm run test-mocha-headless-chrome` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 6209 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 6208 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 6205 | `mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 6112 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 6089 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6072 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5264 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5209 | `mocha src/**/*Tests.js --harmony` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 5166 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5135 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5123 | `gulp lint && mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5012 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4946 | `gulp build; mocha;` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4915 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4886 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4882 | `./node_modules/.bin/mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4864 | `npm run lint && npm run mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4829 | `mocha` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5538 | `mocha` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5476 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 5410 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5406 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5374 | `mocha -r esm` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5360 | `mocha test` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5334 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5264 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5209 | `mocha src/**/*Tests.js --harmony` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 5166 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5135 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5123 | `gulp lint && mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5037 | `mocha --recursive` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5012 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5264 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5209 | `mocha src/**/*Tests.js --harmony` | 
| [GoogleChromeLabs/quicklink](https://github.com/GoogleChromeLabs/quicklink) | 5166 | `yarn run build && mocha test/bootstrap.js --recursive test` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5135 | `mocha --color` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 5123 | `gulp lint && mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 5037 | `mocha --recursive` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 5012 | `nyc --require @babel/register _mocha -- test/tests/index.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4946 | `gulp build; mocha;` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 4923 | `nyc mocha --exit` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4915 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 4904 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4886 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4882 | `./node_modules/.bin/mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 4864 | `npm run lint && npm run mocha` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4857 | `mocha -R spec 'tests/app'` | 
| [santinic/how2](https://github.com/santinic/how2) | 4840 | `mocha test` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4829 | `mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 4807 | `nyc mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3223 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3223 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3213 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3170 | `mocha` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3150 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3148 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 3140 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3088 | `nyc mocha --recursive` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3082 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3051 | `npm run mocha && npm run lint` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3022 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3017 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3015 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2988 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 2985 | `mocha test-node` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2976 | `mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2963 | `mocha --require @babel/register --recursive spec` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2962 | `mocha` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2956 | `mocha -R spec --recursive src/test` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 2927 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [github-tools/github](https://github.com/github-tools/github) | 2904 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 2888 | `mocha -R spec spec spec/reporters` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2886 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2875 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 2869 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2845 | `istanbul cover _mocha` | 
| [css/csso](https://github.com/css/csso) | 2815 | `mocha --reporter dot` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2813 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [conventional-changelog/conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) | 2813 | `nyc mocha --timeout 30000 packages/*/test{,/*}.js` | 
| [retejs/rete](https://github.com/retejs/rete) | 2789 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2787 | `mocha --require should --reporter spec` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2765 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2758 | `xo && mocha` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2756 | `mocha "./test/**/*-test.js"` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2750 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2743 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2710 | `mocha --recursive --watch` | 
| [yeoman/yo](https://github.com/yeoman/yo) | 2709 | `nyc mocha --timeout=10000` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2700 | `nyc mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2686 | `mocha --timeout 100000` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2659 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2534 | `mocha test/src/**/*.unit.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2533 | `export TESTING=true; mocha --reporter list` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2531 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2527 | `nyc --reporter=html --reporter=text mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2517 | `mocha --reporter=spec test/*-test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2511 | `mocha && eslint .` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2505 | `mocha` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2496 | `TEST=all mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2451 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2442 | `mocha -R spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2442 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [Qix-/color](https://github.com/Qix-/color) | 2437 | `mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2423 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2423 | `nyc --require babel-register npm run _mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2404 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2387 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2385 | `npm run build && mocha --require babel-register` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2451 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2442 | `mocha -R spec` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2442 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [Qix-/color](https://github.com/Qix-/color) | 2437 | `mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2423 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2423 | `nyc --require babel-register npm run _mocha` | 
| [noble/noble](https://github.com/noble/noble) | 2404 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2387 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2385 | `npm run build && mocha --require babel-register` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2378 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2371 | `node node_modules/mocha/bin/_mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2219 | `mocha test test/unit/**/*_test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2205 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2202 | `mocha && eslint *.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2185 | `mocha test/runner.js --reporter spec` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2184 | `cross-env BABEL_ENV=test mocha` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2155 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2140 | `mocha --compilers js:babel-register` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2130 | `mocha --compilers js:babel-core/register __tests__` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2098 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2093 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2185 | `mocha test/runner.js --reporter spec` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2180 | `mocha test/**/*.coffee` | 
| [ziishaned/dumper.js](https://github.com/ziishaned/dumper.js) | 2176 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha && ./node_modules/.bin/codecov` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2172 | `mocha --timeout 10000 --exit test/*-test.js test/security/*.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 2162 | `./node_modules/.bin/mocha && npm run jshint` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 2155 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2146 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2137 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2130 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 2128 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2098 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2093 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1823 | `nyc mocha --timeout=20000 test.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1806 | `npm run lint && npm run mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1800 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1798 | `mocha test/setup.js test/spec/*.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1760 | `mocha tests.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1758 | `npm run lint && mocha && npm run typescript` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1743 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1742 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1738 | `./node_modules/.bin/mocha` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1733 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1726 | `mocha test/**/*_test.js --bail` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1726 | `mocha test --timeout 600000` | 
| [kach/nearley](https://github.com/kach/nearley) | 2052 | `mocha test/*.test.js` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2050 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2046 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2038 | `npm run mocha && npm run karma` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 2038 | `npm run lint && mocha -R dot && npm run cover` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 2032 | `mocha test/unit --recursive && mocha test/runner --recursive` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2030 | `mocha tests --require @babel/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2022 | `mocha && npm run lint` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2020 | `mocha --reporter spec --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 2017 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 2011 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2002 | `mocha --require=test/test_helper.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1997 | `mocha test` | 
| [slate/slate](https://github.com/slate/slate) | 1995 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1983 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1825 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1823 | `nyc mocha --timeout=20000 test.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1818 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1813 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1799 | `mocha --timeout 5000` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1798 | `mocha test/setup.js test/spec/*.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1792 | `eslint --cache . && tsc && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1760 | `mocha tests.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1758 | `npm run lint && mocha && npm run typescript` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1751 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1896 | `mocha test -u bdd -R spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1885 | `mocha compiled_tests/` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1879 | `mocha tests.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1879 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1871 | `mocha ./test/basic.js -t 5000` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1859 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1841 | `npm run lint && npm run mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1825 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1823 | `nyc mocha --timeout=20000 test.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1819 | `mocha test` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1818 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1813 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1806 | `npm run lint && npm run mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1800 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1799 | `mocha --timeout 5000` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1798 | `mocha test/setup.js test/spec/*.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1792 | `eslint --cache . && tsc && mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1760 | `mocha tests.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1758 | `npm run lint && mocha && npm run typescript` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1751 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1743 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1742 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1685 | `mocha && size-limit` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1680 | `mocha ./test/test*.js --reporter spec` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1675 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1667 | `xo && mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1662 | `mocha spec` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1651 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1644 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1638 | `mocha tests/test.js` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1626 | `NODE_ENV=test mocha tests/*.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1619 | `mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1612 | `mocha test.js` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1612 | `./node_modules/mocha/bin/mocha -R spec` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1610 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1625 | `mocha --reporter spec` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1622 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1619 | `mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1618 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1612 | `./node_modules/mocha/bin/mocha -R spec` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1610 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1599 | `mocha --recursive` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1590 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1574 | `mocha test/unit` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1572 | `nyc mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1566 | `mocha -R spec ./test/unit/**` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1557 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1553 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1513 | `mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1512 | `npm run lint && npm run mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1507 | `mocha test/**/*.spec.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1507 | `npm run lint && mocha && karma start --single-run` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1504 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1503 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1499 | `mocha --timeout 10000 ./tests/lib.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1496 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1493 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1471 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1465 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1462 | `mocha --reporter dot` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1461 | `cross-env BABEL_ENV=commonjs mocha --require @babel/register --recursive -r ./test/setup.js` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1454 | `mocha test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1454 | `mocha --recursive test` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1453 | `mocha --opts test/opts/mocha.opts` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1440 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1566 | `mocha -R spec ./test/unit/**` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1558 | `./node_modules/.bin/mocha` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1557 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1553 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1549 | `mocha tests/test-*` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1548 | `npm run test:lint && npm run test:mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1542 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1542 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1540 | `node_modules/.bin/mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1540 | `mocha -u tdd` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1537 | `mocha --check-leaks --require @babel/register` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1525 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1523 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1513 | `mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1512 | `npm run lint && npm run mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1507 | `mocha test/**/*.spec.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1507 | `npm run lint && mocha && karma start --single-run` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1504 | `mocha` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1503 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1499 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1497 | `mocha -R spec test/*.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1496 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1493 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1471 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1469 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1465 | `standard && istanbul cover _mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1407 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1407 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1406 | `istanbul cover _mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1402 | `mocha --recursive test/bin` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1395 | `mocha --recursive` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1393 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1387 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1384 | `./node_modules/mocha/bin/mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1373 | `./node_modules/.bin/mocha test` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1371 | `cross-env NODE_ENV=test nyc mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1364 | `webpack && npm run lint && npm run mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1356 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1356 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1408 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1407 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1407 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1407 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1406 | `istanbul cover _mocha` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1402 | `mocha --recursive test/bin` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1395 | `mocha --recursive` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1393 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1387 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1384 | `./node_modules/mocha/bin/mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1379 | `mocha --check-leaks --reporter spec --bail test/` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1373 | `./node_modules/.bin/mocha test` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1371 | `cross-env NODE_ENV=test nyc mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1364 | `webpack && npm run lint && npm run mocha` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1297 | `mocha` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1297 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1294 | `babel-node node_modules/mocha/bin/_mocha -- ./test/entry.js ./test/**/*.spec.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1293 | `mocha --timeout 30000 --recursive ./tests` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1291 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1290 | `mocha --timeout 20000` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1289 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1286 | `mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1266 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1264 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1261 | `mocha tests` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1259 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1258 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1256 | `mocha` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1170 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1169 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1165 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1160 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 1149 | `mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1148 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1140 | `mocha test` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1138 | `mocha --reporter spec test --recursive` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1129 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1128 | `mocha test/*` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 1127 | `npm run convertto:es5 && npm run mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 1126 | `mocha && standard` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 1120 | `mocha --require babel-register --colors ./test/*.spec.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 1119 | `standard && mocha -b` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1116 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1114 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1114 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1105 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1104 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1099 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1099 | `mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1098 | `node_modules/.bin/mocha && npm run lint` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1097 | `mocha --recursive --bail --reporter spec test` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 1097 | `eslint src test && mocha --compilers babel-register` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1096 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1090 | `mocha --compilers js:babel-register` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1089 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 1083 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1083 | `mocha test/tests.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [tomas/needle](https://github.com/tomas/needle) | 1066 | `mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1064 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1062 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1053 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1051 | `npm run lint && npm run mocha` | 
| [ElemeFE/page-skeleton-webpack-plugin](https://github.com/ElemeFE/page-skeleton-webpack-plugin) | 1051 | `npm run lint && npm run mocha` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1049 | `mocha $(find test -name '*.test.js')` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1049 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1046 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1030 | `mocha --recursive test/unit/` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1029 | `mocha --reporter spec --timeout 3000` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1024 | `mocha test/*.test.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1022 | `mocha --reporter spec --bail --check-leaks test/` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1022 | `mocha --reporter spec --bail --check-leaks test/` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 1019 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1018 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [tediousjs/tedious](https://github.com/tediousjs/tedious) | 1013 | `nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer && mocha test/unit test/unit/token test/unit/tracking-buffer` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 1013 | `mocha --recursive ./test/*_spec.js` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1011 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1006 | `mocha --check-leaks -R dot` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 1005 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1005 | `mocha -R list` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1002 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 998 | `mocha spec/*.js` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 996 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 994 | `mocha --compilers js:babel-register test/*.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 994 | `npm run lint && mocha -R spec` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 941 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 940 | `mocha test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 939 | `mocha --timeout 5000` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 932 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 931 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 927 | `./node_modules/.bin/mocha test/**/*` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 927 | `istanbul cover -- _mocha --reporter spec` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 918 | `mocha -t 5000` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 917 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 925 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 924 | `standard && standard ./bin/* && mocha` | 
| [Shopify/slate](https://github.com/Shopify/slate) | 919 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 918 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 918 | `mocha -t 5000` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 917 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 916 | `mocha spec/*.spec.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 909 | `mocha test` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 908 | `npm run lint && npm run mocha:no-functional` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 908 | `mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 906 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 908 | `mocha test/index.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 908 | `npm run lint && npm run mocha:no-functional` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 908 | `mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 906 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 903 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [syt123450/giojs](https://github.com/syt123450/giojs) | 898 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 897 | `node_modules/.bin/mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 877 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 872 | `mocha --reporter list` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 870 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 863 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 863 | `istanbul cover _mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 862 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 862 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 861 | `mocha --reporter spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 858 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 858 | `mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 857 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 856 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 854 | `nyc mocha` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 854 | `mocha --harmony tests/**` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 853 | `mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 889 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 887 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 885 | `node_modules/.bin/mocha test/spec` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 883 | `npm run build && istanbul test _mocha test/test.js` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 882 | `mocha -r should --exit test/*.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 881 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 877 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 877 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 877 | `mocha --harmony --full-trace --check-leaks` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 873 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 872 | `mocha --reporter list` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 870 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 877 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 877 | `mocha --harmony --full-trace --check-leaks` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 873 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 872 | `mocha --reporter list` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 870 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 863 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 863 | `istanbul cover _mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 862 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 862 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 861 | `mocha --reporter spec` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 858 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 858 | `mocha` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 857 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 856 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 854 | `nyc mocha` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 854 | `mocha --harmony tests/**` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 854 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 853 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 852 | `mocha --check-leaks -t 20000` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 850 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 849 | `npm run lint && mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 848 | `mocha` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 847 | `mocha --opts mocha.opts` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 846 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 846 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 845 | `./node_modules/.bin/mocha test/unit -R spec -t 5000 --recursive` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 845 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 843 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 841 | `mocha --async-only` | 
| [developit/decko](https://github.com/developit/decko) | 838 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 837 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 836 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [developit/decko](https://github.com/developit/decko) | 838 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 837 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 836 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 834 | `mocha test` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 832 | `nyc mocha` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 832 | `npm run lint && mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 830 | `mocha && ember test` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 829 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 827 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 827 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 825 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 822 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 820 | `npm run mocha-test test/integration` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 819 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 806 | `mocha --require babel-register` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 804 | `mocha` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 799 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 799 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 798 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 796 | `mocha --no-timeouts` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 796 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 794 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 788 | `npm run lint && npm run mocha` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 787 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 786 | `nyc mocha` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 788 | `npm run lint && npm run mocha` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 787 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 786 | `nyc mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 784 | `mocha` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 784 | `mocha` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 782 | `mocha tests --timeout 10000` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 781 | `mocha --recursive -s 15 test/` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 777 | `mocha test` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 775 | `mocha -R spec src/**/*_test.js` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 774 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 773 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 772 | `eslint . && mocha` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 770 | `jenkins-mocha ./tests/*.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 770 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [koajs/static](https://github.com/koajs/static) | 766 | `mocha --harmony --reporter spec --exit` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 765 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 764 | `npm run-script jshint && npm run-script mocha` | 
| [susam/texme](https://github.com/susam/texme) | 764 | `standard && mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 763 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 775 | `mocha -R spec src/**/*_test.js` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 774 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 773 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require @babel/register` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 772 | `babel-node node_modules/.bin/_mocha -- test` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 772 | `eslint . && mocha` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 770 | `jenkins-mocha ./tests/*.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 770 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [koajs/static](https://github.com/koajs/static) | 766 | `mocha --harmony --reporter spec --exit` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 765 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 764 | `npm run-script jshint && npm run-script mocha` | 
| [susam/texme](https://github.com/susam/texme) | 764 | `standard && mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 763 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 744 | `npm run test-mocha && npm run test-karma` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 744 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 742 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 741 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 740 | `npm run bundle && mocha` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 738 | `mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 736 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 736 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 734 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 734 | `mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 744 | `npm run test-mocha && npm run test-karma` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 744 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 744 | `mocha test.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 742 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 742 | `mocha 'test/**/*.tests.js'` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 741 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 740 | `npm run bundle && mocha` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 738 | `mocha` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 736 | `mocha` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 736 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 736 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 736 | `mocha --reporter spec` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 734 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 734 | `mocha` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 731 | `mocha $(find test -name '*.test.js')` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [17koa/koa-generator](https://github.com/17koa/koa-generator) | 730 | `mocha --reporter spec --bail --check-leaks test/` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 729 | `mocha ./test/test.js --timeout 1000000` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 728 | `mocha --compilers js:babel-core/register` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 727 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 726 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 723 | `mocha --reporter spec test/` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 723 | `./node_modules/.bin/mocha tests/*.js` | 
| [wbyoung/avn](https://github.com/wbyoung/avn) | 718 | `jshint . && jscs . && istanbul cover node_modules/.bin/_mocha --report html --` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 716 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 715 | `mocha` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 713 | `mocha --reporter spec` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 707 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [typicode/katon](https://github.com/typicode/katon) | 707 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 703 | `mocha` | 