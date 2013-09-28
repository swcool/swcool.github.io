---
layout: post
title: Build A Blog Website Using Octopress
category: blog
tags: [jekyll, github] 
---

## What is Octopress?[1]

Octopress is [Jekyll](https://github.com/mojombo/jekyll) blogging at its finest.

1. **Octopress sports a clean responsive theme** written in semantic HTML5, focused on readability and friendliness toward mobile devices.
2. **Code blogging is easy and beautiful.** Embed code (with [Solarized](http://ethanschoonover.com/solarized) styling) in your posts from gists, jsFiddle or from your filesystem.
3. **Third party integration is simple** with built-in support for Twitter, Pinboard, Delicious, GitHub Repositories, Disqus Comments and Google Analytics.
4. **It's easy to use.** A collection of rake tasks simplifies development and makes deploying a cinch.
5. **Ships with great plug-ins** some original and others from the Jekyll community &mdash; tested and improved.

## Setup and Deploy in Github
  1. `git clone git://github.com/imathis/octopress.git octopress`
  1. `cd octopress; bundle install`
  1. `rake install`  # Install the default Octopress theme
  1. set up a project name "username.github.com" on GitHub  
  1. `rake setup_github_pages` This will:  
      1. Ask you for your Github Pages repository url.
      2. Rename the remote pointing to imathis/octopress from ‘origin’ to ‘octopress’
      3. Add your Github Pages repository as the default origin remote.
      4. Switch the active branch from master to source.
      5. Configure your blog’s url according to your repository.
      6. Setup a master branch in the _deploy directory for deployment.
  1. `rake generate`
  1. `rake deploy`
  1. Don't forget to commit the source
      1. `git add .`
      2. `git commit -m "my message"`
      3. `git push origin source`

## In Local Source Branch

  1. edit _posts post (or use create_post to generate)
  2. `rake generate`
  3. `rake preview` (check local)
  4. `rake deploy` ( deploy on github page)
  5. `git add .`
  6. `git commit -a -m "update"`
  7. `git push origin source`

  * Wrap 2-7 step in a bash shell:

```bash
        rake generate
        rake deploy
        git add .
        git commit -m "update"
        git push origin source
```

## Reference

  * [Octopress](https://github.com/imathis/octopress)  
  * [Jekyll](https://github.com/mojombo/jekyll)  
  * [1] The answer is from [Octopress's README](https://github.com/imathis/octopress/blob/master/README.markdown)
