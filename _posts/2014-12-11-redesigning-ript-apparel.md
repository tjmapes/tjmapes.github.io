---
title: Redesigning RIPT Apparel
date: 2014-12-11 00:00:00 Z
categories:
- design
layout: post
desc: redesigning riptapparel.com
keywords: re-design, design, development, business, e-commerce
comments: true
---

Earlier this year it dawned on me that riptapparel.com needed a facelift.  Not just a fresh coat of paint, but some user experience tweaks and some user interface overhauls to better set us up for the future.  

What exactly does that mean?  We've branched outside our daily model and have started [offering other products for sale](https://www.riptapparel.com/store).  This is something we plan on continuing but the old website wasn't really designed with that in mind.  Granted, we haven't gotten to where I want to be 100% yet due to [lacking development resources]({% post_url 2014-11-21-trials-and-tribulations-of-hiring-in-house-software-engineers %}) but we've laid the groundwork for whats to come in 2015.

So what's changed you ask?
<!--more-->

### The Product Slider

The product slider on the homepage is without a doubt the most important piece of real estate we have.  It's why people come everyday... to see the daily designs for sale.

#### The old product slider

The old slider made it sometimes very difficult to see what the actual design was.  Firstly it showed the Men's model upon page load, then after a few seconds, started auto advancing to the next product.  We felt this was distracting to the user and took control away from the user as well, ultimately resulting in a poor user experience.  

Besides that, it was pretty clunky.  If you hovered over the visible area, the sliding was supposed to pause.  This wasn't always the case and sometimes bad code took control and left the user paralyzed.

<img src="/images/slider-old.jpg" alt="RIPT Apparel's old product slider">


#### The *NEW* product slider

The countdown timer is much much larger and now incorporates our mascot, the Reaper (yet to officially be named).

The new slider showcases the zoomed/cropped image first instead of a model shot, so within seconds, users will know exactly what the designs are.  The slider no longer auto advances giving control back to the user.  The image housing is now clickable on either the left or right side (via arrows) to easily scroll through all the available products for sale of each design.

<img src="/images/slider-new.jpg" alt="RIPT Apparel's new product slider">



### Comments

People come to our website to see the daily offerings but also like to share opinions on them via the comments section.

#### Facebook Comments (old)

Our old comment system was one giant facebook comment thread.  Being tied directly to Facebook had it's benefits but ultimately, it was hard to carry out a conversation day in and day out.  We decided it was time to go.  

<img src="/images/comments-old.jpg" alt="RIPT Apparel's old comment system">

#### In-House Comments (New)

We decided to rebuild the comments from the ground up.  This initial V1.0 release brings with it your typical commenting features:

- Ability to leave a comment and reply to a comment
- Use of your RIPT Apparel username and avatar

The only additional features are the special avatars and ranks configurable by admins.  This can lead to some real fun :)  We still need to hash out exactly what all the ranks are, but it's the first of many new features to come in the overall *gamification* of the comment system.

<img src="/images/comments-new.jpg" alt="RIPT Apparel's NEW comment system">


### Other Changes

There are really way too many changes to list.  One nice upgrade we feel was the [T-Shirt Graveyard](https://www.riptapparel.com/graveyard).  Now it's more interactive and has much larger images.

<img src="/images/graveyard-new.jpg" alt="RIPT Apparel's Graveyard">

We've also really tried putting a focus on customer service by including our phone number and live chat options right in the header of the page.

### Goals for 2015

- Build out new features
- Gamify the comments app
- Vigorously A/B test the product slider and other areas
- Move to a more service oriented architecture to help with load times on the front end as well as the back end, in turn making our current monolith stronger and smarter

Thanks for reading.  If you have thoughts or suggestions on the new look, feel free to comment below and let me know.
