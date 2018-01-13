# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:19 01/13/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39507 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 38498 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 36049 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 35805 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28445 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23110 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 20129 | `mocha test/index.js` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17247 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [developit/preact](https://github.com/developit/preact) | 17152 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 15805 | `cross-env NODE_ENV=test mocha` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15327 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14476 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13664 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12676 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12403 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11943 | `mocha` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 11799 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11762 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11575 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11435 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 10770 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10630 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10395 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 10047 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9737 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9363 | `mocha --reporter spec` | 
| [tj/co](https://github.com/tj/co) | 9193 | `mocha --harmony` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9191 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9034 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tmpvar/jsdom](https://github.com/tmpvar/jsdom) | 9017 | `mocha test/index.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 8939 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 8803 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8776 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8440 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8232 | `mocha test/*-test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8116 | `mocha --check-leaks -R dot` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8067 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8043 | `mocha test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8036 | `grunt clean:test && mocha` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7677 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7647 | `./node_modules/.bin/mocha test/src` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7629 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7498 | `mocha --compilers js:babel-register test/test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7481 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7434 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7410 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [websockets/ws](https://github.com/websockets/ws) | 7251 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7217 | `npm run eslint && npm run mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7142 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 7102 | `mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7092 | `npm run build && istanbul cover _mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7003 | `mocha tests/*.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7000 | `./node_modules/.bin/mocha test` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6600 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6541 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6491 | `mocha $HARMONY_OPTS` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6384 | `xo && mocha test/*.js --timeout 100000` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6377 | `mocha --require babel-core/register ./packages/*/test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 6307 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6187 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6163 | `mocha --opts mocha.opts` | 
| [almende/vis](https://github.com/almende/vis) | 6120 | `mocha --compilers js:babel-core/register` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6067 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6029 | `nyc mocha test/** -r ./test/before` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 5970 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5926 | `mocha` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5821 | `npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 5796 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5738 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5677 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5540 | `npm run jshint && mocha test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5493 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5416 | `mocha tests/node.js` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5384 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5295 | `mocha && eslint lib/**` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5291 | `mocha test --recursive` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5277 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5219 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5166 | `mocha --color` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5155 | `mocha test/test.js` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5127 | `mocha src/**/*Tests.js --harmony` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5024 | `mocha --timeout 10000 && npm run lint` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4865 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4861 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 4844 | `mocha --compilers js:babel-core/register` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4745 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4695 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4613 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4612 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4583 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4577 | `mocha --reporter spec -t 8000` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4524 | `mocha ./test/runner.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4458 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4404 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4376 | `gulp build; mocha;` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4373 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4316 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4305 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4293 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4274 | `./node_modules/.bin/mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4256 | `standard && mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4226 | `mocha -R spec ./test --recursive` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4137 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4137 | `mocha` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4134 | `mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4084 | `mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4044 | `mocha test` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 4016 | `mocha && ./bin/shipit staging test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3966 | `nyc mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 3928 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3887 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 3856 | `npm run build-cli && mocha` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3837 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3815 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [muicss/mui](https://github.com/muicss/mui) | 3767 | `mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3737 | `mocha --recursive && make test` | 
| [tj/ejs](https://github.com/tj/ejs) | 3729 | `mocha --require should --reporter spec` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3701 | `NODE_ENV=test mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3670 | `mocha --require test/babel-hook test/*.js` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3636 | `npm run jshint && npm run mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3612 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3594 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3568 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3544 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3540 | `standard && mocha --timeout 60000 test/test.js` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3523 | `nyc mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3512 | `mocha tests/javascript` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3489 | `npm run lint ; mocha && mocha test/individual` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3430 | `mocha --reporter spec --timeout 3000` | 
| [primus/primus](https://github.com/primus/primus) | 3419 | `npm run build && mocha test/*.test.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3419 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3381 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3380 | `mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3359 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3356 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3307 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 3299 | `mocha; jshint *.js lib` | 
| [easy-mock/easy-mock](https://github.com/easy-mock/easy-mock) | 3207 | `cross-env NODE_ENV=test istanbul cover _mocha test/*` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3166 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3127 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3124 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3106 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3103 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3091 | `mocha --check-leaks --reporter spec --bail` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3080 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3064 | `mocha` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3061 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3047 | `./node_modules/.bin/mocha test/test.*.js` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3004 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 2982 | `node_modules/.bin/mocha test/tests.js` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 2979 | `npm run lint && npm run mocha` | 
| [expressjs/session](https://github.com/expressjs/session) | 2967 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2953 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 2950 | `nyc mocha "test/**/*.test.js"` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 2941 | `yarn run build:cjs && mocha --require babel-core/register ./test/index.js` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2905 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2894 | `mocha` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2878 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2862 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2796 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2789 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2754 | `mocha --require should --reporter spec` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2753 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2749 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2720 | `mocha -R spec --recursive src/test` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2709 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2696 | `mocha` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2692 | `istanbul cover _mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2687 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2679 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2666 | `mocha test/index.js && npm run demo` | 
| [tj/should.js](https://github.com/tj/should.js) | 2657 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2631 | `nyc mocha && tsc` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2619 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2616 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2605 | `mocha` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2590 | `xo && mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2586 | `mocha --timeout 100000` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2584 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [github-tools/github](https://github.com/github-tools/github) | 2584 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2580 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2571 | `mocha-phantomjs ./test/index.html` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2570 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2558 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2546 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2533 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2526 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2523 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2519 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2516 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2514 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [css/csso](https://github.com/css/csso) | 2513 | `mocha --reporter dot` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2508 | `mocha --opts mocha.opts` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2500 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2497 | `npm run mocha && npm run lint` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2476 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2473 | `mocha --recursive --watch` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2463 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2454 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2454 | `mocha --compilers js:babel-register --recursive spec` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2449 | `mocha` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2411 | `npm run compile && mocha --require babel-core/register` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2405 | `mocha --reporter=spec test/*-test.js` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2401 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2390 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2380 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2365 | `node node_modules/mocha/bin/_mocha` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2360 | `mocha` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2348 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2324 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2321 | `mocha --no-colors --reporter spec` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2319 | `mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2311 | `grunt jshint && mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2294 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2271 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2270 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2268 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2254 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2254 | `mocha test` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2252 | `mocha test/src/**/*.unit.js` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2235 | `gulp && cd test && mocha . --reporter dot` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2229 | `NODE_ENV=test mocha` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2221 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2212 | `node_modules/.bin/mocha --reporter spec` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2210 | `mocha test test/unit/**/*_test.js` | 
| [octokit/node-github](https://github.com/octokit/node-github) | 2208 | `nyc mocha test/**/*-test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2208 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mozilla/send](https://github.com/mozilla/send) | 2174 | `mocha test/unit` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2169 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2159 | `mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2158 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [json5/json5](https://github.com/json5/json5) | 2138 | `mocha --ui exports --reporter spec` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2129 | `mocha test/unit --require mochahook` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2128 | `npm run lint && npm run build && npm run mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2127 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2116 | `mocha -R spec` | 
| [gajus/swing](https://github.com/gajus/swing) | 2114 | `mocha --compilers js:babel-register` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2077 | `mocha` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2069 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [mde/ejs](https://github.com/mde/ejs) | 2062 | `mocha --require should --reporter spec` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2059 | `mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2024 | `mocha` | 
| [slate/slate](https://github.com/slate/slate) | 2021 | `mocha --require babel-core/register ./packages/*/test/index.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2017 | `cross-env BABEL_ENV=test mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2005 | `nyc --reporter=html --reporter=text mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 1973 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1937 | `mocha -R spec test/*.js` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1918 | `mocha --require=test/test_helper.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1901 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1899 | `mocha --bail --reporter spec --check-leaks test/` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 1895 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1879 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1872 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 1868 | `mocha ./test/*.spec.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1866 | `mocha test/index.js --reporter dot` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1863 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1850 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1842 | `mocha -c test/index.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1840 | `mocha test && npm run lint` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1829 | `mocha` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1824 | `mocha tests.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1823 | `mocha test.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1823 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1819 | `mocha --require ./test/common --growl test/expect.js` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1810 | `mocha -R landing test/index` | 
| [Qix-/color](https://github.com/Qix-/color) | 1809 | `mocha` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1807 | `mocha --timeout 5000` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1800 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1799 | `mocha --reporter spec --timeout 5000` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1783 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1764 | `cross-env NODE_ENV=test mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1755 | `mocha --compilers js:babel-register` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1754 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1751 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1749 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [then/promise](https://github.com/then/promise) | 1744 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1741 | `mocha test` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1737 | `mocha test/runner.js --reporter spec` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1733 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1727 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1722 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1706 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1704 | `mocha --compilers js:babel-core/register __tests__` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1697 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1696 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1696 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1694 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1694 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [Hardmath123/nearley](https://github.com/Hardmath123/nearley) | 1689 | `mocha test/*.test.js` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1684 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1683 | `mocha` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1672 | `mocha test` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1671 | `mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [KunalKapadia/express-mongoose-es6-rest-api](https://github.com/KunalKapadia/express-mongoose-es6-rest-api) | 1669 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1668 | `npm run lint && mocha --reporter spec test/*.js` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1659 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1655 | `./node_modules/.bin/mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1647 | `mocha && eslint *.js` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1637 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [share/sharedb](https://github.com/share/sharedb) | 1630 | `./node_modules/.bin/mocha && npm run jshint` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1627 | `mocha --reporter spec && npm run test-typescript` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1627 | `npm run lint && mocha --recursive` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1623 | `mocha -R spec spec spec/reporters` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1622 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1622 | `npm run lint && npm run mocha` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1616 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1612 | `./node_modules/mocha/bin/mocha -R spec` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1611 | `npm run lint && mocha -R dot && npm run cover` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1606 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1605 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1605 | `mocha tests/test.js` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1604 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1602 | `mocha --expose-gc --slow 300` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1600 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1592 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1587 | `npm run mocha && npm run karma` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1585 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1564 | `mocha test/*.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1564 | `mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1545 | `./node_modules/.bin/mocha` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1544 | `mocha && npm run lint` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1540 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1532 | `npm run lint && mocha` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1530 | `nyc npm run _mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1525 | `mocha --reporter spec --grep .` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1521 | `npm run mocha && npm run lint` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1519 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1514 | `mocha tests --compilers js:babel-core/register` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1492 | `mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1491 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1490 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1489 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1487 | `mocha test -u bdd -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1486 | `mocha test/` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1483 | `mocha spec/` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1482 | `mocha ./test/basic.js -t 5000` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1479 | `mocha test/* --reporter spec` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1467 | `mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1467 | `mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 1466 | `npm run lint && npm run mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1466 | `mocha -R spec` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1465 | `npm run test:lint && npm run test:mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1464 | `./node_modules/mocha/bin/mocha -R spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1455 | `mocha -u tdd` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1454 | `npm run lint && npm run mocha` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1453 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1442 | `node_modules/.bin/mocha --recursive` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1433 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1432 | `mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1428 | `mocha --reporter spec test/*.js` | 
| [samccone/drool](https://github.com/samccone/drool) | 1427 | `mocha test/tests.js --timeout=10000` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1418 | `mocha --reporter spec` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1403 | `mocha test.js` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1403 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1397 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1364 | `nyc mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1361 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1355 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1354 | `mocha --compilers js:babel-register` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1351 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1351 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1349 | `standard "src/*.js" && npm run build && mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1345 | `./node_modules/mocha/bin/mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1344 | `eslint --rulesdir=dev-tools/eslint --cache . && tsc && mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1342 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1341 | `standard "./src/*.js" && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1340 | `mocha --check-leaks -R dot` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1325 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1323 | `mocha test.js` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1319 | `cross-env NODE_ENV=test nyc mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1318 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1314 | `mocha test --timeout 600000` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1307 | `mocha --recursive` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1299 | `istanbul cover _mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1279 | `mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1269 | `mocha-phantomjs tests/index.html` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1260 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1258 | `npm run build && mocha -r should` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1250 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1249 | `mocha --check-leaks --reporter spec --bail` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1248 | `mocha --timeout 10000 ./tests/lib.js` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1245 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [sandeepmistry/bleno](https://github.com/sandeepmistry/bleno) | 1243 | `mocha -R spec test/*.js` | 
| [zeit/ms](https://github.com/zeit/ms) | 1241 | `mocha tests.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1235 | `./node_modules/.bin/mocha test` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1226 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1223 | `mocha spec/exec.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1220 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1220 | `mocha test/setup.js test/spec/*.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1217 | `mocha` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1191 | `npm run lint && npm run mocha` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1188 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1185 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1184 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1183 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1178 | `mocha test/**/*Spec.js` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1176 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1175 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1173 | `istanbul cover _mocha test -- --timeout 20000` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1168 | `mocha test` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1165 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1164 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1160 | `mocha --recursive` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1159 | `mocha` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1152 | `./node_modules/.bin/mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1151 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1151 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1139 | `node ./node_modules/mocha/bin/mocha tests` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1139 | `mocha --opts test/opts/mocha.opts` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1138 | `eslint lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1128 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1127 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1123 | `mocha --check-leaks --require @babel/register` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1122 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1122 | `mocha` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1108 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1093 | `npm run lint && npm run mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1093 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1091 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [normalize/mz](https://github.com/normalize/mz) | 1089 | `mocha --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1088 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1088 | `node_modules/.bin/mocha && npm run lint` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1086 | `mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1083 | `eslint . && mocha -t 5000` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1079 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1076 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1073 | `mocha src/test.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1073 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1073 | `mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1066 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1060 | `mocha --check-leaks -t 20000` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1059 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1059 | `mocha --compilers js:babel-register` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1056 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1055 | `mocha test/*` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1052 | `node_modules/.bin/mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1051 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1049 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1049 | `mocha --reporter spec --timeout 3000` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1049 | `standard && istanbul cover _mocha` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1042 | `mocha $(find test -name '*.test.js')` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1041 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1038 | `mocha --reporter dot` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1032 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1030 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1030 | `eslint src && mocha && karma start --single-run` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1029 | `xo && mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1027 | `mocha test/unit` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1026 | `istanbul test _mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1023 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1023 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [jas/playground](https://github.com/jas/playground) | 1020 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1018 | `mocha --check-leaks -R dot` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1014 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1006 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1006 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1004 | `mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1002 | `NODE_PATH=. mocha **/*.spec.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 995 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 990 | `mocha --check-leaks --reporter spec --bail test/` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 989 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 983 | `mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 983 | `mocha test/tests.js` | 
| [googlevr/webvr-polyfill](https://github.com/googlevr/webvr-polyfill) | 980 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 980 | `mocha --colors ./test/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 979 | `istanbul cover _mocha test/*.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 976 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 973 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 972 | `mocha` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 964 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 963 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 959 | `mocha --timeout 5000` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 957 | `mocha tests/test-*` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 956 | `mocha --recursive --bail --reporter spec test` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 950 | `mocha -R list` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 947 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 947 | `mocha test` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 946 | `npm run rollup-cjs && mocha test/test.js` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 945 | `mocha` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 943 | `standard && mocha` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 940 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 939 | `mocha --recursive test/unit/` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 939 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 938 | `mocha $(find test -name '*.test.js')` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 937 | ` NODE_ENV=test mocha --compilers js:babel-register` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 932 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 929 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 927 | `mocha --reporter spec` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 926 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 924 | `npm run prepublish && mocha test/test.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 920 | `mocha test` | 
| [router5/router5](https://github.com/router5/router5) | 920 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 913 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 910 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 909 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 907 | `mocha -t 120000 test/*.test.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 905 | `mocha ./test/index.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 902 | `mocha spec/*.spec.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 902 | `standard && mocha -b` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 901 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 901 | `mocha` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 892 | `./node_modules/.bin/mocha --globals angular,require` | 
| [teambit/bit](https://github.com/teambit/bit) | 892 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 890 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 887 | `webpack && mocha test/unit` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 884 | `mocha` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 880 | `mocha --recursive test` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 879 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 879 | `mocha --reporter spec --bail --check-leaks test/` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 878 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 876 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 874 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [electron/asar](https://github.com/electron/asar) | 873 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 873 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 870 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 870 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 865 | `mocha --reporter list` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 862 | `nyc mocha --timeout=20000 test.js` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 862 | `mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 861 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 860 | `mocha` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 859 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 854 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 854 | `mocha --reporter spec --bail --check-leaks test/` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 853 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 852 | `mocha "client.test" --compilers js:babel-register` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 850 | `mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 845 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 844 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [electron/spectron](https://github.com/electron/spectron) | 843 | `mocha && standard` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 840 | `mocha --compilers js:babel-register test/*.js` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 840 | `node_modules/.bin/mocha` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 839 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 833 | `eslint test && mocha --compilers js:babel/register` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 832 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 831 | `npm run lint && mocha -R spec` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 827 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 827 | `npm run lint && npm run mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 826 | `mocha --timeout 200000` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 826 | `mocha` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 823 | `mocha --reporter spec --bail --check-leaks test/` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 823 | `mocha --reporter spec --bail --check-leaks test/` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 820 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 818 | `nyc mocha --require babel-register` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 816 | `node_modules/.bin/mocha test/spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 816 | `mocha` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 815 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 814 | `mocha --reporter spec` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 814 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 810 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 809 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 808 | `npm run convertto:es5 && npm run mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 808 | `mocha && ember test` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 808 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 807 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 807 | `mocha tests` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 807 | `mocha tests/*.test.js --reporter spec` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 807 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 798 | `mocha ./test/test*.js --reporter spec` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 797 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 797 | `mocha ./test -R spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 795 | `mocha --check-leaks -t 20000` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 790 | `mocha -R spec tests/` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 790 | `mocha -u tdd` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 788 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 786 | `mocha --require babel-register` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 784 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 784 | `istanbul cover _mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 784 | `mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 782 | `npm run lint && mocha --compilers js:babel-register` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 780 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 780 | `standard && standard ./bin/* && mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 778 | `mocha -R spec ./test/unit/**` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 782 | `npm run lint && mocha --compilers js:babel-register` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 780 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 780 | `standard && standard ./bin/* && mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 778 | `mocha -R spec ./test/unit/**` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 778 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 778 | `cake build && mocha ./test/mocha/*.coffee` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 776 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 776 | `mocha -t 5000` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 776 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 774 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 773 | `mocha --reporter spec --bail --check-leaks test/` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 764 | `mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 764 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 763 | `mocha --colors --reporter spec test.js` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 760 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 760 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 760 | `mocha test --compilers js:babel-register` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 760 | `istanbul cover -- _mocha --reporter spec` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 757 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 756 | `npm run lint && mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 753 | `mocha -t 600000` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 753 | `mocha` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 753 | `mocha -R spec` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 752 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 751 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 751 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 751 | `mocha --async-only` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 750 | `mocha` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 748 | `nyc mocha specs` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 747 | `xo && mocha -R spec` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 742 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 738 | `mocha --ui tdd --require ./test/__setup` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 737 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 734 | `mocha -R spec src/**/*_test.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 733 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 730 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 729 | `mocha spec/*.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 728 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 727 | `mocha --reporter list` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 727 | `mocha tests/*.js` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 729 | `mocha spec/*.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 728 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 727 | `mocha --reporter list` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 727 | `mocha tests/*.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 726 | `mocha --reporter spec` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 725 | `./node_modules/.bin/mocha -R spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 722 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 720 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 712 | `mocha test.js` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 711 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 711 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 707 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 706 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require babel-register --no-timeouts` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 701 | `cross-env NODE_ENV=test nyc mocha` | 
| [contra/gulp-concat](https://github.com/contra/gulp-concat) | 699 | `mocha` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 690 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 688 | `npm run mocha-test test/integration` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 688 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 686 | `mocha tests/*.mocha.js` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 680 | `npm run lint && mocha test` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 680 | `npm run build && istanbul test _mocha test/test.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 679 | `mocha test` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 678 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 678 | `npm run mocha:istanbul` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 678 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 677 | `mocha ./test/index.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 677 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 676 | `eslint src test && mocha --compilers babel-register` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 680 | `npm run lint && mocha test` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 680 | `npm run build && istanbul test _mocha test/test.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 679 | `mocha test` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 678 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 678 | `npm run mocha:istanbul` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 678 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 677 | `mocha ./test/index.js` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 677 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 676 | `eslint src test && mocha --compilers babel-register` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 673 | `mocha test` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 670 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 670 | `mocha -b -R spec test/*` | 
| [bitpay/insight](https://github.com/bitpay/insight) | 670 | `mocha test` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 667 | `mocha --reporter spec` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 666 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 665 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 664 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 664 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 663 | `mocha` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 663 | `mocha` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 662 | `mocha --reporter spec` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 659 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [developit/decko](https://github.com/developit/decko) | 658 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 658 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 654 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [appleple/SmartPhoto](https://github.com/appleple/SmartPhoto) | 653 | `npm run lint && mocha ./test/test.js --timeout 1000000` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 652 | `./node_modules/.bin/mocha test/integration` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 652 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 651 | `mocha` | 