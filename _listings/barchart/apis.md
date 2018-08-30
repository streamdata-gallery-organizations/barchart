---
name: Barchart
x-slug: barchart
description: Barchart.com is the leading provider of intraday stock and commodities
  real-time or delayed charts with powerful indicators and technical analysis.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21632-www-barchart-com.jpg
x-kinRank: "7"
x-alexaRank: "15739"
tags: Barchart
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/barchart/master/_listings/barchart/apis.md
specificationVersion: "0.14"
apis:
- name: Barchart API - Get Quote
  x-api-slug: getquote-json-get
  description: The getQuote API is used to request price data, either real-time, delayed
    or end-of-day, by symbol. In addition to Last Price or Settlement, other fields
    such as Open, High, Low, Close, Bid, Ask, 52-week high and low, and more are available.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21632-www-barchart-com.jpg
  humanURL: https://www.barchart.com
  baseURL: https://marketdata.websol.barchart.com//
  tags: SaaS, Market Data, API Provider, Profiles, Publish, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/barchart/master/_listings/barchart/getquote-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/barchart/master/_listings/barchart/getquote-json-get-openapi.md
- name: Barchart API - Get Equities by Exchange
  x-api-slug: getequitiesbyexchange-json-get
  description: Receive all real-time or delayed stock and/or index price data by exchange
    through a single onDemand query.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21632-www-barchart-com.jpg
  humanURL: https://www.barchart.com
  baseURL: https://marketdata.websol.barchart.com//
  tags: SaaS, Market Data, API Provider, Profiles, Publish, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/barchart/master/_listings/barchart/getequitiesbyexchange-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/barchart/master/_listings/barchart/getequitiesbyexchange-json-get-openapi.md
- name: Barchart API - Get Futures by Exchange
  x-api-slug: getfuturesbyexchange-json-get
  description: Receive all real-time or delayed, or end-of-day Futures data by exchange
    through a single onDemand query.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21632-www-barchart-com.jpg
  humanURL: https://www.barchart.com
  baseURL: https://marketdata.websol.barchart.com//
  tags: SaaS, Market Data, API Provider, Profiles, Publish, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/barchart/master/_listings/barchart/getfuturesbyexchange-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/barchart/master/_listings/barchart/getfuturesbyexchange-json-get-openapi.md
- name: Barchart API - Get Close Price
  x-api-slug: getcloseprice-json-get
  description: Get the close price for given instruments for the given date.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21632-www-barchart-com.jpg
  humanURL: https://www.barchart.com
  baseURL: https://marketdata.websol.barchart.com//
  tags: SaaS, Market Data, API Provider, Profiles, Publish, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/barchart/master/_listings/barchart/getcloseprice-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/barchart/master/_listings/barchart/getcloseprice-json-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://bank.of.scotland.api.gallery.streamdata.io
- type: x-api-stack
  url: http://barchart.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/barchart-com
- type: x-email
  url: solutions@barchart.com
- type: x-email
  url: careers@barchart.com
- type: x-email
  url: colleen.sheeren@barchart.com
- type: x-github
  url: https://github.com/barchart
- type: x-twitter
  url: https://twitter.com/Barchart
- type: x-website
  url: https://www.barchart.com
- type: x-websockets
  url: https://github.com/barchart/barchart-ondemand-client-js
- type: x-website
  url: http://www.barchart.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---