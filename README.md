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
|  Graph| [GFA](https://wustl.box.com/s/4hefdyjgpaqww4ph49qgr0ke0ji9mj22) [GBZ](https://wustl.box.com/s/2fqgbyy6eudrft42ra6xsq4aysutsyyx)| [GFA](https://wustl.box.com/s/y6cgmgzoq3ezuwukb4vi8vaoatx5gi6d) [GBZ](https://wustl.box.com/s/qt8olly50uor56rshla21r4w24elkju3)|  [GFA](https://wustl.box.com/s/tbm4aol3c8xjh2g9faxnfcialw80fuwz)|  [GFA](https://wustl.box.com/s/algtmrme867ywvqhdz1iyorgyz4kktil) [GBZ](https://wustl.box.com/s/algtmrme867ywvqhdz1iyorgyz4kktil)|  
|  Full (Unclipped) Graph |  [GFA](https://wustl.box.com/s/5p47tv8m3e2ivck4r336iy4811h5dgby) [GBZ](https://wustl.box.com/s/dow1idkt2i47xez9mwsq0i4icj4v4z8r)| [GFA](https://wustl.box.com/s/ww65iar07qva7t6stgb8zshkel0yiz2u) [GBZ](https://wustl.box.com/s/syn8etjf7o3wbf22lc6ix568rwpckuzq)| [VCF](https://wustl.box.com/s/tbm4aol3c8xjh2g9faxnfcialw80fuwz)| [GFA](https://wustl.box.com/s/algtmrme867ywvqhdz1iyorgyz4kktil) [GBZ](https://wustl.box.com/s/algtmrme867ywvqhdz1iyorgyz4kktil) | 
|  Decomposed VCF|  [VCF](https://wustl.box.com/s/giskmgths34lkolu8ke4si27ixshznve) | [VCF](https://wustl.box.com/s/yqaibvf2zsp00wpfyg76ofm7cw9c1z00)| [VCF](https://wustl.box.com/s/tbm4aol3c8xjh2g9faxnfcialw80fuwz)| [VCF](https://wustl.box.com/s/algtmrme867ywvqhdz1iyorgyz4kktil) |
|  Raw VCF|  [VCF](https://wustl.box.com/s/w41h6005qvdbvvkxx6inmheeb4mx9iv2) | [VCF](https://wustl.box.com/s/pwia2bfgwo0uqx6st7am4n8dzun49dme)| [VCF](https://wustl.box.com/s/tbm4aol3c8xjh2g9faxnfcialw80fuwz) |  [VCF](https://wustl.box.com/s/algtmrme867ywvqhdz1iyorgyz4kktil)| 
|  Multiple Alignment|  [HAL](https://wustl.box.com/s/e0vbeliuov4y9m2lz2o13y8hjgdp5s10)| [HAL](https://wustl.box.com/s/3q3jefm2hkf85gwpoy6bvd7x2znhxaig)| [HAL](https://pages.github.com/)| [HAL](https://wustl.box.com/s/algtmrme867ywvqhdz1iyorgyz4kktil) | 
| VG Indexes |  [gbz](https://wustl.box.com/s/v6x2igksd1ioaodr61hytn7g7kqrv838) [dist](https://wustl.box.com/s/v6x2igksd1ioaodr61hytn7g7kqrv838) [min](https://wustl.box.com/s/yb12cz2kzen3nbvrsk2qoqvpqqier24d)| [gbz](https://wustl.box.com/s/syn8etjf7o3wbf22lc6ix568rwpckuzq) [dist](https://wustl.box.com/s/oxnag0f4330lgpt7wynfy68t7n2z5bqb) [min](https://wustl.box.com/s/kz5hpler2f87ctyhrbzuk2ollpjngwta)| [gbz](https://wustl.box.com/s/tbm4aol3c8xjh2g9faxnfcialw80fuwz) [dist](https://wustl.box.com/s/tbm4aol3c8xjh2g9faxnfcialw80fuwz)  [min](https://wustl.box.com/s/tbm4aol3c8xjh2g9faxnfcialw80fuwz)|  [gbz](https://wustl.box.com/s/algtmrme867ywvqhdz1iyorgyz4kktil) [dist](https://wustl.box.com/s/algtmrme867ywvqhdz1iyorgyz4kktil) [min](https://wustl.box.com/s/algtmrme867ywvqhdz1iyorgyz4kktil) |
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
| Mus musculus domesticus |GRCm39 |References|GCA_000001635.9|GRCm39 |[FASTA](https://wustl.box.com/s/yxn1pxobbigfli6pnhlbph98h1d1a8v9)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | mm10|References| GCF_000001635.26|GRCm38.p6 |[FASTA](https://wustl.box.com/s/p65sjrxp7gqaa008fujp6hm2sv50gkxs)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | A_J|Founders | GCA_001624215.1|A_J_v1 |[FASTA](https://wustl.box.com/s/e1kuii99n8nubxrjoskty7aht8ajfcwa)|[GTF](https://wustl.box.com/s/o8xdc1rvg4he0dlcp9enxgvhirokpw06)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | 129S1_SvImJ|Founders | GCA_001624185.1|129S1_SvImJ_v1 |[FASTA](https://wustl.box.com/s/zshlgett36tc46dff81jgl6fiemqlhmc)|[GTF](https://wustl.box.com/s/sg7k4je6ddhyjmi726mh4tz0544hl04b)|[Links](https://pages.github.com/)|
| Mus musculus castaneus | CAST_EiJ|Founders | GCA_001624445.1|CAST_EiJ_v1 | [FASTA](https://wustl.box.com/s/k0qzcks18t2a9y7zy04ykhlz6esepkgr)|[GTF](https://wustl.box.com/s/5uo6f4r62cbppfmvkwwvdekiun4dv3mv)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | NOD_ShiLtJ|Founders| GCA_001624675.1|NOD_ShiLtJ_v1 |[FASTA](https://wustl.box.com/s/zycq4s6js4ngpvlhkufi2qec3d94mf3l)|[GTF](https://wustl.box.com/s/zjgftstm73hpvj94y0uombavs2js2vqj)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | NZO_HlLtJ|Founders| GCA_001624745.1|NZO_HlLtJ_v1 |[FASTA](https://wustl.box.com/s/m4yh1o7zw5lcfknih2wtxcujm2rznz9j)|[GTF](https://wustl.box.com/s/8xe0ur00iptkeeue365t1q9c0jx0luyw)|[Links](https://pages.github.com/)|
| Mus musculus musculus | PWK_PhJ|Founders| GCA_001624775.1|PWK_PhJ_v1 |[FASTA](https://wustl.box.com/s/3lxspogzff7q4gpiegvnbixtystxw5i9)|[GTF](https://wustl.box.com/s/6oh54rh0bzazz4kcpmhw95ggh18oyuy3)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | WSB_EiJ|Founders| GCA_001624835.1|WSB_EiJ_v1 |[FASTA](https://wustl.box.com/s/u6xmzscuqwydmphjmxxhfn01cmgwqk8k)|[GTF](https://wustl.box.com/s/g8iciw1pb6j13xhxbpmxhimmt0o0tsb5)|[Links](https://pages.github.com/)|
#### 75 RI lines
|  Strain   | Graph group| Genome|Annotations|Other data|
| --- | --- | --- | --- | --- |
| CC001 | RI| [FASTA](https://wustl.box.com/s/uy454353kqj852wztq8spjt7jm3l0yg5)|[GTF](https://wustl.box.com/s/fqqmvlcp3ejnxgij0ny61xge0iurqvb3)|[Links](https://pages.github.com/)|
| CC002 | RI| [FASTA](https://wustl.box.com/s/dvn5xjpmgdgkxcnpq6xa5cr09dcc0ffi)|[GTF](https://wustl.box.com/s/82depwkq7vgweo6iib0u3tndhklogx4i)|[Links](https://pages.github.com/)|
| CC003 | RI| [FASTA](https://wustl.box.com/s/mhy6f808l0gprtbjg4c204zvc77qvegk)|[GTF](https://wustl.box.com/s/e07k9jfql0dx62432mt8msic5gquqij3)|[Links](https://pages.github.com/)|
| CC004 | RI| [FASTA](https://wustl.box.com/s/d9nrgl8ssjsne8trnj1ykwan48eu6shm)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC005 | RI| [FASTA](https://wustl.box.com/s/7sqekhkqtcy3yzar3d7bg6uipk22530o)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC006 | RI|[FASTA](https://wustl.box.com/s/j1aeh4tqrcg4jvuca8xuq03husjo1bw5)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC007 | RI| [FASTA](https://wustl.box.com/s/f525vgkmseu09tuozuoa38ccv7kwxav8)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC008 | RI| [FASTA](https://wustl.box.com/s/ctqyiidzcb5m4mfs5ma0b1pn7u6gk5if)|[GTF](https://wustl.box.com/s/dlrfd4ljgiybe987m76s8y5w7ibanma9)|[Links](https://pages.github.com/)|
| CC009 | RI| [FASTA](https://wustl.box.com/s/3pgcv4pa2nz989lcgblt8hxcgljwagfn)|[GTF](https://wustl.box.com/s/hj911zwg1rm1pprnq21dtgxm5suze0v0)|[Links](https://pages.github.com/)|
| CC010 | RI| [FASTA](https://wustl.box.com/s/3z9ncw2orle8vr9s1x41q3ym61rxt0bo)|[GTF](https://wustl.box.com/s/hvyn4bc8ps5zdf1fv9lkhejkw17o2a8p)|[Links](https://pages.github.com/)|
| CC011 | RI| [FASTA](https://wustl.box.com/s/w9yfneozo51j9hsx1srf0bi3a94xmy17)|[GTF](https://wustl.box.com/s/3carwbv877vouj4hl9p4j2ool8eeqc6k)|[Links](https://pages.github.com/)|
| CC012 | RI| [FASTA](https://wustl.box.com/s/puivsvqd65hos4vcas9x2qly9n4s4s9r)|[GTF](https://wustl.box.com/s/sc22uk0uvw0156r02axk79ll002808a9)|[Links](https://pages.github.com/)|
| CC013 | RI| [FASTA](https://wustl.box.com/s/qob66de772nxfw7tnht0gk2feum9l9uf)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC015 | RI| [FASTA](https://wustl.box.com/s/3jvrvsbayjuessk5dbmrg25qxvspwbsa)|[GTF](https://wustl.box.com/s/rgv9v3sfi02ryhcaen8dr5w5c4w7bsr5)|[Links](https://pages.github.com/)|
| CC016 | RI| [FASTA](https://wustl.box.com/s/gei3fqy6njikhdjapr6tb6exg2baqtuf)|[GTF](https://wustl.box.com/s/zg61ogutaedi86lnkc3xzqo6uh504759)|[Links](https://pages.github.com/)|
| CC017 | RI| [FASTA](https://wustl.box.com/s/59lmliu74fpxpcd3j2cjfisaetuyrc4m)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC018 | RI| [FASTA](https://wustl.box.com/s/8lrq3ctan75dy68xf9ry3g54kqmrpi6f)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC019 | RI| [FASTA](https://wustl.box.com/s/un7mn93wqo63eo1pgxy5ov1zu0fdvfuo)|[GTF](https://wustl.box.com/s/v9p767p3i4lqqcvoisxprq3on10m8740)|[Links](https://pages.github.com/)|
| CC020 | RI| [FASTA](https://wustl.box.com/s/qhm5shmq601v73n5mdluw9eek6r0fj2t)|[GTF](https://wustl.box.com/s/4w8gzgbxpo5sq9li3fsrv02iwpr8im62)|[Links](https://pages.github.com/)|
| CC021 | RI| [FASTA](https://wustl.box.com/s/dai28jwp0sy2mde1745owqay89f3ty7y)|[GTF](https://wustl.box.com/s/knd70q7b8sjth5jivel3t8ya5htzybz5)|[Links](https://pages.github.com/)|
| CC022 | RI| [FASTA](https://wustl.box.com/s/tbcp6j6euz309eulux9i0ntwklg5grow)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC023 | RI| [FASTA](https://wustl.box.com/s/49mbj6ueiby25vl3i796q8vnfrderao5)|[GTF](https://wustl.box.com/s/31vwmpmr9lvigj7oft8jk979r078ugzq)|[Links](https://pages.github.com/)|
| CC024 | RI| [FASTA](https://wustl.box.com/s/as2yqmywg6yezmvfxlojoylj5bsfk42l)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC025 | RI| [FASTA](https://wustl.box.com/s/4740z6ezj9tx1p86wipf3c83b2y3q0gy)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC026 | RI| [FASTA](https://wustl.box.com/s/fzbyvtxhkub0txfefgjqr6nxcq6xrpju)|[GTF](https://wustl.box.com/s/1np97i2pk1lih4xboqotfu6hl13auijt)|[Links](https://pages.github.com/)|
| CC027 | RI| [FASTA](https://wustl.box.com/s/9sczg47616g26yzqlv9uvqkp4t8phiab)|[GTF](https://wustl.box.com/s/6l1wad0cmvgnveni17ttatbjikd61tcc)|[Links](https://pages.github.com/)|
| CC028 | RI| [FASTA](https://wustl.box.com/s/a2m76bktiodzh77z3su4nt039duuvyyj)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC029 | RI| [FASTA](https://wustl.box.com/s/cb1vzi0bit21v1n8uwx7opthbf7fg1bw)|[GTF](https://wustl.box.com/s/4oyvvdjsy2i8tkkn8uyn7z3qhaak6z1t)|[Links](https://pages.github.com/)|
| CC030 | RI| [FASTA](https://wustl.box.com/s/pyviel82yfznzupv1x6immkg4f704rmg)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC031 | RI| [FASTA](https://wustl.box.com/s/h5ng9vugkxm0jytrguvqu2m0pn6osba3)|[GTF](https://wustl.box.com/s/1zi1bfm0f3wyh7id4dz9nkj9lm78fsvr)|[Links](https://pages.github.com/)|
| CC032 | RI| [FASTA](https://wustl.box.com/s/akbu71tw1lyh0cb1otn7d6k4z0cntacs)|[GTF](https://wustl.box.com/s/owtf7kindznhdglhgukqe2t6arp93954)|[Links](https://pages.github.com/)|
| CC033 | RI| [FASTA](https://wustl.box.com/s/8jf636t6rriaymxpucjn7tm839sb020y)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC034 | RI| [FASTA](https://wustl.box.com/s/vsf0x18ofcro6ayca47uz4ip7zz0jnlj)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC035 | RI| [FASTA](https://wustl.box.com/s/4kznuirh3gh28rx7fid1kpnfmryrgzui)|[GTF](https://wustl.box.com/s/5cakzyhiklklsgfa6vswht690pd00kmo)|[Links](https://pages.github.com/)|
| CC036 | RI| [FASTA](https://wustl.box.com/s/omxuub32p4ffg0dg0h004l69pbmeal4o)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC037 | RI| [FASTA](https://wustl.box.com/s/gydkxb1u9d0ikpvhjzuqsdrsp8g9q71f)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC038 | RI| [FASTA](https://wustl.box.com/s/qi062zt94lie6eyygiqdnj2c11g8a523)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC039 | RI| [FASTA](https://wustl.box.com/s/m5p62uwz1ha0drbnfq9y4075oagp3w3r)|[GTF](https://wustl.box.com/s/e3p5l1tnhb04k2g3lazj80y1xea1kd91)|[Links](https://pages.github.com/)|
| CC040 | RI| [FASTA](https://wustl.box.com/s/acwk7tzpakipxxi48b7jmq5oamjeh8xb)|[GTF](https://wustl.box.com/s/7t5cw1durs7odyyjnv2v8hqaact9bhra)|[Links](https://pages.github.com/)|
| CC041 | RI| [FASTA](https://wustl.box.com/s/tfhd81a3p3q85kq38qmklrp2huyr8qar)|[GTF](https://wustl.box.com/s/aqshbvxqc001thyx68bsd7knb8xzpk3y)|[Links](https://pages.github.com/)|
| CC042 | RI| [FASTA](https://wustl.box.com/s/epxk0w01sge6yandbv8vpzjtrn9j7i54)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC043 | RI| [FASTA](https://wustl.box.com/s/o25hx0ulkpgcmanqg9c8sbvwvc38ol1h)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC044 | RI| [FASTA](https://wustl.box.com/s/rkg6a4fy9hctuak7y4iz6ws6hzs7irjt)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC045 | RI| [FASTA](https://wustl.box.com/s/lpj7t2bh960rdyfc6p4qvmmo285z3f8y)|[GTF](https://wustl.box.com/s/yr16ilt2xen70nlcj7th2uvini4pec4e)|[Links](https://pages.github.com/)|
| CC046 | RI| [FASTA](https://wustl.box.com/s/xah49ag6qiyxzig0jp7uzp2axqvr27oh)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC047 | RI| [FASTA](https://wustl.box.com/s/d9yyk10d7okfh1hacr5gmzyf0u2tbpkr)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC049 | RI| [FASTA](https://wustl.box.com/s/fbhta7do8hr0b4au33r1o9gt8y8fzhxt)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC050 | RI| [FASTA](https://wustl.box.com/s/0qwcj9mkt6602d85x7vy2kkag90xta82)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC051 | RI| [FASTA](https://wustl.box.com/s/lz6yvskixr1sakxg7s4et9rsx1nny14z)|[GTF](https://wustl.box.com/s/v0x9nizgsygwhw3ssmakyiv839yog3k8)|[Links](https://pages.github.com/)|
| CC052 | RI| [FASTA](https://wustl.box.com/s/g0n0caawq27str6e8203445qs7fe85jd)|[GTF](https://wustl.box.com/s/evu0blsdvk6lwvzryiwr48eo12sryb75)|[Links](https://pages.github.com/)|
| CC053 | RI| [FASTA](https://wustl.box.com/s/w96lee6eez6mag3c760ypdusq39ogiz5)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC055 | RI| [FASTA](https://wustl.box.com/s/chxx9jleoa7o31qng8jkbckmhuqi68mj)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC056 | RI| [FASTA](https://wustl.box.com/s/sfs9sb62mjua2vxox6mowrpwqo61k8ov)|[GTF](https://wustl.box.com/s/zeu6766agkre72r99pojvew1il3216xy)|[Links](https://pages.github.com/)|
| CC057 | RI| [FASTA](https://wustl.box.com/s/cf5ynv5y2zo6kvtb9d87q5kucqtkste1)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC058 | RI| [FASTA](https://wustl.box.com/s/g2jjoqodqshn90rkwpf9rzyiwtm3d0gm)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC059 | RI| [FASTA](https://wustl.box.com/s/wrzbisnal0zs9vdn37kh2evf5dw32w9p)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC060 | RI| [FASTA](https://wustl.box.com/s/wtzgugmc0a1irp5mu4xfddq2df1x3zu7)|[GTF](https://wustl.box.com/s/e4imggp0cfqn26horumdypkupfiunqz6)|[Links](https://pages.github.com/)|
| CC061 | RI| [FASTA](https://wustl.box.com/s/p67yel5bjvv851ylujw3v6ddm5xbfhpj)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC062 | RI| [FASTA](https://wustl.box.com/s/zbnwmhsgcxwg25stizr4ippj91lrify7)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC063 | RI| [FASTA](https://wustl.box.com/s/5kcq3jdlzq01sd6y0dhmv3a5ykbttbo1)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC065 | RI| [FASTA](https://wustl.box.com/s/jydl0b147vwc2om5z2km56zc6oqxhoxl)|[GTF](https://wustl.box.com/s/86f1kt27ka7irzh9j0agknlfj37p83u0)|[Links](https://pages.github.com/)|
| CC068 | RI| [FASTA](https://wustl.box.com/s/4unjg2ofnnz0ahffwiljwupg6d8ksf0l)|[GTF](https://wustl.box.com/s/240lk531p2b9uvv5d52nquzearw29f24)|[Links](https://pages.github.com/)|
| CC070 | RI| [FASTA](https://wustl.box.com/s/teiiafktcyocffhl65vtypq1u8vbzpjf)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC071 | RI| [FASTA](https://wustl.box.com/s/xzcn7cyk0v81e02bxrohgkv2vf6wvek5)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC072 | RI| [FASTA](https://wustl.box.com/s/jsn0piyz7lpb2jqn96wynrj6pbi7gvjx)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC073 | RI| [FASTA](https://wustl.box.com/s/ce5xlazlijcsbydal2umbobxjxk4muib)|[GTF](https://wustl.box.com/s/cqabfv49b6gvrpe5movkdaap1ylk1hyx)|[Links](https://pages.github.com/)|
| CC074 | RI| [FASTA](https://wustl.box.com/s/621niri16f35m9rebuvwgfgmhonom1e2)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC075 | RI| [FASTA](https://wustl.box.com/s/352s8r9yxge3a5t1r96ghlszfpg3shy8)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC076 | RI| [FASTA](https://wustl.box.com/s/hfiufa2wbgzr07c9pe00xrgdh8fa16ma)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC078 | RI| [FASTA](https://wustl.box.com/s/s5paq12jmwmudqbickxe86wz0nrq695w)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC079 | RI| [FASTA](https://wustl.box.com/s/ij5j5pw5b9eufpow57ru1ds0toq59qtp)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC080 | RI| [FASTA](https://wustl.box.com/s/k2ebewhnx6e8d5a29j9wyhkzmx9l04se)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC081 | RI| [FASTA](https://wustl.box.com/s/4gmkhqjeakejcrk6101txz1qtn2c6uv9)|[GTF](https://wustl.box.com/s/ur0bnp1qxnf15caprbgvozo96qxu60dc)|[Links](https://pages.github.com/)|
| CC082 | RI| [FASTA](https://wustl.box.com/s/ngjfksb6601e1d5wormdbx7u5temnz4t)|[GTF](https://pages.github.com/)|[Links](https://pages.github.com/)|
| CC083 | RI| [FASTA](https://wustl.box.com/s/thqtz9zc6yhn1bbw1fpzy9at3fix2v5c)|[GTF](https://wustl.box.com/s/s4bnprqa3r8b919yjeedovc0r3gof1jc)|[Links](https://pages.github.com/)|

#### Other Strains
|Species  | Strain   |Graph group| Accession|Assembly Name|Genome|Annotations|Gaps bed|
| --- |--- | --- | --- | --- | --- |--- |--- |
| Mus musculus domesticus | AKR_J|Others | GCA_001624295.1|AKR_J_v1 |[FASTA](https://wustl.box.com/s/u94tjri2eamzutfe7s0fsalups4omclu)|[GTF](https://wustl.box.com/s/5fafwqz46hy6nnmu1u2aza97pgb18n5h)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | BALB_cJ|Others | GCA_001632525.1|BALB_cJ_v1 |[FASTA](https://wustl.box.com/s/vj9xg4l572u5zdu17l8v4i674pfq35ch)|[GTF](https://wustl.box.com/s/bi40jxli7z2ho3qb3d9j0coikxvrw2dh)|[Links](https://pages.github.com/)|
| Mus musculus domesticus| C3H_HeJ|Others | GCA_001632575.1|C3H_HeJ_v1 | [FASTA](https://wustl.box.com/s/j0gwujaw8jdqfsyk30gnafrm9ijmras3)|[GTF](https://wustl.box.com/s/z4dnos2d3ayhvh5vh619gupfvhdq7syd)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | C57BL_6_T2T|Others| ||[FASTA](https://wustl.box.com/s/4idif3qkrv7v19pn1plmr129ctehp8tc)|[GTF](https://wustl.box.com/s/fv8i21h3uldljuplepoyw095bu0615or)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | C57BL_6NJ|Others| GCA_001632555.1|C57BL_6NJ_v1 |[FASTA](https://wustl.box.com/s/kvu3dk9booxwc8767zstygqsqivo47vw)|[GTF](https://wustl.box.com/s/9ftxssrfumasxnusp4srcun1xqivw3je)|[Links](https://pages.github.com/)|
| Mus musculus  | CBA_J|Others| GCA_001624475.1|CBA_J_v1 |[FASTA](https://wustl.box.com/s/97v42w36hb7frrjb0wgjie6shf2hu315)|[GTF](https://wustl.box.com/s/hs97qifvwff3zihol8u4j11xshb4zax8)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | DBA_2J|Others| GCA_001624505.1|DBA_2J_v1 |[FASTA](https://wustl.box.com/s/55fcw0k1mtrkjz2h0jua8b75kqc6h8cx)|[GTF](https://wustl.box.com/s/zxbhj4gt1zhpicpkmaxfa4qumdh1ygcw)|[Links](https://pages.github.com/)|
| Mus musculus  | FVB_NJ|Others| GCA_001624535.1|FVB_NJ_v1 |[FASTA](https://wustl.box.com/s/aqzsj5thwlwrvlptvxrq5k3u590gsxs6)|[GTF](https://wustl.box.com/s/0ehe137q5pwj282nlcazk8dqfzud1c3c)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | LG_J|Others| | |[FASTA](https://wustl.box.com/s/pywsyez6o3goi6las2ss66xmj4cqy40b)|[GTF](https://wustl.box.com/s/f61pqe51j4fe9ubmdchizvdpt480262n)|[Links](https://pages.github.com/)|
| Mus musculus domesticus | LP_J|Others|GCA_001632615.1|LP_J_v1 |[FASTA](https://wustl.box.com/s/cuk47i5c17ie78cbdnd559nhkqv69u6d)|[GTF](https://wustl.box.com/s/i7ogq354z7d86edxyq73qswevcnctzh1)|[Links](https://pages.github.com/)|
| | SM_J|Others|| |[FASTA](https://wustl.box.com/s/zq2ykv6uxs3pymzftdg9l1w2m1d351sc)|[GTF](https://wustl.box.com/s/df1u87dchc91obxxd66eqv1dvlg7yfmf)|[Links](https://pages.github.com/)|

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
