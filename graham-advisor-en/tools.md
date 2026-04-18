# Benjamin Graham Analysis Tools

## Tool 1: Margin of Safety Calculator

```
┌─────────────────────────────────────────────────┐
│            Margin of Safety Calculator           │
├─────────────────────────────────────────────────┤
│ Company Name: _______________________           │
│ Intrinsic Value (conservative): ________        │
│ Current Price: ___________________             │
│                                                  │
│ MOS = (IV - Price) / IV                        │
│     = (________ - ________) / ________          │
│     = __________ %                              │
│                                                  │
│ Graham Standard: MOS > 30% before considering   │
│ Aggressive Standard: MOS > 50% for more safety │
└─────────────────────────────────────────────────┘

Judgment:
□ MOS > 50% — Strong buy signal
□ MOS 30-50% — Worth considering
□ MOS < 30% — Caution, wait for better price
□ MOS < 0 — Price exceeds value, don't buy
```

---

## Tool 2: Intrinsic Value Estimation

### Method 1: Graham Formula

```
V = EPS × (8.5 + 2g)

Where:
- V = Intrinsic Value
- EPS = Earnings Per Share (TTM or expected)
- 8.5 = Empirical coefficient (reasonable P/E baseline)
- g = Expected annual growth rate next 7-10 years (%)

Calculation:
EPS = ___________
g (expected growth rate) = ___________ %
V = ___________ × (8.5 + 2 × ___________)
V = ___________

Current Price: ___________
MOS = (_________ - _________) / _________ = _______%
```

### Method 2: Liquidation Value Method

```
Total Assets = ___________
Total Liabilities = ___________
Liquidation Value = Assets - Liabilities = ___________

Note: Liquidation value assumes immediate company shutdown.
Best for asset-heavy companies (industrial, financial).
Not suitable for asset-light companies (tech, services).

Per-share Liquidation Value = ___________ / shares = ___________
Current Stock Price = ___________
Ratio = Current Price / Per-share Liquidation = ___________

Graham Standard: Ratio < 1/3 for margin of safety
```

### Method 3: Discounted Cash Flow (Simplified)

```
Average annual cash flow next 5 years = ___________
Perpetual growth rate (assumed) = ___________ %
Discount rate = ___________ % (Graham typically uses 10-12%)

Step 1: Calculate present value of 5-year cash flows
Year 1: ________ / (1+____%)^1 = ________
Year 2: ________ / (1+____%)^2 = ________
Year 3: ________ / (1+____%)^3 = ________
Year 4: ________ / (1+____%)^4 = ________
Year 5: ________ / (1+____%)^5 = ________
Subtotal = ___________

Step 2: Calculate perpetual value
Perpetual Value = PV annuity factor × last year cash flow
                = (1 / (rate - growth)) × last year cash flow
                = (1 / (________ - ________)) × ________
                = ___________

Step 3: Calculate enterprise value
Enterprise Value = 5yr CF PV + perpetual value PV
                = ________ + ________ / (1+____%)^5
                = ___________
```

---

## Tool 3: Investment Decision Checklist

```
┌─────────────────────────────────────────────────┐
│           Graham Investment Decision Checklist     │
├─────────────────────────────────────────────────┤
│                                                  │
│ □ 1. Do I know this company's intrinsic value?  │
│    Answer: _________________                      │
│                                                  │
│ □ 2. Is current price well below IV (>30% MOS)? │
│    Answer: _________________                      │
│                                                  │
│ □ 3. Do I understand WHY the price is so low?   │
│    □ Market doesn't see the value (opportunity) │
│    □ Hidden risks (trap)                        │
│    □ Uncertain                                  │
│                                                  │
│ □ 4. Can I hold for at least 3-5 years?        │
│    Answer: _________________                      │
│                                                  │
│ □ 5. Can I absorb a 30% further market drop?    │
│    Answer: _________________                      │
│                                                  │
│ □ 6. What's the worst-case outcome if I'm wrong? │
│    Answer: _________________                      │
│                                                  │
│ □ 7. Do I have sufficient cash flow for living  │
│    without needing to liquidate this position?  │
│    Answer: _________________                      │
│                                                  │
│ Only invest when ALL answers satisfy you.        │
└─────────────────────────────────────────────────┘
```

---

## Tool 4: Corporate Financial Health Check

```
┌─────────────────────────────────────────────────┐
│           Graham Financial Health Check           │
├─────────────────────────────────────────────────┤
│                                                  │
│ Profitability Indicators:                         │
│ □ Profitability every year for past 10 yrs:     │
│   _______ years out of 10                        │
│ □ ROE (Return on Equity) > 15%: ________        │
│ □ Gross margin stable or improving: ________     │
│                                                  │
│ Financial Stability:                             │
│ □ Current Ratio > 2: _________                  │
│ □ Long-term debt / Total assets < 50%: ________ │
│ □ Interest coverage ratio > 5: ________         │
│                                                  │
│ Valuation Indicators:                            │
│ □ P/E ratio < 20: _________                    │
│ □ P/B ratio < 1.5: _________                  │
│ □ Dividend yield > 3% (if conservative): _____ │
│                                                  │
│ Conclusion:                                      │
│ □ Passes all checks → Deep analysis            │
│ □ Some indicators fail → Caution, potential    │
│   discount opportunity                          │
│ □ Most indicators fail → Doesn't meet Graham  │
│   standards                                    │
└─────────────────────────────────────────────────┘
```

---

## Tool 5: Market Sentiment Thermometer

```
┌─────────────────────────────────────────────────┐
│            Market Sentiment Thermometer          │
├─────────────────────────────────────────────────┤
│                                                  │
│ Observe these signals to judge market sentiment: │
│                                                  │
│ 【Fear Signals】← May be buy opportunities       │
│ □ VIX index > 30 (market panic)                 │
│ □ Newspaper headlines are all bad news         │
│ □ People around you discuss losses             │
│ □ IPO market is cold                           │
│ □ Mutual funds are hard to sell                │
│                                                  │
│ 【Greed Signals】← May be sell signals          │
│ □ VIX index < 15 (market complacency)          │
│ □ Newspaper headlines are all good news       │
│ □ People around you discuss making money       │
│ □ IPOs oversubscribed 10x+                    │
│ □ New investors rushing in                     │
│                                                  │
│ 【Current Judgment】                              │
│ Market Sentiment: □ Extreme Fear  □ Fear       │
│                   □ Neutral    □ Greed           │
│                   □ Extreme Greed               │
│                                                  │
│ Graham's Advice: Buy at extreme fear,           │
│ sell at extreme greed                          │
└─────────────────────────────────────────────────┘
```

---

## Usage Instructions

These tools are designed to help you **actually apply** Graham's thinking framework.

How to use:
1. When facing an investment decision, pull out the Margin of Safety Calculator
2. Use the Intrinsic Value Estimation to value the business
3. Run through the Investment Decision Checklist for final check
4. Use the Financial Health Check for quick screening
5. Use the Market Sentiment Thermometer to time entry

Remember: **Graham's core is conservatism.** Better to miss an opportunity than to take a risk without certainty.
