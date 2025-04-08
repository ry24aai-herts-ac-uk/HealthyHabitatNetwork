# HealthyHabitatNetwork
This is a masters Project work for Software Engineering exercise

Useful Links:

* Git Repo: https://github.com/ry24aai-herts-ac-uk/HealthyHabitatNetwork.git
* trelloBoard : https://trello.com/b/AylUpgj4/healthy-habitat-network

**1. Functional and Non-Functional Requirements**

**Functional Requirements:**

* **User Interaction:**
    * Users should be able to browse a list of health and wellness services and products. [cite: 3, 4, 5]
    * Users should be able to search for specific services or products.
    * Users should be able to view detailed information about each service or product (e.g., descriptions, pricing, provider information).
    * The platform should connect users with businesses offering these services and products. [cite: 2, 3]
* **Service/Product Listings:**
    * Businesses should be able to list their health and wellness services and products.
    * The platform should categorize services and products (e.g., Healthy Eating Programs, Fitness and Wellness, Sustainable Living). [cite: 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18]
    * The platform should allow for the inclusion of details such as descriptions, images, and contact information for each listing.
* **Platform Administration:**
    * An administrator should be able to manage user accounts.
    * An administrator should be able to approve or reject business listings.
    * An administrator should be able to manage categories and subcategories of services and products.

**Non-Functional Requirements:**

* **Usability:** The platform should be easy to navigate and user-friendly.
* **Accessibility:** The platform should be accessible to users with disabilities.
* **Performance:** The platform should load quickly and respond efficiently to user interactions.
* **Scalability:** The platform should be able to handle a growing number of users and listings.
* **Security:** The platform should protect user data and ensure secure transactions (if applicable).
* **Maintainability:** The codebase should be well-organized and easy to maintain and update.
* **Reliability:** The platform should be reliable and available with minimal downtime.

**2. Implementation Plan (PHP, MySQL)**

Okay, let's revise the implementation plan and Trello board structure to use Laravel instead of CodeIgniter.

**Revised Implementation Plan (PHP, MySQL, Laravel)**

* **Technology Stack:**
    * Frontend: HTML, CSS, JavaScript
    * Backend: PHP (Laravel)
    * Database: MySQL
* **Development Steps:**
        1.  **Database Design:** Design the MySQL database schema to store information about users, businesses, services, products, categories, etc.
    2.  **Backend Development (Laravel):**
        * Set up the Laravel project.
        * Define Eloquent models to interact with the database.
        * Create migrations to manage the database schema.
        * Develop controllers to handle user requests and business logic.
        * Implement user authentication and authorization using Laravel's built-in features.
        * Build APIs (if needed) using Laravel's routing and response mechanisms.
    3.  **Frontend Development (HTML, CSS, JavaScript):**
        * Develop the user interface for browsing listings, searching, viewing details, and user account management.
        * Use JavaScript to handle dynamic elements and interactions on the page.
        * Integrate with the backend APIs to fetch and display data.
    4.  **Testing:** Conduct thorough testing at each stage (unit testing, integration testing, user testing) to ensure quality and identify bugs.
    5.  **Deployment:** Deploy the Laravel application to a web server.
    6.  **Maintenance:** Ongoing maintenance, updates, and bug fixes.

**Why Laravel?**

Laravel is a powerful and popular PHP framework that offers several advantages:

* **MVC Architecture:** Enforces a clean MVC pattern for better code organization.
* **Eloquent ORM:** Provides an elegant way to interact with the database.
* **Blade Templating Engine:** Simplifies the creation of dynamic views.
* **Authentication and Authorization:** Built-in support for user authentication and authorization.
* **Routing:** A robust routing system for defining application routes.
* **Community and Ecosystem:** A large and active community with extensive documentation and packages (e.g., for APIs, security, etc.).

While Laravel has a steeper learning curve than CodeIgniter, its features and capabilities can lead to more robust and maintainable applications in the long run.

**Trello Boards**

The overall structure of the Trello boards card content:

* **Board 1: Project Management**
    * Lists:
        * **Backlog:** User stories and tasks that need to be completed.
        * **To Do:** Tasks that are currently being worked on.
        * **In Progress:** Tasks that are actively being developed.
        * **Testing:** Tasks that are ready for testing.
        * **Done:** Completed tasks.
* **Board 2:  Database Development**
    * Lists:
        * **To Do:** Database schema design tasks (e.g., design user table, product table, etc.)
        * **In Progress:** Tasks related to creating the database schema.
        * **Testing:** Tasks related to testing the database schema.
        * **Done:** Completed database schema.
* **Board 3: Backend Development (Laravel)**
    * Lists:
        * **Backlog:**
            * "Implement user registration using Laravel's authentication."
            * "Create Eloquent models for Product and Category."
            * "Develop API routes for product listings."
        * **To Do:**
            * "Set up Laravel project and database connection."
            * "Create migrations for users, products, and categories."
        * **In Progress:**
            * "Develop the ProductController."
            * "Implement the logic to display product details."
        * **Testing:**
            * "Test user registration."
            * "Test API endpoints for product data."
        * **Done:**
            * "Laravel project set up."
            * "Database migrations created."
            * "User authentication implemented."
* **Board 4: Frontend Development**
    * Lists:
        * **Backlog:** Tasks related to frontend development (e.g., create homepage, product display page, etc.)
        * **To Do:** Frontend tasks ready for development.
        * **In Progress:** Tasks being actively developed.
        * **Testing:** Frontend components ready for testing.
        * **Done:** Completed frontend components.

**Card Examples:**

* **Backlog:**
    * "As a user, I can browse services by category."
    * "Design the product details page."
    * "Implement user registration."
* **To Do:**
    * "Set up CodeIgniter project."
    * "Create the database connection."
* **In Progress:**
    * "Develop the API endpoint for fetching product listings."
    * "Style the homepage."
* **Testing:**
    * "Test user registration functionality."
    * "Test product search."
* **Done:**
    * "Database schema created."
    * "User authentication implemented."