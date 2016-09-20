# A maven project containing Selenium and Cucumber

## Setup for local development

- Rename any "settings.xml" file in your .m2 directory which may point to your company's Nexus repo, as your company's repo may not updated to have the latest dependencies contained in this project.
- Just download the required version of ChromeDrive, IE and Edge Drivers in C:/Windows, as this path already exists in the system variables and the exe will be executed when Selenium runs.
- Install PhantomJS
- In the serenity.properties file, edit the name of the driver to what you want, eg- webdriver.driver=ie, to use IE.
