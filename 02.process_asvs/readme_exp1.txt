Files: 
[in order of creation]
[note: 100 indicates the clustering was 100% - i.e. ASVs, all of them are at this level so I stopped using 100 in the file names]

ps.all.raw100.rds = all the ASVs
ps.all.clean.100.rds = all ASVs after quality control steps
ps.all.clean.100.less.rds = 5 low read samples removed
ps.clean.trim.rds = 5 low read samples removed, singleton ASVs removed, and ASVs that make up <146 reads total removed
ps.clean.trim.rare9200.rds = same as trim but also rarefied to 9200