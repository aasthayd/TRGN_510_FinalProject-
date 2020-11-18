# TRGN_510_FinalProject
<h3>Title:
<h4>"Differential Expression analysis of Bronchus and Lung cancer genes between patients of white and african american ethnicities".

<h3>Author:
<h4>Aastha Yatin Dave

<h3>Contact:
<h4>davea@usc.edu

<h3>Overview :
  <h4>The aim of this project is to identify the differential expression of genes in Bronchus and Lung cancer between people who are identified as white and african american and also between males and females.All the patients are diagnosed with adenomas and adenocarcinomas. I will be using Bioconductor packages (Limma, Glimma, egdeR) to analyze the RNA Seq data. 
   The reference Vignette: https://www.bioconductor.org/packages/devel/workflows/vignettes/RNAseq123/inst/doc/limmaWorkflow.html
<h3>Data: 
<h4> The data is obtained from : https://portal.gdc.cancer.gov/repository?facetTab=cases&filters=%7B%22op%22%3A%22and%22%2C%22content%22%3A%5B%7B%22content%22%3A%7B%22field%22%3A%22cases.case_id%22%2C%22value%22%3A%5B%22set_id%3AvpGcj3UB-W348b5h03Fy%22%5D%7D%2C%22op%22%3A%22IN%22%7D%2C%7B%22op%22%3A%22in%22%2C%22content%22%3A%7B%22field%22%3A%22cases.demographic.gender%22%2C%22value%22%3A%5B%22male%22%5D%7D%7D%2C%7B%22op%22%3A%22in%22%2C%22content%22%3A%7B%22field%22%3A%22cases.primary_site%22%2C%22value%22%3A%5B%22bronchus%20and%20lung%22%5D%7D%7D%2C%7B%22op%22%3A%22in%22%2C%22content%22%3A%7B%22field%22%3A%22cases.project.project_id%22%2C%22value%22%3A%5B%22TCGA-LUAD%22%5D%7D%7D%2C%7B%22op%22%3A%22in%22%2C%22content%22%3A%7B%22field%22%3A%22files.analysis.workflow_type%22%2C%22value%22%3A%5B%22HTSeq%20-%20Counts%22%5D%7D%7D%2C%7B%22op%22%3A%22in%22%2C%22content%22%3A%7B%22field%22%3A%22files.data_category%22%2C%22value%22%3A%5B%22transcriptome%20profiling%22%5D%7D%7D%2C%7B%22op%22%3A%22in%22%2C%22content%22%3A%7B%22field%22%3A%22files.data_format%22%2C%22value%22%3A%5B%22txt%22%5D%7D%7D%5D%7D
  
<h3>Milestone1:
<h4> I will filter out and download the data from the GDC portal. 20 samples of white  and 20 samples of african american patients. Load the data into R. Set up R and carry out data packaging. 

<h3>Milestone2:
<h4> Normalize the data and perform differential expression analysis. Represent the results using graphical representations.
  <h4>Update: Included a new variate which also divides data on bases of gender along with ethnicities. The log FC was changed to 0.1 from 1 in order to get better results. The gene set testing with camera function was completed. 
  
<h3>Deliverables:
<h4> R Markdown
