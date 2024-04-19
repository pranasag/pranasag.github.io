---
layout: page
title: Hiring!
description: Multiple student projects available
img: assets/img/uncleSam.jpg
importance: 1
category: Student projects
#related_publications: einstein1956investigations, einstein1950meaning
---

There is a number of theoretical projects open for students interested in any of the research topics (both at BSc and MSc level). Some of the specific openings will be posted below. 

Internships involve multiple modeling types (genome-scale metabolic modelling and kinetic modelling) and rely on programming with Python, MATLAB and/or R for data analysis and visualization. Obviously, you are also welcome to bring any interesting reseach question yourself - we love puzzles at the Systems Biology Lab! Keep in mind that the students from the Vrije Universiteit have priority in hiring, although students from other universities/HBO are also open for consideration. 
Please contact me for more details!

#### Open positions
##### Improving construction of enzyme-constrained metabolic models for non-model organisms
MSc Minor/Major, 24-30 EC | both on-site and remote | availability: ASAP

Supervisor: Pranas Grigaitis

Genome-scale metabolic models (GEMs) are computable databases of all the biochemical conversions that an organism could do given all the metabolic proteins that are encoded by its genome. These models have been extensively used to advance our understanding of microbial growth strategies and production of valuable compounds (see a review by our group: Somerville *et al.* 2022 *Curr Opin Food Sci*), and modeling of higher eukaryote networks is currently in the focus. 

The predictive power of GEMs is limited by several strong assumptions. To mention a few, these models do not include any information about enzyme action (reaction thermodynamics, kinetic parameters) and the physico-chemical constraints of growth (cell size, maximal cell density…). So-called *enzyme-constrained* GEMs (*ecModels*) are a GEM extension framework that introduces simplified enzyme kinetics and enzyme usage constraints in the cell.

The GECKO toolbox (Chen *et al.* 2024 *Nat Protocol*) is a user-friendly pipeline, written in MATLAB, to generate *ecModels*. It includes some steps that are dependent on the target organism: (i) matching information in biological databases with input proteome data, and (ii) infer the experimentally determined stoichiometry of protein complexes. These data resources are either scarce or nonexistent for non-model organisms, and the resulting ecModels are incomplete in that sense.

In this project, we want to extend the organism information-dependent steps in GECKO to perform homology-based search in the databases normally used by GECKO. The expected outcome is to make the method more suitable to reconstruct the *ecModels* of organisms outside the usual cohort of “model organisms”. 

We expect you to have (or be willing to quickly acquire) a good command of programming in MATLAB. Basic familiarity with the good practices of software carpentry (e.g. version control using *git*) is desired. 


##### Correlating genetic and functional variability of enzymes with thermodynamics
MSc Minor/Major, 24-36 EC | both on-site and remote | availability: Summer 2024

Supervisors: Pranas Grigaitis, Frank Bruggeman

Most biochemical processes require protein catalysts – enzymes – to proceed at rates which can sustain life. The catalysis function of these proteins has evolved under (and is still subject to) natural selection as different variants of the enzymes emerge through genetic mutations. Mutations can bring both innovations (improved or novel function) and detrimental damage (loss of function) to the enzymes and thus directly influence cell fitness. We would like to test the hypothesis whether the genes, encoding enzymes which catalyze reactions close to thermodynamic equilibrium (small \|ΔG\| values) are less prone to accumulate mutations in selected microbial species.

In this project, we want to correlate the functional information of enzymes with their mutational patterns at different levels (gene, transcript, protein) and expression of these enzymes. We have previously developed a routine to compute ΔG values for all known enzyme-catalyzed metabolic reactions from the genome-scale metabolic models. We will collect and use the set of gene-, transcript-, and protein sequences of sequenced microbial isolates and absolute proteome quantification data for reference strains to correlate sequence variability and enzyme expression levels with the thermodynamic parameters. 

We expect you to be experienced in Python scripting and dedicated data handling libraries (pandas, numpy, scipy). Good understanding of core statistical analyses will be needed for analyzing data. Previous experience with setting up command-line bioinformatics routines is an advantage. We offer you an opportunity to gain experience in handling large-scale datasets, and learn how to setup and run complex, multi-step bioinformatics pipelines.

