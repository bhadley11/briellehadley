# **How to Create a Personal Website Using Markdown and GitHub**

Creating your own personal website might sound intimidating, but it's surprisingly simple with Markdown and GitHub. Here’s a step-by-step guide to help you build and host your website—even if you have no prior coding experience!

---

## **Step 1: Set Up Your Tools**
1. **Create a GitHub Account**  
   If you don’t already have one, sign up for free at [github.com](https://github.com).  
2. **Install GitHub Desktop (Optional)**  
   Download and install [GitHub Desktop](https://desktop.github.com/) to manage your projects visually.
3. **Download a Text Editor**  
   Use a simple text editor like [Atom](https://atom.io/) or [VS Code](https://code.visualstudio.com/) to edit your files.
---

## **Step 2: Create Your Repository**
This can be achieved by either (1) creating a new repository (described below), or (2)forking an existing template.
### **Using a Template**
If you would like to use a template, you can fork [this repository](https://github.com/CyVerse-learning-materials/FOSS-mkdocs-template) created by the Cyverse Team at the University of Arizona.
1. **Log in to GitHub**
2. **Open Template**
    - Select the link to the template (above).
3. **Fork the Repository**
This step essentially creates a copy of the template that will be your own, housed in your own GitHub account.

  - **Select** the green "Code" button.

  - **Copy** the URL.

  - **Import** the repository by selecting the dropdown in the upper right hand corner of the homepage of GitHub and clicking "Import Repository."
    - **Paste** the URL you copied under the "The URL for your source repository."
    - **Name** your repository.
    - **Select** begin import in the bottom right hand side of the screen. Note, the default is that this repository will be public.

### **Create the Materials Yourself**
1. **Log in to GitHub**  
    - Go to your GitHub account and click the green **"New"** button to create a new repository.  
2. **Set Repository Details**  
    - **Name**: Choose a name for your website (e.g., `my-website`).  
    - **Description**: Add a short description (optional).  
    - **Visibility**: Set the repository to "Public" (necessary for hosting).  
    - Check **"Add a README file"** to include a starting file.  
3. **Create the Repository**  
    - Click **"Create repository"** to finalize.
---

## **Step 3: Set Up Your Website**
1. **Enable GitHub Pages**  
    - In your repository, go to **Settings** > **Pages**.  
    - Under **Source**, select **Main** (or the branch you want to use) and click **Save**.  
    - GitHub will provide a link to your live site (e.g., `https://yourusername.github.io/my-website`).
2. **Choose a Theme**  
    - In the Pages settings, scroll to the theme section.  
    - Select a theme to style your site automatically.
---

## **Step 4: Create Your Website Content**
1. **Learn Basic Markdown**  
   Markdown is a simple text formatting language.  
   Example syntax:
    - `#` for headings  
    - `**bold**` for bold text  
    - `[link text](url)` for hyperlinks  
2. **Edit Your README File**  
    - Go to your repository and click on `README.md`.  
    - Use the pencil icon to edit it and add content in Markdown.  
   Example:  
   ```markdown
   # Welcome to My Website
   Hi! I'm [Your Name]. This is my personal site built with Markdown and GitHub Pages.
   ```
3. **Save Changes**  
    - Click **"Commit changes"** to update your site.

---

## **Step 5: Add Additional Pages**
1. **Create New Markdown Files**  
    - Click **"Add file"** > **"Create new file"**.  
    - Name your file (e.g., `about.md`) and add content in Markdown.  
2. **Link Between Pages**  
    - Use links to navigate between pages:  
     ```markdown
     [About Me](about.md)
     [Home](README.md)
     ```
3. **Commit Changes**  
    - Save each file by clicking **"Commit changes"**.

---

## **Step 6: Customize Your Site with MkDocs (Optional)**
If you want a more structured website:  
1. **Install MkDocs**  
    - Download Python from [python.org](https://www.python.org/) and install it.  
    - Use a terminal or command prompt to install MkDocs:  
     ```bash
     pip install mkdocs
     ```
2. **Create an MkDocs Project**  
    - Open a terminal and navigate to your repository folder:  
     ```bash
     cd /path/to/your-repository
     ```  
     - Create a new project:  
     ```bash
     mkdocs new .
     ```
3. **Edit Your `mkdocs.yml`**  
    - Update the configuration file to include your site's structure.  
4. **Serve Locally**  
    - Preview your site locally before pushing changes:  
     ```bash
     mkdocs serve
     ```
5. **Deploy to GitHub Pages**  
    - Push your changes, then deploy:  
     ```bash
     mkdocs gh-deploy
     ```
---

## **Step 7: Share Your Website**
Once your site is live, share your GitHub Pages link with your colleagues, organization, or potential employers!  

---

## **Resources**
- **GitHub Markdown Guide**: [GitHub Docs](https://guides.github.com/features/mastering-markdown/)
- **MkDocs Documentation**: [MkDocs.org](https://www.mkdocs.org/)

With these steps, you’re on your way to creating a functional personal website!

Another useful resource when building a personal website is ChatGPT. If you would like to customize your website, ChatGPT can help provide you with directions on how to achieve the exact characteristics and components you'd like to incorporate into your website.
