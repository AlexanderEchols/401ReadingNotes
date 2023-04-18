Alexander Echols
15 April 2023

# AWS Describe Abstraction
This is important because we will end up working with companies of various sizes and needs. Understanding how AWSs various builds can benefit each different type of company will make us better at helping companies build, maintain, and secure their organizations and networks.
1. This is similar to running a D&D campaign. You want to start running a game but don’t want to build the whole campaign yourself. Wizards of the Coast has pre-built campaigns that come with everything you need to start. But what if you want more control and you want to build the campaign but maybe not create the maps, Wizards of the Coast has pre-built maps one may purchase. 

    This is how the levels of abstraction work in AWS, you can build out the whole thing from the ground up or you can get a fully deployable, pre-built environment and pretty much everything between. This will make the creation of your network fully customizable for your companies needs

2. **Control Plane** is responsible for deploying and managing your containers
**Data Plane** is responsible for providing the resources(CPU, Memory, Network, Power, Storage) that the containers need to function properly.
3. **Lambda** falls at the top of the levels of abstraction and that is because it (Lambda) is an “execution environment” which means you don’t need to run or manage a full OS. As for what makes it special is the fact that it is an “event-driven” model, meaning one may trigger a lambda function through an event that occurs on another AWS service

## **What I wanna know more about:**
What is the least level of abstraction? Least level of abstraction would be the “bare metal abstraction” 
