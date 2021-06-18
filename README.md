# Very simple proxy

[![N|Solid](https://spring.io/images/spring-logo-9146a4d3298760c2e7e49595184e1975.svg)](https://spring.io/projects/spring-boot)

## Possible Future Features

- Support to SSL Connections with SSLConnectionSocketFactory
- Implement a Blacklist or Whitelist of urls
- Support to multipart data
- Support to automatic redirection when the http status is 3xx

## Execute

To execute can use the IDE that prefered

## Use

This is an example of query with curl using the local proxy:

```sh
curl -i --proxy 127.0.0.1:8080 http://www.google.com
```


## License

MIT
