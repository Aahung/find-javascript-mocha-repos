# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:07 06/06/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 41947 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40655 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38628 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29621 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 23384 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 22743 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22352 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 18995 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18421 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16302 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15903 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16302 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15903 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14395 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14134 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13486 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12741 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12489 | `mocha 'test/**/*.spec.js'` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 12361 | `mocha --reporter spec` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12317 | `./node_modules/.bin/mocha test/` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12150 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12095 | `mocha --reporter spec test/*-test.js` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11878 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11149 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11022 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10566 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10431 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9988 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9725 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9713 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9693 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9667 | `set NODE_ENV=test && mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9305 | `mocha` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 9179 | `mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9159 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 8950 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8846 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8787 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 8754 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8488 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8374 | `mocha test/test.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8341 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8295 | `mocha --check-leaks -R dot` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8226 | `mocha test/src` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8221 | `grunt clean:test && mocha --exit` | 
| [amark/gun](https://github.com/amark/gun) | 8169 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8039 | `mocha tests/*.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8017 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7943 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7756 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7744 | `npm run eslint && npm run mocha` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7591 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7571 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7504 | `./node_modules/.bin/mocha test` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7439 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7335 | `npm run build && istanbul cover _mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7070 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7051 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6882 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 6881 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6868 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6816 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6777 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6705 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6608 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6308 | `npm run lint -s && npm run mocha -s` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6154 | `npm run jshint && mocha test/` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6127 | `npm run test:mocha:src` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 6126 | `mocha test node-test --recursive` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 6126 | `npm run build-cli && mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6114 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6028 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5937 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5874 | `mocha --exit --require babel-core/register` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5842 | `mocha test/test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5838 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5404 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5381 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 5349 | `mocha` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5277 | `mocha --timeout 10000 && npm run lint` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 5262 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5162 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5153 | `mocha --color` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4960 | `standard && mocha` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4932 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3357 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3354 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3278 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3125 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3120 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3115 | `mocha` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3079 | `mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3047 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3040 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3007 | `NODE_ENV=test mocha --exit` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2991 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4555 | `mocha ./test/runner.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4553 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4502 | `mocha test` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4498 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4416 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4357 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4323 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4321 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4221 | `NODE_ENV=test mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4221 | `mocha -R spec ./test --recursive` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4207 | `mocha --recursive && make test` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3968 | `mocha --require test/babel-hook test/*.js` | 
| [muicss/mui](https://github.com/muicss/mui) | 3965 | `mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3949 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3915 | `mocha -R spec ./test` | 
| [tj/ejs](https://github.com/tj/ejs) | 3899 | `mocha --require should --reporter spec` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3882 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3875 | `export TESTING=true; mocha --reporter list` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3871 | `npm run lint && npm run mocha` | 
| [erming/shout](https://github.com/erming/shout) | 3803 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3799 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3787 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3769 | `prettier-check src/**/*.js && mocha ./test/*.spec.js` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3695 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3662 | `npm run jshint && npm run mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3619 | `standard && mocha --timeout 60000 test/test.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3611 | `mocha --check-leaks --reporter spec --bail` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3605 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [primus/primus](https://github.com/primus/primus) | 3591 | `npm run build && mocha test/*.test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3560 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3560 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3497 | `mocha --reporter spec --timeout 3000` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3479 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3466 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3456 | `nyc mocha "test/**/*.test.js"` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3449 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3432 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3431 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3422 | `mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3406 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3396 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3357 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3354 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3357 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3354 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3332 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3303 | `node_modules/.bin/mocha test/tests.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3278 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3125 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3120 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3115 | `mocha` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 3007 | `NODE_ENV=test mocha --exit` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3006 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2991 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2976 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2953 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2944 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2940 | `mocha test/index.js && npm run demo` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2904 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2901 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2876 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2868 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2855 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2844 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2841 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2838 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2837 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2811 | `mocha` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2901 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2876 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2868 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2855 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2844 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2841 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2838 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2837 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2811 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2790 | `istanbul cover _mocha` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2776 | `mocha --require should --reporter spec` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2773 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2770 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2768 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2767 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2758 | `mocha --opts mocha.opts` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2747 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2745 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2740 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2736 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2728 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2713 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2697 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2696 | `npm run mocha && npm run lint` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2679 | `xo && mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2673 | `mocha --require babel-register --recursive spec` | 
| [css/csso](https://github.com/css/csso) | 2669 | `mocha --reporter dot` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2664 | `mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2659 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2626 | `mocha --timeout 100000` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2602 | `mocha-phantomjs ./test/index.html` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2600 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2356 | `mocha test/unit --require mochahook` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2352 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2341 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2338 | `grunt jshint && mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2333 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2299 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2287 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2258 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2252 | `mocha -R spec` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2244 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2243 | `nyc --reporter=html --reporter=text mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2234 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2224 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1877 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1866 | `mocha tests.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1856 | `./node_modules/.bin/mocha && npm run jshint` | 
| [kach/nearley](https://github.com/kach/nearley) | 1835 | `mocha test/*.test.js` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1816 | `mocha` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1815 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1813 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1809 | `mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1802 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1798 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1781 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1780 | `mocha --reporter spec && npm run test-typescript` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1768 | `npm run lint && mocha --reporter spec test/*.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1767 | `npm run mocha && npm run karma` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1752 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [pahen/madge](https://github.com/pahen/madge) | 1737 | `npm run lint && npm run mocha` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2258 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2252 | `mocha -R spec` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2244 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2243 | `nyc --reporter=html --reporter=text mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2234 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2224 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [gajus/swing](https://github.com/gajus/swing) | 2196 | `mocha --compilers js:babel-register` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2174 | `mocha test && npm run lint` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2173 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2163 | `eslint . && mocha -t 5000` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2157 | `mocha && eslint .` | 
| [noble/noble](https://github.com/noble/noble) | 2121 | `mocha -R spec test/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2108 | `cross-env BABEL_ENV=test mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2089 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2083 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2065 | `mocha --compilers js:babel-register` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2037 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [Qix-/color](https://github.com/Qix-/color) | 2020 | `mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2015 | `standard && mocha` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2014 | `mocha test/index.js --reporter dot` | 
| [slate/slate](https://github.com/slate/slate) | 2008 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2003 | `mocha test/ --no-timeouts` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1777 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1768 | `npm run lint && mocha --reporter spec test/*.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1767 | `npm run mocha && npm run karma` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1765 | `mocha -R spec spec spec/reporters` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1754 | `mocha test` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1752 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1722 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1719 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1709 | `mocha --reporter spec test/*.js` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1705 | `mocha --reporter spec --grep .` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1701 | `mocha tests --compilers js:babel-core/register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1699 | `npm run lint && mocha test/unit --recursive && mocha test/runner --recursive` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1692 | `./node_modules/.bin/mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1689 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1674 | `xo && mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1671 | `mocha test/**/*.js` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1657 | `mocha test -u bdd -R spec` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1653 | `npm run lint && mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1643 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1642 | `mocha test --timeout 600000` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1638 | `mocha test/*.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1637 | `mocha ./test/basic.js -t 5000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1637 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1634 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1628 | `mocha --expose-gc --slow 300` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1623 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1620 | `mocha --compilers js:babel-register` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1619 | `mocha tests/test.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1618 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1612 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1610 | `mocha && size-limit` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1618 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1612 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1610 | `mocha && size-limit` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1599 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1595 | `npm run lint && npm run mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1595 | `mocha test/* --reporter spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1587 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1585 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1551 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1550 | `./node_modules/.bin/mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1474 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1471 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1468 | `nyc mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1466 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1458 | `mocha` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1450 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1449 | `mocha test/tests.js --timeout=10000` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1442 | `mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1436 | `mocha test.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1432 | `nyc npm run mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1384 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1481 | `node_modules/.bin/mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1481 | `mocha -u tdd` | 
| [zeit/ms](https://github.com/zeit/ms) | 1478 | `mocha tests.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1474 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1472 | `mocha -R spec` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1471 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1470 | `mocha test.js` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1468 | `nyc mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1468 | `mocha test/setup.js test/spec/*.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1466 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1458 | `mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1457 | `mocha test/**/*.spec.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1453 | `mocha --check-leaks --reporter spec --bail` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1450 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1449 | `mocha test/tests.js --timeout=10000` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1442 | `mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1437 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1436 | `mocha test.js` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1450 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1449 | `mocha test/tests.js --timeout=10000` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1442 | `mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1437 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1436 | `mocha test.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1432 | `nyc npm run mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1432 | `mocha --recursive` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1395 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1360 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1357 | `mocha test` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1356 | `istanbul cover _mocha` | 
| [noble/bleno](https://github.com/noble/bleno) | 1353 | `mocha -R spec test/*.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1348 | `cross-env NODE_ENV=test nyc mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1329 | `npm run build && mocha -r should` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1328 | `mocha` | 
| [electron/devtron](https://github.com/electron/devtron) | 1320 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1161 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1160 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 1149 | `TEST=all mocha` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1145 | `mocha` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1137 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1133 | `mocha -R spec ./test/unit/**` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1131 | `mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1130 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1123 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1121 | `mocha ./test/test*.js --reporter spec` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1121 | `NODE_ENV=test mocha tests/*.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1114 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1112 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1111 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1280 | `mocha --recursive` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1279 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1277 | `mocha` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1277 | `mocha spec/exec.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1274 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1272 | `mocha --opts test/opts/mocha.opts` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1265 | `mocha test/unit` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1262 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1253 | `eslint src && mocha && karma start --single-run` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1252 | `mocha` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1249 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1247 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1242 | `mocha --timeout 60000 test/` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1240 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1237 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1237 | `mocha test/*.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1231 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1231 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1229 | `mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1228 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1227 | `mocha --reporter dot` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1227 | `mocha tests` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1224 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1224 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1219 | `mocha tests/test-*` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1216 | `mocha test/test.js` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1213 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1209 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1205 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1193 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1191 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1191 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1189 | `node ./node_modules/mocha/bin/mocha tests` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1189 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1188 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1186 | `mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1186 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1185 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1185 | `mocha test` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1178 | `mocha src/test.js` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1177 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1170 | `mocha --reporter spec` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1168 | `mocha` | 
| [twolfson/grunt-spritesmith](https://github.com/twolfson/grunt-spritesmith) | 1161 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 1161 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [variety/variety](https://github.com/variety/variety) | 1161 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1160 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1160 | `npm run lint && npm run mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1159 | `mocha --check-leaks --reporter spec --bail test/` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1139 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1137 | `istanbul test node_modules/mocha/bin/_mocha --report html -- test/svg-sprite.js --reporter spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1136 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1133 | `mocha -R spec ./test/unit/**` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1131 | `mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1130 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1123 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1122 | `NODE_ENV=test mocha tests/*.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1121 | `mocha ./test/test*.js --reporter spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1114 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1112 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1110 | `npm run prepublishOnly && mocha test/test.js` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 1121 | `mocha ./test/test*.js --reporter spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1114 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1112 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1111 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1110 | `npm run prepublishOnly && mocha test/test.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1105 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1104 | `mocha --recursive test` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1103 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1102 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1100 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1100 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1099 | `mocha $(find test -name '*.test.js')` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1098 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1098 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1090 | `mocha` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1090 | `xo && mocha` | 
| [firebase/firebase-tools](https://github.com/firebase/firebase-tools) | 1088 | `npm run lint && npm run mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1083 | `istanbul cover _mocha test/*.js` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1083 | `mocha test/*` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1082 | `mocha --check-leaks -t 20000` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1080 | `mocha --compilers js:babel-core/register` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1080 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1079 | `NODE_PATH=. mocha **/*.spec.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1079 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1078 | `nodeunit test; mocha test` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1074 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1074 | `mocha --compilers js:babel-register` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1073 | `mocha --recursive test/bin` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1069 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1058 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1058 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1053 | `istanbul test _mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1043 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1040 | `mocha --reporter spec --timeout 3000` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1037 | `standard && mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1036 | `mocha test/tests.js` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1031 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1029 | `mocha` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1027 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1022 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1022 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [electron/asar](https://github.com/electron/asar) | 1015 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1014 | `mocha --check-leaks -R dot` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1011 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1009 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 1008 | `webpack && mocha test/unit` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1005 | `mocha $(find test -name '*.test.js')` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1004 | `mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 998 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 996 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 993 | `mocha --reporter spec --bail --check-leaks test/` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 992 | `mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 989 | `mocha test` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 988 | `mocha --recursive test/unit/` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 986 | `standard && mocha -b` | 
| [electron/spectron](https://github.com/electron/spectron) | 983 | `mocha && standard` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 979 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 977 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 976 | `mocha --async-only` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 974 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 970 | `mocha -R list` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 967 | `eslint src test && mocha --compilers babel-register` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 976 | `mocha --async-only` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 974 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 970 | `mocha -R list` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 967 | `eslint src test && mocha --compilers babel-register` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 967 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 963 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 960 | `mocha --reporter spec` | 
| [ulid/javascript](https://github.com/ulid/javascript) | 960 | `./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha -- -R spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 959 | `npm run mocha:istanbul` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 957 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 951 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 948 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 951 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 948 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 947 | `mocha --timeout 5000` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 940 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 928 | `npm run convertto:es5 && npm run mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 924 | `mocha "client.test" --compilers js:babel-register` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 918 | `npm-run-all test:jest test:server:mocha` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 918 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 917 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 912 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 911 | `mocha ./test/index.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 911 | `mocha --compilers js:babel-register test/*.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 910 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 909 | `mocha --reporter spec --bail --check-leaks test/` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 903 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 902 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 902 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 897 | `npm run lint && mocha -R spec` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 897 | `mocha -R spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 890 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 888 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 886 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 880 | `mocha tests` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 872 | `mocha --reporter list` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 870 | `node_modules/.bin/mocha` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 870 | `mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 868 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 866 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 865 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 865 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 862 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 862 | `mocha -t 600000` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 861 | `mocha --timeout 200000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 861 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 861 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 860 | `npm run lint && npm run mocha:no-functional` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 859 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 859 | `mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 853 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 853 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 851 | `node_modules/.bin/mocha test/spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 851 | `eslint test && mocha --compilers js:babel/register` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 849 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 841 | `mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 839 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 838 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 837 | `mocha -t 5000` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 835 | `mocha --check-leaks -t 20000` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 833 | `mocha --reporter spec` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 833 | `mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 833 | `mocha spec/*.js` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 829 | `istanbul cover _mocha` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 829 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 828 | `mocha test --compilers js:babel-register` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 825 | `./node_modules/.bin/mocha -R spec` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 824 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 824 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 823 | `mocha test --compilers js:babel-core/register` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 821 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 819 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 816 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 815 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 813 | `npm run lint && mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 813 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 812 | `mocha tests/*.test.js --reporter spec` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 813 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 812 | `mocha tests/*.test.js --reporter spec` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 808 | `mocha --reporter spec --bail --check-leaks test/` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 807 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 804 | `mocha --reporter list` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 803 | `mocha --require babel-register` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 802 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 800 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 799 | `mocha` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 797 | `./node_modules/.bin/mocha --reporter spec` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 796 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 795 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 795 | `mocha --timeout 30000 --recursive ./tests` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 794 | `mocha -u tdd` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 766 | `nyc --check-coverage mocha test/*.test.js` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 766 | `mocha` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 765 | `mocha test/index.js` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 761 | `mocha --recursive ./test/*_spec.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 760 | `mocha --ui tdd --require ./test/__setup` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 759 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 758 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 758 | `mocha --harmony --full-trace --check-leaks` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 757 | `mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 756 | `mocha test` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 755 | `mocha -R spec src/**/*_test.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 752 | `npm run build && istanbul test _mocha test/test.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 750 | `mocha` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 750 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 749 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 747 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 746 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 759 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 758 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 757 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 757 | `mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 756 | `mocha test` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 755 | `mocha -R spec src/**/*_test.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 752 | `npm run build && istanbul test _mocha test/test.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 750 | `mocha` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 750 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 749 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 746 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 745 | `mocha --recursive -s 15 test/` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 743 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 742 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 741 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 759 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 758 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 758 | `mocha --harmony --full-trace --check-leaks` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 757 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 757 | `mocha` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 756 | `mocha test` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 755 | `mocha -R spec src/**/*_test.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 752 | `npm run build && istanbul test _mocha test/test.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 750 | `mocha` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 750 | `mocha` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 749 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 747 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 746 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 745 | `mocha --recursive -s 15 test/` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 743 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 742 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 730 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 729 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 727 | `mocha --no-timeouts` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 724 | `mocha test.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 724 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 722 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 722 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 718 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 718 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 717 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 717 | `npm run lint && npm run mocha` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 717 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 724 | `mocha test.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 724 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 722 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 722 | `mocha` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 721 | `mocha tests/*.mocha.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 718 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 718 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 717 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 717 | `npm run lint && npm run mocha` | 
| [serverless-heaven/serverless-webpack](https://github.com/serverless-heaven/serverless-webpack) | 717 | `nyc ./node_modules/mocha/bin/_mocha tests/all index.test.js "lib/**/*.test.js" -R spec --recursive` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 712 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 711 | `npm run bundle && mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 711 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 710 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 707 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 706 | `mocha` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 705 | `mocha -r should --reporter spec test/*.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 705 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 704 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 702 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 701 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 698 | `mocha` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 697 | `mocha ./test/index.js` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 696 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 696 | `babel-node node_modules/.bin/_mocha -- test` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 693 | `./node_modules/.bin/mocha -t 60000` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 692 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 692 | `mocha --reporter spec build/test/index.js` | 
| [scality/S3](https://github.com/scality/S3) | 691 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 691 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 688 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 688 | `./bin/selenium-standalone install && mocha` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 687 | `mocha --reporter spec` | 
| [dchester/epilogue](https://github.com/dchester/epilogue) | 684 | `npm run-script jshint && npm run-script mocha` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 682 | `mocha ./test/test.js --timeout 1000000` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 681 | `mocha` | 