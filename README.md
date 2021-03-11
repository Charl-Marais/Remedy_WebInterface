# Remedy_WebInterface

This is an interface to Remedy Web Portal that can be used to interact with Remedy. 
The idea is to create method to automate task done on remedy via te browser in instances 
where there is no Rest API or the Rest API is not exposed.
This will be primarily for my own use in our organisation so it may not work out of the 
box for you. This was developed on Remedy 9 with Selenium ChromeDriver.

Requirements:
Requires Selenium WebDriver. 
Remedy 9

General Concept
The goal is of this is to provide enough high level commands to users so that they can 
navigate and manipulate remedy Incidents or Workorders in order to automate managing them. 

Each page will need to be identifyable, and all elements on them must be defined such as
buttons, data tables, drop downs, etc.

Pages Exposed:
* Home Page
* Incident Search Page
* WorkOrder Page