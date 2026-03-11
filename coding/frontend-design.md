# Skill: Frontend Design

## Purpose
Create modern, responsive web pages and components from a description. Produces clean HTML, CSS, and JavaScript ready to deploy.

## Instructions
When asked to build a web page, component, or UI:

1. **Clarify the brief** — ask about:
   - Purpose (landing page, portfolio, form, dashboard, etc.)
   - Brand colours, fonts, and style preferences
   - Content to include (text, images, sections)
   - Target audience
   - Mobile-first or desktop-first

2. **Design approach:**
   - Use semantic HTML5 elements
   - Mobile-responsive by default (flexbox/grid, media queries)
   - Clean, modern aesthetic — generous whitespace, clear typography
   - Accessible (proper headings, alt text, contrast ratios, ARIA labels)
   - Fast-loading (minimal dependencies, inline CSS where practical)

3. **Tech stack (default):**
   - HTML5 + CSS3 + vanilla JavaScript
   - No frameworks unless requested
   - Google Fonts for typography
   - CSS custom properties for colours/theming
   - If a framework is requested, prefer Tailwind CSS

4. **Deliver:**
   - Complete, working HTML file (single file unless complex)
   - Comments explaining key sections
   - Instructions for customisation (where to change colours, text, images)

## Output Format
```html
<!DOCTYPE html>
<html lang="en">
<!-- Clean, well-structured, ready to open in a browser -->
</html>
```

## Style Guidelines
- Fonts: Use 2 max (one heading, one body)
- Colours: Create a palette from the brand colours provided (primary, secondary, accent, background, text)
- Spacing: Consistent padding/margins using a scale (0.5rem, 1rem, 1.5rem, 2rem, 3rem, 4rem)
- Buttons: Clear hover/focus states, adequate padding
- Images: Always include width/height or aspect-ratio, lazy loading
- Dark mode: Include if requested, use `prefers-color-scheme` media query

## Examples of What This Skill Handles
- Landing pages
- Portfolio sites
- Contact/enquiry forms
- Pricing tables
- Testimonial sections
- Navigation menus (responsive hamburger)
- Hero sections
- Card layouts
- Email signup forms
- Simple dashboards
