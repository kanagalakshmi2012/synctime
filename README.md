# queries
**It's a metric used to measure the number of requests a system receives and processes per second.**

OPTIMIZING READ PERFORMANCE IN DISTRIBUTED KEY-VALUE STORES USING SERIALIZABLE CONSISTENCY\
Author: \
Published In : \
Publication Date:\
E-ISSN:\
Impact Factor:\
Link:

**Abstract**:\
ETCD is a distributed key-value store that ensures high availability and strong consistency using the Raft consensus protocol. It supports two types of read operations: linearizable reads, which guarantee the most up-to-date data but with higher latency, and serializable reads, which offer lower latency with slightly stale data. This paper focuses on improving performance issues caused by linearizable reads by leveraging serializable read operations. By balancing consistency and efficiency, the approach enhances ETCD’s scalability and responsiveness. This makes ETCD more adaptable for diverse distributed system needs.

**Key Contributions:** 
* **Algorithm Development** \
  Designed and optimized Serializable Read methodology targetting high number of query processing per second.
* **Performance Comparison** \
  Conducted bench marking between Linearizable Read qps and Serializable Read qps.
* **Reserach Leadership**
  Led the research and technical implementation , focusing on advancing distributed database through algorithm innovation.

**Relevance & Real-World Impact**
* **Kubernetes infrastructure optimization:**\
    Enhances distributed key-value store performance by improving the number of queries to process per second.
* **Query Processing Improvement:** \
* **Academic Recognition :** \
* **Educational Impact:** \

**Experimental Results (Summary)** \


| Cluster Size (Nodes) | Linearizable Read QPS | Serializable Read QPS | Improvement (%) |
| ---------------------| --------------------- | --------------------- | ----------------|
| 3                    | 1200                  | 1350                  | 12.5            |
| 5                    | 1050                  | 1250                  | 19.0            |
| 7                    | 900                   | 1100                  | 22.2            |
| 9                    | 800                   | 1050                  | 31.3            |
| 11                   | 700                   |  950                  | 35.7            |
   
