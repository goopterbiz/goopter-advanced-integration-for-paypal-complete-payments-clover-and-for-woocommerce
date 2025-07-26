=== Goopter advanced integration for PayPal Complete Payments Clover and for WooCommerce ===
Contributors: goopter
Tags: woocommerce, paypal, apple pay, clover, credit card
Tested up to: 6.8
Stable tag: 1.0.10
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Integrate PayPal with WooCommerce, allowing payments via PayPal, credit/debit cards, Apple Pay, Google Pay, Venmo, or Pay Later at checkout.

== Description ==

Easily integrate PayPal and Clover with your WooCommerce store. This plugin helps you connect your PayPal and Clover accounts so customers can pay using PayPal, Clover, their preferred credit/debit cards, Apple Pay, Google Pay, Venmo, or Pay Later at checkout.

== Installation ==

= Setup for PayPal Complete Payments =

1. Open PayPal Complete Payments Settings:
   Go to Settings > PayPal Complete Payments in your WordPress admin.

2. Start Connecting Your PayPal Account:
   Click the "Start Now" button to begin the connection process.

3. Log In to PayPal:
   A PayPal popup window will open. Log in with your PayPal credentials and follow 
   the instructions.

4. Complete the Connection:
   After successfully connecting, the popup will close and a green checkmark will 
   confirm a successful setup.

5. Modify Settings (Optional):
   To adjust configuration details later, click the "Modify Setup" button in the 
   PayPal Complete Payments settings.

= Setup for Clover Payments (Required: contact Goopter Support at info@goopter.com to use this feature) =

1. Open Clover Settings:
   In your WordPress admin, go to WooCommerce > Settings > Payments > PayPal Complete Payments & Clover > Manage.
2. Enable Clover Pay:
   Tick the Enable Clover Pay checkbox.
3. Enter Your Clover Credentials:
   - Clover Merchant ID
   - Goopter Soft Descriptor
   - Goopter Webhook Secret Key
   You’ll receive these details from Goopter Support at info@goopter.com.
4. Modify Settings (Optional):
   If you plan to accept Credit Card, Google Pay or Apple Pay via Clover, disable those options under the PayPal settings to prevent conflicts.
5. Save Changes:
   Click the Save Changes button to apply your configuration.

Congratulations! Your WooCommerce store is now ready to accept payments via PayPal and/or Clover.

= Minimum Requirements =

* WooCommerce 3.0 or higher

== External Services ==
This plugin communicates with PayPal’s API or Clover's API to facilitate payment transactions. 
The PayPal or Clover API may collect information required for processing payments, such as user details, payment method, and transaction information.
By using this plugin, you agree to the following terms and conditions related to PayPal’s or Clover services:

*Service Provider: PayPal
*Terms of Use: [PayPal Terms of Service](https://www.paypal.com/us/legalhub/paypal/home)
*Privacy Policy: [PayPal Privacy Policy](https://www.paypal.com/us/legalhub/paypal/privacy-full)

*Service Provider: Clover
*Terms of Use: [Clover Terms of Service](https://www.clover.com/terms)
*Privacy Policy: [Clover Privacy Policy](https://www.clover.com/privacy-policy)

== Changelog ==

= 1.0.10 - 2025-07-25 =
* New: Initial Release
