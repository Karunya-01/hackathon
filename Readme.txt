
Problem Statement : Display Bookshelves
Website           : "https://www.urbanladder.com/"
---------------------------------------------------------------------

1) Display the name, price of

   * Bookshelves- below Rs. 15000, Storage type should be open, Including out of stock 
               Take first 3 study chair details 
   *If more than one item with same price displayed, include that details as well.

2) Display the name, price of
   * Bookshelves from brand 'By @home' , use same filters as above.

3) Verify the error message from the ‘Gift Cards’ page.



Steps of the Procedure:
----------------------------------------------------------------------

1)  Launch any browser (In this code we have used Chrome browser and Microsoft Edge browser). 
2)  Goto “https://www.urbanladder.com/”. 
3)  Scroll the page and click on ‘Bookshelves’ option. (It will take user to ‘Bookshelves’ page).
4)  Drag and drop the ‘price’ slider to Rs.15000.
5)  Choose ‘Storage Type’ as ‘Open’.
6)  Select the ‘Exclude Out Of Stock’ checkbox field.
7)  Take the list of first 3 bookshelves and print it on the console.
8)  Select the ‘By @home’ from the ‘Brand’ menu option.
9)  Take the list of all the bookshelves under 'By @home' and print it on the console. 
10) Scroll the page up and click on ‘Gift Cards’ Option. (It will take user to ‘Gift Cards’ page).
11) Click on the ‘Birthday/Anniversary’ option.
12) In the ‘Amount’ textbox, enter the amount as ‘1000’.
13) Click ‘NEXT’ Button.
14) Fill all the mandatory fields except ‘Recipient’s Email’ textbox.
15) Enter invalid value in the ‘Recipient’s Email’ textbox.
16) Click ‘CONFIRM’ Button.
17) Check whether error message is displayed.
18) Display the error message on the console.


Folders
----------------------------------------------------------------------

1) src/test/java
       i)   dataTables
            -BookShelvesBelow15000.xlsx 
            -ByAtHomeBookShelves.xlsx
            -Config.properties
            -GiftCardInput.json 
       ii)  testObjectRepository
            -HomePageBookShelves.java
            -HomePageByAtHome.java
            -HomePageGiftCards.java
       iii) testScenarios
            -DiplayBookshelves.java
       iv)  userDefinedLibraries
            -DriverSetup.java
            -ExcelWrite.java-ExplicitWait.java
            -ExtentReportManager.java
            -FailReport.java-JsonRead.java
            -PropertiesLoad.java
            -PropertiesRead.java
            -RetryFailedTestCases.java
            -RetryListener.java
            -ScreenRecorderUtil.java
            -ScreenShot.java

2) Drivers
   i)  chromedriver.exe
   ii) msedgedriver.exe

3) reports- (extent report saved here)
      
4) ScreenRecording
     
5) Screenshot



Data Driven Concepts
-----------------------------------------------------------------------
1) Properties File (Reading Data)

   * (Config.properties)- This properties file is present in        
   * This file conists of Browser name and URL value.

2) JSON File (Reading data)
    
   * (GiftCardInput.json)- This JSON file is present in      
   * This file conists of values to be entered in 'Gift Cards' form.These include values of
     -> Amount 
     -> Recipient's Name
     -> Recipient's Email
     -> Your Name
     -> Your Email
     -> Your Mobile
     -> Message

3) Excel File (Writing data)

   1. (BookShelvesBelow15000.xlsx)- This Excel file is present in    

      * The bookshelves below 15000 after applying appropriate filters are written to this file.

   2. (ByAtHomeBookShelves.xlsx)- This Excel file is present in    

      * The bookshelves under brand 'By @home' are written to this file.



Key Automation Scope
-------------------------------------------------------------------------

-> Using drag & drop
-> Locating elements precisely.
-> Using appropriate synchronization technique.
-> Extracting menu items & store in collections
-> Scrolling up and down in web page
-> Filling form (in different objects in web page)
-> Capture warning message   
-> Taking Screenshots
-> Recorder


Technology/Automation Tools Used
-------------------------------------------------------------------------
1) Selenium Webdriver and it's concepts.
2) Maven
3) TestNG framework and it's concepts.
4) Data Driven approach
5) Page Object Model
6) Extent Report/ TestNG Report
7) Excel, JSON and Property file concepts
8) Multiple Browser testing concepts
9) Java Concepts


                                  
                                  ----------------------------
                                  |                          |
                                  |      IMPORTANT NOTE      |
                                  |                          |
                                  ----------------------------

    -> For mutiple browsers (chrome and Edge), The brower name is read from 'Config.properties' file
    -> If you want to use chrome brower, please go to 'Config.properties' file and set browser name as 'chrome'.
    -> If you want to use edge brower, please go to 'Config.properties' file and set browser name as 'edge'.
    -> Then execute the Test.


 
     

   