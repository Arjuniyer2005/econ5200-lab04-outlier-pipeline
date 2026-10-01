# econ5200-lab04-outlier-pipeline
# Outlier Detection on California Housing

## Objective
I compared three outlier-detection methods on the California Housing dataset to see where they agree, where they differ, and which one I would recommend for this data.

## Methodology
- I found and fixed three bugs in an existing outlier-detection pipeline so that it produced correct results.
- I used an `OutlierDetector` class that supports three methods: modified Z-score, Tukey fences, and Isolation Forest. The class checks its settings before running and reports a summary of what it flagged.
- I ran the modified Z-score and Tukey fences on a single column, `MedInc` (median income).
- I ran Isolation Forest on all 9 columns to catch points that look unusual across several variables at once.
- I compared the flagged rows across all three methods to find the points every method agreed on.
- I wrote a memo on which method to use and why.
- I built an interactive explorer that lets a user switch between methods and see which points each one flags.

## Key Findings
- Modified Z-score on `MedInc` flagged [YOUR VALUE] rows.
- Tukey fences on `MedInc` flagged [YOUR VALUE] rows.
- Isolation Forest on all 9 columns flagged [YOUR VALUE] rows.
- All three methods agreed on [YOUR VALUE] rows.
- In my method-selection memo, I recommended [YOUR VALUE].
