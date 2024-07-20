---
layout: article
title: "Tutorial T08: Single cell signal processing and data analysis in Matlab"
tags: tutorial cns*2024
sharing: true
aside:
  toc: true
sidebar:
  nav: layouts
key: page-tutorial
pageview: true
---

### Organizers:

Dr. Cengiz Gunay<br>
Dept. Information Technology, School of Science and Technology, Georgia Gwinnett College, USA

<!--iframe width="560" height="315" src="https://www.youtube.com/embed/Q7Gc-Dq48Yw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe-->

### Tutorial time:

|-|-|-|-|-|
|Time zone: | Natal, Brazil |
|- 
| July 20, 2024 | 9am - noon |

### Draft schedule

|-|-|
| Time | Sessions with 5 minute break between | 
|- 
| 3:00 pm | Introduction & installation
| 3:45 pm | Practice: Signal processing 
| 4:30 pm | Practice: Tabular analysis 
| 5:15 pm | Practice: Plotting 
| 6:00 pm | End of tutorial

### Download materials

- [Slides]({{ "/assets/present-pandora-tutorial-cns2024.pdf" | relative_url }})

<!--more-->

## Description

Matlab (Mathworks, Natick, MA) is a popular computing environment that
offers an alternative to more advanced environments with its
simplicity, especially for those less computationally inclined or for
collaborating with experimentalists. In this tutorial, we will focus
on the following tasks in Matlab:

1. Signal processing of recorded or simulated traces (e.g., filtering
   noise, spike and burst finding in single-unit intracellular
   electrophysiology data in current-clamp, and extracting numerical
   characteristics);
2. analyzing tabular data (e.g. obtained from Excel or from the result
   of other analyses);
3. plotting and visualization.

For all of these, we will take advantage of the PANDORA toolbox, which
is an open-source project that has been proposed for analysis and
visualization ( RRID: SCR_001831, [1]). PANDORA was initially
developed for managing and analyzing brute-force neuronal parameter
search databases. However, it has proven useful for various other
types of simulation or experimental data analysis [2-7]. PANDORA’s
original motivation was to offer an object-oriented program for
analyzing neuronal data inside the Matlab environment, in particular
with a database table-like object, similar to the “dataframe” object
offered in the R ecosystem and the pandas Python module. PANDORA
offers a similarly convenient syntax for a powerful database querying
system. A typical workflow would constitute of generating parameter
sets for simulations, and then analyze the resulting simulation output
and other recorded data, to find spikes and to measure additional
characteristics to construct databases, and finally analyze and
visualize these database contents. PANDORA provides objects for
loading datasets, controlling simulations, importing/exporting data,
and visualization. In this tutorial, we use the toolbox’s standard
features and show how to customize them for a given project.

### Software tools:

- Matlab
- PANDORA - [Github](https://github.com/cengique/pandora-matlab) and [MathWorks File Exchange](https://www.mathworks.com/matlabcentral/fileexchange/60237-cengique-pandora-matlab) pages

### References:

- Günay et al. 2009 Neuroinformatics, 7(2):93-111. doi: 10.1007/s12021-009-9048-z
- Doloc-Mihu et al. 2011 Journal of biological physics, 37(3), 263–283. doi:10.1007/s10867-011-9215-y
- Lin et al. 2012 J Neurosci 32(21): 7267–77
- Wolfram et al. 2014 J Neurosci, 34(7): 2538–2543; doi: 10.1523/JNEUROSCI.4511-13.2014
- Günay et al. 2015 PLoS Comp Bio. doi: 10.1371/journal.pcbi.1004189
- Wenning et al. 2018 eLife 2018;7:e31123 doi: 10.7554/eLife.31123
- Günay et al. 2019 eNeuro, 6(4), ENEURO.0417-18.2019. doi:10.1523/ENEURO.0417-18.2019

[See all CNS*2024 Tutorials here](https://www.cnsorg.org/cns-2024-tutorials){:target="_blank"}

TBA
