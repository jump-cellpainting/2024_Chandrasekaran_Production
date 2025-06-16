# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Setup

```bash
# Environment setup
conda env create -f 0.visualize-orf-data/environment.yml
conda activate visualize-orf

# Initialize submodules
git submodule update --init --recursive

# Configure commit template for co-author attribution
git config --local commit.template .gitmessage
```

## Key Commands

```bash
# Run Jupyter notebooks for analysis
cd 0.visualize-orf-data && jupyter lab
```

## Architecture

**Main analysis directory:** `0.visualize-orf-data/`
- `utils.py` - Data loading utilities for S3/local access
- Analysis notebooks: metadata creation, UMAP plotting, negative control analysis
- Cell painting dataset with 13 experimental batches

**Git workflow:** Use `git commit` (without `-m`) for co-author attribution via template

## Ignore Patterns

- Completely ignore the folders `datasets/` and `jump-orf-data/` - these are submodules that should not be worried about