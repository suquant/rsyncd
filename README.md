# rsyncd
Rsync docker image

## Example

```
docker run --rm -v /src:/src -v /dst:/dst suquant/rsyncd:latest -a /src /dst
```