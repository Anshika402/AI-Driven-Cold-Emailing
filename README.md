# AI-driven-Cold-Emailing

**PROJECT OVERVIEW**

The Email Automation Tool is designed to streamline the email management process by parsing and analyzing emails from Google and Outlook accounts. OAuth authentication is implemented to securely access these accounts, ensuring the confidentiality of user credentials and data. Instead of OpenAI, sentiment analysis is employed to understand the tone and context of emails, assign labels automatically, and respond accordingly. Python serves as the development language due to its compatibility with sentiment analysis libraries.

***

**TECHNOLOGIES USED**

* Python: Chosen as the primary programming language
* OAuth: To facilitate secure authentication with Gmail and Outlook APIs
* Gmail API: To access and interact with emails in Gmail accounts securely.
* Outlook API: To access and interact with emails in Outlook accounts securely.
* Bull MQ: For Task Scheduling

***

**Steps to Run the Code**

*Prerequisities*

* Python Installed on your system.
* Redis Installed on your system
* A Google Cloud Platform (GCP) project with the Gmail API enabled and OAuth 2.0 credentials set up.
* A Microsoft Azure account with the Outlook API enabled and OAuth 2.0 credentials set up.

*Setup*
* Clone the repository
* Download the 'Config.json' file provided
* Retrieve the OAuth credentials and then upload them as 'client_secret'.
* Execute the Python script - 'EmailReply.ipynb'

*Usage*
* Once the application runs, it will parse and check emails from both Google and Outlook email IDs.
* It will then use machine learning to understand the context of the emails and assign automatic labels.
* Based on the context of the emails, automated replies will be sent.

***

**RESULT**

*Email Sent*

![image](https://github.com/Anshika402/AI-driven-Cold-Emailing/assets/91580336/3d4184d6-eccc-48c3-9cb0-2b690b30735a)

*Replies*

![image](https://github.com/Anshika402/AI-driven-Cold-Emailing/assets/91580336/68a88ca0-09ab-4b4d-80dc-ece2b0a91e6e)





