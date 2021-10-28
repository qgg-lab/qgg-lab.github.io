---
title: Wen Huang Laboratory | Michigan State University
layout: pages
active: home
permalink: /index.html
---

## <center>Wen Huang Laboratory</center>  
### <center>Quantitative Genetics and Genomics</center>

<center><a href="http://www.ans.msu.edu" target="_blank">Department of Animal Science</a></center>
<center><a href="https://msu.edu" target="_blank">Michigan State University</a></center>

-----

### introduction

We are a lab of quantitative genetics and genomics, primarily in the model organism <i>Drosophila melanogaster</i> and livestock animals. We seek to understand why some cows produce more milk than others, or why some people are more prone to certain diseases than others, and questions of that nature. By doing that, we hope to be able to understand the biological processes underlying complex quantitative trait variation and eventually breed better animals and improve human health. We tackle these questions using a variety of approaches, including genetics, genomics, statistics, and bioinformatics.

### recruiting now | <a href="{{ site.baseurl }}/join.html">all opportunities</a>

<i class="fa fa-check-circle" aria-hidden="true" style="color:green"></i> Postdocs (see [ad]({{ site.baseurl }}/news/2021/09/01/postdoc.html)); <i class="fa fa-check-circle" aria-hidden="true"  style="color:green"></i> Graduate Students; <i class="fa fa-check-circle" aria-hidden="true"  style="color:green"></i> Undergraduate Students
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
- <a href="https://academic.oup.com/nar/advance-article/doi/10.1093/nar/gkab933/6413608" target="blank">MetazExp: a database for gene expression and alternative splicing profiles and their analyses based on 53 615 public RNA-seq samples in 72 metazoan species</a>, <i>Nucleic Acids Res</i>, 2021
- <a href="https://www.nature.com/articles/s41467-020-19131-y" target="blank">Genotype by environment interaction for gene expression in <i>Drosophila melanogaster</i></a>, <i>Nat Commun</i>, 2020
- <a href="https://genome.cshlp.org/content/early/2020/03/18/gr.257592.119.abstract" target="blank">Gene expression networks in the Drosophila Genetic Reference Panel</a>, <i>Genome Res</i>, 2020
- <a href="https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.3000645" target="blank">Context-dependent genetic architecture of Drosophila life span</a>, <i>PLOS Biol</i>, 2020
- <a href="https://doi.org/10.3389/fmicb.2020.00032" target="blank">Metagenomic characterization of intestinal regions in pigs with contrasting feed efficiency</a>, <i>Front Microbiol</i>, 2020
- <a href="https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-020-6472-9" target="blank">ASlive: a database for alternative splicing atlas in livestock animals</a>, <i>BMC Genomics</i>, 2020
- <a href="https://www.g3journal.org/content/10/1/109" target="blank">Influence of genetic interactions on polygenic prediction</a>, <i>G3</i>, 2020

### web servers

- <a href="https://bioinfo.njau.edu.cn/metazExp/" target="blank">MetazExp</a>: metazoan expression atlas
- <a href="http://aslive.org" target="blank">ASlive</a>: alternative splicing in livestock animals
- <a href="http://dgrp2.gnets.ncsu.edu" target="blank">DGRP</a>: GWAS in DGRP

### contact information
<i class="fa fa-envelope" aria-hidden="true" style="color:#18453b"></i> huangw53 AT msu.edu  
<i class="fa fa-phone" aria-hidden="true"  style="color:#18453b"></i> (517) 353-9136  
1205F Anthony Hall    
Michigan State University  
East Lansing, Michigan 48824


<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-145611606-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-145611606-1');
</script>
