# HappenHub

- Designed and created a web page that allows users to search for events and purchase tickets


## 1. Overview 
- Frontend: an interactive web page with `AJAX` technology implemented with `HTML`, `CSS` and `JavaScript`. 

- Backend: create `Java` servlet with `RESTful APIs` to handle HTTP requests and responses
   * Utilized relational and NoSQL databases (MySQL/MongoDB) to store real business data, such as name, description, location and price, from TicketMaster API

- Presentation: HTML, CSS, JavaScript
- Data: MySQL, MongoDB
- Logic: Java

## 2. API
   * Search
      * search events with Ticketmaster API
   * History
      * get, set, delete favorite items with query database
   * Recommendation
      * Retreive favorite history to find similar events
   * Register
      * Set a new user into users table/collection in database
   * Login
      * Query database to check
   * Logout
      * Terminate the session if active and redirect to index.html


## 3. Database Implementation
- MySQL
   * **users** - store user information.
   * **items** - store item information.
   * **category** - store item-category relationship
   * **history** - store user favorite history

> MySQL database design

- MongoDB
   * **users** - store user information and favorite history
   * **items** - store item information and item-category relationship
   * **logs** – store log information

