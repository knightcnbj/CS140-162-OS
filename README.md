# CS140-162-OS
Operating System by Stanford &amp; Berkley 

<h2> Lec 2 Thread & Process </h2>

1. challenge of multi-programming
    1. virtual machine abstraction: each app wants to own the machine
    2. protection & concurrency
    3. communication

2. process: unit of resource allocation and execution
    1. owns memory, file descriptor, encapsulate one or more threads
    2. provide more protection than thread
    3. slower than thread
    4. made of threads & address space