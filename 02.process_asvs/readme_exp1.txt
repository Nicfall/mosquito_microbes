Files: 
[in order of creation]
[note: 100 indicates the clustering was 100% - i.e. ASVs, all of them are at this level so I stopped using 100 in the file names eventually]

ps.all.raw100.rds = all the ASVs, first phyloseq object
ps.all.clean.100.rds = all ASVs after quality control steps
ps.clean.trim.rds = ASVs that make up <153 reads total removed
ps.clean.trim.less.rds = low read samples removed
ps.clean.trim.rare9200.rds = same as trim but rarefied to 9200 reads

Within /counts_taxa_info/ folder
metadata_cleaned.csv
mosquito_raw_reads.xlsx
seqtable100_counts.csv = raw output from CMAIKI
sequences_100_original.fasta = raw output from CMAIKI
sequences_100.1-4 = cleaning up the fasta file
taxa_v138.1_boot60.rds = taxonomic assignment done on the cluster
taxa_v138.1_boot60.csv = same file as before but reformatted with lots of info for phyloseq object
taxa_v138.1_boot60_edits.csv = same file as above but added pool name columns for the taxa we intentionally introduced
