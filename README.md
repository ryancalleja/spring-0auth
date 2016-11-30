# spring-0auth2
A small example demonstrating the use of 0Auth2 server in a Spring application, having separate 
servers per functional groups. Also experimenting using YAML properties instead of the
traditional properties files. 

## Improvements ##

* Identify from where the login is coming from Facebook or Github, show data based on social login.
* Remove webjars, and add client module on its own.
* Remove starter packs for spring-boot and include only dependencies required.