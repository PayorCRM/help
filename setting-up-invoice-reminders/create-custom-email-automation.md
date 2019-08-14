# Customizing Email Rules

The Email rules allow you to define the customers who will receive reminders and the invoices that will be send in the reminder email.

The app runs through the rules every day to check if there are any Customers and invoices matching the rule .If a match is found , The customers defined in the rule would receive a single email with all the invoices matching the rule

![](../.gitbook/assets/emailrules.PNG)

Click on "New Emailing Rule"

Customer rules section allows you to specify which customer \(using customer number\) or group of customers \(using customer categories\) would receive the mail

Invoice rules section allows you to specify which invoices of the above selected customer needs to be sent in the reminder email.

Some common invoice rules  
1. Invoice amount greater/less than xxxx and due in y days  
2. Invoice overdue by x days  
3. invoice due in y day

![](../.gitbook/assets/image%20%282%29.png)

_Email rules to define the rules based on which the email will be sent_

### Example

In the above example as you can see the rule says that PayorCRM needs to send Customers categorized as "VIP customers " invoice reminders if they are due the next day.

_Test rules_

![](../.gitbook/assets/testrules.PNG)

Click on the test rule button to test the rule with the invoices you have currently loaded on PayorCRM.This will open up a popup with the results of the rule as of today.

Once you are satisfied with the rule , You can click on save button to save the rule.

To see more examples of Email rules go to [https://help.payorcrm.com/setting-up-invoice-reminders/examples-of-email-reminder-rules](https://help.payorcrm.com/setting-up-invoice-reminders/examples-of-email-reminder-rules) 

