# Dummy Json Server

Dummy server to test checkout events from magento

## DB

Store checkouts with the following payload:

"""
{
    "id": integer           //DB Auto Increment ID 
	"user_id": string       //User email
	"quote_id": 1,          //Shopping Cart id
	"coins": 10             //Number of coins purchased
}
"""