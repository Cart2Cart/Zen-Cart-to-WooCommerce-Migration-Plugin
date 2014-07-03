=== Cart2Cart: Zen Cart to WooCommerce Migration ===

Contributors: Cart2Cart
Tags: zen cart to woocommerce, zen cart to woocommerce migration, migrate zen cart to woocommerce
Requires at least: 3.8.1
Tested up to: 3.8.1
Stable tag: 3.8.1
License: GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html
This plugin allows you to make your Zen Cart  to WooCommerce data migration easier than ever before.

== Description ==
This migration plugin allows you to migrate your Zen Cart data to WooCommerce with no troubles. You do not have to a technician as the whole process is automated and takes no efforts.

= Features of migration with Cart2Cart =
- **Simple** - just follow migration wizard instructions.  
- **Fast** - data move takes only a few hours. Moreover, when you have launched the migration, close your browser and wait for email notification or just watch the procedure.
- **Free Demo** - migrate up to 10 products/customers/orders for free to test the service functionality.
 
= There is a possibility to transfer from Zen Cart to WooCommerce such entities =
* Products, product images, product extra fields, product attributes, product variants;
* Customers, customer shipping address, customer billing address;
* Categories, category images;
* Orders, order statuses; 
* Reviews.

*Supported Zen Cart versions: Zen Cart 1.2.x, 1.3.x, 1.5.x 
*Supported WooCommerce versions:* 1.4.x, 1.5.x, 1.6.x, 2.0.x (new software versions are constantly being added).

**Please note.** *Cart2Cart does not perform a template migration.*

The plugin automatically installs connection bridges that allow you to perform your Zen Cart  to WooCommerce migration easily. They provide safe interaction of stores data. After you are done with bridges installation, you will be redirected to migration wizard. There Full migration can be finally completed.

= Steps to take before migration =
* Prepare for your migration and make sure that Zen Cart  and WooCommerce are accessible from web.
* Get your your Zen Cart  FTP access details from your hosting provider - you will need them to install your connection bridge.

== Installation ==
1. Download the plugin archived file.
1. Unzip plugin file to your PC.
1. Upload extracted file to wp-content/plugin directory
1. Go to Admin -> Plugins, click “Cart2Cart Zen Cart to WooCommerce Migration” to activate.
1. Paste Zen Cart FTP details and download Connection bridge files. 
1. An upload of the connection bridge for your WooCommerce store will be performed automatically.
1. Press Start Migration button and get a redirection to Cart2Cart page to complete a move.   

== Frequently Asked Questions ==

= Store images directory is not writable or doesn't exist. =
Please, create image directory and set the write permissions (chmod 777) to it and to ALL subfolders/files it contains. The reasons for the error can be the following: 
Path to image directory doesn’t exist. Create image directory.
Path to image directory doesn’t correspond to the path specified in store configuration.
There is no access permissions required. Set the write permissions (chmod -R 777 [images_dir]) to images directory and to ALL subfolders/files it contains.
The shopping cart may use non-default image directory. In this case contact Support Center of your shopping platform.

= Can I try your service before setting up paid migration? =
Yes, we provide FREE Demo Migration service that you can use before starting full migration.

You should create an account and setup the source and target carts. You will be able to check the results of a limited number of entities (up to 10 products/customers/orders). Approximate time of Demo Migration is 10-30 minutes.

You can make any changes you need and run DEMO migration again. After you are satisfied with results you can run the live migration.

= Can Cart2Cart switch domain names? =
Cart2Cart doesn’t provide the service of domain switching. Check the whole list of Services.

= Can I migrate orders without customers? =
Cart2Cart doesn't allow to migrate Orders without Customers, because this data is connected. For more details about entities that could be transferred, please check the appropriate page of your shopping cart in the category "Supported carts".

= Does Cart2Cart strip HTML from category and product name? =
In case your product or category name contain HTML tags like "<b>Some product name</b>" in source store then "<b>" and all other HTML tags will be stripped and product name will look like "Some product name" in target store.

= Invalid response received =
Сontact us at support@shopping-cart-migration.com

= An error occurred when trying to connect to your site =
Сontact us at support@shopping-cart-migration.com

= An unknown error occurred =
Сontact us at support@shopping-cart-migration.com
== Screenshots ==
1. screenshot-1.jpg
2. screenshot-2.jpg 
3. screenshot-3.jpg
 
== Changelog ==
= 1.0.0 =* Initial commit