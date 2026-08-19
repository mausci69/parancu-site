# ParancU

ParancU is a local-first evidence retrieval application for user-provided documents.

It is designed to retrieve and expose answer-bearing passages rather than hide retrieval behind a generated answer. ParancU combines multilingual E5 embeddings with lexical and anchor evidence, while keeping retrieved source passages, guiding questions, summaries, and scores inspectable.

## App Store

ParancU 0.1.0 is available on the Apple App Store for iOS 17 or later.

[View ParancU on the Apple App Store](https://apps.apple.com/it/app/parancu/id6788739843)

## Project materials

* [ParancU v1.1 White Paper](parancu_v1_1_white_paper.pdf)
* [ParancU Pitch](parancu_pitch.pdf)
* [ParancU Instructions](parancu_instructions.pdf)
* [Demo Script and Test Queries](parancu_demo_script_and_test_queries.pdf)

## Website

[maurizioscibilia.com](https://www.maurizioscibilia.com/)

This repository also contains the website, support page, and privacy page used for ParancU.

## Current architecture

ParancU currently uses:

* local multilingual E5-small embeddings;
* semantic plus lexical/anchor score fusion;
* inspectable Top-5 source evidence;
* OCR-assisted ingestion from camera or images;
* a constrained OpenAI API step during corpus preparation to generate summaries and guiding questions;
* local corpus persistence, query embedding, scoring, ranking, and evidence inspection after preparation.

## Evaluation

The current white paper reports local Top-5 evidence-containment results of:

* 85% for Question Answering;
* 82% for Sicilia Normanna;
* 78% for Multiple Sclerosis.

These are benchmark-specific descriptive results rather than universal performance claims.

## Author

Maurizio Scibilia
AI Engineer | Retrieval, Evaluation & Applied AI Systems

