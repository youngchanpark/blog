---
layout: post
title:  "Setting up this Blog"
date:   2020-07-27 18:10:12 +0900
categories: jekyll
---

[Jekyll][jekyll-docs] is a static site generator, helping users to build a
static website with ease. I wanted to write some materials to organise and 
archive some of my thoughts at this time, and I stumbled upon Jekyll on a 
Korean bioinformatics community post.

I thought I'd check it out, and indeed it was easy and free to set up. 

## Basic Set up and Themes

Jekyll's documentation contains easy [step-by-step tutorial][jekyll-step-by-step] on how to set up a basic blog. I myself just went with the [quickstart][jekyll-quickstart] 
version and moved on to choose a theme. 

Jekyll's [Resources](https://jekyllrb.com/resources/) page has several links
which directs you to sites with a collection of pre-made Jekyll themes. I went 
with the simple looking, free [Cayman Blog][cayman-blog] theme. As I was planning
to host the website using GitHub Pages (more on this later), I followed the 
theme's [instructions][cayman-blog-instructions]. 

The dynamicity of the HTML files were driven by the _Liquid_ template language,
which appeared very similar to that of [Django's template language (DTL)][dtl-link] and 
Flask's [Jinja2][jinja2-link]. As I was already familiar with the latter two 
language syntaxes, understanding and modifying the theme's layout HTML files
were not too difficult. The [step-by-step tutorial][jekyll-step-by-step] should be a 
good starting point for those unfamiliar with _Liquid_. 

The contents of the blog is modifiable by editing markdown(`.md` or `.markdown`) 
files. Markdown files were widely used, so I'd imagine most readers would already 
be familiar with the syntax. For those who are unfamiliar, here is a link to a 
[cheetsheet][github-cheatsheet] and a [guide][github-md-guide] from a quick 
Google search.

After filling in the contents of the blog and modifying the theme to my liking,
now was the time for deployment. 


## Hosting using GitHub Pages

GitHub Pages is a service which allow users to host static websites directly
from GitHub repositories. GitHub Pages officially supports Jekyll, so both Jekyll and 
GitHub provides official documentation for deployment:

- Jekyll: [Deploy Jekyll 4 on GitHub Pages][jekyll-deployment]
- GitHub: [Setting up a GitHub Pages site with Jekyll][github-pages-deployment]


[jekyll-docs]: https://jekyllrb.com/docs/
[jekyll-home]: https://jekyllrb.com/
[jekyll-step-by-step]: https://jekyllrb.com/docs/step-by-step/01-setup/
[jekyll-quickstart]: https://jekyllrb.com/docs/
[jekyll-deployment]: https://jekyllrb.com/docs/continuous-integration/github-actions/

[github-cheatsheet]: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
[github-md-guide]: https://guides.github.com/features/mastering-markdown/
[github-pages-deployment]: https://docs.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll

[cayman-blog]: https://github.com/lorepirri/cayman-blog
[cayman-blog-instructions]: https://github.com/lorepirri/cayman-blog#hosting-with-github-pages


[dtl-link]: https://docs.djangoproject.com/en/3.0/ref/templates/language/
[jinja2-link]: https://jinja.palletsprojects.com/en/2.11.x/

