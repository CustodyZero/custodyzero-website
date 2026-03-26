---
title: "Type"
description: "A writing instrument for long-form writers and theorists. Local-first. LLM-assisted. Your words, your machine, your control."
---

## What Type is

Type is a writing instrument for long-form writers and theorists --- novelists, academics, essayists, researchers. It combines a rich document editor with an LLM-powered editorial assistant that reads your work and offers suggestions in the margin, like a human editor sitting beside you.

The metaphor is a typewriter page on a desk, with an editor's pencil in the margin. The author writes in ink. The assistant annotates in a different color. The page is warm paper, not a sterile white rectangle.

## What Type is not

Type is not a business document tool. No spreadsheets. No tables. No dashboards. No project management panels. If you need those, use Word or Google Docs.

Type is not a Markdown editor. It supports rich formatting --- bold, italic, font control, mathematical expressions --- because writers need these tools. Markdown is an import/export format, not the writing surface.

Type is not a code editor. One cursor. One selection. Formatting toolbar. The interface is for prose, not programs.

## Local-first

The project directory lives where you put it --- local disk, iCloud, Google Drive, OneDrive. Type writes files. The storage provider is your choice. No cloud account required. No telemetry. No data leaves your machine unless you explicitly configure an LLM provider.

The writer owns the data. The writer owns the workflow. The writer owns the output.

## The Assist

Type includes an editorial assistant powered by the LLM provider of your choice --- Anthropic, OpenAI, or a local model. The Assist reads your work and responds in three modes:

- **Advisory** --- margin annotations offering observations, references, and continuity notes
- **Proposed edits** --- tracked suggestions the writer approves, dismisses, or denies
- **Direct edits** --- changes made with explicit consent

The Assist maintains a per-project voice file capturing how the writer writes. Suggestions sound like the writer, not a generic editor.

The Assist is invoked explicitly. No background processing. Predictable cost control. The writer decides when the editor speaks.

## The surface

The writing surface is built on the physical metaphor of paper. The page is warm, slightly off-white. The desk beneath is muted stone. The margin line is drawn in faint pencil.

Three typefaces, each with a defined role:

- **Cormorant** --- display and headings. The voice of titles and structure.
- **Literata** --- the writing surface. Designed for long reading sessions on screens.
- **DM Mono** --- chrome and UI. Status bars, sidebars, labels. Never on the writing surface.

## Architecture

The document model is C++20 --- deterministic, with CRDT-ready identifiers designed for eventual collaborative editing. The UI is Avalonia (.NET 9), cross-platform desktop. The build system uses Factory for change control.

Documents are composed of paragraphs containing runs. Formatting is presentational, not semantic. Drafts are intentional milestones, not auto-saves. The semantic store is a custom C++ embedding model with HNSW + BM25 hybrid search, project-scoped and fully offline.

## Status

Type is in active development. It is not yet available for purchase.

## Licensing

When Type ships, it will be a perpetual license. You buy it. It is yours. Updates are optional. The product does not stop working if you stop paying.
