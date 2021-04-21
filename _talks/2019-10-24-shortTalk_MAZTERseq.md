---
title: "Short talk - Deciphering the “m6A Code” via Antibody-Independent Quantitative Profiling"
collection: talks
type: "Talk"
permalink: /talks/shortTalk_IsraelRNA2019
venue: "Lola Hall, Sackler School of Medicine, Tel Aviv University"
date: 2019-10-24
location: "Tel Aviv, Israel"
---	

[Slides](https://drive.google.com/file/d/1xoLJjXM5nsb-mjUwaV-JA4uRpUFLBTif/view)

## 1: Intro

My name is Miguel Garcia.
My research centers on m6A, the most abundant mRNA modification on eukaryotes; implicated in
development, physiology, and disease. A major limitation in the field has been the inability to
quantify its stoichiometry at individual sites in a high-throughput manner. Blinding us to the
fine-grained resolution in which m6A may operate.

## 2: MAZTER-seq methodology

To alleviate this limitation, we developed MAZTER-seq, coupling RNA-seq with the ability of the
MazF RNAse to cleave at the unmethylated ACA motif, but not at its m6A-methylated
counterpart.
For analysis of MAZTER-seq data, we developed a computational pipeline called MAZTER-mine,
which processes raw data and calculates the mazF “Cleavage efficiency” for each ACA site in the
transcriptome.
Using in-vitro transcripts harboring a single m6A site, we generated spike-ins with different
stoichiometries of m6A, for which MAZTER-seq yielded highly correlated measurements.
Next, an example of a known m6A site in a wild-type yeast strain, in which cleavage by mazF is
substantially reduced compared to a double knock-out strain of the m6A methyltransferase IME4.

## 3. m6A stoichiometry is predictable across the transcriptome 

After establishing MAZTER-seq, we compared all the ACA sites of the IME4 knock-out yeast to its
control. Doing this, we detected significant differences for 410 sites, including 56 previously
known sites.
Using both known and newly detected m6A sites, we used their sequence, along with additional
data, to fit a linear regression. Our results show that measured and predicted stoichiometries have
a high correlation, explaining almost fifty percent of the variation in stoichiometry levels.
Moreover, we performed an analog experiment in mouse embryonic stem cells, achieving
comparable results when knocking out the methyltransferase METTL3. Graphical depictions of
the models resonate with each other, as both models share similar coefficients to calculate m6A
stoichiometries.

## Epilogue

My results, thus show that:
MAZTER-seq allows systematic m 6 A quantification at single-nucleotide resolution in diverse
biological settings.
And, m 6 A stoichiometry is “hard-coded” by a simple, predictable, and conserved code.
