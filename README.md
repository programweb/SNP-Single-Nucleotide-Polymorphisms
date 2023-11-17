# Single-Nucleotide-Polymorphisms (SNP)

A single nucleotide polymorphism (abbreviated SNP, pronounced snip; plural snips) is a DNA sequence variation occurring commonly within a population (e.g. 1%) in which a single nucleotide in the DNA - A, T, C or G of a shared sequence differs between members of a biological species (or paired chromosome of the same individual).  Scientists study if/how SNPs in a genome influence health, disease, drug response and other traits or phenotypic expressions.


The National Library of Medicine hosts the dbSNP.  dbSNP contains human single nucleotide variations, microsatellites, and small-scale insertions and deletions along with publication, population frequency, molecular consequence, and genomic and RefSeq mapping information for both common variations and clinical mutations.

It is possible to use the Entrez Programming Utilities (E-utilities) to query the National Center for Biotechnology Information (NCBI) dbSNP database.  EDirect is a set of UNIX programs that bring the functionality of E-utilities to the command line. Once installed, EDirect can facilitate the construction of powerful queries and extraction pipelines with minimal coding.
   1) we can run a query
   2) we can pipe that query XML output to efetch:

![aaa](https://github.com/programweb/Single-Nucleotide-Polymorphisms-SNP-/assets/12736699/3c37a69b-9583-480b-856a-18d98fbe8b22)

There are a plethora of single nucleotide polymorphism related tools 
&nbsp;

**Discovery tools**: find SNPs eg of recessive genes for certain phenotypes
&nbsp;

**Annotation tools**: These tools annotate SNPs with information such as gene annotation, functional annotation, and conservation scores.
&nbsp;

**Quality control tools**: These tools perform quality control checks on SNP data, such as removing SNPs with low call rates or high missingness.
&nbsp;

**Association analysis tools**: These tools are used to test for associations between SNPs and phenotypes. 
&nbsp;

**Imputation tools**: These tools are used to impute missing genotypes in SNP data.
&nbsp;

**Visualization tools**: These tools are used to visualize SNP data.
&nbsp;

-----------------------------------------------------------
&nbsp;

**Map SNPs to Genes & Chromosome Loci**
(aka: SNP identifier mapping)
&nbsp;

The tool g:SNPense maps human single nucleotide polymorphisms (SNP) to gene names, chromosomal locations and variant consequence terms from Sequence Ontology.
With the rapid growth of whole genome sequencing technology, researchers are uncovering extensive genetic variation and large collections of known SNPs are available for human and other species. In order to easily map SNP identifiers (e.g. rs4244285) to gene names, chromosomal coordinates and retrieve their functional consequences we now provide a new service called g:SNPense. Information about genome variants is retrieved from dbSNP and mapped to NCBI Genes. Potential functional consequences of the variants are retrieved from Ensembl Variation data and grouped into 35 Sequence Ontology terms of various severity.
&nbsp;

Here is an example with: rs4244285

![bbb](https://github.com/programweb/Single-Nucleotide-Polymorphisms-SNP-/assets/12736699/fd4bc6a6-f8bb-496b-b375-4ee991eb0828)
![ccc](https://github.com/programweb/Single-Nucleotide-Polymorphisms-SNP-/assets/12736699/a3f63559-bceb-4bb2-8414-d694dadb85bc)

