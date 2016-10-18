1. **`worker_processes 1;`** : a lower traffic site and all (nginx, database, web application) all run on the same server.
2. **`worker_processes auto;`** : a higher traffic site, a dedicated nginx server, set one worker per CPU core.
3. **`use epoll;`** : use a scalable I/O event notification mechanism that I/O is utilized to the best of its ability.
4. **`multi_accept on;`** : accept all new connections at one time.
