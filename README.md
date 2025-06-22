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
|  Graph| [GFA](https://wustl.box.com/s/4hefdyjgpaqww4ph49qgr0ke0ji9mj22) [GBZ](https://wustl.box.com/s/2fqgbyy6eudrft42ra6xsq4aysutsyyx)| [GFA](https://wustl.box.com/s/y6cgmgzoq3ezuwukb4vi8vaoatx5gi6d) [GBZ](https://wustl.box.com/s/qt8olly50uor56rshla21r4w24elkju3)|  [GFA](https://wustl.box.com/s/tbm4aol3c8xjh2g9faxnfcialw80fuwz)|  [GFA](https://wustl.box.com/s/algtmrme867ywvqhdz1iyorgyz4kktil) [GBZ](https://wustl.box.com/s/algtmrme867ywvqhdz1iyorgyz4kktil)|  
|  Full (Unclipped) Graph |  [GFA](https://wustl.box.com/s/5p47tv8m3e2ivck4r336iy4811h5dgby) [GBZ](https://wustl.box.com/s/dow1idkt2i47xez9mwsq0i4icj4v4z8r)| [GFA](https://wustl.box.com/s/ww65iar07qva7t6stgb8zshkel0yiz2u) [GBZ](https://wustl.box.com/s/syn8etjf7o3wbf22lc6ix568rwpckuzq)| [VCF](https://wustl.box.com/s/tbm4aol3c8xjh2g9faxnfcialw80fuwz)| [GFA](https://wustl.box.com/s/algtmrme867ywvqhdz1iyorgyz4kktil) [GBZ](https://wustl.box.com/s/algtmrme867ywvqhdz1iyorgyz4kktil) | 
|  Decomposed VCF|  [VCF](https://wustl.box.com/s/giskmgths34lkolu8ke4si27ixshznve) | [VCF](https://wustl.box.com/s/yqaibvf2zsp00wpfyg76ofm7cw9c1z00)| [VCF](https://wustl.box.com/s/tbm4aol3c8xjh2g9faxnfcialw80fuwz)| [VCF](https://wustl.box.com/s/algtmrme867ywvqhdz1iyorgyz4kktil) |
|  Raw VCF|  [VCF](https://wustl.box.com/s/w41h6005qvdbvvkxx6inmheeb4mx9iv2) | [VCF](https://wustl.box.com/s/pwia2bfgwo0uqx6st7am4n8dzun49dme)| [VCF](https://wustl.box.com/s/tbm4aol3c8xjh2g9faxnfcialw80fuwz) |  [VCF](https://wustl.box.com/s/algtmrme867ywvqhdz1iyorgyz4kktil)| 
|  Multiple Alignment|  [HAL](https://wustl.box.com/s/e0vbeliuov4y9m2lz2o13y8hjgdp5s10)| [HAL](https://wustl.box.com/s/3q3jefm2hkf85gwpoy6bvd7x2znhxaig)| [HAL](https://pages.github.com/)| [HAL](https://wustl.box.com/s/algtmrme867ywvqhdz1iyorgyz4kktil) | 
| VG Indexes |  [gbz](https://wustl.box.com/s/v6x2igksd1ioaodr61hytn7g7kqrv838) [dist](https://wustl.box.com/s/v6x2igksd1ioaodr61hytn7g7kqrv838) [min](https://wustl.box.com/s/yb12cz2kzen3nbvrsk2qoqvpqqier24d)| [gbz](https://wustl.box.com/s/syn8etjf7o3wbf22lc6ix568rwpckuzq) [dist](https://wustl.box.com/s/oxnag0f4330lgpt7wynfy68t7n2z5bqb) [min](https://wustl.box.com/s/kz5hpler2f87ctyhrbzuk2ollpjngwta)| [gbz](https://wustl.box.com/s/tbm4aol3c8xjh2g9faxnfcialw80fuwz) [dist](https://wustl.box.com/s/tbm4aol3c8xjh2g9faxnfcialw80fuwz)  [min](https://wustl.box.com/s/tbm4aol3c8xjh2g9faxnfcialw80fuwz)|  [gbz](https://wustl.box.com/s/algtmrme867ywvqhdz1iyorgyz4kktil) [dist](https://wustl.box.com/s/algtmrme867ywvqhdz1iyorgyz4kktil) [min](https://wustl.box.com/s/algtmrme867ywvqhdz1iyorgyz4kktil) |
| Graph groups | GRCm38.p6 & GRCm39, Founders,RI, Others|GRCm38.p6 & GRCm39, Founders,RI|GRCm38.p6 & GRCm39, Founders,RI|GRCm38.p6 & GRCm39,RI|
| Number of assemblies | 95|84|82|4|
| All Files | [Files](https://wustl.box.com/s/og0ugqesyl2k26accv7frpmv2171k6o3)|[Files](https://wustl.box.com/s/659wuos68gbli9h4ldc75by4vupee7d8)|[Files](https://wustl.box.com/s/tbm4aol3c8xjh2g9faxnfcialw80fuwz)|[Files](https://wustl.box.com/s/algtmrme867ywvqhdz1iyorgyz4kktil)|

## Assembly Inputs and Annotations
FIles for assemblied can be found in the<link>XXX</link>. 
Total 95 assemblies, including ****C57BL/6J (version:GRCm38.p6 (accesssion GCF_000001635.26) and GRCm39 (accession GCA_000001635.9)), other 7 founder lines(A/J, 129S1/SvImJ, NOD/ShiLtJ, NZO/HlLtJ, CAST/EiJ, PWK/PhJ, and WSB/EiJ), 75 Collaborative Cross RI lines and other 11 mouse strains(including a C57 T2T ).** **
> These assemblies only contain chr[1-19|X|Y|M]
> > The GTF file generated by Liftoff with the --copies flag includes comprehensive annotations—genes, exons, transcripts, and duplicated features—mapped from GRCm38 to the target assembly.


Assembles and associated Annotations files are summarized below.
#### 8 founder lines
|Species  | Strain   |Graph group| Accession|Assembly Name|Genome|Annotations|Other data|
| --- |--- | --- | --- | --- | --- |--- |--- |
| Mus musculus domesticus |GRCm39 |References|GCA_000001635.9|GRCm39 |[FASTA](https://wustl.box.com/s/yxn1pxobbigfli6pnhlbph98h1d1a8v9)|||
| Mus musculus domesticus | mm10|References| GCF_000001635.26|GRCm38.p6 |[FASTA](https://wustl.box.com/s/p65sjrxp7gqaa008fujp6hm2sv50gkxs)|||
| Mus musculus domesticus | A_J|Founders | GCA_001624215.1|A_J_v1 |[FASTA](https://wustl.box.com/s/e1kuii99n8nubxrjoskty7aht8ajfcwa)|[GTF](https://wustl.box.com/s/o8xdc1rvg4he0dlcp9enxgvhirokpw06)|[Links](https://wustl.box.com/s/9kmec7vj7i1xtmymy0b97z4nbzmz2383)|
| Mus musculus domesticus | 129S1_SvImJ|Founders | GCA_001624185.1|129S1_SvImJ_v1 |[FASTA](https://wustl.box.com/s/zshlgett36tc46dff81jgl6fiemqlhmc)|[GTF](https://wustl.box.com/s/sg7k4je6ddhyjmi726mh4tz0544hl04b)|[Links](https://wustl.box.com/s/xpcvo15es691xztj603xwypn5f9tk1hj)|
| Mus musculus castaneus | CAST_EiJ|Founders | GCA_001624445.1|CAST_EiJ_v1 | [FASTA](https://wustl.box.com/s/k0qzcks18t2a9y7zy04ykhlz6esepkgr)|[GTF](https://wustl.box.com/s/5uo6f4r62cbppfmvkwwvdekiun4dv3mv)|[Links](https://wustl.box.com/s/uelkgtjy5h3p4fhm89shxlzzdjkvfe6u)|
| Mus musculus domesticus | NOD_ShiLtJ|Founders| GCA_001624675.1|NOD_ShiLtJ_v1 |[FASTA](https://wustl.box.com/s/zycq4s6js4ngpvlhkufi2qec3d94mf3l)|[GTF](https://wustl.box.com/s/zjgftstm73hpvj94y0uombavs2js2vqj)|[Links](https://wustl.box.com/s/u89okf40krecgqw3tg0ldrzojbeqm5nv)|
| Mus musculus domesticus | NZO_HlLtJ|Founders| GCA_001624745.1|NZO_HlLtJ_v1 |[FASTA](https://wustl.box.com/s/m4yh1o7zw5lcfknih2wtxcujm2rznz9j)|[GTF](https://wustl.box.com/s/8xe0ur00iptkeeue365t1q9c0jx0luyw)|[Links](https://wustl.box.com/s/6632q5c6ts2dd8dm8rxpfr3p13decqbc)|
| Mus musculus musculus | PWK_PhJ|Founders| GCA_001624775.1|PWK_PhJ_v1 |[FASTA](https://wustl.box.com/s/3lxspogzff7q4gpiegvnbixtystxw5i9)|[GTF](https://wustl.box.com/s/6oh54rh0bzazz4kcpmhw95ggh18oyuy3)|[Links](https://wustl.box.com/s/rszukox645d4gbndt9t1058r2hs303uv)|
| Mus musculus domesticus | WSB_EiJ|Founders| GCA_001624835.1|WSB_EiJ_v1 |[FASTA](https://wustl.box.com/s/u6xmzscuqwydmphjmxxhfn01cmgwqk8k)|[GTF](https://wustl.box.com/s/g8iciw1pb6j13xhxbpmxhimmt0o0tsb5)|[Links](https://wustl.box.com/s/mguwmgmwr3qhi3g8v8rvltsz5lnlv1eu)|
#### 75 RI lines
|  Strain   | Graph group| Genome|Annotations|Other data|
| --- | --- | --- | --- | --- |
| CC001 | RI| [FASTA](https://wustl.box.com/s/uy454353kqj852wztq8spjt7jm3l0yg5)|[GTF](https://wustl.box.com/s/fqqmvlcp3ejnxgij0ny61xge0iurqvb3)|[Links](https://wustl.box.com/s/j5y2h337j1n1kqu7ksd87xtfvugg7hme)|
| CC002 | RI| [FASTA](https://wustl.box.com/s/dvn5xjpmgdgkxcnpq6xa5cr09dcc0ffi)|[GTF](https://wustl.box.com/s/82depwkq7vgweo6iib0u3tndhklogx4i)|[Links](https://wustl.box.com/s/g7yaye74f1qdr4mzxmckoqthhbro6dlr)|
| CC003 | RI| [FASTA](https://wustl.box.com/s/mhy6f808l0gprtbjg4c204zvc77qvegk)|[GTF](https://wustl.box.com/s/e07k9jfql0dx62432mt8msic5gquqij3)|[Links](https://wustl.box.com/s/dr1j5o8fit7fiyqbet3lv4pwgit02hbq)|
| CC004 | RI| [FASTA](https://wustl.box.com/s/d9nrgl8ssjsne8trnj1ykwan48eu6shm)|[GTF](https://wustl.box.com/s/2m0g8hg4dgwdwnll4f342jmh9905y08r)|[Links](https://wustl.box.com/s/t1h1l283funsorkkt628a12q9asjrt1o)|
| CC005 | RI| [FASTA](https://wustl.box.com/s/7sqekhkqtcy3yzar3d7bg6uipk22530o)|[GTF](https://wustl.box.com/s/j4s2bwg1yw2p3f96l42ie1sgjxky7tzh)|[Links](https://wustl.box.com/s/xrr2pr4zvr98yre3tlsvddnd0v3ttn06)|
| CC006 | RI| [FASTA](https://wustl.box.com/s/j1aeh4tqrcg4jvuca8xuq03husjo1bw5)|[GTF](https://wustl.box.com/s/yw7fntul86icv8ovb9kur2i2e0troagk)|[Links](https://wustl.box.com/s/j59rc5nfjowt0dj4hhp20ueo14c91edx)|
| CC007 | RI| [FASTA](https://wustl.box.com/s/f525vgkmseu09tuozuoa38ccv7kwxav8)|[GTF](https://wustl.box.com/s/g88ligwh9feywelw9chdc1slkytzruh3)|[Links](https://wustl.box.com/s/8azl2j97r6mzi09sfs9qaoxx1s09p8a0)|
| CC008 | RI| [FASTA](https://wustl.box.com/s/ctqyiidzcb5m4mfs5ma0b1pn7u6gk5if)|[GTF](https://wustl.box.com/s/dlrfd4ljgiybe987m76s8y5w7ibanma9)|[Links](https://wustl.box.com/s/nbb66t4d556u26ddo3dlmpvkayl3lxl0)|
| CC009 | RI| [FASTA](https://wustl.box.com/s/3pgcv4pa2nz989lcgblt8hxcgljwagfn)|[GTF](https://wustl.box.com/s/hj911zwg1rm1pprnq21dtgxm5suze0v0)|[Links](https://wustl.box.com/s/r0nnx16w6vezvvbt1dl6pq6f8wrae0aw)|
| CC010 | RI| [FASTA](https://wustl.box.com/s/3z9ncw2orle8vr9s1x41q3ym61rxt0bo)|[GTF](https://wustl.box.com/s/hvyn4bc8ps5zdf1fv9lkhejkw17o2a8p)|[Links](https://wustl.box.com/s/4bfp76c3khu131xnq3id2f0ducc38gyn)|
| CC011 | RI| [FASTA](https://wustl.box.com/s/w9yfneozo51j9hsx1srf0bi3a94xmy17)|[GTF](https://wustl.box.com/s/3carwbv877vouj4hl9p4j2ool8eeqc6k)|[Links](https://wustl.box.com/s/bnme3knwcg0a3hgt2zil3zpa0wn4nbaf)|
| CC012 | RI| [FASTA](https://wustl.box.com/s/puivsvqd65hos4vcas9x2qly9n4s4s9r)|[GTF](https://wustl.box.com/s/sc22uk0uvw0156r02axk79ll002808a9)|[Links](https://wustl.box.com/s/ste9q9i8ickfmhphfzq8mrtg5kbqqscz)|
| CC013 | RI| [FASTA](https://wustl.box.com/s/qob66de772nxfw7tnht0gk2feum9l9uf)|[GTF](https://wustl.box.com/s/z3omo46qv8hua8yx9rwqja74acdrx503)|[Links](https://wustl.box.com/s/805mfqgsg2rr0om45mp3l1zy5zw7f9sb)|
| CC015 | RI| [FASTA](https://wustl.box.com/s/3jvrvsbayjuessk5dbmrg25qxvspwbsa)|[GTF](https://wustl.box.com/s/rgv9v3sfi02ryhcaen8dr5w5c4w7bsr5)|[Links](https://wustl.box.com/s/f79j5dz9uj1zl9mbobhviaqxvfcebg9u)|
| CC016 | RI| [FASTA](https://wustl.box.com/s/gei3fqy6njikhdjapr6tb6exg2baqtuf)|[GTF](https://wustl.box.com/s/zg61ogutaedi86lnkc3xzqo6uh504759)|[Links](https://wustl.box.com/s/ji7ehx8ou1wr8wjdd99dhut0cyldbs5r)|
| CC017 | RI| [FASTA](https://wustl.box.com/s/59lmliu74fpxpcd3j2cjfisaetuyrc4m)|[GTF](https://wustl.box.com/s/5bu9ge24n7cxzg4dxxgarok5sxsjf0hb)|[Links](https://wustl.box.com/s/hhz0lm6qdhrsjzd89hfzsu2oagsbjsr7)|
| CC018 | RI| [FASTA](https://wustl.box.com/s/8lrq3ctan75dy68xf9ry3g54kqmrpi6f)|[GTF](https://wustl.box.com/s/imobo55kj3ggb2i9ilnashnas541jzkt)|[Links](https://wustl.box.com/s/nrowt6id7enpsirx6vs1csge7yb99at8)|
| CC019 | RI| [FASTA](https://wustl.box.com/s/un7mn93wqo63eo1pgxy5ov1zu0fdvfuo)|[GTF](https://wustl.box.com/s/v9p767p3i4lqqcvoisxprq3on10m8740)|[Links](https://wustl.box.com/s/1vv7qsg519hti708fo8h156lu7v3y759)|
| CC020 | RI| [FASTA](https://wustl.box.com/s/qhm5shmq601v73n5mdluw9eek6r0fj2t)|[GTF](https://wustl.box.com/s/4w8gzgbxpo5sq9li3fsrv02iwpr8im62)|[Links](https://wustl.box.com/s/et1dewtj0gqnr52l4lc4ctqcez3f4sby)|
| CC021 | RI| [FASTA](https://wustl.box.com/s/dai28jwp0sy2mde1745owqay89f3ty7y)|[GTF](https://wustl.box.com/s/knd70q7b8sjth5jivel3t8ya5htzybz5)|[Links](https://wustl.box.com/s/d55r8ekybswsrqfydmmqb7yp33d7hw50)|
| CC022 | RI| [FASTA](https://wustl.box.com/s/tbcp6j6euz309eulux9i0ntwklg5grow)|[GTF](https://wustl.box.com/s/d811gg9n64d8mzmq8x8uoz0fbkvk91hx)|[Links](https://wustl.box.com/s/tmz0n585jlm2qgktjafxezbfdntjv3ly)|
| CC023 | RI| [FASTA](https://wustl.box.com/s/49mbj6ueiby25vl3i796q8vnfrderao5)|[GTF](https://wustl.box.com/s/31vwmpmr9lvigj7oft8jk979r078ugzq)|[Links](https://wustl.box.com/s/so0ytfjvab30d57unwreh7al4nhu89rd)|
| CC024 | RI| [FASTA](https://wustl.box.com/s/as2yqmywg6yezmvfxlojoylj5bsfk42l)|[GTF](https://wustl.box.com/s/dp32a52easdnr5p3yfsxmocolzzqphqk)|[Links](https://wustl.box.com/s/lapy1xohu3fn1hojd6d1ce6twd60xc7v)|
| CC025 | RI| [FASTA](https://wustl.box.com/s/4740z6ezj9tx1p86wipf3c83b2y3q0gy)|[GTF](https://wustl.box.com/s/mih8c106ensg9n1bxk7ceqgh7yah9skf)|[Links](https://wustl.box.com/s/njejrjqn7k333vt7bh9jjx1xw5u7mbux)|
| CC026 | RI| [FASTA](https://wustl.box.com/s/fzbyvtxhkub0txfefgjqr6nxcq6xrpju)|[GTF](https://wustl.box.com/s/1np97i2pk1lih4xboqotfu6hl13auijt)|[Links](https://wustl.box.com/s/tfaz8s25nc3to9ykj8nctkp9s7wwwtat)|
| CC027 | RI| [FASTA](https://wustl.box.com/s/9sczg47616g26yzqlv9uvqkp4t8phiab)|[GTF](https://wustl.box.com/s/6l1wad0cmvgnveni17ttatbjikd61tcc)|[Links](https://wustl.box.com/s/1ksd7rd46zzrj3iz9f03nis0fleu1x5g)|
| CC028 | RI| [FASTA](https://wustl.box.com/s/a2m76bktiodzh77z3su4nt039duuvyyj)|[GTF](https://wustl.box.com/s/wi0ky52inljrqjaijsx4f8zr3g6ewheu)|[Links](https://wustl.box.com/s/lothv5a14m0a815oga37vbk86exbzg96)|
| CC029 | RI| [FASTA](https://wustl.box.com/s/cb1vzi0bit21v1n8uwx7opthbf7fg1bw)|[GTF](https://wustl.box.com/s/4oyvvdjsy2i8tkkn8uyn7z3qhaak6z1t)|[Links](https://wustl.box.com/s/c2dg0fr744bfpap3ol3pmeylcmts6xp9)|
| CC030 | RI| [FASTA](https://wustl.box.com/s/pyviel82yfznzupv1x6immkg4f704rmg)|[GTF](https://wustl.box.com/s/awqotaroxoriy8u88ot53ogc1m71yt3y)|[Links](https://wustl.box.com/s/zzzvs6s3fjy8ekw5229h8ekolripbwu5)|
| CC031 | RI| [FASTA](https://wustl.box.com/s/h5ng9vugkxm0jytrguvqu2m0pn6osba3)|[GTF](https://wustl.box.com/s/1zi1bfm0f3wyh7id4dz9nkj9lm78fsvr)|[Links](https://wustl.box.com/s/x7e9e48ufw52u6dixhcs17myworn3fdj)|
| CC032 | RI| [FASTA](https://wustl.box.com/s/akbu71tw1lyh0cb1otn7d6k4z0cntacs)|[GTF](https://wustl.box.com/s/owtf7kindznhdglhgukqe2t6arp93954)|[Links](https://wustl.box.com/s/gt7a4eb82mrckigbosd8ulfvk4m72fvm)|
| CC033 | RI| [FASTA](https://wustl.box.com/s/8jf636t6rriaymxpucjn7tm839sb020y)|[GTF](https://wustl.box.com/s/vp5nucj2rd3gudveo33l3adqmzoy3pr8)|[Links](https://wustl.box.com/s/39op39mu7u88ov9qz0i37oxyvafzu9wm)|
| CC034 | RI| [FASTA](https://wustl.box.com/s/vsf0x18ofcro6ayca47uz4ip7zz0jnlj)|[GTF](https://wustl.box.com/s/eptrtvhg79e9k0roem8zqgsunutiio2p)|[Links](https://wustl.box.com/s/6ya521h9p8jvwa1xhhwp8l4qtu2cuxb4)|
| CC035 | RI| [FASTA](https://wustl.box.com/s/4kznuirh3gh28rx7fid1kpnfmryrgzui)|[GTF](https://wustl.box.com/s/5cakzyhiklklsgfa6vswht690pd00kmo)|[Links](https://wustl.box.com/s/qyqkkqzprspwegx8fjfu6ly35k72siva)|
| CC036 | RI| [FASTA](https://wustl.box.com/s/omxuub32p4ffg0dg0h004l69pbmeal4o)|[GTF](https://wustl.box.com/s/cpjdcd0236696jt3oifdlrg22ubcl6lq)|[Links](https://wustl.box.com/s/j73zzph9t24cc8jrxwgcu9nu84y75vg0)|
| CC037 | RI| [FASTA](https://wustl.box.com/s/gydkxb1u9d0ikpvhjzuqsdrsp8g9q71f)|[GTF](https://wustl.box.com/s/ii37byr25viv8efedwo6ttupb7xu2tyd)|[Links](https://wustl.box.com/s/7isai3qw1msl31fsri8sma93zco2pr9g)|
| CC038 | RI| [FASTA](https://wustl.box.com/s/qi062zt94lie6eyygiqdnj2c11g8a523)|[GTF](https://wustl.box.com/s/goj0kszt2yuh66act7gahwef4a04e559)|[Links](https://wustl.box.com/s/kvdj5hz63pl2gz222jb4ej092ntjau9n)|
| CC039 | RI| [FASTA](https://wustl.box.com/s/m5p62uwz1ha0drbnfq9y4075oagp3w3r)|[GTF](https://wustl.box.com/s/e3p5l1tnhb04k2g3lazj80y1xea1kd91)|[Links](https://wustl.box.com/s/k5i2umwqr0l003tqx5o5wkv4vh7izzcf)|
| CC040 | RI| [FASTA](https://wustl.box.com/s/acwk7tzpakipxxi48b7jmq5oamjeh8xb)|[GTF](https://wustl.box.com/s/7t5cw1durs7odyyjnv2v8hqaact9bhra)|[Links](https://wustl.box.com/s/ycduh3zmey61jfvqd8sfie596jnilpc3)|
| CC041 | RI| [FASTA](https://wustl.box.com/s/tfhd81a3p3q85kq38qmklrp2huyr8qar)|[GTF](https://wustl.box.com/s/aqshbvxqc001thyx68bsd7knb8xzpk3y)|[Links](https://wustl.box.com/s/c90vv1j9skcps9bj2hg70apqgk2l4bjz)|
| CC042 | RI| [FASTA](https://wustl.box.com/s/epxk0w01sge6yandbv8vpzjtrn9j7i54)|[GTF](https://wustl.box.com/s/3zn7fvplx7cmbp300uyxjizxv433dsrv)|[Links](https://wustl.box.com/s/025e8f0yfmh58cuqbgp1ohribiqumjeo)|
| CC043 | RI| [FASTA](https://wustl.box.com/s/o25hx0ulkpgcmanqg9c8sbvwvc38ol1h)|[GTF](https://wustl.box.com/s/5d1x6u1moi1aws08wrnxv7ueb2jlp1yg)|[Links](https://wustl.box.com/s/3wboj917yesu0rz7hsiy3ttdozi5esg3)|
| CC044 | RI| [FASTA](https://wustl.box.com/s/rkg6a4fy9hctuak7y4iz6ws6hzs7irjt)|[GTF](https://wustl.box.com/s/1aoggkjitkr3nqreps02dvmmyj67yov6)|[Links](https://wustl.box.com/s/qud5s8yee80ugye73u81vn1dm9asuwgl)|
| CC045 | RI| [FASTA](https://wustl.box.com/s/lpj7t2bh960rdyfc6p4qvmmo285z3f8y)|[GTF](https://wustl.box.com/s/yr16ilt2xen70nlcj7th2uvini4pec4e)|[Links](https://wustl.box.com/s/tgeztd6i5ugzpmti0lyv3trujlmb4qrw)|
| CC046 | RI| [FASTA](https://wustl.box.com/s/xah49ag6qiyxzig0jp7uzp2axqvr27oh)|[GTF](https://wustl.box.com/s/8i2qmdpsabuflq9kitfdftsf3j9jt2wd)|[Links](https://wustl.box.com/s/46s3d9o482n58iimf2xqmh4vhb52d5q0)|
| CC047 | RI| [FASTA](https://wustl.box.com/s/d9yyk10d7okfh1hacr5gmzyf0u2tbpkr)|[GTF](https://wustl.box.com/s/qi6ih72ebhswtnvazbhv082az3a69vau)|[Links](https://wustl.box.com/s/t1ibe0tvbefeas5pom1lrzmwe46lfjiy)|
| CC049 | RI| [FASTA](https://wustl.box.com/s/fbhta7do8hr0b4au33r1o9gt8y8fzhxt)|[GTF](https://wustl.box.com/s/xqjne9azrb6udq98f4068iuiu95pxgkd)|[Links](https://wustl.box.com/s/ewb30i870zawddmpdj08jo59e64ykuyy)|
| CC050 | RI| [FASTA](https://wustl.box.com/s/0qwcj9mkt6602d85x7vy2kkag90xta82)|[GTF](https://wustl.box.com/s/1pgz6xnskab9pdhq1b5prw8c96bs0qmd)|[Links](https://wustl.box.com/s/y2k1rlm8h9qlo3x45n014xw6cu6hvs5s)|
| CC051 | RI| [FASTA](https://wustl.box.com/s/lz6yvskixr1sakxg7s4et9rsx1nny14z)|[GTF](https://wustl.box.com/s/v0x9nizgsygwhw3ssmakyiv839yog3k8)|[Links](https://wustl.box.com/s/4xzwt4l93kn25vtpozbxoca5c95t6g0l)|
| CC052 | RI| [FASTA](https://wustl.box.com/s/g0n0caawq27str6e8203445qs7fe85jd)|[GTF](https://wustl.box.com/s/evu0blsdvk6lwvzryiwr48eo12sryb75)|[Links](https://wustl.box.com/s/vmo6sn5xr8z2amg8gxmwwqa8oehjh54f)|
| CC053 | RI| [FASTA](https://wustl.box.com/s/w96lee6eez6mag3c760ypdusq39ogiz5)|[GTF](https://wustl.box.com/s/z11u5qdqyrfwpecnqprcju7zzljpwwrp)|[Links](https://wustl.box.com/s/83zyvd9yzzjtuhil92w636melhnvfkll)|
| CC055 | RI| [FASTA](https://wustl.box.com/s/chxx9jleoa7o31qng8jkbckmhuqi68mj)|[GTF](https://wustl.box.com/s/60439ryttpjac1m18j02dtacwp0tpo0b)|[Links](https://wustl.box.com/s/w8t2ofjescntrhyroa426ozpl38wrnun)|
| CC056 | RI| [FASTA](https://wustl.box.com/s/sfs9sb62mjua2vxox6mowrpwqo61k8ov)|[GTF](https://wustl.box.com/s/zeu6766agkre72r99pojvew1il3216xy)|[Links](https://wustl.box.com/s/t18983r2kzhbf8cytvrbokbvn4gdekoy)|
| CC057 | RI| [FASTA](https://wustl.box.com/s/cf5ynv5y2zo6kvtb9d87q5kucqtkste1)|[GTF](https://wustl.box.com/s/0anwpupbwetyviu992asiwltcbvldef0)|[Links](https://wustl.box.com/s/mb835apktvr3am33xt8pqrhdhn8sgn6l)|
| CC058 | RI| [FASTA](https://wustl.box.com/s/g2jjoqodqshn90rkwpf9rzyiwtm3d0gm)|[GTF](https://wustl.box.com/s/dg0ryznvzhurluxvicz1y1xbim8917c7)|[Links](https://wustl.box.com/s/d5qo3hckkrf7vndu7fr9uwon5zs3a66g)|
| CC059 | RI| [FASTA](https://wustl.box.com/s/wrzbisnal0zs9vdn37kh2evf5dw32w9p)|[GTF](https://wustl.box.com/s/wykf7lzw95ko2gidmj87lmnxb8ed072f)|[Links](https://wustl.box.com/s/0miuofrz18a0uirntl800erutm3wbzkd)|
| CC060 | RI| [FASTA](https://wustl.box.com/s/wtzgugmc0a1irp5mu4xfddq2df1x3zu7)|[GTF](https://wustl.box.com/s/e4imggp0cfqn26horumdypkupfiunqz6)|[Links](https://wustl.box.com/s/yb33cj4hg895rhz930tv265hd49caycd)|
| CC061 | RI| [FASTA](https://wustl.box.com/s/p67yel5bjvv851ylujw3v6ddm5xbfhpj)|[GTF](https://wustl.box.com/s/u7fitpjcp13es9tsybwctyutmwz0gmzg)|[Links](https://wustl.box.com/s/8jy70thegkl18161294mxn2i7g7rbxl6)|
| CC062 | RI| [FASTA](https://wustl.box.com/s/zbnwmhsgcxwg25stizr4ippj91lrify7)|[GTF](https://wustl.box.com/s/jbzmex99the3mzet8egzgos5tlemhecw)|[Links](https://wustl.box.com/s/ystoukndakl8znjaiwb8x0y2h5xxizd7)|
| CC063 | RI| [FASTA](https://wustl.box.com/s/5kcq3jdlzq01sd6y0dhmv3a5ykbttbo1)|[GTF](https://wustl.box.com/s/77a35x2ll7huz5t6jlozdj15ml1fbmgk)|[Links](https://wustl.box.com/s/nbob9jb1gslw68uqm7je38rqzyq3l0sj)|
| CC065 | RI| [FASTA](https://wustl.box.com/s/jydl0b147vwc2om5z2km56zc6oqxhoxl)|[GTF](https://wustl.box.com/s/86f1kt27ka7irzh9j0agknlfj37p83u0)|[Links](https://wustl.box.com/s/atsxhyvy246t5k1a0ud05m0jjlhg33oh)|
| CC068 | RI| [FASTA](https://wustl.box.com/s/4unjg2ofnnz0ahffwiljwupg6d8ksf0l)|[GTF](https://wustl.box.com/s/240lk531p2b9uvv5d52nquzearw29f24)|[Links](https://wustl.box.com/s/7adroqez3xodtrgxcfrlrvoe7phbjhl3)|
| CC070 | RI| [FASTA](https://wustl.box.com/s/teiiafktcyocffhl65vtypq1u8vbzpjf)|[GTF](https://wustl.box.com/s/21w7qmo27lps8rhnr7s28o98nuqee3k2)|[Links](https://wustl.box.com/s/zxob83y3hn1itf5b5bhbw3gtfe1inzqv)|
| CC071 | RI| [FASTA](https://wustl.box.com/s/xzcn7cyk0v81e02bxrohgkv2vf6wvek5)|[GTF](https://wustl.box.com/s/4qpc2338wfmph0jbj9noyyykto2vxs4s)|[Links](https://wustl.box.com/s/vtpec4nw9gcjpkvqjo88q5uwsavsnwvz)|
| CC072 | RI| [FASTA](https://wustl.box.com/s/jsn0piyz7lpb2jqn96wynrj6pbi7gvjx)|[GTF](https://wustl.box.com/s/40l66arm82gr90bu7gq1ybg6yboeacsh)|[Links](https://wustl.box.com/s/6rymb1vrvg0crw403fxvff5k0nr0h63g)|
| CC073 | RI| [FASTA](https://wustl.box.com/s/ce5xlazlijcsbydal2umbobxjxk4muib)|[GTF](https://wustl.box.com/s/cqabfv49b6gvrpe5movkdaap1ylk1hyx)|[Links](https://wustl.box.com/s/ki1g05xq2dzgda1vvd3wc084b46hkcvf)|
| CC074 | RI| [FASTA](https://wustl.box.com/s/621niri16f35m9rebuvwgfgmhonom1e2)|[GTF](https://wustl.box.com/s/zk07tnd094s405b7o26y6id8os5y7jku)|[Links](https://wustl.box.com/s/1bn0klzr5pl73m5x9lijkby2dosr2s4z)|
| CC075 | RI| [FASTA](https://wustl.box.com/s/352s8r9yxge3a5t1r96ghlszfpg3shy8)|[GTF](https://wustl.box.com/s/axtxmiswtz2gz341o9vacqcr21uiguy5)|[Links](https://wustl.box.com/s/4xzql5hhwnjjvqf5vjowei9e6a89zjt9)|
| CC076 | RI| [FASTA](https://wustl.box.com/s/hfiufa2wbgzr07c9pe00xrgdh8fa16ma)|[GTF](https://wustl.box.com/s/5g75im5lq4osn7hft3b438m4mn7eo1rq)|[Links](https://wustl.box.com/s/nayu3pdqeh5fw2svpevki7efb02q3vj7)|
| CC078 | RI| [FASTA](https://wustl.box.com/s/s5paq12jmwmudqbickxe86wz0nrq695w)|[GTF](https://wustl.box.com/s/075dswhhozud64o10pjl88lp3dm1q3yq)|[Links](https://wustl.box.com/s/m8uf1opzrle26fmr51zil02z0shjsao0)|
| CC079 | RI| [FASTA](https://wustl.box.com/s/ij5j5pw5b9eufpow57ru1ds0toq59qtp)|[GTF](https://wustl.box.com/s/dz0ymjk2qh13e98cncsv06augutt9iou)|[Links](https://wustl.box.com/s/v3ddrz8p317gk3pqd2mdg3i9c6p2wqqq)|
| CC080 | RI| [FASTA](https://wustl.box.com/s/k2ebewhnx6e8d5a29j9wyhkzmx9l04se)|[GTF](https://wustl.box.com/s/5l71e3yqzejq10zpoeq0z1r88q1kq6t1)|[Links](https://wustl.box.com/s/byi4rk4eshttl3fyok56sahvo0bn5g4y)|
| CC081 | RI| [FASTA](https://wustl.box.com/s/4gmkhqjeakejcrk6101txz1qtn2c6uv9)|[GTF](https://wustl.box.com/s/ur0bnp1qxnf15caprbgvozo96qxu60dc)|[Links](https://wustl.box.com/s/045ec0334n3qn1vjqc2pysn9pf8ux2fg)|
| CC082 | RI| [FASTA](https://wustl.box.com/s/ngjfksb6601e1d5wormdbx7u5temnz4t)|[GTF](https://wustl.box.com/s/fyg15t3answj2h9ldxgf37a400yx296a)|[Links](https://wustl.box.com/s/imov16s6080o35lxsjdyhfsqhn313rlz)|
| CC083 | RI| [FASTA](https://wustl.box.com/s/thqtz9zc6yhn1bbw1fpzy9at3fix2v5c)|[GTF](https://wustl.box.com/s/s4bnprqa3r8b919yjeedovc0r3gof1jc)|[Links](https://wustl.box.com/s/8r5fm7diupqh29ls6hhboj2m1hpvjgnt)|

#### Other Strains
|Species  | Strain   |Graph group| Accession|Assembly Name|Genome|Annotations|Other data|
| --- |--- | --- | --- | --- | --- |--- |--- |
| Mus musculus domesticus | AKR_J|Others | GCA_001624295.1|AKR_J_v1 |[FASTA](https://wustl.box.com/s/u94tjri2eamzutfe7s0fsalups4omclu)|[GTF](https://wustl.box.com/s/5fafwqz46hy6nnmu1u2aza97pgb18n5h)|[Links](https://wustl.box.com/s/99bnhpnvih8p6n0l863fqu035g6pm24c)|
| Mus musculus domesticus | BALB_cJ|Others | GCA_001632525.1|BALB_cJ_v1 |[FASTA](https://wustl.box.com/s/vj9xg4l572u5zdu17l8v4i674pfq35ch)|[GTF](https://wustl.box.com/s/bi40jxli7z2ho3qb3d9j0coikxvrw2dh)|[Links](https://wustl.box.com/s/ou3z1bsyiy8fv6mmciufyltcekqt3zxk)|
| Mus musculus domesticus| C3H_HeJ|Others | GCA_001632575.1|C3H_HeJ_v1 | [FASTA](https://wustl.box.com/s/j0gwujaw8jdqfsyk30gnafrm9ijmras3)|[GTF](https://wustl.box.com/s/z4dnos2d3ayhvh5vh619gupfvhdq7syd)|[Links](https://wustl.box.com/s/qgny8bf6p1gfah6jgokmlqp38beitp9z)|
| Mus musculus domesticus | **C57BL_6_T2T**|Others| ||[FASTA](https://wustl.box.com/s/4idif3qkrv7v19pn1plmr129ctehp8tc)|[GTF](https://wustl.box.com/s/fv8i21h3uldljuplepoyw095bu0615or)|[Links](https://wustl.box.com/s/5z85wgcl4mh2bzyzilw8hx1kuau1iplk)|
| Mus musculus domesticus | C57BL_6NJ|Others| GCA_001632555.1|C57BL_6NJ_v1 |[FASTA](https://wustl.box.com/s/kvu3dk9booxwc8767zstygqsqivo47vw)|[GTF](https://wustl.box.com/s/9ftxssrfumasxnusp4srcun1xqivw3je)|[Links](https://wustl.box.com/s/62qoujpho0b78i0s72svgk9i3qyo1z8g)|
| Mus musculus  | CBA_J|Others| GCA_001624475.1|CBA_J_v1 |[FASTA](https://wustl.box.com/s/97v42w36hb7frrjb0wgjie6shf2hu315)|[GTF](https://wustl.box.com/s/hs97qifvwff3zihol8u4j11xshb4zax8)|[Links](https://wustl.box.com/s/u82qhme9ddgwdsyffe858un1h1o5lcjo)|
| Mus musculus domesticus | DBA_2J|Others| GCA_001624505.1|DBA_2J_v1 |[FASTA](https://wustl.box.com/s/55fcw0k1mtrkjz2h0jua8b75kqc6h8cx)|[GTF](https://wustl.box.com/s/zxbhj4gt1zhpicpkmaxfa4qumdh1ygcw)|[Links](https://wustl.box.com/s/2yvsfl09faa8wpfr89spuf9sqokbzo1o)|
| Mus musculus  | FVB_NJ|Others| GCA_001624535.1|FVB_NJ_v1 |[FASTA](https://wustl.box.com/s/aqzsj5thwlwrvlptvxrq5k3u590gsxs6)|[GTF](https://wustl.box.com/s/0ehe137q5pwj282nlcazk8dqfzud1c3c)|[Links](https://wustl.box.com/s/jm5m11188w2490ilpx5apyn5lft81m9h)|
| Mus musculus domesticus | LG_J|Others| | |[FASTA](https://wustl.box.com/s/pywsyez6o3goi6las2ss66xmj4cqy40b)|[GTF](https://wustl.box.com/s/f61pqe51j4fe9ubmdchizvdpt480262n)|[Links](https://wustl.box.com/s/tjiqdrzjpa0557mos4ghjdx2px9hgjmj)|
| Mus musculus domesticus | LP_J|Others|GCA_001632615.1|LP_J_v1 |[FASTA](https://wustl.box.com/s/cuk47i5c17ie78cbdnd559nhkqv69u6d)|[GTF](https://wustl.box.com/s/i7ogq354z7d86edxyq73qswevcnctzh1)|[Links](https://wustl.box.com/s/gerpzft07h4nt7kf8kb38jjrnsv7cytm)|
| | SM_J|Others|| |[FASTA](https://wustl.box.com/s/zq2ykv6uxs3pymzftdg9l1w2m1d351sc)|[GTF](https://wustl.box.com/s/df1u87dchc91obxxd66eqv1dvlg7yfmf)|[Links](https://wustl.box.com/s/kj2fyh32pbar5zz6vbopdzf1t00jctco)|

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
|JJ011|[FASTQ](https://wustl.box.com/s/r4sjugfswr0yz08dyqapjpng168q25qg)|
|JJ012|[FASTQ](https://wustl.box.com/s/12t0wddzk820kw2pe8ggpgqprbld8slf)|
