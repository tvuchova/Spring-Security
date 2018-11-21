Spring Security  Example Project

   Spring Security is a framework that focuses on providing both authentication and authorization to Java applications.
   
   <b>Basics of the SS process</b>
   @PreAuthorize can check for authorization before entering into method. @PreAuthorize is checked on the basis of role 
   or the  argument which is passed to the method. @PostAuthorize checks for authrorisation after method execution.
   <br><b>Authentication</b>: Process of checking the user, who they claim to be.
   <br><b>Authorization</b>: Process of deciding whether an user is allowed to perform an activity within the application.
   
   
   In order to use SS I have added dependency for spring security and @EnableWebSecurity in configuration file,
   which extends WebSecurityConfigurerAdapter.In this file there are overrided 3 configure methotds
   
   Application <b>demo-spring-security</b> spring boot security
   <br>auto configuration:
       <br>Mapping filter: 'springSecurityFilterChain' to: [/*] : Spring Security is by default turned on for all 
       <br>the URLs in the application.
       <br>Basic Authentication is the default.
       <br>Using default security password: 25e07e82-720d-4109-ba8d-25177c6347e6 : Default userid is user. Default password
       <br><br>is printed in the server start up log. In this example, password is 25e07e82-720d-4109-ba8d-25177c6347e6
       <br>Some filter chains are configured to enable security

