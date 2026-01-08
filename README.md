# Recombination-Analysis-Workflow

This repository presents the conceptual modeling of the Recombination Analysis Workflow (RAW), a computational framework designed to identify and characterize genomic recombination events. RAW integrates sequence alignment and annotation, recombination detection, SNP profiling, phylogenetic inference, and assessment of recombination effects on phylogenetic tree topology.

The workflow was applied to dengue virus genomes as a case study for recombination analysis, results are provided in the corresponding directories.

## Steps

RAW/  
├──Activity 1.Genomic data collection: GenBank and NCBI   
├──Activity 2. Serotype and genotype classification: GenomeDetective v2.77  
├──Activity 3. Genome annotation and alignment: FLAVi2  
├──Activity 4. Recombination detection: RDP v5.55  
├──Activity 5. Recombinant SNPs analysis: SNIPIT  
├──Activity 6. Literature search: Google Scholar and Pubmed  
├──Activity 7. Phylogenomic tree: RAxML v8.2.12, TNT v1.6, and IQ-TREE2.0.7  
└──Activity 8. Tree topology analysis: TNT v1.6 and YBYRÁ

## Dependencies:

1. GenBank (https://www.ncbi.nlm.nih.gov/genbank/) and BV-BRC (https://www.bv-brc.org/);

2. GenomeDetective (https://www.genomedetective.com/app/typingtool/virus/);

2. FLAVi2 (https://gitlab.com/MachadoDJ/FLAVi);

3. RDP v5.55 (https://web.cbio.uct.ac.za/~darren/rdp.html);

3. RAxML v8.2.12 (https://github.com/stamatak/standard-RAxML);

4. IQ-TREE v2.0.7 (https://github.com/iqtree/iqtree2);

5. TNT v1.6 (https://www.lillo.org.ar/phylogeny/tnt/);

6. YBYRÁ (https://gitlab.com/MachadoDJ/ybyra);
-svgwrite

7. Python (≥3.9)  
-biopython  
-pandas  
-snipit
-parsl
-setuptools
