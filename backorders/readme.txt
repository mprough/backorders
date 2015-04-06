Zen Cart Backorders Module v 1.0
Version Release Date: 09/10/2014
Publisher: PRO-Webs, Inc
Released for Zen Cart v 1.3.x & 1.5.X

This installation is considered a intermediate level Zen Cart module installation.

This Zen Cart module and customization will allow you to add a mock backorder 
function to your Zen Cart.

This installation contains only Zen Cart 1.5.3 files and you will need to carefully 
the commented changes for other versions.


INSTALLATION INSTRUCTIONS
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

1. FIRST MAKE A FULL BACKUP OF YOUR WEBSITE'S FILES AND DATABASE!

2. Upload/merge the files in the catalog directory with your own
   Zen Cart files.
   
   **
   (note, you can also turn on the date available in your product
   layout section, I used this method for placement and notability
   on the page)
   
3. In your Zen Cart admin under Configuration >> Stock, set the
   following values.
   - Allow Checkout = TRUE
   - Products status in Catalog when out of stock should be set to = 1
   - Show Sold Out Image in place of Add to Cart = 0
   
4. In a product for which you are awaiting stock under Catalog >>
   Categories & Products update the product so that is has a 
   quantity in stock and set the Date Available near the top to
   when the product is expected.
  
5. In your admin under Localization >> Orders Status create a
   new status called "Backorder".
   
6. Now when a backordered items comes in, you will have the expected
  available date in your order screen and the customer will know it
  is backordered.
      

INFORMATION
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Core file Edits: admin/orders.php
Database Changes: None


UNINSTALL
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Simply remove the package files for a full uninstall.


SUPPORT
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Please seek support here https://pro-webs-support.com/


VERSION HISTORY
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Original Release PRO-Webs.net 09/10/2014


Copyright (c) 2014 PRO-Webs, Inc.