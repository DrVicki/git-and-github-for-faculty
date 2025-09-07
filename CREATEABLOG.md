# Create & Deploy Blog with GitHub Pages

Creating a simple blog using Markdown files is a great final project to combine writing documentation with version control and GitHub. 

We'll use **GitHub Pages** to host the blog and **Markdown** for each blog post. 

- Here's a step-by-step guide to setting up your Markdown-based blog:

## Final Project: Create a Simple Blog with Markdown

### Project Overview:
You'll learn how to:
- Write blog posts using Markdown.
- Organize these posts in a GitHub repository.
- Host the blog using GitHub Pages.

## Step-by-Step Instructions:
1. Set Up the Repository
    - Create a New Repository on GitHub
    - Go to your GitHub account.
    - Click the "**New**" button to create a new repository.

- Name it ``my-markdown-blog``.
- Initialize the repository with a ``README`` (optional). 
- No need to add any licensing or ``.gitignore`` files at this point.
- Click "**Create repository**."

2. Clone the Repository Locally
``git clone https://github.com/YourUsername/my-markdown-blog.git``

- Replace ``YourUsername`` with your actual GitHub username.
- Navigate into your repository:
``cd my-markdown-blog``

3. Create Your Blog Structure
- Set Up Markdown Posts
    -Inside ``my-markdown-blog``, create a directory called    ``_posts`` which will contain all your blog post files:

``mkdir _posts``

4. Write Your First Post
- Navigate into the ``_post`` directory:
``cd _posts``
- Create a new Markdown file with a specific naming convention: ``YYYY-MM-DD-title.md``, for example:
``touch 2023-10-25-my-first-blog-post.md``
- Write Your Post Content
    - Open your Markdown file in a text editor (e.g., VSCode, Sublime Text):
    - Begin writing your content in the file:

---
layout: post
title: "My First Blog Post"
date: 2025-09-09
categories: blog update
---
​
# Welcome to My First Faculty Blog Post!
​
This is my first post using Markdown. It's a simple and effective way to format my thoughts!
​
- I am learning Git and GitHub not just for me, but to benefit my students.
- GitHub is a typical requirement in a majority og technolo0gy and design careers.
- GitHub supports Markdown, which makes it integrate well with version control, and supports teams and collaboration.
​
Stay tuned for more updates!

5. Configure GitHub Pages
- Set Up GitHub Pages
    - Go to your repository on GitHub.
    - Click on the "**Settings**" tab.
    - Scroll down to the "**Pages**" section in the menu on the left.
    - Under "**Source**," select the branch you want to serve (usually ``main``) and choose ``/root`` for the folder.
    - Click "**Save**."

6. Commit and Push Your Changes
- Add and Commit Your Files
    - Add your changes to the staging area:
``git add .``
    - Commit your changes:
``git commit -m "Add first blog post using Markdown"``

- Push Your Changes to GitHub
``git push origin main``

7. View Your Blog
- After pushing, it might take a few minutes for GitHub Pages to publish your site.

- The default URL is: ``https://YourUsername.github.io/my-markdown-blog/``

- Replace ``YourUsername`` with your actual GitHub username.
- Open this URL in a browser to view your blog live!

8. Expand Your Blog
- Add More Posts: Repeat the process to add more posts to the ``_posts`` directory.
Customize: Optionally, add a CNAME file for a custom domain or customize using Jekyll themes for a more sophisticated look.
Conclusion:
With just a few files and some basic Markdown knowledge, you've set up a simple, yet effective blog using GitHub Pages. This workflow introduces Markdown, Git version control, and the concept of static site generation, a skill set that's valuable for both professional documentation and personal projects.