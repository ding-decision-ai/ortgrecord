# FeatureBench: Baseline and ORTG

This attachment contains 65 Baseline (Codex) / ORTG case comparisons.

- [Baseline and ORTG results](comparison.csv)
- [Machine-readable comparisons](index.json)
- [Model run records](model-replies/README.md)

Each case presents Baseline and ORTG side by side. FAIL_TO_PASS and PASS_TO_PASS are passed/total test counts. Original reports, model records, experiment conditions and costs are linked from each case.

The Meson case lists its original report counts separately from the comparable parent-test counts because its raw F2P denominators differ. The independent Sphinx C-domain case has different network conditions for the two configurations.

Actual run conditions are recorded in each `conditions.json`. Unknown values are null. Shared or overlapping cost entries must not be summed. `SHA256SUMS` lists file checksums.
