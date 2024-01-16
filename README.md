This repository contains the code for a main header component designed for a web application. The main header includes various elements for user interaction and navigation.

HTML Structure
The main header is structured using HTML with the following elements:

html
Copy code
<div class="main-header__container">
  <i class="fas fa-user"></i>
  <a href="" class="main-header__btn">My cart<i class="fas fa-regular fa-cart-shopping"></i></a>
  <a href="" class="main-header__btn"><i class="fas fa-regular fa-cart-shopping"></i></a>
  <input type="search" class="main-header__input" placeholder="Buscar productos"><i class="fas fa-solid fa-magnifying-glass"></i>
</div>
Description of Elements:
User Icon: Represented by <i class="fas fa-user"></i>, indicating a user-related action.
Cart Buttons: Two buttons for cart actions, represented by <a> elements with the class "main-header__btn" and icons.
Search Input: An input field for searching products, represented by <input> with the class "main-header__input" and a search icon.
Usage
To use this main header component, include the provided HTML code in your project's HTML file. Customize the links and icons as needed for your application.

Feel free to modify and adapt the code to suit the styling and functionality requirements of your project. If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request.

Author
Alessandro Velasco

License
This main header component is licensed under the MIT License.
