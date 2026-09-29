S Anukriti website - files and how to publish them

WHAT'S HERE
  index.html      Home page
  research.html   Research page (theme filters)
  writing.html    Writing and media page
  cv.pdf          Your CV (linked from "CV" in the menu and on the Home page)
  img/            Photos and the report cover
  .nojekyll       Leave this in place; it tells GitHub Pages to serve the files as they are

PUBLISH ON GITHUB PAGES (about 15 minutes)
  1. Sign in at github.com (create a free account if needed).
  2. Click "New repository". Name it exactly  <your-username>.github.io  and set it to Public.
  3. In the new repository: "Add file" > "Upload files". Drag in ALL the contents of this folder
     (the three .html files, cv.pdf, and the img folder). Click "Commit changes".
     Tip: .nojekyll is a hidden file on Mac/Windows. If it doesn't upload, create it on GitHub with
     "Add file" > "Create new file", name it .nojekyll, leave it empty, and commit.
  4. Settings > Pages > "Deploy from a branch" > main, / (root) > Save.
  5. After a minute or two the site is live at  https://<your-username>.github.io

UPDATING LATER
  Upload the changed file (e.g. a new cv.pdf or research.html) with the same name and commit.
  GitHub keeps every earlier version, so you can always roll back.

CUSTOM DOMAIN (optional)
  Settings > Pages > Custom domain, enter your domain, then follow GitHub's instructions to add the
  DNS records at your registrar. Tick "Enforce HTTPS" once it is available.
