---
layout: page
title: Frito Lays
description: Demostration of the Frito Lays
img: assets/img/frito lays.png
importance: 1
category: work
---

<!DOCTYPE html>

<html>

<head>

<meta charset="utf-8" />
<meta name="generator" content="pandoc" />
<meta http-equiv="X-UA-Compatible" content="IE=EDGE" />


<meta name="author" content="Stephanie" />

<meta name="date" content="2023-08-11" />

<title>CaseStudy2</title>

<script src="site_libs/header-attrs-2.23/header-attrs.js"></script>
<script src="site_libs/jquery-3.6.0/jquery-3.6.0.min.js"></script>
<meta name="viewport" content="width=device-width, initial-scale=1" />
<link href="site_libs/bootstrap-3.3.5/css/bootstrap.min.css" rel="stylesheet" />
<script src="site_libs/bootstrap-3.3.5/js/bootstrap.min.js"></script>
<script src="site_libs/bootstrap-3.3.5/shim/html5shiv.min.js"></script>
<script src="site_libs/bootstrap-3.3.5/shim/respond.min.js"></script>
<style>h1 {font-size: 34px;}
       h1.title {font-size: 38px;}
       h2 {font-size: 30px;}
       h3 {font-size: 24px;}
       h4 {font-size: 18px;}
       h5 {font-size: 16px;}
       h6 {font-size: 12px;}
       code {color: inherit; background-color: rgba(0, 0, 0, 0.04);}
       pre:not([class]) { background-color: white }</style>
<script src="site_libs/navigation-1.1/tabsets.js"></script>
<link href="site_libs/highlightjs-9.12.0/default.css" rel="stylesheet" />
<script src="site_libs/highlightjs-9.12.0/highlight.js"></script>

<style type="text/css">
  code{white-space: pre-wrap;}
  span.smallcaps{font-variant: small-caps;}
  span.underline{text-decoration: underline;}
  div.column{display: inline-block; vertical-align: top; width: 50%;}
  div.hanging-indent{margin-left: 1.5em; text-indent: -1.5em;}
  ul.task-list{list-style: none;}
    </style>

<style type="text/css">code{white-space: pre;}</style>
<script type="text/javascript">
if (window.hljs) {
  hljs.configure({languages: []});
  hljs.initHighlightingOnLoad();
  if (document.readyState && document.readyState === "complete") {
    window.setTimeout(function() { hljs.initHighlighting(); }, 0);
  }
}
</script>









<style type = "text/css">
.main-container {
  max-width: 940px;
  margin-left: auto;
  margin-right: auto;
}
img {
  max-width:100%;
}
.tabbed-pane {
  padding-top: 12px;
}
.html-widget {
  margin-bottom: 20px;
}
button.code-folding-btn:focus {
  outline: none;
}
summary {
  display: list-item;
}
details > summary > p:only-child {
  display: inline;
}
pre code {
  padding: 0;
}
</style>


<style type="text/css">
.dropdown-submenu {
  position: relative;
}
.dropdown-submenu>.dropdown-menu {
  top: 0;
  left: 100%;
  margin-top: -6px;
  margin-left: -1px;
  border-radius: 0 6px 6px 6px;
}
.dropdown-submenu:hover>.dropdown-menu {
  display: block;
}
.dropdown-submenu>a:after {
  display: block;
  content: " ";
  float: right;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
  border-width: 5px 0 5px 5px;
  border-left-color: #cccccc;
  margin-top: 5px;
  margin-right: -10px;
}
.dropdown-submenu:hover>a:after {
  border-left-color: #adb5bd;
}
.dropdown-submenu.pull-left {
  float: none;
}
.dropdown-submenu.pull-left>.dropdown-menu {
  left: -100%;
  margin-left: 10px;
  border-radius: 6px 0 6px 6px;
}
</style>

<script type="text/javascript">
// manage active state of menu based on current page
$(document).ready(function () {
  // active menu anchor
  href = window.location.pathname
  href = href.substr(href.lastIndexOf('/') + 1)
  if (href === "")
    href = "index.html";
  var menuAnchor = $('a[href="' + href + '"]');

  // mark the anchor link active (and if it's in a dropdown, also mark that active)
  var dropdown = menuAnchor.closest('li.dropdown');
  if (window.bootstrap) { // Bootstrap 4+
    menuAnchor.addClass('active');
    dropdown.find('> .dropdown-toggle').addClass('active');
  } else { // Bootstrap 3
    menuAnchor.parent().addClass('active');
    dropdown.addClass('active');
  }

  // Navbar adjustments
  var navHeight = $(".navbar").first().height() + 15;
  var style = document.createElement('style');
  var pt = "padding-top: " + navHeight + "px; ";
  var mt = "margin-top: -" + navHeight + "px; ";
  var css = "";
  // offset scroll position for anchor links (for fixed navbar)
  for (var i = 1; i <= 6; i++) {
    css += ".section h" + i + "{ " + pt + mt + "}\n";
  }
  style.innerHTML = "body {" + pt + "padding-bottom: 40px; }\n" + css;
  document.head.appendChild(style);
});
</script>

<!-- tabsets -->

<style type="text/css">
.tabset-dropdown > .nav-tabs {
  display: inline-table;
  max-height: 500px;
  min-height: 44px;
  overflow-y: auto;
  border: 1px solid #ddd;
  border-radius: 4px;
}

.tabset-dropdown > .nav-tabs > li.active:before, .tabset-dropdown > .nav-tabs.nav-tabs-open:before {
  content: "\e259";
  font-family: 'Glyphicons Halflings';
  display: inline-block;
  padding: 10px;
  border-right: 1px solid #ddd;
}

.tabset-dropdown > .nav-tabs.nav-tabs-open > li.active:before {
  content: "\e258";
  font-family: 'Glyphicons Halflings';
  border: none;
}

.tabset-dropdown > .nav-tabs > li.active {
  display: block;
}

.tabset-dropdown > .nav-tabs > li > a,
.tabset-dropdown > .nav-tabs > li > a:focus,
.tabset-dropdown > .nav-tabs > li > a:hover {
  border: none;
  display: inline-block;
  border-radius: 4px;
  background-color: transparent;
}

.tabset-dropdown > .nav-tabs.nav-tabs-open > li {
  display: block;
  float: none;
}

.tabset-dropdown > .nav-tabs > li {
  display: none;
}
</style>

<!-- code folding -->




</head>

<body>


<div class="container-fluid main-container">




<div class="navbar navbar-default  navbar-fixed-top" role="navigation">
  <div class="container">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-bs-toggle="collapse" data-target="#navbar" data-bs-target="#navbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <a class="navbar-brand" href="index.html"></a>
    </div>
    <div id="navbar" class="navbar-collapse collapse">
      <ul class="nav navbar-nav">
        <li>
  <a href="index.html">Home</a>
</li>
<li>
  <a href="Case_Study2.html">Frito Lays Project</a>
</li>
      </ul>
      <ul class="nav navbar-nav navbar-right">
        
      </ul>
    </div><!--/.nav-collapse -->
  </div><!--/.container -->
</div><!--/.navbar -->

<div id="header">



<h1 class="title toc-ignore">CaseStudy2</h1>
<h4 class="author">Stephanie</h4>
<h4 class="date">2023-08-11</h4>

</div>


<pre class="r"><code># Loading Data From S3 Objects Using the aws.s3 package
library(aws.s3)</code></pre>
<pre><code>## Warning: package &#39;aws.s3&#39; was built under R version 4.3.1</code></pre>
<pre class="r"><code>library(class)
library(caret)</code></pre>
<pre><code>## Warning: package &#39;caret&#39; was built under R version 4.3.1</code></pre>
<pre><code>## Loading required package: ggplot2</code></pre>
<pre><code>## Warning: package &#39;ggplot2&#39; was built under R version 4.3.1</code></pre>
<pre><code>## Loading required package: lattice</code></pre>
<pre class="r"><code>library(e1071)
library(naniar)
library(ggplot2)
library(GGally)</code></pre>
<pre><code>## Registered S3 method overwritten by &#39;GGally&#39;:
##   method from   
##   +.gg   ggplot2</code></pre>
<pre class="r"><code>library(dplyr)</code></pre>
<pre><code>## Warning: package &#39;dplyr&#39; was built under R version 4.3.1</code></pre>
<pre><code>## 
## Attaching package: &#39;dplyr&#39;</code></pre>
<pre><code>## The following objects are masked from &#39;package:stats&#39;:
## 
##     filter, lag</code></pre>
<pre><code>## The following objects are masked from &#39;package:base&#39;:
## 
##     intersect, setdiff, setequal, union</code></pre>
<pre class="r"><code>library(stringr)
library(tidyverse)</code></pre>
<pre><code>## Warning: package &#39;tidyverse&#39; was built under R version 4.3.1</code></pre>
<pre><code>## Warning: package &#39;readr&#39; was built under R version 4.3.1</code></pre>
<pre><code>## ── Attaching core tidyverse packages ──────────────────────── tidyverse 2.0.0 ──
## ✔ forcats   1.0.0     ✔ readr     2.1.4
## ✔ lubridate 1.9.2     ✔ tibble    3.2.1
## ✔ purrr     1.0.1     ✔ tidyr     1.3.0</code></pre>
<pre><code>## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
## ✖ dplyr::filter() masks stats::filter()
## ✖ dplyr::lag()    masks stats::lag()
## ✖ purrr::lift()   masks caret::lift()
## ℹ Use the conflicted package (&lt;http://conflicted.r-lib.org/&gt;) to force all conflicts to become errors</code></pre>
<pre class="r"><code>library(plotly)</code></pre>
<pre><code>## 
## Attaching package: &#39;plotly&#39;
## 
## The following object is masked from &#39;package:ggplot2&#39;:
## 
##     last_plot
## 
## The following object is masked from &#39;package:stats&#39;:
## 
##     filter
## 
## The following object is masked from &#39;package:graphics&#39;:
## 
##     layout</code></pre>
<pre class="r"><code>library(ROCit)
library(readxl)</code></pre>
<pre><code>## Warning: package &#39;readxl&#39; was built under R version 4.3.1</code></pre>
<pre class="r"><code>library(knitr)

Sys.setenv(&quot;AWS_ACCESS_KEY_ID&quot; = &quot;AKIAWFX3XJDVJTTPBKEQ&quot;,
           &quot;AWS_SECRET_ACCESS_KEY&quot; = &quot;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&quot;,
           &quot;AWS_DEFAULT_REGION&quot; = &quot;us-east-2&quot;)


#Read in CaseStudy2-data.csv
case_study&lt;- s3read_using(FUN = read.csv, 
                           bucket = &quot;ddsproject1&quot;,
                           object = &quot;CaseStudy2-data.csv&quot;)

View(case_study)
Casestudy2 &lt;- case_study

library(readr)
CaseStudy2CompSet_No_Attrition &lt;- read_csv(&quot;CaseStudy2CompSet No Attrition.csv&quot;)</code></pre>
<pre><code>## Rows: 300 Columns: 35
## ── Column specification ────────────────────────────────────────────────────────
## Delimiter: &quot;,&quot;
## chr  (8): BusinessTravel, Department, EducationField, Gender, JobRole, Marit...
## dbl (27): ID, Age, DailyRate, DistanceFromHome, Education, EmployeeCount, Em...
## 
## ℹ Use `spec()` to retrieve the full column specification for this data.
## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.</code></pre>
<pre class="r"><code>View(CaseStudy2CompSet_No_Attrition)

library(readxl)
CaseStudy2CompSet_No_Salary &lt;- read_excel(&quot;CaseStudy2CompSet No Salary.xlsx&quot;)
View(CaseStudy2CompSet_No_Salary)

#Review for any missing values
gg_miss_var(Casestudy2) + ggtitle(&quot;Missing Values in Dataset&quot;)</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-1-1.png" width="672" /></p>
<pre class="r"><code>#change multiple columns to factors
Casestudy2[c(3,4,6,9,13,17,19,23,24)] &lt;- lapply(Casestudy2[c(3,4,6,9,13,17,19,23,24)],as.factor)



# In this chunk, I graphed several ggplots to determine which fields would best determine employee attrition.

Casestudy2 %&gt;% ggplot(aes(x= JobSatisfaction, fill=JobRole)) + geom_boxplot() + ggtitle(&quot; Job Satisfation by Roles&quot;)</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-1-2.png" width="672" /></p>
<pre class="r"><code>Casestudy2 %&gt;% ggplot(aes(x= YearsAtCompany, fill=JobRole)) + geom_boxplot() + xlab(&quot;Years at Company&quot;)+ ggtitle(&quot; Years at the Company by Roles&quot;)</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-1-3.png" width="672" /></p>
<pre class="r"><code>#Plot Numbner Roles worked within companies
Casestudy2 %&gt;% ggplot(aes(x= NumCompaniesWorked  , fill=JobRole)) + geom_boxplot() + ggtitle(&quot;Number of Companies Worked by Roles&quot;)</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-1-4.png" width="672" /></p>
<pre class="r"><code>Casestudy2 %&gt;% ggplot(aes(x= YearsAtCompany  , fill=JobRole)) + geom_boxplot() + ggtitle(&quot;Number of Years Worked by Roles&quot;)</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-1-5.png" width="672" /></p>
<pre class="r"><code>Casestudy2 %&gt;% ggplot()+
  geom_point(aes(x=NumCompaniesWorked ,y =YearsInCurrentRole ,color = Attrition),alpha = 0.7,position = &#39;jitter&#39;)+
  ggtitle(&#39;Number of Companies Worked vs Years in Current Role&#39;)+
    scale_color_manual(values=c(&quot;Green&quot;,&quot;Red&quot;))</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-1-6.png" width="672" /></p>
<pre class="r"><code>Casestudy2 %&gt;% ggplot()+
 geom_point(aes(x=JobLevel ,y =YearsInCurrentRole ,color = Attrition),alpha = 0.7,position = &#39;jitter&#39;)+
 ggtitle(&#39;Number of Companies Worked vs Years in Current Role&#39;)+
 scale_color_manual(values=c(&quot;Green&quot;,&quot;Red&quot;))</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-1-7.png" width="672" /></p>
<pre class="r"><code>Casestudy2 %&gt;% ggplot()+
     geom_boxplot(aes(x=YearsInCurrentRole, y=JobLevel, fill=Attrition), alpha=0.7)+
     ggtitle(&quot;Attrition by Job Satisfaction&quot;)</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-1-8.png" width="672" /></p>
<pre class="r"><code>Casestudy2 %&gt;%  select(Attrition,YearsAtCompany,MonthlyIncome,JobLevel) %&gt;% ggpairs(aes(color = Attrition))</code></pre>
<pre><code>## `stat_bin()` using `bins = 30`. Pick better value with `binwidth`.
## `stat_bin()` using `bins = 30`. Pick better value with `binwidth`.
## `stat_bin()` using `bins = 30`. Pick better value with `binwidth`.</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-1-9.png" width="672" /></p>
<pre class="r"><code>Casestudy2 %&gt;% ggplot(aes(x= JobSatisfaction, fill=Gender)) + geom_boxplot() + ggtitle(&quot; Job Satisfation by Gender&quot;)</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-1-10.png" width="672" /></p>
<pre class="r"><code>#Plotting Attrition by Years at company
Casestudy2 %&gt;% ggplot(aes(x = YearsAtCompany, fill = Attrition)) + geom_bar() + ggtitle(&quot;Distribution of YearsAtCompany and Attrition&quot;) + ylab(&quot;Attrition&quot;)</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-1-11.png" width="672" /></p>
<pre class="r"><code>#Plotting Attrition by JobLevel
Casestudy2 %&gt;% ggplot(aes(x = JobLevel, fill = Attrition)) + geom_bar() + ggtitle(&quot;Distribution of JobLevel and Attrition&quot;) + ylab(&quot;Attrition&quot;)</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-1-12.png" width="672" /></p>
<pre class="r"><code>#Plotting Attrition by years at current role.
ggplot(data=Casestudy2, aes(YearsInCurrentRole)) +
     geom_bar(aes(fill=Attrition), position=&quot;fill&quot;) +
     ggtitle(&#39;Percentage of Attrition based on Years in Current Role&#39;)</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-1-13.png" width="672" /></p>
<pre class="r"><code>#Two spikes, one after about 2 years and one at 10 years with a close 6 years.
ggplot(Casestudy2, aes(x=TotalWorkingYears)) + geom_bar(aes(fill=Attrition)) + ggtitle(&quot;Attrition vs. Total Working Year&quot;, subtitle = &quot;Attrition Overview&quot; )</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-1-14.png" width="672" /></p>
<pre class="r"><code>#The bar graph does suggest that there is more attrition in the age around 30, with a median age of 33 years.
Casestudy2 %&gt;%  ggplot(aes(x = Age, fill = Attrition)) + geom_bar() + ggtitle(&quot;Distribution of Age and Attrition&quot;) + ylab(&quot;Attrition&quot;)</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-1-15.png" width="672" /></p>
<pre class="r"><code>Casestudy2 %&gt;% filter(Attrition == &quot;Yes&quot;) %&gt;% ggplot(aes(x = Age, fill = Attrition)) + geom_bar() + ggtitle(&quot;Distribution of Age and Attrition&quot;) + ylab(&quot;Attrition&quot;)</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-1-16.png" width="672" /></p>
<pre class="r"><code>#Plot Percentage Attrition by JobLevel filled by years at company
Casestudy2 %&gt;% group_by(StockOptionLevel, JobLevel, Attrition) %&gt;% summarise(JRCount = n()) %&gt;% group_by(JobLevel) %&gt;% mutate(PA = JRCount/sum(JRCount)) %&gt;% filter(Attrition == &quot;Yes&quot;) %&gt;% ggplot(aes(x = JobLevel, y = PA,fill = StockOptionLevel)) + geom_bar(stat=&quot;identity&quot;) + ggtitle(&quot;Distribution of JobLevel by  Attrition&quot;) + ylab(&quot;Attrition&quot;) + xlab(&quot;JobLevel&quot;)</code></pre>
<pre><code>## `summarise()` has grouped output by &#39;StockOptionLevel&#39;, &#39;JobLevel&#39;. You can
## override using the `.groups` argument.</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-1-17.png" width="672" /></p>
<pre class="r"><code>#Top 3 Attrition Reason
#From the Attrition Analysis in previous 2 sections - Age, Job Level, Monthly Income, and  Years at Company were identified as important inputs for Attrition.I ran numerous models with knn and NB selecting the 3 variables at a time. The best model that I got was using Naive Bayes model with inputs Age, Job level , and Years at company(which was changed to Factor).

Casestudy2 %&gt;% ggplot(aes(x= JobLevel, fill=Attrition)) + geom_histogram() + ggtitle(&quot;Histogram of Job Level by Attrition&quot;)</code></pre>
<pre><code>## `stat_bin()` using `bins = 30`. Pick better value with `binwidth`.</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-2-1.png" width="672" /></p>
<pre class="r"><code>Casestudy2 %&gt;% ggplot(aes(x= MonthlyIncome, fill=Attrition)) + geom_histogram() + ggtitle(&quot;Histogram of Monthly Income by Attrition&quot;)</code></pre>
<pre><code>## `stat_bin()` using `bins = 30`. Pick better value with `binwidth`.</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-2-2.png" width="672" /></p>
<pre class="r"><code>Casestudy2 %&gt;% ggplot(aes(x= Age, fill=Attrition)) + geom_histogram() + ggtitle(&quot;Histogram of Age by Attrition&quot;)</code></pre>
<pre><code>## `stat_bin()` using `bins = 30`. Pick better value with `binwidth`.</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-2-3.png" width="672" /></p>
<pre class="r"><code>Casestudy2 %&gt;% ggplot(aes(x= YearsAtCompany, fill=Attrition)) + geom_histogram() + ggtitle(&quot;Histogram of Years at Company by Attrition&quot;)</code></pre>
<pre><code>## `stat_bin()` using `bins = 30`. Pick better value with `binwidth`.</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-2-4.png" width="672" /></p>
<pre class="r"><code>newdata &lt;- Casestudy2 %&gt;% select(c(2,3:9,12:22,26:27,29:36)) 
dataatt &lt;- newdata %&gt;% group_by(Attrition)

# Creating dataset with &quot;Yes&quot; and &quot;No&quot; Attrition
datayes &lt;- Casestudy2 %&gt;% filter(Attrition ==&quot;Yes&quot;)
datano &lt;- Casestudy2 %&gt;% filter(Attrition ==&quot;No&quot;)

# NaiveBayes Model with Age(2), Job level(16), YearsAtCompany(33)
AccHolder = numeric(50)
SensHolder = numeric(50)
SpecHolder = numeric(50)

for (seed in 1:50)
{
set.seed(seed)
trainIndices_yes = sample(seq(1:140),115)
trainIndices_no = sample(seq(1:730),555)
trainAttrition = rbind(datayes[trainIndices_yes,] , datano[trainIndices_no,])
testAttrition = rbind(datayes[-trainIndices_yes,], datano[-trainIndices_no,])
model = naiveBayes(trainAttrition[,c(2,16,33)],trainAttrition$Attrition)
CM = confusionMatrix(table(testAttrition$Attrition, predict(model,testAttrition[,c(2,16,33)])))
AccHolder[seed] = CM$overall[1]
SensHolder[seed] = CM$byClass[1]
SpecHolder[seed] = CM$byClass[2]
}

CM</code></pre>
<pre><code>## Confusion Matrix and Statistics
## 
##      
##        No Yes
##   No  174   1
##   Yes  23   2
##                                           
##                Accuracy : 0.88            
##                  95% CI : (0.8267, 0.9216)
##     No Information Rate : 0.985           
##     P-Value [Acc &gt; NIR] : 1               
##                                           
##                   Kappa : 0.1193          
##                                           
##  Mcnemar&#39;s Test P-Value : 1.814e-05       
##                                           
##             Sensitivity : 0.8832          
##             Specificity : 0.6667          
##          Pos Pred Value : 0.9943          
##          Neg Pred Value : 0.0800          
##              Prevalence : 0.9850          
##          Detection Rate : 0.8700          
##    Detection Prevalence : 0.8750          
##       Balanced Accuracy : 0.7750          
##                                           
##        &#39;Positive&#39; Class : No              
## </code></pre>
<pre class="r"><code>mean(AccHolder) # Mean Accuracy = 0.88</code></pre>
<pre><code>## [1] 0.8766</code></pre>
<pre class="r"><code>#Standard Error of the Mean
sd(AccHolder)/sqrt(50) </code></pre>
<pre><code>## [1] 0.001190438</code></pre>
<pre class="r"><code>mean(SensHolder) # Mean Sensitivity = 0.88</code></pre>
<pre><code>## [1] 0.8813156</code></pre>
<pre class="r"><code>#Standard Error of the Mean
sd(SensHolder)/sqrt(50) </code></pre>
<pre><code>## [1] 0.0006977996</code></pre>
<pre class="r"><code>mean(SpecHolder,na.rm = TRUE) # Mean Specificity = 1</code></pre>
<pre><code>## [1] 0.6259788</code></pre>
<pre class="r"><code>#Standard Error of the Mean
sd(SensHolder)/sqrt(50)</code></pre>
<pre><code>## [1] 0.0006977996</code></pre>
<pre class="r"><code>### Best Model to Predict Attrition
# NaiveBayes Model with Age(2),Job level(16), YearsAtCompany (33), and monthly Income (20) to check if the model is stable.
AccHolder = numeric(50)
SensHolder = numeric(50)
SpecHolder = numeric(50)

for (seed in 1:50)
{
set.seed(seed)
trainIndices_yes = sample(seq(1:140),112)
trainIndices_no = sample(seq(1:730),584)
trainAttrition = rbind(datayes[trainIndices_yes,] , datano[trainIndices_no,])
testAttrition = rbind(datayes[-trainIndices_yes,], datano[-trainIndices_no,])
model = naiveBayes(trainAttrition[,c(2,16,20,33)],trainAttrition$Attrition)
CM = confusionMatrix(table(testAttrition$Attrition, predict(model,testAttrition[,c(2,16,20,33)])))
AccHolder[seed] = CM$overall[1]
SensHolder[seed] = CM$byClass[1]
SpecHolder[seed] = CM$byClass[2]
}

mean(AccHolder) # Mean Accuracy </code></pre>
<pre><code>## [1] 0.8382759</code></pre>
<pre class="r"><code>mean(SensHolder) # Mean Sensitivity </code></pre>
<pre><code>## [1] 0.8550768</code></pre>
<pre class="r"><code>mean(SpecHolder,na.rm = TRUE) # Mean Specificity </code></pre>
<pre><code>## [1] 0.5472527</code></pre>
<pre class="r"><code>AccHolder</code></pre>
<pre><code>##  [1] 0.8333333 0.8620690 0.8275862 0.8563218 0.7988506 0.8390805 0.8275862
##  [8] 0.8448276 0.8218391 0.8390805 0.8448276 0.8448276 0.8563218 0.8448276
## [15] 0.8045977 0.8333333 0.8390805 0.8505747 0.8103448 0.8448276 0.8505747
## [22] 0.8333333 0.8390805 0.8448276 0.8563218 0.8333333 0.7873563 0.8390805
## [29] 0.8390805 0.8505747 0.8390805 0.8275862 0.8333333 0.8333333 0.8275862
## [36] 0.8275862 0.8218391 0.8390805 0.8505747 0.8448276 0.8333333 0.8563218
## [43] 0.8448276 0.8333333 0.8620690 0.8505747 0.8390805 0.8678161 0.8333333
## [50] 0.8505747</code></pre>
<pre class="r"><code>SensHolder</code></pre>
<pre><code>##  [1] 0.8502994 0.8588235 0.8536585 0.8579882 0.8404908 0.8734177 0.8452381
##  [8] 0.8650307 0.8662420 0.8430233 0.8606061 0.8520710 0.8538012 0.8479532
## [15] 0.8544304 0.8679245 0.8511905 0.8614458 0.8466258 0.8520710 0.8571429
## [22] 0.8588957 0.8597561 0.8479532 0.8538012 0.8679245 0.8609272 0.8554217
## [29] 0.8470588 0.8529412 0.8511905 0.8670886 0.8461538 0.8545455 0.8536585
## [36] 0.8493976 0.8571429 0.8554217 0.8529412 0.8650307 0.8502994 0.8579882
## [43] 0.8562874 0.8381503 0.8588235 0.8529412 0.8554217 0.8639053 0.8461538
## [50] 0.8571429</code></pre>
<pre class="r"><code>SpecHolder</code></pre>
<pre><code>##  [1] 0.4285714 1.0000000 0.4000000 0.8000000 0.1818182 0.5000000 0.3333333
##  [8] 0.5454545 0.4117647 0.5000000 0.5555556 0.6000000 1.0000000 0.6666667
## [15] 0.3125000 0.4666667 0.5000000 0.6250000 0.2727273 0.6000000 0.6666667
## [22] 0.4545455 0.5000000 0.6666667 1.0000000 0.4666667 0.3043478 0.5000000
## [29] 0.5000000 0.7500000 0.5000000 0.4375000 0.4000000 0.4444444 0.4000000
## [36] 0.3750000 0.3846154 0.5000000 0.7500000 0.5454545 0.4285714 0.8000000
## [43] 0.5714286 0.0000000 1.0000000 0.7500000 0.5000000 1.0000000 0.4000000
## [50] 0.6666667</code></pre>
<pre class="r"><code># Best prediction model
set.seed(9)
trainIndices_yes = sample(seq(1:140),112)
trainIndices_no = sample(seq(1:730),584)
trainAttrition = rbind(datayes[trainIndices_yes,] , datano[trainIndices_no,])
testAttrition = rbind(datayes[-trainIndices_yes,], datano[-trainIndices_no,])
model = naiveBayes(trainAttrition[,c(2,16,20,33)],trainAttrition$Attrition)
CM = confusionMatrix(table(testAttrition$Attrition, predict(model,testAttrition[,c(2,16,20,33)])))
model</code></pre>
<pre><code>## 
## Naive Bayes Classifier for Discrete Predictors
## 
## Call:
## naiveBayes.default(x = trainAttrition[, c(2, 16, 20, 33)], y = trainAttrition$Attrition)
## 
## A-priori probabilities:
## trainAttrition$Attrition
##        No       Yes 
## 0.8390805 0.1609195 
## 
## Conditional probabilities:
##                         Age
## trainAttrition$Attrition     [,1]     [,2]
##                      No  37.52397 8.570729
##                      Yes 33.43750 9.032256
## 
##                         JobLevel
## trainAttrition$Attrition     [,1]     [,2]
##                      No  2.142123 1.112230
##                      Yes 1.642857 1.003212
## 
##                         MonthlyIncome
## trainAttrition$Attrition     [,1]     [,2]
##                      No  6804.099 4761.912
##                      Yes 4838.009 3906.460
## 
##                         YearsAtCompany
## trainAttrition$Attrition     [,1]     [,2]
##                      No  7.491438 6.108223
##                      Yes 5.285714 5.692462</code></pre>
<pre class="r"><code>CM</code></pre>
<pre><code>## Confusion Matrix and Statistics
## 
##      
##        No Yes
##   No  136  10
##   Yes  21   7
##                                           
##                Accuracy : 0.8218          
##                  95% CI : (0.7568, 0.8756)
##     No Information Rate : 0.9023          
##     P-Value [Acc &gt; NIR] : 0.99964         
##                                           
##                   Kappa : 0.2158          
##                                           
##  Mcnemar&#39;s Test P-Value : 0.07249         
##                                           
##             Sensitivity : 0.8662          
##             Specificity : 0.4118          
##          Pos Pred Value : 0.9315          
##          Neg Pred Value : 0.2500          
##              Prevalence : 0.9023          
##          Detection Rate : 0.7816          
##    Detection Prevalence : 0.8391          
##       Balanced Accuracy : 0.6390          
##                                           
##        &#39;Positive&#39; Class : No              
## </code></pre>
<pre class="r"><code># Accuracy = 0.8218
# Sensitivity = 0.8662
# Specificity = 0.4118</code></pre>
<pre class="r"><code># Data modification for No Attrition Dataset

head(CaseStudy2CompSet_No_Attrition)</code></pre>
<pre><code>## # A tibble: 6 × 35
##      ID   Age BusinessTravel    DailyRate Department  DistanceFromHome Education
##   &lt;dbl&gt; &lt;dbl&gt; &lt;chr&gt;                 &lt;dbl&gt; &lt;chr&gt;                  &lt;dbl&gt;     &lt;dbl&gt;
## 1  1171    35 Travel_Rarely           750 Research &amp;…               28         3
## 2  1172    33 Travel_Rarely           147 Human Reso…                2         3
## 3  1173    26 Travel_Rarely          1330 Research &amp;…               21         3
## 4  1174    55 Travel_Rarely          1311 Research &amp;…                2         3
## 5  1175    29 Travel_Rarely          1246 Sales                     19         3
## 6  1176    51 Travel_Frequently      1456 Research &amp;…                1         4
## # ℹ 28 more variables: EducationField &lt;chr&gt;, EmployeeCount &lt;dbl&gt;,
## #   EmployeeNumber &lt;dbl&gt;, EnvironmentSatisfaction &lt;dbl&gt;, Gender &lt;chr&gt;,
## #   HourlyRate &lt;dbl&gt;, JobInvolvement &lt;dbl&gt;, JobLevel &lt;dbl&gt;, JobRole &lt;chr&gt;,
## #   JobSatisfaction &lt;dbl&gt;, MaritalStatus &lt;chr&gt;, MonthlyIncome &lt;dbl&gt;,
## #   MonthlyRate &lt;dbl&gt;, NumCompaniesWorked &lt;dbl&gt;, Over18 &lt;chr&gt;, OverTime &lt;chr&gt;,
## #   PercentSalaryHike &lt;dbl&gt;, PerformanceRating &lt;dbl&gt;,
## #   RelationshipSatisfaction &lt;dbl&gt;, StandardHours &lt;dbl&gt;, …</code></pre>
<pre class="r"><code>CaseStudy2CompSet_No_Attrition$SalaryFactor = cut(CaseStudy2CompSet_No_Attrition$MonthlyIncome, breaks = c(1080,3000,6000,12000,25000),labels = c(&quot;&lt;3k&quot;,&quot;3k to 6k&quot;,&quot;6k to 12k&quot;,&quot;&gt;12k&quot;))

CaseStudy2CompSet_No_Attrition$BusinessTravel = as.factor(CaseStudy2CompSet_No_Attrition$BusinessTravel)

CaseStudy2CompSet_No_Attrition$JobLevelFactor = as.factor(CaseStudy2CompSet_No_Attrition$JobLevel)

CaseStudy2CompSet_No_Attrition$WorkYearFactor = cut(CaseStudy2CompSet_No_Attrition$TotalWorkingYears, breaks = c(-1,11,21,40),labels = c(&quot;1&quot;,&quot;2&quot;,&quot;3&quot;))

CaseStudy2CompSet_No_Attrition$YearsWithCurrManagerFactor  = cut(CaseStudy2CompSet_No_Attrition$YearsWithCurrManager, breaks = c(-1,5,10,17),labels = c(&quot;Low&quot;,&quot;Med&quot;,&quot;High&quot;))

CaseStudy2CompSet_No_Attrition$Age = as.factor(CaseStudy2CompSet_No_Attrition$Age)

#Prediction of Attrition for No Attrition Data
CaseStudy2CompSet_No_Attrition$NBPrediction = predict(model,CaseStudy2CompSet_No_Attrition[,c(2,16,20,33)])</code></pre>
<pre><code>## Warning in predict.naiveBayes(model, CaseStudy2CompSet_No_Attrition[, c(2, :
## Type mismatch between training and new data for variable &#39;Age&#39;. Did you use
## factors with numeric labels for training, and numeric values for new data?</code></pre>
<pre><code>## Warning in predict.naiveBayes(model, CaseStudy2CompSet_No_Attrition[, c(2, :
## Type mismatch between training and new data for variable &#39;JobLevel&#39;. Did you
## use factors with numeric labels for training, and numeric values for new data?</code></pre>
<pre><code>## Warning in predict.naiveBayes(model, CaseStudy2CompSet_No_Attrition[, c(2, :
## Type mismatch between training and new data for variable &#39;MonthlyIncome&#39;. Did
## you use factors with numeric labels for training, and numeric values for new
## data?</code></pre>
<pre><code>## Warning in predict.naiveBayes(model, CaseStudy2CompSet_No_Attrition[, c(2, :
## Type mismatch between training and new data for variable &#39;YearsAtCompany&#39;. Did
## you use factors with numeric labels for training, and numeric values for new
## data?</code></pre>
<pre class="r"><code># Viewing the Prediction
CaseStudy2CompSet_No_Attrition$NBPrediction</code></pre>
<pre><code>##   [1] No No No No No No No No No No No No No No No No No No No No No No No No No
##  [26] No No No No No No No No No No No No No No No No No No No No No No No No No
##  [51] No No No No No No No No No No No No No No No No No No No No No No No No No
##  [76] No No No No No No No No No No No No No No No No No No No No No No No No No
## [101] No No No No No No No No No No No No No No No No No No No No No No No No No
## [126] No No No No No No No No No No No No No No No No No No No No No No No No No
## [151] No No No No No No No No No No No No No No No No No No No No No No No No No
## [176] No No No No No No No No No No No No No No No No No No No No No No No No No
## [201] No No No No No No No No No No No No No No No No No No No No No No No No No
## [226] No No No No No No No No No No No No No No No No No No No No No No No No No
## [251] No No No No No No No No No No No No No No No No No No No No No No No No No
## [276] No No No No No No No No No No No No No No No No No No No No No No No No No
## Levels: No Yes</code></pre>
<pre class="r"><code>#writing csv file for submission
write.csv(CaseStudy2CompSet_No_Attrition,file = &#39;C:\\Users\\Steph\\OneDrive\\Documents\\MSDS_6306_Doing-Data-Science\\Unit 14 and 15 Case Study 2/Case2PredictionsAttrition.csv&#39;)</code></pre>
<pre class="r"><code>###Salary analysis

Casestudy2 %&gt;% ggplot(aes(x= Age, y=MonthlyIncome)) + geom_point() + ggtitle(&quot;Monthly Income by Age&quot;) + geom_smooth(method = &quot;lm&quot;) </code></pre>
<pre><code>## `geom_smooth()` using formula = &#39;y ~ x&#39;</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-5-1.png" width="672" /></p>
<pre class="r"><code>Casestudy2 %&gt;% ggplot(aes(x= JobLevel, y=MonthlyIncome)) + geom_point() + ggtitle(&quot; Monthly Income by Job Level&quot;) + geom_smooth(method = &quot;lm&quot;) </code></pre>
<pre><code>## `geom_smooth()` using formula = &#39;y ~ x&#39;</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-5-2.png" width="672" /></p>
<pre class="r"><code>cor(case_study$JobLevel, case_study$MonthlyIncome)</code></pre>
<pre><code>## [1] 0.95164</code></pre>
<pre class="r"><code>Casestudy2 %&gt;% ggplot(aes(x= YearsAtCompany, y=MonthlyIncome)) + geom_point() + ggtitle(&quot; Monthly Income by Years at Company&quot;) + geom_smooth(method = &quot;lm&quot;) </code></pre>
<pre><code>## `geom_smooth()` using formula = &#39;y ~ x&#39;</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-5-3.png" width="672" /></p>
<pre class="r"><code>### Salary Models

# Model 1 with Job level
fit1 = lm(MonthlyIncome~JobLevel, data = Casestudy2)
summary(fit1)</code></pre>
<pre><code>## 
## Call:
## lm(formula = MonthlyIncome ~ JobLevel, data = Casestudy2)
## 
## Residuals:
##     Min      1Q  Median      3Q     Max 
## -5037.1  -928.2    80.1   697.1  3723.6 
## 
## Coefficients:
##             Estimate Std. Error t value Pr(&gt;|t|)    
## (Intercept) -1793.93     101.68  -17.64   &lt;2e-16 ***
## JobLevel     4013.67      43.98   91.26   &lt;2e-16 ***
## ---
## Signif. codes:  0 &#39;***&#39; 0.001 &#39;**&#39; 0.01 &#39;*&#39; 0.05 &#39;.&#39; 0.1 &#39; &#39; 1
## 
## Residual standard error: 1413 on 868 degrees of freedom
## Multiple R-squared:  0.9056, Adjusted R-squared:  0.9055 
## F-statistic:  8329 on 1 and 868 DF,  p-value: &lt; 2.2e-16</code></pre>
<pre class="r"><code>confint(fit1)</code></pre>
<pre><code>##                 2.5 %    97.5 %
## (Intercept) -1993.494 -1594.375
## JobLevel     3927.352  4099.990</code></pre>
<pre class="r"><code>fit1_Preds = predict(fit1, newdata = Casestudy2)
as.data.frame(fit1_Preds)</code></pre>
<pre><code>##     fit1_Preds
## 1     6233.408
## 2    18274.422
## 3    10247.080
## 4    10247.080
## 5     2219.737
## 6    10247.080
## 7     2219.737
## 8     6233.408
## 9     2219.737
## 10    6233.408
## 11   18274.422
## 12    2219.737
## 13   10247.080
## 14    2219.737
## 15    2219.737
## 16    6233.408
## 17    6233.408
## 18    6233.408
## 19    2219.737
## 20    6233.408
## 21    6233.408
## 22    6233.408
## 23    6233.408
## 24    6233.408
## 25    6233.408
## 26   18274.422
## 27    6233.408
## 28    6233.408
## 29   10247.080
## 30    2219.737
## 31    6233.408
## 32    2219.737
## 33   14260.751
## 34    2219.737
## 35    6233.408
## 36    2219.737
## 37   10247.080
## 38    6233.408
## 39   18274.422
## 40    2219.737
## 41   14260.751
## 42    6233.408
## 43    2219.737
## 44   18274.422
## 45    2219.737
## 46    2219.737
## 47    6233.408
## 48   10247.080
## 49    2219.737
## 50    2219.737
## 51    2219.737
## 52   18274.422
## 53    2219.737
## 54    6233.408
## 55    6233.408
## 56    2219.737
## 57    2219.737
## 58    2219.737
## 59   10247.080
## 60    2219.737
## 61   10247.080
## 62   10247.080
## 63    2219.737
## 64    2219.737
## 65    2219.737
## 66    2219.737
## 67    6233.408
## 68    2219.737
## 69    2219.737
## 70    2219.737
## 71    2219.737
## 72    6233.408
## 73    6233.408
## 74    2219.737
## 75   10247.080
## 76    6233.408
## 77   10247.080
## 78   14260.751
## 79   10247.080
## 80    2219.737
## 81    6233.408
## 82    6233.408
## 83    6233.408
## 84    6233.408
## 85    6233.408
## 86   14260.751
## 87    6233.408
## 88    2219.737
## 89   10247.080
## 90   18274.422
## 91    2219.737
## 92   10247.080
## 93    2219.737
## 94    6233.408
## 95   18274.422
## 96    6233.408
## 97   14260.751
## 98    6233.408
## 99    2219.737
## 100   2219.737
## 101   2219.737
## 102  10247.080
## 103   6233.408
## 104   2219.737
## 105  14260.751
## 106   2219.737
## 107   6233.408
## 108  18274.422
## 109   6233.408
## 110   2219.737
## 111   2219.737
## 112  14260.751
## 113  10247.080
## 114   6233.408
## 115   6233.408
## 116  10247.080
## 117   6233.408
## 118   6233.408
## 119   2219.737
## 120   6233.408
## 121  10247.080
## 122   2219.737
## 123  10247.080
## 124   6233.408
## 125   6233.408
## 126   6233.408
## 127   2219.737
## 128   6233.408
## 129   6233.408
## 130  14260.751
## 131   6233.408
## 132   6233.408
## 133   6233.408
## 134   6233.408
## 135   6233.408
## 136   6233.408
## 137   2219.737
## 138  10247.080
## 139   2219.737
## 140  10247.080
## 141  14260.751
## 142   2219.737
## 143  10247.080
## 144   6233.408
## 145   6233.408
## 146   6233.408
## 147   2219.737
## 148   6233.408
## 149   2219.737
## 150   6233.408
## 151   6233.408
## 152   6233.408
## 153   6233.408
## 154   6233.408
## 155   2219.737
## 156   6233.408
## 157   6233.408
## 158  14260.751
## 159  10247.080
## 160  10247.080
## 161   6233.408
## 162  10247.080
## 163   6233.408
## 164   6233.408
## 165  10247.080
## 166   2219.737
## 167  14260.751
## 168  14260.751
## 169   6233.408
## 170   2219.737
## 171   6233.408
## 172   6233.408
## 173  10247.080
## 174  10247.080
## 175  14260.751
## 176   2219.737
## 177  18274.422
## 178   2219.737
## 179  10247.080
## 180   6233.408
## 181  10247.080
## 182   6233.408
## 183   2219.737
## 184  10247.080
## 185   2219.737
## 186   2219.737
## 187   6233.408
## 188  14260.751
## 189  18274.422
## 190   6233.408
## 191   6233.408
## 192  10247.080
## 193   6233.408
## 194   6233.408
## 195   2219.737
## 196   2219.737
## 197   2219.737
## 198  14260.751
## 199  10247.080
## 200   2219.737
## 201  14260.751
## 202   6233.408
## 203   6233.408
## 204   2219.737
## 205   2219.737
## 206   2219.737
## 207   6233.408
## 208   6233.408
## 209   2219.737
## 210  10247.080
## 211  14260.751
## 212  18274.422
## 213   2219.737
## 214   6233.408
## 215   2219.737
## 216   2219.737
## 217   6233.408
## 218  14260.751
## 219   2219.737
## 220   2219.737
## 221   6233.408
## 222   6233.408
## 223   6233.408
## 224   2219.737
## 225   2219.737
## 226   2219.737
## 227   2219.737
## 228   2219.737
## 229   6233.408
## 230  14260.751
## 231   6233.408
## 232   2219.737
## 233  14260.751
## 234   6233.408
## 235  14260.751
## 236  10247.080
## 237  18274.422
## 238   6233.408
## 239   2219.737
## 240  10247.080
## 241  10247.080
## 242  18274.422
## 243   2219.737
## 244   2219.737
## 245   6233.408
## 246   2219.737
## 247  10247.080
## 248   2219.737
## 249   6233.408
## 250  14260.751
## 251   2219.737
## 252   6233.408
## 253   2219.737
## 254   2219.737
## 255  10247.080
## 256   2219.737
## 257   2219.737
## 258   6233.408
## 259  10247.080
## 260   2219.737
## 261   2219.737
## 262   2219.737
## 263   2219.737
## 264   2219.737
## 265   2219.737
## 266   2219.737
## 267  14260.751
## 268   2219.737
## 269   6233.408
## 270   6233.408
## 271   6233.408
## 272   6233.408
## 273   6233.408
## 274   6233.408
## 275  18274.422
## 276  18274.422
## 277   2219.737
## 278   2219.737
## 279   6233.408
## 280   6233.408
## 281   6233.408
## 282   2219.737
## 283   6233.408
## 284   6233.408
## 285   2219.737
## 286   6233.408
## 287   2219.737
## 288   2219.737
## 289  10247.080
## 290   2219.737
## 291   2219.737
## 292   6233.408
## 293   2219.737
## 294  10247.080
## 295  14260.751
## 296   2219.737
## 297   6233.408
## 298   6233.408
## 299   2219.737
## 300   2219.737
## 301   6233.408
## 302  10247.080
## 303   2219.737
## 304   6233.408
## 305   2219.737
## 306   2219.737
## 307   2219.737
## 308   2219.737
## 309   6233.408
## 310   6233.408
## 311   6233.408
## 312  14260.751
## 313   2219.737
## 314   6233.408
## 315   6233.408
## 316   6233.408
## 317   2219.737
## 318   6233.408
## 319   6233.408
## 320   2219.737
## 321   2219.737
## 322   2219.737
## 323   2219.737
## 324   6233.408
## 325  14260.751
## 326   2219.737
## 327  18274.422
## 328   6233.408
## 329   6233.408
## 330  14260.751
## 331  14260.751
## 332  10247.080
## 333   2219.737
## 334  10247.080
## 335  18274.422
## 336   6233.408
## 337   6233.408
## 338   6233.408
## 339   6233.408
## 340   2219.737
## 341   2219.737
## 342   2219.737
## 343  10247.080
## 344   2219.737
## 345   6233.408
## 346  14260.751
## 347   6233.408
## 348   6233.408
## 349   2219.737
## 350  14260.751
## 351  10247.080
## 352   6233.408
## 353   6233.408
## 354   6233.408
## 355  10247.080
## 356   6233.408
## 357   2219.737
## 358   2219.737
## 359   6233.408
## 360   2219.737
## 361  18274.422
## 362   2219.737
## 363  18274.422
## 364  18274.422
## 365  18274.422
## 366  14260.751
## 367   6233.408
## 368   6233.408
## 369   2219.737
## 370   6233.408
## 371   6233.408
## 372  10247.080
## 373  10247.080
## 374   2219.737
## 375   2219.737
## 376  14260.751
## 377   2219.737
## 378   6233.408
## 379   2219.737
## 380   2219.737
## 381  18274.422
## 382   2219.737
## 383   6233.408
## 384   2219.737
## 385   2219.737
## 386  10247.080
## 387  10247.080
## 388   6233.408
## 389   6233.408
## 390   2219.737
## 391   6233.408
## 392   6233.408
## 393   2219.737
## 394  10247.080
## 395   2219.737
## 396   2219.737
## 397  14260.751
## 398   2219.737
## 399   6233.408
## 400  10247.080
## 401   6233.408
## 402   6233.408
## 403   2219.737
## 404  10247.080
## 405   2219.737
## 406  14260.751
## 407   6233.408
## 408   2219.737
## 409  14260.751
## 410  14260.751
## 411   2219.737
## 412  10247.080
## 413   2219.737
## 414   6233.408
## 415   2219.737
## 416   6233.408
## 417   2219.737
## 418   2219.737
## 419   6233.408
## 420  10247.080
## 421   6233.408
## 422   6233.408
## 423   6233.408
## 424   2219.737
## 425   6233.408
## 426  10247.080
## 427   2219.737
## 428   2219.737
## 429   2219.737
## 430   6233.408
## 431   6233.408
## 432   2219.737
## 433   6233.408
## 434   2219.737
## 435  10247.080
## 436   6233.408
## 437   2219.737
## 438   2219.737
## 439   2219.737
## 440   6233.408
## 441   6233.408
## 442   2219.737
## 443   2219.737
## 444   2219.737
## 445  18274.422
## 446   2219.737
## 447   6233.408
## 448   6233.408
## 449   6233.408
## 450   6233.408
## 451   6233.408
## 452   2219.737
## 453   6233.408
## 454   6233.408
## 455  14260.751
## 456  18274.422
## 457   6233.408
## 458   6233.408
## 459   2219.737
## 460   6233.408
## 461   2219.737
## 462   2219.737
## 463  10247.080
## 464   6233.408
## 465   2219.737
## 466   2219.737
## 467   2219.737
## 468   2219.737
## 469   6233.408
## 470   6233.408
## 471   2219.737
## 472   2219.737
## 473  10247.080
## 474   2219.737
## 475   2219.737
## 476   6233.408
## 477   6233.408
## 478   6233.408
## 479   2219.737
## 480  10247.080
## 481   6233.408
## 482   2219.737
## 483   6233.408
## 484   2219.737
## 485  10247.080
## 486   6233.408
## 487   2219.737
## 488   2219.737
## 489  10247.080
## 490   6233.408
## 491  18274.422
## 492  14260.751
## 493   6233.408
## 494  10247.080
## 495   6233.408
## 496  14260.751
## 497   2219.737
## 498   2219.737
## 499   6233.408
## 500   6233.408
## 501  10247.080
## 502   2219.737
## 503   2219.737
## 504  10247.080
## 505  14260.751
## 506   6233.408
## 507   2219.737
## 508  10247.080
## 509   2219.737
## 510  18274.422
## 511   6233.408
## 512  10247.080
## 513   2219.737
## 514  10247.080
## 515   2219.737
## 516   6233.408
## 517   2219.737
## 518   2219.737
## 519   6233.408
## 520   2219.737
## 521   2219.737
## 522   2219.737
## 523  10247.080
## 524  18274.422
## 525   2219.737
## 526  10247.080
## 527   6233.408
## 528   6233.408
## 529   2219.737
## 530   2219.737
## 531  10247.080
## 532   6233.408
## 533   2219.737
## 534   6233.408
## 535   2219.737
## 536   2219.737
## 537  10247.080
## 538   2219.737
## 539   2219.737
## 540   6233.408
## 541   6233.408
## 542   2219.737
## 543   2219.737
## 544   6233.408
## 545   2219.737
## 546   2219.737
## 547  10247.080
## 548   6233.408
## 549  10247.080
## 550   2219.737
## 551  18274.422
## 552   2219.737
## 553   6233.408
## 554   2219.737
## 555   6233.408
## 556   6233.408
## 557   6233.408
## 558   2219.737
## 559   6233.408
## 560   6233.408
## 561   2219.737
## 562  14260.751
## 563   2219.737
## 564  10247.080
## 565   2219.737
## 566   2219.737
## 567   6233.408
## 568   6233.408
## 569   6233.408
## 570  14260.751
## 571   6233.408
## 572   2219.737
## 573   6233.408
## 574   6233.408
## 575   6233.408
## 576   6233.408
## 577   2219.737
## 578   2219.737
## 579   6233.408
## 580   6233.408
## 581   2219.737
## 582  14260.751
## 583   6233.408
## 584   6233.408
## 585   6233.408
## 586   6233.408
## 587   6233.408
## 588   2219.737
## 589   2219.737
## 590   2219.737
## 591   2219.737
## 592   6233.408
## 593   2219.737
## 594   2219.737
## 595  10247.080
## 596   6233.408
## 597  10247.080
## 598   6233.408
## 599   6233.408
## 600   2219.737
## 601   2219.737
## 602   6233.408
## 603  10247.080
## 604   2219.737
## 605   2219.737
## 606  14260.751
## 607   6233.408
## 608   6233.408
## 609   2219.737
## 610   2219.737
## 611   6233.408
## 612   6233.408
## 613   2219.737
## 614   2219.737
## 615  10247.080
## 616   6233.408
## 617   2219.737
## 618   6233.408
## 619  10247.080
## 620   2219.737
## 621   2219.737
## 622   6233.408
## 623   2219.737
## 624  10247.080
## 625   2219.737
## 626   2219.737
## 627   6233.408
## 628  10247.080
## 629  10247.080
## 630  10247.080
## 631   2219.737
## 632  10247.080
## 633   6233.408
## 634   2219.737
## 635  10247.080
## 636   2219.737
## 637  14260.751
## 638  10247.080
## 639   2219.737
## 640   2219.737
## 641   2219.737
## 642   6233.408
## 643  14260.751
## 644   2219.737
## 645   2219.737
## 646  10247.080
## 647   2219.737
## 648   2219.737
## 649   6233.408
## 650   2219.737
## 651   2219.737
## 652   6233.408
## 653  10247.080
## 654  10247.080
## 655   2219.737
## 656   6233.408
## 657  10247.080
## 658  14260.751
## 659   6233.408
## 660   6233.408
## 661   6233.408
## 662   2219.737
## 663  10247.080
## 664   2219.737
## 665   6233.408
## 666   6233.408
## 667  10247.080
## 668   2219.737
## 669   6233.408
## 670  14260.751
## 671  10247.080
## 672   6233.408
## 673   6233.408
## 674   2219.737
## 675   2219.737
## 676  18274.422
## 677   6233.408
## 678   6233.408
## 679   6233.408
## 680   2219.737
## 681   6233.408
## 682   2219.737
## 683   6233.408
## 684  10247.080
## 685   2219.737
## 686  10247.080
## 687  10247.080
## 688   2219.737
## 689   2219.737
## 690   2219.737
## 691   6233.408
## 692  10247.080
## 693   6233.408
## 694   2219.737
## 695   6233.408
## 696   2219.737
## 697  14260.751
## 698   6233.408
## 699   2219.737
## 700  18274.422
## 701   2219.737
## 702   6233.408
## 703  10247.080
## 704   2219.737
## 705   2219.737
## 706   6233.408
## 707   6233.408
## 708   2219.737
## 709   2219.737
## 710  14260.751
## 711  10247.080
## 712  14260.751
## 713   2219.737
## 714  10247.080
## 715  10247.080
## 716   2219.737
## 717   6233.408
## 718   6233.408
## 719   6233.408
## 720  10247.080
## 721  10247.080
## 722   6233.408
## 723   2219.737
## 724  10247.080
## 725   2219.737
## 726   6233.408
## 727   2219.737
## 728   2219.737
## 729   2219.737
## 730   2219.737
## 731   6233.408
## 732   6233.408
## 733   2219.737
## 734   6233.408
## 735   2219.737
## 736   6233.408
## 737  14260.751
## 738   6233.408
## 739   6233.408
## 740   6233.408
## 741   6233.408
## 742  10247.080
## 743   6233.408
## 744   2219.737
## 745   6233.408
## 746   2219.737
## 747   2219.737
## 748   6233.408
## 749   2219.737
## 750   2219.737
## 751   2219.737
## 752   2219.737
## 753  14260.751
## 754  10247.080
## 755  10247.080
## 756   2219.737
## 757   6233.408
## 758   6233.408
## 759   2219.737
## 760  18274.422
## 761   2219.737
## 762  14260.751
## 763   6233.408
## 764   6233.408
## 765   2219.737
## 766   6233.408
## 767   2219.737
## 768  10247.080
## 769   6233.408
## 770   6233.408
## 771   6233.408
## 772  10247.080
## 773  10247.080
## 774   2219.737
## 775  10247.080
## 776   2219.737
## 777   2219.737
## 778   2219.737
## 779   2219.737
## 780   2219.737
## 781   2219.737
## 782   6233.408
## 783   2219.737
## 784   6233.408
## 785   6233.408
## 786  14260.751
## 787  10247.080
## 788   6233.408
## 789  18274.422
## 790   2219.737
## 791   6233.408
## 792   2219.737
## 793  10247.080
## 794  10247.080
## 795   6233.408
## 796   2219.737
## 797  14260.751
## 798   2219.737
## 799   2219.737
## 800   6233.408
## 801   6233.408
## 802   6233.408
## 803  14260.751
## 804  10247.080
## 805   6233.408
## 806  10247.080
## 807   6233.408
## 808   2219.737
## 809   2219.737
## 810   2219.737
## 811   6233.408
## 812   2219.737
## 813   6233.408
## 814  18274.422
## 815   2219.737
## 816   2219.737
## 817   6233.408
## 818  10247.080
## 819   2219.737
## 820   6233.408
## 821   2219.737
## 822   6233.408
## 823   6233.408
## 824   2219.737
## 825   6233.408
## 826  18274.422
## 827  10247.080
## 828   6233.408
## 829   2219.737
## 830  18274.422
## 831   6233.408
## 832   2219.737
## 833   2219.737
## 834   2219.737
## 835  14260.751
## 836  10247.080
## 837   2219.737
## 838   6233.408
## 839  10247.080
## 840  18274.422
## 841   2219.737
## 842  10247.080
## 843  14260.751
## 844  10247.080
## 845   6233.408
## 846   6233.408
## 847   2219.737
## 848  10247.080
## 849   6233.408
## 850   2219.737
## 851   6233.408
## 852   2219.737
## 853   6233.408
## 854   6233.408
## 855   6233.408
## 856   2219.737
## 857   2219.737
## 858  10247.080
## 859   2219.737
## 860  10247.080
## 861   2219.737
## 862  10247.080
## 863   6233.408
## 864  14260.751
## 865  10247.080
## 866  10247.080
## 867   6233.408
## 868   6233.408
## 869   2219.737
## 870   6233.408</code></pre>
<pre class="r"><code>plot(density(fit1_Preds),main = &quot;Model 1 Residual with Job Level&quot;)</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-5-4.png" width="672" /></p>
<pre class="r"><code>RMSE1 = sqrt(mean((Casestudy2$MonthlyIncome - fit1_Preds)^2))
RMSE1= 1411.67

# Model 2 with Age
fit2 = lm(MonthlyIncome~Age, data = Casestudy2)
summary(fit2)</code></pre>
<pre><code>## 
## Call:
## lm(formula = MonthlyIncome ~ Age, data = Casestudy2)
## 
## Residuals:
##     Min      1Q  Median      3Q     Max 
## -9744.0 -2622.7  -643.3  1968.7 12651.7 
## 
## Coefficients:
##             Estimate Std. Error t value Pr(&gt;|t|)    
## (Intercept)  -2796.8      579.6  -4.825 1.65e-06 ***
## Age            249.4       15.3  16.308  &lt; 2e-16 ***
## ---
## Signif. codes:  0 &#39;***&#39; 0.001 &#39;**&#39; 0.01 &#39;*&#39; 0.05 &#39;.&#39; 0.1 &#39; &#39; 1
## 
## Residual standard error: 4025 on 868 degrees of freedom
## Multiple R-squared:  0.2345, Adjusted R-squared:  0.2337 
## F-statistic:   266 on 1 and 868 DF,  p-value: &lt; 2.2e-16</code></pre>
<pre class="r"><code>confint(fit2)</code></pre>
<pre><code>##                  2.5 %     97.5 %
## (Intercept) -3934.4502 -1659.1417
## Age           219.4314   279.4758</code></pre>
<pre class="r"><code>fit2_Preds = predict(fit2, newdata = Casestudy2)
as.data.frame(fit2_Preds)</code></pre>
<pre><code>##     fit2_Preds
## 1     5185.719
## 2     7181.348
## 3     5934.080
## 4     5185.719
## 5     3190.090
## 6     3938.451
## 7     7430.801
## 8     6432.987
## 9     5684.626
## 10    5684.626
## 11    7929.708
## 12    4187.905
## 13    5934.080
## 14    4686.812
## 15    8678.069
## 16    4936.265
## 17    5185.719
## 18    8678.069
## 19    5684.626
## 20    8179.162
## 21    6183.533
## 22    9176.976
## 23    7929.708
## 24    4936.265
## 25    5435.173
## 26    8179.162
## 27    6682.440
## 28    5435.173
## 29   10424.244
## 30   10174.791
## 31    5185.719
## 32    5435.173
## 33    8678.069
## 34    5934.080
## 35    5185.719
## 36    5185.719
## 37    5934.080
## 38    6183.533
## 39   11172.605
## 40    4936.265
## 41   11671.512
## 42    8428.616
## 43    9426.430
## 44    7680.255
## 45    2940.637
## 46    7680.255
## 47    5185.719
## 48    6682.440
## 49    1693.369
## 50    3938.451
## 51    6682.440
## 52   11671.512
## 53    8179.162
## 54    8428.616
## 55    4936.265
## 56    7430.801
## 57    7680.255
## 58    4437.358
## 59    6432.987
## 60    3439.544
## 61    6183.533
## 62    6183.533
## 63    4936.265
## 64    1693.369
## 65    3190.090
## 66    5185.719
## 67    5934.080
## 68    2940.637
## 69    5934.080
## 70    6432.987
## 71    7430.801
## 72    4187.905
## 73    5934.080
## 74    7430.801
## 75   10174.791
## 76    4686.812
## 77    5684.626
## 78    8678.069
## 79    8428.616
## 80    4936.265
## 81    6432.987
## 82    5934.080
## 83    6682.440
## 84    6432.987
## 85    6183.533
## 86   11920.966
## 87    8927.523
## 88    5934.080
## 89    3938.451
## 90    8678.069
## 91    6682.440
## 92    4437.358
## 93    6432.987
## 94    5934.080
## 95    9675.884
## 96    7680.255
## 97    8678.069
## 98    6432.987
## 99    4437.358
## 100   5684.626
## 101   3938.451
## 102   4936.265
## 103   5684.626
## 104   2940.637
## 105  10424.244
## 106   3688.997
## 107   4437.358
## 108  10923.151
## 109   8678.069
## 110   5185.719
## 111   4187.905
## 112  10174.791
## 113  10174.791
## 114   5934.080
## 115   5934.080
## 116   6432.987
## 117   3439.544
## 118   4437.358
## 119   7430.801
## 120   5684.626
## 121   6183.533
## 122   2441.729
## 123   8428.616
## 124   6682.440
## 125   4437.358
## 126   5934.080
## 127   5185.719
## 128   8428.616
## 129   7929.708
## 130   8678.069
## 131   4437.358
## 132   9426.430
## 133   7680.255
## 134   6931.894
## 135   7929.708
## 136   7181.348
## 137   4437.358
## 138  10673.698
## 139   6931.894
## 140   6432.987
## 141  11172.605
## 142  11671.512
## 143   8678.069
## 144   6432.987
## 145   7181.348
## 146   4437.358
## 147   5435.173
## 148   5435.173
## 149   3190.090
## 150   4187.905
## 151   4936.265
## 152   5185.719
## 153   5185.719
## 154   7430.801
## 155   5684.626
## 156   4686.812
## 157   7181.348
## 158   6931.894
## 159   7929.708
## 160   7680.255
## 161   4686.812
## 162   4187.905
## 163   5435.173
## 164   7680.255
## 165   5934.080
## 166   2192.276
## 167   9426.430
## 168   5435.173
## 169  10174.791
## 170   4437.358
## 171   4686.812
## 172   8927.523
## 173   8678.069
## 174   5435.173
## 175  10424.244
## 176   2441.729
## 177  10923.151
## 178   3688.997
## 179   5185.719
## 180   6682.440
## 181   5934.080
## 182   6682.440
## 183   7929.708
## 184   6931.894
## 185   6931.894
## 186   4187.905
## 187   3439.544
## 188   8927.523
## 189   9675.884
## 190   4187.905
## 191   4686.812
## 192   4936.265
## 193   8678.069
## 194   9176.976
## 195   3688.997
## 196   9925.337
## 197   9925.337
## 198   9426.430
## 199   8179.162
## 200   3190.090
## 201   7181.348
## 202   5185.719
## 203   5185.719
## 204   4187.905
## 205   5185.719
## 206   8179.162
## 207   7929.708
## 208   6682.440
## 209   4686.812
## 210   7430.801
## 211   7430.801
## 212   7680.255
## 213   6432.987
## 214   7680.255
## 215   3938.451
## 216   7181.348
## 217   6682.440
## 218   9176.976
## 219   4686.812
## 220   3688.997
## 221   5684.626
## 222   8428.616
## 223   5435.173
## 224   4187.905
## 225   6682.440
## 226   4686.812
## 227   5934.080
## 228   2691.183
## 229   3190.090
## 230   9426.430
## 231   8428.616
## 232   5934.080
## 233   8927.523
## 234  10673.698
## 235   7929.708
## 236   6432.987
## 237   7680.255
## 238   5185.719
## 239   3439.544
## 240   9675.884
## 241   7680.255
## 242   8428.616
## 243   4437.358
## 244   3439.544
## 245   4437.358
## 246   4437.358
## 247   4936.265
## 248   5185.719
## 249   7430.801
## 250   7430.801
## 251   5435.173
## 252   6183.533
## 253   8428.616
## 254   4936.265
## 255   7181.348
## 256   7929.708
## 257   4936.265
## 258   4686.812
## 259   5684.626
## 260   3439.544
## 261   4936.265
## 262   4437.358
## 263   5435.173
## 264   4437.358
## 265   3190.090
## 266   5934.080
## 267   5684.626
## 268   5185.719
## 269   5435.173
## 270   4686.812
## 271   8428.616
## 272   5684.626
## 273   3938.451
## 274   6183.533
## 275  10923.151
## 276  11172.605
## 277   2691.183
## 278   7929.708
## 279   3439.544
## 280  10923.151
## 281   7929.708
## 282   7430.801
## 283   7181.348
## 284   4936.265
## 285   6682.440
## 286   5435.173
## 287   2691.183
## 288   5684.626
## 289   6183.533
## 290   5934.080
## 291   8428.616
## 292   6183.533
## 293   3938.451
## 294   8927.523
## 295   7181.348
## 296   5934.080
## 297   5684.626
## 298   5684.626
## 299   4936.265
## 300   4187.905
## 301   5185.719
## 302   5934.080
## 303  10923.151
## 304   5934.080
## 305  11671.512
## 306   3190.090
## 307   9675.884
## 308   5684.626
## 309  10923.151
## 310   3439.544
## 311   5684.626
## 312   7181.348
## 313   4936.265
## 314   9925.337
## 315  12170.419
## 316   8927.523
## 317   5684.626
## 318   3190.090
## 319   6931.894
## 320   1942.822
## 321   5185.719
## 322   5684.626
## 323   4686.812
## 324   8678.069
## 325   6931.894
## 326   3938.451
## 327   8179.162
## 328   7680.255
## 329   6682.440
## 330   7680.255
## 331   9426.430
## 332   5185.719
## 333   8179.162
## 334   3938.451
## 335  11920.966
## 336   5435.173
## 337   5934.080
## 338   5684.626
## 339   9675.884
## 340   3938.451
## 341   6183.533
## 342   4187.905
## 343   5435.173
## 344   4686.812
## 345   4686.812
## 346   6931.894
## 347   5684.626
## 348   3688.997
## 349   8179.162
## 350  11172.605
## 351   7680.255
## 352   4936.265
## 353   7181.348
## 354   7181.348
## 355   7430.801
## 356   5684.626
## 357   3688.997
## 358   4437.358
## 359   5185.719
## 360   6183.533
## 361  10174.791
## 362   4437.358
## 363  10174.791
## 364   7181.348
## 365  10923.151
## 366  11172.605
## 367   5684.626
## 368   7181.348
## 369   2940.637
## 370   5185.719
## 371   4936.265
## 372   4686.812
## 373   8428.616
## 374   6432.987
## 375   2192.276
## 376   9675.884
## 377   6183.533
## 378   7680.255
## 379   4437.358
## 380   4686.812
## 381   8927.523
## 382   3688.997
## 383   9176.976
## 384   2940.637
## 385   9925.337
## 386   6682.440
## 387   5934.080
## 388   4437.358
## 389   6183.533
## 390   2441.729
## 391   5684.626
## 392   3688.997
## 393   4936.265
## 394  12170.419
## 395   7680.255
## 396   4936.265
## 397   8678.069
## 398   5684.626
## 399  11172.605
## 400   8179.162
## 401   4686.812
## 402   7680.255
## 403   8927.523
## 404   6183.533
## 405   5934.080
## 406   7929.708
## 407   4936.265
## 408   6183.533
## 409  10424.244
## 410   7929.708
## 411   6183.533
## 412   7430.801
## 413   6432.987
## 414   5185.719
## 415   5684.626
## 416   5934.080
## 417   4686.812
## 418   6183.533
## 419   6432.987
## 420   4437.358
## 421   5684.626
## 422   6432.987
## 423   4936.265
## 424   1693.369
## 425   4187.905
## 426   7929.708
## 427   4686.812
## 428   2441.729
## 429   5185.719
## 430   5684.626
## 431   3938.451
## 432   7181.348
## 433   9426.430
## 434   4437.358
## 435   7181.348
## 436   3938.451
## 437   4187.905
## 438   3688.997
## 439   9675.884
## 440   6682.440
## 441   5185.719
## 442   4437.358
## 443   4187.905
## 444   8179.162
## 445   8678.069
## 446   8927.523
## 447   6682.440
## 448   7680.255
## 449   6682.440
## 450   8428.616
## 451   5435.173
## 452   8179.162
## 453   5934.080
## 454   5435.173
## 455   9176.976
## 456   7181.348
## 457   4936.265
## 458   9925.337
## 459  11172.605
## 460   6183.533
## 461   7680.255
## 462   6183.533
## 463   9675.884
## 464   4936.265
## 465   7929.708
## 466   6682.440
## 467   6183.533
## 468   6183.533
## 469   3688.997
## 470  10424.244
## 471   3938.451
## 472   4437.358
## 473   8428.616
## 474   8428.616
## 475   4187.905
## 476   8678.069
## 477   6432.987
## 478   3688.997
## 479  10174.791
## 480   6432.987
## 481   4437.358
## 482   4936.265
## 483   5684.626
## 484  11172.605
## 485  11671.512
## 486   7430.801
## 487   4686.812
## 488   4936.265
## 489   9176.976
## 490   5684.626
## 491   9426.430
## 492   9675.884
## 493   4437.358
## 494   5934.080
## 495   6183.533
## 496   9925.337
## 497   8428.616
## 498   6432.987
## 499   6183.533
## 500   6931.894
## 501  11671.512
## 502   4187.905
## 503   9176.976
## 504   4437.358
## 505   8927.523
## 506   5185.719
## 507   5435.173
## 508   9925.337
## 509   6432.987
## 510   7430.801
## 511   6682.440
## 512   6931.894
## 513   5185.719
## 514   5435.173
## 515   2441.729
## 516   9925.337
## 517   3439.544
## 518   7680.255
## 519   4686.812
## 520  11172.605
## 521   5684.626
## 522   4187.905
## 523   8428.616
## 524   9426.430
## 525  11920.966
## 526  10424.244
## 527   8428.616
## 528   4936.265
## 529   5934.080
## 530  11172.605
## 531   6682.440
## 532   6183.533
## 533   4437.358
## 534   5185.719
## 535   4437.358
## 536   7929.708
## 537   6682.440
## 538   7680.255
## 539   3190.090
## 540   7680.255
## 541   4686.812
## 542   5435.173
## 543   3938.451
## 544   6682.440
## 545   5684.626
## 546   5684.626
## 547   9426.430
## 548   7181.348
## 549   6682.440
## 550   8428.616
## 551   7430.801
## 552   4187.905
## 553   6183.533
## 554   9176.976
## 555   7181.348
## 556   6432.987
## 557  10673.698
## 558   5684.626
## 559   7680.255
## 560   3688.997
## 561   6183.533
## 562  11671.512
## 563   3938.451
## 564   4936.265
## 565   4686.812
## 566   8179.162
## 567   5185.719
## 568   4686.812
## 569   7680.255
## 570   9675.884
## 571   7430.801
## 572   2441.729
## 573   4187.905
## 574   5684.626
## 575   3688.997
## 576   6432.987
## 577   6682.440
## 578   8179.162
## 579   6931.894
## 580   4437.358
## 581   3439.544
## 582   7680.255
## 583   6682.440
## 584   4187.905
## 585   8179.162
## 586   7181.348
## 587   6682.440
## 588   6183.533
## 589   6432.987
## 590   5934.080
## 591   2691.183
## 592   5684.626
## 593   4187.905
## 594   9426.430
## 595   7181.348
## 596   5435.173
## 597   5934.080
## 598   7181.348
## 599   3938.451
## 600   3190.090
## 601   3190.090
## 602   5185.719
## 603   4686.812
## 604   4437.358
## 605   4437.358
## 606  10424.244
## 607  11920.966
## 608   6682.440
## 609   3688.997
## 610   5435.173
## 611   5934.080
## 612   7430.801
## 613   5435.173
## 614   1942.822
## 615   4686.812
## 616   5684.626
## 617   5435.173
## 618   8179.162
## 619   6931.894
## 620   5934.080
## 621   2192.276
## 622   8927.523
## 623   5684.626
## 624   5934.080
## 625   4187.905
## 626   3938.451
## 627   3190.090
## 628   6682.440
## 629  10923.151
## 630   5684.626
## 631  10923.151
## 632   5684.626
## 633   6682.440
## 634   6183.533
## 635   7929.708
## 636   5934.080
## 637   7680.255
## 638   5684.626
## 639   3190.090
## 640   3938.451
## 641   4686.812
## 642   7181.348
## 643  10923.151
## 644   5684.626
## 645   7430.801
## 646   7181.348
## 647   1693.369
## 648   3688.997
## 649   5934.080
## 650   7181.348
## 651   5934.080
## 652  12170.419
## 653   7181.348
## 654   9176.976
## 655   2691.183
## 656   3688.997
## 657   9925.337
## 658  10673.698
## 659   7430.801
## 660   6183.533
## 661   5185.719
## 662   5684.626
## 663   8678.069
## 664   5934.080
## 665   5684.626
## 666   4437.358
## 667   4437.358
## 668   5435.173
## 669   5185.719
## 670  10673.698
## 671   6432.987
## 672   5435.173
## 673   4187.905
## 674   5934.080
## 675   3938.451
## 676   8678.069
## 677   6183.533
## 678   7181.348
## 679   6183.533
## 680   4936.265
## 681   3439.544
## 682   7929.708
## 683   6183.533
## 684  11422.059
## 685   4187.905
## 686   4936.265
## 687   4437.358
## 688   5435.173
## 689   1942.822
## 690   6682.440
## 691   6682.440
## 692   8927.523
## 693   7680.255
## 694   4686.812
## 695   6432.987
## 696   8927.523
## 697   9176.976
## 698   6183.533
## 699   1693.369
## 700   8678.069
## 701   4437.358
## 702   5684.626
## 703   5934.080
## 704   3688.997
## 705  11920.966
## 706   7430.801
## 707  10673.698
## 708   4936.265
## 709   6682.440
## 710   9675.884
## 711   4686.812
## 712  11422.059
## 713   9176.976
## 714   6183.533
## 715   6183.533
## 716   3190.090
## 717   4686.812
## 718   4187.905
## 719   5934.080
## 720   4187.905
## 721   6432.987
## 722   6432.987
## 723   5684.626
## 724   6183.533
## 725   7680.255
## 726   3439.544
## 727   6432.987
## 728   5684.626
## 729   3688.997
## 730   2691.183
## 731   7929.708
## 732   6931.894
## 733   3938.451
## 734   5185.719
## 735   5684.626
## 736   3938.451
## 737   6931.894
## 738  11920.966
## 739   5934.080
## 740   5934.080
## 741   3439.544
## 742   4936.265
## 743   6432.987
## 744   2940.637
## 745   3439.544
## 746   3190.090
## 747   4437.358
## 748   5684.626
## 749   3190.090
## 750   5435.173
## 751   2192.276
## 752   4936.265
## 753   9675.884
## 754   8678.069
## 755  10673.698
## 756   8179.162
## 757   5934.080
## 758   9426.430
## 759   6682.440
## 760   8428.616
## 761   4437.358
## 762   8927.523
## 763   7430.801
## 764   9675.884
## 765   5684.626
## 766   8428.616
## 767   7430.801
## 768   7181.348
## 769   8678.069
## 770   8428.616
## 771   5435.173
## 772   8678.069
## 773   6931.894
## 774   6183.533
## 775   7680.255
## 776   2940.637
## 777   4686.812
## 778   5185.719
## 779   3688.997
## 780   4437.358
## 781   7430.801
## 782   6931.894
## 783   5435.173
## 784   5435.173
## 785   8927.523
## 786   4936.265
## 787   9925.337
## 788  10174.791
## 789  10923.151
## 790   3439.544
## 791   9426.430
## 792   5684.626
## 793   6682.440
## 794   6183.533
## 795   9426.430
## 796   5435.173
## 797   8428.616
## 798   2691.183
## 799   1942.822
## 800   6183.533
## 801   5435.173
## 802   4936.265
## 803   6931.894
## 804   5934.080
## 805   8179.162
## 806   6183.533
## 807   3439.544
## 808   2691.183
## 809   4686.812
## 810   3938.451
## 811   4686.812
## 812   3439.544
## 813   3190.090
## 814   8927.523
## 815   6682.440
## 816   5435.173
## 817   4686.812
## 818   5435.173
## 819   4686.812
## 820   4187.905
## 821   5185.719
## 822   4437.358
## 823   5684.626
## 824   4936.265
## 825   6183.533
## 826   8678.069
## 827   4936.265
## 828   5684.626
## 829   6682.440
## 830   9675.884
## 831   8428.616
## 832   1942.822
## 833   4187.905
## 834   1942.822
## 835  10923.151
## 836   6432.987
## 837   6432.987
## 838   5684.626
## 839   8927.523
## 840   9176.976
## 841   1693.369
## 842   4437.358
## 843  10174.791
## 844   5684.626
## 845   5684.626
## 846   4187.905
## 847   1942.822
## 848   6931.894
## 849   7181.348
## 850   3688.997
## 851   4936.265
## 852   4686.812
## 853   4437.358
## 854   4187.905
## 855   5934.080
## 856   5934.080
## 857   4686.812
## 858   4936.265
## 859   7430.801
## 860   8179.162
## 861   9925.337
## 862   7929.708
## 863   5684.626
## 864   8927.523
## 865   8428.616
## 866   9176.976
## 867   5185.719
## 868   8927.523
## 869   8428.616
## 870   5934.080</code></pre>
<pre class="r"><code>plot(density(fit2_Preds),main = &quot;Model 2 Residual with Age&quot;)</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-5-5.png" width="672" /></p>
<pre class="r"><code>RMSE2 = sqrt(mean((Casestudy2$MonthlyIncome - fit2_Preds)^2))
RMSE2= 4020.251

# Model 3 combined JobLevel and Age
fit3 = lm(MonthlyIncome~JobLevel + Age, data = Casestudy2)
summary(fit3)</code></pre>
<pre><code>## 
## Call:
## lm(formula = MonthlyIncome ~ JobLevel + Age, data = Casestudy2)
## 
## Residuals:
##     Min      1Q  Median      3Q     Max 
## -5119.6  -954.7    67.4   734.7  3848.8 
## 
## Coefficients:
##              Estimate Std. Error t value Pr(&gt;|t|)    
## (Intercept) -2334.680    202.630  -11.52  &lt; 2e-16 ***
## JobLevel     3940.027     49.871   79.00  &lt; 2e-16 ***
## Age            18.760      6.091    3.08  0.00213 ** 
## ---
## Signif. codes:  0 &#39;***&#39; 0.001 &#39;**&#39; 0.01 &#39;*&#39; 0.05 &#39;.&#39; 0.1 &#39; &#39; 1
## 
## Residual standard error: 1406 on 867 degrees of freedom
## Multiple R-squared:  0.9066, Adjusted R-squared:  0.9064 
## F-statistic:  4210 on 2 and 867 DF,  p-value: &lt; 2.2e-16</code></pre>
<pre class="r"><code>confint(fit3)</code></pre>
<pre><code>##                    2.5 %      97.5 %
## (Intercept) -2732.383300 -1936.97659
## JobLevel     3842.144503  4037.90964
## Age             6.805894    30.71438</code></pre>
<pre class="r"><code>fit3_Preds = predict(fit3, newdata = Casestudy2)
as.data.frame(fit3_Preds)</code></pre>
<pre><code>##     fit3_Preds
## 1     6145.699
## 2    18115.861
## 3    10142.006
## 4    10085.726
## 5     2055.590
## 6     9991.925
## 7     2374.513
## 8     6239.499
## 9     2243.192
## 10    6183.219
## 11   18172.141
## 12    2130.631
## 13   10142.006
## 14    2168.151
## 15    2468.313
## 16    6126.938
## 17    6145.699
## 18    6408.340
## 19    2243.192
## 20    6370.820
## 21    6220.739
## 22    6445.861
## 23    6352.060
## 24    6126.938
## 25    6164.459
## 26   18190.901
## 27    6258.259
## 28    6164.459
## 29   10479.688
## 30    2580.874
## 31    6145.699
## 32    2224.432
## 33   14288.395
## 34    2261.952
## 35    6145.699
## 36    2205.671
## 37   10142.006
## 38    6220.739
## 39   18416.023
## 40    2186.911
## 41   14513.516
## 42    6389.580
## 43    2524.594
## 44   18153.381
## 45    2036.830
## 46    2393.273
## 47    6145.699
## 48   10198.286
## 49    1943.030
## 50    2111.871
## 51    2318.232
## 52   18453.543
## 53    2430.793
## 54    6389.580
## 55    6126.938
## 56    2374.513
## 57    2393.273
## 58    2149.391
## 59   10179.526
## 60    2074.351
## 61   10160.766
## 62   10160.766
## 63    2186.911
## 64    1943.030
## 65    2055.590
## 66    2205.671
## 67    6201.979
## 68    2036.830
## 69    2261.952
## 70    2299.472
## 71    2374.513
## 72    6070.658
## 73    6201.979
## 74    2374.513
## 75   10460.928
## 76    6108.178
## 77   10123.246
## 78   14288.395
## 79   10329.607
## 80    2186.911
## 81    6239.499
## 82    6201.979
## 83    6258.259
## 84    6239.499
## 85    6220.739
## 86   14532.276
## 87    6427.101
## 88    2261.952
## 89    9991.925
## 90   18228.422
## 91    2318.232
## 92   10029.445
## 93    2299.472
## 94    6201.979
## 95   18303.462
## 96    6333.300
## 97   14288.395
## 98    6239.499
## 99    2149.391
## 100   2243.192
## 101   2111.871
## 102  10066.965
## 103   6183.219
## 104   2036.830
## 105  14419.716
## 106   2093.111
## 107   6089.418
## 108  18397.263
## 109   6408.340
## 110   2205.671
## 111   2130.631
## 112  14400.955
## 113  10460.928
## 114   6201.979
## 115   6201.979
## 116  10179.526
## 117   6014.378
## 118   6089.418
## 119   2374.513
## 120   6183.219
## 121  10160.766
## 122   1999.310
## 123  10329.607
## 124   6258.259
## 125   6089.418
## 126   6201.979
## 127   2205.671
## 128   6389.580
## 129   6352.060
## 130  14288.395
## 131   6089.418
## 132   6464.621
## 133   6333.300
## 134   6277.020
## 135   6352.060
## 136   6295.780
## 137   2149.391
## 138  10498.449
## 139   2336.992
## 140  10179.526
## 141  14475.996
## 142   2693.435
## 143  10348.368
## 144   6239.499
## 145   6295.780
## 146   6089.418
## 147   2224.432
## 148   6164.459
## 149   2055.590
## 150   6070.658
## 151   6126.938
## 152   6145.699
## 153   6145.699
## 154   6314.540
## 155   2243.192
## 156   6108.178
## 157   6295.780
## 158  14157.074
## 159  10292.087
## 160  10273.327
## 161   6108.178
## 162  10010.685
## 163   6164.459
## 164   6333.300
## 165  10142.006
## 166   1980.550
## 167  14344.675
## 168  14044.513
## 169   6520.901
## 170   2149.391
## 171   6108.178
## 172   6427.101
## 173  10348.368
## 174  10104.486
## 175  14419.716
## 176   1999.310
## 177  18397.263
## 178   2093.111
## 179  10085.726
## 180   6258.259
## 181  10142.006
## 182   6258.259
## 183   2412.033
## 184  10217.047
## 185   2336.992
## 186   2130.631
## 187   6014.378
## 188  14307.155
## 189  18303.462
## 190   6070.658
## 191   6108.178
## 192  10066.965
## 193   6408.340
## 194   6445.861
## 195   2093.111
## 196   2562.114
## 197   2562.114
## 198  14344.675
## 199  10310.847
## 200   2055.590
## 201  14175.834
## 202   6145.699
## 203   6145.699
## 204   2130.631
## 205   2205.671
## 206   2430.793
## 207   6352.060
## 208   6258.259
## 209   2168.151
## 210  10254.567
## 211  14194.594
## 212  18153.381
## 213   2299.472
## 214   6333.300
## 215   2111.871
## 216   2355.753
## 217   6258.259
## 218  14325.915
## 219   2168.151
## 220   2093.111
## 221   6183.219
## 222   6389.580
## 223   6164.459
## 224   2130.631
## 225   2318.232
## 226   2168.151
## 227   2261.952
## 228   2018.070
## 229   5995.617
## 230  14344.675
## 231   6389.580
## 232   2261.952
## 233  14307.155
## 234   6558.422
## 235  14232.114
## 236  10179.526
## 237  18153.381
## 238   6145.699
## 239   2074.351
## 240  10423.408
## 241  10273.327
## 242  18209.662
## 243   2149.391
## 244   2074.351
## 245   6089.418
## 246   2149.391
## 247  10066.965
## 248   2205.671
## 249   6314.540
## 250  14194.594
## 251   2224.432
## 252   6220.739
## 253   2449.553
## 254   2186.911
## 255  10235.807
## 256   2412.033
## 257   2186.911
## 258   6108.178
## 259  10123.246
## 260   2074.351
## 261   2186.911
## 262   2149.391
## 263   2224.432
## 264   2149.391
## 265   2055.590
## 266   2261.952
## 267  14063.273
## 268   2205.671
## 269   6164.459
## 270   6108.178
## 271   6389.580
## 272   6183.219
## 273   6051.898
## 274   6220.739
## 275  18397.263
## 276  18416.023
## 277   2018.070
## 278   2412.033
## 279   6014.378
## 280   6577.182
## 281   6352.060
## 282   2374.513
## 283   6295.780
## 284   6126.938
## 285   2318.232
## 286   6164.459
## 287   2018.070
## 288   2243.192
## 289  10160.766
## 290   2261.952
## 291   2449.553
## 292   6220.739
## 293   2111.871
## 294  10367.128
## 295  14175.834
## 296   2261.952
## 297   6183.219
## 298   6183.219
## 299   2186.911
## 300   2130.631
## 301   6145.699
## 302  10142.006
## 303   2637.155
## 304   6201.979
## 305   2693.435
## 306   2055.590
## 307   2543.354
## 308   2243.192
## 309   6577.182
## 310   6014.378
## 311   6183.219
## 312  14175.834
## 313   2186.911
## 314   6502.141
## 315   6670.982
## 316   6427.101
## 317   2243.192
## 318   5995.617
## 319   6277.020
## 320   1961.790
## 321   2205.671
## 322   2243.192
## 323   2168.151
## 324   6408.340
## 325  14157.074
## 326   2111.871
## 327  18190.901
## 328   6333.300
## 329   6258.259
## 330  14213.354
## 331  14344.675
## 332  10085.726
## 333   2430.793
## 334   9991.925
## 335  18472.303
## 336   6164.459
## 337   6201.979
## 338   6183.219
## 339   6483.381
## 340   2111.871
## 341   2280.712
## 342   2130.631
## 343  10104.486
## 344   2168.151
## 345   6108.178
## 346  14157.074
## 347   6183.219
## 348   6033.138
## 349   2430.793
## 350  14475.996
## 351  10273.327
## 352   6126.938
## 353   6295.780
## 354   6295.780
## 355  10254.567
## 356   6183.219
## 357   2093.111
## 358   2149.391
## 359   6145.699
## 360   2280.712
## 361  18340.983
## 362   2149.391
## 363  18340.983
## 364  18115.861
## 365  18397.263
## 366  14475.996
## 367   6183.219
## 368   6295.780
## 369   2036.830
## 370   6145.699
## 371   6126.938
## 372  10048.205
## 373  10329.607
## 374   2299.472
## 375   1980.550
## 376  14363.435
## 377   2280.712
## 378   6333.300
## 379   2149.391
## 380   2168.151
## 381  18247.182
## 382   2093.111
## 383   6445.861
## 384   2036.830
## 385   2562.114
## 386  10198.286
## 387  10142.006
## 388   6089.418
## 389   6220.739
## 390   1999.310
## 391   6183.219
## 392   6033.138
## 393   2186.911
## 394  10611.009
## 395   2393.273
## 396   2186.911
## 397  14288.395
## 398   2243.192
## 399   6595.942
## 400  10310.847
## 401   6108.178
## 402   6333.300
## 403   2487.074
## 404  10160.766
## 405   2261.952
## 406  14232.114
## 407   6126.938
## 408   2280.712
## 409  14419.716
## 410  14232.114
## 411   2280.712
## 412  10254.567
## 413   2299.472
## 414   6145.699
## 415   2243.192
## 416   6201.979
## 417   2168.151
## 418   2280.712
## 419   6239.499
## 420  10029.445
## 421   6183.219
## 422   6239.499
## 423   6126.938
## 424   1943.030
## 425   6070.658
## 426  10292.087
## 427   2168.151
## 428   1999.310
## 429   2205.671
## 430   6183.219
## 431   6051.898
## 432   2355.753
## 433   6464.621
## 434   2149.391
## 435  10235.807
## 436   6051.898
## 437   2130.631
## 438   2093.111
## 439   2543.354
## 440   6258.259
## 441   6145.699
## 442   2149.391
## 443   2130.631
## 444   2430.793
## 445  18228.422
## 446   2487.074
## 447   6258.259
## 448   6333.300
## 449   6258.259
## 450   6389.580
## 451   6164.459
## 452   2430.793
## 453   6201.979
## 454   6164.459
## 455  14325.915
## 456  18115.861
## 457   6126.938
## 458   6502.141
## 459   2655.915
## 460   6220.739
## 461   2393.273
## 462   2280.712
## 463  10423.408
## 464   6126.938
## 465   2412.033
## 466   2318.232
## 467   2280.712
## 468   2280.712
## 469   6033.138
## 470   6539.661
## 471   2111.871
## 472   2149.391
## 473  10329.607
## 474   2449.553
## 475   2130.631
## 476   6408.340
## 477   6239.499
## 478   6033.138
## 479   2580.874
## 480  10179.526
## 481   6089.418
## 482   2186.911
## 483   6183.219
## 484   2655.915
## 485  10573.489
## 486   6314.540
## 487   2168.151
## 488   2186.911
## 489  10385.888
## 490   6183.219
## 491  18284.702
## 492  14363.435
## 493   6089.418
## 494  10142.006
## 495   6220.739
## 496  14382.195
## 497   2449.553
## 498   2299.472
## 499   6220.739
## 500   6277.020
## 501  10573.489
## 502   2130.631
## 503   2505.834
## 504  10029.445
## 505  14307.155
## 506   6145.699
## 507   2224.432
## 508  10442.168
## 509   2299.472
## 510  18134.621
## 511   6258.259
## 512  10217.047
## 513   2205.671
## 514  10104.486
## 515   1999.310
## 516   6502.141
## 517   2074.351
## 518   2393.273
## 519   6108.178
## 520   2655.915
## 521   2243.192
## 522   2130.631
## 523  10329.607
## 524  18284.702
## 525   2712.195
## 526  10479.688
## 527   6389.580
## 528   6126.938
## 529   2261.952
## 530   2655.915
## 531  10198.286
## 532   6220.739
## 533   2149.391
## 534   6145.699
## 535   2149.391
## 536   2412.033
## 537  10198.286
## 538   2393.273
## 539   2055.590
## 540   6333.300
## 541   6108.178
## 542   2224.432
## 543   2111.871
## 544   6258.259
## 545   2243.192
## 546   2243.192
## 547  10404.648
## 548   6295.780
## 549  10198.286
## 550   2449.553
## 551  18134.621
## 552   2130.631
## 553   6220.739
## 554   2505.834
## 555   6295.780
## 556   6239.499
## 557   6558.422
## 558   2243.192
## 559   6333.300
## 560   6033.138
## 561   2280.712
## 562  14513.516
## 563   2111.871
## 564  10066.965
## 565   2168.151
## 566   2430.793
## 567   6145.699
## 568   6108.178
## 569   6333.300
## 570  14363.435
## 571   6314.540
## 572   1999.310
## 573   6070.658
## 574   6183.219
## 575   6033.138
## 576   6239.499
## 577   2318.232
## 578   2430.793
## 579   6277.020
## 580   6089.418
## 581   2074.351
## 582  14213.354
## 583   6258.259
## 584   6070.658
## 585   6370.820
## 586   6295.780
## 587   6258.259
## 588   2280.712
## 589   2299.472
## 590   2261.952
## 591   2018.070
## 592   6183.219
## 593   2130.631
## 594   2524.594
## 595  10235.807
## 596   6164.459
## 597  10142.006
## 598   6295.780
## 599   6051.898
## 600   2055.590
## 601   2055.590
## 602   6145.699
## 603  10048.205
## 604   2149.391
## 605   2149.391
## 606  14419.716
## 607   6652.222
## 608   6258.259
## 609   2093.111
## 610   2224.432
## 611   6201.979
## 612   6314.540
## 613   2224.432
## 614   1961.790
## 615  10048.205
## 616   6183.219
## 617   2224.432
## 618   6370.820
## 619  10217.047
## 620   2261.952
## 621   1980.550
## 622   6427.101
## 623   2243.192
## 624  10142.006
## 625   2130.631
## 626   2111.871
## 627   5995.617
## 628  10198.286
## 629  10517.209
## 630  10123.246
## 631   2637.155
## 632  10123.246
## 633   6258.259
## 634   2280.712
## 635  10292.087
## 636   2261.952
## 637  14213.354
## 638  10123.246
## 639   2055.590
## 640   2111.871
## 641   2168.151
## 642   6295.780
## 643  14457.236
## 644   2243.192
## 645   2374.513
## 646  10235.807
## 647   1943.030
## 648   2093.111
## 649   6201.979
## 650   2355.753
## 651   2261.952
## 652   6670.982
## 653  10235.807
## 654  10385.888
## 655   2018.070
## 656   6033.138
## 657  10442.168
## 658  14438.476
## 659   6314.540
## 660   6220.739
## 661   6145.699
## 662   2243.192
## 663  10348.368
## 664   2261.952
## 665   6183.219
## 666   6089.418
## 667  10029.445
## 668   2224.432
## 669   6145.699
## 670  14438.476
## 671  10179.526
## 672   6164.459
## 673   6070.658
## 674   2261.952
## 675   2111.871
## 676  18228.422
## 677   6220.739
## 678   6295.780
## 679   6220.739
## 680   2186.911
## 681   6014.378
## 682   2412.033
## 683   6220.739
## 684  10554.729
## 685   2130.631
## 686  10066.965
## 687  10029.445
## 688   2224.432
## 689   1961.790
## 690   2318.232
## 691   6258.259
## 692  10367.128
## 693   6333.300
## 694   2168.151
## 695   6239.499
## 696   2487.074
## 697  14325.915
## 698   6220.739
## 699   1943.030
## 700  18228.422
## 701   2149.391
## 702   6183.219
## 703  10142.006
## 704   2093.111
## 705   2712.195
## 706   6314.540
## 707   6558.422
## 708   2186.911
## 709   2318.232
## 710  14363.435
## 711  10048.205
## 712  14494.756
## 713   2505.834
## 714  10160.766
## 715  10160.766
## 716   2055.590
## 717   6108.178
## 718   6070.658
## 719   6201.979
## 720  10010.685
## 721  10179.526
## 722   6239.499
## 723   2243.192
## 724  10160.766
## 725   2393.273
## 726   6014.378
## 727   2299.472
## 728   2243.192
## 729   2093.111
## 730   2018.070
## 731   6352.060
## 732   6277.020
## 733   2111.871
## 734   6145.699
## 735   2243.192
## 736   6051.898
## 737  14157.074
## 738   6652.222
## 739   6201.979
## 740   6201.979
## 741   6014.378
## 742  10066.965
## 743   6239.499
## 744   2036.830
## 745   6014.378
## 746   2055.590
## 747   2149.391
## 748   6183.219
## 749   2055.590
## 750   2224.432
## 751   1980.550
## 752   2186.911
## 753  14363.435
## 754  10348.368
## 755  10498.449
## 756   2430.793
## 757   6201.979
## 758   6464.621
## 759   2318.232
## 760  18209.662
## 761   2149.391
## 762  14307.155
## 763   6314.540
## 764   6483.381
## 765   2243.192
## 766   6389.580
## 767   2374.513
## 768  10235.807
## 769   6408.340
## 770   6389.580
## 771   6164.459
## 772  10348.368
## 773  10217.047
## 774   2280.712
## 775  10273.327
## 776   2036.830
## 777   2168.151
## 778   2205.671
## 779   2093.111
## 780   2149.391
## 781   2374.513
## 782   6277.020
## 783   2224.432
## 784   6164.459
## 785   6427.101
## 786  14006.993
## 787  10442.168
## 788   6520.901
## 789  18397.263
## 790   2074.351
## 791   6464.621
## 792   2243.192
## 793  10198.286
## 794  10160.766
## 795   6464.621
## 796   2224.432
## 797  14269.634
## 798   2018.070
## 799   1961.790
## 800   6220.739
## 801   6164.459
## 802   6126.938
## 803  14157.074
## 804  10142.006
## 805   6370.820
## 806  10160.766
## 807   6014.378
## 808   2018.070
## 809   2168.151
## 810   2111.871
## 811   6108.178
## 812   2074.351
## 813   5995.617
## 814  18247.182
## 815   2318.232
## 816   2224.432
## 817   6108.178
## 818  10104.486
## 819   2168.151
## 820   6070.658
## 821   2205.671
## 822   6089.418
## 823   6183.219
## 824   2186.911
## 825   6220.739
## 826  18228.422
## 827  10066.965
## 828   6183.219
## 829   2318.232
## 830  18303.462
## 831   6389.580
## 832   1961.790
## 833   2130.631
## 834   1961.790
## 835  14457.236
## 836  10179.526
## 837   2299.472
## 838   6183.219
## 839  10367.128
## 840  18265.942
## 841   1943.030
## 842  10029.445
## 843  14400.955
## 844  10123.246
## 845   6183.219
## 846   6070.658
## 847   1961.790
## 848  10217.047
## 849   6295.780
## 850   2093.111
## 851   6126.938
## 852   2168.151
## 853   6089.418
## 854   6070.658
## 855   6201.979
## 856   2261.952
## 857   2168.151
## 858  10066.965
## 859   2374.513
## 860  10310.847
## 861   2562.114
## 862  10292.087
## 863   6183.219
## 864  14307.155
## 865  10329.607
## 866  10385.888
## 867   6145.699
## 868   6427.101
## 869   2449.553
## 870   6201.979</code></pre>
<pre class="r"><code>plot(density(fit3_Preds),main = &quot;Model 3 Residual with Job Level and Age&quot;)</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-5-6.png" width="672" /></p>
<pre class="r"><code>RMSE3 = sqrt(mean((Casestudy2$MonthlyIncome - fit3_Preds)^2))
RMSE3= 1404.01

# Model 4 combined JobLevel, Age, and Years at Company
fit4 = lm(MonthlyIncome~JobLevel + Age + YearsAtCompany, data = Casestudy2)
summary(fit4)</code></pre>
<pre><code>## 
## Call:
## lm(formula = MonthlyIncome ~ JobLevel + Age + YearsAtCompany, 
##     data = Casestudy2)
## 
## Residuals:
##     Min      1Q  Median      3Q     Max 
## -5056.6  -951.9    65.3   737.8  3845.3 
## 
## Coefficients:
##                 Estimate Std. Error t value Pr(&gt;|t|)    
## (Intercept)    -2334.160    202.704 -11.515  &lt; 2e-16 ***
## JobLevel        3955.801     56.008  70.629  &lt; 2e-16 ***
## Age               18.962      6.102   3.108  0.00195 ** 
## YearsAtCompany    -5.761      9.297  -0.620  0.53563    
## ---
## Signif. codes:  0 &#39;***&#39; 0.001 &#39;**&#39; 0.01 &#39;*&#39; 0.05 &#39;.&#39; 0.1 &#39; &#39; 1
## 
## Residual standard error: 1407 on 866 degrees of freedom
## Multiple R-squared:  0.9067, Adjusted R-squared:  0.9064 
## F-statistic:  2805 on 3 and 866 DF,  p-value: &lt; 2.2e-16</code></pre>
<pre class="r"><code>confint(fit4)</code></pre>
<pre><code>##                       2.5 %      97.5 %
## (Intercept)    -2732.009068 -1936.31155
## JobLevel        3845.874125  4065.72825
## Age                6.986221    30.93732
## YearsAtCompany   -24.008864    12.48633</code></pre>
<pre class="r"><code>fit4_Preds = predict(fit4, newdata = Casestudy2)
as.data.frame(fit4_Preds)</code></pre>
<pre><code>##     fit4_Preds
## 1     6155.412
## 2    18088.091
## 3    10185.383
## 4    10059.362
## 5     2042.156
## 6     9993.360
## 7     2376.028
## 8     6273.266
## 9     2260.580
## 10    6176.052
## 11   18168.022
## 12    2135.287
## 13   10150.815
## 14    2184.733
## 15    2453.554
## 16    6113.406
## 17    6138.129
## 18    6443.922
## 19    2237.535
## 20    6400.238
## 21    6242.782
## 22    6476.085
## 23    6346.708
## 24    6136.451
## 25    6174.374
## 26   18152.416
## 27    6246.138
## 28    6174.374
## 29   10526.695
## 30    2584.608
## 31    6138.129
## 32    2166.722
## 33   14320.957
## 34    2239.213
## 35    6178.458
## 36    2199.611
## 37   10122.009
## 38    6248.543
## 39   18466.376
## 40    2197.933
## 41   14496.647
## 42    6384.632
## 43    2539.245
## 44   18235.479
## 45    2052.000
## 46    2348.900
## 47    6184.219
## 48   10207.700
## 49    1962.953
## 50    2122.086
## 51    2342.188
## 52   18492.777
## 53    2398.346
## 54    6378.870
## 55    6101.883
## 56    2370.267
## 57    2406.513
## 58    2113.920
## 59   10206.023
## 60    2089.924
## 61   10123.687
## 62   10175.538
## 63    2197.933
## 64    1962.953
## 65    2070.962
## 66    2193.850
## 67    6143.163
## 68    2028.955
## 69    2268.019
## 70    2225.285
## 71    2370.267
## 72    6079.565
## 73    6235.343
## 74    2393.312
## 75   10473.165
## 76    6077.160
## 77   10120.331
## 78   14211.493
## 79   10277.059
## 80    2203.695
## 81    6273.266
## 82    6200.775
## 83    6251.899
## 84    6238.699
## 85    6167.886
## 86   14578.983
## 87    6428.317
## 88    2262.258
## 89    9993.360
## 90   18305.565
## 91    2336.427
## 92   10019.761
## 93    2323.226
## 94    6212.298
## 95   18364.128
## 96    6258.611
## 97   14286.390
## 98    6273.266
## 99    2154.248
## 100   2237.535
## 101   2104.802
## 102  10046.162
## 103   6204.859
## 104   2040.478
## 105  14442.167
## 106   2068.557
## 107   6069.721
## 108  18430.130
## 109   6397.832
## 110   2205.373
## 111   2135.287
## 112  14423.205
## 113  10473.165
## 114   6235.343
## 115   6200.775
## 116  10177.216
## 117   6028.441
## 118   6104.288
## 119   2347.222
## 120   6141.485
## 121  10169.777
## 122   2008.316
## 123  10357.717
## 124   6257.661
## 125   6069.721
## 126   6183.491
## 127   2170.805
## 128   6378.870
## 129   6277.573
## 130  14251.822
## 131   6069.721
## 132   6477.763
## 133   6339.269
## 134   6288.145
## 135   6340.947
## 136   6289.823
## 137   2165.771
## 138  10499.566
## 139   2349.627
## 140  10206.023
## 141  14441.440
## 142   2709.901
## 143  10359.395
## 144   6250.221
## 145   6266.778
## 146   6104.288
## 147   2201.289
## 148   6191.658
## 149   2053.678
## 150   6079.565
## 151   6147.973
## 152   6126.606
## 153   6109.322
## 154   6337.591
## 155   2260.580
## 156   6134.773
## 157   6272.539
## 158  14124.851
## 159  10302.509
## 160  10323.876
## 161   6088.683
## 162  10006.560
## 163   6174.374
## 164   6356.553
## 165  10133.531
## 166   1989.354
## 167  14395.126
## 168  14080.215
## 169   6505.842
## 170   2131.203
## 171   6100.205
## 172   6422.555
## 173  10393.962
## 174  10107.130
## 175  14396.077
## 176   2008.316
## 177  18458.937
## 178   2097.363
## 179  10088.169
## 180   6251.899
## 181  10156.576
## 182   6257.661
## 183   2419.713
## 184  10261.230
## 185   2315.060
## 186   2123.764
## 187   6011.158
## 188  14362.964
## 189  18335.322
## 190   6079.565
## 191   6088.683
## 192  10103.774
## 193   6392.071
## 194   6435.756
## 195   2091.602
## 196   2582.930
## 197   2565.646
## 198  14366.320
## 199  10240.813
## 200   2070.962
## 201  14241.754
## 202   6126.606
## 203   6103.561
## 204   2112.242
## 205   2205.373
## 206   2409.869
## 207   6369.753
## 208   6292.228
## 209   2173.210
## 210  10258.825
## 211  14151.252
## 212  18235.479
## 213   2317.465
## 214   6350.791
## 215   2110.564
## 216   2362.828
## 217   6292.228
## 218  14272.462
## 219   2161.688
## 220   2068.557
## 221   6187.575
## 222   6424.961
## 223   6168.613
## 224   2146.809
## 225   2313.382
## 226   2121.359
## 227   2279.542
## 228   2015.755
## 229   6015.241
## 230  14331.752
## 231   6373.109
## 232   2273.780
## 233  14247.739
## 234   6566.810
## 235  14160.369
## 236  10154.171
## 237  18114.492
## 238   6149.651
## 239   2084.163
## 240  10400.674
## 241  10272.025
## 242  18298.125
## 243   2142.726
## 244   2078.401
## 245   6069.721
## 246   2148.487
## 247  10057.684
## 248   2216.895
## 249   6320.307
## 250  14162.774
## 251   2241.618
## 252   6219.737
## 253   2469.159
## 254   2203.695
## 255  10239.863
## 256   2419.713
## 257   2197.933
## 258   6129.011
## 259  10149.137
## 260   2084.163
## 261   2203.695
## 262   2119.681
## 263   2218.573
## 264   2154.248
## 265   2047.917
## 266   2256.497
## 267  14053.087
## 268   2222.656
## 269   6151.329
## 270   6111.728
## 271   6384.632
## 272   6158.768
## 273   6037.559
## 274   6242.782
## 275  18349.473
## 276  18477.899
## 277   2027.277
## 278   2390.907
## 279   6016.919
## 280   6603.056
## 281   6335.186
## 282   2295.371
## 283   6307.107
## 284   6124.928
## 285   2301.859
## 286   6116.762
## 287   2033.039
## 288   2254.819
## 289  10164.016
## 290   2268.019
## 291   2446.114
## 292   6208.214
## 293   2093.280
## 294  10349.550
## 295  14126.529
## 296   2273.780
## 297   6164.530
## 298   6170.291
## 299   2192.172
## 300   2135.287
## 301   6126.606
## 302  10145.054
## 303   2641.493
## 304   6183.491
## 305   2715.662
## 306   2047.917
## 307   2563.968
## 308   2266.341
## 309   6574.249
## 310   6034.203
## 311   6210.620
## 312  14132.290
## 313   2169.127
## 314   6538.731
## 315   6703.626
## 316   6416.794
## 317   2243.296
## 318   6009.480
## 319   6288.145
## 320   1976.153
## 321   2211.134
## 322   2208.728
## 323   2161.688
## 324   6357.503
## 325  14107.567
## 326   2127.847
## 327  18152.416
## 328   6350.791
## 329   6182.764
## 330  14170.214
## 331  14372.081
## 332  10059.362
## 333   2427.153
## 334   9993.360
## 335  18546.306
## 336   6128.284
## 337   6212.298
## 338   6187.575
## 339   6525.531
## 340   2127.847
## 341   2298.503
## 342   2141.048
## 343  10141.698
## 344   2184.733
## 345   6123.250
## 346  14113.328
## 347   6204.859
## 348   6035.881
## 349   2455.959
## 350  14493.291
## 351  10254.741
## 352   6119.167
## 353   6330.152
## 354   6324.390
## 355  10183.928
## 356   6147.246
## 357   2085.841
## 358   2160.010
## 359   6132.367
## 360   2217.846
## 361  18240.736
## 362   2165.771
## 363  18246.497
## 364  18082.330
## 365  18378.279
## 366  14510.575
## 367   6158.768
## 368   6289.823
## 369   2046.239
## 370   6143.890
## 371   6142.212
## 372  10050.245
## 373  10248.253
## 374   2277.136
## 375   1989.354
## 376  14252.773
## 377   2206.323
## 378   6373.837
## 379   2142.726
## 380   2161.688
## 381  18318.765
## 382   2068.557
## 383   6476.085
## 384   2057.762
## 385   2531.079
## 386  10167.372
## 387  10139.293
## 388   6110.050
## 389   6185.169
## 390   2002.554
## 391   6204.859
## 392   6058.926
## 393   2186.411
## 394  10567.247
## 395   2406.513
## 396   2197.933
## 397  14344.002
## 398   2254.819
## 399   6564.405
## 400  10356.039
## 401   6117.489
## 402   6345.030
## 403   2501.322
## 404  10198.583
## 405   2250.735
## 406  14298.639
## 407   6096.122
## 408   2263.936
## 409  14349.987
## 410  14281.356
## 411   2275.458
## 412  10253.063
## 413   2317.465
## 414   6184.219
## 415   2254.819
## 416   6200.775
## 417   2127.120
## 418   2298.503
## 419   6198.370
## 420  10025.522
## 421   6193.336
## 422   6204.131
## 423   6124.928
## 424   1962.953
## 425   6079.565
## 426  10342.838
## 427   2184.733
## 428   2002.554
## 429   2211.134
## 430   6158.768
## 431   6060.604
## 432   2357.067
## 433   6483.524
## 434   2165.771
## 435  10285.953
## 436   6043.320
## 437   2141.048
## 438   2074.318
## 439   2552.446
## 440   6246.138
## 441   6138.129
## 442   2142.726
## 443   2152.571
## 444   2444.436
## 445  18305.565
## 446   2478.277
## 447   6223.093
## 448   6373.837
## 449   6240.377
## 450   6373.109
## 451   6151.329
## 452   2427.153
## 453   6183.491
## 454   6145.568
## 455  14381.926
## 456  18082.330
## 457   6107.644
## 458   6486.880
## 459   2666.216
## 460   6202.453
## 461   2406.513
## 462   2281.220
## 463  10469.809
## 464   6136.451
## 465   2431.236
## 466   2324.904
## 467   2286.981
## 468   2298.503
## 469   6058.926
## 470   6559.371
## 471   2104.802
## 472   2165.771
## 473  10386.523
## 474   2440.353
## 475   2129.525
## 476   6397.832
## 477   6273.266
## 478   6070.448
## 479   2578.847
## 480  10142.649
## 481   6098.527
## 482   2174.888
## 483   6135.723
## 484   2671.978
## 485  10402.575
## 486   6320.307
## 487   2184.733
## 488   2180.649
## 489  10437.647
## 490   6193.336
## 491  18356.689
## 492  14419.849
## 493   6098.527
## 494  10133.531
## 495   6202.453
## 496  14340.870
## 497   2463.398
## 498   2300.181
## 499   6219.737
## 500   6299.667
## 501  10575.413
## 502   2129.525
## 503   2479.955
## 504  10025.522
## 505  14265.022
## 506   6143.890
## 507   2241.618
## 508  10477.249
## 509   2271.375
## 510  18095.530
## 511   6240.377
## 512  10238.185
## 513   2199.611
## 514  10072.563
## 515   2002.554
## 516   6521.447
## 517   2089.924
## 518   2389.229
## 519   6094.444
## 520   2660.455
## 521   2237.535
## 522   2146.809
## 523  10380.762
## 524  18195.373
## 525   2734.624
## 526  10451.798
## 527   6401.915
## 528   6130.689
## 529   2250.735
## 530   2654.694
## 531  10144.327
## 532   6254.305
## 533   2113.920
## 534   6155.412
## 535   2131.203
## 536   2408.191
## 537  10248.029
## 538   2400.752
## 539   2047.917
## 540   6339.269
## 541   6088.683
## 542   2189.767
## 543   2127.847
## 544   6292.228
## 545   2231.774
## 546   2208.728
## 547  10312.577
## 548   6330.152
## 549  10196.178
## 550   2440.353
## 551  18095.530
## 552   2123.764
## 553   6202.453
## 554   2531.806
## 555   6318.629
## 556   6261.744
## 557   6595.617
## 558   2231.774
## 559   6321.985
## 560   6024.358
## 561   2258.175
## 562  14577.305
## 563   2122.086
## 564  10057.684
## 565   2178.972
## 566   2432.914
## 567   6149.651
## 568   6088.683
## 569   6345.030
## 570  14367.998
## 571   6326.068
## 572   2014.077
## 573   6068.043
## 574   6164.530
## 575   6041.642
## 576   6238.699
## 577   2336.427
## 578   2427.153
## 579   6265.100
## 580   6092.766
## 581   2078.401
## 582  14279.678
## 583   6292.228
## 584   6062.282
## 585   6388.715
## 586   6295.584
## 587   6223.093
## 588   2275.458
## 589   2305.943
## 590   2273.780
## 591   2015.755
## 592   6135.723
## 593   2135.287
## 594   2498.916
## 595  10188.011
## 596   6151.329
## 597  10122.009
## 598   6330.152
## 599   6054.842
## 600   2065.201
## 601   2070.962
## 602   6149.651
## 603  10056.006
## 604   2113.920
## 605   2160.010
## 606  14465.212
## 607   6673.142
## 608   6251.899
## 609   2074.318
## 610   2235.857
## 611   6189.253
## 612   6308.785
## 613   2195.528
## 614   1976.153
## 615  10056.006
## 616   6135.723
## 617   2218.573
## 618   6388.715
## 619  10232.424
## 620   2279.542
## 621   1995.115
## 622   6359.181
## 623   2243.296
## 624  10145.054
## 625   2152.571
## 626   2104.802
## 627   6003.718
## 628  10190.417
## 629  10558.857
## 630  10131.853
## 631   2635.732
## 632  10097.286
## 633   6292.228
## 634   2298.503
## 635  10342.838
## 636   2273.780
## 637  14158.691
## 638  10131.853
## 639   2042.156
## 640   2110.564
## 641   2184.733
## 642   6295.584
## 643  14480.091
## 644   2237.535
## 645   2393.312
## 646  10222.579
## 647   1962.953
## 648   2097.363
## 649   6154.685
## 650   2357.067
## 651   2268.019
## 652   6651.774
## 653  10188.011
## 654  10443.408
## 655   2027.277
## 656   6041.642
## 657  10442.681
## 658  14432.322
## 659   6326.068
## 660   6225.498
## 661   6126.606
## 662   2226.012
## 663  10347.872
## 664   2268.019
## 665   6170.291
## 666   6110.050
## 667  10019.761
## 668   2224.334
## 669   6126.606
## 670  14455.367
## 671  10206.023
## 672   6168.613
## 673   6085.327
## 674   2227.690
## 675   2116.325
## 676  18253.713
## 677   6208.214
## 678   6278.300
## 679   6237.021
## 680   2169.127
## 681   6022.680
## 682   2419.713
## 683   6242.782
## 684  10585.258
## 685   2123.764
## 686  10046.162
## 687  10037.045
## 688   2230.096
## 689   1976.153
## 690   2278.814
## 691   6263.422
## 692  10366.834
## 693   6368.075
## 694   2184.733
## 695   6244.460
## 696   2495.560
## 697  14387.687
## 698   6185.169
## 699   1962.953
## 700  18294.042
## 701   2165.771
## 702   6187.575
## 703  10122.009
## 704   2085.841
## 705   2728.863
## 706   6274.217
## 707   6561.049
## 708   2192.172
## 709   2313.382
## 710  14258.534
## 711  10050.245
## 712  14564.104
## 713   2526.045
## 714  10140.971
## 715  10158.254
## 716   2070.962
## 717   6088.683
## 718   6062.282
## 719   6177.730
## 720  10012.321
## 721  10177.216
## 722   6255.983
## 723   2243.296
## 724  10135.209
## 725   2418.035
## 726   6028.441
## 727   2294.420
## 728   2237.535
## 729   2108.886
## 730   2027.277
## 731   6387.037
## 732   6311.190
## 733   2127.847
## 734   6161.174
## 735   2260.580
## 736   6043.320
## 737  14113.328
## 738   6661.619
## 739   6212.298
## 740   6223.820
## 741   6039.964
## 742  10092.252
## 743   6221.415
## 744   2040.478
## 745   6022.680
## 746   2070.962
## 747   2160.010
## 748   6147.246
## 749   2042.156
## 750   2230.096
## 751   1989.354
## 752   2192.172
## 753  14264.295
## 754  10359.395
## 755  10534.134
## 756   2427.153
## 757   6183.491
## 758   6489.285
## 759   2342.188
## 760  18159.855
## 761   2171.532
## 762  14230.455
## 763   6245.411
## 764   6421.828
## 765   2249.057
## 766   6373.109
## 767   2341.461
## 768  10285.953
## 769   6415.116
## 770   6344.303
## 771   6162.852
## 772  10267.214
## 773  10163.288
## 774   2298.503
## 775  10214.412
## 776   2046.239
## 777   2161.688
## 778   2222.656
## 779   2074.318
## 780   2160.010
## 781   2376.028
## 782   6201.726
## 783   2224.334
## 784   6145.568
## 785   6462.884
## 786  14059.576
## 787  10488.771
## 788   6517.364
## 789  18481.982
## 790   2084.163
## 791   6489.285
## 792   2249.057
## 793  10224.984
## 794  10117.926
## 795   6466.240
## 796   2189.767
## 797  14227.099
## 798   2033.039
## 799   1976.153
## 800   6231.260
## 801   6174.374
## 802   6130.689
## 803  14107.567
## 804  10150.815
## 805   6394.476
## 806  10146.732
## 807   6034.203
## 808   2027.277
## 809   2132.881
## 810   2104.802
## 811   6077.160
## 812   2078.401
## 813   6003.718
## 814  18307.243
## 815   2330.666
## 816   2166.722
## 817   6146.295
## 818  10084.085
## 819   2161.688
## 820   6096.849
## 821   2211.134
## 822   6110.050
## 823   6176.052
## 824   2197.933
## 825   6242.782
## 826  18305.565
## 827  10115.297
## 828   6204.859
## 829   2307.621
## 830  18208.574
## 831   6378.870
## 832   1981.915
## 833   2118.003
## 834   1976.153
## 835  14341.820
## 836  10182.977
## 837   2288.659
## 838   6164.530
## 839  10297.699
## 840  18228.263
## 841   1962.953
## 842  10025.522
## 843  14423.205
## 844  10126.092
## 845   6210.620
## 846   6050.759
## 847   1976.153
## 848  10169.050
## 849   6301.345
## 850   2074.318
## 851   6153.734
## 852   2132.881
## 853   6075.482
## 854   6062.282
## 855   6223.820
## 856   2279.542
## 857   2161.688
## 858  10063.446
## 859   2370.267
## 860  10309.949
## 861   2548.362
## 862  10227.613
## 863   6193.336
## 864  14253.500
## 865  10369.239
## 866  10385.796
## 867   6166.935
## 868   6439.839
## 869   2457.637
## 870   6206.537</code></pre>
<pre class="r"><code>plot(density(fit4_Preds),main = &quot;Model Residual with Job Level, Age, and Years at Company&quot;)</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-5-7.png" width="672" /></p>
<pre class="r"><code>RMSE4 = sqrt(mean((Casestudy2$MonthlyIncome - fit4_Preds)^2))
RMSE4= 1403.698</code></pre>
<p>#Choosing to predit the test dataset using Model4 since it has a best
RMSE</p>
<pre class="r"><code>Model1_fit = lm(MonthlyIncome~JobLevel+Age+YearsAtCompany, data = Casestudy2)
summary(Model1_fit)</code></pre>
<pre><code>## 
## Call:
## lm(formula = MonthlyIncome ~ JobLevel + Age + YearsAtCompany, 
##     data = Casestudy2)
## 
## Residuals:
##     Min      1Q  Median      3Q     Max 
## -5056.6  -951.9    65.3   737.8  3845.3 
## 
## Coefficients:
##                 Estimate Std. Error t value Pr(&gt;|t|)    
## (Intercept)    -2334.160    202.704 -11.515  &lt; 2e-16 ***
## JobLevel        3955.801     56.008  70.629  &lt; 2e-16 ***
## Age               18.962      6.102   3.108  0.00195 ** 
## YearsAtCompany    -5.761      9.297  -0.620  0.53563    
## ---
## Signif. codes:  0 &#39;***&#39; 0.001 &#39;**&#39; 0.01 &#39;*&#39; 0.05 &#39;.&#39; 0.1 &#39; &#39; 1
## 
## Residual standard error: 1407 on 866 degrees of freedom
## Multiple R-squared:  0.9067, Adjusted R-squared:  0.9064 
## F-statistic:  2805 on 3 and 866 DF,  p-value: &lt; 2.2e-16</code></pre>
<pre class="r"><code>confint(Model1_fit)</code></pre>
<pre><code>##                       2.5 %      97.5 %
## (Intercept)    -2732.009068 -1936.31155
## JobLevel        3845.874125  4065.72825
## Age                6.986221    30.93732
## YearsAtCompany   -24.008864    12.48633</code></pre>
<pre class="r"><code>Model1_Preds = predict(Model1_fit, newdata = CaseStudy2CompSet_No_Salary)
as.data.frame(Model1_Preds)</code></pre>
<pre><code>##     Model1_Preds
## 1       6352.469
## 2       2230.096
## 3      14422.478
## 4       2275.458
## 5       2093.280
## 6       6311.190
## 7       6162.852
## 8       2008.316
## 9       2132.881
## 10     14427.289
## 11     10365.156
## 12      2357.067
## 13      6092.766
## 14      6066.365
## 15      6127.333
## 16      5977.317
## 17      6087.005
## 18      6222.142
## 19      6124.928
## 20      2256.497
## 21      6284.062
## 22     10079.051
## 23     10353.633
## 24      6054.842
## 25     10416.280
## 26     10353.633
## 27     10158.982
## 28     14170.214
## 29      6164.530
## 30      2292.742
## 31      2122.086
## 32      6405.999
## 33      6441.517
## 34      2374.351
## 35     14290.473
## 36      6185.897
## 37     10347.872
## 38      6244.460
## 39      2141.048
## 40      2222.656
## 41     18214.112
## 42      2307.621
## 43      2357.067
## 44     10114.570
## 45      6343.352
## 46      5990.518
## 47      2135.287
## 48      6041.642
## 49      2146.809
## 50      2734.624
## 51      2173.210
## 52      2279.542
## 53      6254.305
## 54      6350.791
## 55     14455.367
## 56      2339.783
## 57      6126.606
## 58     10150.088
## 59      2033.039
## 60      2188.089
## 61      6135.723
## 62     10099.691
## 63     10253.063
## 64      2715.662
## 65      1995.115
## 66      2076.723
## 67     10382.440
## 68     10477.249
## 69      6276.622
## 70      2146.809
## 71      2351.305
## 72     10232.424
## 73     10531.001
## 74      6072.126
## 75      1962.953
## 76      6092.766
## 77      2014.077
## 78      2097.363
## 79      2074.318
## 80      6439.839
## 81      2383.468
## 82      6295.584
## 83      6255.983
## 84      2104.802
## 85      6288.145
## 86     10357.717
## 87     10560.535
## 88      2182.327
## 89     10299.153
## 90     18366.029
## 91      2136.965
## 92      6284.062
## 93      6274.944
## 94      6270.861
## 95      2084.163
## 96     18237.380
## 97      2142.726
## 98     10158.254
## 99     14425.611
## 100     2097.363
## 101     6049.081
## 102     6113.406
## 103     2129.525
## 104     1995.115
## 105     6009.480
## 106     2148.487
## 107     6476.085
## 108     2332.344
## 109    10098.964
## 110    18368.211
## 111     2256.497
## 112    10388.201
## 113     2596.131
## 114     2091.602
## 115     6225.498
## 116     2205.373
## 117     2038.800
## 118     6161.174
## 119    10151.766
## 120     2197.933
## 121     6288.145
## 122     2047.917
## 123     6082.921
## 124     6335.913
## 125     6269.183
## 126     6129.962
## 127     2330.666
## 128    14397.755
## 129    10139.293
## 130     2222.656
## 131     6426.639
## 132     6468.645
## 133     6132.367
## 134     6439.839
## 135     2485.716
## 136     6199.097
## 137     1989.354
## 138     6286.467
## 139    18409.491
## 140     6542.087
## 141    10229.068
## 142     6216.381
## 143     6109.322
## 144     6181.813
## 145     6111.728
## 146     2402.430
## 147     2366.184
## 148    10139.293
## 149    10044.484
## 150     1962.953
## 151     6384.632
## 152     6254.305
## 153     6305.429
## 154    10254.014
## 155    14226.148
## 156    18149.787
## 157     6153.734
## 158     6022.680
## 159     6021.002
## 160    10252.336
## 161     6166.935
## 162     2385.146
## 163     9993.360
## 164     2108.886
## 165     6289.823
## 166     1995.115
## 167     6016.919
## 168    10505.328
## 169    10249.707
## 170     6081.243
## 171     2180.649
## 172     2230.096
## 173    10164.016
## 174     6156.363
## 175     2123.764
## 176     2146.809
## 177     6269.183
## 178    10101.369
## 179     2087.519
## 180     6229.582
## 181    10348.095
## 182     2258.175
## 183     6363.992
## 184     2141.048
## 185     2110.564
## 186     2084.163
## 187     6077.887
## 188    14206.459
## 189     6221.415
## 190     2123.764
## 191     6589.128
## 192     6170.291
## 193     6128.284
## 194     2040.478
## 195     6648.419
## 196     2034.717
## 197     2351.305
## 198    18415.475
## 199     6180.135
## 200     2558.207
## 201     2127.847
## 202     6090.361
## 203     1989.354
## 204     6105.966
## 205     6639.301
## 206    14211.493
## 207    18369.162
## 208     6107.644
## 209     6213.976
## 210     6345.030
## 211     2368.589
## 212     2262.258
## 213     2052.000
## 214     6177.730
## 215    10201.939
## 216    10188.011
## 217     6136.451
## 218     2336.427
## 219     2180.649
## 220     6054.842
## 221     6087.005
## 222     6173.647
## 223    10177.216
## 224     6307.107
## 225     6016.919
## 226     6244.460
## 227     2305.943
## 228     2167.449
## 229     2182.327
## 230     6221.415
## 231    18088.091
## 232     6307.107
## 233     6251.899
## 234    10509.411
## 235     2269.697
## 236     2131.203
## 237     2081.757
## 238     6400.238
## 239     6049.081
## 240     6212.298
## 241     6160.446
## 242    10617.420
## 243    10118.653
## 244     6502.486
## 245    10326.505
## 246     2093.280
## 247     6273.266
## 248     6056.520
## 249    10598.458
## 250     2220.251
## 251    10464.048
## 252    14370.403
## 253     6107.644
## 254    14227.099
## 255     2260.580
## 256     1981.915
## 257     2042.156
## 258     6534.648
## 259    14139.729
## 260     2015.755
## 261    10109.536
## 262    14119.089
## 263     6316.224
## 264     2319.143
## 265     2199.611
## 266     2085.841
## 267     2294.420
## 268     6303.023
## 269    10161.610
## 270    14223.743
## 271     6113.406
## 272     6321.985
## 273    10356.989
## 274     6085.327
## 275     6354.147
## 276     6401.915
## 277     6199.097
## 278     2197.933
## 279     2154.248
## 280     6082.921
## 281     2319.143
## 282     6054.842
## 283     6578.333
## 284     2146.809
## 285     6420.150
## 286    14415.766
## 287     2154.248
## 288     6254.305
## 289     2110.564
## 290     6242.782
## 291     2421.391
## 292    10248.029
## 293     2108.158
## 294    10200.261
## 295     2068.557
## 296     2216.895
## 297    10228.340
## 298     6117.489
## 299     2104.802
## 300     2277.136</code></pre>
<pre class="r"><code>MSPE1 = sqrt(mean((Casestudy2$MonthlyIncome - Model1_Preds)^2))</code></pre>
<pre><code>## Warning in Casestudy2$MonthlyIncome - Model1_Preds: longer object length is not
## a multiple of shorter object length</code></pre>
<pre class="r"><code>MSPE1= 5994.025

#salary prediction to file
MonthlyIncome = predict(Model1_fit, newdata = CaseStudy2CompSet_No_Salary)
Model1_Preds_df &lt;- as.data.frame(round(MonthlyIncome))
names(Model1_Preds_df) &lt;- &quot;MonthlyIncome&quot;
CS2Test2_pred &lt;- cbind(CaseStudy2CompSet_No_Salary, Model1_Preds_df)

CS2Test2_pred %&gt;% 
  ggplot(aes(x = YearsAtCompany, y = MonthlyIncome)) + geom_point() + ggtitle(&quot; MonthlyIncome v. YearsAtCompany&quot;) + geom_smooth(method = &quot;lm&quot;) </code></pre>
<pre><code>## `geom_smooth()` using formula = &#39;y ~ x&#39;</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-6-1.png" width="672" /></p>
<pre class="r"><code>CS2Test2_pred %&gt;% 
  ggplot(aes(x = JobLevel, y = MonthlyIncome)) + geom_point() + ggtitle(&quot;MonthlyIncome v. JobLevel&quot;) + geom_smooth(method = &quot;lm&quot;) </code></pre>
<pre><code>## `geom_smooth()` using formula = &#39;y ~ x&#39;</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-6-2.png" width="672" /></p>
<pre class="r"><code>CS2Test2_pred %&gt;% 
  ggplot(aes(x = Age, y = MonthlyIncome)) + geom_point() + ggtitle(&quot;MonthlyIncome v. Age&quot;) + geom_smooth(method = &quot;lm&quot;) </code></pre>
<pre><code>## `geom_smooth()` using formula = &#39;y ~ x&#39;</code></pre>
<p><img src="Case_Study2_files/figure-html/unnamed-chunk-6-3.png" width="672" /></p>
<pre class="r"><code>CS2Salary &lt;- CS2Test2_pred %&gt;% select(ID, MonthlyIncome)

#write the predictions to a file
write.csv(CS2Salary, file = &quot;C:\\Users\\Steph\\OneDrive\\Documents\\MSDS_6306_Doing-Data-Science\\Unit 14 and 15 Case Study 2/Case2PredictionSalary.csv&quot;, row.names = FALSE)</code></pre>




</div>

<script>

// add bootstrap table styles to pandoc tables
function bootstrapStylePandocTables() {
  $('tr.odd').parent('tbody').parent('table').addClass('table table-condensed');
}
$(document).ready(function () {
  bootstrapStylePandocTables();
});


</script>

<!-- tabsets -->

<script>
$(document).ready(function () {
  window.buildTabsets("TOC");
});

$(document).ready(function () {
  $('.tabset-dropdown > .nav-tabs > li').click(function () {
    $(this).parent().toggleClass('nav-tabs-open');
  });
});
</script>

<!-- code folding -->


<!-- dynamically load mathjax for compatibility with self-contained -->
<script>
  (function () {
    var script = document.createElement("script");
    script.type = "text/javascript";
    script.src  = "https://mathjax.rstudio.com/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML";
    document.getElementsByTagName("head")[0].appendChild(script);
  })();
</script>

</body>
</html>
