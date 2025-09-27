<!--RESOURCES.html-->
Line 1: <!DOCTYPE html> → Declares the document type as HTML5.
Line 2: <html lang="en"> → Opens the HTML document, sets language to English.
Line 3: <head> → Starts the head section (metadata, styles, etc.).
Line 4: <meta charset="UTF-8" /> → Sets character encoding to UTF-8.
Line 5: <meta name="viewport" content="width=device-width, initial-scale=1.0" /> → Ensures page scales correctly on mobile devices.
Line 6: <meta name="description" content="This is the Resources Page" /> → Provides a short description for search engines.
Line 7: <link rel="stylesheet" href="RESOURCES.css" /> → Links the external CSS file.
Line 8: <link rel="icon" type="image/x-icon" href="images/dog.png" /> → Sets favicon image.
Line 9: <title>Resources Page</title> → Title of the page (shown in browser tab).
Line 10: </head> → Ends head section.
Line 11: <body> → Opens the body of the document.
Line 12: <nav id="navbar"> → Creates navigation bar with id "navbar".
Line 13–19: Series of <a> tags inside <nav> → Navigation links to HOME, member pages, RESOURCES, FEEDBACK.
Line 20: </nav> → Closes navigation bar.
Line 21: <div class="sidebar"> → Sidebar container for additional navigation.
Line 22–47: <ul> list of sidebar items → Each <li> contains a link with optional icon, text label (Resources, Ee Jie, Yew Zhian, Dinash, Bottom).
Line 48: </div> → Closes sidebar.
Line 49: <h1>Learning Resources</h1> → Main heading of the page.
Line 50: <img class="resources" src="images/resources.webp" /> → Displays resources image with class resources.
Line 51: <br /> → Line break.
Line 52: <main> → Main content section.
Line 53–57: <section> → Intro paragraph explaining purpose of the page.
Line 58: <br /> → Line break.
Line 59: <section id="#platforms"> → Section for platforms (note: id="#platforms" has extra #, should be id="platforms").
Line 60: <h2>Platforms</h2> → Subheading.
Line 61: <br /> → Line break.
Line 62: <p>FreeCodeCamp</p> → Text content listing platform.
Line 63: </section> → Closes platforms section.
Line 64–66: Breaks and horizontal rule <hr />.
Line 67: <section id="#tools"> → Section for tools (same id mistake with #).
Line 68: <h2>Tools</h2> → Subheading.
Line 69: </section> → Closes tools section.
Line 70–72: Breaks and <hr />.
Line 73: <section id="#courses"> → Section for courses.
Line 74: <h2>Courses</h2> → Subheading.
Line 75–81: Paragraph with links → freeCodeCamp, CodeAcademy, YouTube videos.
Line 82: </section> → Closes courses section.
Line 83: </main> → Ends main content.
Line 84: <footer> → Footer section begins.
Line 85–87: Breaks and <hr />.
Line 88: <h2 id="bottom">References</h2> → Footer heading with id for sidebar link.
Line 89–90: Breaks.
Line 91: <p>&copy;2025 PHUA YEW ZHIAN. All Rights Reserved</p> → Copyright notice.
Line 92–97: Footer paragraph → References image/video sources, contact email.
Line 98: </footer> → Ends footer.
Line 99: </body> → Closes body.
Line 100: </html> → Ends HTML document.

/*RESOURCES.css*/
Line 1–6: * { ... } → Universal reset: removes margin/padding, sets box-sizing, font, smooth scrolling, and letter spacing.
Line 7–13: body { ... } → Page background with fixed image, padding, and text justification.
Line 14–24: .sidebar { ... } → Fixed vertical sidebar on the left, collapsible width.
Line 25–27: .sidebar:hover { ... } → Expands sidebar width when hovered.
Line 28–31: .sidebar ul { ... } → Removes default list styling for sidebar.
Line 32–34: h2 { ... } → Adds scroll margin for smooth anchor navigation.
Line 35–43: .sidebar ul li a { ... } → Styles sidebar links (flexbox, padding, colors, transitions).
Line 44–52: .sidebar ul li a::before { ... } → Creates hover highlight bar effect on left.
Line 53–55: .sidebar ul li:hover a::before { ... } → Expands highlight bar on hover.
Line 56–61: .sidebar ul li a .icon { ... } → Styles icons inside sidebar links.
Line 62–66: .sidebar ul li a .text { ... } → Styles text labels inside sidebar links.
Line 67–71: nav, main, footer, h1 { ... } → Adds left margin/padding to shift content away from sidebar.
Line 72–80: #navbar { ... } → Styles top navigation bar: background, flexbox layout, centered links.
Line 81–85: #navbar a { ... } → Styles nav links (spacing, color, padding).
Line 86–88: #navbar a:hover { ... } → Nav links turn orange on hover.
Line 89–99: h1, h2, h3 { ... } → Adds black text with white outline using text-shadow.
Line 100–102: h4 { ... } → Styles h4 headings with burlywood color.
Line 103–106: footer { ... } → White text, left aligned.
Line 107–109: h1 { ... } → Adds top padding.
Line 110–112: h1, h2, h3, h4 { ... } → Aligns all headings left.
Line 113–115: section p { ... } → Paragraphs inside sections are white.
Line 116–118: div ul li a img { ... } → Sidebar logo image size (25px wide).
Line 119–122: .resources { ... } → Image on resources page is responsive (max-width 100%).
Line 123–125: a { ... } → Default link styling: turquoise, no underline.
