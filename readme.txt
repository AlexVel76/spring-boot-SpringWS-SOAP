Generate Objects from xsd - cmd C:\_project\hometask>xjc -d src/main/java -p com.epam.htsa.soapclient.dto src\main\resources\dto.xsd
Generate xsd from Entity -  cmd schemagen src/main/java/com/epam/htsa/entity/*.java

To see wsdl go to http://localhost:8080/ws/userevent.wsdl

See SOAPClientTest.java as SOAP Client. To test it just run main Spring Boot Application as usual
and than run the test as common test.