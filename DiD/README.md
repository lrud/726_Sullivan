
# Callaway & Sant'Anna (2021) Replication (Python)

**Goal:** Replicate the minimum wage DiD/event study from the R code using Python, matching logic and output.

## Progress
- Data loaded, covariates constructed, summary stats match R output.
- DiD/event study with `csdid` (Python): group-time ATT, conditional/unconditional, plots with CIs.
- Visual/statistical interpretation: post-treatment ATT(g, t) significance = CI band for t = g+1 excludes zero.

## Left To Do
- (Optional) Sensitivity/robustness checks (e.g., parallel trends, placebo).
- Final review/documentation polish if needed.
