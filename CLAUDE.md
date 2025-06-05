# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple single-page AI Positivity Quiz application for the AIP site. The entire application consists of a single `index.html` file containing HTML, CSS, and JavaScript.

## Architecture

- **Single-page application**: All code is contained in `index.html`
- **Styling**: Uses Blueprint CSS framework via CDN plus custom CSS variables for brand colors
- **JavaScript**: Vanilla JavaScript for quiz functionality and scoring
- **Brand colors**: Defined as CSS custom properties (--brand-blue, --brand-teal, --brand-white, --brand-dark)

## Development

Since this is a static HTML file, no build process is required. Simply open `index.html` in a browser to view and test changes.

## Quiz Functionality

- 3-question quiz about AI usage and attitudes
- Scoring: Each question has values 0-3, final score is percentage of maximum (9 points)
- Results display immediately after form submission