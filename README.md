# lab2links

Order Service
https://github.com/DomHeallis/order-servicelab2.git

Product Service
https://github.com/DomHeallis/product-servicelab2.git

Store Front
https://github.com/DomHeallis/store-front-lab2.git

Youtube Demo
https://youtu.be/3b4Uyz-L05Y

### Reflection Questions

## 1. What changes did you make to the order-service and product-service to comply with the Configurations and Backing Services factors of the 12-Factor App methodology?

I updated the services to load their configurations from environment variables instead of hhardcoding them. This made the services easier to run in different environments. We complied with the first 4 factors of the 12 factor metholodogy. We created repos for each service to adhere by Codebase(#1), we made sure all the dependencies where installed and properly declared (#2). We made sure the environment variables were being used and not hardcored (#3), and lastly, we treated the backend service like an attached resource (#4).

## 2. Why is it important to use environment variables instead of hard-coding configurations in your application?

It's very important. Environment variables makes applications more secure. Imagine having a username and password hardcoded, and you published it to github, everyone or whoever has access to the repo would be able to see it same goes for API keys, this way, environment variables keeps them private. It also makes it more portable, where you can uyse the same codebase to run in different environments without needing to change much.

## 3. Why is it important to have separate repositories for each microservice? How does this help maintain independence and scalability of each service?

It makes each microservice more independent and easier to work on. One service can be worked on, without necessarily breaking all of them. It makes the code easier to work on because you're only dealing with 1 codebase that is all connected, instead of larger codebase that could technically make it more challenging/confusing.