# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the landing page for **Iniciativa Grow's ISO 27001 consulting service** in Panama, hosted at `grc.iniciativagrow.com`. It is a single static HTML file (`grc_landing (2).html`) with no build system, dependencies, or tests.

## Architecture

- **Single-file static site**: All HTML, CSS, and JS live in one self-contained `.html` file
- **No build tools**: Open the file directly in a browser to preview; no bundler, preprocessor, or dev server
- **Language**: All user-facing content is in Spanish
- **CSS**: Uses CSS custom properties (`:root` vars) for theming — key colors are `--primary-dark`, `--primary-blue`, `--accent-teal`, `--accent-yellow`
- **Responsive**: Media queries at 900px and 600px breakpoints
- **External dependencies**: None — no frameworks, no CDN imports. Only external resources are images loaded from `iniciativagrow.com` and partner sites

## Key External Links

- Main CTA form: `https://share.deftform.com/kyVEeg`
- Free assessment tool (CalCu): `https://calcu.iniciativagrow.com`
- Parent site: `https://iniciativagrow.com`
- GRC platform partners: Vanta, Scrut
