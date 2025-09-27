<!--EE_JIE.html-->
For my part, my HTML and CSS are both in one file, I will separate them into HTML part and CSS part explaination.
HTML part
Line 1: <!DOCTYPE html> - Declares this as an HTML5 document.
Line 2: <html lang="en"> - Starts the HTML file and sets the language to English.
Line 3: <head> - Opens the head section, contains metadata, title, styles.
Line 4: <meta charset="UTF-8" /> - Character encoding set to UTF-8.
Line 5: <meta name="viewport" content="width=device-width, initial-scale=1.0" /> - Ensures responsiveness on different devices.
Line 6: <title>Chan Ee Jie</title> - Sets browser tab title.
Line 7: <link ... fonts.googleapis.com ...> - Imports Google Fonts (Nunito, Quicksand).
Line 8–141: <style> ... </style> - Contains all CSS rules for styling this page.
Line 142: </head> - Ends head section.
Line 143: <body> - Opens body content.
Line 144: <header> - Header of the page.
Line 145–153: <nav> with links → Navigation bar with links to HOME, team member pages, RESOURCES, FEEDBACK.
Line 154: <h1>Ee Jie's Life</h1> - Main heading with the page owner’s name.
Line 155–165: <div class="intro-banner"> - Banner section with hero image and introduction.
 Line 156: <img ... class="hero-image" /> - Profile image (rock climbing).
 Line 157–165: <div class="about-me"> - Introduction text and list of personal facts/interests.
Line 166: </header> → Ends header.
Line 167–169: <div class="section-divider"> - Divider section with text “More about me”.
Line 170: <main> - Main content starts.
Line 171–177: <section> - First section with a table of learning goals and achievements.
Line 178–184: <section id="skills"> - Section describing skills in game dev, climbing, and music.
Line 185–187: <section id="reflection"> - Reflection text about personal journey.
Line 188: </main> → Ends main content.
Line 189–196: <section id="Climbing"> - Section with a YouTube embedded video about rock climbing.
Line 197: </section> - Ends climbing section.
Line 198–201: <footer> - Footer section with project info and group details.
Line 202: </body> - Closes body.
Line 203: </html> - Ends document.

CSS part
Line 9–13: :root { ... } - Defines CSS variables for colors (snow-white, light-tan, glass).
Line 15–20: * { ... } - Universal selector resets margin, padding, box-sizing, and enables smooth scroll.
Line 22–28: body { ... } - Sets font, background image, text color, line height.
Line 30–35: header { ... } - Centers header text, background color, padding.
Line 37–43: header h1 { ... } - Sets heading font (Quicksand), size, color, and spacing.
Line 46–49: table, th, td { ... } - Adds border and padding for tables.
Line 51–56: nav { ... } - Full width nav bar, dark background, centered links.
Line 58–66: nav a { ... } - Navigation links styled with spacing, bold font, smooth hover transition.
Line 69–71: nav a:hover { ... } - Nav links turn white when hovered.
Line 73–79: main { ... } - Uses CSS grid layout for responsive sections, background tint.
Line 81–88: section { ... } - Glass-like cards with blur, shadow, rounded corners.
Line 90–94: h2 { ... } - Subheadings style, colored in light tan.
Line 96–99: img { ... } - Makes images responsive with rounded corners.
Line 101–105: table { ... } - Full width, collapsed borders, margin top.
Line 108–111: ul.custom-list { ... } - Removes default list styles.
Line 113–121: .video-container { ... } - Responsive 16:9 container for embedded videos.
Line 122–126: .video-container iframe { ... } - Full width/height video, no border.
Line 129–134: footer { ... } - Footer with centered text, dark background, light tan color.
Line 136–138: section:hover { ... } - Slight upward hover effect for sections.
Line 140–147: .intro-banner { ... } - Flexbox for profile section (image + text).
Line 149–154: .hero-image { ... } - Styled profile image with border and radius.
Line 156–160: .about-me { ... } - Text block beside image, max width, left aligned.
Line 163–168: .section-divider { ... } - Divider with background, font styling.
Line 170–173: ul.custom-list li::before { ... } - Adds emoji/icon before each custom list item.
