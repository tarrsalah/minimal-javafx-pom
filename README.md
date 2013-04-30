
# minimal-javafx-pom

This is a minimal **javafx-2** maven setup, using [Zonski javafx maven plugin](https://github.com/zonski/javafx-maven-plugin).

For more informations about the motivations behind it, see this [StackOverflow question](http://stackoverflow.com/questions/16287053/scene-getstylesheets-add-not-working-inside-jar-file/16287238#16287238).

### How to run it ?

    $ mvn -Pdev clean compile jfx:run
  
### How to run it from the jar file ?  

    $ mvn -Pproduction clean compile jfx:build-jar      

    $ java -jar target/minimal-javafx-pom-0.1-jfx.jar
  
