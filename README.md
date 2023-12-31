## Studying Transcriptomic Complexity through Next-Generation Sequencing Data Analysis
_Universidade Federal da Bahia & Instituto Gonçalo Moniz - Fiocruz Bahia_

_December 18-22, 2023 | Salvador, Bahia, Brazil_


## Course Overview

RNA sequencing technologies have evolved drastically since the publication of the first draft of the human genome in 2001. Over this period, new technologies have been developed, contributing to the characterization of the complexity of the transcriptomes of several communicable and non-communicable diseases, by allowing the study of the set of RNAs from these conditions in a comparative way with healthy tissues, or even through the characterization of the transcriptome of pathogens and disease vectors. 

This comprehensive 5-day course was designed to provide participants with advanced knowledge and practical skills in transcriptomic data analysis. Led by experts in the field, the course covers a wide range of topics, including the complexity of eukaryotic transcriptomes, experimental methodologies for transcriptional analysis, de novo transcript reconstruction, functional annotation of transcripts, quantification of gene and transcript expression, differential expression analysis, analysis of transposable elements, computational analysis of non-coding RNAs, and alternative splicing. Additionally, participants will be introduced to the emerging field of single-cell transcriptomics. The course combines theoretical sessions with hands-on practical exercises, ensuring that attendees gain a deep understanding of transcriptomic analysis techniques and their applications. It is a valuable opportunity for researchers and students seeking to enhance their expertise in the study of gene expression and transcriptomes using next-generation sequencing data.



## Scientific Organizing Committee
- [Dr. Ricardo Khouri](https://scholar.google.com/citations?hl=es&user=U-XypIYAAAAJ), Universidade Federal da Bahia & Instituto Gonçalo Moniz - Fiocruz Bahia (Brasil).
- [Dr. Vinicius Maracaja-Coutinho](https://scholar.google.com.br/citations?user=T_dpe84AAAAJ&hl), Advanced Center for Chronic Diseases (ACCDiS), Universidad de Chile, Chile.


## Instructors

- [Dr. Guillermo Parada](https://scholar.google.com/citations?hl=es&user=PTLeXysAAAAJ), University of Toronto (Canada).
- [MSc. & PhD(c) Juan Pablo Silva](https://scholar.google.com/citations?user=02dF20IAAAAJ), Universidad de Chile (Chile).
- [Dr. Mónica Saldarriaga-Córdoba](https://scholar.google.com/citations?hl=es&user=nBBt_2UAAAAJ), Universidad Bernardo O’Higgins (Chile).
- [Dr. Raúl Arias-Carrasco](https://scholar.google.com/citations?user=WRPcvtMAAAAJ&hl=en), Universidad Tecnológica Metropolitana - UTEM (Chile).
- [Dr. Romain Guyot](https://scholar.google.com/citations?hl=es&user=1jAQU2wAAAAJ), IRD Montpellier (France).
- [Dr. Vinicius Maracaja-Coutinho](https://scholar.google.com.br/citations?user=T_dpe84AAAAJ&hl), Advanced Center for Chronic Diseases (ACCDiS), Universidad de Chile (Chile).

 
## Hands-On Bioinformatics Training Material

Below, you will find the links to the pre-course videos and Google Colab notebooks for the practical modules. You can find the lectures slides at the Google Classroom dedicated for the course.


### Pre-course Videos:

- [Introduction to R for Biologists:](https://melbournebioinformatics.github.io/r-intro-biologists/intro_r_biologists.html)
_This course has been designed to introduce biologists to R, showing some basics, and also some powerful things R can do (things that would be more difficult to do with Excel)._
- [Linux for Biologists Workshop:](https://github.com/ssbcb/Linux-for-biologists-workshop/blob/main/Introduction-to-linux-101/Introduction-to-linux-101.md)
_This material covers the basics of shell scripting, a powerful tool for automating tasks and data processing in bioinformatics._
- [Python for Biologists:](https://www.pythonforbiologists.org/)
_This material provides a collection of episodes with videos, codes, and exercises for learning the basics of the Python programming language through genomics examples_
- [Get started with Google Colaboratory:](https://www.youtube.com/watch?v=inN8seMm7UI)
_This video provides a basic understanding of Google Colaboratory or Google Colab and their notebooks structure, which is the web-based interactive computing platform that we will be using along with our bioinformatics practical work._


### Practical Modules with Google Colab Notebooks:

- [Notebook 01 - Filtering raw RNA-seq data](https://colab.research.google.com/drive/1yqbTYG5Lpma0SMC-ExwANB7pAf_lZ_ZQ?usp=sharing):
_This collaborative notebook guides researchers in evaluating RNA sequencing data quality. Through FastQC, MultiQC, and Fastp, it swiftly assesses data integrity, detects anomalies, and refines data for downstream analysis. Step-by-step instructions and code snippets enable users to efficiently apply these tools, ensuring robust data quality for diverse RNA sequencing experiments. Targeting researchers and bioinformaticians, this resource streamlines QC analysis and enhances data reliability, vital for accurate biological interpretations._

- [Notebook 02 - De novo transcriptome reconstruction](https://colab.research.google.com/drive/17K_FpCnPJVN5JkRhlrYbJNdorwAC1wO2?usp=drive_link)
 _This Google Colab notebook serves as a comprehensive guide for de novo transcriptome reconstruction from RNA sequencing reads, showcasing the methodology using SOAPdenovo-Trans. While using a subset of sequencing reads from Phyllomedusa Bahiana as an example, this resource elucidates all the step necessary to reconstruct a transcriptome without relying on a reference genome._

- [Notebook 03 - Transcriptome reconstruction based on reference genome](https://colab.research.google.com/drive/1dNTzWAAc6UlAXY-0JuwjNOdANCJ8TaNK?usp=drive_link)
 _This Google Colab notebook acts as a comprehensive tutorial for transcriptome reconstruction based on a reference genome. It provides an in-depth exploration of the methodology, employing tools like Hisat2 for read mapping and samtools for data manipulation. Participants will gain hands-on experience in the entire process, from mapping sequencing reads to reconstructing transcripts using stringTie, and ultimately quantifying gene and transcript expression levels with featureCounts._

- [Notebook 04 - Funtional Annotation](https://colab.research.google.com/drive/1eRUSkEjx6JyirB89CTk7VPSlKBCRGxo8?usp=sharing) 
_This Google Colab notebook provides a detailed walkthrough for gene functional annotation utilizing the Diamond tool and orthologous group identification using OrthoFinder. Researchers can follow step-by-step instructions to annotate genes swiftly and establish orthologous relationships, crucial for evolutionary and functional genomics studies._

- [Notebook 05 - Differential expression analysis](https://colab.research.google.com/drive/171scE-KZrtYrBvQTUSHZaA0Jmd55iWlT?usp=sharing)
_This notebook focuses on conducting a differential expression analysis using the DESeq2 package. This comprehensive guide enables researchers to analyze RNA sequencing data effectively, identifying genes with significant expression changes across experimental conditions. Step-by-step instructions empower users to explore and interpret differential expression, aiding in the discovery of biologically meaningful insights._

- [Notebook 06 - Noncoding RNA annotation and miRNA sequencing analysis](https://colab.research.google.com/drive/11VuWxJNlybJKk2Fm5AUoaeR_UBji4HxG?usp=sharing)
_This Google Colab notebook offers a comprehensive guide for annotating non-coding RNAs (ncRNAs) using RNAmining and Infernal tools. Additionally, it provides a step-by-step procedure for small RNA sequencing data analysis, aiding in the identification of microRNAs (miRNAs). Tailored for researchers and bioinformaticians, this resource facilitates ncRNA annotation and miRNA discovery, crucial for understanding regulatory RNA functions and mechanisms._
**Google collab notebook with the answers to the differential expression analysis exercise:** [Notebook 06 - Answered](https://colab.research.google.com/drive/151EaxtINxnulFMbFGKaC3PJ-ABvRP5CS?usp=sharing)

### Authorship and Acknowledgments:

This comprehensive material has been a result of collaborative efforts since 2021 and has been successfully employed in numerous courses organized by the Advanced Center for Chronic Diseases - ACCDiS, Universidad de Chile and Universidad Tecnológica Metropolitana - UTEM. We extend our heartfelt gratitude to all the individuals listed below, who have actively contributed to the development and refinement of this material over the years. Their dedication and expertise have been instrumental in making this resource valuable for the bioinformatics community.

We appreciate the continuous support and feedback from participants, mentors, and institutions that have made this endeavor possible. Together, we strive to advance the understanding and application of data-driven biology in Latin America and the Caribbean.

**List of Contributors - Listed Alphabetically:**

- **PhD(c) Allan Peñaloza-Otarola**, Universidad de Chile (Chile).
- [MSc. & PhD(c) Juan Pablo Silva](https://scholar.google.com/citations?user=02dF20IAAAAJ), Universidad de Chile (Chile).
- [Dr. Raúl Arias-Carrasco](https://scholar.google.com/citations?user=WRPcvtMAAAAJ&hl=en), Universidad Tecnológica Metropolitana - UTEM (Chile).
- [Dr. Vinicius Maracaja-Coutinho](https://scholar.google.com.br/citations?user=T_dpe84AAAAJ&hl), Advanced Center for Chronic Diseases (ACCDiS), Universidad de Chile (Chile).
- [PhD(c) Wladimir Corrales](https://scholar.google.com/citations?hl=es&user=vt3Erm4AAAAJ), Universidad de Chile (Chile).
    

******
## License
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
