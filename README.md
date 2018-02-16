# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:07:07 02/16/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39763 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 39298 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [webpack/webpack](https://github.com/webpack/webpack) | 37125 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation` | 
| [expressjs/express](https://github.com/expressjs/express) | 36659 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28786 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23383 | `npm run lint && npm run mocha-node-test` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 20694 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 19145 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 17702 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17519 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15569 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 14850 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13793 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 13057 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12665 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12059 | `mocha 'test/**/*.spec.js'` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12042 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 11999 | `mocha` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11688 | `mocha --reporter spec test/*-test.js` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11672 | `./node_modules/.bin/mocha test/` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 11248 | `cross-env BABEL_ENV=commonjs NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 10968 | `mocha --reporter spec` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10579 | `nyc grunt mocha-and-karma` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 10453 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 9955 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9637 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9485 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 9312 | `mocha --harmony` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9252 | `mocha test/index.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9241 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9114 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9013 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8878 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8524 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8374 | `mocha test/*-test.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8296 | `mocha` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8141 | `mocha --check-leaks -R dot` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8130 | `mocha test/test.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8075 | `grunt clean:test && mocha --exit` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 7902 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7830 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7787 | `./node_modules/.bin/mocha test/src` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7735 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7691 | `mocha --compilers js:babel-register test/test.js` | 
| [websockets/ws](https://github.com/websockets/ws) | 7676 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7438 | `mocha` | 
| [dthree/cash](https://github.com/dthree/cash) | 7436 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7436 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js` | 
| [amark/gun](https://github.com/amark/gun) | 7384 | `mocha` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7339 | `npm run eslint && npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7231 | `mocha tests/*.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7154 | `npm run build && istanbul cover _mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7107 | `./node_modules/.bin/mocha test` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 6878 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6820 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6596 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6552 | `mocha $HARMONY_OPTS` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6495 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6431 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6354 | `mocha --opts mocha.opts` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6349 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6306 | `nyc mocha test/**/* -r ./test/before` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6259 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [almende/vis](https://github.com/almende/vis) | 6249 | `mocha --compilers js:babel-core/register` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6205 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack) | 6136 | `mocha test/*.test.js test/*.unittest.js --max-old-space-size=4096 --harmony --trace-deprecation` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5941 | `npm run jshint -s && npm run mocha -s` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5923 | `mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5832 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5785 | `npm run test:mocha:src` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5709 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5687 | `npm run jshint && mocha test/` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5488 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5486 | `mocha tests/node.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5446 | `mocha test --recursive` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5386 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5365 | `mocha && eslint lib/**` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5331 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5316 | `mocha test/test.js` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5161 | `mocha --color` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5138 | `mocha src/**/*Tests.js --harmony` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5110 | `mocha --timeout 10000 && npm run lint` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5083 | `mocha --exit --require babel-core/register` | 
| [mozilla/nunjucks](https://github.com/mozilla/nunjucks) | 4990 | `jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 4976 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4768 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4736 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4689 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4666 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [santinic/how2](https://github.com/santinic/how2) | 4623 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4609 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4607 | `mocha --reporter spec -t 8000` | 
| [reduxactions/redux-actions](https://github.com/reduxactions/redux-actions) | 4567 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 4552 | `npm run build-cli && mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4536 | `mocha ./test/runner.js` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 4460 | `mocha` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4457 | `gulp build; mocha;` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4429 | `standard && mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4388 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4387 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4377 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4333 | `mocha` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4333 | `./node_modules/.bin/mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4318 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4262 | `mocha` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4221 | `mocha -R spec ./test --recursive` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4195 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4193 | `mocha` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4155 | `mocha test` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4109 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 4066 | `mocha && ./bin/shipit staging test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 3997 | `nyc mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 3953 | `mocha; jshint *.js lib` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3893 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3864 | `mocha --require test/babel-hook test/*.js` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3848 | `export TESTING=true; mocha --reporter list` | 
| [muicss/mui](https://github.com/muicss/mui) | 3827 | `mocha` | 
| [erming/shout](https://github.com/erming/shout) | 3814 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3803 | `NODE_ENV=test mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3783 | `mocha --require should --reporter spec` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3743 | `npm run lint && npm run mocha` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3725 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3639 | `npm run jshint && npm run mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3635 | `nyc mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3607 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3595 | `npm run lint ; mocha && mocha test/individual` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3550 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3544 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3529 | `mocha tests/javascript` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3462 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [primus/primus](https://github.com/primus/primus) | 3459 | `npm run build && mocha test/*.test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3450 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3428 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3403 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3397 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3395 | `mocha` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3391 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3390 | `node_modules/.bin/mocha` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3345 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3282 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3281 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3220 | `mocha --check-leaks --reporter spec --bail` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3200 | `npm run lint && npm run mocha` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3192 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3178 | `mocha ./test/*.spec.js` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3131 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3127 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3095 | `mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3084 | `nyc mocha "test/**/*.test.js"` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3079 | `yarn run build:cjs && mocha --require babel-core/register ./test/index.js` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3070 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3062 | `./node_modules/.bin/mocha test/test.*.js` | 
| [expressjs/session](https://github.com/expressjs/session) | 3057 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3019 | `node_modules/.bin/mocha test/tests.js` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2966 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 2963 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2943 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2934 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2925 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2876 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2865 | `mocha test/*.js` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2851 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2830 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 2784 | `NODE_ENV=test mocha test/**/*.js` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2774 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2768 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2757 | `mocha --require should --reporter spec` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2743 | `mocha -R spec --recursive src/test` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2742 | `mocha` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2735 | `nyc mocha && tsc` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2719 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2718 | `istanbul cover _mocha` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2717 | `mocha test/index.js && npm run demo` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2707 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2696 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2690 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2670 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [github-tools/github](https://github.com/github-tools/github) | 2670 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2666 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [tj/should.js](https://github.com/tj/should.js) | 2666 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2649 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2647 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2638 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2628 | `mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2619 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2610 | `mocha` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2610 | `xo && mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2604 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2598 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2596 | `mocha --timeout 100000` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2581 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2579 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2578 | `mocha-phantomjs ./test/index.html` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2578 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2573 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2567 | `mocha --opts mocha.opts` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2546 | `npm run mocha && npm run lint` | 
| [css/csso](https://github.com/css/csso) | 2541 | `mocha --reporter dot` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2517 | `export TESTING=true; mocha --reporter list` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2516 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2505 | `mocha --recursive --watch` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2499 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2491 | `mocha --compilers js:babel-register --recursive spec` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2487 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2460 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2448 | `mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2437 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2423 | `mocha --reporter=spec test/*-test.js` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2407 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2395 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2380 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2368 | `node node_modules/mocha/bin/_mocha` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2368 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2337 | `NODE_ENV=test mocha` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2331 | `mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2327 | `mocha --no-colors --reporter spec` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2323 | `grunt jshint && mocha` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2322 | `mocha -t 30000 -R spec tests/unit/index.js` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2317 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2314 | `node_modules/.bin/mocha --reporter spec` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2305 | `nyc mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2296 | `nyc mocha 'test/**/*-test.js'` | 
| [mozilla/send](https://github.com/mozilla/send) | 2292 | `mocha test/unit` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2290 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2290 | `mocha test` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2279 | `npm run build && cd test && mocha . --reporter dot` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2261 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2260 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [json5/json5](https://github.com/json5/json5) | 2239 | `mocha --ui exports --reporter spec` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2220 | `mocha test test/unit/**/*_test.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2217 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2211 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2199 | `mocha` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2198 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2184 | `mocha test/unit --require mochahook` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2179 | `npm run lint && npm run build && npm run mocha` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2176 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2175 | `mocha "test/**/*-test.js"` | 
| [mde/ejs](https://github.com/mde/ejs) | 2162 | `mocha --require should --reporter spec` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2153 | `mocha -R spec` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2134 | `mocha` | 
| [gajus/swing](https://github.com/gajus/swing) | 2134 | `mocha --compilers js:babel-register` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2130 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2112 | `export TESTING=true; mocha --reporter list` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2083 | `mocha` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2051 | `cross-env BABEL_ENV=test mocha` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2047 | `nyc --reporter=html --reporter=text mocha` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2036 | `mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2027 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2023 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2018 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [slate/slate](https://github.com/slate/slate) | 2018 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [noble/noble](https://github.com/noble/noble) | 1991 | `mocha -R spec test/*.js` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 1976 | `mocha test.js` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 1975 | `mocha && eslint .` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 1971 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 1948 | `mocha -R landing test/index` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1927 | `mocha --require=test/test_helper.js` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1917 | `mocha test && npm run lint` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1903 | `mocha` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1902 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1900 | `mocha --bail --reporter spec --check-leaks test/` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1890 | `mocha -c test/index.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1884 | `mocha test/index.js --reporter dot` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1882 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [Qix-/color](https://github.com/Qix-/color) | 1868 | `mocha` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1861 | `mocha` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1846 | `mocha --require ./test/common --growl test/expect.js` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1842 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1841 | `mocha tests.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1838 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1832 | `mocha --reporter spec --timeout 5000` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1821 | `mocha --compilers js:babel-register` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1820 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1804 | `mocha --timeout 5000` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1804 | `mocha --timeout 5000` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1793 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1790 | `mocha test/runner.js --reporter spec` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1789 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1785 | `cross-env NODE_ENV=test mocha` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1774 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [then/promise](https://github.com/then/promise) | 1767 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1760 | `mocha --compilers js:babel-core/register __tests__` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1755 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1751 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1750 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1749 | `mocha test` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1748 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1747 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1737 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1734 | `mocha test/**/*_test.js --bail` | 
| [kach/nearley](https://github.com/kach/nearley) | 1727 | `mocha test/*.test.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1724 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1711 | `mocha` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1705 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1702 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [share/sharedb](https://github.com/share/sharedb) | 1702 | `./node_modules/.bin/mocha && npm run jshint` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1701 | `mocha && eslint *.js` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1700 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1699 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1699 | `mocha test` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1696 | `npm run lint && mocha -R dot && npm run cover` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1689 | `npm run jshint && mocha --recursive` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1688 | `mocha` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1673 | `npm run lint && mocha server/test --recursive --exit` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1670 | `xo && mocha` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1668 | `./node_modules/mocha/bin/mocha -R spec` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1663 | `./node_modules/.bin/mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1663 | `mocha --reporter spec && npm run test-typescript` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1662 | `npm run mocha && npm run karma` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1662 | `mocha` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 1659 | `node ./node_modules/mocha/bin/mocha --reporter spec --full-trace` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1658 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1652 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1647 | `mocha -R spec spec spec/reporters` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1643 | `npm run lint && npm run mocha` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [shouldjs/should.js](https://github.com/shouldjs/should.js) | 1625 | `mocha -R mocha-better-spec-reporter --require ./cjs/should --color --check-leaks ./test/*.test.js ./test/**/*.test.js` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1624 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1619 | `nyc npm run _mocha` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1609 | `mocha tests/test.js` | 
| [iurimatias/embark-framework](https://github.com/iurimatias/embark-framework) | 1606 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1604 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1604 | `mocha --expose-gc --slow 300` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1603 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1600 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1593 | `mocha && npm run lint` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1577 | `mocha test/*.js` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1570 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1566 | `mocha --reporter spec --grep .` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1564 | `mocha` | 
| [slackapi/node-slack-sdk](https://github.com/slackapi/node-slack-sdk) | 1562 | `npm run mocha && npm run lint` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1562 | `npm run lint && mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1559 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1556 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1554 | `mocha tests --compilers js:babel-core/register` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1545 | `./node_modules/.bin/mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1545 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [pahen/madge](https://github.com/pahen/madge) | 1540 | `npm run lint && npm run mocha` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1535 | `mocha test -u bdd -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1528 | `mocha test/` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1526 | `mocha` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1523 | `mocha ./test/basic.js -t 5000` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1519 | `mocha test/* --reporter spec` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1518 | `mocha spec` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1499 | `mocha --reporter spec test/*.js` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1498 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1495 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1491 | `mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1478 | `mocha test --timeout 600000` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1476 | `npm run lint && npm run mocha` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1476 | `./node_modules/mocha/bin/mocha -R spec` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1475 | `npm run test:lint && npm run test:mocha` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1471 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1467 | `mocha -R spec` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1464 | `mocha -u tdd` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1456 | `standard "src/*.js" && npm run build && mocha` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1449 | `node_modules/.bin/mocha --recursive` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1442 | `mocha --reporter spec` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1434 | `mocha` | 
| [samccone/drool](https://github.com/samccone/drool) | 1432 | `mocha test/tests.js --timeout=10000` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1423 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1413 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1411 | `mocha --compilers js:babel-register` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1404 | `mocha test.js` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1387 | `nyc mocha` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1384 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1383 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1382 | `mocha --check-leaks -R dot` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1379 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1378 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1373 | `eslint --cache . && tsc && mocha` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1367 | `mocha test.js` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1362 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1360 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1358 | `standard "./src/*.js" && mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1349 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1348 | `./node_modules/mocha/bin/mocha` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1340 | `mocha --recursive` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1326 | `cross-env NODE_ENV=test nyc mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1325 | `mocha` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1321 | `istanbul cover _mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1319 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1316 | `mocha tests.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1302 | `mocha --check-leaks --reporter spec --bail` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1301 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1292 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1289 | `mocha-phantomjs tests/index.html` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1283 | `mocha` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1279 | `mocha --timeout 10000 ./tests/lib.js` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1277 | `eslint . && mocha -t 5000` | 
| [noble/bleno](https://github.com/noble/bleno) | 1277 | `mocha -R spec test/*.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1275 | `npm run build && mocha -r should` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1261 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1260 | `mocha compiled_tests/` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1259 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1255 | `mocha test/setup.js test/spec/*.js` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1253 | `./node_modules/.bin/mocha test` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1243 | `mocha spec/exec.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1240 | `npm run lint && npm run mocha` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1237 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [electron/devtron](https://github.com/electron/devtron) | 1232 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1226 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1222 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1222 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1213 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1213 | `istanbul cover _mocha test -- --timeout 20000` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1212 | `mocha tests` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1209 | `mocha test/*.js` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1205 | `mocha test/test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1204 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1197 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1193 | `mocha test/**/*Spec.js` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1192 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1186 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1185 | `mocha` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1182 | `mocha --recursive` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1181 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1180 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1175 | `mocha --check-leaks --require @babel/register` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1175 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1170 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1170 | `mocha test` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1163 | `mocha --opts test/opts/mocha.opts` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1161 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1155 | `node ./node_modules/mocha/bin/mocha tests` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1150 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1148 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1146 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1138 | `mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1125 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1121 | `mocha` | 
| [patriksimek/node-mssql](https://github.com/patriksimek/node-mssql) | 1119 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1111 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1110 | `npm run lint && npm run mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1109 | `mocha --reporter spec` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1100 | `mocha src/test.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1100 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [variety/variety](https://github.com/variety/variety) | 1100 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1097 | `standard && istanbul cover _mocha` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1096 | `mocha test/unit` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1094 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1094 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1094 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1093 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1093 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1092 | `mocha --reporter dot` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1089 | `node_modules/.bin/mocha && npm run lint` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1088 | `node_modules/.bin/mocha` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1083 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1083 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1082 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1080 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1079 | `eslint src && mocha && karma start --single-run` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1074 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1067 | `mocha --check-leaks -t 20000` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1066 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1065 | `mocha --compilers js:babel-register` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1064 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1062 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1061 | `mocha test/*` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1057 | `mocha $(find test -name '*.test.js')` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1054 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1050 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1049 | `xo && mocha` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1047 | `mocha --reporter spec --timeout 3000` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1046 | `mocha test` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1043 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1040 | `NODE_ENV=test mocha-webpack --opts test/mocha-webpack.opts` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1034 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1033 | `mocha` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1032 | `istanbul test _mocha` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1030 | `mocha --check-leaks --reporter spec --bail test/` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1028 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1020 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1017 | `NODE_PATH=. mocha **/*.spec.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1015 | `mocha --check-leaks -R dot` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1013 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1010 | `istanbul cover _mocha test/*.js` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1008 | `mocha tests/test-*` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1003 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 999 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 999 | `mocha test/tests.js` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 997 | `mocha` | 
| [teambit/bit](https://github.com/teambit/bit) | 993 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 991 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 989 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 987 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 985 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 983 | `mocha --colors ./test/*.spec.js` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 980 | `mocha` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 976 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 975 | `nyc mocha --timeout=20000 test.js` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 974 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 972 | `mocha --recursive --bail --reporter spec test` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 971 | `mocha` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 970 | `npm run prepublish && mocha test/test.js` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 969 | `standard && mocha` | 
| [lukasoppermann/html5sortable](https://github.com/lukasoppermann/html5sortable) | 960 | `mocha test/umd/module.js && mocha test/*.js && npm run standard && npm run standard-test && standard-readme` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 960 | `npm run rollup-cjs && mocha test/test.js` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 960 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 959 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 954 | `mocha -R list` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 954 | `mocha --timeout 5000` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 950 | `mocha $(find test -name '*.test.js')` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 948 | `mocha --recursive test/unit/` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 947 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [router5/router5](https://github.com/router5/router5) | 946 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 943 | `mocha --async-only` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 942 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 942 | `mocha` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 938 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 937 | `mocha --reporter spec` | 
| [tomas/needle](https://github.com/tomas/needle) | 936 | `mocha test` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 933 | `mocha -t 120000 test/*.test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 932 | `mocha --recursive test` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 930 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 929 | `standard && mocha -b` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 928 | `mocha --compilers js:babel-core/register` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 925 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 922 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 914 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 914 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 912 | `webpack && mocha test/unit` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 905 | `nyc mocha` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 904 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [electron/asar](https://github.com/electron/asar) | 899 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 897 | `mocha` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 896 | `mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 892 | `mocha --reporter spec --bail --check-leaks test/` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 891 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 890 | `./node_modules/.bin/mocha --globals angular,require` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 887 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [kriasoft/universal-router](https://github.com/kriasoft/universal-router) | 886 | `nyc mocha --require @babel/register` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 882 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 879 | `mocha` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 877 | `mocha ./test/test*.js --reporter spec` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 877 | `mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 877 | `mocha "client.test" --compilers js:babel-register` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 876 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 873 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 871 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [electron/spectron](https://github.com/electron/spectron) | 869 | `mocha && standard` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 867 | `mocha --compilers js:babel-register test/*.js` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 865 | `mocha -R spec ./test/unit/**` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 865 | `mocha --reporter list` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 862 | `mocha tests/*.js` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 860 | `mocha` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 859 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 858 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 857 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 853 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 850 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 848 | `node_modules/.bin/mocha` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 846 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 845 | `mocha --reporter spec --bail --check-leaks test/` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 845 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 845 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 844 | `mocha` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 842 | `npm run convertto:es5 && npm run mocha` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 841 | `npm run lint && mocha -R spec` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 840 | `mocha` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 838 | `eslint test && mocha --compilers js:babel/register` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 835 | `npm run lint && npm run mocha` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 833 | `mocha ./test -R spec` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 829 | `mocha tests` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 829 | `mocha --timeout 200000` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 825 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 825 | `mocha` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 824 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 823 | `npm run lint && mocha --compilers js:babel-register` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 822 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [testdouble/testdouble.js](https://github.com/testdouble/testdouble.js) | 821 | `mocha --ui mocha-given --reporter $npm_package_config_mocha_reporter --compilers js:babel-core/register,coffee:coffeescript --recursive regression/node-helper.coffee regression/src` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 820 | `node_modules/.bin/mocha test/spec` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 818 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 817 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 817 | `mocha && ember test` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 815 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 813 | `mocha --reporter spec` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 812 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 810 | `mocha tests/*.test.js --reporter spec` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 803 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 803 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 802 | `mocha --check-leaks -t 20000` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 799 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 797 | `istanbul cover _mocha` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 797 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 797 | `mocha -R spec` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 796 | `eslint src test && mocha --compilers babel-register` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 793 | `mocha --require babel-register` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 792 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 791 | `mocha -R spec tests/` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 791 | `standard && standard ./bin/* && mocha` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 789 | `mocha` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 788 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 787 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 787 | `npm run lint && npm run mocha` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 785 | `nyc mocha` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 785 | `mocha -t 5000` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 783 | `mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 780 | `mocha -t 600000` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 780 | `cake build && mocha ./test/mocha/*.coffee` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 778 | `mocha test --compilers js:babel-register` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 777 | `mocha` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 776 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 775 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 774 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 773 | `mocha` | 
| [edsu/anon](https://github.com/edsu/anon) | 772 | `mocha --colors --reporter spec test.js` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 771 | `istanbul cover -- _mocha --reporter spec` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 767 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 766 | `nyc mocha specs` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 765 | `mocha` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 765 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 764 | `npm run lint && mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 762 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 762 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 761 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 760 | `mocha --async-only` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 757 | `mocha spec/*.js` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 756 | `xo && mocha -R spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 756 | `mocha` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 752 | `./node_modules/.bin/mocha -R spec` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 751 | `mocha --reporter list` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 747 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 746 | `mocha --ui tdd --require ./test/__setup` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 739 | `npm run mocha:istanbul` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 739 | `mocha -R spec src/**/*_test.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 736 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 734 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 732 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 730 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 727 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 727 | `mocha --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 723 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [bitpay/insight](https://github.com/bitpay/insight) | 723 | `mocha test` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 721 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 720 | `mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 719 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 718 | `cross-env NODE_ENV=test nyc mocha` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 717 | `mocha --recursive -s 15 test/` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 717 | `mocha test.js` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 716 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 712 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 709 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 708 | `mocha` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 707 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 705 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 702 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 701 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 701 | `npm run bundle && mocha` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 699 | `npm run mocha-test test/integration` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 697 | `mocha test` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 697 | `mocha tests/*.mocha.js` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 695 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 691 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 689 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 689 | `npm run build && istanbul test _mocha test/test.js` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 687 | `mocha test` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 683 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 681 | `NODE_PATH=src nyc mocha --timeout 10s --compilers js:babel-register --recursive test/auto/node test/manual` | 
| [developit/decko](https://github.com/developit/decko) | 681 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 681 | `mocha` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 680 | `mocha ./test/index.js` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 678 | `npm run lint && mocha test` | 
| [ericmdantas/generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) | 676 | `npm run lint && mocha test/ --recursive -R dot --check-leaks --require babel-core/register` | 