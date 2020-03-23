# Destiny-2-Gear-Level-Calculator

## How to create api key/clientid/etc

1. Go to https://www.bungie.net/en/User/API
1. Login if needed
1. Create New App
1. Redirect URL = https://script.google.com/macros/d/<script id here>/usercallback
	* To get script id go to spreadsheet -> Tools -> Script Editor -> File -> Project Properties -> Info -> Property -> Script ID -> Value
1. Scope = Read your Destiny 2 information (Vault, Inventory, and Vendors), as well as Destiny 1 Vault and Inventory data
