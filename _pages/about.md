---
permalink: /
title: "Welcome!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a graduate student studying physics and astronomy at the University of California, Santa Cruz under my advisor [Tesla Jeltema](http://scipp.ucsc.edu/~tesla/). My main interests are in observational cosmology - the study of the structure, evolution, and origin of the universe by sticking a big camera on an even larger telescope and looking up! 

I am a member of the [Dark Energy Survey](https://www.darkenergysurvey.org/) (DES), an international collaboration of hundreds of scientists investigating the dynamics and large-scale structure of the universe using multiple observationalprobes. We do this by taking hundreds of thousands of images of the Southern sky at the 4-meter Victor Blanco Telescope at [Cerro Tololo Inter-American Observatory (CTIO)](http://www.ctio.noao.edu/noao/) in central Chile. Check out our newest [publications here](https://www.darkenergysurvey.org/news-and-results/publications/)!

I spend most of my time building statistical models and running large simulations to understand how subtle systematics affect our cosmological results. Check out my work on [Balrog](https://github.com/sweverett/Balrog-GalSim), an image simulation tool that characterizes measurement biases by injecting an ensemble of fake objects into real images. Lately I've been working on a new DES [clusters cosmology pipeline](https://bitbucket.org/mpaterno/y3_cluster_cpp/) that quickly evalutates millions of high-dimensional integration samples using [CosmoSIS](https://bitbucket.org/joezuntz/cosmosis/wiki/Home). Or take a look at my [github account](https://github.com/sweverett) for all my latest projects!

I am also a committee representative for Early Career Scientists (ECS), a group of students, postdocs, and research fellows within DES. We provide a space where the career interests and concerns of younger scientists are discussed and regularly meet with DES leadership express ECS concerns. We also plan ECS-related activities at collaboration meetings including career panels, application and professional skill workshops, and biannual ECS drinks!

I have been lucky to have had many supportive mentors along my (still early!) scientific career, particularly [Tesla Jeltema](https://scipp.ucsc.edu/~tesla/) at UCSC, [Phil Marshall](http://www.slac.stanford.edu/~pjm/Site/Welcome.html) at SLAC National Laboratory, and [Jesus Pando](https://csh.depaul.edu/faculty-staff/faculty-a-z/Pages/physics/jesus-pando.aspx) at DePaul University.

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

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
