# Global Data Center Resource Consumption Analysis
This project explores operational efficiency and resource consumption
patterns across global data centers.

The analysis focuses on:

- Electricity Consumption
- Water Consumption
- Power Usage Effectiveness (PUE)
- Cooling System Efficiency
- Facility Type Comparisons
- Data Quality Assessment
  
# Dataset Size:
- 126,770 records
- 14 features

Key Variables:
- Estimated Capacity (MW)
- Daily Electricity Usage (MWh)
- Daily Water Usage (Gallons)
- PUE
- Cooling System Type
- Facility Type

# Tools
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Cooling System Efficiency

Liquid-cooled facilities achieved the best average PUE.

| Cooling System | Average PUE |
|---------------|------------|
| Liquid Cooled | 1.34 |
| Evaporative | 1.59 |
| Air Cooled | 1.67 |

---

### Facility Type Analysis

Hyperscale/AI facilities consumed the most resources.

| Facility Type | Water Usage (Gallons) |
|--------------|----------------------|
| Enterprise | 30,037 |
| Colocation | 298,375 |
| Hyperscale/AI | 1,074,522 |

---

### Resource Trade-Off

Hyperscale/AI facilities had:

- Best energy efficiency (lowest PUE)
- Worst water efficiency (highest Water/MWh)

This suggests that optimizing one sustainability metric does not necessarily optimize another.

The Country field contained:

- Country names
- Postal codes
- Building names
- Multiple language representations

Examples:

- Netherlands
- Nederland
- Niederlande

This limited reliable country-level analysis and highlighted
the importance of data quality validation.
