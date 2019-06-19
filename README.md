# Donidson

Ideas:
- Don't add huge outliers to scan once decent averages have been established. (like 200% of average cost).
- If it is possible to store list of sellers/price/time_left: 
  - Check time since last scan, and if it is < the time_left was, we know it sold, and can get statistics on what actually sold
  - Don't add item as "new scan" if it is the same item as an old scan. Don't want one person to throw off the results.
