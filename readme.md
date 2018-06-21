


## 关于NodeJS的一切

- [Packages](#packages)
	- [Command-line apps-命令行应用](#command-line-apps)
	- [Functional programming-函数式编程](#functional-programming)
	- [HTTP-HTTP](#http)
	- [Debugging / Profiling](#debugging--profiling)
	- [Logging-日志](#logging)
	- [Command-line utilities-命令行工具](#command-line-utilities)
	- [Build tools-构建工具](#build-tools)
	- [Templating-模板](#templating)
	- [Web frameworks-web框架](#web-frameworks)
	- [Documentation-文档](#documentation)
	- [Filesystem-文件系统](#filesystem)
	- [Control flow-控制流](#control-flow)
	- [Streams-流](#streams)
	- [Real-time-实时](#real-time)
	- [Image-图片](#image)
	- [Text-文本](#text)
	- [Number-数字](#number)
	- [Math-数学](#math)
	- [Date-日期](#date)
	- [URL](#url)
	- [Data validation-数据校验](#data-validation)
	- [Parsing-解析](#parsing)
	- [Humanize-人性化](#humanize)
	- [Compression-压缩](#compression)
	- [Database-数据库](#database)
	- [Testing-测试](#testing)
	- [Security-安全](#security)
	- [Benchmarking-基准测试](#benchmarking)
	- [Minifiers-最小化](#minifiers)
	- [Authentication-认证](#authentication)
	- [Authorization-权限](#authorization)
	- [Email-邮件](#email)
	- [Job queues-任务队列](#job-queues)
	- [Node.js management-管理](#nodejs-management)
	- [Process management-进程管理](#process-management)
	- [Automation-自动化](#automation)
	- [AST-语法树](#ast)
	- [Static site generators-静态网站生成](#static-site-generators)
	- [Content management systems-CMS](#content-management-systems)
	- [Forum-论坛](#forum)
	- [Blogging-播客](#blogging)
	- [Weird-好玩的](#weird)
	- [Serialization-序列化](#serialization)
	- [Miscellaneous-杂项](#miscellaneous)
- [Resources-资源](#resources)
	- [Tutorials-教程](#tutorials)
	- [Discovery-发现](#discovery)
	- [Articles-文章](#articles)
	- [Newsletters-新闻](#newsletters)
	- [Book-图书](#books)
	- [Blogs-播客](#blogs)
	- [Courses-课程](#courses)
	- [Cheatsheets-快捷表](#cheatsheets)
	- [Tools-工具](#tools)
	- [Community-社区](#community)
	- [Miscellaneous-杂项](#miscellaneous)


## Packages


### Command-line apps-命令行应用

- [np](https://github.com/sindresorhus/np) - Better `npm publish`.
- [trash](https://github.com/sindresorhus/trash) - Safer alternative to `rm`.
- [speed-test](https://github.com/sindresorhus/speed-test) - Test your internet connection speed and ping.
- [emoj](https://github.com/sindresorhus/emoj) - Find relevant emoji from text on the command-line.
- [pageres](https://github.com/sindresorhus/pageres) - Capture website screenshots.
- [public-ip](https://github.com/sindresorhus/public-ip) - Get your public IP address.
- [XO](https://github.com/xojs/xo) - Enforce strict code style using the JavaScript happiness style.
- [Standard](https://github.com/feross/standard) - JavaScript Standard Style — One style to rule them all.
- [ESLint](http://eslint.org) - The pluggable linting utility for JavaScript.
- [David](https://github.com/alanshaw/david) - Tells you when your package npm dependencies are out of date.
- [http-server](https://github.com/indexzero/http-server) - Simple, zero-config command-line HTTP server.
- [Live Server](https://github.com/tapio/live-server) - Development HTTP-server with livereload capability.
- [fkill](https://github.com/sindresorhus/fkill-cli) - Fabulously kill processes. Cross-platform.
- [alex](https://github.com/wooorm/alex) - Catch insensitive, inconsiderate writing.
- [trymodule](https://github.com/VictorBjelkholm/trymodule) - Try out npm packages in the terminal.
- [jscpd](https://github.com/kucherenko/jscpd) - Copy/paste detector for source code.
- [atmo](https://github.com/Raathigesh/Atmo) - Server-side API mocking.
- [yapi](https://github.com/YMFE/yapi) - Server-side API mocking.
- [auto-install](https://github.com/siddharthkp/auto-install) - Auto installs dependencies as you code.
- [cost-of-modules](https://github.com/siddharthkp/cost-of-modules) - Find out which dependencies are slowing you down.
- [localtunnel](https://github.com/localtunnel/localtunnel) - Expose your localhost to the world.
- [gtop](https://github.com/aksakalli/gtop) - System monitoring dashboard for the terminal.


### Functional programming-函数式编程

- [lodash](https://lodash.com) - Utility library delivering consistency, customization, performance, & extras. A better and faster Underscore.js.
- [immutable](https://github.com/facebook/immutable-js) - Immutable data collections.
- [Ramda](https://github.com/ramda/ramda) - Utility library with a focus on flexible functional composition enabled by automatic currying and reversed argument order. Avoids mutating data.
- [Folktale](http://folktale.origamitower.com) - Suite of libraries for generic functional programming in JavaScript that allows you to write elegant, modular applications with fewer bugs, and more reuse.
- [Bacon.js](http://baconjs.github.io) - Functional reactive programming.
- [RxJS](http://reactivex.io) - Functional reactive library for transforming, composing, and querying various kinds of data.
- [Lazy.js](https://github.com/dtao/lazy.js) - Utility library similar to lodash/Underscore but with lazy evaluation, which can translate to superior performance in many cases.


### HTTP-HTTP

- [got](https://github.com/sindresorhus/got) - Nicer interface to the built-in `http` module.
- [axios](https://github.com/mzabriskie/axios) - Promise based HTTP client (works in the browser too).
- [request](https://github.com/request/request) - Simplified HTTP request client.
- [download](https://github.com/kevva/download) - Download and extract files effortlessly.
- [http-proxy](https://github.com/nodejitsu/node-http-proxy) - HTTP proxy.
- [superagent](https://github.com/visionmedia/superagent) - HTTP request library.


### Debugging / Profiling

- [ironNode](https://github.com/s-a/iron-node) - Node.js debugger supporting ES2015 out of the box.
- [node-inspector](https://github.com/node-inspector/node-inspector) - Debugger based on Blink Developer Tools.
- [debug](https://github.com/visionmedia/debug) - Tiny debugging utility.
- [leakage](https://github.com/andywer/leakage) - Write memory leak tests.


### Logging-日志

- [pino](https://github.com/pinojs/pino) - Extremely fast logger inspired by Bunyan.
- [winston](https://github.com/winstonjs/winston) - Multi-transport async logging library.
- [signale](https://github.com/klauscfhq/signale) - Hackable console logger with beautiful output.


### Command-line utilities-命令行工具

- [chalk](https://github.com/chalk/chalk) - Terminal string styling done right.
- [meow](https://github.com/sindresorhus/meow) - CLI app helper.
- [yargs](https://github.com/yargs/yargs) - Command-line parser that automatically generates an elegant user-interface.
- [ora](https://github.com/sindresorhus/ora) - Elegant terminal spinner.
- [Ink](https://github.com/vadimdemedes/ink) - React for interactive command-line apps.
- [vorpal](https://github.com/dthree/vorpal) - Interactive CLI apps.
- [blessed](https://github.com/chjj/blessed) - Curses-like library.
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - Interactive command-line prompt.
- [cli-table](https://github.com/Automattic/cli-table) - Pretty unicode tables.
- [update-notifier](https://github.com/yeoman/update-notifier) - Update notifications for your CLI app.
- [progress](https://github.com/tj/node-progress) - Flexible ascii progress bar.
- [omelette](https://github.com/f/omelette) - Shell autocompletion helper.
- [cross-env](https://github.com/kentcdodds/cross-env) - Set environment variables cross-platform.
- [shelljs](https://github.com/shelljs/shelljs) - Portable Unix shell commands.
- [Bit](https://github.com/teambit/bit) - Create, maintain, find and use small modules and components across repositories.
- [oclif](https://github.com/oclif/oclif) - CLI framework complete with parser, automatic documentation, testing, and plugins.


### Build tools-构建工具

- [parcel](https://github.com/parcel-bundler/parcel) - Blazing fast, zero config web app bundler.
- [webpack](https://github.com/webpack/webpack) - Packs modules and assets for the browser.
- [rollup](https://github.com/rollup/rollup) - Next-generation ES2015 module bundler.
- [gulp](http://gulpjs.com) - Streaming and fast build system that favors code over config.
- [Broccoli](https://github.com/broccolijs/broccoli) - Fast, reliable asset pipeline, supporting constant-time rebuilds and compact build definitions.
- [Brunch](https://github.com/brunch/brunch) - Front-end web app build tool with simple declarative config, fast incremental compilation, and an opinionated workflow.
- [FuseBox](https://github.com/fuse-box/fuse-box) - Fast build system that combines the power of webpack, JSPM and SystemJS, with first-class TypeScript support.
- [pkg](https://github.com/zeit/pkg) - Package your Node.js project into an executable.





### Templating-模板

- [marko](https://github.com/marko-js/marko) - HTML-based templating engine that compiles templates to CommonJS modules and supports streaming, async rendering and custom tags.
- [nunjucks](https://github.com/mozilla/nunjucks) - Templating engine with inheritance, asynchronous control, and more (jinja2 inspired).
- [handlebars.js](https://github.com/wycats/handlebars.js) - Superset of Mustache templates which adds powerful features like helpers and more advanced blocks.
- [EJS](https://github.com/mde/ejs) - Simple unopinionated templating language.
- [Pug](https://github.com/pugjs/pug) - High-performance template engine heavily influenced by Haml.


### Web frameworks-web框架

- [Hapi](http://hapijs.com) - Framework for building applications and services.
- [Koa](http://koajs.com) - Framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs.
- [Express](http://expressjs.com) - Web application framework, providing a robust set of features for building single and multi-page, and hybrid web applications.
- [Feathers](http://feathersjs.com) - Microservice framework built in the spirit of Express.
- [LoopBack](http://loopback.io) - Powerful framework for creating REST APIs and easily connecting to backend data sources.
- [Meteor](https://www.meteor.com) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework. *(You might like [awesome-meteor](https://github.com/Urigo/awesome-meteor))*
- [Restify](http://restify.com) - Enables you to build correct REST web services.
- [ThinkJS](https://github.com/thinkjs/thinkjs) - Framework with ES2015+ support, WebSockets, REST API.
- [MERN](http://mern.io) - Easily build production-ready universal apps with MongoDB, Express, React, and webpack.
- [Next.js](https://github.com/zeit/next.js) - Minimalistic framework for server-rendered universal JavaScript web apps.
- [Nuxt.js](https://github.com/nuxt/nuxt.js) - Minimalistic framework for server-rendered Vue.js apps.
- [seneca](https://github.com/senecajs/seneca) - Toolkit for writing microservices.
- [AdonisJs](http://adonisjs.com) - A true MVC framework for Node.js built on solid foundations of Dependency Injection and IoC container.
- [Micro](https://github.com/zeit/micro) - Minimalistic microservice framework with an async approach.
- [Moleculer](https://moleculer.services) - Fast & powerful microservices framework.
- [Fastify](https://github.com/fastify/fastify) - Fast and low overhead web framework.
- [Nest](https://github.com/nestjs/nest) - Angular-inspired framework for building efficient and scalable server-side apps.


### Documentation-文档

- [documentation.js](https://github.com/documentationjs/documentation) - API documentation generator with support for ES2015+ and flow annotation.
- [ESDoc](https://github.com/esdoc/esdoc) - Documentation generator targeting ES2015, attaching test code and measuring documentation coverage.
- [Docco](http://jashkenas.github.io/docco/) - Documentation generator which produces an HTML document that displays your comments intermingled with your code.
- [JSDoc](http://usejsdoc.org) - API documentation generator similar to JavaDoc or PHPDoc.


### Filesystem-文件系统

- [del](https://github.com/sindresorhus/del) - Delete files/folders using globs.
- [globby](https://github.com/sindresorhus/globby) - Glob files with support for multiple patterns.
- [rimraf](https://github.com/isaacs/rimraf) - Recursively delete files like `rm -rf`.
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - Drop-in replacement for the `fs` module with various improvements.
- [chokidar](https://github.com/paulmillr/chokidar) - Filesystem watcher which stabilizes events from `fs.watch` and `fs.watchFile` as well as using native `fsevents` on macOS.
- [fs-jetpack](https://github.com/szwacz/fs-jetpack) - Completely redesigned file system API for convenience in everyday use.
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - Extra methods for the `fs` module.


### Control flow-控制流

- Promises
	- [Bluebird](https://github.com/petkaantonov/bluebird) - Promise library with focus on innovative features and performance.
	- [pify](https://github.com/sindresorhus/pify) - Promisify a callback-style function.
	- [More…](https://github.com/sindresorhus/promise-fun)
- Observables
	- [zen-observable](https://github.com/zenparsing/zen-observable) - Implementation of Observables.
	- [RxJS](https://github.com/ReactiveX/RxJS) - Reactive programming.
	- [More…](https://github.com/sindresorhus/awesome-observables)
- Streams
	- [Highland.js](https://github.com/caolan/highland) - Manages synchronous and asynchronous code easily, using nothing more than standard JavaScript and Node-like Streams.
- Callbacks
	- [async](https://github.com/caolan/async) - Provides straight-forward, powerful functions for working with asynchronicity.
- Channels
	- [js-csp](https://github.com/ubolonton/js-csp) - Communicating sequential processes for JavaScript (like Clojurescript core.async, or Go).


### Streams-数据流

- [through2](https://github.com/rvagg/through2) - Tiny wrapper around streams2 Transform to avoid explicit subclassing noise.
- [byline](https://github.com/jahewson/node-byline) - Super-simple line-by-line Stream reader.
- [multistream](https://github.com/feross/multistream) - Combine multiple streams into a single stream.
- [readable-stream](https://github.com/nodejs/readable-stream) - Mirror of Streams2 and Streams3 implementations in core.


### Real-time-实时

- [µWebSockets](https://github.com/uWebSockets/uWebSockets) - Highly scalable WebSocket server & client library.
- [Socket.io](https://github.com/socketio/socket.io) - Enables real-time bidirectional event-based communication.
- [Faye](https://github.com/faye/faye) - Real-time client-server message bus, based on Bayeux protocol.
- [SocketCluster](https://github.com/SocketCluster/socketcluster) - Scalable HTTP + WebSocket engine which can run on multiple CPU cores.
- [Primus](https://github.com/primus/primus) - An abstraction layer for real-time frameworks to prevent module lock-in.
- [MQTT.js](https://github.com/mqttjs/MQTT.js) - Client for MQTT - Pub-sub based messaging protocol for use on top of TCP/IP.


### Image-图片

- [sharp](https://github.com/lovell/sharp) - The fastest module for resizing JPEG, PNG, WebP and TIFF images.
- [gm](https://github.com/aheckmann/gm) - GraphicsMagick and ImageMagick wrapper.
- [lwip](https://github.com/EyalAr/lwip) - Lightweight image processor which does not require ImageMagick.
- [pica](https://github.com/nodeca/pica) - High quality & fast resize (lanczos3) in pure JS. Alternative to canvas drawImage(), when no pixelation allowed.
- [jimp](https://github.com/oliver-moran/jimp) - Image processing in pure JavaScript.


### Text-文本

- [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - Convert character encodings.
- [escape-string-regexp](https://github.com/sindresorhus/escape-string-regexp) - Escape RegExp special characters.
- [he](https://github.com/mathiasbynens/he) - HTML entity encoder/decoder.
- [i18n-node](https://github.com/mashpie/i18n-node) - Simple translation module with dynamic JSON storage.
- [i18next](https://github.com/i18next/i18next) - Internationalization framework.


### Number-数字

- [random-int](https://github.com/sindresorhus/random-int) - Generate a random integer.
- [random-float](https://github.com/sindresorhus/random-float) - Generate a random float.
- [unique-random](https://github.com/sindresorhus/unique-random) - Generate random numbers that are consecutively unique.
- [round-to](https://github.com/sindresorhus/round-to) - Round a number to a specific number of decimal places: `1.234` → `1.2`.


### Math-数学

- [ndarray](https://github.com/scijs/ndarray) - Multidimensional arrays.
- [mathjs](https://github.com/josdejong/mathjs) - An extensive math library.


### Date-日期

- [Luxon](https://github.com/moment/luxon) - Library for working with dates and times.
- [date-fns](https://github.com/date-fns/date-fns) - Modern date utility.
- [Moment.js](http://momentjs.com) - Parse, validate, manipulate, and display dates.


### URL-URL

- [normalize-url](https://github.com/sindresorhus/normalize-url) - Normalize a URL.
- [humanize-url](https://github.com/sindresorhus/humanize-url) - Humanize a URL: http://sindresorhus.com → sindresorhus.com.
- [speakingurl](https://github.com/pid/speakingurl) - Generate a slug from a string with transliteration.
- [linkify-it](https://github.com/markdown-it/linkify-it) - Link patterns detector with full unicode support.
- [url-pattern](https://github.com/snd/url-pattern) - Easier than regex string matching patterns for URLs and other strings.


### Data validation-数据验证

- [joi](https://github.com/hapijs/joi) - Object schema description language and validator for JavaScript objects.
- [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - JSON Schema validator that uses code generation to be extremely fast.
- [schema-inspector](https://github.com/Atinux/schema-inspector) - JSON API sanitization and validation.
- [ajv](https://github.com/epoberezkin/ajv) - The fastest JSON Schema validator. Supports v5 proposals.


### Parsing-解析

- [remark](https://github.com/wooorm/remark) - Markdown processor powered by plugins.
- [markdown-it](https://github.com/markdown-it/markdown-it) - Markdown parser with 100% CommonMark support, extensions and syntax plugins.
- [parse5](https://github.com/inikulin/parse5) - Fast full-featured spec compliant HTML parser.
- [URI.js](https://github.com/medialize/URI.js) - URL mutation.
- [PostCSS](https://github.com/postcss/postcss) - CSS parser / stringifier.
- [JSONStream](https://github.com/dominictarr/JSONStream) - Streaming JSON.parse and stringify.
- [csv-parser](https://github.com/mafintosh/csv-parser) - Streaming CSV parser that aims to be faster than everyone else.
- [PEG.js](https://github.com/pegjs/pegjs) - Simple parser generator that produces fast parsers with excellent error reporting.
- [x-ray](https://github.com/lapwinglabs/x-ray) - Web scraping utility.
- [nearley](https://github.com/Hardmath123/nearley) - Simple, fast, powerful parsing for JavaScript.
- [js-yaml](https://github.com/nodeca/js-yaml) - Very fast YAML parser.
- [xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - XML to JavaScript object converter.
- [Jison](https://github.com/zaach/jison) - Friendly JavaScript parser generator. It shares genes with Bison, Yacc and family.


### Humanize-人性化

- [pretty-bytes](https://github.com/sindresorhus/pretty-bytes) - Convert bytes to a human readable string: `1337` → `1.34 kB`.
- [pretty-ms](https://github.com/sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: `1337000000` → `15d 11h 23m 20s`.
- [ms](https://github.com/rauchg/ms.js) - Tiny millisecond conversion utility.
- [pretty-error](https://github.com/AriaMinaei/pretty-error) - Errors with less clutter.


### Compression-压缩

- [yazl](https://github.com/thejoshwolfe/yazl) - Zip.
- [yauzl](https://github.com/thejoshwolfe/yauzl) - Unzip.
- [Archiver](https://github.com/archiverjs/node-archiver) - Streaming interface for archive generation, supporting ZIP and TAR.
- [pako](https://github.com/nodeca/pako) - High speed zlib port to pure js (deflate, inflate, gzip).
- [tar-stream](https://github.com/mafintosh/tar-stream) - Streaming tar parser and generator. Also see [tar-fs](https://github.com/mafintosh/tar-fs).
- [decompress](https://github.com/kevva/decompress) - Decompression module with support for `tar`, `tar.gz` and `zip` files out of the box.




### Database-数据库

- Drivers-驱动
	- [PostgreSQL](https://github.com/brianc/node-postgres) - PostgreSQL client. Pure JavaScript and native libpq bindings.
	- [Redis](https://github.com/luin/ioredis) - Redis client.
	- [LevelUP](https://github.com/Level/levelup) - LevelDB.
	- [MySQL](https://github.com/mysqljs/mysql) - MySQL client.
	- [couchdb-nano](https://github.com/apache/couchdb-nano) - CouchDB client.
	- [Aerospike](https://github.com/aerospike/aerospike-client-nodejs) - Aerospike client.
	- [Couchbase](https://github.com/couchbase/couchnode) - Couchbase client.
	- [MongoDB](https://github.com/mongodb/node-mongodb-native) - MongoDB driver.
- ODM / ORM
	- [Sequelize](https://github.com/sequelize/sequelize) - Multi-dialect ORM. Supports PostgreSQL, SQLite, MySQL.
	- [Bookshelf](https://github.com/bookshelf/bookshelf) - ORM for PostgreSQL, MySQL and SQLite3 in the style of Backbone.js.
	- [Mongoose](https://github.com/Automattic/mongoose) - Elegant MongoDB object modeling.
	- [Waterline](https://github.com/balderdashy/waterline) - Datastore-agnostic tool that dramatically simplifies interaction with one or more databases.
	- [orm2](https://github.com/dresende/node-orm2) - ORM for PostgreSQL, MariaDB, MySQL, Amazon Redshift, SQLite, MongoDB.
	- [Objection.js](https://github.com/Vincit/objection.js) - Lightweight ORM built on the SQL query builder Knex.
	- [TypeORM](https://github.com/typeorm/typeorm) - ORM for PostgreSQL, MariaDB, MySQL, SQLite, and more.
- Query builder-查询构建
	- [Knex](https://github.com/tgriesser/knex) - Query builder for PostgreSQL, MySQL and SQLite3, designed to be flexible, portable, and fun to use.
- Other
	- [NeDB](https://github.com/louischatriot/nedb) - Embedded persistent database written in JavaScript.
	- [Lowdb](https://github.com/typicode/lowdb) - Small JavaScript database powered by Lodash.


### Testing-测试

- [AVA](https://ava.li) - Futuristic test runner.
- [Mocha](http://mochajs.org) - Feature-rich test framework making asynchronous testing simple and fun.
- [nyc](https://github.com/bcoe/nyc) - Code coverage tool built on istanbul that works with subprocesses.
- [tape](https://github.com/substack/tape) - TAP-producing test harness.
- [power-assert](https://github.com/power-assert-js/power-assert) - Provides descriptive assertion messages through the standard assert interface.
- [trevor](https://github.com/vdemedes/trevor) - Run tests against multiple versions of Node.js without switching versions manually or pushing to Travis CI.
- [loadtest](https://github.com/alexfernandez/loadtest) - Run load tests for your web application, with an API for automation.
- [Sinon.JS](https://github.com/sinonjs/sinon) - Test spies, stubs and mocks.
- [Nock](https://github.com/pgte/nock) - HTTP mocking and expectations.
- [intern](https://github.com/theintern/intern) - Code testing stack.
- [toxy](https://github.com/h2non/toxy) - Hackable HTTP proxy to simulate failure scenarios and network conditions.
- [Nightwatch](https://github.com/nightwatchjs/nightwatch) - Automated UI testing framework based on Selenium WebDriver.
- [WebdriverIO](https://github.com/webdriverio/webdriverio) - Automated testing based on the WebDriver protocol.
- [Jest](https://github.com/facebook/jest) - Painless JavaScript testing.
- [TestCafe](https://github.com/DevExpress/testcafe) - Automated browser testing.


### Security-安全

- [snyk](https://github.com/Snyk/snyk) - CLI and build-time tool to find & fix vulnerable npm dependencies.
- [upash](https://github.com/simonepri/upash) - Unified API for all password hashing algorithms.


### Benchmarking-基准测试

- [Benchmark.js](https://github.com/bestiejs/benchmark.js) - Benchmarking library that supports high-resolution timers and returns statistically significant results.
- [matcha](https://github.com/logicalparadox/matcha) - Simplistic approach to benchmarking.


### Minifiers-最小化

- [babili](https://github.com/babel/babili) - ES2015+ aware minifier based on the Babel toolchain.
- [UglifyJS2](https://github.com/mishoo/UglifyJS2) - JavaScript minifier.
- [clean-css](https://github.com/jakubpawlowicz/clean-css) - CSS minifier.
- [imagemin](https://github.com/imagemin/imagemin) - Image minifier.


### Authentication-认证

- [Passport](https://github.com/jaredhanson/passport) - Simple, unobtrusive authentication.
- [Grant](https://github.com/simov/grant) - OAuth middleware for Express, Koa, and Hapi.


### Authorization-权限

- [CASL](https://github.com/stalniy/casl) - Isomorphic authorization for UI and API.


### Email-邮件

- [Nodemailer](https://github.com/andris9/Nodemailer) - The fastest way to handle email.
- [emailjs](https://github.com/eleith/emailjs) - Send text/HTML emails with attachments to any SMTP server.
- [email-templates](https://github.com/niftylettuce/email-templates) - Create, preview, and send custom email templates.


### Job queues-任务队列

- [kue](https://github.com/Automattic/kue) - Redis-backed priority job queue.
- [bull](https://github.com/OptimalBits/bull) - Persistent job and message queue.
- [agenda](https://github.com/rschmukler/agenda) - MongoDB-backed job scheduling.


### Node.js management-node版本管理

- [n](https://github.com/tj/n) - Node.js version management.
- [nodeenv](https://github.com/ekalinin/nodeenv) - Node.js virtual environment compatible to Python's virtualenv.
- [nvm for Windows](https://github.com/coreybutler/nvm-windows) - Version management for Windows.





### Process management-进程管理

- [PM2](https://github.com/Unitech/pm2) - Advanced Process Manager.
- [nodemon](https://github.com/remy/nodemon) - Monitor for changes in your app and automatically restart the server.
- [node-windows](https://github.com/coreybutler/node-windows) - Run scripts as a native Windows service and log to the Event viewer.
- [supervisor](https://github.com/petruisfan/node-supervisor) - Restart scripts when they crash or restart when a `*.js` file changes.
- [Phusion Passenger](https://github.com/phusion/passenger) - Friendly process manager that integrates directly into Nginx.


### Automation-自动化

- [robotjs](https://github.com/octalmage/robotjs) - Desktop Automation: control the mouse, keyboard and read the screen.


### AST-语法树

- [Acorn](https://github.com/ternjs/acorn) - Tiny, fast JavaScript parser.


### Static site generators-静态网站生成

- [Wintersmith](https://github.com/jnordberg/wintersmith) - Flexible, minimalistic, multi-platform static site generator.
- [Assemble](https://github.com/assemble/assemble/) - Static site generator for Node.js, Grunt.js, and Yeoman.
- [DocPad](https://github.com/docpad/docpad) - Static site generator with dynamic abilities and huge plugin ecosystem.
- [Phenomic](https://github.com/phenomic/phenomic) - Modern static website generator based on the React and Webpack ecosystem.
- [docsify](https://github.com/QingWei-Li/docsify) - Markdown documentation site generator with no statically built HTML files.


### Content management systems-CMS

- [KeystoneJS](https://github.com/keystonejs/keystone) - CMS and web application platform built on Express and MongoDB.
- [ApostropheCMS](https://github.com/apostrophecms/apostrophe) - Content management system with an emphasis on intuitive front end content editing and administration built on Express and MongoDB.
- [Strapi](https://github.com/strapi/strapi) - Content Management Framework (headless-CMS) to build powerful APIs.


### Forum-论坛

- [nodeBB](https://github.com/NodeBB/NodeBB) - Forum platform for the modern web.


### Blogging-博客

- [Ghost](https://github.com/TryGhost/Ghost) - Simple, powerful publishing platform.
- [Hexo](https://github.com/hexojs/hexo) - Fast, simple and powerful blogging framework.


### Weird-好玩的

- [cows](https://github.com/sindresorhus/cows) - ASCII cows.
- [superb](https://github.com/sindresorhus/superb) - Get superb like words.
- [cat-names](https://github.com/sindresorhus/cat-names) - Get popular cat names.
- [dog-names](https://github.com/sindresorhus/dog-names) - Get popular dog names.
- [superheroes](https://github.com/sindresorhus/superheroes) - Get superhero names.
- [supervillains](https://github.com/sindresorhus/supervillains) - Get supervillain names.
- [cool-ascii-faces](https://github.com/maxogden/cool-ascii-faces) - Get some cool ascii faces.
- [cat-ascii-faces](https://github.com/melaniecebula/cat-ascii-faces) - ₍˄·͈༝·͈˄₎◞ ̑̑ෆ⃛ (=ↀωↀ=)✧ (^･o･^)ﾉ”
- [nerds](https://github.com/SkyHacks/nerds) - Get data from nerdy topics like Harry Potter, Star Wars, and Pokémon.


### Serialization-序列化

- [snappy](https://github.com/kesla/node-snappy) - Native bindings for Google's Snappy compression library.
- [protobuf](https://github.com/dcodeIO/protobuf.js) - Implementation of Protocol Buffers.


### Miscellaneous-杂项

- [execa](https://github.com/sindresorhus/execa) - Better `child_process`.
- [cheerio](https://github.com/cheeriojs/cheerio) - Fast, flexible, and lean implementation of core jQuery designed specifically for the server.
- [Electron](https://github.com/atom/electron) - Build cross platform desktop apps with web technologies.
- [opn](https://github.com/sindresorhus/opn) - Opens stuff like websites, files, executables.
- [hasha](https://github.com/sindresorhus/hasha) - Hashing made simple. Get the hash of a buffer/string/stream/file.
- [mem](https://github.com/sindresorhus/mem) - Memoize functions - an optimization technique used to speed up consecutive function calls by caching the result of calls with identical input.
- [ssh2](https://github.com/mscdex/ssh2) - SSH2 client and server module.
- [file-type](https://github.com/sindresorhus/file-type) - Detect the file type of a Buffer.
- [Bottleneck](https://github.com/SGrondin/bottleneck) - Rate limiter that makes throttling easy.
- [ow](https://github.com/sindresorhus/ow) - Function argument validation for humans.
- [webworker-threads](https://github.com/audreyt/node-webworker-threads) - Lightweight Web Worker API implementation with native threads.
- [clipboardy](https://github.com/sindresorhus/clipboardy) - Access the system clipboard (copy/paste).
- [node-pre-gyp](https://github.com/mapbox/node-pre-gyp) - Makes it easy to publish and install Node.js C++ addons from binaries.
- [opencv](https://github.com/peterbraden/node-opencv) - Bindings for OpenCV. The defacto computer vision library.
- [dotenv](https://github.com/motdotla/dotenv) - Load environment variables from .env file.
- [semver](https://github.com/npm/node-semver) - Semantic version parser.
- [Faker.js](https://github.com/Marak/Faker.js) - Generate massive amounts of fake data.
- [nodegit](https://github.com/nodegit/nodegit) - Native bindings to Git.
- [jsdom](https://github.com/tmpvar/jsdom) - JavaScript implementation of HTML and the DOM.
- [hypernova](https://github.com/airbnb/hypernova) - Server-side rendering your JavaScript views.
- [emittery](https://github.com/sindresorhus/emittery) - Simple and modern async event emitter.


## Resources-资源

### Tutorials-教学

- [Nodeschool](http://nodeschool.io) - Learn Node.js with interactive lessons.
- [The Art of Node](https://github.com/maxogden/art-of-node/#the-art-of-node) - An introduction to Node.js.
- [stream-handbook](https://github.com/substack/stream-handbook) - How to write Node.js programs with streams.
- [module-best-practices](https://github.com/mattdesl/module-best-practices) - Some good practices when writing new npm modules.
- [The Node Way](http://thenodeway.io) - An entire philosophy of Node.js best practices and guiding principles exists for writing maintainable modules, scalable applications, and code that is actually pleasant to read.
- [You Don't Know Node.js](https://github.com/azat-co/you-dont-know-node) - Introduction to Node.js core features and asynchronous JavaScript.


### Discovery-发现

- [npms](https://npms.io) - Superb package search with deep analysis of package quality using a [myriad of metrics](https://npms.io/about).
- [npm addict](https://npmaddict.com) - Your daily injection of npm packages.
- [npmcompare.com](https://npmcompare.com) - Compare and discover npm packages.

### Articles-文章

- [Error Handling in Node.js](https://www.joyent.com/node-js/production/design/errors)
- [Teach Yourself Node.js in 10 Steps](https://ponyfoo.com/articles/teach-yourself-nodejs-in-10-steps)
- [Mastering the filesystem in Node.js](https://medium.com/@yoshuawuyts/mastering-the-filesystem-in-node-js-4706b7cb0801)
- [Semver: A Primer](https://nodesource.com/blog/semver-a-primer/)
- [Semver: Tilde and Caret](https://nodesource.com/blog/semver-tilde-and-caret/)
- [Why Asynchronous?](https://nodesource.com/blog/why-asynchronous/)
- [Understanding the Node.js Event Loop](https://nodesource.com/blog/understanding-the-nodejs-event-loop/)
- [Understanding Object Streams](https://nodesource.com/blog/understanding-object-streams/)
- [Art of README](https://github.com/noffle/art-of-readme) - Learn the art of writing quality READMEs.

### Newsletters-新闻

- [Node Weekly](http://nodeweekly.com) - Weekly e-mail round-up of Node.js news and articles.
- [Node Module Of The Week!](https://nmotw.in) - Weekly dose of hand picked node modules.


### Books-图书

- [Node.js in Action](https://www.manning.com/books/node-js-in-action-second-edition)
- [Node.js in Practice](http://www.amazon.com/Node-js-Practice-Alex-R-Young/dp/1617290939)
- [Mastering Node](http://visionmedia.github.io/masteringnode/)
- [Node.js 8 the Right Way](https://pragprog.com/book/jwnode2/node-js-8-the-right-way)
- [Professional Node.js: Building Javascript Based Scalable Software](http://www.amazon.com/Professional-Node-js-Building-Javascript-Scalable-ebook/dp/B009L7QETY/)
- [Practical Node.js: Building Real-World Scalable Web Apps](http://practicalnodebook.com)
- [Mixu's Node book](http://book.mixu.net/node/)
- [Web Development with Node and Express](http://shop.oreilly.com/product/0636920032977.do)
- [Pro Express.js](http://proexpressjs.com)
- [Secure Your Node.js Web Application](http://www.amazon.com/Secure-Your-Node-js-Web-Application/dp/1680500856)
- [Express in Action](https://www.manning.com/books/express-in-action)

### Blogs-博客

- [Node.js blog](https://nodejs.org/en/blog/)
- [webapplog.com](http://webapplog.com/tag/node-js/) - Blog posts on Node.js and JavaScript from the author of Practical Node.js and Pro Express.js Azat Mardan.

### Courses-课程

- [Learn to build apps and APIs with Node.js](https://learnnode.com/friend/AWESOME) - Video course by Wes Bos.
- [Real Time Web with Node.js](https://www.codeschool.com/courses/real-time-web-with-node-js)
- [Learn and Understand Node.js](https://www.udemy.com/understand-nodejs)

### Cheatsheets-快捷表

- [Express.js](https://github.com/azat-co/cheatsheets/blob/master/express4)
- [Stream FAQs](https://github.com/stephenplusplus/stream-faqs) - Answering common questions about streams, covering pagination, events, and more.

### Tools-工具

- [OctoLinker](https://chrome.google.com/webstore/detail/octolinker/jlmafbaeoofdegohdhinkhilhclaklkp) - Chrome extension that linkifies dependencies in package.json, .js, .jsx, .coffee and .md files on GitHub.
- [npm-hub](https://chrome.google.com/webstore/detail/npm-hub/kbbbjimdjbjclaebffknlabpogocablj) - Chrome extension to display npm dependencies at the bottom of a repo's readme.
- [RunKit](http://blog.tonicdev.com/2015/09/30/embedded-tonic.html) - Embed a Node.js environment on any website.
- [RequireBin](http://requirebin.com) - Shareable JavaScript programs powered by npm and browserify.
- [github-npm-stats](https://chrome.google.com/webstore/detail/github-npm-stats/oomfflokggoffaiagenekchfnpighcef) - Chrome extension that displays npm download stats on GitHub.

### Community-社区

- [Gitter](https://gitter.im/nodejs/node)
- [`#node.js` on Freenode](http://webchat.freenode.net/?channels=node.js)
- [Stack Overflow](http://stackoverflow.com/questions/tagged/node.js)
- [Reddit](https://www.reddit.com/r/node)
- [Twitter](https://twitter.com/nodejs)
- [Hashnode](https://hashnode.com/n/nodejs)

### Miscellaneous-杂项

- [nodebots](http://nodebots.io) - Robots powered by JavaScript.
- [node-module-boilerplate](https://github.com/sindresorhus/node-module-boilerplate) - Boilerplate to kickstart creating a node module.
- [generator-nm](https://github.com/sindresorhus/generator-nm) - Scaffold out a node module.
- [Microsoft Node.js Guidelines](https://github.com/Microsoft/nodejs-guidelines) - Tips, tricks, and resources for working with Node.js on Microsoft platforms.
- [Module Requests & Ideas](https://github.com/sindresorhus/module-requests) - Request a JavaScript module you wish existed or get ideas for modules.
