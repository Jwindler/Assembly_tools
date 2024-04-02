# Assembly analysis tools and papers

![GitHub Repo stars](https://img.shields.io/github/stars/Jwindler/Assembly_tools) ![GitHub pull requests](https://img.shields.io/github/issues-pr/Jwindler/Assembly_tools) ![GitHub License](https://img.shields.io/github/license/Jwindler/Assembly_tools)

Genome Assembly tools are added by pipeline. **Welcome contribute and get in touch!**

[Google Group](https://groups.google.com/g/assembly-tools) | [Volunteers](https://github.com/Jwindler/Assembly_tools/blob/main/Volunteers.md)  | [CONTRIBUTING](https://github.com/Jwindler/Assembly_tools/blob/main/CONTRIBUTING.md)



>   **If there is an error in cited papers or tool does not included in list, please raise an** [ISSUE](https://github.com/Jwindler/Assembly_tools/issues). 



## Table of content

- [Assembly analysis tools and papers](#assembly-analysis-tools-and-papers)
  - [Table of content](#table-of-content)
  - [Survery](#survery)
  - [Conitg](#conitg)
  - [Scaffold](#scaffold)
  - [Polish](#polish)
  - [Evaluation](#evaluation)

 




## Survery



| Name        | Introduction                                                 | Paper                                                        | Url                                                 | Note            | Public Date |
| ----------- | ------------------------------------------------------------ | ------------------------------------------------------------ | --------------------------------------------------- | --------------- | ----------- |
| GenomeScope | Fast genome analysis from unassembled short reads.           | [*Bioinformatics*](https://doi.org/10.1093/bioinformatics/btx153) | [Github](https://github.com/schatzlab/genomescope)  |                 | 2017.3      |
| smudgeplot  | Such an approach also allows us to analyze obscure genomes with duplications, various ploidy levels, etc. | [*Nature Communications*](https://doi.org/10.1038/s41467-020-14998-3) | [Github](https://github.com/KamilSJaron/smudgeplot) | GenomeScope 2.0 | 2020.3      |
| Jellyfish   | Jellyfish is a tool for fast, memory-efficient counting of k-mers in DNA. | [*Bioinformatics*](https://doi.org/10.1093/bioinformatics/btr011) | [Github](https://github.com/gmarcais/Jellyfish)     |                 | 2011.1      |
| nQuire      | A statistical framework for ploidy estimation using NGS short-read data. | [*BMC Bioinformatics*](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-018-2128-z) | [Github](https://github.com/clwgg/nQuire)           |                 | 2018.4      |
| KMC         | Counting and manipulating k-mer statistics.                  | [*Bioinformatics*](https://academic.oup.com/bioinformatics/article/33/17/2759/3796399?login=false) | [Github](https://github.com/refresh-bio/KMC)        |                 | 2017.5      |
| KAT         | a K-mer analysis toolkit to quality control NGS datasets and genome assemblies | [*Bioinformatics*](https://academic.oup.com/bioinformatics/article/33/4/574/2664339) | [Github](https://github.com/TGAC/KAT)               |                 | 2016.11     |





## Conitg



| Name           | Introduction                                                 | Paper                                                        | Url                                                          | Note | Public Date |
| -------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ---- | ----------- |
| Hifiasm        | Hifiasm is a fast haplotype-resolved de novo assembler initially designed for PacBio HiFi reads. | [*Nat Methods*](https://doi.org/10.1038/s41592-020-01056-5)  | [Github](https://github.com/chhylp123/hifiasm)               |      | 2021.2      |
| HiCanu         | designed for high-noise single-molecule sequencing (such as the [PacBio](http://www.pacb.com/) [RS II](http://www.pacb.com/products-and-services/pacbio-systems/rsii/)/[Sequel](http://www.pacb.com/products-and-services/pacbio-systems/sequel/) or [Oxford Nanopore](https://www.nanoporetech.com/) [MinION](https://nanoporetech.com/products)). | [*Genome Research*](https://genome.cshlp.org/content/early/2020/08/14/gr.263566.120) | [Github](https://github.com/marbl/canu)                      |      | 2020.8      |
| NextDenovo     | NextDenovo is a string graph-based *de novo* assembler for long reads (CLR, ~~HiFi~~ and ONT). | [*bioRxiv*](https://www.biorxiv.org/content/10.1101/2023.03.09.531669v1) | [Github](https://github.com/Nextomics/NextDenovo)            |      | 2023.3      |
| IPA            |                                                              |                                                              | [Github](https://github.com/PacificBiosciences/pbipa)        |      |             |
| Flye           | De novo assembler for single molecule sequencing reads using repeat graphs. | [*Nature Methods*](https://doi.org/10.1038/s41592-020-00971-x) | [Github](https://github.com/fenderglass/Flye)                |      | 2020.10     |
| Peregrine      | Peregrine is a fast genome assembler for accurate long reads (length > 10kb, accuracy > 99%). | [*bioRxiv*](https://www.biorxiv.org/content/10.1101/705616v1.full-text) | [Github](https://github.com/cschin/Peregrine)                |      | 2019.7      |
| HGAP4          | HGAP4 is suitable for assembling a wide range of genome sizes and complexity. | [*Nature Methods*](https://www.nature.com/articles/nmeth.2474) | [PacBio](https://www.pacb.com/videos/tutorial-hgap4-de-novo-assembly-application/) |      | 2013.5      |
| Wtdbg2         | A fuzzy Bruijn graph approach to long noisy reads assembly.  | [*Nature Methods*](https://www.nature.com/articles/s41592-019-0669-3) | [Github](https://github.com/ruanjue/wtdbg2)                  |      | 2019.12     |
| Falcon         | a set of tools for fast aligning long reads for consensus and assembly. | [*Nature Methods*](https://www.nature.com/articles/nmeth.4035) | [Github](https://github.com/PacificBiosciences/FALCON/)      |      | 2016.10     |
| SMARTdenovo    | Ultra-fast de novo assembler using long noisy reads.         | [*Gigabyte*](https://gigabytejournal.com/articles/15)        | [Github](https://github.com/ruanjue/smartdenovo)             |      | 2021.3      |
| miniasm        | Ultrafast de novo assembly for long noisy reads (though having no consensus step) | [*Bioinformatics*](https://doi.org/10.1093/bioinformatics/btw152) | [Github](https://github.com/lh3/miniasm)                     |      | 2016.6      |
| necat          | Nanopore data assembler                                      | [*Nature Communications*](https://www.nature.com/articles/s41467-020-20236-7) | [Github](https://github.com/xiaochuanle/NECAT)               |      | 2021.1      |
| Hypo-Assembler | A diploid genome polisher and assembler.                     | [*Nature Methods*](https://www.nature.com/articles/s41592-023-02142-0) | [Github](https://github.com/kensung-lab/hypo-assembler)      |      | 2024.3      |
| Verkko         | a hybrid genome assembly pipeline developed for T2T assembly of  HiFi or ONT reads. | [*Nature Biotechnology*](https://doi.org/10.1038/s41587-023-01662-6) | [Github](https://github.com/marbl/verkko)                    |      | 2023.2      |
| NextPolish2    | Repeat-aware polishing genomes assembled using HiFi long reads. | [*GPB*](https://doi.org/10.1093/gpbjnl/qzad009)              | [Github](https://github.com/Nextomics/NextPolish2)           |      | 2024.1      |
| Merfin         | Evaluate variant calls and its combination with k-mer multiplicity. | [*Nature Methods*](https://doi.org/10.1038/s41592-022-01445-y) | [Github](https://github.com/arangrhie/merfin)                |      | 2022.3      |
| SOAPdenovo2    | Next generation sequencing reads de novo assembler.          | [*Bioinformatics*](https://doi.org/10.1093/bioinformatics/btv033) | [Github](https://github.com/aquaskyline/SOAPdenovo2)         |      | 2015.1      |
| Canu           | A single molecule sequence assembler for genomes large and small. | [*Genome Research*](https://doi.org/10.1101%2Fgr.215087.116) | [Github](https://github.com/marbl/canu)                      |      | 2017.5      |





## Scaffold



| Name         | Introduction                                                 | Paper                                                        | Url                                                    | Note                                            | Public Date |
| ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------ | ----------------------------------------------- | ----------- |
| 3D-DNA       | Scaffold genome with Hi-C data.                              | [*Science*](https://www.science.org/doi/10.1126/science.aal3327) | [Github](https://github.com/aidenlab/3d-dna)           | Use Hi-C data                                   | 2017.3      |
| LACHESIS     | Use Hi-C data for ultra-long-range scaffolding of *de novo* genome assemblies. | [*Nature Biotechnology*](https://www.nature.com/articles/nbt.2727) | [Github](https://github.com/shendurelab/LACHESIS)      | LACHESIS is no longer being actively developed. | 2013.12     |
| SALSA2       | A tool to scaffold long read assemblies with Hi-C data.      | [*bioRxiv*](https://www.biorxiv.org/content/10.1101/261149v1) | [Github](https://github.com/marbl/SALSA)               |                                                 | 2018.2      |
| YaHS         | Yet another Hi-C scaffolding tool.                           | [*Bioinformatics*](https://doi.org/10.1093/bioinformatics/btac808) | [Github](https://github.com/c-zhou/yahs)               | recommend                                       | 2022.12     |
| instaGRAAL   | Large genome reassembly based on Hi-C data, continuation of GRAAL. | [*Nature Communications*](https://www.nature.com/articles/ncomms6695) | [Github](https://github.com/koszullab/instaGRAAL)      | NVIDIA graphics card is required                | 2014.12     |
| EndHiC       | a fast and easy-to-use Hi-C scaffolding tool.                | [*Quantitative Biology*](https://doi.org/10.48550/arXiv.2111.15411) | [Github](https://github.com/fanagislab/EndHiC)         |                                                 | 2021.11     |
| Pin_hic      | A Hi-C scaffolding method.                                   | [*BMC Bioinformatics*](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-021-04453-5) | [Github](https://github.com/dfguan/pin_hic)            |                                                 | 2021.11     |
| AutoHiC      | A novel genome assembly pipeline based on deep learning.     | [*bioRxiv*](https://doi.org/10.1101/2023.08.27.555031)       | [Github](https://github.com/Jwindler/AutoHiC)          | recommend (Deep Learning)                       | 2023.8      |
| ALLHiC       | phasing and scaffolding polyploid genomes based on Hi-C data. | [*Nature Plants*](https://www.nature.com/articles/s41477-019-0487-8) | [Github](https://github.com/tangerzhang/ALLHiC)        | recommend (Plant)                               | 2019.8      |
| Juicebox     | a point-and-click interface for using Hi-C heatmaps to identify and correct errors in a genome assembly. | [*bioRxiv*](https://www.biorxiv.org/content/10.1101/254797v1) | [Github](https://github.com/aidenlab/Juicebox)         |                                                 | 2018.1      |
| SLR          | Scaffolding using long reads obtained by the third generation sequencing technologies. | [*BMC Bioinformatics*](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-3114-9) | [Github](https://github.com/luojunwei/SLR)             |                                                 | 2019.10     |
| LongStitch   | Correct and scaffold assemblies using long reads.            | [*BMC Bioinformatics*](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-021-04451-7) | [Github](https://github.com/bcgsc/LongStitch)          |                                                 | 2021.10     |
| RagTag       | a collection of software tools for scaffolding and improving modern genome assemblies. | [*Genome Biology*](https://doi.org/10.1186/s13059-022-02823-7) | [Github](https://github.com/malonge/RagTag)            |                                                 | 2022.12     |
| HapHiC       | a fast, reference-independent, allele-aware scaffolding tool based on Hi-C data. | [*bioRxiv*](https://doi.org/10.1101/2023.11.18.567668)       | [Github](https://github.com/zengxiaofei/HapHiC)        |                                                 | 2023.11     |
| scaffhic     | Pipeline for genome scaffolding by modelling distributions of HiC pairs. |                                                              | [Github](https://github.com/wtsi-hpag/scaffHiC)        |                                                 |             |
| HiCAssembler | Software to assemble contigs/scaffolds into chromosomes using Hi-C data. | [*Genes & Dev*](https://doi.org/10.1101/gad.328971.119)      | [Github](https://github.com/maxplanck-ie/HiCAssembler) |                                                 | 2019.10     |
| HaploHiC     | comprehensive haplotype division of Hi-C PE-reads based on local contacts ratio. |                                                              | [Github](https://github.com/Nobel-Justin/HaploHiC)     |                                                 |             |
| DipAsm       | Efficient chromosome-scale haplotype-resolved assembly of human genomes. | [*bioRxiv*](https://www.biorxiv.org/content/10.1101/810341v2) | [Github](https://github.com/shilpagarg/DipAsm)         |                                                 | 2020.7      |





## Polish



| Name            | Introduction                                                 | Paper                                                        | Url                                                          | Note | Public Date |
| --------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ---- | ----------- |
| YAGcloser       | Yet-Another-Gap-Closer based on spanning of long reads.      | [*Journal of Heredity*](https://academic.oup.com/jhered/article/113/6/665/6585917) | [Github](https://github.com/merlyescalona/yagcloser)         |      | 2022.5      |
| TGS-Gapcloser   | A gap-closing software tool that uses long reads to enhance genome assembly. | [*GigaScience*](https://doi.org/10.1093/gigascience/giaa094) | [Github](https://github.com/BGI-Qingdao/TGS-GapCloser)       |      | 2020.9      |
| DENTIST         | Close assembly gaps using long-reads at high accuracy.       | [*GigaScience*](https://doi.org/10.1093/gigascience/giab100) | [Github](https://github.com/a-ludi/dentist)                  |      | 2022.1      |
| Redundans       | a pipeline that assists an assembly of heterozygous/polymorphic genomes. | [*Nucleic Acids Research*](https://doi.org/10.1093/nar/gkw294) | [Github](https://github.com/Gabaldonlab/redundans)           |      | 2016.4      |
| Purge Haplotigs | an effective tool for the early stages of curating highly heterozygous genome assemblies produced from third-generation long read sequencing. | [*BMC Bioinformatics*](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-018-2485-7) | [Bitbucket](https://bitbucket.org/mroachawri/purge_haplotigs) |      | 2018.11     |
| Purge_dups      | haplotypic duplication identification tool.                  | [*Bioinformatics*](https://doi.org/10.1093/bioinformatics/btaa025) | [Github](https://github.com/dfguan/purge_dups)               |      | 2020.1      |
| Pilon           | an automated genome assembly improvement and variant detection tool. | [*PLOS ONE*](https://doi.org/10.1371/journal.pone.0112963)   | [Github](https://github.com/broadinstitute/pilon)            |      | 2014.11     |
| Racon           | Ultrafast consensus module for raw de novo genome assembly of long uncorrected reads. | [*Genome Research*](https://genome.cshlp.org/content/early/2017/01/18/gr.214270.116) | [Github](https://github.com/isovic/racon)                    |      | 2017.1      |
| nextpolish      | Fast and accurately polish the genome generated by long reads. | [*Bioinformatics*](https://doi.org/10.1093/bioinformatics/btz891) | [Github](https://github.com/Nextomics/NextPolish)            |      | 2020.4      |



## Evaluation

**Genome assembly evaluation tools.**

| Name           | Introduction                                                 | Paper                                                        | Url                                                          | Note              | Public Date |
| -------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------- | ----------- |
| QUAST          | a quality assessment tool for evaluating and comparing genome assemblies. | [*Bioinformatics*](https://doi.org/10.1093/bioinformatics/btt086) | [Github](https://github.com/ablab/quast)                     |                   | 2013.2      |
| BioNanoAnalyst | a visualisation tool to assess genome assembly quality using BioNano data. | [*BMC Bioinformatics*](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-017-1735-4) | [Github](https://github.com/AppliedBioinformatics/BioNanoAnalyst) | Use BioNano  data | 2017.6      |
| CRAQ           | Identification of errors in draft genome assemblies with single-base pair resolution for quality assessment and improvement. | [*Nature Communications*](https://www.nature.com/articles/s41467-023-42336-w) | [Github](https://github.com/JiaoLaboratory/CRAQ)             | Single base scale | 2023.10     |
| BUSCO          | assessing genome assembly and annotation completeness with single-copy orthologs. | [*Bioinformatics*](https://doi.org/10.1093/bioinformatics/btv351) | [BUSCO](https://busco.ezlab.org/)                            |                   | 2015.6      |
| Merqury        | k-mer based assembly evaluation                              | [*Genome Biology*](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-020-02134-9) | [Github](https://github.com/marbl/merqury)                   |                   | 2020.9      |
| Klumpy         | A Tool to Evaluate the Integrity of Long-Read Genome Assemblies and Illusive Sequence Motifs. | [*bioRxiv*](https://www.biorxiv.org/content/10.1101/2024.02.14.580330v1.full) | [Bitbucket](https://bitbucket.org/Gio12/klumpy/src/master/)  |                   |             |
| GAEP           | a comprehensive genome assembly evaluating pipeline.         | [*JGG*](https://pubmed.ncbi.nlm.nih.gov/37245652/)           | [Github](https://github.com/zy-optimistic/GAEP)              |                   | 2023.5      |
| Flagger        | Evaluating genome assemblies.                                | [*Nature*](https://www.nature.com/articles/s41586-023-05896-x) | [Github](https://github.com/mobinasri/flagger)               |                   | 2023.5      |
| Asset          | assembly evaluation tool.                                    |                                                              | [Github](https://github.com/dfguan/asset)                    |                   |             |
| Inspector      | A tool for evaluating long-read de novo assembly results.    | [*Genome Biology*](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-021-02527-4) | [Github](https://github.com/Maggi-Chen/Inspector)            |                   | 2021.11     |









