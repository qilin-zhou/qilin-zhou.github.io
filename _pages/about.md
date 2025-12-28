---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Qilin Zhou is a 4th-year PhD candidate in the [Department of Computer Science at City University of Hong Kong](https://www.cs.cityu.edu.hk/), supervised by [Wing-Kwong Chan](https://www.cs.cityu.edu.hk/~wkchan/). He earned his B.Eng. in Software Engineering from the Outstanding Engineer Program at South China University of Technology in 2022. His research interests lie at the intersection of Software Engineering (SE) and Artificial Intelligence (AI), with a specific focus on Formal Quality Assurance for AI.


Research Paper
======
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>

### First-Author Papers
- arXiv 2025 **Toward Patch Robustness Certification and Detection for Deep Learning Systems Beyond Consistent Samples**, **Qilin Zhou**, Zhengyuan Wei, Haipeng Wang, Zheng Wang, W. K. Chan.
- QRS 2025 **Scalable and Precise Patch Robustness Certification for Deep Learning Models with Top-k Predictions**, **Qilin Zhou**, Haipeng Wang, Zhengyuan Wei, W. K. Chan.
- FSE 2024 **CrossCert: A Cross-Checking Detection Approach to Patch Robustness Certification for Deep Learning Models**, **Qilin Zhou**, Zhengyuan Wei, Haipeng Wang, Bo Jiang, W. K. Chan.
- ASE-NIER 2023 **A Majority Invariant Approach to Patch Robustness Certification for Deep Learning Models**, **Qilin Zhou**, Zhengyuan Wei, Haipeng Wang, W. K. Chan.

### Co-Authored Papers
- TOSEM 2024 Context-Aware Fuzzing for Robustness Enhancement of Deep Learning Models, Haipeng Wang, Zhengyuan Wei, **Qilin Zhou**, W. K. Chan.
- SANER 2024 Delving into parameter-efficient fine-tuning in code change learning: An empirical study, Shuo Liu, Jacky Keung, Zhen Yang, Fang Liu, **Qilin Zhou**, Yuhan Liao.
- QRS 2023 Aster: Encoding Data Augmentation Relations into Seed Test Suites for Robustness Assessment and Fuzzing of Data-Augmented Deep Learning Models, Haipeng Wang, Zhengyuan Wei, **Qilin Zhou**, Bo Jiang, W. K. Chan.
- In Submission A3Rank: Augmentation Alignment Analysis for Prioritizing Overconfident Failing Samples for Deep Learning Models, Zhengyuan Wei, Haipeng Wang, **Qilin Zhou**, W. K. Chan.



Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

Publications
======
Test
Test
Test
Test
Test
Test

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these 
