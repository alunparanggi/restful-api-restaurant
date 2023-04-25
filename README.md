# restful-api-restaurant
RESTful API to manage restaurant written in Go with MongoDB as storage

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
