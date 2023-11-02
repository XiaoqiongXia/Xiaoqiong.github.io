---
permalink: /
title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
About me
======
I am a PhD candidate at the Institutes of Biomedical Sciences, Fudan University. My PhD advisor is Professor Lei Liu, who is a leading researcher in the field of bioinformatics. I expect to graduate in June 2024. My research interests focus on artificial intelligence for early-stage drug discovery. I worked on developing drug-target interaction, drug activity prediction, and molecular generation models by combining deep learning algorithms with computer-aid drug design tools. My proposed methods facilitate drug discovery and repurposing.

RESEARCH INTERESTS
======
Deep learning; Drug discovery; Drug target interaction; Drug response; Molecule generation; Molecular representation; CADD; Omics analysis; Knowledge graph.

EDUCATION
======
* **Ph.D.**, Institutes of Biomedical Sciences, Fudan University (**GPA: 3.27/4**)	2019.09-2024.06  
Supervisor: Professor Lei Liu  
* **B.S.**, Biomedical engineering, China Medical University (**TOP 1**)	2015.09–2019.06

RESEARCH EXPERIENCES
======
**1. Develop a structure-based molecular generation model (primary researcher)**	2022.12–present  
* Used MGLTools and AutoDock-GPU to build a virtual screening process for molecular fragments on a Linux system and screen high-scored molecular fragments efficiently.  
* Developed a fragment growth model using a diffusion algorithm to generate reasonable candidate molecules with high affinity to the target.  
* Used the GROMACS tool to perform molecular dynamics simulation of the receptor-ligand complex.  
**The project helps accelerate drug development.**  

**2. Develop a cancer-drug response prediction model (primary researcher)**	2022.06–2023.09
* Used pre-trained models ChemBERTa and GIN, MLP to learn the drug’s structural information.  
* Applied MLP to learn multi-omics profiles of cell lines.  
* Fused multimodal features based on multi-head attention mechanisms.  
* Transfer learning improves the model’s generalization to predict drug cell line response (IC50).  
**The model could accelerate drug discovery and precision medicine.**  

**3. Develop a multimodal fusion DTI prediction model (primary researcher)**	2020.09–2022.12
* Used deep learning modules such as CNN/Transformer, GNNs, and TransE to integrate structural information, knowledge graphs, and gene expression profiles of drugs and proteins to predict drug-target interactions accurately.
**The model helps in drug repurposing and drug discovery. The paper was published in Bioinformatics.**

**4. Multimodal reasoning based on knowledge graph embedding (Cooperative)**	2020.09–2023.07
* Constructed RDKG-115, a rare disease knowledge graph based on 372,384 high-quality literature and 4 biomedical datasets: DRKG, Pathway Commons, PharmKG, and PMapp.  
* Developed a trimodal KGE model containing structure, category, and description embeddings using reverse-hyperplane projection.  
* Utilized this model to infer 4199 reliable new inferred triplets from RDKG-115.  
* The project provides a paradigm for large-scale screening of drug repurposing and discovery for rare diseases.  
**The model could accelerate drug discovery and precision medicine.**  

PUBLICATIONS
======
1. **Xiaoqiong Xia**, Chaoyu Zhu, Fan Zhong, Lei Liu. MDTips: A Multimodal-data based Drug-Target interaction prediction system fusing knowledge, gene expression profile and structural data. *Bioinformatics*. 2023 Jun 22

2. **Xiaoqiong Xia**, Chaoyu Zhu, Fan Zhong, Lei Liu. TransCDR: a deep learning model for enhancing the generalizability of cancer drug response prediction through transfer learning and multimodal data fusion. *computer methods and programs in biomedicine*. Under review.
  
3. Chaoyu Zhu, Zhihao Yang, **Xiaoqiong Xia**, Nan Li, Fan Zhong, Lei Liu. Multimodal reasoning based on knowledge graph embedding for specific diseases. *Bioinformatics*. 2022 Apr 12.

4. Chaoyu Zhu, **Xiaoqiong Xia**, Nan Li, Fan Zhong, Lei Liu. RDKG-115: Assisting Drug Repurposing and Discovery for Rare Diseases by Trimodal Knowledge Graph Embedding. *Computers in Biology and Medicine*. 2023 Jul 17.

5. Gang Liu, Zhenhao Liu, Xiaomeng Sun, **Xiaoqiong Xia**, Yunhe Liu, Lei Liu. Pan-Cancer Genome-Wide DNA Methylation Analyses Revealed That Hypermethylation Influences 3D Architecture and Gene Expression Dysregulation in HOXA Locus During Carcinogenesis of Cancers. *Frontiers in cell and developmental biology*. 2021 Mar 18.

6. **Xiaoqiong Xia**, Mengyu Zhou, Hao Yan, Sijia Li, Xianzheng Sha, Yin Wang. Network analysis of aging acceleration reveals systematic properties of 11 types of cancers. *FEBS Open Bio*. 2019 Jul.  

SKILLS
======
* Familiar with Linux systems, proficient in R, Python, and PyTorch framework to build, train, and test models and GPU acceleration.  
* Proficient in utilizing PyG and DGL Python packages for graph representation.  
* Familiar with CNN/RNN/Transformer model, GCN/GAT/EGNN model and diffusion model.  
* Proficient in PyMOL, MOE, AutoDock, RDKit, and GROMACS for molecular docking and molecular dynamics simulation.  
* Familiar with open-source databases for compound/gene/protein/perturbation expression profiles and omics data analysis processes.  
* Good English reading and writing skills, CET-6:558.  
* Excellent written, communication skills, and collaborative ability.  


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
