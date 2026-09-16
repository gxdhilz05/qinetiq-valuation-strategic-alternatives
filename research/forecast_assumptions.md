# Forecast assumptions

## Model structure

The model will compare three outcomes for Global Solutions:

1. Retain with limited improvement.
2. Retain and restructure.
3. Divest the US business.

One forecast model will eventually use a scenario selector instead of three separate Excel files. The assumptions below are the initial retain-with-limited-improvement base case. They assume both segments remain in the group, no acquisitions or disposals, and constant exchange rates.

## Segment forecast formulas

```text
Revenue = Previous-year revenue x (1 + revenue growth)
Operating profit = Revenue x operating margin
Group revenue = EMEA revenue + Global Solutions revenue
Group operating profit = EMEA operating profit + Global Solutions operating profit
Group margin = Group operating profit / Group revenue
```

## Segment assumptions

| Assumption | FY27E | FY28E | FY29E | FY30E | FY31E |
|---|---:|---:|---:|---:|---:|
| EMEA revenue growth | 5.0% | 5.0% | 4.5% | 4.0% | 3.5% |
| Global Solutions revenue growth | 0.0% | 2.0% | 3.0% | 3.0% | 3.0% |
| EMEA operating margin | 11.9% | 12.0% | 12.1% | 12.1% | 12.0% |
| Global Solutions operating margin | 8.5% | 9.0% | 9.5% | 9.8% | 10.0% |

## Calculated segment forecast

| £m except percentages | FY27E | FY28E | FY29E | FY30E | FY31E |
|---|---:|---:|---:|---:|---:|
| EMEA revenue | 1,605.7 | 1,685.9 | 1,761.8 | 1,832.3 | 1,896.4 |
| Global Solutions revenue | 393.4 | 401.3 | 413.3 | 425.7 | 438.5 |
| Group revenue | 1,999.1 | 2,087.2 | 2,175.1 | 2,258.0 | 2,334.9 |
| Group revenue growth | 4.0% | 4.4% | 4.2% | 3.8% | 3.4% |
| Group operating profit | 224.5 | 238.4 | 252.4 | 263.4 | 271.4 |
| Group operating margin | 11.2% | 11.4% | 11.6% | 11.7% | 11.6% |

FY27 is anchored to management's guidance of 3-5% group revenue growth and an 11.0-11.5% underlying operating margin. The segment assumptions produce approximately 4.0% growth and an 11.2% margin, near the middle of those ranges.

EMEA growth is supported by the funded backlog, the LTPA extension and demand for test and evaluation, but it tapers as visibility declines. Global Solutions is held flat in FY27 because the US recovery has not yet been demonstrated, then returns gradually to modest growth. EMEA margins stay near 12%; Global Solutions margins recover slowly as the reduced cost base and contract mix improve.

## Historical UFCF calibration

| £m except percentages | FY22A | FY23A | FY24A | FY25A | FY26A |
|---|---:|---:|---:|---:|---:|
| Revenue | 1,320.4 | 1,580.7 | 1,912.1 | 1,931.6 | 1,922.6 |
| Underlying D&A | 52.1 | 59.0 | 65.5 | 86.3 | 96.5 |
| Underlying D&A / revenue | 3.9% | 3.7% | 3.4% | 4.5% | 5.0% |
| Gross capital expenditure | 84.3 | 109.0 | 96.3 | 108.8 | 72.5 |
| Capital expenditure / revenue | 6.4% | 6.9% | 5.0% | 5.6% | 3.8% |
| Cash-flow working-capital movement (source positive) | 22.0 | (7.7) | 9.8 | 49.8 | (15.5) |
| Cash tax paid | 20.0 | 30.2 | 36.9 | 48.6 | 44.4 |
| Underlying effective tax rate | 16.9% | 19.4% | 25.3% | 26.0% | 26.6% |

Underlying D&A excludes acquisition-related amortisation, goodwill impairment and other specific adjusting items. This is important because the statutory FY25 D&A and impairment line was distorted by a £143.9m goodwill impairment and should not be used as the recurring UFCF add-back.

Gross capital expenditure equals cash purchases of property, plant and equipment plus intangible assets. The working-capital row follows the cash-flow statement sign convention: a positive figure is a cash source and a negative figure is a cash use.

## UFCF forecast assumptions

| Assumption | FY27E | FY28E | FY29E | FY30E | FY31E |
|---|---:|---:|---:|---:|---:|
| Cash tax rate | 26.5% | 26.5% | 26.5% | 26.5% | 26.5% |
| D&A / revenue | 5.0% | 5.0% | 5.0% | 5.0% | 5.0% |
| Capital expenditure / revenue | 4.5% | 4.5% | 4.5% | 4.5% | 4.5% |
| NWC investment / change in revenue | 1.0% | 1.0% | 1.0% | 1.0% | 1.0% |

### Cash tax rate: 26.5%

The UK statutory corporation-tax rate is 25%. QinetiQ's underlying effective tax rate increased to 26.0% in FY25 and 26.6% in FY26, and management expects it to remain marginally above the UK statutory rate because of geographic profit mix and non-deductible items. A flat 26.5% is therefore a practical normalized rate without forecasting one-off deferred-tax movements.

### D&A: 5.0% of revenue

Underlying D&A rose from 3.4% of revenue in FY24 to 4.5% in FY25 and 5.0% in FY26 as the depreciable and internally developed asset base increased. Holding the FY26 ratio constant recognizes that recent investment will continue to be depreciated while avoiding any further automatic increase.

### Capital expenditure: 4.5% of revenue

Historical CapEx was volatile: 3.8%-6.9% of revenue, with a five-year average of approximately 5.5%. FY26 was unusually low, while earlier years included heavier LTPA and digital investment. A 4.5% normalized rate sits above FY26 but below the investment-heavy historical average. It assumes continued maintenance and capability investment, with some moderation after the recent build-out.

### Change in net working capital: 1.0% of revenue growth

QinetiQ's annual working-capital movements are volatile because contract assets, customer advances, receivables and payables depend on programme milestones and payment timing. Extrapolating the FY25 inflow or FY26 outflow would be misleading. The model therefore assumes a small cash investment equal to 1.0% of incremental revenue: growing sales use a little cash, but not enough to imply a structural deterioration in cash conversion.

## UFCF formula and output

```text
NOPAT = EBIT x (1 - cash tax rate)
D&A = Revenue x D&A / revenue
Capital expenditure = Revenue x CapEx / revenue
Change in NWC = Change in revenue x NWC investment rate
UFCF = NOPAT + D&A - Capital expenditure - Change in NWC
```

| £m | FY27E | FY28E | FY29E | FY30E | FY31E |
|---|---:|---:|---:|---:|---:|
| NOPAT | 165.0 | 175.2 | 185.5 | 193.6 | 199.5 |
| D&A | 100.0 | 104.4 | 108.8 | 112.9 | 116.7 |
| Capital expenditure | (90.0) | (93.9) | (97.9) | (101.6) | (105.1) |
| Change in NWC | (0.8) | (0.9) | (0.9) | (0.8) | (0.8) |
| UFCF | 174.2 | 184.8 | 195.5 | 204.1 | 210.4 |

The FY27-FY29 cumulative UFCF is approximately £554.6m. Management targets more than £550m of reported free cash flow over the same period. This is a useful directional sense check, but it is not like-for-like: management's measure includes interest and exceptional operating cash flows, whereas UFCF excludes financing and uses normalized operating assumptions.

## Commercial considerations

- Higher defence budgets support demand only after relevant contracts are awarded and delivered.
- The large EMEA backlog gives stronger near-term visibility than Global Solutions.
- Autonomy, cyber, mission data, synthetic training and directed energy support demand for testing and integration, but no separate AI premium is assumed.
- Growth assumptions are nominal and already include ordinary inflation; wage and facility inflation may limit margin expansion.
- The base case uses constant exchange rates.
- The retain, restructure and divest cases will change the US growth, margin, restructuring-cost and disposal assumptions. Shared assumptions such as tax, D&A, CapEx and working capital will be reused where appropriate rather than rebuilt blindly.

## Main sources

- [QinetiQ FY27 Q1 trading update](https://www.qinetiq.com/en/news/q1-trading-update)
- [QinetiQ FY26 full-year results](https://www.rns-pdf.londonstockexchange.com/rns/1743F_1-2026-5-20.pdf)
- [QinetiQ Annual Report and Accounts 2026](https://www.annualreports.com/Click/37681)
- [QinetiQ Annual Report and Accounts 2024](https://www.annualreports.com/HostedData/AnnualReportArchive/q/LSE_QQ.L_2024.pdf)
- [QinetiQ Annual Report and Accounts 2023](https://www.annualreports.com/HostedData/AnnualReportArchive/q/LSE_QQ.L_2023.pdf)
- [QinetiQ Annual Report and Accounts 2022](https://www.annualreports.com/HostedData/AnnualReportArchive/q/LSE_QQ.L_2022.pdf)

The assumptions should be reviewed when QinetiQ publishes new information or announces the outcome of the US strategic review.
