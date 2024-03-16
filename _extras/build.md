---
title: "Build from Styles Notes"
teaching: 0
exercises: 0
questions:
- What is a Software Carpentry lesson template?
- Which lesson template should we use for source?
- How to import lesson template as a GitHub repo?
objectives:  
- Identify Software Carpentry lesson template source.
- Build DUNE repo and corresponding .io site.
keypoints:
- Build from styles template is straightforward but requires a few steps for GitHub Pages to render correctly.
---

## Introduction

In this lesson we will build a github.io site for the upcoming training of the DUNE Computing HWDB which has learning materials presented using the Software Carpentry (SC) templates. 

Identify SC lesson template source:
Work from the latest version of the lesson template, to verify versioning, visit https://github.com/swcarpentry,  and check out the meta-repository to help navigate the lessons and repos of the SC Community: https://github.com/swcarpentry/swcarpentry 

Scrolling down, under Lesson template: We maintain a set of CSS and Jekyll scaffolding that can be used to help organize and create lessons in our style (swcarpentry/styles). Instructions for how to contribute are in swcarpentry/lesson-example.
Collapsed Accordion: An observation at https://github.com/carpentries/styles indicates no commits to the styles repo have been made in the last 2 years, with latest release: styles v9.5.3 Latest on Aug 21, 2018.

### Steps in a Nutshell
* Copy styles .git URL to buffer
* Create DUNE GitHub instance 
* Import styles (not fork, not clone)
* GitHub settings, set default branch to gh-pages, then delete the main branch.
* Locally, clone your github instance using GitHub Desktop
* In a terminal window whle in top level of your repo, and using $python bin/lesson_initialize.py
* Run $make serve to enable Jekyll/Ruby/Bundler based editing for localhost viewing
* Make edits, when ready push updates to the master repo on Github

### Step by Step Instructions


<a href="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image1.png">
  <img src="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image1.png" alt="Image 1" />
</a>

<a href="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image2.png">
  <img src="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image2.png" alt="Image 2" />
</a>

<a href="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image3.png">
  <img src="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image3.png" alt="Image 3" />
</a>

<a href="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image4.png">
  <img src="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image4.png" alt="Image 4" />
</a>

<a href="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image5.png">
  <img src="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image5.png" alt="Image 5" />
</a>

<a href="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image6.png">
  <img src="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image6.png" alt="Image 6" />
</a>

<a href="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image7.png">
  <img src="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image7.png" alt="Image 7" />
</a>

<a href="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image8.png">
  <img src="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image8.png" alt="Image 8" />
</a>

<a href="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image9.png">
  <img src="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image9.png" alt="Image 9" />
</a>

<a href="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image10.png">
  <img src="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image10.png" alt="Image 10" />
</a>
<a href="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image11.png">
  <img src="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image11.png" alt="Image 11" />
</a>

<a href="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image12.png">
  <img src="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image12.png" alt="Image 12" />
</a>

<a href="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image13.png">
  <img src="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image13.png" alt="Image 13" />
</a>

<a href="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image14.png">
  <img src="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image14.png" alt="Image 14" />
</a>

<a href="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image15.png">
  <img src="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image15.png" alt="Image 15" />
</a>

<a href="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image16.png">
  <img src="{{ page.root }}/fig/Build-for-May-2024-DUNE-computing-HWDB-training-on-github/images/image16.png" alt="Image 16" />
</a>



{% include links.md %}
