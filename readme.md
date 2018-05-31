# Dockerized JSMTProxy

> [JSMTProxy Github](https://github.com/FreedomPrevails/JSMTProxy)

## Howto

### Run

```bash
docker run -d --restart always --name jsmtproxy -e MTPROTO_SECRET=<SECRET> -p <PORT>:6969 superegor/jsmtproxy
```

### Share link for it with friends

```
tg://proxy?server=<SERVER>&port=<PORT>&secret=<SECRET>
```
