# Task 11: A/B Testing — Hypothesis Testing in Python

## Objective
The objective of this task is to perform A/B testing to compare the performance of two marketing channels
(Email vs Paid Search) using statistical hypothesis testing.

## Dataset
Marketing campaign dataset containing:
- campaign_id
- channel
- objective
- start_date
- end_date
- target_segment
- expected_uplift

## Tools & Technologies
- Google Colab
- Python
- Libraries: pandas, numpy, scipy, matplotlib

## Methodology
1. Loaded the dataset into Google Colab
2. Defined Email campaigns as the Control group
3. Defined Paid Search campaigns as the Test group
4. Formulated null and alternative hypotheses
5. Performed an independent t-test
6. Evaluated statistical significance using p-value
7. Calculated 95% confidence interval
8. Visualized uplift distributions
9. Generated business recommendation

## Results
Paid Search campaigns showed a higher average expected uplift compared to Email campaigns.
The statistical test indicated that the difference is significant.

## Files in Repository
- task11_abtest.ipynb : Complete analysis notebook
- campaigns.csv : Dataset used
- ab_test_summary.csv : Summary of results
- final_recommendation.txt : Business recommendation

## Conclusion
Based on the A/B testing results, it is recommended to focus more on Paid Search campaigns
to improve marketing performance.
