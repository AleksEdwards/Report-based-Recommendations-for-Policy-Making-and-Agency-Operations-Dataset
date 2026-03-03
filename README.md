
# PubRec-Bench: Report-Based Recommendation Generation Benchmark

## Dataset Summary

PubRec-Bench is the first benchmark dataset for report-based recommendation generation aimed at supporting policy-making and agency operations in public sector contexts.

The dataset consists of manually curated evidence\'96recommendation pairs extracted from official public reports across UK and US institutions.

The task is defined as:

> Given a piece of evidence extracted from an official report, generate a policy-focused recommendation that is consistent, actionable, and grounded in the evidence.

This dataset was introduced in:

**Edwards et al. (2026). Report-based Recommendations for Policy Making and Agency Operations: Dataset and LLM Evaluation.**\



## Dataset Structure

The dataset contains three sub-datasets:

- UK Care Homes reports
- US Children's Bureau reports
- NSPCC Serious Case Reviews

Each entry contains:

- `report_id`
- `evidence`
- `recommendation`
- `dataset_source`

Additionally, we provide:

- Human evaluation annotations (fluency, coherence, relevance, actionability)
- Zero-shot and one-shot evaluation settings



## Dataset Statistics

- 110 reports
- 493 recommendation pairs
- Domains: Child protection, adult social care, foster care, public agency review


## Intended Use

This dataset is intended for:

- Recommendation generation research
- Policy-oriented NLG tasks
- LLM evaluation in high-stakes domains
- Benchmarking automatic vs human evaluation metrics


## Limitations

- English only
- UK and US policy contexts only
- Limited size due to nature of serious case reviews


## Ethical Considerations

The dataset is based entirely on publicly available reports.
The goal is to support (not replace) subject matter experts in drafting policy recommendations.


## Citation

If you use PubRec-Bench in your research, please cite:

```bibtex
@inproceedings{edwards-etal-2026-pubrecbench,
  title = {Report-based Recommendations for Policy Making and Agency Operations: Dataset and {LLM} Evaluation},
  author = {Edwards, Aleksandra and
            Edwards, Thomas and
            Camacho-Collados, Jose and
            Preece, Alun},
  booktitle = {Proceedings of the Thirteenth International Conference on Language Resources and Evaluation (LREC 2026)},
  year = {2026},
  publisher = {European Language Resources Association (ELRA)}
}
\}}
