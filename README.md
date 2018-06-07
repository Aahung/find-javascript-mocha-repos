# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:01 06/07/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 41974 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40668 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38644 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29629 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24093 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23405 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 22829 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22365 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19010 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18428 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16310 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15912 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14407 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14139 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13490 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12746 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12495 | `mocha 'test/**/*.spec.js'` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 12384 | `mocha --reporter spec` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12327 | `./node_modules/.bin/mocha test/` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12152 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12096 | `mocha --reporter spec test/*-test.js` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11894 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11158 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11035 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10582 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10443 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9998 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9727 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9719 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9700 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9674 | `set NODE_ENV=test && mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9349 | `mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9162 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 8964 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8847 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8792 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 8762 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8495 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8375 | `mocha test/test.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8347 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8296 | `mocha --check-leaks -R dot` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8231 | `mocha test/src` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8222 | `grunt clean:test && mocha --exit` | 
| [amark/gun](https://github.com/amark/gun) | 8172 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8043 | `mocha tests/*.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8020 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7943 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7776 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7744 | `npm run eslint && npm run mocha` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7599 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7585 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7505 | `./node_modules/.bin/mocha test` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7439 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7337 | `npm run build && istanbul cover _mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7076 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7057 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 6891 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6889 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6878 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6820 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6776 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6714 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6613 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6310 | `npm run lint -s && npm run mocha -s` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6164 | `npm run jshint && mocha test/` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 6141 | `npm run build-cli && mocha` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 6139 | `mocha test node-test --recursive` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6132 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6113 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6029 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5935 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5880 | `mocha --exit --require babel-core/register` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5844 | `mocha test/test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5840 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5728 | `mocha tests/node.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 5701 | `mocha; jshint *.js lib` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5624 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5601 | `mocha && eslint lib/**` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5530 | `mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5405 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5384 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5358 | `mocha` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5276 | `mocha --timeout 10000 && npm run lint` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5271 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5163 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5153 | `mocha --color` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2845 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2840 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2840 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2837 | `mocha -R spec --recursive src/test` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2775 | `mocha --require should --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2774 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [github-tools/github](https://github.com/github-tools/github) | 2768 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2760 | `mocha --opts mocha.opts` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2750 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2748 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2743 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2732 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2716 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2680 | `xo && mocha` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2663 | `mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2659 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2626 | `mocha --timeout 100000` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2553 | `mocha -R landing test/index` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4559 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4555 | `mocha ./test/runner.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4505 | `mocha test` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4497 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4416 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4360 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4323 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4321 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4225 | `NODE_ENV=test mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4220 | `mocha -R spec ./test --recursive` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4213 | `mocha --recursive && make test` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3125 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3121 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3115 | `mocha` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3078 | `mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3077 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3049 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3042 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3011 | `NODE_ENV=test mocha --exit` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2991 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2977 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2955 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2950 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2944 | `mocha test/index.js && npm run demo` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2905 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2902 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2840 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2810 | `mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2775 | `mocha --require should --reporter spec` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2748 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2738 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2732 | `mocha` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2680 | `xo && mocha` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2663 | `mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2659 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2602 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2558 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2414 | `mocha test.js` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2404 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2388 | `mocha test/src/**/*.unit.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2373 | `mocha` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2352 | `mocha` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2294 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2288 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2702 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2696 | `npm run mocha && npm run lint` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2680 | `xo && mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2675 | `mocha --require babel-register --recursive spec` | 
| [css/csso](https://github.com/css/csso) | 2669 | `mocha --reporter dot` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2663 | `mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2659 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2626 | `mocha --timeout 100000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2602 | `mocha-phantomjs ./test/index.html` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2602 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2594 | `node_modules/.bin/mocha --reporter spec` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2589 | `mocha --recursive --watch` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2558 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2553 | `mocha -R landing test/index` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2294 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2288 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2254 | `mocha -R spec` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2244 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2177 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2176 | `mocha test && npm run lint` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2168 | `eslint . && mocha -t 5000` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2158 | `mocha && eslint .` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2109 | `cross-env BABEL_ENV=test mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2404 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2388 | `mocha test/src/**/*.unit.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2373 | `mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2369 | `node node_modules/mocha/bin/_mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2357 | `mocha test/unit --require mochahook` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2355 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2352 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2341 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2337 | `grunt jshint && mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2335 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2299 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2294 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2288 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1969 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1968 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [teambit/bit](https://github.com/teambit/bit) | 1956 | `mocha --require babel-core/register './specs/**/*.spec.js'` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1922 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1918 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1915 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1914 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1909 | `mocha --compilers js:babel-core/register __tests__` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1906 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1883 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1881 | `mocha --require ./test/common --growl test/expect.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1877 | `nyc npm run _mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1867 | `mocha && eslint *.js` | 
| [then/promise](https://github.com/then/promise) | 1858 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1982 | `mocha test/runner.js --reporter spec` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1969 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1958 | `mocha -c test/index.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 1956 | `mocha --require babel-core/register './specs/**/*.spec.js'` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1948 | `mocha --require=test/test_helper.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1922 | `mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1922 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1918 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1915 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1914 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1907 | `mocha --reporter spec --timeout 5000` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1906 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1898 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1922 | `mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1922 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1914 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1909 | `mocha --compilers js:babel-core/register __tests__` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1907 | `mocha --reporter spec --timeout 5000` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1906 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1898 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1883 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1881 | `mocha --require ./test/common --growl test/expect.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1880 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1877 | `nyc npm run _mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1867 | `mocha && eslint *.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1866 | `mocha tests.js` | 
| [then/promise](https://github.com/then/promise) | 1858 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [share/sharedb](https://github.com/share/sharedb) | 1857 | `./node_modules/.bin/mocha && npm run jshint` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1883 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1881 | `mocha --require ./test/common --growl test/expect.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1880 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1877 | `nyc npm run _mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1867 | `mocha && eslint *.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1866 | `mocha tests.js` | 
| [then/promise](https://github.com/then/promise) | 1858 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [share/sharedb](https://github.com/share/sharedb) | 1857 | `./node_modules/.bin/mocha && npm run jshint` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1849 | `npm run lint && mocha -R dot && npm run cover` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1829 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1817 | `mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1814 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1813 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1808 | `mocha` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1804 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1232 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1229 | `mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1226 | `mocha tests` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1224 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1221 | `mocha tests/test-*` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1213 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1205 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1198 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1193 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1188 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1187 | `mocha test` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1186 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1164 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1161 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1161 | `npm run lint && npm run mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1161 | `mocha --check-leaks --reporter spec --bail test/` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1752 | `mocha test` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1752 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [pahen/madge](https://github.com/pahen/madge) | 1741 | `npm run lint && npm run mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1724 | `mocha && npm run lint` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1722 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1719 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1719 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1710 | `npm run lint && npm run mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1709 | `mocha --reporter spec test/*.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1708 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1707 | `mocha --reporter spec --grep .` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1705 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1702 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1702 | `mocha tests --compilers js:babel-core/register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1702 | `npm run lint && mocha test/unit --recursive && mocha test/runner --recursive` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1692 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1690 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1674 | `xo && mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1672 | `mocha test/**/*.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1653 | `npm run lint && mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1650 | `mocha test --timeout 600000` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1643 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1638 | `mocha test/*.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1637 | `mocha ./test/basic.js -t 5000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1636 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1634 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1628 | `mocha --expose-gc --slow 300` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1620 | `mocha --compilers js:babel-register` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1588 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1588 | `mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1552 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1543 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1527 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1504 | `npm run test:lint && npm run test:mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1499 | `eslint --cache . && tsc && mocha` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1489 | `standard "./src/*.js" && mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1482 | `node_modules/.bin/mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1482 | `mocha -u tdd` | 
| [zeit/ms](https://github.com/zeit/ms) | 1478 | `mocha tests.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1475 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1472 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1472 | `mocha -R spec` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1470 | `mocha test.js` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1468 | `nyc mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1468 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1454 | `mocha --check-leaks --reporter spec --bail` | 
| [samccone/drool](https://github.com/samccone/drool) | 1449 | `mocha test/tests.js --timeout=10000` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1443 | `mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1439 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1384 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1369 | `mocha --timeout 10000 ./tests/lib.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1362 | `mocha test` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1329 | `npm run build && mocha -r should` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1384 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1369 | `./node_modules/mocha/bin/mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1369 | `mocha --timeout 10000 ./tests/lib.js` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1362 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1362 | `mocha test` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1358 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1349 | `cross-env NODE_ENV=test nyc mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1330 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1329 | `npm run build && mocha -r should` | 
| [electron/devtron](https://github.com/electron/devtron) | 1321 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1317 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1315 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1305 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1304 | `nyc mocha --timeout=20000 test.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1302 | `mocha --check-leaks --require @babel/register` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1298 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1293 | `mocha-phantomjs tests/index.html` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1291 | `./node_modules/.bin/mocha test` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1283 | `mocha --recursive` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1281 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1278 | `mocha` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1278 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1278 | `mocha spec/exec.js` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1272 | `mocha --opts test/opts/mocha.opts` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1253 | `mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1250 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1248 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1242 | `mocha --timeout 60000 test/` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1238 | `mocha test/*.js` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1232 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1229 | `mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1228 | `standard && istanbul cover _mocha` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1226 | `mocha tests` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1224 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1224 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1221 | `mocha tests/test-*` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1213 | `mocha` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1205 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1198 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1193 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1205 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1193 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1192 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1189 | `node ./node_modules/mocha/bin/mocha tests` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1188 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1186 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1186 | `mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1185 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1178 | `mocha src/test.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1178 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1170 | `mocha --reporter spec` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1169 | `mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1164 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [variety/variety](https://github.com/variety/variety) | 1162 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1161 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1160 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1224 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1221 | `mocha tests/test-*` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1213 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1209 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1205 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1198 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1193 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1192 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1189 | `node ./node_modules/mocha/bin/mocha tests` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1189 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1188 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1187 | `mocha test` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1186 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1186 | `mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1185 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 911 | `mocha ./test/index.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 911 | `mocha --compilers js:babel-register test/*.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 902 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 886 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 870 | `node_modules/.bin/mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 868 | `mocha` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 867 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 866 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 865 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 863 | `mocha -t 600000` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 862 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 861 | `mocha --timeout 200000` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 861 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 860 | `npm run lint && npm run mocha:no-functional` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 859 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 859 | `mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 854 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 852 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 851 | `eslint test && mocha --compilers js:babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 849 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 841 | `mocha` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 838 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 837 | `mocha -t 5000` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 837 | `mocha spec/*.js` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 835 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 835 | `mocha --check-leaks -t 20000` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 833 | `mocha --reporter spec` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 831 | `nyc mocha specs` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 831 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 830 | `istanbul cover _mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 829 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 828 | `mocha test --compilers js:babel-register` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 826 | `./node_modules/.bin/mocha -R spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 826 | `./node_modules/.bin/mocha -R spec` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 824 | `mocha test --compilers js:babel-core/register` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 824 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 824 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 824 | `istanbul cover -- _mocha --reporter spec` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 821 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 820 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 817 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 815 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 813 | `npm run lint && mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 813 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 811 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 803 | `mocha --require babel-register` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 801 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 799 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 798 | `./node_modules/.bin/mocha --reporter spec` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 796 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 796 | `mocha --timeout 30000 --recursive ./tests` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 795 | `mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 794 | `mocha -u tdd` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 793 | `cake build && mocha ./test/mocha/*.coffee` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 791 | `mocha -R spec tests/` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 791 | `mocha test` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 789 | `mocha --async-only` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 788 | `mocha` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 787 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 745 | `mocha --recursive -s 15 test/` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 745 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 743 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [webpack-contrib/webpack-serve](https://github.com/webpack-contrib/webpack-serve) | 738 | `nyc npm run mocha` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 737 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 733 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 732 | `mocha test` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 731 | `mocha --reporter spec` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 730 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 729 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 727 | `mocha --no-timeouts` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 766 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 766 | `mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 765 | `npm run mocha-test test/integration` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 765 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 760 | `mocha --ui tdd --require ./test/__setup` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 760 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 759 | `mocha test` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 758 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 758 | `mocha --harmony --full-trace --check-leaks` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 757 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 757 | `mocha` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 755 | `mocha -R spec src/**/*_test.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 753 | `npm run build && istanbul test _mocha test/test.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 750 | `mocha` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 750 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 751 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 750 | `mocha` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 750 | `mocha` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 745 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 745 | `mocha --recursive -s 15 test/` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 745 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 743 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 743 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [developit/decko](https://github.com/developit/decko) | 742 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [webpack-contrib/webpack-serve](https://github.com/webpack-contrib/webpack-serve) | 738 | `nyc npm run mocha` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 737 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 736 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 733 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 733 | `mocha test` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 733 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 733 | `mocha test` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 732 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 732 | `mocha test` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 731 | `mocha --reporter spec` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 731 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 730 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 729 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 727 | `mocha --no-timeouts` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 725 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 724 | `mocha test.js` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 723 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 722 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 722 | `mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 721 | `mocha tests/*.mocha.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 720 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 693 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 693 | `./node_modules/.bin/mocha -t 60000` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 692 | `mocha --reporter spec build/test/index.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 691 | `./bin/selenium-standalone install && mocha` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 690 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 688 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 687 | `mocha --reporter spec` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 685 | `npm run-script jshint && npm run-script mocha` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 681 | `mocha ./test/test.js --timeout 1000000` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 681 | `mocha` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 679 | `npm run lint && mocha test` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 676 | `./node_modules/.bin/mocha test/**/*` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 697 | `mocha ./test/index.js` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 696 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 696 | `babel-node node_modules/.bin/_mocha -- test` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 693 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 693 | `./node_modules/.bin/mocha -t 60000` | 
| [scality/S3](https://github.com/scality/S3) | 692 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 692 | `mocha --reporter spec build/test/index.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 691 | `./bin/selenium-standalone install && mocha` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 690 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 688 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 687 | `mocha --reporter spec` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 681 | `mocha ./test/test.js --timeout 1000000` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 681 | `mocha` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 679 | `npm run lint && mocha test` | 
| [nodesecurity/eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) | 676 | `./node_modules/.bin/mocha test/**/*` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 672 | `mocha -b -R spec test/*` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 672 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 669 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 668 | `mocha` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 669 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 668 | `mocha` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 667 | `mocha $(find test -name '*.test.js')` | 
| [walmartlabs/react-ssr-optimization](https://github.com/walmartlabs/react-ssr-optimization) | 667 | `istanbul test _mocha -- -R spec --recursive test/spec` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 665 | `nyc mocha` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 664 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 661 | `mocha --compilers js:babel-core/register` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 661 | `mocha` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 660 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 658 | `mocha --reporter spec` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 656 | `jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 655 | `./node_modules/.bin/mocha test/integration` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 654 | `mocha -R spec` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 654 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 654 | `mocha` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 652 | `mocha` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 650 | `mocha` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 649 | `mocha --bail test/` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 648 | `mocha --recursive --compilers js:babel-core/register` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 648 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 648 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [mysamai/mysam](https://github.com/mysamai/mysam) | 606 | `npm run lint && npm run mocha` | 
| [phodal/sherlock](https://github.com/phodal/sherlock) | 603 | `mocha --reporter spec` | 
| [rofrischmann/react-look](https://github.com/rofrischmann/react-look) | 601 | `npm run lint && mocha --recursive --compilers js:babel/register` | 
| [danawoodman/react-fontawesome](https://github.com/danawoodman/react-fontawesome) | 598 | `mocha` | 
| [w0rm/gulp-svgstore](https://github.com/w0rm/gulp-svgstore) | 597 | `gulp build && mocha test.js` | 
| [jfromaniello/passport.socketio](https://github.com/jfromaniello/passport.socketio) | 596 | `mocha` | 
| [ck86/main-bower-files](https://github.com/ck86/main-bower-files) | 595 | `mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 595 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require babel-register` | 
| [shinnn/gulp-gh-pages](https://github.com/shinnn/gulp-gh-pages) | 594 | `mocha test.js --timeout 50000 --full-trace` | 
| [susielu/d3-legend](https://github.com/susielu/d3-legend) | 591 | `mocha` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 631 | `mocha --reporter spec` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 630 | `mocha --reporter spec` | 
| [tonyhb/redux-ui](https://github.com/tonyhb/redux-ui) | 628 | `$(npm bin)/mocha  --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [manavsehgal/reactspeedcoding](https://github.com/manavsehgal/reactspeedcoding) | 625 | `NODE_ENV=test npm run elint && npm run slint && npm run test:mocha` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 625 | `npm run lint && mocha` | 
| [robwierzbowski/generator-jekyllrb](https://github.com/robwierzbowski/generator-jekyllrb) | 623 | `mocha` | 
| [59naga/babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports) | 622 | `mocha --require babel-register` | 
| [jbrooksuk/node-summary](https://github.com/jbrooksuk/node-summary) | 622 | `mocha --compilers js:babel-core/register --require should --reporter spec` | 
| [amasad/debug_utils](https://github.com/amasad/debug_utils) | 622 | `mocha ./test --bail` | 
| [floatdrop/gulp-watch](https://github.com/floatdrop/gulp-watch) | 621 | `xo && mocha -r test/util/set-default-options -t 5000 -R spec test/test-*` | 
| [gridcontrol/gridcontrol](https://github.com/gridcontrol/gridcontrol) | 588 | `NODE_ENV='test' DEBUG='gc:*' ./node_modules/.bin/mocha test/*.mocha.js -b` | 
| [matthewmueller/graph.ql](https://github.com/matthewmueller/graph.ql) | 588 | `./node_modules/.bin/mocha` | 
| [SamyPesse/gitkit-js](https://github.com/SamyPesse/gitkit-js) | 587 | `./node_modules/.bin/mocha ./testing/setup.js ./lib/**/*/__tests__/*.js --bail --reporter=list` | 
| [JustClear/blurify](https://github.com/JustClear/blurify) | 587 | `mocha test/index.js` | 
| [putaoshu/jdf](https://github.com/putaoshu/jdf) | 586 | `mocha test/index.js` | 
| [dleitee/valid.js](https://github.com/dleitee/valid.js) | 584 | `mocha --compilers js:babel-register` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 583 | `mocha` | 
| [jimpick/lambda-comments](https://github.com/jimpick/lambda-comments) | 583 | `mocha --compilers js:./babel-register` | 
| [LouisBarranqueiro/reapop](https://github.com/LouisBarranqueiro/reapop) | 583 | `babel-node ./node_modules/karma/bin/karma start ./build/karma.conf.js --reporters mocha` | 
| [jaredhanson/passport-google-oauth](https://github.com/jaredhanson/passport-google-oauth) | 583 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [docpress/docpress](https://github.com/docpress/docpress) | 583 | `nyc mocha` | 
| [bitovi/documentjs](https://github.com/bitovi/documentjs) | 582 | `mocha test.js --reporter spec` | 
| [webdriverio/webdrivercss](https://github.com/webdriverio/webdrivercss) | 580 | `./node_modules/.bin/mocha` | 
| [zpratt/react-tdd-guide](https://github.com/zpratt/react-tdd-guide) | 579 | `npm run lint && mocha */test` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 579 | `_mocha -u bdd --colors test/` | 
| [esnext/esnext](https://github.com/esnext/esnext) | 579 | `mocha` | 
| [aliyun-UED/aliyun-sdk-js](https://github.com/aliyun-UED/aliyun-sdk-js) | 579 | `mocha test` | 
| [bbc/VideoContext](https://github.com/bbc/VideoContext) | 578 | `node ./node_modules/mocha/bin/mocha --compilers js:babel-core/register` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 578 | `mocha` | 
| [formio/formio](https://github.com/formio/formio) | 577 | `npm run version && env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 575 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [scrollback/scrollback](https://github.com/scrollback/scrollback) | 574 | `node_modules/.bin/mocha test/test.js` | 
| [ziyasal/scientist.js](https://github.com/ziyasal/scientist.js) | 573 | `node ./node_modules/babel-cli/bin/babel-node.js ./node_modules/mocha/bin/_mocha --timeout 20000 tests/**/*.spec.js` | 
| [hparra/gulp-rename](https://github.com/hparra/gulp-rename) | 605 | `mocha` | 
| [maxkueng/victor](https://github.com/maxkueng/victor) | 604 | `mocha --ui bdd --reporter spec` | 
| [phodal/sherlock](https://github.com/phodal/sherlock) | 603 | `mocha --reporter spec` | 
| [Ivshti/linvodb3](https://github.com/Ivshti/linvodb3) | 602 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [rofrischmann/react-look](https://github.com/rofrischmann/react-look) | 601 | `npm run lint && mocha --recursive --compilers js:babel/register` | 
| [danawoodman/react-fontawesome](https://github.com/danawoodman/react-fontawesome) | 598 | `mocha` | 
| [tj/node-blocked](https://github.com/tj/node-blocked) | 598 | `./node_modules/mocha/bin/mocha` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 597 | `mocha` | 
| [w0rm/gulp-svgstore](https://github.com/w0rm/gulp-svgstore) | 597 | `gulp build && mocha test.js` | 
| [jfromaniello/passport.socketio](https://github.com/jfromaniello/passport.socketio) | 596 | `mocha` | 
| [IjzerenHein/autolayout.js](https://github.com/IjzerenHein/autolayout.js) | 596 | `mocha` | 
| [joaonuno/tree-model-js](https://github.com/joaonuno/tree-model-js) | 596 | `istanbul cover _mocha` | 
| [ck86/main-bower-files](https://github.com/ck86/main-bower-files) | 595 | `mocha` | 
| [jfromaniello/passport.socketio](https://github.com/jfromaniello/passport.socketio) | 596 | `mocha` | 
| [IjzerenHein/autolayout.js](https://github.com/IjzerenHein/autolayout.js) | 596 | `mocha` | 
| [echenley/react-news](https://github.com/echenley/react-news) | 596 | `./node_modules/.bin/karma start ./test/karma.conf.js --reporters mocha,coverage` | 
| [joaonuno/tree-model-js](https://github.com/joaonuno/tree-model-js) | 596 | `istanbul cover _mocha` | 
| [ck86/main-bower-files](https://github.com/ck86/main-bower-files) | 595 | `mocha` | 
| [LucasBassetti/react-simple-chatbot](https://github.com/LucasBassetti/react-simple-chatbot) | 595 | `./node_modules/.bin/mocha tests/helpers/setup.js tests/**/*.spec.js --require babel-register` | 
| [shinnn/gulp-gh-pages](https://github.com/shinnn/gulp-gh-pages) | 594 | `mocha test.js --timeout 50000 --full-trace` | 
| [postcss/gulp-postcss](https://github.com/postcss/gulp-postcss) | 593 | `nyc mocha test.js` | 
| [robrich/gulp-if](https://github.com/robrich/gulp-if) | 592 | `mocha && jshint .` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 592 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [susielu/d3-legend](https://github.com/susielu/d3-legend) | 591 | `mocha` | 
| [gridcontrol/gridcontrol](https://github.com/gridcontrol/gridcontrol) | 588 | `NODE_ENV='test' DEBUG='gc:*' ./node_modules/.bin/mocha test/*.mocha.js -b` | 
| [aaronshaf/react-toggle](https://github.com/aaronshaf/react-toggle) | 588 | `nyc mocha --require babel-register --require spec/setup.js spec/**/*.spec.js` | 
| [matthewmueller/graph.ql](https://github.com/matthewmueller/graph.ql) | 588 | `./node_modules/.bin/mocha` | 
| [SamyPesse/gitkit-js](https://github.com/SamyPesse/gitkit-js) | 587 | `./node_modules/.bin/mocha ./testing/setup.js ./lib/**/*/__tests__/*.js --bail --reporter=list` | 
| [jkphl/gulp-svg-sprite](https://github.com/jkphl/gulp-svg-sprite) | 565 | `gulp && istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [times/cardkit](https://github.com/times/cardkit) | 565 | `./node_modules/.bin/istanbul cover --dir test/coverage ./node_modules/.bin/_mocha -- --compilers js:babel-core/register --require ignore-styles` | 
| [M6Web/websocket-bench](https://github.com/M6Web/websocket-bench) | 564 | `gulp mocha` | 
| [azproduction/autopolyfiller](https://github.com/azproduction/autopolyfiller) | 563 | `npm run lint && mocha -R spec` | 
| [mtth/avsc](https://github.com/mtth/avsc) | 562 | `mocha` | 
| [expressjs/cookie-session](https://github.com/expressjs/cookie-session) | 561 | `mocha --check-leaks --reporter spec --bail test/` | 
| [jmar777/suspend](https://github.com/jmar777/suspend) | 558 | `node ./node_modules/mocha/bin/mocha --harmony --reporter list` | 
| [LearnBoost/up](https://github.com/LearnBoost/up) | 558 | `./node_modules/mocha/bin/mocha test/*.test.js` | 
| [matthewmueller/socrates](https://github.com/matthewmueller/socrates) | 557 | `devtool node_modules/mocha/bin/_mocha -qc -- ./test/` | 
| [moshen/node-googlemaps](https://github.com/moshen/node-googlemaps) | 556 | `./node_modules/.bin/mocha test/unit` | 
| [gulp-community/gulp-less](https://github.com/gulp-community/gulp-less) | 556 | `jshint index.js && node_modules/.bin/mocha` | 
| [GianlucaGuarini/icaro](https://github.com/GianlucaGuarini/icaro) | 554 | `npm run lint && mocha test` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 578 | `mocha` | 
| [blueberryapps/react-bluekit](https://github.com/blueberryapps/react-bluekit) | 578 | `mocha --compilers js:babel/register --recursive` | 
| [formio/formio](https://github.com/formio/formio) | 577 | `npm run version && env TEST_SUITE=1 mocha test/test.js -b -t 60000 --exit` | 
| [mikaelbr/gulp-notify](https://github.com/mikaelbr/gulp-notify) | 577 | `mocha -R spec` | 
| [svrcekmichal/redux-axios-middleware](https://github.com/svrcekmichal/redux-axios-middleware) | 577 | `mocha --compilers js:babel-register --require ./test/test_helper.js` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 575 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [scrollback/scrollback](https://github.com/scrollback/scrollback) | 574 | `node_modules/.bin/mocha test/test.js` | 
| [ziyasal/scientist.js](https://github.com/ziyasal/scientist.js) | 573 | `node ./node_modules/babel-cli/bin/babel-node.js ./node_modules/mocha/bin/_mocha --timeout 20000 tests/**/*.spec.js` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 573 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [sindresorhus/jshint-stylish](https://github.com/sindresorhus/jshint-stylish) | 573 | `xo && mocha` | 
| [theoephraim/node-google-spreadsheet](https://github.com/theoephraim/node-google-spreadsheet) | 571 | `node_modules/.bin/mocha` | 
| [edankwan/penis.js](https://github.com/edankwan/penis.js) | 570 | `mocha --ui bdd --reporter spec test/` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 569 | `mocha` | 
| [felixge/node-dirty](https://github.com/felixge/node-dirty) | 568 | `mocha test/test-*.js -R list` | 