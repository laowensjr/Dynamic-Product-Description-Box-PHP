# Dynamic-Product-Description-Box
This is a dynamic product description box

# A Dynamic Product Description Box

Industry Uses: Brokers, E-commerce, Car Sales, Gallery Sales, Online Retailers just to name a few…

SUMMARY:  When instantiated this class will get the Inventory that is associated with the web page. For example, if we wanted to see all the surface drills in stock. We past the page name to the current script via the URL parameters. The function named getPageInventory(), being a method of the current script, will received the page variable’s value from the URL.

For Example when the URL Reads:
http://YOURDOMAIN.com/inventory.php?page=surfacedrills 

The current script will process the request by calling:
getPageInventory(‘surfacedrills’)

RESULTS: A VERTICAL LIST OF 20 PRODUCT DESCRIPTION BOXES PER PAGE THAT CONTAIN:
1) Product Title
2) Product Pictures
3) Brief Product Description
4) Price
5) Sale Alert(RED)
6) Product Tagline
7) Phone Number
8) Inquire Button to see more details
*************************
DynamicProductBox.jpg
