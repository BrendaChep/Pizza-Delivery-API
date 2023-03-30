# Pizza-Delivery-API.
A Pizza Delivery API project for a pizza delivery service.
|METHOD     | ROUTE     | FUNCTIONALITY            | ACCESS
| :------------ |   :---:       | --------:        |--------:
| POST        | /api/signup       | Register new user        |All users
| POST         | /api/login         | Login user    |All users
| POST         | /api/order         | Place an order    |All users
| PUT        | /api/order/update/{id}/       | Update an order        |All users
| PUT         | /api/order/status/{id}/        | Update order status    |Superuser
| DELETE        | /api/order/delete/{id}/      | Delete an order        |All users
| GET         | /api/user/orders/         | Get user's orders    |All users
| GET        | /api/orders/       | List all orders made        |Superuser
| GET        | /api/orders/{id}/        | Retrieve an order    |Superuser
| GET        | /api/user/order/{id}/         | Get user's specific order    |All users
| GET        | /docs/         | View API Documentations    |All users
