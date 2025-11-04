# Casino Promotion Dashboard  

## Overview  
This project presents a **Promotion Analytics Dashboard** built using mock casino data.  
The goal is to analyze the performance of promotional campaigns and visualize player engagement, prize redemption, and reinvestment efficiency.  

It simulates a real-world scenario in the casino & e-gaming industry, where data-driven insights help optimize marketing promotions and player reinvestment strategies.  

---

## Objectives  
The dashboard is designed to help management and analysts:  
- Evaluate **promotion performance** 
- Measure **reinvestment efficiency** from prizes.  
- Understand **player engagement by tier**.  
- Identify **cross-promotion opportunities**.  
- Highlight **top-performing players**

---

## Key Dashboard Components  
**1. PROMO REDEMPTION DASHBOARD**

**Table 1: Promotion Detail**

Purpose: Show core promotion metrics—especially Reinvestment Rate (RR)—to track outcomes and flag under-performing campaigns for adjustment.
Includes:
- Number of participants
- Player turnover
- Win/Loss
- Theo Win
- Points Earned
- Prizes issued
- Redeemed value
- Reinvestment rate (= Redeemed Value / Theo Win)  

**Chart 2: Unique Headcount by Campaign & Membership Tier**

Purpose: Reveal tier engagement and prize-claim patterns so marketers can confirm targeting and adjust mix if needed.
- Stacked bar chart visualizing number of players claiming prizes by tier  

**Table 3: Top 10 Players**

Purpose: Identify high-value players and the promotions invested in them to enable tailored offers.
- Lists top 10 players by turnover
- Includes their turnover, win/ loss, prize issued, redeemed value and reinvestment rate

**Chart 4: Prizes Issued By Tier**

Purpose: Highlight which tiers are most active in claiming prizes.
- Shows number of players who redeemed prizes, segmented by tier

**2. OUTLIERS & CROSSOVER PROMOTIONS**

**Chart 5: Player Scatter Plot**

Purpose: Compare each player’s actual Win/Loss against Theo Win to spot trends and outliers (big winners/losers) and inform targeted promotions.
- Scatter plot: Player Win/Loss vs. Theoretical Win (Theo Win)  
- Segment: Winning player (actual WL > expected loss) and Losing Player (actual WL < expected loss)


**Chart 6: Crossover Promotion Analysis**

Purpose: Understand player overlap across campaigns to evaluate cross-promotion effectiveness and identify combinations to bundle or review.
- Matrix visualization showing % of players joining multiple promotions  

---

## Insights Highlighted  
- Which promotions attract **high-value players**.  
- Relationship between **rewards and reinvestment behavior**.  
- **Tier-level engagement trends** and prize redemption patterns.  
- Overlaps between promotions → potential **bundling or segmentation opportunities**.  
