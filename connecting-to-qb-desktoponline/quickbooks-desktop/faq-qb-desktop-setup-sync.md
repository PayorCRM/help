# FAQ - QB Desktop Setup/Sync

## I cannot find newly added invoices or customers in the app

This is most likely due to QuickBooks web-services application not syncing data to the app

To ensure that the sync is happening automatically ensure that&#x20;

* QuickBooks webconnector application is running in the background in your computer
* Ensure that the current company file open in QB Desktop application is the one that you would like to be synced

## How do i manually sync data to fix any sync issues

Click on PayorCRM option in the below screen and click on "Update Selected" button to manually sync.&#x20;

Note - Please ensure that the correct company file that needs to be synced is open on QB Desktop before following the above step

![](../../.gitbook/assets/qb-web-connector-update.png)

## What happens if I delete/have to delete an invoice in QuickBooks Desktop?



Deletions of invoice are not synced to PayorCRM due to limitations in QB Desktop sync API's. There are two ways to go about this

**Void invoices on QB Desktop instead of deleting the invoice (recommended)**

When an invoice is voided on QBD, The invoice amount as well as the due amount of the invoice is changed to $0. The invoice will then be automatically voided in PayorCRM system during the next sync

**Void invoices on PayorCRM manually after deleting the invoice in QB Desktop**

PayorCRM application also provides the ability to void invoices manually. Go to invoices view -> Select the invoice(s) to be voided -> Click on "Void invoices" button (see image below).

{% hint style="info" %}
Important : After an invoice is manually voided on PayorCRM, Please make sure that the same invoice is **deleted/voided** on QB Desktop.
{% endhint %}

<figure><img src="../../.gitbook/assets/void invoice.png" alt=""><figcaption></figcaption></figure>



