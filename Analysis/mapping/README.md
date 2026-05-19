
**Mapping Results**
RNA STAR Alignment (dm6 reference genome)
Sample|Total Aligned|Uniquely Aligned|
----|----|----|
GSM461177 (untreated)|81.2%|78.4%|
GSM461180 (treated)|85.2%|82.8%|

- Both samples were above the 70% threshold for acceptable mapping
- Low percentage of multi-mapped reads — within normal range for Illumina short-read sequencing
- Splice-aware mapping confirmed reads spanning exon-exon junctions
- Reference genome used: Drosophila melanogaster dm6 Full
- Annotation file used: Drosophila_melanogaster.BDGP6.32.109_UCSC.gtf.gz

**Read Counting (featureCounts)**

- ~40% of reads assigned to annotated genes
- Strand specificity: Unstranded
- Only reads with minimum mapping quality of 10 were counted
- Reads counted at exon level, summarized to gene level using gene_id
