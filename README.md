## Setting up your Project Website

<img align="right" width="100" height="100" src="https://picsum.photos/100/100">

### How to copy this site as a template
1.  Create [a GitHub account](https://github.com/)
2.	Create a new GitHub repository with the name **user.github.io**, where **user** is your GitHub username as shown below. Select *public* and do not tick *Add a README file*. [![screenshot][1]][1]
3.	From your new repository, you should see a *Quick setup* guide. Scroll down to the bottom of the page and click *Import code*, as shown: [![screenshot][2]][2]
4.	In the box that says *Your old repository’s clone URL*, copy and paste this URL: `https://github.com/atmosalex/atmosalex.github.io/`, then proceed.
5.	Go to the *Settings* tab, then click *Pages* (under *Code and automation*), and check that the *Build and deployment* section looks like this: [![screenshot][3]][3]
6.	Go to the *Actions* tab and check that the build and deployment action has finished. Once it has, navigate to user.github.io to see your site, which should be a copy of this one!

[1]: /assets/IMG/instr_create.png
[2]: /assets/IMG/instr_import.png
[3]: /assets/IMG/instr_bd.png

### How to change the theme (optional)
1.	You can choose a different theme [from this page](https://pages.github.com/themes/).
2.	Open `_config.yml` and replace `theme: jekyll-theme-minimal` with `theme: jekyll-theme-name` where `name` is the name of the theme from the above list. **Only the `minima` theme works with the shortened preface `theme: `**, the others seem to need the whole preface `theme: jekyll-theme-`. You can check the *Actions* tab (as in step 6. above) to make sure the site is building successfully.

### How to change your site logo (optional)
1. Some themes, such as `jekyll-theme-minimal`, show a logo. In your repository, upload a logo or profile picture to the `assets/IMG/` directory
2. Open `_config.yml` and modify the line `logo: /assets/IMG/template_IMG.png` to point to your new image

### Adding content
* The `README.md` file (the file you are reading now) acts like a home page. Replace its contents with whatever you want the world to see.
* Check a [guide to writing Markdown](https://www.markdownguide.org/basic-syntax/), or ask [ChatGPT](https://chat.openai.com/) for help.
* You can create other markdown files (.md) in your repository and navigate to them from this page using links, i.e.: [here is a link to `project.md`](project.md)
* When editing a markdown file on GitHub's website, it is useful to wrap text by selecting the *Soft wrap* option as shown: [![screenshot][4]][4]
  
[4]: /assets/IMG/instr_wrap.png

***

## Linking to your Project

Your final report should be delivered via your website. There are two components required:
* A link to a separate repository on GitHub with your project code (best option), or a link to download the code from a directory in your website repository.
* A link to download the report. It is recommended to write the report using a word processor or Latex, then export it as a .pdf file and upload it to the `assets` directory. Link to it [like so](/assets/project_demo.pdf).
