---
layout: post
title: Coding Dojo &middot; Weeks Four & Five
categories: [coding dojo, bootcamp]
---

**Week 4:**

This week started off with finishing the assignment I shared in the previous post, The Wall. On Tuesday, we moved on to PHP Object-Oriented Programming (OOP). OOP is a different style of coding (compared to the procedural style we learned first) that focuses on grouping similar tasks into classes. This style is kind of difficult to wrap your head around at first, but it helps keep code clean and easy to maintain. It’s nice to only have to update your code in one place as opposed to every time you called the task within your document.

<!--more-->

Next – CodeIgniter! CodeIgniter is a development framework for PHP, using the Model-View-Controller pattern. Essentially, you have a model that interacts with your database and a controller that sends information to/from the view (the page you see in your browser). We started simply with just a controller and view, and by the end of the week had multiple models/controllers/views sending code all over.

Some example assignments:

* Generate a string of random numbers and letters every time you click (handy if you need characters for a password.)
* Adding to and deleting from a database – as well as showing the data that was currently in there. When “remove” is clicked, you’re sent to a separate confirmation page before the information is actually removed.

**Week 5:**

More CodeIgniter this week!
A basic login/registration with validations! 😱

Finally, in week 5 we worked on using AJAX and APIs. AJAX is a way of exchanging data with a server to dynamically update a website without reloading. For example, when you delete an item from your shopping cart on a website, it doesn’t cause the whole page to reload – it’s just removed right then and there.

Notes assignment: a page to add "post-its" (and be able to edit/delete.) The key here is that all of this is done without the page reloading at all. If I do reload the page, it’ll show whatever notes I had on the page. When the notes are added, it’s done so dynamically – they’re added to the database for more permanent storage, but you see a temporary version of it on the screen. If the page is reloaded, the database version is shown. The new notes are submitted when “Add Note” is clicked and the descriptions are sent when you click anywhere outside of the description box.

I was not able to delve into APIs as much yet, but I played around with the Open Weather API. There are many, many APIs out there (Twitter, Flickr, etc) that allow you to use information from those sources. The Open Weather one allows you to grab a host of current weather information from anywhere in the world and use it on your site.

And that was it! Moving on to Week 6!