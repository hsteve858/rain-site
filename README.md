# Where Does the Rain Go?

A static site for a two-week hybrid 5th grade Earth science unit on the water cycle and weather (Colorado Academic Standard, Grade 5, Standard 3 — Earth and Space Science, 5-ESS2-1).

Plain HTML/CSS, no build step, no dependencies to install.

## Pages

- `index.html` — unit overview + two-week schedule
- `day3-lesson.html` — full Day 3 lesson plan (Water Cycle in a Bag)
- `assessment.html` — formative checks + summative rubric
- `parent-guide.html` — printable parent/caregiver guide
- `style.css` — shared styling

## Publish it with GitHub Pages

1. Create a new repository on GitHub (or use an existing one) and push these files to it:

   ```bash
   git init
   git add .
   git commit -m "Add Where Does the Rain Go unit site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git push -u origin main
   ```

2. On GitHub, go to your repository's **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Set the branch to `main` and the folder to `/ (root)`, then **Save**.
5. GitHub will publish the site at `https://<your-username>.github.io/<your-repo>/` within a minute or two.

## Editing

Every page is a self-contained HTML file — edit the content directly, or edit `style.css` to change colors, type, or layout site-wide (see the `:root` variables at the top of the file).
