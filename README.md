# Task 1: Facebook Messenger App automation

Botium currently supports automated testing of chatbots running on websites (using Selenium). The community is asking for automated testing of chatbots running within smartphone apps (using Appium). Most chatbots are running in Facebook Messenger, therefore this is the first one to support. 

The task is to create a script which:
* opens an Appium session
* installs Facebook Messenger Apps (see [here](https://medium.com/@SimonKaz/appium-test-example-download-app-from-google-play-store-6ed932663f09) how to do it)
* performs the login using given credentials
* opens the window for a given chatbot (just choose one from the available ones)
* sends a given text to the chatbot
* receives the chatbot response and output it in the console window

Other requirements:
* The script should be developed in Javascript (Node.js)
* Preferably with [Webdriver.io library](http://webdriver.io)
* The ["botium-connector-webdriverio"](https://github.com/codeforequity-at/botium-connector-webdriverio)-Module on github can be used as a starter, it uses webdriver.io for automating Facebook Messenger in a desktop browser
* With a Saucelabs trial account, there is access for several Android emulators out of the box, no need to set up Appium locally

The code will be the base for a new Botium module which will be published later on (not part of this task).
