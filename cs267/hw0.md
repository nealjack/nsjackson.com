---
layout: page
title: hw0
---

<div class="mdl-cell mdl-cell--3-col" markdown="1">
</div>
<div class="mdl-cell mdl-cell--4-col" markdown="1">
### Bio
I'm Neal Jackson, a first year PhD student at the University of California,
Berkeley.

I work as a Research Assistant with Prabal Dutta and
[Lab11](http://lab11.eecs.umich.edu/).  My research is focused on enabling
ubiquitous sensing with low power embedded devices. Most recently, I've been
working on the [Signpost](https://github.com/lab11/signpost) project, an effort
to develop a modular, easily deployable, and user-friendly sensor node to
enable city-wide sensing, research, and applications. I've also developed the
[GAP](http://lab11.eecs.umich.edu/GAP) (Generic Access Point), a gateway for
resource constrained embedded devices.

My current work doesn't involve applications of parallel computing, but I've
always found scientific simulation fascinating. I'm primarily taking this class
to learn more about efficiently writing parallel programs.

### Application: Protein Folding
Proteins initially exist as random coils of amino acids, and only assume a
lasting 3-dimensional structure after being synthesized by a cell's ribosome.
The correctness of this 3D structure is essential to the proteins function.
Misfolded proteins are believed to result in many allergies and several
neurodegenerative conditions such as Alzheimer's Disease and Huntington's
Disease. [[1]](#references)

Folding@home is a distributed computing project led by Vijay Pande at Stanford
University attempting to simulate the folding of various proteins essential to
the human body. [[2]](#references) The project seeks to examine the causes of
protein misfolding and how the final structure of folded proteins interact with
other molecules, using statistical simulation methods. The project uses
commodity parallel computing platforms such as PCs, gaming systems, and
smartphones provided by volunteers who have downloaded and installed the
Folding@home application on their devices.

The statistical method of Folding@home calculations maps well
to this distributed system, as simulations can be partitioned and independently
computed. The choice to use commodity hardware does limit the performance of
independent calculations, but this loss is made up by the scale of
distribution, which is reported to run at 100petaFLOPS.  [[3]](#references)
The performance and accuracy of Folding@home rivals special-purpose systems
like ANTON, a supercomputer built to perform molecular dynamics simulations
of proteins.  [[4]](#references)

To date, the project has produced 129 publications, some have found that
the simulations align with experimental evidence. [[5][6][7]](#references)


### References
<a name="references"></a>
[1] [https://en.wikipedia.org/wiki/Protein_folding](https://en.wikipedia.org/wiki/Protein_folding)

[2] [https://foldingathome.stanford.edu/](https://foldingathome.stanford.edu/)

[3] [https://en.wikipedia.org/wiki/Folding@home](https://en.wikipedia.org/wiki/Folding@home)

[4] [Markov State Model Reveals Folding and Functional Dynamics in Ultra-Long MD Trajectories](http://pubs.acs.org/doi/abs/10.1021/ja207470h)

[5] [http://folding.stanford.edu/home/papers](http://folding.stanford.edu/home/papers)

[6] [Molecular simulation of ab initio protein folding for a millisecond folder NTL9(1–39)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2835335/)

[7] [Absolute comparison of simulated and experimental protein-folding dynamics](http://sansan.phy.ncu.edu.tw/~hclee/ref/SnowNature2002.pdf)

</div>
<div class="mdl-cell mdl-cell--3-col" markdown="1">
</div>
