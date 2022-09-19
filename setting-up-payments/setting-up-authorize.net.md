# Setting up Authorize.Net



**Credit Card Payments**

To accept credit card payments through Authorize.net , Please ensure that Customer Information Manager (CIM) is enabled for your account

To enable Customer Information Manager (CIM) service:

1. Log into your Merchant Interface at [https://account.authorize.net](https://account.authorize.net/).
2. Click **Customer Information Manager** in the main left side menu.
3. Click **Sign up for Customer Information Manager (CIM) Now**.
4. Click the checkbox labeled **I have read and understand the Terms of Service**.
5. Click **I Agree**.

**ACH payments**&#x20;

Authorize.Net also supports ACH payments along with credit card&#x20;

To be able to accept ACH payments using PayorCRM ,

* You must be a US based merchant selling to customers in the US.
* You must have an Authorize.Net account configured in PayorCRM
* Your account must be enabled for [eCheck.Net](http://www.authorize.net/solutions/merchantsolutions/merchantservices/echeck/)  processing by Authorize.Net
  * To use eCheck.Net you must submit the [eCheck.Net application](http://www.authorize.net/files/echecknetapplication.pdf)  and undergo an underwriting process.



### Configuring Authorize.Net with PayorCRM to accept Credit card and ACH payments <a href="#configuring-authorize-net-with-chargebee" id="configuring-authorize-net-with-chargebee"></a>

Follow the steps to configure Authorize.Net to accept Credit card and ACH Payments

Step 1 : On the left menu in PayorCRM click on settings

Step 2 : Under Accounts Setting > Under Pay with Credit card > Select the Processor as Authorize.Net

Step 3: Click on Active Check Box and enter the Authorize.Net Login ID and Authorize.Net Transaction key

![](<../.gitbook/assets/image (18).png>)

Step 4 : Click on Save

Step 5 : To setup ACH payments under Pay with Bank to Bank Transfer > Select the processor as Authorize.Net and enter the login Id and transaction key as above

**API Login Id** - The API Login Id can be found in your Authorize.Net Merchant Interface under _Account > Settings > Security Settings > API Login ID and Transaction Key_.

**Transaction Key** - The Transaction Key can be obtained by providing the Secret Answer to your Secret Question. Once you have that in place, copy the Transaction Key and enter it in PayorCRM.



#### Turn off Test Mode

Authorize.Net has a test mode in its production account which lets you test your connection with the payment gateway without carrying out actual charges. By default, your payment gateway account is set to "Test Mode". To carry out live transactions, ensure your Live Mode is turned on. To do this, in your Authorize.Net account, navigate to _Account > Settings > Security Settings > General Security Settings_ and set the mode to _Live_ as shown below:&#x20;

!["](https://www.chargebee.com/docs/assets/screenshots/images/authorize/testmode.png)

