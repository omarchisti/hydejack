---
layout: post
title: Learning Jekyll...
description: An intro post
noindex: true
---
Hi Folks. Thanks for visting my github page. At some point I may add some more
content here, but don't hate if it is sparse for quite some time! This was
mainly an opportunity to play with Jekyll themes and github pages. Basically
Jekyll is a ruby parser that will take markdown files and convert to static
html. It's supported natively by github pages for easy hosting.

A few learnings:
----------------

I tried many of the jekyll themes. I couldn't get many to work (I'm sure it was
user error), but the two I did have success with were:

\- <https://hydejack.com/docs/> (The theme you are looking at right now is
hydejack.)

\- <http://jekyllthemes.org/themes/materialize/>

### Here are some notes on installing the materialize theme.

Ok so the basics...

I started here:

<http://www.stephaniehicks.com/githubPages_tutorial/pages/githubpages-jekyll.html>

#### **Step 1**: Install the software you need to be able to compile and run the themes locally

Jekyll install

1: Install Ruby via https://www.ruby-lang.org/en/downloads/

2: Install bundler

\$ gem install jekyll

#### **Step 2**: Using basic jekyll

<http://www.stephaniehicks.com/githubPages_tutorial/pages/githubpages-jekyll.html>

The steps on here to basically used to install a jekyll site and then run
locally. (This can later be pushed to github and turned on live)

Basically follow the steps on the stephanie hicks site, but the key commands to
run locally:

jekyll new myrepo= the folder you want to create

\$ jekyll new myrepo

move to the new directory you just created, then:

\$ jekyll build

\$ jekyll serve

To view the website locally, go to <http://localhost:4000>.

some key files are:

\_config.yml

gemfile

You may have to edit these to get a theme to work.

#### **Step 3**: Installing jekyll materialize theme

<http://jekyllthemes.org/themes/materialize/>

Note, if you are just pulling this down from an already running github, you
don't have to do this, otherwise this is to install and run from scratch
locally.

Steps:

Assuming Step 1 was done.

Assuming Step 2 was done and you want to use that folder as a Jekyll folder. If
Not, go back to step two and create a new directory where you will isntall the
jekyll materialize theme.

Visit this site:
<https://github.com/macrod68/jekyll-materialize-starter-template>

1. Download the entire zip file to your local computer.

2. extract all the files into your folder as mentioned above in step 2.

3. Replace the existing files. (I think it asked for 4)

4. Go to the command prompt. I ran Bundler as a command, but I'm not sure that's
required. Perhaps someone can try without and confirm this step.

Then run:

\$ jekyll build

\$ jekyll serve

Visit: <http://localhost:4000/>

When you are done testing, go back and ctrl-c your running local server and
terminate the session.

The theme is now installed, and you can git init, and upload to github...

Description of the content is here as this theme is a theme extension

<https://github.com/jekyll/minima>

#### **Step 4**: Running on github pages

You have to turn on pages and point where the content is stored (settings under
repo).  At this point commit to the master branch and assuming you have the site configured properly it will work.

#### **Step 5**: Editing content

So basically you just play in the folders not named "_site" - site gets
overwritten.

Example: Color variables- : color variables are in \_color.scss


 
