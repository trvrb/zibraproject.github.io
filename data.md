---
layout: default
title: "Data"
---

## Sequencing data

We have an open data release policy and links to datasets will be made available
as soon as we produce them.

### Validation data

#### MP1751

We have sequenced the MP1751 strain of Zika virus. This virus was originally described by Haddow [1] and has undergone several rounds of passage. This work was performed in collaboration with Public Health England. The Illumina-generated consensus sequence is <a href="/data/Zika_MP1751_NCPV_consensus.fasta">available from this site</a> (data generated by Steve Pullan, Richard Vipond, Miles Carroll and colleagues at Public Health England)

  - MP1751 (R9 pore) <a href="http://s3.climb.ac.uk/nanopore/Zika_MP1751_PHE_Long_R9_2D.tgz">47.9gb</a> (note this is a tar file, extract with ``tar -x``).
  - MP1751 (R9 pore) - multiplex test <a href="http://s3.climb.ac.uk/nanopore/R9_MinKNOW_0.51_PHE_amplicons_lambda_barcoded_demultiplexed_pass.tar">25gb</a>

#### WHO reference strain

We have sequenced the proposed WHO reference strain from French Polynesia (closely related to Brazilian strains) using the latest version of our multiplexed PCR protocol. The strain was kindly supplied by Sally Baylis from the Paul-Ehrlich-Instiut. The Illumina generated consensus sequence <a href="http://www.ncbi.nlm.nih.gov/nuccore/KX369547.1">is available in Genbank (accession KX369547.1)</a>.

  - <a href="http://s3.climb.ac.uk/nanopore/primal_KX369547_R7.3.tgz">PF13/251013-18 (R7 pore, 50000 reads, 26.4Gb)</a>
  - <a href="http://s3.climb.ac.uk/nanopore/primal_KX369547_R9.tgz">PF13/251013-18 (R9 pore, 50000 reads, 9.5Gb)</a>

## Road trip data

Below are links to MinION R9 reads basecalled with Metrichor that fall into the 'pass' folder, i.e. meet a quality threshold and are successfully demultiplexed. Only reads that map to the Zika genome are included. Not all runs have yet completed basecalling, so they may represent a subset of the total available reads. Each PCR run contains a negative water control which is sequenced (not necessarily on each flowcell).

### Flowcell 1

Date: 4th June
Location: Natal

| Barcode | 2D pass reads | Mapped reads | Covered bases (cov>=1) | Covered bases (cov>=20) | link |
|--------|-------|--------|--------|--------|------|
| NB01  |  5952  |  676  |  3719  |  2070  | <a href="http://s3.climb.ac.uk/nanopore/zika_flowcell1_12plex_NB01.tar">FAST5 mapped</a> |
| NB02  |  2361  |  822  |  2859  |  708  | <a href="http://s3.climb.ac.uk/nanopore/zika_flowcell1_12plex_NB02.tar">FAST5 mapped</a> |
| NB03  |  4082  |  1258  |  4481  |  2601  | <a href="http://s3.climb.ac.uk/nanopore/zika_flowcell1_12plex_NB03.tar">FAST5 mapped</a> |
| NB04  |  1554  |  311  |  4750  |  356  | <a href="http://s3.climb.ac.uk/nanopore/zika_flowcell1_12plex_NB04.tar">FAST5 mapped</a> |
| NB05  |  4256  |  1584  |  4934  |  2265  | <a href="http://s3.climb.ac.uk/nanopore/zika_flowcell1_12plex_NB05.tar">FAST5 mapped</a> |
| NB06  |  2406  |  477  |  5145  |  1853  | <a href="http://s3.climb.ac.uk/nanopore/zika_flowcell1_12plex_NB06.tar">FAST5 mapped</a> |
| NB07  |  2442  |  492  |  5572  |  2499  | <a href="http://s3.climb.ac.uk/nanopore/zika_flowcell1_12plex_NB07.tar">FAST5 mapped</a> |
| NB08  |  4246  |  700  |  4785  |  834  | <a href="http://s3.climb.ac.uk/nanopore/zika_flowcell1_12plex_NB08.tar">FAST5 mapped</a> |
| NB09  |  3049  |  1014  |  5233  |  2698  | <a href="http://s3.climb.ac.uk/nanopore/zika_flowcell1_12plex_NB09.tar">FAST5 mapped</a> |
| NB10  |  6446  |  1148  |  6416  |  3859  | <a href="http://s3.climb.ac.uk/nanopore/zika_flowcell1_12plex_NB10.tar">FAST5 mapped</a> |
| NB11  |  7078  |  1602  |  6147  |  3837  | <a href="http://s3.climb.ac.uk/nanopore/zika_flowcell1_12plex_NB11.tar">FAST5 mapped</a> |
| NB12  |  2231  |  860  |  5043  |  1182  | <a href="http://s3.climb.ac.uk/nanopore/zika_flowcell1_12plex_NB12.tar">FAST5 mapped</a> |

### Flowcell 2

Date: 4th June
Location: Natal

| Barcode | 2D pass reads | Mapped reads | Covered bases (cov>=1) | Covered bases (cov>=20) | link |
|--------|-------|--------|--------|--------|------|
| NB01  |  2496  |  433  |  4783  |  1704  | <a href="http://s3.climb.ac.uk/nanopore/zika_library2_12plex_NB01.tar">FAST5 mapped</a> |
| NB02  |  1675  |  602  |  7347  |  1836  | <a href="http://s3.climb.ac.uk/nanopore/zika_library2_12plex_NB02.tar">FAST5 mapped</a> |
| NB03  |  1821  |  344  |  5158  |  1351  | <a href="http://s3.climb.ac.uk/nanopore/zika_library2_12plex_NB03.tar">FAST5 mapped</a> |
| NB04  |  98  |  22  |  4458  |  0  | <a href="http://s3.climb.ac.uk/nanopore/zika_library2_12plex_NB04.tar">FAST5 mapped</a> |
| NB05  |  2604  |  541  |  7048  |  2572  | <a href="http://s3.climb.ac.uk/nanopore/zika_library2_12plex_NB05.tar">FAST5 mapped</a> |
| NB06  |  2424  |  68  |  5216  |  308  | <a href="http://s3.climb.ac.uk/nanopore/zika_library2_12plex_NB06.tar">FAST5 mapped</a> |
| NB07  |  2788  |  2059  |  9408  |  6891  | <a href="http://s3.climb.ac.uk/nanopore/zika_library2_12plex_NB07.tar">FAST5 mapped</a> |
| NB08  |  3016  |  2878  |  10332  |  8789  | <a href="http://s3.climb.ac.uk/nanopore/zika_library2_12plex_NB08.tar">FAST5 mapped</a> |
| NB09  |  2291  |  2235  |  10333  |  8957  | <a href="http://s3.climb.ac.uk/nanopore/zika_library2_12plex_NB09.tar">FAST5 mapped</a> |
| NB10  |  2660  |  479  |  6396  |  2466  | <a href="http://s3.climb.ac.uk/nanopore/zika_library2_12plex_NB10.tar">FAST5 mapped</a> |
| NB11  |  2442  |  122  |  7611  |  303  | <a href="http://s3.climb.ac.uk/nanopore/zika_library2_12plex_NB11.tar">FAST5 mapped</a> |
| NB12  |  2015  |  364  |  8002  |  2746  | <a href="http://s3.climb.ac.uk/nanopore/zika_library2_12plex_NB12.tar">FAST5 mapped</a> |

### Flowcell 3

Date: 6th June 
Location: Joao Pessoa

| Barcode | 2D pass reads | Mapped reads | Covered bases (cov>=1) | Covered bases (cov>=20) | link |
|--------|-------|--------|--------|--------|------|
| NB01  |  3414  |  1717  |  8236  |  6254  | <a href="http://s3.climb.ac.uk/nanopore/zika_library3_11plex_NB01.tar">FAST5 mapped</a> |
| NB02  |  3565  |  1421  |  7708  |  4251  | <a href="http://s3.climb.ac.uk/nanopore/zika_library3_11plex_NB02.tar">FAST5 mapped</a> |
| NB03  |  2606  |  1401  |  8653  |  4834  | <a href="http://s3.climb.ac.uk/nanopore/zika_library3_11plex_NB03.tar">FAST5 mapped</a> |
| NB04  |  4609  |  1164  |  7892  |  5326  | <a href="http://s3.climb.ac.uk/nanopore/zika_library3_11plex_NB04.tar">FAST5 mapped</a> |
| NB05  |  4001  |  2363  |  8359  |  6590  | <a href="http://s3.climb.ac.uk/nanopore/zika_library3_11plex_NB05.tar">FAST5 mapped</a> |
| NB06  |  4683  |  1511  |  8566  |  5385  | <a href="http://s3.climb.ac.uk/nanopore/zika_library3_11plex_NB06.tar">FAST5 mapped</a> |
| NB07  |  3160  |  361  |  6657  |  2377  | <a href="http://s3.climb.ac.uk/nanopore/zika_library3_11plex_NB07.tar">FAST5 mapped</a> |
| NB08  |  3275  |  46  |  4337  |  0  | <a href="http://s3.climb.ac.uk/nanopore/zika_library3_11plex_NB08.tar">FAST5 mapped</a> |
| NB09  |  288  |  121  |  7108  |  326  | <a href="http://s3.climb.ac.uk/nanopore/zika_library3_11plex_NB09.tar">FAST5 mapped</a> |
| NB10  |  2277  |  293  |  6064  |  2108  | <a href="http://s3.climb.ac.uk/nanopore/zika_library3_11plex_NB10.tar">FAST5 mapped</a> |
| NB11  |  56  |  13  |  3190  |  0  | <a href="http://s3.climb.ac.uk/nanopore/zika_library3_11plex_NB11.tar">FAST5 mapped</a> |

### Flowcell 4

Date: 7th June
Location: Joao Pessoa

| Barcode | 2D pass reads | Mapped reads | Covered bases (cov>=1) | Covered bases (cov>=20) | link |
|--------|-------|--------|--------|--------|------|
| NB01  |  293  |  56  |  3527  |  54  | <a href="http://s3.climb.ac.uk/nanopore/zika_library_4_12plex_NB01.tar">FAST5 mapped</a> |
| NB02  |  3592  |  329  |  4117  |  1477  | <a href="http://s3.climb.ac.uk/nanopore/zika_library_4_12plex_NB02.tar">FAST5 mapped</a> |
| NB03  |  2617  |  108  |  3299  |  737  | <a href="http://s3.climb.ac.uk/nanopore/zika_library_4_12plex_NB03.tar">FAST5 mapped</a> |
| NB04  |  3670  |  991  |  8300  |  5379  | <a href="http://s3.climb.ac.uk/nanopore/zika_library_4_12plex_NB04.tar">FAST5 mapped</a> |
| NB05  |  14586  |  704  |  3281  |  746  | <a href="http://s3.climb.ac.uk/nanopore/zika_library_4_12plex_NB05.tar">FAST5 mapped</a> |
| NB06  |  4231  |  53  |  3742  |  224  | <a href="http://s3.climb.ac.uk/nanopore/zika_library_4_12plex_NB06.tar">FAST5 mapped</a> |
| NB07  |  6881  |  470  |  4390  |  1890  | <a href="http://s3.climb.ac.uk/nanopore/zika_library_4_12plex_NB07.tar">FAST5 mapped</a> |
| NB08  |  27  |  3  |  755  |  0  | <a href="http://s3.climb.ac.uk/nanopore/zika_library_4_12plex_NB08.tar">FAST5 mapped</a> |
| NB09  |  25  |  0  |  0  |  0  | <a href="http://s3.climb.ac.uk/nanopore/zika_library_4_12plex_NB09.tar">FAST5 mapped</a> |
| NB10  |  3527  |  703  |  7671  |  3354  | <a href="http://s3.climb.ac.uk/nanopore/zika_library_4_12plex_NB10.tar">FAST5 mapped</a> |
| NB11  |  2939  |  250  |  4741  |  1489  | <a href="http://s3.climb.ac.uk/nanopore/zika_library_4_12plex_NB11.tar">FAST5 mapped</a> |
| NB12  |  647  |  68  |  2469  |  318  | <a href="http://s3.climb.ac.uk/nanopore/zika_library_4_12plex_NB12.tar">FAST5 mapped</a> |

### Flowcell 5

Date: 10th June
Location: Recife

| Barcode | 2D pass reads | Mapped reads | Covered bases (cov>=1) | Covered bases (cov>=20) | link |
|--------|-------|--------|--------|--------|------|
| NB01  |  2073  |  452  |  4236  |  1308  | <a href="http://s3.climb.ac.uk/nanopore/Zika_library_5_8plex_NB01.tar">FAST5 mapped</a> |
| NB02  |  3152  |  612  |  2912  |  1862  | <a href="http://s3.climb.ac.uk/nanopore/Zika_library_5_8plex_NB02.tar">FAST5 mapped</a> |
| NB03  |  2597  |  258  |  3384  |  351  | <a href="http://s3.climb.ac.uk/nanopore/Zika_library_5_8plex_NB03.tar">FAST5 mapped</a> |
| NB04  |  2398  |  277  |  2069  |  628  | <a href="http://s3.climb.ac.uk/nanopore/Zika_library_5_8plex_NB04.tar">FAST5 mapped</a> |
| NB05  |  2770  |  272  |  3522  |  669  | <a href="http://s3.climb.ac.uk/nanopore/Zika_library_5_8plex_NB05.tar">FAST5 mapped</a> |
| NB06  |  2903  |  319  |  4187  |  1060  | <a href="http://s3.climb.ac.uk/nanopore/Zika_library_5_8plex_NB06.tar">FAST5 mapped</a> |
| NB07  |  3112  |  132  |  3837  |  319  | <a href="http://s3.climb.ac.uk/nanopore/Zika_library_5_8plex_NB07.tar">FAST5 mapped</a> |
| NB08  |  954  |  432  |  339  |  329  | <a href="http://s3.climb.ac.uk/nanopore/Zika_library_5_8plex_NB08.tar">FAST5 mapped</a> |

### References

[1] Haddow, A. J., Williams, M. C., Woodall, J. P., Simpson, D. I. H., & Goma, L. K. H. (1964). [Twelve isolations of Zika virus from Aedes (Stegomyia) africanus (Theobald) taken in and above a Uganda forest](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2555143/). Bulletin of the World Health Organization, 31(1), 57–69.
