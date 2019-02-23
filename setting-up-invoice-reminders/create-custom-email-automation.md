# Customize Email Rules

The Email rules define which customers will receive the emails and invoices will be send in the reminder email along with the email template to be used while sending the email

PayorCRM runs through the rules every day to check if there are any Customers and invoices matching the rule on a particular day.If there is a match , The customer defined in the rule would then receive a mail with all the invoices matching the rule

![](../.gitbook/assets/emailrules.PNG)

Click on "New Emailing Rule"

Customer rules section allows you to specify which customer \(using customer number\) or group of customers \(using customer categories\) would receive the mail

Invoice rules section allows you to specify which invoices of the above selected customer needs to be sent in the reminder email.

Some common invoice rules  
1. Invoice amount greater/less than xxxx  
2. Invoice overdue days in the bucket 30-60 days  
3. invoice due in 1 day

![](../.gitbook/assets/emailingrules-new.PNG)

_Email rules to define the rules based on which the email will be sent_

### Example

In the above example as you can see the rule says that PayorCRM needs to send all customers who has invoices with Invoice amount greater than 1000 and is in the 30 to 60 days overdue bucket.

_Test rules_

![](../.gitbook/assets/testrules.PNG)

Click on the test rule button to test the rule with the invoices you have currently loaded on PayorCRM.This will open up a popup with the results of the rule as of today.

Once you are satisfied with the rule , You can click on save button to save the rule.

To see more examples of Email rules go to [https://help.payorcrm.com/setting-up-invoice-reminders/examples-of-email-reminder-rules](https://help.payorcrm.com/setting-up-invoice-reminders/examples-of-email-reminder-rules) 

