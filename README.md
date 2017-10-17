# task-rest-service

 Start up the virtual machine:
$ vagrant up

 Stop the virtual machine:
$ vagrant halt

Service is available:

localhost:8081/contacts    "all"
   
localhost:8081/contacts?nameFilter=A    "^A.*$"

localhost:8081/contacts?nameFilter=B    "^.*[aei].*$" 


Postgresq:
localhost:5432 <br>
  Database: myapp <br>
  Username: myapp <br>
  Password: dbpass <br>
  
  
  [![Build Status](https://travis-ci.org/PliutaMykhailo/task-rest-service.svg?branch=master)](https://travis-ci.org/PliutaMykhailo/task-rest-service)
  [![CircleCI Build Status](https://circleci.com/gh/PliutaMykhailo/task-rest-service.svg?style=shield)](https://circleci.com/gh/PliutaMykhailo/task-rest-service)
