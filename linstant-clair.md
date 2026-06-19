# L'Instant Clair

A French news platform designed to be run end to end by AI.
Product: https://linstantclair.com

## The problem
The economics of online media push toward volume and opacity. Readers rarely know how a story was produced or what it is based on. I wanted to test the opposite, a newsroom that is AI-augmented and radically transparent about its own method.

## What it does
Language models analyse and enrich each story through pipelines that pull in sources and context, and a human layer adds methodology and editorial judgment. Each story carries a transparent, per-story account of how it was produced.

## How it is built
A full-stack web product on top of LLM analysis pipelines. Articles flow through stages (sourcing, analysis and enrichment, structuring) with the model output captured as structured data so it can drive both the article and an interactive data layer for readers. The human editorial pass sits on top of the automated pipeline rather than replacing it.

## Stack
Full-stack web (front end plus an API), LLM analysis pipelines, structured content storage.

## Why it matters
The objective is to rethink media economics with AI-augmented, transparent journalism instead of opaque content farms, and to show that automation and editorial trust are not mutually exclusive.
