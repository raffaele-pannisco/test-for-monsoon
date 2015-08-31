# Moonson test

Technical test requirements

-magento 1.9 fresh installation with samples data

Tasks:

1-category women->newarrivals must have the catalog category view image
under the navigation menu and on top of the other elements(layered
navigation, product list, recently viewed, etc). This rule applies to
all device but ipad.


2-the poduct list toolbar must be hidden to all mobile devices

Installation:

git clone https://github.com/raffaele-pannisco/test-for-monsoon.git

check that all files are in the proper path

go to the magento admin, log in and go to System->configuration

click on Design(tab on the left side)

change configuration as follow:

package -> Current Package Name = rwd

themes -> default = responsive

          add one exception 
              matched expression = iPad
              value              = default
              
flush your cache.



