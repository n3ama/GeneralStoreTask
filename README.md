*Very Important Note* 
You need to add the app.apk file path in App_Path variable before running App_Product Testcase.

" Test cases/Add_Product " 
Objective:
Verify that the General Store app on an Android device functions correctly by ensuring that a user can successfully open the app, select a country, enter personal information, add a product to the cart, and verify its presence in the cart.

Test Steps:
1. Open the General Store app on an Android device (real or emulator).
2. From the provided dropdown list, select "Andorra" as the country.
3. In the designated text field, enter a valid name.
4. Choose your gender from the available options.
5. Press the "Let’s Shop" button to proceed to the shopping section.
6. Navigate through the product categories and add at least one product to the shopping cart.
7. Access the cart screen, either through a dedicated cart icon or navigation within the app.
8. Assert that the added product is correctly displayed in the cart.

Expected Results:
1. The General Store app should open without errors.
2."Andorra" should be selected as the country.
3. The entered name should be visible in the respective field.
4. Gender selection should be successful.
5. Upon clicking "Let’s Shop," the user should be directed to the shopping section.6.
6. At least one product should be successfully added to the cart.
7. The cart screen should display the added product with accurate details.
8. The test should pass without any assertion failures.

Actual Results:
1. The General Store app opens without any errors, displaying the main screen.
2. "Andorra" is successfully selected from the dropdown list.
3. The entered name is visible in the designated text field.
4. The chosen gender is accurately reflected in the app.
5. The app transitions to the shopping section upon clicking the "Let’s Shop" button.
6. The product is added to the cart without encountering any errors.
7. The user navigates to the cart screen without issues.
8. The added product is correctly displayed in the cart with accurate details such as name, quantity, price, and a visible product image.

Statue:
passed
