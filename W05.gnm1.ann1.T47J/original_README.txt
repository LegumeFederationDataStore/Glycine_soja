Files open for downloading include:

	Gsoja.W05.genome.fa.gz: Genome sequence of Glycine soja W05
	Gsoja.W05.gene.gff.gz: Gene annotation file of Glycine soja W05
	Gsoja.W05.gene.transcript.fa.gz: Transcript sequences for annotated genes (UTR sequences included)
	Gsoja.W05.gene.cds.fa.gz: Coding sequences for annotated genes (UTR sequences not included)
	Gsoja.W05.gene.protein.fa.gz: Protein sequences for annotated genes
	Gsoja.W05.gene.function.InterProScan.tsv.txt.gz: Functional doamins assigned for protein sequences using InterProScan. 
	NCBIvsLocal.Seq.ID.map.txt: Link map between NCBI and local sequence ID
	NCBIvsLocal.gene.ID.map.txt: Link map between NCBI and local gene ID
	MD5.TXT: md5 value for compressed files

For the InterProScan TSV file, it includes the following columns:

	1. Sequence ID 
	2. Sequence MD5 digest (e.g. 14086411a2cdf1c4cba63020e1622579)
	3. Sequence Length (e.g. 3418)
	4. Analysis (e.g. Pfam / PRINTS / Gene3D)
	5. Signature Accession (e.g. PF09103 / G3DSA:2.40.50.140)
	6. Signature Description (e.g. BRCA2 repeat profile)
	7. Domain start location
	8. Domain stop location
	9. Score - is the e-value (or score) of the match reported by member database method (e.g. 3.1E-52)
	10. Status - is the status of the match (T: true)
	11. Date - is the date of the run
	12. InterPro annotations - accession (e.g. IPR002093)
	13. InterPro annotations - description (e.g. BRCA2 repeat)
	14. GO annotations (e.g. GO:0005515)
	15. Pathways annotations (e.g. REACT_71)
For the use of the genomic data of W05, please cite:
	Xie, M. et al. (2019) A reference-grade wild soybean genome. Nat Commun, 10:1216

