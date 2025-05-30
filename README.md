# Mouse-Pangenomics-Resources
![](https://github.com/yal054/Mouse-Pangenomics-Resources/assets/M_GG_Illust.png)

## Background information
### Preprint

[XXXXXXX](https://pages.github.com/)

## Graph Creation Strategies
Graphs are constructed from [Minigraph-Catus](https://github.com/ComparativeGenomicsToolkit/cactus/blob/master/doc/pangenome.md)([cite](https://www.nature.com/articles/s41587-023-01793-w)) summarized in the table below:

|     | Minigraph-Catus |
| --- | --- |
| sequence comparison | reference-based, progressive |
| resolution | base-level| 
| scope | Non-centromeric| 
| cyclic paths |  non-reference| 
| short read mapping |  yes |
| long read mapping | untested |
| Assembly mapping | untested |


## Graphs
Graphs and associated files are summarized below.


| Description| Max Graph| Collaborative Cross (CC) graph| Less Two(LT) graph|F1 Graph|
|  --- |  --- |  --- | --- | --- |
|  Graph|   [GFA](https://wustl.box.com/s/4hefdyjgpaqww4ph49qgr0ke0ji9mj22) [GBZ](https://wustl.box.com/s/2fqgbyy6eudrft42ra6xsq4aysutsyyx)|| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)|  [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)|  [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)|  
|  Full (Unclipped) Graph |  [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/) | 
|  Clipped Graph |  [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)|  [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/) |  
|  Decomposed VCF|  [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/) |
|  Raw VCF|  [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)|  [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/) | 
|  Multiple Alignment|  [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/) | 
| VG Indexes |  [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)|  [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/) |
|  Assembly mapping |  [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| 
| Graph groups | References, Founders,RI, Others|References, Founders,RI|References, Founders,RI|References,RI|
| Number of assemblies | 95|84|82|4|


## Assembly Inputs and Annotations
FIles for assemblied can be found in the<link>XXX</link>. 
Total 95 assemblies, including  C57BL/6J (version:GRCm38.p6 (accesssion GCF_000001635.26) and GRCm39 (accession GCA_000001635.9)), other 7 founder lines(A/J, 129S1/SvImJ, NOD/ShiLtJ, NZO/HlLtJ, CAST/EiJ, PWK/PhJ, and WSB/EiJ), 75 Collaborative Cross RI lines and other 10 mouse strains. 

Assembles and associated Annotations files are summarized below.
#### 8 founder lines
|Species  | Strain   |Graph group| Accession|Assembly Name|Genome|Annotations|Other data|
| --- |--- | --- | --- | --- | --- |--- |--- |
| Mus musculus domesticus |GRCm39 |References|GCA_000001635.9|GRCm39 |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | mm10|References| GCF_000001635.26|GRCm38.p6 |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | A_J|Founders | GCA_001624215.1|A_J_v1 |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | 129S1_SvImJ|Founders | GCA_001624185.1|129S1_SvImJ_v1 |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus castaneus | CAST_EiJ|Founders | GCA_001624445.1|CAST_EiJ_v1 | [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | NOD_ShiLtJ|Founders| GCA_001624675.1|NOD_ShiLtJ_v1 |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | NZO_HlLtJ|Founders| GCA_001624745.1|NZO_HlLtJ_v1 |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus musculus | PWK_PhJ|Founders| GCA_001624775.1|PWK_PhJ_v1 |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | WSB_EiJ|Founders| GCA_001624835.1|WSB_EiJ_v1 |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
#### 75 RI lines
|  Strain   | Graph group| Genome|Annotations|Other data|
| --- | --- | --- | --- | --- |
| CC001 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC002 | RI|[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC003 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC004 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC005 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC006 | RI|[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC007 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC008 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC009 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC010 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC011 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC012 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC013 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC015 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC016 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC017 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC018 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC019 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC020 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC021 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC022 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC023 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC024 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC025 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC026 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC027 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC028 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC029 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC030 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC031 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC032 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC033 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC034 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC035 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC036 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC037 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC038 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC039 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC040 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC041 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC042 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC043 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC044 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC045 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC046 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC047 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC049 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC050 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC051 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC052 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC053 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC055 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC056 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC057 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC058 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC059 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC060 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC061 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC062 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC063 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC065 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC068 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC070 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC071 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC072 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC073 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC074 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC075 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC076 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC078 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC079 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC080 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC081 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC082 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC083 | RI| [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|

#### Other Strains
|Species  | Strain   |Graph group| Accession|Assembly Name|Genome|Annotations|Other data|
| --- |--- | --- | --- | --- | --- |--- |--- |
| Mus musculus domesticus | AKR_J|Others | GCA_001624295.1|AKR_J_v1 |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | BALB_cJ|Others | GCA_001632525.1|BALB_cJ_v1 |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus| C3H_HeJ|Others | GCA_001632575.1|C3H_HeJ_v1 | [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | C57BL_6_T2T|Others| ||[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | C57BL_6NJ|Others| GCA_001632555.1|C57BL_6NJ_v1 |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus  | CBA_J|Others| GCA_001624475.1|CBA_J_v1 |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | DBA_2J|Others| GCA_001624505.1|DBA_2J_v1 |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus  | FVB_NJ|Others| GCA_001624535.1|FVB_NJ_v1 |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | LG_J|Others| | |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | LP_J|Others|GCA_001632615.1|LP_J_v1 |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| | SM_J|Others|| |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|

## Datasets
### Whole genome sequencing dataset
#### sequencing datasets
|Sample|	Sample_size	|Reference	|Aligner	|Coordinate| Links|
| --- |--- | --- | --- | --- | --- |
|Real mouse line WGS	|6	|GRCm38	|bwa mem	|GRCm38|[GTF](https://pages.github.com/)|
|Real mouse line WGS	|6	|Self Genome	|bwa mem	|Self Genome|[GTF](https://pages.github.com/)|
|Real mouse line WGS|	6	|CC Pangenome	|vg giraffe	|CC Pangenome|[GTF](https://pages.github.com/)|
|Real mouse line WGS	|10	|F1 Graph	|vg giraffe	|F1 Graph|[GTF](https://pages.github.com/)|
|Real mouse line WGS|	6	|CC Pangenome	|vg giraffe	|GRCm38 (by surjection)|[GTF](https://pages.github.com/)|
|Real mouse line WGS	|10	|F1 Graph	|vg giraffe	|GRCm38 (by surjection)|[GTF](https://pages.github.com/)|

#### simulated datasets
|Sample|	Sample_size	|Reference	|Aligner	|Coordinate| Links|
| --- |--- | --- | --- | --- | --- |
|Simulated RI line WGS|	40|	GRCm38|	bwa mem	|GRCm38|[GTF](https://pages.github.com/)|
|Simulated RI line WGS|	40|	Self Genome|	bwa mem	|Self Genome|[GTF](https://pages.github.com/)|
|Simulated RI line WGS|	40|	CC Pangenome|	vg giraffe|	CC Pangenome|[GTF](https://pages.github.com/)|
|Simulated RI line WGS|	40|	F1 Graph|	vg giraffe|	F1 Graph|[GTF](https://pages.github.com/)|
|Simulated RI line WGS|	6|	LT Pangenome|	vg giraffe|	LT Pangenome|[GTF](https://pages.github.com/)|
|Simulated RI line WGS|	40|	CC Pangenome|	vg giraffe|	GRCm38 (by surjection)|[GTF](https://pages.github.com/)|
|Simulated RI line WGS|	40|	F1 Graph|	vg giraffe|	GRCm38 (by surjection)|[GTF](https://pages.github.com/)|
|Simulated RI line WGS|	6	|LT Pangenome|	vg giraffe|	GRCm38 (by surjection)|[GTF](https://pages.github.com/)|
### Melthylation datasets
| Sample |Links|
| --- |--- | 
||[GTF](https://pages.github.com/)|
||[GTF](https://pages.github.com/)|
### ATAC-seq datasets
| Sample |Links|
| --- |--- | 
|JJ011|[GTF](https://pages.github.com/)|
|JJ012|[GTF](https://pages.github.com/)|
