---
title: "WASTER"
collection: tools
category: released
type: "Tool"
permalink: /tools/waster
date: 2026-02-14
---

Practical de novo phylogenomics from low-coverage short reads

[README](https://github.com/chaoszhang/ASTER/blob/master/tutorial/waster.md)

The advent of affordable whole-genome sequencing has spurred numerous large-scale projects aimed at inferring the tree of life, yet achieving a complete species-level phylogeny remains a distant goal due to significant costs and computational demands. Traditional species tree inference methods, though effective, are hampered by the need for high-coverage sequencing, high-quality genomic alignments, and extensive computational resources. To address these challenges, this study introduces WASTER, a novel de novo tool for inferring shallow phylogenies directly from short-read sequences. WASTER employs a k-mer based approach for identifying variable sites, circumventing the need for genome assembly and alignment. Using simulations, we demonstrate that WASTER achieves accuracy comparable to that of traditional alignment-based methods, even for low sequencing depth, and has substantially higher accuracy than other alignment free methods. We validate WASTER’s efficacy on real data, where it accurately reconstructs phylogenies of eukaryotic species with as low depth as 1.5X. WASTER provides a fast and efficient solution for phylogeny estimation in cases where genome assembly and/or alignment may bias analyses or is challenging, for example due to low sequencing depth. It also provides a method for generating guide trees for tree-based alignment algorithms. WASTER’s ability to accurately estimate shallow phylogenies from low-coverage sequencing data without relying on assembly and alignment will lead to substantially reduced sequencing and computational costs in phylogenomic projects.