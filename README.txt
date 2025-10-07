================================================================================
                    IDLE MASTER WEBSITE - README
        Professional Multi-Page Website with Modern Design
================================================================================

📋 TABLE OF CONTENTS
--------------------
1. Introduction
2. File Structure
3. How to Run Locally
4. Customization Guide
5. Changing Links
6. Updating Colors
7. Modifying Content
8. SEO & Keywords
9. Responsive Design
10. Browser Support
11. Troubleshooting
12. Credits

================================================================================

1. INTRODUCTION
---------------
This is a professional, modern, responsive multi-page website for Idle Master.
The design is inspired by idlemaster.net but with a cleaner, more elegant 
approach. All pages are fully responsive and optimized for mobile, tablet, 
and desktop devices.

Color Palette Used:
- Primary Background: #EFEFEF
- Secondary Background: #FFFFFF
- Accent Color: #D10000
- Accent Dark: #A00000

================================================================================

2. FILE STRUCTURE
-----------------
IdleMaster3/
│
├── index.html          → Home page with hero section and features
├── about.html          → About page with mission and vision
├── contact.html        → Contact page with Google Form button
├── download.html       → Download page with system requirements
├── style.css           → All styling and responsive design
├── script.js           → JavaScript for interactivity
└── README.txt          → This file

================================================================================

3. HOW TO RUN LOCALLY
---------------------
OPTION 1: Direct Opening (Simple)
----------------------------------
1. Navigate to the folder containing the files
2. Double-click on "index.html"
3. The website will open in your default browser
4. Navigate between pages using the navigation menu

OPTION 2: Using Live Server (Recommended for Development)
----------------------------------------------------------
If you have Visual Studio Code:
1. Install "Live Server" extension
2. Right-click on index.html
3. Select "Open with Live Server"
4. The site will open with auto-reload functionality

OPTION 3: Using Python HTTP Server
-----------------------------------
1. Open terminal/command prompt in the folder
2. Run: python -m http.server 8000
3. Open browser and visit: http://localhost:8000

OPTION 4: Using Node.js HTTP Server
------------------------------------
1. Install: npm install -g http-server
2. Run: http-server
3. Visit the URL shown in terminal

================================================================================

4. CUSTOMIZATION GUIDE
----------------------
The website is designed to be easily customizable. All key elements can be
modified through the HTML files and style.css.

================================================================================

5. CHANGING LINKS
-----------------

A. Google Form Link (Contact Page)
-----------------------------------
File: contact.html
Find: href="https://docs.google.com/forms/d/e/1FAIpQLSfXccBSTtUKYMICf3NnmZpUrl8_CD2NmDD1Chn2ACITgjXihQ/viewform?usp=header"
Replace with: YOUR_NEW_GOOGLE_FORM_URL

B. GitHub Repository Link
--------------------------
Files: All HTML files
Find: href="https://github.com/subtitle-edit/Idle-Master"
Replace with: YOUR_GITHUB_URL

C. Download Link
----------------
Files: index.html, download.html
Find: href="https://idlemaster.net/download/"
Replace with: YOUR_DOWNLOAD_URL

D. Official Website Link
-------------------------
Files: index.html (hero section)
Find: href="https://idlemaster.net/"
Replace with: YOUR_OFFICIAL_SITE_URL

================================================================================

6. UPDATING COLORS
------------------
To change the color scheme, edit style.css at the top where CSS variables
are defined:

File: style.css (Lines 1-15)

:root {
    --primary-bg: #EFEFEF;        ← Change main background color
    --secondary-bg: #FFFFFF;      ← Change card/section background
    --accent-red: #D10000;        ← Change accent color (buttons, links)
    --accent-dark: #A00000;       ← Change darker accent (hover states)
    --text-primary: #1a1a1a;      ← Change main text color
    --text-secondary: #4a4a4a;    ← Change secondary text color
    --text-light: #6a6a6a;        ← Change light text color
}

After changing these variables, all colors throughout the site will update
automatically!

Example: To change accent color to blue:
--accent-red: #0066CC;
--accent-dark: #004C99;

================================================================================

7. MODIFYING CONTENT
--------------------

A. Homepage Content (index.html)
---------------------------------
Hero Section:
- Line 48: Badge text
- Line 49: Main heading
- Line 50-52: Hero description
- Line 57-70: Button text and links

Features Section:
- Lines 84-115: Feature cards (4 cards)
- Edit icons, titles, and descriptions as needed

How It Works Section:
- Lines 124-149: Step cards (3 steps)
- Modify step numbers, titles, and descriptions

B. About Page Content (about.html)
-----------------------------------
About Hero:
- Line 48: Badge text
- Line 49: Page title
- Line 50: Description

Main Content:
- Lines 58-108: About paragraphs and sections
- Edit text, add/remove paragraphs as needed

Mission & Vision:
- Lines 111-127: Mission and vision cards
- Customize goals and values

C. Contact Page Content (contact.html)
---------------------------------------
Contact Hero:
- Line 48: Badge text
- Line 49: Page title
- Line 50: Description

Contact Form Button:
- Line 59: Button text "Open Contact Form"
- Line 57: Google Form URL

Additional Sections:
- Lines 67-93: GitHub and Official Website cards
- Lines 95-105: Quick Response Tips

D. Download Page Content (download.html)
-----------------------------------------
Download Hero:
- Line 48: Badge text
- Line 49: Page title
- Line 50: Description
- Line 52: Download button URL

Features Grid:
- Lines 77-100: Feature cards (4 cards)

System Requirements:
- Lines 109-135: Minimum and recommended specs

Installation Guide:
- Lines 141-163: Installation steps (3 steps)

FAQ Section:
- Lines 169-193: Frequently asked questions

================================================================================

8. SEO & KEYWORDS
-----------------
The website is optimized for SEO with focus keyword "idle master".

Meta Tags (Each HTML file):
- Title tag: Located in <head> section
- Description meta: Line 5 of each HTML
- Keywords meta: Can be added to <head>

Internal Linking:
- The keyword "Idle Master" is naturally integrated throughout content
- Links to official site (https://idlemaster.net/) appear organically
- Footer links connect all pages

To Add More Keywords:
1. Identify target keywords
2. Integrate naturally in content paragraphs
3. Use in headings (h2, h3) where appropriate
4. Add to meta descriptions

Example:
<meta name="keywords" content="idle master, steam cards, trading cards, steam farming">

================================================================================

9. RESPONSIVE DESIGN
--------------------
The website is fully responsive with breakpoints at:

Desktop: 1400px+ (Full layout)
Tablet: 768px - 1399px (Adjusted grid)
Mobile: 320px - 767px (Stacked layout, mobile menu)

Mobile Navigation:
- Hamburger menu activates below 968px
- Slide-in menu from right side
- Smooth animations and transitions

Testing Responsiveness:
1. Open site in browser
2. Press F12 to open DevTools
3. Click "Toggle Device Toolbar" (Ctrl+Shift+M)
4. Test different screen sizes

================================================================================

10. BROWSER SUPPORT
-------------------
Fully tested and compatible with:
✅ Google Chrome (Latest)
✅ Mozilla Firefox (Latest)
✅ Microsoft Edge (Latest)
✅ Safari (Latest)
✅ Opera (Latest)

Mobile Browsers:
✅ Chrome Mobile
✅ Safari iOS
✅ Samsung Internet
✅ Firefox Mobile

================================================================================

11. TROUBLESHOOTING
-------------------

Issue: Styles not loading
Solution: Ensure style.css is in the same folder as HTML files

Issue: JavaScript not working
Solution: Check that script.js is in the same folder and linked correctly

Issue: Mobile menu not opening
Solution: Clear browser cache and refresh (Ctrl+F5)

Issue: Links not working
Solution: Verify URLs are correct and have http:// or https://

Issue: Fonts not loading
Solution: Check internet connection (Google Fonts require internet)

Issue: Colors not changing after editing CSS
Solution: Clear browser cache (Ctrl+Shift+Delete)

================================================================================

12. CREDITS
-----------
Design & Development: Idle Master Team
Fonts: Google Fonts (Inter)
Icons: Bootstrap Icons (SVG)
Inspiration: https://idlemaster.net/
Color Palette: Custom (#EFEFEF, #FFFFFF, #D10000)

================================================================================

📧 NEED HELP?
-------------
If you need assistance with customization or encounter any issues:

1. Check the GitHub repository for documentation
2. Submit an issue on GitHub
3. Contact through the contact form on the website
4. Review HTML/CSS comments for inline guidance

================================================================================

🎉 ENJOY YOUR NEW WEBSITE!
--------------------------
This website is designed to grow with your needs. Feel free to:
- Add new pages
- Modify existing content
- Change design elements
- Integrate additional features

Remember to:
✅ Test all changes across different devices
✅ Keep backups of your files
✅ Validate HTML/CSS before deploying
✅ Optimize images for web use

================================================================================

Last Updated: 2025
Version: 1.0
License: Open Source

================================================================================
