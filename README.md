# Microservices Practice App

This project is intended to help me understand the basics of Microservices and have a great
understanding of proper code workflow.

## Structure

This project is currently divided into 6 folders:

-   Client - `React side of the application`
-   Comment Service - `Backend Service for comments`
-   Post Service `Backend Service for post`
-   Event Bus - `Received events from different services and updates who ever needs that event`
-   Query - `Emit the get end point for post and comment service (Note: This service can also be used for all other get end points for other services`
-   Moderation Service - `This service will flag if the comment is approved|pending|rejected`

## Run Locally

Clone the project

```bash
  git clone https://github.com/rbnograles/blog-microservice my-project
```

Go to the project directory

```bash
  cd my-project
```

Make sure that you are running docker and kubernetes

```bash
  skaffold dev
```

## Tech Stack

![Node.JS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.JS](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)

![React.JS](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-326ce5.svg?&style=for-the-badge&logo=kubernetes&logoColor=white)

## License

[MIT](https://choosealicense.com/licenses/mit/)

## 🔗 Links

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.linkedin.com/in/ryan-nograles-63b00221a/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ryan-nograles-63b00221a/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/rbnograles)

## Acknowledgements

-   [Udemy Course: Microservices with Node JS and React](https://www.udemy.com/course/microservices-with-node-js-and-react/)

## Author

-   [@rbnograles](https://www.github.com/rbnograles) :writing_hand:
