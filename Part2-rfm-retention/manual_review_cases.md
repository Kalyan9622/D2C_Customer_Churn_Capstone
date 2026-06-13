# Manual Review Cases

This document outlines 10 edge-case customers where the automated RFM segment assignment presents a conflict or requires business judgment.

### 1. Customer: CUST00001
- **Features:** Recency: 32 days | Frequency: 6 | Monetary: 2490 INR | Ticket Count: 0 | Last Visit: 4 days ago
- **Conflict:** Just missed the "Champions" recency cutoff ($\le$ 30 days) but has incredibly high frequency and recent web engagement.
- **Recommended Action:** Override to "Champions". The recent web visit indicates they are actively browsing. Send an exclusive non-discount preview of an upcoming product to trigger the 7th purchase.

### 2. Customer: CUST00002
- **Features:** Recency: 5 days | Frequency: 3 | Monetary: 1713 INR | Avg Discount: 35% | Ticket Count: 0
- **Conflict:** Qualifies as both a "Champion" (R $\le$ 30, F $\ge$ 3, M $>$ 1500) and "Discount-Sensitive" (Avg Discount $>$ 30%).
- **Recommended Action:** Classify as "Discount-Sensitive". High spend driven entirely by heavy discounting hurts margins. Only target this user during end-of-season sales rather than offering premium loyalty perks.

### 3. Customer: CUST00003
- **Features:** Recency: 171 days | Frequency: 2 | Monetary: 649 INR | Ticket Count: 3
- **Conflict:** Technically a "Dormant Customer" (R $>$ 120), but the 3 support tickets indicate significant historical friction that likely caused the dormancy.
- **Recommended Action:** Do not attempt standard win-back. Before writing them off, have Customer Support verify if the past tickets were properly resolved. If not, a personal apology email might reactivate them better than an automated campaign.

### 4. Customer: CUST00004
- **Features:** Recency: 131 days | Frequency: 1 | Monetary: 1604 INR | Ticket Count: 0
- **Conflict:** "Dormant Customer" based on recency, but their single purchase was very high value.
- **Recommended Action:** Treat as a high-value re-acquisition target. Send an aggressive one-time "Welcome Back" bundle discount to see if this big spender can be brought back into the fold.

### 5. Customer: CUST00005
- **Features:** Recency: 38 days | Frequency: 5 | Monetary: 3290 INR | Avg Rating: 1.5 | Ticket Count: 2
- **Conflict:** Massive spender ("Loyal" based on RF), but terrible order ratings (1.5) and multiple tickets flag them as "High-Value but Unhappy".
- **Recommended Action:** High-priority manual intervention. Do not send automated marketing. A Customer Success Manager should reach out via phone/email to resolve the systemic issues causing low ratings despite high spend.

### 6. Customer: CUST00006
- **Features:** Recency: 51 days | Frequency: 5 | Monetary: 3727 INR | Return Rate: 16% (1 return)
- **Conflict:** "Loyal Customer" based on RFM, but recently returned a Baby Care item.
- **Recommended Action:** Proceed with normal upsell, but suppress baby care products from their next few marketing emails in case the return was due to sizing or product dissatisfaction.

### 7. Customer: CUST00010
- **Features:** Recency: 22 days | Frequency: 1 | Monetary: 626 INR | Last Visit: 22 days ago
- **Conflict:** "Low-Engagement Customer" (Visit $>$ 20, F=1), but they purchased quite recently. It means they bought and never returned to the site.
- **Recommended Action:** Send a post-purchase educational onboarding email (e.g., "How to get the most out of your product") rather than immediately offering a discount.

### 8. Customer: CUST00015
- **Features:** Recency: 85 days | Frequency: 4 | Monetary: 1950 INR | Ticket Count: 0
- **Conflict:** High historical loyalty, but now falling into "At-Risk" territory (Recency 60-120 days).
- **Recommended Action:** Priority win-back. Because their frequency was historically high, 85 days indicates an abnormal break in their purchasing pattern. Trigger a "Free Shipping" offer immediately.

### 9. Customer: CUST00021
- **Features:** Recency: 5 days | Frequency: 10 | Monetary: 1400 INR | Ticket Count: 0
- **Conflict:** Incredible frequency (10 orders) but strictly low-value items, keeping them under the "Champion" monetary threshold of 1500 INR.
- **Recommended Action:** Override to "Loyal Customers". Their extreme habituation is valuable. Promote bulk-buy or subscription options to raise their average order value (AOV).

### 10. Customer: CUST00030
- **Features:** Recency: 110 days | Frequency: 1 | Monetary: 249 INR | Last Visit: 2 days ago
- **Conflict:** "At-Risk/Low-Engagement" based on order history, but they visited the site just 2 days ago.
- **Recommended Action:** They are currently browsing! Do not wait. Intercept their active session window with a time-sensitive flash discount (e.g., 10% off for the next 24 hours) to convert the browsing intent into their second purchase.
