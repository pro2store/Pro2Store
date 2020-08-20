# Welcome BETA testers! 👋

# NEW BETA TODAY 20th AUG

See Changlog here: https://headwayapp.co/pro2store-changelog

# BETA (20th Aug) DOWNLOAD HERE:  <a href="https://we.tl/t-4CFa9g23c1"> GET THE BETA </a>

Please use this Repository's <a href="https://github.com/pro2store/Pro2Store/issues"> Issues tab </a> to report issues.

Please only report bugs, issues and errors. If you wish to discuss feature requests, please join the Gitter: https://gitter.im/pro2store/community?utm_source=share-link&utm_medium=link&utm_campaign=share-link

Thank You!

Read announcement Issue here: <a href="https://github.com/pro2store/Pro2Store/issues/1"> Announcement Issue </a>  

## Read the 10th Aug Update here: <a href="https://github.com/pro2store/Pro2Store/issues/1"> Issue Updated </a>   

## Installation and Setup instructions:

**Step 1:** Install the package file as you would any Joomla package

**Step 2:** Go to "Extensions >> Manage" and search for "pro2store". Make sure all plugins, modules, components and libraries are enabled. The instal script should take care fo this, but please make sure everything installed correctly.

**Step 3:** Set up a shop category and a few articles to get your shop started. Do this in the Joomla Article manager

**Step 4:** Set up your templates in Yootheme Pro. Drag and drop the new Pro2Store elements into your templates. 

**NOTE You need to enable jQuery in your Yootheme Settings**

**Step 5:** Activate your Joomla articles as Pro2store Products. Go to the "Pro2Store Activation" tab in the article edit. Select "Yes" and save.

**Step 6:** Add Product data to your products. Again this is done in the article manager under the tab "Pro2Store Fields".

**Step 7:** Set up a currency (you might need to do this earlier in the process... depends what errors are thrown). Do this in the Pro2Store component.

**Step 8:** Go to the Pro2Store component params and set up your values. You can set things like empty cart redirects and terms and conditions pages etc here.

**Step 9:** At the moment I only have Stripe Checkout working for the checkout. So go to the Stripe Checkout plugin and enter some test API Keys.

**Step 10:** Set up your Checkout. <a href="https://www.youtube.com/watch?v=NVi9_P24Fno"> WATCH VIDEO HERE </a> At the moment the checkout system is a collection of Joomla Modules. So first create a Joomla Article for your checkout and set it as a Yootheme Builder page. Now drop in the modules and arrange them as you wish. These are: 

* **mod_protostorecartsummary** - Displays a summary of the checkout totals - subtotal, shipping total, grand total etc.

* **mod_protostorecartuser** - Module for allowing the user to login and register "in-checkout". Also manages addresses for the order.

* **mod_protostorecheckoutitems** - Displays a list of the items being ordered

* **mod_protostorecheckoutpaymentbuttons** - Displays the checkout buttons for whatever payment plugins are enabled (Stripe Checkout only at the moment)

* **mod_protostorecouponfield** - Displays a text field for entering discount codes (these can be managed via the Pro2Store component)

These modules work independantly of each other, so if you wish to build a multipage checkout, you're welcome to. This feature is not heavily tested so please report your findings on this.

**Step 11:** Set up Stripe  <a href="https://www.youtube.com/watch?v=aFq8BQVjo4U"> WATCH VIDEO HERE </a>. You'll need to set up a webhook in the Stripe Dash. Watch the video for a guide. Copy endpoint URL: _index.php?option=com_protostore_


**Step 12:** Make a few test orders! :)

**Step 13:** Come on to Github and tell me how you get on. Use the issue tracker to let me know if you spot any bugs etc.
