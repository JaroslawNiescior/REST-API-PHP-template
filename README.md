Project structure folders and files.<br/>
├─ api/<br/>
├─── config/<br/>
├────── core.php - file used for core configuration<br/>
├────── database.php - file used for connecting to the database.<br/>
├─── objects/<br/>
├────── product.php - contains properties and methods for "product" database queries.<br/>
├────── category.php - contains properties and methods for "category" database queries.<br/>
├─── product/<br/>
├────── create.php - a file that will accept posted product data to be saved to the database.<br/>
├────── delete.php - a file that will accept a product ID to delete a database record.<br/>
├────── read.php - a file that will output JSON data based on "products" database records.<br/>
├────── read_paging.php - a file that will output "products" JSON data with pagination.<br/>
├────── read_one.php - a file that will accept product ID to read a record from the database.<br/>
├────── update.php - a file that will accept a product ID to update a database record.<br/>
├────── search.php - a file that will accept keywords parameter to search "products" database.<br/>
├─── category/<br/>
├────── read.php - a file that will output JSON data based on "categories" database records.<br/>
├─── shared/<br/>
├────── utilities.php - a file that will return pagination array.<br/>