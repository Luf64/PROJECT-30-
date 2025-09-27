<!--HOME.html-->
Line 1: <!DOCTYPE html> - Declares HTML5 document.

Line 2: <head> - Starts head section.

Line 3: <link href="HOME.css" rel="stylesheet"> - Links CSS file.

Line 5: <link rel="preconnect" href="https://fonts.googleapis.com"> → Preconnect to Google Fonts.
Line 6: <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin> → Preconnect to fonts.gstatic for performance.
Line 7: <link href="https://fonts.googleapis.com/css2?family=MedievalSharp&display=swap" rel="stylesheet"> → Loads MedievalSharp font.

Line 9: </head> - Ends head.

Line 12: <body> - Opens body.

Line 13: <title>GROUP G HOMEPAGE</title> - Page title (though usually belongs in <head>).

Line 14: <section class="banner"> - Banner section starts.

Line 15: <nav> - Navigation bar starts.

Line 16–26: <div class="nav-links"> <ul> <li>...</li> </ul> </div> - Navigation links list (HOME, NAUFAL, EE JIE, YEW ZHIAN, DINASH, RESOURCES, FEEDBACK).

Line 27: </nav> - Ends navigation.

Line 31: <div class="text-box"> - Central welcome message.
Line 32: <h1>Welcome to FC03 Group G Home Page</h1> - Main heading.
Line 33: <h2>Introduction to the webpage</h2> - Subheading.
Line 34: <p>This is the homepage for our group project... </p> - Introductory text.
Line 36: </div> - Ends text box.

Line 37: </section> - Ends banner section.

Line 39: <section class="video"> - Video section starts.
Line 40: <h2>Feel Free to Watch Our Roleplay Video</h2> - Video heading.
Line 41: <iframe ... ></iframe> - Embedded YouTube video.
Line 42: <p>This video was created... scenario about IT teams...</p> - Video description.

Line 46: <div class="footer"> - Footer starts.
Line 47: <h4>Thank you for visiting our webpage</h4> - Footer heading.
Line 48: <p>We hope you find the information useful...</p> - Footer text.
Line 49: </div> - Ends footer.

Line 51: </body> - Closes body.

Line 52: </section> - Extra closing tag (should be removed).

Line 54: </body> - Duplicate closing body tag (extra, should remove).

Line 55: </html> - Closes HTML document.
/*HOME.css*/
Line 1: *{ margin: 0; padding: 0%; scroll-behavior: smooth; font-family: "MedievalSharp", cursive; } - Applies global reset: removes margin/padding, enables smooth scrolling, and sets font.

Line 8: .banner{ min-height: 100vh; width: 100%; background-image: linear-gradient(rgba(62,63,68,0.7), rgba(4,9,30,0.7)), url(images/LakeShack.jpg); } - Banner section covers full screen height with a dark gradient overlay on a background image.

Line 13: nav{ display: flex; padding: 2% 6%; justify-content: space-evenly; align-items: center; } - Navigation bar uses flexbox, evenly spaces items.

Line 18: nav img{ width: 100px; } - Logo image set to 100px width.

Line 21: .nav-links{ flex: 1; text-align: center; } - Navigation links container expands and centers content.

Line 25: .nav-links ul li{ list-style: none; display: inline-block; padding: 8px 12px; position: relative; } - Removes bullets, displays items inline, with padding.

Line 31: .nav-links ul li a{ color: #fff; text-decoration: none; font-size: 13px; font-family: 'Poppins', sans-serif; } - Menu links styled white, small size, no underline.

Line 37: .nav-links ul li::after{ content: ''; width: 0%; height: 2px; background: #ff8b2c; display: block; margin: auto; } - Creates orange underline effect (hidden at start).

Line 44: .nav-links ul li:hover::after{ width: 100%; transition: 0.5s; } - Underline grows fully on hover.

Line 48: .text-box{ width: 90%; color: #ffbb86; position: absolute; top: 50%; left: 50%; transform: translate(-50%,-50%); text-align: center; } - Text box centered in banner with highlighted text.

Line 55: .text-box h1{ font-size: 50px; color: #ff9b44; margin-bottom: 20px; } - Main heading large orange text.

Line 59: .text-box h2{ font-size: 30px; color: #ffc490; margin-bottom: 4%; } - Subheading medium size, light orange.

Line 63: .text-box p{ margin: 30px 50px; font-size: 26px; color: #fff; } - Paragraph white text, spaced margins, medium font size.

Line 67: .video { background-image: linear-gradient(rgba(4,9,30,0.7), rgba(62,63,68,0.7)), url(images/LakeShackInvert.jpg); width: 100%; margin: auto; text-align: center; } - Video section has inverted background image with gradient overlay, centered content.

Line 74: .video h2{ font-size: 40px; color: #ff9b44; padding: 20px; margin-bottom: 40px; } - Video heading large orange.

Line 79: .video iframe{ margin-bottom: 40px; } - Space below video.

Line 82: .video p{ font-size: 20px; color: #fff; margin-bottom: 40px; } - Video description white text.

Line 87: .footer{ background-color: #ad690a; text-align: center; padding: 50px 20px; color: #ffffff; } - Footer has brown background, white centered text, padding.
