#  Building Modern Python Applications on AWS (COURSERA)
![pub package](https://img.shields.io/badge/dev-meetsandeepan-magenta.svg)

This is my solution to all the quizzes of Building Modern Python Applications on AWS (Coursera) taught by Taught by Morgan, Seph, Jon, and Rick. After completing this course you will get a broad idea of AWS Fundamentals. Try to solve all the quizzes by yourself first, but if you get stuck somewhere then feel free to browse the repository.

# About this course

In modern cloud native application development, it’s oftentimes the goal to build out serverless architectures that are scalable, are highly available, and are fully managed. This means less operational overhead for you and your business, and more focusing on the applications and business specific projects that differentiate you in your marketplace. In this course, we will be covering how to build a modern, greenfield serverless backend on AWS. 

Building brand new applications on AWS is a different task than lifting and shifting existing applications into AWS. When you have an existing application that you need to move to AWS, you might first look to using Amazon EC2 as your virtual machines, or maybe you might look into using docker containers and container hosting services like Amazon Elastic Container Service or Amazon Elastic Kubernetes Service. Those are all great application hosting options, but in most cases, they still require you to have some kind of pulse on the underlying infrastructure hosting your application. 	`

Building Modern Python Applications on AWS will explore how to build an API driven application using Amazon API Gateway for serverless API hosting, AWS Lambda for serverless computing, and Amazon Cognito for serverless authentication. We will follow an API driven development process and first mock up what the API will look like. We will cover all the ins and outs of the service Amazon API Gateway, and as you’ll learn- it does a lot more than just hosting an API. 

Then we will add authentication to the API using Amazon Cognito. You’ll learn about how the authorization flow works with Cognito, and how to build it into your APIs. From there, we will add a Lambda backend that will be triggered by API Gateway. The lambda functions will be using the AWS SDKs to perform various data processing tasks. You’ll learn about the different configurations that exist for Lambda, and we will show you how to create and manage lambda functions. Some of the features of our API will require multiple lambda functions to execute in a specific order, like a workflow, and we will use AWS Step Functions to create a serverless workflow. Finally, we will talk about how to optimize your APIs at every layer using AWS features.

Note: There are three versions of this class, "Building Modern Node.js Applications on AWS" for Node.js developers, "Building Modern Python Applications on AWS" for Python developers, and "Building Modern Java Applications on AWS" for Java developers.  The courses do for a large part, overlap and in general, we recommend that you take the course that focuses on the SDK you plan to use to develop your AWS Cloud based applications.

We expect that you have basic knowledge of AWS already. Some examples of concepts you should be familiar with are: you should know the basics of the AWS Global infrastructure, like what regions and availability zones are. You also should know the at a high-level AWS Identity and Access Management, or IAM, and how it is used to control access to AWS resources. You should also understand what an Amazon EC2 instance is, what Amazon S3 is, what a VPC is, as well as other basic AWS terminology.

# Reference

[Course Link](https://www.coursera.org/learn/building-modern-python-applications-on-aws)