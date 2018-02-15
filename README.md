# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:59 02/15/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39752 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 39282 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 37099 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation` | 
| [expressjs/express](https://github.com/expressjs/express) | 36638 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28784 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23376 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 22132 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 20683 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 19054 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 17675 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17513 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15564 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14838 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13790 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 13043 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12659 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12056 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12031 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11996 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11685 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11666 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 11234 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10958 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10575 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 10443 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9953 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9631 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9477 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 9309 | `mocha --harmony` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9249 | `mocha test/index.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9237 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9110 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9006 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8874 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8522 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8371 | `mocha test/*-test.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8293 | `mocha` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8141 | `mocha --check-leaks -R dot` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8129 | `mocha test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8073 | `grunt clean:test && mocha --exit` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7891 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7825 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7783 | `./node_modules/.bin/mocha test/src` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7735 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7686 | `mocha --compilers js:babel-register test/test.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 7669 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7438 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7435 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7431 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 7380 | `mocha` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7335 | `npm run eslint && npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7225 | `mocha tests/*.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7152 | `npm run build && istanbul cover _mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7105 | `./node_modules/.bin/mocha test` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6868 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6811 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6593 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6550 | `mocha $HARMONY_OPTS` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6490 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6430 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6351 | `mocha --opts mocha.opts` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6342 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6300 | `nyc mocha test/**/* -r ./test/before` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6253 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [almende/vis](https://github.com/almende/vis) | 6244 | `mocha --compilers js:babel-core/register` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6188 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5941 | `npm run jshint -s && npm run mocha -s` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5923 | `mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5831 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5782 | `npm run test:mocha:src` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5703 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5685 | `npm run jshint && mocha test/` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5486 | `mocha tests/node.js` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5479 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5440 | `mocha test --recursive` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5386 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5364 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5329 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5316 | `mocha test/test.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5161 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5137 | `mocha src/**/*Tests.js --harmony` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5109 | `mocha --timeout 10000 && npm run lint` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5078 | `mocha --exit --require babel-core/register` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4988 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4974 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4768 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4736 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4687 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4660 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [santinic/how2](https://github.com/santinic/how2) | 4624 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4609 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4607 | `mocha --reporter spec -t 8000` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4563 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 4536 | `npm run build-cli && mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4535 | `mocha ./test/runner.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4455 | `gulp build; mocha;` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4422 | `standard && mocha` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 4395 | `mocha` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4389 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4385 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4375 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4333 | `mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4330 | `./node_modules/.bin/mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4319 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4259 | `mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4221 | `mocha -R spec ./test --recursive` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4193 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4191 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4151 | `mocha test` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4108 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 4066 | `mocha && ./bin/shipit staging test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3997 | `nyc mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 3932 | `mocha; jshint *.js lib` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3891 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3856 | `mocha --require test/babel-hook test/*.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3848 | `export TESTING=true; mocha --reporter list` | 
| [muicss/mui](https://github.com/muicss/mui) | 3824 | `mocha` | 
| [erming/shout](https://github.com/erming/shout) | 3816 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3802 | `NODE_ENV=test mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3783 | `mocha --require should --reporter spec` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3740 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3723 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3639 | `npm run jshint && npm run mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3635 | `nyc mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3607 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3594 | `npm run lint ; mocha && mocha test/individual` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3550 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3543 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3529 | `mocha tests/javascript` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3462 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [primus/primus](https://github.com/primus/primus) | 3458 | `npm run build && mocha test/*.test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3450 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3428 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3398 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3395 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3390 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3388 | `node_modules/.bin/mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3377 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3345 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3281 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3280 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3217 | `mocha --check-leaks --reporter spec --bail` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3196 | `npm run lint && npm run mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3191 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3175 | `mocha ./test/*.spec.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3128 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3123 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3095 | `mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3079 | `nyc mocha "test/**/*.test.js"` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3076 | `yarn run build:cjs && mocha --require babel-core/register ./test/index.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3070 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3061 | `./node_modules/.bin/mocha test/test.*.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 3056 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3018 | `node_modules/.bin/mocha test/tests.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2966 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2963 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2939 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2932 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2924 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2871 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2864 | `mocha test/*.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2850 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2828 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 2784 | `NODE_ENV=test mocha test/**/*.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2773 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2768 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2757 | `mocha --require should --reporter spec` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2742 | `mocha -R spec --recursive src/test` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2742 | `mocha` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2731 | `nyc mocha && tsc` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2719 | `istanbul cover _mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2718 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2717 | `mocha test/index.js && npm run demo` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2705 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2695 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2688 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2669 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2669 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [tj/should.js](https://github.com/tj/should.js) | 2666 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2662 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2647 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2647 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2638 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2628 | `mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2616 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2609 | `xo && mocha` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2606 | `mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2600 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2595 | `mocha --timeout 100000` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2595 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2578 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2577 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2576 | `mocha-phantomjs ./test/index.html` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2574 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2572 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2564 | `mocha --opts mocha.opts` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2545 | `npm run mocha && npm run lint` | 
| [css/csso](https://github.com/css/csso) | 2541 | `mocha --reporter dot` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2517 | `export TESTING=true; mocha --reporter list` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2516 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2505 | `mocha --recursive --watch` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2498 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2488 | `mocha --compilers js:babel-register --recursive spec` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2485 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2458 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2447 | `mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2437 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2422 | `mocha --reporter=spec test/*-test.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2406 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2394 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2375 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2367 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2334 | `NODE_ENV=test mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2333 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2327 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2323 | `grunt jshint && mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2321 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2316 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2311 | `node_modules/.bin/mocha --reporter spec` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2304 | `nyc mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2296 | `nyc mocha 'test/**/*-test.js'` | 
| [mozilla/send](https://github.com/mozilla/send) | 2290 | `mocha test/unit` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2290 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2289 | `mocha test/src/**/*.unit.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2277 | `npm run build && cd test && mocha . --reporter dot` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2260 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2256 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [json5/json5](https://github.com/json5/json5) | 2237 | `mocha --ui exports --reporter spec` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2220 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2217 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2211 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2198 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2198 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2182 | `mocha test/unit --require mochahook` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2178 | `npm run lint && npm run build && npm run mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2176 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2172 | `mocha "test/**/*-test.js"` | 
| [mde/ejs](https://github.com/mde/ejs) | 2157 | `mocha --require should --reporter spec` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2152 | `mocha -R spec` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2135 | `mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2134 | `mocha --compilers js:babel-register` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2129 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2105 | `export TESTING=true; mocha --reporter list` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2082 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2051 | `cross-env BABEL_ENV=test mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2045 | `nyc --reporter=html --reporter=text mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2036 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2027 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2019 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [slate/slate](https://github.com/slate/slate) | 2018 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [noble/noble](https://github.com/noble/noble) | 1991 | `mocha -R spec test/*.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1975 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1971 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1967 | `mocha test.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1947 | `mocha -R landing test/index` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1927 | `mocha --require=test/test_helper.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1915 | `mocha test && npm run lint` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1903 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1901 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1900 | `mocha --bail --reporter spec --check-leaks test/` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1889 | `mocha -c test/index.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1884 | `mocha test/index.js --reporter dot` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1881 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Qix-/color](https://github.com/Qix-/color) | 1865 | `mocha` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1860 | `mocha` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1846 | `mocha --require ./test/common --growl test/expect.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1839 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1836 | `mocha tests.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1836 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1832 | `mocha --reporter spec --timeout 5000` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1824 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1821 | `mocha --compilers js:babel-register` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1804 | `mocha --timeout 5000` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1793 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1789 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1789 | `mocha test/runner.js --reporter spec` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1784 | `cross-env NODE_ENV=test mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1772 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 1767 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1760 | `mocha --compilers js:babel-core/register __tests__` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1754 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1750 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1749 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1749 | `mocha test` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1748 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1745 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1737 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [kach/nearley](https://github.com/kach/nearley) | 1726 | `mocha test/*.test.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1723 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1710 | `mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1703 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1701 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 1701 | `./node_modules/.bin/mocha && npm run jshint` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1699 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1699 | `mocha test` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1699 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1698 | `mocha && eslint *.js` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1695 | `npm run lint && mocha -R dot && npm run cover` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1688 | `mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1671 | `npm run lint && mocha server/test --recursive --exit` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1667 | `./node_modules/mocha/bin/mocha -R spec` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1662 | `./node_modules/.bin/mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1662 | `mocha` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1659 | `npm run mocha && npm run karma` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1659 | `mocha --reporter spec && npm run test-typescript` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1659 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1657 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1650 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1645 | `mocha -R spec spec spec/reporters` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1643 | `npm run lint && npm run mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1624 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1624 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1618 | `nyc npm run _mocha` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1609 | `mocha tests/test.js` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1604 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1604 | `mocha --expose-gc --slow 300` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1603 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1600 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1596 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1592 | `mocha && npm run lint` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1576 | `mocha test/*.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1570 | `mocha` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1564 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1563 | `mocha --reporter spec --grep .` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1561 | `npm run mocha && npm run lint` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1561 | `npm run lint && mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1556 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1554 | `mocha tests --compilers js:babel-core/register` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1552 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1545 | `./node_modules/.bin/mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1541 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [pahen/madge](https://github.com/pahen/madge) | 1539 | `npm run lint && npm run mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1535 | `mocha test -u bdd -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1528 | `mocha test/` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1525 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1520 | `mocha ./test/basic.js -t 5000` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1517 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1515 | `mocha spec` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1499 | `mocha --reporter spec test/*.js` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1498 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1495 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1489 | `mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1476 | `npm run lint && npm run mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1476 | `./node_modules/mocha/bin/mocha -R spec` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1475 | `npm run test:lint && npm run test:mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1474 | `mocha test --timeout 600000` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1471 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1467 | `mocha -R spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1464 | `mocha -u tdd` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1456 | `standard "src/*.js" && npm run build && mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1448 | `node_modules/.bin/mocha --recursive` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1441 | `mocha --reporter spec` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1434 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1432 | `mocha test/tests.js --timeout=10000` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1423 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1413 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1411 | `mocha --compilers js:babel-register` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1403 | `mocha test.js` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1385 | `nyc mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1383 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1383 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1381 | `mocha --check-leaks -R dot` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1379 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1378 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1373 | `eslint --cache . && tsc && mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1366 | `mocha test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1362 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1360 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1356 | `standard "./src/*.js" && mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1348 | `./node_modules/mocha/bin/mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1347 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1339 | `mocha --recursive` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1326 | `cross-env NODE_ENV=test nyc mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1323 | `mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1321 | `istanbul cover _mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1318 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1316 | `mocha tests.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1302 | `mocha --check-leaks --reporter spec --bail` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1299 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1290 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1289 | `mocha-phantomjs tests/index.html` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1281 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1278 | `mocha --timeout 10000 ./tests/lib.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1277 | `eslint . && mocha -t 5000` | 
| [noble/bleno](https://github.com/noble/bleno) | 1276 | `mocha -R spec test/*.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1274 | `npm run build && mocha -r should` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1261 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1260 | `mocha compiled_tests/` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1255 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1253 | `./node_modules/.bin/mocha test` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1253 | `mocha test/setup.js test/spec/*.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1243 | `mocha spec/exec.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1238 | `npm run lint && npm run mocha` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1237 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [electron/devtron](https://github.com/electron/devtron) | 1232 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1224 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1222 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1222 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1213 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1213 | `istanbul cover _mocha test -- --timeout 20000` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1211 | `mocha tests` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1209 | `mocha test/*.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1205 | `mocha test/test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1203 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1197 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1192 | `mocha test/**/*Spec.js` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1192 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1186 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1185 | `mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1182 | `mocha --recursive` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1181 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1180 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1175 | `mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1172 | `mocha --check-leaks --require @babel/register` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1170 | `mocha test` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1167 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1163 | `mocha --opts test/opts/mocha.opts` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1160 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1154 | `node ./node_modules/mocha/bin/mocha tests` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1149 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1148 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1146 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1138 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1125 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1120 | `mocha` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1117 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1111 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1110 | `npm run lint && npm run mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1108 | `mocha --reporter spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1100 | `mocha src/test.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1100 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [variety/variety](https://github.com/variety/variety) | 1100 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1094 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1094 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1093 | `mocha test/unit` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1093 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1093 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1092 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1091 | `mocha --reporter dot` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1091 | `standard && istanbul cover _mocha` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1089 | `node_modules/.bin/mocha && npm run lint` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1088 | `node_modules/.bin/mocha` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1083 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1081 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1081 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1080 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1078 | `eslint src && mocha && karma start --single-run` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1074 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1067 | `mocha --check-leaks -t 20000` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1066 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1065 | `mocha --compilers js:babel-register` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1064 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1061 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1061 | `mocha test/*` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1057 | `mocha $(find test -name '*.test.js')` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1053 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1049 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1049 | `xo && mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1047 | `mocha --reporter spec --timeout 3000` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1045 | `mocha test` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1040 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1034 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1033 | `istanbul test _mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1031 | `mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1029 | `mocha --check-leaks --reporter spec --bail test/` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1025 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1020 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1016 | `NODE_PATH=. mocha **/*.spec.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1015 | `mocha --check-leaks -R dot` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1012 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1010 | `istanbul cover _mocha test/*.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1006 | `mocha tests/test-*` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1002 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 999 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 998 | `mocha test/tests.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 997 | `mocha` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 991 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 987 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 985 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 985 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 983 | `mocha --colors ./test/*.spec.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [teambit/bit](https://github.com/teambit/bit) | 982 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 980 | `mocha` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 975 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 972 | `mocha --recursive --bail --reporter spec test` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 971 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 971 | `nyc mocha --timeout=20000 test.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 970 | `npm run prepublish && mocha test/test.js` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 968 | `standard && mocha` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 960 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 960 | `npm run rollup-cjs && mocha test/test.js` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 959 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 957 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 954 | `mocha --timeout 5000` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 953 | `mocha -R list` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 950 | `mocha $(find test -name '*.test.js')` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 947 | `mocha --recursive test/unit/` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 946 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [router5/router5](https://github.com/router5/router5) | 946 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 945 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 943 | `mocha --async-only` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 942 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 940 | `mocha` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 938 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 937 | `mocha --reporter spec` | 
| [tomas/needle](https://github.com/tomas/needle) | 936 | `mocha test` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 933 | `mocha -t 120000 test/*.test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 932 | `mocha --recursive test` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 930 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 928 | `mocha --compilers js:babel-core/register` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 928 | `standard && mocha -b` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 924 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 922 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 914 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 912 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 912 | `webpack && mocha test/unit` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 905 | `nyc mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 902 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [electron/asar](https://github.com/electron/asar) | 898 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 896 | `mocha` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 894 | `mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 891 | `mocha --reporter spec --bail --check-leaks test/` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 890 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 886 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 885 | `nyc mocha --require @babel/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 882 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 877 | `mocha` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 876 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 876 | `mocha "client.test" --compilers js:babel-register` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 875 | `mocha ./test/test*.js --reporter spec` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 875 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 873 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 871 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [electron/spectron](https://github.com/electron/spectron) | 869 | `mocha && standard` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 867 | `mocha --compilers js:babel-register test/*.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 865 | `mocha --reporter list` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 862 | `mocha -R spec ./test/unit/**` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 860 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 860 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 858 | `mocha tests/*.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 857 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 856 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 853 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 850 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 848 | `node_modules/.bin/mocha` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 845 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 845 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 844 | `mocha --reporter spec --bail --check-leaks test/` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 843 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 842 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 841 | `npm run convertto:es5 && npm run mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 839 | `npm run lint && mocha -R spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 839 | `mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 838 | `eslint test && mocha --compilers js:babel/register` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 835 | `npm run lint && npm run mocha` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 831 | `mocha ./test -R spec` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 829 | `mocha tests` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 829 | `mocha --timeout 200000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 825 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 825 | `mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 824 | `npm run lint && mocha --compilers js:babel-register` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 824 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 820 | `node_modules/.bin/mocha test/spec` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 819 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffeescript --recursive regression/node-helper.coffee regression/src` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 818 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 816 | `mocha && ember test` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 815 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 814 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 813 | `mocha --reporter spec` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 812 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 803 | `mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 802 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 802 | `mocha --check-leaks -t 20000` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 798 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 797 | `istanbul cover _mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 797 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 795 | `mocha -R spec` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 795 | `eslint src test && mocha --compilers babel-register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 793 | `mocha --require babel-register` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 791 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 791 | `mocha -R spec tests/` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 791 | `standard && standard ./bin/* && mocha` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 788 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 788 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 787 | `mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 785 | `nyc mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 785 | `mocha -t 5000` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 782 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 779 | `mocha -t 600000` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 779 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 777 | `mocha` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 777 | `mocha test --compilers js:babel-register` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 776 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 775 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 774 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [edsu/anon](https://github.com/edsu/anon) | 772 | `mocha --colors --reporter spec test.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 772 | `mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 770 | `istanbul cover -- _mocha --reporter spec` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 767 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 766 | `nyc mocha specs` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 765 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 765 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 764 | `npm run lint && mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 762 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 762 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 761 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 760 | `mocha --async-only` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 757 | `npm run lint && npm run mocha` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 757 | `mocha spec/*.js` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 756 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 755 | `xo && mocha -R spec` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 752 | `./node_modules/.bin/mocha -R spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 751 | `mocha --reporter list` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 746 | `mocha --ui tdd --require ./test/__setup` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 743 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 739 | `npm run mocha:istanbul` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 739 | `mocha -R spec src/**/*_test.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 736 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 734 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 732 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 730 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 728 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 727 | `mocha --reporter spec` | 
| [bitpay/insight](https://github.com/bitpay/insight) | 724 | `mocha test` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 723 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 721 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 719 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 717 | `mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 717 | `mocha --recursive -s 15 test/` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 717 | `cross-env NODE_ENV=test nyc mocha` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 716 | `mocha test.js` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 716 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 712 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 709 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 708 | `mocha` | 
| [3Dparallax/insight](https://github.com/3Dparallax/insight) | 707 | `mocha test` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 705 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 705 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 702 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 701 | `npm run bundle && mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 700 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 698 | `npm run mocha-test test/integration` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 697 | `mocha test` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 697 | `mocha tests/*.mocha.js` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 695 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 690 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 689 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 688 | `npm run build && istanbul test _mocha test/test.js` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 686 | `mocha test` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 682 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 681 | `mocha` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 680 | `mocha ./test/index.js` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 680 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [developit/decko](https://github.com/developit/decko) | 679 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 678 | `npm run lint && mocha test` | 