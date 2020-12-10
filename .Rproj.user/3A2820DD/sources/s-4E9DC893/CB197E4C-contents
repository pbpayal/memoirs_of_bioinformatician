# Make the tables for resume

```{r setup, include=FALSE}
# Build table for Technical expertise
tech_expertise <- matrix(c("Programming","Bash scripting, Python, R",
                           "Next Generation Sequencing Pipelines","RNA Sequencing, DNA Sequencing, Microbiome, T-cell Receptor Sequencing, Chip Seq, Single Cell sequencing, Microarray",
                           "Cloud Resource NGS Platforms", "DNA Nexus, Illumina Basepace (including DRAGEN), Galaxy, Cavatica, GenePattern",
                           "Cloud Computing","AWS EC2 and S3",
                           "Operating Systems","Unix (Linux,Ubuntu, Centos, macOS)",
                           "Website Management", "Github Pages , Relational Databases (RDMS), MySQL, HTML, PHP, Apache, Data Model Design, Drupal"),
                         ncol=2,byrow=TRUE)
colnames(tech_expertise) <- c("Area","Technique")
rownames(tech_expertise) <- c("1","2","3","4","5","6")
tech_expertise <- as.table(tech_expertise)
tech_expertise
```


```{r include=FALSE}
knitr::kable(
  tech_expertise[1:6, 1:2], caption = '**Technical Expertise**'
)
```



```{r setup, include=FALSE}
# Build table for Education
education <- matrix(c("M.S.","Bioinformatics","Georgetown University","2014-2015","Washington, DC, USA",
                      "M.S.","Biochemistry","Bangalore University","2011-2013","Bangalore, India",
                      "B.S.","Biotechnology, Microbiology, Biochemistry","Bangalore University","2008-2011","Bangalore, India"),
                    ncol=5,byrow=TRUE)
colnames(education) <- c("Degree","Field","University/College","Timeline","Place")
rownames(education) <- c("1","2","3")
education <- as.table(education)
education
```

```{r include=FALSE}
knitr::kable(
  education[1:3, 1:5], caption = '**Education**'
)
```


```{r setup, include=FALSE}
# Build table for Education
publication <- matrix(c("Immunotherapy of Relapsed and Refractory Solid Tumors With Ex Vivo Expanded Multi-Tumor Associated Antigen Specific Cytotoxic T Lymphocytes: A Phase I Study","Journal of Clinical Oncology","https://ascopubs.org/doi/10.1200/JCO.19.00177",
                        "Enabling precision medicine in neonatology, an integrated repository for preterm birth research","Scientific Data","https://www.nature.com/articles/sdata2018219",
                        "A cross-sectional analysis of the urine microbiome of children with neuropathic bladders","[Science Direct","https://doi.org/10.1016/j.jpurol.2020.02.005",
                        "Identification of amygdala-expressed genes associated with autism spectrum disorder","Molecular Autism","https://doi.org/10.1186/s13229-020-00346-1",
                        "Endothelin-1 signaling maintains glial progenitor proliferation in the postnatal subventricular zone","Nature Communications","https://doi.org/10.1038/s41467-020-16028-8"),
                      ncol=3,byrow=TRUE)
colnames(publication) <- c("Title","Journal Name","Link")
rownames(publication) <- c("1","2","3","4","5")
publication <- as.table(publication)
publication
```

```{r include=FALSE}
knitr::kable(
  publication[1:5, 1:3], caption = '**Publication**'
)
```




