# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:05 03/05/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39912 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 39643 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 36950 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28890 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23474 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 22327 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 20916 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 19971 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 17917 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17633 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15652 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15008 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13854 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 13261 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12756 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12179 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12130 | `mocha 'test/**/*.spec.js'` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12022 | `mocha` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11772 | `./node_modules/.bin/mocha test/` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11736 | `mocha --reporter spec test/*-test.js` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 11467 | `cross-env BABEL_ENV=test NODE_ENV=test mocha --recursive --require babel-register --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11190 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10670 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 10656 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10124 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9756 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9639 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9371 | `mocha test/index.js` | 
| [tj/co](https://github.com/tj/co) | 9369 | `mocha --harmony` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9329 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9177 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9125 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8922 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8598 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8431 | `mocha test/*-test.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8392 | `mocha` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8174 | `mocha --check-leaks -R dot` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8154 | `mocha test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8095 | `grunt clean:test && mocha --exit` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 8071 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7900 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7858 | `./node_modules/.bin/mocha test/src` | 
| [websockets/ws](https://github.com/websockets/ws) | 7830 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7775 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7742 | `mocha --compilers js:babel-register test/test.js` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7576 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [amark/gun](https://github.com/amark/gun) | 7533 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7453 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7436 | `mocha` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7377 | `npm run eslint && npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7332 | `mocha tests/*.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7179 | `npm run build && istanbul cover _mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7160 | `./node_modules/.bin/mocha test` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6988 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6961 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6714 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6572 | `mocha $HARMONY_OPTS` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6532 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6482 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6443 | `mocha --opts mocha.opts` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6438 | `nyc mocha test/**/* -r ./test/before` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6426 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6349 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6335 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [almende/vis](https://github.com/almende/vis) | 6326 | `mocha --compilers js:babel-core/register` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5973 | `npm run jshint -s && npm run mocha -s` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5922 | `mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5866 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5837 | `npm run test:mocha:src` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5832 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5740 | `npm run jshint && mocha test/` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5595 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5510 | `mocha tests/node.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5491 | `mocha test --recursive` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5409 | `mocha && eslint lib/**` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5389 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5383 | `mocha test/test.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5374 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5199 | `mocha --exit --require babel-core/register` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5164 | `mocha --color` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5140 | `mocha --timeout 10000 && npm run lint` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5138 | `mocha src/**/*Tests.js --harmony` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5017 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 4983 | `mocha` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 4870 | `npm run build-cli && mocha` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4783 | `gulp lint && mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4770 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4745 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4734 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4634 | `mocha test` | 
| [redux-utilities/redux-actions](https://github.com/redux-utilities/redux-actions) | 4633 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4621 | `mocha --reporter spec -t 8000` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4615 | `mocha -R spec 'tests/app'` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4534 | `mocha ./test/runner.js` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4509 | `standard && mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4508 | `gulp build; mocha;` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4432 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4418 | `mocha` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4409 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4395 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4353 | `./node_modules/.bin/mocha` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4330 | `mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4314 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 4298 | `mocha; jshint *.js lib` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4223 | `mocha -R spec ./test --recursive` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4221 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4210 | `mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4206 | `mocha test` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4190 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 4091 | `mocha && ./bin/shipit staging test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4010 | `nyc mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3923 | `mocha --recursive && make test` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3907 | `mocha --require test/babel-hook test/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3896 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [muicss/mui](https://github.com/muicss/mui) | 3862 | `mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3852 | `NODE_ENV=test mocha` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3850 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3807 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [tj/ejs](https://github.com/tj/ejs) | 3796 | `mocha --require should --reporter spec` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3791 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3769 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3669 | `nyc mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3638 | `npm run jshint && npm run mocha` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3626 | `npm run lint ; mocha && mocha test/individual` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3614 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3575 | `mocha ./test/*.spec.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3559 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3549 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3537 | `mocha tests/javascript` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3526 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3498 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3484 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [primus/primus](https://github.com/primus/primus) | 3481 | `npm run build && mocha test/*.test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3455 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3437 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3400 | `node_modules/.bin/mocha test/lib/` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3400 | `node_modules/.bin/mocha` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3398 | `mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3360 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3356 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3328 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3323 | `npm run lint && npm run mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3280 | `mocha --check-leaks --reporter spec --bail` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3213 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3169 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3167 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3144 | `nyc mocha "test/**/*.test.js"` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3115 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 3104 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3101 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3072 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3065 | `./node_modules/.bin/mocha test/test.*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3048 | `node_modules/.bin/mocha test/tests.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3001 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2975 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2969 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2967 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2962 | `mocha` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2930 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2911 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2887 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2850 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 2835 | `NODE_ENV=test mocha test/**/*.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2789 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2789 | `nyc mocha && tsc` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2782 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2764 | `mocha -R spec --recursive src/test` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2759 | `mocha --require should --reporter spec` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2756 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2756 | `mocha` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2753 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2744 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2742 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2742 | `mocha test/index.js && npm run demo` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2735 | `istanbul cover _mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2734 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2720 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2702 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2688 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2675 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2669 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2668 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2654 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2650 | `mocha` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2633 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2633 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2631 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2626 | `xo && mocha` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2608 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2604 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2602 | `mocha --opts mocha.opts` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2598 | `mocha --timeout 100000` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2592 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2583 | `mocha-phantomjs ./test/index.html` | 
| [css/csso](https://github.com/css/csso) | 2577 | `mocha --reporter dot` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2565 | `npm run mocha && npm run lint` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2536 | `mocha` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2529 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2522 | `mocha --recursive --watch` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2516 | `mocha --compilers js:babel-register --recursive spec` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2507 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2497 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2490 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2464 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2454 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2427 | `mocha --reporter=spec test/*-test.js` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2422 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2417 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2403 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2386 | `NODE_ENV=test mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2381 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2366 | `node node_modules/mocha/bin/_mocha` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2358 | `node_modules/.bin/mocha --reporter spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2346 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2344 | `nyc mocha test/mocha-node-setup.js 'test/**/*-test.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2338 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2331 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2329 | `grunt jshint && mocha` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2325 | `nyc mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2322 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2315 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2312 | `npm run build && cd test && mocha . --reporter dot` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2311 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2300 | `mocha test` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2260 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [json5/json5](https://github.com/json5/json5) | 2260 | `mocha --ui exports --reporter spec` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2223 | `mocha test test/unit/**/*_test.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2215 | `mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2215 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2214 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2210 | `mocha test/unit --require mochahook` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2210 | `mocha "test/**/*-test.js"` | 
| [mde/ejs](https://github.com/mde/ejs) | 2204 | `mocha --require should --reporter spec` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2202 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2200 | `npm run lint && npm run build && npm run mocha` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 2193 | `npm run lint && mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2190 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2173 | `mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2167 | `mocha -R spec` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2158 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [gajus/swing](https://github.com/gajus/swing) | 2140 | `mocha --compilers js:babel-register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2082 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2072 | `nyc --reporter=html --reporter=text mocha` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2070 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2064 | `cross-env BABEL_ENV=test mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2043 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2041 | `mocha test.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2041 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [slate/slate](https://github.com/slate/slate) | 2015 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [noble/noble](https://github.com/noble/noble) | 2008 | `mocha -R spec test/*.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2002 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1998 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1997 | `mocha -R landing test/index` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1950 | `mocha test && npm run lint` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1930 | `mocha --require=test/test_helper.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1924 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1917 | `standard && mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1906 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1900 | `mocha --bail --reporter spec --check-leaks test/` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1893 | `mocha test/index.js --reporter dot` | 
| [Qix-/color](https://github.com/Qix-/color) | 1887 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1885 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1884 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1878 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1863 | `mocha --compilers js:babel-register` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1851 | `mocha --require ./test/common --growl test/expect.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1851 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1846 | `mocha tests.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1842 | `mocha --reporter spec --timeout 5000` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1819 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1814 | `mocha test/runner.js --reporter spec` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1809 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1803 | `mocha --timeout 5000` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1797 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1790 | `cross-env NODE_ENV=test mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1790 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [then/promise](https://github.com/then/promise) | 1782 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1776 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1775 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1768 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1766 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1766 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1762 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1750 | `mocha test` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1748 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [kach/nearley](https://github.com/kach/nearley) | 1744 | `mocha test/*.test.js` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1738 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1737 | `mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1735 | `mocha test/**/*_test.js --bail` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1723 | `npm run lint && mocha -R dot && npm run cover` | 
| [share/sharedb](https://github.com/share/sharedb) | 1722 | `./node_modules/.bin/mocha && npm run jshint` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1716 | `npm run lint && mocha --reporter spec test/*.js` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1716 | `mocha && eslint *.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1715 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1711 | `mocha test` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1706 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1705 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1692 | `mocha -R spec spec spec/reporters` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1689 | `mocha` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1688 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1687 | `npm run jshint && mocha --recursive` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1684 | `npm run mocha && npm run karma` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1684 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1683 | `npm run lint && mocha server/test --recursive --exit` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1679 | `mocha --reporter spec && npm run test-typescript` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1670 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1667 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1666 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1665 | `mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1660 | `nyc npm run _mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1656 | `npm run lint && npm run mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1640 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1613 | `mocha tests/test.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1609 | `mocha && npm run lint` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1604 | `mocha --expose-gc --slow 300` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1603 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1603 | `mocha` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1603 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1595 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1589 | `mocha --reporter spec --grep .` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1582 | `npm run mocha && npm run lint` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1580 | `mocha test/*.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1576 | `npm run lint && mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1574 | `mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1571 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1568 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1568 | `mocha tests --compilers js:babel-core/register` | 
| [pahen/madge](https://github.com/pahen/madge) | 1566 | `npm run lint && npm run mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1554 | `mocha test -u bdd -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1552 | `mocha test/**/*.js` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1548 | `./node_modules/.bin/mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1543 | `mocha ./test/basic.js -t 5000` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1537 | `mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1532 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1530 | `mocha spec` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1524 | `mocha --reporter spec test/*.js` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1519 | `mocha test --timeout 600000` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1504 | `standard "src/*.js" && npm run build && mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1504 | `mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1499 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1495 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1494 | `npm run lint && npm run mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1481 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1480 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1480 | `npm run test:lint && npm run test:mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1471 | `mocha -R spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1469 | `mocha -u tdd` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1455 | `node_modules/.bin/mocha --recursive` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1450 | `mocha --reporter spec` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1438 | `mocha --compilers js:babel-register` | 
| [samccone/drool](https://github.com/samccone/drool) | 1436 | `mocha test/tests.js --timeout=10000` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1430 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1418 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1406 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1406 | `mocha test.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1399 | `eslint --cache . && tsc && mocha` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1398 | `nyc mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1395 | `mocha --check-leaks -R dot` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1392 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1390 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1390 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1386 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1380 | `mocha test.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1374 | `standard "./src/*.js" && mocha` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1367 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1367 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1355 | `mocha --recursive` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1351 | `./node_modules/mocha/bin/mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1344 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1339 | `mocha tests.js` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1331 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1329 | `eslint . && mocha -t 5000` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1328 | `mocha --check-leaks --reporter spec --bail` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1327 | `cross-env NODE_ENV=test nyc mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1326 | `istanbul cover _mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1321 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1319 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1304 | `mocha compiled_tests/` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1302 | `mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1293 | `mocha-phantomjs tests/index.html` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1291 | `mocha test/setup.js test/spec/*.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1289 | `mocha --timeout 10000 ./tests/lib.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1286 | `nyc npm run mocha` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1284 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1283 | `mocha -R spec test/*.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1279 | `npm run build && mocha -r should` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1261 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1258 | `./node_modules/.bin/mocha test` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1247 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1247 | `mocha spec/exec.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1242 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1240 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1240 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1234 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1232 | `istanbul cover _mocha test -- --timeout 20000` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1218 | `mocha test/*.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1214 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1213 | `mocha tests` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1207 | `mocha test/test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1206 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1203 | `mocha --check-leaks --require @babel/register` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1202 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1200 | `mocha --recursive` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1198 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1194 | `mocha` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1192 | `mocha test/**/*Spec.js` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1188 | `mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1187 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1186 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1185 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1185 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1179 | `mocha --opts test/opts/mocha.opts` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1171 | `mocha test` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1170 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1163 | `node ./node_modules/mocha/bin/mocha tests` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1162 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1158 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1156 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1147 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1144 | `mocha` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1140 | `mocha` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1138 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1126 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1121 | `mocha test/unit` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1120 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1120 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1119 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1116 | `mocha` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1115 | `standard && istanbul cover _mocha` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1114 | `mocha --reporter dot` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1113 | `npm run lint && npm run mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1113 | `mocha --reporter spec` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1109 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1108 | `mocha src/test.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1107 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [variety/variety](https://github.com/variety/variety) | 1106 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1106 | `node_modules/.bin/mocha` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1100 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1099 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1098 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1096 | `mocha test` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1096 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1095 | `eslint src && mocha && karma start --single-run` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1089 | `node_modules/.bin/mocha && npm run lint` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1085 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1078 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1078 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1077 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [teambit/bit](https://github.com/teambit/bit) | 1077 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1073 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1073 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1070 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1068 | `mocha --compilers js:babel-register` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1066 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1065 | `mocha test/*` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1064 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1063 | `mocha $(find test -name '*.test.js')` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1058 | `xo && mocha` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1050 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1047 | `mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1044 | `mocha --reporter spec --timeout 3000` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1044 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1044 | `mocha --check-leaks --reporter spec --bail test/` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1041 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1035 | `istanbul test _mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1034 | `nyc mocha --timeout=20000 test.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1034 | `mocha tests/test-*` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1026 | `NODE_PATH=. mocha **/*.spec.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1022 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1021 | `istanbul cover _mocha test/*.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1020 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1017 | `mocha --check-leaks -R dot` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1013 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1012 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1011 | `mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1010 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1006 | `mocha test/tests.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 997 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 992 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 989 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 989 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 987 | `mocha` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 984 | `mocha --colors ./test/*.spec.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 983 | `mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 981 | `standard && mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 979 | `npm run prepublishOnly && mocha test/test.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 976 | `mocha --recursive --bail --reporter spec test` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 974 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 971 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 967 | `npm run rollup-cjs && mocha test/test.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 963 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 958 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 957 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 957 | `mocha --recursive test/unit/` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 957 | `mocha -R list` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 957 | `mocha --recursive test` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 955 | `mocha --timeout 5000` | 
| [router5/router5](https://github.com/router5/router5) | 953 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 952 | `mocha $(find test -name '*.test.js')` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 949 | `mocha --async-only` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 947 | `mocha --compilers js:babel-core/register` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 945 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 945 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 945 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 943 | `mocha --reporter spec` | 
| [tomas/needle](https://github.com/tomas/needle) | 942 | `mocha test` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 940 | `mocha -t 120000 test/*.test.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 936 | `standard && mocha -b` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 934 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 931 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 931 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 930 | `webpack && mocha test/unit` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 927 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 921 | `mocha -R spec ./test/unit/**` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 921 | `mocha --reporter spec --bail --check-leaks test/` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 918 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 917 | `mocha ./test/test*.js --reporter spec` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 912 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 909 | `mocha` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 909 | `mocha spec/*.spec.js` | 
| [electron/asar](https://github.com/electron/asar) | 909 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [electron/spectron](https://github.com/electron/spectron) | 908 | `mocha && standard` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 907 | `mocha ./test/index.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 906 | `mocha --reporter spec --bail --check-leaks test/` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 905 | `mocha tests/*.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 901 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 899 | `nyc mocha --require @babel/register` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 896 | `eslint src test && mocha --compilers babel-register` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 893 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 891 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 889 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 889 | `./node_modules/.bin/mocha --globals angular,require` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 885 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 884 | `mocha "client.test" --compilers js:babel-register` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 883 | `mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 883 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 881 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 881 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 873 | `npm run lint && npm run mocha` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 873 | `npm run lint && npm run mocha` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 873 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 871 | `mocha --compilers js:babel-register test/*.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 871 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 869 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 866 | `mocha --reporter list` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 863 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 861 | `mocha --reporter spec --bail --check-leaks test/` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 860 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 858 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 858 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 858 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 856 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 852 | `node_modules/.bin/mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 851 | `npm run convertto:es5 && npm run mocha` | 
| [reactivestack/cookies](https://github.com/reactivestack/cookies) | 851 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 848 | `mocha ./test -R spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 848 | `mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 846 | `npm run lint && mocha -R spec` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 845 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 839 | `npm run lint && mocha --compilers js:babel-register` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 838 | `npm run lint && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 836 | `mocha --timeout 200000` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 836 | `eslint test && mocha --compilers js:babel/register` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 835 | `mocha tests` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 833 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 833 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 832 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 829 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 825 | `node_modules/.bin/mocha test/spec` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 825 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 818 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 818 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 818 | `mocha && ember test` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 816 | `mocha -R spec` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 815 | `mocha --reporter spec` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 815 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 813 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 805 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 805 | `mocha --check-leaks -t 20000` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 803 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 803 | `mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 799 | `istanbul cover _mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 796 | `mocha -t 600000` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 795 | `standard && standard ./bin/* && mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 794 | `mocha --require babel-register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 792 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 791 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 791 | `mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 791 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 791 | `mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 789 | `mocha -t 5000` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 788 | `mocha --reporter spec --bail --check-leaks test/` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 788 | `mocha test --compilers js:babel-register` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 787 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 785 | `cake build && mocha ./test/mocha/*.coffee` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 782 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 781 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 780 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 779 | `istanbul cover -- _mocha --reporter spec` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 777 | `nyc mocha specs` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 777 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [edsu/anon](https://github.com/edsu/anon) | 776 | `mocha --colors --reporter spec test.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 771 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 770 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 768 | `mocha` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 765 | `mocha` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 765 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 764 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 764 | `npm run lint && mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 763 | `mocha --async-only` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 763 | `mocha spec/*.js` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 762 | `./node_modules/.bin/mocha -R spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 762 | `mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 761 | `mocha --reporter list` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 761 | `xo && mocha -R spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 756 | `npm run mocha:istanbul` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 753 | `mocha --ui tdd --require ./test/__setup` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 750 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 748 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 746 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 741 | `mocha -R spec src/**/*_test.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 739 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [bitpay/insight](https://github.com/bitpay/insight) | 734 | `mocha test` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 733 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 730 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 729 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 729 | `mocha --reporter spec` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 726 | `mocha --recursive -s 15 test/` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 725 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 725 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 724 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 724 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 722 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 721 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 721 | `mocha test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 714 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 712 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 712 | `npm run mocha-test test/integration` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 711 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 709 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [3Dparallax/insight](https://github.com/3Dparallax/insight) | 709 | `mocha test` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 708 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [developit/decko](https://github.com/developit/decko) | 704 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 704 | `mocha tests/*.mocha.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 703 | `mocha` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 703 | `mocha test` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 703 | `npm run build && istanbul test _mocha test/test.js` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 703 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 701 | `npm run bundle && mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 699 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 696 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 695 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 693 | `mocha` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 692 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 691 | `mocha test` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 688 | `mocha` | 