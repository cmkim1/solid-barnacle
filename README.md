# Effects of Cordyceps sinensis on mouse gut microbiome
## Community
### analysis procedure
- read processing: FastQC
- OTU picking: DADA2
- OTU picking DB: SILVA SSU 138.1

### Statistics
- Samples: 88 mice
- Total numbers of reads: 5,251,173
- raw read number (average): 59,672
- read number after QC (average): 36,044 (read number after QC < 10000: CM27, CM70, CM71)

### bar plot
- Genus level profile was used for drawing bar plot.
- Only 10 abundant genera (>0.5% total abundance) were noted.
![Rplot](https://user-images.githubusercontent.com/119988478/206132172-fe349477-a305-4a81-b0f5-07cea4c1a682.png)

### nmds analysis
- nmds analysis was performed with OTU level profile
![sheet2_nmds_ellipse](https://user-images.githubusercontent.com/119988478/206134161-795288fd-c59c-4df9-8b2b-7f8404e43dd1.png)


### diversity box plot
- Measured indexes: Shannon, Simpson
![sheet1_diversity](https://user-images.githubusercontent.com/119988478/206093761-0ba97b02-564e-4f65-9215-243f51538482.png)
