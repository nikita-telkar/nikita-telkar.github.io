---
title: "Placental miRNome Database"
output: 
  html_document: 
    theme: flatly
    highlight: monochrome
    keep_md: yes 
    # toc: true  
    # toc_depth: 6
    # toc_float: 
    #   collapsed: true 
    #   smooth_scroll: true
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

View the R Shiny application I built displaying [microRNA expression within the human placenta](https://robinsonlab.shinyapps.io/Placental_miRNome_Expression_Database/)!  

<br>

<iframe src="https://robinsonlab.shinyapps.io/Placental_miRNome_Expression_Database/?showcase=0" width="100%" height="400px" data-external="1"></iframe>


<div class="tocify-extend-page" data-unique="tocify-extend-page" style="height: 0;"></div>


