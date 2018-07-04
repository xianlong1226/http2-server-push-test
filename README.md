
## Requirements

- Node.js >= 8.4.0

## Run

```sh
npm start
```

or

```sh
node --expose-http2 index.js
```

Open: https://localhost:3000

## Result

![HTTP/2 push](/network.png)

## http/2 protocol illustrate
server push的资源必须满足同源策略，而且必须是本服务器能直接访问到的文件，并且浏览器能通过get请求访问到，不能是通过网络请求的文件。