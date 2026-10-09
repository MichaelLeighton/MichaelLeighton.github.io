---
title: 'Planning a systematic literature search (week 3 of my PhD)'
date: 2026-10-09
permalink: /posts/2026/10/planning-a-systematic-search/
tags:
  - phd-journey
  - literature-review
  - methods
---

This week I went to a library workshop on searching academic databases. I came away with a much clearer idea of how to plan the literature search for my project, so I'm writing it up while it's fresh.

## Why a plan matters

A systematic review depends on a search that is reproducible and documented. If someone else can't rerun your search and get the same results, the review isn't really systematic. The workshop's main message was to design the search deliberately before typing anything into a database.

## Step 1: Identify the keywords

For my topic (sleep and Alzheimer's disease prediction using wearable data), the core concepts are:

- Alzheimer's disease / dementia
- sleep
- actigraphy / accelerometry / wearables
- prediction / risk
- multimodal AI

Each concept gets its own group of synonyms, because different papers use different terminology.

## Step 2: Choose where to search

Different databases cover different literature. Web of Science and Scopus are good general starting points, and the library's subject guides help you find ones specific to your field.

## Step 3: Build the search

The techniques that made the biggest difference to how I think about this:

- **Boolean connectors:** OR within a concept group, AND between groups.
- **Truncation:** `accelerom*` catches accelerometer, accelerometry and accelerometers.
- **Phrase searching:** quotation marks keep multi-word terms together, e.g. "sleep efficiency".
- **Proximity operators:** `sleep NEAR/3 fragmentation` finds the words within three of each other (Web of Science uses `NEAR/`, Scopus uses `W/`).

A first draft of my search looks something like this:

    (Alzheimer* OR dementia) AND (sleep) AND (actigraph* OR accelerom* OR wearable*) AND (predict* OR prognos* OR "risk")

It will need refining, but it's a starting point I can test and document.

## Step 4: Test it

A useful tip: pick a key paper you already know should appear, and check whether your search finds it. If it doesn't, the search needs work.

## Next steps

I'll refine the search, test it against a few known papers, and record every decision so the process stays reproducible. More updates as it develops.
