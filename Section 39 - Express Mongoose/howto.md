# howto

```cmd
// In CMD
$ node index.js
$ node seeds.js
$ mongo

// In Mongo
> db
test
> db
test
> show dbs
admin      0.000GB
config     0.000GB
farmStand  0.000GB
local      0.000GB
> use farmStand
switched to db farmStand
> show collections
products
> db.products.find()
{ "_id" : ObjectId("6433b48e6d071154ac6e281a"), "name" : "Fairy Eggplant", "price" : 1, "category" : "vegetable", "__v" : 0 }
{ "_id" : ObjectId("6433b48e6d071154ac6e281b"), "name" : "Organic Goddess Melon", "price" : 4.99, "category" : "fruit", "__v" : 0 }
{ "_id" : ObjectId("6433b48e6d071154ac6e281c"), "name" : "Organic Mini Seedless Watermelon", "price" : 3.99, "category" : "fruit", "__v" : 0 }
{ "_id" : ObjectId("6433b48e6d071154ac6e281d"), "name" : "Organic Celery", "price" : 1.5, "category" : "vegetable", "__v" : 0 }
{ "_id" : ObjectId("6433b48e6d071154ac6e281e"), "name" : "Chocolate Whole Milk", "price" : 2.69, "category" : "dairy", "__v" : 0 }
>
```