
## API endpoints

1. `POST /api/auth/signup`
2. `POST /api/auth/signin` 

## postman
Signup

```js
{
    firstname: string,
    lastname: string,
    email: string,
    password: string
}
```

Signin 

```js
{
    email: string,
    password: string
}
```

Install the required dependencies

```sh
npm install
```

Initialize database 

```sh
npm run db:init
```

Start 

```sh
npm start
```
