# Big Data in Education
Tong Wang and Yeyi Ma  |  Hid: fa18-523-73 and fa18-523-74  |  Email: wangton@iu.edu and yeyima@umail.iu.edu

## Abstract

The advancement of technology has affected education in a big way. In recent times, the educators and administrators mainly rely on the Student Information Systems (SISs), Learning Management Systems (LMSs), and Admissions Management Systems to streamline classroom, school and campus operations[@fa18-523-73-John2015]. Therefore, as institutions continue to adopt such systems, user data is generated, which helps the education stakeholders including the parents to make more informed decisions on how the learning process can be improved. As a result[@fa18-523-73-Jan2017], highlights that big data has fundamentally changed the way education is offered, and institutions that invest in the big data and successfully derive value from their data will have a distinct advantage over others. Moreover[@fa18-523-73-Ben2017] anticipates that in the near future there will be a performance gap between the institutions with big data systems and those that have not implemented such systems. This is because as time goes by, more relevant data will be generated, and the emerging technologies and digital channels will offer better acquisition and delivery mechanisms. For instance, teachers can mine learning patterns to see how students master specific subjects and experimental designs. Therefore, this paper analyzes how big data is relevant in the education system. 

## Introduction

Today, many organizations are collecting, storing, and analyzing massive amounts of data. This data is commonly referred to as “big data” because of its volume, the velocity with which it arrives and the variety of forms it takes. Therefore, big data can be described as the process which is used to convert continuous, analog information into discrete, digital and machine reliable format. Examples of big data include web data, text data, time and location data, smart grid, and social network data. Such data can be utilized in educational institutions by using the data-driven approaches that make it possible to study learning in real-time and offer systematic feedback to students and teachers[@fa18-523-73-Jan2017]. As a result, it is crucial to explore how the big data is used to mine learning information for insights regarding student performance and learning approaches.  

## Forms of Big Data in Education institution

### A.	Administrative Data
These type of data refers to the demographic, behavioral, and achievement data collected through schools, government agencies, and their contractors. It is obtained by sampling many participants, which can be longitudinally at prescribed, or regular intervals. In most cases, this type of data is made up by attendance records, test scores, transcripts, and surveys. Examples of the administrative data that can be taken as big data include international test scores, a national assessment of educational progress data, and the behavior data that is collected by the U.S. Department of Education’s Civil Rights Data Collection.

### B.	Learning Process Data

They are continuous or near-continuous, fine-grained records, mostly in the form of digital interactions of students behaviors to illuminate learning processes. The learning process data is considered big data since it involves many participants and a large number of variables in regards to a single person. Examples of learning process include online assessments and courses such as the massive open online courses. 

## The Value of Systematic, Real-Time Data

The use of a computerized system in schools helps the instructors to assess the learning process in real-time. Therefore, by the use of data mining and analytic data software, it is possible to get the immediate feedback in regards to how the learning process is taking place. In the process, the analytic software analyzes the underlying patterns, which help advice on the best practices to undertake for improving or maintaining high performance. An example of the application of the real-time data is in Connected Chemistry that enables students to understand more in-depth the key concepts in molecular theory and gasses[@fa18-523-73-Ben2017]. Therefore, the use of mining and analytic software allows the teachers to mine learning patterns to analyze how the students understand the various areas of chemistry.

Moreover, Joseph Beck and Jack Mostow are known individuals who have examined the benefits of the big data in education. In their experimentation, they applied the intelligent tutor software to study how the students comprehend a story. In the process, they analyzed the reading time, word knowledge, reading mistakes, and the help requests. Beck and Mostow concluded that when students re-read an old story, it assists them understands the words better than reading a new story. 

The other example that showcases how big data relates to education is research carried out by James Theroux of the University of Massachusetts at Amherst. The study focused on students who did average courses, aiming to analyze their perceptions of the uses of online learning compared to the traditional approach. Theroux found out that majority of the students preferred learning via online platforms against the conventional methods. Their preference was mainly because it is a modern method that relates to them. Therefore, the big data technologies can help the institutional faculties to assess the degree to which the students understand the various concepts when learning via online as to other methods. Similarly, the same issue was raised by scholars Robert Perkins and Margaret McKnight of 139 who also concluded that most students prefer using online platforms for leaning as they enjoyed their collaborative and interactive nature[@fa18-523-73-Ben2017]. 

Therefore, the big data is very applicable in schools. For instance, the data collected in real-time can help evaluate the performance of a learning process. The data-driven approaches make it possible to study learning in real-time and offer regular feedback to students and teachers[@fa18-523-73-Jan2017]. One advantage of the real-time data is that it provides more accurate results than other methods since the data is not manipulated or distorted before it is analyzed. Thus, schools need to have learning analytics modes to scrutinize the learning process in real-time to identify areas of improvements. 

## Learning Analytics

In recent times, learning analytics has become an area of research and application. However, unlike the traditional data mining, it draws on a broader array of academic disciplines, incorporating concepts and techniques from information science and sociology. Therefore, the approach primarily focuses on the analysis and reporting of the data. In other words, it aims to look at the application of known methods to answer the crucial questions that affect the performance in schools. Thus, learning analytics can monitor and predict student’s learning performance and brings out the potential issues that the administration needs to address. 

## Requirements

When establishing the requirement of the big data implementation, it is important to adopt a user-center design approach. It is an appropriate method rather than specifying the elements at the beginning for various reasons. According to Williamson[@fa18-523-73-Ben2017], when requirements are collected at the beginning of the project, it may result in later problems in the system development. On the other hand, a user-centered approach enables the development team to establish the communication between users and developers and to gather different requirements on each side. However, when determining the conditions for big data implementation, the procedures are guided by ISO/IEC/IEEE 42010:2011 “Systems and software engineering- Architecture description.” The following are various requirements that need to be established to implement the system successfully.

### 1.	Prediction

The first requirement of big data in school is to develop a model that can help infer a single aspect of the data. For instance, it can assist detect students behaviors when they are involved in activities such as gaming, engaging in off-task behavior. Moreover, the predicting model is also applied to study the behavior of the students in an online learning environment by examining their participation in discussion forums and taking practice tests. Therefore, it is important to have a prediction model to forecast and understand student educational outcomes such as success on posttests after tutoring. 

### 2.	Clustering

The second requirement needs one to find data points that can assist in grouping the collected information. For instance, one can group the students based on their learning difficulties and interaction patterns. For example, in an online learning set-up, the analytics can examine the student’s cognitive interview and also how they post in the discussion board. 

### 3.	Relationship Mining

It involves establishing the relationship between variables in a dataset and then creating the rules to be used in later stages. For example, it is important to identify how students within a specific cluster relate. One of the methods used is the association rule mining, which assists in determining the behaviors students. The other method applied to discover relationship is sequential pattern mining which aids in capturing the connections between occurrences of subsequent events. For instance, it is used in detecting students regressing to make errors in mechanics when they are writing with more complex and critical thinking techniques. 

## Architecture

When designing big-data applications, one needs to have particular methods, tools, and technologies that can handle data efficiently from the initial stage of data collection to the final stage of the interpretation. As a result, a meaningful big data architecture should consider the characteristics of the data extracted. For this project, the architecture is divided into two main section: data management and data analytics. The data management process acquire, govern, integrate, secure and store data that is prepared to be used in data-analytics methods. The data management system is composed of five different categories: distributed file system, cluster management, data store, governance and security, and data ingestion. On the other hand, data analytics involves data modeling, analyzing and interpreting to transform raw data into valuable knowledge. It is divided into distributed data, processing and programming, visualization, data analysis, and pre-processing data components. 

### Data Management

#### Distributed File System (DFS) 
As shown in the diagram above, DFS is the lowest level of the architecture. It is used for the storage and maintains large amounts of data across multiple nodes of commodity hardware. However, it is designed in such a way that it conforms to master and slave node architecture. 

#### Cluster Management 
The components help in deploying, scheduling and orchestrating the jobs across the other parts of the architecture to ensure there is a readily available and highly scalable computing infrastructure.

#### Distributed Data Processing and Programming 
It is used to process the big amount of batch data and millions of data in real time.

#### Data Store  
It is used for the storage of the diverse and large number of data generated throughout the architecture. To increases the efficiency of the architecture, it is important to have a distributed, scalable, schema-free and fault-tolerant data stores.

#### Visualization 
Visualization entails representing the massive amount of data in graphical formats for easy interpretation. 

#### Data analysis 
Data analysis is the process of deploying analytic data software to analyze the raw data and present useful, meaningful information to the end users. Therefore, an analytic model is used to infer knowledge by finding patterns and drawing conclusions with the aid of specialized tools and algorithms. 

#### Data pre-processing 
This step ensures that the data stored and used for interpretation is reliable. During this stage, the data is cleaned to eliminate noises, errors, or incomplete data to improve the overall success of data analysis. 

#### Governance and Security 
These entails the rules laid out to ensure the data is secure. Within the big data architecture, there exist several governance policies. For instance, Apache Atlas provides a scalable and extensible set of core foundational governance services. On the other hand, Apache Ranger gives the details of how to successfully implement a secure data framework to monitor and manage the data across the system. 

#### Data Ingestion 
It helps in transferring data from outside sources to the internal systems within the architecture. Since the big data involves a large volume of data and velocity characteristics of big data, data ingestion needs to be resilient and fault-tolerant. 

#### Application  
The application layer helps present the analyzed data to the under-users. An example of application is Nutch, which is a production-ready web crawler. 

In conclusion, the architecture represents a key part of the big data. For that reason, it is crucial for an educational institution to try and create a unified information architecture, to ensure it leverages all types of data. Moreover, a well-designed architecture promotes a unified vision for information management and analytics. Therefore, it is important to get a better understanding of the role of the implementation of the big data, which would provide a better context for deriving requirements for architecture. 

## Implementation

### Factors to Consider Before Implementing the Big Data

The big data has become a game changer in shaping the future of education. However, certain factors need to be considered before applying the big data project.

#### 1.	Understanding Industry Point-of-View on Big Data 
The education institutions needs first to assess the capabilities and trends to sidestep mistakes made in other sectors, particularly in the business world. For instance, it is advisable that before an institution or organization implement the big data to first study reports from well-regarded publications such as IDC and Forrester's.  

#### 2.	Developing a Proof of Concept (PoC) 
It is helpful first to create a business case that showcases all the values and the costs associated with the implementations of the big data.

#### 3.	Understanding the Current Tools and Technology 
After the institution approves of continuing with the implementation of the big data, the next step entails analyzing the available tools and technology that can help meet architectural guidelines requirements.  

#### 4.	Developing the Measures of Successful Big Data 
It is important to have a target that will measure the benefits of the implementation of the big data system.

### Steps of Successful implementation of the Big Data

#### 1.	Identification of the Goals 

Both in business and education world requires one first to determine the purpose of the big data. For instance, in an education set-up, the institutional management needs to clarify whether the big data is to increase the efficiency of the learning process, improve institution’s marketing, or to improve the overall performance of the institution. Therefore, based on the purpose, then it is easy to choose a methodology, hire employees, and select the right sources of data.

#### 2.	Leverage a Proven Big Data Strategy

There exist four prove strategies, which are based on the objective of the big data as well as the availability of the data. 

##### i.	Performance Management  
This approach involves applying the transactional data such as the client purchase history and their turnover. However, this approach is not suitable for an education set up.

##### ii.	Data Exploration 

This strategy primarily relies on the use of data mining and research to obtain solutions to the various problems an organization might be facing. In the process, the analytic teams can identify new segments of data.

##### iii.	Social Analytics 

Social analytics approach employs the non-transaction data on social media platforms such as Facebook, Twitter, and Instagram. It is an applicable method in an education setting since most of the students use such platforms as their modes of communication.  

##### iv.	Decision Science 

This approach relies on the analysis of non-transactional data such as online discussion forums. Therefore, it utilizes text and sentiment analysis to determine students/customer’s opinions in regards to new services and schemes. 

#### 3.	Identify infrastructural changes 

To meet the requirements of the big data, the institution may need to change some of its infrastructures. For instance, the traditional storage mediums might not facilitate the running of complex algorithms and analysis. It may also involve the reconfiguration of the hardware platform to meet the new computation needs. 

#### 4.	Training of the Staffs

It is crucial that all the staffs working within the institutions are conversant with the big data. Therefore, at the start, it is important to hire outside consulting team to guide on how best to utilize the big data. Moreover, it is essential to hire new strong system programmers who can work in a parallel processing environment and a network communications specialist. 

## Benchmarking

Big data benchmarks are used to evaluate and compare the performance of big data systems and architecture. A successful benchmarking entails five steps: planning, generating data, generate tests, execution, and analysis and evaluation. 

The process provides a realistic and accurate measure of the big data systems and therefore, it can enable one to make efficient decision-making. For instance, a successful big data support education institutions to make decisions for planning system features, tuning system configuration and validate the deployment strategies. The following are the various steps of benchmarking:

### 1.	Planning 

One needs to make a plan on how the big data benchmarking will take place. Therefore, it is important to first come up with the goals of the benchmarking process. For instance, it should be able to generate application-specific workloads and tests such that it’s easier to draw meaningful conclusions. Also, in the planning tests, it is imperative to lay down the methodology to use in the benchmarking process. 

### 2.	Generating Data

There are four properties associated with big data: volume, velocity, variety, and veracity. Therefore, benchmarking should aim to cover those areas, and thus, it is crucial to apply real-world data or generates synthetic data for application-specific workloads. However, in most cases, most real-owners are not willing to share their real-data because of the security issues. Consequently, in big data benchmarks, the consensus is generated synthetic data as inputs of workloads by real data sets.

### 3.	Generating Tests

In big-data benchmarks, one should first identify the typical workload behaviors for an application domain. Besides, it is important to take into considerations the diversity of workloads to cover different types of application domains, and at the same time to generate tests based on the workloads automatically. However, due to complexities involved in big data, it is challenging to develop big data benchmarks that reflect the real workload cases.

### 4.	Execution

The execution stage needs to address various challenges. For instance, the big-data benchmarks need to adapt to different data formats. For example, the text data can be stored in the form of text files, web pages or pdf. The data also needs to be portable to represent different software stacks to provide a fully functional solution. Besides, the execution must reflect the user’s experiences in using benchmarks. 

## Conclusion

From the discussion, it is a crucial time for the education institution to implement big data. Massive quantities of educational data can now be stored, analyzed and shared. For instance, various big-data algorithms can help track individual students in school and as a result keep detailed information about their academic performance, behavior, and educational needs. Moreover, the big-data systems can help improve educational services by assisting the teachers to analyze what students know and what techniques are most useful for each pupil. Furthermore, technologies such as data mining and data analytics can provide fast feedback to students and teachers about their academic performance. 

However, irrespective of the benefits associated with the big data, several challenges need to be addressed. For instance, the massive amounts of data generated by the big-data systems require much larger storage systems. To overcome such a problem, the data specialists need databases that do not use the traditional SQL based queries. The other challenge is in regards to the analysis as data is generated in different structure and size, and the study of the data may consume a lot of time and resources. Moreover, it is challenging reporting the analyzed information since when a large amount of data are involved, the traditional reports become difficult to interpret by human beings. Therefore, it requires useful tools and techniques that can address such challenges. An example includes the analytics software which can provide an in-depth analysis of some education patterns and extract valuable knowledge from them. 
















