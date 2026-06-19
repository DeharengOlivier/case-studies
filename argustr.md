# Argustr

Multi-agent AI decision support for financial markets (stocks, FX, crypto, ETFs).
Product: https://argustr.com

## The problem
Most AI market tools hand you a black-box buy or sell signal. A serious investor cannot act on a number with no reasoning attached, and cannot audit it afterwards when it turns out wrong. The missing ingredient is not prediction, it is justification.

## What it does
Argustr produces structured, auditable reasoning rather than a bare signal. For a given asset it exposes the explicit assumptions it relied on, a conviction level, and a traceable logic path from the underlying data to the conclusion, so a human can follow each step and challenge it.

## How it is built
A set of specialised agents decompose the analysis, each owning one part of the work (gathering and normalising data, analysing factors, assembling a thesis), followed by a critic step that stress-tests the thesis before it is shown. Their outputs are composed into a single sourced report rather than a one-shot generation. An explicit assumptions ledger and output guardrails keep every claim attributable and the final answer auditable.

## Stack
Multi-agent LLM orchestration, Python, structured and schema-constrained model outputs, full-stack web delivery.

## Why it matters
The bet behind Argustr is that in finance, transparency drives adoption more than raw accuracy. A reasoning trail people can audit is what makes an AI tool usable in a domain where being wrong has a cost.
