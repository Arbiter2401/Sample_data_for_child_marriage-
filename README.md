# Sample_data_for_child_marriage-
# Data for: Warming Climate May Increase the Prevalence of Girl Child Marriage and Adolescent Childbearing: A Global Analysis in 57 Low- and Middle-Income Countries

This repository provides a representative data sample supporting the results of the main text.

The full individual-level records were obtained from [The DHS Program](https://dhsprogram.com/data/) under its data use agreement, which **permits analysis but prohibits redistribution** of the microdata. To enable inspection and replication while complying with this restriction, we deposit a stratified 1% random sample.

### Variables

| Variable | Description |
|---|---|
| `country`, `DHS_survey` | Country and DHS survey identifier |
| `child_marriage` | First formal union before age 18 (1/0) |
| `child_marriage_level` | Age at marriage subgroup |
| `child_birth` | Adolescent childbearing (livebirth at age 15–19) (1/0) |
| `child_birth_level` | Age at birth subgroup |
| `temp_marry_12m`, `precip_marry_12m` | Mean temperature / cumulative precipitation over the 12 months before first marriage |
| `temp_birth_12m`, `precip_birth_12m` | Same, for the 12 months before estimated conception of first birth |
| `highest_edu_level`, `religion`, `resid_type`, `paternal_edu` | Women's education, religion, urban/rural residence, partner's education |
| `floor_mat`, `roof_mat`, `wealth_level` | Household flooring, roofing, DHS wealth quintile |
| `CPI`, `GDP` | Country-year Crop Production Index and GDP per capita |
| `marry_1_year`, `marry_1_month`, `birth_1_year`, `birth_1_month` | Year and month of first marriage / first birth |

Temperature and precipitation were derived from ERA5 reanalysis matched to DHS cluster coordinates.
