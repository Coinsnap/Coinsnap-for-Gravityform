=== Coinsnap Bitcoin + Lightning payment plug-in 1.0.0 for Gravity form ===
Contributors: coinsnap
Tags: Lightning, SATS, bitcoin, Gravity form, payment gateway
Requires at least: 5.2
Tested up to: 6.4.3
Requires PHP: 7.4
Stable tag: 1.0.0
License: MIT
License URI: https://github.com/Coinsnap/Coinsnap-for-Gravityform/blob/main/license.txt


Bitcoin and Lightning payment processing with the Coinsnap add-on for Gravity form Wordpress plugin.

== Description ==

Coinsnap is a Lightning payment provider and offers a payment gateway for processing Bitcoin and Lightning payments. Website owner only needs a Lightning wallet with a lightning address to accept Bitcoin and Lightning payments on their website.

== Installation ==

### 1. Install the Coinsnap Gravity form add-on from the WordPress directory. ###

The Coinsnap Gravity form add-on can be searched and installed in the WordPress plugin directory.

In your WordPress instance, go to the Plugins > Add New section.
In the search you enter Coinsnap and get as a result the Coinsnap Gravity form plugin displayed.

Then click Install.

After successful installation, click Activate and then you can start setting up the plugin.

### 1.1. Add plugin ###

If you don’t want to install add-on directly via plugin, you can download Coinsnap Gravity form add-on from Coinsnap Github page or from WordPress directory and install it via “Upload Plugin” function:

Navigate to Plugins > Add Plugins > Upload Plugin and Select zip-archive downloaded from Github.

Click “Install now” and Coinsnap Gravity form add-on will be installed in WordPress.

After you have successfully installed the plugin, you can proceed with the connection to Coinsnap payment gateway.

### 1.2. Configure Coinsnap Gravity form add-on ###

After the Coinsnap Gravity form add-on is installed and activated, a notice appears that the plugin still needs to be configured.

### 1.3. Deposit Coinsnap data ###

* Navigate to Forms > Settings and select coinsnap
* Enter Store ID and API Key
* Click Setting Save
* Navigate to Forms > New Forms > Settings > Coinsnap > Add New Feeds and Save Settings

If you don’t have a Coinsnap account yet, you can do so via the link shown: Coinsnap Registration

### 2. Create Coinsnap account ####

### 2.1. Create a Coinsnap Account ####

Now go to the Coinsnap website at: https://app.coinsnap.io/register and open an account by entering your email address and a password of your choice.

If you are using a Lightning Wallet with Lightning Login, then you can also open a Coinsnap account with it.

### 2.2. Confirm email address ####

You will receive an email to the given email address with a confirmation link, which you have to confirm. If you do not find the email, please check your spam folder.

Then please log in to the Coinsnap backend with the appropriate credentials.

### 2.3. Set up website at Coinsnap ###

After you sign up, you will be asked to provide two pieces of information.

In the Website Name field, enter the name of your online store that you want customers to see when they check out.

In the Lightning Address field, enter the Lightning address to which the Bitcoin and Lightning transactions should be forwarded.

A Lightning address is similar to an e-mail address. Lightning payments are forwarded to this Lightning address and paid out. If you don’t have a Lightning address yet, set up a Lightning wallet that will provide you with a Lightning address.

For more information on Lightning addresses and the corresponding Lightning wallet providers, click here:
https://coinsnap.io/lightning-wallet-mit-lightning-adresse/

### 3. Connect Coinsnap account with Gravity form add-on ###

### 3.1. Gravity form Coinsnap Settings ###

* Navigate to Forms > Settings and select coinsnap
* Enter Store ID and API Key
* Click Setting Save
* Navigate to Forms > New Forms > Settings > Coinsnap > Add New Feeds and Save Settings

### 4. Test payment ###

### 4.1. Test payment in Gravity form ###

After all the settings have been made, a test payment should be made.

We make a real donation payment in our test Gravity form site.

### 4.2. Bitcoin + Lightning payment page ###

The Bitcoin + Lightning payment page is now displayed, offering the payer the option to pay with Bitcoin or also with Lightning. Both methods are integrated in the displayed QR code.

== Upgrade Notice ==

Follow updates on plugin's GitHub page:
https://github.com/Coinsnap/Coinsnap-for-Gravityform/

== Frequently Asked Questions ==

Plugin's page on Coinsnap website: https://coinsnap.io/en/

== Screenshots ==

== Changelog ==
= 1.0 :: 2024-03-03 =
* First public release for testing.