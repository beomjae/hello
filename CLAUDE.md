# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple static HTML website project with Korean language content. The repository contains basic HTML pages for demonstration and learning purposes.

## File Structure

- `index.html` - Main page with JavaScript examples demonstrating array iteration methods (for loops, forEach, for...of)
- `1.html` - First sub-page (Korean: "첫번째 서브 페이지")
- `survey_main.html` - Survey page (Korean: "설문조사 메인 페이지")
- `test.txt`, `test2.txt`, `test3`, `test4`, `test5` - Empty test files from commit history

## Development

### Viewing the Site

Since this is a static HTML site with no build process, you can view it by:

1. Opening HTML files directly in a browser:
   ```bash
   # For file-based viewing
   open index.html  # macOS
   xdg-open index.html  # Linux
   ```

2. Using a local HTTP server (recommended for avoiding CORS issues):
   ```bash
   # Python 3
   python -m http.server 8000

   # Python 2
   python -m SimpleHTTPServer 8000

   # Node.js (if http-server is installed)
   npx http-server -p 8000
   ```
   Then visit `http://localhost:8000` in your browser.

### Commit Message Convention

Based on git history, commit messages are written in Korean and follow the pattern:
- Feature additions: `#<number> <feature name> <status>` (e.g., "#2 설문조사 추가작업완료")
- General changes: Descriptive message in Korean (e.g., "메인페이지 내용 변경")

## Code Characteristics

- **Language**: Korean is used for page content and commit messages
- **JavaScript Style**: Uses both ES5 (var, for loops) and ES6 (arrow functions, for...of) syntax in index.html
- **HTML Standard**: HTML5 with UTF-8 encoding and viewport meta tags for responsive design
