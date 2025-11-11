# AI PR Review

This is my final year project for automated PR reviewing using Python (FastAPI), GPT API, and GitHub Actions.

## Overview
This project integrates OpenAI GPT models to automatically review pull requests, summarize code changes, and generate useful feedback directly in GitHub.

## Technologies Used
- **Backend:** Python (FastAPI)
- **AI Model:** GPT-4 / Claude
- **CI/CD:** GitHub Actions
- **Version Control:** Git & GitHub

## How It Works
1. Developer opens a Pull Request.
2. GitHub Action triggers and sends PR data to GPT API.
3. GPT reviews and adds comments or summaries to the PR automatically.

## Setup
- Add your **OpenAI API key** as a secret (`OPENAI_API_KEY`) in your repo.
- Add your **GitHub Token** as a secret (`GITHUB_TOKEN`) in your repo (auto-provided).
- The workflow file: `.github/workflows/openai-pr-reviewer.yml`

## Credits
Based on the open-source project by [x86nick/openai-pr-reviewer](https://github.com/x86nick/openai-pr-reviewer).

# Testing AI PR Reviewer Workflow
