---
title: I rebuilt my website the hard way... again
excerpt: >- 
    Having rebuilt my website the hard way last year, I decided to rebuild my website the hard way, again...
date: '2020-09-27'
layout: post
---

Having [rebuilt my website the hard way last year](/blog/i-rebuilt-my-website-the-hard-way), I decided to rebuild my website the hard way, again. 

## Why?

* I learned a lot by building my site with 11ty last year, but I wasn't quite sure how to connect it to a CMS (it doesn't suit me to have to update my website with a code editor on my laptop)
* I wanted to learn more about things like Jekyll and Netlify
* I wanted to tweak the layout a bit but I didn't want to get bogged down doing all the CSS from scratch like I did last year
* Mainly, I just felt like it

## What I did

* Fiddled about with things like [Forestry.io](https://forestry.io/), [Siteleaf](https://www.siteleaf.com/), [Netlify](https://www.netlify.com/) and [Stackbit](https://www.stackbit.com/)
* Concluded that things didn't seem to join up with [11ty](https://www.11ty.dev/) (the static site generator I built my old site on) quite as well as they might with something like [Jekyll](https://jekyllrb.com/)
* ...I've no doubt this conclusion is founded in total ignorance, but nevertheless, overall it felt like a better starting static site generator would have been Jekyll
* Via Stackbit I found the [Exto Jekyll theme](https://github.com/stackbithq/stackbit-theme-exto) – I really didn't want to faff about building something from scratch, so I thought an adaptation of this would do nicely 
* I created a GitHub repo for my new Jekyll-based Exto-based site using Stackbit (I honestly can't remember how but it seemed simple... just head to [Stackbit](https://www.stackbit.com/) and 'Get started')
* I cloned the repo to my machine and started typing relatively random words into Visual Studio Code to get it all to start
* I wrote down "bundle exec jekyll serve" in a note, because there's no way my silly brain will remember this, and it's important because I have to type it into terminal every time I want to load the site
* I fiddled about with the CSS and added content
* It was relatively simple migrating the content from 11ty to Jekyll. I copied the markdown files from the old folder to the new folder (not through Terminal, just drag and drop), then had to tweak the front matter (the bits at the top of the markdown file) to suit Jekyll. I also had to find and replace a few things like the links to images. 
* I connected the repo to Netlify, then pointed my domain to it

## Still to do

* Connect the site up to Netlify CMS if I can, or maybe Forestry – having an easier way to edit it was part of the point, after all

## Reflections

* Jekyll's pretty much the same as 11ty, at least for me – it just seems a bit more standard and connected
* I still don't really know what I'm doing with all this stuff
* I really don't
* I don't like using code editors and terminal – my visual brain prefers to live in GUI world
* So why didn't I just use Squarespace? Good question, I think I just like to learn about the nitty gritty
* Also, I love the speed of a static sites
* Having a personal site like this with the version control from GitHub is just totally pointless, and I just end up writing 'Various' whenever I have to name a commit
* At least, I thought it was until I broke something in Jekyll and had to undo it
* Why isn't there a super simple website builder / CMS built on the power of words, like a super-charged notepad? Or is there? 
