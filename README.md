# wordpress_multisite

### 2 site wordpress 
```
#step1 you want create below.
-   create folder and have.
    -> data
        |-> No file
    -> database
        |-> No file
    -> init
        |-> 01.sql
    -> letsencrypt
        |-> No file
    -> www
        |-> th  #site1
        |-> en  #site2
#step2
-   run command deploy
    $ docker stack deploy -c docker-compose.yaml multisite

#step3
-   Open Web bowser <nginx proxy manager> url: http://localhost:81 
    ```
        Email:    admin@example.com
        Password: changeme
    ```
-   Config Host Proxy to subdomain to THE END.
```
** Service Database phpmyadmin: port 82