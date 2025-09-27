# Test Scenarios for ProfitLens GPT

## Test 1: Basic Product
**Input**:
- "I want to sell a water bottle for $25"
- Cost: $8
- Category: Sports & Outdoors
- Weight: 1 lb

**Expected Output**:
- Referral Fee: $3.75 (15%)
- FBA Fee: $4.08
- Storage: ~$0.03
- Net Profit: $13.14
- Margin: 52.6%
- ROI: 164.3%
- Verdict: HIGHLY PROFITABLE

---

## Test 2: Low Price Product
**Input**:
- "Can you analyze a $9.99 notebook?"
- Cost: $3
- Category: Office Products
- Weight: 0.5 lb

**Expected Output**:
- Should calculate low/negative margins
- Verdict: NOT PROFITABLE
- Should suggest higher price point

---

## Test 3: Heavy Item
**Input**:
- "Kettlebell set for $79.99"
- Cost: $30
- Category: Sports & Outdoors
- Weight: 35 lbs

**Expected Output**:
- Should identify as oversize
- Calculate higher FBA fees
- Show impact of weight on profitability

---

## Test 4: Special Category (Jewelry)
**Input**:
- "Silver necklace at $45"
- Cost: $12
- Category: Jewelry
- Weight: 0.1 lb

**Expected Output**:
- Referral Fee: $9.00 (20% - special rate!)
- Should note higher referral fee
- Still show good margins despite fee

---

## Test 5: Grocery Under $15
**Input**:
- "Protein bars for $13.99"
- Cost: $5
- Category: Grocery
- Weight: 0.8 lb

**Expected Output**:
- Referral Fee: $2.10 (15% because under $15)
- Should explain the special rule
- Suggest pricing above $15 for 8% fee

---

## Conversation Test Points:

1. **Missing Information**:
   - User provides incomplete data
   - GPT should ask for missing details politely

2. **Follow-up Questions**:
   - After analysis, user asks "what if I sell for $30?"
   - GPT should recalculate with new price

3. **Educational Moments**:
   - GPT should provide tips based on results
   - Explain why certain products work/don't work

4. **Multiple Products**:
   - User wants to compare 2-3 products
   - GPT should analyze each and compare

5. **Beginner Questions**:
   - "What's a referral fee?"
   - GPT should explain while calculating