SOJIB PORTFOLIO WEBSITE — HOW TO EDIT
=====================================

Files
  index.html  -> the website (do not need to touch)
  data.js     -> ALL content (name, projects, skills, links, colors...)
  admin.html  -> visual editor for data.js
  assets/     -> put your photo / project images here

Edit (easy way)
  1. Open admin.html in your browser (double-click it).
  2. Change anything. Use + Add / ↑ ↓ / ✕ to add, reorder, delete items.
     Upload a photo in Profile > Photo (or put assets/photo.jpg in the path box).
  3. Click "Preview" to see the site with your changes.
  4. Click "Download data.js" and replace the old data.js in this folder.

Publish on Netlify (free)
  Go to app.netlify.com/drop and drag this whole folder in.
  After each edit: replace data.js, then drag the folder in again
  (or "Deploys > Drag and drop" on your existing site).

Tips
  - Settings > showSections: untick to hide a section.
  - Settings > accentColor / accentColor2: change the site colors.
  - Contact > formMode: "mailto" opens the visitor's email app;
    "netlify" saves messages in your Netlify dashboard (Forms tab).
  - Profile > resumeUrl: paste a Google Drive link to your CV to show a "Download CV" button.
  - Social icons supported: linkedin, github, email, facebook, twitter,
    youtube, medium, huggingface, website.
