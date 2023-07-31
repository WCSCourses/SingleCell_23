## Course overview

Single-cell sequencing technologies are powerful tools used to assess genomic, transcriptomic and proteomics information at the single-cell level. In recent years, the application of techniques that use single-cell sequencing have become increasingly common in several areas of research: including medicine, agriculture, and other life sciences disciplines. Single-cell sequencing may be used to study many aspects of an organism’s biology, both in health and disease, and the results of these studies contribute immensely to advancing the understanding of organisms as a whole. 

Illustrated by the successful formation of scientific networks within the [Human Cell Atlas](https://www.humancellatlas.org/biological-networks/), there is growing interest among scientists and increased need for building capacity for single cell technologies. However, there is a lack of infrastructure, limited funding, and expertise  relevant for applying these advanced technologies in Latin America. Therefore, this short course offers hands-on laboratory training and bioinformatics analysis in single-cell technologies to contribute to capacity development in Latin America. 

[Course website](https://coursesandconferences.wellcomeconnectingscience.org/event/single-cell-genomics-latin-america-and-the-caribbean-20230728/)

## Scientific Organising Committee
- [Patricia Abrão Possik](https://www.researchgate.net/profile/Patricia-Possik-2), National Institute of Cancer (INCA), Brazil
- [David Adams](https://www.sanger.ac.uk/person/adams-david/), Wellcome Sanger Institute, UK
- [Mariana Boroni](https://www.gov.br/inca/pt-br/assuntos/pesquisa/pesquisa-basica-e-experimental/bioinformatica-e-biologia-computacional), National Institute of Cancer (INCA), Brazil
- Vinicius Maracaja-Coutinho, University of Chile, Chile

## Instructors & Speakers
- Erick Armingol, University of California, San Diego, USA
- [Lia Chappell](https://www.sanger.ac.uk/person/chappell-lia/), Wellcome Sanger Institute, UK
- [Yesid Cuesta Astroz](https://icmt.org.co/investigadores/yesid-cuesta-astroz/), Colombian Institute of Tropical Medicine (ICMT), Colombia
- Benilton de Sá Carvalho, Unicamp, Brazil
- [Anita Scoones](https://www.earlham.ac.uk/profile/anita-scoones), Earlham Institute, UK
- [Patricia Severino](https://www.researchgate.net/profile/Patricia-Severino), Albert Einstein Research & Education Institute, Brazil
- [Danielle Carvalho](https://www.linkedin.com/in/danielle-carvalho-2aa894197/), National Institute of Cancer (INCA), Brazil
- [Flavia Aguiar](https://www.linkedin.com/in/flavia-aguiar-7412b8211/), National Institute of Cancer (INCA), Brazil


## Hands-On Bioinformatics Training Material

Below, you will find the links to the pre-course videos and Google Colab notebooks for the practical modules. 

### Pre-course Videos:

- [Plotting in R for Biologists:](https://lms.wellcomeconnectingscience.org/course/view.php?id=106)
_This material provides an introduction to the R programming language, which is extensively used in bioinformatics and will be crucial in all the modules implemented over the course._
- [Introduction to Linux for Biologists:](https://lms.wellcomeconnectingscience.org/course/view.php?id=107)
_This material covers the basics of shell scripting, a powerful tool for automating tasks and data processing in bioinformatics._
- [Get started with Google Colaboratory:](https://www.youtube.com/watch?v=inN8seMm7UI)
_This video provides a basic understanding of Google Colaboratory or Google Colab and their notebooks structure, which is the web-based interactive computing platform that we will be using along with our bioinformatics practical work._

## Practical Modules with Google Colab Notebooks:

- [Notebook 01 - Processing raw scRNA-seq data](https://colab.research.google.com/drive/1PmK1h4ECQgjoVJmVguz3rlwLorThhafD?ouid=109970662236337661286&usp=drive_link):
_Processing raw single-cell sequencing data (scRNA-seq) is a crucial step in the whole pipeline analysis of scRNA-Seq experiments. Depending on the library preparation method used, the RNA sequences will be acquired either from 3’ ends (or 5’ ends) of the transcripts (10X Genomics, CEL-seq2, Drop-seq, inDrops) or from full-length transcripts (Smart-seq). The choice of a specific method will depend entirely on the biological question and the downstream analysis to be implemented from a count matrix. In this notebook we will cover theoretical and practical steps in setting up from raw sequences (reads)to count matrix analysis pipelines, as well as explore the basic output of the Cell Ranger tool._
**Related Slides 01:** [Module 01 - Processing raw seqs](https://docs.google.com/presentation/d/1-JtH_fVxiBIU0RdUCJiFpRu8M3MHlGTQV0T9f-0612o/edit).

- [Notebook 02 - Quality Control, Exploratory Analysis, Data Normalization, and Clustering in scRNA-seq experiments](https://colab.research.google.com/drive/1fJfiP8rGGRcMFlzC96C9WyTu7a9f2cQD?usp=sharing):
_In that part of the course, we will guide you through the initial steps of scRNA-seq data analysis, including data importing and organization, filtering, and preliminary visualization. These essential steps ensure quality and metadata information control over heterogeneous datasets before using the Seurat package and Bioconductor infrastructure. Once the data is imported, we will focus on assessing dataset quality through various metrics and visualizations, enabling the identification and removal of poor-quality cells. Furthermore, we'll delve into normalization techniques to address technical factors and clustering methods to group cells based on expression similarity, facilitating the interpretation of results and characterization of heterogeneity._
**Related Slides 02:** [Quality control and exploration of scRNA-seq datasets](https://docs.google.com/presentation/d/12FaxxhCGsflBTc_Z88weCJKDRmXKoIT6cNwVKrmF1NE/edit); **Related Slides 03:** [Clustering & normalization](https://docs.google.com/presentation/d/1og64xOAQuRZIbDgWfdaJEFTqhKqxekklLf2VHsKEBk0/edit).

- [Notebook 03 - Differential expression, cell type annotation and functional data analysis](https://colab.research.google.com/drive/18qOUPjd2IqRrIjYtqZiPxBGW492ZKG2G):
_Identifying the set of features (genes/transcripts) that show distinct patterns of expression when comparing different conditions is an essential part of scRNA-seq analysis. This enables one to explore what processes might be involved in the differentiation between these circumstances. 
In this notebook, we will discuss mechanisms of analysis that combine differential expression, cell type annotation, and functional analyses to address this issue._
**Related Slides 04:** [Differential expression, cell type annotation and functional data analysis](https://docs.google.com/presentation/d/1og64xOAQuRZIbDgWfdaJEFTqhKqxekklLf2VHsKEBk0/edit).

- [Notebook 04 - Integrating single-cell transcriptomes from multiple samples](https://colab.research.google.com/drive/1pIQkYG3_8oean0BU7yFHnx7zttPs0Mcr):
_With the increasing complexity of single-cell data, the integration of multiple datasets has become common. However, it is crucial to account for batch effects resulting from technical and biological variations to perform accurate analyses. These batch effects can stem from differences in sample handling, experimental protocols, sequencing platforms, as well as biological factors like the donor's genetic background and tissue origin. 
By employing computational methods to address these variations when comparing multiple samples, unwanted sources of variation can be eliminated, allowing researchers to focus on biologically meaningful signals. The process of removing batch effects involves making two important choices: selecting the appropriate method and parameterization, and determining the batch covariate. While the parameters are specific to the chosen method, the selection of the batch covariate depends on the goal of the integration task. This notebook will cover the key concepts and methods related to data integration and batch-effect correction, followed by hands-on activities that illustrate the integration of multiple datasets using methods from Seurat and Harmony._
**Related Slides 05:** [scRNA-seq dataset integration](https://docs.google.com/file/d/1rMHBVBjhDw6idUPPfkly6MGaUOKF1e1d/edit?usp=docslist_api&filetype=mspresentation).


******
## License
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
