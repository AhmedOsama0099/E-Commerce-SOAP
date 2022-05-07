# JAX-WS SOAP E-Commerce Web Service
### An-E-Commerce-SOAP-built-using-JAX-WS.

## 📃 Documentation
[SOAP-UI messages](https://github.com/AhmedOsama0099/E-Commerce-SOAP/blob/master/E-Commerce-soapui-project-v2.xml)
## 📦 Features
* Content negotiation (support for both XML payloads and responses)
* SOAP 1.1

## ⚙ Technologies used
* JAX-WS (Metro)
* JAX-B
* Maven
* Tomcat
* Intellij IDEA Ultimate
* SoapUi

 ## 🛠 Run with Maven
    **Maven**
* Change the configuration of Tomcat in `pom.xml`. 
* Deploy the application using the following maven command:
 ```
mvn clean compile tomcat7:redeploy
```
* SOAP: import the project into SOAP UI

**🐬MySQL**
* Create a database schema and provide the username and password in the persistence.xml
* Hibernate will automatically create the tables for you
