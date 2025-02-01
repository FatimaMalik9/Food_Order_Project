## Food Order App 🍔🍕

# Description

The Food Order App is a single-page online food ordering website built using HTML, JavaScript, and Bootstrap. 
It features a dynamic interface where users can browse food items, add them to a wishlist or cart, and manage their selections.
# Features

✅ Single-page layout with navbar, header, sidebars, and footer.
✅ Main section displaying food items using Bootstrap cards.
✅ Wishlist feature: Users can add items to a wishlist by clicking the heart icon.
✅ Cart feature: Users can add food items to the cart and modify quantities.
✅ Price summary: Updates dynamically based on cart items.
✅ Internal and inline CSS (Bootstrap used for styling).

# Technologies Used

Frontend: HTML, JavaScript, Bootstrap
CSS Framework: Bootstrap (No separate CSS file)

# Project Files

The project contains the following files:
1️⃣ page_layout.html
Home page layout.
Displays all food items.
Navbar with "Home" and "About" options.
Left and right sidebars (cart and wishlist icons).
Footer at the bottom.
Food items displayed using Bootstrap cards.
Embedded Bootstrap CSS and JS links.

2️⃣ wishlist.html
Displays the wishlist.
Calls the displayWishlist(); function from script.js.
Allows users to remove items from the wishlist.
Includes Bootstrap CSS and JS links.

3️⃣ cart.html
Displays the cart.
Calls the displayCart(); function from script.js.
Shopping cart section shows added food items.
Dynamic price summary updates based on cart items.
Add/remove options for cart products.
Quantity adjustment feature that updates the total price dynamically.
Includes Bootstrap CSS and JS links.

4️⃣ script.js
Contains all functions to make the webpage dynamic.
Manages wishlist and cart operations.

5️⃣ cartScript.js
Contains the function to dynamically display cart products.
Installation & Usage
Clone the repository:
git clone https://github.com/yourusername/Food-Order-App.git
Open page_layout.html in a browser to start browsing food items.
Add items to the wishlist or cart.
Navigate to wishlist.html or cart.html to view and manage selected items.

# Notes

Bootstrap is used for styling, so no external CSS files are included.
JavaScript functions dynamically handle cart and wishlist updates.



