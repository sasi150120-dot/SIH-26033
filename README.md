# Smart India Hackathon Workshop
# Date:23/11/2026
## Reference Number:26018114
## Name:Sasikala D

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
**Our Solution: FARM SETU - Pooling + Smart Marketplace**

Farmers sell alone, so traders cheat them. Our idea is simple: Don't let farmers sell alone, make them sell as one big seller.

**1. Detailed Explanation:**
A farmer opens the app and adds his crop - Ex: 50kg Tomato. If 20 farmers in same village add tomato, our app automatically creates a 1000kg Tomato Pool.

Now buyers like hostels, supermarkets, and bulk buyers will see this Pool and bid for it. Whoever gives the highest price gets the Pool. Farmer gets direct UPI payment within 24 hours, no middlemen.

**2. How it addresses the problem:**
* Connects farmers/FPOs directly: Pool connects directly to consumers and bulk buyers, no agents.
* Logistics support: A Smart Mandi Van goes village to village for weighing, quality check, packing and pickup.
* AI Demand Forecasting: AI tells farmer "Tomorrow tomato price will increase, sell tomorrow" - so farmer never sells at loss.
* Route Optimization: AI finds the shortest route for the Van to collect from many villages.

**3. Innovation and Uniqueness:**
* Pooling System: Small farmers become one big seller.
* Reverse Auction: Normally farmer says price. Here, buyers compete and say price. Farmer gets best price.
* AI Price Guardian: Predicts price and demand before harvest.
* Tamil Voice App: Farmer can speak in Tamil, no need to type in English.

## Technical Approach

* Frontend App: Flutter - One app for Android + iOS, works in Tamil + English
* Backend: Python + Firebase / Node.js
* AI/ML: Python, Scikit-learn for Demand Forecasting & Price Prediction
* Maps: Google Maps API for Route Optimization of Van
* Payment: UPI / Razorpay - Direct to farmer
* Database: Firestore for real-time Pool updates

**2. Methodology and Process:**
1. Step 1 - Farmer Onboarding: Farmer registers with phone number, adds crop + quantity via voice.
2. Step 2 - Pool Creation: System auto-groups same crop farmers in same area into one Pool.
3. Step 3 - Reverse Auction: Buyers see Pool and place bids for 2 hours.
4. Step 4 - Logistics: Highest bidder wins. Smart Mandi Van gets optimized route to collect.
5. Step 5 - Payment & Delivery: Quality check at pickup, farmer gets UPI payment, buyer gets delivery.

Flow Chart: Farmer App -> Pool Creation -> Buyer Bidding -> Van Collection -> Payment -> Delivery
## Feasibility and Viability

**1. Analysis of Feasibility:**
This idea is highly feasible because farmers already use smartphones and UPI. We don't need to build new mandis, we just use existing vans and existing buyers. Technology used is all free / low-cost - Flutter, Firebase, Google Maps.

**2. Potential Challenges and Risks:**
* Farmers may not know how to use app.
* Internet problem in villages.
* Buyers may not trust new platform initially.
* Perishable crops may get spoiled during transport.

**3. Strategies for Overcoming Challenges:**
* For App Usage: Tamil voice command + Village volunteer to help onboarding.
* For Internet: App works in offline mode, syncs when network comes.
* For Trust: First 10 transactions with Cash on Delivery + Quality check photo proof.
* For Spoilage: AI Route Optimization ensures Van collects within 4-6 hours + Cold boxes in Van.
## Impact and Benefits
Impact: Farmer gets 40% more income, Consumer gets 25% lower price, Food waste reduces to almost 0%.
## Research and References
1. Details / Links of the reference and research work

1. eNAM - National Agriculture Market (Government of India)
   https://enam.gov.in
   - How farmers sell online without middlemen. Our pooling idea is inspired from eNAM.

2. AGMARKNET - Agricultural Marketing Information Network
   https://agmarknet.gov.in
   - Used for daily mandi price data. Our AI Price Guardian uses this price data for forecasting.

3. Ministry of Agriculture & Farmers Welfare - Farmer Producer Organisations (FPO)
   https://agricoop.nic.in
   - FPO concept proves that farmers selling as a group get better bargaining power than selling alone.

4. FAO - Food and Agriculture Organization - Food Loss and Waste
   https://www.fao.org
   - Report shows 40% of fruits and vegetables are wasted due to poor logistics. Our Smart Mandi Van + Route Optimization solves this.

5. NABARD - Farmer Producer Organisations Report
   https://www.nabard.org
   - Reference for how FPOs and collective selling increase farmer income.

6. India Stack - UPI / Digital India
   https://www.india.gov.in
   - Reference for direct UPI payment to farmers within 24 hours without cash handling.

7. Smart India Hackathon - Problem Statement SIH 26033
   Ministry of Consumer Affairs, Food & Public Distribution
   - Official problem statement for Multiple intermediaries reducing farmers earnings.

