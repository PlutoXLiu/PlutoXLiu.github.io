---
permalink: /
title: "Pluto Xiaoyue Liu"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Kia ora | Hello
I am a PhD student at the University of Otago, New Zealand, supervised by Prof. Ceridwen Fraser and Dr. Alana Alexander. I am studying about the population genomics of buoyant kelp (*Macrocystis pyrifera* | giant bladder kelp or Rimurimu in Maori and *Durvillaea antarctica* | southern bull kelp or Rimurapa in Maori) around the Southern Ocean, and whether they could establish in Antartctica in the future. My methods include population genomics (genotyping-by-sequencing), physiological tolerance experimentation as well as ecological modelling.

Why study this?
======
Antarctica has long been considered to be isolated, with strong oceanographic barriers preventing species - except those that can swim or fly long distances - from reaching it. Antarctica has also been seen as a pristine land largely untouched by humans, with no permanent human settlements other than research stations. However, exciting emerging research (e.g. (https://www.nature.com/articles/d41586-022-01584-4) is challenging both assumptions. Non-indigenous invertebrates, mosses, grass and seaweeds have been discovered along Antarctic coasts, while human activities have been rapidly increasing over the past decades, actively introducing exotic species. 
Buoyant kelp (particularly southern bull kelp *Durvillaea antarctica* and giant bladder kelp *Macrocystis pyrifera*) can travel thousands of kilometres from one coast to another, and reproductively viable kelp originating from sub-Antarctic islands such as South Georgia has been found washed up on Antarctic beaches. Secondly, various organisms (molluscs, polychaetes, arthropods, echinoderms etc.) can hitchhike with rafting kelp, for example within kelp holdfasts. Based on modelling, we now think that such events have been happening frequently and for a long time, with establishment only prevented - for now - by the extreme iciness of Antarctica. There is a pressing need to study the origins, sources, dispersal trajectories and Antarctic viability of these marine species, which seem poised to establish along Antarctic coasts in the future.

You can learn more about our project through these publications:

Fraser CI et al. (2018). Antarctica’s ecological isolation will be broken by storm-driven dispersal and warming. Nature Climate Change 8, 704–708. [https://doi.org/10.1038/s41558-018-0209-7](https://doi.org/10.1038/s41558-018-0209-7).

Fraser CI et al. (2022). Southern Hemisphere coasts are biologically connected by frequent, long-distance rafting events. Current Biology 32(14), 3154-3160. [https://doi.org/10.1016/j.cub.2022.05.035](https://doi.org/10.1016/j.cub.2022.05.035).


![How kelp reached Antarctica (Fraser et al. 2018 Nat. Clim. Change.).](https://github.com/plutoxliu/plutoxliu.github.io/blob/eb5326af1f089de097b8adb8d1e50c74e99ad3b4/images/Fraser%20et%20al.%202018.png)

publications
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
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
