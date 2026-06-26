# Gleam Duster

清辉拂过，尘埃无处可藏。

A static asset analyzer for web repositories. Crawls repos for unused
images, orphaned CSS, stale fonts, and dead-end links. Generates cleanup
reports with file-level granularity.

## How It Works
- Scheduled crawls across target repositories
- AST-based usage analysis for frontend assets
- Structured cleanup manifests committed as JSON reports

## Goal
Every kilobyte matters. Gleam Duster finds what you forgot to delete.

Written in Python. Runs on GitHub Actions hourly.
