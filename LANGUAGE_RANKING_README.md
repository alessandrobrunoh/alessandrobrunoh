# GitHub Repository Language Ranking System

This repository includes an automated system that analyzes all GitHub repositories for the user `alessandrobrunoh` and creates a ranking based on programming language usage.

## 🚀 Features

- **Automated Analysis**: Scans all public repositories to identify primary programming languages
- **Smart Ranking**: Creates rankings based on estimated code volume and repository count
- **Visual Progress Bars**: Shows language distribution with ASCII progress bars
- **Auto-updating README**: Automatically updates the profile README with current statistics
- **Weekly Updates**: Runs automatically every Sunday via GitHub Actions
- **Manual Trigger**: Can be manually triggered when needed

## 📋 Components

### Core Files

1. **`repo_language_analyzer.py`** - Main Python script that performs the analysis
   - Analyzes repository data
   - Calculates language statistics and percentages
   - Generates both JSON and Markdown outputs
   - Excludes build/config files (HTML, CSS, Makefile, Dockerfile) from rankings

2. **`.github/workflows/update-language-rankings.yml`** - GitHub Actions workflow
   - Runs weekly on Sunday at 00:00 UTC
   - Can be triggered manually via workflow_dispatch
   - Automatically commits and pushes updates to README.md

3. **`language_ranking.json`** - Raw data output (auto-generated)
4. **`language_ranking.md`** - Formatted markdown report (auto-generated)

### Generated Outputs

The system generates several types of rankings:

- **Top Languages by Code Volume**: Shows languages ranked by estimated total bytes
- **Language Distribution**: ASCII visualization of language percentages
- **Repository Breakdown**: Lists which repositories use each language

## 🛠️ How It Works

1. **Data Collection**: The script uses manually curated repository data (to avoid API rate limits)
2. **Language Analysis**: Each repository's primary language is identified
3. **Estimation**: Code volume is estimated based on typical project sizes for each language
4. **Ranking Calculation**: Languages are ranked by total estimated bytes across all repositories
5. **Report Generation**: Creates both machine-readable (JSON) and human-readable (Markdown) outputs
6. **README Integration**: The ranking is automatically inserted into the profile README

## 🎯 Current Statistics

Based on 19 repositories:
- **Rust** is the dominant language (73.2% of total estimated code)
- **8 Rust projects** including web frameworks (Leptos, Dioxus), games, and APIs
- **Multiple web technologies** including Vue, TypeScript, and React
- **Data science projects** using Jupyter Notebooks
- **Various project types** from academic work to personal experiments

## 🔄 Automation Schedule

- **Weekly Updates**: Every Sunday at midnight UTC
- **Manual Triggers**: Can be run on-demand via GitHub Actions tab
- **Push Triggers**: Runs when the analyzer script is updated

## 📈 Future Enhancements

- Real-time GitHub API integration (when tokens are available)
- More sophisticated language detection
- Trending analysis over time
- Language ecosystem analysis (frameworks, libraries)
- Contribution activity correlation

## 🤝 Contributing

The system is designed to be self-maintaining, but improvements to the analyzer logic or visualization are welcome via pull requests.

---
*Last updated: Automatically maintained by GitHub Actions*