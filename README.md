I have used express js for the task along with mysql for the database.
In the main server file i have used one get and post request for rendering the view. I served the html file with the help of jQuery. Also there is a database which will hold the purchased item from the cart.

# Below is the screenshot of the html page

![Screenshot (327)](https://user-images.githubusercontent.com/43828339/72221922-16f07000-3585-11ea-9fa5-f7212a609187.png)


here you can see that i have made it little bit styled like a card element. Alse you can see the main header is styled very well.

# below is the screenshot for the cart.

![Screenshot (328)](https://user-images.githubusercontent.com/43828339/72221312-72b7fa80-357f-11ea-8d69-f156a66677bc.png)

I have provided remove button for each item and add/subtract no of items as well. There is responsive styling of cart element.

# below is the purchase/checkout for the cart.

![Screenshot (332)](https://user-images.githubusercontent.com/43828339/72221968-8cf4d700-3585-11ea-8400-bef1db06b74b.png)


Here as soon as the purchase button is clicked,an alert is generated ,thanking the user for buying the items and cart-item is removed. after that server get comes to start page and it triggers the sequelize query ,adding the cart-items purchased to the database.

# Some additional screenshots.


![Screenshot (330)](https://user-images.githubusercontent.com/43828339/72221986-b7df2b00-3585-11ea-97f1-f6fc65279982.png)


![Screenshot (337)](https://user-images.githubusercontent.com/43828339/72221987-b7df2b00-3585-11ea-8b28-1b67dded5fd4.png)


![Screenshot (338)](https://user-images.githubusercontent.com/43828339/72221988-b7df2b00-3585-11ea-87d8-dba2aadc38c5.png)
