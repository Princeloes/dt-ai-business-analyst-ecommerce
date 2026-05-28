# Task 1: Campaign Viability Analysis (GlowNest Skincare)

This document contains the complete unit economics, profitability analysis, scenario evaluations, and a voice note narration script for GlowNest.

---

## Brand Details (Base Inputs)
* **Product**: Premium Face Serum
* **Selling Price (SP)**: ₹800 per unit
* **Cost of Goods Sold (COGS)**: ₹280 per unit
* **Amazon Referral Fee**: 12% of SP
* **Monthly Ad Spend**: ₹3,00,000
* **Units Sold via Ads (Monthly)**: 1,500
* **Organic Units Sold (Monthly)**: 2,000
* **Fixed Costs (Monthly)**: ₹1,50,000

---

## Answers to Campaign Viability Questions

### Q1: Unit Economics
Calculate the gross margin, Amazon fee, ad cost per unit, and net margin per unit for ad-attributed sales.

* **Gross Margin per Unit**:
  $$\text{Gross Margin} = \text{Selling Price (SP)} - \text{COGS}$$
  $$\text{Gross Margin} = 800 - 280 = \text{₹520 per unit}$$
  *(Contribution margin ratio before platform fees is $520 / 800 = 65\%$.)*

* **Amazon Referral Fee per Unit**:
  $$\text{Amazon Fee} = \text{SP} \times 12\%$$
  $$\text{Amazon Fee} = 800 \times 0.12 = \text{₹96 per unit}$$

* **Ad Cost per Unit**:
  $$\text{Ad Cost per Unit} = \frac{\text{Total Ad Spend}}{\text{Units Sold via Ads}}$$
  $$\text{Ad Cost per Unit} = \frac{3,00,000}{1,500} = \text{₹200 per unit}$$

* **Net Margin per Unit (for Ad-Attributed Sales)**:
  $$\text{Net Margin (Ad)} = \text{Gross Margin} - \text{Amazon Fee} - \text{Ad Cost per Unit}$$
  $$\text{Net Margin (Ad)} = 520 - 96 - 200 = \text{₹224 per unit}$$
  *(Net margin ratio for ad-attributed sales is $224 / 800 = 28\%$.)*

---

### Q2: Monthly Profitability
What is GlowNest's monthly profit from Amazon (considering both organic and ad-attributed sales)? Assume organic sales have zero advertising cost.

* **Net Margin per Unit (for Organic Sales)**:
  Since organic sales carry zero advertising cost, the net margin per unit is higher:
  $$\text{Net Margin (Organic)} = \text{Gross Margin} - \text{Amazon Fee}$$
  $$\text{Net Margin (Organic)} = 520 - 96 = \text{₹424 per unit}$$

* **Total Monthly Profitability Calculation**:
  $$\text{Monthly Profit} = \left(\text{Net Margin (Ad)} \times \text{Ad Units}\right) + \left(\text{Net Margin (Organic)} \times \text{Organic Units}\right) - \text{Fixed Costs}$$
  $$\text{Monthly Profit} = \left(224 \times 1,500\right) + \left(424 \times 2,000\right) - 1,50,000$$
  $$\text{Monthly Profit} = 3,36,000 + 8,48,000 - 1,50,000$$
  $$\text{Monthly Profit} = 11,84,000 - 1,50,000 = \text{₹10,34,000}$$

GlowNest's monthly net profit from Amazon is **₹10,34,000** (a net profit margin of $10,34,000 / (3,500 \times 800) = 36.93\%$).

---

### Q3: ACOS and TACOS
Calculate GlowNest's current ACOS and TACOS. Are these healthy? Explain your reasoning.

* **ACOS (Advertising Cost of Sale)**:
  $$\text{Ad-Attributed Revenue} = \text{Ad Units} \times \text{SP} = 1,500 \times 800 = \text{₹12,00,000}$$
  $$\text{ACOS} = \frac{\text{Ad Spend}}{\text{Ad Revenue}} \times 100$$
  $$\text{ACOS} = \frac{3,00,000}{12,00,000} \times 100 = \mathbf{25.00\%}$$
  *(This corresponds to a campaign-level ROAS of 4.0.)*

* **TACOS (Total Advertising Cost of Sale)**:
  $$\text{Total Revenue} = \left(\text{Ad Units} + \text{Organic Units}\right) \times \text{SP} = 3,500 \times 800 = \text{₹28,00,000}$$
  $$\text{TACOS} = \frac{\text{Total Ad Spend}}{\text{Total Revenue}} \times 100$$
  $$\text{TACOS} = \frac{3,00,000}{28,00,000} \times 100 = \mathbf{10.71\%}$$

* **Health Assessment & Rationale**:
  * **ACOS of 25.00% is highly healthy**. The product's contribution margin before advertising is 53% (Net Margin Organic / SP = $424 / 800$). Because ACOS (25%) is significantly below the product margin (53%), the ad campaigns are directly profitable on their own, yielding a 28% net margin on every ad-attributed sale.
  * **TACOS of 10.71% is excellent**. In e-commerce, a TACOS between 10% and 15% is the sweet spot. It indicates that the ad spend is successfully driving rank and index position without locking the brand into a paid-ad treadmill. Over 57% of GlowNest's sales are organic ($2,000 / 3,500$), indicating strong brand equity.

---

### Q4: Break-Even Ad Spend
What is the maximum monthly ad spend GlowNest can afford before the Amazon business becomes unprofitable? What ACOS does this correspond to?

To find the break-even ad spend for the **overall Amazon business**, we solve for when $\text{Total Monthly Profit} = 0$, assuming sales volumes remain constant:
$$\text{Total Monthly Profit} = \left(\text{Total Units} \times \text{Net Margin before Ads}\right) - \text{Ad Spend} - \text{Fixed Costs} = 0$$
$$\left(3,500 \text{ units} \times 424\right) - \text{Ad Spend} - 1,50,000 = 0$$
$$14,84,000 - \text{Ad Spend} - 1,50,000 = 0$$
$$\text{Ad Spend} = 13,34,000$$

* **Maximum Break-Even Ad Spend**: **₹13,34,000/month**
* **Corresponding ACOS**:
  $$\text{ACOS} = \frac{\text{Ad Spend}}{\text{Ad-Attributed Revenue}} \times 100 = \frac{13,34,000}{12,00,000} \times 100 = \mathbf{111.17\%}$$

* **Interpretation Note**: 
  While spending ₹13.34L on ads means losing money on ad-attributed sales individually, the highly profitable organic sales (2,000 units generating ₹8,48,000 in net margin) and the ad-attributed sales' baseline margin of ₹6,36,000 (before ads) subsidize the ad deficit. 
  *If we consider only the ad campaign's individual break-even point, the maximum ad spend is **₹6,36,000** (Ad Units 1,500 × ₹424 margin before ads), which corresponds to a break-even ACOS of **53.00%**.*

---

### Q5: Scenario: Ad Efficiency Drops
GlowNest's ACOS worsens from the current level to 40%. Units sold via ads drop to 1,200. Organic stays the same at 2,000. What happens to monthly profitability? What would you recommend?

* **New Calculations**:
  * **New Ad Revenue**: $1,200 \times 800 = \text{₹9,60,000}$
  * **New Ad Spend (40% ACOS)**: $9,60,000 \times 0.40 = \text{₹3,84,000}$
  * **New Ad Cost per Unit**: $3,84,000 / 1,200 = \text{₹320 per unit}$
  * **New Net Margin per Unit (Ad)**: $520 - 96 - 320 = \text{₹104 per unit}$
  * **New Monthly Profit**:
    $$\text{Monthly Profit} = \left(104 \times 1,200\right) + \left(424 \times 2,000\right) - 1,50,000$$
    $$\text{Monthly Profit} = 1,24,800 + 8,48,000 - 1,50,000 = \mathbf{₹8,22,800}$$

* **Impact**:
  * Profit dropped from ₹10,34,000 to ₹8,22,800, a **drop of ₹2,11,200 (or 20.42%)**.
  * Even though ACOS worsened to 40%, ad-attributed sales are still profitable in absolute terms (generating ₹104 net margin per unit).

* **Recommendations**:
  1. **Audit Keyword Placements**: Identify where the ad leakage is happening. Look for high-spend, low-conversion keywords and add them as negative terms.
  2. **Bid Adjustments**: Shift budget from high CPC broad-match terms to exact-match search terms where CVR is higher.
  3. **Listing Optimization**: A drop in ad volume suggests either competitor price-cutting or listing decay. Audit listing images, customer QA, and reviews to restore the conversion rate.

---

### Q6: Scenario: Scaling Up
GlowNest wants to double ad spend to ₹6,00,000/month. They expect units via ads to increase to 2,500 (diminishing returns). Is this a good decision? Show the math and your reasoning.

* **New Calculations**:
  * **New Ad Revenue**: $2,500 \times 800 = \text{₹20,00,000}$
  * **New ACOS**: $\frac{6,00,000}{20,00,000} \times 100 = \mathbf{30.00\%}$
  * **New Ad Cost per Unit**: $6,00,000 / 2,500 = \text{₹240 per unit}$
  * **New Net Margin per Unit (Ad)**: $520 - 96 - 240 = \text{₹184 per unit}$
  * **New Monthly Profit**:
    $$\text{Monthly Profit} = \left(184 \times 2,500\right) + \left(424 \times 2,000\right) - 1,50,000$$
    $$\text{Monthly Profit} = 4,60,000 + 8,48,000 - 1,50,000 = \mathbf{₹11,58,000}$$

* **Comparison**:
  * **Original Profit**: ₹10,34,000
  * **Scaled Profit**: ₹11,58,000
  * **Net Profit Increase**: **+₹1,24,000 (or 11.99% increase)**
  * **Incremental ROI on Ad Spend**: 
    $$\frac{\text{Incremental Net Margin}}{\text{Incremental Ad Spend}} = \frac{(4,60,000 - 3,36,000)}{(6,00,000 - 3,00,000)} = \frac{1,24,000}{3,00,000} = 41.33\%$$

* **Decision & Reasoning**:
  * **Yes, this is a good decision**. 
  * Although ad efficiency drops (ACOS increases from 25% to 30%, and ROAS drops from 4.0 to 3.33) due to diminishing returns, the scaling effort generates an extra ₹1,24,000 in monthly net profit. 
  * Furthermore, the brand increases its market share by selling 1,000 more units. This higher sales velocity will likely improve organic keyword rankings over the next 90 days, potentially boosting organic sales beyond 2,000 units in the future.
  * *Constraint to watch*: Verify that GlowNest has the warehousing capacity, inventory runway, and working capital to support the extra 1,000 units per month.

---

## 3. Task 1 Voice Note Script (2-3 Minutes)

### Outline & Guidelines
* **Objective**: Explain the analysis, highlighting key findings, what surprised you, and how you would advise the founder.
* **Tone**: Professional, analytical, advisory.

### Script

* "Hi there, I’ve completed the viability analysis for GlowNest’s face serum, and I wanted to walk you through my findings and what they mean for the brand's growth strategy.
* First, looking at the unit economics, GlowNest has incredibly strong fundamentals. The serum sells for ₹800, and with a COGS of ₹280, it has a 65% gross margin. Even after Amazon's 12% referral fee, the brand keeps ₹424 on every organic unit sold. 
* Right now, they spend ₹3,00,000 on ads to generate 1,500 sales, which means their ad cost is ₹200 per unit. This translates to an ACOS of 25%—which is highly efficient. When we combine their ad sales and organic sales, their total monthly net profit is ₹10,34,000. That is a 37% net profit margin on the Amazon channel. That's a very healthy business.
* Now, looking at the scaling opportunities, what really surprised me is how resilient their model is to scaling friction. When we model doubling the ad spend to ₹6,00,000, we do hit diminishing returns—units sold via ads only grow by 66% to 2,500 units, pushing ACOS up to 30%. 
* In many e-commerce brands, a drop in ad efficiency is a cause for panic. But because GlowNest's margins are so fat, the math shows that doubling ad spend increases monthly profit by ₹1,24,000, bringing it to ₹11,58,000. My recommendation to the founder is to proceed with this scale-up. It's a 41% marginal return on ad spend, and it buys them valuable market share and sales velocity that will improve their organic rankings.
* On the flip side, if ad efficiency drops—say ACOS worsens to 40% and ad units drop to 1,200—the monthly profit falls to ₹8,22,800. This is a ₹2.1L drop, but the business remains highly profitable.
* Ultimately, my advice to GlowNest is that they are in a strong position. They should push the ad spend to ₹6L to capture category share, while closely monitoring their inventory pipeline to prevent out-of-stock issues that would kill the organic momentum they've built."
