## Rules example for processing Creditcard application

## API method

* Run go run main.go

## JSON method

* Create flogo app
* copy function.go to flogoapp/src folder
* Run flogo build
* Start the generated binary
* Run below curl requests
```
Curl request 1
$ curl -X PUT http://localhost:7777/applicant-d '{"name":"Sam4","age":"26","salary":"50100","address":"SFO","id":"4"}'

Curl request 2
$ curl -X PUT http://localhost:7777/cibildata -d '{"id":"4","name":"Sam4","creditScore":"850"}'
```

* Application status will be printed on the console