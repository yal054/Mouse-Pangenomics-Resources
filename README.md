# Mouse-Pangenomics-Resources
![](https://github.com/yal054/Mouse-Pangenomics-Resources/assets/M_GG_Illust.png)

## Background information
### Preprint

[XXXXXXX]()

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
|  Graph| [GFA](https://wustl.box.com/s/4hefdyjgpaqww4ph49qgr0ke0ji9mj22) [GBZ](https://wustl.box.com/s/2fqgbyy6eudrft42ra6xsq4aysutsyyx)|| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)|  [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)|  [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)|  
|  Full (Unclipped) Graph |  [GFA](https://wustl.box.com/s/5p47tv8m3e2ivck4r336iy4811h5dgby) [GBZ](https://wustl.box.com/s/dow1idkt2i47xez9mwsq0i4icj4v4z8r)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/) | 
|  Decomposed VCF|  [VCF](https://wustl.box.com/s/giskmgths34lkolu8ke4si27ixshznve) | [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/) |
|  Raw VCF|  [VCF](https://wustl.box.com/s/w41h6005qvdbvvkxx6inmheeb4mx9iv2) | [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)|  [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/) | 
|  Multiple Alignment|  [HAL](https://wustl.box.com/s/e0vbeliuov4y9m2lz2o13y8hjgdp5s10) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/) | 
| VG Indexes |  [gbz](https://wustl.box.com/s/v6x2igksd1ioaodr61hytn7g7kqrv838) [dist](https://wustl.box.com/s/v6x2igksd1ioaodr61hytn7g7kqrv838) [min](https://wustl.box.com/s/yb12cz2kzen3nbvrsk2qoqvpqqier24d)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)| [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/)|  [GitHub Pages](https://pages.github.com/) [GitHub Pages](https://pages.github.com/) |
| Graph groups | References, Founders,RI, Others|References, Founders,RI|References, Founders,RI|References,RI|
| Number of assemblies | 95|84|82|4|


## Assembly Inputs and Annotations
FIles for assemblied can be found in the<link>XXX</link>. 
Total 95 assemblies, including **C57BL/6J (version:GRCm38.p6 (accesssion GCF_000001635.26) and GRCm39 (accession GCA_000001635.9)), other 7 founder lines(A/J, 129S1/SvImJ, NOD/ShiLtJ, NZO/HlLtJ, CAST/EiJ, PWK/PhJ, and WSB/EiJ), 75 Collaborative Cross RI lines and other 11 mouse strains. **
> These assemblies only contain chr[1-19|X|Y|M]

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
| CC068 | RI| [FASTA](https://wustl.box.com/s/4unjg2ofnnz0ahffwiljwupg6d8ksf0l)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC070 | RI| [FASTA](https://wustl.box.com/s/teiiafktcyocffhl65vtypq1u8vbzpjf)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC071 | RI| [FASTA](https://wustl.box.com/s/xzcn7cyk0v81e02bxrohgkv2vf6wvek5)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC072 | RI| [FASTA](https://wustl.box.com/s/jsn0piyz7lpb2jqn96wynrj6pbi7gvjx)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC073 | RI| [FASTA](https://wustl.box.com/s/ce5xlazlijcsbydal2umbobxjxk4muib)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC074 | RI| [FASTA](https://wustl.box.com/s/621niri16f35m9rebuvwgfgmhonom1e2)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC075 | RI| [FASTA](https://wustl.box.com/s/352s8r9yxge3a5t1r96ghlszfpg3shy8)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC076 | RI| [FASTA](https://wustl.box.com/s/hfiufa2wbgzr07c9pe00xrgdh8fa16ma)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC078 | RI| [FASTA](https://wustl.box.com/s/s5paq12jmwmudqbickxe86wz0nrq695w)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC079 | RI| [FASTA](https://wustl.box.com/s/ij5j5pw5b9eufpow57ru1ds0toq59qtp)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC080 | RI| [FASTA](https://wustl.box.com/s/k2ebewhnx6e8d5a29j9wyhkzmx9l04se)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC081 | RI| [FASTA](https://wustl.box.com/s/4gmkhqjeakejcrk6101txz1qtn2c6uv9)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC082 | RI| [FASTA](https://wustl.box.com/s/ngjfksb6601e1d5wormdbx7u5temnz4t)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC083 | RI| [FASTA](https://wustl.box.com/s/thqtz9zc6yhn1bbw1fpzy9at3fix2v5c)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|

#### Other Strains
|Species  | Strain   |Graph group| Accession|Assembly Name|Genome|Annotations|Other data|
| --- |--- | --- | --- | --- | --- |--- |--- |
| Mus musculus domesticus | AKR_J|Others | GCA_001624295.1|AKR_J_v1 |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | BALB_cJ|Others | GCA_001632525.1|BALB_cJ_v1 |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus| C3H_HeJ|Others | GCA_001632575.1|C3H_HeJ_v1 | [FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | C57BL_6_T2T|Others| ||[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | C57BL_6NJ|Others| GCA_001632555.1|C57BL_6NJ_v1 |[FASTA](https://wustl.box.com/s/kvu3dk9booxwc8767zstygqsqivo47vw)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus  | CBA_J|Others| GCA_001624475.1|CBA_J_v1 |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | DBA_2J|Others| GCA_001624505.1|DBA_2J_v1 |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus  | FVB_NJ|Others| GCA_001624535.1|FVB_NJ_v1 |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | LG_J|Others| | |[FASTA](https://pages.github.com/)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | LP_J|Others|GCA_001632615.1|LP_J_v1 |[FASTA](https://wustl.box.com/s/cuk47i5c17ie78cbdnd559nhkqv69u6d)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| | SM_J|Others|| |[FASTA](https://wustl.box.com/s/t8wtnr90ejl57bvg2mg2mjh6zv8ejztk)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|

## Datasets
### Whole genome sequencing dataset
#### sequencing datasets
|Sample|	Sample_size	|Reference	|Aligner	|Coordinate| Links|
| --- |--- | --- | --- | --- | --- |
|Real mouse line WGS	|6	|GRCm38	|bwa mem	|GRCm38|[FASTQ](https://pages.github.com/)|
|Real mouse line WGS	|6	|Self Genome	|bwa mem	|Self Genome|[FASTQ](https://pages.github.com/)|
|Real mouse line WGS|	6	|CC Pangenome	|vg giraffe	|CC Pangenome|[FASTQ](https://pages.github.com/)|
|Real mouse line WGS	|10	|F1 Graph	|vg giraffe	|F1 Graph|[FASTQ](https://pages.github.com/)|
|Real mouse line WGS|	6	|CC Pangenome	|vg giraffe	|GRCm38 (by surjection)|[FASTQ](https://pages.github.com/)|
|Real mouse line WGS	|10	|F1 Graph	|vg giraffe	|GRCm38 (by surjection)|[FASTQ](https://pages.github.com/)|

#### simulated datasets
|Sample|	Sample_size	|Reference	|Aligner	|Coordinate| FASTQ|
| --- |--- | --- | --- | --- | --- |
|Simulated RI line WGS|	40|	GRCm38|	bwa mem	|GRCm38|[FASTQ](https://pages.github.com/)|
|Simulated RI line WGS|	40|	Self Genome|	bwa mem	|Self Genome|[FASTQ](https://pages.github.com/)|
|Simulated RI line WGS|	40|	CC Pangenome|	vg giraffe|	CC Pangenome|[FASTQ](https://pages.github.com/)|
|Simulated RI line WGS|	40|	F1 Graph|	vg giraffe|	F1 Graph|[FASTQ](https://pages.github.com/)|
|Simulated RI line WGS|	6|	LT Pangenome|	vg giraffe|	LT Pangenome|[FASTQ](https://pages.github.com/)|
|Simulated RI line WGS|	40|	CC Pangenome|	vg giraffe|	GRCm38 (by surjection)|[FASTQ](https://pages.github.com/)|
|Simulated RI line WGS|	40|	F1 Graph|	vg giraffe|	GRCm38 (by surjection)|[FASTQ](https://pages.github.com/)|
|Simulated RI line WGS|	6	|LT Pangenome|	vg giraffe|	GRCm38 (by surjection)|[FASTQ](https://pages.github.com/)|
### Melthylation datasets
Sample sources: [GSE87101](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE87101)
### ATAC-seq datasets
| Sample |FASTQ|
| --- |--- | 
|JJ011|[FASTQ](https://wustl.box.com/s/r4sjugfswr0yz08dyqapjpng168q25qg)|
|JJ012|[FASTQ](https://wustl.box.com/s/12t0wddzk820kw2pe8ggpgqprbld8slf)|
