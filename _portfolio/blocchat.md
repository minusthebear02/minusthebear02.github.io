---
layout: post
title: BlocChat
thumbnail-path: "img/blocchat.png"
short-description: Build an easy to use chat application

---

{:.center}
![]({{ site.baseurl }}/img/blocchat.png)

## Explanation

A simple chat application is often underestimated. Communication is of the utmost importance when it comes to business, friendship, and life. That’s why creating an understated chat app that’s efficient and works when you need it is crucial. This is why I was brought onto the team as the sole developer to build out the application.

In today's internet age we expect everyone to have the same technological skill as we do but that's not always the case. Our main focus for this application was to make it inviting for everyone within our client's company to use and to not be overwhelmed by. 

## Problem

BlocChat was created out of the need for business employees to communicate with each other in a straightforward application during the course of the work day and beyond. Without simple communication companies cannot thrive. With a sales background I was brought on to build the app to make sure it meets our client's needs.

## Solution

We had asked our potential customers what they would like to see in a chat application and how they would like it to work. The overwhelming answer we received was some form of “Make it easy to use and understand”. From there we talked about the best UI design for the would be user. After a few prototypes and revisions we finalized on a simple two column layout, to separate the chat-room itself from the list of rooms available. 

At this point, the client had brought up a few ideas, such as opening a new window for each chat room, but I discussed some UX concerns and we decided to keep it in-app since that's more in-line with our minimalist design thoughts.

For optimized usability and ease of use we only included three main functions into the app. The first being a log in prompt that prompts the user to sign in with a username if there is currently no username detected.

{:.center}
![]({{ site.baseurl }}/img/blocchat-username.png)

The second being an option to create and name a new chat-room via the “Add Room” button. 

{:.center}
![]({{ site.baseurl }}/img/blocchat-addroom.png)

The last, and most obvious, being the ability to send a message to a chat-room with the “Send” button. Each function works as planned and is easy and straightforward.

Creating a linking a database to handle the information for each message was the first step. I chose Firebase as the best initial option to handle this and it was the perfect fit for our current needs.

## Results

After shipping the beta version of the product for use in business for inter-company communication BlocChat received some great reviews. The clients were surveyed and most were happy with the simplicity of creating chat rooms and sending messages. As is usually the case we had a few small bugs to sure up before we were finished. For instance, some users had trouble creating new chat rooms after opening the "Add Room" window. After asking some further follow up questions to try to pinpoint the exact issue we found the bug in the button script, made the quick fix and shipped it back out to those customers for retesting. After following back up with these users they had no issue going forward. 

## Conclusion

This was a quick project with a short deadline that was completed with regards to its user’s aversion for complicated programs. By working with Firebase I was able to learn some of the basics of working with databases. What surprised me was how easy it was to understand how to use it. Overall, this was a great project and I look forward to adding some more useful functions while keeping the app easy to use.