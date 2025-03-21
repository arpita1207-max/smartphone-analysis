#Smartphone Analysis
```
##Project Summary: Smartphone Price Analysis
This project explores how various features in a smartphone impact its price. By analyzing key specifications such as processor type, RAM, storage, camera quality, battery capacity, display type, and brand value, we aim to identify trends and patterns that influence smartphone pricing.

Through data analysis and visualization, this study helps in understanding which features contribute most to price variations, enabling consumers to make informed purchasing decisions and manufacturers to optimize pricing strategies. The insights gained can be valuable for market research, competitive analysis, and product positioning in the smartphone industry.
```
```
##Smartphone Price Analysis - Key Findings
### 1. Price Distribution & Outliers
Price is fairly right-skewed, indicating that higher-priced phones are fewer. Outliers are present.
Rating follows a moderately normal distribution (most ratings between 75 and 85) with no outliers.
Processor Speed has a bimodal distribution (between 2 & 3 GHz) with no outliers.
Fast Charging exhibits a multimodal distribution (some phones have fast charging of 140W+). Outliers are present.
Screen Size is fairly left-skewed (some phones <6" and some >7"). Outliers are present.
PPI, Primary Rear Camera, Primary Front Camera, and Battery Capacity show multimodal distributions with outliers present.
```
```
###2. Feature Distributions & Trends
56% of phones support 5G.
40% of phones have NFC.
16% of phones have an IR Blaster (mostly found in Chinese phones).
Snapdragon is the most common processor brand.
91.8% of phones have octa-core processors.
85.4% of phones support fast charging.
339 phones have 8GB RAM, 234 phones have 6GB RAM, and 217 phones have 4GB RAM.
523 phones have 128GB storage, and 193 phones have 64GB storage.
76.4% of phones have a fairly good PPI (>300 and ≤450), while 23.6% have a low PPI (<300).
63.9% of phones support extended memory.

Among phones with extended memory:
51.7% support up to 1024GB.
22.9% support up to 512GB.
20.5% support up to 256GB.

Camera distribution:
54.8% of phones have 4 cameras.
21.1% of phones have 3 cameras.
16.2% of phones have 5 cameras.
```

```
###3. Correlation Insights (Before & After Feature Engineering)
Rating's correlation with price increased from 0.2835 to 0.3087.
Processor Speed's correlation with price increased from 0.4740 to 0.4900.
Extended Memory (Up to) correlation changed from 0.0483 to -0.0585.
Other feature correlations remained largely unchanged.
```
```
### 4. Pricing Insights by Features
Phones with 5G → Median price above ₹30,000.
Phones with NFC → Median price above ₹40,000.
Phones with Bionic processors → Median price ₹80,000.
Phones with Apple processors → Median price ₹1,00,000.
Apple phones → Median price above ₹80,000.
iOS phones → Price range above ₹80,000.
No. of cores → Median price above ₹60,000.
8GB RAM → Median price above ₹40,000.
12GB & 16GB RAM → Median price above ₹60,000.
18GB RAM → Median price above ₹80,000.
Phones with 512GB storage → Prices between ₹1,00,000 and ₹1,25,000.
Phones with 1024GB storage → Prices between ₹1,50,000 and ₹1,75,000.
Phones with 256GB storage → Prices between ₹50,000 and ₹75,000.
Phones with fast charging → Prices above ₹20,000.
Phones with medium PPI → Median price above ₹20,000.
Phones with a 165Hz refresh rate → Median price ₹80,000.
Phones with a 240Hz refresh rate → Median price ₹1,20,000.
Phones with extended memory (up to) → Price range above ₹20,000.
```
```
This summary provides a detailed view of how different smartphone features impact price, along with key distribution patterns and trends. 
```
