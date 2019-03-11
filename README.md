# url-demo
This project demonstrates Applitools using the eyes-selenium-java3 SDK. The examples provided scan through a list of url's in the resources folder. The urls can be scanned with a local Chrome instance, a local Selenium grid with one Firefox and one Chrome instance that you must set up yourself (see https://github.com/SeleniumHQ/docker-selenium and try using docker-compose), or with the forthcoming Applitools Visual Grid. Simply shoose the corresponding testng file and run it.

When calling the testng runs you must specify your Applitools Eyes API Key in the VM options / command line for the testng file.

for example 

-DeyesAPIKey=API KEY GOES HERE
  
Specific Baselines can be set by uncommenting the code on lines 41 and 43 of LocalChrome.java
