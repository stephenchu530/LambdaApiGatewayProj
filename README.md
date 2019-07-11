# Lambda Api Gateway Project + Repeated Word
This is a Code Fellows 401 project that tests out how to setup AWS Lambda + AWS API Gateway

## Try it Out!
Open your favorite browser and point your URL bar to [here](https://i38e6qarbk.execute-api.us-west-2.amazonaws.com/repeatedWord?input=):
```
 https://i38e6qarbk.execute-api.us-west-2.amazonaws.com/repeatedWord?input=
```
Make sure to add to the end of the URL a string to parse through. For example:
```
 https://i38e6qarbk.execute-api.us-west-2.amazonaws.com/repeatedWord?input=A b a B a
```

The output would be:
```
 "a"
```

## Problems and Difficulties
* Setting up AWS Lambda was striaght forward
* Setting up AWS API Gateway was painful because the Lambda function only accepts raw String input while AWS API Gateway by default passes JSON to the Lambda function.

## Contributors
* Stephen Chu, [stephenchu530](https://github.com/stephenchu530)

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/stephenchu530/LambdaApiGatewayProj/blob/master/LICENSE)