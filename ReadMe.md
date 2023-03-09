To run this perform these steps

1.    cp docker-compose.example.yml docker-compose.yml`
2.    `cp .env.example .env`
3.    Open `docker-compose.yml` using **vim or any other editor** and change the networks names to your network and ports according to your need
4.    Open `.env` and change updated all of the required `env variables` like db, redis etc.
5.    Run `docker compose up -d` 
6.    It should work now 

**Note:** I am not using nginx proxy but you can also publis it behind any proxy