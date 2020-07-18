---
layout: article
title: "Showcase #3: Advances in the PANDORA Matlab Toolbox for intracellular electrophysiology data"
sharing: true
aside:
  toc: true
sidebar:
  nav: layouts
key: page-showcase
pageview: true
# tags: tutorial
---

**Presenter:** Dr. Cengiz Gunay <br>
School of Science and Technology, Georgia Gwinnett College, USA

**Showcase time:**

|-|-|-|-|-|
| Time zone: | Los Angeles | New York | Berlin | Sydney |
|- 
| July 18, 2020 | 3pm | 6pm | midnight | 8am (July 19) |

[All CNS*2020 Tutorials](https://www.cnsorg.org/cns-2020-tutorials)

### Description of the software showcase



[PANDORA](https://github.com/cengique/pandora-matlab) is
an
[open-source toolbox for Matlab](https://www.mathworks.com/matlabcentral/fileexchange/60237-cengique-pandora-matlab) (Mathworks,
Natick, MA), which has been originally developed for analysis and
visualization of single-unit intracellular electrophysiology data
([RRID: SCR_001831](https://scicrunch.org/resources/about/registry/SCR_001831),
Günay et al. 2009 Neuroinformatics,
7(2):93-111. [doi: 10.1007/s12021-009-9048-z](https://link.springer.com/article/10.1007/s12021-009-9048-z)). Even
though there are more modern and popular environments, such as the
Python and Anaconda ecosystem, Matlab still offers an advantage in its
simplicity, especially towards those less computationally inclined,
for instance for collaboration with experimentalists. PANDORA was
originally intended for managing and analyzing brute-force neuronal
parameter search databases (Günay et al. 2008 J Neurosci. 28(30):
7476-7491; Günay et al. 2010 J Neurosci. 30: 1686–98). However, it has
been proven useful for other types of simulation or experimental data
analysis
([Doloc-Mihu et al. 2011 Journal of biological physics, 37(3), 263–283. doi:10.1007/s10867-011-9215-y](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3101324/);
Lin et al. 2012 J Neurosci 32(21): 7267–77; [Wolfram et al. 2014 J Neurosci, 34(7): 2538–2543; doi: 10.1523/JNEUROSCI.4511-13.2014](http://www.jneurosci.org/content/34/7/2538.short);
[Günay et al. 2015 PLoS Comp Bio. doi: 10.1371/journal.pcbi.1004189](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004189);
[Wenning et al. 2018 eLife 2018;7:e31123 doi: 10.7554/eLife.31123](https://elifesciences.org/articles/31123);
[Günay et al. 2019 eNeuro, 6(4), ENEURO.0417-18.2019. doi:10.1523/ENEURO.0417-18.2019](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6709225/)). PANDORA’s
original motivation was to offer object-oriented analysis specific to
neuronal data inside the Matlab environment, in particular with a
database table-like object, similar to R and the Python PANDAS
toolbox’s “dataframe” object, and a new syntax for a powerful database
querying system. The typical workflow would constitute of generating
parameter sets for simulations, and then in the resulting output data,
finding spikes and additional characteristics to construct databases,
and finally analyze and visualize these database contents. PANDORA
provides objects for loading datasets, controlling simulations,
importing/exporting data, and visualization. Since it’s inception, it
has grown with added functionality. In this showcase, we review the
toolbox’s standard features and show how to customize them for a given
project, and then introduce some of the new and experimental features,
such as ion channel fitting, evolutionary/genetic
algorithms. Furthermore, we will give a developers’ perspective for
those who may be interested in adding modules to this toolbox.

### Software tools

- PANDORA - [Github](https://github.com/cengique/pandora-matlab) and [MathWorks File Exchange](https://www.mathworks.com/matlabcentral/fileexchange/60237-cengique-pandora-matlab) pages

### Background readings

- [Günay et al. 2009 Neuroinformatics,
7(2):93-111. doi: 10.1007/s12021-009-9048-z](https://link.springer.com/article/10.1007/s12021-009-9048-z)
- [Doloc-Mihu et al. 2011 Journal of Biological Physics, 37(3), 263–283. doi:10.1007/s10867-011-9215-y](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3101324/)
- Lin et al. 2012 J Neurosci 32(21): 7267–77
- [Wolfram et al. 2014 J Neurosci, 34(7): 2538–2543; doi: 10.1523/JNEUROSCI.4511-13.2014](http://www.jneurosci.org/content/34/7/2538.short)
- [Günay et al. 2015 PLoS Comp Bio. doi: 10.1371/journal.pcbi.1004189](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004189)
- [Wenning et al. 2018 eLife 2018;7:e31123 doi: 10.7554/eLife.31123](https://elifesciences.org/articles/31123)
- [Günay et al. 2019 eNeuro, 6(4), ENEURO.0417-18.2019. doi:10.1523/ENEURO.0417-18.2019](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6709225/))

<!--more-->

### Download materials

- [Slides](present-pandora-updates.pdf)

### Showcase organization

1. Pandora introduction and updates
2. Tutorials and demo examples
3. Q & A feedback


