# Syllabus

| Department | Computer Science |
|---|---|
| **Program** | B.C.A. (Bachelor of Computer Applications) |
| **Course Code** | BCA-WT301 |
| **Course Name** | Web Technology |
| **L** | **T** | **P** | **C** |
| 3 | 0 | 0 | 3 |

---

## Pre-requisite:
Basic knowledge of Computer Fundamentals and Introduction to Programming.

---

## Course Objectives:
1. To introduce students to the fundamentals of the Internet and World Wide Web.
2. To enable students to design and develop static web pages using HTML.
3. To equip students with the skills to style web pages using CSS.
4. To familiarize students with the Bootstrap framework for responsive web design.
5. To develop the ability to build complete, well-structured, and visually appealing websites.

---

## Course Outcomes:
After completion of the course, the student will be able to:

1. **CO1:** Understand the basic concepts of the Internet, WWW, web browsers, web servers, and network protocols.
2. **CO2:** Create structured web pages using HTML tags, forms, tables, lists, multimedia elements, and hyperlinks.
3. **CO3:** Apply CSS techniques including selectors, box model, layouts, and animations to style and enhance web pages.
4. **CO4:** Develop responsive and mobile-friendly web pages using the Bootstrap framework including its grid system, components, and utilities.
5. **CO5:** Integrate HTML, CSS, and Bootstrap to design and develop complete, professional-quality static websites.

---

## CO-PO Mapping
*(Scale — 1: Low, 2: Medium, 3: High)*

| CO-PO Mapping | PO1 | PO2 | PO3 | PO4 | PO5 | PO6 | PO7 | PO8 | PO9 | PO10 | PO11 | PO12 | PSO1 | PSO2 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| CO1 | 3 | 2 | 1 | 1 | 2 | 1 | 1 | - | 2 | 2 | 1 | 2 | 3 | 2 |
| CO2 | 3 | 3 | 2 | 2 | 3 | 1 | 1 | - | 2 | 2 | 1 | 2 | 3 | 3 |
| CO3 | 3 | 3 | 2 | 2 | 3 | 1 | 1 | - | 2 | 2 | 1 | 2 | 3 | 3 |
| CO4 | 2 | 3 | 3 | 2 | 3 | 1 | 1 | - | 2 | 2 | 1 | 2 | 3 | 3 |
| CO5 | 3 | 3 | 3 | 3 | 3 | 2 | 1 | - | 3 | 3 | 2 | 3 | 3 | 3 |

---

## Unit 1 — Introduction to Internet and World Wide Web &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 08 Hours

- History and Evolution of the Internet; Concept of WWW, Web Browsers and Web Servers.
- Internet Protocols: TCP/IP, HTTP, HTTPS, FTP, SMTP; IP Addressing and Domain Name System (DNS).
- URL Structure, Types of Websites (Static vs Dynamic), Client-Server Architecture.
- Overview of Web Technologies: Front-End vs Back-End; Introduction to HTML, CSS, JavaScript.
- Web Hosting Concepts: Types of Hosting (Shared, VPS, Dedicated, Cloud); Domain Registration.
- Introduction to Web Standards and W3C; Overview of Search Engines and how they work.

**Practical Application:** Setting up a basic local development environment (VS Code / Notepad++), understanding browser developer tools (Inspect Element, Console).

---

## Unit 2 — HyperText Markup Language (HTML) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 08 Hours

- Introduction to HTML: Structure of an HTML Document, DOCTYPE, Head and Body sections.
- HTML Tags: Heading tags (h1–h6), Paragraph, Line Break, Horizontal Rule, Comments.
- Text Formatting Tags: Bold, Italic, Underline, Strong, Em, Sub, Sup, Blockquote, Pre.
- Links and Navigation: Anchor tag (`<a>`), Absolute vs Relative URLs, Target attribute, Email links.
- Images and Multimedia: `<img>`, `<audio>`, `<video>` tags and their attributes.
- Lists: Ordered List (`<ol>`), Unordered List (`<ul>`), Definition List (`<dl>`).
- Tables: `<table>`, `<tr>`, `<th>`, `<td>`, colspan, rowspan, table attributes.
- Forms: `<form>`, Input types (text, password, email, radio, checkbox, file, submit, reset), `<select>`, `<textarea>`, `<button>`, Form attributes (action, method).
- Semantic HTML5 Elements: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`.
- HTML5 New Features: `<canvas>`, `<progress>`, `<meter>`, data attributes, meta tags for SEO.

**Practical Application:** Creating a complete personal profile webpage using HTML with navigation, tables, forms, and multimedia.

---

## Unit 3 — Cascading Style Sheets (CSS) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 08 Hours

- Introduction to CSS: Types of CSS (Inline, Internal, External), CSS Syntax, Linking CSS to HTML.
- CSS Selectors: Universal, Element, Class, ID, Attribute, Pseudo-class (`:hover`, `:focus`, `:nth-child`), Pseudo-element (`::before`, `::after`).
- CSS Properties: Color, Background, Font (font-family, font-size, font-weight, font-style), Text properties (text-align, text-decoration, letter-spacing, line-height).
- Box Model: Content, Padding, Border, Margin; `box-sizing` property.
- CSS Display & Positioning: `display` (block, inline, inline-block, none), `position` (static, relative, absolute, fixed, sticky), `z-index`, `overflow`.
- CSS Flexbox: Flex Container and Flex Items, `justify-content`, `align-items`, `flex-wrap`, `flex-direction`.
- CSS Grid: Grid Container, Grid Template Columns/Rows, `gap`, `grid-area`.
- CSS Responsive Design: Media Queries (`@media`), Viewport Meta Tag, Fluid Layouts.
- CSS Transitions and Animations: `transition`, `@keyframes`, `animation` properties.
- CSS Variables (Custom Properties): Declaration with `--variable-name`, usage with `var()`.

**Practical Application:** Styling the HTML webpage created in Unit 2 using external CSS — applying layouts using Flexbox/Grid, adding hover effects, transitions, and making it responsive using Media Queries.

---

## Unit 4 — Bootstrap Framework &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 08 Hours

- Introduction to Bootstrap: What is Bootstrap, Features and Advantages, CDN vs Local Setup, Bootstrap 5 Overview.
- Bootstrap Grid System: Container, Row, Columns, Breakpoints (xs, sm, md, lg, xl, xxl), Offset Classes, Nesting Columns.
- Bootstrap Typography and Colors: Utility classes for headings, display text, text colors, background colors.
- Bootstrap Components:
  - **Navigation:** Navbar, Nav tabs, Breadcrumbs.
  - **Buttons:** Button classes, Button groups, Outline buttons.
  - **Cards:** Card structure, Card header/footer, Card deck/group.
  - **Forms:** Form controls, Form floating labels, Input groups, Form validation classes.
  - **Alerts and Badges:** Alert types, Dismissible alerts, Badges.
  - **Modal:** Modal dialog, Static backdrop, Modal sizes.
  - **Carousel:** Image slider, Controls, Indicators.
  - **Tables:** Striped, Bordered, Hoverable, Responsive tables.
- Bootstrap Utilities: Spacing (margin/padding), Display utilities, Flex utilities, Border, Shadow, Visibility.
- Bootstrap Icons: Including and using Bootstrap Icons in web pages.

**Practical Application:** Rebuilding the webpage from Unit 3 using Bootstrap 5 — implementing a responsive navbar, card-based layout, modal popup, and a contact form with Bootstrap form validation styles.

---

## Unit 5 — Integrated Web Development Project &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 08 Hours

- Review of HTML, CSS, and Bootstrap integration for complete website development.
- Planning a Website: Wireframing and Sitemap design, Understanding user requirements.
- Multi-page Website Development: Creating multiple linked HTML pages (Home, About, Services, Contact).
- Advanced Bootstrap Layouts: Combining Grid, Flexbox utilities, and custom CSS for complex page layouts.
- Working with Web Fonts: Google Fonts integration, Font Awesome Icons.
- Best Practices in Web Development: Clean and semantic HTML, CSS naming conventions (BEM), Code organization and folder structure.
- Website Accessibility (a11y): ARIA attributes, Alt text, Keyboard navigation.
- Introduction to SEO Basics: Meta tags, Heading hierarchy, Image optimization.
- Deployment Basics: Uploading a website to hosting server (FTP), Introduction to GitHub Pages for free hosting.

**Practical Application:** Developing a complete 4–5 page static website (e.g., College Club Website / Portfolio Website / Product Landing Page) using HTML5, CSS3, and Bootstrap 5 — incorporating Navbar, Hero section, Cards, Forms, Footer, and responsive design across all pages.

---

## Total Lecture Hours: 40 Hours

---

## Textbooks:
1. Ivan Bayross, *Web Enabled Commercial Application Development Using HTML, CSS, JavaScript & PHP*, BPB Publications.
2. Deitel & Deitel, *Internet & World Wide Web: How to Program*, Pearson Education.
3. Jon Duckett, *HTML and CSS: Design and Build Websites*, John Wiley & Sons.
4. Mark Otto & Jacob Thornton, *Bootstrap Official Documentation*, https://getbootstrap.com/docs/

---

## Reference Books:
1. Jennifer Niederst Robbins, *Learning Web Design*, O'Reilly Media.
2. Eric A. Meyer, *CSS: The Definitive Guide*, O'Reilly Media.
3. David Flanagan, *JavaScript: The Definitive Guide*, O'Reilly Media.
4. W3Schools Web Tutorials — https://www.w3schools.com
5. MDN Web Docs — https://developer.mozilla.org

---

## Evaluation Scheme:

| Types of Courses | Components of Evaluation | | % Weightage |
|---|---|---|---|
| Theory Courses with ESE | Continuous Internal Evaluation (CIE) | Mid Semester Examination (MSE) | 30% |
| | | Continuous Assessment (CA) | 20% |
| | End Semester Examination (ESE) | End Semester Examination (ESE) | 50% |

---

*Syllabus Designed for: B.C.A. Program — Web Technology (BCA-WT301)*
*Total Credits: 3 | Lecture Hours per Week: 3*
