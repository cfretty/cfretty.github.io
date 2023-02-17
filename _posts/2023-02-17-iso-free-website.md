---
title: 'In search of a free personal website'
date: 2023-02-17 08:00:00 -0600
categories: [Technology]
tags: [blog,docs as code,github pages,website,wordpress]  # TAG names should always be lowercase#
image:
  path: /assets/img/notebooklaptop.png
  alt:  a notebook and laptop
---
<!-- excerpt -->
*My experience creating a free personal website using two popular options: WordPress.com and GitHub Pages.*

This winter I built a personal website. Well, two (and a half) websites. There are many products and options out there, it can be overwhelming. Defining my requirements helped me focus my research:
1. Free. Spend no money, not even on a domain name.
2. Learn about a new (to me) framework.
3. If possible, find more than one option and compare. Try to use similar design themes.
4. No code or low code, easy to maintain.

I chose WordPress.com and GitHub Pages. Check out my websites:
* [https://charityfretty.wordpress.com](https://charityfretty.wordpress.com){:target="_blank" rel="noopener"}
* [https://cfretty.github.io](https://cfretty.github.io){:target="_blank" rel="noopener"}

My evaluation is below, but ***which do you prefer? Why?*** I would appreciate your feedback. Shoot me a message or comment on LinkedIn, or email me.

# WordPress.com 
Released in 2003 as a blogging platform, WordPress is a popular content management system (CMS). Released in 2005, WordPress.com is a website builder service that uses the CMS in the background to help you build a website using no (or little) code. WordPress.com also provides managed hosting. In other words, you don't have to download WordPress software, create the site, and manage it on a server or hosting service. With WordPress.com you can get started with little or no overhead and add functionality--for a fee--as you grow.

## Pros and cons of WordPress.com
Pros: 
* The website you see is free. It uses the wordpress.com domain name. You can use a custom domain name.
* Lots of documentation, training courses, and videos are available from WordPress and others.
* You truly need no coding experience to build a site. WordPress Editor (aka Block editor, fka Gutenberg) is easy to use, especially if you understand a little about HTML markup. It’s especially easy to add links and images using this editor.
* Comments and stats (traffic, site insights) are free and easy to use.
* It took longer to select a theme than it did to get my site published. It took less than one day to get the basic site with two static pages (home, about) and two or three posts. This included time to review the getting started guide and too much time spent messing around with image files.

>***Side rant*** Content teams: If you want people who are not full-time writers to contribute structured content, you :100: need a UX like WordPress Editor (Block editor).
{: .prompt-tip }

Cons: 
* There are ads, annoying and unprofessional. I thought this might be due to the theme I selected, but it seems not. [Free sites have ads.](https://wordpress.com/support/no-ads/){:target="_blank" rel="noopener"}
* Free themes are difficult to identify and use. I struggled and still don't fully understand how page templates get applied and I have thrown up my hands on some things like featured images.
* There are lots of customization options and features, though it seems most require a paid subscription.
* While the block editor is easy to use, I want to use offline editors to write posts. I end up copying and pasting my posts into the editor. This is not an ideal workflow. You can configure Wordpress.com to use [markdown](https://en.wikipedia.org/wiki/Markdown){:target="_blank" rel="noopener"} but I haven't looked into it yet.
* So. Many. Emails from WordPress. They want you to pay, but I have a feeling even if I subscribed, the offers and reminders in my email wouldn't stop.
* SEO tools are unavailable on the free tier.

# GitHub Pages
Released in 2008, the same year as GitHub itself, GitHub Pages is a static site hosting service. It takes files from a repository on GitHub, if needed runs the files through a build process, and publishes a website. GitHub pages can use HTML, CSS, and JavaScript files directly, or you can use a [static site generator](https://en.wikipedia.org/wiki/Static_site_generator){:target="_blank" rel="noopener"} to generate files from text input files. 

The first version of my GitHub Pages site (the "half" site) was a simple HTML-based single-page site. There are plenty of free templates available (see [One Page Love](https://onepagelove.com/){:target="_blank" rel="noopener"}). I made some edits, replaced the images, and that was it. 

But I wanted to learn more about static site generation. In the technical writing industry, *Docs as Code* is an important strategy. This refers to developing documentation using the same tools and processes as developing code. In other words, author docs in plain text files, manage files using version control, and build web output using static site generators. At my last job, to help with a migration project, we designed and built a tool that generated static HTML pages from markdown text files, but I didn't have the time to play with any actual static site generators.

## Pros and cons of GitHub Pages
Pros
* The website you see is free. It uses the github.io domain name and is part of the GitHub free tier. You can use a custom domain name. GitHub is a hosting service for software development and version control. Many people who want to learn about software development or want to collaborate on software already have GitHub accounts. Including me.
* The website is ad-free. To be fair, it seems some static site generator themes also include ads. If you find a free theme, star the repository and consider sponsoring the project.
* Lots of documentation, tutorials, and videos are available from GitHub and others.
* The HTML-based first version took only minutes to get up and running. The static site generator-based version using a theme with a starter took a couple of hours. But I am comfortable with HTML, markdown, and source code management.
* Markdown files are familiar and easy for me to write, though I did install a spelling and grammar checker plugin for Visual Studio Code.

Cons
* You do need technical know-how to configure the build and deployment of the website in GitHub, and you need to use Git to manage it.
* There are tons of customization options, but you will need to learn about the static site generator and its languages.  
* Comments and stats are available, but not out of the box, I need to research and do some coding to enable them. Comments may require a GitHub account, so if I want to engage with a wider audience, this may not work.

# My takeaway and next steps
For a no-code solution, WordPress.com is great. Though I will have to learn a lot more about the product and ultimately I will have to pay for the features and configurability I want. If I had a product or service to sell or wanted to monetize a site and I wanted to focus on the business, then WordPress.com is a good option. (Though to be clear, it's one of many, many options, and if I am paying, then I would compare WordPress to the other top vendors before making my choice.)

Honestly, for me, managing text files in a source code management system is familiar and enjoyable. As long as I am learning more about software development, open source, and Docs as Code, GitHub Pages is the more natural fit.

The decision for which platform I ultimately choose depends on my needs and goals for the website. These goals are not defined for me quite yet.

So, while I continue to experiment and gather feedback, I will maintain both sites for a time.

Next steps:
* figure out how to streamline and automate creating and publishing posts in both frameworks
* enable comments in GitHub
* stats in GitHub
* SEO in both frameworks

# References
[https://wordpress.com/support/getting-started-with-wordpress-com/](https://wordpress.com/support/getting-started-with-wordpress-com/){:target="_blank" rel="noopener"}

A developer's post about moving to a Jekyll (a type of static site generator) site from WordPress (Ooo! Theme twins. I see the Chirpy theme everywhere now.) [https://heidloff.net/article/welcome-to-new-jekyll-based-blog/](https://heidloff.net/article/welcome-to-new-jekyll-based-blog/){:target="_blank" rel="noopener"}

[https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages){:target="_blank" rel="noopener"}

[https://www.writethedocs.org/guide/docs-as-code/](https://www.writethedocs.org/guide/docs-as-code/){:target="_blank" rel="noopener"}

[https://idratherbewriting.com/trends/trends-to-follow-or-forget-docs-as-code.html](https://idratherbewriting.com/trends/trends-to-follow-or-forget-docs-as-code.html){:target="_blank" rel="noopener"}

_Photo by [Trent Erwin](https://unsplash.com/it/@tjerwin?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText){:target="_blank" rel="noopener"} on [Unsplash](https://unsplash.com/photos/UgA3Xvi3SkA?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText){:target="_blank" rel="noopener"}_
  