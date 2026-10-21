# Build report

Source scripts copied: 36
Missing allowlisted scripts: 0
Compact result CSVs copied: 36

## Copied scripts
- `prepare_tfl_2023_2026.py`
- `fix_tfl_calendar_lags.py`
- `baseline_tfl_forecasting.py`
- `ablation_tfl_forecasting_v2.py`
- `ablation_tfl_forecasting_v3.py`
- `advanced_tfl_forecasting.py`
- `dataset_diagnostics.py`
- `generate_figures.py`
- `scientific_validation_stage32b.py`
- `stage32c_final_reconciliation.py`
- `validate_tfl_ml_dataset.py`
- `verify_tfl_ablation_v3.py`
- `stage75_mhtdr_station_ablation_preflight.py`
- `stage76_mhtdr_station_ablation.py`
- `stage77_temporal_leakage_feature_integrity_results_auditv.py`
- `stage77_1_rolling_feature_reaudit.py`
- `stage77_2_test_period_target_usage_audit.py`
- `stage77_3_forecasting_protocol_audit.py`
- `stage77_4_test_feature_provenance_operational_validity_audit.py`
- `stage77_5_1_station_coverage_stratified_metrics_audit.py`
- `stage77_5_2_forecast_protocol_decision_manuscript_reporting_audit.py`
- `stage35_final_consistency_audit.py`
- `stage35b_manuscript_only_audit.py`
- `stage37_final_manuscript_audit_and_figure_restore.py`
- `stage38_final_manuscript_figure_replacement_rebuild_audit.py`
- `stage38b_docx_only_final_audit.py`
- `stage39_final_zip_content_inspection_submission_readiness.py`
- `stage40_final_manuscript_submission_package_review.py`
- `stage41_final_manuscript_content_review.py`
- `stage41a_residual_definition_verification.py`
- `stage41b_fix_residual_audit.py`
- `stage41c_final_content_reaudit.py`
- `stage42_final_submission_package_integrity_recheck.py`
- `stage48_generate_supplementary_tables.py`
- `stage49_supplementary_tables_scientific_audit.py`
- `stage49_1_supplementary_tables_correction_reaudit.py`

## Missing scripts — review
- None

## Summary CSVs
- `tfl_baseline_results\baseline_comparison_table.csv`
- `tfl_baseline_results\feature_importance.csv`
- `tfl_baseline_results\validation_baseline_results.csv`
- `tfl_ablation_results\ablation_results.csv`
- `tfl_ablation_results\feature_summary.csv`
- `tfl_ablation_results_v2\ablation_results_v2.csv`
- `tfl_ablation_results_v2\feature_diagnostics_v2.csv`
- `tfl_ablation_results_v2\feature_summary_v2.csv`
- `tfl_ablation_results_v2\split_summary_v2.csv`
- `tfl_ablation_results_v3\ablation_results_v3.csv`
- `tfl_ablation_results_v3\calendar_feature_diagnostics_v3.csv`
- `tfl_ablation_results_v3\date_validation_v3.csv`
- `tfl_ablation_results_v3\feature_diagnostics_v3.csv`
- `tfl_ablation_results_v3\feature_summary_v3.csv`
- `tfl_ablation_results_v3\MANUSCRIPT_ABLATION_TABLE_V3.csv`
- `tfl_ablation_results_v3\split_summary_v3.csv`
- `tfl_advanced_results\advanced_feature_importance.csv`
- `tfl_advanced_results\advanced_validation_results.csv`
- `tfl_ml_validation\station_coverage.csv`
- `tfl_ml_validation\validation_2024.csv`
- `tfl_mhtdr_station_ablation_stage76\station_ablation_metrics.csv`
- `tfl_stage77_5_1_station_coverage_audit\station_coverage_summary.csv`
- `tfl_stage77_5_1_station_coverage_audit\stratified_metrics_by_variant.csv`
- `tfl_stage77_5_1_station_coverage_audit\unseen_station_metrics_by_variant.csv`
- `tfl_stage77_audit\stage77_1_rolling_reaudit.csv`
- `tfl_stage77_audit\stage77_3_protocol_findings.csv`
- `tfl_stage77_audit\stage77_audit_checks.csv`
- `tfl_stage77_audit\stage77_results_artifact_audit.csv`
- `tfl_stage77_audit\stage77_split_coverage.csv`
- `dataset_diagnostics\DATASET_COMPARISON.csv`
- `scientific_validation_results\FINAL_MANUSCRIPT_FEATURE_IMPORTANCE_TOP10.csv`
- `scientific_validation_results\scientific_validation_summary.csv`
- `scientific_validation_results\stage35b_audit\figure_audit.csv`
- `scientific_validation_results\stage35_audit\figure_file_audit.csv`
- `scientific_validation_results\stage35_audit\model_comparison_deltas.csv`
- `scientific_validation_results\stage35_audit\STAGE35_FINAL_AUDIT_SUMMARY.csv`

## Required manual checks
- Confirm scripts are the exact versions used for the manuscript.
- Check paths, dependencies, output filenames, and data-source terms.
- Compare copied tables and figures with the manuscript.
- Check for personal information, credentials, raw data, and unrelated files.
- Run in a clean environment before claiming reproducibility.
