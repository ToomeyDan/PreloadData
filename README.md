# PreloadData

I enjoy reading about new features in Java/Spring that I can use in my development work. Most 
of the articles provide excellent articles on the feature, but many lack how to load in example 
data into the database to exercise the feature. This article explains the steps needed.

Published in medium.com at https://medium.com/@dan_495/how-to-preload-data-in-a-spring-boot-application-c8df34a650d7

Start the application. If we enter the url to get the product list (http://localhost:8080/products) we should 
see (my browser has an automatic PrettyPrint option):
```
[
  {
    "id": 1,
    "name": "First",
    "price": 20
  },
  {
    "id": 2,
    "name": "Second",
    "price": 15
  },
  {
    "id": 3,
    "name": "Third",
    "price": 25
  }
]
```


