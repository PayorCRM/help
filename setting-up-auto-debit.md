# Setting up Auto/Recurring payments

PayorCRM allows you to setup Auto/Recurring payments using ACH / CC payment methods

Before setting up Auto/Recurring payments you will need to make sure you have setup payments in your payorCRM account. Go to  [https://help.payorcrm.com/setting-up-payments](https://help.payorcrm.com/setting-up-payments) to do that

1. To setup Auto/Recurring payments click on the Menu "Auto Payments" as shown below

![](.gitbook/assets/image%20%2814%29.png)

 2. Click on the "Add rule" button to create a rule.This opens up a popup where you can define the customer , the trigger and payment method to be used for Auto payments

![](.gitbook/assets/image%20%2820%29.png)

3. In the pop-up window that opens,  Select the customer you want to accept auto recurring payments from along with the payment method \( Card / Bank account \) and the exact card/bank account to be used for processing the payment

![Select bank account to be used for Auto Payments](.gitbook/assets/image%20%289%29.png)

4. Select Auto Payment type. This defines the condition that triggers auto-payments

You have the following options to choose from

* Charge all invoices
* Charge invoices identified as Auto Pay
* Charge invoices with amount less than

**Charge all invoices** - All invoices generated for that particular customers automatically get processed using the saved card or Bank account

**Charge invoices identified as Auto Pay** - This rule processes only the invoices that were identified as to be Autopaid.This is achieved by using the comments field \(in case of QuickBooks Online \) and Memo field \( in case of QuickBooks Desktop \).

When creating an invoice using QuickBooks Online or QuickBooks Desktop ensure that the above field contains the text "AutoPay" for those invoices that needs to be considered for Auto payment

**Charge invoices with amount less than** - This rule processes only those invoices that has payment amount less than the specified value.

5. Charge on - This field used to specify the time trigger when the invoice needs to be processed .You could specify the no of days before or after due date by which the invoice needs to be processed.

![](.gitbook/assets/image%20%283%29.png)

{% hint style="info" %}
If you want all the invoices to be autopaid whenever it is created you can the set the value in "Charge on as below"

Charge on  _3000_  days _before_ due date

Since the invoices usually have a due date less than 3000 before due date when they are generated , They are considered for Auto Payments automatically
{% endhint %}

