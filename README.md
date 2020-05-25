# todo-100

This project challenge was created to evaluate the skills of candidates, applying for a *Full Stack Developer* position.
The candidates should create a simple Todo app, showcasing their abilities to build, structure, and deploy the application. It's not about the todo app itself, it's about architecture, style, and engineering skills. 

## Getting Started

All the requirements to complete this project are listed below. You can also watch the video for more details.
https://drive.google.com/open?id=1Sx0L-U-P-OOxyDSiOvpExXsMVPp-KAFY

## Requirements

You are required to build a scalable and responsive ReactJS Todo app and deploy it on AWS following microservices architecture using ECS.

## Build With

**ReactJS**
* For this project do NOT use Redux, all must be done using the following items
* React Hooks and Context API

**Consider the following key points:**
* Reusability of your components
* Your project structure
* Performance; We expect you to be familiar with “rendering performance” as well as “pixel pipeline”. (You may refer to his link https://developers.google.com/web/fundamentals/performance/rendering). This app is mobile-first design, and you should consider we have a large number of tasks that must be rendered in client sider (~1000+ tasks), the app should NOT **render** all the tasks at once to avoid sluggish and slow interface. The app should utilize scrolling, not paging. You have to implement a mechanism to only render the part of the data is needed to be presented on a phone screen.

**Authentication**\
You are free to choose between Firebase OR Amplify to manage authentication using Google account.

**User Interface Functionalities**
* Create task
* Assign task (Ask for another user Gmail account, and send a realtime notification to the assignee)
* Remove task
* Update task
* Delete task

**Real-time Notifications**\
You are free to choose one of the following approaches:
* Amplify (Recommended)
* PusherJS
* Firebase

**Back-end**\
Follow serverless / microservices design using one of the following technologies:
* AWS (Recommended)
* MongoDB Stitch
* Firebase
* GCP\

**Database**\
For the database, you can try one of the following items: 
* MongoDB
* AWS DynamoDB
* Firebase

**Documentation**\
You are required to illustrate your system design and cloud architecture within a conceptual diagram.

**Deployment Platforms**\
You may try one of the following platforms:
* Amplify (Recommended)
* Firebase
* MongoDB Stitch (Atlas)
* GCP
* Heroku

_Remember we are looking at your experience in building scalable apps, so utilizing docker containers, load balancers, and other techniques are suggested._


**BONUS**\
Things below add bonus points:
* PWA
* Using GraphQL
* Establish a Cache layer using Redis or Memcached
* Create an API document for your services/function/api using one of the following api docs provider:
  * https://redoc.ly/
  * https://swagger.io/tools/swagger-ui/
  * Readme.io
  * Or any other tools

HAVE FUN! 😉









