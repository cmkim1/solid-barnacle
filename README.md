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
- Only 10 abundant genera were noted.
![sheet1_bar_final](https://user-images.githubusercontent.com/119988478/206201402-6f7bddaa-9540-49dd-8e0d-48f9ff16f9ac.png)


### nmds analysis
- nmds analysis was performed with OTU level profile
![sheet1_nmds_final](https://user-images.githubusercontent.com/119988478/206220072-1a42d926-1c2d-4241-b829-27d7002393e7.png)



### diversity box plot
- Measured indexes: Shannon, Simpson
![sheet1_diversity](https://user-images.githubusercontent.com/119988478/206093761-0ba97b02-564e-4f65-9215-243f51538482.png)
