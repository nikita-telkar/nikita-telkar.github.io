---
title: "Projects"
output: 
  html_document: 
    theme: flatly
    highlight: monochrome
    keep_md: yes 
    toc: true
    toc_depth: 6
    toc_float:
      collapsed: true
      smooth_scroll: true
--- 



<style>
#TOC {
  background: url("static/TOC.png");
  background-size: contain;
  padding-top: 80px !important;
  padding-bottom: 80px !important;
  background-repeat: no-repeat;
}
</style>

<style>
a:link {
    color: purple;
}

a:visited {
    color: purple;
}

 a:hover {
    color: purple;
}

hr {
  height: 1px;
  background-color: #999999;
  border: none;
    }

</style>


<style type="text/css">

@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;1,400&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Bitter:wght@400&display=swap');

/* title of page */
.title {
  font-family: 'Bitter';
}

/* body of page */
body {
    font-family: 'Open Sans';
    font-size: 15px;
    background-color: #fbf9f7;
}

/* styling for headings in TOC */
h4, #TOC>ul>li {
  font-family: 'Montserrat';
}

h5, #TOC>ul>ul>li {
  font-family: 'Montserrat';
}



/* styling for headings on page */
h4 {
  font-family: 'Bitter';
  font-size: 23px;
  color: #853078;
}

h5 {
  font-family: 'Bitter';
  font-size: 20px;
}

.tocify {
  # position: -webkit-sticky;
  # position: sticky; 
  # top: 120px; /*Controls where TOC stops when sticky */
  width: 100% !important;
  border: none;
}


/* styling for TOC overall */
.list-group-item {
    color: #666666;
    font-size: 15px;
    background-color: #F7F3F0;
}

/* styling for active item selected in TOC */
.list-group-item.active {
    color: white;
    background-color: #853078;
    border: none;
}

/* styling for item/heading being hovered over in TOC */
.list-group-item:hover, 
.list-group-item.active:hover {
    color: #853078;
    background-color: white;
}


/*----------------NAVBAR ---------------*/
.navbar-default {
    background-color: #333333f2;
}

.navbar-default .navbar-nav>.open>a, 
.navbar-default .navbar-nav>.active>a, 
a.dropdown-toggle:hover {
  background-color: #333333 !important;
}

/* Dropdown menu color */
.navbar-default .dropdown-menu {
  background-color: #333333;
}

/* Dropdown menu hover color */
  .navbar-default .dropdown-menu>li>a:hover {
    background-color: #333333f2;
  }

/* Navbar Links when hovered*/
.navbar-default .dropdown-menu>.active>a
.navbar-default .navbar-nav>.active>a:hover, 
.navbar-default .navbar-nav:hover, 
.navbar-default .navbar-nav>li>a:hover, 
a.navbar-brand:hover {
  color: #ffffffab !important;
  background-color: #333333;
}
</style>


***  

### PhD Projects 

<br> 

#### Primary Project

<br>

**Characterizing small non-coding RNAs in the human placenta**  

The human placenta is indispensible for the growth of the fetus and for the healthy progression of pregnancy. It serves as the interface between the mother and baby for all water, nutrient, gas, and waste exchange; as such regulation of gene expression is tightly regulated at every stage. Gene regulation is carried out by a number of factors, and expression modulation by small non-coding RNAs (sncRNAs) is one such regulatory mechanism.  [Exclusive placentally-expressed sncRNA loci in the placenta have been identified](https://10.1016/j.ajog.2015.07.046), however, studies have routinely focused on only one species of sncRNA (microRNAs), largely due to sample availability.

**My project aims at**:  

1. Characterizing human placental sncRNA species in whole tissue and 4 placental cell types (cytotrophoblasts, endothelial cells, stromal cells, HofBauer cells)   
2. Investigating novel placental sncRNAs    
3. Assessing biological (cell type, trimester, sex of the fetus, ancestry, depression and anti-depressant status of the mother, stress) and technical variables (method of extraction and various sequencing metrics) driving expression    
4. Testing association between sample-matched DNA methyaltion and sncRNA expression  
5. Examining shared expression characteristics between placenetal development and cancer  

`Data:` low-input small-RNA-seq, DNA methylation  
`Software:` R, GSEA, pathway enrichment  
`Code:` 

- [R Shiny app](https://robinsonlab.shinyapps.io/Placental_miRNome_Expression_Database/) (to be updated once manuscript is published)    
- [Raw sequence to expression counts walkthrough](https://github.com/nikita-telkar/Projects/blob/master/RNA-seq%20-%20FASTQ%20to%20Expression%20Counts/FASTQ_to_Read_Counts.md)  
- [Pilot Project](https://github.com/nikita-telkar/Projects/blob/master/sncRNA%20in%20the%20Human%20Placenta%20(Pilot)/Pilot_script_full.md)  
- [Preliminary sncRNA QC](https://github.com/nikita-telkar/Projects/tree/master/Differential%20Input%20RNA%20Concentration%20Analysis)  
- [Preliminary sncRNA-DNAme correlation](https://github.com/nikita-telkar/Projects/tree/master/sncRNA-DNA%20Methylation%20Association)  

`Project Impact:`  

- Selected New Investigator Talk - [International Federation of Placenta Associations (IFPA)](https://www.ifpa.epineux.com/meetings) (the biggest international conference on placental biology) 2024 conference  
- Selected Talk, New Technologies for Cancer Research - [European Society of Human Genetics (ESHG) 2023](https://2023.eshg.org/)  
- [Poster](https://github.com/nikita-telkar/nikita-telkar.github.io/blob/main/static/DoHAD_2022_NT.pdf) Example: Developmental Origins of Health and Disease (DOHaD) 2022 Conference  


***  

#### Collaborations  

<br>  

##### 1. BC Children's Hospital Research Institute / [The Ted Steiner Lab](https://www.bcchr.ca/tsteiner)  

**Project: An IBD-mimic human colonoid chronic-injury model**     

Intestinal cells undergo regeneration after acute injury. However, the feasibility and capacity of these cells to undergo repeated renewal and regeneration on chronic injury is still not well understood. Using intestinal epithelial cells collected from 2 human  patients, colonoid organoids were generated in the lab and were further subjected to rounds of induced damage, inflammation and rescue to observe the renewal mechanisms of these cells  

*I was recruited as a Bioinformatician for this exploratory project to analyze their RNA-seq data, for which I was given second-authorship on the respective manuscript*


`Data:` Human and murine RNA-seq 
`Software:` R, GSEA    
`Code:`  
- [Geneset enrichment analysis](https://github.com/nikita-telkar/Projects/tree/master/GSEA%20of%20Human%20Colonic%20Organoids)  
- [GEO accession](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE178698)  

`Publication:` [Second-author in Cell Reports](https://www.cell.com/cell-reports/fulltext/S2211-1247(21)01798-8)

***  

##### 2. Centre for Heart Lung Innovation: St. Paul's Hospital / [The Decheng Yang Lab](https://www.hli.ubc.ca/researchers/decheng-yang/)  

**Project: Role of NFAT5 in the pathogenesis of coxsackievirus-induced myocarditis**    

*I was recruited to analyse their bioinformatics data in the POC study, which also availed me to undertake a project related to the scientific area which intersts me the most - cardiovasuclar disease* 

`Data:` Murine RNA-seq  
`Software:` R  

`Publication:` [Basic Research in Cardiology](https://link.springer.com/article/10.1007/s00395-024-01058-w)  

*** 

##### 3. BC Children's Hospital Research Institute / [The Gregor Reid Lab](https://bcchr.ca/greid)  

**Project: Investigating the dynamic immunophenotypic cell population changes during childhood acute lymphoblastic leukemia (ALL) relapse**  

*I trained the first-author physician-scientist in R Programming* 

`Data:` Human RNA-seq  
`Software:` R  

`Publication:` Manuscript submitted to Nature Cancer    


***  

##### 4. BC Cancer Research Centre / [The Kevin Bennewith Lab](https://www.bccrc.ca/dept/io/people/kevin-bennewith)  

**Project: Telmisartan treated tumours show an improved response to radiaition therapy**    

<br>

*In progress: Follow-up validation experiments of in-silico results*  

`Data:` Human + murine single-cell RNA-seq  
`Software:` R  

***  

##### 5. Djavad Mowafaghian Centre for Brain Health / [The Yu Tian Wang Lab](https://www.centreforbrainhealth.ca/faculty/yu-tian-wang/)  

**Notch1 signaling plays an essential role in metabolic rewiring in docetaxel resistance prostate cancer**    

<br>

*In progress: Manuscript writing*  

`Data:` Human RNA-seq  
`Software:` R  

*** 


### Master's Project  

<br>

**Comparing the Genetic Architecture of Lipid Traits between Populations**  

The majority of Genome-wide Association Studies, even now, focus on Caucasian, European populations. Genetic differences exist people of differing populations, where people of a certain ancestry or ethnicity can have genetic variants not present in those of European popualtions. These variants can lead to variable gene expression, as well as a differential response to drugs admistered. Hence, the resulsts of these single-poulation centric studies cannot be extrapolated to different populations. There is, therefore, an increased need to conduct such genome-wide studies in several other populations, along with accounting for population differences in large-scale studies. 


**I collected GWAS summary statistics of three lipid (cholesterol) biomarkers from seven different populations (British, two Greek isolates, Chinese, Japanese, East Asian, Ugandan) calculated the Polygeneic Risk Scores (PRSs) of each individual using the commonly overlapping lipid SNPs to assess if these scores varied across the  populations. The heritability as well as trans-ancestral correlation was also calculated. The measured blood lipid biomarker levels were then examined across the genetic scores, to investigate the correlation between the blood lipid levels of one biomarker against the genetic score of another (biomarker-score cross association).**  

`Data:` Human SNP (GWAS)  
`Software`: UNIX, command-line R, PLINK, GEMMA, Popcorn   

`Results`:  

- The majority of European CVD/lipid loci overlap with the Japanese, Chinese, Greek-isolate, and African Ugandan populations.  
- HDL biomarker/score showed an inverse relationship with LDL biomarker score; LDL and Triglycerides had a linear relationship, except for in the Ugandan population where triglyceride score did not correlate with biomarker score.  
- The two Greek-isolate populations showed near perfect heritability and trans-ethnic correlation with the UK population, same as the Japanese and Chinese population with the East Asian population.  


`Project Impact`:  

- Second-author publication in [Nature Communications](https://doi.org/10.1038/s41467-019-12026-7)  
- PRSs available on EMBL-EBI’s [PGS Catalog](http://www.pgscatalog.org/publication/PGP000046/)  
- Opportunity to work as as a Visiting Scientist at the [Wellcome Sanger Institute](https://www.sanger.ac.uk/)  

***  

### Undergraduate Summer Research


**Using WNT5A Expression to Characterize Development in the Human Gut**      

The [WNT genes](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2001-3-1-reviews3001) are known to participate in genetic pathways involved in cell patterning, signalling, and proliferation during development. WNT5A in particular is invloved in a number of [syndromes](https://www.genecards.org/cgi-bin/carddisp.pl?gene=WNT5A) which are caused by abnormal cell signalling or growth. The gut (made up of the esophagus, intestines, and anus) is one of the organs that grows and elongates the most during embryonic develpement.  

**Using immunohistochemistry, I measured the presence of the WNT5A protein the human embryonic gut at [Carnegie Stage 20 (~50 days post conception)](https://embryology.med.unsw.edu.au/embryology/index.php/Carnegie_stage_20).**  


`Project Impact`:  

- Received the UK-wide competitive [Genetics Society Summer Studentship Award](https://genetics.org.uk/grants/summer-studentships/) 2016   
- Trained in MAPaint and Amira software on Linux, which involved transferring the wet-lab protein expression results into a computer-based 3D model   
- Expression data and results of the project  uploaded to the NIH-funded HuDSeN database under the [Human Developmental Biology Resource (HDBR)](http://hdbratlas.org/organ-systems/gi-tract/gi-models.html).  
- [Attended the Genetics Society Summer Workshop](https://genetics.org.uk/wp-content/uploads/2017/11/15027387_10211122879777688_5581119349267154163_n.jpg) to present my research and the report of the same was selected to be published in the [Genetics Society January 2017 Newsletter](https://genetics.org.uk/wp-content/uploads/2017/09/Issue-76-_-January-2017.pdf)  
- [Research poster](https://drive.google.com/file/d/1jmUJNHydDgV3-tvmsTmlrqDHbtkCfDcq/view?usp=sharing
) won awards at two separate [University competitions](https://research.ncl.ac.uk/expeditionresearchscholarships/prizewinners/2016winners/).  


***

<div class="tocify-extend-page" data-unique="tocify-extend-page" style="height: 0;"></div>


