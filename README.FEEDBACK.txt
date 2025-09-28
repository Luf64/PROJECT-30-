<!--FEEDBACK.html-->
HTML part
Line 1: <!DOCTYPE html> – Declares the document type as HTML5.
Line 2: <html lang="en"> – Opens the HTML document and sets the language to English.
Line 3: <head> – Head section starts, used for metadata and styles.
Line 4: <title>Contact / Feedback Page</title> – Sets the title of the browser tab.
Line 5: <style> – Internal CSS starts here.

CSS part (inside <style></style>)
Line 6: * { box-sizing: border-box; margin: 0; padding: 0; scroll-behavior: smooth; } – Resets all elements (no margin/padding) and ensures consistent box sizing. Smooth scrolling enabled.
Line 7: body { background: url("images/6217047.jpg") no-repeat center center fixed; background-size: cover; background-color: rgba(161,161,161,0.388); } – Sets a fixed background image, covers the screen, and adds a gray overlay color.
Line 8: h2 { padding-top: 1em; padding-bottom: 1em; font-size: 1.5em; margin-bottom: 0.5em; color: rgba(6,4,35,0.872); } – Styles <h2> headers with spacing and dark blue color.
Line 9: section { background: rgba(55,66,87,0.221); padding: 1.5em; border-radius: 12px; backdrop-filter: blur(8px); box-shadow: 0 0 20px rgba(0,0,0,0.2); max-width: 800px; margin: 0 auto; width: 100%; margin-top: 2em; color: antiquewhite; } – Styles each content section with a transparent blurred background (glass effect), shadow, and centered layout.
Line 10: nav { width: 100%; background-color: rgba(6,4,35,0.872); margin-bottom: 0; padding: 1em; text-align: center; } – Styles navigation bar with dark background, padding, and center alignment.
Line 11: nav a { position: sticky; margin: 1em; color: rgba(121,198,249,0.897); text-decoration: none; font-weight: bold; transition: color 0.3s; z-index: 1000; } – Styles nav links with light blue color, spacing, bold font, and hover transition.
Line 12: nav a:hover { color: #f5faff; } – When hovering, link turns to white.
Line 13: h1 { color: rgba(6,4,35,0.872); } – Styles main title with dark blue.
Line 14: </style> – Ends CSS.

HTML Body Part
Line 15: <body> – Page content starts.
Line 16: <nav class="nav" id="nav_bar1"> ... </nav> – Navigation bar with links to all members’ pages and other project pages.
Line 17: <section> – A section for Feedback Form.
Line 18: <h1>Feedback</h1> – Main heading of the feedback page.
Line 19: <h2>Send Us a Message</h2> – Subheading for the contact form.
Line 20: <h3> – Starts form content (though better use <form>, here it uses <h3> as container).
Line 21–29: Input fields for Name, Email, and Message with labels and textareas. All are required.
Line 30: <input type="submit" value="Send" /> – Submit button to send the message.
Line 31: </h3> – Closes the form container.
Line 32: </section> – Ends feedback form section.

Acknowledgment Section
Line 33: <section> – New section for acknowledgments.
Line 34: <h2>Acknowledgment</h2> – Heading for acknowledgments.
Line 35: <p>We would like to thank Chan1, Chan2, Chan3, and Chan4 for making this possible.</p> – Lists acknowledgment text.
Line 36: </section> – Ends acknowledgment section.

Credits Section
Line 37: <section> – New section for credits.
Line 38: <h2>Credits</h2> – Heading for credits.
Line 39–44: <ul> list containing group members’ names and roles/contributions. Each member is listed with their work.
Line 45: </section> – Ends credits section.

Closing
Line 46: </body> – Ends body content.
Line 47: </html> – Ends HTML document.
