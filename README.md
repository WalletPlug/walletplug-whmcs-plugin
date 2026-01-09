WalletPlug WHMCS Plugin

Accept local and international payments in WHMCS using WalletPlug multi currency wallets cards and global payment APIs.

Quick Installation Guide

1 Download and Upload

Upload the plugin zip to your WHMCS root folder and extract it.
Make sure these files exist:

/modules/gateways/walletplug.php  
/modules/gateways/callback/walletplug.php

---------------------------------------------
2 Activate in WHMCS

Log in to your WHMCS admin panel and go to:

Setup → Payments → Payment Gateways

Select WalletPlug and click Activate
----------------------------------------------

3 Configure API Credentials

Enter the following values:

API Base URL
walletplug com

Merchant ID and API Key
From your WalletPlug dashboard

Webhook Secret Key
From your WalletPlug dashboard

Test Mode
Enable for sandbox testing

Click Save Changes

===============================================

4 Set Webhook Callback

In your WalletPlug dashboard, set the webhook URL to:

walletplug com/modules/gateways/callback/walletplug php


Make sure the Webhook Secret Key matches in both systems.

===============================================

5 Test and Go Live

Create a test invoice in WHMCS
Complete a sandbox payment

Once successful, disable Test Mode to start accepting real payments.

================================================


Support

If you need help installing or using the WalletPlug WHMCS plugin, contact our developer support team:

Email
devt@walletplug.com

Our team can help with:
Plugin setup
API keys
Webhook configuration
Live mode activation
