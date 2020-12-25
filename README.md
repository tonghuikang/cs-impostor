# How to be a CS impostor

After failing multiple technical interviews for being clueless on the computer science concepts, I realised that I needed to be better impostor.

Collaborators are welcome and much needed, because I do not have the required background (my degree is not Computer Science). 

I do not know if I am even asking the correct questions.

* auto-gen TOC:
{:toc}



### How do you use this

This repository compiles answers optimised for interviews

- The purpose of your answer is to demostrate knowledge of the subject, rather than to teach the concept. You do not need to explain everything from scratch.
- You should keep your answer concise, at around three sentences. You should not explain everything you know. They will ask for more if they want. There is likely many other questions to go through, and you might need to code too.
- You should know what you are talking about. It is better to concede when you do not know further.
- To show your experience and make your answer unique, you may want to elaborate with an example on how you applied the concepts in question.



### What should this contain

- No opinions. While we should have opinions (ethics, predictions, positions), you have to figure them out and justify them yourself.
- References. This will serve as attribution, and also further reading material to understand the topic.
- Good questions. This should contain questions that can be asked in a technical interview. It should not be a history quiz or a numbers trivia.
- Relevant questions. The knowledge should have direct technical application for either a software engineer or a machine learning practitioner.



#### Excluded topics

- Algorithms (please refer to other resources to prepare for the coding component of the interview)
- Mathematics and Theory of Computation
- Computation Structures (Arithmetric Logic Unit) - will this ever be asked in an interview?
- Robotics
- Game Design and Development
- Graphics and Image Processing
- Data Analysis and Information Visualisation



### Useful resources

- [GeeksForGeeks articles](https://www.geeksforgeeks.org/most-asked-computer-science-subjects-interview-questions-in-amazon-microsoft-flipkart/). They tend to explain everything, here I want to summarise the answer that it is good for interview.
- [donnemartin's System Design Primer](https://github.com/donnemartin/system-design-primer) This describes how to prepare to interview questions on designing large-scale systems.
- [Tech Interview Handbook](https://yangshun.github.io/tech-interview-handbook/) How to apply for job, and algorithms.
- [MIT CSAIL Missing Semester](https://missing.csail.mit.edu/) Introduces tools for software development which is hardly covered in courses.
- [Programmer competency matrix](https://sijinjoseph.netlify.app/programmer-competency-matrix/) An outline of the the different competency levels of each domain of computer science.
- [Attempted comparison of CS courses between Singapore universities](https://www.reddit.com/r/SGExams/comments/g3yion/uni_computer_science_curricula/)
- Syllabus and course objectives of the courses you have taken. It should be a good summary of what you have learnt throughout the course.
- Job descriptions of whatever jobs you are applying for



## Computer Science Topics

(Should be ordered in some reasonable order)




### Networking

[SUTD 50.012 Networks](https://istd.sutd.edu.sg/undergraduate/courses/50012-networks)

What happens when you access a website?

- DNS lookup for IP address, and then?

(packet switching, layered architectures, TCP/IP, physical layer, error control, window flow control, local area networks (Ethernet, Token Ring; FDDI), network layer, congestion control, quality of service, multicast, network programming interfaces, networked applications)






### Cybersecurity

[SUTD 50.042 Foundations of Cybersecurity](https://istd.sutd.edu.sg/undergraduate/courses/50042-foundations-cybersecurity)

[SUTD 50.020 Network Security]( https://istd.sutd.edu.sg/undergraduate/courses/50020-network-security)

[SUTD 50.044 System Security](https://istd.sutd.edu.sg/undergraduate/courses/50044-system-security)

(The course objectives above lacked keywords for me to extract)



What are the objectives of Cybersecurity?

-  Confidentiality, Integrity and Availability



How does secure communciation happen through https?

- Security and encryption process - Authentication with Certificate Authority with asymmetric encryption, symmetric for secure communication



What is the difference between symmetric and asymmetric encryption?

- Symmetric encryption uses the same keys to encrypt and decrypt, 



How does your computer ensure that the website that you are visiting is authentic?

- Certificate authority



Describe how the following attack works, and how to project against it

- Cross-Site Request Forgery (CSRF)
- Cross-site scripting (XSS)
- Distributed Denial of Service (DDoS)
- SQL injection






### Operating Systems

[SUTD 50.005 Computer System Engineering](https://istd.sutd.edu.sg/undergraduate/courses/50005-computer-system-engineering)

What is the difference between process and threads?

- A process may have multiple threads. Different processes do not share memory, different threads of a process share a memory



- Process management and multithreaded programming
- Process scheduling, synchronization, deadlock
- Memory management, file system, and I/O system





### Databases

[SUTD 50.043 Database and Big Data Systems](https://istd.sutd.edu.sg/undergraduate/courses/50043-database-and-big-data-systems)

How do we index a database and why?

- Databases use index to allow faster access to an entry in the database. indexing is done with balance binary search tree to allow O(log n) acceess to the element. you may index the table on multiple columns. the downside of using indexes is storage cost, as well as increase time when modifying the table



What is the difference between MySQL, PostgresSQL

- No idea





(What is the deal with NoSQL?)

Hadoop and MapReduce





### Distributed Systems

[50.041 Distributed Systems and Computing](https://istd.sutd.edu.sg/undergraduate/courses/50041-distributed-systems-computing)



What is the CAP theorem and how is it applied?

- Consistency, Availability, Partition tolerance





1. Build models of distributed systems.
2. Prototype distributed software systems.
3. Build distributed algorithms using industry-strength programming language.
4. Build algorithms to analyse the correctness of distributed systems.
5. Prototype software and systems to manage files and records in a distributed environment.
6. Build algorithms to analyse and test possible faults in distributed systems.
7. Build techniques to recover from faults in distributed systems.
8. Build techniques at the level of supervisory software to support distributed applications.



Normal and byzantine faults



(Go programming language and why it is suitable?)




### Frontend Technologies

(Vue, React, ?)






### Mobile Technologies

Outline the procedure to publish an application on Google Play Store, and on iOS App Store

- TBC



(Differences between the mobile browser and desktop browser)



### Blockchain

[SUTD 50.037 Blockchain Technology]()

What is blockchain?

- TBC




What are some applications of blockchain?

- TBC



### System Design

Questions from the System Design Primer

Explain the following tradeoffs
- Performance vs scalability
- Latency vs throughput
- Availability vs consistency



### Unclassified

Different stacks and its merits

- LAMP, MEAN



Development processes (?) (Agile Scrum, Lean Manufacturing, Design Thinking, Six Sigma, Lean Startup, DevOps)



Continuous Integration, Continuous Delivery



Containers and Kubernetes



How does the git source control process work (fetch, pull, add, commit, push)?



Benefits of on-prem, and on cloud, and hybrid setup?



Cloud offerings and how to choose between them



Serverless versus monolithic, advantages and disadvantages



Kafka, Airflow, etc



The data pipeline?



UI/UX, QA



(Primal-dual formulation? Seems like an important concept in optimisation but I do not understand)



(Programming languages, choice and design?)



Bluetooth technologies, and TraceTogether



Ruby on Rails, Sidekiq, Redis



Terraform



Describe the difference between L1, L2 and L3 support



