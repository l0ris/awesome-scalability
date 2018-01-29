# Awesome Scalability, Availability, and Stability Back-end Design Patterns
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of selected readings to illustrate Scalability, Availability, and Stability Design Patterns in Back-end Development. Concepts are explained in the articles of notable engineers (Werner Vogels, James Hamilton, Martin Fowler, Robert C. Martin, Tom White, etc) and high quality reference sources (highscalability.com, infoq.com, etc). Case studies are taken from battle-tested systems those are serving millions of users (Netflix, Instagram, Riot Games, LINE, Expedia, etc).

#### What if your Back-end went slow?
> Understand your problems: performance problem (slow for a single user) or scalability problem (fast for a single user but slow under heavy load) by reviewing [design principles](#principles). You can also check some [talks](#talks) of elite engineers from tech giants (Google, Facebook, Netflix, etc) to see how they build and scale their systems.

#### What if your Back-end went down?
> "Even if you lose all one day, you can build all over again if you retain your calm!" - Thuan Pham, CTO at Uber Technologies Inc.

#### Community Power

> Contributions are greatly welcome! You may want to take a look at the [contribution guidelines](CONTRIBUTING.md). If you find this project helpful, please help me share it to more and more people! Thank you very much!

## Contents
- [Principles](#principles)
- [Scalability](#scalability)
- [Availability](#availability)
- [Stability](#stability)
- [Performance](#performance)
- [Other Aspects](#others)
- [Talks](#talks)
- [Books](#books)

## Principles
* [Principles of Chaos Engineering](https://www.usenix.org/conference/srecon17americas/program/presentation/rosenthal)
* [Finding the Order in Chaos](https://www.usenix.org/conference/srecon16/program/presentation/lueder)
* [The Clean Architecture - Robert C. Martin (Uncle Bob)](https://8thlight.com/blog/uncle-bob/2012/08/13/the-clean-architecture.html)
* [The Twelve-Factor App](https://12factor.net/)
* [CAP Theorem and Trade-offs](http://robertgreiner.com/2014/08/cap-theorem-revisited/)
* [CAP Twelve Years Later: How the "Rules" Have Changed (2012) - Eric Brewer, VP of Infrastructure at Google](https://www.infoq.com/articles/cap-twelve-years-later-how-the-rules-have-changed)	
* [Scale Up or Scale Out, What it is and Why You Should Care](https://www.brianjgraf.com/2013/05/17/scalability-scale-up-scale-out-care/)
* [Scaling Up vs Scaling Out: Hidden Costs](https://blog.codinghorror.com/scaling-up-vs-scaling-out-hidden-costs/)
* [ACID and BASE](https://neo4j.com/blog/acid-vs-base-consistency-models-explained/)
* [Blocking/Non-Blocking and Sync/Async](https://blogs.msdn.microsoft.com/csliu/2009/08/27/io-concept-blockingnon-blocking-vs-syncasync/)
* [Why Non-Blocking?](https://techblog.bozho.net/why-non-blocking/)
* [SQL and NoSQL](https://www.upwork.com/hiring/data/sql-vs-nosql-databases-whats-the-difference/)
* [Consistent Hashing - Tom White, author of 'Hadoop: the Definitive Guide'](http://www.tom-e-white.com/2007/11/consistent-hashing.html)
* [Uniform Consistent Hashing](https://medium.com/netflix-techblog/distributing-content-to-open-connect-3e3e391d4dc9)
* [Eventually Consistent - Werner Vogels, CTO at Amazon](https://www.allthingsdistributed.com/2008/12/eventually_consistent.html)
* [Cache is King!](https://www.stevesouders.com/blog/2012/10/11/cache-is-king/)
* [Anti-Caching](http://the-paper-trail.org/blog/paper-notes-anti-caching/)
* [Understand Latency](http://highscalability.com/latency-everywhere-and-it-costs-you-sales-how-crush-it)
* [Architecture Issues When Scaling Web Applications: Bottlenecks, Database, CPU, IO](http://highscalability.com/blog/2014/5/12/4-architecture-issues-when-scaling-web-applications-bottlene.html)	
* [20 Common Bottlenecks](http://highscalability.com/blog/2012/5/16/big-list-of-20-common-bottlenecks.html)
* [Life Beyond Distributed Transactions](https://queue.acm.org/detail.cfm?id=3025012)
* [Relying on Software to Redirect Traffic Reliably at Various Layers](https://www.usenix.org/conference/srecon15/program/presentation/taveira)
* [Advantages and Drawbacks of Microservices](https://cloudacademy.com/blog/microservices-architecture-challenge-advantage-drawback/)
* [Breaking Things on Purpose](https://www.usenix.org/conference/srecon17americas/program/presentation/andrus)
* [Avoid Over Engineering](https://medium.com/@rdsubhas/10-modern-software-engineering-mistakes-bc67fbef4fc8)
* [Scalability Worst Practices](https://www.infoq.com/articles/scalability-worst-practices)
* [Use Solid Technologies - Don’t Re-invent the Wheel - Keep It Simple!](https://medium.com/@DataStax/instagram-engineerings-3-rules-to-a-scalable-cloud-application-architecture-c44afed31406)
* [Performance is a Feature](https://blog.codinghorror.com/performance-is-a-feature/)
* [Make Performance Part of Your Workflow](https://codeascraft.com/2014/12/11/make-performance-part-of-your-workflow/)
* [The Benefits of Server Side Rendering Over Client Side Rendering](https://medium.com/walmartlabs/the-benefits-of-server-side-rendering-over-client-side-rendering-5d07ff2cefe8)
* [Writing Code that Scales](https://blog.rackspace.com/writing-code-that-scales)
* [AWS Do's and Don'ts](https://8thlight.com/blog/sarah-sunday/2017/09/15/aws-dos-and-donts.html)
* [(UI) Design Doesn’t Scale - Stanley Wood, Design Director at Spotify](https://medium.com/@hellostanley/design-doesnt-scale-4d81e12cbc3e)
* [Design for Loose-coupling](http://bulgerpartners.com/how-loosely-coupled-architectures-are-helping-the-modernization-of-legacy-software/)
* [Design for Resiliency](http://highscalability.com/blog/2012/12/31/designing-for-resiliency-will-be-so-2013.html)
* [Design for Self-healing](https://docs.microsoft.com/en-us/azure/architecture/guide/design-principles/self-healing)
* [Design for Scaling Out](https://docs.microsoft.com/en-us/azure/architecture/guide/design-principles/scale-out)
* [Best Practices for Scaling Out](https://blog.openshift.com/best-practices-for-horizontal-application-scaling/)	
* [Design for Evolution](https://docs.microsoft.com/en-us/azure/architecture/guide/design-principles/design-for-evolution)	
* [Learn from Mistakes](http://highscalability.com/blog/2013/8/26/reddit-lessons-learned-from-mistakes-made-scaling-to-1-billi.html)

## Scalability
* [Microservices](https://hackernoon.com/microservices-are-hard-an-invaluable-guide-to-microservices-2d06bd7bcf5d)
	* [Microservices Resource Guide - Martin Fowler, Chief Scientist at ThoughtWorks](https://martinfowler.com/microservices/)
	* [Thinking Inside the Container - Riot Games (8 part series)](https://engineering.riotgames.com/news/thinking-inside-container)
	* [Containerization at Pinterest](https://medium.com/@Pinterest_Engineering/containerization-at-pinterest-92295347f2f3)
	* [The Evolution of Container Usage at Netflix](https://medium.com/netflix-techblog/the-evolution-of-container-usage-at-netflix-3abfc096781b)
	* [Dockerizing MySQL at Uber](https://eng.uber.com/dockerizing-mysql/)
	* [Testing of Microservices at Spotify](https://labs.spotify.com/2018/01/11/testing-of-microservices/)
	* [Organize Monolith Before Breaking it into Services at Weebly](https://medium.com/weebly-engineering/how-to-organize-your-monolith-before-breaking-it-into-services-69cbdb9248b0)
* [Distributed Caching](https://www.wix.engineering/single-post/scaling-to-100m-to-cache-or-not-to-cache)
	* [Write-behind and Write-through](https://docs.oracle.com/cd/E15357_01/coh.360/e15723/cache_rtwtwbra.htm#COHDG5177)
	* [Eviction Policies](http://highscalability.com/blog/2016/1/25/design-of-a-modern-cache.html)
	* [Peer-To-Peer Caching](https://en.wikipedia.org/wiki/P2P_caching)
	* [Distributed Caching at Netflix with EVCache](https://medium.com/netflix-techblog/caching-for-a-global-netflix-7bcc457012f1)
	* [Robust Memcache Traffic Analyzer at Box.com](https://blog.box.com/blog/introducing-memsniff-robust-memcache-traffic-analyzer/)
	* [How Etsy caches: Consistent Hashing and Cache Smearing](https://codeascraft.com/2017/11/30/how-etsy-caches/)
	* [An Analysis of Facebook Photo Caching](https://code.facebook.com/posts/220956754772273/an-analysis-of-facebook-photo-caching/)
* [Distributed Tracking and Tracing](https://www.oreilly.com/ideas/understanding-the-value-of-distributed-tracing)
	* [Tracking Service Infrastructure at Scale at Spotify](https://www.usenix.org/conference/srecon17americas/program/presentation/arthorne)
	* [Distributed Tracing with Pintrace at Pinterest](https://medium.com/@Pinterest_Engineering/distributed-tracing-at-pinterest-with-new-open-source-tools-a4f8a5562f6b)
	* [Analyzing Distributed Trace Data at Pinterest](https://medium.com/@Pinterest_Engineering/analyzing-distributed-trace-data-6aae58919949)
	* [Distributed Tracing at Uber](https://eng.uber.com/distributed-tracing/)
	* [Data Checking at Dropbox](https://www.usenix.org/conference/srecon17asia/program/presentation/mah)
	* [Tracing distributed systems at Showmax](https://tech.showmax.com/2016/10/tracing-distributed-systems-at-showmax/)
* [Distributed Logging](https://blog.treasuredata.com/blog/2016/08/03/distributed-logging-architecture-in-the-container-era/)
	* [The Log: What Every Software Engineer Should Know](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)	
	* [Scalable and reliable log ingestion at Pinterest](https://medium.com/@Pinterest_Engineering/scalable-and-reliable-data-ingestion-at-pinterest-b921c2ee8754)
	* [Building DistributedLog at Twitter: High-performance replicated log service](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2015/building-distributedlog-twitter-s-high-performance-replicated-log-servic.html)
	* [Logging Service with Spark at CERN Accelerator](https://databricks.com/blog/2017/12/14/the-architecture-of-the-next-cern-accelerator-logging-service.html)
	* [Logging and Aggregation at Quora](https://engineering.quora.com/Logging-and-Aggregation-at-Quora)
	* [BookKeeper: Distributed Log Storage at Yahoo](https://yahooeng.tumblr.com/post/109908973316/bookkeeper-yahoos-distributed-log-storage-is)
	* [LogDevice: Distributed Data Store for Logs at Facebook](https://code.facebook.com/posts/357056558062811/logdevice-a-distributed-data-store-for-logs/)
* [Distributed Messaging](https://arxiv.org/pdf/1704.00411.pdf)
	* [Understanding When to use RabbitMQ or Apache Kafka](https://content.pivotal.io/blog/understanding-when-to-use-rabbitmq-or-apache-kafka)
	* [Running Kafka at scale at Linkedin](https://engineering.linkedin.com/kafka/running-kafka-scale)
	* [Delaying Asynchronous Message Processing with RabbitMQ at Indeed](http://engineering.indeedblog.com/blog/2017/06/delaying-messages/)
	* [Real-time Data Pipeline with Kafka at Yelp](https://engineeringblog.yelp.com/2016/07/billions-of-messages-a-day-yelps-real-time-data-pipeline.html)
	* [Audit Kafka End-to-End at Uber (count each message exactly once, audit a message across tiers)](https://eng.uber.com/chaperone/)
	* [Deduplication Techniques](https://en.wikipedia.org/wiki/Data_deduplication)
		* [Exactly-once Semantics are Possible: Here’s How Kafka Does it](https://www.confluent.io/blog/exactly-once-semantics-are-possible-heres-how-apache-kafka-does-it/)
		* [Real-time Deduping at Scale with Kafka-based Pipleline at Tapjoy](http://eng.tapjoy.com/blog-list/real-time-deduping-at-scale)
		* [Delivering Billions of Messages Exactly Once: Deduping at Segment](https://segment.com/blog/exactly-once-delivery/)
* [Distributed Searching](http://nwds.cs.washington.edu/files/nwds/pdf/Distributed-WR.pdf)
	* [Search Architecture of Instagram](https://engineering.instagram.com/search-architecture-eeb34a936d3a)
	* [Search Architecture of eBay](http://www.cs.otago.ac.nz/homepages/andrew/papers/2017-8.pdf)
	* [Nautilus: Travel Search Engine of Expedia](http://blog.expedia.com/expedias-nautilus-travel-search-engine-overview-and-applications/)
	* [Galene: Search Architecture of LinkedIn](https://engineering.linkedin.com/search/did-you-mean-galene)
	* [Search at Slack](https://slack.engineering/search-at-slack-431f8c80619e)
	* [Search Service (Half a Trillion Documents and Query Average Latency < 100ms) at Twitter (2014)](https://blog.twitter.com/engineering/en_us/a/2014/building-a-complete-tweet-index.html)				
* [Distributed Storage](http://highscalability.com/blog/2011/11/1/finding-the-right-data-solution-for-your-application-in-the.html)
	* [In-memory Storage](https://medium.com/@denisanikin/what-an-in-memory-database-is-and-how-it-persists-data-efficiently-f43868cff4c1)
		* [Optimizing Memcached Efficiency at Quora](https://engineering.quora.com/Optimizing-Memcached-Efficiency)
		* [Real-Time Data Warehouse with MemSQL on Cisco UCS](https://blogs.cisco.com/datacenter/memsql)
		* [Moving to MemSQL at Tapjoy: Horizontally Scalable, ACID Compliant, MySQL Compatibility](http://eng.tapjoy.com/blog-list/moving-to-memsql)
	* [Durable Storage (typically Object Storage)](http://www.datacenterknowledge.com/archives/2013/10/04/object-storage-the-future-of-scale-out)
		* [Amazon S3](https://aws.amazon.com/s3/)
			* [Reasons for Choosing S3 over HDFS at Databricks](https://databricks.com/blog/2017/05/31/top-5-reasons-for-choosing-s3-over-hdfs.html)
			* [S3 in the Data Infrastructure at Airbnb](https://medium.com/airbnb-engineering/data-infrastructure-at-airbnb-8adfb34f169c)
			* [Quantcast File System on Amazon S3](https://www.quantcast.com/blog/quantcast-file-system-on-amazon-s3/)
			* [Using S3 in Netflix Chukwa](https://medium.com/netflix-techblog/evolution-of-the-netflix-data-pipeline-da246ca36905)	
		* [Yahoo Cloud Object Store - Object Storage at Exabyte Scale](https://yahooeng.tumblr.com/post/116391291701/yahoo-cloud-object-store-object-storage-at)
		* [Ambry: Distributed Immutable Object Store at LinkedIn](https://www.usenix.org/conference/srecon17americas/program/presentation/shenoy)
		* [Hammerspace: Persistent, Concurrent, Off-heap Storage at Airbnb](https://medium.com/airbnb-engineering/hammerspace-persistent-concurrent-off-heap-storage-3db39bb04472)

* [NoSQL](https://www.thoughtworks.com/insights/blog/nosql-databases-overview)
	* [Key-Value Databases (DynamoDB, Voldemort, Manhattan)](http://highscalability.com/anti-rdbms-list-distributed-key-value-stores)
		* [Scaling Mapbox infrastructure with DynamoDB Streams](https://blog.mapbox.com/scaling-mapbox-infrastructure-with-dynamodb-streams-d53eabc5e972)
		* [Manhattan: Twitter’s distributed key-value database](https://blog.twitter.com/engineering/en_us/a/2014/manhattan-our-real-time-multi-tenant-distributed-database-for-twitter-scale.html)
		* [Sherpa: Yahoo’s distributed NoSQL key-value store](https://yahooeng.tumblr.com/post/120730204806/sherpa-scales-new-heights)
		* [Riak inside Chat Service Architecture at Riot Games](https://engineering.riotgames.com/news/chat-service-architecture-persistence)
	* [Column Databases (Cassandra, HBase, Vertica, Sybase IQ)](https://aws.amazon.com/nosql/columnar/)
		* [Consistent Hashing in Cassandra](https://blog.imaginea.com/consistent-hashing-in-cassandra/)
		* [When NOT to use Cassandra?](https://stackoverflow.com/questions/2634955/when-not-to-use-cassandra)
		* [Storing Images in Cassandra at Walmart Scale](https://medium.com/walmartlabs/building-object-store-storing-images-in-cassandra-walmart-scale-a6b9c02af593)
		* [Cassandra at Instagram](https://www.slideshare.net/DataStax/cassandra-at-instagram-2016)
		* [How Yelp Scaled Ad Analytics with Cassandra](https://engineeringblog.yelp.com/2016/08/how-we-scaled-our-ad-analytics-with-cassandra.html)
		* [How Discord Stores Billions of Messages with Cassandra](https://blog.discordapp.com/how-discord-stores-billions-of-messages-7fa6ec7ee4c7)
	* [Document Databases (MongoDB, CouchDB)](https://msdn.microsoft.com/en-us/magazine/hh547103.aspx)
		* [eBay: Building Mission-Critical Multi-Data Center Applications with MongoDB](https://www.mongodb.com/blog/post/ebay-building-mission-critical-multi-data-center-applications-with-mongodb)
		* [MongoDB at Baidu: Multi-Tenant Cluster Storing 200+ Billion Documents across 160 Shards](https://www.mongodb.com/blog/post/mongodb-at-baidu-powering-100-apps-across-600-nodes-at-pb-scale)
		* [The AWS and MongoDB Infrastructure of Parse (acquired by Facebook)](https://medium.baqend.com/parse-is-gone-a-few-secrets-about-their-infrastructure-91b3ab2fcf71)
		* [Couchbase Ecosystem at LinkedIn](https://engineering.linkedin.com/blog/2017/12/couchbase-ecosystem-at-linkedin)
	* [Graph Databases](https://www.ibm.com/developerworks/library/cl-graph-database-1/index.html)		
		* [Neo4j case studies with Walmart, eBay, AirBnB, NASA, etc](https://neo4j.com/customers/)
		* [FlockDB: Distributed Graph Database for Storing Adjancency Lists at Twitter](https://blog.twitter.com/engineering/en_us/a/2010/introducing-flockdb.html)
		* [JanusGraph: Scalable Graph Database backed by Google, IBM and Hortonworks](https://architecht.io/google-ibm-back-new-open-source-graph-database-project-janusgraph-1d74fb78db6b)
		* [Amazon Neptune](https://aws.amazon.com/neptune/)
	* [Datastructure Databases (Redis, Hazelcast)](https://db-engines.com/en/system/Hazelcast%3BMemcached%3BRedis)
		* [Using Redis To Scale at Twitter](http://highscalability.com/blog/2014/9/8/how-twitter-uses-redis-to-scale-105tb-ram-39mm-qps-10000-ins.html)
		* [Scaling Job Queue with Redis at Slack](https://slack.engineering/scaling-slacks-job-queue-687222e9d100)
		* [Moving persistent data out of Redis at Github](https://githubengineering.com/moving-persistent-data-out-of-redis/)
		* [Storing Hundreds of Millions of Simple Key-Value Pairs in Redis at Instagram](https://engineering.instagram.com/storing-hundreds-of-millions-of-simple-key-value-pairs-in-redis-1091ae80f74c)
		* [Redis in Chat Architecture of Twitch (from 27:22)](https://www.infoq.com/presentations/twitch-pokemon)
	* [Practical NoSQL resilience design pattern for the enterprise (eBay)](https://www.ebayinc.com/stories/blogs/tech/practical-nosql-resilience-design-pattern-for-the-enterprise/)		
* [RDBMS (MySQL, MSSQL, PostgreSQL)](https://www.mysql.com/products/cluster/scalability.html)
	* [MS SQL versus MySQL](https://www.upwork.com/hiring/data/sql-vs-mysql-which-relational-database-is-right-for-you/)
	* [Why SQL is beating NoSQL, and what this means for the future of data](https://blog.timescale.com/why-sql-beating-nosql-what-this-means-for-future-of-data-time-series-database-348b777b847a)
	* [Sharding MySQL at Pinterest](https://medium.com/@Pinterest_Engineering/sharding-pinterest-how-we-scaled-our-mysql-fleet-3f341e96ca6f)
	* [How Airbnb Partitioned Main MySQL Database in Two Weeks](https://medium.com/airbnb-engineering/how-we-partitioned-airbnb-s-main-database-in-two-weeks-55f7e006ff21)
	* [Replication is the Key for Scalability & High Availability](http://basho.com/posts/technical/replication-is-the-key-for-scalability-high-availability/)
	* [How Twitch uses PostgreSQL](https://blog.twitch.tv/how-twitch-uses-postgresql-c34aa9e56f58)
	* [Scaling MySQL-based financial reporting system at Airbnb](https://medium.com/airbnb-engineering/tracking-the-money-scaling-financial-reporting-at-airbnb-6d742b80f040)
	* [Scaling to 100M at Wix: MySQL is a Better NoSQL](https://www.wix.engineering/single-post/scaling-to-100m-mysql-is-a-better-nosql)
	* [Why Uber Engineering Switched from Postgres to MySQL](https://eng.uber.com/mysql-migration/)
	* [Handling Growth with Postgres at Instagram](https://engineering.instagram.com/handling-growth-with-postgres-5-tips-from-instagram-d5d7e7ffdfcb)
	* [Scaling the Analytics Database (Postgres) at TransferWise](http://tech.transferwise.com/scaling-our-analytics-database/)
* [Time Series Database (TSDB)](https://www.influxdata.com/time-series-database/)
	* [Time Series Data: Why and How to Use a Relational Database instead of NoSQL](https://blog.timescale.com/time-series-data-why-and-how-to-use-a-relational-database-instead-of-nosql-d0cd6975e87c)
	* [Beringei: High-performance Time Series Storage Engine at Facebook](https://code.facebook.com/posts/952820474848503/beringei-a-high-performance-time-series-storage-engine/)	
	* [Atlas: In-memory Dimensional Time Series Database at Netflix](https://medium.com/netflix-techblog/introducing-atlas-netflixs-primary-telemetry-platform-bd31f4d8ed9a)
	* [Heroic: Time Series Database at Spotify](https://labs.spotify.com/2015/11/17/monitoring-at-spotify-introducing-heroic/)
	* [Building a Scalable Time Series Database on PostgreSQL](https://blog.timescale.com/when-boring-is-awesome-building-a-scalable-time-series-database-on-postgresql-2900ea453ee2)
	* [Scaling Time Series Data Storage at Netflix](https://medium.com/netflix-techblog/scaling-time-series-data-storage-part-i-ec2b6d44ba39)
* [HTTP Caching (Reverse Proxy, CDN)](https://developer.mozilla.org/en-US/docs/Web/HTTP/Caching)
	* [Reverse Proxy (Nginx, Varnish, Squid, rack-cache)](https://www.mertech.com/overview-reverse-proxying/)
	* [Stop Worrying and Love the Proxy](https://blog.turbinelabs.io/how-we-learned-to-stop-worrying-and-love-the-proxy-89af98fabaf8)
	* [Playing HTTP Tricks with Nginx](https://www.elastic.co/blog/playing-http-tricks-nginx)
	* [Using CDN to Improve Site Performance at Coursera](https://building.coursera.org/blog/2015/07/09/improving-coursera-global-site-performance-a-head-to-head-cdn-battle-with-production-traffic/)
	* [Strategy: Caching 404s Saved 66% On Server Time at The Onion](http://highscalability.com/blog/2010/3/26/strategy-caching-404s-saved-the-onion-66-on-server-time.html)
	* [Increasing Application Performance with HTTP Cache Headers](https://devcenter.heroku.com/articles/increasing-application-performance-with-http-cache-headers)
* [Load Balancing](https://blog.vivekpanyam.com/scaling-a-web-service-load-balancing/)
	* [Introduction to Modern Network Load Balancing and Proxying](https://blog.envoyproxy.io/introduction-to-modern-network-load-balancing-and-proxying-a57f6ff80236)
	* [Load Balancing infrastructure to support more than 1.3 billion users at Facebook](https://www.usenix.org/conference/srecon15europe/program/presentation/shuff)
	* [DHCPLB: Open Source Load Balancer for DHCP at Facebook](https://code.facebook.com/posts/1734309626831603/dhcplb-an-open-source-load-balancer/)
	* [Load Balancing with Eureka at Netflix](https://medium.com/netflix-techblog/netflix-shares-cloud-load-balancing-and-failover-tool-eureka-c10647ef95e5)
	* [Load Balancing at Yelp](https://engineeringblog.yelp.com/2017/05/taking-zero-downtime-load-balancing-even-further.html)
	* [Load Balancing at Github](https://githubengineering.com/introducing-glb/)
	* [Consistent Hashing to Improve Load Balancing at Vimeo](https://medium.com/vimeo-engineering-blog/improving-load-balancing-with-a-new-consistent-hashing-algorithm-9f1bd75709ed)
	* [UDP Load Balancing at 500 pixel](https://developers.500px.com/udp-load-balancing-with-keepalived-167382d7ad08)	
* [Concurrency](http://joeduffyblog.com/2016/11/30/15-years-of-concurrency/)
	* [Message-Passing Concurrency](https://link.springer.com/chapter/10.1007/978-3-642-35170-9_11)
	* [Software Transactional Memory](https://dl.acm.org/citation.cfm?id=3037750)
	* [Dataflow Concurrency](http://www.marketwired.com/press-release/java-concurrency-and-scalability-platform-akka-celebrates-fifth-anniversary-1928674.htm)
	* [Shared-State Concurrency](https://common-lisp.net/project/ssc/darcs/spec/specification.pdf)
	* [Concurrency series by Larry Osterman (Principal SDE at Microsoft)](https://social.msdn.microsoft.com/Profile/Larry%2bOsterman%2b%5BMSFT%5D/activity)
		* [Part 8 – Concurrency for scalability](https://blogs.msdn.microsoft.com/larryosterman/2005/02/28/concurrency-part-8-concurrency-for-scalability/)
		* [Part 9 - APIs that enable scalable programming](https://blogs.msdn.microsoft.com/larryosterman/2005/03/02/concurrency-part-9-apis-that-enable-scalable-programming/)
		* [Part 10 - How do you know if you’ve got a scalability issue?](https://blogs.msdn.microsoft.com/larryosterman/2005/03/03/concurrency-part-10-how-do-you-know-if-youve-got-a-scalability-issue/)
		* [Part 11 – Hidden scalability issues](https://blogs.msdn.microsoft.com/larryosterman/2005/03/04/concurrency-part-11-hidden-scalability-issues/)
		* [Part 12 – Hidden scalability issues (cont)](https://blogs.msdn.microsoft.com/larryosterman/2005/03/07/concurrency-part-12-hidden-scalability-issues-part-2/)
	* [Concurrency with Erlang](http://learnyousomeerlang.com/the-hitchhikers-guide-to-concurrency)
		* [Erlang in WhatsApp](https://blog.whatsapp.com/196/1-million-is-so-2011)
		* [Erlang in Riot Chat Server](https://engineering.riotgames.com/news/chat-service-architecture-servers)
		* [How Discord Scaled Elixir to Five Millions Concurrent Users](https://blog.discordapp.com/scaling-elixir-f9b8e1e7c29b)
		* [Mnesia: A Distributed DBMS Rooted in Concurrency](https://www.developer.com/db/article.php/3864331/Mnesia-A-Distributed-DBMS-Rooted-in-Concurrency.htm)
		* [Mesia and CAP](https://medium.com/@jlouis666/mnesia-and-cap-d2673a92850)		
* [Parallel Computing](https://blogs.msdn.microsoft.com/ddperf/2009/05/02/are-we-taking-advantage-of-parallelism/)
	* [SPMD (Single Program Multiple Data): The Genetic Pattern](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2012/EECS-2012-186.html)
	* [Master/Worker Pattern](https://docs.gigaspaces.com/sbp/master-worker-pattern.html)
	* [Loop Parallelism Pattern: Extracting parallel tasks from loops](https://www.cs.umd.edu/class/fall2001/cmsc411/projects/unroll/main.htm)
	* [Fork/Join Pattern: Good for recursive data processing](http://highscalability.com/learn-how-exploit-multiple-cores-better-performance-and-scalability)
	* [Map-Reduce: Born for Simplified Data Processing on Large Clusters](http://static.googleusercontent.com/media/research.google.com/en/us/archive/mapreduce-osdi04.pdf)
	* [On the Death of Map-Reduce - Henry Robinson, Cloudera](http://the-paper-trail.org/blog/the-elephant-was-a-trojan-horse-on-the-death-of-map-reduce-at-google/)
	* [Server-side Optimization to Parallelize the Rendering of Web Pages at Yelp](https://engineeringblog.yelp.com/2017/07/generating-web-pages-in-parallel-with-pagelets.html)
* [Event-Driven Architecture](https://martinfowler.com/articles/201701-event-driven.html)
	* [Messaging](https://www.ibm.com/support/knowledgecenter/en/SSAW57_8.5.5/com.ibm.websphere.nd.doc/ae/cjt1004_.html)
		* [Publish-Subscribe](https://aws.amazon.com/pub-sub-messaging/)
			* [Autoscaling Pub-Sub Consumers at Spotify](https://labs.spotify.com/2017/11/20/autoscaling-pub-sub-consumers/)
			* [Pulsar: Pub-Sub Messaging at Scale at Yahoo](https://yahooeng.tumblr.com/post/150078336821/open-sourcing-pulsar-pub-sub-messaging-at-scale)
			* [Wormhole: Pub-Sub system at Facebook (2013)](https://code.facebook.com/posts/188966771280871/wormhole-pub-sub-system-moving-data-through-space-and-time/)
			* [Pub-Sub in Chatting Architecture on LINE LIVE](https://engineering.linecorp.com/en/blog/detail/85)
		* [Point-To-Point and Its Differences from Pub-Sub](https://www.journaldev.com/9743/jms-messaging-models)
		* [Store-Forward](https://docs.oracle.com/cd/E13222_01/wls/docs91/saf_admin/overview.html)
		* [Request-Reply](https://docs.tibco.com/pub/ftl/4.3.0/doc/html/GUID-A64ABED1-682E-4E1D-A94A-5590CB91B9BB.html)
	* [Enterprise Service Bus](http://www.oracle.com/technetwork/articles/soa/ind-soa-esb-1967705.html)
	* [Domain Events](https://martinfowler.com/eaaDev/DomainEvent.html)
		* [Domain Events: Simple and Reliable Solution](http://enterprisecraftsmanship.com/2017/10/03/domain-events-simple-and-reliable-solution/)
	* [Event Stream Processing](https://www.sas.com/en_us/insights/articles/big-data/3-things-about-event-stream-processing.html)
		* [Kafka Streams on Heroku](https://blog.heroku.com/kafka-streams-on-heroku)
		* [Bullet: Forward-Looking Query Engine for Streaming Data at Yahoo](https://yahooeng.tumblr.com/post/161855616651/open-sourcing-bullet-yahoos-forward-looking)
		* [Benchmarking Streaming Computation Engines at Yahoo](https://yahooeng.tumblr.com/post/135321837876/benchmarking-streaming-computation-engines-at)
	* [Event Sourcing](https://martinfowler.com/eaaDev/EventSourcing.html)
		* [Event Sourced Architectures for High Availability](https://www.infoq.com/presentations/Event-Sourced-Architectures-for-High-Availability)
		* [Event Sourcing and Stream Processing at Scale](https://martin.kleppmann.com/2016/01/29/event-sourcing-stream-processing-at-ddd-europe.html)
		* [Scaling Event Sourcing for Netflix Downloads](https://www.infoq.com/presentations/netflix-scale-event-sourcing)
		* [Scaling Event-Sourcing at Jet.com](https://medium.com/@eulerfx/scaling-event-sourcing-at-jet-9c873cac33b8)
	* [Command & Query Responsibility Segregation (CQRS)](https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs)	
* [Distributed Machine Learning](https://arxiv.org/pdf/1512.09295.pdf)
	* [Scalable Deep Learning Platform On Spark In Baidu](https://www.slideshare.net/JenAman/scalable-deep-learning-platform-on-spark-in-baidu)
	* [Horovod: Uber’s Open Source Distributed Deep Learning Framework for TensorFlow](https://eng.uber.com/horovod/)	
	* [Scaling Gradient Boosted Trees for Click-Through-Rate Prediction at Yelp](https://engineeringblog.yelp.com/2018/01/building-a-distributed-ml-pipeline-part1.html)
	* [TensorFlowOnSpark: Distributed Deep Learning on Big Data Clusters at Yahoo](https://yahooeng.tumblr.com/post/157196488076/open-sourcing-tensorflowonspark-distributed-deep)
	* [CaffeOnSpark: Distributed Deep Learning on Big Data Clusters at Yahoo](https://yahooeng.tumblr.com/post/139916828451/caffeonspark-open-sourced-for-distributed-deep)
	* [AIOps in Practice at Baidu](https://www.usenix.org/conference/srecon17asia/program/presentation/qu)
	* [Learning with Privacy at Scale - Differential Privacy Team, Apple](https://machinelearning.apple.com/2017/12/06/learning-with-privacy-at-scale.html)

## Availability
* [Failover](http://cloudpatterns.org/mechanisms/failover_system)
	* [The Evolution of Global Traffic Routing and Failover](https://www.usenix.org/conference/srecon16/program/presentation/heady)
	* [Testing for Disaster Recovery Failover Testing](https://www.usenix.org/conference/srecon17asia/program/presentation/liu_zehua)
* [Replication](https://m.alphasights.com/a-primer-on-database-replication-381b319cd032)
	* [Master-Slave](https://engineering.bitnami.com/articles/enabling-additional-nodes-to-bitnami-mysql-with-replication.html)
	* [Tree Replication](https://link.springer.com/chapter/10.1007/3-540-44863-2_47)
	* [Master-Master](http://sabbour.me/highly-available-and-scalable-master-master-mysql-on-azure-virtual-machines/)
	* [Buddy Replication](https://developer.jboss.org/wiki/JBossCacheBuddyReplicationDesign)
* [NodeJS High Availability at Yahoo](https://yahooeng.tumblr.com/post/68823943185/nodejs-high-availability)
* [Every Day Is Monday in Operations - LinkedIn (11 part series)](https://www.linkedin.com/pulse/introduction-every-day-monday-operations-benjamin-purgason)
* [Practical Guide to Monitoring and Alerting with Time Series at Scale](https://www.usenix.org/conference/srecon17americas/program/presentation/wilkinson)
* [How Robust Monitoring Powers High Availability for LinkedIn Feed](https://www.usenix.org/conference/srecon17americas/program/presentation/barot)
* [Architectural Patterns for High Availability - Adrian Cockcroft, Director of Architecture at Netflix](https://www.infoq.com/presentations/Netflix-Architecture)

## Stability
* [Circuit Breaker](https://martinfowler.com/bliki/CircuitBreaker.html)
	* [Circuit Breaking in Distributed Systems](https://www.infoq.com/presentations/circuit-breaking-distributed-systems)
	* [Circuit Breakers for Distributed Services at LINE](https://engineering.linecorp.com/en/blog/detail/76)
	* [Applying Circuit Breaker to Channel Gateway at LINE](https://engineering.linecorp.com/en/blog/detail/78)
	* [Circuit Breaker for Scaling Containers](https://f5.com/about-us/blog/articles/the-art-of-scaling-containers-circuit-breakers-28919)
* [Always use timeouts (if possible)](https://www.javaworld.com/article/2824163/application-performance/stability-patterns-applied-in-a-restful-architecture.html)
* [Let it crash/Supervisors: Embrace failure as a natural state in the life-cycle of the application](http://erlang.org/doc/design_principles/sup_princ.html)
* [Crash early: An error now is better than a response tomorrow](http://odino.org/better-performance-the-case-for-timeouts/)
* [Bulkheads: Partition and tolerate failure in one part](https://skife.org/architecture/fault-tolerance/2009/12/31/bulkheads.html)
* [Steady state: Always put logs on separate disk](https://docs.microsoft.com/en-us/sql/relational-databases/policy-based-management/place-data-and-log-files-on-separate-drives)
* [Throttling: Maintain a steady pace](http://www.sosp.org/2001/papers/welsh.pdf)
* [Multi-clustering: Improving Resiliency and Stability of a Large-scale Monolithic API Service at LinkedIn](https://engineering.linkedin.com/blog/2017/11/improving-resiliency-and-stability-of-a-large-scale-api)

## Performance
* [Web Performance: Cache Efficiency Exercise at Facebook](https://code.facebook.com/posts/964122680272229/web-performance-cache-efficiency-exercise/)
* [Improving Performance with Background Data Prefetching at Instagram](https://engineering.instagram.com/improving-performance-with-background-data-prefetching-b191acb39898)
* [Compression Techniques to Solve Network I/O Bottlenecks at eBay](https://www.ebayinc.com/stories/blogs/tech/how-ebays-shopping-cart-used-compression-techniques-to-solve-network-io-bottlenecks/)
* [Optimizing Web Servers for High Throughput and Low Latency at Dropbox](https://blogs.dropbox.com/tech/2017/09/optimizing-web-servers-for-high-throughput-and-low-latency/)
* [Boosting Site Speed Using Brotli Compression at LinkedIn](https://engineering.linkedin.com/blog/2017/05/boosting-site-speed-using-brotli-compression)
* [Linux Performance Analysis in 60.000 Milliseconds at Netflix](https://medium.com/netflix-techblog/linux-performance-analysis-in-60-000-milliseconds-accc10403c55)
* [Optimizing 360 Photos at Scale at Facebook](https://code.facebook.com/posts/129055711052260/optimizing-360-photos-at-scale/)

## Others
* [Distributed Git Server at Palantir](https://medium.com/@palantir/stemma-distributed-git-server-70afbca0fc29)
* [Configuration Management for Distributed Systems (using GitHub and cfg4j) at Flickr](https://code.flickr.net/2016/03/24/configuration-management-for-distributed-systems-using-github-and-cfg4j/)
* [Seagull: Distributed System that Helps Running > 20 Million Tests Per Day at Yelp](https://engineeringblog.yelp.com/2017/04/how-yelp-runs-millions-of-tests-every-day.html)
* [Cloud Bouncer: Distributed Rate Limiting at Yahoo](https://yahooeng.tumblr.com/post/111288877956/cloud-bouncer-distributed-rate-limiting-at-yahoo)
* [Scalable gaming patterns on AWS (Sep 2017)](https://d0.awsstatic.com/whitepapers/aws-scalable-gaming-patterns.pdf)
* [Building a Modern Bank Backend at Monzo](https://monzo.com/blog/2016/09/19/building-a-modern-bank-backend/)
* [Selecting a cloud provider at Etsy](https://codeascraft.com/2018/01/04/selecting-a-cloud-provider/)
* [Architecture of Tripod (Flickr’s Backend)](https://yahooeng.tumblr.com/post/157200523046/introducing-tripod-flickrs-backend-refactored)
* [Syscall Auditing at Scale at Slack](https://slack.engineering/syscall-auditing-at-scale-e6a3ca8ac1b8)

## Talks
* [Talks on Efficiency, Reliability, and Scaling - James Hamilton, Vice President and Distinguished Engineer at AWS](http://mvdirona.com/jrh/work/)
* [Building Real Time Infrastructure at Facebook - Jeff Barber and Shie Erlich, Software Engineer at Facebook](https://www.usenix.org/conference/srecon17americas/program/presentation/erlich)
* [Building Reliable Social Infrastructure for Google - Marc Alvidrez, Senior Manager at Google](https://www.usenix.org/conference/srecon16/program/presentation/alvidrez)
* [How Google Does Planet-Scale for Planet-Scale Infra - Melissa Binde, SRE Director for Google Cloud Platform](https://www.youtube.com/watch?v=H4vMcD7zKM0)
* [Netflix Guide to Microservices - Josh Evans, Director of Operations Engineering at Netflix](https://www.youtube.com/watch?v=CZ3wIuvmHeM&t=2837s)
* [Achieving Rapid Response Times in Large Online Services - Jeff Dean, Google Senior Fellow](https://www.youtube.com/watch?v=1-3Ahy7Fxsc)
* [How We've Scaled Dropbox - Kevin Modzelewski, Back-end Engineer at Dropbox](https://www.youtube.com/watch?v=PE4gwstWhmc)
* [Lessons of Scale at Facebook - Bobby Johnson, Director of Engineering at Facebook](https://www.youtube.com/watch?v=QCHiNEw73AU)
* [Scaling Instagram Infrastructure - Lisa Guo, Instagram Engineering](https://www.youtube.com/watch?v=hnpzNAPiC0E)
* [Scaling Twitter Core Infrastructure - Yao Yue, Staff Software Engineer at Twitter](https://www.youtube.com/watch?v=6OvrFkLSoZ0)
* [Scaling Pinterest - Marty Weiner, Pinterest’s founding engineer](https://www.youtube.com/watch?v=jQNCuD_hxdQ&list=RDhnpzNAPiC0E&index=11)
* [Scaling Spotify Data Infrastructure - Matti (Lepistö) Pehrs, Spotify](https://www.youtube.com/watch?v=cdsfRXr9pJU)
* [Scaling Uber's Backend by Breaking Everything - Matt Ranney, Chief Systems Architect at Uber](https://www.youtube.com/watch?v=nuiLcWE8sPA)
* [Scaling Slack - Bing Wei, Software Engineer (Infrastructure) at Slack](https://www.infoq.com/presentations/slack-scalability)

## Books
* [Google Site Reliability Engineering (Online - Free)](https://landing.google.com/sre/book.html)
* [Distributed Systems for Fun and Profit (Online - Free)](http://book.mixu.net/distsys/)
* [Beyond the Twelve-Factor App - Exploring the DNA of Highly Scalable, Resilient Cloud Applications (Free)](http://www.oreilly.com/webops-perf/free/beyond-the-twelve-factor-app.csp)
* [Chaos Engineering - Building Confidence in System Behavior through Experiments (Free)](http://www.oreilly.com/webops-perf/free/chaos-engineering.csp?intcmp=il-webops-free-product-na_new_site_chaos_engineering_text_cta)
* [The Art of Scalability](http://theartofscalability.com/)
* [Designing Data-Intensive Applications](https://dataintensive.net/)
* [Web Scalability for Startup Engineers](https://www.goodreads.com/book/show/23615147-web-scalability-for-startup-engineers)
* [Scalability Rules: 50 Principles for Scaling Web Sites](http://scalabilityrules.com/)

## Special Thanks
* Jonas Bonér, CTO at Lightbend, for the [original inspiration](https://www.slideshare.net/jboner/scalability-availability-stability-patterns)

## License

[![CC-BY](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg)](https://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).