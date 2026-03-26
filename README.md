# marketing-incrementality-geo-lift
Incrementality Testing: Measuring True Marketing Lift with Geo Holdout Design


# Incrementality Testing: Geo Lift (Difference-in-Differences)

## Objective
This project measures the causal impact of a marketing campaign using a geo holdout experiment and a difference-in-differences (DiD) approach.

## Methodology

### 1. Experimental Design
- Regions were split into treatment and control groups.
- The campaign was applied only to treatment regions during the post period.

### 2. Difference-in-Differences (DiD)
- Estimated causal lift by comparing changes in treatment vs control groups over time.
- Controlled for baseline differences and time trends.

### 3. Incremental Metrics
- Incremental conversions
- Incremental revenue
- Incremental spend
- Incremental ROI (iROI)

## Key Results

- Incremental conversions: ~5,065
- Incremental revenue: ~$212,675
- Incremental spend: ~$287,300
- Incremental ROI: **0.74**

## Insights

- The campaign generated significant incremental lift.
- However, incremental ROI was below 1, indicating the campaign was not profitable in the short term.
- Results suggest the need for optimization in targeting and budget allocation.

## Business Recommendations

- Optimize targeting and audience segmentation.
- Reallocate budget toward higher-performing channels.
- Evaluate long-term impact (LTV, brand awareness) before discontinuing the campaign.

## Tools Used
- Python (pandas, statsmodels, matplotlib, seaborn)

## Next Steps
- Extend to user-level uplift modeling
- Combine with MMM for holistic measurement
- Incorporate customer lifetime value (LTV)
