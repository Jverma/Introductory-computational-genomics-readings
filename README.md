## Diving into bioinformatics : Introductory studies for a mathematician/statistician or a computer scientist


I'm a quantitative researcher in the [Buckler Lab at Cornell University](http://www.maizegenetics.net/), specializing in computational genomics. I apply bioinformatics and data mining techniques to understand crop genomics. 

My background is in mathematics and theoretical physics. Prior to joining Buckler lab, I had zero knowledge of bioinformatics and genomics. In past year and half, I have read a bunch of papers, bugged my coworkers, spammed forums to get an idea of basic concepts. 

As a first step in disseminating my learnings, I decided** to make a list of some papers that I read in first 6 months of my job. I believe this will help someone with a background in mathematics/statistics/CS to begin in bioinformatics and computational genomics. These still require some knowledge of basic genomic terminology which took me a couple months to get to. 

Most of these papers assume familiarity with statistics, linear algebra, computer science fundamentals and knowledge of basic genomics lingo. Some papers also require basic knowledge in data mining and machine learning. 


# **Sequencing**

**Next Gen Sequencing (NGS)** : Jay Shendure, Hanlee Ji (2008) [Next-generation DNA sequencing](http://www.nature.com/nbt/journal/v26/n10/full/nbt1486.html) *Nature Biotechnology* 26, 1135-1145 (2008)

# **Alignment**
- **BLAST** [Basic Local Alignment Search Tool](http://blast.ncbi.nlm.nih.gov/Blast.cgi)
- **BowTie**: Ben Langmead, Cole Trapnell, Mihai Pop, Steven Salzberg. (2009) [Ultrafast and memory-efficient alignment of short DNA sequences to the human genome](http://genomebiology.com/2009/10/3/R25) *Genome Biology* 2009, 10:R25
- BWA: Li H. and Durbin R. (2009) [Fast and accurate short read alignment with Burrows-Wheeler transform](http://www.ncbi.nlm.nih.gov/pubmed/19451168) *Bioinformatics*, 25, 1754-1760.
- BWA-MEM: Li H. (2013) [Aligning sequence reads, clone sequences and assembly contigs with BWA-MEM](http://arxiv.org/abs/1303.3997)  

# **Assembly**
- **de Bruijn graphs:** Phillip E C Compeau, Pavel A Pavzner, Glenn Tesler (2011). [How to apply de Bruijn graphs to genome assembly](http://www.nature.com/nbt/journal/v29/n11/full/nbt.2023.html) *Nature Biotechnology* 29, 987-991(2011).
- **de Bruijn Assembly:** Pavel Pevzner, Haixu Tang, Michael Waterman (2001) [An Eulerian path approach to DNA fragment assembly](http://ai.stanford.edu/~serafim/cs262/Papers/Euler.pdf) *PNAS* 98, 9748-9753
- **Velvet:** D.R. Zerbino and E. Birner (2008) [Velvet: algorithms for de novo short read assembly using de Bruijn graphs](http://genome.cshlp.org/content/18/5/821.short) *Genome Research* 18:821-829
- **Evaluation:** Keith Bradnam et al (2013) [Assemblathon 2: evaluating de novo methods of genome assembly in three vertebrate species](http://www.gigasciencejournal.com/content/2/1/10) *GigaScience* 2:10 (2013)

#  **SNP calling**
- **GATK 1:** McKenna A et al (2010) [The Genome Analysis Toolkit : A MapReduce framework for analyzing next-generation DNA sequencing data](http://genome.cshlp.org/content/20/9/1297) *Genome Research* 20:1297-1303
- **GATK 2:** DePristo M et al (2011) [A framework for variation and genotyping using next-generation DNA sequencing data](http://www.nature.com/ng/journal/v43/n5/full/ng.806.html) *Nature Genetics* 43:491-498
- **FreeBayes:** [Haplotype-based variant detection from short-read sequencing](http://arxiv.org/abs/1207.3907)


#  Hidden Markov Models: 
Byubg-Jun Yoon (2008) [Hidden Markov models and their applications in biological sequence analysis](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC2766791/pdf/CG-10-402.pdf)


#  Genome Wide Association Studies (GWAS) 
- David J. Balding (2006) [A tutorial on statistical methods for population association studies](http://www.nature.com/nrg/journal/v7/n10/full/nrg1916.html) *Nature Reviews Genetics* 7, 781-791.
- Witte J.S. (2010) [Genome-wide association studies and beyond](http://www.ncbi.nlm.nih.gov/pubmed/20235850) *Annual Rev Public Health* 2010;31:9-20
- Thomas A. Peason [How to Interpret a Genome-wide Association Study](http://jama.jamanetwork.com/article.aspx?articleid=181647) *JAMA* 2008;299(11):1335-1344


#  Principle Component Analysis in GWAS
- Alkes Price et al (2006) [Principal components analysis corrects for stratification in genome-wide association studies](http://www.nature.com/ng/journal/v38/n8/abs/ng1847.html) *Nature Genetics* 38, 904-909

# File formats
- [FASTA format](https://en.wikipedia.org/wiki/FASTA_format)
- [FASTQ format](https://en.wikipedia.org/wiki/FASTQ_format)
- [GFF](http://www.sanger.ac.uk/resources/software/)
- [GFF3](http://gmod.org/wiki/GFF3)
- [VCF](http://samtools.github.io/hts-specs/VCFv4.1.pdf)
- [SAM/BAM](http://samtools.github.io/hts-specs/SAMv1.pdf)

** - It was a task assigned to me by my adviser. 
