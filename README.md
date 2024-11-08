💻 Project Title

This project displays a set of clickable social media icons styled with HTML and CSS. Each icon links to a different social media profile, and unique hover effects reveal the platform name and change the icon's color.

Live Demo [https://tazida.github.io/Social-media/]

Features
- Social Media Links: Icons link to LinkedIn, GitHub, Instagram, Facebook, Threads, and X (formerly Twitter) profiles.
- Hover Effects: Hovering over each icon changes its background color, reveals a tooltip with the platform name, and changes the SVG icon color.
- Responsive Design: The layout is centered and uses flexible CSS grid properties, making it adaptive to different screen sizes.

Project Structure
HTML:
- Sets up a header text ("Connect with Tazida on Social Media") and a container for social media links.
- Each icon link is contained within an <a> tag, where data-social holds the platform name.
CSS:
- Fonts: Imports "Poppins" from Google Fonts for consistent typography.
- Global Styles: Basic styling for HTML elements and body layout.
- Icon Styles: Each social icon is styled as a circular button with background colors and shadow effects. Hover states use CSS transitions for smooth effects, with colors specified via CSS variables for each platform.
- Tooltips: Tooltips appear when hovering over icons, showing the platform name in a rotated, positioned label above each icon.
  
Files
index.html: Contains the structure and links for each social media platform.
style.css: Includes all styling for icons, tooltips, and hover effects.
