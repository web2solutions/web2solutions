# Projects timeline

## Imóvel Manager - 2009

Imóvel Manager was a Real Estate ERP software offered by my startup company as SaaS starting in 2009. From client management, up to financial automation, Imóvel Manager supported 2 hundred agencies paying small rates for cloud software.

In 2007 I started to attend several Real Estate agencies looking to develop websites and CRM tools. Then I created a product to attend that niche. At that point of time, the system was a monolithic ASP (my firstly learnt platform) application. Once the acceptance had increased and it required to be backed by better technologies, I decided to migrate it to Perl.

The goal was to decouple front and back end, completely, by creating a RIA application in the front and a REST api in the back end, leveraging things like preforking and event loops. To decrease the time and impact, the VB code was progressively rewrite to Perl, stills yet running on ASP.

In order to move from Windows to Linux, I initially picked Apache::ASP as an interface to run the migrated code, and finally I could have the entire codebase migrated from ASP/IIS to Mojolicious and Starman behind a Nginx.

Skills: Algorithm Design · Front-End Development · Node.js · Javascript · Perl · Test Driven Development · Event Driven Programming · Representational State Transfer (REST) · Microservices · Distributed Systems · Software Engineering · Software Architecture · PostgreSQL · Linux · HTML5 · REST · MongoDB · Git · Redis · RabbitMQ . crawling

Company WEB2 Solutions

Team: 1 engineer (me).

References:

1 - International blog showcasing the ERP:

<https://dhtmlx.com/blog/customer-spotlight-dhtmlx-cash-flow/>

2 - Perl bot created by me, that provides host automation over the shared hosting offered by Kinghost (<www.kinghost.com.br>). It fully automates the onboarding process of new clients:

- create host account
- setup domain
- setup main boxes
- setup host environment

<https://metacpan.org/pod/WWW::Kinghost::Painel>

## DHTMLX-Perl - 2012

The DHTMLX-Perl package is the Perl, open source replacement for the DHTMLX PHP connector (<https://docs.dhtmlx.com/connector__php__index.html#:~:text=DHTMLX%20connector%20is%20a%20helper,%2C%20filtering%2C%20validation%2C%20etc>.)

The DHTMLX PHP is the backend distribution that powers the version 4 and 5 of the DHTMLX framework (<www.dhtmlx.com>)

I created this package to be able to use all DHTMLX features under the Perl ecosystem.

Company WEB2 Solutions

Reference:

<https://github.com/web2solutions/DHTMLX-Perl>

Skills: Perl, Vanilla Javascript, ES5, PostgreSQL, MS-SQL, MySQL, Oracle, CGI, PSGI, ASP, IIS, Apache, Windows, Linux, Mojolicious

## ADV Manager - 2012

ADV Manager was ERP software for Lawyers and Attorneys, offered by my startup company as SaaS starting in 20012. From client management, up to process management and tracker.

In order to provide tracking automation for process, I created a set of Perl bots to get updated information of each process from their respective justice sector (websites such as TRT-ES, TJ-ES, TJ-RJ and so on). Some of those crawler bots were published as open source software.

Skills: Algorithm Design · Front-End Development · Node.js · Javascript · Perl · Test Driven Development · Event Driven Programming · Representational State Transfer (REST) · Microservices · Distributed Systems · Software Engineering · Software Architecture · PostgreSQL · Linux · HTML5 · REST · MongoDB · Git · Redis · RabbitMQ . crawling

Team: 1 engineer (me).

Company WEB2 Solutions

References:

- <https://metacpan.org/pod/Tribunais::TJES>
- <https://metacpan.org/pod/Tribunais::TRTES>

--------------------

## PaypalREST - 2013

The PaypalREST is a Perl module built entire by me to support the entire financial and billing operations for the first version of MAP (My Adoption Portal).

- It POC is published here: <https://github.com/web2solutions/PaypalREST>

Company CAIRS Solutions

Skills: Perl, web crawling, PayPal, API consuming.

--------------------

## TMS - 2013

TMS is a fullstack application (SPA + Node.js backend) entire created by me that fully automates the process from request up to delivering printed "Family Books".

Features:

- Book Request Management.
- Book Design: The family have the ability to create their own desired UX for their books through an intuitive web interface.
- Book Printing: Printer management.
- Book Delivery: Delivery management for books.

Company CAIRS Solutions

Reference: <https://parentfinder.com/>

Skills: Fullstack . Javascript . Node.js . DHTMLX . MySQL . Serial communication . Linux . REST . Redis . RabbitMQ . pm2

--------------------

## CAIRS Framework - 2014

The CAIRS Framework is a framework created entirely by me to support the creation of a series of SPAs for the company's different products: MAP, PF and Child Connect.

Features:

- REST client
- Data persistence on browsers.
- Lazy loading for Javascript modules
- Cookie management
- JSON -> XML and XML -> JSON parsers
- XML serialization
- Type checking for ES5
- custom array prototype methods for ES5
- Custom OO implementation for ES5 (supporting Inheritance)
- PDF rendering
- UI components

Company CAIRS Solutions

Reference: <https://github.com/web2solutions/CAIRS_Framework>

Skills: Javascript, Node.js, IndexedDB, DOM API, BOM API

--------------------

## CAIRS Mediator - 2014

The CAIRS Mediator was a Node.js module entirely created by me that provides a custom implementation of the "Mediator Pattern" and was the core piece used in the microservices communication.

Company CAIRS Solutions

Skills: Javascript . Node.js . Redis . RabbitMQ . pm2

--------------------

## MAP-API - 2014

The MAP API is a Perl framework to create distributed REST APIs that provides vertical scaling capabilities "inside the box".

Company CAIRS Solutions

Reference:

<https://github.com/web2solutions/MAP-API>
<https://github.com/web2solutions/MAP-API/tree/master/docs/deploy>
<https://github.com/web2solutions/MAP-API/tree/master/docs/end%20points>

Skills: Perl, MS SQL, REST, Starman, Centos, Dancer. PSGI

--------------------

## dhxMVP - 2016

dhxMVP is a framework for building online, offline and sync-able Javascript MVP Single Page Applications using DHTMLX.

Reference:

<https://github.com/web2solutions/dhxMVP>

Skills: Javascript . Node.js . Gulp . Electron . DHTMLX . IndexedDB . Backbone.js

--------------------

## Jumentix - 2019

Jumentix is a backend framework that provides full `Application foundation` for `REST` and `Realtime Node.JS micro service` applications.

References:  

- <https://github.com/web2solutions/Jumentix>
- <https://web2solutions.github.io/Jumentix/>
- <https://www.youtube.com/watch?v=rGdnkaB-SvM>
- <https://www.youtube.com/watch?v=FIabzM9iapw&feature=youtu.be>

Skills: Node.js, Javascript, OpenAPI, Code Automation, Code Generation, Low-Code, Meta-Programming, RAD, MongoDB, RabbitMQ, Redis, Cassandra, Elastic Search, pm2, Centos

--------------------

## Jumentix-VUE-UI - 2019

Jumentix-VUE-UI is a framework that builds Single Page Application and Personal Web Application and it most powerful feature is the `runtime generated Vue.js` `User Interfaces` by leveraging extended Swagger OpenAPI specification as declarative metadata.

Reference:

- <https://github.com/web2solutions/Jumentix-Vue-UI>
- <https://www.youtube.com/watch?v=rGdnkaB-SvM>
- <https://www.youtube.com/watch?v=FIabzM9iapw&feature=youtu.be>

Skills: Node.js, Javascript, Vue, OpenAPI, Code Automation, Code Generation, Low-Code, Meta-Programming, RAD, Vuetify, JQWidgets, DHTMLX,

--------------------

## Voodux - 2020

Frontend agnostic framework that provides building blocks to build `offline first` SPAs and PWAs. Provides features such as local persistence and realtime data sync between local browser sessions.

Reference:

- <https://web2solutions.github.io/voodux/code/index.html>
- <https://github.com/web2solutions/voodux>
- <https://www.youtube.com/watch?v=LALGgiqPxlA&feature=youtu.be>

skills: Javascript, IndexedDB, DOM API, BOM API, WebSocket, React, Vue, DHTMLX, Svelte

--------------------

## Connector Framework

The Connector Framework is a npm module built with typescript that encapsulates a set of `non-functional requirements` and is the core dependency of all microservices at Fabric.inc that provides communication with multiple third party service providers (almost 200) such as Stripe, Authorize.net, CyberSource, SalesForce, Paypal, Shopify, and so on.

Company Fabric.inc

Reference:

- <https://fabric.inc/>

skills: AWS Lambda, AWS SNS, AWS SQS, serverless framework, Node.js, Typescript, DynamoDB, Redis, The Clean Architecture, Jest, TDD, Event Driven Architecture

--------------------
## Guessing Game 2021

Guessing game

<https://github.com/web2solutions/guessing_game>

skills: Rust

--------------------

## ds-ts - 2022

The `ds-ts` project is a set of `Articles` and `Algorithms`, built for portuguese speakers, that mitigates `data-structures` like `queues`, `stacks`, `lists`, `heap` and `trees` using the Typescript language.

Reference:

https://github.com/web2solutions/ds-ts

Skills: javascript typescript, stack queue interview, trie data-structures, binary-search-tree, binary-tree, linkedlist, interview-practice, interview-questions, estrutura-de-dados, coding-challenge, interview-preparation, tries, trie-tree

--------------------


## arithmetic-calculator-api and arithmetic-calculator-ui - 2023

The projects arithmetic-calculator-api (backend) and arithmetic-calculator-ui (frontend) were made as coding challenge for [TrueNorth](https://www.truenorth.co/).

Reference:

- https://github.com/web2solutions/arithmetic-calculator-api
- https://github.com/web2solutions/arithmetic-calculator-ui
- https://arithmetic-calculator-ui-nu.vercel.app/ user: admin@admin.com password: 123456

Skills: AWS lambda, serverless and serverless-offline, Node.js, TypeScript, MongoDB and Mongo Atlas as Database, Redis and Redis Labs as Cache layer, Jest,  Eslint, Docker, CI/CD, unit tests, e2e tests, Vue 3, Bootstrap, IndexedDB, REST, Cypress, Pinia.

--------------------

## ddd-app - 2023

Domain driven designed, Application Framework Agnostic, REST API boilerplate made with Typescript.

Reference:

https://github.com/web2solutions/ddd-app

Skills: nodejs, docker, lambda, express, typescript, kafka, ec2, serverless, lambda-functions, domain-driven-design, ecs, clean-architecture, test-driven-development, agnostic-to-frameworks, hexagonal-architecture

--------------------

## typescript-boilerplate - 2023

Clean architectured, Infrastructure agnostic and Domain Driven designed Typescript application boilerplate.

Reference:

https://github.com/thecleanarchitecture/typescript-boilerplate

Skills: javascript, typescript, clean-code, domain-driven-design, clean-architecture, repository-pattern, hexagonal-architecture, component-architecture, inmemory-db, TDD, CI/CD

--------------------

## Domain Designer - 2023

The Domain Designer is an application that designs and generates component code for REST APIs and microservices based on some paradigms such as DDD, Hexagonal Architecture and The Clean Architecture.

Features:

- Easy application domain visualization.
- Visually build application domains and it components
- Generate UML diagrams
- Generate Data Models
- Generate OpenAPI specs
- penAPI specification versioning
- Generate Data Transfer Objects
- Generate Controllers
- Generate Services
- Generate Use Cases
- Coordinate Product and Engineering teams
- Single source of truth for APIs specifications.
- API Publishing
- API Versioning

Reference:

- https://github.com/web2solutions/domain-designer
- https://www.linkedin.com/posts/eduardo-perotta-de-almeida_rapidprototyping-agile-uml-activity-7107550946720702464-m_h-?utm_source=share&utm_medium=member_desktop
- https://domain-designer.vercel.app/

Skills: Typescript, Node.js. Vue 3, Bulma, IndexedDB, Vite, DDD, Hexagonal Architecture, The Clean Architecture, Meta-programming, RAD, OpenAPI, Product Management

--------------------