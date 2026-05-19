**Raw Quality Control (Falco + MultiQC)**

- Total reads: 10.6 million paired sequences for GSM461177 (untreated) and 12.3 million for GSM461180 (treated)
- Read length: 37 bp for all samples
- Overall quality was good for 3 out of 4 files
- GSM461180_treat_paired_reverse showed a notable quality drop at the end of reads
- High duplication levels observed — expected and normal for RNA-Seq data

**After Trimming (Cutadapt)**

- Quality cutoff applied: Q20
- Minimum read length: 20 bp
- GSM461177: 2.5% of read pairs removed (too short after trimming)
- GSM461180: 12.4% of read pairs removed (higher removal consistent with poorer reverse read quality)
- More bases trimmed from reverse reads than forward reads in both samples
- Trimmed reads carried forward for mapping
