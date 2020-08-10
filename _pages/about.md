---
permalink: /
title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a lecturer in the [School of Computer Science](https://www.st-andrews.ac.uk/subjects/computer-science/) at the [University of St Andrews](https://www.st-andrews.ac.uk/), Scotland, UK. I am a member of the [Programming Languages](https://plrg.cs.st-andrews.ac.uk/) group.

Before becoming a lecturer, I was previously a post-doc at St Andrews, and previous to that, I worked in industry briefly, after graduating from my PhD from the University of kent. 

My research ambition lately has generally been focussed around building new tools and techniques to make it easier and more accessible, through the use of refactoring technology, for application programmers to develop multi-core software. But I am generally interested in programming languages, and compilers. My area of expertise lies in refactoring, programming languages, including functional programming, parallel programming, programming language design (including semantics, and formal reasoning), compilers and GPU programming. Based on the research that I undertook as part of my PhD, I have developed new refactoring tools and techniques for parallel computing systems, for a variety of languages, including C/C++, Haskell and Erlang. These provide software developers with much-needed tool capabilities to allow them to easily and effectively exploit modern multi-core hardware, enabling their applications to run faster, safer and with less development effort and expertise. 

I am strongly active amongst the programming language and parallelism communities, where I contribute heavily to the design and implementation of refactoring tools and compiler technology (leading to two refactoring tools, HaRe, for Haskell and ParaFormance, for C/C++); parallel programming (including a new parallel skeleton library for Erlang, Skel); GPU programming; and the design, implementation and application of functional programming languages.

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
