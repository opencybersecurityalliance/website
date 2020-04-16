[![Netlify Status](https://api.netlify.com/api/v1/badges/e7bc3ca8-6e6c-4de7-8e58-886e9e68eacb/deploy-status)](https://app.netlify.com/sites/pedantic-sinoussi-974ee3/deploys)

# Open Cybersecurity Alliance Website Repository

This repository houses the content for [our website](https://opencybersecurityalliance.org/). It is forked from the OASIS static site template for open projects. It makes use of Hugo, a customizable Hugo theme, github-driven deployment, and hosting with Netlify. For more information about these tools, see:

* https://gohugo.io/about/
* https://themes.gohugo.io/gohugo-theme-ananke/
* https://gohugo.io/hosting-and-deployment/hosting-on-netlify/

## Updating and Maintaining the Website

This template assumes you are comfortable with git-based development workflows and have experience downloading & installing new software packages for your operating system. An understanding of HTML is helpful, as is basic understanding of Markdown. 

### Quick Start

* [Install Hugo](https://gohugo.io/getting-started/installing/). Hugo's dependencies are [git](https://git-scm.com/) and [Go](https://golang.org/dl/). 
* Clone the repository. After you clone, you'll need to cd into the /template folder and run `git submodule update --init`. In your terminal, type `hugo server` then navigate to localhost:1313 to see the site display in the browser.
* Update the template's config.toml file to reflect the correct information for your open project. You can add posts, pictures, sponsor files, etc. See below for more information on customizing your site. 
* Be sure to check your terminal and localhost for any errors you may be introducing while you are making changes. By default, the Hugo server continuosly watches for changes and updates localhost for you, so you don't have to stop and restart the server constantly. Type `hugo server -help` for more command line server tools.
* Save & push your changes to a branch on your fork which you intend to use as the production branch for your website.
* Let the OASIS Open Project Administrator know that you're ready to deploy your site. OASIS will take care of setting up DNS and hosting. We are currently using Netlify for this service. It only takes a few moments once this is wired up for the site to start propagating through the DNS system.

### Updating Content & Styling 

In your new website repo, you can update posts, pages, images, project sponsors, the `config.toml` file, and project-specific layouts. Things you can do to customize your site:

1. Update the strings in the `config.toml` file - this is where you will put links to your social media accounts, contact emails, project logo, etc. 
1. Add your own images and logo to the /static/images directory
1. Update the content on the main and about pages
1. Add your own posts in the 'news' section

#### Content
Content files are written in Markdown, with .yaml headers to define any meta-data about that content (title, date, draft status, author, etc). All content files must live in the 'content' directory. Keep in mind that the URL of a given piece of content will be the file path followed by the name of the markdown file. For example, if you have a file called 'examples.md' living in the 'news' directory of your content folder, the URL will be 'yourwebsite.com/news/example'. Content that is not included in a subdirectory (e.g. content/news/example.md) is rendered as a top-level item and will show up in your main navigation.

#### Styling
Content is rendered by its corresponding HTML layout, which lives in the layouts directory. If no layout has been defined, it will use the theme's default layouts (found in /themes/ananke/layouts/_default). If you want to create your own custom layout for a section, you can add that .html file to your own /layouts folder. Note that the structure of the content directory mirrors that of the layout directory. 

This theme uses the [Tachyons](https://tachyons.io/#style) grid and style system. You can customize your site further by updating the classes in your html layouts to use different Tachyon styles - for example, you can change a font to Garamond by adding the .garamond class to your section or div. You can also add custom CSS styling in the /static/css/custom.css file. You can set the background color and other basic styling as well using tachyon classes in the config.toml file. 

#### About the Theme Directory
The theme directory is where the default styling, templates & partials, and other page logic lives. Hugo themes are installed as submodules - that means that although you may see it in your code editor, the code actually lives in a different repository. OASIS has a fork of the Ananke theme in order to provide some customizations for Open Projects by default, but projects can easily install [other Hugo themes](https://themes.gohugo.io/) or make their own. 

If you want to change files in the /themes directory, you will need to submit those as a PR to OASIS's theme repository or fork it and point the theme submodule to your own fork. You will need to do this before changes to your site will deploy successfully. 

## Deploying Changes
If you are updating your site - meaning that you are adding or editing content, images, or configs - all you have to do to deploy those changes (once you've tested them locally, of course) is push or merge changes into to your production branch. Netlify automatically rebuilds and deploys the site for you. If for some reason the build fails, the latest successful build remains live. 

 Any file located in the theme directory actually lives in the theme submodule's repo, not in your repo. If you want to update the theme in some way, you can:

1. add your own layouts, partials & styling into the appropriate directories on your website repo (recommended)
1. fork the OASIS theme repo; make whatever changes they'd like to make and the fork in as the theme submodule
1. file an issue or PR against the OASIS theme repo to incorporate changes that may improve the theme for all projects
1. choose an altogether different theme at https://themes.gohugo.io, or roll your own custom theme entirely

If you've made changes to the theme directory, you will need to push those changes to the appropriate theme repo. You will also need to trigger Netlify to rebuild the site, which you can do from the Netlify dashboard.

