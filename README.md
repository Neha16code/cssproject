Here’s how you can add a `README.md` file to your GitHub repo **cssproject** (at `Neha16code/cssproject`):

---

### Steps to add a README locally and push

1. In your project folder (on your PC / working directory), create a file called `README.md`.

   ```bash
   cd D:\Learning Full stack\Assignment
   touch README.md
   ```

2. Open `README.md` in a text editor and add some content. Example:

   ```markdown
   # CSS Project

   This project contains basic HTML and CSS files to practice styling and layout.

   ## Files
   - `Untitled-11.html` — main HTML structure  
   - `style11.css` — styles for the HTML  
   - `photo.jpg` — image used in the project

   ## How to run
   Open the HTML file in your browser.

   ---

   *Created by Neha16code*
   ```

3. Stage and commit the `README.md` file:

   ```bash
   git add README.md
   git commit -m "Add README.md file"
   ```

4. Push the commit to GitHub:

   ```bash
   git push origin main
   ```

   (If your default branch is named differently, replace `main` with that branch name.)

