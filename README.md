Overview
The project is a dynamic and responsive website using HTML for structure, CSS and Bootstrap for styling,layout and responsive design and JavaScript for functionality. The site's inspiration was drawn form various e-commerce websites such as Apple.com,shein.com, asos.com and sephora.com.
The site includes key features like product galleries, hover effects, shopping cart functionality and checkout forms. Most of the sites structure and elements rely heavily on Bootstrap with most of the bootstrap code being sourced from getbootstrap.com documentation.
Bootstrap elements.

1. The Grid System whose purpose is to structure the layout for product cards, icons and other content. The Bootstrap grid divides the screen into 12 columns. The classes like col-6 and col-md-3 are used for responsiveness.
2. The Buttons whose purpose is for user actions like adding products to the cart and proceeding to checkout. Buttons with Bootstrap classes like btn,btn-primary and btn-dark.
3. The Modals whose purpose is to display cart details and the checkout form in pop-up windows. The modal implementation includes the modal class and supporting attributes like data-bs-toggle="modal"
4. The Cards whose purpose is to display individual products with an image, title, price and action buttons. It is used with additional custom styling.
5. The icons are used to enhance the user interface with visually appealing elements. The bootstrap icons(eg, bi-heart,bi-bag) are used for favourites,shopping carts and accounts.

JavaScript Funtionality

1. Product Gallery and dynamic generation
   In an attempt to minimize the code in the html part of the code, a products array was created with all the values to be displayed in the e-commerce website using JavaScript. The same was done in making the icons displayed on the website to enhance automation and reduce repetition.
2. Hover Effect on Images
   In an attempt to mimic the interactive UI of the existing e-commerce websites available, a hover effect that swaps out the images on hover of the mouse was added. This enables the user to see various products of the same type without needing to add any other buttons.
3. Add to cart functionality
   To add functionality to the website, a function was called to be able to add items to the shopping cart and further calculate the total while dispalying the cart summary only with the click of a single button. On clicking the said button the products are added to the cart array and updates the UI.
4. Checkout Form Validation
   A function was created to validate the checkout form upon user inputting data to esure that the required fields are filled. This prevents form submission if required fields are missing or invalid. This performs validations on the input fiels in the form and prevents the user from being able to submit the form until the required values are input
   5.Generation of the Order Summary
   The function calculated and displays the order summary after the user confirms the order and it provides a detailed breakdown of the order, including the prices, discounts and taxes. All these are done to give a final output in form of a once-hidden modal.

The documentation above simply summarizes the key aspects of the project and explains its functionality. Sources attributed to google search, getbootstrap.com and w3schools.com
