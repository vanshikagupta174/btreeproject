# btreeproject
Implemented a b-tree based indexing in Java to speed up the latency of queries in a relational database and to improve search performance. The RDBMS query is served via page scan. When a B-Tree based index is created, the RDMS query is served via index seek. This leads to minimization of the page reads from hard disk. 
Search time reduces by a factor of log n where n is the degree of b tree.
