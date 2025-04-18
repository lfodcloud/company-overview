# Architecture Overview

## Overview

This repository outlines the high-level architecture for the Live Free or Die Cloud Solutions suite of products. It focuses on lightweight, scalable tools that avoid dependencies on heavy frameworks or mobile apps.

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript (Vanilla or lightweight libraries)
- **Backend**: Ruby on Rails, Sinatra, or Node.js (minimal API-first design)
- **Database**: PostgreSQL or SQLite (depending on tool size)
- **CI/CD**: GitHub Actions, Docker
- **Hosting**: Heroku, DigitalOcean, or lightweight VPS

## Microtools Breakdown

Each tool (SchedLink, TipLink, QuickInvoice, etc.) is:
- A self-contained web app or API
- Built for fast deployment
- Designed to be embeddable via link or QR code

## Design Principles

- Text-first, no-app experience
- Works over SMS and mobile web
- Simple interfaces and flows
- Easily white-labeled by vendors
