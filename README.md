# Software-Testing-Assignment

# Testing this website available with this URL url https://magento.softwaretestingboard.com/

# test1 description: Selecting a Product in Women's Category Dropdown Menu

## Overview (test1.js)
This test case involves automating the selection of a product in the Women's category on an e-commerce website using Selenium WebDriver and Node.js. The automated test navigates through the website, clicks on the Women's category, selects a specific product in the Tees section, customizes the product by choosing size and color, adds it to the shopping cart, and verifies the success message and the selected product in the cart.

## Prerequisites
- Node.js installed
- Selenium WebDriver for JavaScript (`selenium-webdriver`) package installed
- Chai Assertion Library (`chai`) installed

## Test Scenario
1. Open the website: `https://magento.softwaretestingboard.com`
2. Navigate to the Women's category using the dropdown menu.
3. Select the "Tees" subcategory.
4. Choose a specific product ("Diva Gym Tee") from the Tees category.
5. Customize the product by selecting a size and color.
6. Add the product to the shopping cart.
7. Verify that the correct success message is displayed.
8. Confirm that the selected product is in the shopping cart.

## Test Script
The test script is written in JavaScript using the Selenium WebDriver library and Chai assertion library. The script uses asynchronous functions and WebDriver's built-in `until` condition to wait for elements to be located.

## Instructions to Run
1. Ensure that Node.js is installed on your machine.
2. Install the required Node.js packages:
   ```bash
   npm install selenium-webdriver chai
   npm run test

# Mousehover Test Project

## Overview (test2.js)
This test case involves automating a mouse hover action to select a category on an e-commerce website using Selenium WebDriver and Node.js. The test navigates through the website, performs a mouse hover action on the Women's category, selects a sub-menu item, clicks on the "Tees" link, chooses a specific product, customizes the product, adds it to the shopping cart, and verifies the success message.

## Test Scenario

1. Open the webpage: https://magento.softwaretestingboard.com
2. Perform a mouse hover on the Women's category.
3. Select a sub-menu item ("Tops").
4. Click on the "Tees" link.
5. Choose a specific product ("Diva Gym Tee") from the Tees category.
6. Customize the product by selecting size and color.
7. Add the product to the shopping cart.
8. Verify that the correct success message is displayed.

## Test Script
The test script is written in JavaScript using the Selenium WebDriver library. The `Actions` class is utilized to perform mouse hover actions, and Chai assertion library (`chai`) is used for assertions.

# Search for Product 

## test3.js

As a customer, I want to be able to search for a product, so that I can find the product I want to buy.

## Test Scenario
The test case involves searching for a product on an e-commerce website and verifying that the desired product is displayed in the search results. The test case is written in JavaScript using Selenium WebDriver, Mocha for test structure, and Chai for assertions.

### Test Case Description
#### Context: I search for a product
- **Test Scenario:** I should see the product that I have searched for.
- **Steps:**
  1. Start the web browser.
  2. Navigate to the Magento site (`https://magento.softwaretestingboard.com/`).
  3. Click on the "Tops" link in the Women's category.
  4. Find the first product in the displayed list.
  5. Extract and verify the product title and price.
  6. Perform assertions to ensure the product title is 'Radiant Tee' and the price is '$22.00'.
  7. Log information about each product.

### Instructions to Run
1. Ensure that Node.js is installed on your machine.
2. Install the required Node.js packages
   ```bash or command prompt
   npm install selenium-webdriver chai mocha
   npm run test




