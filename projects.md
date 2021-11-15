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

</style>

<style type="text/css">

@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;1,400&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');

body {
    font-family: 'Open Sans';
    font-size: 15px;
}


h4, #TOC>ul>li {
  font-family: 'Montserrat';
}

# h5, #TOC>ul>ul>li {
#  color: #323b58;
# }

.tocify {
  # position: -webkit-sticky;
  # position: sticky; 
  # top: 120px; /*Controls where TOC stops when sticky */
  width: 100% !important;
  border: none;
}

.list-group-item {
    color: #666666;
    font-size: 15px;
}

.list-group-item.active {
    color: white;
    background-color: #853078;
    border: none;
}


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

The human placenta is the indispensible organ necessary for all water, nutrient, gas, and waste exchange between the mother and fetus; as such gene expression is tightly regulated. Gene regulation is carried out a number of mechanisms, and gene repression by small non-coding RNAs (sncRNAs) is one of these processes. [Exclusive placentally-expressed sncRNA loci in the placenta have been identified](https://10.1016/j.ajog.2015.07.046), however, studies have routinely focused on only one species of sncRNA (microRNAs).

**My project aims at**:  

1. Characterizing the sncRNA species that are present in the human placenta and 4 placental cell types (trophoblasts, endothelial cells, stromal cells, HofBauer cells)   
2. Investigating novel sncRNA species  
3. Cataloguing the ones that differ in expression by different variables (like trimester of the pregnancy, sex of the fetus, ancestry, depression and anti-depressant status of the mother, and a few others).  

DNA methylation is another epigenetic regulatory mechanism, and [the placenta has been recognized for its unique epigenetic landscape](https://10.1101/cshperspect.a023044). The sncRNA expression data observed will be integrated with sample-matched DNAm data to investigate whether any correlation in expression exists between the two gene regulation mechansisms. [The placental gene expression profile also resembles that of cancer](https://10.1098/rsob.180081), and the top sncRNAs of interest will be examined for their connection to cancer progression.     

**Software**: R Programming. Some of my code is available on my [GitHub](https://github.com/nikita-telkar/Projects).    

**Project Highlights**:     

- Self-taught R, RMarkdown, and RNA-seq data analysis  
  - quality control, normalization, PCA, linear modeling, DNAm correlation, gene/pathway enrichment 
- First instance of large-scale trancriptomic sequencing of the human placenta.  
- Establishment of the normative placental transcriptomic profile by several inherent biological variables, and extrinsic technical and environmental variables.   
- Correlation to some cardiovasuclar and cancer pathway genes  
- Pilot analysis showed that there indeed are microRNAs differentially-expressed by trimester  


**Communication**:   

[Project Overview](https://drive.google.com/file/d/1OL7ODzJILB5Q56cb9N2DDmLlxZmwdvTz/view?usp=sharing)  
[BCCHR: Healthy Starts Research Day 2021 - Poster](https://drive.google.com/file/d/1K4JreNCGIXvbKClrT0TwzAF8Sf3B23Yh/view?usp=sharing)  

***  

#### Collaborations  

<br>  

##### 1. Human Colon Organoids   

Intestinal cells undergo regeneration after acute injury. However, the feasibility and capacity of these cells to undergo repeated renewal and regeneration on chronic injury is still not well understood. Using intestinal epithelial cells collected from 2 human  patients, colonoid organoids were generated in the lab and were further subjected to rounds of induced damage, inflammation and rescue to observe the renewal mechanisms of these cells  

**I was recruited as a Bioinformatician for this exploratory project by the [Ted Steiner lab at BC Children's Hospital Research Institute](https://www.bcchr.ca/tsteiner) to analyze their RNA-seq data, for which I was given second-authorship on the respective manuscript** 

**Software**: R, GSEA    

<br>

**Project Highlights**:  

- Second-author publication (https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3875768)  

***  

### Master's Project  

<br>

**Comparing the Genetic Architecture of Lipid Traits between Populations**  

The majority of Genome-wide Association Studies, even now, focus on Caucasian, European populations. Genetic differences exist people of differing populations, where people of a certain ancestry or ethnicity can have genetic variants not present in those of European popualtions. These variants can lead to variable gene expression, as well as a differential response to drugs admistered. Hence, the resulsts of these single-poulation centric studies cannot be extrapolated to different populations. There is, therefore, an increased need to conduct such genome-wide studies in several other populations, along with accounting for population differences in large-scale studies. 


**I collected GWAS summary statistics of three lipid (cholesterol) biomarkers from seven different populations (British, two Greek isolates, Chinese, Japanese, East Asian, Ugandan) calculated the Polygeneic Risk Scores (PRSs) of each individual using the commonly overlapping lipid SNPs to assess if these scores varied across the  populations. The heritability as well as trans-ancestral correlation was also calculated. The measured blood lipid biomarker levels were then examined across the genetic scores, to investigate the correlation between the blood lipid levels of one biomarker against the genetic score of another (biomarker-score cross association).**  

**Software**: UNIX, command-line R, PLINK, GEMMA, Popcorn  

<br>

**Results**:  

- The majority of European CVD/lipid loci overlap with the Japanese, Chinese, Greek-isolate, and African Ugandan populations.  
- HDL biomarker/score showed an inverse relationship with LDL biomarker score; LDL and Triglycerides had a linear relationship, except for in the Ugandan population where triglyceride score did not correlate with biomarker score.  
- The two Greek-isolate populations showed near perfect heritability and trans-ethnic correlation with the UK population, same as the Japanese and Chinese population with the East Asian population.  


**Project Highlights**:  

- Opportunity to work as as a Visiting Scientist at the [Wellcome Sanger Institute](https://www.sanger.ac.uk/)  
- Second-author publication in [Nature Communications](https://doi.org/10.1038/s41467-019-12026-7)  
- PRSs available on EMBL-EBI’s [PGS Catalog](http://www.pgscatalog.org/publication/PGP000046/)  
- First comparison study of its kind: Lipid phenotype (lipid blood levels) was found to be associated with lipid genotype (PRS)   

***  

### Undergraduate Summer Research

<br>

**Using WNT5A Expression to Characterize Development in the Human Gut**      

The [WNT genes](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2001-3-1-reviews3001) are known to participate in genetic pathways involved in cell patterning, signalling, and proliferation during development. WNT5A in particular is invloved in a number of [syndromes](https://www.genecards.org/cgi-bin/carddisp.pl?gene=WNT5A) which are caused by abnormal cell signalling or growth. The gut (made up of the esophagus, intestines, and anus) is one of the organs that grows and elongates the most during embryonic develpement.  

**Using immunohistochemistry, I measured the presence of the WNT5A protein the human embryonic gut at [Carnegie Stage 20 (~50 days post conception)](https://embryology.med.unsw.edu.au/embryology/index.php/Carnegie_stage_20).**  

<br>  

**Project Highlights**:  

- Received the UK-wide competitive [Genetics Society Summer Studentship Award](https://genetics.org.uk/grants/summer-studentships/) 2016.  
- Trained in MAPaint and Amira software on Linux, which involved transferring the wet-lab protein expression results into a computer-based 3D model.  
- Expression data and results of the project  uploaded to the NIH-funded HuDSeN database under the [Human Developmental Biology Resource (HDBR)](http://hdbratlas.org/organ-systems/gi-tract/gi-models.html).  
- [Attended the Genetics Society Summer Workshop](https://genetics.org.uk/wp-content/uploads/2017/11/15027387_10211122879777688_5581119349267154163_n.jpg) to present my research and the report of the same was selected to be published in the [Genetics Society January 2017 Newsletter](https://genetics.org.uk/wp-content/uploads/2017/09/Issue-76-_-January-2017.pdf).  
- [Research poster](https://drive.google.com/file/d/1jmUJNHydDgV3-tvmsTmlrqDHbtkCfDcq/view?usp=sharing
) won awards at two separate [University competitions](https://research.ncl.ac.uk/expeditionresearchscholarships/prizewinners/2016winners/).  


***

<div class="tocify-extend-page" data-unique="tocify-extend-page" style="height: 0;"></div>


