# gmail-simplifier
An app to pull out relevant emails from your gmail account to more easily get the information you require and process it accordingly.

### For exhaustive documentation, check out the project [wiki](https://github.com/baishali-ghosh/gmail-simplifier/wiki)

### Please report any bugs or issues [here](https://github.com/baishali-ghosh/gmail-simplifier/issues)

#### Installation instructions
* Install the latest edition of Node.js from [here](https://nodejs.org/en/download/)
* Install all dependencies with `npm i --silent`
* Navigate to [Google Developer Console] (https://console.developers.google.com/flows/enableapi?apiid=gmail) to setup an OAuth client ID.
* Create a project to which you want to add credentials
* Click on Credentials tab Add credentials to your project page.
* Select Gmail API in the dropdown for "Which API you are using?"
* Choose where you will be calling the API from
* Set what data you will be accessing as "User Data"
* Click on the created credential and in restricted section, set the Authorized redirect URIs as "http://localhost:(port_number)"
* Save the generated JSON file.
* Move this file to your working directory and rename it client_secret.json. 


### Build and Execution
* npm quickstart.js
