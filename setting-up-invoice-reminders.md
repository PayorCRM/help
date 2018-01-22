# Setting up Invoice Reminders based on rules

To automate your collections process first you will need to come up with you collections strategy .Are there certain customers / invoice amounts / dates  for which you want PayorCRM to send automated mail reminders

For eg :

* You might want to send a mail with a certain content to all customers whose invoices will be due in the next 5 dates
* You might want to send a mail with a certain content to all customers every 5 days who has invoices with Amount greater than 5000 dollars

### Step 1 : Create an email template

Initially you will have to come up with the mail template for each of these reminders.

![](http://www.payorcrm.com/wp-content/uploads/2018/01/Email-template.png "Email template screen allows you to define templates for various reminder emails")

_Click on create a new template where you could define your template look and feel and text content._

Make sure you add the variable field {invoice\_list} .This defined the position where the table with the list of invoices would go .The table would contain the fields invoice number ,amount ,due date .

### Step 2 : Define the rule

The rules define which customers will receive the emails and also defines the invoices that will be send in the email.You can also select the template that will be used to generate the email body here.

PayorCRM runs through the rules every day to check if there are any invoices matching the rule on a particular day.If there is a match , The customer defined in the rule would then receive a mail with all the invoices matching the rule

![](http://www.payorcrm.com/wp-content/uploads/2018/01/Email-Rule.png)

_Email rules to define the rules based on which the email will be sent_

##### Example

In the above example as you can see the rule says that PayorCRM needs to send the customer Sally invoices with amount greater than 10000 on a daily basis using the email template “Invoice reminder” \(created in the previous screen\).If there are no invoices with amount greater than 10000 , the email reminder wont be sent.

