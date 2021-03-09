# FindProductShopify
This Python Code utilizes multiple modules like json, re, requests
and time to monitor a shopify website for a product and retrieve its 
link and size id based on the size entered. It works on virtually 
any shopify site that allows webscrapping.

Keywords should be a string formatted as "+apple, +cherry" with plus
signs right before each word and comma and space inbetween each word.

Site link is a string that should be grabbed from the url of the 
website directly.

Size is a string i.e. "9" for size 9 shoes or "M" for size medium clothing

Monitor_delay tells the program how long to wait to ping the site 
again and the parameter expects an int.
