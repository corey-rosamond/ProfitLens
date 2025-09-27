# ProfitLens - Amazon FBA Calculator GPT

> 🔍 **Instant FBA profitability analysis powered by AI** - Calculate fees, analyze margins, and maximize ROI through natural conversation.

## ✅ Phase 1 Complete!

### What's Working Now:
- 📊 Complete FBA fee calculations using 2024 rates
- 💰 Profit margin and ROI analysis
- 🎯 Clear profitability verdicts
- 📚 Educational tips with each calculation
- 🧮 GPT performs all calculations using knowledge files (no external APIs needed)

## Project Structure

```
ProfitLens/
├── config/
│   └── instructions.md    # GPT personality and calculation logic
├── knowledge/
│   ├── fba_fees.md        # 2024 Amazon fee structure
│   ├── calculation_examples.md  # Step-by-step examples
│   └── test_scenarios.md  # Test cases for validation
└── .ai/
    ├── PLAN.md            # Development phases
    └── ANALYSIS.md        # Architecture decisions
```

## 🚀 How to Deploy

1. **Create Custom GPT**:
   - Go to [chat.openai.com/gpts/editor](https://chat.openai.com/gpts/editor)
   - Click "Create a GPT"

2. **Configure GPT**:
   - Name: "ProfitLens - FBA Calculator"
   - Description: "Calculate Amazon FBA fees and profitability instantly"
   - Copy contents of `config/instructions.md` to Instructions

3. **Upload Knowledge Files**:
   - Upload `knowledge/fba_fees.md`
   - Upload `knowledge/calculation_examples.md`

4. **Test**:
   - Use scenarios from `knowledge/test_scenarios.md`
   - Verify calculations match examples

5. **Publish**:
   - Save and publish to GPT Store
   - Share link with users

## 💡 How It Works

The GPT uses its language model to:
1. Read fee structures from knowledge files
2. Perform calculations step-by-step
3. Show clear breakdowns
4. Provide actionable recommendations

**No external APIs or actions required!**

## 📊 Example Calculation

```
User: "Analyze a yoga mat selling for $35"
Cost: $12, Weight: 2 lbs, Category: Sports

GPT Response:
📊 PROFITABILITY ANALYSIS
━━━━━━━━━━━━━━━━━━
• Referral Fee (15%): $5.25
• FBA Fulfillment: $4.75
• Storage: $0.05
• Total Fees: $10.05

• Net Profit: $12.95
• Margin: 37.0%
• ROI: 107.9%

🎯 VERDICT: HIGHLY PROFITABLE ✅
```

## 🔄 Development Status

### ✅ Phase 1 (Complete)
- Basic fee calculator
- Profitability analysis
- Knowledge-based calculations

### 📅 Phase 2 (Next)
- BSR to sales estimates
- Competition assessment
- Market analysis

### 🔮 Phase 3 (Future)
- Multi-step conversations
- Educational content
- User level adaptation

## 🧪 Testing

Run through scenarios in `knowledge/test_scenarios.md`:
- Basic products (✅ Working)
- Special categories (✅ Working)
- Edge cases (✅ Handled)

## 🤝 Contributing

1. Test the GPT with real products
2. Report calculation errors
3. Suggest new features
4. Improve conversation flows

## 📝 Key Learnings

- GPTs cannot execute code or call fictional APIs
- All logic must be in instructions + knowledge files
- GPT uses AI to perform calculations from reference data
- Simpler architecture = more reliable results

---

**Version**: 1.0.0
**Status**: Phase 1 Complete, Ready for Testing
*Calculate smarter, sell better!* 💰