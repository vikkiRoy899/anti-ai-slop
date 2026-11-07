# Design System

## Goal
Create a distinctive, premium, non-generic UI. Avoid anything that looks like typical AI-generated design.

## Design References
- Primary inspiration: Linear.app + Vercel
- Secondary: Raycast, Arc browser, Stripe
- Avoid: Generic SaaS templates, purple gradients, Inter font, basic card grids

## Typography
- Headings: **Satoshi** or **General Sans** (or Clash Display for more personality)
- Body: **Inter** only if necessary, prefer **Satoshi** or **Geist**
- Never use: Roboto, Arial, system-ui as primary fonts
- Strong hierarchy: Big bold headings, good line-height, clear weight contrast

## Color Palette
- Use a unique, limited palette (max 5-6 colors)
- Prefer muted + one strong accent
- Avoid default Tailwind indigo/violet/purple combos
- Dark mode should feel rich, not just pure black

## Layout & Spacing
- Avoid perfect 3-column feature grids
- Prefer asymmetric or interesting layouts
- Generous but intentional whitespace
- Sections should not feel repetitive

## Components Style
- Cards: subtle borders or soft shadows, not heavy glassmorphism
- Buttons: clear hierarchy (primary solid, secondary ghost/outline)
- Avoid excessive rounded corners + heavy shadows combo
- Icons: prefer Lucide or custom, consistent stroke width

## Forbidden (AI Slop Patterns)
- Purple/blue gradients on hero
- "Trusted by" logo clouds with low opacity
- Generic 3-column feature cards with icons on top
- Inter + indigo everywhere
- Overuse of glassmorphism
- Perfect centering of everything
- Too many testimonials in a row

## Motion
- Subtle and meaningful micro-interactions
- Prefer CSS transitions over heavy animation libraries unless needed
