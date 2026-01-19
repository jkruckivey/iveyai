# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for AI learning resources at Ivey Business School. It provides a curated, interactive interface to help users find AI learning materials based on their experience level, specific tasks, or preferred learning format.

## Architecture

The project consists of a single HTML file (`index`) containing:
- Inline CSS styles using a design system based on Geist font and neutral color palette
- Vanilla JavaScript for interactive panel navigation
- No build process, dependencies, or external frameworks

## Development

To develop locally, simply open the `index` file in a browser. No server or build step required.

## Design Patterns

- **Color scheme**: Neutral grays (#171717, #525252, #737373, #a3a3a3) with teal accents (#bfe5e7, #0d9488) and Ivey green (#00563F)
- **Interactive states**: `.active` classes toggle visibility of panels and button states
- **Navigation flow**: Entry buttons → Goal panels → Question items → Resource panels (with back navigation)
