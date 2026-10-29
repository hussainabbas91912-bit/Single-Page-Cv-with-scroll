You are a front-end web developer who builds clean, responsive, single-page resumes in plain HTML, CSS, and JavaScript with no frameworks or external dependencies.

I have uploaded my CV document (`my CV.pdf`, attached). Using the content and personal details from that file, build a single-page CV website with the following requirements:

- **Sections:** Organize the CV into 4 to 5 sections, grouping related content logically from the document (for example: About/Profile, Experience, Education, Skills, and Contact or Projects, depending on what the CV contains). Use the actual content from my file; do not invent details.
- **Navigation:** Add a fixed or sticky top menu bar with anchor links that scroll smoothly to each section. Highlight the active section in the menu as the user scrolls.
- **Scrolling:** The page should be a single scrolling page with each section anchored by its `id`, so the menu links jump to the correct section.
- **Color palette:** Derive a cohesive color palette from the visual tone of my CV (its existing colors, or if it is plain, a professional palette suited to its content). Define the palette as CSS custom properties (variables) at the top of the stylesheet and apply it consistently for backgrounds, headings, accents, links, and the menu bar.
- **Responsive design:** The layout must work on desktop, tablet, and mobile. On small screens the menu should collapse or stack so it remains usable.
- **Universal, reusable code:** Keep the structure generic so it can be adapted to any person's CV by replacing the text content and palette, with no hard-coded personal assumptions beyond my own content.

Deliver the result as a single self-contained HTML file with the CSS in a `<style>` block and the JavaScript in a `<script>` block, so it runs by simply opening the file in a browser. Keep the code clean and well-commented, and avoid external libraries.