# CA3 — Bootstrap Responsive Design

## Overview
A single, fully responsive page built strictly with Bootstrap 5.3 utility and component classes — no custom CSS files and no inline `<style>` blocks (with two narrowly scoped, justified exceptions for inline sizing). The constraint was deliberate: it tests fluency with a component framework rather than hand-rolled CSS.

## What's Inside

### Q1 — Responsive Multi-Section Site
A three-section page:
- A `navbar` header with an active state, a disabled item, and a collapsing mobile menu
- A full-viewport-height hero section using Bootstrap's grid (`col` / `row`) that reflows from a two-column desktop layout to a stacked, centered mobile layout
- A card-based blog section (`card`, `shadow`, `badge`) that stacks on mobile
- A bottom contact form using Bootstrap's floating labels and form grid

The page also implements Bootstrap's built-in dark mode via the `data-bs-theme="dark"` attribute on key sections.

## Key Skills
- Bootstrap 5.3 grid system and responsive breakpoints
- Bootstrap components: navbar, cards, badges, forms, floating labels
- Framework-driven responsive design (mobile-first reflow without custom media queries)
- Native Bootstrap theming (`data-bs-theme`)

## What I Learned
Working strictly within a component framework's constraints is a different skill from writing CSS from scratch — it's about knowing the library's vocabulary well enough to compose a polished, responsive layout using almost nothing but class names, and understanding how a framework's grid system handles breakpoints under the hood.

## Folder Structure
```
CA3-Bootstrap-Responsive-Design/
└── Q1/
```
