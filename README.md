# MockApiTest
This is MockApi project for API Automation framework using Java, restAssured, Gradle and TestNG.  

Rest API : http://demo4032024.mockable.io/apitest.  

**1.Utils**
    
    Categories -> provides categories which can be used as tags to run TestNG tests.  
    Constants -> provides employee details that can be consumed as a Test Data.  
   
    
**2.Properties** -> provides method to set host when running scripts across different environments

**3.Reporting** -> basic HTML report with TestNG

**6.SampleTests** -> Following tests are automated. 

        Get Employee Details : http://demo4032024.mockable.io/apitest. 
        
        shouldTestGetEmployeeDetailsStatusCode(). 
        
        verifyResponseHeadersIsJsonFormat().  
        
        verifyEmployeeDetailsResponseBody(). 
        
        verifyResponseWithCompanyData().  

# Steps to Run on Local Machine  
1.Clone the repository.   

2.Open the project as gradle project (by opening build.gradle file using Intillij Idea). 
Wait till all dependencies are downloaded.  

3.Add lombok plugin and enable annotation processing.  

(https://stackoverflow.com/questions/41161076/adding-lombok-plugin-to-intellij-project). 

**Scenarios Automated:**. 

**Assertion 1 :** Validate Response Status code as 200. 

**Assertion 2 :** Validate Response Header for JSON response. 

**Assertion 3 :** Validate Response body with following data using (JsonPath/ JsonParser/ etc.). 

Status=200. 

Age= 25.  

Role=QA Automation Developer.  

Dob=25-02-1994.  

Message=data retrieved successful.   


**Assertion 4 :** Validate Response body with following data Company=ABC Infotech. 




