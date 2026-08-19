# Awesome rethinkdb with stars

<h3 align="center">
	<img width="120" src="https://github.com/d3viant0ne/awesome-rethinkdb/blob/master/media/rethinkdb.jpg" alt="RethinkDB">
	<br>
</h3>
## Awesome RethinkDB [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome RethinkDB resources, libraries, tools and applications

Inspired by the [awesome](https://github.com/sindresorhus/awesome) ⭐ 497,717 | 🐛 102 | 📅 2026-08-18 list. Feel free to improve this list by [contributing](CONTRIBUTING.md)!

### Table of Contents

* [Resources](#resources)
* [Documentation](#documentation)
* [Community](#community)
* [JavaScript](#javascript-libraries)
* [Python](#python-libraries)
* [Ruby](#ruby-libraries)
* [Java](#java-libraries)
* [Additional Languages](#additional-languages)
* [Community Supported](#community-supported-drivers)
* [Research and Training](#research-and-training)
* [Articles](#articles)
* [Talks](#talks)
* [RethinkDB Examples](#rethinkdb-examples)
* [Community Examples](#community-examples)
* [Tools](#tools)
* [Administration](#administrative-tools)
* [Deployment](#deployment)

<br>
> <h3>RethinkDB Ecosystem</h3>

#### Documentation

* [RethinkDB](http://rethinkdb.com/docs/) - RethinkDB Documentation
* [ReQL API](http://rethinkdb.com/api/javascript/) - JavaScript ReQL command reference

#### Community

* [Request Slack Invite](http://slack.rethinkdb.com/)
* [RethinkDB StackOverflow](http://stackoverflow.com/tags/rethinkdb)
* [RethinkDB Blog](https://www.rethinkdb.com/blog/)
* [RethinkDB Google Group](https://groups.google.com/forum/#!forum/rethinkdb)
* [RethinkDB YouTube Channel](https://www.youtube.com/channel/UC1kJkmSWt_snLDfuXgJnLnQ)
* [RethinkDB Reddit](https://www.reddit.com/r/rethinkdb/)

<br>
> <h3>JavaScript Libraries</h3>

##### Drivers

* [RethinkDB JavaScript](https://www.rethinkdb.com/docs/install-drivers/javascript/) - Officially Supported JavaScript Driver.
* Maintainer: `RethinkDB Team`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/rethinkdb) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/rethinkdb)
* [RethinkDB Dash](https://github.com/neumino/rethinkdbdash) ⭐ 841 | 🐛 53 | 🌐 JavaScript | 📅 2022-05-06 - An advanced Node.js driver for RethinkDB with connection pool and Streams Support.
* Maintainer: `Michel`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/neumino) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/neumino)

##### ORM

* [Thinky](https://github.com/neumino/thinky) ⭐ 1,113 | 🐛 107 | 🌐 JavaScript | 📅 2021-11-21 - JavaScript ORM for RethinkDB
* [JSData RethinkDB](https://github.com/js-data/js-data-rethinkdb) ⭐ 32 | 🐛 9 | 🌐 JavaScript | 📅 2017-08-18 - RethinkDB adapter for the js-data ORM.
* Maintainer: `Michel`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/neumino) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/neumino)
* Maintainer: `JS Data Organization`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/js-data)

##### Extension Libraries

* [Express Session RethinkDB](https://github.com/armenfilipetyan/express-session-rethinkdb) ⭐ 23 | 🐛 5 | 🌐 JavaScript | 📅 2016-11-22 - RethinkDB session store for Express 4.x.
* [RethinkDB Pool](https://github.com/hden/rethinkdb-pool) ⭐ 22 | 🐛 6 | 🌐 JavaScript | 📅 2026-08-02 - Connection-pool for RethinkDB.
* Maintainer: `Hao-kang Den`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/hden)
* Maintainer: `@armenfilipetyan`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/armenfilipetyan)

##### Technology Integrations

* [Sails Hook Thinky](https://github.com/mwielbut/sails-hook-thinky) ⚠️ Archived - A hook to enable the Thinky ORM for RethinkDB in Sails.
* [KOA RethinkDB](https://github.com/hden/koa-rethinkdb) ⚠️ Archived - Koa middleware that gets you a RethinkDB client.
* [Hapi RethinkDB CRUD](https://github.com/athlite/hapi-rethinkdb-crud) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2016-02-02 - CRUD handlers for Hapi interaction with Rethinkdb.
* Maintainer: `Thomas Eng`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/athlite)
* Maintainer: `Matt Wielbut`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/mwielbut) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/mwielbut)
* Maintainer: `Hao-kang Den`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/hden)
* [RabbitMQ](http://rethinkdb.com/docs/rabbitmq/javascript/) - Integrating RethinkDB with RabbitMQ
* Maintainer: `RethinkDB Team`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/rethinkdb) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/rethinkdb)

**[Back to top](#table-of-contents)**

<br>
> <h3>Python Libraries</h3>

##### Drivers

* [RethinkDB Python](https://www.rethinkdb.com/docs/install-drivers/python/) - Officially Supported JavaScript Driver.
* Maintainer: `RethinkDB Team`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/rethinkdb) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/rethinkdb)

##### ORM

* [Remodel](https://github.com/linkyndy/remodel) ⭐ 192 | 🐛 3 | 🌐 Python | 📅 2020-05-13 - Very simple yet powerful and extensible Object Document Mapper for RethinkDB, written in Python.
* [Rethink](https://github.com/caoimhghin/rethink) ⭐ 14 | 🐛 2 | 🌐 Python | 📅 2015-08-01 - Python RethinkDB Object Mapper Interface Inspired by Appengine NDB.
* Maintainer: `Andrei Horak`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/linkyndy) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/linkyndy)
* Maintainer: `Kevin Amerson`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/caoimhghin) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/kevinamerson)

##### Technology Integrations

* [flask-rethinkdb](https://github.com/linkyndy/flask-rethinkdb) ⭐ 27 | 🐛 1 | 🌐 Python | 📅 2021-06-22 - Adds RethinkDB support to Flask.
* Maintainer: `Andrei Horak`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/linkyndy) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/linkyndy)
* [RabbitMQ](https://www.rethinkdb.com/docs/rabbitmq/python/) - Integrating RethinkDB with RabbitMQ
* Maintainer: `RethinkDB Team`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/rethinkdb) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/rethinkdb)

**[Back to top](#table-of-contents)**

<br>
> <h3>Ruby Libraries</h3>

##### Drivers

* [RethinkDB Ruby](http://rethinkdb.com/docs/install-drivers/ruby/) - Officially Supported Ruby Driver.
* Maintainer: `RethinkDB Team`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/rethinkdb) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/rethinkdb)

##### ORM

* [NoBrainer](https://github.com/nviennot/nobrainer) ⭐ 385 | 🐛 18 | 🌐 Ruby | 📅 2025-04-28 - Ruby ORM for RethinkDB.
* Maintainer: `Nicolas Viennot`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/nviennot) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/nviennot)

##### Technology Integrations

* [Epiphy](https://github.com/kureikain/epiphy) ⭐ 7 | 🐛 7 | 🌐 Ruby | 📅 2014-08-12 - Lightweight RethinkDB ORM.
* [lotus-rethinkdb](https://github.com/angeloashmore/lotus-rethinkdb) ⭐ 6 | 🐛 1 | 🌐 Ruby | 📅 2016-05-13 - RethinkDB adapter for Lotus::Model.
* Maintainer: `Vinh Quốc Nguyễn`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/kureikain) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/kureikain)
* Maintainer: `Angelo Ashmore`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/angeloashmore) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/angeloashmore)
* [RabbitMQ](https://www.rethinkdb.com/docs/rabbitmq/ruby/) - Integrating RethinkDB with RabbitMQ
* Maintainer: `RethinkDB Team`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/rethinkdb) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/rethinkdb)

**[Back to top](#table-of-contents)**

<br>
> <h3>Java Libraries</h3>

##### Drivers

* [Rethinker](https://github.com/futurechimp/rethinker) ⭐ 2 | 🐛 0 | 🌐 Scala | 📅 2016-03-21 - A simplistic serialisation library for use alongside the official RethinkDb Java driver.
* [Rethinkdb4j](https://github.com/tony-brewerio/rethinkdb4j) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2015-11-16 - Asynchronous Netty-based RethinkDB driver for Java.
* [RethinkDB Java](http://rethinkdb.com/docs/install-drivers/java/) - Officially Supported Java Driver.
* Maintainer: `RethinkDB Team`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/rethinkdb) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/rethinkdb)
* Maintainer: `Dave Hrycyszyn`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/futurechimp) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/futurechimp)
* Maintainer: `Anton Ustyuzhanin`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/tony-brewerio)

##### ORM

* [RethinkDB Java ORM](https://github.com/PeterKnego/rethinkdb-java-orm) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2016-09-12 - A custom POJO converter for RethinkDB Java driver.
* Maintainer: `Peter Knego`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/PeterKnego) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/peterknego)

##### Technology Integrations

* [RabbitMQ](https://www.rethinkdb.com/docs/rabbitmq/java/) - Integrating RethinkDB with RabbitMQ
* Maintainer: `RethinkDB Team`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/rethinkdb) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/rethinkdb)

**[Back to top](#table-of-contents)**

<br>
> <h3>Additional Languages</h3>

#### Community Supported Drivers

* [Go](https://github.com/dancannon/gorethink) ⭐ 1,646 | 🐛 27 | 🌐 Go | 📅 2025-10-24 - Go language driver for RethinkDB.
* [Elixir](https://github.com/hamiltop/rethinkdb-elixir) ⭐ 491 | 🐛 20 | 🌐 Elixir | 📅 2018-11-27 - Multiplexed RethinkDB client in pure Elixir.
* [C#](https://github.com/bchavez/RethinkDb.Driver) ⭐ 381 | 🐛 24 | 🌐 C# | 📅 2020-12-12 - A C#/.NET RethinkDB driver striving for 100% ReQL API coverage.
* [PHP](https://github.com/danielmewes/php-rql) ⭐ 336 | 🐛 35 | 🌐 PHP | 📅 2022-09-09 - A PHP client driver for the RethinkDB query language (ReQL).
* [Clojure](https://github.com/apa512/clj-rethinkdb) ⭐ 203 | 🐛 41 | 🌐 Clojure | 📅 2019-04-24 - A RethinkDB client for Clojure.
* [Scala](https://github.com/kclay/rethink-scala) ⭐ 101 | 🐛 13 | 🌐 Scala | 📅 2016-02-02 - Scala Driver for RethinkDB.
* [C++](https://github.com/AtnNn/librethinkdbxx) ⭐ 100 | 🐛 16 | 🌐 C++ | 📅 2017-11-08 - RethinkDB driver for C++.
* [Haskell](https://github.com/AtnNn/haskell-rethinkdb) ⭐ 93 | 🐛 6 | 🌐 Haskell | 📅 2017-05-11 - RethinkDB client library for Haskell.
* [Lisp](https://github.com/orthecreedence/cl-rethinkdb) ⭐ 48 | 🐛 7 | 🌐 Common Lisp | 📅 2016-07-08 - RethinkDB driver for Common Lisp.
* [Dart](https://github.com/billysometimes/rethinkdb) ⭐ 38 | 🐛 4 | 🌐 Dart | 📅 2024-02-21 - A Dart driver for RethinkDB v2.0.3.
* [Perl](https://github.com/njlg/perl-rethinkdb) ⚠️ Archived - A Pure Perl RethinkDB Driver.
* [Objective-C](https://github.com/dparnell/rethink-db-client) ⭐ 13 | 🐛 0 | 🌐 Objective-C | 📅 2016-05-10 - A RethinkDB client written in Objective-C.
* [Lua](https://github.com/grandquista/Lua-ReQL) - Rethinkdb driver in Lua.

**[Back to top](#table-of-contents)**

<br>
> <h3> Research And Training</h3>

#### Articles

* [Shahid Shaikh | 08-Mar-16](https://codeforgeek.com/2016/03/building-real-time-polling-app-rethinkdb-nodejs/) - Building real time polling app using RethinkDB and Nodejs.
* [Dr. Gleb Bahmutov PhD | 08-Feb-16](https://glebbahmutov.com/blog/redux-and-rethinkdb/) - Redux and RethinkDB
* [Scott Hasbrouck | 13-Mar-16](http://www.scotthasbrouck.com/blog/2016/3/13/using-socketio-with-rethinkdb-changefeeds-to-build-a-reactive-backend) - Using Socket.Io With RethinkDB Changefeeds To Build A Reactive JavaScript Stack
* [Khalid Abuhakmeh | 15-Nov-15](http://www.khalidabuhakmeh.com/getting-started-with-rethinkdb-and-asp-net-5) - Getting Started With RethinkDB and ASP.NET 5.
* [Slava Akhmechet | 01-Sept-15](http://www.infoworld.com/article/2975838/database/build-real-time-web-apps-with-rethinkdb.html) - Build real-time Web apps with RethinkDB.
* [Justin for Fanout | 20-May-15](http://blog.fanout.io/2015/05/20/building-a-realtime-api-with-rethinkdb/) - Building a realtime API with RethinkDB.
* [Nicholas Duffy | 30-Apr-15](https://strongloop.com/strongblog/rethinkdb-connector-loopback-node-js-framework/) - Getting Started with the RethinkDB Connector for LoopBack.
* [Rob Conery | 17-Apr-15](http://rob.conery.io/2015/04/17/rethinkdb-2-0-is-amazing/) - RethinkDB 2.0 Is Amazing.
* [Gordon Dent | 01-Apr-15](https://www.airpair.com/rethinkdb/posts/moving-from-sql-to-rethinkdb) - A Comprehensive Guide to moving from SQL to RethinkDB.
* [Gordon Dent | 11-Mar-15](http://blog.workshape.io/we-use-rethinkdb-at-workshapeio/) - We use RethinkDB at Workshape.io.

#### Talks

* [Michael Glukhovsky at Clevertech | 30-Mar-16](https://www.youtube.com/watch?v=28XKxLPv0Hs) - RethinkDB Presentation to Clevertech.
* [Ryan Paul at ForwardJS | 21-Jan-16](https://www.youtube.com/watch?v=xCU9RHDWXIY) - RethinkDB: Database for realtime apps.
* [Rob Conery at DevDay 2015 | 17-Sept-15](https://www.youtube.com/watch?v=Ee1v_SuECRk) - Rethinking NoSQL.
* [Jorge Silva at RethinkDB Meetup | 29-June-15](https://www.youtube.com/watch?v=vJtDNRsUozk) - Data Modeling in RethinkDB.
* [Ben Tranter | 05-Apr-15](https://www.youtube.com/watch?v=d01rLeIjTLE) - A Simple REST API with Express, RethinkDB, and Thinky.
* [Associated Source](https://github.com/bentranter/ampersand-rethink-express) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2016-05-30
* [Ryan Paul at Mattermark | 17-Feb-15](https://www.youtube.com/watch?v=dhb63boH8E8) - Build a realtime RethinkDB cluster monitoring app with live graphs.
* [Associated Blog Post](http://rethinkdb.com/blog/realtime-cluster-monitoring/) - A realtime RethinkDB cluster monitoring app with live graphs.

#### RethinkDB Examples

* [RethinkDB NodeJS Chat](https://github.com/rethinkdb/rethinkdb-example-nodejs-chat) ⚠️ Archived - A node.js chat application running on rethinkdb.
* [RethinkDB Angular Express Promise](https://github.com/rethinkdb/rethinkdb-example-nodejs/tree/master/todo-angular-express-promise) ⚠️ Archived - Promise based Todo example with RethinkDB, ExpressJS and AngularJS .
* [RethinkDB Angular Express](https://github.com/rethinkdb/rethinkdb-example-nodejs/tree/master/todo-angular-express) ⚠️ Archived - Todo example with RethinkDB, ExpressJS and AngularJS.
* [RethinkDB Angular KOA](https://github.com/rethinkdb/rethinkdb-example-nodejs/tree/master/todo-angular-koa) ⚠️ Archived - Todo example with RethinkDB, KoaJS and AngularJS.
* [RethinkDB Flask Backbone ToDo](https://github.com/rethinkdb/rethinkdb-example-flask-backbone-todo) ⚠️ Archived - A canonical backbone todo application running on flask and RethinkDB.
* [RethinkDB PubNub Live Blog](https://github.com/rethinkdb/rethinkdb-pubnub-liveblog) ⚠️ Archived - PubNub / Express Blog Example App.
* [RethinkDB ccoenraets/nodecellar Fork](https://github.com/rethinkdb/nodecellar-rethinkdb) ⚠️ Archived - Sample app built with Backbone.js,Bootstrap, Node.js, Express, RethinkDB.

#### Community Examples

* [3ree](https://github.com/GordyD/3ree) ⭐ 840 | 🐛 4 | 🌐 JavaScript | 📅 2018-10-06 - An example universal JS application written with the 3REE stack, React + Redux + RethinkDB + Express.
* [Meguca](https://github.com/bakape/meguca) ⚠️ Archived - High performance real-time imageboard in Go, TypeScript and RethinkDB.
* [RethinkDB Chat](https://github.com/thejsj/rethinkdb-chat) ⭐ 66 | 🐛 0 | 🌐 JavaScript | 📅 2017-10-07 - A simple chat applications built with RethinkDB + Sockets.
* [Go RethinkDB ToDo](https://github.com/dancannon/GoRethink_TodoDemo) ⚠️ Archived - Go RethinkDB Todo List Example Application.
* [VueJS RethinkDB](https://github.com/alexcheninfo/vuejs-rethinkdb-example) ⭐ 61 | 🐛 5 | 🌐 JavaScript | 📅 2023-12-17 - Vuejs + Express + RethinkDB example.
* [Meteor GraphQL](https://github.com/AdamBrodzinski/Meteor-RethinkDB-GraphQL) ⭐ 44 | 🐛 2 | 🌐 JavaScript | 📅 2016-01-17 - A Meteor and RethinkDB Example Using GraphQL.
* [Boot RethinkDB](https://github.com/geowarin/boot-rethinkdb) ⭐ 40 | 🐛 2 | 🌐 Java | 📅 2018-02-20 - Chat example with spring boot and RethinkDB.
* [Realtime Chat RethinkDB](https://github.com/Unrestricted-Coding/realtime-chat-RethinkDB) ⭐ 28 | 🐛 2 | 🌐 JavaScript | 📅 2020-09-14 - A realtime chatroom built with RethinkDB
* [RethinkDB Reactjs](https://github.com/arkency/rethinkdb-reactjs) ⭐ 22 | 🐛 0 | 🌐 Ruby | 📅 2015-04-26 - rethinkdb + react.js + ActionController::Live (Rails) + Server Side Events.

**[Back to top](#table-of-contents)**

<br>
> <h3>Tools</h3>

#### Administrative Tools

* [Chateau](https://github.com/neumino/chateau) ⭐ 207 | 🐛 18 | 🌐 JavaScript | 📅 2017-09-27 - Another (awesome) data explorer for RethinkDB.
* [RethinkDB CLI](https://github.com/athlite/rethinkdb-cli) ⭐ 22 | 🐛 0 | 🌐 JavaScript | 📅 2021-02-13 - CLI and REPL for Rethinkdb.
* [RethinkDB Nightly](https://github.com/robconery/rethinkdb_nightly) - A node module that will execute a nightly backup and push it to S3.

#### Deployment

* [Docker](https://github.com/crosbymichael/Dockerfiles/blob/master/rethinkdb/Dockerfile) ⭐ 300 | 🐛 0 | 🌐 Python | 📅 2017-04-25 - Single node Dockerfile.
* [Vagrant](https://github.com/RyanAmos/rethinkdb-vagrant) ⭐ 46 | 🐛 2 | 🌐 Shell | 📅 2016-02-15 - Install RethinkDB using Vagrant.
* [Chef](https://github.com/AVVSDevelopment/chef-rethinkdb) ⭐ 15 | 🐛 0 | 🌐 Ruby | 📅 2014-05-10 - Chef RethinkDB cookbook.
* [Wrecker](https://github.com/mies/box-rethinkdb) ⭐ 10 | 🐛 1 | 🌐 Shell | 📅 2015-06-27 - Wercker box for RethinkDB.
* [Puppet](https://github.com/tmont/puppet-rethinkdb) ⭐ 4 | 🐛 1 | 🌐 Puppet | 📅 2014-09-20 - Puppet module for RethinkDB.

<br>
> <h3>License</h3>

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
