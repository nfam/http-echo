# http-echo

A small HTTP server that echos the request headers and body back at a client as JSON in the response body.

## Usage

```sh
docker run -d \
    --name=http-echo \
    -p 8080:8080 \
    nfam/http-echo
```
