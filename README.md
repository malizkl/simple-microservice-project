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

![Alt text](/Users/mojave/Desktop/microservice.png "Optional title")