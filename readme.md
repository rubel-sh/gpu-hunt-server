### API: https://gpuhunt-server.vercel.app/

## Get Operations

- /api/users [Returns all users: ADMIN ONLY]
- /api/products/category/:name [Returns all products to that catagory, filter out sold products]
- /api/products/advertised [Returns only advertised products, filter out sold products]
- /api/users/wishlists [Returns wishlists for single user] [OPTIONAL]
- /api/users/sellers [Returns all Sellers]
- /api/users/buyers [Returns all Buyers]
- /api/blogs [Returns all Blogs]
- /api/users/role/:email [Get user role]
- /api/categories [Returns all categories]
- /api/categories/:catName [Get single category items]
- /api/users/verified [if user verified or not verified]
- /api/orders/:email [return all orders for that buyer]

## Post Operations

- /api/users [Insers a new user]
- /api/products [Inserts a new product]
- /api/orders [Inserts a new order]

## PUT Operations

- /api/users/:id [Update existing user role]
- /api/products/myProducts/:id [Update existing product's advertise status]
- /api/products/paid/:id [Update existing product's paid status]
- /api/users/wishlists/:productId [Adds a wishlist array of id to usersCollection] [OPTIONAL]
- /api/users/sellers/:id [Update existing seller's verified status]
- /api/orders/:productId [Pay by product id]
- /api/users/ [Update product's reported status]

## Delete Operations

- /api/products/reported/:id [delete reported product]
- /api/products/myProducts/:id [delete a product]
- /api/users/buyers/:id [delete a user]
- /api/users/sellers/:id [delete a seller]
