# Setup Email Rules

The Email rules allow you to define the customers who will receive reminders and the invoices that will be send in the reminder email.

The app runs through the rules every day to check if there are any Customers and invoices matching the rule .If a match is found , The customers defined in the "**customer rule selection"** would receive a single email with all the invoices matching the **"invoice rule selection"**

### **Setting up a New Email Rule**

1. Click on the "New Emailing Rule" Button



![](../.gitbook/assets/emailrules.PNG)

2. This will open up the below given screen

![](../.gitbook/assets/image%20%2831%29.png)



3. There are 2 parts to a rule

**Customer selection condition**  - Here you can define how customers are selected when the rule runs everyday 

![](../.gitbook/assets/image%20%2822%29.png)

**Invoice selection condition** - Here you can define out of the customers selected in the customer selection rule , What invoices needs to be picked up on a particular day.

Some common invoice rules  
1. Invoice amount greater/less than xxxx and due in y days  
2. Invoice overdue by x days  
3. invoice due in y day



**Test the rule**

![](../.gitbook/assets/testrules.PNG)

Click on the test rule button will run the rule for the invoices you have currently loaded on PayorCRM.This will open up a popup with the results of the rule as of today.

Once you are satisfied with the rule , You can click on save button to save the rule.

To see examples of Email rules go to [https://help.payorcrm.com/setting-up-invoice-reminders/examples-of-email-reminder-rules](https://help.payorcrm.com/setting-up-invoice-reminders/examples-of-email-reminder-rules) 

