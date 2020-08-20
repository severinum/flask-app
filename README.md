# flask-app

Here is little test for that app

# basic call to test server
address: http://82.37.8.181:5000

# Adding product to DB
address: http://82.37.8.181:5000/product
method: POST
json body passed :
{
    "name": "First Product",
    "description": "This is prod 1 description",
    "price": 425.00,
    "qty": 100
}


# get list of all products from DB
address: http://82.37.8.181:5000/product
method: GET
output: list of products as json
