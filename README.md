🎯 Objective

Deploy your static website so it becomes publicly accessible using a GitHub Pages URL like:

https://<yourusername>.github.io

🛠️ Tools Required

GitHub account

Git installed (or GitHub Desktop)

Any static website files (HTML, CSS, JS)

📂 Project Deliverable

A public GitHub repository with a live website hosted on GitHub Pages.

🚀 Steps to Deploy Your Website
1. Create a new GitHub repository

Go to GitHub → New Repository

Name it exactly:

<yourusername>.github.io


Example:
anushree123.github.io

Set repository to Public

Click Create Repository

2. Clone the repository locally

Using Git CLI:

git clone https://github.com/<yourusername>/<yourusername>.github.io


Or use GitHub Desktop → "Clone a repository".

3. Add your website files

Inside the cloned folder, copy your:

index.html
style.css
script.js
images/


Make sure index.html is at the root.

4. Commit and Push

Using Git CLI:

git add .
git commit -m "Initial website upload"
git push origin main


Or using GitHub Desktop → Commit → Push.

5. Enable GitHub Pages

Open the repository on GitHub

Go to Settings → Pages

Under Source, choose:

Branch: main
Folder: /


Click Save

6. Open your live website

Wait 1–2 minutes, then open:

https://<yourusername>.github.io


Example:

https://anushree123.github.io

7. Update Your Website

Any time you update your HTML/CSS/JS:

git add .
git commit -m "Update site"
git push origin main


Your live site updates automatically!

