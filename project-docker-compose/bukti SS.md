1. Prepare single database, single table, and single column, for timestamp
![alt text](image-4.png)

2. Create golang project, and add route "/ping" if can connect to database, output to browser is Pong! and console is Ping Successful, if failed, Ouch and console is Ping Failed. And can show timestamp if connected.
![alt text](image.png)

3. Created docker-compose.yml for run 2 container, set container name, network name, also volume name
![alt text](image-2.png)

4. Create docker compose and can see on docker desktop 
![alt text](image-1.png)

5. Run localhost:4331 and show word that have been created 
![alt text](image-3.png)

6. Run localhost:4331/ping and show pong for success and new data timestamp inserted in database
![alt text](image-5.png)
![alt text](image-6.png)

7. Check log from each container
![alt text](image-7.png)
![alt text](image-8.png)
