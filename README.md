### Microservice Project with Golang and JWT

In this project, built a microservice that generates JWT token and another microservice that can parse it.

## Run api and jwt_creator

```bash
go run main.go
```
## Get JWT token

```bash
curl localhost:8090
```

## Run

```bash
curl http://localhost:9001 --header 'Token: Your generated token(Please paste your token with one space at the begining)'
```

After run this command, you should see the output (Super Secret Information)

<img width="1018" alt="microservice" src="https://user-images.githubusercontent.com/63977569/188915319-1851fc80-a4f1-42b7-ba80-db0b3a52a753.png">
