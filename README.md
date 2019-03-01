# Find Repos in JavaScript Tested using Mocha

The list was updated at 00:55:37 03/01/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [socketio/socket.io](https://github.com/socketio/socket.io) | 45330 | `nyc mocha --reporter spec --slow 200 --bail --timeout 10000 test/socket.io.js` | 
| [expressjs/express](https://github.com/expressjs/express) | 42629 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/` | 
| [h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate) | 42352 | `gulp archive && mocha --require babel-core/register --reporter spec --timeout 5000` | 
| [gulpjs/gulp](https://github.com/gulpjs/gulp) | 30963 | `mocha --async-only` | 
| [lord/slate](https://github.com/lord/slate) | 26152 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [sahat/hackathon-starter](https://github.com/sahat/hackathon-starter) | 25915 | `nyc mocha --timeout=10000 --exit` | 
| [hexojs/hexo](https://github.com/hexojs/hexo) | 25437 | `mocha test/index.js` | 
| [caolan/async](https://github.com/caolan/async) | 25278 | `npm run lint && npm run mocha-node-test` | 
| [developit/preact](https://github.com/developit/preact) | 21673 | `npm-run-all lint --parallel test:mocha test:karma test:ts test:flow test:size` | 
| [GitbookIO/gitbook](https://github.com/GitbookIO/gitbook) | 20266 | `./node_modules/.bin/mocha ./testing/setup.js "./lib/**/*/__tests__/*.js" --bail --reporter=list --timeout=10000` | 
| [rstacruz/nprogress](https://github.com/rstacruz/nprogress) | 18236 | `mocha` | 
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | 18092 | `mocha --exit test/*.test.js test/**/*.test.js` | 
| [Marak/faker.js](https://github.com/Marak/faker.js) | 17785 | `node_modules/.bin/mocha test/*.*.js` | 
| [ramda/ramda](https://github.com/ramda/ramda) | 15501 | `cross-env BABEL_ENV=cjs mocha --require babel-register --reporter spec` | 
| [jaredhanson/passport](https://github.com/jaredhanson/passport) | 15157 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js` | 
| [hubotio/hubot](https://github.com/hubotio/hubot) | 14760 | `nyc --reporter=html --reporter=text mocha` | 
| [highlightjs/highlight.js](https://github.com/highlightjs/highlight.js) | 13844 | `mocha --globals document test` | 
| [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) | 13417 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [FormidableLabs/webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard) | 13075 | `mocha 'test/**/*.spec.js'` | 
| [websockets/ws](https://github.com/websockets/ws) | 10694 | `npm run lint && nyc --reporter=html --reporter=text mocha test/*.test.js` | 
| [tj/co](https://github.com/tj/co) | 10481 | `mocha --harmony` | 
| [JedWatson/classnames](https://github.com/JedWatson/classnames) | 9967 | `mocha tests/*.js` | 
| [nodejitsu/node-http-proxy](https://github.com/nodejitsu/node-http-proxy) | 9862 | `nyc --reporter=text --reporter=lcov npm run mocha` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9741 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9626 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9538 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9483 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9375 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9239 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8998 | `mocha test/src` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8962 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8722 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8638 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8594 | `mocha --check-leaks -R dot` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8510 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8489 | `grunt clean:test && mocha --exit` | 
| [stylus/stylus](https://github.com/stylus/stylus) | 9741 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [amark/gun](https://github.com/amark/gun) | 9626 | `mocha` | 
| [louischatriot/nedb](https://github.com/louischatriot/nedb) | 9538 | `./node_modules/.bin/mocha --reporter spec --timeout 10000` | 
| [systemjs/systemjs](https://github.com/systemjs/systemjs) | 9483 | `mocha -b -r esm` | 
| [ccampbell/mousetrap](https://github.com/ccampbell/mousetrap) | 9375 | `mocha --reporter=nyan tests/test.mousetrap.js` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 9239 | `mocha --opts mocha.opts` | 
| [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch) | 8998 | `mocha test/src` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8962 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 8937 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8722 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8638 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8594 | `mocha --check-leaks -R dot` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8510 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8489 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8315 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8287 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [tgriesser/knex](https://github.com/tgriesser/knex) | 8962 | `npm run pre_test && nyc mocha --exit --check-leaks --globals __core-js_shared__ -t 10000 -R spec test/index.js && npm run tape && npm run bin_test` | 
| [docsifyjs/docsify](https://github.com/docsifyjs/docsify) | 8937 | `mocha` | 
| [qrohlf/trianglify](https://github.com/qrohlf/trianglify) | 8722 | `mocha test/test.js` | 
| [reactide/reactide](https://github.com/reactide/reactide) | 8638 | `mocha --compilers js:babel-register test/test.js` | 
| [arasatasaygin/is.js](https://github.com/arasatasaygin/is.js) | 8594 | `mocha --check-leaks -R dot` | 
| [MichMich/MagicMirror](https://github.com/MichMich/MagicMirror) | 8510 | `NODE_ENV=test ./node_modules/mocha/bin/mocha tests --recursive` | 
| [hacksalot/HackMyResume](https://github.com/hacksalot/HackMyResume) | 8489 | `grunt clean:test && mocha --exit` | 
| [marko-js/marko](https://github.com/marko-js/marko) | 8315 | `mocha --timeout 10000 ./test/*/*.test.js` | 
| [brave/browser-laptop](https://github.com/brave/browser-laptop) | 8303 | `cross-env NODE_ENV=test mocha "test/**/*Test.js"` | 
| [senchalabs/connect](https://github.com/senchalabs/connect) | 8287 | `mocha --require test/support/env --reporter spec --bail --check-leaks test/` | 
| [Tencent/vConsole](https://github.com/Tencent/vConsole) | 8136 | `mocha` | 
| [visionmedia/supertest](https://github.com/visionmedia/supertest) | 8109 | `nyc --reporter=html --reporter=text mocha --exit --require should --reporter spec --check-leaks` | 
| [uncss/uncss](https://github.com/uncss/uncss) | 8096 | `npm run eslint && npm run mocha` | 
| [gabrielbull/react-desktop](https://github.com/gabrielbull/react-desktop) | 8080 | `./node_modules/.bin/mocha test` | 
| [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) | 8036 | `mocha --ui qunit --reporter list --timeout 10000 -- test/index.js` | 
| [aui/art-template](https://github.com/aui/art-template) | 7942 | `export NODE_ENV=production && istanbul cover node_modules/mocha/bin/_mocha -- --ui exports --colors 'test/**/*.js'` | 
| [webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) | 7643 | `mocha --exit --require @babel/register` | 
| [almende/vis](https://github.com/almende/vis) | 7642 | `mocha --compilers js:babel-core/register` | 
| [oliver-moran/jimp](https://github.com/oliver-moran/jimp) | 7640 | `cross-env BABEL_ENV=test mocha --require @babel/register './packages/**/test/**/*.test.js' --require ts-node/register ./packages/**/test/*.test.ts` | 
| [Mango/slideout](https://github.com/Mango/slideout) | 7619 | `npm run build && istanbul cover _mocha` | 
| [ethereum/web3.js](https://github.com/ethereum/web3.js) | 7616 | `mocha; jshint *.js lib` | 
| [Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) | 7544 | `mocha -r intelli-espower-loader -t 20000 app.test.js --exit` | 
| [rstacruz/jquery.transit](https://github.com/rstacruz/jquery.transit) | 7450 | `mocha` | 
| [remoteintech/remote-jobs](https://github.com/remoteintech/remote-jobs) | 7321 | `mocha` | 
| [segmentio/metalsmith](https://github.com/segmentio/metalsmith) | 7154 | `mocha $HARMONY_OPTS` | 
| [apidoc/apidoc](https://github.com/apidoc/apidoc) | 7116 | `npm run jshint && mocha test/` | 
| [GoogleChrome/workbox](https://github.com/GoogleChrome/workbox) | 7103 | `nyc --clean false --require @std/esm --require ./infra/testing/sw-env --silent mocha --timeout 60000 ./infra/testing/auto-stub-logger.mjs` | 
| [kelektiv/node-uuid](https://github.com/kelektiv/node-uuid) | 7011 | `mocha test/test.js` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4461 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4392 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4334 | `npm run lint ; mocha && mocha test/individual` | 
| [agershun/alasql](https://github.com/agershun/alasql) | 4257 | `npm run build && cd test && mocha . --reporter dot` | 
| [rendrjs/rendr](https://github.com/rendrjs/rendr) | 4191 | `mocha -R spec ./test --recursive` | 
| [muicss/mui](https://github.com/muicss/mui) | 4154 | `mocha` | 
| [tj/ejs](https://github.com/tj/ejs) | 4108 | `mocha --require should --reporter spec` | 
| [expressjs/session](https://github.com/expressjs/session) | 4081 | `mocha --require test/support/env --check-leaks --bail --no-exit --reporter spec test/` | 
| [shoutem/ui](https://github.com/shoutem/ui) | 4061 | `mocha -R spec --require test-utils/setup.js --require react-native-mock/mock.js --compilers js:babel-core/register $(find . -name '*.spec.js' ! -ipath '*node_modules*')` | 
| [mqttjs/MQTT.js](https://github.com/mqttjs/MQTT.js) | 3999 | `node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly --` | 
| [ZijianHe/koa-router](https://github.com/ZijianHe/koa-router) | 3969 | `NODE_ENV=test mocha test/**/*.js` | 
| [yeoman/generator-angular](https://github.com/yeoman/generator-angular) | 5927 | `mocha` | 
| [mozilla-services/react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form) | 5920 | `cross-env NODE_ENV=test mocha --require babel-register --require ./test/setup-jsdom.js test/**/*_test.js` | 
| [rauchg/slackin](https://github.com/rauchg/slackin) | 5917 | `mocha && eslint lib/**` | 
| [yargs/yargs](https://github.com/yargs/yargs) | 5898 | `nyc --cache mocha --require ./test/before.js --timeout=12000 --check-leaks` | 
| [teambit/bit](https://github.com/teambit/bit) | 5895 | `mocha --require babel-core/register './src/**/*.spec.js'` | 
| [KELiON/cerebro](https://github.com/KELiON/cerebro) | 5821 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [react-tools/react-move](https://github.com/react-tools/react-move) | 5746 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [helmetjs/helmet](https://github.com/helmetjs/helmet) | 5682 | `mocha` | 
| [humanwhocodes/computer-science-in-javascript](https://github.com/humanwhocodes/computer-science-in-javascript) | 5679 | `npm run lint && mocha tests/**/*.js` | 
| [mimecorg/vuido](https://github.com/mimecorg/vuido) | 5622 | `mocha test/index.js test/spec/**/*.spec.js` | 
| [josdejong/jsoneditor](https://github.com/josdejong/jsoneditor) | 5499 | `mocha test` | 
| [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js) | 5474 | `mocha -r esm` | 
| [luin/ioredis](https://github.com/luin/ioredis) | 5428 | `NODE_ENV=test mocha --timeout 8000 -r ts-node/register --exit` | 
| [bookshelf/bookshelf](https://github.com/bookshelf/bookshelf) | 5406 | `npm run lint &&  mocha --check-leaks -t 10000 -b test/index.js` | 
| [sintaxi/harp](https://github.com/sintaxi/harp) | 4756 | `mocha --reporter spec -t 8000` | 
| [keithwhor/nodal](https://github.com/keithwhor/nodal) | 4589 | `mocha ./test/runner.js` | 
| [lebab/lebab](https://github.com/lebab/lebab) | 4571 | `mocha --require babel-register "./test/**/*Test.js"` | 
| [bda-research/node-crawler](https://github.com/bda-research/node-crawler) | 4509 | `mocha --timeout=15000 tests/*.test.js` | 
| [josephg/ShareJS](https://github.com/josephg/ShareJS) | 4487 | `node_modules/mocha/bin/mocha test/server test/browser` | 
| [nukeop/nuclear](https://github.com/nukeop/nuclear) | 4461 | `mocha --require babel-register --require babel-polyfill --require ignore-styles --timeout 10000 --prof` | 
| [derbyjs/derby](https://github.com/derbyjs/derby) | 4392 | `./node_modules/.bin/mocha test/all/*.mocha.js; ./node_modules/.bin/jshint lib/*.js test/*.js` | 
| [ramboxapp/community-edition](https://github.com/ramboxapp/community-edition) | 4381 | `./node_modules/.bin/mocha test/tests/**/*.spec.js` | 
| [tjunnone/npm-check-updates](https://github.com/tjunnone/npm-check-updates) | 4334 | `npm run lint ; mocha && mocha test/individual` | 
| [node-apn/node-apn](https://github.com/node-apn/node-apn) | 3683 | `node_modules/.bin/mocha` | 
| [nolanlawson/optimize-js](https://github.com/nolanlawson/optimize-js) | 3682 | `standard && mocha --timeout 60000 test/test.js` | 
| [socketio/engine.io](https://github.com/socketio/engine.io) | 3680 | `npm run lint && mocha && EIO_WS_ENGINE=uws mocha` | 
| [jspm/jspm-cli](https://github.com/jspm/jspm-cli) | 3674 | `npm run jshint && npm run mocha` | 
| [expressjs/body-parser](https://github.com/expressjs/body-parser) | 3663 | `mocha --require test/support/env --reporter spec --check-leaks --bail test/` | 
| [yeoman/generator-webapp](https://github.com/yeoman/generator-webapp) | 3608 | `eslint . && mocha --reporter spec --timeout 3000` | 
| [blakeembrey/code-problems](https://github.com/blakeembrey/code-problems) | 3606 | `mocha tests/javascript` | 
| [GoogleChromeLabs/sw-toolbox](https://github.com/GoogleChromeLabs/sw-toolbox) | 3601 | `gulp lint default && node ./test/helpers/download-browsers.js && mocha` | 
| [socketstream/socketstream](https://github.com/socketstream/socketstream) | 3563 | `node_modules/.bin/mocha test/unit/**/*.js --reporter spec` | 
| [contra/react-responsive](https://github.com/contra/react-responsive) | 3547 | `cross-env NODE_PATH=$NODE_PATH:$PWD/src mocha -R spec --compilers js:@babel/register --require ./test/setup.js test/*_test.js` | 
| [fzaninotto/uptime](https://github.com/fzaninotto/uptime) | 3496 | `node_modules/.bin/mocha test/lib/` | 
| [henryboldi/felony](https://github.com/henryboldi/felony) | 3468 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [konvajs/konva](https://github.com/konvajs/konva) | 3457 | `mocha-headless-chrome -f ./test/runner.html -a disable-web-security` | 
| [ttezel/twit](https://github.com/ttezel/twit) | 3450 | `./node_modules/.bin/mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners` | 
| [dthree/vantage](https://github.com/dthree/vantage) | 3448 | `mocha` | 
| [StephenGrider/ReduxSimpleStarter](https://github.com/StephenGrider/ReduxSimpleStarter) | 3447 | `mocha --compilers js:babel-core/register --require ./test/test_helper.js --recursive ./test` | 
| [wuchangming/spy-debugger](https://github.com/wuchangming/spy-debugger) | 3415 | `mocha -R landing test/index --exit` | 
| [nadbm/react-datasheet](https://github.com/nadbm/react-datasheet) | 3380 | `standard src/*.js && NODE_ENV=test nyc --  mocha ./test/**/*.js --compilers js:babel-register` | 
| [google-map-react/google-map-react](https://github.com/google-map-react/google-map-react) | 3369 | `NODE_ENV=eee mocha --compilers js:babel-register --recursive --require babel-polyfill` | 
| [aui/font-spider](https://github.com/aui/font-spider) | 3342 | `mocha test/index.js && npm run demo` | 
| [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) | 3291 | `mocha` | 
| [shakiba/planck.js](https://github.com/shakiba/planck.js) | 3286 | `mocha test/*.js` | 
| [swagger-api/swagger-node](https://github.com/swagger-api/swagger-node) | 3264 | `mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons` | 
| [yagop/node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) | 3262 | `npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [codemix/fast.js](https://github.com/codemix/fast.js) | 3235 | `mocha` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3196 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [heroku/react-refetch](https://github.com/heroku/react-refetch) | 3196 | `mocha --compilers js:babel-core/register --recursive --require ./test/setup.js` | 
| [KartikTalwar/gmail.js](https://github.com/KartikTalwar/gmail.js) | 3190 | `./node_modules/.bin/mocha test/test.*.js` | 
| [gsuitedevs/md2googleslides](https://github.com/gsuitedevs/md2googleslides) | 3187 | `npm run compile && mocha --compilers js:babel-core/register --timeout 5000` | 
| [broccolijs/broccoli](https://github.com/broccolijs/broccoli) | 3178 | `mocha` | 
| [Yomguithereal/react-blessed](https://github.com/Yomguithereal/react-blessed) | 3137 | `mocha -R spec --require babel-register ./test/endpoint.js` | 
| [octokit/rest.js](https://github.com/octokit/rest.js) | 3122 | `nyc mocha test/mocha-node-setup.js "test/*/**/*-test.js"` | 
| [jpuri/react-draft-wysiwyg](https://github.com/jpuri/react-draft-wysiwyg) | 3122 | `cross-env BABEL_ENV=test mocha --compilers js:config/test-compiler.js config/test-setup.js src/**/*Test.js` | 
| [pegjs/pegjs](https://github.com/pegjs/pegjs) | 3120 | `nyc mocha --recursive` | 
| [mongo-express/mongo-express](https://github.com/mongo-express/mongo-express) | 3105 | `npm run mocha && npm run lint` | 
| [arkency/reactjs_koans](https://github.com/arkency/reactjs_koans) | 3069 | `npm run compile && mocha -b --compilers js:babel/register --require test/helpers.js test/**/*.js || echo` | 
| [auth0/express-jwt](https://github.com/auth0/express-jwt) | 3062 | `node_modules/.bin/mocha --reporter spec` | 
| [draft-js-plugins/draft-js-plugins](https://github.com/draft-js-plugins/draft-js-plugins) | 3046 | `node_modules/.bin/mocha --compilers js:babel-core/register --require testHelper.js "./{,!(node_modules)/**/}/__test__/*.js"` | 
| [mdaines/viz.js](https://github.com/mdaines/viz.js) | 3036 | `mocha test-node` | 
| [jsonresume/resume-cli](https://github.com/jsonresume/resume-cli) | 3025 | `node node_modules/mocha/bin/mocha test test/*.js` | 
| [toji/gl-matrix](https://github.com/toji/gl-matrix) | 3015 | `mocha --require @babel/register --recursive spec` | 
| [negomi/react-burger-menu](https://github.com/negomi/react-burger-menu) | 3015 | `cross-env NODE_ENV=test mocha --require babel-register --require jsdom-global/register --reporter list` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2637 | `mocha-phantomjs ./test/index.html` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2601 | `mocha test --exit && npm run lint` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2582 | `mocha` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2565 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2557 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2552 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2535 | `mocha --reporter=spec test/*-test.js` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2527 | `mocha test/index.js --reporter dot` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2508 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2499 | `nyc --require babel-register npm run _mocha` | 
| [katiefenn/parker](https://github.com/katiefenn/parker) | 2453 | `mocha --no-colors --reporter spec` | 
| [NeXTs/Jets.js](https://github.com/NeXTs/Jets.js) | 2637 | `mocha-phantomjs ./test/index.html` | 
| [oauthjs/node-oauth2-server](https://github.com/oauthjs/node-oauth2-server) | 2628 | `NODE_ENV=test ./node_modules/.bin/mocha 'test/**/*_test.js'` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2594 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2589 | `TEST=all mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2587 | `mocha && eslint .` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2573 | `mocha test/src/**/*.unit.js` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2565 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2557 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2552 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2535 | `mocha --reporter=spec test/*-test.js` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2508 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [Qix-/color](https://github.com/Qix-/color) | 2489 | `mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2471 | `mocha -R spec` | 
| [tapio/live-server](https://github.com/tapio/live-server) | 2601 | `mocha test --exit && npm run lint` | 
| [reactGo/reactGo](https://github.com/reactGo/reactGo) | 2594 | `mocha ./app/tests/setup.js --compilers css:./app/tests/compilers/css ./app/**/*-test.js` | 
| [orbitdb/orbit-db](https://github.com/orbitdb/orbit-db) | 2589 | `TEST=all mocha` | 
| [apostrophecms/apostrophe](https://github.com/apostrophecms/apostrophe) | 2587 | `mocha && eslint .` | 
| [kamranahmedse/pennywise](https://github.com/kamranahmedse/pennywise) | 2582 | `mocha` | 
| [wix/react-templates](https://github.com/wix/react-templates) | 2573 | `mocha test/src/**/*.unit.js` | 
| [fex-team/fis3](https://github.com/fex-team/fis3) | 2567 | `mocha test` | 
| [mrvautin/adminMongo](https://github.com/mrvautin/adminMongo) | 2565 | `find ./tests -name '*.js' | xargs mocha -R spec -t 5000` | 
| [h2non/toxy](https://github.com/h2non/toxy) | 2557 | `standard index.js 'lib/**/*.js' 'test/**/*.js' && mocha --timeout 5000 --bail --reporter spec --ui tdd 'test/**/*.js'` | 
| [devongovett/regexgen](https://github.com/devongovett/regexgen) | 2552 | `mocha` | 
| [spdy-http2/node-spdy](https://github.com/spdy-http2/node-spdy) | 2535 | `mocha --reporter=spec test/*-test.js` | 
| [Reportr/dashboard](https://github.com/Reportr/dashboard) | 2534 | `export TESTING=true; mocha --reporter list` | 
| [panzerdp/voca](https://github.com/panzerdp/voca) | 2527 | `mocha test/index.js --reporter dot` | 
| [lindell/JsBarcode](https://github.com/lindell/JsBarcode) | 2508 | `gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec` | 
| [mysticatea/npm-run-all](https://github.com/mysticatea/npm-run-all) | 2499 | `nyc --require babel-register npm run _mocha` | 
| [Qix-/color](https://github.com/Qix-/color) | 2489 | `mocha` | 
| [jhnns/rewire](https://github.com/jhnns/rewire) | 2471 | `mocha -R spec` | 
| [danvk/source-map-explorer](https://github.com/danvk/source-map-explorer) | 2249 | `mocha && eslint *.js` | 
| [hipache/hipache](https://github.com/hipache/hipache) | 2246 | `istanbul test _mocha --report html -- test/**/*.js --reporter spec --timeout 4000` | 
| [mplewis/src2png](https://github.com/mplewis/src2png) | 2218 | `mocha test test/unit/**/*_test.js` | 
| [rgrove/rawgit](https://github.com/rgrove/rawgit) | 2212 | `NODE_ENV=test mocha -R dot test/**/test.*.js` | 
| [vpulim/node-soap](https://github.com/vpulim/node-soap) | 2212 | `mocha --timeout 15000 --bail --exit test/*-test.js test/security/*.js` | 
| [OptimalBits/node_acl](https://github.com/OptimalBits/node_acl) | 2208 | `mocha test/runner.js --reporter spec` | 
| [mozilla/readability](https://github.com/mozilla/readability) | 2201 | `mocha test/test-*.js` | 
| [dankogai/js-base64](https://github.com/dankogai/js-base64) | 2184 | `mocha --compilers js:babel-register` | 
| [carlsednaoui/ouibounce](https://github.com/carlsednaoui/ouibounce) | 2160 | `mocha` | 
| [borisyankov/react-sparklines](https://github.com/borisyankov/react-sparklines) | 2155 | `mocha --compilers js:babel-core/register __tests__` | 
| [apocas/dockerode](https://github.com/apocas/dockerode) | 2151 | `./node_modules/mocha/bin/mocha -R spec --exit` | 
| [dherault/serverless-offline](https://github.com/dherault/serverless-offline) | 2147 | `mocha test` | 
| [lynndylanhurley/redux-auth](https://github.com/lynndylanhurley/redux-auth) | 2134 | `node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2100 | `mocha` | 
| [kach/nearley](https://github.com/kach/nearley) | 2099 | `mocha test/*.test.js` | 
| [uber-archive/image-diff](https://github.com/uber-archive/image-diff) | 2388 | `grunt jshint && mocha` | 
| [s-a/iron-node](https://github.com/s-a/iron-node) | 2366 | `node node_modules/mocha/bin/_mocha` | 
| [pahen/madge](https://github.com/pahen/madge) | 2362 | `npm run lint && npm run mocha` | 
| [lmenezes/cerebro](https://github.com/lmenezes/cerebro) | 2335 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha-webpack` | 
| [kunalkapadia/express-mongoose-es6-rest-api](https://github.com/kunalkapadia/express-mongoose-es6-rest-api) | 2334 | `cross-env NODE_ENV=test ./node_modules/.bin/mocha --ui bdd --reporter spec --colors server --recursive` | 
| [adaltas/node-csv](https://github.com/adaltas/node-csv) | 2326 | `mocha test/**/*.coffee` | 
| [gajus/swing](https://github.com/gajus/swing) | 2326 | `mocha --compilers js:babel-register` | 
| [acdlite/redux-router](https://github.com/acdlite/redux-router) | 2320 | `mocha --compilers js:babel/register --recursive --require src/__tests__/init.js src/**/*-test.js` | 
| [opentypejs/opentype.js](https://github.com/opentypejs/opentype.js) | 2317 | `mocha --require reify --compilers js:buble/register --recursive && jshint . && jscs .` | 
| [esbenp/pdf-bot](https://github.com/esbenp/pdf-bot) | 2314 | `nyc --reporter=lcov --reporter=text mocha test/*.test.js --recursive --coverage` | 
| [davidmerfield/Typeset](https://github.com/davidmerfield/Typeset) | 2290 | `mocha -u bdd -R spec -t 500 --recursive` | 
| [reactjs/react-a11y](https://github.com/reactjs/react-a11y) | 2105 | `npm run mocha && npm run karma` | 
| [paulsonnentag/swip](https://github.com/paulsonnentag/swip) | 2100 | `mocha` | 
| [ivanakimov/hashids.js](https://github.com/ivanakimov/hashids.js) | 2065 | `mocha tests --require @babel/register` | 
| [fb55/htmlparser2](https://github.com/fb55/htmlparser2) | 2064 | `mocha && npm run lint` | 
| [mjrussell/redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) | 2056 | `mocha --compilers js:babel-core/register --recursive --require test/init.js test/authWrapper-test.js` | 
| [freeCodeCamp/guide](https://github.com/freeCodeCamp/guide) | 2055 | `yarn ensure-page-naming && mocha  -R spec "./{,!(node_modules)/**/}*.test.js"` | 
| [yeoman/generator-chrome-extension](https://github.com/yeoman/generator-chrome-extension) | 2043 | `mocha --reporter spec --timeout 5000` | 
| [then/promise](https://github.com/then/promise) | 2020 | `mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak` | 
| [hojberg/cssarrowplease](https://github.com/hojberg/cssarrowplease) | 2015 | `mocha --require=test/test_helper.js` | 
| [jaredhanson/passport-local](https://github.com/jaredhanson/passport-local) | 2013 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [slate/slate](https://github.com/slate/slate) | 1993 | `cross-env BABEL_ENV=test FORBID_WARNINGS=true mocha --require babel-core/register ./packages/*/test/index.js` | 
| [webrtcHacks/adapter](https://github.com/webrtcHacks/adapter) | 1779 | `grunt && grunt downloadBrowser && mocha test/unit && karma start test/karma.conf.js` | 
| [speakeasyjs/speakeasy](https://github.com/speakeasyjs/speakeasy) | 1777 | `mocha` | 
| [gcanti/tcomb](https://github.com/gcanti/tcomb) | 1773 | `npm run lint && mocha && npm run typescript` | 
| [mbloch/mapshaper](https://github.com/mbloch/mapshaper) | 1752 | `node node_modules/mocha/bin/mocha --check-leaks -R dot` | 
| [expressjs/compression](https://github.com/expressjs/compression) | 1750 | `mocha --check-leaks --reporter spec --bail` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1745 | `./node_modules/.bin/mocha` | 
| [cliftonc/calipso](https://github.com/cliftonc/calipso) | 1743 | `NODE_ENV=mocha ./node_modules/.bin/mocha --reporter spec -t 80000 -s 500` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1733 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1731 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1728 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1724 | `mocha test/**/*_test.js --bail` | 
| [Kong/mashape-oauth](https://github.com/Kong/mashape-oauth) | 1724 | `mocha` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1720 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1716 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [pstadler/flightplan](https://github.com/pstadler/flightplan) | 1745 | `./node_modules/.bin/mocha` | 
| [cazala/coin-hive](https://github.com/cazala/coin-hive) | 1734 | `mocha test --timeout 600000` | 
| [trailsjs/trails](https://github.com/trailsjs/trails) | 1733 | `eslint --ignore-path .gitignore index.js lib/ test/ && nyc mocha` | 
| [molnarg/node-http2](https://github.com/molnarg/node-http2) | 1731 | `istanbul test _mocha -- --reporter spec --slow 500 --timeout 15000` | 
| [webpack/webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) | 1728 | `nyc --reporter lcovonly mocha --full-trace --check-leaks --exit` | 
| [toish/chromatism](https://github.com/toish/chromatism) | 1727 | `BABEL_ENV=test mocha --compilers js:babel-core/register` | 
| [eleith/emailjs](https://github.com/eleith/emailjs) | 1725 | `mocha` | 
| [facebookarchive/fb-flo](https://github.com/facebookarchive/fb-flo) | 1724 | `mocha test/**/*_test.js --bail` | 
| [danmactough/node-feedparser](https://github.com/danmactough/node-feedparser) | 1720 | `mocha` | 
| [bkimminich/juice-shop](https://github.com/bkimminich/juice-shop) | 1716 | `cd frontend && ng test --watch=false --source-map=false && cd .. && nyc --report-dir=./build/reports/coverage/server-tests mocha test/server` | 
| [Automattic/knox](https://github.com/Automattic/knox) | 1714 | `mocha` | 
| [BinaryMuse/fluxxor](https://github.com/BinaryMuse/fluxxor) | 1693 | `npm run jshint && mocha --recursive` | 
| [helpers/handlebars-helpers](https://github.com/helpers/handlebars-helpers) | 1691 | `mocha` | 
| [ai/visibilityjs](https://github.com/ai/visibilityjs) | 1689 | `mocha && size-limit` | 
| [securingsincity/react-ace](https://github.com/securingsincity/react-ace) | 1683 | `mocha --require babel-register --require tests/setup.js tests/**/*.spec.js --exit` | 
| [mzgoddard/hard-source-webpack-plugin](https://github.com/mzgoddard/hard-source-webpack-plugin) | 1676 | `NODE_ENV=test mocha tests/*.js` | 
| [gajus/redux-immutable](https://github.com/gajus/redux-immutable) | 1672 | `mocha --compilers js:babel-register './tests/**/*.js'` | 
| [gitsummore/nile.js](https://github.com/gitsummore/nile.js) | 1671 | `./node_modules/mocha/bin/mocha ./test.js` | 
| [FormidableLabs/freactal](https://github.com/FormidableLabs/freactal) | 1669 | `mocha spec` | 
| [addyosmani/tmi](https://github.com/addyosmani/tmi) | 1667 | `xo && mocha` | 
| [openstyles/stylus](https://github.com/openstyles/stylus) | 1657 | `mocha test/ test/middleware/ --require should --bail --check-leaks --reporter dot` | 
| [JustinTulloss/zeromq.node](https://github.com/JustinTulloss/zeromq.node) | 1645 | `mocha --expose-gc --slow 300` | 
| [jakiestfu/himawari.js](https://github.com/jakiestfu/himawari.js) | 1640 | `mocha tests/test.js` | 
| [sasstools/sass-lint](https://github.com/sasstools/sass-lint) | 1637 | `istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec -t 3000 tests tests/rules tests/helpers` | 
| [Caligatio/jsSHA](https://github.com/Caligatio/jsSHA) | 1634 | `mocha --reporter spec` | 
| [seejohnrun/haste-server](https://github.com/seejohnrun/haste-server) | 1634 | `mocha --recursive` | 
| [Foliotek/Croppie](https://github.com/Foliotek/Croppie) | 1626 | `mocha test/unit` | 
| [node-webot/weixin-robot](https://github.com/node-webot/weixin-robot) | 1625 | `./node_modules/mocha/bin/mocha -R spec` | 
| [guo-yu/douban.fm](https://github.com/guo-yu/douban.fm) | 1624 | `node_modules/mocha/bin/mocha tests/*.js --require tests/babelhook` | 
| [apifytech/apify-js](https://github.com/apifytech/apify-js) | 1624 | `npm run build &&  nyc --reporter=html --reporter=text mocha --timeout 60000 --require @babel/register --recursive --exit` | 
| [ericclemmons/react-resolver](https://github.com/ericclemmons/react-resolver) | 1622 | `mocha` | 
| [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) | 1618 | `mocha -R spec ./test/unit/**` | 
| [jamiebuilds/babel-react-optimize](https://github.com/jamiebuilds/babel-react-optimize) | 1614 | `eslint packages/*/test packages/*/src && mocha packages/*/test/index.js --compilers js:babel-register` | 
| [lodash/babel-plugin-lodash](https://github.com/lodash/babel-plugin-lodash) | 1569 | `mocha --check-leaks --require @babel/register` | 
| [andreaferretti/paths-js](https://github.com/andreaferretti/paths-js) | 1559 | `mocha --reporter nyan --compilers js:babel/register --recursive test` | 
| [socraticorg/mathsteps](https://github.com/socraticorg/mathsteps) | 1556 | `node_modules/.bin/mocha --recursive` | 
| [superscriptjs/superscript](https://github.com/superscriptjs/superscript) | 1546 | `mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive` | 
| [numbers/numbers.js](https://github.com/numbers/numbers.js) | 1544 | `mocha -u tdd` | 
| [zendesk/cross-storage](https://github.com/zendesk/cross-storage) | 1543 | `./node_modules/.bin/zuul --local 8080 --ui mocha-bdd -- test/test.js` | 
| [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill) | 1541 | `npm run lint && mocha && karma start --single-run` | 
| [gaearon/react-document-title](https://github.com/gaearon/react-document-title) | 1538 | `mocha` | 
| [kefirjs/kefir](https://github.com/kefirjs/kefir) | 1535 | `./configs/prettier.sh check && rollup -c ./configs/rollup.dev.js && mocha && flow check` | 
| [lukehaas/Scrollify](https://github.com/lukehaas/Scrollify) | 1530 | `mocha ./test/scrollify_test.js --recursive ./test` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1524 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1524 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [tschaub/gh-pages](https://github.com/tschaub/gh-pages) | 1517 | `mocha --recursive test` | 
| [noble/bleno](https://github.com/noble/bleno) | 1517 | `mocha -R spec test/*.js` | 
| [carteb/carte-blanche](https://github.com/carteb/carte-blanche) | 1527 | `node_modules/.bin/mocha --opts mocha.opts` | 
| [frctl/fractal](https://github.com/frctl/fractal) | 1524 | `./node_modules/.bin/_mocha --require test/support/env --reporter spec` | 
| [web-push-libs/web-push](https://github.com/web-push-libs/web-push) | 1524 | `node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --ui tdd test/test*` | 
| [wit-ai/node-wit](https://github.com/wit-ai/node-wit) | 1520 | `mocha --timeout 10000 ./tests/lib.js` | 
| [noble/bleno](https://github.com/noble/bleno) | 1517 | `mocha -R spec test/*.js` | 
| [dilame/instagram-private-api](https://github.com/dilame/instagram-private-api) | 1511 | `./node_modules/mocha/bin/mocha --inline-diffs --timeout 1000000 tests/run.js` | 
| [punkave/sanitize-html](https://github.com/punkave/sanitize-html) | 1509 | `npm run prepublishOnly && mocha test/test.js` | 
| [djfarrelly/MailDev](https://github.com/djfarrelly/MailDev) | 1508 | `standard && istanbul cover _mocha` | 
| [fbeline/Design-Patterns-JS](https://github.com/fbeline/Design-Patterns-JS) | 1502 | `mocha test --compilers js:babel-core/register` | 
| [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) | 1490 | `node test/demo.js && node test/load_dict_demo.js && mocha --timeout 10s -R spec test/test.js && mocha --timeout 10s -R spec test/load_dict_test.js` | 
| [johntitus/node-horseman](https://github.com/johntitus/node-horseman) | 1479 | `mocha -R spec` | 
| [yahoo/serialize-javascript](https://github.com/yahoo/serialize-javascript) | 1469 | `istanbul cover -- ./node_modules/mocha/bin/_mocha test/unit/ --reporter spec` | 
| [zcreativelabs/react-simple-maps](https://github.com/zcreativelabs/react-simple-maps) | 1403 | `mocha './tests/**/*.spec.js' --compilers js:babel-core/register` | 
| [rwieruch/favesound-redux](https://github.com/rwieruch/favesound-redux) | 1394 | `mocha --compilers js:babel-core/register --require ./test/setup.js 'src/**/spec.js'` | 
| [abouolia/sticky-sidebar](https://github.com/abouolia/sticky-sidebar) | 1394 | `mocha --compilers js:babel-core/register` | 
| [dlmanning/gulp-sass](https://github.com/dlmanning/gulp-sass) | 1384 | `./node_modules/.bin/mocha test` | 
| [wonderunit/storyboarder](https://github.com/wonderunit/storyboarder) | 1384 | `mocha $(find test -name '*[!renderer].test.js') && electron-mocha --renderer test/*.renderer.test.js test/**/*.renderer.test.js && electron-mocha test/**/*.main.test.js` | 
| [marcelduran/webpagetest-api](https://github.com/marcelduran/webpagetest-api) | 1370 | `./node_modules/mocha/bin/mocha -R spec test/*-test.js` | 
| [vuejs/babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx) | 1369 | `npm run lint && mocha --require @babel/register` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1347 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1347 | `mocha tests/` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1346 | `mocha` | 
| [primus/eventemitter3](https://github.com/primus/eventemitter3) | 1343 | `nyc --reporter=html --reporter=text mocha test/test.js` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1336 | `npm run lint && npm run mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1334 | `mocha --timeout 60000 test/` | 
| [donejs/donejs](https://github.com/donejs/donejs) | 1302 | `npm run jshint && npm run mocha && npm run document && npm run test-guides` | 
| [domenic/chai-as-promised](https://github.com/domenic/chai-as-promised) | 1299 | `mocha` | 
| [FormidableLabs/victory-native](https://github.com/FormidableLabs/victory-native) | 1298 | `mocha --compilers test/compiler.js --recursive test/spec/*.js` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1271 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1263 | `mocha tests` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1250 | `mocha` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [kantord/just-dashboard](https://github.com/kantord/just-dashboard) | 1347 | `mocha-webpack "src/**/*.test.js" --webpack-config webpack.test.config.js --require babel-polyfill --reporter mochawesome` | 
| [Ziv-Barber/officegen](https://github.com/Ziv-Barber/officegen) | 1347 | `mocha tests/` | 
| [evanw/node-source-map-support](https://github.com/evanw/node-source-map-support) | 1346 | `mocha` | 
| [themikenicholson/passport-jwt](https://github.com/themikenicholson/passport-jwt) | 1343 | `./node_modules/.bin/mocha --reporter spec --require test/bootstrap test/*test.js` | 
| [react-tools/react-form](https://github.com/react-tools/react-form) | 1343 | `mocha-webpack --opts tests/mocha-webpack.opts` | 
| [ctimmerm/axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) | 1342 | `mocha` | 
| [messageformat/messageformat](https://github.com/messageformat/messageformat) | 1341 | `lerna run test && mocha` | 
| [adleroliveira/dreamjs](https://github.com/adleroliveira/dreamjs) | 1340 | `mocha` | 
| [btmills/geopattern](https://github.com/btmills/geopattern) | 1336 | `npm run lint && npm run mocha` | 
| [andywer/leakage](https://github.com/andywer/leakage) | 1334 | `mocha --timeout 60000 test/` | 
| [shakiba/stage.js](https://github.com/shakiba/stage.js) | 1332 | `mocha test/*.js` | 
| [justadudewhohacks/face-recognition.js](https://github.com/justadudewhohacks/face-recognition.js) | 1330 | `mocha --timeout 30000 --recursive ./tests` | 
| [FormidableLabs/rapscallion](https://github.com/FormidableLabs/rapscallion) | 1329 | `mocha spec/exec.js` | 
| [webpro/reveal-md](https://github.com/webpro/reveal-md) | 1328 | `mocha` | 
| [nicolas-t/Chocolat](https://github.com/nicolas-t/Chocolat) | 1328 | `./node_modules/.bin/mocha-phantomjs test/index.html` | 
| [Schmavery/facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) | 1327 | `mocha` | 
| [yyx990803/pod](https://github.com/yyx990803/pod) | 1326 | `mocha test/api.js -r jscoverage -R spec --slow 1250 --timeout 5000 && bash test/cli.sh` | 
| [gkajs/gka](https://github.com/gkajs/gka) | 1325 | `mocha --timeout 20000` | 
| [fossasia/open-event-wsgen](https://github.com/fossasia/open-event-wsgen) | 1271 | `mocha` | 
| [enyo/opentip](https://github.com/enyo/opentip) | 1266 | `node_modules/mocha-phantomjs/bin/mocha-phantomjs test/test.html` | 
| [lloyd/node-toobusy](https://github.com/lloyd/node-toobusy) | 1263 | `mocha tests` | 
| [normalize/mz](https://github.com/normalize/mz) | 1260 | `mocha --reporter spec` | 
| [ramda/ramda-fantasy](https://github.com/ramda/ramda-fantasy) | 1250 | `mocha` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1250 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1244 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1231 | `node ./node_modules/mocha/bin/mocha tests` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1221 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [pillarjs/hbs](https://github.com/pillarjs/hbs) | 1250 | `istanbul cover node_modules/mocha/bin/_mocha` | 
| [electron/asar](https://github.com/electron/asar) | 1244 | `xvfb-maybe electron-mocha --reporter spec && mocha --reporter spec && npm run lint` | 
| [mhink/react-ionize](https://github.com/mhink/react-ionize) | 1241 | `mocha-webpack --webpack-config webpack.test.config.js "test/**/*.spec.js"` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1239 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [arqex/freezer](https://github.com/arqex/freezer) | 1231 | `node ./node_modules/mocha/bin/mocha tests` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1229 | `mocha test` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1213 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1213 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1210 | `mocha --recursive -r tests/setup tests` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1209 | `mocha test` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1209 | `mocha --reporter spec --bail --check-leaks test/` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1207 | `mocha test/test.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1205 | `npm-run-all test:jest test:server:mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1205 | `mocha --reporter spec --bail --check-leaks test/` | 
| [catamphetamine/webpack-isomorphic-tools](https://github.com/catamphetamine/webpack-isomorphic-tools) | 1239 | `mocha --compilers js:babel-core/register --colors --bail --reporter spec test/ --recursive` | 
| [patriksimek/vm2](https://github.com/patriksimek/vm2) | 1229 | `mocha test` | 
| [slushjs/slush](https://github.com/slushjs/slush) | 1221 | `node gulpfile.js && NODE_ENV=test mocha --reporter spec` | 
| [depcheck/depcheck](https://github.com/depcheck/depcheck) | 1213 | `node -r @babel/register node_modules/mocha/bin/_mocha ./test ./test/special --timeout 10000` | 
| [web-pal/DBGlass](https://github.com/web-pal/DBGlass) | 1213 | `cross-env NODE_ENV=test mocha --compilers js:babel-register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [microstates/microstates.js](https://github.com/microstates/microstates.js) | 1210 | `mocha --recursive -r tests/setup tests` | 
| [shift-js/shift-js](https://github.com/shift-js/shift-js) | 1209 | `mocha test` | 
| [expressjs/generator](https://github.com/expressjs/generator) | 1209 | `mocha --reporter spec --bail --check-leaks test/` | 
| [Rich-Harris/butternut](https://github.com/Rich-Harris/butternut) | 1207 | `mocha test/test.js` | 
| [coralproject/talk](https://github.com/coralproject/talk) | 1205 | `npm-run-all test:jest test:server:mocha` | 
| [expressjs/cookie-parser](https://github.com/expressjs/cookie-parser) | 1205 | `mocha --reporter spec --bail --check-leaks test/` | 
| [symfony/webpack-encore](https://github.com/symfony/webpack-encore) | 1203 | `mocha --reporter spec test --recursive` | 
| [levelgraph/levelgraph](https://github.com/levelgraph/levelgraph) | 1107 | `mocha --recursive --bail --reporter spec test` | 
| [laravel/elixir](https://github.com/laravel/elixir) | 1102 | `cd elixir-test-app && mocha --require babel-core/register --require=test/bootstrap.js` | 
| [jaredhanson/passport-facebook](https://github.com/jaredhanson/passport-facebook) | 1101 | `node_modules/.bin/mocha --require test/bootstrap/node test/*.test.js` | 
| [mridgway/hoist-non-react-statics](https://github.com/mridgway/hoist-non-react-statics) | 1097 | `mocha tests/unit/ --recursive --compilers js:babel-register --reporter spec` | 
| [derbyjs/racer](https://github.com/derbyjs/racer) | 1097 | `node_modules/.bin/mocha && npm run lint` | 
| [gaearon/babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) | 1093 | `mocha --compilers js:babel-register` | 
| [YuzuJS/setImmediate](https://github.com/YuzuJS/setImmediate) | 1088 | `mocha test/tests.js` | 
| [tomas/needle](https://github.com/tomas/needle) | 1082 | `mocha test` | 
| [mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api) | 1082 | `./node_modules/jshint/bin/jshint index.js && ./node_modules/jscs/bin/jscs index.js && ./node_modules/mocha/bin/mocha` | 
| [jacobrask/styledocco](https://github.com/jacobrask/styledocco) | 1080 | `nodeunit test; mocha test` | 
| [gulpjs/vinyl](https://github.com/gulpjs/vinyl) | 1071 | `mocha --async-only` | 
| [olahol/react-tagsinput](https://github.com/olahol/react-tagsinput) | 1064 | `standard src/index.js && mocha --compilers js:babel-register` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1057 | `mocha $(find test -name '*.test.js')` | 
| [kisenka/svg-sprite-loader](https://github.com/kisenka/svg-sprite-loader) | 1057 | `mocha test/*.test.js` | 
| [bigpipe/bigpipe](https://github.com/bigpipe/bigpipe) | 1057 | `mocha $(find test -name '*.test.js')` | 
| [johnagan/clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) | 1055 | `mocha --recursive ./test/*_spec.js` | 
| [RisingStack/graffiti](https://github.com/RisingStack/graffiti) | 1039 | `NODE_ENV=test mocha --compilers js:babel-register 'src/**/*.spec.js'` | 
| [SelectTransform/st.js](https://github.com/SelectTransform/st.js) | 1038 | `mocha --recursive test/unit/` | 
| [expressjs/serve-static](https://github.com/expressjs/serve-static) | 1033 | `mocha --reporter spec --bail --check-leaks test/` | 
| [apollographql/graphql-tag](https://github.com/apollographql/graphql-tag) | 1030 | `mocha test/graphql.js test/graphql-v0.12.js && tav --ci --compat` | 
| [blockstack/blockstack-browser](https://github.com/blockstack/blockstack-browser) | 1027 | `npm run lint && npm run flow && cross-env NODE_ENV=test nyc mocha` | 
| [james-proxy/james](https://github.com/james-proxy/james) | 1026 | `mocha-webpack --reporter dot --webpack-config webpack.test.config.js --recursive test/unit` | 
| [AlexGilleran/jsx-control-statements](https://github.com/AlexGilleran/jsx-control-statements) | 1026 | `mocha spec/*.js` | 
| [MohammadYounes/rtlcss](https://github.com/MohammadYounes/rtlcss) | 1022 | `npm run lint && mocha -R spec` | 
| [sghall/resonance](https://github.com/sghall/resonance) | 1019 | `cross-env BABEL_ENV=test mocha "src/**/*.spec.js"` | 
| [krasimir/cssx](https://github.com/krasimir/cssx) | 1017 | `mocha --colors ./test/*.spec.js` | 
| [GantMan/ReactStateMuseum](https://github.com/GantMan/ReactStateMuseum) | 1017 | `node_modules/mocha/bin/_mocha ./test/index.js` | 
| [brianreavis/sifter.js](https://github.com/brianreavis/sifter.js) | 1007 | `mocha -R list` | 
| [js-joda/js-joda](https://github.com/js-joda/js-joda) | 1007 | `NODE_ENV=test ./node_modules/.bin/mocha --timeout 5000 --require babel-core/register ./test/*Test.js ./test/**/*Test.js ./test/**/**/*Test.js ./test/*Test_mochaOnly.js` | 
| [pwnn/is.js](https://github.com/pwnn/is.js) | 1007 | `mocha --check-leaks -R dot` | 
| [mozilla/node-convict](https://github.com/mozilla/node-convict) | 1004 | `mocha --check-leaks -R spec test/*-tests.js` | 
| [defunctzombie/zuul](https://github.com/defunctzombie/zuul) | 997 | `DEBUG=zuul* mocha --ui qunit --timeout 0 --bail -- test/index.js` | 
| [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) | 989 | `mocha "client.test" --compilers js:babel-register` | 
| [pid/speakingurl](https://github.com/pid/speakingurl) | 983 | `mocha` | 
| [OverZealous/run-sequence](https://github.com/OverZealous/run-sequence) | 983 | `mocha --reporter spec` | 
| [ianstormtaylor/react-values](https://github.com/ianstormtaylor/react-values) | 981 | `cross-env BABEL_ENV=test mocha --require babel-core/register ./test/index.js` | 
| [strongloop/microgateway](https://github.com/strongloop/microgateway) | 979 | `mocha -t 600000 --exit` | 
| [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | 979 | `mocha tests` | 
| [nolanlawson/marky](https://github.com/nolanlawson/marky) | 979 | `npm run rollup-cjs && mocha test/test.js` | 
| [gaearon/react-side-effect](https://github.com/gaearon/react-side-effect) | 979 | `mocha` | 
| [pillarjs/multiparty](https://github.com/pillarjs/multiparty) | 951 | `mocha --reporter spec --bail --check-leaks --no-exit test/` | 
| [crcn/sift.js](https://github.com/crcn/sift.js) | 948 | `mocha ./test -R spec --compilers js:babel-core/register` | 
| [shanelau/zhihu](https://github.com/shanelau/zhihu) | 945 | `./node_modules/mocha/bin/mocha --timeout 15000` | 
| [digitalbazaar/jsonld.js](https://github.com/digitalbazaar/jsonld.js) | 943 | `cross-env NODE_ENV=test mocha --delay -t 30000 -A -R ${REPORTER:-spec} tests/test.js` | 
| [dantrain/react-stonecutter](https://github.com/dantrain/react-stonecutter) | 928 | `mocha -R spec --compilers jsx:babel-register test/*.jsx` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 923 | `mocha -t 5000` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 921 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [domchristie/humps](https://github.com/domchristie/humps) | 920 | `mocha` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 919 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 914 | `mocha test` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 900 | `node_modules/.bin/mocha` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 898 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [zalando/tailor](https://github.com/zalando/tailor) | 887 | `mocha --harmony tests/**` | 
| [micromatch/micromatch](https://github.com/micromatch/micromatch) | 882 | `mocha` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 881 | `npm run lint && mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 876 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 874 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 872 | `istanbul cover _mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 870 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 866 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 866 | `mocha --reporter spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [leizongmin/node-segment](https://github.com/leizongmin/node-segment) | 923 | `mocha -t 5000` | 
| [alexa-js/alexa-app](https://github.com/alexa-js/alexa-app) | 921 | `./node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [indutny/node-ip](https://github.com/indutny/node-ip) | 919 | `jscs lib/*.js test/*.js && jshint lib/*.js && mocha --reporter spec test/*-test.js` | 
| [axemclion/browser-perf](https://github.com/axemclion/browser-perf) | 919 | `node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 914 | `mocha test` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 913 | `mocha` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 911 | `mocha -r should --exit test/*.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 908 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 908 | `npm run lint && npm run mocha:no-functional` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 900 | `node_modules/.bin/mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 900 | `npm run build && istanbul test _mocha test/test.js` | 
| [hunterloftis/newton](https://github.com/hunterloftis/newton) | 915 | `mocha spec/*.spec.js` | 
| [yanhaijing/template.js](https://github.com/yanhaijing/template.js) | 914 | `mocha test` | 
| [andrewrk/node-s3-client](https://github.com/andrewrk/node-s3-client) | 913 | `mocha` | 
| [mthenw/frontail](https://github.com/mthenw/frontail) | 911 | `mocha -r should --exit test/*.js` | 
| [codemix/babel-plugin-typecheck](https://github.com/codemix/babel-plugin-typecheck) | 908 | `mocha ./test/index.js` | 
| [EragonJ/Kaku](https://github.com/EragonJ/Kaku) | 908 | `./node_modules/.bin/mocha -u tdd -t 5000 --reporter dot --compilers js:babel-core/register --require ./tests/unit/setup.js 'tests/unit/*.test.js'` | 
| [MaxCDN/bootstrapcdn](https://github.com/MaxCDN/bootstrapcdn) | 908 | `npm run lint && npm run mocha:no-functional` | 
| [ryanflorence/ember-tools](https://github.com/ryanflorence/ember-tools) | 902 | `node_modules/.bin/mocha --require should --reporter dot --ui bdd --growl $(find test -name "*.spec.js")` | 
| [brianc/node-sql](https://github.com/brianc/node-sql) | 900 | `node_modules/.bin/mocha` | 
| [proj4js/proj4js](https://github.com/proj4js/proj4js) | 900 | `npm run build && istanbul test _mocha test/test.js` | 
| [lodash/lodash-webpack-plugin](https://github.com/lodash/lodash-webpack-plugin) | 898 | `mocha --check-leaks --slow 1e3 -r @babel/register` | 
| [lightning-viz/lightning](https://github.com/lightning-viz/lightning) | 897 | `mocha --timeout 200000` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 859 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 858 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 857 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 855 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 855 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 853 | `mocha` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 850 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 848 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [ritzyed/ritzy](https://github.com/ritzyed/ritzy) | 844 | `mocha --compilers js:compiler.js src/**/*-test.js` | 
| [gulpjs/gulp-util](https://github.com/gulpjs/gulp-util) | 842 | `jshint *.js lib/*.js test/*.js && mocha` | 
| [ztoben/assets-webpack-plugin](https://github.com/ztoben/assets-webpack-plugin) | 842 | `mocha test` | 
| [jonathantneal/postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) | 839 | `echo 'Running tests...'; ./node_modules/.bin/mocha && npm run lint` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 838 | `mocha` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 837 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 834 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [btford/ngmin](https://github.com/btford/ngmin) | 881 | `./node_modules/.bin/mocha --globals angular,require` | 
| [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) | 881 | `npm run lint && mocha` | 
| [lmatteis/peer-tweet](https://github.com/lmatteis/peer-tweet) | 880 | `cross-env NODE_ENV=test mocha --compilers js:babel-core/register --recursive --require ./test/setup.js test/**/*.spec.js` | 
| [auth0-community/socketio-jwt](https://github.com/auth0-community/socketio-jwt) | 878 | `mocha` | 
| [tshelburne/redux-batched-actions](https://github.com/tshelburne/redux-batched-actions) | 876 | `node_modules/.bin/mocha --compilers js:babel-core/register` | 
| [jaredhanson/locomotive](https://github.com/jaredhanson/locomotive) | 875 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js test/helpers/**/*.test.js` | 
| [TailorDev/monod](https://github.com/TailorDev/monod) | 874 | `NODE_ENV=test MONOD_DATA_DIR=app/__tests__/fixtures/ mocha` | 
| [SamyPesse/betty](https://github.com/SamyPesse/betty) | 873 | `mocha --reporter list` | 
| [dareid/chakram](https://github.com/dareid/chakram) | 872 | `istanbul cover _mocha` | 
| [saintedlama/passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | 870 | `cross-env NODE_ENV=test nyc --reporter=text-summary mocha --recursive --throw-deprecation --require babel-polyfill --require babel-core/register` | 
| [volumio/Volumio2](https://github.com/volumio/Volumio2) | 867 | `npm install fs-extra && npm install --only=dev && ./node_modules/.bin/mocha --reporter spec` | 
| [alexkuz/react-json-tree](https://github.com/alexkuz/react-json-tree) | 866 | `npm run lint && NODE_ENV=test mocha --compilers js:babel-core/register --recursive` | 
| [phodal/skilltree](https://github.com/phodal/skilltree) | 866 | `mocha --reporter spec` | 
| [mikemintz/react-rethinkdb](https://github.com/mikemintz/react-rethinkdb) | 865 | `eslint test && mocha --compilers js:babel/register` | 
| [yeoman/generator](https://github.com/yeoman/generator) | 863 | `mocha --reporter spec --bail --check-leaks test/` | 
| [developit/decko](https://github.com/developit/decko) | 861 | `npm run test:ts && eslint {src,tests}/**.js && mocha --compilers js:babel/register tests/**/*.js` | 
| [lelylan/simple-oauth2](https://github.com/lelylan/simple-oauth2) | 860 | `nyc mocha` | 
| [sequelize/umzug](https://github.com/sequelize/umzug) | 860 | `mocha -r babel-register --check-leaks test/index.js` | 
| [oortcloud/meteorite](https://github.com/oortcloud/meteorite) | 860 | `mocha spec/unit spec/acceptance -t 240000 -R spec` | 
| [edwardhotchkiss/mongoose-paginate](https://github.com/edwardhotchkiss/mongoose-paginate) | 859 | `./node_modules/.bin/mocha tests/*.js -R spec --ui bdd --timeout 5000` | 
| [fossasia/yaydoc](https://github.com/fossasia/yaydoc) | 858 | `./node_modules/.bin/mocha tests --timeout 1500000` | 
| [matteodem/meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) | 857 | `meteor test --port 4400 --driver-package=practicalmeteor:mocha` | 
| [zzarcon/microm](https://github.com/zzarcon/microm) | 857 | `mocha-phantomjs -s localToRemoteUrlAccessEnabled=true -s webSecurityEnabled=false --reporter spec test/runner.html` | 
| [sliptree/bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield) | 857 | `mocha --ui bdd --recursive --reporter spec --require must` | 
| [electron-userland/electron-json-storage](https://github.com/electron-userland/electron-json-storage) | 855 | `npm run lint && electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec` | 
| [salomvary/soundcleod](https://github.com/salomvary/soundcleod) | 855 | `mocha` | 
| [johnpapa/generator-hottowel](https://github.com/johnpapa/generator-hottowel) | 854 | `mocha` | 
| [assetgraph/assetgraph](https://github.com/assetgraph/assetgraph) | 853 | `mocha` | 
| [njpatel/grpcc](https://github.com/njpatel/grpcc) | 850 | `mocha` | 
| [neumino/rethinkdbdash](https://github.com/neumino/rethinkdbdash) | 850 | `mocha --check-leaks -t 20000` | 
| [schrodinger/fixed-data-table-2](https://github.com/schrodinger/fixed-data-table-2) | 848 | `mocha-webpack --webpack-config webpack.config-test.js "src/**/*-test.js" --require build_helpers/test-globals.js` | 
| [Rich-Harris/shimport](https://github.com/Rich-Harris/shimport) | 846 | `mocha --opts mocha.opts` | 
| [ruanyf/es-checker](https://github.com/ruanyf/es-checker) | 846 | `mocha` | 
| [troybetz/react-youtube](https://github.com/troybetz/react-youtube) | 838 | `mocha` | 
| [crowi/crowi](https://github.com/crowi/crowi) | 837 | `mocha -r test/bootstrap.js --globals chai --reporter dot test/**/*.test.js --timeout 10000` | 
| [ebradyjobory/finance.js](https://github.com/ebradyjobory/finance.js) | 837 | `mocha` | 
| [arithmetric/aws-lambda-ses-forwarder](https://github.com/arithmetric/aws-lambda-ses-forwarder) | 834 | `istanbul cover _mocha -- --check-leaks --timeout 3000` | 
| [BretFisher/node-docker-good-defaults](https://github.com/BretFisher/node-docker-good-defaults) | 833 | `cross-env NODE_ENV=test PORT=8081 mocha --timeout 10000 --exit --inspect=0.0.0.0:9230` | 
| [RisingStack/graphql-server](https://github.com/RisingStack/graphql-server) | 832 | `NODE_ENV=test mocha --compilers js:babel/register --require co-mocha $(find src -name "*.spec.js")` | 
| [abalone0204/Clairvoyance](https://github.com/abalone0204/Clairvoyance) | 832 | `cross-env NODE_ENV=test NODE_PATH=front-end/app mocha tests --recursive --compilers js:babel-register` | 
| [ember-fastboot/ember-cli-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) | 832 | `mocha && ember test` | 
| [taskrabbit/ReactNativeSampleApp](https://github.com/taskrabbit/ReactNativeSampleApp) | 831 | `npm run mocha-test test/integration` | 
| [hovancik/stretchly](https://github.com/hovancik/stretchly) | 830 | `mocha test` | 
| [bjornharrtell/jsts](https://github.com/bjornharrtell/jsts) | 830 | `NODE_PATH=src nyc mocha --timeout 10s -r esm --recursive test/auto/node test/manual` | 
| [fossasia/CommonsNet](https://github.com/fossasia/CommonsNet) | 827 | `_mocha` | 
| [themadcreator/seen](https://github.com/themadcreator/seen) | 827 | `cake build && mocha ./test/mocha/*.coffee` | 
| [cthackers/adm-zip](https://github.com/cthackers/adm-zip) | 827 | `mocha test/mocha.js test/crc/index.js` | 
| [start-react/sb-admin-react](https://github.com/start-react/sb-admin-react) | 826 | `mocha "src/**/*.test.js" --require test/setup.js --compilers js:babel-register` | 
| [fitzgen/wu.js](https://github.com/fitzgen/wu.js) | 823 | `npm run build && mocha --full-trace --no-colors --compilers js:babel/register` | 
| [dynamoosejs/dynamoose](https://github.com/dynamoosejs/dynamoose) | 822 | `mocha` | 
| [danielfsousa/express-rest-es2017-boilerplate](https://github.com/danielfsousa/express-rest-es2017-boilerplate) | 820 | `cross-env NODE_ENV=test nyc --reporter=html --reporter=text mocha --timeout 20000 --recursive src/api/tests` | 
| [edsu/anon](https://github.com/edsu/anon) | 819 | `mocha --colors --reporter spec test.js` | 
| [entwicklerstube/babel-plugin-root-import](https://github.com/entwicklerstube/babel-plugin-root-import) | 818 | `mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register` | 
| [mjackson/mach](https://github.com/mjackson/mach) | 817 | `jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'` | 
| [SabakiHQ/Sabaki](https://github.com/SabakiHQ/Sabaki) | 815 | `mocha` | 
| [petecoop/generator-express](https://github.com/petecoop/generator-express) | 813 | `mocha` | 
| [pyloque/fastscan](https://github.com/pyloque/fastscan) | 811 | `mocha index.test.js` | 
| [scality/cloudserver](https://github.com/scality/cloudserver) | 809 | `CI=true S3BACKEND=mem mocha --recursive tests/unit` | 
| [peter-murray/node-hue-api](https://github.com/peter-murray/node-hue-api) | 808 | `mocha test` | 
| [basicallydan/interfake](https://github.com/basicallydan/interfake) | 808 | `mocha tests/*.test.js --reporter spec` | 
| [rendro/vintageJS](https://github.com/rendro/vintageJS) | 808 | `mocha --require babel-register` | 
| [indutny/webpack-common-shake](https://github.com/indutny/webpack-common-shake) | 806 | `mocha --reporter=spec test/*-test.js && npm run lint` | 
| [nfriedly/express-rate-limit](https://github.com/nfriedly/express-rate-limit) | 804 | `eslint . && mocha` | 
| [flickr/yakbak](https://github.com/flickr/yakbak) | 803 | `mocha` | 
| [jaredhanson/passport-http-bearer](https://github.com/jaredhanson/passport-http-bearer) | 803 | `node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js` | 
| [davglass/license-checker](https://github.com/davglass/license-checker) | 799 | `jenkins-mocha ./tests/*.js` | 
| [ant-design/antd-init](https://github.com/ant-design/antd-init) | 798 | `mocha --no-timeouts` | 
| [floatdrop/gulp-plumber](https://github.com/floatdrop/gulp-plumber) | 798 | `xo && mocha -R spec` | 
| [bojand/mailgun-js](https://github.com/bojand/mailgun-js) | 797 | `npm run lint && npm run mocha` | 
| [ripple/ripple-lib](https://github.com/ripple/ripple-lib) | 796 | `nyc mocha` | 
| [mozilla/awsbox](https://github.com/mozilla/awsbox) | 793 | `mocha -R spec tests/` | 
| [jhusain/eslint-plugin-immutable](https://github.com/jhusain/eslint-plugin-immutable) | 792 | `mocha --recursive -s 15 test/` | 
| [fossasia/loklak_scraper_js](https://github.com/fossasia/loklak_scraper_js) | 792 | `mocha tests --timeout 10000` | 
| [natefaubion/matches.js](https://github.com/natefaubion/matches.js) | 791 | `mocha -u tdd` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 766 | `mocha 'test/**/*.tests.js'` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 762 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [vuex-orm/vuex-orm](https://github.com/vuex-orm/vuex-orm) | 754 | `cross-env mocha-webpack --webpack-config test/webpack.config.js --require test/bootstrap.js 'test/{feature,unit}/**/*.spec.js'` | 
| [bevacqua/contra](https://github.com/bevacqua/contra) | 751 | `mocha --reporter tap && jshint --reporter node_modules/jshint-tap/jshint-tap.js test/*.js` | 
| [nfroidure/gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) | 749 | `mocha tests/*.mocha.js` | 
| [adriancooney/voyeur.js](https://github.com/adriancooney/voyeur.js) | 748 | `mocha` | 
| [kyledrake/coinpunk](https://github.com/kyledrake/coinpunk) | 774 | `NODE_ENV=test istanbul test ./node_modules/.bin/_mocha -- --reporter list test/coinpunk/*` | 
| [mironov/react-redux-loading-bar](https://github.com/mironov/react-redux-loading-bar) | 774 | ``npm bin`/mocha --require babel-core/register --exit spec/` | 
| [mongoosastic/mongoosastic](https://github.com/mongoosastic/mongoosastic) | 773 | `npm run lint && istanbul cover _mocha --report lcovonly -- test/*-test.js` | 
| [klei/gulp-inject](https://github.com/klei/gulp-inject) | 773 | `mocha -R spec src/**/*_test.js` | 
| [erikras/redux-form-material-ui](https://github.com/erikras/redux-form-material-ui) | 771 | `mocha --compilers js:babel-register --recursive --recursive "src/**/__tests__/*" --require src/__tests__/setup.js` | 
| [TooBug/wemark](https://github.com/TooBug/wemark) | 770 | `npm run lint&&mocha tests/*.js` | 
| [susam/texme](https://github.com/susam/texme) | 770 | `standard && mocha` | 
| [omnidan/redux-ignore](https://github.com/omnidan/redux-ignore) | 769 | `NODE_ENV=test ./node_modules/.bin/mocha --compilers js:babel-core/register --recursive` | 
| [joshwcomeau/panther](https://github.com/joshwcomeau/panther) | 769 | `NODE_ENV=test mocha --compilers js:babel-core/register --require ./test/test-helper.js --recursive` | 
| [stasm/innerself](https://github.com/stasm/innerself) | 768 | `mocha --ui tdd --require ./test/__setup` | 
| [lance-gg/lance](https://github.com/lance-gg/lance) | 767 | `mocha ./test/serializer/ --compilers js:babel-core/register` | 
| [vvo/selenium-standalone](https://github.com/vvo/selenium-standalone) | 766 | `./bin/selenium-standalone install && mocha` | 
| [mwilliamson/mammoth.js](https://github.com/mwilliamson/mammoth.js) | 766 | `mocha 'test/**/*.tests.js'` | 
| [erikolson186/zangodb](https://github.com/erikolson186/zangodb) | 764 | `mocha --reporter spec build/test/index.js` | 
| [jackfranklin/gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) | 762 | `npm run lint && NODE_PATH=test/global_modules mocha` | 
| [MaxArt2501/share-this](https://github.com/MaxArt2501/share-this) | 738 | `nyc --require babel-core/register mocha test/*.js test/sharers/*.js` | 
| [ali-sdk/ali-oss](https://github.com/ali-sdk/ali-oss) | 738 | `mocha -t 60000 -r thunk-mocha -r should test/node/*.test.js` | 
| [inikulin/publish-please](https://github.com/inikulin/publish-please) | 737 | `npm run prettier-format && npm run lint && npm run build && npm run mocha-with-coverage && npm run check-coverage` | 
| [jonschlinkert/markdown-toc](https://github.com/jonschlinkert/markdown-toc) | 737 | `mocha` | 
| [3rd-Eden/useragent](https://github.com/3rd-Eden/useragent) | 737 | `mocha $(find test -name '*.test.js')` | 
| [fynyky/reactor.js](https://github.com/fynyky/reactor.js) | 737 | `mocha` | 
| [crypto-utils/keygrip](https://github.com/crypto-utils/keygrip) | 735 | `mocha --reporter spec test/` | 
| [aslansky/css-sprite](https://github.com/aslansky/css-sprite) | 735 | `mocha --reporter spec` | 
| [Ebookcoin/ebookcoin](https://github.com/Ebookcoin/ebookcoin) | 731 | `mocha` | 
| [mondora/asteroid](https://github.com/mondora/asteroid) | 728 | `env NODE_ENV=test env NODE_PATH=src _mocha --compilers js:babel-core/register --recursive test/unit` | 
| [camsong/fetch-jsonp](https://github.com/camsong/fetch-jsonp) | 727 | `mocha --compilers js:babel/register --recursive --ui bdd --reporter spec` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 723 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 718 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 723 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 718 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 716 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 714 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [kiranz/just-api](https://github.com/kiranz/just-api) | 709 | `npm run clean_testlogs  && ./node_modules/.bin/mocha --timeout 10000 test/cli/*.spec.js` | 
| [gf3/sandbox](https://github.com/gf3/sandbox) | 707 | `mocha` | 
| [gyzerok/adrenaline](https://github.com/gyzerok/adrenaline) | 726 | `mocha --compilers js:babel-register $(find ./src -name '*.spec.js')` | 
| [LukeLin/js-stl](https://github.com/LukeLin/js-stl) | 724 | `mocha ./test/index.js` | 
| [twolfson/spritesmith](https://github.com/twolfson/spritesmith) | 723 | `npm run precheck && mocha src-test/ --timeout 60000 --reporter dot && npm run lint` | 
| [speedskater/babel-plugin-rewire](https://github.com/speedskater/babel-plugin-rewire) | 723 | `./node_modules/.bin/mocha && ./node_modules/.bin/mocha usage-tests` | 
| [mozilla/multi-account-containers](https://github.com/mozilla/multi-account-containers) | 718 | `npm run lint && mocha ./test/setup.js test/**/*.test.js` | 
| [jneen/parsimmon](https://github.com/jneen/parsimmon) | 717 | `nyc --reporter=lcov --reporter=text-summary npm run test:mocha` | 
| [sebhildebrandt/systeminformation](https://github.com/sebhildebrandt/systeminformation) | 716 | `nyc mocha --require ts-node/register --require source-map-support/register  ./test/**/*.test.ts` | 
| [skyvow/m-mall-admin](https://github.com/skyvow/m-mall-admin) | 714 | `./node_modules/.bin/mocha -t 10000 --compilers js:babel-core/register --recursive --reporter mochawesome` | 
| [rakeshpai/pi-gpio](https://github.com/rakeshpai/pi-gpio) | 702 | `mocha --reporter spec` | 
| [mariocasciaro/object-path](https://github.com/mariocasciaro/object-path) | 701 | `istanbul cover ./node_modules/mocha/bin/_mocha test.js --report html -- -R spec` | 
| [js-cli/js-liftoff](https://github.com/js-cli/js-liftoff) | 701 | `mocha -t 5000 -b -R spec test/index` | 
| [villadora/express-http-proxy](https://github.com/villadora/express-http-proxy) | 699 | `npm -s run mocha && npm run -s lint` | 
| [prerender/prerender-node](https://github.com/prerender/prerender-node) | 698 | `./node_modules/.bin/mocha` | 
| [mirkokiefer/aws-lib](https://github.com/mirkokiefer/aws-lib) | 695 | `./node_modules/.bin/mocha -t 60000` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 693 | `_mocha -u bdd --colors test/` | 
| [Savjee/SavjeeCoin](https://github.com/Savjee/SavjeeCoin) | 690 | `mocha tests/*.test.js` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 689 | `npm run lint && mocha test` | 
| [conradoqg/naivecoin](https://github.com/conradoqg/naivecoin) | 693 | `_mocha -u bdd --colors test/` | 
| [jonkemp/gulp-useref](https://github.com/jonkemp/gulp-useref) | 693 | `mocha` | 
| [Savjee/SavjeeCoin](https://github.com/Savjee/SavjeeCoin) | 690 | `mocha tests/*.test.js` | 
| [GianlucaGuarini/allora](https://github.com/GianlucaGuarini/allora) | 689 | `npm run lint && mocha test` | 
| [apollographql/eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) | 687 | `tav --ci && mocha test/index.js` | 
| [afc163/fanyi](https://github.com/afc163/fanyi) | 687 | `npm run lint && mocha tests/index.js --timeout 0` | 
| [inProgress-team/react-native-meteor](https://github.com/inProgress-team/react-native-meteor) | 684 | `mocha --compilers js:babel-core/register --require test/setup --recursive` | 
| [azazdeaz/react-gsap-enhancer](https://github.com/azazdeaz/react-gsap-enhancer) | 684 | `mocha --compilers js:babel-register` | 
| [inadarei/nodebootstrap](https://github.com/inadarei/nodebootstrap) | 683 | `mocha --bail test/` | 
| [aaronshaf/react-toggle](https://github.com/aaronshaf/react-toggle) | 660 | `nyc mocha --require babel-register --require spec/setup.js spec/**/*.spec.js` | 
| [yeoman/generator-backbone](https://github.com/yeoman/generator-backbone) | 658 | `mocha --reporter spec` | 
| [LouisBarranqueiro/reapop](https://github.com/LouisBarranqueiro/reapop) | 658 | `babel-node ./node_modules/karma/bin/karma start ./build/karma.conf.js --reporters mocha` | 
| [pburtchaell/react-notification](https://github.com/pburtchaell/react-notification) | 657 | `node_modules/.bin/mocha --compilers js:babel-core/register --reporter spec --recursive --timeout 5000 test/setup.js test/**/*.js` | 
| [douglasduteil/isparta](https://github.com/douglasduteil/isparta) | 657 | `mocha` | 
| [racker/dreadnot](https://github.com/racker/dreadnot) | 657 | `mocha` | 
| [jbrooksuk/node-summary](https://github.com/jbrooksuk/node-summary) | 656 | `mocha --compilers js:babel-core/register --require should --reporter spec` | 
| [anorudes/redux-easy-boilerplate](https://github.com/anorudes/redux-easy-boilerplate) | 654 | `NODE_PATH=./app mocha --require ./bin/test.js 'app/**/*spec.js'` | 
| [docpress/docpress](https://github.com/docpress/docpress) | 654 | `nyc mocha` | 
| [iron-meteor/iron-cli](https://github.com/iron-meteor/iron-cli) | 650 | `./node_modules/.bin/mocha test/integration` | 
| [omnidan/node-emoji](https://github.com/omnidan/node-emoji) | 649 | `./node_modules/.bin/mocha --require should --bail --reporter spec test/*` | 
| [wprl/baucis](https://github.com/wprl/baucis) | 649 | `./node_modules/.bin/mocha --bail` | 
| [postcss/gulp-postcss](https://github.com/postcss/gulp-postcss) | 648 | `nyc mocha test.js` | 
| [CharlesStover/reactn](https://github.com/CharlesStover/reactn) | 648 | `mocha -r chai/register-expect -r @babel/register -r ts-node/register "tests/**/*.spec.ts?(x)"` | 