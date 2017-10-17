# task2

 Start up the virtual machine:
$ vagrant up

 Stop the virtual machine:
$ vagrant halt

Service is available:
localhost:8081/contacts    "all"   
localhost:8081/contacts?nameFilter=A    "^A.*$"
localhost:8081/contacts?nameFilter=B    "^.*[aei].*$" 

Postgresq:
localhost:5432
  Database: myapp
  Username: myapp
  Password: dbpass
