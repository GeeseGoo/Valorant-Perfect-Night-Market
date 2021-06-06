# Valorant-Perfect-Night-Market
A tool to get the best night market possible in valorant

## Description
FOR EDUCATIONAL PURPOSES ONLY

This repository includes a .side script meant for Selenium IDE browser extension. It can be downloaded here: https://www.selenium.dev/selenium-ide/. 
The Selenium script is for automating the process of creating a Valorant account. It is necessary to use the browser extension, as web browsers can detect if you are using a web driver. The script will take in a username, and then add a number to the end.

The python script is to get screenshots of each account's night market. If you want the data in text form, it's possible to directly use the Valorant in-game API. Please refer to this documentation for further information: https://github.com/RumbleMike/ValorantClientAPI

It's also possible to run the browsers headlessly. Click here for more information: https://selenium-python.readthedocs.io/api.html?highlight=headless# 

## Usage
### Creating the Accounts
You must enter in the email you want the accounts to be associated with, and a unique username, and a password. You can change the speed at which the commands are run, but your efficiency may be affected. 

### Viewing the Night Market
If you created your accounts using the Selenium script, Just input your username and password, and be sure to input how many accounts you created. If you want to view the night market of accounts that were not created using the script, you have to manually put them in the accounts list. The script will output images into the current directory, if you want to change it just change the path of the screenshot function. 
