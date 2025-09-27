<!--YEW_ZHIAN.html-->
Line 1: <!DOCTYPE html> defines this file as an HTML5 document.  
Line 2: <html lang="en"> opens the HTML document, language is set to English.  
Line 3: <head> starts the head section, which contains metadata and styles.  
Line 4: <meta charset="UTF-8" /> ensures proper text encoding using UTF-8.  
Line 5: <meta name="viewport" content="width=device-width, initial-scale=1.0" /> makes the page responsive to different screen sizes.  
Line 6: <meta name="description" content="This is Yew Zhian's Profile Page" /> gives a short description for browsers and search engines.  
Line 7: <link rel="stylesheet" href="YEW_ZHIAN.css" /> links to the external CSS file for styling.  
Line 8: <link rel="icon" type="image/x-icon" href="images/dog.png" /> adds a favicon image for the browser tab.  
Line 9: <title>Yew Zhian's Profile</title> sets the page title shown in the tab.  
Line 10: </head> closes the head section.  
Line 11: <body> begins the visible content of the webpage.  
Line 12: <nav id="navbar"> creates the top navigation bar for page links.  
Line 13: Inside the navbar, <a> tags link to Home, Members, Resources, and Feedback pages.  
Line 14: <div class="overlay"></div> is reserved for overlay or design effects.  
Line 15: </nav> closes the navigation bar.  
Line 16: <h1 class="textcenter"> adds a centered welcome heading.  
Line 17: <div class="sidebar"> creates a sidebar on the left side of the page.  
Line 18: Inside the sidebar, <ul> contains list items <li> with links to each section of the page.  
Line 19: Sidebar links include About Me, Goals & Achievements, Skills, Learning Journey, Future Plan, YouTube Channel, Video, Useful Links, and Bottom.  
Line 20: </div> closes the sidebar.  
Line 21: <main> begins the main content section of the profile.  
Line 22: The first <section> contains About Me with a profile image and short introduction.  
Line 23: The next <section> describes Learning Goals and Achievements with ordered and unordered lists.  
Line 24: Another <section> explains Skills Acquired with a paragraph.  
Line 25: A Reflection on Learning Journey section highlights personal growth.  
Line 26: My Future Plan section includes a table showing a 22-week study plan.  
Line 27: My Favourite YouTube Channel section shows an image, link, and embedded video.  
Line 28: Video to Understand Program section embeds another YouTube tutorial.  
Line 29: Useful Links section provides external learning resources such as Coursera, Udemy, FreeCodeCamp, and Codecademy.  
Line 30: </main> closes the main content.  
Line 31: <footer> begins the footer section.  
Line 32: Footer includes References, Copyright, YouTube reference, and Contact email.  
Line 33: </footer> closes the footer.  
Line 34: </body> ends the page body.  
Line 35: </html> ends the HTML document.  
<!--YEW_ZHIAN.css-->
Line 1: CSS begins with *{...} to reset styles, set global font, enable smooth scrolling, and add letter spacing.  
Line 2: body{...} sets the background image, centers it, covers the screen, and adds padding.  
Line 3: .sidebar{...} fixes the sidebar to the left, sets default width to 50px, and background color to dark.  
Line 4: .sidebar:hover expands the width to 290px when hovered.  
Line 5: .sidebar ul li a{...} styles sidebar links with flex layout, white text, and hover transitions.  
Line 6: .sidebar ul li a::before adds a turquoise bar effect on hover using transform animation.  
Line 7: #navbar{...} styles the top navigation bar with dark background, flexbox, and centered items.  
Line 8: #navbar a styles links with padding, white text, and orange hover effect.  
Line 9: h1,h2,h3,caption{...} apply a black color with a thin white text-shadow outline.  
Line 10: #student styles the profile image to be round with 200px width.  
Line 11: #mosh styles the YouTube channel icon to be round with 100px width.  
Line 12: table{...} sets black background and full width, with grey header and lightgrey rows.  
Line 13: .iframe styles embedded videos with 560x315px size and dashed white border.  
Line 14: .textcenter aligns text to the center.  
Line 15: .juststaycenterman uses flexbox to horizontally center items with padding.  
Line 16: section{...} colors text white and adds padding around sections.  
Line 17: footer{...} sets white text, left alignment, and turquoise links.  
