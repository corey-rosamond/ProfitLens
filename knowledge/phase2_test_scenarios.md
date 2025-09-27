# Phase 2 Test Scenarios

## Test 1: High Opportunity Product
**Input**:
- Product: Resistance Bands Set
- Price: $29.99
- Cost: $8.00
- Category: Sports & Outdoors
- Weight: 1.2 lbs
- BSR: 2,500
- Top competitor reviews: 350
- Number of sellers: 45

**Expected Analysis**:
- **Profit**: ~$14 net, 47% margin, 175% ROI
- **Demand**: 250-500 units/month (moderate-good)
- **Competition**: LOW (< 50 sellers, < 500 reviews)
- **Opportunity Score**: 7-8/10
- **Verdict**: STRONG BUY

**Key Points to Verify**:
- BSR converts to correct sales range
- Competition assessed as LOW
- High opportunity score
- Positive recommendation

---

## Test 2: Saturated Market Product
**Input**:
- Product: Phone Case
- Price: $12.99
- Cost: $3.50
- Category: Cell Phone Accessories
- Weight: 0.2 lbs
- BSR: 15,000
- Top competitor reviews: 5,000+
- Number of sellers: 500+

**Expected Analysis**:
- **Profit**: ~$5 net, 38% margin (good)
- **Demand**: 50-100 units/month (low)
- **Competition**: HIGH (many sellers, dominant players)
- **Opportunity Score**: 2-3/10
- **Verdict**: NOT RECOMMENDED

**Key Points to Verify**:
- Despite good margins, competition kills opportunity
- Low BSR sales estimate
- Warns about market saturation
- Suggests avoiding

---

## Test 3: Medium Competition Product
**Input**:
- Product: Bamboo Cutting Board
- Price: $34.99
- Cost: $12.00
- Category: Home & Kitchen
- Weight: 3 lbs
- BSR: 8,000
- Top competitor reviews: 800
- Number of sellers: 120

**Expected Analysis**:
- **Profit**: ~$13 net, 37% margin, 108% ROI
- **Demand**: 150-300 units/month
- **Competition**: MEDIUM (moderate sellers/reviews)
- **Opportunity Score**: 5-6/10
- **Verdict**: GOOD OPPORTUNITY with differentiation

**Key Points to Verify**:
- Balanced assessment
- Suggests differentiation strategy
- Moderate opportunity score
- Conditional recommendation

---

## Test 4: Seasonal Product (Q4)
**Input**:
- Product: Christmas Ornament Set
- Price: $24.99
- Cost: $6.00
- Category: Home & Kitchen
- Weight: 0.8 lbs
- BSR: 3,000 (in November)
- Top competitor reviews: 400
- Number of sellers: 35
- Note: "It's November"

**Expected Analysis**:
- **Profit**: Good margins
- **Demand**: 600-1000 units/month (Q4 boost)
- **Competition**: LOW
- **Seasonal Warning**: High risk after December
- **Verdict**: PROCEED CAUTIOUSLY - seasonal

**Key Points to Verify**:
- Recognizes seasonal nature
- Adjusts sales for Q4
- Warns about post-season risk
- Suggests limited investment

---

## Test 5: High-Ticket Product
**Input**:
- Product: Professional Yoga Mat
- Price: $89.99
- Cost: $28.00
- Category: Sports & Outdoors
- Weight: 5 lbs
- BSR: 12,000
- Top competitor reviews: 250
- Number of sellers: 25

**Expected Analysis**:
- **Profit**: ~$38 net, 42% margin, 135% ROI
- **Demand**: 60-120 units/month (lower but high ticket)
- **Competition**: LOW
- **Revenue Potential**: $5,400-10,800/month
- **Opportunity Score**: 7/10
- **Verdict**: GOOD OPPORTUNITY

**Key Points to Verify**:
- Recognizes high-ticket dynamics
- Lower volume but high revenue
- Calculates monthly revenue potential
- Notes higher investment requirement

---

## Test 6: Progressive Information Gathering
**Scenario**: User provides information in stages

**Stage 1**:
User: "Analyze this water bottle for $25"
GPT: Asks for cost, weight, category

**Stage 2**:
User: "Cost $7, weighs 1 lb, Sports category"
GPT: Provides basic profitability, then asks for BSR and competition

**Stage 3**:
User: "BSR is 4,000, top listing has 600 reviews"
GPT: Provides complete analysis with opportunity score

**Verify**:
- Doesn't overwhelm with all questions
- Provides value at each stage
- Builds complete picture progressively

---

## Edge Cases to Test

### Edge 1: No BSR Provided
- Should still calculate profitability
- Mention that demand analysis needs BSR
- Provide partial recommendation

### Edge 2: New Product (No BSR)
- Calculate profitability
- Explain BSR absence normal for new products
- Focus on competition assessment

### Edge 3: Conflicting Signals
- High profit but high competition
- Low profit but low competition
- Should provide balanced assessment

### Edge 4: Category Confusion
- User unsure of category
- GPT should explain impact
- Suggest likely category based on product

### Edge 5: Experience Level Impact
- Beginner with high competition product
- Should strongly warn
- Suggest easier alternatives

---

## Conversation Quality Checks

### Check 1: Educational Value
Every response should include at least one learning point about:
- BSR meaning
- Competition impact
- Margin importance
- Market dynamics

### Check 2: Progressive Complexity
- Start simple
- Add complexity as needed
- Don't overwhelm beginners
- Provide depth for experienced

### Check 3: Action Orientation
Every analysis should end with:
- Clear next steps
- Specific recommendations
- Risk mitigation if needed
- Alternative options

### Check 4: Accuracy
- Fee calculations match Phase 1
- BSR conversions align with tables
- Competition assessment consistent
- Opportunity scores logical

---

## Success Criteria

✅ **Phase 2 Complete When**:
1. Can estimate sales from BSR accurately
2. Assesses competition correctly
3. Provides opportunity scores
4. Gives strategic recommendations
5. Handles progressive information gathering
6. Maintains educational approach
7. All test scenarios pass