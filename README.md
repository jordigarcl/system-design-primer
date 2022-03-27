# System Design Interview Primer
System design is a broad topic. There is a vast amount of resources scattered throughout the web on system design principles. This repo is an **organized collection** of resources to help you learn how to build systems at scale.

## Motivation
**Prep for the system design interview**

In addition to coding interviews, system design interviews are a required component of the technical interview process at many tech companies.

Practice common system design interview questions and compare your results with sample solutions: discussions, code, and diagrams.

**Learn how to design large-scale systems**

Learning how to design scalable systems will help you become a better engineer.

-----------
## Index
1. Interview Prep
2. System Design Topics
3. Appendix
-----

## 1. Interview Prep
1. [Study guide](#11-study-guide)
2. [How to approach a system design interview question](#12-how-to-approach-a-system-design-interview)
3. [System design interview questions, **with solutions**](#1-3-system-design-interview-questions-with-solutions)
4. [Object-oriented design interview questions, **with solutions**](#1-4-object-oriented-design-interview-questions-with-solutions)

### 1.1. Study Guide
You **don't need** **to know** ***everyhing*** here for interviews. More experienced candidates are generally expected to know more about system design. Architects or team leads might be expected to know more than individual contributors. Top tech companies are likely to have one or more design interview rounds.

Start broad and go deeper in a few areas. **It helps to know a little about various key system design topics**. Adjust the following guide based on your timeline, experience, what positions you are interviewing for, and which companies you are interviewing with.

- **Short timeline** - Aim for **breadth** with system design topics.  Practice by solving **some** interview questions.
* **Medium timeline** - Aim for **breadth** and **some depth** with system design topics.  Practice by solving **many** interview questions.
* **Long timeline** - Aim for **breadth** and **more depth** with system design topics.  Practice by solving **most** interview questions.

| | Short | Medium | Long |
|---|---|---|---|
| Read through the [System design topics](#index-of-system-design-topics) to get a broad understanding of how systems work | :+1: | :+1: | :+1: |
| Read through a few articles in the [Company engineering blogs](#company-engineering-blogs) for the companies you are interviewing with | :+1: | :+1: | :+1: |
| Read through a few [Real world architectures](#real-world-architectures) | :+1: | :+1: | :+1: |
| Review [How to approach a system design interview question](#how-to-approach-a-system-design-interview-question) | :+1: | :+1: | :+1: |
| Work through [System design interview questions with solutions](#system-design-interview-questions-with-solutions) | Some | Many | Most |
| Work through [Object-oriented design interview questions with solutions](#object-oriented-design-interview-questions-with-solutions) | Some | Many | Most |
| Review [Additional system design interview questions](#additional-system-design-interview-questions) | Some | Many | Most |

### 1.2. How to approach a system design interview
The system design interview is an **open-ended conversation**.  You are expected to **lead it**.

You can use the following steps to guide the discussion. To help solidify this process, work through the [System design interview questions with solutions](#system-design-interview-questions-with-solutions) section using the following steps.

- Step 0: Back of the envelope calculations
- Step 1: Outline use cases, constraints, and assumptions
- Step 2: Create a high level design
- Step 3: Design core components
- Step 4: Scale the design

**Step 0: Back-of-the-envelope calculations**

You might be asked to do some estimates by hand. Refer to the [Appendix](#) for the following resources:

* [Use back of the envelope calculations](http://highscalability.com/blog/2011/1/26/google-pro-tip-use-back-of-the-envelope-calculations-to-choo.html)
* [Powers of two table](#powers-of-two-table)
* [Latency numbers every programmer should know](#latency-numbers-every-programmer-should-know)

**Step 1: Outline use cases, constraints, and assumptions**

- Gather requirements and scope the problem.
- Ask questions to clarify use cases and constraints.
- Discuss assumptions.

Examples:
* Who is going to use it?
* How are they going to use it?
* How many users are there?
* What does the system do?
* What are the inputs and outputs of the system?
* How much data do we expect to handle?
* How many requests per second do we expect?
* What is the expected read to write ratio?

**Step 2: Create a high level design**

- Outline a high-level design with all the important components.
- Sketch the main components and connections
- Justify your ideas

**Step 3: Design core components**

- Dive into details for each core component

**Step 4: Scale the design**

- Identify and address bottlenecks, given the constraints.
- Discuss potential solutions and trade-offs.
- Address bottlenecks using principles of scalable system design

**Source(s) and further reading**

Check out the following links to get a better idea of what to expect:

* [How to ace a systems design interview](https://www.palantir.com/2011/10/how-to-rock-a-systems-design-interview/)
* [The system design interview](http://www.hiredintech.com/system-design)
* [Intro to Architecture and Systems Design Interviews](https://www.youtube.com/watch?v=ZgdS0EUmn70)
* [System design template](https://leetcode.com/discuss/career/229177/My-System-Design-Template)

### 1.3. System design interview questions with solutions
Common system design interview questions with sample discussions, code, and diagrams.

Solutions linked to content in the `solutions/` folder.

| Question | |
|---|---|
| Design Pastebin.com (or Bit.ly) | [Solution](solutions/system_design/pastebin/README.md) |
| Design the Twitter timeline and search (or Facebook feed and search) | [Solution](solutions/system_design/twitter/README.md) |
| Design a web crawler | [Solution](solutions/system_design/web_crawler/README.md) |
| Design Mint.com | [Solution](solutions/system_design/mint/README.md) |
| Design the data structures for a social network | [Solution](solutions/system_design/social_graph/README.md) |
| Design a key-value store for a search engine | [Solution](solutions/system_design/query_cache/README.md) |
| Design Amazon's sales ranking by category feature | [Solution](solutions/system_design/sales_rank/README.md) |
| Design a system that scales to millions of users on AWS | [Solution](solutions/system_design/scaling_aws/README.md) |
| Add a system design question | [Contribute](#contributing) |

### 1.4. Object-oriented design interview questions with solutions
Common object-oriented design interview questions with sample discussions, code, and diagrams.

Solutions linked to content in the `solutions/` folder.

>**Note: This section is under development**

| Question | |
|---|---|
| Design a hash map | [Solution](solutions/object_oriented_design/hash_table/hash_map.ipynb)  |
| Design a least recently used cache | [Solution](solutions/object_oriented_design/lru_cache/lru_cache.ipynb)  |
| Design a call center | [Solution](solutions/object_oriented_design/call_center/call_center.ipynb)  |
| Design a deck of cards | [Solution](solutions/object_oriented_design/deck_of_cards/deck_of_cards.ipynb)  |
| Design a parking lot | [Solution](solutions/object_oriented_design/parking_lot/parking_lot.ipynb)  |
| Design a chat server | [Solution](solutions/object_oriented_design/online_chat/online_chat.ipynb)  |
| Design a circular array | [Contribute](#contributing)  |
| Add an object-oriented design question | [Contribute](#contributing) |


## 2. System Design topics
1. System Design Review
2. Performance vs scalability
3. Latency vs throughput
4. Availability vs Consistency
5. Consistency patterns
6. Availability patterns
7. Availability in numbers
8. Domain Name System (DNS)
9. Context Delivery Network (CDN)
10. Load Balancer
11. Reverse Proxy
12. Application Layer
13. Database
14. Cache
15. Asynchronism
16. Communication
17. Security

### 2.1. System Design Review
New to system design? First, you'll need a basic understanding of common principles, learning about what they are, how they are used, and their pros and cons.

- Step 1: Review the scalability video lecture
- Step 2: Review the scalability article

**Step 1: Review the scalability video lecture**

[Scalability Lecture at Harvard](https://www.youtube.com/watch?v=-W9F__D3oY4)

Topics covered:
* Vertical scaling
* Horizontal scaling
* Caching
* Load balancing
* Database replication
* Database partitioning

**Step 2: Review the scalability article**

[Scalability article](http://www.lecloud.net/tagged/scalability/chrono)

Topics covered:
* [Clones](http://www.lecloud.net/post/7295452622/scalability-for-dummies-part-1-clones)
* [Databases](http://www.lecloud.net/post/7994751381/scalability-for-dummies-part-2-database)
* [Caches](http://www.lecloud.net/post/9246290032/scalability-for-dummies-part-3-cache)
* [Asynchronism](http://www.lecloud.net/post/9699762917/scalability-for-dummies-part-4-asynchronism)

### 2.2. Performance vs Scalability
A service is **scalable** if it results in increased **performance** in a manner proportional to resources added. Generally, increasing performance means serving more units of work, but it can also be to handle larger units of work, such as when datasets grow.<sup><a href=http://www.allthingsdistributed.com/2006/03/a_word_on_scalability.html>1</a></sup>

Another way to look at performance vs scalability:

* If you have a **performance** problem, your system is slow for a single user.
* If you have a **scalability** problem, your system is fast for a single user but slow under heavy load.

**Source(s) and further reading**
* [A word on scalability](http://www.allthingsdistributed.com/2006/03/a_word_on_scalability.html)
* [Scalability, availability, stability, patterns](http://www.slideshare.net/jboner/scalability-availability-stability-patterns/)

### 2.3. Latency vs Throughput
- **Latency** is the time to perform some action or to produce some result.
- **Throughput** is the number of such actions or results per unit of time.

Generally, you should aim for **maximal throughput** with **acceptable latency**.

**Source(s) and further reading**

* [Understanding latency vs throughput](https://community.cadence.com/cadence_blogs_8/b/sd/archive/2010/09/13/understanding-latency-vs-throughput)

### 2.4. Availability vs Consistency
**CAP theorem**

<p align="center">
  <img src="images/bgLMI2u.png">
  <br/>
  <i><a href=http://robertgreiner.com/2014/08/cap-theorem-revisited>Source: CAP theorem revisited</a></i>
</p>

In a distributed computer system, you can only support two of the following guarantees:

* **Consistency** - Every read receives the most recent write or an error
* **Availability** - Every request receives a response, without guarantee that it contains the most recent version of the information
* **Partition Tolerance** - The system continues to operate despite arbitrary partitioning due to network failures

Networks aren't reliable, so you'll need to support partition tolerance. You'll need to make a **software tradeoff** between **consistency** and **availability**:

- CP - consistency and partition tolerance
- AP - availability and partition tolerance

**CP - consistency and partition tolerance**

Waiting for a response from the partitioned node might result in a **timeout error**. CP is a good choice if your business needs require atomic reads and writes.

**AP - availability and partition tolerance**

Responses return the most readily available version of the data available on any node, which **might not be the latest**. Writes might take some time to propagate when the partition is resolved.

AP is a good choice if the business needs allow for [eventual consistency](#eventual-consistency) or when the system needs to continue working despite external errors.

**Source(s) and further reading**

* [CAP theorem revisited](http://robertgreiner.com/2014/08/cap-theorem-revisited/)
* [A plain english introduction to CAP theorem](http://ksat.me/a-plain-english-introduction-to-cap-theorem)
* [CAP FAQ](https://github.com/henryr/cap-faq)
* [The CAP theorem](https://www.youtube.com/watch?v=k-Yaq8AHlFA)

### 2.5. Consistency patterns
With multiple copies of the same data, we are faced with options on how to synchronize them so clients have a consistent view of the data. Recall the definition of consistency from the [CAP theorem](#cap-theorem) - Every read receives the most recent write or an error.

- Weak consistency
- Eventual consistency
- Strong consistency

**Weak consistency**

After a write, reads may or may not see it. A best effort approach is taken.

This approach is seen in systems such as memcached.  Weak consistency works well in real time use cases such as VoIP, video chat, and realtime multiplayer games.  For example, if you are on a phone call and lose reception for a few seconds, when you regain connection you do not hear what was spoken during connection loss.

**Eventual consistency**

After a write, reads will eventually see it (typically within milliseconds). Data is replicated **asynchronously**.

This approach is seen in systems such as DNS and email. Eventual consistency works well in highly available systems.

**Strong consistency**
After a write, reads will see it.  Data is replicated **synchronously**.

This approach is seen in file systems and RDBMSes. Strong consistency works well in systems that need transactions.

**Source(s) and further reading**
* [Transactions across data centers](http://snarfed.org/transactions_across_datacenters_io.html)

### 2.6. Availability patterns
There are two complementary patterns to support high availability: **fail-over** and **replication**.

- Fail-over
- Replication

### Fail-over
**Active-passive fail-over** 

In **active-passive fail-over** (AKA master-slave fail-over), heartbeats are sent between the active and the passive server on standby. If the heartbeat is interrupted, the passive server takes over the active's IP address and resumes service.

The length of downtime is determined by whether the passive server is already running in 'hot' standby or whether it needs to start up from 'cold' standby. Only the active server handles traffic.

**Active-active fail-over**

In **active-active fail-over** (AKA master-slave fail-over), both servers are managing traffic, spreading the load between them.

If the servers are public-facing, the DNS would need to know about the public IPs of both servers. If the servers are internal-facing, application logic would need to know about both servers.

**Fail-over disadvantages**

* Fail-over adds more hardware and additional complexity.
* There is a potential for loss of data if the active system fails before any newly written data can be replicated to the passive.

### Replication
This topic is further discussed in the [Database](#database) section:

* [Master-slave replication](#master-slave-replication)
* [Master-master replication](#master-master-replication)

### 2.7. Availability in numbers
Availability is often quantified by uptime (or downtime) as a percentage of time the service is available.  Availability is generally measured in number of 9s--a service with 99.99% availability is described as having four 9s.

**99.9% availability - three 9s**

| Duration            | Acceptable downtime|
|---------------------|--------------------|
| Downtime per year   | 8h 45min 57s       |
| Downtime per month  | 43m 49.7s          |
| Downtime per week   | 10m 4.8s           |
| Downtime per day    | 1m 26.4s           |

**99.99% availability - four 9s**

| Duration            | Acceptable downtime|
|---------------------|--------------------|
| Downtime per year   | 52min 35.7s        |
| Downtime per month  | 4m 23s             |
| Downtime per week   | 1m 5s              |
| Downtime per day    | 8.6s               |

#### Availability in-parallel vs in-sequence

If a service consists of multiple components prone to failure, the service's overall availability depends on whether the components are in sequence or in parallel.

**In-sequence**

Overall availability decreases when two components with availability < 100% are in sequence:

```
Availability (Total) = Availability (Foo) * Availability (Bar)
```

If both `Foo` and `Bar` each had 99.9% availability, their total availability in sequence would be 99.8%.

**In-parallel**

Overall availability increases when two components with availability < 100% are in parallel:

```
Availability (Total) = 1 - (1 - Availability (Foo)) * (1 - Availability (Bar))
```

If both `Foo` and `Bar` each had 99.9% availability, their total availability in parallel would be 99.9999%.

### 2.8. Domain Name System (DNS)

<p align="center">
  <img src="images/IOyLj4i.jpg">
  <br/>
  <i><a href=http://www.slideshare.net/srikrupa5/dns-security-presentation-issa>Source: DNS security presentation</a></i>
</p>

A Domain Name System (DNS) translates a domain name such as www.example.com to an IP address.

DNS is hierarchical, with a few authoritative servers at the top level.  Your router or ISP provides information about which DNS server(s) to contact when doing a lookup.  Lower level DNS servers cache mappings, which could become stale due to DNS propagation delays.  DNS results can also be cached by your browser or OS for a certain period of time, determined by the [time to live (TTL)](https://en.wikipedia.org/wiki/Time_to_live).

* **NS record (name server)** - Specifies the DNS servers for your domain/subdomain.
* **MX record (mail exchange)** - Specifies the mail servers for accepting messages.
* **A record (address)** - Points a name to an IP address.
* **CNAME (canonical)** - Points a name to another name or `CNAME` (example.com to www.example.com) or to an `A` record.

Services such as [CloudFlare](https://www.cloudflare.com/dns/) and [Route 53](https://aws.amazon.com/route53/) provide managed DNS services.  Some DNS services can route traffic through various methods:

* [Weighted round robin](https://www.g33kinfo.com/info/round-robin-vs-weighted-round-robin-lb)
    * Prevent traffic from going to servers under maintenance
    * Balance between varying cluster sizes
    * A/B testing
* [Latency-based](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html#routing-policy-latency)
* [Geolocation-based](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html#routing-policy-geo)

### Disadvantage(s): DNS

* Accessing a DNS server introduces a slight delay, although mitigated by caching described above.
* DNS server management could be complex and is generally managed by [governments, ISPs, and large companies](http://superuser.com/questions/472695/who-controls-the-dns-servers/472729).
* DNS services have recently come under [DDoS attack](http://dyn.com/blog/dyn-analysis-summary-of-friday-october-21-attack/), preventing users from accessing websites such as Twitter without knowing Twitter's IP address(es).

### Source(s) and further reading

* [DNS architecture](https://technet.microsoft.com/en-us/library/dd197427(v=ws.10).aspx)
* [Wikipedia](https://en.wikipedia.org/wiki/Domain_Name_System)
* [DNS articles](https://support.dnsimple.com/categories/dns/)




### 3. Appendix 

## References
- https://github.com/donnemartin/system-design-primer
