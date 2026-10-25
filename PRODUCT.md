# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

- Primary: AML and crypto transaction monitoring analysts performing an initial bounded review of Ethereum USDT activity.
- Secondary: quality control reviewers checking whether the analyst documented scope, evidence, reasoning, alternatives, gaps, and disposition consistently.
- Portfolio audience: recruiters and hiring teams evaluating Brandon Candela's AML judgment, crypto tracing approach, Python and JavaScript implementation, and attention to investigative limits.

The user roles above are inferred from the explicit redesign brief, existing product copy, and the repository's implemented workflow.

## Product Purpose

Trace Desk turns a bounded set of public USDT transfers into a reviewable investigation case. It helps an analyst collect or open evidence, inspect relationships and transfers, record an evidence-linked assessment, save a portable case file, and hand a snapshot to a QC reviewer.

Success means another person can understand what was reviewed, inspect the cited evidence, see the analyst's reasoning and limitations, and verify the documented conclusion without mistaking indicators for proof of wrongdoing.

## Positioning

The product combines bounded public-chain tracing with analyst reasoning, portable evidence, and a file-based QC handoff. It emphasizes reviewability and investigative limits rather than wallet attribution, automated guilt decisions, or opaque risk scores.

## Operating Context

- Start from the verified saved example, import a portable case file, or collect a limited live case from a public Ethereum node.
- Inspect the address graph, subject counterparties, candidate sequences, indicators, and exact transaction evidence.
- Record expected activity, observations, alternative explanations, missing evidence, next steps, disposition, and rationale.
- Pin evidence, complete a documentation checklist, export a case summary, and save a portable JSON case file.
- Submit a snapshot for file-based QC, add categorized findings, return it for correction, or document completed QC.

## Capabilities and Constraints

- Preserve exact token amounts, bounded query limits, current indicators, evidence IDs, graph behavior, notes, case import and export, QC history, tests, and GitHub Pages deployment.
- The browser UI is dependency-free JavaScript; Python verifies and prepares the saved example.
- Notes and QC work live in browser memory until a portable case file is saved.
- The prototype has no authenticated identities, permissions, separation-of-duties enforcement, durable server storage, tamperproof audit trail, wallet-owner attribution, sanctions screening, or automated suspicious-activity determination.
- Visual changes must not imply production controls that the product does not implement.

## Brand Commitments

- Product name: Trace Desk AML Workspace.
- Voice: precise, candid, evidence-led, and understandable to an entry-level analyst without talking down to experienced reviewers.
- Presentation: professional enterprise fintech software suitable for major banks, fintech companies, and technology firms; restrained rather than decorative.

## Evidence on Hand

- Verified saved case and raw node responses under `data/`.
- Investigation logic in Python and JavaScript with regression tests under `tests/`.
- Example report in `CASE_REPORT.md`.
- Public GitHub Pages deployment and repository documentation.
- No customer testimonials, production deployment claims, proprietary attribution data, or verified reviewer identities are available and none should be fabricated.

## Product Principles

1. Keep evidence, interpretation, and limitations visibly distinct.
2. Help analysts move from scope to evidence to assessment in a predictable sequence.
3. Keep the current case and filter state visible so users do not rely on memory.
4. Make QC review readable as a case narrative, while preserving the exact submitted snapshot.
5. Prefer honest, bounded claims over implied automation or compliance certainty.

## Accessibility & Inclusion

The application should support keyboard operation, visible focus, WCAG AA text contrast, redundant graph cues beyond color, readable mobile layouts, and clear language for analysts with different levels of blockchain experience.
