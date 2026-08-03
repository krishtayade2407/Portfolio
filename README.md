Personal Portfolio Website - Assignment 1
Name: Krish Tayade

Course: Full Stack Development

Design Rationale
This portfolio website was designed with a primary focus on simplicity, readability, and accessibility. I chose a clean blue and white color palette because it provides excellent text contrast (ensuring WCAG AA compliance) and delivers a professional, academic aesthetic. The HTML structure is built entirely on semantic tags—including <header>, <nav>, <main>, <section>, and <article>—to guarantee that the document outline is logical and easily interpreted by screen readers. The design uses CSS custom properties (:root) to manage this theme globally, making future color updates seamless.

Layout Technique Justification
For the structural layout, I chose to implement CSS Flexbox rather than CSS Grid. Flexbox is exceptionally well-suited for the one-dimensional alignments required in this project, such as evenly spacing the navigation links and vertically centering the header content. For the project and education sections, using Flexbox combined with flex-wrap: wrap provided an efficient way to create a responsive card system. It allows the cards to naturally flow onto the next line on smaller screens, making it incredibly easy to manage the tablet (768px) and mobile (480px) breakpoints without writing overly complex CSS rules.

Known Limitations
Because this foundational assignment strictly utilizes only HTML5 and CSS3, the contact form is currently static; it looks fully functional but does not yet process, validate, or submit user data. Additionally, interactive elements are strictly limited to basic CSS hover states and transitions. These limitations will be resolved in future assignments once JavaScript and a Node.js/Express backend are integrated.
