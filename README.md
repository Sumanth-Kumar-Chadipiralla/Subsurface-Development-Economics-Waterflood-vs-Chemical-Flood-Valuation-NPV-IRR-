# Subsurface-Development-Economics-Waterflood-vs-Chemical-Flood-Valuation-NPV-IRR-
Energy Economics 
```markdown
# Chemical EOR Economics: After-Tax DCF Comparison of Waterflood vs Chemical Flood

This project is an Excel-based subsurface energy economics model that evaluates whether upgrading a base waterflood to a chemical flood (tertiary EOR) creates incremental value. The workbook compares both cases using an after-tax discounted cash flow (DCF) framework with an economic limit cutoff.

## What’s Inside
- **Base Waterflood Case**
  - Production/revenue and cost model
  - Taxes and depletion allowance
  - After-tax cash flow + mid-year discounting
  - Economic limit determination, economic life, and economic reserves (EUR)

- **Chemical Flood Case**
  - Modified production profile (uplift + different decline behavior)
  - Updated watercut trend assumptions
  - Incremental OPEX assumptions
  - Facility upgrade CAPEX with **MACRS 7-year depreciation**
  - After-tax cash flow + mid-year discounting
  - Economic limit determination, economic life, and EUR

## Key Methods & Assumptions (high level)
- **After-tax DCF** with:
  - Royalty and Working Interest applied to revenue
  - Severance tax and income tax
  - Depletion allowance (base and updated for chemical flood case)
  - Depreciation (MACRS for facility upgrade)
- **Discounting:** 15% discount rate with **mid-year convention**
- **Economic limit:** project stops when annual undiscounted after-tax cash flow becomes negative

> Note: Results depend on assumptions (prices, costs, decline, watercut, CAPEX timing). Update these inputs to match your case.

## Project Outcomes (what this model produces)
- After-tax **NPV** (discounted NPV)
- **IRR** (if included / can be added)
- **Payout** (if included / can be added)
- **Economic life** (years to economic limit)
- **Economic reserves (EUR)** until economic limit

## How to Use the Workbook
1. Open the Excel file:
   - `Sumanth's Final Project Chemical Waterflood-1.xlsx`
2. Review/confirm the **input assumptions** (prices, WI/royalty, taxes, costs, discount rate).
3. Check the **Base Case** calculations:
   - Production and watercut
   - Revenue, OPEX, taxes
   - After-tax cash flow and discounted cash flow
   - Economic limit and EUR
4. Check the **Chemical Flood Case** calculations:
   - Incremental production behavior and decline
   - Updated OPEX and CAPEX
   - Depreciation schedule (MACRS)
   - Economic limit and EUR
5. Compare results:
   - Base vs Chemical: NPV, economic life, EUR, and value drivers

## What to Highlight on a Resume (4 bullets)
- Built an **after-tax DCF** model in Excel to compare **base waterflood vs chemical flood** economics using royalty/WI, severance tax, income tax, and **15% mid-year discounting**.
- Forecasted production performance using decline and watercut behavior; determined **economic limit, economic life, and EUR** for each case.
- Modeled chemical flood investment impacts including **$5MM facilities CAPEX**, **MACRS 7-year depreciation**, incremental OPEX, and updated depletion allowance.
- Evaluated **NPV/IRR and key economic drivers** to recommend whether chemical flooding creates incremental value versus continuing the base waterflood.

## File Structure
- `Sumanth's Final Project Chemical Waterflood-1.xlsx` — main workbook (inputs, base case, chemical case, results)

## Notes / Known Checks (recommended)
- Verify the chemical flood **CAPEX is included as an upfront cash outflow** (not only depreciation benefits).
- Confirm the NPV value is calculated from discounted cash flows (not manually entered).
- Confirm the economic limit logic matches your course definition (before/after tax, discounted/undiscounted).

## License
Academic / personal portfolio use.
```
