# Weather Snack
A CLI weather app made with Go.<br/>
[Github go docs](https://github.com/golang/tools/blob/master/gopls/doc/workspace.md)
[Go package docs](https://pkg.go.dev/)


## Made with:
- [Go](https://go.dev/) - Build simple, secure, scalable systems.
- [OpenWeather](https://openweathermap.org/)


## Setup:
* Clone this repo
```
git clone <repo-url>
cd weather_snack
```

* Setup environment variables and edit `.env`
```
cp .envExample .env
```

## Run the project 
### Without build
```
go run main.go
```

### With build
* Build project
```
go build
```

* Move executable file to /usr/bin
```
sudo mv weather_snack /usr/bin
```

* Run the project
```
weather_snack
```

## Acknowledgement:
* [Credits](https://www.youtube.com/watch?v=zPYjfgxYO7k)