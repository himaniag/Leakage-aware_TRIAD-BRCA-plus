Figures and Tables for "Leakage-Aware Ensemble Learning for Multi-Omics Breast Cancer Subtype Classification"
==============================================================================

Authors: Himani Agrawal (1) and Megha Rathi (1, *)
(1) Department of Computer Science & Engineering and Information Technology, Jaypee Institute of
    Information Technology, A-10, Sector 62, Noida 201309, Uttar Pradesh, India
E-mail: agrawal.himani1010@gmail.com (H. Agrawal); *megha.rathi@mail.jiit.ac.in (M. Rathi, corresponding author)

Description
-----------
This record contains every figure and table of the manuscript and of its Supplementary Materials:
6 main figures, 10 main tables, 11 supplementary figures and 15 supplementary tables. Tables are given
as individual CSV files, as one Excel workbook per folder (one sheet per table, with caption and notes),
and as Word and PDF compilations. Each folder also contains the captions.

Source code, data and logs that regenerate all figures and tables:
https://github.com/himaniag/Multi-Omics-Breast-Cancer

Folder structure
----------------
1_Figures/  (main figures, PNG, 300 dpi)
    Fig1_architecture.png                          Fig. 1. Architecture of TRIAD-BRCA+.
    Fig2_critical_difference_diagram.png           Fig. 2. Critical-difference diagram of mean balanced-accuracy ranks over the 10 paired folds.
    Fig3_confusion_matrices.png                    Fig. 3. Confusion matrices of pooled out-of-fold predictions (repeat 1, n = 1,559).
    Fig4_permutation_importance.png                Fig. 4. Permutation importance of TRIAD-BRCA+ on outer test folds (repeat 1).
    Fig5_kaplan_meier_survival.png                 Fig. 5. Kaplan–Meier curves by reference PAM50 label and by TRIAD-BRCA+ out-of-fold prediction.
    Fig6_tcga_external_transfer.png                Fig. 6. External transfer to TCGA-BRCA (n = 506).
    Figure_captions.txt                            Full captions of Figs. 1-6

2_Tables/  (main tables)
    Table01_data_sources.csv                       Table 1. Data sources and their role in the study.
    Table02_leakage_governance.csv                 Table 2. Leakage governance: variable categories excluded before any modelling, and the retained clinical view.
    Table03_metagene_modules.csv                   Table 3. Knowledge-guided meta-gene modules, fixed a priori from the literature and restricted to genes present on the 489-gene panel.
    Table04_leakage_audit.csv                      Table 4. Leakage audit over the 10 paired folds.
    Table05_model_performance.csv                  Table 5. Performance on core-4 PAM50 subtyping (METABRIC, repeated 5-fold CV × 2, mean ± SD over 10 paired folds).
    Table06_incremental_ablation.csv               Table 6. Incremental ablation from TRIAD-BRCA v1 (A0) to TRIAD-BRCA+ (A5).
    Table07_fusion_by_decision_rule.csv            Table 7. Fusion × decision analysis on identical expert fits.
    Table08_tcga_transfer.csv                      Table 8. Cross-cohort transfer METABRIC → TCGA-BRCA.
    Table09_research_question_answers.csv          Table 9. Answers to the research questions (RQs) and the supporting evidence.
    Table10_state_of_the_art_comparison.csv        Table 10. Comparison with recent (2024–2026) state-of-the-art studies of breast-cancer molecular subtype classification.
    Table_captions_and_notes.csv                   Captions, notes and dimensions of Tables 1-10
    Main_Tables.xlsx                               All main tables in one workbook (one sheet per table)
    Main_Tables.docx / Main_Tables.pdf             All main tables with captions and notes

3_Supplementary_Figures/  (supplementary figures, JPG/PNG)
    FigS01_label_distribution_and_module_scores.jpg Fig. S1. Analytical cohort and knowledge-guided meta-gene modules.
    FigS02_leakage_audit.jpg                       Fig. S2. Leakage audit.
    FigS03_model_comparison.jpg                    Fig. S3. Comparison of all 16 configurations over the 10 paired folds.
    FigS04_ablation_waterfall.jpg                  Fig. S4. Incremental ablation from TRIAD-BRCA v1 (A0) to TRIAD-BRCA+ (A5).
    FigS05_fusion_by_decision_heatmap.jpg          Fig. S5. Fusion rule × decision rule analysis on identical expert fits.
    FigS06_roc_and_precision_recall.jpg            Fig. S6. Discrimination of TRIAD-BRCA+ on pooled out-of-fold predictions (repeat 1).
    FigS07_per_subtype_f1.png                      Fig. S7. Per-subtype F1 scores with 95% bootstrap confidence intervals on pooled out-of-fold predictions for the TRIAD-BRCA v1 equal-weight ensemble (V1), TRIAD-BRCA+ at the arg-max operating point and TRIAD-BRCA+ with the balanced-risk rule.
    FigS08_reliability_diagrams.jpg                Fig. S8. Reliability diagrams on pooled out-of-fold predictions: observed accuracy versus mean top-label confidence.
    FigS09_expert_error_correlation.jpg            Fig. S9. Pairwise error correlation between experts on pooled out-of-fold predictions.
    FigS10_robustness.jpg                          Fig. S10. Robustness to degraded molecular input applied at inference only.
    FigS11_learning_curves.jpg                     Fig. S11. Learning curves.
    Supplementary_figure_captions.txt              Full captions of Figs. S1-S11

4_Supplementary_Tables/  (supplementary tables)
    TableS01_cohort_characteristics.csv            Table S1. Characteristics of the analytical METABRIC cohort by PAM50 subtype (core-4, n = 1,559).
    TableS02_module_scores_by_subtype.csv          Table S2. Descriptive mean scores of the knowledge-guided meta-gene modules by subtype (standardised units) and Kruskal–Wallis tests on the full core-4 cohort.
    TableS03_hyperparameters.csv                   Table S3. Hyper-parameters, search spaces and the values selected by inner cross-fitting.
    TableS04_paired_significance_tests.csv         Table S4. Paired comparison of TRIAD-BRCA+ with every comparator over the 10 folds: mean difference and Nadeau–Bengio corrected resampled t-test, Holm-adjusted within each configuration and metric; effect size, Wilcoxon test and win/tie/loss counts refer to balanced accuracy.
    TableS05_leave_one_component_out.csv           Table S5. Leave-one-component-out analysis of TRIAD-BRCA+ (p: corrected resampled t-test, Holm-adjusted).
    TableS06_routing_weights.csv                   Table S6. Mean BE-adaptive routing weights (v1 Eqs.
    TableS07_per_subtype_performance.csv           Table S7. Per-subtype performance on pooled out-of-fold predictions (repeat 1; every patient predicted once, n = 1,559).
    TableS08_probability_calibration.csv           Table S8. Probability calibration on pooled out-of-fold posteriors (lower is better).
    TableS09_permutation_importance.csv            Table S9. Permutation importance (model reliance) of TRIAD-BRCA+ on outer test folds of repeat 1: view-level (5 permutations) and the 20 most important individual features (2 permutations).
    TableS10_error_diversity.csv                   Table S10. Error diversity of the expert triads on pooled out-of-fold predictions (lower Q / error correlation = more complementary).
    TableS11_robustness.csv                        Table S11. Robustness to degraded molecular input at inference (5 folds of repeat 1, balanced accuracy mean ± SD).
    TableS12_learning_curves.csv                   Table S12. Learning curves: Balanced accuracy (mean ± SD over the 5 folds of repeat 1) versus the number of training patients.
    TableS13_survival_validity.csv                 Table S13. Clinical validity: prognostic stratification by reference PAM50 labels versus out-of-fold predicted subtypes (univariable Cox models, Luminal A reference; hazard ratio (HR) with 95% CI).
    TableS14_tcga_cohort.csv                       Table S14. External TCGA-BRCA cohort characteristics.
    TableS15_headline_comparison.csv               Table S15. Headline comparison.
    Table_captions_and_notes.csv                   Captions, notes and dimensions of Tables S1-S15
    Supplementary_Tables.xlsx                      All supplementary tables in one workbook
    Supplementary_Tables.docx / .pdf               All supplementary tables with captions and notes

Notes
-----
- CSV files are UTF-8 encoded (with byte-order mark, so they open correctly in Excel).
- Rows in which only the first cell is filled (for example "Single-model baselines") are group labels.
- Numbers in square brackets in Tables 1 and 10 refer to the reference list of the manuscript.
- Abbreviations are defined in the table notes (Table_captions_and_notes.csv) and in the figure captions.
