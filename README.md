# WEDE_Part1
Part1_Submission
# WEDE_Part2
Explanation of Fixes:
Navigation Menu (Point 1): Created a <nav> with HTML links (<a href="#home">, etc.) that function as anchor links within this single page to simulate smooth navigation. For a full multi-page set, duplicate the <header> and <nav> in separate files (e.g., about.html with href="index.html#home" for back links). This ensures links work across pages when implemented.

Base Style (2.2): Included a CSS reset and base styles (font-family, size, colors, background) applied to body for site-wide consistency.

Typography Styles (2.3): Applied font-family, font-size, font-weight, line-height, and letter-spacing to headings and paragraphs. Used a simple scale for harmony.

Layout Structure (2.4): Used Flexbox for header/nav (flex-direction, justify-content, align-items). Used CSS Grid for main content (grid-template-areas, grid-template-columns) to create a desktop layout with hero, content, sidebar, and footer. Clear and navigable.

Visual Styles (2.5): Added color, background-color, border, box-shadow to elements. Used pseudo-classes (:hover, :focus, :active) on links and buttons for interactivity (e.g., color changes, underlines).

Responsive Design (3.1): Defined breakpoints (desktop, tablet, mobile) with media queries. On larger screens: multi-column grid. On smaller: single-column, stacked nav/content, adjusted font sizes and padding. Navigation modifies to vertical on mobile/tablet.
