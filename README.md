# About
This repository looks to share public-facing information as part of a project at the University of Manchester, by using Github pages to generate a website. The project is investigating electronic research notebooks (of which a subset are more commonly referred to as electronic laboratory notebooks) for potential implementation.

# Credit
The basis of the notebook attributes is the [ELN Finder](https://eln-finder.ulb.tu-darmstadt.de/home)'s [metadata schema v1.0](https://doi.org/10.4126/FRL01-006452815), which is kindly made available by [CC BY 4.0 licence](https://creativecommons.org/licenses/by/4.0/).

Following the [Contributor Role Taxonomy](https://credit.niso.org/), Qingy Mao, [@Moy36](https://github.com/Moy36), was predominantly responsible for the data curation, formal analysis and development of this software, while James R.T. Bird, [@jamesbird58](https://github.com/jamesbird58), was responsible for the conceptualization, methodology, supervision and some software development.

> [!NOTE]
> Please note that changes made to the [research-notebooks](https://github.com/oiseau-lab/research-notebooks) repository are now first made downstream in the [research-notebooks-dev](https://github.com/oiseau-lab/research-notebooks-dev) fork. For a changelog, interested parties would therefore be better off referring to the dev repo. This change was made to avoid 'breaking' the deployed webpage in the absence of complete local testing.

> [!TIP]
> If you wish to run the Jupyter notebook `PlotAndPageGenerationForInterviews.ipynb`, which is used to generate plots and define some of the site structure and formatting, you will be able to do so by setting up a conda :snake: environment by cloning the `environment.yml`.

> [!IMPORTANT]
> Cloning or forking this repository, without modification, and activating Pages (i.e. automatically defining a sequence of Github Actions) will deploy the site. Like other Jekyll sites, to deploy the site locally, you can do so with Ruby using gems :gem: and bundler as detailed [here](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll). :link: 

> [!WARNING]
> For MacOS :computer: users: it is advisable to use [rbenv](https://github
