# Replication materials

## Released package

The package contains the prepared inputs, execution scripts, fixed clarification
instructions and constitution, sanitized execution records, human coding records,
and source provenance. Release hashes describe the sanitized files; experimental
configuration hashes identify the original files.

## Results

The 180 responses contain 894 tagged items: 224 baseline, 221 syntactic,
224 semantic, and 225 pragmatic. Of the executions, 176 contain five items.
Counts are equal in 131 of 135 baseline–variant comparisons.

Two human specialists classified 100 selected questions by consensus:
76 requirements concerns and 24 operational details. These content categories
are not defect-detection rates. The final labels appear in the Final worksheet
of `reference/final_audit_documented.xlsx` and in `reference/final_classification.csv`.
Other coding worksheets document earlier stages, not independent final assessments.
The study does not report human inter-rater reliability or independent validation
of the intended defects across all 135 variants.

## Sampling

The sample contains 25 questions per condition from 77 executions and 39 parent
stories. Selection was intentional and considered different themes and datasets.
No reproducible item-level selection rule, theme quotas, or dataset quotas were
recorded. The sample does not support prevalence estimates for all 894 items.

## Provenance

`reference/story_provenance.csv` distinguishes source text, prepared baseline,
and variant. Source comparisons verify the file, line, and text of the 30 additions.
Preparation removed benefit clauses and sometimes normalized actors, potentially
introducing clarification needs in baselines.

For US_001, source text matches the baseline after benefit-clause removal.
Source links for the other 14 legacy stories were confirmed by the researcher;
`source_verification` distinguishes that confirmation from exact textual matches.
`reference/legacy_source_comparison.csv` preserves wording differences, and
`candidate_source_*` fields preserve the earlier source investigation.
The detailed historical editing sequence is not documented.

Source dataset copies and their hashes are in `reference/source_datasets/`.
Descriptive themes are in `reference/dataset_themes.md` and `theme_summary` in
`story_provenance.csv`; these are not reconstructed sampling quotas.
