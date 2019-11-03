## ARRAYS

### ASSIGNMENT 001

Instructions: Create a new array which contains a copy of each entry in the `products` array, (_see code below_) but each product object contains an additional property `total` which contains the total value of the product: price + VAT 23%. Example entry: ```{ price: 200, name: "iPhone", total: 246 }```

```javascript
const products = [
    { price: 200, name: "iPhone" },
    { price: 300, name: "Nokia" },
    { price: 250, name: "Samsung" },
    { price: 150, name: "Xiaomi" },
    { price: 400, name: "Nexus" },
    { price: 500, name: "Sony" },
    { price: 500, name: "Huawei" },
    { price: 270, name: "Motorola" }
];
```

[Source code](./assignment-arrays-001.js)

### ASSIGNMENT 002

Make sure that the phrase "To be or not to be" ends with a period "." and not an extra space:

We want this:

`"To be or not to be."`

Not this:

`"To be or not to be "`

..to be returned from the reduce callback. Make sure that the logic that does the check and applies the period,
is contained inside the `createPhrase()` function.

[Source code](./assignment-arrays-002.html)

### ASSIGNMENT 003

Get the products Array you created from Exercise Arrays 001 which contains total price

1) Loop over the array and for each element display an HTML element, which contains the price, total price and product name

2) Create 2 buttons with text "Display ASC", "Display DESC". When the user clicks on the 'Display ASC' button, the list is sorted based on the price in ascending order and displayed in the screen. When the user clicks on the Display DESC, the list of products is displayed according to price in descending order.

3) Filter the products array, create a new array which contains only products that are cheaper than 500 and display the list in the console