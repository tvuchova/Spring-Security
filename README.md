Spring Security  Example Project

   Spring Security is a framework that focuses on providing both authentication and authorization to Java applications.
   
   <b>Basics of the SS process</b>
   @PreAuthorize can check for authorization before entering into method. @PreAuthorize is checked on the basis of role 
   or the  argument which is passed to the method. @PostAuthorize checks for authrorisation after method execution.
   <b>Authentication</b>: Process of checking the user, who they claim to be.
   <b>Authorization</b>: Process of deciding whether an user is allowed to perform an activity within the application.
   
   
   In order to use SS I have added dependency for spring security and @EnableWebSecurity in configuration file,
   which extends WebSecurityConfigurerAdapter.In this file there are overrided 3 configure methotds
