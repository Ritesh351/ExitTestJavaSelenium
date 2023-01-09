# Flipkart Website Automation Suite

#To run Flipkart Automated Suite from command Line in the project Folder


## Packages Description

-com.nagarro.SeleniumJava.abstractcomponents: Defining all the basic Requiremnent.

-com.nagarro.SeleniumJava.pages: Implemented POM (Page factory)

-com.nagarro.SeleniumJava.tests: Defining all the pages tests and asserts. 

-com.nagarro.SeleniumJava.util: Defining all  utilities needed for Screenshot.

###Page.java and Test.java files description

***Footer Page and Test :- Check for functions defined in footer like- Gateway Logos, Payment ,Social Sites, Copyright, HelpCenter, Contact Us, GiftCard, Advertise and BecameASeller.

***Home Page and Test :-  Check for  various functions like-  Title, logo , Login Tab , NextSlide click, BackSlide click , BecomeASellerTab, 
                          Navbar menu, SearchProduct.                   

***ProductSearch Page and Test :- Search for product in search bar and Add the Product to the Cart.

***Register Page and Test :- Test for Register new user.


###BaseTest:The main class 
- @BeforeSuite -to setExtent
- @AfterSuite - to end endReport
- @BeforeMethod - to open the browser, to open url
- @AfterMethod - Attached the screenshot, to close Browser


###Other files description

- Screenshots.java: defines function to take screenshots


## Important Directory

- Drivers : ./Resources/drivers/
- Report File : ./Reports/ExtentReportGenerated.html
- Log File : application.log
- Configuration File: ./Resources/Config.properties
- Screenshots Folder: ./FailedTestsScreenshots/


## Main Parameters in Configuration.properties file
- global wait : to apply implicit wait
- URL : URL of Site
- Driver name : Name of browser
- Driver Address : Address of Driver



###Reports and Screenshots

- Extent report gets generated after the run under\src\test\Report\Report.html

- TestNG report as "emailable-report.html" gets generated under \test-output

- Screenshots gets placed under\Screenshots folder with test name and date and time

- Log File get placed under \application.log

###GitHub Repository Link

- LINK : 