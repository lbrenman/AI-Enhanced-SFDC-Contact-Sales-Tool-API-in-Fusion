# Amplify Fusion Enhanced Contacts API

Enhanced contact API created in Amplify Fusion that demonstrates how to leverage the OpenAI API in a sales operation example. The contacts are retrieved from Salesforce using Fusion's Salesforce connector and enhanced using the OpenAI API and a prompt that provides the contact details including contact name, account name and industry and recent activity for the contact. Currently the recent activity is retrieved from the contact's description field. In a real work example, you can look at the contacts activity and other related data in Salesforce. The prompt provides the data and requests insights, talking points and next steps as illustrated below:

![Imgur](https://i.imgur.com/vT8Iyow.png)

* You can read more about how the prompt was engineered as well as the details of the OpenAI API call and response [here](https://gist.github.com/lbrenman/67ee78c716210448cb2605c8f5d6b2b7).
* The Open API Specification used to create the API in Fusion is in this repo in the file `enhancedcontact.json` [here](https://github.com/lbrenman/AI-Enhanced-SFDC-Contact-Sales-Tool-API-in-Fusion/blob/master/enhancedcontact.json).
* You can see the use case in action in a Nodejs Web app [here](https://github.com/lbrenman/enhanced-contact-nodejs-web-app)
* Some screen shots from the Fusion project are shown below:
![Imgur](https://i.imgur.com/5lso8e6.png)
![Imgur](https://i.imgur.com/iDNnZAf.png)
![Imgur](https://i.imgur.com/VeeeD5S.png)
![Imgur](https://i.imgur.com/Q7hN7GF.png) 