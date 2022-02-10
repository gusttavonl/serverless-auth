## Getting started

### 1. Clone the repository (or generate a serverless project)

```sh
sls create --name auth-service --template-url https://github.com/GustavoNoronha0/serverless-auth
cd auth-service
```

### Install dependencies

```sh
npm install
```

### Deploy

```sh
sls deploy -v
```

### 5. Final test

To make sure everything works, send a POST request (using curl, Postman etc.) to your private endpoint.

You can grab a test token from Auth0. Make sure to provide your token in the headers like so:

```
"Authorization": "Bearer YOUR_TOKEN"
```
