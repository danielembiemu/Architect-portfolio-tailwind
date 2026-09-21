# Architect-portfolio-tailwind


A brutalist-style multi-page portfolio built with HTML and Tailwind CSS, based on a provided wireframe and focused on precise layout matching using CSS Grid and Flexbox.

I used the @theme block to define two custom colors: deep-charcoal (a near-black used for text, backgrounds, and buttons) and bright-blue (used as an accent for contrast, mainly on hover states and interactive elements). Defining them as CSS variables inside @theme meant Tailwind automatically generated utility classes for them (bg-deep-charcoal, text-bright-blue, etc.), so I could use them anywhere in the project the same way I'd use any built-in Tailwind color — no extra setup needed per page. I applied them consistently across buttons, links, and hover states wherever the wireframe showed color contrast.

I used CSS Grid throughout the site, but the most challenging layout was the Home page's Methodology/Lab Archive/Dialogue section. It required nesting a grid inside a flex column, which itself sat inside another grid (the outer 2-column split between the project image and this content block). Getting the right column to correctly stack one full-width card on top of two smaller side-by-side cards — while keeping consistent spacing — took some trial and error, but it let me match the wireframe's layout precisely without resorting to position: absolute.
