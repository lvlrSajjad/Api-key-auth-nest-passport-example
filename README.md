# Usage
`cd server`

`pnpm install`

`pnpm start`

`curl --location --request GET 'http://localhost:3000' \
--header 'x-api-key: d2e621a6646a4211768cd68e26f21228a81'`

Or

`curl --location --request GET 'http://localhost:3000' \
--header 'x-api-key: d2e621a6646a4211768cd68e26f21228a'`


You should Receive: 

```Hello World!```

`curl --location --request GET 'http://localhost:3000' \
--header 'x-api-key: d2e621a6646a4211768cd68e26f21228a8'`

You should Receive:

```{"statusCode":401,"message":"Unauthorized"}```
