# Saved-table evaluator report

All numbers below and figures are generated from saved CSVs. Research and world targets stay separate; smoke examples are not efficacy estimates.

| Endpoint | Policies | PASS | FAIL | INSUFFICIENT |
| --- | ---: | ---: | ---: | ---: |
| research / latent_effect | 11 | 11 | 0 | 0 |
| world / infrastructure | 13 | 13 | 0 | 0 |
| world / release_latency | 13 | 5 | 8 | 0 |

| Diagnostic outcome | Rows |
| --- | ---: |
| alarm | 51 |
| late_after_recovery | 26 |
| miss | 88 |
| not_supported_by_generator | 44 |
| quiet | 554 |
| success | 38 |
| unverifiable_target | 13 |

Final inputs remain sealed: the new mixture audit does not replace the governing per-family gate. Tied/saturated-score failures, missing targets, premature alarms, capped misses and abstentions are retained. No validation retuning occurred.

World release attribution is an offline same-exogenous paired completion-statistic target, not an observed online counterfactual. Infrastructure targets and policies are distinct. Completion latency alone can miss OOM/drop harm.

See raw generator-specific results, `validation_by_null_family.csv`, `abstentions.csv`, and `fit_diagnostics.csv`. Performance scopes remain separate: update wall time, traced allocations, engine, HTTP/API, VM renderer and attempted real browser execution.

Browser status: UNVERIFIED. Browser failure is not replaced by a VM FPS claim.
