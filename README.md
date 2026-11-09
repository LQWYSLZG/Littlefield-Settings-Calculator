# Littlefield Settings Calculator

A one-page calculator for the Littlefield Technologies lead-time game (268-day horizon, three pricing contracts, 3 stuffers / 1 tester / 1 tuner at Day 0).

Enter the average orders per day from the Day 0–50 data. The page gives:

1. Machines to buy at each station (keeps each station at or below about two-thirds utilization)
2. When to switch to the $1,250 / 0.5-day contract
3. Reorder point and order quantity (EOQ with interest as the holding cost; reorder point covers the 4-day delivery plus safety stock)
4. The final kit order to place before Day 218

The rules come from a queueing analysis and a discrete-event simulation of the factory. They are a strong starting point, not a guarantee: check lead times, utilization and kit stock during the game.

Open `index.html` in a browser, or view it on GitHub Pages.
