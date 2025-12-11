# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a GitHub profile README repository for izthiaka (Thiaka BADJI). It displays as the profile page on github.com/izthiaka.

## Structure

- `README.md` - The profile page content displayed on GitHub
- `devcard.svg` - Daily.dev developer card image, auto-updated by GitHub Actions
- `.github/workflows/main.yml` - Workflow that updates devcard.svg daily via dailydotdev/action-devcard

## Workflow

The DevCard workflow runs:
- On push to main branch
- Daily at midnight (cron)
- On manual trigger (workflow_dispatch)

## Commit Guidelines

Never add Claude/AI co-author attribution to commits in this repository.
