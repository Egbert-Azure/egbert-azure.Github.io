---
layout: post
title: "What's next? Continues improvement and finding the right tools"
date: 2024-03-16
tags: [chess, tools, technology, UltraCorr23, Noctie.ai, chessbase]
description:  "In the pursuit of chess mastery, the search for effective tools and resources is ongoing. Join me as I explore my journey towards improvement and the latest innovations in chess technology."
image:  '/images/hunter-haley-s8OO2-t-HmQ-unsplash.jpg'
---

<div style="text-align: left; font-size: smaller;">
Photo by <a href="https://unsplash.com/@hnhmarketing?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Hunter Haley</a> on <a href="https://unsplash.com/photos/four-handheld-tools-on-board-s8OO2-t-HmQ?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
</div>

## Introduction

For me, the question is actually, "How do you continue, and what do you want to be in chess?" Setting goals can be simple. Now that I have achieved the CCE title, I have proven that seniors can improve their game, and age is just a number. Am I good at blitz or rapid? Of course not. I need my time. So, correspondence chess is the ideal setup for me. The slow pace and chat with individuals around the world are very rewarding.

With ELO of 2157 now, let's say I want to reach 2200 by early spring next year (woot woot, that's bold). I need to revisit my repertoire and improve my endgame to work towards the goal. Which I actually do! I'm a long-time ChessBase heavy user and do most of the preparation and learning, such as repertoire training with ChessBase. 

## Chessbase?

However, I have 6 support tickets open and I'm getting increasingly frustrated and questioning the future of ChessBase. Why? ChessBase's so-called cloud, for example, is not a cloud. It's just a file share or, at best, a function like OneDrive. If you move your repertoire to ChessBase "Cloud," don't expect local changes to be synced. They don't sync. MegaDatabase, the core of the truth, needs more innovation. A local player database is still mandatory and there is no reason why.


Then the online tools, compared to offline tools, could be more consistent and even have a more clear GUI. The premium account certainly gives you some return due content, but MegaDatabase is on top and lacks quality in annotated games. Just look at very famous games from Bobby Fischer and check the annotations. Inconsistent, mixed language. And there is more. Do I expect everything to be perfect in such a vast database? Not really, but the basics should be. Opening Database released every year is the same thing. If you expect those annotated games to roll up to MegaDatabase or are the same, they are not. And then Correspondence Chess. ChessBase keeps a correspondence chess database separate for extra money. That's fine, but why am I not able to find players in the player database, at least?

Next, the engines. Chess engines have helped us analyze perfect all stages of a game. I wanted a remote server connected to ChessBase Software for analyzing chess games, tactical analysis, etc. You might think, why not just run Stockfish or other engines on your laptop. Well, that is true, but the heavy CPU usage of such an engine on a laptop -let's assume 8 cores- drains the battery fast if it is not connected to power. Also, a remote chess engine running on a cluster performs and can scale much better. In short, Chessbase is not able to deliver this. I wrote some blogs about it, and if you would like to do a deep dive, check out my [GitHub repo](https://github.com/Egbert-Azure/stockfish-cluster). Chessbase argues they have a cloud option to share an engine or book one. This is true, but it's not cloud computing. You can share your computing power, and then your computer is blocked. I even reached out directly to the man himself 2 years ago, Matthias Wüllenweber, sharing the concept and draft architecture. Since then, I have never heard back.
That said, Chessify is now making a business out of it and is adding functions similar to Chessbase.

## Decisions

Long story short, I canceled my Chessbase premium subscription and will no longer buy Megadatabase. Instead, I will update with games from [The Week in Chess](https://theweekinchess.com/) and support the great work of *Mark Crowther*, who runs The Week in Chess since 1994. 

I will also continue with Ultracorr from Dr. Tim Harding. [Ultracorr](https://www.chessmail.com/index.html) costs a fraction of Chessbase's own correspondence database, and the quality is fantastic because it is from a real expert.

Now, let's come to the core of my thought process. Regardless of all the great functions in Chessbase, I miss one essential feature: *here is my game; please tell me immediately where I failed in the opening and tactics humanly, like a chess coach.*

And some clever people have thought about this already.

## New Kids on the block

### [Noctie.Ai](https://www.linkedin.com/company/noctie-ai/about/)

**Noctie.ai** is a remarkable personal AI chess coach with a human touch. Its mission is to teach chess in a joyful and effective manner, much like you would experience with a respected human coach. 

Some of the people behind it:

- [Samuel Sonning](https://www.linkedin.com/in/samuelsonning/)

- [Sabina Sonnig](https://www.linkedin.com/in/sabinasonning/)

- [Daniel Öhrlund](https://www.linkedin.com/in/danielohrlund/)

 In their own words about Noctie:

>*"We're making the world's best chess training universally accessible, giving every player a personal, AI-powered chess tutor."*
>
>The best way to learn anything is one-on-one tutoring. One out of ten people plays chess regularly, but few have access to tutoring. We let them learn effectively on their own by practicing against a human-like AI and getting instant feedback on their play. Unlike other chess computers, our AI emulates human play and is both fun and instructive to play against. 

Here are some key features of **Noctie.ai**:

1. **Play Rating Test**: Challenge Noctie to a game and discover your real chess rating. Receive instant feedback while playing against a chess AI that emulates human play at your level.

2. **Custom Tactics & Exercises**: Noctie provides custom flashcard exercises based on real situations from your games. Practice with spaced repetition learning to enhance your skills.

3. **Openings & Endgames**: Play against the computer in specific openings you want to improve. Master endgames and solidify your learnings.


**How does Noctie compare to regular chess bots?**
Unlike regular bots that calculate far ahead and play mechanically, Noctie emulates human intuition and play. It behaves like a human at your level, providing a more realistic experience.


<div style="text-align:center;">
  <img src="{{site.baseurl}}/images/noctie-exec-flash.png" alt="Exercises" style="width:50%;">
</div>


And another example

<div style="text-align:center;">
  <img src="{{site.baseurl}}/images/noctie.png" alt="Exercises" style="width:40%;">
</div>


The above shows some results after a quick test, and I was impressed.
Unlike Chessable, which involves repeating and repeating without understanding until you memorize the lines, this is interactive and works with electronic flashcards. The questions the bot asks are great and very interactive.

Now, where is the hook? Sure, the price tag


<div style="text-align:center;">
  <img src="{{site.baseurl}}/images/noctie-exec.png" alt="Costs" style="width:50%;">
</div>

$15.50 per month is definitely at the very upper level. If the company wants to address the amateur chess player market —which I believe it is—that's a lot. However, the concept is excellent, and I will keep an eye on it.

Another exciting but still in-the-making tool is Chesscloud; its founder is Jeffrey Thor.

### [ChessCloud](https://www.chesscloud.com/)

**ChessCloud** is a platform created by **Jeffrey Thor** for chess enthusiasts. It offers tools and resources to enhance your chess experience. The primary focus of ChessCloud is for opening repertoire management. With a central place to store your opening lines, you can tailor post-game analysis to your own repertoire. The plan is also to run ChessCloud, which is also a game server. You can explore ChessCloud at [chesscloud.com](https://www.chesscloud.com/). Additionally, Jeffrey Thor runs a [YouTube channel](https://www.youtube.com/watch?v=ZCdgGx1L7aY)

<p><iframe src="https://www.youtube.com/embed/ZCdgGx1L7aY" frameborder="0" allowfullscreen></iframe></p>

I didn't check it out because you can only log in with your Google or other social accounts, not email. However, it is quite an interesting approach and might be another option in the near future.


### Chessify

If you consider Chessify just a remote engine cluster, you might consider a different approach. But if you see now what the company has built around, it is worth checking it out.

There is a good overview on YouTube, where IM Kostya Kavutskiy reviews the new web analysis tool from Chessify. This tool allows users to annotate games, build an opening repertoire, prepare for opponents, and more.

<p><iframe src="https://www.youtube.com/embed/ivYG1Fb3OQI" frameborder="0" allowfullscreen></iframe></p>


Remember, this video is an affiliated review, but it's pretty accurate.

Chessify is an intriguing alternative to ChessBase, offering various features and functionalities. Let's explore how they stack up:

- Web-Based Accessibility:
Chessify stands out for its accessibility through web browsers, enabling users to analyze games, curate opening repertoires, and prepare for opponents from anywhere. In contrast, ChessBase relies on standalone software installed on a computer.

- Engine Integration:
Chessify provides cloud engines and servers compatible with third-party GUI programs like ChessBase, SCID, and Fritz19. On the flip side, ChessBase features its own integrated engines and supports external engines like Stockfish.

- Functionality:
Chessify allows users to annotate games, perform position analysis, and build opening repertoires. Meanwhile, ChessBase offers a comprehensive suite of tools encompassing database management, game analysis, and training resources.

- Cost and Accessibility:
Chessify offers flexible pricing options with its cloud packages, allowing users to select plans tailored to their needs. The pricing is very clear; there are no hidden additional costs. You get what you pay for. Conversely, ChessBase operates on a one-time purchase subscription model called ducats, which has additional costs for supplementary engines.

[Link to try Chessify](https://chessify.me/auth/signin?ref=JimMorrison42*6923)

For me the combination with ChessBase 17 and Chessify makes a difference in preparing and analysing.
And some additional functions are beyond what ChessBase is able to deliver. First example is video finder feature on Chessify is a powerful tool that makes it easier to locate specific positions within YouTube videos.


<p><iframe src="https://www.youtube.com/embed/gu9T-VGmpbI" frameborder="0" allowfullscreen></iframe></p>

Another killer feature is the scanner, a powerful tool designed to convert printed chess diagrams from books, magazines, or other sources into a pgn format. You take a photo of a printed chess position using your smartphone or tablet. The Chessify app processes the image and recognizes the chessboard, pieces, and their positions. You can share or store the position.


<p><iframe src="https://www.youtube.com/embed/BRrlxWyhbO4" frameborder="0" allowfullscreen></iframe></p>

[I think it's worth to give Chessify a try](https://chessify.me/auth/signin?ref=JimMorrison42*6923)

Chessifiy recently announced a new feature with chess-enhanced GPT which might have a similar approach like Noctie.ai (I'm guessing here).

As part of the collaboration with ICCF, Chessify provide a special 20% discount for all correspondence chess players. Simply use the promo code ICCF at the checkout to save 20% on your [first purchase](https://chessify.me/auth/signin?ref=JimMorrison42*6923). 

## Conclusion

I'm very impressed by Noctie.ai and will continue using the free version for a while to get a better idea. The free version with daily game with live feedback, flashcards from your mistakes, some basic endgames but with opening focus might be good enough for a start. However, the $15 price tag for a full blown version is not an option for me. 

As an amateur player, I think you should spend your money where you believe you can have fun playing the game, improve, and reach your goals.
The best chess improvement resources cost money, but there are plenty of free resources out there to boost your rating. You can study all aspects of the game at length without damaging your bank account.

In my next blog, I will update you on the games and how I do in the tournaments. 

**Amici Sumus**


> [Subscribe to receive exclusive chess tips, updates, and strategies directly in your inbox](https://follow.it/senior-chess-improver?leanpub) 

> [Follow me on Mastodon for chess insights and more.](https://mastodon.online/invite/mWSpfQP8)

