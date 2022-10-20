<!--  Home page: -->

# List of  all products
https://asusnode.herokuapp.com/product
# List of quick search
https://asusnode.herokuapp.com/quick

<!--  second page: -->
# detail of product
https://asusnode.herokuapp.com/details/6

# detail of sub product
https://asusnode.herokuapp.com/sub/200

<!--  order page: -->

# order details
  {
    "_id": "63512cb039a402269ea89e69",
    "orderid": 2,
    "name": "kumar",
    "email": "kumar@gmail.com",
    "address": "ku street",
    "phone": "456769",
    "product_id": 7,
    "price": 249990
  }

# place the order(post)
https://asusnode.herokuapp.com/placeOrder
{
    "id:[7]
}


<!--  payment page: -->

# list of order
https://asusnode.herokuapp.com/orders

# list of order wrt to email
https://asusnode.herokuapp.com/orders?email=anand@gmail.com

# update payment details(put)
https://asusnode.herokuapp.com/updateOrder/:2
{
    "status":"Delievered",
    "bank_name":"abc",
    "date":"10/10/2022"
}
# delete the order(delete)
https://asusnode.herokuapp.com/deleteOrder/63512d1839a402269ea89e6a


