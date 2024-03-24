---
layout: post
title: "Enhancing Your Chess Journey with Chessify: A Comprehensive Review"
date: 2024-03-21
tags: [chess, tools, technology, chessbase, chessify]
description:  "we delve into the latest innovations in chess technology and explore the enhancements Chessify brings to the table."
image:  '/images/shri-CG-JvqWqutM-unsplash.jpg'
---

<div style="text-align: left; font-size: smaller;">
Photo by <a href="https://unsplash.com/@thefatdash?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">shri</a> on <a href="https://unsplash.com/photos/chess-pieces-on-chess-board-CG-JvqWqutM?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
</div>  

# Website Update

I made a significant change to my blog page which includes some new features including topic tags, featured blog posts with a beautiful and modern design which is also great on mobile devices. Additonally search is enabled now and makes it easier to find topics of interest. 

If there is still any hiccup, bear with me, or even better: drop me a note.

If you like it: drop me a note or comment

If you don't like it: yeah, you know what to do

## Introduction

Seeking constant improvement is intrinsic to the pursuit of chess mastery. In my previous blog post, "What's Next," I evaluated Chessify and other tools as potential aids in this journey, aiming to augment or replace certain functions of ChessBase with more efficient alternatives.

Now, breaking news surfaces: Chessify has seamlessly integrated the ICCF database, boasting over 2 million high-quality correspondence chess games. Even more enticing, for a limited time, they offer FREE access to all users! While this development promises affordability, especially when compared to maintaining a Stockfish cluster on platforms like Azure or personal hardware solutions, there's a caveat: existing subscribers must cancel their current subscription to take advantage of this offer, rather than seamlessly transitioning or receiving a discounted rate.



<div style="border: 1px solid white; padding: 10px">
     <blockquote style="font-size: 20px; font-style: italic; font-weight: 400;">
Hello Egbert,

Thank you for your kind words and congratulations!

Regarding your subscription and the ICCF discount, you can renew your subscription in November and take advantage of the ICCF special offer at that time. However, if you'd like to use the discount now, you'll need to upgrade your subscription from Amateur to Master.

We appreciate your support and for mentioning us on your blog page. 

Sincerely,
Chessify support team
   </blockquote>
</div>

As a user you can chose now between several databases: Megadatabase, which claims to be the competitor to ChessBase, ICCF, the newly added database and last the Lichess game database. Typical filter functions are available and for MegaDatabase you can exclude rapid and blitz as an example.

<div style="text-align:center;">
  <img src="{{site.baseurl}}/images/Chessify 2024-03-20 160443.png" alt="Chessify" style="width:80%;">
</div>

I proceeded to put Chessify through its paces, initiating several maneuvers and analyses. Firstly, I filtered games with my name:

<div style="text-align:center;">
  <img src="{{site.baseurl}}/images/Chessify 2024-03-20 163214.png" alt="Chessify" style="width:80%;">
</div>

Subsequently, I requested a thorough analysis with a depth of 30:

<div style="text-align:center;">
  <img src="{{site.baseurl}}/images/Chessify 2024-03-20 164423.png" alt="Chessify" style="width:80%;">
</div>

Initial impressions suggested parity with industry staples like ChessBase or Lichess, yet reality proved otherwise. Utilizing a recent challenging game from the 2024 Champions League, I instructed Chessify to analyze via the ChessBase plugin, employing *Fine* and *9s* parameters. The game, characterized by a tense climax resulting in a draw, exposed a significant discrepancy:

#### ChessBase Tactical Analysis

<iframe style='border: 0;' width='900px' height='600px' src='https://share.chessbase.com/SharedGames/frame/?p=nNnDqfUIXcgWG1elveS60I0zIeLvvKgmmmwDFpbsiMIiR7OuL75ArDMSGRmDPPpW'></iframe>

Subsequently, using the standard PGN from the ICCF website, I subjected it to Chessify's full game analysis, configured with a depth of 20, which is the standard preset on the the website.

#### Chessify Full Game Analysis

<iframe style='border: 0;' width='900px' height='600px' src='https://share.chessbase.com/SharedGames/frame/?p=yFHpqEPJQk5D3BZo3YSiU/Q4FP/Cm3qRxfMH3qPDHuakP01X9doz7tvtMuATRRav'></iframe>

The disparity is stark! Chessify flagged move 33. ..g5?! as a Black inaccuracy, favoring White with a 1.01-point advantage, only to later suggest the erroneous move 34. Bd2!? for White, erroneously indicating a minor advantage. That this was the only correct move was overlooked and really weird, Chessify suggested then the alternative 34. Bd2, which is exactly the move I made.

In contrast, Lichess failed to identify any flaws:

<iframe width="600" height="371" src="https://lichess.org/study/embed/PmMDa3wy/GfOBTEdT" frameborder=0></iframe>

## Chessify Mobile App

Finally, exploring the Chessify Mobile App proved frustrating. Despite its potential, the app operates independently of the Chessify platform, akin to the disjointed structure observed with the ChessBase app. This segmentation introduces an additional revenue stream, diverging from user expectations. Why should loyal subscribers incur extra expenses merely to access the app on mobile devices?


<div style="border: 1px solid white; padding: 10px;">
     <blockquote style="font-size: 20px; font-style: italic; font-weight: 400;">
Actually, our mobile app and website are separate products, so you need different accounts, as well as different subscriptions for them.

If you have any further questions or need assistance, please don't hesitate to reach out.

Sincerely,
Chessify support team
        </blockquote>
</div>

# Conculsion

In the ever-evolving landscape of chess technology, Chessify emerges as a promising contender. Its integration of the ICCF database heralds a new era of accessibility and analysis. However, discrepancies in analysis accuracy and the disjointed nature of its mobile app underscore areas for improvement. As enthusiasts, we eagerly anticipate advancements that align with the seamless, intuitive experience we crave in our pursuit of chess excellence.

**Amici Sumus**


> [Subscribe to receive exclusive chess tips, updates, and strategies directly in your inbox](https://follow.it/senior-chess-improver?leanpub) 

> [Follow me on Mastodon for chess insights and more.](https://mastodon.online/invite/mWSpfQP8)