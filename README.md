# Protein Foundation Models: A Comprehensive Survey

This repository contains the figures and tables used in the paper "Protein Foundation Models: A Comprehensive Survey". 

<p align="center">
  <img src="figures/Figure1.png" alt="Description" width="800"/>
</p>



## Folder Structure
- `figures/`: Contains figures from the paper.

## Tables

### Table Data: Protein Databases & benchmark

The table below provides details on various protein databases and benchmarks.

| Database       | Size / Content                                     | Last update   | URL                                                          |
| -------------- | -------------------------------------------------- | ------------- | ------------------------------------------------------------ |
| UniProtKB      | 253M sequences                                     | 2025_03       | https://www.uniprot.org/uniprotkb                            |
| UniParc        | 982M sequences                                     | 2025_03       | https://www.uniprot.org/uniparc                              |
| UniRef         | 465M / 208M / 70M clustered sequences (100/90/50%) | 2025_03       | https://www.uniprot.org/uniref                               |
| NCBI (Protein) | > 1.4B sequences                                   | July 2025     | https://www.ncbi.nlm.nih.gov/protein                         |
| RefSeq         | 408M sequences                                     | May 2025      | https://www.ncbi.nlm.nih.gov/refseq                          |
| MGnify         | 2.4B metagenomic protein sequences                 | May 2025      | https://www.ebi.ac.uk/metagenomics                           |
| JGI            | Comprehensive protein sequences                    | June 30, 2024 | [https://img.jgi.doe.gov](https://img.jgi.doe.gov/)          |
| GOPC           | 2.458B marine microbial proteins                   | 2024          | https://db.cngb.org/maya/datasets/MDB0000002                 |
| OMG            | 3.3B protein-coding + 2.8B intergenic sequences    | 2024          | https://huggingface.co/datasets/tattabio/OMG                 |
| Pfam           | 24K protein families (MSA + HMM)                   | v37.2         | [http://pfam.xfam.org](http://pfam.xfam.org/)                |
| BFD            | 2.2B clustered sequences                           | 2021          | [https://bfd.mmseqs.com](https://bfd.mmseqs.com/)            |
| OAS            | > 1B immune repertoire sequences                   | 2021          | https://opig.stats.ox.ac.uk/webapps/oas                      |
| PDB            | 231K protein 3D structures                         | 2025_03       | [https://www.rcsb.org](https://www.rcsb.org/)                |
| CATH           | 601K domains                                       | v4.4          | [https://www.cathdb.info](https://www.cathdb.info/)          |
| AlphaFold DB   | 214M predicted structures                          | 2025_03       | [https://www.alphafold.ebi.ac.uk](https://www.alphafold.ebi.ac.uk/) |
| ESM Atlas      | 772M metagenomic predicted structures              | 2023_02       | [https://esmatlas.com](https://esmatlas.com/)                |
| PDA            | 1.5K de novo designed structures                   | 2025_01       | [https://www.proteindesignatlas.org](https://www.proteindesignatlas.org/) |
| SCOPe          | 259,664 domain entries                             | v2.08         | [https://scop.berkeley.edu](https://scop.berkeley.edu/)      |
| GO             | 8.6M functional annotations                        | 2025_03       | [http://geneontology.org](http://geneontology.org/)          |
| EC             | 8K enzyme classes                                  | 2024_11       | [https://enzyme.expasy.org](https://enzyme.expasy.org/)      |
| KEGG           | 578 pathway maps                                   | 2025_04       | [https://www.kegg.jp](https://www.kegg.jp/)                  |
| Ensembl        | Genome/protein sequences & annotations             | 2024          | [https://www.ensembl.org](https://www.ensembl.org/)          |
| STRING         | > 20B PPIs                                         | v12.0         | [https://string-db.org](https://string-db.org/)              |
| Predictomes    | 40K AlphaFold-predicted PPIs                       | 2025_02       | [https://predictomes.org](https://predictomes.org/)          |
| BindingDB      | 2.9M compound–protein pairs                        | 2025_03       | [https://www.bindingdb.org](https://www.bindingdb.org/)      |
| PDBbind        | 27K binding affinity sets                          | 2024          | [http://www.pdbbind.org.cn](http://www.pdbbind.org.cn/)      |
| SKEMPI 2.0     | 7K mutation-induced interaction changes            | v2.0          | https://life.bsc.es/pid/skempi2                              |
| MINT           | 139,901 curated PPIs                               | 2025_07       | [https://mint.bio.uniroma2.it](https://mint.bio.uniroma2.it/) |
| ProteinGym     | ~300K mutants (benchmark)                          | v1.2          | [https://www.proteingym.org](https://www.proteingym.org/)    |
| VenusMuthub    | Mutation effect prediction benchmark               | 2025          | https://huggingface.co/datasets/AI4Protein/VenusMutHub       |
| ProteinBench   | Benchmark for pFMs                                 | 2024          | https://proteinbench.github.io/                              |
| PFMBench       | 21.8M variants, 3.1M pairs, 1.5M entries           | 2025          | https://github.com/RL4BioMed-AI/PFMBench                     |

### Table Model: Protein Foundation Models

The table below presents key information about various protein foundation models.

| Method (model name)  | Training paradigm | Open source | Year | DOI                                                |
| -------------------- | ----------------- | ----------- | ---- | -------------------------------------------------- |
| ESM-1b               | Autoencoding      | √           | 2021 | 10.1126/science.abe5650                            |
| ProtBert             | Autoencoding      | √           | 2021 | 10.48550/arXiv.2007.06225                          |
| ProtT5               | Autoencoding      | √           | 2021 | 10.48550/arXiv.2007.06225                          |
| ESM-MSA-1b           | Autoencoding      | √           | 2021 | 10.48550/arXiv.2104.12276                          |
| ESM-1v               | Autoencoding      | √           | 2021 | 10.48550/arXiv.2202.01344                          |
| PMLM                 | Autoencoding      | ×           | 2021 | 10.1109/TCBB.2021.3051506                          |
| ProteinBert          | Autoencoding      | √           | 2022 | 10.1093/bioinformatics/btac020                     |
| ESM-2                | Autoencoding      | √           | 2023 | 10.1126/science.ade2574                            |
| Evo-velocity         | Autoencoding      | √           | 2022 | 10.1038/s41586-021-04365-8                         |
| LM-GVP               | Autoencoding      | √           | 2022 | 10.1101/2022.04.11.487886                          |
| ESM-GearNet          | Autoencoding      | √           | 2023 | 10.48550/arXiv.2302.01349                          |
| CLEAN                | Autoencoding      | √           | 2023 | 10.48550/arXiv.2303.07317                          |
| PromptProtein        | Autoencoding      | √           | 2023 | 10.48550/arXiv.2212.11062                          |
| SaProt               | Autoencoding      | √           | 2024 | 10.48550/arXiv.2401.00902                          |
| ESM3                 | Autoencoding      | √           | 2025 | 10.1126/science.ads0018                            |
| ESM C                | Autoencoding      | √           | 2024 | https://www.evolutionaryscale.ai/blog/esm-cambrian |
| ProtGPS              | Autoencoding      | √           | 2025 | 10.1126/science.adq2634                            |
| ESM All-Atom         | Autoencoding      | √           | 2024 | 10.1101/2024.03.04.583284v3                        |
| CaLM                 | Autoencoding      | √           | 2024 | 10.48550/arXiv.2403.03816                          |
| ProMEP               | Autoencoding      | ×           | 2024 | 10.1038/s41422-024-00989-2                         |
| Ankh                 | Autoencoding      | √           | 2023 | 10.48550/arXiv.2301.06568                          |
| EVOLVEpro            | Autoencoding      | √           | 2024 | 10.1126/science.adr6006                            |
| ProtGPT2             | Autoregressive    | √           | 2022 | 10.1093/bioinformatics/btac409                     |
| RITA                 | Autoregressive    | √           | 2022 | 10.48550/arXiv.2205.07524                          |
| ZymCTRL              | Autoregressive    | √           | 2022 | 10.48550/arXiv.2212.11077                          |
| IgLM                 | Autoregressive    | √           | 2023 | 10.48550/arXiv.2301.09642                          |
| ProGen               | Autoregressive    | √           | 2023 | 10.1038/s41587-022-01618-2                         |
| ProGen2              | Autoregressive    | √           | 2023 | 10.1016/j.cels.2023.10.002                         |
| ProGen3              | Autoregressive    | √           | 2025 | 10.1101/2025.04.15.649055v1                        |
| PoET                 | Autoregressive    | √           | 2023 | 10.48550/arXiv.2301.05062                          |
| xTrimoPGLM           | Autoregressive    | √           | 2025 | 10.1038/s41592-025-02636-z                         |
| Fold2Seq             | Autoregressive    | √           | 2021 | 10.1038/s41592-021-01219-2                         |
| ESM-IF1              | Autoregressive    | √           | 2022 | 10.1101/2022.04.10.487779v2                        |
| MSA-Augmenter        | Autoregressive    | √           | 2023 | 10.48550/arXiv.2306.01824                          |
| pAbT5                | Autoregressive    | √           | 2023 | 10.48550/arXiv.2301.02748                          |
| ProteinMPNN          | Autoregressive    | √           | 2022 | 10.1126/science.add2187                            |
| LigandMPNN           | Autoregressive    | √           | 2025 | 10.1038/s41592-025-02626-1                         |
| Pinal                | Autoregressive    | √           | 2024 | 10.1101/2024.08.01.606258                          |
| DiffAb               | Diffusion         | √           | 2022 | 10.48550/arXiv.2211.05234                          |
| RFdiffusion          | Diffusion         | √           | 2023 | 10.1038/s41586-023-06415-8                         |
| DPLM                 | Diffusion         | √           | 2024 | 10.48550/arXiv.2402.18567                          |
| RFdiffusion All-Atom | Diffusion         | √           | 2024 | 10.1126/science.adl2528                            |
| PLACER               | Diffusion         | √           | 2025 | 10.1126/science.adu2454                            |
| DPLM-2               | Diffusion         | √           | 2025 | 10.48550/arXiv.2410.13782                          |
| FoldingDiff          | Diffusion         | √           | 2024 | 10.1038/s41467-024-45051-2                         |
| DiffSBDD             | Diffusion         | √           | 2024 | 10.1038/s43588-024-00737-x                         |
| Genie                | Diffusion         | √           | 2023 | 10.48550/arXiv.2303.07347                          |
| Genie 2              | Diffusion         | √           | 2025 | 10.48550/arXiv.2405.15489                          |
| InstaNovo+           | Diffusion         | √           | 2025 | 10.1038/s42256-025-01019-5                         |
| AlphaFold3           | Diffusion         | √           | 2024 | 10.1038/s41586-024-07487-w                         |
| Protenix             | Diffusion         | √           | 2025 | 10.1101/2025.01.08.631967                          |
| Chai-1               | Diffusion         | √           | 2024 | 10.1101/2024.10.10.615955                          |
| ProteinSGM           | Diffusion         | √           | 2023 | 10.48550/arXiv.2303.01812                          |
| FrameDiff            | Diffusion         | √           | 2023 | 10.48550/arXiv.2302.02277                          |
| EigenFold            | Diffusion         | √           | 2023 | 10.48550/arXiv.2304.02198                          |
| DiffDock             | Diffusion         | √           | 2022 | 10.48550/arXiv.2210.01776                          |
| Chroma               | Diffusion         | √           | 2023 | 10.1038/s41586-023-06728-8                         |
| AlphaFolding         | Diffusion         | √           | 2025 | 10.48550/arXiv.2408.12419                          |
| Boltz-1              | Diffusion         | √           | 2024 | 10.1101/2024.11.19.624167                          |
| Boltz-2              | Diffusion         | √           | 2025 | 10.1101/2025.06.14.659707                          |
| BioEmu               | Diffusion         | √           | 2025 | 10.1101/2024.12.05.626885                          |
| Str2Str              | Diffusion         | √           | 2024 | 10.48550/arXiv.2306.03117                          |
| Proteina             | Flow matching     | √           | 2025 | 10.48550/arXiv.2503.00710                          |
| La-Proteina          | Flow matching     | √           | 2025 | 10.48550/arXiv.2507.09466                          |
| RFdiffusion2         | Flow matching     | √           | 2025 | 10.1101/2025.04.09.648075                          |
| AlphaFlow            | Flow matching     | √           | 2024 | 10.48550/arXiv.2402.04845                          |
| MultiFlow            | Flow matching     | √           | 2024 | 10.48550/arXiv.2402.04997                          |
| P2DFlow              | Flow matching     | √           | 2025 | 10.1021/acs.jctc.4c01620                           |
| FrameFlow            | Flow matching     | √           | 2023 | 10.48550/arXiv.2310.05297                          |
| GAFL                 | Flow matching     | √           | 2024 | 10.48550/arXiv.2411.05238                          |
| FoldFlow             | Flow matching     | √           | 2024 | 10.48550/arXiv.2310.02391                          |
| FoldFlow-2           | Flow matching     | √           | 2024 | 10.48550/arXiv.2405.20313                          |
| CoFlow               | Flow matching     | √           | 2025 | 10.1093/bioinformatics/btaf248                     |

## Contributions

### Contact
For inquiries, feedback, or suggestions, please reach out to **Hao Xu** at xuhao@bmi.ac.cn. Your input is highly appreciated!