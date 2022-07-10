# dex-change-password
dex-change-password is a [dex](https://github.com/dexidp/dex) web client to change a users password.  
It is originally based on the [example-app](https://github.com/dexidp/dex/tree/master/examples/example-app) and the [grpc-client](https://github.com/dexidp/dex/tree/master/examples/grpc-client) of [dex](https://github.com/dexidp/dex)

## Build
```
$ go build
```
## Run
```
$ ./dex-change-password --issuer https://dex:5554/dex --issuer-root-ca ca.crt --tls-cert cert.crt --tls-key cert.key
```

## Use
Open http[s]://localhost:5555 in a Browser.  
You will be redirected to dex. After a successful login with dex, a new password can be provided
