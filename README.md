# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:45 06/09/18 PDT

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 42028 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 40693 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [expressjs/express](https://github.com/expressjs/express) | 38683 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 29643 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 24102 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 23429 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 22964 | `cross-env NODE_ENV=test mocha` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 22390 | `mocha test/index.js` | 
| [developit/preact](https://github.com/developit/preact) | 19029 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 18444 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 16321 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15933 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 14427 | `node_modules/.bin/mocha test/*.*.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14148 | `nyc --reporter=html --reporter=text mocha` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 13497 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12755 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12499 | `mocha 'test/**/*.spec.js'` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 12423 | `mocha --reporter spec` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 12337 | `./node_modules/.bin/mocha test/` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12154 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 12100 | `mocha --reporter spec test/*-test.js` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 11912 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 11160 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 11059 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 10598 | `mocha --reporter dot` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 10459 | `nyc --reporter=text --reporter lcov npm run test:mocha` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 10010 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9733 | `mocha --harmony` | 
| [reduxjs/redux-devtools](https://github.com/reduxjs/redux-devtools) | 9729 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9712 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9694 | `set NODE_ENV=test && mocha` | 
| [RelaxedJS/ReLaXed](https://github.com/RelaxedJS/ReLaXed) | 9425 | `mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9163 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [reduxjs/redux-thunk](https://github.com/reduxjs/redux-thunk) | 8983 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8851 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8798 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 8781 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 8515 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8387 | `mocha test/test.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 8353 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8299 | `mocha --check-leaks -R dot` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8238 | `mocha test/src` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8223 | `grunt clean:test && mocha --exit` | 
| [amark/gun](https://github.com/amark/gun) | 8179 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 8052 | `mocha tests/*.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8025 | `mocha --compilers js:babel-register test/test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7948 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7784 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7749 | `npm run eslint && npm run mocha` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 7604 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 7590 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [dthree/cash](https://github.com/dthree/cash) | 7516 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7510 | `./node_modules/.bin/mocha test` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7439 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7338 | `npm run build && istanbul cover _mocha` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 7081 | `mocha --opts mocha.opts` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 7073 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [aui/art-template](https://github.com/aui/art-template) | 6898 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6894 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6886 | `eslint lib/**/*.js test/**/*.js index.js && mocha --exit --require should --reporter spec --check-leaks` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6831 | `xo && mocha test/*.js --timeout 100000` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6784 | `mocha $HARMONY_OPTS` | 
| [almende/vis](https://github.com/almende/vis) | 6723 | `mocha --compilers js:babel-core/register` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 6627 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 6313 | `npm run lint -s && npm run mocha -s` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 6172 | `npm run jshint && mocha test/` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 6170 | `mocha test node-test --recursive` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 6159 | `npm run build-cli && mocha` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 6136 | `npm run test:mocha:src` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 6112 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6030 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5935 | `mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5890 | `mocha --exit --require babel-core/register` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5849 | `mocha test/test.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5846 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5162 | `mocha src/**/*Tests.js --harmony` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5152 | `mocha --color` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5112 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4968 | `standard && mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4962 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4935 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4896 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4819 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4715 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4696 | `mocha -R spec 'tests/app'` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4693 | `mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4671 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4658 | `gulp build; mocha;` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4637 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4603 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4579 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 5112 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4968 | `standard && mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4962 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4935 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4896 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4819 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4715 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4696 | `mocha -R spec 'tests/app'` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4693 | `mocha` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4671 | `mocha --reporter spec -t 8000` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4658 | `gulp build; mocha;` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4637 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4603 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 4579 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4556 | `mocha ./test/runner.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4509 | `mocha test` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4500 | `./node_modules/.bin/mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4417 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4366 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4337 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4321 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 4239 | `NODE_ENV=test mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 4222 | `mocha --recursive && make test` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4219 | `mocha -R spec ./test --recursive` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3499 | `mocha --reporter spec --timeout 3000` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 3495 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3484 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3465 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3465 | `nyc mocha "test/**/*.test.js"` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3448 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3437 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3431 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3424 | `mocha` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 3412 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3410 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 3369 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3365 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3353 | `node_modules/.bin/mocha test/tests.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3337 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3289 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 3210 | `NODE_ENV=test mocha test/**/*.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3125 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3123 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3115 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3115 | `./node_modules/.bin/mocha test/test.*.js` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 3097 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 3095 | `yarn tsc && yarn lint && yarn mocha-exclude-redis-cache` | 
| [express-validator/express-validator](https://github.com/express-validator/express-validator) | 3092 | `nyc mocha && tsc` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 3080 | `mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3053 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 3048 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3009 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 3002 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 2995 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2979 | `mocha test/*.js` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2908 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2904 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2889 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2875 | `mocha` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2866 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2847 | `mocha` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2843 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2842 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2837 | `mocha -R spec --recursive src/test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2813 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2777 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2775 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2775 | `mocha --require should --reporter spec` | 
| [github-tools/github](https://github.com/github-tools/github) | 2770 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2763 | `mocha --opts mocha.opts` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2756 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2755 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2751 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2739 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2737 | `mocha` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2777 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2775 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2775 | `mocha --require should --reporter spec` | 
| [github-tools/github](https://github.com/github-tools/github) | 2770 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2769 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2763 | `mocha --opts mocha.opts` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 2756 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2755 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2751 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2739 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2737 | `mocha` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 2725 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2703 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2699 | `npm run mocha && npm run lint` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2681 | `xo && mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2676 | `mocha --require babel-register --recursive spec` | 
| [css/csso](https://github.com/css/csso) | 2673 | `mocha --reporter dot` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2667 | `mocha` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2661 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2626 | `mocha --timeout 100000` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2612 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2603 | `mocha-phantomjs ./test/index.html` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2597 | `node_modules/.bin/mocha --reporter spec` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2590 | `mocha --recursive --watch` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2562 | `mocha -R landing test/index` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2559 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2549 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2547 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2538 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2510 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2496 | `npm run build && cd test && mocha . --reporter dot` | 
| [json5/json5](https://github.com/json5/json5) | 2460 | `nyc --reporter=html --reporter=text mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2459 | `mocha --reporter=spec test/*-test.js` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2450 | `nyc mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2424 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2420 | `mocha test.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2420 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2417 | `mocha test` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2411 | `mocha "test/**/*-test.js"` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2410 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2388 | `mocha test/src/**/*.unit.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2374 | `mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2363 | `mocha test/unit --require mochahook` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2357 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2356 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2341 | `mocha --no-colors --reporter spec` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2339 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2338 | `grunt jshint && mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2303 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2295 | `npm run lint && npm run build:test && npm run build:user && npm run mocha` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2289 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2258 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2256 | `mocha -R spec` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2245 | `nyc --reporter=html --reporter=text mocha` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2244 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2233 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2225 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 2209 | `eslint . && mocha -t 5000` | 
| [gajus/swing](https://github.com/gajus/swing) | 2196 | `mocha --compilers js:babel-register` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 2184 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2182 | `mocha test && npm run lint` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2165 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2157 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [noble/noble](https://github.com/noble/noble) | 2126 | `mocha -R spec test/*.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2110 | `cross-env BABEL_ENV=test mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2094 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2089 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2085 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 2070 | `mocha --compilers js:babel-register` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 2042 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2034 | `mocha test/index.js --reporter dot` | 
| [Qix-/color](https://github.com/Qix-/color) | 2024 | `mocha` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 2018 | `standard && mocha` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 2015 | `mocha test/ --no-timeouts` | 
| [slate/slate](https://github.com/slate/slate) | 2009 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1983 | `mocha test/runner.js --reporter spec` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1971 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [teambit/bit](https://github.com/teambit/bit) | 1970 | `mocha --require babel-core/register './specs/**/*.spec.js'` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1969 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1959 | `mocha -c test/index.js` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1676 | `mocha test/**/*.js` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1662 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1661 | `mocha test -u bdd -R spec` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1650 | `mocha test --timeout 600000` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1642 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1640 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1636 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1628 | `mocha --expose-gc --slow 300` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1626 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1625 | `mocha --compilers js:babel-register` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1619 | `mocha tests/test.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1618 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1612 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1611 | `mocha && size-limit` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1605 | `npm run lint && npm run mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1600 | `mocha test/* --reporter spec` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1595 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1884 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1881 | `nyc npm run _mocha` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1881 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1880 | `mocha --require ./test/common --growl test/expect.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1871 | `mocha && eslint *.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1865 | `mocha tests.js` | 
| [share/sharedb](https://github.com/share/sharedb) | 1861 | `./node_modules/.bin/mocha && npm run jshint` | 
| [then/promise](https://github.com/then/promise) | 1857 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1851 | `npm run lint && mocha -R dot && npm run cover` | 
| [kach/nearley](https://github.com/kach/nearley) | 1839 | `mocha test/*.test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1830 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1821 | `mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1816 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1815 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1807 | `mocha` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1786 | `mocha test` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1785 | `mocha --reporter spec && npm run test-typescript` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1781 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1778 | `rimraf dbtest && npm run lint && SQLPAD_DB_PATH='./dbtest' mocha server/test --timeout 10000 --recursive --exit` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1770 | `mocha -R spec spec spec/reporters` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1769 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1755 | `mocha test` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1752 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [pahen/madge](https://github.com/pahen/madge) | 1742 | `npm run lint && npm run mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1727 | `mocha && npm run lint` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1722 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1719 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1718 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1712 | `mocha --reporter spec test/*.js` | 
| [webpack-contrib/webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) | 1711 | `mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1711 | `npm run lint && npm run mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1709 | `mocha --reporter spec --grep .` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1706 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1705 | `mocha tests --compilers js:babel-core/register` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1703 | `npm run lint && mocha test/unit --recursive && mocha test/runner --recursive` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1692 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1690 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1676 | `mocha test/**/*.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1673 | `xo && mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1662 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1661 | `mocha test -u bdd -R spec` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1653 | `npm run lint && mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1650 | `mocha test --timeout 600000` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1640 | `mocha test/*.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1639 | `mocha ./test/basic.js -t 5000` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1636 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1634 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1628 | `mocha --expose-gc --slow 300` | 
| [Tencent/omi](https://github.com/Tencent/omi) | 1626 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1625 | `mocha --compilers js:babel-register` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1619 | `mocha tests/test.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1618 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1612 | `mocha spec` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1611 | `mocha && size-limit` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1605 | `npm run lint && npm run mocha` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1600 | `mocha test/* --reporter spec` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1597 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1595 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1589 | `mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1589 | `mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1552 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1549 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1543 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1526 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1520 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1517 | `mocha --reporter spec` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1514 | `mocha compiled_tests/` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1514 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1509 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1505 | `npm run test:lint && npm run test:mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1500 | `eslint --cache . && tsc && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1491 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1490 | `standard "./src/*.js" && mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1482 | `node_modules/.bin/mocha --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1481 | `mocha -u tdd` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1453 | `mocha --check-leaks --reporter spec --bail` | 
| [samccone/drool](https://github.com/samccone/drool) | 1449 | `mocha test/tests.js --timeout=10000` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1444 | `mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1439 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1438 | `nyc npm run mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1438 | `mocha` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1435 | `mocha test.js` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1431 | `mocha --recursive` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1396 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1386 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1370 | `./node_modules/mocha/bin/mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1369 | `mocha --timeout 10000 ./tests/lib.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1368 | `mocha test` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1364 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1361 | `mocha -R spec test/*.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1360 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1351 | `cross-env NODE_ENV=test nyc mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1331 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1369 | `mocha --timeout 10000 ./tests/lib.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1368 | `mocha test` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1364 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1361 | `mocha -R spec test/*.js` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1360 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1351 | `cross-env NODE_ENV=test nyc mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1331 | `mocha` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1330 | `npm run build && mocha -r should` | 
| [electron/devtron](https://github.com/electron/devtron) | 1323 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1319 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1006 | `mocha` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1004 | `mocha $(find test -name '*.test.js')` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1001 | `mocha --reporter spec --bail --check-leaks test/` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 998 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 994 | `mocha` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 981 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 979 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 975 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 972 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 971 | `mocha -R list` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 969 | `eslint src test && mocha --compilers babel-register` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 967 | `npm run mocha:istanbul` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 962 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 961 | `mocha --reporter spec` | 
| [intoli/remote-browser](https://github.com/intoli/remote-browser) | 1100 | `npm run build && NODE_ENV=test mocha --exit --require babel-core/register` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1100 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1099 | `mocha $(find test -name '*.test.js')` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1098 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [Tencent/TSW](https://github.com/Tencent/TSW) | 1097 | `mocha --recursive test/bin` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1093 | `mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1092 | `node_modules/.bin/mocha && npm run lint` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1084 | `mocha --check-leaks -t 20000` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1083 | `mocha --compilers js:babel-core/register` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 1082 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 1062 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [ianstormtaylor/permit](https://github.com/ianstormtaylor/permit) | 1058 | `yarn build && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [poooi/poi](https://github.com/poooi/poi) | 1056 | `mocha --recursive --harmony --require ./test/babelhook` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1054 | `istanbul test _mocha` | 
| [router5/router5](https://github.com/router5/router5) | 1053 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1050 | `mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1050 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 1049 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 1048 | `mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 1047 | `webpack && npm run lint && npm run mocha` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1041 | `standard && mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1040 | `mocha --reporter spec --timeout 3000` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1040 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1039 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 1037 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1036 | `mocha test/tests.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1031 | `mocha --recursive --bail --reporter spec test` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1031 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 1028 | `mocha` | 
| [jas/playground](https://github.com/jas/playground) | 1023 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 1023 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 1017 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 1013 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1013 | `mocha --check-leaks -R dot` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 1006 | `mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1005 | `npm run lint && mocha --require @babel/register` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1004 | `mocha $(find test -name '*.test.js')` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1001 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1001 | `mocha --reporter spec --bail --check-leaks test/` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 998 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 998 | `mocha --colors ./test/*.spec.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 994 | `mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 994 | `mocha --reporter spec --bail --check-leaks test/` | 
| [tomas/needle](https://github.com/tomas/needle) | 990 | `mocha test` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 988 | `mocha --recursive test/unit/` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 987 | `standard && mocha -b` | 
| [electron/spectron](https://github.com/electron/spectron) | 984 | `mocha && standard` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 988 | `mocha --recursive test/unit/` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 987 | `standard && mocha -b` | 
| [electron/spectron](https://github.com/electron/spectron) | 984 | `mocha && standard` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 981 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 979 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 978 | `mocha --async-only` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 975 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 972 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 971 | `mocha -R list` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 971 | `npm run rollup-cjs && mocha test/test.js` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 969 | `eslint src test && mocha --compilers babel-register` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 968 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 967 | `npm run mocha:istanbul` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 963 | `mocha --timeout 20000` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 962 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 961 | `mocha --reporter spec` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 953 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 952 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 947 | `mocha --timeout 5000` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 941 | `mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 870 | `mocha` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 866 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 866 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 865 | `mocha -t 600000` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 865 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 865 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 862 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 861 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 861 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 859 | `npm run lint && npm run mocha:no-functional` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 858 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 839 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 839 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 836 | `mocha -t 5000` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 901 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 898 | `mocha -R spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 891 | `mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 890 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 886 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 883 | `mocha tests` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 874 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 871 | `node_modules/.bin/mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 871 | `mocha --reporter list` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 870 | `mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 869 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [tightenco/ziggy](https://github.com/tightenco/ziggy) | 866 | `NODE_ENV=test mocha-webpack 'tests/js/**/*.js'` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 866 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 865 | `mocha -t 600000` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 865 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 865 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 862 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 861 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 861 | `mocha --timeout 200000` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 861 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 860 | `mocha` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 859 | `npm run lint && npm run mocha:no-functional` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 858 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 834 | `mocha --check-leaks -t 20000` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 832 | `nyc mocha specs` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 831 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 831 | `standard && standard ./bin/* && mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 829 | `mocha test --compilers js:babel-core/register` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 829 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 828 | `mocha test --compilers js:babel-register` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 826 | `./node_modules/.bin/mocha -R spec` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 822 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 822 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 822 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 820 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 815 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 814 | `npm run lint && mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 814 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 834 | `mocha --check-leaks -t 20000` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 833 | `mocha --reporter spec` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 832 | `nyc mocha specs` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 831 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 831 | `standard && standard ./bin/* && mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 830 | `istanbul cover _mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 829 | `mocha test --compilers js:babel-core/register` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 829 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 828 | `mocha test --compilers js:babel-register` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 826 | `./node_modules/.bin/mocha -R spec` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 825 | `istanbul cover -- _mocha --reporter spec` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 822 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 822 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 822 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [JoshuaWise/better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) | 820 | `$(npm bin)/mocha --bail --timeout 5000 --slow 5000` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 819 | `mocha && ember test` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 816 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 815 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 809 | `mocha --reporter spec --bail --check-leaks test/` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 808 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 804 | `mocha --reporter list` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 803 | `mocha --require babel-register` | 
| [ConsenSys/eth-lightwallet](https://github.com/ConsenSys/eth-lightwallet) | 801 | `./node_modules/.bin/mocha --reporter spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 800 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 799 | `mocha` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 797 | `mocha --timeout 30000 --recursive ./tests` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 797 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 795 | `mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 795 | `mocha -u tdd` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 794 | `cake build && mocha ./test/mocha/*.coffee` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 794 | `mocha test` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 789 | `./node_modules/.bin/mocha --reporter spec test --recursive` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 789 | `mocha --async-only` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 779 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 775 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 773 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 770 | `mocha test/index.js` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 769 | `nyc --check-coverage mocha test/*.test.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 767 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 766 | `mocha` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 761 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 760 | `mocha --ui tdd --require ./test/__setup` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 773 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 771 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [fex-team/ua-device](https://github.com/fex-team/ua-device) | 770 | `mocha test/index.js` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 770 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 769 | `nyc --check-coverage mocha test/*.test.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 769 | `xo && mocha -R spec` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 767 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 766 | `npm run mocha-test test/integration` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 766 | `mocha` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 763 | `mocha --recursive ./test/*_spec.js` | 
| [webpack-contrib/html-loader](https://github.com/webpack-contrib/html-loader) | 762 | `mocha --harmony --full-trace --check-leaks` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 761 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 760 | `mocha --ui tdd --require ./test/__setup` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 760 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 759 | `mocha test` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 757 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 757 | `mocha` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 755 | `mocha -R spec src/**/*_test.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 754 | `npm run build && istanbul test _mocha test/test.js` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 753 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 751 | `mocha` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 750 | `mocha` | 
| [webpack-contrib/webpack-serve](https://github.com/webpack-contrib/webpack-serve) | 747 | `nyc npm run mocha` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 747 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 746 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 745 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 745 | `mocha --recursive -s 15 test/` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 744 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [developit/decko](https://github.com/developit/decko) | 743 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [edusoho/edusoho](https://github.com/edusoho/edusoho) | 743 | `mocha --recursive --reporter mochawesome --require babel-core/register tests/Js/test && open mochawesome-report/mochawesome.html && npm run test:cover` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 737 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 736 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) | 733 | `node ./node_modules/mocha/bin/_mocha --exit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 733 | `mocha test` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 733 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 732 | `mocha test` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 732 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 731 | `mocha --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 730 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 729 | `mocha --no-timeouts` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 729 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 729 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 725 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 725 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 720 | `npm run lint && npm run mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 718 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 715 | `npm run bundle && mocha` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 714 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [typicode/katon](https://github.com/typicode/katon) | 711 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 710 | `mocha -r should --reporter spec test/*.js` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 710 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 708 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 706 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 706 | `mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 705 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 705 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 706 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 706 | `mocha` | 
| [pantsel/konga](https://github.com/pantsel/konga) | 705 | `mocha` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 705 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 702 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [hughsk/flat](https://github.com/hughsk/flat) | 702 | `mocha -u tdd --reporter spec && standard index.js test/index.js` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 702 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 699 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 698 | `mocha ./test/index.js` | 
| [loganfsmyth/babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) | 696 | `babel-node node_modules/.bin/_mocha -- test` | 
| [scality/S3](https://github.com/scality/S3) | 694 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 694 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 656 | `jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 655 | `./node_modules/.bin/mocha test/integration` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 654 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 654 | `mocha` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 650 | `mocha` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 649 | `mocha --recursive --compilers js:babel-core/register` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 648 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 648 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 645 | `mocha --compilers js:babel-register` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 645 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 643 | `./node_modules/.bin/mocha --bail` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 631 | `mocha --reporter spec` | 
| [PrismarineJS/mineflayer](https://github.com/PrismarineJS/mineflayer) | 630 | `mocha --reporter spec` | 
| [tonyhb/redux-ui](https://github.com/tonyhb/redux-ui) | 628 | `$(npm bin)/mocha  --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 626 | `npm run lint && mocha` | 
| [manavsehgal/reactspeedcoding](https://github.com/manavsehgal/reactspeedcoding) | 625 | `NODE_ENV=test npm run elint && npm run slint && npm run test:mocha` | 
| [catamphetamine/libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js) | 623 | `mocha --require babel-core/register --colors --bail --reporter spec --require ./test/setup.js "source/**/*.test.js" "test/**/*.test.js" --recursive` | 
| [jbrooksuk/node-summary](https://github.com/jbrooksuk/node-summary) | 622 | `mocha --compilers js:babel-core/register --require should --reporter spec` | 
| [leoasis/redux-immutable-state-invariant](https://github.com/leoasis/redux-immutable-state-invariant) | 662 | `mocha --compilers js:babel-core/register` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 661 | `mocha` | 
| [imaya/zlib.js](https://github.com/imaya/zlib.js) | 660 | `npm run test-mocha && npm run test-karma` | 
| [koajs/static](https://github.com/koajs/static) | 660 | `mocha --harmony --reporter spec --exit` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 659 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 658 | `mocha --reporter spec` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 656 | `jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 655 | `./node_modules/.bin/mocha test/integration` | 
| [ForbesLindesay/connect-roles](https://github.com/ForbesLindesay/connect-roles) | 654 | `mocha -R spec` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 654 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [styledown/styledown](https://github.com/styledown/styledown) | 654 | `mocha` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 652 | `mocha` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 650 | `mocha` | 
| [indexiatech/redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) | 649 | `mocha --recursive --compilers js:babel-core/register` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 649 | `mocha --bail test/` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 648 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 648 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 645 | `mocha --compilers js:babel-register` | 
| [calvinmetcalf/lie](https://github.com/calvinmetcalf/lie) | 645 | `npm run jshint && mocha -R nyan ./test/cover.js && tsc --noEmit ./test/types.ts` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 644 | `./node_modules/.bin/mocha` | 
| [strathausen/dracula](https://github.com/strathausen/dracula) | 644 | `mocha --compilers js:babel-register src/**/*.spec.js src/*.spec.js` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 643 | `./node_modules/.bin/mocha --bail` | 
| [shime/livedown](https://github.com/shime/livedown) | 639 | `node node_modules/.bin/standard test/* server.js bin/livedown utils.js public/client.js && node ./node_modules/.bin/mocha` | 