# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:06 01/31/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39652 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 38955 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 36598 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [expressjs/express](https://github.com/expressjs/express) | 36383 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28627 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23255 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 20471 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 18283 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 17479 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17390 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15461 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14684 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13730 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 12892 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12544 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 11983 | `mocha 'test/**/*.spec.js'` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11973 | `mocha` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 11904 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11645 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11564 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 11041 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10802 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10495 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 10262 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9879 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9508 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9343 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 9255 | `mocha --harmony` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9150 | `mocha test/index.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9147 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9023 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 8916 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8831 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8493 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8296 | `mocha test/*-test.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8200 | `mocha` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8133 | `mocha --check-leaks -R dot` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8072 | `mocha test/test.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7729 | `./node_modules/.bin/mocha test/src` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7726 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7709 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7705 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7630 | `mocha --compilers js:babel-register test/test.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 7478 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7439 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7421 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7305 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [giakki/uncss](https://github.com/giakki/uncss) | 7298 | `npm run eslint && npm run mocha` | 
| [amark/gun](https://github.com/amark/gun) | 7242 | `mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7139 | `mocha tests/*.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7118 | `npm run build && istanbul cover _mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7060 | `./node_modules/.bin/mocha test` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6763 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6706 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6526 | `mocha $HARMONY_OPTS` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6497 | `BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6443 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6392 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6291 | `mocha --opts mocha.opts` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6272 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [almende/vis](https://github.com/almende/vis) | 6189 | `mocha --compilers js:babel-core/register` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6179 | `nyc mocha test/**/* -r ./test/before` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6165 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6092 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 5975 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation --check-leaks` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5922 | `mocha` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5889 | `npm run jshint -s && npm run mocha -s && npm run test-components -s && npm run test-components-deprecated -s` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5788 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5743 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5632 | `npm run jshint && mocha test/` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5607 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5464 | `mocha tests/node.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5384 | `mocha test --recursive` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5383 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5332 | `mocha && eslint lib/**` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5321 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5280 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5248 | `mocha test/test.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5164 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5135 | `mocha src/**/*Tests.js --harmony` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5090 | `mocha --timeout 10000 && npm run lint` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 4982 | `mocha --compilers js:babel-core/register` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4934 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4930 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4760 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4716 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4659 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4614 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4596 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4594 | `mocha --reporter spec -t 8000` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4577 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4527 | `mocha ./test/runner.js` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4500 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4407 | `gulp build; mocha;` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4383 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4357 | `standard && mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4345 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4340 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4318 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4306 | `./node_modules/.bin/mocha` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 4277 | `npm run build-cli && mocha` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4233 | `mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4222 | `mocha -R spec ./test --recursive` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4211 | `mocha` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4174 | `mocha` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4164 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4113 | `mocha test` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 4043 | `mocha && ./bin/shipit staging test` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4019 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3976 | `nyc mocha` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3886 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3843 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3818 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3812 | `mocha --recursive && make test` | 
| [muicss/mui](https://github.com/muicss/mui) | 3798 | `mocha` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3772 | `mocha --require test/babel-hook test/*.js` | 
| [tj/ejs](https://github.com/tj/ejs) | 3761 | `mocha --require should --reporter spec` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3753 | `NODE_ENV=test mocha` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3696 | `npm run lint && npm run mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 3692 | `mocha; jshint *.js lib` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3675 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3639 | `npm run jshint && npm run mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3599 | `nyc mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3588 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3554 | `npm run lint ; mocha && mocha test/individual` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3548 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3544 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3527 | `mocha tests/javascript` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3441 | `mocha --reporter spec --timeout 3000` | 
| [primus/primus](https://github.com/primus/primus) | 3435 | `npm run build && mocha test/*.test.js` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3426 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3417 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3389 | `mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3389 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3389 | `mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3389 | `node_modules/.bin/mocha test/lib/` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3377 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3333 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3272 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3267 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3235 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3219 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3167 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3155 | `mocha --check-leaks --reporter spec --bail` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3100 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3094 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3068 | `mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3068 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3054 | `./node_modules/.bin/mocha test/test.*.js` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3024 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 3010 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3009 | `mocha ./test/*.spec.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3007 | `node_modules/.bin/mocha test/tests.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2961 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2924 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2918 | `mocha` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2914 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2900 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2900 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2849 | `mocha test/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2812 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2795 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2779 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2763 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2759 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2756 | `mocha --require should --reporter spec` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2735 | `mocha -R spec --recursive src/test` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 2733 | `NODE_ENV=test mocha test/**/*.js` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2717 | `mocha` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2707 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2705 | `istanbul cover _mocha` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2614 | `mocha` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2601 | `xo && mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2596 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2590 | `mocha --timeout 100000` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2589 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2581 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2579 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2569 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2561 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2561 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2561 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2555 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2550 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2536 | `mocha --opts mocha.opts` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2535 | `npm run compile && mocha --require babel-core/register` | 
| [css/csso](https://github.com/css/csso) | 2530 | `mocha --reporter dot` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2524 | `npm run mocha && npm run lint` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2523 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2509 | `export TESTING=true; mocha --reporter list` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2502 | `mocha --recursive --watch` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2495 | `mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2487 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2473 | `mocha --compilers js:babel-register --recursive spec` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2536 | `mocha --opts mocha.opts` | 
| [hilongjw/vue-lazyload](https://github.com/hilongjw/vue-lazyload) | 2535 | `npm run compile && mocha --require babel-core/register` | 
| [css/csso](https://github.com/css/csso) | 2530 | `mocha --reporter dot` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2524 | `npm run mocha && npm run lint` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2523 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2509 | `export TESTING=true; mocha --reporter list` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2502 | `mocha --recursive --watch` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2495 | `mocha` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2487 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2473 | `mocha --compilers js:babel-register --recursive spec` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2436 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2418 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2415 | `mocha --reporter=spec test/*-test.js` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2409 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2406 | `mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2393 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2365 | `node node_modules/mocha/bin/_mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2351 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2345 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2331 | `mocha` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2328 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2322 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2322 | `grunt jshint && mocha` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2309 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2296 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2288 | `NODE_ENV=test mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2276 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2274 | `mocha test` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2265 | `node_modules/.bin/mocha --reporter spec` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2264 | `nyc mocha 'test/**/*-test.js'` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2262 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [mozilla/send](https://github.com/mozilla/send) | 2258 | `mocha test/unit` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2256 | `npm run build && cd test && mocha . --reporter dot` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2220 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2217 | `mocha test test/unit/**/*_test.js` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2208 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2208 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [json5/json5](https://github.com/json5/json5) | 2202 | `mocha --ui exports --reporter spec` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2190 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2181 | `mocha` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2163 | `mocha test/unit --require mochahook` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2158 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2149 | `npm run lint && npm run build && npm run mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2141 | `mocha -R spec` | 
| [gajus/swing](https://github.com/gajus/swing) | 2123 | `mocha --compilers js:babel-register` | 
| [mde/ejs](https://github.com/mde/ejs) | 2119 | `mocha --require should --reporter spec` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2103 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2103 | `mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2081 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2040 | `cross-env BABEL_ENV=test mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2035 | `mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2033 | `nyc --reporter=html --reporter=text mocha` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2020 | `export TESTING=true; mocha --reporter list` | 
| [slate/slate](https://github.com/slate/slate) | 2020 | `BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2000 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 1970 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [sandeepmistry/noble](https://github.com/sandeepmistry/noble) | 1965 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1948 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1940 | `mocha && eslint .` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1924 | `mocha --require=test/test_helper.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1910 | `mocha test.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1898 | `mocha --bail --reporter spec --check-leaks test/` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1887 | `mocha -R landing test/index` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1884 | `mocha` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1884 | `mocha test && npm run lint` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1879 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1876 | `mocha test/index.js --reporter dot` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1872 | `mocha -c test/index.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1862 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1848 | `mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 1846 | `mocha` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1832 | `mocha tests.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1830 | `mocha --require ./test/common --growl test/expect.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1824 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1817 | `mocha --reporter spec --timeout 5000` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1805 | `mocha --timeout 5000` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1803 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1794 | `mocha --compilers js:babel-register` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1787 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1778 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1776 | `cross-env NODE_ENV=test mocha` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1767 | `mocha test/runner.js --reporter spec` | 
| [then/promise](https://github.com/then/promise) | 1761 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1751 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1747 | `mocha test` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 1747 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1745 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1742 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1735 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1735 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1732 | `mocha --compilers js:babel-core/register __tests__` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1726 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1725 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [kach/nearley](https://github.com/kach/nearley) | 1718 | `mocha test/*.test.js` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1700 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1697 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1697 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1694 | `mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1693 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1691 | `npm run jshint && mocha --recursive` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1686 | `npm run lint && mocha --reporter spec test/*.js` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1686 | `mocha` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1685 | `mocha test` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1675 | `mocha && eslint *.js` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 1669 | `./node_modules/.bin/mocha && npm run jshint` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1662 | `mocha` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1661 | `npm run lint && mocha -R dot && npm run cover` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1657 | `./node_modules/.bin/mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1652 | `npm run lint && mocha --recursive --exit` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1647 | `./node_modules/mocha/bin/mocha -R spec` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1643 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1641 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1639 | `mocha --reporter spec && npm run test-typescript` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1638 | `mocha -R spec spec spec/reporters` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1636 | `npm run lint && npm run mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1632 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1625 | `npm run mocha && npm run karma` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1613 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1610 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1608 | `mocha tests/test.js` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1602 | `mocha --expose-gc --slow 300` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1600 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1592 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1576 | `mocha && npm run lint` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1575 | `nyc npm run _mocha` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1570 | `mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1567 | `mocha test/*.js` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1550 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1547 | `npm run lint && mocha` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1545 | `./node_modules/.bin/mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1545 | `mocha --reporter spec --grep .` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1541 | `npm run mocha && npm run lint` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1540 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1539 | `mocha tests --compilers js:babel-core/register` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1531 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1520 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1515 | `mocha` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1513 | `mocha test/` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1513 | `mocha spec/` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1512 | `mocha test -u bdd -R spec` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1512 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1507 | `mocha ./test/basic.js -t 5000` | 
| [pahen/madge](https://github.com/pahen/madge) | 1505 | `npm run lint && npm run mocha` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1503 | `mocha test/* --reporter spec` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1496 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1496 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1479 | `mocha --reporter spec test/*.js` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1477 | `mocha` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1469 | `npm run test:lint && npm run test:mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1469 | `./node_modules/mocha/bin/mocha -R spec` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1466 | `mocha -R spec` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1466 | `npm run lint && npm run mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1462 | `mocha -u tdd` | 
| [thejameskyle/babel-react-optimize](https://github.com/thejameskyle/babel-react-optimize) | 1457 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1447 | `node_modules/.bin/mocha --recursive` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1435 | `mocha --reporter spec` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1430 | `mocha test/tests.js --timeout=10000` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1415 | `mocha test --timeout 600000` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1415 | `mocha test/**/*.spec.js` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1406 | `standard "src/*.js" && npm run build && mocha` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1406 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1403 | `mocha test.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1391 | `mocha --compilers js:babel-register` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1377 | `nyc mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1374 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1371 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1363 | `eslint --cache . && tsc && mocha` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1362 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1362 | `mocha --check-leaks -R dot` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1361 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1359 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1358 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1349 | `mocha test.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1346 | `standard "./src/*.js" && mocha` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1346 | `./node_modules/mocha/bin/mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1332 | `mocha --recursive` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1326 | `cross-env NODE_ENV=test nyc mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1317 | `mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1311 | `istanbul cover _mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1310 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1298 | `mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1283 | `mocha-phantomjs tests/index.html` | 
| [zeit/ms](https://github.com/zeit/ms) | 1281 | `mocha tests.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1279 | `mocha --check-leaks --reporter spec --bail` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1268 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1268 | `mocha --timeout 10000 ./tests/lib.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1265 | `npm run build && mocha -r should` | 
| [sandeepmistry/bleno](https://github.com/sandeepmistry/bleno) | 1264 | `mocha -R spec test/*.js` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1261 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1261 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1255 | `mocha` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1245 | `./node_modules/.bin/mocha test` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1236 | `mocha compiled_tests/` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1233 | `mocha spec/exec.js` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1232 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1232 | `mocha test/setup.js test/spec/*.js` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1231 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [electron/devtron](https://github.com/electron/devtron) | 1223 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1217 | `npm run lint && npm run mocha` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1210 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1209 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1207 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1204 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1203 | `mocha test/*.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1201 | `mocha test/test.js` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1198 | `mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1197 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1197 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1191 | `istanbul cover _mocha test -- --timeout 20000` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1191 | `istanbul cover _mocha test -- --timeout 20000` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1186 | `mocha test/**/*Spec.js` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1186 | `mocha` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1185 | `eslint . && mocha -t 5000` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1185 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1180 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1178 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1171 | `mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1170 | `mocha --recursive` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1169 | `mocha test` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1165 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1165 | `mocha` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1158 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1157 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1155 | `mocha --check-leaks --require @babel/register` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1148 | `node ./node_modules/mocha/bin/mocha tests` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1146 | `mocha --opts test/opts/mocha.opts` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1143 | `eslint lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1143 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1138 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1131 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1127 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1112 | `mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1102 | `mocha --reporter spec` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1101 | `npm run lint && npm run mocha` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1100 | `mocha` | 
| [variety/variety](https://github.com/variety/variety) | 1098 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1097 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1092 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1091 | `mocha` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1091 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1090 | `mocha src/test.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1088 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1088 | `node_modules/.bin/mocha && npm run lint` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1081 | `nodeunit test; mocha test` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1077 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1076 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1076 | `standard && istanbul cover _mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1074 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1073 | `mocha --reporter dot` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1068 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1068 | `node_modules/.bin/mocha` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1067 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1065 | `mocha test/unit` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1065 | `mocha --compilers js:babel-register` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1065 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1064 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1064 | `mocha --check-leaks -t 20000` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1061 | `mocha test/*` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1059 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1057 | `eslint src && mocha && karma start --single-run` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1050 | `mocha $(find test -name '*.test.js')` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1048 | `mocha --reporter spec --timeout 3000` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1047 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1044 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1042 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1039 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1038 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1035 | `xo && mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1028 | `istanbul test _mocha` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1023 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1020 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1020 | `mocha --check-leaks --reporter spec --bail test/` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1019 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1018 | `mocha --check-leaks -R dot` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1017 | `mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1013 | `NODE_PATH=. mocha **/*.spec.js` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1012 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1008 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1002 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 997 | `mocha test` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 995 | `istanbul cover _mocha test/*.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 993 | `mocha test/tests.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 991 | `mocha` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 990 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 987 | `mocha tests/test-*` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 986 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 985 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 983 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 981 | `mocha --colors ./test/*.spec.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 980 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 976 | `mocha` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 966 | `mocha --recursive --bail --reporter spec test` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 964 | `mocha` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 960 | ` NODE_ENV=test mocha --compilers js:babel-register` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 958 | `npm run rollup-cjs && mocha test/test.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 957 | `mocha --timeout 5000` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 956 | `standard && mocha` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 956 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 954 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 952 | `mocha -R list` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 952 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 948 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 948 | `npm run prepublish && mocha test/test.js` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 947 | `mocha $(find test -name '*.test.js')` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 942 | `mocha --recursive test/unit/` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 939 | `mocha --async-only` | 
| [router5/router5](https://github.com/router5/router5) | 937 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 932 | `mocha --reporter spec` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 932 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 930 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 881 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 881 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [electron/asar](https://github.com/electron/asar) | 880 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 878 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 876 | `mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 876 | `mocha --reporter spec --bail --check-leaks test/` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 874 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 873 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 867 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 864 | `mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 864 | `mocha --reporter list` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 863 | `mocha "client.test" --compilers js:babel-register` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 862 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 858 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 857 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 852 | `mocha --compilers js:babel-register test/*.js` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 899 | `nyc mocha --timeout=20000 test.js` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 897 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 896 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 893 | `mocha` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 892 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 892 | `mocha --reporter spec --bail --check-leaks test/` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 891 | `./node_modules/.bin/mocha --globals angular,require` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 882 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 881 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 881 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [electron/asar](https://github.com/electron/asar) | 880 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 878 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 876 | `mocha` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 876 | `mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 876 | `mocha --reporter spec --bail --check-leaks test/` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 858 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 857 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 852 | `mocha --compilers js:babel-register test/*.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 851 | `mocha && standard` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 851 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 846 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 843 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 842 | `node_modules/.bin/mocha` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 842 | `nyc mocha --require @babel/register` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 836 | `eslint test && mocha --compilers js:babel/register` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 835 | `npm run lint && mocha -R spec` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 833 | `mocha --reporter spec --bail --check-leaks test/` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 833 | `mocha ./test/test*.js --reporter spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 833 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 832 | `npm run convertto:es5 && npm run mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 832 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 831 | `npm run lint && npm run mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 828 | `mocha` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 827 | `mocha --timeout 200000` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 826 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 823 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 821 | `mocha tests` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 820 | `node_modules/.bin/mocha test/spec` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 820 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 820 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 818 | `mocha tests/*.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 817 | `mocha -R spec ./test/unit/**` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 817 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 816 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 815 | `mocha ./test -R spec` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 814 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 813 | `mocha --reporter spec` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 812 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 812 | `mocha && ember test` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 808 | `npm run lint && mocha --compilers js:babel-register` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 800 | `mocha --check-leaks -t 20000` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 796 | `mocha` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 794 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffee-script --recursive regression/node-helper.coffee regression/src` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 787 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 784 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 783 | `mocha --reporter spec --bail --check-leaks test/` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 783 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 782 | `standard && standard ./bin/* && mocha` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 781 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 780 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 778 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 776 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 775 | `mocha` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 772 | `mocha -R spec` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 772 | `mocha` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 770 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 767 | `mocha -t 600000` | 
| [edsu/anon](https://github.com/edsu/anon) | 766 | `mocha --colors --reporter spec test.js` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 767 | `mocha -t 600000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 767 | `NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 767 | `istanbul cover -- _mocha --reporter spec` | 
| [edsu/anon](https://github.com/edsu/anon) | 766 | `mocha --colors --reporter spec test.js` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 766 | `mocha test --compilers js:babel-register` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 764 | `mocha` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 763 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 761 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 759 | `nyc mocha specs` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 759 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 758 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 757 | `mocha --async-only` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 756 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 754 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 752 | `xo && mocha -R spec` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 754 | `mocha` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 752 | `xo && mocha -R spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 752 | `mocha` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 746 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require babel-register --no-timeouts` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 744 | `mocha spec/*.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 743 | `mocha --ui tdd --require ./test/__setup` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 742 | `mocha --reporter list` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 742 | `./node_modules/.bin/mocha -R spec` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 736 | `mocha -R spec src/**/*_test.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 732 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 732 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 730 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 727 | `mocha --reporter spec` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 723 | `npm run mocha:istanbul` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 722 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 722 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 718 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 716 | `mocha test.js` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 714 | `mocha --recursive -s 15 test/` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 711 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 709 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 708 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 708 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 707 | `cross-env NODE_ENV=test nyc mocha` | 
| [3Dparallax/insight](https://github.com/3Dparallax/insight) | 707 | `mocha test` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 706 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 703 | `mocha` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 700 | `eslint src test && mocha --compilers babel-register` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 698 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 697 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 697 | `npm run bundle && mocha` | 
| [bitpay/insight](https://github.com/bitpay/insight) | 696 | `mocha test` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 695 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 693 | `npm run mocha-test test/integration` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 691 | `mocha tests/*.mocha.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 689 | `mocha test` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 684 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 683 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 682 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 682 | `npm run build && istanbul test _mocha test/test.js` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 682 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 681 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 680 | `npm run lint && mocha test` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 679 | `mocha ./test/index.js` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 679 | `mocha test` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 678 | `mocha` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 677 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 675 | `mocha` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 673 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 673 | `mocha --reporter spec` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 672 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 
| [developit/decko](https://github.com/developit/decko) | 670 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [moreartyjs/moreartyjs](https://github.com/moreartyjs/moreartyjs) | 670 | `mocha -b -R spec test/*` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 668 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 663 | `mocha` | 
| [themeteorchef/base](https://github.com/themeteorchef/base) | 663 | `meteor test --driver-package practicalmeteor:mocha --port 5000` | 
| [gre/bezier-easing](https://github.com/gre/bezier-easing) | 663 | `mocha` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 662 | `mocha --reporter spec` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 662 | `mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 661 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 660 | `mocha --no-timeouts` | 