# CLAUDE.md

## Repository Purpose

This repository is an auto-organized collection of Obsidian plugins that integrate AI and LLM capabilities. It serves as a reference list for discovering plugins that bring AI-powered features to Obsidian vaults.

## Content

The README contains:
- Quick stats (total plugins, combined stars, category count)
- Most popular plugins by stars
- Table of contents with category links and star counts
- Plugins organized into 17 categories based on GitHub metadata
- Each plugin entry includes GitHub stars, repo link, Obsidian "Add Plugin" link, and description

## Organization

Plugins are auto-categorized based on:
- GitHub repository topics
- Repository description keywords
- Manual overrides for repos with poor metadata

Categories are sorted by total combined stars.

## Maintenance

To regenerate the README:
1. The categorization script is in `/tmp/categorize_repos_v2.py` (or recreate it)
2. Pull fresh GitHub metadata using `gh api`
3. Run the categorization script to regenerate

When adding new plugins manually:
1. Add to the appropriate category section (sorted by stars)
2. Include all three badges:
   - GitHub stars: `[![GitHub stars](https://img.shields.io/github/stars/owner/repo?style=flat-square)](https://github.com/owner/repo)`
   - GitHub repo: `[![GitHub](https://img.shields.io/badge/GitHub-owner%2Frepo-181717?logo=github)](https://github.com/owner/repo)`
   - Obsidian plugin: `[![Add Plugin](https://img.shields.io/badge/Obsidian-Add_Plugin-7c3aed?logo=obsidian)](https://obsidian.md/plugins?id=plugin-id)`
3. Add description and metadata line
4. Use `---` as a separator between plugins

## Note

This list is auto-organized based on GitHub metadata and has not been manually reviewed for accuracy or quality. Some plugins may be deprecated, unmaintained, or miscategorized.
