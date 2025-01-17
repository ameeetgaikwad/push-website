---
slug: notify-decentralized-prediction-markets
title: 'Notify Decentralized Prediction Markets (DPM) with EPNS'
description: 'Notify Decentralized Prediction Markets (DPM) with EPNS'
authors: [push]
image: './cover-image.webp'
text: "The past week has seen a huge increase in the popularity and usage of prediction markets, particularly decentralized prediction markets. The reason is very obvious — The US Elections."
tags: [ Prediction Markets
,Blockchain
,Ethereum
,Notifications
,Blog
]
---
import { ImageText } from '@site/src/css/SharedStyling';

![Cover Image of Notify Decentralized Prediction Markets (DPM) with EPNS](./cover-image.webp)

<!--truncate-->

Photo by [Jen Theodore](https://unsplash.com/@jentheodore?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/oracle?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)

The past week has seen a huge increase in the popularity and usage of prediction markets, particularly decentralized prediction markets. The reason is very obvious — The US Elections. People turned to prediction markets trying to make a quick buck by predicting who will emerge victorious to get the keys to the White House. But decentralized prediction markets (DPM) aren’t just used to predict the next President of the US, but it aims to be a place to predict any event that could possibly happen in the real world. No matter what it is you want to predict — be it the next President, the weather for tomorrow, the prices of cryptos like Bitcoin, or even the price of oranges next week.

![Image of Notify Decentralized Prediction Markets (DPM) with EPNS](./image-1.webp)

🔥🔥🔥

In this article, we will discuss about prediction markets, its working, and how decentralized notifications can help bridge the gap between markets and its users!

### **Prediction Markets**

A Market can be any place where people come to buy and sell commodities. This can be either online (Stock Market, E-commerce stores, etc) or a physical store (Grocery, Supermarkets, etc). A prediction market is more or less the same thing but instead of buying and selling any commodity, you buy and sell predictions (or shares of that prediction, just like you buy shares of a company in the stock market.). These predictions could be anything. It is usually :

1.  **_Tied to some real-world event._**
2.  **_Something that has a finite and definite outcome._**
3.  **_Has considerably fewer possible outcomes, such as 2 or 3._**
4.  **_And also something isn’t very easy to predict (like what is the weather going to be like tomorrow) already but has high stakes._**

As [Augur](https://augur.net/ipfs/trading/), a DPM puts it, “ There are two types of shares in a prediction market: YES (long) shares and NO (short) shares. The ultimate value (payout) of each share depends on whether an event occurs or not. In a simple prediction market, each YES share pays out a dollar if the event in question occurs and pays out nothing if it does not occur. Each NO share pays out a dollar if the event does not occur and nothing if it does.”

Currently, most prediction markets are centralized and hence face the common problems faced by most centralized financial institutions today.

These are:

1.  **_They are closed, siloed, and highly regulated._**
2.  **_The risk of markets being shut down by regulators discourages participation._**
3.  **_Low betting caps, hence preventing high-confidence players from sufficiently and accurately expressing their conviction and moving the markets by trading at higher amounts._**
4.  **_They usually have high trading fees._**

DPMs like [Augur](https://twitter.com/AugurProject), [Omen](https://twitter.com/Omen_eth), [Gnosis](https://twitter.com/gnosisPM), [Stox](https://twitter.com/stx_coin), and [Polymarket](https://twitter.com/PolymarketHQ), built on top of Etherum have shown us that, it is absolutely possible to have Decentralized Prediction Markets but we have to caution ourselves that it is still a new experimental idea and the feasibility and risk associated is still high.

With the rise of hype associated with the recently concluded US Elections, DPMs have been riding the tide on the rise to their popularity. According to an article by CoinTelegraph, the [Matic](https://twitter.com/maticnetwork)\-powered decentralized prediction platform Polymarket saw significant trade, posting a new volume record of more than $10 million.

**YTRUMP** and **NTRUMP** tokens from the Augur- and Balancer-powered Catnip Exchange drove around $1.3 million in speculative action over the past 24 hours.

Augur also saw significant action, reporting $8.6 million in total election volume, and $4.75 million in open interest.

[Ethhub](https://twitter.com/ethhub_io) and [TheDailyGwei](https://t.co/PdcbhdHNgv?amp=1) founder [Anthony Sassano](https://twitter.com/sassal0x) noted the opportunity that the election provides for decentralized prediction platforms to attract users, [stating](https://thedailygwei.substack.com/p/predict-this-the-daily-gwei-110?token=eyJ1c2VyX2lkIjo5ODExMjIxLCJwb3N0X2lkIjoxNzQ0MjkzMiwiXyI6Ik9KZkhEIiwiaWF0IjoxNjA0NTMyMDA2LCJleHAiOjE2MDQ1MzU2MDYsImlzcyI6InB1Yi01Mjg5MyIsInN1YiI6InBvc3QtcmVhY3Rpb24ifQ.RX9Wbw0nyb7QqUsKRBy4tfWKdffQEzF-wIM59EmfhNk):

> It seems that prediction markets finally found their stride because there was a market for people to bet on that they actually cared about.

[Vitalik Buterin](https://twitter.com/VitalikButerin) also got into the discussion during the eve of election night to mention that DPMs have proven to be a much more accurate representation of the elections, by stating 3 hypotheses that he shared on Twitter (as seen below).

**The Need for Notifications in DPMs**
======================================

Betting on or buying shares of predictions sounds cool for the most part, but DPMs don’t currently have a method to let you know when new predictions are made open or when existing ones are closed.

With the help of EPNS, DPMs will be able to send notifications and allow their users to stay up to date on the recent happenings within the platform.

Some use cases are mentioned below but are not limited to them. They are :

**1\. When new Prediction pools are listed**
--------------------------------------------

_“Will Trump be re-elected for 2021?”, “Will Bitcoin cross $16k?”, “Will FC Barcelona beat Real Madrid in the next El Clasico?”._

As days pass if DPMs want to stay relevant they must list relevant prediction pools on their platform, and also let their users know about it! Prediction markets get more accurate as more people participate in it. By adding notifications to the picture, DPMs can ensure that interested people will stake their funds into the pools as well as users can stay updated on what are the possible predictions they can invest in!

**2\. When prediction markets fluctuate**
-----------------------------------------

Market outcomes and predictions can fluctuate as time passes as more data on the topic come to light. Often this leads to one side of the prediction being favored more and hence gets more costly.

Consider you take the case of dice and you are to predict the outcome when rolled would either be an odd or even number. This turns out to be a 50% probability, hence equalling the price of the shares, but later if it is revealed that the dice is 4sided, then the probability shifts as there is a shift of probability to 75/25 ratio, hence making one of the shares cost more!

Letting users know when the price changes drastically or when the market favoring changes, will allow them to make educated decisions on whether to sell, hold, or buy shares.

**3\. When the market closes**
------------------------------

Since prediction markets are tied to some real-world event or probable outcome, and within a definite time, markets will close a listing when the real-world event occurs and hence will result in users either gaining or losing based on the shares they have in hand.

With notifications, a participant in the prediction market can be notified when the market closes and also be aware of how much they have won or lost. This in turn also allows the participants in the market who won to claim their shares and withdraw money in a timely manner. In case there is any delay in the result of the outcome of the event, then this information can be passed on to the user as well.

**4\. General Predictions**
---------------------------

DPMs can help create network effects and also help you plan your actions accordingly. For example, if a DPM notifies you that there is an 80% chance that the price of ETH will cross $500 in the first week of December with the release of Ethereum 2.0, you would plan to stock up on some ETH before the price increase, hence creating scarcity and eventually increasing its price. Similarly, if you get notified that there is a 65% chance of there being a traffic jam at 8 am on Monday, then you would plan accordingly to get to work. Convenient, isn’t it?

**Conclusion**
==============

Looking at the above use cases one can deduce that notifications are crucial for every stage of a prediction lifecycle for a decentralized prediction market. DPMs are still quite early in the game, and sometimes the user participation levels are quite low because of the lack of stake or interest in existing predictions being listed on such platforms. One could hope these platforms to grow day by day and eventually beat their centralized counterparts into being more mainstream, and they already have proved to be more accurate. Another way to look at it is that “are DPMs too advanced an ambition or a concept too early for its time?” One can only wait and see where this goes.

EPNS is a decentralized notification service, where one can receive notifications in a decentralized way for the decentralized protocols they use. Often dubbed to be the “missing piece in Web3 and blockchain” EPNS lends its hand in utilities across a variety and multitude of decentralized platforms.

Predictions are looking awesome for EPNS to play a key role in decentralization.

_References:_

[_https://augur.net/blog/prediction-markets/_](https://augur.net/blog/prediction-markets/)[_https://cointelegraph.com/news/crypto-powered-prediction-market-flourish-during-us-presidential-election_](https://cointelegraph.com/news/crypto-powered-prediction-market-flourish-during-us-presidential-election)

Become part of our buzzing community! Join the conversation on one of our channels:  
[Twitter](https://twitter.com/epnsproject) | [Telegram](https://t.me/epnsproject)