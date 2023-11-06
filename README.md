# Secret Santa Generator Application :santa:
  
A __secret santa generator web application__ built using __Spring Boot technologies__, __Thymeleaf views__, __JPA__, __H2 Database__, and more. The project features Spring Model, View, and Controller (MVC) architecture and Service and Repository layers.

This project is based on the popular Christmas game __Secret Santa__ where friends draw names from a hat to decide who they are required to give a present to. This project allows users to add names, and the project randomly generates secret santa matches (it isn't as simple as creating random pairs). There are different solutions to the "Secret Santa problem" as the problem essentially creates a directed graph. 

**Preview images** :small_red_triangle_down:
<details>
<summary>Some images of the application </summary> 

* Welcome Page

![Welcome](https://github.com/NotTheBest/secretsanta-generator/blob/master/preview-images/welcomepage.png?raw=true)

* Add People

![Add](https://github.com/NotTheBest/secretsanta-generator/blob/master/preview-images/addpage.png?raw=true)

* Generate "Matches"

![Matches](https://github.com/NotTheBest/secretsanta-generator/blob/master/preview-images/generatepage.png?raw=true)

</details>

## Running the application from jenkins

job build step 1 --package
step 2 -- execute shell --
java -jar -Dserver.port:8081 target/*.jar
execute jar file to run application..



extra notes:::::::::::::::::
java -jar target/*.jar
You can then access the application here: http://jenkinspubip:8080/
Or you can run it from Maven directly using the Spring Boot Maven plugin.

```
