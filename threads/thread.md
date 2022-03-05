## **Process**

- a process is the instance of a computer program that is being executed by one or many threads. 
- every process has at least one thread, but there is no maximum number of threads a process can use. For specialized tasks, the more threads you have, the better your computer's performance will be. With multiple threads, a single process can handle a variety of tasks simultaneously.

## **Thread**

- threads let an application perform multiple tasks concurrently

### concurrency and synchronization
- concurrency: doing things at the same time
- synchronization: keep things consistent

### common use of threads:
web servers: a web server "listens" for requests. When a request arrives, a thread to handle that request is created so the server can quickly go back to listening for more requests
GUIs: progress bars that indicate amount of progress run in separate threads so that they can be updated while the actual "work" is being done simultaneously
anytime you want to parallelize a task
