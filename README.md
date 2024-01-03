# Backend E-commerce Project
This repository contains the backend RESTful API for a full-fledged E-commerce platform, tailored for both Web and Mobile E-Shop Applications.

# Technologies Used
- Node.js
- Express.js
- JWT (JSON Web Tokens)
- Mongoose.js
- Multer (for file uploading)
- Express-validator
- Sharp (for image processing)
- Stripe API (for credit card payments)

# Features
# Product and Category Management
- Product Management:
The product management functionality within this API encompasses a range of operations allowing for comprehensive handling of products within the E-commerce platform:

- Create Product:
Create new products with detailed information such as title, description, price, images, and other relevant attributes.

- Read Product Details:
- Retrieve specific product details using its unique identifier, accessing information like title, description, price, images, ratings, and availability.

- Update Product Information:
Modify and update existing product details, including attributes like title, description, price, images, and any other relevant information.

- Delete Product:
Remove products from the platform based on their unique identifier, facilitating the elimination of outdated or irrelevant items.


- Category Management
Managing categories involves organizing products into distinct groups or classifications to facilitate efficient browsing and search functionalities:

- Create Category:
Establish new categories or tags to classify products, providing a structured organization for products based on common attributes or themes.

- Read Category Details:
Retrieve information regarding specific categories, accessing details like name, description, and associated products within that category.

- Update Category Information:
Modify and update existing category details, enabling changes to category names, descriptions, or associations with specific products.

- Delete Category:
Remove categories from the system, allowing for the elimination of redundant or unused classifications.


# Search, Sort, Pagination, and Filtering
The API provides robust functionality for users to efficiently search, sort, paginate, and filter product data, enabling a seamless browsing experience.

Search Products
- Search by Keyword:
  Users can search for products using keywords, allowing them to find items based on titles, descriptions, or other relevant attributes.

- Search Filters:
Advanced search filters enable precise queries, narrowing down results based on specific parameters like price range, category, or availability.

Sorting
- Sort by Attributes:
Users can sort search results based on various attributes such as price (ascending/descending), popularity, or alphabetical order.

- Flexible Sorting Options:
The API offers flexibility in sorting preferences, allowing users to tailor the sorting order according to their requirements.

Pagination
- Paginated Results:
Pagination is implemented to handle large datasets, breaking down search results into manageable pages to improve performance.

- Limit and Offset Parameters:
Users can specify the number of items per page and navigate through result pages using limit and offset parameters.

Filtering
- Filtering by Categories and Attributes:
Users can filter products based on categories, attributes, or specific criteria, refining search results to match their preferences.

- Customized Filtering Options:
Custom filters enable users to set criteria based on price ranges, ratings, sizes, colors, or any other product-specific attributes.

