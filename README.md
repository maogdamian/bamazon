# bamazon

I have created a mySQL database of products that allows you to use a node.js app to "buy" items. Once you purchase an item the inventory is updated.

First run the node app: bamazonCustomer.js 
Using the NPM reqruirer package, you are prompted to select a prouduct and quantity. 

![alt text](https://github.com/maogdamian/bamazon/img/ss1.png)

Once you make your selections the sql database removes the purchased items and displays an updated product list.

![alt text](https://github.com/maogdamian/bamazon/img/ss2.png)

If you try and exceed the inventory amount, an error is displayed.

![alt text](https://github.com/maogdamian/bamazon/img/ss3.png)