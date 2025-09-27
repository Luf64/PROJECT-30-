<!--YEW_ZHIAN.html-->
HTML Explanation

Line 1: <!DOCTYPE html>- Declares this document as HTML5.
Line 2: <html lang="en"> - Opens the HTML document and sets the language to English.
Line 3: <head> - Starts the head section (metadata, resources).
Line 4: <meta charset="UTF-8" /> - Sets character encoding to UTF-8 (universal).
Line 5: <meta name="viewport" content="width=device-width, initial-scale=1.0" /> - Makes the page responsive on all screen sizes.
Line 6: <meta name="description" content="This is Yew Zhian's Profile Page" /> - Provides a description for search engines/browsers.
Line 7: <link rel="stylesheet" href="YEW_ZHIAN.css" /> - Connects the external CSS file.
Line 8: <link rel="icon" type="image/x-icon" href="images/dog.png" /> - Sets favicon for the browser tab.
Line 9: <title>Yew Zhian's Profile</title> - Title shown on the browser tab.
Line 10: </head> - Ends the head section.
Line 11: <body> - Starts the body (visible content).

Navigation Bar
Line 12: <nav id="navbar"> - Opens the top navigation bar.
Line 13: <div class="overlay"></div> - Overlay element (empty div, can be styled).
Line 14–21: <a href="..."> ... </a> - Navigation links (HOME, NAUFAL, EE JIE, YEW ZHIAN, DINASH, RESOURCES, FEEDBACK).
Line 22: </nav> - Ends navigation bar.

Header Title
Line 23: <h1 class="textcenter">Welcome to Yew Zhian's Profile</h1> - Main page heading, centered.

Sidebar Navigation
Line 24: <div class="sidebar"> - Opens sidebar container.
Line 25: <ul> - Unordered list to hold sidebar items.
Line 26–72: <li> ... </li> - Each list item has links to page sections: Profile, About Me, Goals, Skills, Journey, Future Plan, YouTube Channel, Video, Useful Links, Bottom.
Line 73: </ul> - Closes sidebar list.
Line 74: </div> - Ends sidebar.

Main Content
Line 75: <main> - Opens main content area.

About Me Section
Line 76–93: <section class="textcenter"> ... </section> - About Me section with photo, heading, and introduction paragraph.

Goals & Achievements Section
Line 95–141: <section> ... </section> - Lists learning goals (HTML, CSS, Python, JavaScript, C++, computer science concepts, projects, competitions) and achievements.

Skills Section
Line 143–157: <section> ... </section> - Describes technical skills (HTML, CSS, Python, JavaScript, tools like Clickup & VS Code, problem-solving, teamwork, communication).

Learning Journey Section
Line 159–172: <section> ... </section> - Reflection paragraph describing learning experiences and progress.

Future Plan Section
Line 174–206: <section> ... </section> - A 22-week plan table for becoming a beginner front-end developer (HTML & CSS, JavaScript, React, Git).

YouTube Channel Section
Line 208–226: <section> ... </section> - Favorite YouTube channel (Programming with Mosh) with image, link, and embedded YouTube video.

Video Section
Line 228–237: <section> ... </section> - Another embedded video to understand programming basics.

Useful Links Section
Line 239–260: <section> ... </section> - Provides external learning resources (Coursera, Udemy, FreeCodeCamp, Codecademy).

Footer Section
Line 261: </main> - Ends main content.
Line 262: <footer> - Starts footer.
Line 263–268: <h2>References</h2> ... - Copyright, references, and contact details.
Line 269: </footer> - Closes footer.
Line 270: </body> - Closes body.
Line 271: </html> - Closes HTML document. 

/*YEW_ZHIAN.css*/
CSS Explanation (YEW_ZHIAN.css)

Line 1: * { margin: 0; padding: 0; box-sizing: border-box; } - Resets default browser spacing, ensures consistent element sizing.
Line 2: body { font-family: Arial, sans-serif; background-color: #f5f5f5; color: #333; } - Sets page font, background color (light grey), and text color (dark grey).
Line 3: #navbar { display: flex; justify-content: center; background-color: #333; padding: 10px 0; position: sticky; top: 0; z-index: 1000; } - Styles navbar: dark background, items centered, sticky on top.
Line 4: #navbar a { color: white; text-decoration: none; padding: 10px 15px; transition: background 0.3s; } - White navbar links, spacing, smooth hover effect.
Line 5: #navbar a:hover { background-color: #555; border-radius: 5px; } - Darker background with rounded corners on hover.
Line 6: .textcenter { text-align: center; margin: 20px 0; } - Centers text with spacing above and below.
Line 7: .sidebar { position: fixed; left: 0; top: 60px; width: 200px; height: 100%; background: #444; padding-top: 20px; } - Sidebar fixed on the left, below navbar, dark background.
Line 8: .sidebar ul { list-style: none; padding: 0; } - Removes bullet points from sidebar list.
Line 9: .sidebar ul li { margin: 10px 0; } - Adds space between sidebar items.
Line 10: .sidebar ul li a { color: white; text-decoration: none; display: block; padding: 10px; transition: background 0.3s; } - Sidebar links are white, block style, clickable area with padding.
Line 11: .sidebar ul li a:hover { background: #666; border-radius: 5px; } - Darker hover effect with rounded corners.
Line 12: main { margin-left: 220px; padding: 20px; } - Pushes main content to the right (space for sidebar), adds padding.
Line 13: section { margin-bottom: 40px; } - Adds space after each section.
Line 14: section h2 { margin-bottom: 15px; color: #222; } - Section headings with darker text and spacing.
Line 15: img { max-width: 100%; height: auto; border-radius: 10px; } - Makes images responsive and rounded.
Line 16: .iframe iframe { width: 100%; height: 400px; border-radius: 10px; } - Embedded videos take full width, fixed height, rounded corners.
Line 17: table { width: 100%; border-collapse: collapse; margin: 20px 0; } - Tables stretch full width, no gaps between borders.
Line 18: table, th, td { border: 1px solid #ccc; } - Light grey border for table and cells.
Line 19: th, td { padding: 10px; text-align: center; } - Spacing inside table cells, text centered.
Line 20: th { background: #eee; } - Table header has light grey background.
Line 21: footer { background: #333; color: white; text-align: center; padding: 20px; } - Footer with dark background, white text, centered.
Line 22: footer a { color: lightblue; text-decoration: none; } - Footer links in light blue.
Line 23: footer a:hover { text-decoration: underline; } - Footer links underline on hover.
