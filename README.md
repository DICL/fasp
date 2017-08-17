# Failure-Atomic Slotted Paging

 we develop a novel “failure-atomic slotted page structure” for persistent memory that leverages byteaddressability
and durability of persistent memory to minimize redundant write operations used to maintain consistency in traditional database systems. Failure-atomic slottedpaging consists of two key elements: (i) **in-place commit per page using hardware transactional memory** and (ii) **slotheader logging** that logs the commit mark of each page. The proposed scheme is implemented in SQLite

## Publication

Jihye Seo , Wook-Hee Kim, Woongki Baek, Beomseok Nam, and Sam H. Noh 
"Failure-Atomic Slotted Paging for Persistent Memory", 
22nd International Conference on Architectural Support for Programming Languages and Operating Systems (ASPLOS '17), Xi'an, China, Apr. 2017. 

## Acknowledgement
This research was supported by MKE/KEIT (No.10041608, Embedded System Software for New Memory based Smart Devices), MSIP (No. R0190-15-2012, High Performance Big Data Analytics Platform Performance Acceleration Technologies Development) and National Research Foundation of Korea (No. 2014R1A1A2058843).
