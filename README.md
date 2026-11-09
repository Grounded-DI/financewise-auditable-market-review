# FinanceWise — Auditable Market Review

A source-bounded comparative analysis of FinanceWise and the J.P. Morgan 2026 Mid-Year Outlook, focused on evidence control, horizon-specific conditions, corrections, lineage, and reproducible financial research.

## Overview

This repository contains a 23-page comparative report published by Grounded DI LLC on August 3, 2026. The report examines how FinanceWise is framed as a market-review and research-control layer and compares that framing with the public J.P. Morgan mid-year outlook.

The report is the public artifact. The underlying FinanceWise market outlook is not published here.

## What the Report Covers

The analysis compares:

- scope and intended use;
- evidence and source control;
- horizon structure and condition handling;
- correction and lineage practices;
- auditability and reproducibility; and
- possible portfolio-review context.

It is a comparative architecture and evidence-control analysis, not a performance study.

## Executable FinanceWise Replay Evidence

[FinanceWise transaction-to-covenant replay — October 19, 2026](https://github.com/Grounded-DI/grounded-di-replay-certificate-registry/tree/main/benchmarks/2026-10-19-financewise-transaction-covenant-replay) is a separate, public, runnable-evidence record for a controlled financial workflow. Its documented results include:

- **Two canonical executions** with identical outputs across **five recorded artifact hashes**.
- **15 of 15 recorded controls passed:** 14 mutated-input pipeline executions and one mutated-intermediate downstream execution.
- A **separately implemented internal evaluator** recalculated the source-bound financial values and decision state without importing the primary stage logic.
- Canonical synthetic cash of **128,000** and current liabilities of **32,000** yield a ratio of **4.0**, exceeding the recorded **1.5** covenant threshold. Nevertheless, the final disposition is **`REVIEW_REQUIRED`** because unresolved record-level evidence remains.

**Why this matters:** a favorable financial calculation is not the same as an authorized decision. The trace preserves the relationship among inputs, governing rules, arithmetic, exceptions, and the final state. [Read the replay report](https://github.com/Grounded-DI/grounded-di-replay-certificate-registry/tree/main/benchmarks/2026-10-19-financewise-transaction-covenant-replay/REPORT.md) or [inspect its recorded result](https://github.com/Grounded-DI/grounded-di-replay-certificate-registry/tree/main/benchmarks/2026-10-19-financewise-transaction-covenant-replay/FINAL_RESULT.json).

The covenant benchmark is a bounded synthetic workflow, **not** an execution of the proprietary FWO-01–FWO-15 formula suite. It complements the institutional market-review comparison in this repository.

## Evidence and Provenance

- [FinanceWise vs. J.P. Morgan 2026 Mid-Year Outlook — Comparative Analysis](FinanceWise_vs_JPMorgan_2026_MidYear_Outlook_Comparative_Analysis.pdf)
- [Publication commit — August 3, 2026](https://github.com/Grounded-DI/financewise-auditable-market-review/commit/3911e8e3c07f745394a3d4e453f2531fac74a65b)

The repository contains the PDF and this README. No source code, benchmark harness, or standalone replay verifier is included.

## Status and Scope

**Status: PUBLIC COMPARATIVE ANALYSIS.** The report makes no claim of predictive superiority or investment performance. It does not reproduce the J.P. Morgan report, publish the underlying FinanceWise market outlook, issue investment advice, provide allocation guidance, or give transaction instructions.

The report's conclusions should be read within the sources and comparison defined in the document. They do not establish a live market forecast or a recommendation.

No open-source license file is present in this repository.

## Evaluation and Collaboration

Finance, research, and governance teams evaluating auditable market-review workflows may use the report as a discussion and proof-of-concept starting point. Grounded DI collaboration, integration, and licensing inquiries: [Grounded DI on GitHub](https://github.com/Grounded-DI).
