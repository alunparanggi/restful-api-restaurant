# restful-api-restaurant
RESTful API to manage restaurant written in Go with MongoDB as storage

## ERD
![ERD](https://github.com/alunparanggi/restful-api-restaurant/blob/master/documentation/ERD.png)

## List of endpoints:
* GET    ```/users```
* GET    ```/users/:user_id```    
* POST   ```/users/signup```           
*  POST   ```/users/login```            
*  GET & POST    ```/foods```             
*  GET  & PATCH   ```/foods/:food_id```                   
*  GET & POST   ```/menus```                 
*  GET  & PATCH   ```/menus/:menu_id```                    
*  GET & POST    ```/tables```                  
*  GET  & PATCH   ```/tables/:table_id```                      
*  GET & POST   ```/orders```                
*  GET  & PATCH   ```/orders/:order_id```                      
* GET & POST   ```/orderItems```             
* GET    ```/orderItems/:orderItem_id```
* GET & PATCH   ```/orderItems-order/:order_id```         
*  GET & POST    ```/invoices```                
* GET & PATCH  ```/invoices/:invoice_id```           

## List of packages used in this project:
* [gin](https://pkg.go.dev/github.com/gin-gonic/gin)
* [jwt](https://pkg.go.dev/github.com/dgrijalva/jwt-go)
* [validator](https://pkg.go.dev/github.com/go-playground/validator/v10)
* [mongo driver](https://pkg.go.dev/go.mongodb.org/mongo-driver)
