# Mouse-Pangenomics-Resources
![](https://github.com/yal054/Mouse-Pangenomics-Resources/assets/M_GG_Illust.png)
The mouse, *Mus musculus*, serves as an important genetic model organism in biomedical research. However, the current linear reference genome limits our ability to accurately capture the genetic diversity and genomic alterations in diverse mouse strains. Here, we present the first draft of the mouse pangenome at base-level resolution, comprising **95** assemblies of widely used mouse breeding strains. Our draft mouse pangenome comprises over **35** million base pairs of genetic variants, which well captures the species’ population structure and underlying evolutionary history. Through comprehensive benchmarking, we demonstrate that our draft mouse pangenome graph surpasses linear genomes by **18.7%** in perfect read mapping quality and reduces reference bias for approximately **3.3%** of genetic variants. By utilizing the personalized pangenomic approach, we can recover over **98%** of variant recombinants from the draft mouse pangenome, even when the recombinant offspring are not explicitly represented in the pangenome. These comprehensive reference resources enhance haplotype- and allele-specific functional genomics analyses across diverse mouse genetic backgrounds.


## Graph Creation Strategies
Graphs are constructed from [Minigraph-Catus](https://github.com/ComparativeGenomicsToolkit/cactus/blob/master/doc/pangenome.md)([cite](https://www.nature.com/articles/s41587-023-01793-w)) summarized in the table below:

|     | Minigraph| Minigraph-Catus |
| --- |--- | --- |
| sequence comparison | reference-based, progressive | reference-based, progressive |
| resolution | SV only|  base-level| 
| scope | full assemblies|  Non-centromeric| 
| cyclic paths |no|  non-reference| 
| short read mapping| untested  |  yes |
| long read mapping| untested | untested |
| Assembly mapping | untested| untested |


## Graphs
Graphs and associated files are summarized below.

| Description| Max Graph| Collaborative Cross (CC) graph| Less Two(LT) graph|F1 Graph|
|  --- |  --- |  --- | --- | --- |
|  Graph| [GFA](https://wustl.box.com/s/xpk01r3ztu68o2h5qlv78rd68ir7m7zd) [GBZ](https://wustl.box.com/s/3z9fockubpvj4da0zci5a3h81lht0rya)| [GFA](https://wustl.box.com/s/gong1snafdvt5nqalipnk04ulv6nmmje) [GBZ](https://wustl.box.com/s/33ax4rhasq4oit84px70iudu17pv23aq)|  [GFA](https://wustl.box.com/s/hgkwd0kzoqb0024xm69w90sqker1nb7o) [GBZ](https://wustl.box.com/s/scwoatvni832o3tvd54z6u26uwq3rrrg)|  [GFA](https://wustl.box.com/s/dvw41wg2dydizgm99oqcc747pphej616) [GBZ](https://wustl.box.com/s/dvw41wg2dydizgm99oqcc747pphej616)|  
|  Full (Unclipped) Graph |  [GFA](https://wustl.box.com/s/jp30waelaaenovtqntct2lqwf2k0vo8a) [GBZ](https://wustl.box.com/s/j3dis9nce0oic8apwn4005m3r79b87i2)| [GFA](https://wustl.box.com/s/evfk0603urcexvxciu61i1hoyony44a1) [GBZ](https://wustl.box.com/s/c59z3plsln71dhr3qerbhbsqjs9y23bq)| [GBZ](https://wustl.box.com/s/2rgi56ciav4er7y3hwj2ay3rpm4z3pjj)| [GFA](https://wustl.box.com/s/dvw41wg2dydizgm99oqcc747pphej616) [GBZ](https://wustl.box.com/s/dvw41wg2dydizgm99oqcc747pphej616) | 
|  Decomposed VCF|  [VCF](https://wustl.box.com/s/owgvcp6p8d6gsnyazsrmd8t653jdia4e) | [VCF](https://wustl.box.com/s/4icd04lr32dya4cwovbg4jg5n48ealvl)| [VCF](https://wustl.box.com/s/3dtkban8ms167cnhvs949tlhroyo4jc9)| [VCF](https://wustl.box.com/s/dvw41wg2dydizgm99oqcc747pphej616) |
|  Raw VCF|  [VCF](https://wustl.box.com/s/ueqyg1bd83rpvi8l27xi302qyonvu1tk) | [VCF](https://wustl.box.com/s/bwdegss4arxpz0dpv9urm4jkkai9m11b)| [VCF](https://wustl.box.com/s/plhqus3atckjbl4o2gzirv1nnlh4wp4h) |  [VCF](https://wustl.box.com/s/dvw41wg2dydizgm99oqcc747pphej616)| 
|  Multiple Alignment|  [HAL](https://wustl.box.com/s/34406okkdytm3hfsid7oszygu9e9zsry)| [HAL](https://wustl.box.com/s/7f00pb3hh1932mid9o1pm57ewdgrcc4p)| [HAL](https://wustl.box.com/s/l62568f800jucqeejhh4s1yyxhoaiu34)| [HAL](https://wustl.box.com/s/dvw41wg2dydizgm99oqcc747pphej616) | 
|  VG Indexes |  [gbz](https://wustl.box.com/s/3z9fockubpvj4da0zci5a3h81lht0rya) [dist](https://wustl.box.com/s/6j72wphwe9yf0etcqopbhrmxx23welcc) [min](https://wustl.box.com/s/cw8kz63rqhdsn52j2c10fi5ddciuwue3)| [gbz](https://wustl.box.com/s/33ax4rhasq4oit84px70iudu17pv23aq) [dist](https://wustl.box.com/s/d8ei3kbdcu59zowfvdaav672soilnvz6) [min](https://wustl.box.com/s/w9nwb03y8wtt6h532dc2dehl4w6fxahg)| [gbz](https://wustl.box.com/s/scwoatvni832o3tvd54z6u26uwq3rrrg) [dist](https://wustl.box.com/s/uxj2x1vr5hoocupj4gtxxjfvz2uqfuiv)  [min](https://wustl.box.com/s/k94jztxery2w9649beovcymzradnpwhg)|  [gbz](https://wustl.box.com/s/dvw41wg2dydizgm99oqcc747pphej616) [dist](https://wustl.box.com/s/dvw41wg2dydizgm99oqcc747pphej616) [min](https://wustl.box.com/s/dvw41wg2dydizgm99oqcc747pphej616) |
|  Graph groups | GRCm38.p6 & GRCm39, Founders,RI, Others|GRCm38.p6 & GRCm39, Founders,RI|GRCm38.p6 & GRCm39, Founders,RI|GRCm38.p6 & GRCm39,RI|
|  Number of assemblies | 95|84|82|4|
|  All Files | [Files](https://wustl.box.com/s/322tmoo7zvzl1940bixyp7jmwsbl1xav)|[Files](https://wustl.box.com/s/7j415ntnomo2shci6jy3vtkrhw27wopu)|[Files](https://wustl.box.com/s/i72ajwlr24ompyjwgehh6ocd308me7cm)|[Files](https://wustl.box.com/s/dvw41wg2dydizgm99oqcc747pphej616)|

## Assembly Inputs and Annotations
FIles for assemblied can be found in the<link>XXX</link>. 
Total 95 assemblies, including ****C57BL/6J (version:GRCm38.p6 (accesssion GCF_000001635.26) and GRCm39 (accession GCA_000001635.9)), other 7 founder lines(A/J, 129S1/SvImJ, NOD/ShiLtJ, NZO/HlLtJ, CAST/EiJ, PWK/PhJ, and WSB/EiJ), 75 Collaborative Cross RI lines and other 11 mouse strains(including a C57 T2T ).** **
> These assemblies only contain chr[1-19|X|Y|M]
> > The GTF file generated by Liftoff with the --copies flag includes comprehensive annotations—genes, exons, transcripts, and duplicated features—mapped from GRCm38 to the target assembly.


Assembles and associated Annotations files are summarized below.
#### 8 founder lines
|Species  | Strain   |Graph group| Accession|Assembly Name|Genome|Annotations|Other data|
| --- |--- | --- | --- | --- | --- |--- |--- |
| Mus musculus domesticus |GRCm39 |References|GCA_000001635.9|GRCm39 |[FASTA](https://wustl.box.com/s/ynnsl3ltkemp769zjq0xxa6rholx8r4d)|||
| Mus musculus domesticus | mm10|References| GCF_000001635.26|GRCm38.p6 |[FASTA](https://wustl.box.com/s/qym3igrwwklet0my9vx8kw2kspirmwkh)|||
| Mus musculus domesticus | A_J|Founders | GCA_001624215.1|A_J_v1 |[FASTA](https://wustl.box.com/s/p1u1dvaq7ht5p271f8l81e3r4qitptx8)|[GTF](https://wustl.box.com/s/bwbvauxxse46k2ttd4mofbodgq71vi17)|[Links](https://wustl.box.com/s/cpc88mimm0eaanavcdwf0bmy0mk1nfih)|
| Mus musculus domesticus | 129S1_SvImJ|Founders | GCA_001624185.1|129S1_SvImJ_v1 |[FASTA](https://wustl.box.com/s/x7mz8u3sa0ellw4izrlt12eh8no1wma3)|[GTF](https://wustl.box.com/s/n9jn9h2ft7ui5w036wz87as849nxbq9c)|[Links](https://wustl.box.com/s/cpc88mimm0eaanavcdwf0bmy0mk1nfih)|
| Mus musculus castaneus | CAST_EiJ|Founders | GCA_001624445.1|CAST_EiJ_v1 | [FASTA](https://wustl.box.com/s/gdk6adwh5b8ov6xmfg8wu8cy7nam7348)|[GTF](https://wustl.box.com/s/r3no1ajuhmn567s40t1sbv056p0vqlru)|[Links](https://wustl.box.com/s/cpc88mimm0eaanavcdwf0bmy0mk1nfih)|
| Mus musculus domesticus | NOD_ShiLtJ|Founders| GCA_001624675.1|NOD_ShiLtJ_v1 |[FASTA](https://wustl.box.com/s/tg4cvued7paah445l97a93zk5bmjssxi)|[GTF](https://wustl.box.com/s/5bmmp2jc0zyz18zijs99veac7h2115rt)|[Links](https://wustl.box.com/s/cpc88mimm0eaanavcdwf0bmy0mk1nfih)|
| Mus musculus domesticus | NZO_HlLtJ|Founders| GCA_001624745.1|NZO_HlLtJ_v1 |[FASTA](https://wustl.box.com/s/otlhbsod76gelujm4rqzrj7ie3fv4p9m)|[GTF](https://wustl.box.com/s/qk77ptz14vb59psyy3jnf1bpfgtn57fc)|[Links](https://wustl.box.com/s/cpc88mimm0eaanavcdwf0bmy0mk1nfih)|
| Mus musculus musculus | PWK_PhJ|Founders| GCA_001624775.1|PWK_PhJ_v1 |[FASTA](https://wustl.box.com/s/iybsk4k3mgf4ic3eg4bqjmw36fo84sqx)|[GTF](https://wustl.box.com/s/bs0p9ie5gjtier4gp3rrsclxltyd6siq)|[Links](https://wustl.box.com/s/cpc88mimm0eaanavcdwf0bmy0mk1nfih)|
| Mus musculus domesticus | WSB_EiJ|Founders| GCA_001624835.1|WSB_EiJ_v1 |[FASTA](https://wustl.box.com/s/ncr13pfg89hnpzd5nrhsct2p5fnteysv)|[GTF](https://wustl.box.com/s/klwjyuuzxlg5eyy0kjzar6o2xnm3dacf)|[Links](https://wustl.box.com/s/cpc88mimm0eaanavcdwf0bmy0mk1nfih)|
#### 75 RI lines
|  Strain   | Graph group| Genome|Annotations|Other data|
| --- | --- | --- | --- | --- |
| CC001 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC002 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/ts0gqgcfymujll9a2zk8rfu8n3xuhrup)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC003 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/yyd5klen8otoj62ctdas24halq5493ua)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC004 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC005 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/wkakr7yt32gk9znzehz0y0enlzrfhjvd)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC006 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/dvn14x15gv6e9odpti9ioka0v4wa05lr)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC007 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/pmpq89boocg9s062c5g2lb8bt48c14g9)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC008 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC009 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC010 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC011 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC012 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/jl0ht8cn5f1o2oo57o5nh9q827u64oc1)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC013 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC015 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/xb5r9ppajeomotr8mighje6gi42wdwyp)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC016 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/nza4q9qlvrhyq5zikrkcbqxg3j4znmef)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC017 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/hr7oc9tib5kfje1an9l68kgu5irlsh2h)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC018 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC019 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC020 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/qx9l86jrtjo0nmv3h1pc35co7cplozgu)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC021 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC022 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC023 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC024 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/o2o961ilyd1dzakngat0miw0eu9e0gv2)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC025 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/pjxso3z261jtkf51nzdiw731vlae08nv)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC026 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC027 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/q5y5kxk9hsr58jv4w9w6ncey2kk28qu5)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC028 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/11g2p8m85ekzwrqgp2iprpk2g1214ioy)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC029 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/m8xpnvpe53p9qnbof5arz8ciiyq4o72g)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC030 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/igvsmbq5rbglcmz26kxdb5ym4hnnbtu4)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC031 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/19jmqtt86nevk8xqylgidmoh3mfwolxf)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC032 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC033 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC034 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC035 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/ps1sk3bjv26h6ccc7qnafay5p67a7cvu)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC036 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/zvf7p583yj9mgwchvgerpu4g1m5rshqa)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC037 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/1s8v6425u0x3av1f7qlsoymanwwo52sv)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC038 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/wac02uj267xqka14otmy7szn3tgvb00p)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC039 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC040 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC041 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC042 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC043 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC044 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/oiuzl503luwu5l0el7kxqepnjqf0b430)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC045 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC046 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/259ym5toog4vmrvxarjvuf5awkj7uv3p)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC047 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/p5i72mdqbt0n9n1ugrnlegtpyvm8a6bz)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC049 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/lxxye61x2zo2ub35whh57zc5ir4xxno7)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC050 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/y7cs7iwii93p1zjxih9rknqkz8gegyxh)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC051 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC052 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC053 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC055 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/08wc8tzdedtgacior3soiicczer6oz2i)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC056 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC057 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/wy28qun8jcles7tknbw7qhlf1xw90l36)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC058 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/cja5unsrjffk6sh2lksw90yyifnnupsv)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC059 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC060 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC061 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/sqp9ksyhyus8anbrdpidkg528medlemx)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC062 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC063 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC065 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC068 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/ihxp9whsqe7gwobyek9xadeiv2wymk3c)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC070 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC071 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/hx39eydkjfcxrdvkhvuman6qyct0sfvp)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC072 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/28e07on3thjvqqc0vn2aumzt8jbb0ma2)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC073 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/24yta37uy37kxtchf9xbj5igxeojjsl3)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC074 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC075 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC076 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/9y6vt3qsugsosg1bwqy717aoaiuvhztr)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC078 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/7od5409460qxe5un0t8925u135sz2dp7)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC079 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/ile9jgo053luiw72fv0yoj1wylj7uzkn)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC080 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC081 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/9y6cdmz8o2b5gxmdywwpqzkqh0azvr39)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC082 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/rq5pmykbaxoxupo4jo9olgxwesg0rxg3)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| CC083 | RI| [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/3688r34s2qjp0u2w9q9ll2g6jgeecmip)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|

#### Other Strains
|Species  | Strain   |Graph group| Accession|Assembly Name|Genome|Annotations|Other data|
| --- |--- | --- | --- | --- | --- |--- |--- |
| Mus musculus domesticus | AKR_J|Others | GCA_001624295.1|AKR_J_v1 |[FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/e8ln2sqs0ojh3wxtj8njzostl2erzovy)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| Mus musculus domesticus | BALB_cJ|Others | GCA_001632525.1|BALB_cJ_v1 |[FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/dkiswr95yaickcj9q7i6u9fpdyx2861m)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| Mus musculus domesticus| C3H_HeJ|Others | GCA_001632575.1|C3H_HeJ_v1 | [FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/7tipumlma6hnd4mmsmj627hijfex5t3g)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| Mus musculus domesticus | **C57BL_6_T2T**|Others| ||[FASTA](https://wustl.box.com/s/5qt3ltaxg5s2p8whky2buo0f1uksdpep)|[GTF](https://wustl.box.com/s/5qt3ltaxg5s2p8whky2buo0f1uksdpep)|[Links](https://wustl.box.com/s/lmhn2379zslxpvzjrdoxm6ji79r8blxj)|
| Mus musculus domesticus | C57BL_6NJ|Others| GCA_001632555.1|C57BL_6NJ_v1 |[FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/jsk9grlu0lsmz25s4s82ls96wh8ek6y6)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| Mus musculus  | CBA_J|Others| GCA_001624475.1|CBA_J_v1 |[FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/9hu1u7lnk1n2c0s72h3ac60t6a8d9wyn)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| Mus musculus domesticus | DBA_2J|Others| GCA_001624505.1|DBA_2J_v1 |[FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/ese61lpnolb9mxn1qc90uczmmox20otb)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| Mus musculus  | FVB_NJ|Others| GCA_001624535.1|FVB_NJ_v1 |[FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/99kpi9t9vunq8zexsxw088pgcwv4mova)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| Mus musculus domesticus | LG_J|Others| | |[FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/eg5w8s7upy16mvmfzeueuir46o8lewsm)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| Mus musculus domesticus | LP_J|Others|GCA_001632615.1|LP_J_v1 |[FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/zju14ja57rp1osqv5fkqi5jfhg2otb04)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|
| | SM_J|Others|| |[FASTA](https://wustl.box.com/s/lc668nghe37s24n3fxauig5s2taans91)|[GTF](https://wustl.box.com/s/gdllhz8hhzprrp3c1rkxl6tcs6jlmd9k)|[Links](https://wustl.box.com/s/exz45aph80yxmfsah1pnwffiz3v9nekz)|

## Datasets
### Whole genome sequencing dataset
Sample sources: [The Mouse Genomes Project](https://www.mousegenomes.org/snps-indels/)

### Melthylation datasets
whole genome bisulfite sequencing (WGBS) data for the C57BL/6J and CAST/EiJ mouse strains, each with 4 biological replicates

Sample sources: [GSE87101](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE87101)


### ATAC-seq datasets
JJ011 and JJ012 are two biological replicates of F1 hybrid mice, generated from a cross between CC032 (maternal) and CC072 (paternal) strains.
| Sample |FASTQ|
| --- |--- | 
|JJ011|[FASTQ](https://wustl.box.com/s/vlcjgw9aizmnpv5zixha9jnrrytbf9ed)|
|JJ012|[FASTQ](https://wustl.box.com/s/oacltq9zoh1dst3a8o9vqqbicz1dm0kv)|

## Cite

[![DOI](https://zenodo.org/badge/992726133.svg)](https://doi.org/10.5281/zenodo.22967912)
