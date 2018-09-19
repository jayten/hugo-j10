+++
title = "Getting started with CFD"

date = 2018-06-10T00:00:00
lastmod = 2018-06-10T00:00:00
draft = true

tags = ["CFD"]
summary = "Brief discussion for people starting their careers in CFD"

[header]
image = "X43A.png"
caption = "Image credit: [**NASA Photo**](https://www.nasa.gov/centers/dryden/multimedia/imagegallery/X-43A/ED97-43968-1.html)"

[[gallery_item]]
album = "1"
image = "post/books/CulbertBLaney.jpg"
caption = "[Buy](http://www.cambridge.org/us/academic/subjects/engineering/aerospace-engineering/computational-gasdynamics?format=PB&isbn=9780521625586)"

[[gallery_item]]
album = "1"
image = "post/books/ECFDRamakrishna.png"
caption = "[Download ECFD](http://www.ae.iitm.ac.in/%7Ekrishna/b/wordpress/ecfd.html)"

[[gallery_item]]
album = "1"
image = "https://raw.githubusercontent.com/gcushen/hugo-academic/master/images/theme-dark.png"
caption = "Dark"

[[gallery_item]]
album = "1"
image = "https://raw.githubusercontent.com/gcushen/hugo-academic/master/images/theme-forest.png"
caption = "Default"

[[gallery_item]]
album = "1"
image = "https://raw.githubusercontent.com/gcushen/hugo-academic/master/images/theme-coffee-playfair.png"
caption = "Coffee theme with Playfair font"

[[gallery_item]]
album = "1"
image = "https://raw.githubusercontent.com/gcushen/hugo-academic/master/images/theme-1950s.png"
caption = "1950s"
+++

**Academic** is a framework to help you create a beautiful website quickly. Perfect for personal sites, blogs, or business/project sites. [Check out the latest demo](https://themes.gohugo.io/theme/academic/) of what you'll get in less than 10 minutes. Then head on over to the [Quick Start guide](https://sourcethemes.com/academic/docs/) or take a look at the [Release Notes](https://sourcethemes.com/academic/updates/).

[![Screenshot](https://raw.githubusercontent.com/gcushen/hugo-academic/master/academic.png)](https://github.com/gcushen/hugo-academic/)

Key features:

- Easily manage various content including homepage, blog posts, publications, talks, and projects
- Extensible via **color themes** and **widgets/plugins**
- Write in [Markdown](https://sourcethemes.com/academic/docs/writing-markdown-latex/) for easy formatting and code highlighting, with [LaTeX](https://en.wikibooks.org/wiki/LaTeX/Mathematics) for mathematical expressions
- Social/academic network linking, [Google Analytics](https://analytics.google.com), and [Disqus](https://disqus.com) comments
- Responsive and mobile friendly
- Simple and refreshing one page design
- Multilingual and easy to customize

## Books

Choice of these books is subjective. There are many more good books
[![Buy](https://books.google.co.in/books/content?id=7h_snAAACAAJ&printsec=frontcover&img=1&zoom=1&imgtk=AFLRE734mh2gUVFrK6ZQS5HYxOSLDbQmLIZhhEhKH8XqJ-_IzChUWuFy-F9SfO0fjCDFknKm9i7-aga-tTAOFUsVnUoAmU8gqe281FT9A0_d5i2dMlyXg6saZPGExkQ_qPbH4MI79waU?display=inline-block)](http://www.cambridge.org/us/academic/subjects/engineering/aerospace-engineering/computational-gasdynamics?format=PB&isbn=9780521625586)
[![Buy](http://assets.cambridge.org/97805216/25586/cover/9780521625586.jpg)](http://www.cambridge.org/us/academic/subjects/engineering/aerospace-engineering/computational-gasdynamics?format=PB&isbn=9780521625586) [![Buy](http://assets.cambridge.org/97805210/09249/cover/9780521009249.jpg)](http://www.cambridge.org/us/academic/subjects/mathematics/numerical-analysis/finite-volume-methods-hyperbolic-problems?format=PB&isbn=9780521009249) [![Download](./img/post/books/ECFDRamakrishna.png)](http://www.ae.iitm.ac.in/%7Ekrishna/b/wordpress/ecfd.html)

{{< gallery >}}

## Install

You can choose from one of the following four methods to install:

* one-click install using your web browser (recommended)
* install on your computer using Git with the Command Prompt/Terminal app
* install on your computer by downloading the ZIP files
* install on your computer with RStudio

### Quick install using your web browser

1. [Install Academic with Netlify](https://app.netlify.com/start/deploy?repository=https://github.com/sourcethemes/academic-kickstart)
    * Netlify will provide you with a customizable URL to access your new site
2. On GitHub, go to your newly created `academic-kickstart` repository and edit `config.toml` to personalize your site. Shortly after saving the file, your site will automatically update
3. Read the [Quick Start Guide](https://sourcethemes.com/academic/docs/) to learn how to add Markdown content. For inspiration, refer to the [Markdown content](https://github.com/gcushen/hugo-academic/tree/master/exampleSite) which powers the [Demo](https://themes.gohugo.io/theme/academic/)

### Install with Git

Prerequisites:

* [Download and install Git](https://git-scm.com/downloads)
* [Download and install Hugo](https://gohugo.io/getting-started/installing/#quick-install)

1. [Fork](https://github.com/sourcethemes/academic-kickstart#fork-destination-box) the *Academic Kickstart* repository and clone your fork with Git: 

        git clone https://github.com/sourcethemes/academic-kickstart.git My_Website
    
    *Note that if you forked Academic Kickstart, the above command should be edited to clone your fork, i.e. replace `sourcethemes` with your GitHub username.*

2. Initialize the theme:

        cd My_Website
        git submodule update --init --recursive

### Install with ZIP

1. [Download](https://github.com/sourcethemes/academic-kickstart/archive/master.zip) and extract *Academic Kickstart*
2. [Download](https://github.com/gcushen/hugo-academic/archive/master.zip) and extract the *Academic theme* to the `themes/academic/` folder from the above step

### Install with RStudio

[View the guide to installing Academic with RStudio](https://sourcethemes.com/academic/docs/install/#install-with-rstudio)

## Quick start

1. If you installed on your computer, view your new website by running the following command:
      
        hugo server

    Now visit [localhost:1313](http://localhost:1313) and your new Academic powered website will appear. Otherwise, if using Netlify, they will provide you with your URL.
           
2. Read the [Quick Start Guide](https://sourcethemes.com/academic/docs/) to learn how to add Markdown content, customize your site, and deploy it. For inspiration, refer to the [Markdown content](https://github.com/gcushen/hugo-academic/tree/master/exampleSite) which powers the [Demo](https://themes.gohugo.io/theme/academic/)

3. Build your site by running the `hugo` command. Then [host it for free using Github Pages](https://georgecushen.com/create-your-website-with-hugo/) or Netlify (refer to the first installation method). Alternatively, copy the generated `public/` directory (by FTP, Rsync, etc.) to your production web server (such as a university's hosting service).

## Updating

Feel free to *star* the project on [Github](https://github.com/gcushen/hugo-academic/) to help keep track of updates and check out the [release notes](https://sourcethemes.com/academic/updates) prior to updating your site.

Before updating the framework, it is recommended to make a backup of your entire website directory (or at least your `themes/academic` directory) and record your current version number.

By default, Academic is installed as a Git submodule which can be updated by running the following command:

```bash
git submodule update --remote --merge
```

[Check out the update guide](https://sourcethemes.com/academic/docs/update/) for full instructions and alternative methods.

## Feedback & Contributing

Please use the [issue tracker](https://github.com/gcushen/hugo-academic/issues) to let me know about any bugs or feature requests, or alternatively make a pull request.

For support, head over to the [Hugo discussion forum](http://discuss.gohugo.io).

## License

Copyright 2016-present [George Cushen](https://georgecushen.com).

Released under the [MIT](https://github.com/gcushen/hugo-academic/blob/master/LICENSE.md) license.
