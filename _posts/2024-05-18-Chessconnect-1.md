---
layout: post
title: "The Chessnut eBoard and Chessconnect"
description: "What is Chessconnect and why should you use it?"
image: '/images/45.jpg'
date: 2024-05-18
tags: [tools, technology, chessconnect]
featured: false
---

# Introduction

Time flies! Before diving into today's topic, I want to let you know that I've updated the Blog page. Besides fixing some bugs, I've implemented a contact form. Questions, contributions, feedback - you've come to the right place [here](https://chess.myvortexcloud.com/contact/).

In addition to participating in intense tournaments, I recently explored a fantastic new tool - Chessconnect.

## What is Chessconnect?

Jörn Gehring, the developer of Chessconnect, had a dream: an easy way to connect his Chessnut chessboard with Lichess without connection drops. So, he developed a browser plugin that expanded into a powerful tool with many great features.

# Chessconnect - The Details

As the name suggests, Chessconnect connects smart chessboards from various brands to chess.com or lichess.org.

Chessconnect is a Chrome web extension that allows owners of smart chessboards to connect their boards to either chess.com or lichess.org. It also works seamlessly with Microsoft Edge, which I use all the time.

## Main Features

- Works in the browser, eliminating OS dependencies
- Integrates seamlessly with chess.com and lichess.org
- Supports chess boards from many different manufacturers
- Compatible with both USB and Bluetooth connections
- Reduces issues with cheat detection
- Enables games against bots, human opponents, and live tournaments
- Offers an optional delay to reduce the risk of mouse/board slips
- Provides optional sound or move announcements as speech
- Displays moves and time on the DGT3000 chess clock
- Non-commercial and free to use

Bottom line, Chessconnect delivers features I wish the Chessnut app had, such as latency options and simplified access, regardless of the device I use.

Chessnut Air and Pro both have an internal battery and report their charging status to Chessconnect. The "Connect" button turns red when the remaining charge is less than 33%.

Additionally, Chessconnect allows the board to be rotated by 180°, enabling you to place the black pieces on ranks 1 and 2 and the white pieces on ranks 7 and 8. This is especially useful for the Chessnut Pro, which has no visible coordinates.

## Connection Method

Your chess board can be connected to your computer or mobile device via Bluetooth LE or USB. However, different chess boards use different variants of USB. The connection method must be set before connecting to your board, with the default method being Bluetooth.

If you want to play on lichess.org, Chessconnect needs your username and a so-called “API token.” An API token is a secret string of characters that Chessconnect can use to make moves on your behalf on the Lichess website. To create such a token, go to lichess.org or follow this [link](https://lichess.org/account/oauth/token). You can select which permissions to assign to an API token. Chessconnect only needs the “board API” or “board:play” permission. Everything else can be denied.

Please make sure to enter your username on lichess.org exactly as it is. Otherwise, Chessconnect will not be able to determine which color your pieces have in your games.

You can enter up to three different usernames and corresponding API tokens. The active profile can be chosen by a radio button. If you change your user profile during a game and things do not work right away, try reconnecting to the board.

When you start Lichess, you should see the connect button at the upper right corner:

<div style="text-align: center;">
<img src="{{site.baseurl}}/images/chessconnect1.png" alt="image" width="100%">
</div>

<br>

If you press the new button, the pair function pops up on the left side. After pairing, the connect button changes to green. And that’s it.

You are ready to go. Connect turns red if your board power is down to 33%.

<div style="text-align: center;">
<img src="{{site.baseurl}}/images/chessconnect2.png" alt="image" width="80%">
</div>

Jörn's webpage is [here](https://chessconnect.de/). His preference is tea, so I encourage you to buy him a pot of tea for this absolutely fantastic app plugin.

The chess YouTuber **Adventures of a Chess Noob** has done a video and interview with Jörn:

<iframe width="560" height="315" src="https://www.youtube.com/embed/GpZ2mlVI4Dg?si=6VZmvQ6cPaec42kX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<br>

He also gave an update regarding version 3 of Chessconnect:

<iframe width="560" height="315" src="https://www.youtube.com/embed/7QXEV0ks8NY?si=pWHEyLLPiZvI9t09" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<br>

Chessconnect is now the one and only method I use to connect with Lichess. Bravo Jörn!

<br>
<br>
**Amici Sumus**

See you next week. If you enjoy my insights, consider supporting me with a virtual coffee! ☕️
Or a beer? Either way 😎 - Your support keeps me fueled to continue sharing valuable content.

Click the coffee cup below and subscribe:

> [Please subscribe](https://follow.it/senior-chess-improver?leanpub)
