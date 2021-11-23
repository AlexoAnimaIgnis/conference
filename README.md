# conference

[ACTIVE] Project Based off from Spring MVC Pluralsight Course

# war vs contained
 - deploying JSP pages dont do well with Spring Boot Self contained jars
 - Spring will caution to not deploy application as a fully self-contained JAR and as a Spring Boot app

#configuration
 - more recent web specifications have called for not having a web.xml at all
   - reason is that XML based configuration is error prone
   - often thought as complicated
   - cons: no blackbox
 - spring mvc configuration areas
   - pom.xml : where we declare our dependencies
   - Config : xml or java based
   - Java files/code
   - view: usually served under src/main/webapp
# SpringBootServletInitializer
   - used to launch the application with the desired configured were used to using inside of a webapp
   - tells where to look for the jsp pages and what are the extensions
     - spring.mvc.view.prefix=/WEB-INF/jsp 
     - spring.mvc.view.suffix=.jsp