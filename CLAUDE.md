# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repo is

A single place that holds **two related artifacts**:

1. **Personal website** — Jekyll site published to GitHub Pages at https://blacksnail789521.github.io
2. **Resume** — LaTeX source + compiled PDF, served from the same site

Both surface the same identity, so personal info must stay in sync between them (see "Keeping info in sync" below).

## Resume workflow

Resume sources live under `resume/<YYYY.MM>/` (one folder per revision month, e.g. `resume/2026.05/`). `.gitignore` excludes everything in `resume/` **except** `resume/Ching Chang_Resume.pdf`, which is the public URL the website links to (`author.resume` in `_config.yml`).

When updating the resume:

1. Edit the `.tex` (or `.docx`) in the **current month's folder**. If a folder for this month doesn't exist yet, create `resume/<YYYY.MM>/` and start from the latest prior month's source.
2. Compile to PDF in that same folder.
3. **Copy the new PDF to `resume/Ching Chang_Resume.pdf`** (repo root of the resume folder) — this is the only resume file tracked by git, and it's what visitors download from the site.

## Keeping info in sync

Any change to personal info (title, affiliation, location, education dates, links, email, etc.) must land in **both**:

- The **latest resume** under `resume/<YYYY.MM>/` (and the copied `resume/Ching Chang_Resume.pdf`)
- The **website** — typically `_config.yml` (`author:` block) and `_pages/about.md`

After a sync edit, skim both to confirm no field drifted (e.g. job title in `_config.yml` matching the resume header).
