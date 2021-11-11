# Kashier-Vikwp-UI-Plugin
### Kashier Vikwp Plugins Plugin (VikBooking - VikAppointments)

 * Version: 2.0.0
 * Requires at least: 4.4
 * Tested up to: 5.4.1
 * VikBooking requires at least: Pro 1.3.x
 * VikBooking tested up to: Pro 1.3.x
 * VikAppointments requires at least: Pro 1.2
 * VikAppointments tested up to: Pro 1.2

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Vikwp-UI-Plugin/main/steps/kashier-logo.png)
![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Vikwp-UI-Plugin/main/steps/vikwp-logo.png)

### Features

- Fully PCI DSS compliant as a Level 1 Service for merchant operating in Egypt.

- I-frame integration.

- 3D secure cards authentication support.

- Support multiple payment method.

      1. Card Payments
      2. Wallet Payments 
      3. Bank Installments Payment    

- Support acquiring multiple currencies "EGP, USD, GBP, EUR".

- Plug and play.


### Installation

- Download [kashier.zip](https://raw.githubusercontent.com/Kashier-payments/Kashier-Vikwp-UI-Plugin/main/VikKashier.zip) 

- Upload and activate the plugin on Vikwp.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Vikwp-UI-Plugin/main/steps/kashier_upload.png)

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Vikwp-UI-Plugin/main/steps/kashier_activate.png)

### Obtain Test Credentials

- Login or Sign up on kashier.io https://merchant.kashier.io/

- Navigate to `Integrate now section > payment api keys`.

- Generate a new api key with your prefered name that describes your integration channel, there is 1 default api key you could use that is created when signing up.

- Copy Merchant ID visible under your user name "MID-xx-xx".

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Vikwp-UI-Plugin/main/steps/apikeytest.png)

- Navigate to `VikBooking > Global > payment methods`.

- Add a new payment method by clicking on the Add button on the top.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Vikwp-UI-Plugin/main/steps/add_kashier_payment_method.png)

- Customize the title and description of your payment method that will show up to your users.

- Choose `kashier.php` from file class list

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Vikwp-UI-Plugin/main/steps/initial_configuration_payment_method.png)

- choose payment methods which you would like to use to accept payment via kashier.

- Insert the MID and Test Api Key in the Configuration page of each payment method.

- Make sure the test mode is on.

- Save configuration.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Vikwp-UI-Plugin/main/steps/vikwp_configurtion_payment.png)

### Enable Advanced Options 

- Choose `Yes` from Enforce EGP Payment list to accept only EGP payment via kashier, Regardless what is the default currency displayed on your website.
- After Choosing `Yes` from Enforce EGP Payment list, you have to insert exchange rate from your default currency displayed on your website to EGP currency. the exchange rate must be greater than 1 .
- The next picture is example of advanced options configuration if you display USD currency by default on your website, but you want customers to only pay by EGP currency via kashier payment method. 

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-vikwp-UI-Plugin/main/steps/advanced_options.png)

### Go live

- After activating your account.

- Make sure you are on live mode.

- `Navigate to Integrate now section > payment api keys`.

- Generate a new api key with your prefered name that describes your integration channel, there is 1 default api key you could use that is created when signing up.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Vikwp-UI-Plugin/main/steps/apikeylive.png)

- Insert Live Api Key in the Configuration page of each module.

- Save configuration.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Vikwp-UI-Plugin/main/steps/vikwp_configuration_live.png)


### Support

- Leave us an inquiry ticket on https://kashier.io for questions.
