# DevOps-Challenge
Migrate On-premise service to AWS. This web platform have a simple architecture. A web server (Nginx), running PHP for static and dynamic content. Mysql is used as Database.

I used a Microservices model, so, the first step is dockerize the on-premise App.
Second I think that fargate is a very good option to host the app because is a very good way to modernize the infrastructure since development team to DevOps Team.

There are more ways to host in AWS the app, for example I can replicate the same on-premise architecture with EC2 instances (like virtual machines), but to choose the best option I need more context about the service.
