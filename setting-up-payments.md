# Setting up payments

To setup payments do the following steps

* Click on the settings button in the menu
* ![](.gitbook/assets/settings.JPG)
* Select Account settings from the tab

![](.gitbook/assets/account-settings.JPG)

* You can see three different methods through which a customer of yours can pay you
  * Pay by Multiple
  * Pay by Credit card
  * Pay using Bank to Bank transfer methods

Below are the list of gateways & Banks we support for a demo account under each of these categories

Pay by Credit card

1. Paypal \(world wide\)
2. QuickBooks payments \(you should already have an account with QuickBooks payments to be able to use this\)
3. Authorise.net
4. JP Morgan Chase \(wepay\)

Pay using Bank to Bank transfer methods

1. All banks in India through internet banking \(PayU\)
2. All US banks \( US ACH payments\)
3. QuickBooks payments \(US ACH payments\)
4. Authorise.net
5. JP Morgan Chase \(wepay\)

We support other processors and banks other than the above listed for paid accounts.Please contact us \(solutions@payorcrm.com\) for an upgrade .

## Setting credit card payments {#credit-card-payments}

### 1.Setting up paypal

To accept credit card payments through Paypal you should first create a paypal account for your business

.If you have created an account with

1. [PayPal](https://www.paypal.com/) , login, else Signup
2. Go to [PayPal Developers](https://developer.paypal.com/)
3. Scroll down and click on Create App button under REST API apps

   ![](https://snappy.appypie.com/ckeditor/plugins/imageuploader/uploads//4269e5a11.png)

4. Provide required information, and click on Create App button

   ![](https://snappy.appypie.com/ckeditor/plugins/imageuploader/uploads//427e3800f.png)

5. Switch to Live tab \( Use only the credentials from live app on PayorCRM\)

   ![](https://snappy.appypie.com/ckeditor/plugins/imageuploader/uploads//428efd80c.png)

6. Look for your client id and Secret key

![](.gitbook/assets/paypal-securitykey.png)

Copy and paste the above in the settings screen of PayorCRM and save

![](.gitbook/assets/payorcrm-paypal-security.PNG)

## Setting up bank to bank transfer payments

You could accept payments directly to your bank account by using the following methods

* QuickBooks payments \(US only \)
* US ACH services provided by banks 

### 1.QuickBook payments

QuickBooks in US provides the ability to accept payments.By integrating with QuickBooks to PayorCRM\( logging in using your QuickBooks account to PayorCRM\) . you will be automatically able to accept payments directly .

Details about QuickBooks payments. See [link ](https://quickbooks.intuit.com/payments/)

### 2.US ACH services provided by banks

Almost all US bank provide you the ability to accept payments directly to your bank account.To start accepting payments through this mode you would need to contact your Account Manager to set it up for you.

Please contact _solutions@payorCRM.com_ if you need help through the setup.The below screenshot shows all the configuration information that needs to be filled to set this up

![](.gitbook/assets/us-ach-setup.png)

See links to ACH services provided by some US banks \(incomplete list\)

Bank of America -[ https://www.bofaml.com/en-us/content/ach.html](https://www.bofaml.com/en-us/content/ach.html)

PNC bank - [https://www.pnc.com/en/corporate-and-institutional/treasury-management/payables/automated-clearing-house--ach.html](https://www.pnc.com/en/corporate-and-institutional/treasury-management/payables/automated-clearing-house--ach.html)

US bank - [https://www.usbank.com/small-business/making-payments/singlepoint-essentials-ach.html](https://www.usbank.com/small-business/making-payments/singlepoint-essentials-ach.html)

JP Morgan -[ https://www.jpmorgan.com/tss/General/Automated\_Clearing\_House/1155043013622](https://www.jpmorgan.com/tss/General/Automated_Clearing_House/1155043013622)

