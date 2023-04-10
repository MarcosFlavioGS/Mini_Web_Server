# Basic Web Server in Go
###This is a basic web server project written in Go that serves static files, handles form submissions and responds to a simple "/hello" endpoint.

## Requirements
This project requires Go installed on your system. You can download and install it from the official website: https://golang.org/dl/.

## Installation
Clone the project to your local machine using the following command:

```sh
git clone https://github.com/MarcosFlavioGS/Mini_Web_Server.git
```
Change dir

```sh
cd Mini_Web_Server
```

Run the web server:

```sh
go run main.go
```

By default, the server runs on port 8080. You can change it by modifying the ListenAndServe function in the main function.

## Usage
### Serving Static Files
The server serves static files located in the ./static directory. To access them, simply navigate to http://localhost:8080 in your web browser.

### Handling Form Submissions
To submit a form, navigate to http://localhost:8080/form in your web browser. Enter your name and address, and click "Submit". The server will respond with a message confirming that the request was successful and will display the name and address submitted.

### Responding to "/hello" Endpoint
To access the "/hello" endpoint, navigate to http://localhost:8080/hello in your web browser. The server will respond with a message saying "Hello".
