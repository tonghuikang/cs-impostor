# How to be a CS impostor

After failing multiple technical interviews for being clueless on the computer science concepts, I realised that I needed to be better impostor.

Collaborators are welcome and much needed, because I do not have the required background (my degree is not Computer Science). I do not know if I am even asking the correct questions.

* auto-gen TOC:
{:toc}

### About

This repository compiles answers optimised for interviews

- The purpose of your answer is to demostrate knowledge of the subject.
- You should not explain everything.
- The answer should be at most three sentences. They will ask for more if they want.
- You should know what you are talking about. Concede early if you do not know more. References will be provided if you want to elaborate.
- To show your experience and make your answer unique, you may want to elaborate with an example on how you applied the concepts in question.




### Useful resources

- [GeeksForGeeks articles](https://www.geeksforgeeks.org/most-asked-computer-science-subjects-interview-questions-in-amazon-microsoft-flipkart/). They tend to explain everything, here I want to summarise the answer that it is good for interview.
- [donnemartin's System Design Primer](https://github.com/donnemartin/system-design-primer) This describes how to prepare to interview questions on designing large-scale systems.
- [Tech Interview Handbook](https://yangshun.github.io/tech-interview-handbook/) How to apply for job, and algorithms.
- [MIT CSAIL Missing Semester](https://missing.csail.mit.edu/) Introduces tools for software development which is hardly covered in courses.
- Syllabus and course objectives of the courses you have taken. It should be a good summary of what you have learnt throughout the course.



## Topics

(Should be ordered in some reasonable order)



### Networking

What happens when you access a website?

- DNS lookup for IP address, and then?



What are some networking protocols?

- (no idea - UDP?)



### Cybersecurity

How does secure communciation happen through https?

- Security and encryption process - Authentication with Certificate Authority with asymmetric encryption, symmetric for secure communication



What is the difference between symmetric and asymmetric encryption?

- Symmetric encryption uses the same keys to encrypt and decrypt, 




### Operating Systems

What is the difference between process and threads?

- A process may have multiple threads. Different processes do not share memory, different threads of a process share a memory



### Databases

How do we index a database and why?

- Databases use index to allow faster access to an entry in the database. indexing is done with balance binary search tree to allow O(log n) acceess to the element. you may index the table on multiple columns. the downside of using indexes is storage cost, as well as increase time when modifying the table



What is the difference between MySQL, PostgresSQL

- No idea



(What is the deal with NoSQL?)



### Frontend

(Vue, React, ?)



Describe the difference between React and React Native

- TBC



(Mobile browser and desktop browser)




### Data Science

Why do we split the data into training set, validation set and test set?

- TBC



Why do we do cross validation?

- TBC



What is the difference between parameters and hyperparameters?

- TBC



Explain the bias-variance tradeoff

- TBC



How do you decide whether to include an additional feature into your prediction?

- TBC



(Linear regression, Logistic regression)





### Machine Learning

Describe a simple neural network

- Neurons, weights, bias, activation function



What is the difference between RNN, LSTM and GRU?

- TBC



What is batch normalisation and what problem does it solve?
- TBC



What is the vanishing gradient problem and how it is resolved?
- TBC



What is the attention mechanism?
- TBC



What are transformers?

- TBC



What is the difference between GPT, BERT and XLNet?
- TBC



What is the difference between (the historical and latest CNNs, e.g. MobileNet)?

- TBC



What is the difference between random forest, XGBoost, LightGBM and CatBoost?

- TBC



What does a Graph Neural Network do, and how does it work?

- TBC



Describe the difference between various word vector embeddings.

- TBC



(Reinforcement learning question)



(Conditional Random Field)







### Unclassified

Different stacks and its merits

- LAMP, MEAN



Development processes (?) (Agile, Lean Manufacturing, Design Thinking, Six Sigma, Lean Startup, DevOps)



Continuous Integration, Continuous Delivery



Containers and Kubernetes



How does the git source control process work (fetch, pull, add, commit, push)?



Benefits of on-prem, and on cloud, and hybrid setup?



Kafka, Airflow, etc