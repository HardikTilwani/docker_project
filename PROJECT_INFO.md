**PROJECT - "CONTAINERIZING DATA SCIENCE ENVIRONMENT"**

**DOCKER-COMPOSE  -  INFRASTRUCTURE AS CODE**

**RED HAT ENTERPRISE LINUX [ 8 ]  &  DOCKER ENGINE [ COMMUNITY EDITION ]**

>**PROJECT STRUCTURE** -


     |data-toolbox
   
     |---docker-compose.yaml
  
     |---jupyter-notebook-docker
         |---Dockerfile
  
     |---ml-flow-docker
         |---Dockerfile
         |---wait-for-it.sh
  
     |---postgres-docker
         |---Dockerfile
         |---init.sql
  
     |---Volumes    
   
   
  > **IMAGES USED**
  
    || Python : Latest
    
    || Jupyter/scipy-notebook : Latest
    
    || ML Flow : Latest
    
    || Postgress : Alpine : Latest
    


 > SHELL SCRIPT "wait-for-it.sh" 
 
 --> That Allows You To Wait For Any Service To Accept A TCP Connection And Then Executes Any Other Command.




**MAKING DATA PERSISTENT BY DOCKER VOLUME**



> CONCEPT - "Containerizing Data-Science Environment"

   || Using These 3 Components -
 
   || Jupyter-Notebook Server - " To Conduct Experiments "
 
   || ML Flow Tracking Server - " To Record & Organize Experiment Parameters & Metrics "
 
   || Postgres Database - " As The Backend For The ML Flow Server & As A Handy Data Store For Our Structured Data-Sets"
 
 
 
**SOLVE DEPENDENCIES**

**DOCKER-COMPOSE BUILD**

**DOCKER-COMPOSE UP** 



**CONCLUSION**

=> I hope I was able to demonstrate with this little example how you can easily create a System made up of Multiple Containers, that can interact via a Network and can share data in Volumes.

=> Docker containers can make a lot of things Easier & Faster, from build pipelines to distributed systems and software testing to only name a few. 

=> Some things like Micro Service Architectures are only really feasible with the use of containers. There is probably something in it for you that can make your life easier or streamline your productivity.
 
