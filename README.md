# Swiggy

Swiggy Project Steps Which I did to complete this project

First I created a maven project named ‘ SwiggyProject ’.
All cucumber related dependencies are added in pom.xml
‘chromedriver.exe’ is added in resource folder.
Created one feature file named ‘food_order.feature’ in Features folder where test scenario is described using Gherkin language.
Created ‘in.swiggy.testscripts’ package
Created ‘in.swiggy.pages’ package
Created one java class named ‘ OrderFoodSteps’ to define the steps in food_order.feature file scenario
Created one TestRunner class where I given connection to feature file and glue code
Used hooks ‘Before After’ which enables to setUp and teardown browser
Created one Driver.Java class file where all objects of page classes are instantiated
Created one Tools.Java class to create static WebDriver object (driver) which is used by all classes by extending this class
Created LandingPage.Java class to locate different webelements in landing page of the Swiggy Application
Created RestaurentPage.java class to locate the webelements in next page where all restaurents present with the given location in landing page
Created AllFoodItemsPage.java class to locate the web elements in next page where all food items are present in selected restaurant
Created CheckOutPage.java class to locate the webelements in checkout page of the application
Created TestNg class to run different test scenarios in in.swiggy.testscripts package
HTML reports are generated.
After the project is successfully executed,it is pushed to gitHub.
Here is my GitHub repository url
https://github.com/Sakunthala84/Swiggy.git
Following Are Used To Complete the Project

• Eclipse as IDE • Java Development Kit Version 8 • Selenium standalone server Version 3.141.59 • TestNG • Cucumber

Following concepts are Implemented

• Cucumber (feature file, glue code, Hooks, html reports) • Selenium • Page Object Model • Use a Maven project • GitHub(To push the code) Git Hub Repository Url
