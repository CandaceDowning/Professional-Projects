# Professional-Projects
## A list of projects that have proprietary code that cannot be shared.  

&nbsp;
&nbsp;


# Eatzis.com
## Wordpress site for marketing with a bundled React app for online ordering from one of six Eatzi's stores.

&nbsp;

### Wordpress Marketing side
### `Tech`
- Wordpress
    - Including child theming of templates
- Wocommerce
- PHP
- Javascript
- Sass
- CSS
- Bootstrap
- PHPMyAdmin/SQL

### `Features`
- Built and styled all of the front end templates for a custom theme with backend content handling through advanced custom fields pro
- Creation of a custom dashboard for various management settings 
    - Turning online ordering or delivery on and off
    - Turning banner notifications on and off 
    - handling content of promotional elements
    - Online ordering hours management
    - Peak time handling for altering order time estimates
- A custom API to handle passing data to the React App
    - Adding items to the cart
    - Account creation and sign in 
    - Session cart handling
    - Wallet tokenization
    - Payments
    - Build your own functionality
- A system for adding custom product data to facilitate a 'build your own' product style 
    - Ingredient categories
    - Minimum and maximum allowable ingredients per category
    - Ingredients in each category
    - Additional pricing for ingredients
    - Variations of ingredients allowed
    - Stock handling of ingredients per location
    - Adding a customer name to the item
    - Calculation of product price based on selections
- Usage of the basic Woocommerce platform to present a menu, with override of the add to cart button to take the user to the app to order
- Customization of the account system to allow additional data on an order screen
    - Reordering of previous orders
    - Delivery tracking 
- Order management through the customized Woocommerce dashboard
    - Editing of core and custom order meta  
    - Marking orders completed upon handoff to the customer or delivery driver
    - Color coding of orders based on pickup/delivery types and status
    - Custom order statuses to accomodate the delivery process
    - Customization of the refund functionality to tie into the Worldpay integration

&nbsp;

### React Ordering App
### `Tech`
- Javascript/JSX
- Context
- Moment.js
- Styled components with theme provider
- React router
- Olo dispatch integration for scheduling deliveries
- Wordlpay payment gateway integration
- Utilization of the custom API to retrieve product data, and create orders

### `Features`
- Location selection with map of stores
- Pickup or delivery options
- Quote retrieval and acceptance for delivery orders
- Build your own functionality that allows customers to select ingredients for items like salads, pastas, and meals with side items
- Cart management and payments
- Session cart management
- Sign up and Login management

&nbsp;

### 2 Servers
### `Tech`
- Express
- Javascript

### `Features`
- Main server to handle requests between the React App and Olo, Google, Worldpay, and the print server
- Print Server hanldles passing requests from the main server to the in store printers
    - Individual product tickets print at each preperation station sorted by which product categories are prepared by each station
    - Master ticket prints at the coordinators station to allow packaging of individual products into a single order

&nbsp;
&nbsp;

# Lilyofthedesert.com
## An ecommerce Wordpress site for marketing, selling aloe and nutritional products, and a blog for further product promotion. 
### `Tech`
- Wordpress
- Wocommerce
    - Including child theming of templates
- PHP
- PHPMyAdmin/SQL
- Javascript
- Sass
- CSS
- Bootstrap
- Yotpo integration for reviewing products
- Omnisend integration for newsletter subscriptions and marketing

### `Features`
- Built and styled all of the front end templates for a custom theme with backend content handling through advanced custom fields pro
- Advanced couponing for BOGO style coupons
- A blog with custom navigation for categories and tags
- Brand pages 
- Testimonials

&nbsp;
&nbsp;

# Goeditgraphics.com
## A React app for allowing users to create custom marketing material for student sports programs
### `Tech`
- React
- React router
- Apollo
- Material ui
- Graph QL
- konva
- moment
- Sass
- Express server
- Context

### `Features`
- Account management
- A graphics editing interface for creation of social media assets to promote athletic teams

&nbsp;
&nbsp;

# Kephircoffeeroasters.com
## An ecommerce Wordpress site for selling small batch roasted coffee from the Irish roaster Kephir Coffee that was developed as an independent contractor.
### `Tech`
- Wordpress
    - Including child theming of templates
- Wocommerce
- PHP
- Javascript
- Sass
- CSS
- Bootstrap

### `Features`
- Built and styled all of the front end templates for a custom theme with backend content handling through advanced custom fields pro including:
    - Customization of Woocommerce functionality and child theming templates to allow for a one page store/home page
    - Auxiliary pages for information about the growers, with the ability to link each product to a grower's page
- Custom meta data for product information layouts and content
- Instagram social feed integration
- Mail poet integration for marketing purposes
- Contact Form 7 itegration for customer submission of questions and inquiries

