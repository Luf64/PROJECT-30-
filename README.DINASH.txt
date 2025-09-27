<!--DINASH.html-->
Line 1: <!DOCTYPE html> → Declares HTML5 document
Line 2: <html lang="en"> → Opens HTML, language set to English
Line 3: <head> → Starts head section
Line 4: <meta charset="UTF-8"> → Sets character encoding
Line 5: <title>Dinash's Learning Journey</title> → Page title in browser tab
Line 6: <link rel="stylesheet" href="style.css"> → Connects CSS file
Line 7: </head> → Closes head
Line 8: <body> → Starts page body

Header Section
Line 9: <header> → Opens header
Line 10: <h1>Dinash A/L Anpazhagan</h1> → Main heading (your name)
Line 11: <nav> → Starts navigation
Line 12–20: <ul> ... </ul> → Menu list with links (Home, Resources, Contact, Naufal, Dinash, Chan, Phua)
Line 21: </nav> → Closes navigation
Line 22: </header> → Closes header

Main Section
Line 24: <main> → Opens main content

About Me
Line 26–32: <section> ... </section> → “About Me” with heading, paragraph, and photo

Skills
Line 34–40: <section> ... </section> → “My Skills” list (HTML & CSS, Python, teamwork)

Learning Goals
Line 42–46: <section> ... </section> → Goals paragraph

Learning Journey
Line 49–61: <section> ... </section> → Reflection paragraph + YouTube video (iframe)

Footer Section
Line 67–69: <footer> ... </footer> → Footer with copyright

Line 70: </body> → Closes body
Line 71: </html> → Closes HTML document

<!--Dinash.css-->
Line 1 → /* ===== General Page Styling ===== */ → Comment label.
Line 2 → body { → Start styling the whole page.
Line 3 → font-family: 'Segoe UI', Arial, sans-serif; → Use clean, modern fonts.
Line 4 → margin: 0; → Remove default margins.
Line 5 → padding: 0; → Remove default padding.
Line 6 → background: linear-gradient(to right, #e3f2fd, #f8f9fa); → Soft gradient background.
Line 7 → color: #333; → Dark gray text color.
Line 8 → } → Close body style.

Line 10 → /* ===== Header ===== */ → Comment label.
Line 11 → header { → Start header styling.
Line 12 → background: #0d47a1; → Dark blue background.
Line 13 → color: white; → White text.
Line 14 → text-align: center; → Center align content.
Line 15 → padding: 25px 10px; → Add space inside header.
Line 16 → } → Close header style.

Line 17 → header h1 { → Style header title.
Line 18 → margin: 0; → Remove default margin.
Line 19 → font-size: 2.2em; → Make title larger.
Line 20 → letter-spacing: 1px; → Add spacing between letters.
Line 21 → } → Close h1 style.

Line 23 → /* ===== Navigation ===== */ → Comment label.
Line 24 → nav ul { → Start navigation list styling.
Line 25 → list-style: none; → Remove bullets.
Line 26 → padding: 0; → Remove padding.
Line 27 → margin-top: 12px; → Add top margin.
Line 28 → } → Close nav ul.

Line 29 → nav ul li { → Style each list item.
Line 30 → display: inline-block; → Show items in a row.
Line 31 → margin: 0 14px; → Add spacing between items.
Line 32 → }

Line 34 → nav ul li a { → Style links.
Line 35 → text-decoration: none; → Remove underline.
Line 36 → color: #ffeb3b; → Yellow color.
Line 37 → font-weight: bold; → Bold text.
Line 38 → transition: 0.3s; → Smooth hover effect.
Line 39 → }

Line 40 → nav ul li a:hover { → Style link when hovered.
Line 41 → color: #fff59d; → Lighter yellow.
Line 42 → border-bottom: 2px solid #ffeb3b; → Yellow underline.
Line 43 → }

Line 46 → /* ===== Main Content ===== */
Line 47 → main { → Style main area.
Line 48 → padding: 40px 20px; → Add spacing.
Line 49 → max-width: 1000px; → Limit width.
Line 50 → margin: auto; → Center on page.
Line 51 → line-height: 1.6; → Comfortable text spacing.
Line 52 → }

Line 54 → /* Card-like Sections */
Line 55 → section { → Style each section.
Line 56 → margin-bottom: 40px; → Space below each.
Line 57 → padding: 20px; → Inner space.
Line 58 → background: #ffffff; → White background.
Line 59 → border-radius: 12px; → Rounded corners.
Line 60 → box-shadow: 0 4px 12px rgba(0,0,0,0.1); → Soft shadow.
Line 61 → }

Line 64 → /* Section Headings */
Line 65 → section h2 { → Style section titles.
Line 66 → color: #0d47a1; → Dark blue.
Line 67 → border-left: 6px solid #42a5f5; → Blue left border.
Line 68 → padding-left: 12px; → Space after border.
Line 69 → margin-bottom: 15px; → Space below.
Line 70 → }

Line 72 → /* ===== 2-Column Layout for Bio + Skills ===== */
Line 73 → .columns { → Grid for two columns.
Line 74 → display: grid; → Enable grid.
Line 75 → grid-template-columns: 1fr 1fr; → Two equal columns.
Line 76 → gap: 25px; → Space between.
Line 77 → align-items: start; → Align to top.
Line 78 → }

Line 79 → .columns img { → Style images.
Line 80 → max-width: 100%; → Responsive.
Line 81 → border-radius: 12px; → Rounded edges.
Line 82 → box-shadow: 0 3px 8px rgba(0,0,0,0.2); → Shadow.
Line 83 → }

Line 85 → /* ===== Lists ===== */
Line 86 → ul { → Style unordered lists.
Line 87 → list-style-type: square; → Use square bullets.
Line 88 → padding-left: 25px; → Indent left.
Line 89 → }

Line 91 → ul li { → Style list items.
Line 92 → margin: 8px 0; → Space between.
Line 93 → font-weight: 500; → Semi-bold.
Line 94 → }

Line 97 → /* ===== YouTube Video ===== */
Line 98 → iframe { → Style video.
Line 99 → display: block; → Block element.
Line 100 → margin: 20px auto; → Center with margin.
Line 101 → border: 3px solid #42a5f5; → Blue border.
Line 102 → border-radius: 10px; → Rounded corners.
Line 103 → max-width: 100%; → Responsive.
Line 104 → }

Line 106 → /* ===== Footer ===== */
Line 107 → footer { → Start footer style.
Line 108 → text-align: center; → Center text.
Line 109 → background: #0d47a1; → Blue background.
Line 110 → color: white; → White text.
Line 111 → padding: 15px; → Space inside.
Line 112 → margin-top: 30px; → Space above footer.
Line 113 → font-size: 0.9em; → Smaller text.
Line 114 → }
