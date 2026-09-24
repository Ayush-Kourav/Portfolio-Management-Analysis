# Model Checks

The corrected model checks portfolio capital, portfolio-weight normalization, daily compounding, benchmark normalization, relative return, and statistical beta calculation.

## Key Audit Findings

1. Holdings total ₹100.58 Cr while the original Daily Valuation sheet starts at ₹100 Cr. The corrected analysis uses ₹100.58 Cr.
2. Original Beta was a CAGR ratio, not statistical beta. Corrected beta uses covariance/variance on the available daily returns.
3. The original daily Beta and cumulative Beta columns are ratios, not valid beta estimates.
4. Only 10 daily observations are populated, limiting long-term inference.
