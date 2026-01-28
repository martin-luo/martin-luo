# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a GitHub Profile README repository (`martin-luo/martin-luo`). The README.md in this repo displays on the GitHub profile page at github.com/martin-luo.

## Structure

- `README.md` - The profile README displayed on GitHub (main content to edit)
- `.github/workflows/snake.yml` - GitHub Action that generates the contribution snake animation every 6 hours and on push to main

## GitHub Action

The snake workflow generates SVG animations from the contribution graph and pushes them to the `output` branch. The generated files are:
- `github-contribution-grid-snake.svg` (light mode)
- `github-contribution-grid-snake-dark.svg` (dark mode)

These are referenced in the README via raw.githubusercontent.com URLs.

## Working with This Repo

When editing the README:
- Use `<picture>` elements with `<source>` tags for dark/light mode support
- Stats cards use github-readme-stats.vercel.app
- Activity graph uses github-readme-activity-graph.vercel.app
- Keep personal/company information private
