# Smart India Hackathon Workshop
# Date: 24-11-2026
## Reference Number: 26009780
## Name: Ashika D

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
KrishiConnect: Direct Farmer-to-Consumer Digital Agri-Marketplace

1.Detailed Explanation:

Mobile and web platform connecting farmers/FPOs directly to household consumers and bulk buyers.
Farmers list produce quantity, harvest date, expected price, and pickup location.
Buyers order fresh produce directly from nearby farms.
Integrates local small truck operators for direct farm-to-door transportation.
Algorithms predict crop demand to help farmers plan future harvests.

2.Addressing the Problem:

Eliminates middlemen, brokers, and mandi agents.
Raises farmer income while cutting retail purchase prices.

3.Innovation and Uniqueness:

Shared Local Logistics: Pools existing village pickup trucks using route optimization to lower transport costs.
Demand-Based Harvesting: Guides farmers to harvest based on actual market orders.
Voice-Based Regional UI: Simple voice input allows farmers to list produce in local languages.

## Technical Approach
1.Technologies to be used:

Frontend: React Native (Mobile), React.js (Web Dashboard).
Backend: Node.js, Express.js.
Database: PostgreSQL with PostGIS for location tracking.
Algorithms: Python scripts using Dijkstra’s algorithm for routes and ARIMA for demand forecasting.
Integrations: Razorpay/UPI for payments, Google Maps API for route tracking.

2.Methodology and Process for Implementation:

Step 1 (Listing): Farmers enter produce details via mobile app or voice input.
Step 2 (Ordering): Buyers place orders; system clusters nearby requests.
Step 3 (Logistics): System batches orders, calculates the shortest pickup route, and alerts local drivers.
Step 4 (Delivery & Payment): Drivers deliver goods; funds transfer instantly to the farmer upon OTP verification.
## Feasibility and Viability
1.Analysis of the Feasibility of the Idea:
Technical: Uses standard web, mobile, and mapping technologies.
Operational: Partners with existing FPOs and local transport operators without heavy infrastructure investment.

2.Potential Challenges and Risks:

Limited internet access in remote villages.
Resistance from traditional farmers to digital payments.
Risk of perishable goods spoiling during delays.

3.Strategies for Overcoming These Challenges:

Offline Support: Enables offline listings that auto-sync when network returns.
FPO Volunteers: Deploys local coordinators to help farmers adapt to the app.
Escrow & Timed Deliveries: Secures payments via escrow and schedules early morning delivery slots.
## Impact and Benefits
1.Potential Impact on the Target Audience:
Farmers: 15–20% higher profits by removing agent commissions.
Consumers: 10–15% cheaper, fresher produce.
Transporters: Steady income for local pickup drivers.

2.Benefits of the Solution:

Economic: Increases rural income and minimizes crop waste.
Social: Connects small farmers directly to digital finance.
Environmental: Lowers vehicle emissions through shared, optimized delivery routes.


## Research and References
1.Agmarknet: Data on daily mandi arrival rates and wholesale produce prices.
2.NITI Aayog Agri-Reports: Guidelines on direct farm marketing and supply chain efficiency.
3.ICAR Post-Harvest Loss Data: Statistics on transit spoilage in Indian agriculture.
4.Google Maps API Docs: Route matrix and optimization technical reference.
