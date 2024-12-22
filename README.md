
#Microservices
This project features a Vue.js component designed to display a data table for managing and viewing product details. It is part of a microservices architecture focusing on Order Management and Inventory Management.

#Features
Search Functionality: Allows users to search for products by their titles.
Dynamic Data Table: Displays product information with customizable headers.
Vuetify Integration: Ensures a cohesive and professional UI using Vuetify components.
Modular Design: The component is reusable across different parts of the application.


#Project Structure
components: Houses Vue components, including ProductsTable.vue.
pages: Contains application pages like Dashboard.vue and Shop.vue.
lib: Includes utility files, such as supabase.js.
plugins: Configurations for plugins, including vuetify.js.
router: Handles application routing.
styles: Contains global styling for the project.

#Installation

git clone https://github.com/kry70/OI-Microservice-System.git
cd <repository-folder> 

Install project dependencies:
npm install

Start the development server:
npm run dev  

Open your browser and visit http://localhost:8050 to access the application.

Usage
Go to the "Shop" page to view the Products Table.
Use the search bar to filter products by their title.
Interact with the table to manage product details.
Components Overview
ProductsTable.vue
Props:

products: An array of product data.
headers: An array of table headers.
Slots:

item.title: Allows customization of how product titles are displayed.
Key Features:
Search Bar: Enables filtering products by title.
Data Table: Displays product information with built-in filtering functionality.
Technologies Used
Vue.js
Vuetify
Supabase
Node.js
Contributions
Contributions are encouraged! To contribute:

Fork the repository.
Create a feature branch for your changes.
Commit your updates.
Open a pull request for review.
License
This project is open-source and distributed under the MIT License.