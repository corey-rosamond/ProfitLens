# Final Test Scenarios for ProfitLens GPT

## 🎯 Core Functionality Tests

### Test 1: Basic FBA Fee Calculation
**Input**:
"Calculate FBA fees for a product: $29.99, 1.2 lbs, 10x8x2 inches, Home & Kitchen"

**Expected Output**:
- Exact referral fee (15% for Home & Kitchen)
- Correct FBA fulfillment fee for standard-size
- Monthly storage fee estimate
- Total fees with "Exact" confidence marker

### Test 2: Manual BSR Input
**Input**:
"The product has BSR 8,543 in Toys & Games"

**Expected Output**:
- Sales estimate with range (e.g., 150-250 units/month)
- Clear ±30% variance disclaimer
- Source: "Industry conversion tables"
- Note about factors affecting accuracy

### Test 3: Complete Product Analysis
**Input**:
"Analyze this product: Yoga mat, $24.99 selling price, 2 lbs, 24x6x6 inches, BSR 3,500 in Sports & Outdoors, my cost is $8"

**Expected Output**:
- Complete ProfitLens Analysis format
- All fee calculations
- Sales estimates (400-700 units based on BSR)
- Profit margins and ROI
- Competition assessment
- Seasonal patterns for Sports & Outdoors
- Opportunity score with breakdown
- Full transparency disclaimers

### Test 4: Missing BSR Handling
**Input**:
"What are the sales for a Home & Kitchen product?"

**Expected Output**:
- Explanation that BSR is needed
- Instructions on how to find BSR on Amazon
- Example format for providing BSR

### Test 5: Competition Query
**Input**:
"Is 200 sellers high competition?"

**Expected Output**:
- Yes, typically high competition
- Reference to pattern-based guidelines
- Disclaimer about heuristic nature
- Factors that determine competition beyond seller count

## 📊 Transparency Tests

### Test 6: Data Source Query
**Input**:
"Where does your sales data come from?"

**Expected Output**:
- Clear explanation of industry conversion tables
- ±30% accuracy disclaimer
- Mention that no free real-time APIs exist
- Suggestion of paid tools for better accuracy

### Test 7: Accuracy Challenge
**Input**:
"Your sales estimate seems wrong"

**Expected Output**:
- Acknowledge ±30% variance
- Explain estimation methodology
- Suggest verifying with multiple sources
- Maintain transparency about limitations

## 🔄 Edge Cases

### Test 8: Invalid BSR
**Input**:
"BSR is 0 in Electronics"

**Expected Output**:
- Explain BSR starts at 1
- Ask for correct BSR
- Provide guidance on finding it

### Test 9: Unusual Category
**Input**:
"What's the referral fee for Industrial & Scientific?"

**Expected Output**:
- Provide exact fee (12% for most Industrial)
- Note any subcategory variations
- Source: Amazon 2024 fee schedule

### Test 10: Seasonal Product
**Input**:
"Halloween costume, BSR 50,000 in October"

**Expected Output**:
- Acknowledge extreme seasonality
- Warn about seasonal risk
- Provide adjusted estimates
- Strong disclaimer about seasonal variance

## 💰 Profitability Scenarios

### Test 11: Low Margin Product
**Input**:
"Product sells for $9.99, costs $5, weighs 8 oz, BSR 2,000 in Kitchen"

**Expected Output**:
- Show negative or very low profit
- Warn about viability
- Calculate exact fees showing the issue
- Suggest minimum price points

### Test 12: Oversized Product
**Input**:
"Furniture item: 50 lbs, 48x24x12 inches, $199 price"

**Expected Output**:
- Correct oversize FBA fees
- Higher storage costs
- Special handling fees if applicable
- Note about oversize tier

## 🎓 Educational Queries

### Test 13: Learning Request
**Input**:
"Explain how you calculate opportunity scores"

**Expected Output**:
- Reference to 5-factor weighted model
- Breakdown of each factor
- Explanation of weights
- Note that it's an analytical framework

### Test 14: Comparison Request
**Input**:
"Should I sell a product with BSR 5,000 or BSR 15,000?"

**Expected Output**:
- Explain trade-offs (volume vs competition)
- Need more context (category, profit margins)
- Educational response about BSR interpretation
- Avoid definitive answer without full data

## ✅ Validation Checks

### Test 15: Transparency Check
**Every response should include**:
- Data source attribution
- Confidence levels (🟢🟡🔴)
- Appropriate disclaimers
- No false precision

### Test 16: Initial Greeting
**Input**:
"Hello" or "Hi"

**Expected Output**:
- Welcome message
- List of capabilities
- Transparency commitment
- Invitation to analyze a product

## 🚫 Failure Modes

### Test 17: API Request
**Input**:
"Connect to Amazon API for real-time data"

**Expected Output**:
- Explain no free APIs available
- Mention paid options exist
- Reaffirm transparency approach
- Continue with estimates + disclaimers

### Test 18: Precision Demand
**Input**:
"I need exact sales numbers, not estimates"

**Expected Output**:
- Honest explanation of limitations
- Suggest paid tools (Jungle Scout, Helium 10)
- Explain why exact data costs money
- Offer to continue with transparent estimates

## 📈 Complex Scenarios

### Test 19: Multi-variant Analysis
**Input**:
"Compare 3 sizes of the same product: Small ($19.99, BSR 4,000), Medium ($24.99, BSR 2,000), Large ($29.99, BSR 8,000)"

**Expected Output**:
- Analysis for each variant
- Comparison table
- Recommendation based on profit/volume balance
- Note about managing multiple SKUs

### Test 20: International Marketplace
**Input**:
"What about selling in Amazon UK?"

**Expected Output**:
- Note that data is for US marketplace
- Different fee structures apply
- BSR scales differ by marketplace
- Suggest researching UK-specific data

## ✨ Success Criteria

Each test should demonstrate:
1. **Accuracy** - Correct calculations where exact data exists
2. **Transparency** - Clear source attribution and limitations
3. **Helpfulness** - Educational value even with limitations
4. **Consistency** - Same methodology across responses
5. **Honesty** - No false claims or hidden limitations

## 🎯 Final Integration Test

### Test 21: Real Product Example
**Input**:
"Analyze this real product: Stainless steel water bottle, 32 oz, selling for $27.99, weighs 1.1 lbs, 10x3x3 inches, BSR 12,847 in Sports & Outdoors, I can source for $7.50 including shipping to Amazon"

**Expected Full Analysis Should Include**:
- All FBA fees calculated correctly
- Sales estimate: 60-120 units/month
- Profit: ~$8-9 per unit after all fees
- Medium competition assessment
- Current seasonal factor for Sports & Outdoors
- Opportunity score with full breakdown
- Complete transparency disclosures
- Actionable recommendation

---

**Note**: These tests ensure ProfitLens provides valuable, honest analysis while maintaining complete transparency about data sources and limitations.