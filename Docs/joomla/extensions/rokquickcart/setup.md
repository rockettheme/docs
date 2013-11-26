---
title: RokQuickCart - Setup Guide
description: Your Guide to Using RokQuickCart for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/rokquickcart:RokQuickCart

---

Introduction
-----

RokQuickCart is a very simple Joomla extension that's designed to make it easy to add a cart to your site. As with any e-commerce tool, there are some important considerations to make prior to taking this component live. We have added the ability to set RokQuickCart up in a sandbox mode so you can test it prior to having transactions appear on your Google or PayPal account. We've also explained some of the important taxing and shipping considerations below.

There are two primary areas of interest when setting up the RokQuickCart component. The first area is the **RokQuickCart Configuration** page which is accessible by navigating to **Admin -> System -> Global Configuration -> RokQuickCart**. You can also visit it by selecting **Options** within the **RokQuickCart Items Manager** which is directly accessible by navigating to **Admin -> Components -> RokQuickCart**. These two pages give you the ability to configure your store on the backend.

![][setup1]

RokQuickCart also provides a great deal of configuration options on the backend that allow you to select a checkout method, currency type, add product size and color variations, manage taxes, and more.

Checkout Methods
-----

RokQuickCart supports both PayPal and Google Checkout as checkout methods.

### PayPal
If you wish to use PayPal as a checkout provider you must set up a business PayPal account (at http://www.paypal.com) and provide that business PayPal email to RokQuickCart.

#### Taxes with Paypal

When using PayPal as a checkout provider, you can add taxes into the RokQuickCart display. These will be passed on to PayPal. The taxes as a simple Tax Amount. The Tax Rate is based on a single unit of currency (1.00). So if you want to do a 10% tax rate, you would set the tax rate field in the configuration to 0.10.

#### Shipping amounts with PayPal.

Shipping amounts with PayPal are totaled by the cart and passed to PayPal as a line item in the cart. There are four different types of shipping calculation methods:

Per Item Shipping: Shipping cost is based on the shipping cost per item. If you use a different method, make sure each cart items shipping amount is set to 0.
Flat Rate: One set shipping price for the whole order.
Quantity Rate: Shipping cost per item no matter what item it is.
Percentage of Total: Shipping cost is calculated as a percent of total sales.
The Shipping will be added as a line item

### Google Checkout

If you want to use Google Checkout as your cart processor, please follow the [instructions on signing up with Google Checkout][checkout]. Following these instructions you will signup

At this point, RokQuickCart uses the Google Checkout HTML API. Sp be sure to turn OFF the "Shopping cart post security" as talked about on the Signup Page. This must be turned off for both the Sandbox and Production Google Checkout accounts in order for your cart to be processed.

#### Taxes and Shipping with Google Checkout

Taxes and Shipping for Google Checkout are handled in the Google Checkout Setup. It is based on your location and the location of the purchaser. You can customize your tax rates and shipping based on multiple rules that you define. There for only the tax rate is passed to Google Checkout from RokQuickCart. Google Checkout will only add the taxes and shipping in if you define it to do so in the setup.

Checkout Modes
-----

RokQuickCart provides both Production and Sandbox modes to allow you to easily test your cart and the switch it to production.

### SandBox Mode

Sandbox mode allows you to test the cart against the PayPal and Google Checkout Sandboxes. Using your sandbox ids, you can test the carts against the checkout provider and make sure they are working for your needs. When in sandbox mode no real orders will be taken, and no real charges will be applied.

#### PayPal Sandbox

You can create accounts for [the PayPal sandbox][paypalsandbox]. Please see the [PayPal developers information][info] on how to setup and use the paypal sandbox.

#### Google Checkout Sandbox

You can [create a Google Checkout Sandbox account][googlesandbox] by signing up. Please see the page on working with [Google Checkout on a Development Site][googledev] in order to get more information on using the Google Checkout Sandbox.

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

:	1. **Name** This is the name of your product that will be displayed on the products page. [14%, 31%, se]
	2. **Price** This price (in the currency you've selected on the main configuration page) is for the product itself and does not include shipping. [19%, 31%, se]
	3. **Shipping Cost** This is where you can add the shipping costs for the product that sit apart from the main product price. [25%, 31%, se]
	4. **Select an Image** You can upload a full-size image of your product here. RokQuickCart will automatically create smaller image sizes for your site. [30%, 31%, se]
	5. **Description** This is the description you wish to have appear with the product on your site. [55%, 31%, se]

1. **Name**: This is the name of your product that will be displayed on the products page.

2. **Price**: This price (in the currency you've selected on the main configuration page) is for the product itself and does not include shipping.

3. **Shipping Cost**: This is where you can add the shipping costs for the product that sit apart from the main product price

4. **Select an Image**: You can upload a full-size image of your product here. RokQuickCart will automatically create smaller image sizes for your site

5. **Description**: This is the description you wish to have appear with the product on your site.

![][setup4]

:	1. **Status** You can set the status of the individual product here. An unpublished product will not appear in your active product catalog. [43%, 20%, se]
	2. **Ordering** Your product ordering is set here. [56%, 20%, se]

1. **Status**: You can set the status of the individual product here. An unpublished product will not appear in your active product catalog.

2. **Ordering**: Your product ordering is set here.

![][setup5]

:	1. **Show Sizes** This toggle will enable you to add different sizes to the product. This allows you to list different clothing sizes without creating a new product for every size. [31%, 46%, se]
	2. **Sizes** Click this button to add sizes to the product listing. [44%, 46%, se]
	3. **Show Colors** This toggle will enable you to add different colors to the product listing. When selling products that come in a variety of colors (such as shirts) it will save you from having to build individual products. [57%, 46%, se]
	4. **Colors** Click this button to add colors to the product listing. [70%, 46%, se]

1. **Show Sizes**: This toggle will enable you to add different sizes to the product. This allows you to list different clothing sizes without creating a new product for every size.

2. **Sizes**: Click this button to add sizes to the product listing.

3. **Show Colors**: This toggle will enable you to add different colors to the product listing. When selling products that come in a variety of colors (such as shirts) it will save you from having to build individual products.

4. **Colors**: Click this button to add colors to the product listing.

Configuration
-----

The main **RokQuickCart Configuration** page can be accessed by navigating to **Admin -> System -> Global Configuration -> RokQuickCart** or simply selecting **Options** in the **RokQuickCart Items Manager**. It serves as the primary configuration page to determine how RokQuickCart appears and functions.

![][setup6]

:	1. **Cart Page Title** This is the title for the primary cart page that appears on the frontend of your site. [20%, 46%, se]
	2. **Page Columns** This option sets the number of product columns that will appear on the page. [27%, 46%, se]
	3. **Shelf Item Width** The width of the shelf in pixels. This number should fit your content layout. [34%, 46%, se]
	4. **Shelf Image Width** The width (in pixels) of the product image that appears on the shelf. [40%, 46%, se]
	5. **Cart Item Height** The height (in pixels) of items that appear in the Cart. [46%, 46%, se]
	6. **Cart Image Width** The width (in pixels) of the product image that appears in the Cart. [52%, 46%, se]
	7. **Use RokBox for Full Image** Toggles the ability of the visitor to pull up a full-size copy of the product image for closer inspection. [60%, 46%, se]
	8. **Include Default CSS** Shows the default cart CSS. Set to **No** if you want to override the default template CSS with your own. [70%, 46%, se]
	9. **Use Tax Rate** Toggles whether or not you wish to use the tax rate when determining the final cost of the cart. [83%, 46%, se]

1. **Cart Page Title**: This is the title for the primary cart page that appears on the frontend of your site.

2. **Page Columns**: This option sets the number of product columns that will appear on the page.

3. **Shelf Item Width**: The width of the shelf in pixels. This number should fit your content layout.

4. **Shelf Image Width**: The width (in pixels) of the product image that appears on the shelf.

5. **Cart Item Height**: The height (in pixels) of items that appear in the Cart.

6. **Cart Image Width**: The width (in pixels) of the product image that appears in the Cart.

7. **Use RokBox for Full Image**: Toggles the ability of the visitor to pull up a full-size copy of the product image for closer inspection.

8. **Include Default CSS**: Shows the default cart CSS. Set to **No** if you want to override the default template CSS with your own.

9. **Use Tax Rate**: Toggles whether or not you wish to use the tax rate when determining the final cost of the cart.

![][setup7]

:	1. **Tax Rate** The tax rate to use. This is based on a single unit of currency (1.00). For a 10% tax rate, you'll enter 0.10. [9%, 44%, se]
	2. **Checkout Mode** This option toggles between the Production and Sandbox checkout modes (see above). [18%, 44%, se]
	3. **Checkout Method** Toggles between PayPal and Google Checkout as your primary checkout service. [26%, 44%, se]
	4. **PayPal E-mail** This is the email account associated with your PayPal account. Payments made will go through this account. [37%, 44%, se]
	5. **PayPal Currency** Select the currency your products are priced with. This is likely the dominant currency in your region. [43%, 44%, se]
	6. **Add Shipping** Toggles the addition of shipping costs to the total cart cost. Select **No** for free shipping. [49%, 44%, se]
	7. **Shipping Cost Calculation Method** This toggles the method by which shipping costs are calculated. You can choose between Flat Rate, Quantity Rate, Percentage of Total, and Per-Item Shipping. [56%, 49%, se]
	8. **Flat Rate Amount** If a Flat Rate shipping cost method is used, this is the flat rate for shipping that will be added to order totals. [62%, 44%, se]
	9. **Quantity Rate Amount** If a Quantity Rate shipping cost is used, this is the per-item shipping cost that will be added to order totals. [67%, 44%, se]
	10. **Percent Shipping** If the Percent Shipping cost is used, this will be the percentage of the cart total added to cover shipping. [73%, 44%, se]
	11. **Google Checkout Merchant ID** This is the Merchant ID used for Google Checkout. [82%, 44%, se]
	13. **Google Checkout Currency** This is the currency you wish to accept through Google Checkout. [87%, 44%, se]

1. **Tax Rate**: The tax rate to use. This is based on a single unit of currency (1.00). For a 10% tax rate, you'll enter 0.10

2. **Checkout Mode**: This option toggles between the Production and Sandbox checkout modes (see above).

3. **Checkout Method**: Toggles between PayPal and Google Checkout as your primary checkout service.

4. **PayPal E-mail**: This is the email account associated with your PayPal account. Payments made will go through this account.

5. **PayPal Currency**: Select the currency your products are priced with. This is likely the dominant currency in your region.

6. **Add Shipping**: Toggles the addition of shipping costs to the total cart cost. Select **No** for free shipping.

7. **Shipping Cost Calculation Method**: This toggles the method by which shipping costs are calculated. You can choose between Flat Rate, Quantity Rate, Percentage of Total, and Per-Item Shipping.

8. **Flat Rate Amount**: If a Flat Rate shipping cost method is used, this is the flat rate for shipping that will be added to order totals.

9. **Quantity Rate Amount**: If a Quantity Rate shipping cost is used, this is the per-item shipping cost that will be added to order totals.

10. **Percent Shipping**: If the Percent Shipping cost is used, this will be the percentage of the cart total added to cover shipping.

11. **Google Checkout Merchant ID**: This is the Merchant ID used for Google Checkout.

13. **Google Checkout Currency**: This is the currency you wish to accept through Google Checkout.


[checkout]: http://code.google.com/apis/checkout/developer/Google_Checkout_Shopping_Cart_Signing_Up.html
[paypalsandbox]: https://developer.paypal.com/
[info]: https://cms.paypal.com/us/cgi-bin/?cmd=_render-content&content_ID=developer/howto_testing_sandbox
[googlesandbox]: http://sandbox.google.com/checkout/sell/signup
[googledev]: http://code.google.com/apis/checkout/developer/Google_Checkout_Basic_HTML_Sandbox.html
[setup1]: assets/setup_1.jpeg
[setup2]: assets/setup_2.jpeg
[setup3]: assets/setup_3.jpeg
[setup4]: assets/setup_4.jpeg
[setup5]: assets/setup_5.jpeg
[setup6]: assets/setup_6.jpeg
[setup7]: assets/setup_7.jpeg
[setup2]: assets/setup_2.jpeg