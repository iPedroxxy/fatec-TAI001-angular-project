<h2 align="left">Project Content</h2>

###

<p align="left">Product Registration<br><br>Add new products to the database.<br>Required fields: name, description, expiration date, quantity, unit value, photo, ID.<br>Product Search<br><br>Search for products by various criteria (name, ID, expiration date, etc.).<br>Filter products by expiration date, stock quantity, and price range.<br>Product Update<br><br>Update information of existing products.<br>Allow partial updates (change one or more fields without affecting others).<br>Product Deletion<br><br>Remove products from the database.<br>Soft delete (mark products as inactive instead of permanently deleting them).<br>Inventory Management<br><br>Monitor the quantity of products in stock.<br>Alert when a product is close to expiration or has low stock.<br>Authentication and Authorization<br><br>Access control with different permission levels (administrator, operator, etc.).<br>Implement secure authentication for system access.<br>Activity Logs<br><br>Record all CRUD (Create, Read, Update, Delete) operations.<br>Logs for login and logout activities.<br>Reports<br><br>Generate reports of registered products, products nearing expiration, and products with critical stock levels.<br>Export reports in different formats (PDF, CSV, etc.).<br><br>HTML: The HTML structure includes headings for "Cars and Bicycles" and two sections for displaying information about each item.<br>CSS: The CSS file (style.css) provides styles for the HTML elements, ensuring a consistent and visually appealing presentation. It defines properties such as font families, text alignment, background colors, and spacing.</p>

###

<h2 align="left">Features</h2>

###

<p align="left">Database Structure<br><br>Products Table<br><br>id (integer, primary key, auto-increment)<br>name (text)<br>description (text)<br>expiration_date (date)<br>quantity (integer)<br>unit_value (decimal)<br>photo (text, store URL or base64 of the image)<br>active (boolean, default: true)<br>Users Table<br><br>id (integer, primary key, auto-increment)<br>name (text)<br>email (text, unique)<br>password (text, password hash)<br>role (text, e.g., 'admin', 'operator')<br>Logs Table<br><br>id (integer, primary key, auto-increment)<br>action (text, e.g., 'CREATE', 'READ', 'UPDATE', 'DELETE')<br>description (text, details of the action)<br>timestamp (timestamp)<br>user_id (integer, foreign key referencing users)</p>

###

<h2 align="left">Technologies Used</h2>

###

<p align="left">JSON<br>ANGULAR (FRONT END)</p>

###
