# Summer cocktail

Example on how to use Go and Cucumber.

## Getting started

Install Govendor 
```
$ go get github.com/kardianos/govendor
```
Change directory to your project root 
```
$ mkdir -p $GOPATH/src/github.com/myusername/project && cd "$_"
```
Initialize Govendor and install dependency 
```
$ govendor init
$ govendor fetch github.com/gin-gonic/gin@v1.3
```
Run the project 
```
$ go run main.go
```
Test the ping endpoint
```
$ curl http://127.0.0.1:8080/ping
pong
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details