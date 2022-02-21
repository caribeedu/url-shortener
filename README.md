# URL Shortener 🔀

A http handler implementation for short url redirect written in Go.

## Detailing 📋

### **Description**

*"The goal of this exercise is to create an http.Handler that will look at the path of any incoming web request and determine if it should redirect the user to a new page, much like URL shortener would. For instance, if we have a redirect setup for `/short-url` to `https://www.example.com/long-url-with-some-length` we would look for any incoming web requests with the path /dogs and redirect them."*

This is a simple implementation of url short challenge/exercise, you can read full detailing in [here](https://github.com/gophercises/urlshort).

### **Requirements**

Implement the stubbed out methods `MapHandler` and `YAMLHandler` in `lib/lib.go`. There are a good bit of comments explaining what each method should do, and there is also a main/main.go source file that uses the package to help you test your code and get an idea of what your program should be doing.

## Running Locally 🛠️

1. Be sure you have Go Lang installed (version used here is `v1.17`)
2. Run this command in project folder to install dependencies and build project
```
go build ./main.go
```
3. Run the executable
4. The application will initialize at `http://localhost:8080`

## License 💼

MIT