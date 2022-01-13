# Sequencing101


Tres bon argumentairer pour l'usage de la genomique en matiere de plante. C'est un article de KeyGene dans le [blog nanopore](https://nanoporetech.com/about-us/news/blog-keygene-next-level-crop-reference-genomes-using-plant-trained-basecallers-and)

> Genome sequencing has become an indispensable tool in plant breeding research, through which genetic variation of individual varieties at nucleotide precision can be revealed. Plant breeding companies use reference genomes to:

  - effectively develop trait-linked markers and discover genes
  - perform comparative genomics to elucidate breeding history
  - dissect the genetic architecture of important traits and link them to haplotypes
  - expand trait discovery approaches beyond SNP-based analysis

The insights obtained using a reference genome enable better and faster selection of important breeding trait values in the breeding process and therefore allow to bring new varieties to the market faster.


Ils ont mis aussi les 4C avec le 4eme C comme etant le cout in contrast avec le computing de PacBio. Tres fun!

Correctness, Completeness, Contiguity and Cost, (also dubbed as the 4C’s) are of main importance with regard to generating reference genomes. High contiguity (i.e. Telomere-to-Telomere) and completeness can already be obtained by isolating High Molecular Weight (HMW) genomic DNA, in combination with (ultra) long Oxford Nanopore sequencing.


Ce qui m'a le plus impressionner c'est le processus de assembly and annotation en une semaine


very impressive


![img]()



Price Nanopore



![img](https://github.com/Yedomon/Sequencing101/blob/main/price_nano.PNG)


https://github.com/sirselim/jetson_nanopore_sequencing



[Oxford Nanopore Technology: revolutionizing genomics research in plants](https://www.sciencedirect.com/science/article/abs/pii/S1360138521003101)

![img](https://github.com/Yedomon/Sequencing101/blob/main/nanopore.jfif)


Application 


![img](https://github.com/Yedomon/Sequencing101/blob/main/nanopore.jfif)







[Unleashing the Power of HiFi Sequencing - How the Sequel IIe System Empowers Life Scientists](https://youtu.be/XjK8HIOQbho)


![omage](https://github.com/Yedomon/Sequencing101/blob/main/accuracy.png?raw=true)


Computing env



![d](https://github.com/Yedomon/Sequencing101/blob/main/computing%20requirement.png?raw=true)



- #### [SENCKENBERG BIODIVERSITY GENOMICS SYMPOSIUM 21 April 2021](https://events.pacb.com/senckenberg-biodiversity/page/1723886/tutorials-and-resources)

- #### [Friday, February 12, 2021 | LeafGo: A Workflow That Enables High-Quality Seven-Day Plant Genome Assembly ](https://www.pacb.com/blog/leafgo-plant-genome-workflow/)

- #### [Wednesday, March 25, 2020 | The Evolution of DNA Sequencing Tools](https://www.pacb.com/blog/the-evolution-of-dna-sequencing-tools/)

- #### [Tuesday, July 7, 2020 | From DNA to Discovery – The Steps of SMRT Sequencing](https://www.pacb.com/blog/steps-of-smrt-sequencing/)

- #### [Thursday, May 21, 2020 | Understanding Accuracy in DNA Sequencing](https://www.pacb.com/blog/understanding-accuracy-in-dna-sequencing/)

- #### [The Most Wonderful Webinars of the Year](https://www.pacb.com/blog/2020-webinars-of-the-year/)

- #### [Thursday, December 10, 2020 | Sequencing 101: Ploidy, Haplotypes, and Phasing – How to Get More from Your Sequencing Data](https://www.pacb.com/blog/ploidy-haplotypes-and-phasing/)

- #### [Wednesday, November 25, 2020 | Better Apple Pies: HiFi Reads are a Perfect Recipe for High-Quality Apple Genome and Pangenome Assemblies ](https://www.pacb.com/blog/apple-pangenome/)

- #### [Thursday, October 1, 2020 | Webinar: Crops and Corvids get the Pangenome Treatment with HiFi Sequencing](https://www.pacb.com/blog/crops-and-corvids-pangenome/)


- #### [Haplotype-resolved de novo assembly using phased assembly graphs with hifiasm](https://www.nature.com/articles/s41592-020-01056-5)



- PacBio webinar February 6 2021: Lessons from Assembling High-Quality Reference Genomes for Domesticated & Endangered Ruminants | [Video](https://youtu.be/RK0xDefnqB4)


[Scaffolding explanation](https://youtu.be/RK0xDefnqB4?t=643)

> Contigs assembly alone is not enough in this case and we still need scaffolding of the contigs. We use Hi-C for long-range scaffolding and the Bionano optical map for short range scafolding. I will not go in the details here but basically Optical map is crucial for resolving some of the wrong chimeric contigs and it is also very good in ordering and orientating the scaffolds. Hi-C is very good to join contigs to give chromosome size scaffold



[Video at this moment](https://youtu.be/RK0xDefnqB4?t=723) checking the final assembly by comparing gap and repeat content using ggplot2 graph


![Quality of assemblies](https://github.com/Yedomon/Sequencing101/blob/main/qualityasssembly.png?raw=true)

Can use this graph to compare sesamum indicum assemblies from china pangenome for the PhD.



The comparision of chromosome to a high quality reference genome is another way to check and compare genome assemblies. May use this plot to compare Goenbaek and Zhonzhi13 chromosomal scale assemblies in the phD document also


![quality of assemblies 2](https://github.com/Yedomon/Sequencing101/blob/main/qualityasssembly1.png?raw=true)





Just randomly get such an inspiring graph from [here](https://www.frontiersin.org/articles/10.3389/fmicb.2018.00660/full) showing comparative of pathogen genomes. Can be applied to my fungal genome project case.

![Graph0](https://www.frontiersin.org/files/Articles/308142/fmicb-09-00660-HTML/image_m/fmicb-09-00660-g001.jpg)




- PacBio webinar February 6 2021: Comparative Genomic Analysis in Sorghum Highlights the Extent of Structural Variations | [Video](https://youtu.be/maOj1iQf4ys)



- [Elucidating origins of grapevine agronomic traits with PacBio genome assembly and Iso-Seq analysis](https://youtu.be/IEghDVo6WKo)




- [Improved Phased Assembly using HiFi data](https://youtu.be/HHLJfTByNts)



![hifi_assemblers](https://github.com/Yedomon/Sequencing101/blob/main/Hifi_1.PNG?raw=true)



## Hifi_assemblers


- ##### [01. IPA HiFi Genome Assembler](https://github.com/PacificBiosciences/pbipa)
- ##### [02. Hifiasm](https://github.com/chhylp123/hifiasm#:~:text=Hifiasm%20is%20a%20fast%20haplotype,competitive%20with%20the%20best%20assemblers.)
- ##### [03. Peregrine](https://github.com/cschin/Peregrine)
- ##### [04. Hi-CANU](https://github.com/marbl/canu)
- ##### [05. Flye](https://github.com/fenderglass/Flye)



## Hifi free datasets

![Hifi](https://github.com/Yedomon/Sequencing101/blob/main/public_hifi_data.PNG?raw=true)



PacBio Day | [Workshop: Whole Genome Sequencing for De Novo Assembly of Any Organism](https://events.pacb.com/pagbio-day/agenda/session/442213)


![benef](https://github.com/Yedomon/Sequencing101/blob/main/benef.PNG?raw=true)


![seq](https://github.com/Yedomon/Sequencing101/blob/main/Sequencing_pipeline.PNG?raw=true)



[Assembly and Validation of Two Gap-free Reference Genomes for Xian/indica Rice Reveals Insights into Plant Centromere Architecture](https://www.biorxiv.org/content/10.1101/2020.12.24.424073v2.full.pdf)


![examplegraphformythesis](https://github.com/Yedomon/Sequencing101/blob/main/graph_1.PNG?raw=true)








