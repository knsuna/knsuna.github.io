---
layout: essay
type: essay
title: E5- Blog
# All dates must be YYYY-MM-DD format!
date: 2020-12-03
labels:
  - Me
---
Checkpoint A:
Describe your design for your site's shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.

I am thinking that it will be integrated into the products page. When the user adds a product to the cart, it will appear on the right hand side of the screen. I am thinking that here they can just add or subtract the products that they have. Also, there may be a deletion function for the products. I am pretty set on doing it this way. To make this work, the main thing that I need to work is taking the name and quantities from the cart. Another way that I could use the cart would be to just display how much you have added into the cart. Then just make a form to send to the invoice. One more example of using the cart would be to display all of the information as a popup when clicking on it. I will probably not go down this route because it may become complicated. 

Checkpoint B:
Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their keys) you will use to manage the shopping cart data and how they will beused in SESSION.
I will use sessions to make sure that when adding values to the cart, it is being added from the current session. This gets rid of the problem of multiple users affecting the quantites of the product. The data that will be stored is the group and quantity of the product. For example if you ordered one regular sofa, the cart would display Sofa:[1]. 
 
Checkpoint C:
How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?
I use various data validation functions to make sure that they users have an account or have logged in properly. Once this is done, it will then process you to a certian page. One of the main security concerns is that a cookie may be saved for to long which allows someone other than the intended user to log onto their account.The best solution for this would to make a cookie that expires after a certian period of time or a certian of inactivity.

Checkpoint D:
Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary):
Upon sucessful login, I will display their name. I think that the best way to do this would be to get their cookie information and display their full name based on their username. 

Checkpoint E:
If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?
I am not working with a partner.


Checkpoint F:
How are you approching Assigment 3 differently than Aassignment 2?
I am not actually working that much on the coding than in Assignment 2. However, I am spending much more time thinking about what I am going to do. Most of the time I spend trying to search how I am going to make different components work together with eachother.
