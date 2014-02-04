---
title: How to Create New Products in Magento
description: Creating new products in Magento is a fundamental step to building your online store.
tags: [Products, Tutorial, Product Management]
breadcrumb: /magento:Magento/!basic:Basic/

---

Introduction
-----

Creating products in Magento is a major step towards getting your e-commerce site ready for launch. Products are the meat and potatoes of your store, and everything else is there to make them look good, and put sales on your books.

Unfortunately, the product creation process is not as simple as filling out a form and uploading a photo. You have to take a few steps before you create that product in order to prevent headaches down the road.

For example, you should already have created attributes and attribute sets for your products before reaching this point. Why? What good is creating a product if you do not have specs to assign to it? If you have just one attribute set and a large variety of product types, then you will be stuck using the same set of variables for every product you create. You can not assign an existing product a new attribute set, and this often causes a lot of confusion to new users.

How to Create a New Product
-----

To create a new product, you will first need to navigate to the **Manage Products** page by going to **Admin Panel -> Catalog -> Manage Products**. From here, you can select the **Add New Product** button in the upper-right area of the page to initiate the creation of a new product.

### Product Settings

![][products]

The **Product Settings** page allows you to assign an **Attribute Set** and **Product Type** to the new product. It is important to remember here that once an attribute set is assigned to the product, it can not be changed. This set adds a number of variables to the product that impact how it is listed and sorted in your store.

As an example, you might have a specific attribute set created for digital cameras. This would be the set you would assign here if you are adding a digital camera to your store.

Your **Product Type** determines how your product will be listed on the frontend. For example, a **Simple** product stands on its own as an individual item. It has its own product page, and can be searched independently of other products in its category.

A **Grouped** product is a lot like a simple product on the backend, as it has its own SKU and stock management, but it is grouped with other similar products on a single product page on the frontend. An example of this would be t-shirts with the same logo or style and the only difference between them is the size and/or color.

A **Configurable** product is like a **Grouped** product in that it shares a product page with other variants, though it may also have more than one variable chosen by the customer. For example, if the customer is looking at a shirt with a specific logo on it, but they want a large one in blue. You can do this with this product type.

### Product Information

![][products2]

The next stage in product creation is much more detailed and time consuming. This is where you configure all the variables and options for that product that impact its description, name, SKU number, price, image, and more.

Since you are creating the product for the first time, you will want to make sure you have all the necessary information available at hand. This includes the SKU number you would like to assign to the product, it is stock level (inventory), any related products (if already created) that you would like to have appear on the product page to encourage up-sells and add-ons, and any other information related to the product's pricing structure.

Below, we have broken down the sections of the **Product Information** area. You can find detailed instructions on the official [Magento support site][magento].

#### General

The **General** tab gives you access to the primary aspects of your product. Its name, SKU, status, description, and visibility can be set in this menu. Additionally, you can assign a specific date range for it to appear as a **New** item on your store.

#### Price

The **Price** tab gives you access to set the product's price, special price, a data range for the special price, its cost, tax class, and tiered price. Tiered pricing allows you to set a different price for various customer types. For example, you could have wholesale customers that pay a different rate than your regular retail customers.

#### Meta Information

**Meta Information** is all about search engine optimization (SEO). This is where you set the meta keywords, description, and title for your product page.

#### Images

Images are a very important selling point for your product. In fact, Magento requires three images per product. You will need base, small, and thumbnail images for your product. If you do not upload an image to meet these requirements, a default one is used.

You can configure a default image by visiting **Admin Panel -> System -> Configuration**.

#### Recurring Profile

This tab allows you to enable or disable **Recurring Profile** for this product. Products with recurring profiles participate in the catalog as nominal items.

#### Design

The **Design** tab gives you the ability to modify the look of individual product pages. The product design overrides any design changes made to the category design option. 

You can use the **Active From** and **Active To** options to make this design change temporary. This is handy when a product is new and you would like to theme the individual product page to feature it in a different light than other items in your inventory. 

#### Gift Options

The **Gift Options** tab gives you the ability to allow or disallow gift messages in relation to the product.

#### Inventory

The **Inventory** tab is where you can go to set the initial stock quantity for the product, minimum quantity allowed in shopping carts, minimum quantity for the item to appear in stock (to make replacements possible for lost and/or damaged goods), and backorder capabilities.

#### Websites

This tab is especially useful for Magento installs with multiple websites and/or stores. Here, you will be able to assign your product to the site(s) you wish to have it sold in.

#### Categories

This is where you assign the product to a category / subcategory. A product can be assigned to multiple categories.

#### Related Products

**Related Products** allows you to let Magento know if there are any related products that would be worth promoting within the new product's page. If the product you are adding is a DSLR, you might add similar DSLR models here for customers to consider, should they be searching for something just a little different than this particular product.

#### Up-Sells

Do you have any additional products that would be complementary to the product? This is where you would put them. If the customer is buying a new camera, an appropriate up-sell would be a strap, memory card, or a lens.

#### Cross-Sells

Cross-sells appear in the shopping cart. As your customer is checking out, it is one last potential way to turn a small order into a larger one. If your online store was a physical store, this would be the candy next to the cash register.

#### Custom Options

You can add any custom options (such as details your staff would be able to fulfill) here. If you have a limited number of SKUs, this would be a good place to put variables (such as shirt size, color, etc.) in the event that you want these variations to appear under a single SKU.

[products]: assets/products_1.jpeg
[products2]: assets/products_2.jpeg
[magento]: http://www.magentocommerce.com/knowledge-base/entry/tutorial-creating-products