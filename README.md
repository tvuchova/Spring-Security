# Spring-Security

Spring Security is a framework that focuses on providing both authentication and authorization to Java applications.
 @PreAuthorize can check for authorization before entering into method. @PreAuthorize is checked on the basis of role or the argument which is passed to the method. @PostAuthorize checks for authrorisation after method execution.
 uthentication: Process of checking the user, who they claim to be.Authorization: Process of deciding whether an user is allowed to perform an activity within the application.
 We need to add anotation @EnableWebSecurity to @configuration file,which extends  We need to add anotation @EnableWebSecurity to @configuration file,which extends  We need to add anotation @EnableWebSecurity to @configuration file,which extends 
 WebSecurityConfigurerAdapter.in this file there are overrided 3 configure methotd
