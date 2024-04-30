# H&M-Website

## Languages and Technologies Used
HTML, CSS, JavaScript, MySQL, Flask

## Usage
1.Running the Application: Run the app.py file to start the application.
2.Browser: Navigate to http://localhost:5000 in your browser.
3.Home Page: This is the landing page. By selecting the buttons under the "New Products" category, products are listed with a slider according to categories such as Women, Men, etc. The images here are fetched from the database. Clicking the search button navigates to the search page to search for desired products.
4.Search Page: The searched product is listed on the page. On the left side, the category panel lists the products available in the database under categories such as Women, Men, etc. Clicking on the price and name of the products redirects to the details page via URL.
5.Details Page: The details page displays the image, description, ID number, category, and size buttons of the product.

## Issues
1.The filtering options for size and sorting on the search page are not functioning. I suspect there is an issue in the HTML code causing this.
2.When a category is selected for the searched keyword on the search page, all products in the selected category are retrieved. However, the desired functionality is to filter products in the selected category based on the searched keyword. I believe the issue lies in the JavaScript code.
