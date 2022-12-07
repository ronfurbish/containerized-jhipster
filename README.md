# Containerized JHipster 

I created this as a quick and easy way to spin up JHipster containers so I can easily toggle between multiple versions as needed.

## Docker Instructions

1. Spin up all services
  ```
  docker compose up -d
  ```
  
2. Spin up one service
  ```
  docker compose up -d jhipster7
  ```
  
3. Spin up multiple services, but not all
  ```
  docker compose up -d jhipster7 jdl-studio
  ```
  
## Other Notes

Working on adding one for jhipster dotnetcore, but that is still a work in progress.

If you have any feedback or would like to contribute always happy to make it better!
