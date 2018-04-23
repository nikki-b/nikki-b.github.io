---
layout: post
title: Coding Dojo &middot; Weeks Two & Three
categories: [bootcamp, coding dojo]
---

The last couple of weeks have gone by so quickly – it feels like I just started this program. I essentially re-learned everything I had previously taught myself about web development over the last decade… in the first week and a half of Coding Dojo. Now I’m well into new territory and it’s exciting/slightly terrifying!

<!--more-->
**Week Two:**

The second week focused on jQuery/jQuery UI and database design. jQuery is a Javascript library that provides useful functions for animation, event handling, HTML manipulation, etc. Instead of writing lines of Javascript code, you can use built-in functions for various tasks. jQuery UI is a collection of interface widgets/templates built from the jQuery library.

Database design was a completely different task. Using MySQL Workbench and MAMP/WAMP, we created ERDs (Entity Relationship Diagrams) to be used for storing/accessing information in databases.

After creating ERDs, we moved into getting/changing information in a database using queries.
A query to grab all comedies from a film database might look like this:
{% highlight sql %}
SELECT film.title, film.description, film.release_year, film.rating, film.special_features, category.name
FROM film
JOIN film_category ON film.film_id = film_category.film_id
JOIN category on film_category.category_id = category.category_id
WHERE category.name = “comedy”;
{% endhighlight %}

Queries are straightforward, but get a bit confusing when you have a large database with multiple joined tables so normalization (rules for consistency) is very important.</p>

**Week Three:**

So much PHP this week! PHP is a server-side language that helps deliver information from the back-end to the front of a website. It can grab things from a database and create dynamic content.<br />
Our assignments this week started with the fundamentals of PHP, generating random numbers, creating HTML content, etc. Then we delved into session variables and using PHP with a database. (This is where the database design came into play.)

All of this culminated in a bigger assignment, The Wall. I used Bootstrap to create a clean layout and forms. The SQL database collected login information and the comments/messages, then showed the information via queries and PHP. This assignment was a challenge, but helped me to understand the basic applications of what we’ve used so far. What you don’t see in the video below (EDIT: video gone :( ) is that the code checks the registration info (for empty fields, invalid emails, short or non-matching passwords) and the login info (for a matching email in the database and the right password). If something triggers an error, the main page spits it out below the form to let you know what you need to fix.

Technically this assignment was in the beginning of the current week (four), but it illustrates more what I learned last week.

The next recap will cover Week 4 (Object-Oriented PHP and MVC with CodeIgniter)!