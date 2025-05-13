# Securing-Web-Application Using Spring securities


A Spring MVC application that secures the page with a login form that is backed by a fixed list of users.


# FIRST WE MAKE A SIMPLE UNSECURED WEB APPLICATION


before we apply security we need to first make an unsecure Web application


1] Here we make 2 pages first a Home page then a hello page


2] for making both, we use Thymeleaf Templates


3] Since the application is based upon Spring MVC we need to configure a Spring MVC and set up view controllers to expose these templates.



#  SETUP SPRING SECURITY


Suppose that you want to prevent unauthorized users from viewing the greeting page at /hello. As it is now, if visitors click the link on the home page, they see the greeting with no barriers to stop them. You need to add a barrier that forces the visitor to sign in before they can see that page. SPRING SECURITY IS USED FOR THAT PURPOSE.

1]To incorporate spring security dependency. We have to add a dependency plugin in pom.xml file.




# RUN THE APPLICATION

