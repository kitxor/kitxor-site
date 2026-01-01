# kitxor-site - Claude Context

## Project Overview

This is a minimal, lightweight tech blog hosted on GitHub Pages. The goal is to keep it **super simple** - pure HTML and CSS, no external dependencies, no JavaScript libraries, no frameworks.

## Design Philosophy

- **Lightweight:** No external libraries or dependencies
- **Pure:** Just HTML + CSS
- **Terminal aesthetic:** Monospace font, clean lines, simple borders
- **Light theme:** White background, black text, blue links
- **Compact:** Minimal whitespace, tight spacing

## Current Theme Style

- Font: `'Courier New', Courier, monospace`
- Background: `#ffffff` (white)
- Text: `#000000` (black)
- Links: `#0066cc` (blue)
- Accent: Black borders and lines
- Line height: `1.5` (compact)
- Spacing: Minimal margins and padding

## File Structure

```
kitxor-site/
├── index.html          # Homepage with blog post listing
├── posts/              # Individual blog posts
│   └── url-shortener.html
├── CNAME               # GitHub Pages domain
├── .gitignore
├── README.md
└── claude.md           # This file
```

## My Role

I help convert blog posts from plain text/markdown to HTML format while:

1. **Maintaining the theme:** All posts should match the terminal/monospace aesthetic
2. **Keeping it pure:** No external CSS files, everything inline
3. **Staying compact:** Minimal whitespace between elements
4. **Preserving content:** Never change the user's writing, only add HTML structure

## Blog Writing Philosophy

**Key principle:** Give the key points that build the knowledge tree, not the entire knowledge tree.

- **Compact and concise:** Cut all fat. Remove verbosity. Keep only what matters.
- **Core insights only:** Focus on the essential concepts that form nodes in the knowledge tree
- **No fluff:** No excessive explanations, redundant examples, or verbose descriptions
- **Clean formatting:** No emojis in tables or content (keep it professional)
- **Dense information:** Every sentence should add value

Think: transformer blog style - short paragraphs, gets to the point, no redundancy.

## Current Projects

**CDN Design Series (4-5 parts):**
- Part 1: Fundamentals & Why CDN (completed 2026-01-02)
- Part 2: Architecture + Caching Strategies (planned)
- Part 3: Cache Invalidation + Management (planned)
- Part 4: System Design Interview Guide (planned)
- Part 5: Real-World + Advanced (optional)

## Blog Post Template Structure

Each post should have:
- Back link to homepage
- Post header with title and metadata (date, tags)
- Content with proper semantic HTML (h2, h3, p, ul, ol, code, pre)
- Footer link back to all posts

## Code Sections

- Use `<code>` for inline code
- Use `<pre><code>` for code blocks
- Can link to GitHub repos instead of embedding large code snippets

## Adding New Posts

1. User writes the blog content (plain text or basic HTML)
2. I convert it to full HTML with the same theme/styling as existing posts
3. User adds the post listing to `index.html`

## Key Principles

- **No changes to user's content** - only add formatting
- **Consistency** - all posts should feel cohesive
- **Simplicity** - resist the urge to add features or complexity
- **Lightweight** - every byte counts, keep it minimal

## Notes

- This is hosted on GitHub Pages (free, public repo)
- X: https://x.com/kitxor
- GitHub: https://github.com/kitxor
