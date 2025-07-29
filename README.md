# MLanalysis-of-Pol2-pause-locations
The project focuses on analyzing polymerase II pause locations in yeast. 

The growing impact of machine learning is visible in a variety of fields, especially those that require processing of very large data sets with complex relationships; this project took existing genomic data relating to RNA Polymerase II pause locations in Saccharomyces Cerevisiae mapped using Native Elongated Transcript Sequencing (NET-Seq) as well as data available on histone medication of the Yeast genome and built machine learning algorithms to study their capabilities to accurately predict the presence of pause locations. 
The study made multiple modifications to the default random forest algorithm; it found limited prediction capabilities using histone modification data alone; thus, acknowledging some impact of Histone Modification on RNA Polymerase II pausing as well as its fine tuning by other biological structures and mechanisms. 
The key motivation for this paper was a study by Couvillion, et al., (2021); titled “Transctiption Elongation is finely tunes by dozens of regulatory factors”


Tools : 
The analysis was conducted using Python (version 3.12) in the Jupyter environment (version 7.0.8) through the Anaconda Navigator (Version 2.6); packages such as Numpy, Skitlearn, Matplotlib, Pandas, Joblib and XGBoost were utilized.

Data set : Data set is available at https://1drv.ms/f/c/b1b8c913b258c610/ElEvw97bZexGrLoqvu71HkABHch-Je7Gg-FqjG1maUvmng?e=zk1YnB 
source of the data is as below

National Center for Biotechnology Information (GSE159603) that used NET-Seq to map Pol II concentrations in wild type Saccharomyces Cerevisiae generated for a study by Couvillion, et al., (2021)

In addition, data sets for histone modifications were obtained from datasets made available on the National Center for Biotechnology Information with GSE61888 by (Weiner, et al., 2015). The data sets mapped 26 different chromatin modifications across the yeast genome during transcription (see Suplementary Material, Section 6).

Thank you.
