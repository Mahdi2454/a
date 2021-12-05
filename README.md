# mamunassessment
A task for an eventual job

#Pull the project 

#Start the project
under teh main directory you need to type in the terminal :  docker-compose up

#Keycloak Config 
connect to keycloak with the url: http://localhost:8050/auth

Create a new realm : mamunassessment

in the directory you will find my config for the realm  assesementbe/realm-config
with the import functionality import the realm file and choose if rousource exist => Skip

create 2 users and give them password  in credentials to use them after 

in user page for each one assing them roles (role mapping) you will find roles in the mamunassessmentbe client :
the firs user Admin and manager role 
the second one only manager

#Open the application via this url : http://localhost:4200/

#communication between frontend and backen is with websocket 

#frontend is with angular and backend is with spring boot java
