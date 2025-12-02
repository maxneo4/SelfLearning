# Change: Add Programming Course Structure

## Why

The SelfLearning project needs a structured, navigable course format for GitHub Pages that organizes programming lessons with markdown-based content pages, examples, and clear navigation. Currently, the project has scattered content in README.md and sample files without a cohesive course structure.

## What Changes

- Add markdown-based course content system with main index page
- Create course navigation structure linking main page to topic pages
- Implement example linking system to connect lessons with code samples
- Support Mermaid diagrams in course content (if GitHub Pages supports it)
- Establish HTML as the first course topic with dedicated content pages
- Include basic JavaScript content for adding interactivity to HTML pages
- Define content organization conventions (directory structure, file naming)

## Impact

- **Affected specs**: `course-content` (new capability)
- **Affected code**:
  - New markdown files for course pages (index.md, HTML topic pages, JavaScript basics page)
  - Potential Jekyll/GitHub Pages configuration (_config.yml)
  - Sample files organization in Samples/ directory
  - README.md may need updates to reference new course structure
