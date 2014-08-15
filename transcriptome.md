---
layout: page
order: 3
title: Transcriptome
permalink: /transcriptome/
subproject: true
teaser: /assets/images/transcription.png
abstract: The transcriptome is the readout of the genome. Identifying common features in it across distant species can reveal fundamental principles. To this end, the ENCODE and modENCODE consortia have generated large amounts of matched RNA-sequencing data for human, worm and fly. Uniform processing and comprehensive annotation of these data allow comparison across metazoan phyla, extending beyond earlier within-phylum transcriptome comparisons and revealing ancient, conserved features. Specifically, we discovered co-expression modules shared across animals, many of which are enriched in developmental genes. We used expression patterns to align the stages in worm and fly development, finding a novel pairing between worm embryo and fly pupae, in addition to the expected embryo-to-embryo and larvae-to-larvae pairings. Furthermore, we found that the extent of non-canonical, non-coding transcription is similar in each organism, per base-pair. Finally, we found in all three organisms the gene-expression levels, both coding and noncoding, can be quantitatively predicted from chromatin features at the promoter using a “universal model," based on a single set of organism-independent parameters.

paper:
  title: Comparative analysis of the transcriptome across distant species

  authors: Gerstein MB, Rozowsky J, Yan K, Wang D, Cheng C, Brown JB, Davis CA, Hillier L, Sisu C, Li JJ, Pei B, Harmanci AO, Duff MO, Djebali S, Alexander RP, Alver BH, Auerbach RK, Bell K, Bickel PJ, Boeck ME, Boley NP, Booth BW, Cherbas L, Cherbas P, Di C, Dobin A, Drenkow J, Ewing B, Fang G, Fastuca M, Feingold EA, Frankish A, Gao G, Good PJ, Green P, Guigó R, Hammonds A, Harrow J, Hoskins RA, Howald C, Hu L, Huang H, Hubbard TJP, Huynh C, Jha S, Kasper D, Kato M, Kaufman TC, Kitchen RR, Ladewig E, Lagarde J, Lai E, Leng J, Lu Z, MacCoss M, May G, McWhirter R, Merrihew G, Miller DM, Mortazavi A, Murad R, Oliver B, Olson S, Park PJ, Pazin MJ, Perrimon N, Pervouchine D, Reinke V, Reymond A, Robinson G, Samsonova A, Saunders GI, Schlesinger F, Sethi A, Slack FJ, Spencer WC, Stoiber MH, Strasbourger P, Tanzer A, Thompson OA, Wan KH, Wang G, Wang H, Watkins KL, Wen J, Wen K, Xue C, Yang L, Yip K, Zaleski C, Zhang Y, Zheng H, Brenner SE, Graveley BR, Celniker SE, Gingeras TR, and Waterston R 

  authors_short: Gerstein et al.

  meta: Nature, in press, 2014

  url:   
---

## Protein-Coding Gene Annotation

*   Human protein-coding gene annotation, in gtf format, from GENCODE v10: [gen10_CDS+exons_only_protein-coding_only.gtf.gz](http://cmptxn.gersteinlab.org/Comparative_Datasets.xlsx)
*   Worm protein-coding gene annotation, in gtf format, from modENCODE June 2012 freeze: [AG1201.integrated_transcripts_strictly_coding.ws220.gtf.gz](http://cmptxn.gersteinlab.org/AG1201.integrated_transcripts_strictly_coding.ws220.gtf.gz)
*   Fly protein-coding gene annotation, in gtf format, from modENCODE June 2012 freeze: [coding_Celniker_Drosophila_Annotation_20120616_1428.gtf.gz](http://cmptxn.gersteinlab.org/coding_Celniker_Drosophila_Annotation_20120616_1428.gtf.gz)

## Fly Strict Non-coding Gene

*   Fly strict non-coding annotation, in gtf format, from modENCODE June 2012 freeze: [strict_noncoding_Celniker_Drosophila_Annotation_20120616_1428.gtf.gz](http://cmptxn.gersteinlab.org/strict_noncoding_Celniker_Drosophila_Annotation_20120616_1428.gtf.gz)

## Comparable and Non-comparable Non-coding RNA Annotations

*   Human comparable ncRNA, in gtf format: [human_consensus_ncRNAs_03_23_2013.gtf.tar.bz2](http://cmptxn.gersteinlab.org/human_consensus_ncRNAs_03_23_2013.gtf.tar.bz2)
*   Human non-comparable ncRNA, in gtf format: [human_non_consensus_ncRNAs_03_23_2013.gtf.tar.bz2](http://cmptxn.gersteinlab.org/human_non_consensus_ncRNAs_03_23_2013.gtf.tar.bz2)
*   Worm comparable ncRNA, in gtf format: [worm_consensus_ncRNAs_03_23_2013.gtf.tar.bz2 ](http://cmptxn.gersteinlab.org/worm_consensus_ncRNAs_03_23_2013.gtf.tar.bz2 )
*   Worm non-comparable ncRNA, in gtf format: [worm_non_consensus_ncRNAs_03_23_2013.gtf.tar.bz2](http://cmptxn.gersteinlab.org/worm_non_consensus_ncRNAs_03_23_2013.gtf.tar.bz2)
*   Fly comparable ncRNA, in gtf format: [fly_consensus_ncRNAs_03_23_2013.gtf.tar.bz2](http://cmptxn.gersteinlab.org/fly_consensus_ncRNAs_03_23_2013.gtf.tar.bz2)
*   Fly non-comparable ncRNA, in gtf format: [fly_non_consensus_ncRNAs_03_23_2013.gtf.tar.bz2](http://cmptxn.gersteinlab.org/fly_non_consensus_ncRNAs_03_23_2013.gtf.tar.bz2)

## Human-Worm-Fly Ortholog Lists

*   MIT Human-Worm-Fly Orthologs: [Modencode.merged.orth20120611_wfh_comm_all.csv](http://cmptxn.gersteinlab.org/Modencode.merged.orth20120611_wfh_comm_all.csv)

## Table Summarizing Processed Expression Values for all Annotated Genes

*   Human coding gene details, in Excel format: [human_gene.xlsx](http://cmptxn.gersteinlab.org/human_gene.xlsx)
*   Worm coding gene details, in Excel format: [worm_gene.xlsx](http://cmptxn.gersteinlab.org/worm_gene.xlsx)
*   Fly coding gene details, in Excel format: [fly_gene.xlsx](http://cmptxn.gersteinlab.org/fly_gene.xlsx)

## Transcriptionally Active Regions (TARs)

*   TARs in human at 90% threshold, in bed format: [human_exon_disc_90_tars.bed](http://cmptxn.gersteinlab.org/human_exon_disc_90_tars.bed)
*   TARs in human at 98% threshold, in bed format: [human_exon_disc_98_tars.bed](http://cmptxn.gersteinlab.org/human_exon_disc_98_tars.bed)
*   TARs in worm  at 90% threshold, in bed format: [worm_exon_disc_90_tars.bed](http://cmptxn.gersteinlab.org/worm_exon_disc_90_tars.bed)
*   TARs in worm at 98% threshold, in bed format: [worm_exon_disc_98_tars.bed](http://cmptxn.gersteinlab.org/worm_exon_disc_98_tars.bed)
*   TARs in fly at 90% threshold, in bed format: [fly_exon_disc_90_tars.bed](http://cmptxn.gersteinlab.org/fly_exon_disc_90_tars.bed)
*   TARs in fly at 98% threshold, in bed format: [fly_exon_disc_98_tars.bed](http://cmptxn.gersteinlab.org/fly_exon_disc_98_tars.bed)

## Enhancers

*   Human enhancers used for TAR analysis: [Enhancers](http://encodenets.gersteinlab.org/metatracks/)
*   Worm enhancers used for TAR analysis:
*   Fly enhancers used for TAR analysis:

## Clustering of ncRNAs and TARs with Co-expression Modules

*   incRNAs and TARs associated with the 16 modules in three species, tarball of txt files: [16_module_ncRNA.tar.gz](http://cmptxn.gersteinlab.org/16_module_ncRNA.tar.gz)

## Supervised ncRNA predictions (novel ncRNA fragments)

*   Human supervised ncRNA predictions Feb 6 , 2013, in bed format: [hg_incRNA_tar98_intersection_50_6Feb13.bed](http://cmptxn.gersteinlab.org/hg_incRNA_tar98_intersection_50_6Feb13.bed)
*   Worm supervised ncRNA predictions Feb 6 , 2013, in bed format: [ce_incRNA_tar98_intersection_50_6Feb13.bed](http://cmptxn.gersteinlab.org/ce_incRNA_tar98_intersection_50_6Feb13.bed)
*   Fly supervised ncRNA predictions Feb 6 , 2013, in bed format: [dm_incRNA_tar98_intersection_50_6Feb13.bed](http://cmptxn.gersteinlab.org/dm_incRNA_tar98_intersection_50_6Feb13.bed)

## Gene Co-expression Modules

*   16 human, worm and fly co-expressed and co-evolved modules showing highly coordinated expression patterns only during phylotypic stage, tarball of csv files: [16_module.tar.gz](http://cmptxn.gersteinlab.org/16_module.tar.gz)
*   Gene names in 16 conserved modules: [genelist_16modules.xlsx](http://cmptxn.gersteinlab.org/genelist_16modules.xlsx)
*   Enriched Gene Ontology terms on biological process in 16 conserved modules: [GO_16modules_biological_process.xlsx](http://cmptxn.gersteinlab.org/GO_16modules_biological_process.xlsx)
*   Enriched Gene Ontology terms on cellular component in 16 conserved modules: [GO_16modules_cellular_component.xlsx](http://cmptxn.gersteinlab.org/GO_16modules_cellular_component.xlsx)
*   Enriched Gene Ontology terms on molecular function in 16 conserved modules: [GO_16modules_molecular_function.xlsx](http://cmptxn.gersteinlab.org/GO_16modules_molecular_function.xlsx)

## Developmental Stage Mapping between Worm and Fly

*   Embryonic specific worm genes aligned with fly genes in both embryo stage and pupae stage: [wf_dual_mapping.xls](http://cmptxn.gersteinlab.org/wf_dual_mapping.xls)

## Raw Data for the "Comparative Analysis of the Transcriptome across Distant Species"

*   Descriptions of all raw datasets are available in a [google doc](https://docs.google.com/spreadsheets/d/1IcgCLVUuXPzkTxUXLU0c2hB4qevQResFcs1TER_yGjw/edit?usp=sharing), or can be [downloaded here](Comparative_Datasets_with_Links.xlsx) as an Excel spreadsheet.
*   The raw data links alone can also be accessed by  [clicking here](comparative_tables.html).
