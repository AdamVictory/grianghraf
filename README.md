
# grianghraf - Introduction

<h1 align=center>grianghraf - A B2C Digital Camera Store Website </h1>

<h2 align=center>Introduction</h2>

<p align=center>Project Portfolio 5 for the Code Institute Full-Stack development program: E-Commerce Applications. 
grianghraf is a website for camera lovers dedicated to selling the best digital cameras on the market by filtering different categories. <br><br>
It is a B2C business, that is targeted towards professional photographers and filmakers but also people looking to get into photography. 
This online sales platform allows users to quickly find the camera they are looking for and checkout with a seamless experience. They can also register for a personal profile by filling in their personal details on the website's profile page. All visitors are also welcome to drop a service review to help the admin know how the site is doing. The application has a good appearance with an easy and clear site navigation. 

<br><br> Users can search different brands and add any products they may want to their basket and checkout. <br><br> Wholebeans has been built using the Django framework in python, HTML and CSS, and provides user authentication and full CRUD functionality for recipes </p>

[Visit the live site on Heroku](https://grianghraf.herokuapp.com/)

![Multi Devive Website Mockup Generator Screenshot](docs/images/responsive-screenshot.png)


README Table Content

- [grianghraf - Introduction](#watches--clocks---introduction)
  - [User Experience - UX](#user-experience---ux)
    - [User Stories](#user-stories)
    - [Agile Methodology](#agile-methodology)
    - [The Scope](#the-scope)
      - [Main Site Goals](#main-site-goals)
  - [Design](#design)
      - [Colours](#colours)
      - [Typography](#typography)
      - [Imagery](#imagery)
      - [Video](#video)
    - [Wireframes](#wireframes)
  - [Database Diagram](#database-diagram)
  - [Features](#features)
    - [Landing Page](#landing-page)
    - [Home Page - Images Carousel](#home-page---images-carousel)
    - [Home Page - Selected Products](#home-page---selected-products)
    - [Home Page - Image Banner](#home-page---image-banner)
    - [Home Page - Customers Reviews Carousel](#home-page---customers-reviews-carousel)
    - [Products Page](#products-page)
    - [Products Details](#products-details)
    - [Products Details - Features](#products-details---features)
    - [Products Details - Products on Sale](#products-details---products-on-sale)
    - [Products Shopping Bag](#products-shopping-bag)
    - [Products Shopping Bag - Products Coming Soon](#products-shopping-bag---products-coming-soon)
    - [Products Checkout](#products-checkout)
    - [Products Checkout - Success](#products-checkout---success)
    - [Products Management](#products-management)
    - [Profile Page](#profile-page)
      - [Service Reviews Page](#service-reviews-page)
      - [Add/Edit Service Review Page](#addedit-service-review-page)
    - [Signup Page](#signup-page)
    - [Signup Page - Verify Email](#signup-page---verify-email)
    - [Signup Page - Confirm Email](#signup-page---confirm-email)
    - [Login Page](#login-page)
    - [Logout Page](#logout-page)
    - [Reset Password Page](#reset-password-page)
    - [Change Password Page](#change-password-page)
    - [Navbar](#navbar)
    - [Footer](#footer)
    - [Page 404 - Page Not Found](#page-404---page-not-found)
  - [Messages and Interaction with Users](#messages-and-interaction-with-users)
    - [Sign up 1](#sign-up-1)
    - [Sign up 2](#sign-up-2)
    - [Login](#login)
    - [Logout](#logout)
    - [Profile Update](#profile-update)
    - [Service Review - Add Review](#service-review---add-review)
    - [Service Review - Update Review 1](#service-review---update-review-1)
    - [Service Review - Update Review 2](#service-review---update-review-2)
    - [Service Review - Delete Review 1](#service-review---delete-review-1)
    - [Service Review - Delete Review 2](#service-review---delete-review-2)
    - [Service Review - Delete Review 3](#service-review---delete-review-3)
    - [Add Product](#add-product)
    - [Edit Product 1](#edit-product-1)
    - [Edit Product 2](#edit-product-2)
    - [Edit Product 3](#edit-product-3)
    - [Delete Product 1](#delete-product-1)
    - [Delete Product 2](#delete-product-2)
    - [Delete Product 3](#delete-product-3)
    - [Add Product to Bag](#add-product-to-bag)
    - [Update Bag](#update-bag)
    - [Remove Product from Bag](#remove-product-from-bag)
    - [Purchase Success](#purchase-success)
    - [Purchase Success - Confirmation Email](#purchase-success---confirmation-email)
  - [Admin Panel / Superuser](#admin-panel--superuser)
  - [Marketing and Social Media](#marketing-and-social-media)
    - [Statista - Facebook Users](#statista---facebook-users)
    - [Watches \& Clocks - Facebook Page](#watches--clocks---facebook-page)
    - [Meta Pixel - Tracking Audience](#meta-pixel---tracking-audience)
    - [Mailchimp Subscription Service](#mailchimp-subscription-service)
  - [Privacy Policy](#privacy-policy)
  - [Search Engine Optimization](#search-engine-optimization)
    - [sitemap.xml](#sitemapxml)
    - [robots.txt](#robotstxt)
    - [Sitemap Google Registration](#sitemap-google-registration)
  - [AWS Setup Process](#aws-setup-process)
    - [AWS S3 Bucket](#aws-s3-bucket)
    - [IAM Set Up](#iam-set-up)
    - [Connecting AWS to the Project](#connecting-aws-to-the-project)
  - [Stripe Payments](#stripe-payments)
    - [Payments](#payments)
    - [Webhooks](#webhooks)
  - [Technologies Used](#technologies-used)
    - [Languages Used](#languages-used)
    - [Django Packages](#django-packages)
    - [Frameworks - Libraries - Programs Used](#frameworks---libraries---programs-used)
    - [Testing](#testing)
  - [Creating the Django app](#creating-the-django-app)
  - [Deployment of This Project](#deployment-of-this-project)
  - [Final Deployment](#final-deployment)
  - [Forking This Project](#forking-this-project)
  - [Cloning This Project](#cloning-this-project)
  - [Credits](#credits)
    - [Content](#content)
    - [Information Sources / Resources](#information-sources--resources)
  - [Special Thanks](#special-thanks)


## User Experience- UX 

## The Strategy Plane
<hr>

### Concept 

This project was created as part of the [Code Institute's](https://codeinstitute.net/) Diploma in Full-Stack Software Development. The project aims to create a full-stack website that will show the skills I have gained in HTML, CSS and Javascript. 

The main purpose of this website is to provide a platform for like-minded coffee connoisseurs who are looking for inspiration to brew the best coffee they can while being able to create and add their own recipes. A SuperUser will be able to approve, edit and delete user recipes in order to manage the content on the website. The target audience for this website is anyone interested in speciality coffee from home coffee drinkers to professional baristas. There are so many variables to creating the perfect cup of coffee from the origin of the wholebeans used, brewing device and technique, and even the type of water used. This website is to be used almost like a diary and guide for coffee lovers. 

<h3>Site goals</h3>

* Create a platform that allows users to post their favourite coffee and share their thoughts through comments and likes under posts. 
* The website is designed to be intuitive and easy to navigate. 
* The website was designed to be responsive and to meet all screen sizes. 
* The website should focus on the display of the posts/recipes and present them in a convenient way that is easy to follow while you make your coffee. 
* The website should appeal to both at-home coffee drinkers but also professional baristas acting as a coffee community hub. 

### User Stories

<strong>As a website user, I can: </strong>

* Navigate around the site and easily view desired content. 
* View a list of products and choose them. 
* Search products to find a specific one 
* Click on a product to view further details 
* Register for an account to avail of member services. 
* View product ratings to get an idea of what the admin thinks of it. 
* View reviews for each product to get an idea of what past customers think. 


<strong>As registered user, I can:</strong>

* Review the website service and its cameras. 
* Delete my previous reviews.
* Save my data under my personal profile. 
* Edit my previous reviews. 
* Manage my profile by updating my details. 
* Logout of the website. 
* Checkout easier by using personal profile. 
* Sign up to the newsletter

<strong>As a SuperUser, I can:</strong>

* Create and publish a new product 
* Create a draft of a new product to finish later 
* Create a new user, products and categories. 
* Delete userm products, categories and reviews. 
* Approve user's reviews. 
* Change a user's permissions on the webiste. 
* Have access to the backend django admin system. 



<strong>Agile Methodology</strong>

I managed this project's functions and development through GitHubs projects Kanban board, you can find it here: 

[grianghraf - USER STORIES](https://github.com/users/AdamVictory/projects/3)

<h3>Scope</h3>

#### Main Site Goals

* The website should be functional, easy to navigate and intuitive. 
* The front end should present the content clearly. Visually appealing. 
* Users to manipulate their content (CRUD). 
* Allow logged in users to interact with other posts through comments. 
* Search - all users can use the search bar to quickly find products. 
* Comments and Likes - Users can comment and like other posts. 
* Users can sign in and sign out to view the website from different perspectives. Also can register for an account. 
* Custom 404 page for good UI. 
* Use bootstrap to make the site responsive, and custom CSS and Javascript. 
* Create a webpage application using the Django framework. 
* Provide users a good website experience with cameras and lenses. 
* Provide a website with a clear purpose. 
* Provide a website that allows the business to market themselves. 
* Provude users tools that allows them to search for products. 
* Provide users with a safe way of checking out using Stripe. 


## The Structure Plane 
<hr>

<p>Grianghraf, will have four pages for first-time users.</p>

  * Home page, Coffees, Register, Login, 

<p>Users without an account can navigate through these four pages and will be able to see the details of each coffee recipe. However, they will not be bale to sign up to our newsletter until they have made an account. This is to ensure that our newsletter goes out to those who really value the brand. 

When the user creates an account and is logged in, the following pages will be displayed.</p>

* Home page, Coffees, Logout and My Recipes. 

<p>Logged in users will be able to access all of the website pages. They can access all the details of each recipe while being able to interact with them. 
They will also be able to access all of their recipes, add new posts, edit old posts or delete them.</p>


## The Structure Plane 
<hr>

## Functional Scope 

### Flowchart 

I created this Flowchart using [Figma](https://www.figma.com/)

![grianghraf Flowchart](docs/images/figma-flowchart.png)

## Database Schema 

I created this Database Schema using [Figma](https://www.figma.com/)

![Database Schema](docs/images/databaseschema.png)


## The Skeleton Plane

## Wireframes 

I created the wireframe using [Figma](https://www.figma.com/)

![Home Wireframes](docs/images/figma-wireframe1.png)
![All Recipes Wireframes](docs/images/figma-wireframe2.png)

## The Surface Plane


## Design 

### Color Scheme 

![Color Scheme](docs/images/colour-scheme.png)

I kept the colour scheme simple for this project as i didn't want to distract the user too much and wanted the focus to on the cameras themselves as the images for the cameras look so good. I intentionally chose black and white for the colour scheme to allow all of the focus to be on the camera imagery. 

All colours were generated by using [imagecolorpicker.com](https://imagecolorpicker.com/en). 

### Typography 

Two fonts are used throughout this website. I got them from [Google Fonts](https://fonts.google.comn/). 
The font family for this project was: 'Sofia Sans', sans-serif; . I wanted to keep the font very simple and easy to read as there will be a lot of text within each coffee recipe. 

![Font example](docs/images/font.png)

### Imagery 

I used [Conns Cameras](https://connscameras.ie/) to source the imagery for this project. The image is high quality and gives good inspiration for users on the purpose of this website.

![Background Image](docs/images/wholebeans.png)

## Features 

### Navigation Bar 

There are three different navigation bars: 

* Navigation Bar 1 - General Users

This navbar gives the general user the choice to see the homepage, view all coffee recipes, log in or sign up. They can also use the search bar. 

![Navigation Bar General Users](docs/images/nav1.png)

![Navigation Search Bar](docs/images/search.png)

* Navigation Bar 2 - Registered Users

This navbar shows links to Add recipe, My recipes and Logout. 

![Navigation Bar Registered Users](docs/images/nav2.png)

* Navigation Bar 3 - Super User

This nav bar is for the super user. There is an additional link that allows them to approve, edit or delete recipes. 

![Navigation Bar Super User](docs/images/nav3.png)

### Banner

This banner gives the general user / logged-out user a clear idea of what the site should be used for and also two call-to-action buttons that states "Sign Up" and "Sign in". 

![Banner Logged Out](docs/images/bannerout.png)


Once the user has logged in their banner will now look like this. The new call-to-action button states "Add Recipe"
![Banner Logged In](docs/images/bannerin.png)


### Footer 

My footer is very simple. It consists of social media links to push users to visit our social media channels. 
It also consists of a sentenance stating this website/project is for educational purposes only. \

![Footer](docs/images/footer.png)


### Other features 

* Home page - Consists of a hero image, title and slogan, short description of the website and a call to action in the form of a Sign up or Log in button. It also shows the latest 6 recipes that have been added to the website.
* All recipes - this page shows every recipe that has been added to the website. 
* Add recipe - Thanks to summernote, the user can use their template to add their own coffee recipe. It allows basic styling, ordered lists and to upload images of recipes. 
* My recipes - A page where users can see all of the recipes they have created and added to the website. They can edit or delete the recipes here. 
* Log in , Log out, Sign up - Users can log in or create an account if they wish to have access to functionality only available to registered users. 
* Recipe search - Users can use the search bar to find specific recipes they have in mind. 
* Recipe cards and details - All recipes appear on the recipe as cards, when clicked on it will link them to a recipe detail page. Providing them with even more information on the recipe and also showing them if other users have liked or commented on that recipe, 


### Future features 

* A social media element to the website similar to instagram where the users would have a profile and can post even more pictures while having followers. 


## Testing 

Testing was done throughout this entire project. Each user story view was tested to ensure this project worked from all perspectives. All testing information can be found in this [TESTING.md](TESTING.md) file

### Technologies Used 

* Python 
    * The following modules were used: 
        * asgiref==3.6.0
        * cloudinary==1.31.0
        * dj-database-url==0.5.0
        * Django==3.2.16
        * django-allauth==0.52.0
        * django-cloudinary-storage==0.3.0
        * django-crispy-forms==1.14.0
        * django-summernote==0.8.20.0
        * gunicorn==20.1.0
        * oauthlib==3.2.2
        * psycopg2==2.9.5
        * PyJWT==2.6.0
        * python3-openid==3.2.0
        * pytz==2022.7.1
        * requests-oauthlib==1.3.1
        * sqlparse==0.4.3



* Django 
    * Django has been used as the main framweork for this full stack project. 
    * Django AllAuth has been used for user authentication. 

    <br>

* Heroku - To deploy project
* ElephantSQL - Database for project
* Bootstrap - For styling of CSS/JS
* Django templating - main framework
* Figma - creating wireframes, flowchart and database schema. 
* Font Awesome - icons 
* Gitpod - Create/edit code
* GitHub - Repository to store code 
* Google Fonts - fonts for text 
* Cloudinary - upload imahes ad cloud hosting 
* JPG to WEBP | Cloudconvert - make imagery more accessible for web users. 
* Coolers - choose colour palette
* DevTools - assist development
* WAVE - To test accessibility 
* PEP8 - To test python code
* JShint - To test JavaScript
* Jigsaw - To test CSS
* Validator - To test HTML code 
* Favicon.io - To create different favicon sizes. 


### Resources 

* Code Institute's Codestar Django Blog was used at the start of this project to help me get started. 
* Django documentation 
* WSC Schools for CSS 
* Google 
* Stack overflow 
* Slack 
* Tutor support 

## Deployment 

### Deployment through Heroku 

1. Log in to Heroku

2. Select 'New' and then 'Create New App' 

3. Name the project and select your region, then create app. The name must be unique. This will create an app within Heroku. 

4. Add the database to the app, link your elepant sql url and hidden key to Heroku to connect the app to database. 

5. Navigate to the settings tab, in the config vars section copy the DATABASE_URL for use in Django configuration. 

6. Within the Django app, create a env.py file. Import the os library and set the environment variable for the DATABASE_URL. 

7. Add a secret key to the app using os.environ. Add this secret key to the Heroku Config VARS. 

8. In settings.py, import Path from pathlib, import os, import dj_database_url

9. In terminal migrate models to new database connection. 

10. Log in to cloudinary, in your env.py file add os.environ["CLOUDINARY_URL"]

11. In heroku, add the CLOUDINARY_URL to config vars. Also add DISABLE_COLLECTSTATIC with value of 1, this must be removed before final deployment. 

12. Add cloudinary libraries to list of apps. 

13. In settings.py add the STATIC files settings

14. In settings.py inside the Django project I changed DEBUG = False;

15. Also in the settings.py file I added X_FRAME_OPTIONS = "SAMEORIGIN";

16. In Heroku I went back to Settings > Config VARS and removed the DISABLE_COLLECTSTATIC var;

16. In Heroku I navigated to the Deploy section;

17. I clicked to connect to GitHub and searched for my repository for this project. I clicked on manual deploy to build the App.  When finished, I clicked the View button, which redirected me to the live site.

### Credits 

* Code Institute's Boutique Ado walkthrough. 
* Unsplash for the main image and placeholder image. 
* How to create a search bar by John Elder on YouTube, 
* Create custom 404 error by Cryce Truly 









