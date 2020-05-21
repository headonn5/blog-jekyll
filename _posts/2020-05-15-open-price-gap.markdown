---
layout: post
title:  "Opening Price Gap Theory"
date:   2020-05-15 11:17:57 +0530
categories: Stock Trading
author: Nishant Paul
---

In this post, we are going to discuss about the Open Price Gap trading strategy. This is very useful in scenarios when the stock price opens at a gap from the previous day's closing price, even when there is no news in the market that should have affected the price of the stock. But first things first. Let's discuss about how the opening price of the stock is decided during each trading day.


#### How the stock's open price is decided?

During the pre-market auction, buyers and sellers send their bids to the exchange for the stock. Then Securities Exchange try to match as many bids as possible against the sellers.

#### Example: 

<br/>
<img src="{{site.baseurl}}/assets/img/bid_example.png"/>

<br/>Exchange would try to match buyers and sellers, and come up with a common price that matches as many buyers and sellers bids as possible.

A matches with Y  
B matches with X  
C or D both can match with Z

To enable the maximum possible matches, the exchange decides the price to be $12. So, B, C, and D matches with X(100 shares), Y(100 shares), Z (100 shares) or B, C, D -> X (100 shares), Z (200 shares).

#### Why the opening price of a stock is higher/lower than its closing price on the previous day?

During the pre-market auction, when the opening price of the stock is decided, the opening price is decided by matching the maximum possible bids.

#### What is OPG (Opening Price Gap) Theory?

It says that if the stock opened at a price that created a gap from the previous day's close price of the stock, then current day's stock price should cover the gap at least up to the previous day's close price.

<img src="{{site.baseurl}}/assets/img/opg.png" width="100%"/>

**Note:**
This theory is valid only if during the pre-market auction, there was an imbalance in the number of bids from the buyers vs the number of bids from the sellers. In that case, the opening price would be skewed (bias or inclided) towards majority party's bid . This suggests that the stock is overvalued/undervalued and it would move in the direction of closing the gap. 

This theory is not valid if the stock's open price is influenced by any news related to the company.

#### Example:

Previous day close price is ₹10

<img src="{{site.baseurl}}/assets/img/opg_example.png"/>

Stock will open at ₹16.

In the above example, the bidder who had the highest number of stocks in the limited number of bids is chosen and its price marks the stocks open price. This was also possible because there was demand of the stocks on the market price. But nobody knew that somebody is selling the stock at a bid that is overvalued for the stock.
