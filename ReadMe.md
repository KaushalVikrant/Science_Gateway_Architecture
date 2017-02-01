Link to code:

https://github.com/airavata-courses/TeamAurora

We worked on different modules of the project:

1. API Gateway

2. Data Ingestor

3. Storm Detector

4. Storm Clustering

5. ForecastTriggerWorker


Each module is present in its branch. Some modules have multiple braches as we developed them twice, once in synchronous architecture using REST calls and then we changed our design as we moved to asynchronous architecture using RabbitMQ.

Each module is deployed as a different micro-service in Amazon EC2 instance using Amazon S3.

We have used Travis CI and Amazon Codedeploy for Continuous Integration and Continuous Deployment.

![alt tag](https://github.com/KaushalVikrant/Science_Gateway_Architecture/blob/master/Synchronous%20Architecture.png)
![alt tag](https://github.com/KaushalVikrant/Science_Gateway_Architecture/blob/master/Asynchronous%20Architecture.png)
