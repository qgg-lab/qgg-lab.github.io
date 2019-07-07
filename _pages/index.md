---
title: Wen Huang Laboratory | Michigan State University
layout: pages
active: home
permalink: /index.html
---

##<center>Wen Huang Laboratory</center>  
###<center>Quantitative Genetics and Genomics</center>

<center><a href="http://www.ans.msu.edu" target="_blank">Department of Animal Science</a></center>
<center><a href="https://msu.edu" target="_blank">Michigan State University</a></center>

-----

### introduction

We are a lab of quantitative genetics and genomics, primarily in livestock animals. We seek to understand why some cows produce more milk than others, or why some people are more prone to certain diseases than others, and questions of that nature. By doing that, we hope to be able to understand the biological processes underlying complex quantitative trait variation and eventually breed better animals. We tackle these questions using a variety of approaches, including genetics, genomics, statistics, and bioinformatics.

###  news (<a href="{{ site.baseurl }}/news.html">all news</a>)

<ul>
  {% for news in site.categories.news limit:3 %}
    <li>
      <a href="{{ site.baseurl }}{{ news.url }}">{{ news.date | date: "%m-%d-%Y" }}</a>: {{ news.title }}
    </li>
  {% endfor %}
</ul>



###recent papers (<a href="{{ site.baseurl }}/publications.html">all papers</a>)

- <a href="https://www.biorxiv.org/content/10.1101/667162v1" target="blank">bioRxiv, 2019</a>: Influence of genetic interactions on polygenic prediction.
- <a href="http://onlinelibrary.wiley.com/doi/10.1002/wdev.289/abstract;jsessionid=6F725723A288BD00731A427C18A25DD5.f04t04" target="blank">WIREs Developmental Biology, 2018</a>: Charting the genotype–phenotype map: lessons from the <i>Drosophila melanogaster</i> Genetic Reference Panel
- <a href="http://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1006421" target="_blank">PLoS Genetics, 2016</a>: The genetic architecture of quantitative traits cannot be inferred from variance component analysis.

### contact information
<i class="fa fa-envelope" aria-hidden="true"></i> huangw53 AT msu.edu  
<i class="fa fa-phone" aria-hidden="true"></i> (517) 353-9136  
1205F Anthony Hall    
Michigan State University  
East Lansing, Michigan 48824

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-89481897-2', 'auto');
  ga('send', 'pageview');

</script>
