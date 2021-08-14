

build a simplified banking system

the system has 2 types of users

1. a customer

2. an admin


customer user stories: 

- a user can create a new account with username and password

- a user starts with 0 balance

- a user can deposit more money to his account by uploading a picture of a check and entering the amount of the check. if the check is approved by an admin, the money is added to the bank account.
- /**
- * The picture can be of anything, you don't need to parse it or validate it in any way
- */


- to buy something, the user enters the amount and description; a user can only buy something if she has enough money to cover the cost.

- a user can see a list of balance changes including time and description.


admin user stories:

- an admin account is already created with a hard coded username and password.

- an admin can see a list of pending check deposit pictures with amount and picture and click to approve or deny the deposit.




***
Simplifying Assumptions 

* an admin can’t be also a customer



***
## Extra - How to deploy your application to Expo so we can test it easily

1. Create an account on expo.io;
2. Click on the dropdown menu on the top left corner (the one right next to the Expo logo) then click on the Settings icon;
3. Go to Members > Invite Member and then invite the following emails: assaf@turnoverbnb.com, rafael.0404@hotmail.com and paulo@taskuro.com (viewer permissions are enough);
4. Go to your expo app repository and on the app.json file, add the field ```"owner": "[your expo username on expo.io]"```
5. Run expo publish.

If you follow the steps correctly, the publish command generates a URL that we can use to test the application on our devices using Expo Go. Send that link with your repositories when you finish the test.
