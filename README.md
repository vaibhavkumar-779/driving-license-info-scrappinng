# Diving-License-Info-Scrappinng
# OBJECTIVE
Creating a record of driving license information from parivahan website(https://parivahan.gov.in/rcdlstatus/?pur_cd=101)

# ABOUT
 Here we have used python library Selenium to control webdriver of browser since this library is used for automation.
 The python code reads the location of the tabs where information is to be enter and marks them.
 The input is taken from user regarding the License number and Date of birth to login on the page.
 The captcha is entered manually by the user.
 The fields containing the information are marked.
 A json format dictionary is created and that extracted info is filled in it
 This is converted to json file info and fed into variable named data
 The answer is printed then.
 
 # PREREQUISITE
 1. webdriver(I have used chromedriver since I had Google Chrome in my system.You can use any other Just replace it from   webdriver code)
 2. selenium library(check if you have it in your system or not. Otherwise install it using "pip install selenium on terminal"
 3. Browser(preferably Chrome)
 4. Internet
