# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:33 12/18/17 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39332 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 37931 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 35636 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 35010 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28198 | `mocha --reporter spec` | 
| [caolan/async](https://github.com/caolan/async) | 22928 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 19682 | `mocha test/index.js` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 16995 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [developit/preact](https://github.com/developit/preact) | 16768 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15159 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14234 | `mocha test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13593 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12353 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12232 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11904 | `mocha` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 11680 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11590 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11502 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11287 | `./node_modules/.bin/mocha test/` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 10866 | `cross-env NODE_ENV=test mocha` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 10443 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10363 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10274 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 9794 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9526 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9215 | `mocha --reporter spec` | 
| [tj/co](https://github.com/tj/co) | 9102 | `mocha --harmony` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9028 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 8914 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [tmpvar/jsdom](https://github.com/tmpvar/jsdom) | 8886 | `mocha test/index.js` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 8828 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8697 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [svg/svgo](https://github.com/svg/svgo) | 8653 | `set NODE_ENV=test && mocha` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8363 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8122 | `mocha test/*-test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8101 | `mocha --check-leaks -R dot` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8022 | `grunt clean:test && mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 7987 | `mocha test/test.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 7869 | `mocha` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7634 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7568 | `./node_modules/.bin/mocha test/src` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7515 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7422 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7404 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7324 | `mocha --compilers js:babel-register test/test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7242 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7181 | `npm run eslint && npm run mocha` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7047 | `npm run build && istanbul cover _mocha` | 
| [websockets/ws](https://github.com/websockets/ws) | 7016 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 6933 | `./node_modules/.bin/mocha test` | 
| [amark/gun](https://github.com/amark/gun) | 6920 | `mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 6864 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 6846 | `mocha tests/*.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6443 | `mocha $HARMONY_OPTS` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6386 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6358 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6298 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6183 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6172 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6080 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [almende/vis](https://github.com/almende/vis) | 6005 | `mocha --compilers js:babel-core/register` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 5944 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5934 | `mocha` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 5817 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 5812 | `nyc mocha test/** -r ./test/before` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5662 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5655 | `npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 5639 | `mocha --opts mocha.opts` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5545 | `npm run test:mocha:src` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 5530 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5446 | `npm run jshint && mocha test/` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5387 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5369 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5365 | `mocha tests/node.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5265 | `mocha && eslint lib/**` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5252 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5199 | `mocha test --recursive` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5161 | `mocha --color` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5149 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5111 | `mocha src/**/*Tests.js --harmony` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5066 | `mocha test/test.js` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 4963 | `mocha --timeout 10000 && npm run lint` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4803 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4764 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4726 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4673 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 4628 | `mocha --compilers js:babel-core/register` | 
| [santinic/how2](https://github.com/santinic/how2) | 4607 | `mocha test` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4561 | `mocha --reporter spec -t 8000` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4559 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4559 | `mocha -R spec 'tests/app'` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4511 | `mocha ./test/runner.js` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4366 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4347 | `gulp build; mocha;` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4326 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4313 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4298 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4252 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4233 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4225 | `mocha -R spec ./test --recursive` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4212 | `./node_modules/.bin/mocha` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4163 | `standard && mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4102 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4082 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4028 | `mocha` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 3980 | `mocha && ./bin/shipit staging test` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 3964 | `mocha test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3935 | `nyc mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3892 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 3863 | `mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 3827 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3821 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3812 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [muicss/mui](https://github.com/muicss/mui) | 3740 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3699 | `mocha --require should --reporter spec` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3656 | `mocha --recursive && make test` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3631 | `npm run jshint && npm run mocha` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3597 | `NODE_ENV=test mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3545 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3540 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3530 | `standard && mocha --timeout 60000 test/test.js` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3526 | `mocha --require test/babel-hook test/*.js` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3517 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3507 | `npm run lint && npm run mocha` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3496 | `mocha tests/javascript` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3433 | `npm run lint ; mocha && mocha test/individual` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3413 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3409 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [primus/primus](https://github.com/primus/primus) | 3391 | `npm run build && mocha test/*.test.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3379 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3376 | `mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3372 | `nyc mocha` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 3358 | `npm run build-cli && mocha` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3331 | `node_modules/.bin/mocha` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3283 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3275 | `npm run lint && mocha && EIO_WS_ENGINE=ws mocha` | 
| [easy-mock/easy-mock](https://github.com/easy-mock/easy-mock) | 3104 | `cross-env NODE_ENV=test istanbul cover _mocha test/*` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3080 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3077 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3058 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3040 | `./node_modules/.bin/mocha test/test.*.js` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3039 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3029 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3026 | `mocha --check-leaks --reporter spec --bail` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 2996 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 2969 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 2967 | `node_modules/.bin/mocha test/tests.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2941 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 2925 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 2894 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2892 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [expressjs/session](https://github.com/expressjs/session) | 2884 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2876 | `mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 2869 | `nyc mocha "test/**/*.test.js"` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 2820 | `npm run lint && npm run mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2813 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2804 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2775 | `mocha test/*.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2750 | `mocha --require should --reporter spec` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 2746 | `mocha; jshint *.js lib` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2741 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2735 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2734 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2701 | `mocha -R spec --recursive src/test` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2682 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2680 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2677 | `istanbul cover _mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2624 | `mocha test/index.js && npm run demo` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2605 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2602 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 2601 | `yarn run build:cjs && mocha --require babel-core/register ./test/index.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2585 | `xo && mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2583 | `mocha --timeout 100000` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2581 | `mocha` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2567 | `mocha-phantomjs ./test/index.html` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2564 | `nyc mocha && tsc` | 
| [github-tools/github](https://github.com/github-tools/github) | 2562 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2548 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2537 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2516 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2505 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2505 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2500 | `export TESTING=true; mocha --reporter list` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2498 | `mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2498 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [css/csso](https://github.com/css/csso) | 2491 | `mocha --reporter dot` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2484 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2473 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2471 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2471 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2465 | `mocha --recursive --watch` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2458 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2457 | `npm run mocha && npm run lint` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2456 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2441 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2417 | `mocha --compilers js:babel-register --recursive spec` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2410 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2410 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2394 | `mocha --reporter=spec test/*-test.js` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2378 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2376 | `mocha --opts mocha.opts` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2374 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2363 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2363 | `node node_modules/mocha/bin/_mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2348 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2320 | `mocha --no-colors --reporter spec` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2320 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2311 | `grunt jshint && mocha` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2302 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2297 | `mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2288 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2284 | `mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2282 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2275 | `npm run compile && mocha --compilers js:babel-core/register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2246 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2231 | `mocha test/src/**/*.unit.js` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2227 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2218 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2215 | `mocha test` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2208 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2204 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2202 | `mocha test test/unit/**/*_test.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2200 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2187 | `gulp && cd test && mocha . --reporter dot` | 
| [octokit/node-github](https://github.com/octokit/node-github) | 2165 | `nyc mocha test/**/*-test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2145 | `NODE_ENV=test mocha` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2143 | `node_modules/.bin/mocha --reporter spec` | 
| [mozilla/send](https://github.com/mozilla/send) | 2123 | `mocha test/unit` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2123 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2103 | `npm run lint && npm run build && npm run mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2096 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [gajus/swing](https://github.com/gajus/swing) | 2094 | `mocha --compilers js:babel-register` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2093 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2089 | `mocha -R spec` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2081 | `mocha test/unit --require mochahook` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2073 | `mocha` | 
| [json5/json5](https://github.com/json5/json5) | 2067 | `mocha --ui exports --reporter spec` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2026 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [slate/slate](https://github.com/slate/slate) | 2023 | `mocha --compilers js:babel-core/register ./packages/*/test/index.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2018 | `mocha` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2014 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2007 | `cross-env BABEL_ENV=test mocha` | 
| [mde/ejs](https://github.com/mde/ejs) | 1982 | `mocha --require should --reporter spec` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 1946 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 1937 | `nyc --reporter=html --reporter=text mocha` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1913 | `mocha --require=test/test_helper.js` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1898 | `mocha -R spec test/*.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1896 | `mocha --bail --reporter spec --check-leaks test/` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1870 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1860 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1848 | `mocha test/index.js --reporter dot` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1846 | `mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1837 | `mocha` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 1825 | `mocha ./test/*.spec.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1825 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1823 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1821 | `mocha tests.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1810 | `mocha --timeout 5000` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 1806 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1803 | `mocha --require ./test/common --growl test/expect.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1801 | `mocha test && npm run lint` | 
| [Qix-/color](https://github.com/Qix-/color) | 1789 | `mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1783 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1782 | `mocha` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1778 | `mocha --reporter spec --timeout 5000` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1772 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 1765 | `export TESTING=true; mocha --reporter list` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1760 | `cross-env NODE_ENV=test mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1757 | `mocha -c test/index.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1750 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1747 | `mocha test.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1737 | `mocha test/**/*_test.js --bail` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1734 | `mocha test` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1724 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [then/promise](https://github.com/then/promise) | 1715 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1713 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1713 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1709 | `mocha -R landing test/index` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1702 | `mocha test/runner.js --reporter spec` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1698 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1698 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1696 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1691 | `mocha --compilers js:babel-register` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1690 | `npm run jshint && mocha --recursive` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1678 | `mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1676 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1674 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1672 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1672 | `xo && mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1670 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1666 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1656 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1655 | `mocha test` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1652 | `mocha` | 
| [Hardmath123/nearley](https://github.com/Hardmath123/nearley) | 1649 | `mocha test/*.test.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1647 | `npm run lint && npm run compile && mocha --reporter spec test/*.js` | 
| [verdaccio/verdaccio](https://github.com/verdaccio/verdaccio) | 1647 | `mocha ./test/functional ./test/unit --reporter=spec --full-trace` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1643 | `./node_modules/.bin/mocha` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1639 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [KunalKapadia/express-mongoose-es6-rest-api](https://github.com/KunalKapadia/express-mongoose-es6-rest-api) | 1620 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1611 | `mocha -R spec spec spec/reporters` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1610 | `mocha` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1610 | `mocha && eslint *.js` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1605 | `mocha --reporter spec && npm run test-typescript` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1604 | `mocha tests/test.js` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1604 | `lint && mocha --recursive` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1603 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1603 | `npm run lint && npm run mocha` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1599 | `mocha --expose-gc --slow 300` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1596 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1596 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1588 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1575 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1574 | `./node_modules/mocha/bin/mocha -R spec` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1573 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1553 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1546 | `mocha test/*.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1545 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1543 | `./node_modules/.bin/mocha` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1526 | `npm run mocha && npm run karma` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1519 | `npm run lint && mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1517 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1516 | `mocha && npm run lint` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1509 | `mocha --reporter spec --grep .` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1490 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1487 | `nyc npm run _mocha` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1486 | `npm run mocha && npm run lint` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1486 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1484 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1475 | `mocha tests --compilers js:babel-core/register` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1472 | `mocha` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1463 | `mocha -R spec` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1457 | `mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1455 | `mocha test -u bdd -R spec` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1455 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1454 | `mocha test/` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1454 | `mocha spec/` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1454 | `./node_modules/mocha/bin/mocha -R spec` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1453 | `mocha ./test/basic.js -t 5000` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1453 | `mocha test/* --reporter spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1452 | `mocha -u tdd` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1445 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1441 | `node_modules/.bin/mocha --recursive` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1438 | `npm run lint && npm run mocha` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1430 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1429 | `mocha test/tests.js --timeout=10000` | 
| [pahen/madge](https://github.com/pahen/madge) | 1427 | `npm run lint && npm run mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1426 | `npm run test:lint && npm run test:mocha && npm run site` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1415 | `mocha` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1408 | `npm run lint && mocha -R dot && npm run cover` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1402 | `mocha test.js` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1401 | `mocha --reporter spec` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1392 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1375 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1355 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1354 | `nyc mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1350 | `mocha --reporter spec test/*.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1346 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1343 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1343 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1342 | `./node_modules/mocha/bin/mocha` | 
| [trufflesuite/ganache-cli](https://github.com/trufflesuite/ganache-cli) | 1333 | `mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 1333 | `./node_modules/.bin/mocha && npm run jshint` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1325 | `mocha --check-leaks -R dot` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1322 | `standard "./src/*.js" && mocha` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1321 | `eslint --rulesdir=dev-tools/eslint --cache . && tsc && mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1320 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1319 | `mocha` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1317 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1315 | `cross-env NODE_ENV=test nyc mocha` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1307 | `mocha --compilers js:babel-register` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1292 | `istanbul cover _mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1290 | `mocha --recursive` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1280 | `mocha test.js` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1274 | `standard "src/*.js" && npm run build && mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1262 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1259 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1252 | `npm run build && mocha -r should` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1240 | `mocha` | 
| [sandeepmistry/bleno](https://github.com/sandeepmistry/bleno) | 1227 | `mocha -R spec test/*.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1224 | `./node_modules/.bin/mocha test` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1222 | `mocha --timeout 10000 ./tests/lib.js` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1216 | `mocha spec/exec.js` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1213 | `mocha-phantomjs tests/index.html` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1210 | `mocha --check-leaks --reporter spec --bail` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1209 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [zeit/ms](https://github.com/zeit/ms) | 1206 | `mocha tests.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1205 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1198 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [electron/devtron](https://github.com/electron/devtron) | 1196 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1194 | `mocha tests` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1194 | `mocha test/setup.js test/spec/*.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1191 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [reddit/reddit-mobile](https://github.com/reddit/reddit-mobile) | 1190 | `mocha test/index.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1190 | `mocha test/test.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1188 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1184 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1181 | `mocha test/*.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1179 | `mocha` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1179 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1177 | `mocha test/**/*Spec.js` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1173 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1168 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1167 | `mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1166 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1166 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1166 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1165 | `mocha test` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1162 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1157 | `npm run lint && npm run mocha` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1156 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1152 | `istanbul cover _mocha test -- --timeout 20000` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1148 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1148 | `mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1146 | `mocha --recursive` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1146 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1142 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1139 | `mocha compiled_tests/` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1138 | `./node_modules/.bin/mocha` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1136 | `node ./node_modules/mocha/bin/mocha tests` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1130 | `eslint lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1127 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1122 | `mocha --opts test/opts/mocha.opts` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1114 | `mocha` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1113 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1104 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1098 | `mocha` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1097 | `mocha --check-leaks --require @babel/register` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1093 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1091 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1089 | `mocha test --timeout 600000` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1088 | `node_modules/.bin/mocha && npm run lint` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1082 | `nodeunit test; mocha test` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1082 | `npm run lint && npm run mocha` | 
| [sorrycc/roadhog](https://github.com/sorrycc/roadhog) | 1080 | `npm run lint && npm run build && cross-env NODE_ENV=test nyc mocha --no-timeouts test/**/*-test.js` | 
| [normalize/mz](https://github.com/normalize/mz) | 1079 | `mocha --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1073 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1072 | `mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1068 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1068 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1065 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1059 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1055 | `mocha --compilers js:babel-register` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1052 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1051 | `mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1050 | `mocha --reporter spec --timeout 3000` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1048 | `mocha test/*` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1044 | `mocha src/test.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1041 | `node_modules/.bin/mocha` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1038 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1036 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1035 | `mocha $(find test -name '*.test.js')` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1030 | `standard && istanbul cover _mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1025 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1022 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1022 | `xo && mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1021 | `istanbul test _mocha` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1020 | `mocha --check-leaks -R dot` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1016 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1014 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1012 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1012 | `mocha --reporter dot` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1007 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1005 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1000 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 995 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 993 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 989 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 988 | `mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 987 | `mocha test/unit` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 987 | `eslint src && mocha && karma start --single-run` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 985 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 983 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 982 | `mocha --colors ./test/*.spec.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 982 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 982 | `mocha test/tests.js` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 979 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 975 | `mocha` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 968 | `istanbul cover _mocha test/*.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 965 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [googlevr/webvr-polyfill](https://github.com/googlevr/webvr-polyfill) | 963 | `mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 963 | `mocha --check-leaks --reporter spec --bail test/` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 961 | `mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 959 | `eslint . && mocha -t 5000` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 959 | `mocha --timeout 5000` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 957 | `NODE_PATH=. mocha **/*.spec.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 948 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 945 | `mocha -R list` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 945 | `npm run rollup-cjs && mocha test/test.js` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 944 | `mocha --recursive --bail --reporter spec test` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 944 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 944 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 936 | `mocha --recursive test/unit/` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 935 | `standard && mocha` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 935 | `mocha $(find test -name '*.test.js')` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 934 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 931 | `mocha tests/test-*` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 930 | `mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 920 | `mocha --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 920 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 919 | `mocha --async-only` | 
| [dabeng/OrgChart](https://github.com/dabeng/OrgChart) | 916 | `mocha ./test/**/*-tests.js` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 914 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 913 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [tomas/needle](https://github.com/tomas/needle) | 910 | `mocha test` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 906 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 904 | `mocha ./test/index.js` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 904 | ` NODE_ENV=test mocha --compilers js:babel-register` | 
| [router5/router5](https://github.com/router5/router5) | 903 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 901 | `mocha spec/*.spec.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 896 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 893 | `npm run prepublish && mocha test/test.js` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 893 | `./node_modules/.bin/mocha --globals angular,require` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 889 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 888 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 886 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 886 | `mocha test` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 886 | `standard && mocha -b` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 885 | `mocha -t 120000 test/*.test.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 878 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 874 | `mocha` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 874 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 872 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 871 | `webpack && mocha test/unit` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 870 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 870 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 867 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 867 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 867 | `mocha --reporter list` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 860 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [electron/asar](https://github.com/electron/asar) | 857 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 857 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [teambit/bit](https://github.com/teambit/bit) | 857 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 855 | `mocha` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 854 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 854 | `nyc mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 853 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 850 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 847 | `mocha --recursive test` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 846 | `mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 843 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 843 | `mocha "client.test" --compilers js:babel-register` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 842 | `mocha --reporter spec --bail --check-leaks test/` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 838 | `node_modules/.bin/mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 832 | `eslint test && mocha --compilers js:babel/register` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 831 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 829 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 829 | `mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 828 | `mocha --compilers js:babel-register test/*.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 827 | `mocha` | 
| [electron/spectron](https://github.com/electron/spectron) | 825 | `mocha && standard` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 824 | `npm run lint && mocha -R spec` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 823 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 819 | `mocha --timeout 200000` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 818 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 817 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 816 | `nyc mocha --timeout=20000 test.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 815 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 815 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 812 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 811 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 808 | `mocha && ember test` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 806 | `node_modules/.bin/mocha test/spec` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 806 | `mocha tests/*.test.js --reporter spec` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 805 | `mocha --reporter spec` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 804 | `mocha --reporter spec --bail --check-leaks test/` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 804 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 803 | `mocha` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 802 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 799 | `mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 794 | `mocha tests` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 790 | `mocha -R spec tests/` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 790 | `mocha --check-leaks -t 20000` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 787 | `npm run convertto:es5 && npm run mocha` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 786 | `nyc mocha --require babel-register` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 784 | `mocha --require babel-register` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 783 | `mocha -u tdd` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 783 | `mocha` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 779 | `istanbul cover _mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 775 | `cake build && mocha ./test/mocha/*.coffee` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 773 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 773 | `mocha ./test -R spec` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 772 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 772 | `mocha` | 
| [reactivestack/cookies](https://github.com/reactivestack/cookies) | 770 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 770 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 769 | `nyc mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 768 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 766 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 766 | `standard && standard ./bin/* && mocha` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 765 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 765 | `mocha -t 5000` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 761 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [edsu/anon](https://github.com/edsu/anon) | 761 | `mocha --colors --reporter spec test.js` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 760 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 759 | `mocha ./test/test*.js --reporter spec` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 758 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 758 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 755 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 750 | `mocha` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 749 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 748 | `mocha test --compilers js:babel-register` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 747 | `npm run lint && mocha` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 745 | `mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 745 | `istanbul cover -- _mocha --reporter spec` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 741 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 741 | `xo && mocha -R spec` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 737 | `mocha --async-only` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 736 | `nyc mocha specs` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 736 | `mocha` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 734 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 731 | `mocha -R spec src/**/*_test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 731 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 730 | `npm run lint && mocha --compilers js:babel-register` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 729 | `mocha -t 600000` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 729 | `mocha -R spec` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 728 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 727 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 726 | `mocha --reporter spec` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 724 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 722 | `mocha --ui tdd --require ./test/__setup` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 722 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 722 | `TEST_MODE=unit NODE_ENV=test jest && TEST_MODE=unit NODE_ENV=test mocha -R ${MOCHA_REPORTER:-spec}` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 721 | `mocha -R spec --compilers js:babel-core/register ./tests/setup.js ./tests/** --recursive` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 719 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 718 | `mocha --reporter list` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 716 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 714 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 713 | `mocha spec/*.js` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 707 | `./node_modules/.bin/mocha -R spec` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 707 | `mocha test.js` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 705 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 699 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [contra/gulp-concat](https://github.com/contra/gulp-concat) | 697 | `mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 696 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 676 | `npm run mocha-test test/integration` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 675 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 675 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 675 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 674 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 672 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 670 | `mocha -b -R spec test/*` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 670 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 669 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 669 | `npm run build && istanbul test _mocha test/test.js` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 667 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 666 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require babel-register --no-timeouts` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 665 | `mocha --reporter spec` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 664 | `eslint src test && mocha --compilers babel-register` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 663 | `mocha test` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 663 | `mocha --reporter spec` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 663 | `mocha test` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 675 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 675 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 675 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [pillarjs/cookies](https://github.com/pillarjs/cookies) | 674 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 672 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 670 | `mocha -b -R spec test/*` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 670 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 669 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 669 | `npm run build && istanbul test _mocha test/test.js` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 667 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 666 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require babel-register --no-timeouts` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 665 | `mocha --reporter spec` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 664 | `eslint src test && mocha --compilers babel-register` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 663 | `mocha test` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 663 | `mocha --reporter spec` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 663 | `mocha test` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 663 | `mocha` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 662 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 657 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 656 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 656 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 654 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 653 | `mocha` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 652 | `./node_modules/.bin/mocha test/integration` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 649 | `mocha` | 
| [jh3y/tyto](https://github.com/jh3y/tyto) | 648 | `./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/.bin/phantomjs test/index.html` | 