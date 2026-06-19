# AGENTS.md — AWF Website

## Project

This repository contains the WordPress theme and companion plugin for AWF — ALLO WORK FORCE.

AWF is a Moroccan marketing and social media company positioned as a premium outsourced marketing workforce.

Primary tagline FR:
Votre force marketing externalisée.

Primary tagline EN:
Your outsourced marketing force.

## Brand Rules

Use AWF as the visible brand.
Use ALLO WORK FORCE in footer, legal areas, SEO context, and formal mentions.
Always clarify that AWF is a marketing workforce, not a recruitment or staffing company.

Tone:

* premium
* direct
* strategic
* execution-focused
* business-oriented

Avoid:

* generic agency clichés
* “boost your brand” language
* empty innovation buzzwords
* cheap social media agency tone
* recruitment/staffing vocabulary
* phone, headset, megaphone, rocket clichés

## Visual Direction

The site should feel like a premium marketing control room:

* dark interface
* modular cards
* signal lines
* subtle grid
* dashboard-inspired visuals
* clear conversion pipeline
* restrained motion

Colors:

* #070A12
* #0F172A
* #151D2F
* #F8FAFC
* #94A3B8
* #3B82F6
* #22D3EE
* #F59E0B

Typography:

* headings: Sora or Space Grotesk
* body: Inter
* labels/metrics: IBM Plex Mono or JetBrains Mono

## Technical Rules

Use:

* custom WordPress block theme
* Gutenberg templates and patterns
* theme.json design tokens
* lightweight companion plugin
* clean PHP
* progressive JavaScript only

Do not use:

* Elementor
* heavy multipurpose themes
* excessive plugins
* bloated animation libraries
* generic templates

## Performance

Target:

* Lighthouse 90+ mobile where realistic
* minimal CSS
* deferred JS
* responsive images
* compatible with LiteSpeed Cache
* no unnecessary dependencies

## Accessibility

Required:

* semantic landmarks
* one H1 per page
* keyboard navigation
* visible focus states
* sufficient contrast
* labels on forms
* respects prefers-reduced-motion

## Security

Never request, store, or expose:

* production credentials
* Hostinger credentials
* WordPress admin passwords
* API keys
* Meta/TikTok/Google tokens
* WhatsApp credentials

Develop on staging or locally only.

## Commit Quality

Before final response:

* summarize changed files
* mention checks run
* mention checks not possible
* list remaining TODOs
* avoid claiming success for untested items
