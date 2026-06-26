# Data and Code Archive for Ecotoxicology and Environmental Safety Submission

This folder archives the data tables and scripts used for the current submission package.

## Data

- `cleaned_analysis_dataset_combined_chronic_defs.csv`: cleaned analysis dataset used for the current reanalysis.
- `reanalysis_summary.csv`: sample-size and reanalysis summary.

## Results

- `Table1_combined_chronic_defs.csv`: previous baseline summary output.
- `Table2_egfr_levels_combined_chronic_defs.csv`: single-metal cross-sectional eGFRcr-cys models.
- `Table3_annualized_loss_combined_chronic_defs.csv`: single-metal annualized eGFRcr-cys loss models.
- `Table4_binary_outcomes_combined_chronic_defs.csv`: secondary binary kidney-function outcome models.
- `Table_included_vs_excluded.csv`: included vs excluded participant comparison.
- `Table_mixture_qgcomp_summary.csv`: quantile g-computation mixture summary.
- `Table_mixture_qgcomp_weights.csv`: quantile g-computation component weights.

## Tables

- `Table_1_Baseline_by_Overall_Soil_Metal_Mixture_Quartiles.xlsx`: updated Table 1 by overall residential soil metal mixture quartiles.

## Code

- `rerun_results_combined_chronic_defs.py`: main reanalysis script for cleaned dataset and single-metal models.
- `run_mixture_and_selection_analyses.py`: mixture exposure and sample-selection analyses.
- `build_table1_by_mixture_quartiles_ep.py`: updated Table 1 generation script.
- `update_manuscript_for_table1_mixture_ep.py`: manuscript text update for the revised Table 1.
- `update_manuscript_table1_discussion_ep.py`: discussion update for revised Table 1.
- `mark_table1_notes_red_ep.py`: marks Table 1-related manuscript revisions in red.
- `color_citations_red_ep.py`: marks in-text citation superscripts in red for checking.
- `fix_reference_order_ep.py`: reference ordering and superscript formatting script.
- `update_structured_abstract_ep.py`: structured abstract update script.
- `build_ees_cover_letter.py`: cover letter generation script.

## Notes

The current Table 1 uses quartiles of an overall residential soil metal mixture score. The score was calculated as the sum of metal-specific quartile scores for As, Cd, Co, Cr, Cu, Ni, and Pb in the complete-case descriptive sample.
