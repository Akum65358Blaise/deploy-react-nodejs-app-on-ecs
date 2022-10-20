# react-nodejs-application

Project demonstrating how I developed a React application with Nodejs as backend technology and deploy it to AWS ECS

After developing the application, in order to deploy the application to ECS here are the steps i followed

Firstly, i had to dockerize my application by preparing a Dockerfile.

Secondly, i build an image of the application locally from the dockerfile and tagged the image.

Thirdly, i pushed the image to ECR(Elastic Container Registry).

Lastly i deployed to AWS ECS and i was able to access the web app on the browser.

