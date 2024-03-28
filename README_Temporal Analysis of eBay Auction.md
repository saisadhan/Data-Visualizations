# Welcome to the Temporal Analysis of eBay Auction Read Me

[Explore the Visualizations on Tableau Public](https://public.tableau.com/views/TemporalAnalysisofeBayAuction/Sheet13?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link)

## Overview

Welcome to my eBay Auction Data Visualization repository! Here, I unveil captivating insights derived from meticulous analysis of the eBay Auction dataset using Tableau. My focus lies on unraveling the mysteries of online auction dynamics, with a spotlight on the intriguing phenomenon of auction sniping.

## Understanding eBay Auction

The eBay Auction dataset serves as a treasure trove of online auction dynamics, encompassing vital facets such as bidding behavior, auction durations, item categories, and closing prices.

### What is Auction Sniping?

Auction sniping, a common tactic in online auctions, involves placing bids moments before an auction's conclusion to outmaneuver competitors. This strategic maneuver aims to secure winning bids while minimizing the opportunity for counter-bids.

## Dataset Description

Contained within the `eBayAuction.xlsx` file are essential fields crucial for unraveling auction dynamics:

- **auctionid:** Unique identifier of an auction.
- **bid:** Proxy bid placed by a bidder.
- **bidtime:** Time in days since the start of the auction when the bid was placed.
- **bidder:** eBay username of the bidder.
- **bidderrate:** eBay feedback rating of the bidder.
- **openbid:** Opening bid set by the seller.
- **price:** Closing price of the auctioned item (second highest bid + increment).
- **item:** Auction item (e.g., Cartier wristwatch, Xbox game console).
- **auction_type:** Duration of the auction (3-day, 5-day, or 7-day).

## Insights Derived

My visualizations offer profound insights into auction dynamics and factors influencing closing prices:

1. **Overview Sheet Creation:** I kick-started my analysis by crafting an overview sheet, meticulously examining bid distributions over time to detect potential instances of auction sniping.

2. **Category-Specific Analysis:** Delving deeper into specific auction categories, I unveil how sniping behaviors vary across different item types, uncovering unique patterns within each category.

3. **Reference Line Implementation:** Enhancing clarity, I incorporated reference lines to pinpoint the onset of sniping behavior, aiding in the identification of critical auction moments.

4. **Impact on Closing Prices:** Exploring the interplay between bid timing and final prices, I shed light on the influence of sniping behavior on closing prices.
