
Access keys are composed of Access key ID and Secret Access key.

Similar to normal login = (username,password), Access key = (Access key ID, Secret Access key ) are permanent and long term . 

They're used to get access from CLI or programming languages.

Secret access key will be available once you create a new Access key BUT you can never see it again, so make sure to download and keep it safe.

If you lose your secret access key you have to delete and create a new access key.

Users have maximum ONE username and password but they can have maximum of TWO access keys.

Inside the AWS CLI use this command:

aws configure.  OPTIONAL: ( --profile {NAME}, if you want to give it a name for future use)


