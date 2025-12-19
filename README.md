# Comparable Company & Precedent Transaction Valuation Model (Excel)

This project is a presentation-ready investment banking valuation model built in Excel. It performs comparable company analysis and precedent transaction analysis, converts implied enterprise values to equity value and price per share, and visualizes valuation ranges using a football-field chart with a current share price overlay.

## What this model does
- Builds trading multiples for public peers (EV/Revenue, EV/EBITDA, P/E)
- Builds deal multiples for precedent transactions (EV/Revenue, EV/EBITDA)
- Summarizes valuation statistics using P25, median, and P75 multiples
- Applies multiples to a target company to derive implied EV, equity value, and implied price per share
- Displays valuation ranges in a football-field chart for quick interpretation

## Tabs
- **Inputs_Target**: target financials, net debt (net cash), shares, and current price
- **Comps**: peer set and trading multiple calculations
- **Precedents**: transaction set and deal multiple calculations
- **Valuation_Output**: implied EV → equity value → price per share + football-field visualization

## Notes on methodology
- Financials are handled consistently in USD millions, with shares in millions
- Multiples that are not representative due to peer margin dispersion are excluded from the football-field visualization (while retained in the model for reference)

## Tools
- Microsoft Excel

## Why this project
This model is designed to reflect real-world investment banking workflows: Excel is used for valuation, output checks, and presentation-quality visuals.
