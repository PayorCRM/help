# PayorCRM API Integration

You can make API calls to PayorCRM using the API endpoint .To be able to do that you will need to first get your account's API Secret and API key Values.You can find these in the settings screen as shown below

![](/assets/API key and secret.png)

Copy the above credentials to make API calls with PayorCRM endpoints

## Authorization

Use obtained **API Key **and **API Secret **in header as **api\_key **and **api\_secret. **

For Example:

```
    Content-Type:application/json
    api_secret: 6ed0a...3bad
    api_key: eyJ....MDk
```

## API Endpoints

#### 1. Uploading Invoices List

Send a json post request to **/jsonApi/upload/invoices**. See below for attributes you can use.

```js
POST /jsonApi/upload/invoices
Content-Type:application/json
[{
    // body of post payload. See below
}]
```

For invoice available attributes are

```js
  "companyCode": {
    "type": "string"
  },
  "profitCenter": {
    "type": "string"
  },
  "customerName": {
    "type": "string"
  },
  "customerNumber": {
    "type": "string",
    "required": true 
  },
  "accountingDocNumber": {
    "type": "string"
  },
  "invoiceNumber": {
    "type": "string",
    "required": true
  },
  "postDate": {
    "type": "date"
  },
  "dueDate": {
    "type": "date"
  },
  "paymentTerms": {
    "type": "string"
  },
  "documentType": {
    "type": "string"
  },
  "postingKey": {
    "type": "string"
  },
  "debitCreditIndicator": {
    "type": "string"
  },
  "balanceAmount": {
    "type": "string"
  },
  "billAddr": {
    "type": "json"
  },
  "shipAddr": {
    "type": "json"
  },
  "currency": {
    "type": "string"
  },
  "invoiceAmount": {
    "type": "integer",
    "required": true 
  },
  "reasonCode": {
    "type": "string"
  },
  "reasonCodeDescription": {
    "type": "string"
  },
  "fiscalYear": {
    "type": "string"
  },
  "invoiceDate": {
    "type": "date"
  },
  "reference1": {
    "type": "string"
  },
  "reference2": {
    "type": "string"
  },
  "localAmount": {
    "type": "integer"
  },
  "itemText": {
    "type": "string"
  },
  "fiscalPeriod": {
    "type": "string"
  },
  "issueDate": {
    "type": "date"
  },
  "soldTo": {
    "type": "string"
  },
  "lineItem": {
    "type": "string"
  },
  "referenceDocNo": {
    "type": "string"
  },
  "status": {
    "type": "string"
  }
```

An example Invoice payload body would be

```js
{
    customerNumber: "23123123",
    invoiceNumber: "21321",
    invoiceAmount: 12112
}
```

#### 2. Uploading Customers List

To upload customers list use endpoint **/jsonApi/upload/customers **and send post request containing array of **Customers**

For Example

```
POST /jsonApi/upload/customers
Content-Type:application/json
[{
    // body of customer. See below
}]
```

Attributes for customer object.

```
  "companyname": {
    "type": "string"
  },
  "firstname": {
    "type": "string"
  },
  "lastname": {
    "type": "string"
  },
  "phoneno": {
    "type": "string"
  },
  "emailaddress1": {
    "type": "string",
    "required": true
  },
  "customerno": {
    "type": "string",
    "required": true
  },
  "cocode": {
    "type": "string"
  }
```

An example Customer payload body would be

```
[{
    "companyname" : "Payorcrm LLC",
    "firstname" : "John",
    "lastname": "Doe",
    "phoneno": "+11122334455",
    "emailaddress1": "john@payorcrm.com",
    "customerno" : "231231201",
    "cocode": "XY22"
}]
```

> Please note that before uploading an invoice you make sure the customer already exists so that we can link that invoice to that customer. We use customerNumber field to link those invoices.



