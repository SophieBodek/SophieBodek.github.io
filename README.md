## Introduction
This template utilizes Jekyll, an open source static website generator, as well as a theme based largely off of the Minimal Mistakes theme by Michael Rose. The purpose of this template is to provide you (i.e., me) with a simple, well designed website that is optimized for hosting on Github pages. We aim to reduce the technological know-how and time that is usually required for maintaining a personal or professional website.

## [Getting Started Guide](https://ncsu-libraries.github.io/jekyll-academic-docs/)
Complete documentation for getting started as well as advanced features of Jekyll Academic can be found at [https://ncsu-libraries.github.io/jekyll-academic-docs/](https://ncsu-libraries.github.io/jekyll-academic-docs/).

<!--
#### Why Should I Use This?
By using this template you will have a website that is well designed, easy to maintain, free to host and easy to update. While there are many options out there for personal and professional websites, most are dependant on the platform on which they were built, and cannot be easily migrated. This template, while built for Github Pages integration, provides flexibility should you choose to host it elsewhere.
-->

## Reminders (for me)
What to do when you want to update/modify your webpages:

### About Me/Personal Info
- To modify social media handles, etc., update *_config.yml* (this is also where the color highlight/lowlight for the heading can be changed); if you want to add new networking websites or other bio information not already included in *_config.yml*, modify *_includes/_author-bio.html*.
- To modify the homepage (i.e., the "about me" section), edit the *index.md* markdown document.
- Change the *favicon.png* image to change the icon on the webpage tab.

### Research
- To edit an extant research project webpages, modify the relevant markdown document in the *_posts* folder (e.g., *_posts/2026-9-5-research-stochastic_bedload.md*).
- To add new research project as a webpage, create a new markdown document:
  - Include date in the document name (I think they are ordered by date); the part of the title after the date is the name of the webpage in the url.
  - In the markdown document header, include a title, short excerpt, and image that appear on the **Research** webpage. If no excerpt is included, defaults to showing the first several lines of the text on the research project webpage.
  - The image can be specified to be vertical (i.e., to the left of the excerpt text) or horizontal (i.e., on top of the excerpt text).

### Teaching/Mentoring/Outreach
Edit the markdown document *teaching.md*. 

### Publications
- To add/edit entries, modify *_data/publications.yml*.
- To change format of the citations themselves, modify *_includes/publication_entry.html*.
- If you change the color scheme of the highlight/lowlight in the heading, you will also want to change the color of the article titles in *_sass/publications.scss* (they currently match). 

### CV
Edit the markdown document *cv.md*; this primarily entails updating the hyperlink to a document hosting page with the actual CV pdf. Right now, the pdf is hosted on docdroid. 


<!--
## Migrating to a new default branch name
We've decided to change this project's default branch name to 'main'.  If you've forked this repository prior to July 20th, 2021, then you should a message with update instructions when you go to your fork in github: 

![fork renamed message](https://user-images.githubusercontent.com/3514165/126372022-ae4c07fa-dec7-427c-a4b5-cdd73aec75eb.png)

In your fork on GitHub, go to the branches view, and click on the edit icon next to the 'master' branch.  Change the branch name to main.  Underneath the input box where you change the name you will be presented with the commands that you will need to run on your local copy of your fork.

![local instructions for default branch name change ](https://user-images.githubusercontent.com/3514165/126372635-208fbc4b-698e-4938-bdae-5ff19eed2c96.png)


## Upgrade Notes for June 2021 release
If you are running a fork of Jekyll Academic before June 2021, we made some breaking changes to upgrade the underlying Jekyll version and to address the constant github/dependabot security notices mentioned in issue #4.

We have updated Jekyll to version 4 and removed reveal.js as an included library. We still want to support reveal.js presentations, so we have taken the suggestion from issue #4 and made the reveal.js directory a [git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules). If you are running Jekyll Academic as a Github Page, this should hopefully be a minor change.

If, however, you are running Jekyll Academic locally or on a custom server, after merging this repo's commits in to your fork, you will need to go to the command line in your local or custom instance and perform the following command:

  `$ git submodule update --init`

If you have any reveal.js presentations posted, you may need to make some updates for them to display properly using reveal.js version 4.  See [Jekyll's documentation](https://revealjs.com/upgrading/) for details.

## Keeping reveal.js up to date
Moving forward, if you'd like to update reveal.js you will need to run the following commands:

  `$ git submodule update --remote`
-->
