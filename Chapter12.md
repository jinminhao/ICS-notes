# Chapter 12 Concurrent Programming

## with Process

Processes have a clean model for sharing state information between parents and children: ﬁle tables are shared and user address spaces are not. 

Separate address spaces 

​	pros: It is impossible for one process to accidentally overwrite the virtual memory of another process, which eliminates a lot of confusing failures

​	cons: It makes it more difﬁcult for processes to share state information.

