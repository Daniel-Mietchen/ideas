# About

This file hosts materials related to two submissions for [JupyterCon 2023](https://www.jupytercon.com/), taking place on May 10-12 in Paris. Both are jointly authored with [Sheeba Samuel](https://github.com/Sheeba-Samuel/) and based on our preprint [Computational reproducibility of Jupyter notebooks from biomedical publications](https://arxiv.org/abs/2209.04308).

# Submission 1 (accepted)

Title: Computational reproducibility of Jupyter notebooks from biomedical publications

Session Type: Talk (30 min)

Abstract: In this talk, we present a study that analyzed the computational reproducibility of Jupyter notebooks extracted from GitHub repositories associated with publications indexed in the biomedical literature repository PubMed Central. We will present the key steps of the pipeline we used for assessing the reproducibility of Jupyter Notebooks. The study is based on the metadata extracted from 1419 publications from PubMed Central published in 373 journals. From the 1117 GitHub repositories associated with these publications, a total of 9625 Jupyter Notebooks were downloaded for further reproducibility analysis. The code for the pipeline is adapted from [Felipe et al., 2019](https://doi.org/10.5281/zenodo.2592524). We will discuss the results of the study, including variables such as programming languages, notebook structure, naming practices, modules, dependencies etc. that we found in these notebooks. We will then zoom in on common problems and practices, highlight trends and discuss potential improvements to Jupyter-related workflows associated with biomedical publications. This talk is aimed at researchers who use Jupyter notebooks to publish their results in public repositories and help them to use best practices while documenting their research.

Notes: Important Links:
- Data and Code https://doi.org/10.5281/zenodo.6802158
- Preprint: https://doi.org/10.48550/arXiv.2209.04308 

This talk is complemented by a separate one that focuses on the best practice recommendations.


# Submission 2 (not accepted)

Title: Recommendations for making Jupyter notebooks more reproducible

Session Type: Talk (30 min)

Abstract: In this talk, we will discuss common problems that can arise when trying to reproduce Jupyter notebooks that are shared along with research publications, and we will provide practical advice on addressing these challenges, taking into account the roles of different stakeholders. These recommendations have been distilled from a [systematic re-analysis](https://doi.org/10.48550/arXiv.2209.04308) of Jupyter notebooks shared in the context of biomedical research publications. The issues covered include, for instance, the use of custom libraries and modules, hard-coded paths and file names, inadequate documentation, and non-open data. We will provide real-world examples highlighting specific problems, and we will outline steps to take towards addressing such problems in order to improve the computational reproducibility of Jupyter notebooks. While the bulk of our data is derived from notebooks written in Python, the recommendations are written with Jupyter notebooks using other languages in mind, such as R, Scala and Julia. This talk is primarily aimed at researchers who use Jupyter notebooks in their work, but it also addresses other stakeholders in the wider Jupyter and research ecosystems, such as providers of research infrastructures on which such notebooks run, as well as reviewers, editors and publishers of manuscripts associated with Jupyter notebooks. It will provide valuable insights and tips for improving the reproducibility of computational analyses shared through Jupyter notebooks.

Notes:
The talk is complemented by a separate one that focuses on the methods of our systematic re-analysis of Jupyter notebooks.
