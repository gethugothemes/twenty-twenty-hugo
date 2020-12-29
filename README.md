**This theme is ported from [WordPress Twenty Twenty](https://github.com/WordPress/twentytwenty) Themes.**

# Easy Setup (Hugo + Netlify + Forestry)
Build your website with Twenty Twenty Hugo theme by following this easy steps (No Coding Required)

<a href="http://bit.ly/meghna-hugo-installation" target="_blank" title="meghna hugo installation" rel="nofollow"><img width="100%" src="https://user-images.githubusercontent.com/37659754/70844354-4028be00-1e6a-11ea-8d84-02e9a25e7db8.png"></a>

In this tutorial we will show you to make your website live without buying any hosting and touching a single line of code. We made this tutorial based on [meghna hugo](https://github.com/themefisher/meghna-hugo) but you can setup everithing like this.

### What you need !!

1. Git acccount (Ex: Github, Gitlab etc ) . In our case we use github.
2. [Netlify](https://bit.ly/netlify-account) account to host files and add custom domain .
3. [Forestry](https://bit.ly/forestry-account) account to maintain whole project without code.


### Step 1 : Fork or Clone repository

First we will fork this [Twenty Twenty Hugo](https://github.com/themefisher/twenty-twenty-hugo) template.

### Step 2 : Add your repository in Forestry

Go to your [forestry](https://bit.ly/forestry-account)  account and click on `import your site now`. declare your config.toml file [`exampleSite`] and fill up basic settings . Mark everything is done then go to configuration to change the base url . You can put any url but this have to similar as netlify . So for now put a name which you are going to put in netlify as netlify subdomain.

### Step 3 : Setup and host website with Netlify

Here comes the last step . Go to your [netlify](https://bit.ly/netlify-account) account and click add new site . Choose your git repository to import your website in netlify .  And now you can see the forked `parsa hugo` theme. select it and follow the steps. Then go to `site settings` for change the site name and put your subdoamin name here what you puted on forestry as base url. save it and go to `deploy` from top menu, Wait a while and click on `site preview` or just simply go to the subdomain you puted as base url. **BOOM! Your site is live.** Now you can go to forestry and add, remove or customize every setting and content.

> If you face any issue regarding the installation feel free to onen [open a new issue](https://github.com/themefisher/twenty-twenty-hugo/issues)


## Table of Contents

- [Demo](#demo)
- [Installation](#installation)
- [Reporting Issues](#reporting-issues)
- [Technical Support or Questions](#technical-support-or-questions-(paid))
- [Licensing](#licensing)
- [More Hugo Themes](https://themefisher.com/hugo-themes/)


## Demo

| ![Home](https://user-images.githubusercontent.com/37659754/80334182-4300da00-8872-11ea-8fec-bd66725b3897.png) | ![Blog](https://user-images.githubusercontent.com/37659754/80334180-41371680-8872-11ea-8790-54f5c823587a.png) | ![Contact](https://user-images.githubusercontent.com/37659754/80334178-3f6d5300-8872-11ea-9ece-5bd848d65f84.png)| ![About](https://user-images.githubusercontent.com/37659754/80334176-3d0af900-8872-11ea-885e-e5da6760e21f.png) | ![Sample-Page](https://user-images.githubusercontent.com/37659754/80334171-39777200-8872-11ea-94e6-905c7d4c8ee7.png) |
|---|---|---|---|---|
| Homepage  | Blog  | Contact  | About  | Sample Page  |

[Live Preview](http://demo.themefisher.com/twenty-twenty-hugo/).


## Installation
At the top we have shown an easy hugo installation. but still if you think you want to go with the traditional way then use the following commands:

```
$ git clone https://github.com/themefisher/twenty-twenty-hugo.git
$ cd twenty-twenty-hugo/exampleSite/
$ hugo server --themesDir ../..
```

## Reporting Issues

We use GitHub Issues as the official bug tracker for the **Twenty Twenty Theme**. Please Search [existing issues](https://github.com/themefisher/twenty-twenty-hugo/issues). It’s possible someone has already reported the same problem.
If your problem or idea is not addressed yet, [open a new issue](https://github.com/themefisher/twenty-twenty-hugo/issues/new)

## Technical Support or Questions (Paid)

If you have questions or need help integrating the product please [contact us](mailto:mehedi@themefisher.com) instead of opening an issue.

## Licensing

- Copyright 2020 Designed by [Themefisher](https://themefisher.com/) & Developed by [Gethugothemes](https://gethugothemes.com/)
- Licensed under GPLv2 (https://github.com/themefisher/twenty-twenty-hugo/blob/master/LICENSE)
## Premium Themes

| [![Mega-Bundle-HUGO](https://gethugothemes.com/wp-content/uploads/edd/2019/09/Mega-Bundle-HUGO.png)](https://themefisher.com/products/hugo-mega-bundle/) | [![galaxy](https://gethugothemes.com/wp-content/uploads/edd/2020/04/galaxy.png)](https://gethugothemes.com/products/galaxy/) | [![logbook](https://gethugothemes.com/wp-content/uploads/edd/2020/03/logbook-hugo.jpg)](https://gethugothemes.com/products/logbook-hugo/) |
|:---:|:---:|:---:|
| **Hugo Mega Bundle**  | **Galaxy**  | **LogBook**  |