What are the problems solve by DPDK?

1. Overhead of Linux interrrupt driver
 This is solved by the Poll mode driver used by DPDK.
 
 2. The context switch between kernek driver and user application
  The DPDK uses user mode driver to solve this issue.
  
  3. Thread scheduling overhead
  Bind the thread to the logical cpu
  
  4. Access to shared data structures
  DPDk implemented lockless queues
  
  5. Page swaping overhead
  DPDK uses huge pages
  
  
  DPDK Internal components
  ========================
  ![Optional Text](https://github.com/kesavand/DPDK/blob/master/images/dpdk.png)
  
  
  
