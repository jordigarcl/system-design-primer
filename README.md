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
7. Domain Name System (DNS)
8. Context Delivery Network (CDN)
9. Load Balancer
10. Reverse Proxy
11. Application Layer
12. Database
13. Cache
14. Asynchronism
15. Communication
16. Security

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

### 3. Appendix 

## References
- https://github.com/donnemartin/system-design-primer
