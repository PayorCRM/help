# Setting up Auto/Recurring payments

PayorCRM allows you to setup Auto/Recurring payments using ACH / CC payment methods

Before setting up Auto/Recurring payments you will need to make sure you have setup payments in your payorCRM account. Go to  [https://help.payorcrm.com/setting-up-payments](https://help.payorcrm.com/setting-up-payments) to do that

1. To setup Auto/Recurring payments click on the Menu "Auto Payments" as shown below

![](<.gitbook/assets/image (20).png>)

&#x20;2\. Click on the "Add rule" button to create a rule.This opens up a popup where you can define the customer , the trigger and payment method to be used for Auto payments

![](<.gitbook/assets/image (27).png>)

3\. In the pop-up window that opens,  Select the customer you want to accept auto recurring payments from along with the payment method ( Card / Bank account ) and the exact card/bank account to be used for processing the payment

![Select bank account to be used for Auto Payments](<.gitbook/assets/image (15).png>)

4\. Select Auto Payment type. This defines the condition that triggers auto-payments

You have the following options to choose from

* Charge all invoices
* Charge invoices identified as Auto Pay
* Charge invoices with amount less than

**Charge all invoices** - All invoices generated for that particular customers automatically get processed using the saved card or Bank account

**Charge invoices identified as Auto Pay** - This rule processes only the invoices that were identified as to be Autopaid.Reach out to us at solutions@payorcrm.com for more details about this rule

**Charge invoices with amount less than** - This rule processes only those invoices that has payment amount less than the specified value.

5\. Charge on - This field is used to specify the trigger when the invoice needs to be processed .You could specify the no of days before or after due date on which the invoice needs to be processed.



![](<.gitbook/assets/image (5).png>)

{% hint style="info" %}
Tip - If you want all the invoices to be autopaid whenever it is created you can the set the value in "Charge on" as below

Charge on  _3000_  days _before_ due date

Since the invoices usually have "due days" \[no of days between current date and the due date] less than 3000  , They are considered for Auto Payments automatically on the day they are created.
{% endhint %}
