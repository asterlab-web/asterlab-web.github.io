---
title: "CASTER"
collection: tools
category: published
type: "Tool"
permalink: /tools/caster
date: 2025-01-23
---

Direct species tree inference from whole-genome alignment

[README](https://github.com/chaoszhang/ASTER/blob/master/tutorial/caster-site.md)

Genomes contain mosaics of discordant evolutionary histories, challenging the accurate inference of the tree of life. Although genome-wide data are routinely used for discordance-aware phylogenomic analyses, because of modeling and scalability limitations, the current practice leaves out large chunks of genomes. As more high-quality genomes become available, we urgently need discordance-aware methods to infer the tree directly from a multiple genome alignment. In this study, we introduce Coalescence-Aware Alignment-Based Species Tree Estimator (CASTER), a theoretically justified site-based method that eliminates the need to predefine recombination-free loci. CASTER is scalable to hundreds of mammalian whole genomes. We demonstrate the accuracy and scalability of CASTER in simulations that include recombination and apply CASTER to several biological datasets, showing that its per-site scores can reveal both biological and artifactual patterns of discordance across the genome.