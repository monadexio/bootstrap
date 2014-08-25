# System Architecture

Based on MEAN stack: MongoDB, ExpressJS, AngularJS, and Node.js. Use a
uniform language throughout our stack.

## MongoDB
Key Features
- High Performance

  MongoDB provides high performance data persistence. In particular,
    - Support for embedded data models reduces I/O activity on database system.
    - Indexes support faster queries and can include keys from embedded documents and arrays.

- High Availability

  To provide high availability, MongoDB’s replication facility, called replica sets, provide:
    - automatic failover.
    - data redundancy.

  A replica set is a group of MongoDB servers that maintain the same data
  set, providing redundancy and increasing data availability.

- Automatic Scaling

  MongoDB provides horizontal scalability as part of its core functionality.

    - Automatic sharding distributes data across a cluster of machines.
    - Replica sets can provide eventually-consistent reads for low-latency high throughput deployments.

## ExpressJS
- A simple and robust web application framework for Node.js
- Gives you everything you would expect to build a modern web server
- Middleware, routing, templating, static-files, cookies, mime-types and much much more

## AngularJS
- An extensible client-side application framework
- A swiss army knife of JavaScript MVW goodness
- Data-binding, syncing, templating, components and much, much more

## Payment channels supported
Standard
- UPOP
- ChinaPay
- SndaPay
Express Pay
- UPOP Express Pay
- VISA/MASTER Express Pay
- Wechat build-in channel
- Alipay

## Dashboard
- Livemode and testing
- API Keys

## Application integration
- Prestashop
- 3dcart
