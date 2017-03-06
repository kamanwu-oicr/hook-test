---
title: "High-Throughput Biology: From Sequence to Networks (2017)"
date:   2017-01-25 02:23:33 -0500
author: Stephanie Lin
tags:
published: true
layout: workshop
# permalink:

########################################################################

condition:
  new: false
  disabled: false
  awards: false
  closed: false

image: "/assets/images/CBW-CSHL-graphic-square.png"

start_date: 2017-03-20 02:23:33 -0500

end_date: 2017-03-26 02:23:33 -0500

location_name: "Cold Spring Harbor Laboratory, NY"

faculty:
  title: "Lead Faculty"
  content:
    - "Jared Simpson"
    - "Florence Cavalli"
    - "Mathieu Bourgey"
    - "Malachi Griffith"
    - "Fouad Yousif"
    - "Obi Griffith"
    - "Jüri Reimand"
    - "Veronique Voisin"
    - "Robin Haw"
    - "Quaid Morris"
    - "Michael Hoffman"

fees:
  currency: US
  early_registration:
    price: 2855.00
    start_date: 2016-10-31 02:23:33 -0500
    end_date: 2017-01-15 02:23:33 -0500
  late_registration:
    price:
    start_date:
    end_date:
  limit: 30

poster:

course-outline:
  - title: "Module 3 - Genome Alignment (2017) (Instructor: Mathieu Bourgey)"
    outline:
      content:
        - "What is involved in mapping reads to a reference genome"
        - "What are the FASTQ and SAM/BAM file formats"
        - "Some common terminology used to describe alignments"
    lab_practical:
      title: "Lab Practical"
      content:
        - "Connecting to the Cloud"
        - "Genome alignment exercise"
    integ_assign:
      title: "Integrated Assignment"
      content:
        - "consolidate the skills you learned by performing an alignment."
    day: 1
    PPT: ""
    PDF: ""
    YouTube: ""
  - title: "Module 6 - De Novo Assembly (2017) (Instructor: Jared Simpson)"
    outline:
      content:
        - "Fundamentals of de novo assembly"
        - "Data structures used by assemblers (de Bruijn graphs and overlap graphs)"
        - "Common steps that assemblers perform"
    lab_practical:
      title: "Lab Practical"
      content:
        - "Perform a de novo assembly task."
    day: 2
    PPT: ""
    PDF: ""
    YouTube: ""
  - title: "Module 4 - Small-Variant Calling and Annotation (2017) (instructor: Mathieu Bourgey)"
    outline:
      content:
        - "SNPs, SNVs, and short-INDELs and why to look for them"
        - "BQ recalibration, duplicate removal, aligner choice"
        - "Detecting variants and factors taken into account by the SNP callers"
        - "Different types of SNP calling: haploid/diploid, trio, somatic mutations, pooled"
        - "Determining which SNPS are good from the millions detected"
        - "INDEL cleaning"
        - "Standard file formats for SNPs"
        - "Introduction to SNP calling tools and how they compare with each other"
    lab_practical:
      title: "Lab Practical"
      content:
        - "SNP detection exercise"
    day: 2
    PPT: ""
    PDF: ""
    YouTube: ""
  - title: "Module 5 - Structural Variant Calling (2017) (Instructor: Mathieu Bourgey)"
    outline:
      content:
        - "Structural variants (SVs), different types, mechanisms that give rise to SVs, and how SVs and CNVs differ"
        - "Differences between human and model organism genomes"
        - "Detecting SVs via sequencing (read pair, read depth, combined approach, local de novo assembly) and which SV types are detectable by which strategies"
        - "Introduction to SV detection tools"
        - "File formats used to describe SVs"
    lab_practical:
      title: "Lab Practical"
      content:
        - "SV discovery in a single human genome"
        - "Brief intro to SV visualization and interpretation"
    day: 2
    PPT: ""
    PDF: ""
    YouTube: ""
  - title: "Module 7 - Introduction to RNA Sequencing and Analysis (2017) (Instructor: Malachi Griffith)"
    outline:
      content:
        - "Basic introduction to biology of RNA-seq"
        - "Experimental design and analysis considerations"
        - "Commonly asked questions"
    lab_practical:
      title: "Lab Practical"
      content:
        - "Introduction to the test data"
        - "Examine and understand the format of raw FastQ files"
        - "Obtain reference genomes (fasta) and gene annotation resources (GTF/GFF)"
        - "Perform pre-alignment QC"
    day: 3
    PPT: ""
    PDF: ""
    YouTube: ""
  - title: "Module 8 - RNA-Seq alignment and visualization (2017) (Instructor: Fouad Yousif)"
    outline:
      content:
        - "Use of Bowtie/TopHat"
        - "Introduction to the BAM format"
        - "Basic manipulation of BAMs with samtools, Picard etc."
        - "Visualization of RNA-seq alignments - 'IGV'"
        - "BAM read counting and determination of variant allele expression status"
    lab_practical:
      title: "Lab Practical"
      content:
        - "Run Bowtie2/TopHat2 with parameters suitable for gene expression analysis"
        - "Use samtools to explore the features of the SAM/BAM format and perform basic manipulation of these alignment files (view, sort, index, manipulate headers, extract data, etc.)"
        - "Use IGV to visualize TopHat2 alignments, view a variant position, load exon junctions files, etc."
    day: 3
    PPT: ""
    PDF: ""
    YouTube: ""
  - title: "Module 9 - Expression and Differential Expression (2017) (Instructor: Obi Griffith)"
    outline:
      content:
        - "Get FPKM style expression estimates using Cufflinks"
        - "Perform differential expression analysis with Cuffdiff"
        - "Perform summary analysis with CummeRbund"
        - "Downstream interpretation of expression analysis (multiple testing, clustering, heatmaps, classification, pathway analysis, etc) will also be discussed."
    lab_practical:
      title: "Lab Practical"
      content:
        - "Run Cufflinks, Cuffdiff, and CummeRbund"
        - "Explore the output of these in R"
    day: 4
    PPT: ""
    PDF: ""
    YouTube: ""
  - title: "Module 10 - Reference free analysis (2017) (Instructor: Malachi Griffith)"
    outline:
      content:
        - "Explore the use of Kallisto to get abundance estimates without first aligning to a reference."
    day: 4
    PPT: ""
    PDF: ""
    YouTube: ""
  - title: "Module 11 - Isoform Discovery and Alternate Expression (2017) (Instructor: Malachi Griffith)"
    outline:
      content:
        - "Explore use of Cufflinks in reference annotation based transcript (RABT) assembly mode and 'de novo' assembly mode. Both modes require a reference genome sequence."
    lab_practical:
      title: "Lab Practical"
      content:
        - "Run Cufflinks in alternate modes more conducive to isoform discovery and explore the results"
    day: 4
    PPT: ""
    PDF: ""
    YouTube: ""
  - title: "Module 12 - Introduction to Pathway and Network Analysis (2017) (Instructor: Jüri Reimand)"
    outline:
      content:
        - "Where do gene lists come from and what are they useful for?"
        - "Pathway and network analysis overview"
        - "Presenting a workflow of concepts and tools from gene list to pathway analysis"
        - "Provide examples of multiple paths through the workflow that will be covered in the workshop"
        - "Sources of pathway and network information: GO biological process, network databases, pathway databases. Examples of pros and cons of each type of information"
        - "General issues: gene identifiers, data normalization"
    day: 5
    PPT: ""
    PDF: ""
    YouTube: ""
  - title: "Module 13 - Finding Over-represented Pathways in Gene Lists (2017) (Instructor: Jüri Reimand)"
    outline:
      content:
        - "Statistics for detecting over-representation e.g. hypergeometric test, GSEA"
        - "Multiple testing correction: Bonferroni, Benjamini-Hochberg FDR"
        - "Filtering Gene Ontology e.g. using evidence codes"
    lab_practical:
      title: "Lab Practical: Performing over-representation analysis"
      content:
        - "Workflow of tools and steps"
        - "g:Profiler tool for over-representation analysis"
        - "Gene Set Enrichment Analysis (GSEA) and Enrichment Maps software tool"
        - "Running gene enrichment tools on your gene list"
    day: 5
    PPT: ""
    PDF: ""
    YouTube: ""
  - title: "Module 14 - Network Visualization and Analysis with Cytoscape (2017) (Instructor: Veronique Voisin)"
    outline:
      content:
        - "Introduction to Cytoscape"
        - "Cytoscape demo"
    lab_practical:
      title: "Lab Practical: Tutorials on Cytoscape"
      content:
        - "Layouts"
        - "Labels"
        - "Enrichment maps"
    day: 5
    PPT: ""
    PDF: ""
    YouTube: ""
  - title: "Module 15 - More depth on Pathway and Network Analysis (2017) (Instructor: Robin Haw)"
    outline:
      content:
        - "Basic network concepts"
        - "Types of pathway and network information"
        - "Network and pathway databases"
        - "More examples of pathway and network analysis methods"
        - "Reactome analysis tools: network clustering and paradigm"
    lab_practical1:
      title: "Lab Practical #1 Tutorials on Cytoscape (Veronique Voisin)"
      content:
        - "Networks"
    lab_practical2:
      title: "Lab Practical #2 Reactome (Robin Haw)"
      content:
        - "Workflow of tools and steps"
        - "Reactome FI"
    day: 6
    PPT: ""
    PDF: ""
    YouTube: ""
  - title: "Module 16 - Gene Function Prediction (2017) (Instructor: Quaid Morris Instructor: Veronique Voisin)"
    outline:
      content:
        - "Functional association networks and gene function prediction"
        - "Functional relationships, similarity space"
        - "Guilt-by-association concept"
        - "GeneMANIA and STRING tools"
    lab_practical:
      title: "Lab Practical: (Veronique Voisin)"
      content:
        - "Workflow of tools and steps"
        - "Using GeneMANIA to assess gene and gene list function"
    integ_assign:
      title: "Evening Integrated Assignment Part"
      content:
        - "g:Profiler, EnrichmentMap, ReactomeFi, geneMANIA (Veronique Voisin)"
    day: 6
    PPT: ""
    PDF: ""
    YouTube: ""
  - title: "Module 17 - Regulatory Network Analysis (2017) (Instructor: Michael Hoffman Instructor: Veronique Voisin)"
    outline:
      content:
        - "Overview of transcription and transcriptional regulation"
        - "Data sources for regulatory data - ChIP-seq, DNAse-seq, methylation data"
        - "Using epigenomics data"
        - "Finding transcription factor binding sites"
    lab_practical:
      title: "Lab Practical"
      content:
        - "Overrepresentation of transcription factor motifs using the Cytoscape app iRegulon"
    day: 7
    PPT: ""
    PDF: ""
    YouTube: ""

---

## Course Objectives ##

  With the introduction of next generation sequencing platforms, it is becoming feasible to consider sequencing approaches to address many research projects. Now more than ever, having knowledge of the available bioinformatic resources and the informatic skills to analyze such data is critical.

  The **Canadian Bioinformatics Workshops**, in collaboration with *Cold Spring Harbor Laboratory*, has developed a comprehensive 7-day course covering the key bioinformatics concepts and tools required to analyze DNA- and RNA-sequence reads using a reference genome. Participants will gain experience in cloud computing and data visualization tools, which will be applied throughout the course. Beginning with an understanding of the workflow involved to move from platform images to sequence generation, participants will gain practical experience and skills to be able to evaluate sequence read quality, map reads to a reference and analyze sequence reads for variation and expression level. The workshop will conclude with analyzing and conducting pathway and network analysis on the resultant ‘gene’ list. The tutorials are designed as self-contained units that include example data (e.g. Illumina paired-end data) and detailed instructions for installation of all required bioinformatics tools.

## Target Audience ##

  Graduates, postgraduates and PIs working with or about to embark on analysis of data from next generation sequencing platforms (Illumina focus). *A reference genome is required.*

  *Prerequisites for attendance:*

  Basic familiarity with Linux environment and S, R, or Matlab. Must be able to complete and understand the following simple Linux and R tutorials before attending:
  * [Linux Guide for Beginners](http://www.ee.surrey.ac.uk/Teaching/Unix/)
  * [Quick & Dirty Guide to R](http://ww2.coastal.edu/kingw/statistics/R-tutorials/text/quick&dirty_R.txt)

  You will also require your own laptop computer with wireless internet capability Minimum requirements: 1024x768 screen resolution, 1.5GHz CPU, 1GB RAM, recent versions of Windows, Mac OS X or Linux (Most computers purchased in the past 3-4 years likely meet these requirements). If you do not have access to your own computer, you may loan one from the CSHL. Please contact CSHL in advance to request a laptop.

## Tuition ##
  $2855 USD taxes included

## To Apply ##

  Please visit [CSHL Courses](https://meetings.cshl.edu/courses.aspx?course=C-CBW&year=17) to apply. Deadline for applications is January 15, 2017.

