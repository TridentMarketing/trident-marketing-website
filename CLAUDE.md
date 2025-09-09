# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a WordPress-based marketing website for Trident Marketing that has been exported as static files for GitHub Pages deployment. The site uses a combination of WordPress-generated HTML with Elementor page builder components.

## Architecture

**Static WordPress Export**: The codebase contains a static export of a WordPress site, including:
- `index.html` - Main page with embedded CSS/JS and WordPress structure
- `wp-content/` - WordPress themes, plugins, and uploaded content
- `wp-includes/` - WordPress core JavaScript libraries
- Font Awesome assets (fa-*.woff, fa-*.ttf files) for icons

**WordPress Stack**:
- **Theme**: Twenty Twenty-One theme with custom color overrides
- **Page Builder**: Elementor (v3.26.3) for layout management
- **Plugins**: Header Footer Elementor for site structure

**Deployment**: Configured for GitHub Pages static hosting

## Key Files

- `index.html` - Primary website content (large file ~30k lines with embedded styles/scripts)
- `README.md` - Comprehensive documentation covering deployment, customization, and features
- `_downloads.html` - Additional page content
- Font files in root directory for icon support

## Development Workflow

Since this is a static export from WordPress, direct HTML/CSS editing is the primary method for customization. The WordPress admin interface is not available in this static version.

**Making Changes**:
1. Edit `index.html` directly for content updates
2. Modify embedded CSS within `<style>` sections for styling changes
3. Update meta tags and SEO information in the HTML head
4. Deploy via git push to main branch (GitHub Pages auto-deploys)

**Key Customization Areas** (as documented in README.md):
- Colors: Update CSS gradient variables in embedded styles
- Content: Modify HTML sections for company information, services, team details
- Contact Information: Update business details, address, phone numbers

## No Build Process

This repository contains no build configuration files (package.json, webpack, etc.). All assets are pre-built and included directly. Changes are made by editing static files and pushing to GitHub.