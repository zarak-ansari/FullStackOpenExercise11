# Answer 1
- For linting, the IntelliJ IDE can provide helpful suggestions and even autocorrect in line with the conventional Java coding styles. However, using this would require all developers to use the same IDE and customizing specific styles would be difficult. In addition to this, “checkstyle” seems to be the most popular linter for Java which was first developed in 2001 and is still maintained. 
- For end-to-end testing of web applications, Selenium seems to be the most popular choice. For unit tests, JUnit and Mockito are popular frameworks.
- Gradle and Maven are the major build tools for Java. Gradle seems to have a more readable configuration files whereas maven uses an xml format for defining dependencies which can be a bit cryptic.

# Answer 2
- CircleCI seems to be a highly popular and fully featured CI/CD tool used by large tech companies. 
- In addition, Gitlab provides CI CD tools along with management of repositories which may be a more economical choice. 

# Answer 3
A cloud-based environment may be better in this case. 
Since the application has a team of 6 developers it is likely that the application is not a large-scale application with a lot of unique requirements. Therefore, setting up a self-hosted environment may not be worth the effort. Further, it is not clear whether the team has any expertise in setting up a custom CI/CD environment. Hence utilizing a cloud-based option with minimal requirements for setting up configuration/ security might be more efficient and safe.