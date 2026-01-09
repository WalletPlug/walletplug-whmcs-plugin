<h1>WalletPlug WHMCS Plugin</h1>
<p>
Accept local and international payments in WHMCS using WalletPlug multi currency wallets cards and global payment APIs.
</p>

<hr>

<h2>Quick Installation Guide</h2>

<h3>1 Download and Upload</h3>
<p>
Upload the plugin zip to your WHMCS root folder and extract it.
</p>
<p>Make sure these files exist:</p>

<pre>
/modules/gateways/walletplug.php
/modules/gateways/callback/walletplug.php
</pre>

<hr>

<h3>2 Activate in WHMCS</h3>
<p>Log in to your WHMCS admin panel and go to:</p>

<pre>
Setup → Payments → Payment Gateways
</pre>

<p>
Select <strong>WalletPlug</strong> and click <strong>Activate</strong>.
</p>

<hr>

<h3>3 Configure API Credentials</h3>

<p>Enter the following values:</p>

<ul>
  <li><strong>API Base URL</strong><br>walletplug</li>
  <li><strong>Merchant ID and API Key</strong><br>From your WalletPlug dashboard</li>
  <li><strong>Webhook Secret Key</strong><br>From your WalletPlug dashboard</li>
  <li><strong>Test Mode</strong><br>Enable for sandbox testing</li>
</ul>

<p>Click <strong>Save Changes</strong>.</p>

<hr>

<h3>4 Set Webhook Callback</h3>

<p>In your WalletPlug dashboard, set the webhook URL to:</p>

<pre>
walletplug/modules/gateways/callback/walletplug php
</pre>

<p>
Make sure the Webhook Secret Key matches in both systems.
</p>

<hr>

<h3>5 Test and Go Live</h3>

<ul>
  <li>Create a test invoice in WHMCS</li>
  <li>Complete a sandbox payment</li>
</ul>

<p>
Once successful, disable <strong>Test Mode</strong> to start accepting live payments.
</p>

<hr>

<h2>Support</h2>

<p>
If you need help installing or using the WalletPlug WHMCS plugin, contact our developer support team.
</p>

<p>
<strong>Email</strong><br>
dev@walletplug.com
</p>

<p>Our team can help with:</p>

<ul>
  <li>Plugin setup</li>
  <li>API keys</li>
  <li>Webhook configuration</li>
  <li>Live mode activation</li>
</ul>
