# Welcome BETA testers! 👋

Please use this Repository's <a href="https://github.com/pro2store/Pro2Store/issues"> Issues tab </a> to report issues.

Please only report bugs, issues and errors. If you wish to discuss feature requests, please use this form: <a target="_blank" href="https://pro2.store/pro2store-specification">Feedback Form</a>.
  
Thank You!


## Installation and Setup instructions:

**Step 1:** Install the package file as you would any Joomla package

**Step 2:** Go to "Extensions >> Manage" and search for "pro2store". Make sure all plugins, modules, components and libraries are enabled. the instal script should take care fo this, but please make sure everything installed correctly.

**Step 3:** Set up a shop category and a few articles to get your shop started. Do this in the Joomla Article manager

**Step 4:** set up your templates in Yootheme Pro. Drag and drop the new Pro2Store elements into your templates.

**Step 5:** Activate your Joomla articles as Pro2store Products. Go to the "Pro2Store ACtivation" tab in the article edit. Select "Yes" and save.

**Step 6:** Add Product data to your products. Again this is done in the article manager under the tab "Pro2Store Fields".

**Step 7:** Set up a currency (you might need to do this earlier in the process... depends what errors are thrown). Do this in the Pro2Store component.

**Step 8:** Go to the Pro2Store component params and set up your values.

**Step 9:** At the moment I only have Stripe Checkout working for the checkout. So go to the Stripe Checkout plugin and enter some test API Keys.

**Step 10:** Set up your Checkout. At the moment the checkout system is a collection of Joomla Modules. So first create a Joomla Article for your checkout and set it as a Yootheme Builder page. Now drop in the modules and arrange them as you wish. These are: 

* mod_protostorecartsummary 
* mod_protostorecartuser
* mod_protostorecheckoutitems
* mod_protostorecheckoutpaymentbuttons
* mod_protostorecouponfield

These modules work independantly of each other, so if you wish to build a multipage checkout, you're welcome to. this feature is not heavily tested so please report your findings on this.

**Step 11:** Make a few test orders! :)
