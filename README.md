# TEES - By Juliet Gardener

**Fourth Milestone Project: Full Stack Frameworks with Django - Code Institute**

TEES is an e-commerce T-Shirt web application, that allows users to search and purchase their chosen t-shirt design.
The user will be able to add their selction to the shopping cart and pay for their product using credit or debit card.
To purchase their product the user will need to log in or register an account with TEES.

## Demo

A live demo can be found [here](https://milestone-4-tees.herokuapp.com/)

## UX

My goal in the design was to create an online t-shirt sales where users could view and search for products, with the ability to purchase 
their chosen products. I wanted to create the minimalist look, so the user would not be overloaded with too much design whilst looking
at the product range. I also only included the necessary authentication mechanisms that were needed to be able to carry out the purchasing
of products to aid user productivity.

## Technologies

* HTML5
    * The structure for site
* CSS 
    * The style format for the site
* jQuery 
     * To manipulate the Document Object Model
* JavaScript
     * To create interactive data design
* Python3
     * To create and develop the web application
* Django
     * The web framework for python for web development
* Bootstrap (v3.3.7)
     * Framework for responsive design

## Features

The site features the Stripe API which is connected to Javascript, this allows the functioning and security of online payment processes.
The site also features Bootstraps responsive collapsible navbar that serves the sites navigation header.

## Testing

The site was tested using Djangos backend built-in admin panel, this allows me to authenticate users, 
add and delete products and check orders. To access the admin panel I created a superuser in the command line interface.
I tested the site by inputing data into the authentication mechanisms, then I checked to see if the information pulled through
in the admin panel. I also added new products in the admin panel that are featured on the site.

The product model database for the site was tested by creating a string method.

The site was also tested across multiple browers and mobile devices to ensure responsiveness.
Chrome developer tools was used against the site to check compatibility.

## Deployment

Version control was maintained by pushing new commits to the repository for each new updated piece of 
functionality using git and github.
The final version was then deployed onto the Heroku platform.

## Credits

### Content
The contents of the site were written by me 

### Media
The icon image used on the site was obtained from [here](https://upload.wikimedia.org/wikipedia/en/e/e5/DJKAM_Cartoon.png).
The product information for the site was taken from
[here](https://live.staticflickr.com/7426/11663276606_7e3551f995.jpg),
[here](https://cdn.pixabay.com/photo/2016/10/02/22/17/red-t-shirt-1710578_960_720.jpg),
[here](https://live.staticflickr.com/2780/4511611658_ec1cd61198_z.jpg), and 
[here](https://li6.rightinthebox.com/images/384x500/201603/lbrtmw1458617431185.jpg).

### Acknowledgements
The font heading styling was taken from this [site](https://fonts.google.com/).

The responsive navbar and glyphicons used on the site were taken from [Bootstrap](https://getbootstrap.com/docs/3.3/).

The online secure payments system was registered with this [site](https://stripe.com/gb).



