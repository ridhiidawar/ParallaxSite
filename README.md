# ParallaxSite
A Parallax Effect is a modern web design technique where background images move slower than foreground elements, creating an illusion of depth on the webpage. This technique enhances user experience and is commonly used in landing pages, portfolios, and storytelling websites.

🔹 HTML Structure:

The page begins with the standard <!DOCTYPE html> declaration.
The <head> tag includes metadata, page title, favicon, and a link to external CSS.
Inside the <body>, a div with ID wrapper wraps a container that includes:
A background image (moonlightjpg.jpg) for the parallax effect.
A foreground image (base64-encoded) that scrolls differently to create the illusion of depth.

🔹 CSS (in index.css file):

The .background image is positioned with background-attachment: fixed or a similar technique to make it move at a different speed compared to the foreground content.
z-index, position, and transform properties are used to layer the images effectively.
Responsive units (vh, vw, %) are used for smooth adaptability across devices.
