# portfolio
# Taylor Baker - Web Portfolio README

## 🎨 Design & Development Process

1. **Wireframing & Prototyping**
   - Began with **lo-fi wireframes**, followed by **hi-fi wireframes** and finally an **interactive prototype** outlining the visual layout and user flow.
   - [View my prototype design on Figma »](https://www.figma.com/design/VYsqnS8oKox6S7GsLnmbBm/baker_taylor_prototype?node-id=2553-56&t=s72VsDHvB7IHC0h0-1)

2. **Asset Preparation**
   - Exported, optimized, and organized all media, images, and SVG assets before development began.

3. **HTML Structure**
   - Created basic structure for all three pages with semantic section elements.
   - Built consistent **header and footer** across all pages.

4. **Navigation & Styling**
   - First navigation was custom coded (not using Bootstrap), but discarded due to performance issues.
   - Later iterations incorporated **Bootstrap SCSS customization**, with personalized colors, fonts, and buttons.

5. **Main Content**
   - Started with homepage content before moving to about and contact pages.
   - Alternated work sessions between different pages to avoid burnout and maintain perspective.

6. **Decorative SVG Challenge**
   - Spent 6+ hours troubleshooting positioning issues with layered SVGs.
   - Postponed finalizing home page and worked on remaining pages.

7. **Project Restart**
   - Removed ~90% of custom CSS to better integrate Bootstrap functionality.
   - Reworked layout/styling with Bootstrap classes where feasible.

8. **Final Touches**
   - Implemented custom navigation toggles for small screen sizes.
   - Applied **ARIA roles** and **schema markup** for accessibility and SEO.
   - Created responsive font sizing with CSS media queries and `clamp()`.
   - Rebuilt decorative banners and revised layered design elements.
   - Validated code and aligned project to **WCAG accessibility standards** and **color contrast guidelines**.

---

## 🧩 Challenges & Solutions

### 1. Layered SVG Positioning
- **Issue:** Decorative SVGs and overlapping images broke responsiveness and layout when resized.
- **Solution:** Spent hours testing multiple solutions, then restarted and removed these elements for a cleaner, more functional layout.
- **What I Learned:** Future implementations may require JavaScript or more advanced styling knowledge.

---

### 2. Bootstrap Font & Grid System Failures
- **Issue:** Bootstrap’s responsive classes for fonts and containers didn’t work.
- **Solution:** Applied custom CSS with `media queries` and `clamp()` sizing instead.
- **What I Learned:** Although cause is unknown, I learned to trust custom styling and problem-solve through research and instructor collaboration.

---

### 3. File Path Corruption Due to iCloud
- **Issue:** Ran out of disk space, leading to automatic migration of files to iCloud, which disrupted file paths.
- **Solution:** Relocated files and restored correct structure using GitHub Pages backup.
- **What I Learned:** Always back up work early, commit often, and keep a tidy, local file structure.

---

### 4. Social Media Icons
- **Issue:** None of Bootstrap’s built-in icon sets matched my visual style.
- **Solution:** Used custom SVG image files for social icons, which allowed for better responsiveness and control.
- **What I Learned:** SVGs are tricky, but using `<img>` tags instead of `<svg>` elements improved layout control.

---

## 💡 What I Learned

- **Design realistically for your skill level** – Don’t waste time implementing features beyond your knowledge base.
- **Adapt designs while staying aligned to standards** – Especially for accessibility and responsiveness.
- **Research competitor websites** – Many advanced features require JavaScript or PHP, which I now understand are future learning goals.
- **Start early, work consistently** – Even with regular work sessions, some sessions stretched up to 10 hours.
- **Lean on instructor feedback** – Transparent communication helped validate necessary design changes.

---

## 📚 Resources Used

### Accessibility
- [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)
- [Schema.org Markup Reference](https://schema.org/)
- [ARIA Roles Reference - MDN](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Reference/Roles)

### Image Optimization & Responsiveness
- [Responsive Breakpoints Generator](https://www.responsivebreakpoints.com/)
- [CSS Stats](https://cssstats.com/stats/?url=https%3A%2F%2Fbake0397.github.io%2Fmtm6201-midterm%2F)
- [Imgur](https://imgur.com/)
- [Squoosh App](https://squoosh.app/)

### Development Tools & Code References
- [Bootstrap 5.3 Documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
- [IanLunn Hover.css](https://github.com/IanLunn/Hover/blob/master/css/hover.css)
- [Animate.css CDN](https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css)
- [Animate.style](https://animate.style/)
- [CodePen - Scrolling Text Loop](https://codepen.io/geoffgraham/pen/yLzvXyL)
- [CSS Grid Generator](https://cssgrid-generator.netlify.app/)
- [Google Fonts - Libre Franklin](https://fonts.googleapis.com/css2?family=Libre+Franklin:ital,wght@0,100..900;1,100..900&display=swap)
- [Stack Overflow - Bootstrap Text Issues](https://stackoverflow.com/questions/19070463/using-bootstrap-but-text-not-responsive)
- [Stack Overflow - Background Color Position](https://stackoverflow.com/questions/8558502/background-position-for-background-color)
- [Web.dev CSS Animation Timing](https://web.dev/learn/css/animations#animation-timing-function)
- [SVG W3.org Specification](http://www.w3.org/2000/svg)
- [Make A README Generator](https://www.makeareadme.com/)

### Design Tools
- Adobe Illustrator
- Adobe Photoshop
- Canva

---

## 🖋️ Credits

All designs and layouts were created by **Taylor Baker**.  
All photography and visual assets used in this website are original and owned by **Taylor Baker**.

---

## 🔗 Figma Prototype

[Click here to view the interactive prototype](https://www.figma.com/design/VYsqnS8oKox6S7GsLnmbBm/baker_taylor_prototype?node-id=2553-56&t=s72VsDHvB7IHC0h0-1)

---