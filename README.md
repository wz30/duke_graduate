# duke_graduate
The repo includes duke course materials and my peronsal suugestions, and track what I learned and achieved since joined Duke. 

### Spring Semester 2022
- no classes since i satisfied all the requirments and choose to graduate with project/thesis.
- Auditing danyang's seminar class: Data Center systems(https://courses.cs.duke.edu/spring22/compsci590.4/). Read many classic paper which onctains three categories.
  - data center networking
  - machine leanring system
  - system 
- working on the project
  - extend work on Lightning(https://github.com/wz30/lightning): distributed lightning: master/worker model with hashing slots.
- UCLA with Yuval Tamir(https://web.cs.ucla.edu/~tamir/)

### Winter Break 2021
- socket fuzzing reserach

### Fall Semester 2021
- CS 514 computer network
  - Midterm exam is harder than final exam. The exam is testing if you really understand the concept, not mechanically remember the concept. Quite different from Tyler's computer security 
  - My project: analysis on various TCP congestion algorithm.
  - Homeworks are useful materials to study the key points of the lectures
  - taught by Bruce Maggs and Shane Zhang
- CS 550 computer architecture 
  - taught by Daniel Sorin
- CS 590 secure software system
  - taught by Mattew Lentz
- Academic presentation by Brad
- TA in 201 Data structure
- Intuit full time return offer

### Summer Semester 2021
- Summer internship in Intuit(IDLM team)
  - 1st project: graphql Linter project
    - First stage: build a tool to check schema before runtime.
    - Second stage: deploy a container to host such tool and serving the GraphQL Schema Playground webiste. User can gain the best practice from the website.
  - I learned Kubernates by myself through a real example: sentiment analysis. 
  - 2nd Project: Migration from IKS1 to IKS2 (Intuit Kubernates Services)
    - this is a devops task
    - tech: jenkins peipeline, ArgoCD, Kubernates
- Research: network hint 
  - figure out the better way to manage the traffic flow.
- Learning distributed system
  - Now I am focusing on Raft <img src="https://github.com/raft/logo/blob/master/annie-solo.png" alt="Raft Logo" width="30" height="30"/>. 
    - passed 2A
- Learning distributed System by Mark from Cambridge.

### Spring Semester 2021
- edge computing: empower IoT and cloud computing. Edge node are like the middle layer between IoT and cloud server
  - Me and my partner work on the research project: practical data cleaning in Federated Learning.
  - We are required to read many papers and prepare for reading quiz for each paper.
- ECE 568 robust server software
  - 1st project: django to create rider share web app. 
  - 2nd project: web cache proxy server (using multithread, lock and socket programming)
    - cache overview: https://www.mnot.net/cache_docs/#ABOUT
    - good tutorial about socket programming: http://beej.us/guide/bgnet/html/#select
      - recv can receive header or header+contents. it depends
    - mocklab to customize the response header and contents: https://app.mocklab.io/mock-apis/l7wwd/stubs/54f6eb4b-e621-44ba-96bc-9903ccbb4b4a
  - 3nd project: stock exchange server software: TA will test the propgram in details. Another requirement is loading testing.
  - final project: mini UPS and mini AMAZON. Google protocol buffer is a hard part. Testing is also hard.
  - Midterm is hard sicne we have short time to complete and there are 7 questions. The exam is testing your basic and deep knowledge on the topics. In addition, how to apply the knowledge is another requiremnt for the exam.
  - Final exam is similar to Midterm exam but with more time. It focues more on security topic. Not hard one. 
  - What I learned from this class:
    - how to create a robust server software in various aspects?
    - Class assignment involves lots of codings and takes more time than I thought. Expertise on the programming language/framework is a prerequisite.
- interview class(1.5 credit taught by Owen): leetcode and hackrank problem
- writing class: problem-solution based paper and topic are field related.
- TA CS 201: quite a lot of logistic works. 

- Until 4/5/2021, I am not doing very well in this semester and I just figure out why that would happen. The main reason is that I made myself super busy and that hurts my confidence. TA in 201 is not a good choice for me since it takes up lots up time to grade the homework and ECE 568 projects take more time. Anyway, I need to catch up where I left. 

### Winter break(two months or more)
- Since school ends Fall early, we have two months winter break ever. It is the longest one ever.
- I had an ambitious and detailed plan but it did not work very well.
  - keep working on the research every week but not really productive since I was stuck on this and did not yield any good outputs. Vicious cycle begins. BTW, the research topic is about container and networking. it is a good and a promising area. However, I did not have enough knowledge on that. 
  - OSTEP book: three easy pieces book. Finished around 20 or less chapters. It is a great book to learn and start operating system.
  - first couple chapters of Linux programming intereface.
  - leetcode problem , not a lot.
  - ski once and that was a good experience 
  - container and k8s learning. 
  - Teaching Charles and Cindy every week.
- Overall, it is not a productive winter break and did not work a lot every day. Thera are couple improvements. 
  - workout and shower are the best and feasible way to recover from "Pandenmic mood"

### Fall Semster 2020
- machine leaning in CS department
- computer security in ECE
- Introduction to AI in CS
- Algorithms in real world undergrad courses in CS
- SLIM - network research

#### Intro to AI
- final exam: Since COVID 19, it is a 3 hout exam. And the problem is quite comprehensive, including all the core parts taught in class. 
  - submodular
  - HMM: computer viterbi, forward, backward.
  - Baynes Net: 
    - best case and worst case to compute p(XiXj) in terms of time complexity. 
    - reduce 3SAT to problem "in baysian network, at most two parents, is p(x)>0"
  - Linear sperable: given specific linear funtion such as w1x1+w2x2+w3x3 + w4 >0 , check if given formula is linear seperable or not. E.g. X1 or (X2 and X3)
  - Using Baynes net as linear classfier and derive the expression to compute the label
  - ML: understand what trend of plot when the factors change?
    - learning rate is too high/low
    - iteration is not enough
    - training set is too small
    - stuck on local optimal
