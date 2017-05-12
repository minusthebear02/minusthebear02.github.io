---
layout: post
title: BlocChat
thumbnail-path: "img/blocchat.png"
short-description: Build an easy to use chat application

---

{:.center}
![]({{ site.baseurl }}/img/blocchat.png)

## Explanation

A simple chat application is often underestimated. Communication is of the utmost importance when it comes to business, friendship, and life. That’s why creating an understated chat app that’s efficient and works when you need it is crucial.

## Problem

BlocChat was created out of the need for business employees to communicate with each other in a straightforward application during the course of the work day and beyond. Without simple communication companies cannot thrive. With a sales background I was brought on to build the app to make sure it meets client needs.

## Solution

We had asked our potential customers what they would like to see in a chat application and how they would like it to work. The overwhelming answer we received was some form of “Make it easy to use and understand”. With that in mind we started building.

For optimized usability and ease of use we only included three main functions into the app. The first being a log in prompt that prompts the user to sign in with a username if there is currently no username detected. The second being an option to create and name a new chat-room via the “Add Room” button. The last, and most obvious, being the ability to send a message to a chat-room with the “Send” button. Each function works as planned and is easy and straightforward.

Creating a linking a database to handle the information for each message was the first step. I chose Firebase as the best initial option to handle this but, since we didn’t want to nest message info inside chat-room data for search-ability and efficiency reasons, we had each new message reference the room id that it was inside.


## Results

After shipping the product for use in business for inter-company communication BlocChat received rave reviews. Employees reported have little to no issue figuring out how to use the application without any sort of instruction. We can credit this to building the application with user’s common sense in mind, and it worked!

## Conclusion

This was a quick project with a short deadline that was completed with regards to its user’s aversion for complicated programs. By working with Firebase I was able to learn some of the basics of working with databases. What surprised me was how easy it was to understand how to use it. Overall, this was a great project and I look forward to adding some more useful functions while keeping the app easy to use.