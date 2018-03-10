# Find Repos in JavaScript Tested using Mocha

The list was updated at 02:06:54 03/10/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 39956 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [socketio/socket.io](https://github.com/socketio/socket.io) | 39778 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 37071 | `mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 28930 | `mocha --async-only` | 
| [caolan/async](https://github.com/caolan/async) | 23500 | `npm run lint && npm run mocha-node-test` | 
| [lord/slate](https://github.com/lord/slate) | 22404 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 21010 | `mocha test/index.js` | 
| [parcel-bundler/parcel](https://github.com/parcel-bundler/parcel) | 20208 | `cross-env NODE_ENV=test mocha` | 
| [developit/preact](https://github.com/developit/preact) | 17969 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 17685 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 15682 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 15066 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 13878 | `nyc --reporter=html --reporter=text mocha` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 13334 | `node_modules/.bin/mocha test/*.*.js` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 12796 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [keystonejs/keystone](https://github.com/keystonejs/keystone) | 12207 | `mocha && mocha --opts test/mocha-admin.opts` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 12150 | `mocha 'test/**/*.spec.js'` | 
| [node-inspector/node-inspector](https://github.com/node-inspector/node-inspector) | 12034 | `mocha` | 
| [isagalaev/highlight.js](https://github.com/isagalaev/highlight.js) | 11807 | `./node_modules/.bin/mocha test/` | 
| [janl/mustache.js](https://github.com/janl/mustache.js) | 11750 | `mocha --reporter spec test/*-test.js` | 
| [reactjs/react-redux](https://github.com/reactjs/react-redux) | 11557 | `cross-env BABEL_ENV=test NODE_ENV=test mocha --recursive --require babel-register --require ./test/setup.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 11247 | `mocha --reporter spec` | 
| [JedWatson/react-select](https://github.com/JedWatson/react-select) | 10722 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register` | 
| [strongloop/loopback](https://github.com/strongloop/loopback) | 10692 | `nyc grunt mocha-and-karma` | 
| [nswbmw/N-blog](https://github.com/nswbmw/N-blog) | 10185 | `istanbul cover _mocha` | 
| [chriso/validator.js](https://github.com/chriso/validator.js) | 9803 | `mocha --reporter spec` | 
| [winstonjs/winston](https://github.com/winstonjs/winston) | 9685 | `nyc mocha test/*.test.js test/**/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 9391 | `mocha --harmony` | 
| [jsdom/jsdom](https://github.com/jsdom/jsdom) | 9389 | `mocha test/index.js` | 
| [gaearon/redux-devtools](https://github.com/gaearon/redux-devtools) | 9349 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [NodeRedis/node_redis](https://github.com/NodeRedis/node_redis) | 9218 | `nyc --cache mocha ./test/*.js ./test/commands/*.js --timeout=8000` | 
| [svg/svgo](https://github.com/svg/svgo) | 9155 | `set NODE_ENV=test && mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 8937 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 8606 | `grunt mocha` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 8458 | `mocha test/*-test.js` | 
| [dcloudio/mui](https://github.com/dcloudio/mui) | 8451 | `mocha` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8176 | `mocha --check-leaks -R dot` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8165 | `mocha test/test.js` | 
| [gaearon/redux-thunk](https://github.com/gaearon/redux-thunk) | 8127 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8101 | `grunt clean:test && mocha --exit` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 7922 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [websockets/ws](https://github.com/websockets/ws) | 7884 | `eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 7882 | `./node_modules/.bin/mocha test/src` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 7791 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 7765 | `mocha --compilers js:babel-register test/test.js` | 
| [amark/gun](https://github.com/amark/gun) | 7670 | `mocha` | 
| [lovell/sharp](https://github.com/lovell/sharp) | 7618 | `semistandard && cc && nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js && prebuild-ci` | 
| [dthree/cash](https://github.com/dthree/cash) | 7459 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7437 | `mocha` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 7389 | `npm run eslint && npm run mocha` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 7374 | `mocha tests/*.js` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7198 | `npm run build && istanbul cover _mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 7186 | `./node_modules/.bin/mocha test` | 
| [auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) | 7021 | `mocha --require test/util/fakeDate && nsp check && cost-of-modules` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 6992 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 6797 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 6584 | `mocha $HARMONY_OPTS` | 
| [addyosmani/critical](https://github.com/addyosmani/critical) | 6550 | `xo && mocha test/*.js --timeout 100000` | 
| [aui/art-template](https://github.com/aui/art-template) | 6502 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 6474 | `nyc mocha test/**/* -r ./test/before` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 6473 | `mocha --opts mocha.opts` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 6459 | `eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 6384 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 6368 | `npm run pre_test && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape` | 
| [almende/vis](https://github.com/almende/vis) | 6349 | `mocha --compilers js:babel-core/register` | 
| [angular-fullstack/generator-angular-fullstack](https://github.com/angular-fullstack/generator-angular-fullstack) | 6000 | `mocha --require should --require babel-register --require ./mocha.conf --reporter spec --timeout 120000 test/pre.test.js test/*.test.js` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 5993 | `npm run lint -s && npm run mocha -s` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5927 | `mocha` | 
| [mediaelement/mediaelement](https://github.com/mediaelement/mediaelement) | 5880 | `./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --compilers js:babel-register --require babel-polyfill --recursive test/unit` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 5879 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [cazala/synaptic](https://github.com/cazala/synaptic) | 5853 | `npm run test:mocha:src` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 5759 | `npm run jshint && mocha test/` | 
| [visionmedia/page.js](https://github.com/visionmedia/page.js) | 5604 | `jshint index.js test/tests.js && mocha test/tests.js` | 
| [sockjs/sockjs-client](https://github.com/sockjs/sockjs-client) | 5521 | `mocha tests/node.js` | 
| [josdejong/mathjs](https://github.com/josdejong/mathjs) | 5514 | `mocha test --recursive` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5430 | `mocha && eslint lib/**` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 5404 | `mocha test/test.js` | 
| [matthew-andrews/isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) | 5390 | `jshint `npm run -s files` && lintspaces -i js-comments -e .editorconfig `npm run -s files` && mocha` | 
| [ExactTarget/fuelux](https://github.com/ExactTarget/fuelux) | 5390 | `xvfb-maybe mocha test/mocha.js && grunt travisci --verbose` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 5247 | `mocha --exit --require babel-core/register` | 
| [jscs-dev/node-jscs](https://github.com/jscs-dev/node-jscs) | 5165 | `mocha --color` | 
| [alvarcarto/url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) | 5159 | `mocha --timeout 10000 && npm run lint` | 
| [daniel-lundin/snabbt.js](https://github.com/daniel-lundin/snabbt.js) | 5139 | `mocha src/**/*Tests.js --harmony` | 
| [automerge/automerge](https://github.com/automerge/automerge) | 5071 | `mocha` | 
| [PrismJS/prism](https://github.com/PrismJS/prism) | 5034 | `mocha tests/testrunner-tests.js && mocha tests/run.js` | 
| [trufflesuite/truffle](https://github.com/trufflesuite/truffle) | 4985 | `npm run build-cli && mocha` | 
| [redux-observable/redux-observable](https://github.com/redux-observable/redux-observable) | 4796 | `npm run lint && npm run build && npm run build:tests && mocha temp && npm run test:typings` | 
| [assaf/zombie](https://github.com/assaf/zombie) | 4787 | `gulp lint && mocha` | 
| [deployd/deployd](https://github.com/deployd/deployd) | 4754 | `mocha --timeout 5000 --exit && cd test-app && node runtests.js` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 4744 | `npm run build && npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [redux-utilities/redux-actions](https://github.com/redux-utilities/redux-actions) | 4658 | `mocha --compilers js:babel-register src/**/*-test.js` | 
| [santinic/how2](https://github.com/santinic/how2) | 4639 | `mocha test` | 
| [rmurphey/js-assessment](https://github.com/rmurphey/js-assessment) | 4621 | `mocha -R spec 'tests/app'` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4621 | `mocha --reporter spec -t 8000` | 
| [expressjs/multer](https://github.com/expressjs/multer) | 4546 | `standard && mocha` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4533 | `mocha ./test/runner.js` | 
| [dthree/vorpal](https://github.com/dthree/vorpal) | 4521 | `gulp build; mocha;` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 4478 | `mocha` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 4449 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [gajus/react-css-modules](https://github.com/gajus/react-css-modules) | 4421 | `NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 4417 | `mocha; jshint *.js lib` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4395 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [prerender/prerender](https://github.com/prerender/prerender) | 4362 | `./node_modules/.bin/mocha` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 4353 | `mocha` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4315 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 4225 | `mocha test` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4224 | `mocha --compilers js:babel-register "test/**/*Test.js"` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4224 | `mocha -R spec ./test --recursive` | 
| [matthewmueller/x-ray](https://github.com/matthewmueller/x-ray) | 4221 | `mocha` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 4210 | `nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks` | 
| [shipitjs/shipit](https://github.com/shipitjs/shipit) | 4096 | `mocha && ./bin/shipit staging test` | 
| [peterramsing/lost](https://github.com/peterramsing/lost) | 4014 | `nyc mocha` | 
| [mattgodbolt/compiler-explorer](https://github.com/mattgodbolt/compiler-explorer) | 3940 | `mocha --recursive && make test` | 
| [Khan/tota11y](https://github.com/Khan/tota11y) | 3913 | `mocha --require test/babel-hook test/*.js` | 
| [Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) | 3895 | `istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 3871 | `NODE_ENV=test mocha` | 
| [muicss/mui](https://github.com/muicss/mui) | 3868 | `mocha` | 
| [CodeboxIDE/codebox](https://github.com/CodeboxIDE/codebox) | 3852 | `export TESTING=true; mocha --reporter list` | 
| [erming/shout](https://github.com/erming/shout) | 3808 | `HOME=test/fixtures mocha test/**/*.js && npm run lint` | 
| [agenda/agenda](https://github.com/agenda/agenda) | 3805 | `npm run lint && npm run mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 3804 | `mocha --require should --reporter spec` | 
| [paulmillr/chokidar](https://github.com/paulmillr/chokidar) | 3785 | `istanbul test node_modules/mocha/bin/_mocha` | 
| [ApoorvSaxena/lozad.js](https://github.com/ApoorvSaxena/lozad.js) | 3678 | `nyc mocha` | 
| [AliasIO/Wappalyzer](https://github.com/AliasIO/Wappalyzer) | 3678 | `mocha -R spec ./test` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 3648 | `npm run lint ; mocha && mocha test/individual` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3638 | `npm run jshint && npm run mocha` | 
| [jsbin/jsbin](https://github.com/jsbin/jsbin) | 3622 | `node_modules/mocha/bin/_mocha -t 25000 --ui bdd test/unit/**/*.test.js` | 
| [bfirsh/jsnes](https://github.com/bfirsh/jsnes) | 3601 | `mocha ./test/*.spec.js` | 
| [artf/grapesjs](https://github.com/artf/grapesjs) | 3559 | `cross-env NODE_PATH=./src mocha --compilers js:babel-core/register --require test/helper.js --timeout 10000 --recursive test/main.js` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3557 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3549 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3541 | `mocha tests/javascript` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 3532 | `mocha -r intelli-espower-loader -t 20000 test` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 3514 | `./node_modules/mocha/bin/mocha --reporter spec --bail --timeout 10000 tests/*.js` | 
| [primus/primus](https://github.com/primus/primus) | 3487 | `npm run build && mocha test/*.test.js` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3459 | `mocha --reporter spec --timeout 3000` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3440 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3406 | `node_modules/.bin/mocha` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3402 | `node_modules/.bin/mocha test/lib/` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3400 | `mocha` | 
| [saenzramiro/rambox](https://github.com/saenzramiro/rambox) | 3392 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3363 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server) | 3363 | `npm run lint && npm run mocha` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 3336 | `cross-env NODE_ENV=test BABEL_ENV=cjs mocha "src/**/*.spec.js"` | 
| [expressjs/morgan](https://github.com/expressjs/morgan) | 3291 | `mocha --check-leaks --reporter spec --bail` | 
| [node-serialport/node-serialport](https://github.com/node-serialport/node-serialport) | 3226 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 3187 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3180 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [moroshko/react-autosuggest](https://github.com/moroshko/react-autosuggest) | 3167 | `nyc mocha "test/**/*.test.js"` | 
| [expressjs/session](https://github.com/expressjs/session) | 3125 | `mocha --check-leaks --bail --no-exit --reporter spec test/` | 
| [ianstormtaylor/superstruct](https://github.com/ianstormtaylor/superstruct) | 3120 | `yarn build:cjs && yarn lint && mocha --require babel-core/register ./test/index.js` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3101 | `mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3072 | `mocha` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3068 | `./node_modules/.bin/mocha test/test.*.js` | 
| [ecrmnn/collect.js](https://github.com/ecrmnn/collect.js) | 3060 | `node_modules/.bin/mocha test/tests.js` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3021 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 2989 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [lambci/lambci](https://github.com/lambci/lambci) | 2978 | `mocha` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 2977 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 2975 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [googlesamples/md2googleslides](https://github.com/googlesamples/md2googleslides) | 2935 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [chimurai/http-proxy-middleware](https://github.com/chimurai/http-proxy-middleware) | 2934 | `npm run lint && mocha --recursive --colors --reporter spec` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 2896 | `mocha test/*.js` | 
| [alexmingoia/koa-router](https://github.com/alexmingoia/koa-router) | 2859 | `NODE_ENV=test mocha test/**/*.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 2855 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [ctavan/express-validator](https://github.com/ctavan/express-validator) | 2807 | `nyc mocha && tsc` | 
| [kenwheeler/cash](https://github.com/kenwheeler/cash) | 2795 | `gulp builder; ./node_modules/istanbul/lib/cli.js cover --root './dist' -x './dist/lib/sugar.js' _mocha -- -R spec && npm run lint` | 
| [vuejs/vue-loader](https://github.com/vuejs/vue-loader) | 2789 | `eslint lib && mocha --slow 5000 --timeout 10000` | 
| [commitizen/cz-cli](https://github.com/commitizen/cz-cli) | 2786 | `nyc --require babel-core/register _mocha -- test/tests/index.js` | 
| [Yomguithereal/baobab](https://github.com/Yomguithereal/baobab) | 2786 | `mocha -R spec --require babel-core/register ./test/endpoint.js` | 
| [felipernb/algorithms.js](https://github.com/felipernb/algorithms.js) | 2768 | `mocha -R spec --recursive src/test` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 2768 | `mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 2761 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [reworkcss/rework](https://github.com/reworkcss/rework) | 2760 | `mocha --require should --reporter spec` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 2755 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 2751 | `mocha test/index.js && npm run demo` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 2741 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [react-webpack-generators/generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack) | 2738 | `istanbul cover _mocha` | 
| [expressjs/cors](https://github.com/expressjs/cors) | 2735 | `npm run lint && nyc --reporter=html --reporter=text mocha` | 
| [bitinn/node-fetch](https://github.com/bitinn/node-fetch) | 2731 | `cross-env BABEL_ENV=test mocha --compilers js:babel-register test/test.js` | 
| [github-tools/github](https://github.com/github-tools/github) | 2695 | `mocha --opts ./mocha.opts test/*.spec.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 2689 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) | 2685 | `jshint src/ua-parser.js && mocha -R nyan test/test.js` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 2678 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [jsoma/tabletop](https://github.com/jsoma/tabletop) | 2673 | `node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check` | 
| [tj/consolidate.js](https://github.com/tj/consolidate.js) | 2656 | `mocha` | 
| [taskrabbit/elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump) | 2642 | `mocha` | 
| [jayphelps/core-decorators](https://github.com/jayphelps/core-decorators) | 2642 | `mocha --compilers js:babel-core/register --require babel-polyfill "test/**/*.spec.js"` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 2641 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [addyosmani/psi](https://github.com/addyosmani/psi) | 2631 | `xo && mocha` | 
| [plouc/mozaik](https://github.com/plouc/mozaik) | 2616 | `mocha --opts mocha.opts` | 
| [GetStream/Winds](https://github.com/GetStream/Winds) | 2612 | `NODE_ENV=testing node ./node_modules/mocha/bin/mocha test/bootstrap.test.js test/integration/**/*.test.js` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 2610 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mattallty/Caporal.js](https://github.com/mattallty/Caporal.js) | 2599 | `./node_modules/mocha/bin/mocha --require ./tests/utils/bootstrap.js --full-trace --recursive -R mocha-unfunk-reporter tests/` | 
| [tilemill-project/tilemill](https://github.com/tilemill-project/tilemill) | 2597 | `mocha --timeout 100000` | 
| [css/csso](https://github.com/css/csso) | 2585 | `mocha --reporter dot` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2584 | `mocha-phantomjs ./test/index.html` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 2576 | `npm run mocha && npm run lint` | 
| [istarkov/google-map-react](https://github.com/istarkov/google-map-react) | 2544 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [ecomfe/fontmin](https://github.com/ecomfe/fontmin) | 2543 | `mocha` | 
| [RafalWilinski/express-status-monitor](https://github.com/RafalWilinski/express-status-monitor) | 2527 | `mocha --recursive --watch` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 2520 | `mocha --compilers js:babel-register --recursive spec` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2517 | `export TESTING=true; mocha --reporter list` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2511 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [developit/unfetch](https://github.com/developit/unfetch) | 2505 | `eslint src test && mocha --compilers js:babel-register test/**/*.js` | 
| [webpack-contrib/css-loader](https://github.com/webpack-contrib/css-loader) | 2501 | `mocha` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 2489 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [jaredhanson/oauth2orize](https://github.com/jaredhanson/oauth2orize) | 2460 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [Vincit/objection.js](https://github.com/Vincit/objection.js) | 2459 | `npm run eslint && mocha --slow 10 --timeout 15000 --reporter spec --recursive tests` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 2435 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2430 | `mocha --reporter=spec test/*-test.js` | 
| [OptimalBits/bull](https://github.com/OptimalBits/bull) | 2405 | `NODE_ENV=test mocha` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2403 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [node-ffi/node-ffi](https://github.com/node-ffi/node-ffi) | 2392 | `node-gyp rebuild --directory test && mocha -gc --reporter spec` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 2374 | `node_modules/.bin/mocha --reporter spec` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2367 | `node node_modules/mocha/bin/_mocha` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 2364 | `nyc mocha test/mocha-node-setup.js "test/**/*-test.js"` | 
| [digitalbazaar/forge](https://github.com/digitalbazaar/forge) | 2357 | `cross-env NODE_ENV=test mocha -t 30000 -R ${REPORTER:-spec} tests/unit/index.js` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2344 | `mocha` | 
| [istanbuljs/nyc](https://github.com/istanbuljs/nyc) | 2333 | `npm run clean && npm run build && npm run instrument && npm run test-integration && npm run test-mocha && npm run report` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2332 | `mocha --no-colors --reporter spec` | 
| [benjamine/jsondiffpatch](https://github.com/benjamine/jsondiffpatch) | 2330 | `nyc mocha` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2330 | `grunt jshint && mocha` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 2328 | `npm run build && cd test && mocha . --reporter dot` | 
| [postaljs/postal.js](https://github.com/postaljs/postal.js) | 2324 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2311 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2307 | `mocha test` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2263 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [json5/json5](https://github.com/json5/json5) | 2259 | `mocha --ui exports --reporter spec` | 
| [yujiosaka/headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) | 2229 | `npm run lint && mocha` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2224 | `mocha test test/unit/**/*_test.js` | 
| [mroderick/PubSubJS](https://github.com/mroderick/PubSubJS) | 2222 | `mocha` | 
| [kubernetes/dashboard](https://github.com/kubernetes/dashboard) | 2221 | `export TESTING=true; mocha --reporter list` | 
| [Dash-Industry-Forum/dash.js](https://github.com/Dash-Industry-Forum/dash.js) | 2219 | `mocha test/unit --require mochahook` | 
| [apiaryio/dredd](https://github.com/apiaryio/dredd) | 2219 | `mocha "test/**/*-test.js"` | 
| [mde/ejs](https://github.com/mde/ejs) | 2218 | `mocha --require should --reporter spec` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2216 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2215 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [h5bp/server-configs-apache](https://github.com/h5bp/server-configs-apache) | 2205 | `npm run lint && npm run build && npm run mocha` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2202 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [mcollina/mosca](https://github.com/mcollina/mosca) | 2198 | `mocha --recursive --bail --reporter spec test 2>&1` | 
| [reactjs/react-chartjs](https://github.com/reactjs/react-chartjs) | 2197 | `mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2174 | `mocha -R spec` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2165 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [gajus/swing](https://github.com/gajus/swing) | 2140 | `mocha --compilers js:babel-register` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 2086 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [dmfay/massive-js](https://github.com/dmfay/massive-js) | 2084 | `nyc --reporter=html --reporter=text mocha` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2084 | `mocha` | 
| [kolodny/immutability-helper](https://github.com/kolodny/immutability-helper) | 2070 | `mocha test.js` | 
| [ubolonton/js-csp](https://github.com/ubolonton/js-csp) | 2066 | `cross-env BABEL_ENV=test mocha` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2045 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2042 | `mocha` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 2020 | `mocha -R landing test/index` | 
| [slate/slate](https://github.com/slate/slate) | 2014 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./packages/*/test/index.js` | 
| [noble/noble](https://github.com/noble/noble) | 2013 | `mocha -R spec test/*.js` | 
| [weui/react-weui](https://github.com/weui/react-weui) | 2012 | `mocha --compilers js:babel-core/register --recursive -r ignore-styles -r jsdom-global/register` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2008 | `mocha && eslint .` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 1964 | `mocha test && npm run lint` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 1932 | `mocha --require=test/test_helper.js` | 
| [nodebox/opentype.js](https://github.com/nodebox/opentype.js) | 1930 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [thlorenz/proxyquire](https://github.com/thlorenz/proxyquire) | 1927 | `standard && mocha` | 
| [reactopt/reactopt](https://github.com/reactopt/reactopt) | 1908 | `mocha -c test/index.js` | 
| [1602/jugglingdb](https://github.com/1602/jugglingdb) | 1901 | `mocha --bail --reporter spec --check-leaks test/` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 1898 | `mocha test/index.js --reporter dot` | 
| [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf) | 1898 | `./node_modules/mocha/bin/mocha -u bdd tests/test.js` | 
| [Qix-/color](https://github.com/Qix-/color) | 1887 | `mocha` | 
| [lukehaas/RegexHub](https://github.com/lukehaas/RegexHub) | 1887 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [WeiChiaChang/stacks-cli](https://github.com/WeiChiaChang/stacks-cli) | 1884 | `mocha` | 
| [babel/example-node-server](https://github.com/babel/example-node-server) | 1872 | `mocha --compilers js:babel-register` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 1859 | `mocha --timeout 10000 test/*-test.js test/security/*.js` | 
| [Automattic/expect.js](https://github.com/Automattic/expect.js) | 1856 | `mocha --require ./test/common --growl test/expect.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1849 | `mocha tests.js` | 
| [letsgetrandy/brototype](https://github.com/letsgetrandy/brototype) | 1849 | `mocha tests.js` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 1842 | `mocha --reporter spec --timeout 5000` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 1827 | `mocha test/runner.js --reporter spec` | 
| [wdjungst/react-project](https://github.com/wdjungst/react-project) | 1819 | `npm run build && NODE_ENV=test mocha tests.js --compilers js:babel-register` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 1816 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [davidkpiano/react-redux-form](https://github.com/davidkpiano/react-redux-form) | 1809 | `NODE_ENV=test mocha --require babel-register --require ./test/spec-setup.js` | 
| [diegonetto/generator-ionic](https://github.com/diegonetto/generator-ionic) | 1802 | `mocha --timeout 5000` | 
| [actionhero/actionhero](https://github.com/actionhero/actionhero) | 1797 | `cross-env NODE_ENV=test mocha` | 
| [JoelOtter/kajero](https://github.com/JoelOtter/kajero) | 1790 | `./node_modules/mocha/bin/mocha --compilers js:babel-register --recursive "./src/**/*-spec.js"` | 
| [then/promise](https://github.com/then/promise) | 1787 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 1785 | `mocha --compilers js:babel-core/register __tests__` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 1779 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 1778 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors --compilers js:babel-core/register server/tests --recursive` | 
| [brenden/node-webshot](https://github.com/brenden/node-webshot) | 1772 | `mocha --ui bdd --reporter spec --require should ./test/core.js ./test/options/*` | 
| [omnidan/redux-undo](https://github.com/omnidan/redux-undo) | 1771 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [o1lab/xmysql](https://github.com/o1lab/xmysql) | 1766 | `./node_modules/.bin/mocha tests/*.js --exit` | 
| [seaneking/rucksack](https://github.com/seaneking/rucksack) | 1753 | `mocha test` | 
| [kach/nearley](https://github.com/kach/nearley) | 1751 | `mocha test/*.test.js` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1748 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [lipp/login-with](https://github.com/lipp/login-with) | 1743 | `standard && cross-env NODE_ENV=test nyc mocha ./test/*.js` | 
| [google/closure-compiler-js](https://github.com/google/closure-compiler-js) | 1742 | `mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1733 | `mocha test/**/*_test.js --bail` | 
| [posthtml/posthtml](https://github.com/posthtml/posthtml) | 1732 | `npm run lint && mocha -R dot && npm run cover` | 
| [share/sharedb](https://github.com/share/sharedb) | 1732 | `./node_modules/.bin/mocha && npm run jshint` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 1724 | `mocha && eslint *.js` | 
| [gilbitron/Raneto](https://github.com/gilbitron/Raneto) | 1721 | `npm run lint && mocha --reporter spec test/*.js` | 
| [peers/peerjs-server](https://github.com/peers/peerjs-server) | 1716 | `mocha test` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1716 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1707 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1706 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 1702 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [danielstjules/jsinspect](https://github.com/danielstjules/jsinspect) | 1702 | `mocha -R spec spec spec/reporters` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1690 | `mocha` | 
| [Automattic/juice](https://github.com/Automattic/juice) | 1689 | `mocha --reporter spec && npm run test-typescript` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 1688 | `npm run mocha && npm run karma` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1688 | `npm run jshint && mocha --recursive` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 1688 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [embark-framework/embark](https://github.com/embark-framework/embark) | 1687 | `grunt jshint && mocha test/ --no-timeouts && cd test_app/ && npm install && ../bin/embark test` | 
| [rickbergfalk/sqlpad](https://github.com/rickbergfalk/sqlpad) | 1687 | `npm run lint && mocha server/test --recursive --exit` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 1677 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 1673 | `nyc npm run _mocha` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1671 | `xo && mocha` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1668 | `mocha` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1667 | `./node_modules/.bin/mocha` | 
| [simplecrawler/simplecrawler](https://github.com/simplecrawler/simplecrawler) | 1657 | `npm run lint && npm run mocha` | 
| [ifandelse/machina.js](https://github.com/ifandelse/machina.js) | 1644 | `./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1634 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 1622 | `mocha && npm run lint` | 
| [kimmobrunfeldt/concurrently](https://github.com/kimmobrunfeldt/concurrently) | 1616 | `mocha` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1614 | `mocha tests/test.js` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1606 | `mocha --expose-gc --slow 300` | 
| [techpines/express.io](https://github.com/techpines/express.io) | 1604 | `./node_modules/mocha/bin/mocha test/test.coffee` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1604 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [pencilblue/pencilblue](https://github.com/pencilblue/pencilblue) | 1603 | `istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive` | 
| [glenjamin/webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) | 1601 | `mocha` | 
| [ashtuchkin/iconv-lite](https://github.com/ashtuchkin/iconv-lite) | 1592 | `mocha --reporter spec --grep .` | 
| [pahen/madge](https://github.com/pahen/madge) | 1583 | `npm run lint && npm run mocha` | 
| [alexei/sprintf.js](https://github.com/alexei/sprintf.js) | 1583 | `mocha test/*.js` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1580 | `npm run lint && mocha` | 
| [Codeception/CodeceptJS](https://github.com/Codeception/CodeceptJS) | 1576 | `npm run lint && mocha test/unit && mocha test/runner` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1574 | `mocha` | 
| [tinytacoteam/zazu](https://github.com/tinytacoteam/zazu) | 1572 | `cross-env NODE_ENV=test electron-mocha --recursive test/app` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 1570 | `mocha tests --compilers js:babel-core/register` | 
| [booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) | 1567 | `mocha test -u bdd -R spec` | 
| [flitbit/diff](https://github.com/flitbit/diff) | 1563 | `mocha test/**/*.js` | 
| [sintaxi/surge](https://github.com/sintaxi/surge) | 1551 | `mocha ./test/basic.js -t 5000` | 
| [kissjs/node-mongoskin](https://github.com/kissjs/node-mongoskin) | 1549 | `./node_modules/.bin/mocha` | 
| [bcoin-org/bcoin](https://github.com/bcoin-org/bcoin) | 1540 | `mocha --reporter spec test/*.js` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1539 | `mocha` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1536 | `mocha spec` | 
| [OptimalBits/redbird](https://github.com/OptimalBits/redbird) | 1536 | `mocha test/* --reporter spec` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1534 | `mocha test --timeout 600000` | 
| [felixrieseberg/windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) | 1519 | `standard "src/*.js" && npm run build && mocha` | 
| [stripe/stripe-node](https://github.com/stripe/stripe-node) | 1503 | `npm run lint && npm run mocha` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1503 | `mocha` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1502 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1496 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1492 | `./node_modules/mocha/bin/mocha -R spec` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1482 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [intercellular/cell](https://github.com/intercellular/cell) | 1479 | `npm run test:lint && npm run test:mocha` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1473 | `mocha -u tdd` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1470 | `mocha -R spec` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1457 | `node_modules/.bin/mocha --recursive` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1453 | `mocha --reporter spec` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 1453 | `mocha --compilers js:babel-register` | 
| [samccone/drool](https://github.com/samccone/drool) | 1438 | `mocha test/tests.js --timeout=10000` | 
| [sindresorhus/multiline](https://github.com/sindresorhus/multiline) | 1435 | `mocha` | 
| [RobertWHurst/KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) | 1431 | `mocha test/**/*.spec.js` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1422 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [benjycui/bisheng](https://github.com/benjycui/bisheng) | 1412 | `lerna bootstrap && lerna exec -- _mocha --recursive --opts test/mocha.opts` | 
| [knrz/CSV.js](https://github.com/knrz/CSV.js) | 1409 | `mocha test.js` | 
| [Zarel/Pokemon-Showdown](https://github.com/Zarel/Pokemon-Showdown) | 1403 | `eslint --cache . && tsc && mocha` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1402 | `mocha --check-leaks -R dot` | 
| [jdesboeufs/connect-mongo](https://github.com/jdesboeufs/connect-mongo) | 1401 | `nyc mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 1401 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1398 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1397 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1392 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [observing/pre-commit](https://github.com/observing/pre-commit) | 1387 | `mocha test.js` | 
| [felixrieseberg/npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) | 1383 | `standard "./src/*.js" && mocha` | 
| [mathisonian/premonish](https://github.com/mathisonian/premonish) | 1368 | `semistandard src/** test/** && mocha --compilers js:babel-core/register` | 
| [squaremo/rabbit.js](https://github.com/squaremo/rabbit.js) | 1367 | `./node_modules/mocha/bin/mocha --ui exports test` | 
| [modood/Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) | 1361 | `eslint . && mocha -t 5000` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1356 | `mocha --recursive` | 
| [ebidel/appmetrics.js](https://github.com/ebidel/appmetrics.js) | 1351 | `./node_modules/mocha/bin/mocha` | 
| [socketio/socket.io-redis](https://github.com/socketio/socket.io-redis) | 1351 | `mocha` | 
| [zeit/ms](https://github.com/zeit/ms) | 1346 | `mocha tests.js` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1341 | `mocha --check-leaks --reporter spec --bail` | 
| [webrtc/adapter](https://github.com/webrtc/adapter) | 1340 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 1330 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [kss-node/kss-node](https://github.com/kss-node/kss-node) | 1329 | `istanbul cover _mocha` | 
| [webpack-contrib/npm-install-webpack-plugin](https://github.com/webpack-contrib/npm-install-webpack-plugin) | 1327 | `cross-env NODE_ENV=test nyc mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1323 | `mocha` | 
| [webpack-contrib/copy-webpack-plugin](https://github.com/webpack-contrib/copy-webpack-plugin) | 1317 | `mocha compiled_tests/` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1312 | `mocha` | 
| [captivationsoftware/react-sticky](https://github.com/captivationsoftware/react-sticky) | 1301 | `mocha test/setup.js test/spec/*.js` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1295 | `nyc npm run mocha` | 
| [letsgetrandy/DICSS](https://github.com/letsgetrandy/DICSS) | 1295 | `mocha-phantomjs tests/index.html` | 
| [arnaudbenard/redux-mock-store](https://github.com/arnaudbenard/redux-mock-store) | 1292 | `mocha --compilers js:babel-core/register --reporter spec test/*.js` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1291 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1286 | `mocha -R spec test/*.js` | 
| [twigjs/twig.js](https://github.com/twigjs/twig.js) | 1285 | `npm run build && mocha -r should` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1261 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1259 | `./node_modules/.bin/mocha test` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1250 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [electron/devtron](https://github.com/electron/devtron) | 1248 | `mocha test/unit/*-test.js test/integration/*-test.js && standard` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1248 | `mocha spec/exec.js` | 
| [zalmoxisus/remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) | 1245 | `NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1244 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1242 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [markdalgleish/static-site-generator-webpack-plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) | 1234 | `istanbul cover _mocha test -- --timeout 20000` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1220 | `mocha test/*.js` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1217 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1213 | `mocha tests` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1213 | `mocha --check-leaks --require @babel/register` | 
| [gemini-testing/gemini](https://github.com/gemini-testing/gemini) | 1210 | `istanbul test _mocha -- --recursive test/unit test/functional test/browser` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1207 | `mocha test/test.js` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1207 | `mocha --timeout 10000 test/ && standard src/**/*.js test/**/*.js` | 
| [Kong/mockbin](https://github.com/Kong/mockbin) | 1205 | `mocha --recursive` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1199 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [jhlywa/chess.js](https://github.com/jhlywa/chess.js) | 1196 | `mocha` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1195 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [ToothlessGear/node-gcm](https://github.com/ToothlessGear/node-gcm) | 1194 | `mocha test/**/*Spec.js` | 
| [messageformat/messageformat.js](https://github.com/messageformat/messageformat.js) | 1191 | `mocha` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1189 | `mocha` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1188 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [taptapship/wiredep](https://github.com/taptapship/wiredep) | 1187 | `jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec` | 
| [oracle/node-oracledb](https://github.com/oracle/node-oracledb) | 1185 | `mocha --opts test/opts/mocha.opts` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1185 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1172 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [johnpapa/lite-server](https://github.com/johnpapa/lite-server) | 1172 | `eslint *.js lib/*.js && istanbul cover _mocha -- -R spec` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1171 | `mocha test` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1165 | `node ./node_modules/mocha/bin/mocha tests` | 
| [Ensighten/grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) | 1164 | `npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint` | 
| [paldepind/flyd](https://github.com/paldepind/flyd) | 1164 | `eslint --fix lib/ test/ module/ && mocha -R dot test/*.js module/**/test/*.js` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1150 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [teambit/bit](https://github.com/teambit/bit) | 1150 | `mocha --compilers js:babel-core/register ./specs/**/*.spec.js` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1149 | `mocha` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1148 | `mocha` | 
| [tediousjs/node-mssql](https://github.com/tediousjs/node-mssql) | 1145 | `standard && node_modules/.bin/mocha test/common/unit.js` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1133 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1130 | `mocha test/unit` | 
| [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import) | 1128 | `cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1126 | `standard && istanbul cover _mocha` | 
| [wesleytodd/YeoPress](https://github.com/wesleytodd/YeoPress) | 1125 | `node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage` | 
| [jeffbski/redux-logic](https://github.com/jeffbski/redux-logic) | 1124 | `cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive -r ./test/setup.js` | 
| [archiverjs/node-archiver](https://github.com/archiverjs/node-archiver) | 1119 | `mocha --reporter dot` | 
| [robrich/orchestrator](https://github.com/robrich/orchestrator) | 1116 | `mocha` | 
| [broofa/node-mime](https://github.com/broofa/node-mime) | 1115 | `mocha src/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1115 | `npm run lint && npm run mocha` | 
| [normalize/mz](https://github.com/normalize/mz) | 1114 | `mocha --reporter spec` | 
| [variety/variety](https://github.com/variety/variety) | 1111 | `node_modules/.bin/mocha --compilers js:babel-core/register --require babel-polyfill  --recursive --reporter spec --timeout 15000 spec` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1111 | `node_modules/.bin/mocha` | 
| [Raathigesh/dazzle](https://github.com/Raathigesh/dazzle) | 1110 | `babel-node ./node_modules/istanbul/lib/cli.js --include-all-sources cover node_modules/mocha/bin/_mocha -- --require ./test/entry.js ./test/**/*.spec.js` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1109 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [fent/randexp.js](https://github.com/fent/randexp.js) | 1107 | `istanbul cover node_modules/.bin/_mocha -- test/*-test.js` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 1104 | `mocha test` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1103 | `eslint src && mocha && karma start --single-run` | 
| [Yomguithereal/mnemonist](https://github.com/Yomguithereal/mnemonist) | 1100 | `mocha` | 
| [sitespeedio/coach](https://github.com/sitespeedio/coach) | 1098 | `mocha --recursive test/api test/dom test/har test/merge` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1096 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1095 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1089 | `node_modules/.bin/mocha && npm run lint` | 
| [markdalgleish/redial](https://github.com/markdalgleish/redial) | 1088 | `babel-istanbul cover _mocha && babel-istanbul check-coverage --branches 100` | 
| [coryhouse/pluralsight-redux-starter](https://github.com/coryhouse/pluralsight-redux-starter) | 1086 | `mocha --reporter progress tools/testSetup.js "src/**/*.test.js"` | 
| [terinjokes/gulp-uglify](https://github.com/terinjokes/gulp-uglify) | 1082 | `nyc --reporter=lcov --reporter=text mocha --require intelli-espower-loader` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1081 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1079 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) | 1070 | `istanbul test _mocha --report html -- test/*.js --reporter spec` | 
| [neumino/thinky](https://github.com/neumino/thinky) | 1070 | `mocha --check-leaks -t 20000` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1069 | `mocha --compilers js:babel-register` | 
| [gmetais/sw-delta](https://github.com/gmetais/sw-delta) | 1066 | `./node_modules/.bin/mocha test/unit --reporter spec` | 
| [brigand/react-mixin](https://github.com/brigand/react-mixin) | 1066 | `mocha test/*` | 
| [3rd-Eden/memcached](https://github.com/3rd-Eden/memcached) | 1063 | `mocha $(find test -name '*.test.js')` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1061 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [babel/gulp-babel](https://github.com/babel/gulp-babel) | 1059 | `xo && mocha` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1056 | `mocha` | 
| [conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version) | 1051 | `nyc mocha --timeout=20000 test.js` | 
| [vuejs/vueify](https://github.com/vuejs/vueify) | 1048 | `eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000` | 
| [expressjs/csurf](https://github.com/expressjs/csurf) | 1048 | `mocha --check-leaks --reporter spec --bail test/` | 
| [yeoman/generator-webapp_DEPRECATED](https://github.com/yeoman/generator-webapp_DEPRECATED) | 1044 | `mocha --reporter spec --timeout 3000` | 
| [survivejs/webpack-merge](https://github.com/survivejs/webpack-merge) | 1044 | `mocha tests/test-*` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1042 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [flickr/justified-layout](https://github.com/flickr/justified-layout) | 1035 | `istanbul test _mocha` | 
| [z-pattern-matching/z](https://github.com/z-pattern-matching/z) | 1026 | `NODE_PATH=. mocha **/*.spec.js` | 
| [hokaccha/node-jwt-simple](https://github.com/hokaccha/node-jwt-simple) | 1025 | `istanbul cover _mocha test/*.js` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1024 | `cross-env NODE_ENV=test BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [jas/playground](https://github.com/jas/playground) | 1023 | `istanbul test node_modules/mocha/bin/_mocha && npm run lint` | 
| [pauldijou/redux-act](https://github.com/pauldijou/redux-act) | 1021 | `NODE_ENV=test mocha --recursive --compilers js:babel-core/register --reporter mocha-better-spec-reporter` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1017 | `mocha --check-leaks -R dot` | 
| [immersive-web/webvr-polyfill](https://github.com/immersive-web/webvr-polyfill) | 1016 | `mocha -r test/init.js --compilers js:babel-core/register test/*.test.js` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1016 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [jaebradley/uber-cli](https://github.com/jaebradley/uber-cli) | 1015 | `npm run compile && mocha --recursive --compilers js:babel-core/register` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1014 | `mocha` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1008 | `mocha test/tests.js` | 
| [FormidableLabs/redux-little-router](https://github.com/FormidableLabs/redux-little-router) | 1002 | `BABEL_ENV=commonjs mocha test/.setup.js 'test/**/*.spec.js'` | 
| [gajus/babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) | 1001 | ` NODE_ENV=test mocha --require babel-core/register` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 996 | `mocha --colors ./test/*.spec.js` | 
| [twolfson/gulp.spritesmith](https://github.com/twolfson/gulp.spritesmith) | 994 | `npm run precheck && npm run test-mocha && npm run lint` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 989 | `npm run prepublishOnly && mocha test/test.js` | 
| [nathanboktae/mocha-phantomjs](https://github.com/nathanboktae/mocha-phantomjs) | 989 | `mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000` | 
| [oakmac/chessboardjs](https://github.com/oakmac/chessboardjs) | 988 | `mocha` | 
| [xiongwilee/Gracejs](https://github.com/xiongwilee/Gracejs) | 986 | `mocha` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 983 | `standard && mocha` | 
| [yeoman/generator-polymer](https://github.com/yeoman/generator-polymer) | 983 | `jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec` | 
| [angular-redux/ng-redux](https://github.com/angular-redux/ng-redux) | 978 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 976 | `mocha --recursive --bail --reporter spec test` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 972 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 968 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 968 | `npm run rollup-cjs && mocha test/test.js` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 966 | `mocha --recursive test` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 965 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 961 | `mocha --compilers js:babel-core/register` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 960 | `mocha` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 957 | `mocha --recursive test/unit/` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 957 | `mocha -R list` | 
| [router5/router5](https://github.com/router5/router5) | 957 | `mocha --compilers js:babel-core/register --require test-helper.js --recursive 'packages/*/test/**/*.js'` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 955 | `mocha $(find test -name '*.test.js')` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 954 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [yeoman/generator-mobile](https://github.com/yeoman/generator-mobile) | 954 | `mocha --timeout 5000` | 
| [DemocracyEarth/sovereign](https://github.com/DemocracyEarth/sovereign) | 951 | `meteor test --settings=config/development/settings.json --once --driver-package dispatch:mocha-phantomjs` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 951 | `mocha --async-only` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 950 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [tomas/needle](https://github.com/tomas/needle) | 945 | `mocha test` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 945 | `mocha --reporter spec` | 
| [cnpm/cnpm](https://github.com/cnpm/cnpm) | 945 | `mocha -t 120000 test/*.test.js` | 
| [jhen0409/react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) | 942 | `cross-env NODE_ENV=test mocha -r ./test/setup-app test/app` | 
| [sequelize/sequelize-auto](https://github.com/sequelize/sequelize-auto) | 941 | `./node_modules/.bin/mocha --globals setImmediate,clearImmediate,__core-js_shared__ --ui tdd --check-leaks --colors -t 15000 --reporter spec "test/**/*.test.js"` | 
| [kirjs/react-highcharts](https://github.com/kirjs/react-highcharts) | 938 | `webpack && mocha test/unit` | 
| [LinusU/node-appdmg](https://github.com/LinusU/node-appdmg) | 938 | `standard && mocha -b` | 
| [jerairrest/react-chartjs-2](https://github.com/jerairrest/react-chartjs-2) | 937 | `mocha test/config/setup.js test/__tests__/**/*` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 931 | `mocha -R spec ./test/unit/**` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 931 | `mocha test/test-docx.js test/test-xlsx.js test/test-pptx-nocharts.js test/test-pptx-charts.js` | 
| [electron/asar](https://github.com/electron/asar) | 930 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere) | 928 | `mocha ./test/test*.js --reporter spec` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 924 | `mocha --reporter spec --bail --check-leaks test/` | 
| [greena13/react-hotkeys](https://github.com/greena13/react-hotkeys) | 921 | `mocha` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 920 | `mocha tests/*.js` | 
| [electron/spectron](https://github.com/electron/spectron) | 914 | `mocha && standard` | 
| [developit/snarkdown](https://github.com/developit/snarkdown) | 912 | `eslint src test && mocha --compilers babel-register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 911 | `mocha` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 911 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 910 | `mocha spec/*.spec.js` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 909 | `mocha --reporter spec --bail --check-leaks test/` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 907 | `mocha ./test/index.js` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 903 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [WP-API/node-wpapi](https://github.com/WP-API/node-wpapi) | 898 | `istanbul cover _mocha -- tests --recursive --reporter=nyan` | 
| [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader) | 896 | `mocha` | 
| [hortinstein/node-dash-button](https://github.com/hortinstein/node-dash-button) | 893 | `istanbul cover ./node_modules/mocha/bin/_mocha test/test.js --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage` | 
| [mozilla-iot/gateway](https://github.com/mozilla-iot/gateway) | 891 | `npm run lint && npm run mocha` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 890 | `mocha "client.test" --compilers js:babel-register` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 889 | `./node_modules/.bin/mocha --globals angular,require` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 889 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [huttarichard/instagram-private-api](https://github.com/huttarichard/instagram-private-api) | 887 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 884 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [domenic/sinon-chai](https://github.com/domenic/sinon-chai) | 883 | `mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [krasimir/webpack-library-starter](https://github.com/krasimir/webpack-library-starter) | 874 | `mocha --require babel-core/register --colors ./test/*.spec.js` | 
| [jeremyckahn/shifty](https://github.com/jeremyckahn/shifty) | 873 | `mocha ./node_modules/babel-core/register.js test/index.js` | 
| [electron-userland/electron-compile](https://github.com/electron-userland/electron-compile) | 872 | `mocha --compilers js:babel-register test/*.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 871 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 869 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 866 | `mocha --reporter list` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 864 | `mocha --reporter spec --bail --check-leaks test/` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 863 | `./node_modules/.bin/mocha --timeout 5000 --compilers js:babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [azu/promises-book](https://github.com/azu/promises-book) | 862 | `mocha ./Ch**/test/*.js && npm run textlint` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 860 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 859 | `mocha` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 859 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [erelsgl/limdu](https://github.com/erelsgl/limdu) | 856 | `mocha` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 853 | `node_modules/.bin/mocha` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 853 | `mocha ./test -R spec` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 851 | `standard && karma start karma.conf.js && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [open-xml-templating/docxtemplater](https://github.com/open-xml-templating/docxtemplater) | 851 | `npm run convertto:es5 && npm run mocha` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 850 | `npm run lint && mocha --require @babel/register` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 848 | `npm run lint && mocha -R spec` | 
| [samgozman/YoptaScript](https://github.com/samgozman/YoptaScript) | 848 | `mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 845 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 840 | `npm run lint && npm run mocha` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 837 | `mocha tests` | 
| [skygragon/leetcode-cli](https://github.com/skygragon/leetcode-cli) | 837 | `npm run lint && nyc mocha test/** && nyc report --reporter=lcov` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 837 | `mocha --timeout 200000` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 836 | `eslint test && mocha --compilers js:babel/register` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 835 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 834 | `mocha` | 
| [claudioc/jingo](https://github.com/claudioc/jingo) | 831 | `node_modules/.bin/mocha test/spec` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 829 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 823 | `mocha -R spec` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 823 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [react-materialize/react-materialize](https://github.com/react-materialize/react-materialize) | 822 | `mocha` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 818 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 818 | `mocha && ember test` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 815 | `mocha --reporter spec` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 815 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 814 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [thelinmichael/spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) | 811 | `npm run lint && ./node_modules/.bin/mocha --bail` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 809 | `mocha tests/*.test.js --reporter spec` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 806 | `mocha --check-leaks -t 20000` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 803 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 803 | `mocha` | 
| [tj/node-migrate](https://github.com/tj/node-migrate) | 803 | `standard && standard ./bin/* && mocha` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 802 | `mocha -t 600000` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 801 | `istanbul cover _mocha` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 797 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [felixge/node-dateformat](https://github.com/felixge/node-dateformat) | 797 | `mocha` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 796 | `mocha --require babel-register` | 
| [amplitude/redux-query](https://github.com/amplitude/redux-query) | 795 | `mocha --compilers js:babel-core/register --reporter spec test/**/*.test.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 794 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 793 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 793 | `mocha -u tdd` | 
| [ant-design/babel-plugin-import](https://github.com/ant-design/babel-plugin-import) | 793 | `node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha  -- --require @babel/register --no-timeouts` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 792 | `mocha -R spec tests/` | 
| [kriasoft/isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader) | 792 | `mocha test --compilers js:babel-register` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 791 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 788 | `mocha -t 5000` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 787 | `mocha --reporter spec --bail --check-leaks test/` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 787 | `mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 786 | `cake build && mocha ./test/mocha/*.coffee` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 783 | `mocha` | 
| [mapmeld/gitjk](https://github.com/mapmeld/gitjk) | 783 | `mocha` | 
| [yahoo/blink-diff](https://github.com/yahoo/blink-diff) | 782 | `istanbul cover -- _mocha --reporter spec` | 
| [image-size/image-size](https://github.com/image-size/image-size) | 781 | `nyc mocha specs` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 781 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 777 | `./node_modules/mocha/bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [edsu/anon](https://github.com/edsu/anon) | 776 | `mocha --colors --reporter spec test.js` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 776 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 771 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 771 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 770 | `mocha spec/*.js` | 
| [GitbookIO/nuts](https://github.com/GitbookIO/nuts) | 769 | `mocha --reporter list` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 766 | `npm run lint && mocha` | 
| [tdegrunt/jsonschema](https://github.com/tdegrunt/jsonschema) | 766 | `./node_modules/.bin/mocha -R spec` | 
| [vohof/gulp-livereload](https://github.com/vohof/gulp-livereload) | 765 | `mocha` | 
| [gulpjs/vinyl-fs](https://github.com/gulpjs/vinyl-fs) | 765 | `mocha --async-only` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 764 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [ExpressGateway/express-gateway](https://github.com/ExpressGateway/express-gateway) | 764 | `npm run mocha:istanbul` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 761 | `xo && mocha -R spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 761 | `mocha` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 756 | `babel-node node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 754 | `mocha` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 753 | `mocha --ui tdd --require ./test/__setup` | 
| [gajus/eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype) | 751 | `mocha --compilers js:babel-register ./tests/rules/index.js` | 
| [greggman/twgl.js](https://github.com/greggman/twgl.js) | 748 | `node node_modules/mocha/bin/mocha --recursive 'test/**/*-harness.js'` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 741 | `mocha -R spec src/**/*_test.js` | 
| [bitpay/insight](https://github.com/bitpay/insight) | 740 | `mocha test` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 739 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 734 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 733 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [Gaya/queryloader2](https://github.com/Gaya/queryloader2) | 731 | `node ./node_modules/jscs/bin/jscs src && node ./node_modules/gulp/bin/gulp.js browserify  && node ./node_modules/gulp/bin/gulp.js browserify-tests && node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs test/browser/index.html` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 730 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 729 | `mocha --reporter spec` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 728 | `mocha --recursive -s 15 test/` | 
| [datastax/nodejs-driver](https://github.com/datastax/nodejs-driver) | 727 | `./node_modules/.bin/mocha test/unit -R spec -t 5000` | 
| [Thuzi/facebook-node-sdk](https://github.com/Thuzi/facebook-node-sdk) | 725 | `node ./node_modules/mocha/bin/mocha --recursive --reporter spec` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 725 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [acss-io/atomizer](https://github.com/acss-io/atomizer) | 725 | `./node_modules/.bin/mocha tests/ --recursive --reporter spec` | 
| [jish/pre-commit](https://github.com/jish/pre-commit) | 721 | `mocha test.js` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 720 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 717 | `npm run mocha-test test/integration` | 
| [gulp-community/gulp-concat](https://github.com/gulp-community/gulp-concat) | 713 | `mocha` | 
| [typicode/katon](https://github.com/typicode/katon) | 713 | `mocha --reporter list test/cli/index test/daemon/index` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 712 | `npm run lint && npm run build && npm run compile-test && mocha test/__test-compiled__.js && npm run clean-test` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 710 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [raineroviir/react-redux-socketio-chat](https://github.com/raineroviir/react-redux-socketio-chat) | 709 | `mocha './test/**/*.test.js' --compilers js:babel-core/register --recursive` | 
| [3Dparallax/insight](https://github.com/3Dparallax/insight) | 709 | `mocha test` | 
| [developit/decko](https://github.com/developit/decko) | 708 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [fossasia/open-event-webapp](https://github.com/fossasia/open-event-webapp) | 707 | `mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 706 | `npm run build && istanbul test _mocha test/test.js` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 705 | `mocha test` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 705 | `mocha tests/*.mocha.js` | 
| [webpack-contrib/karma-webpack](https://github.com/webpack-contrib/karma-webpack) | 705 | `mocha --compilers js:babel-register --full-trace --check-leaks test/unit` | 
| [webpro/DOMtastic](https://github.com/webpro/DOMtastic) | 702 | `npm run bundle && mocha` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 700 | `mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 699 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 697 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 695 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [sghiassy/react-native-sglistview](https://github.com/sghiassy/react-native-sglistview) | 694 | `yarn config:enable:babelrc; ./node_modules/.bin/mocha || yarn config:disable:babelrc` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 694 | `./node_modules/.bin/mocha -t 60000` | 
| [kossnocorp/assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin) | 694 | `mocha test` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 693 | `mocha` | 