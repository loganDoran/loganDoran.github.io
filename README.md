# Hosting Your Resume on GitHub Pages
## Purpose
This README provides instructions for hosting a resume on GitHub Pages while demonstrating technical writing principles from "Modern Technical Writing" by Andrew Etter.   

![](resumeGif.gif)
## Prerequisites
To follow this guide, you need:
- A resume formatted in Markdown
- A GitHub account
- Basic knowledge of Markdown syntax

For a Markdown tutorial, see the '[more resources](#more-resources)' section below.
## Instructions

### Step 1: Set Up GitHub Pages
1. Log in to your GitHub account.
2. Create a new repository with the name `username.github.io`, replacing `username` with your GitHub username.
Make sure it's public!
<!-- gif -->
<!-- explain better how to do this -->

Hosting your resume on a distributed version control system, such as GitHub, allows for version control and collaboration on the site.
<!-- share/host on a distributed control system -->

### Step 2: Upload your Markdown formatted resume

1. Upload your Markdown resume file to your newly created repository.

A lightweight markup language recommended by Andrew Etter in "Modern Technical Writing." Markdown allows for easy formatting of text without dealing with 
<!-- use a lightweight markup language -->

### Step 3: Customize Your Resume
Use Jekyll as a static site generator for easy document formatting.
1. Create a `_config.yml` file: In your repository, create a file named `_config.yml`.
2. Add theme configuration: Inside the `_config.yml` file, include the following line to specify the theme for your resume: `theme: [theme_name]`Replace `[theme_name]` with the name of the Jekyll theme you want to use.
3. Save the changes: Commit the `_config.yml` file to your repository to apply the theme configuration.
<!-- Format a document with a static site generator -->

## More Resources
- [Markdown Tutorial](https://markdowntutorial.com/)
- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [Adding theme to GitHub Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll)

## Authors and Acknowledgments
Special thanks to (person who does peer review) for their feedback and support.

## FAQs

### Why is Markdown better than a word processor?
Markdown offers a lightweight and easy-to-read syntax for formatting text without the distractions of complex word processors. It also integrates seamlessly with version control systems like Git.

### Why is my resume not showing up?
Ensure that your Markdown file is named correctly (`index.md`) and located in the correct repository branch. Also, check the repository settings to ensure GitHub Pages is enabled and configured correctly.
