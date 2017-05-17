---
layout: post
title: BlocJams
thumbnail-path: "img/blocjams.png"
short-description: A music app for finding and streaming underground tunes

---

{:.center}
![]({{ site.baseurl }}/img/blocjams.png)

## Summary

The world can will never have enough music. With the huge amount of songs being churned out daily how can one application possibly house it all. Well, it can't. We've all been there, you open Spotify and search for your new favorite song by that underground artist you love and _it's not there!_ If Spotify doesn't have it where could you possibly find it?! That's where BlocJams comes in!

## Explanation

BlocJams is a new web app that was created to handle the streaming of music you wouldn’t hear on Spotify. Their main focus is on easy to use, stream-lined access by anyone and everyone. Easy to use software for obscure, underground music. I was brought onto the BlocJams team at the beginning to help build the app from the ground up.
  

## Problem

Our main focus was on creating three main pages: Home page, Collections page, and the Album/Player page. Building the music player being the most in depth build and the make or break aspect of the app it was crucial to spend the most of our time there. Each individual function of the music player like the Play/Pause button, the Next and Previous buttons, the seek bar, the volume bar, etc. was meticulously coded to ensure correct functionality.

## Solution

 Functionality being of the highest importance, I brainstormed each behavior of the music player, big and small.

<video width="560" height="420" align="center" loop autoplay controls>
    <source src="{{ site.baseurl }}/vid/blocjamsdemo.mp4" type="video/mp4">
</video>

After the first build we conducted beta testing making sure we sent the app to a variety of people with different browsers to make sure we were functional across the board. Getting results back there were a few bugs to fix before the next round of tests. These tests did not reveal any real issues but we plan on proactively testing the product to catch anything that may arise.

## Results

<a href="http://froehlich-bloc-jams.netlify.com/">See for yourself!</a>

I started by creating the app with vanilla Javascript to make sure I knew the ins and outs of the program and how it worked down to the nuts and bolts. After creation, I wanted to turn my attention to efficiency. On that note I refactored much of the application with jQuery and cut a huge amount of now unnecessary lines of code before finally refactoring into the more readable AngluarJS framework. With the final product we have an efficient, easy to understand and use music streaming app where you’ll find the music that’ll become the music you heard before anyone else.

## Conclusion

Each iteration of the application worked, which was the most important thing, but each new version got better and better. This project taught me a lot about the benefits and hindrance of each language used and helped me see the importance of choosing the right language when starting a new project.  It was interesting to see how well jQuery and AngularJS worked together and I’ll be sure to use them in the future.

