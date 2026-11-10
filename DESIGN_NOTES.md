# Swapdesk landing page: design choices

**Concept.** A store that sells tested phones and laptops and lets customers swap old devices. The look is clean and trustworthy, like a well-run repair bench.

**Colour.** Deep ink blue for the header and footer, teal for the hero, a pale grey-blue behind the products, and one amber accent used only for buttons so the "Shop Now" action is always the most visible thing.

**Typography.** Sora for headings (firm, slightly technical) and Public Sans for body text (easy to read at small sizes). Headline size uses `clamp()` so it scales smoothly from phone to desktop.

**Layout and responsiveness.** Built mobile-first. Products show in 1 column on phones, 2 on tablets (700px+) and 4 on desktops (1000px+) using CSS Grid. The nav collapses into a hamburger menu on small screens, done with a hidden checkbox so no JavaScript is needed. The hero phone illustration is CSS-only and hidden on small screens to keep the first view focused.

**Product cards.** Equal-height cards with a fixed 4:3 image ratio, so buttons line up in every row. Descriptions are one line to keep scanning quick.

**Accessibility.** Visible keyboard focus, alt text on images, readable contrast, and reduced-motion support.

**Libraries.** Only Google Fonts. No CSS framework is used.
