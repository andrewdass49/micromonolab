## Potential services

- user management service - handles login in or out and user roles
- subscription service - handle subcribing to a users podcast or blog
- podcast managment service - handles upload and posting of podcast
- blog management service - handles the blogging system using cms
- scheduling and social sharing management service -  allows user to schedule their post and share it with other social medial such as YT, Twitter

## AWS tools
- EC2 to manage vms and networing 
- Elastic Load Balancer to handle the traffic coming to the different services
- Amazon API Gateway - centralized ways to access all api's
- AWS CloudMap -  service registry and discovery
- Amazon Elastic Container Registry - containerize each services
- Amazon EKS - manage containerized services
- to me since the application is small kubernetes may not be needed but if It grows then yes

- Amazon SQS - manage data processing through the app


## App 

- a user of the role Author is able to upload a podcast and write blog similar to the substack . it is a media station for personalities to grow their brand as their also a scheduling feature. A normal user can subscribe to these users and view new post. there will be notification to notify something new has be posted