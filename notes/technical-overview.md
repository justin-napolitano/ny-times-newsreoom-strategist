---
slug: github-ny-times-newsreoom-strategist-note-technical-overview
id: github-ny-times-newsreoom-strategist-note-technical-overview
title: ny-times-newsreoom-strategist
repo: justin-napolitano/ny-times-newsreoom-strategist
githubUrl: https://github.com/justin-napolitano/ny-times-newsreoom-strategist
generatedAt: '2025-11-24T18:42:29.432Z'
source: github-auto
summary: >-
  This repo provides a LaTeX template for resumes, complete with build scripts
  to customize and compile stylish documents using XeLaTeX.
tags: []
seoPrimaryKeyword: ''
seoSecondaryKeywords: []
seoOptimized: false
topicFamily: null
topicFamilyConfidence: null
kind: note
entryLayout: note
showInProjects: false
showInNotes: true
showInWriting: false
showInLogs: false
---

This repo provides a LaTeX template for resumes, complete with build scripts to customize and compile stylish documents using XeLaTeX. 

### Key Components
- LaTeX template with flexible styles.
- Automated workflow using Python and Makefile.
- Dependency management via `pip`.

### Quick Start

1. **Clone the repo:**
   ```bash
   git clone https://github.com/justin-napolitano/ny-times-newsreoom-strategist.git
   cd ny-times-newsreoom-strategist
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Build your resume:**
   Use Makefile or the Python script:
   ```bash
   make clean
   make html
   ```
   or
   ```bash
   python python-build.py
   ```

### Gotchas
Make sure XeLaTeX and Python 3 are installed on your machine. Keep an eye on logs for any build issues.
