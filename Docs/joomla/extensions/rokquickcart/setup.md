---
title: RokQuickCart - Setup Guide
description: Your Guide to Using RokQuickCart for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/rokquickcart:RokQuickCart

---

Introduction
-----

RokQuickCart is a very simple Joomla extension, which works with [SimpleCart][simplecart], that is designed to make it easy to add a cart to your site. As with any e-commerce tool, there are some important considerations to make prior to taking this component live. We have added the ability to set RokQuickCart up in a sandbox mode so you can test it prior to having transactions appear on your Google or PayPal account. We have also explained some of the important taxing and shipping considerations below.

There are two primary areas of interest when setting up the RokQuickCart component. The first area is the **RokQuickCart Configuration** page which is accessible by navigating to **Admin -> System -> Global Configuration -> RokQuickCart**. You can also visit it by selecting **Options** within the **RokQuickCart Items Manager** which is directly accessible by navigating to **Admin -> Components -> RokQuickCart**. These two pages give you the ability to configure your store on the backend.

![][setup1]

RokQuickCart also provides a great deal of configuration options on the backend that allow you to select a checkout method, currency type, add product size and color variations, manage taxes, and more.

Checkout Methods
-----

RokQuickCart supports PayPal, Google Checkout, Amazon, and custom SendForms as checkout methods.

### PayPal
If you wish to use PayPal as a checkout provider you must set up a business PayPal account (at http://www.paypal.com) and provide that business PayPal email to RokQuickCart.

#### Taxes with Paypal

When using PayPal as a checkout provider, you can add taxes into the RokQuickCart display. These will be passed on to PayPal. The Tax Rate is based on a single unit of currency (1.00). So if you want to do a 10% tax rate, you would set the tax rate field in the configuration to 0.10.

#### Shipping amounts with PayPal.

Shipping amounts with PayPal are totaled by the cart and passed to PayPal as a line item in the cart. There are four different types of shipping calculation methods:

Per Item Shipping: Shipping cost is based on the shipping cost per item. If you use a different method, make sure each cart items shipping amount is set to 0.
Flat Rate: One set shipping price for the whole order.

Quantity Rate: Shipping cost per item no matter what item it is.
Percentage of Total: Shipping cost is calculated as a percent of total sales.
The Shipping will be added as a line item

### Google Checkout

If you want to use Google Checkout as your cart processor, please follow the [instructions on signing up with Google Checkout][checkout].

At this point, RokQuickCart uses the Google Checkout HTML API. So be sure to turn OFF the "Shopping cart post security" as talked about on the Signup Page. This must be turned off for both the Sandbox and Production Google Checkout accounts in order for your cart to be processed.

#### Taxes and Shipping with Google Checkout

Taxes and Shipping for Google Checkout are handled in the Google Checkout Setup. It is based on your location and the location of the purchaser. You can customize your tax rates and shipping based on multiple rules that you define. Therefore only the tax rate is passed to Google Checkout from RokQuickCart. Google Checkout will only add the taxes and shipping in if you define it to do so in the setup.

>> NOTE: Google Checkout has been retired by Google and may no longer be available.

### Amazon Payments Checkout

Amazon Payments is one of the dealing platforms by which e-commerce sites are accepting payments. Money received through Amazon Payments Checkout is held by Amazon until confirmation of shipment occurs. This method allows the customers that already have an account with Amazon to use it to make their purchase without having to give their information to another third-party.

You can set up an account with [Amazon Payments][amazonpayments] through its official website.

Checkout Modes
-----

RokQuickCart provides both Production and Sandbox modes to allow you to easily test your cart and then switch it to production.

### SandBox Mode

Sandbox mode allows you to test the cart against the PayPal and Google Checkout Sandboxes. Using the sandbox, you can test the carts against the checkout provider and make sure they are working for your needs. When in sandbox mode no real orders will be taken, and no real charges will be applied.

You can create accounts for [the PayPal sandbox][paypalsandbox]. Please see the [PayPal developers information][info] on how to setup and use the paypal sandbox. You can also see the page on working with [Google Checkout on a Development Site][googledev] in order to get more information on using the Google Checkout Sandbox.

Amazon also has a [useful guide][amazonsandbox] outlining its sandbox protocol.

### Production Mode

Production mode will make your cart live. You can take orders and charges. It hits the main PayPal and Google Checkout sites.

When switching to Production Mode, make sure you set your Merchant ID or PayPal email to your production accounts.

Items Manager
-----

The **Items Manager** is the primary hub for creating and modifying products that appear through RokQuickCart. This is where you create, delete, and edit products that you want to make available for sale on your site. From the main Items Manager page, you are able to quickly enable and disable existing products, delete products you no longer carry, access the main RokQuickCart configuration page, edit existing products, and start the process of adding new products.

### Main Page

![][setup2]

:	1. **New** This button initiates the new product process. [17%, 6%, se]
	2. **Publish and Unpublish** These buttons give you the ability to quickly publish or unpublish selected products. Alternatively, you can click the green checkmark or red x next to the product title to toggle its state. [17%, 27%, se]
	3. **Archive** This button enables you to archive an item so it no longer appears in the primary list, but can be restored at a later date. [17%, 35%, se]
	4. **Check In** This option checks in a product so it can be edited. This is only necessary when someone has left a product editing session without properly closing the page. [17%, 41%, se]
	5. **Trash** This button will delete selected items. [17%, 48%, se]
	6. **Options** You can access the primary RokQuickCart configuration page by clicking this button. [17%, 53%, se]
	7. **Title** Clicking a product title will take you directly to its Edit page where you can adjust its individual settings. [37%, 32%, se]

1. **New**: This button initiates the new product process.

2. **Publish and Unpublish**: These buttons give you the ability to quickly publish or unpublish selected products. Alternatively, you can click the green checkmark or red x next to the product title to toggle its state.

3. **Archive**: This button enables you to archive an item so it no longer appears in the primary list, but can be restored at a later date.

4. **Check In**: This option checks in a product so it can be edited. This is only necessary when someone has left a product editing session without properly closing the page.

5. **Trash**: This button will delete selected items.

6. **Options**: You can access the primary RokQuickCart configuration page by clicking this button.

7. **Title**: Clicking a product title will take you directly to its Edit page where you can adjust its individual settings.

### Item Editor

![][setup3]

:	1. **Name** This is the name of your product that will be displayed on the products page. [19%, 28%, se]
	2. **Price** This price (in the currency you have selected on the main configuration page) is for the product itself and does not include shipping. [24%, 28%, se]
	3. **Shipping Cost** This is where you can add the shipping costs for the product that sit apart from the main product price. [30%, 28%, se]
	4. **Select an Image** You can upload a full-size image of your product here. RokQuickCart will automatically create smaller image sizes for your site. [35%, 28%, se]
	5. **Description** This is the description you wish to have appear with the product on your site. [60%, 28%, se]

1. **Name**: This is the name of your product that will be displayed on the products page.

2. **Price**: This price (in the currency you have selected on the main configuration page) is for the product itself and does not include shipping.

3. **Shipping Cost**: This is where you can add the shipping costs for the product that sit apart from the main product price

4. **Select an Image**: You can upload a full-size image of your product here. RokQuickCart will automatically create smaller image sizes for your site

5. **Description**: This is the description you wish to have appear with the product on your site. The editor is based on RocketTheme's powerful RokPad extension, allowing you much more control over how content appears on your site.

![][setup4]

:	1. **Status** You can set the status of the individual product here. An unpublished product will not appear in your active product catalog. [43%, 20%, se]
	2. **Ordering** Your product ordering is set here. [56%, 20%, se]

1. **Status**: You can set the status of the individual product here. An unpublished product will not appear in your active product catalog.

2. **Ordering**: Your product ordering is set here.

![][setup5]

:	1. **Add New** This button makes it easy to add variables to your products. If you have a product with varying details, you can add them here to avoid having to create a new item for each option. [28%, 69%, se]
	2. **Add and Remove** You can use the + and - buttons to add and remove options for users. These options appear as a drop-down on the frontend giving customers the ability to select these options prior to purchase. [57%, 40%, se]

1. **Add New**: This button makes it easy to add variables to your products. If you have a product with varying details, you can add them here to avoid having to create a new item for each option.

2. **Add and Remove**: You can use the + and - buttons to add and remove options for users. These options appear as a drop-down on the frontend giving customers the ability to select these options prior to purchase.

Setup and Configuration
-----

The main **RokQuickCart Configuration** page can be accessed by navigating to **Admin -> System -> Global Configuration -> RokQuickCart** or simply selecting **Options** in the **RokQuickCart Items Manager**. It serves as the primary configuration page to determine how RokQuickCart appears and functions.

![][config1]

:	1. **Cart Page Title** This is the title for the primary cart page that appears on the frontend of your site. [35%, 46%, se]
	2. **Shelves Per Row** This is the amount of shelves you wish to have appear side-by-side in each row on the frontend. [43%, 46%, se]
	3. **Max Image Width** This is the number of pixels in width images will max out at in your cart display. [51%, 46%, se]
	4. **Use RokBox for Full Image** Toggles the ability of the visitor to pull up a full-size copy of the product image for closer inspection. [60%, 46%, se]
	5. **Include Default CSS** Shows the default cart CSS. Set to **No** if you want to override the default template CSS with your own. [70%, 46%, se]
	6. **Same Height Shelves** Enables you to set whether or not you want the height product shelves to appear at the same height (based on the tallest one). [79%, 46%, se]


1. **Cart Page Title**: This is the title for the primary cart page that appears on the frontend of your site.

2. **Shelves Per Row**: This is the amount of shelves you wish to have appear side-by-side in each row on the frontend.

3. **Max Image Width**: This is the number of pixels in width images will max out at in your cart display.

4. **Use RokBox for Full Image**: Toggles the ability of the visitor to pull up a full-size copy of the product image for closer inspection.

5. **Include Default CSS** Shows the default cart CSS. Set to **No** if you want to override the default template CSS with your own.

6. **Same Height Shelves** Enables you to set whether or not you want the height product shelves to appear at the same height (based on the tallest one).

![][config2]

:	1. **Use Tax Rate** Toggles whether or not you wish to use the tax rate when determining the final cost of the cart. [36%, 46%, se]
	2. **Tax Rate** **Tax Rate** The tax rate to use. This is based on a single unit of currency (1.00). For a 10% tax rate, you will enter 0.10. [50%, 46%, se]
	3. **Apply Tax to Shipping** Enables you to apply tax to the shipping total. [66%, 46%, se]

1. **Use Tax Rate**: Toggles whether or not you wish to use the tax rate when determining the final cost of the cart.

2. **Tax Rate**: The tax rate to use. This is based on a single unit of currency (1.00). For a 10% tax rate, you will enter 0.10.

3. **Apply Tax to Shipping**: Enables you to apply tax to the shipping total.

![][config3]

:	1. **Checkout Mode** This option toggles between the Production and Sandbox checkout modes (see above). [38%, 30%, se]
	2. **Checkout Method** Toggles between PayPal, Google Checkout, Amazon Payments, and a Custom SendForm URL as your primary checkout service. [52%, 30%, se]
	3. **Currency** Select the currency your products are priced with. This is likely the dominant currency in your region. [66%, 30%, se]

1. **Checkout Mode**: This option toggles between the Production and Sandbox checkout modes (see above).

2. **Checkout Method**: Toggles between PayPal, Google Checkout, Amazon Payments, and a Custom SendForm URL as your primary checkout service.

3. **Currency**: Select the currency your products are priced with. This is likely the dominant currency in your region.

![][config4]

:	1. **Add Shipping** Toggles the addition of shipping costs to the total cart cost. Select **No** for free shipping. [29%, 44%, se]
	2. **Shipping Cost Calculation Method** This toggles the method by which shipping costs are calculated. You can choose between Flat Rate, Quantity Rate, Percentage of Total, and Per-Item Shipping. [40%, 49%, se]
	3. **Flat Rate Amount** If a Flat Rate shipping cost method is used, this is the flat rate for shipping that will be added to order totals. [50%, 44%, se]
	4. **Quantity Rate Amount** If a Quantity Rate shipping cost is used, this is the per-item shipping cost that will be added to order totals. [62%, 44%, se]
	5. **Percent Shipping** If the Percent Shipping cost is used, this will be the percentage of the cart total added to cover shipping. [73%, 44%, se]

1. **Add Shipping**: Toggles the addition of shipping costs to the total cart cost. Select **No** for free shipping.

2. **Shipping Cost Calculation Method**: This toggles the method by which shipping costs are calculated. You can choose between Flat Rate, Quantity Rate, Percentage of Total, and Per-Item Shipping.

3. **Flat Rate Amount**: If a Flat Rate shipping cost method is used, this is the flat rate for shipping that will be added to order totals.

4. **Quantity Rate Amount**: If a Quantity Rate shipping cost is used, this is the per-item shipping cost that will be added to order totals.

5. **Percent Shipping**: If the Percent Shipping cost is used, this will be the percentage of the cart total added to cover shipping.

![][config5]

:	1. **PayPal E-mail** This is the email account associated with your PayPal account. Payments made will go through this account. [15%, 36%, se]
	2. **Google Checkout Merchant ID** This is the Merchant ID used for Google Checkout. [30%, 36%, se]
	3. **Google Checkout Currency** This is the currency you wish to accept through Google Checkout. [36%, 36%, se]
	4. **Merchant Signature** This is the merchant signature used for Amazon Payments Checkout. [59%, 36%, se]
	5. **Merchant ID** Your Amazon Merchant ID. [65%, 36%, se]
	6. **AWS Access Key ID** Your AWS Access Key ID used for Amazon Payments Checkout. [71%, 36%, se]
	7. **Checkout URL** The URL leading to your Custom SendForm checkout. [86%, 36%, se]

1. **PayPal E-mail**: This is the email account associated with your PayPal account. Payments made will go through this account.

2. **Google Checkout Merchant ID**: This is the Merchant ID used for Google Checkout.

3. **Google Checkout Currency**: This is the currency you wish to accept through Google Checkout.

4. **Merchant Signature**: This is the merchant signature used for Amazon Payments Checkout.

5. **Merchant ID**: Your Amazon Merchant ID.

6. **AWS Access Key ID**: Your AWS Access Key ID used for Amazon Payments Checkout.

7. **Checkout URL**: The URL leading to your Custom SendForm checkout.

[checkout]: http://code.google.com/apis/checkout/developer/Google_Checkout_Shopping_Cart_Signing_Up.html
[paypalsandbox]: https://developer.paypal.com/
[info]: https://cms.paypal.com/us/cgi-bin/?cmd=_render-content&content_ID=developer/howto_testing_sandbox
[googlesandbox]: http://sandbox.google.com/checkout/sell/signup
[amazonsandbox]: https://payments.amazon.com/help/Checkout-by-Amazon/Using-the-Checkout-by-Amazon-Sandbox/Overview-of-the-Sandbox
[googledev]: http://code.google.com/apis/checkout/developer/Google_Checkout_Basic_HTML_Sandbox.html
[simplecart]: http://simplecartjs.org/
[setup1]: assets/setup_1.jpeg
[setup2]: assets/setup_2.jpeg
[setup3]: assets/setup_3.jpeg
[setup4]: assets/setup_4.jpeg
[setup5]: assets/setup_5.jpeg
[setup6]: assets/setup_6.jpeg
[setup7]: assets/setup_7.jpeg
[setup2]: assets/setup_2.jpeg
[config1]: assets/config_1.jpeg
[config2]: assets/config_2.jpeg
[config3]: assets/config_3.jpeg
[config4]: assets/config_4.jpeg
[config5]: assets/config_5.jpeg
[amazonpayments]: https://payments.amazon.com/business/html-button?ld=NSCBAGooglePA