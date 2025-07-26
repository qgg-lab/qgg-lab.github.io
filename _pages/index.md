---
title: Wen Huang Laboratory | Michigan State University
layout: pages
active: home
permalink: /index.html
---

## <center>Wen Huang Laboratory</center>  
### <center>Quantitative Genetics and Genomics</center>

<center><a href="https://www.canr.msu.edu/ans/" target="_blank">Department of Animal Science</a></center>
<center><a href="https://msu.edu" target="_blank">Michigan State University</a></center>

-----

### introduction

We are a lab of quantitative genetics and genomics, primarily in the model organism <i>Drosophila melanogaster</i> and livestock animals. We seek to understand why some cows produce more milk than others, or why some people are more prone to certain diseases than others, and questions of that nature. By doing that, we hope to be able to understand the biological processes underlying complex quantitative trait variation and eventually breed better animals and improve human health. We tackle these questions using a variety of approaches, including genetics, genomics, statistics, and bioinformatics.

### recruiting now | <a href="{{ site.baseurl }}/join.html">all opportunities</a>

<i class="fa fa-check-circle" aria-hidden="true" style="color:green"></i> Postdocs; <i class="fa fa-check-circle" aria-hidden="true"  style="color:green"></i> Graduate Students; <i class="fa fa-check-circle" aria-hidden="true"  style="color:green"></i> Undergraduate Students
<!---
 <i class="fa fa-times-circle" aria-hidden="true"  style="color:red"></i> Undergraduate Students; 
--->

###  news | <a href="{{ site.baseurl }}/news.html">all news</a>

<ul>
  {% for news in site.categories.news limit:3 %}
    <li>
      <a href="{{ site.baseurl }}{{ news.url }}">{{ news.date | date: "%m-%d-%Y" }}</a>: {{ news.title }}
    </li>
  {% endfor %}
</ul>

### recent papers | <a href="{{ site.baseurl }}/publications.html">all papers</a>

- <a href="https://www.sciencedirect.com/science/article/pii/S2211124725007703?via%3Dihub" target="_blank">Effects of aging on gene expression networks in the Drosophila genetic reference panel.</a><i>Cell Rep</i>, 2025
- <a href="https://www.nature.com/articles/s41467-024-49923-5" target="_blank">Multi-omic characterization of allele-specific regulatory variation in hybrid pigs.</a> <i>Nat Commun</i>, 2024

### web servers

- <a href="https://swimgeno.org" target="_blank">SWIM</a>: swine genome imputation server
- <a href="https://bioinfo.njau.edu.cn/metazExp/" target="_blank">MetazExp</a>: metazoan expression atlas
- <a href="http://aslive.org" target="blank">ASlive</a>: alternative splicing in livestock animals
- <a href="https://quantgenet.msu.edu/dgrp" target="_blank">DGRP</a>: GWAS in DGRP

### contact information
<i class="fa fa-envelope" aria-hidden="true" style="color:#18453b"></i> huangw53 AT msu.edu  
<i class="fa fa-phone" aria-hidden="true"  style="color:#18453b"></i> (517) 353-9136  
1205F Anthony Hall    
Michigan State University  
East Lansing, Michigan 48824

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-21MFXXZDFR"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-21MFXXZDFR');
</script>
