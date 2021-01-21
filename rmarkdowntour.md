---
title: "A Brief R Markdown Tour"
author: "Matteo Rizzuto"
date: "January 26, 2021"
output: 
  ioslides_presentation:
    widescreen: true
    logo: lablogo.png
    css: styles.css
    self_contained: true
    keep_md: true
---

# Roadmap

## Roadmap {.smaller .build}
- Philosophy
- What is R Markdown?
- Why R Markdown?
- Basics of R Markdown
     + Installation
     + Plain text and Code Chunks
     + Figures and Tables
     + Output
- Advanced Stuff
     + References and Bibliographies
     + Interactive Figures
     + Look and Feel

# Philosophy

## What is writing?
<img src="writing1.png" width="75%" style="display: block; margin: auto;" />

## What is writing?
<img src="writing2.png" width="75%" style="display: block; margin: auto;" />

## What is writing?
<img src="writing3.png" width="75%" style="display: block; margin: auto;" />

## What is writing? {.build}

Really, all three. Software-wise, this translates into two main schools:

- **WYSIWYG**--_What You See Is What You Get_: word processing software, e.g. Microsoft Word^1^

- **WISIWIT**--_What I See Is What I Type_: typesetting software, e.g. LaTeX^1^

<div class="footer" style="margin-top:-100px;font-size:80%;">
^1^[https://en.wikipedia.org/wiki/WYSIWYG](WYSIWYG Wikipedia page)</div>

##

<img src="feelings.gif" width="75%" style="display: block; margin: auto;" />

# What is R Markdown?

## What is R Markdown? {.build}

R Markdown is a file format for making **dynamic documents** with R. 
An R Markdown document is written in markdown and contains chunks of embedded code.

Ok, what's markdown? 

Markdown^2^ is a **plain text** formatting syntax: you can read markdown in its source format and still understand it (in fact, you are doing just that). 

<div class="footer" style="margin-top:-100px;font-size:80%;">
^1^[https://www.markdownguide.org](https://www.markdownguide.org)</div>

--- 

<img src="mddocx.png" width="90%" style="display: block; margin: auto;" />

# Why R Markdown?

## Why R Markdown?

<div class="columns-2">
Practical reasons

- Simple
- Powerful
- Transferable
- Adaptable
- Version Control
- Free

Philosophical reasons

- WYSIWYG vs. WISIWIT
- Let's you focus on the writing
- Open
- Transparent
- Stable
</div>
 

## {data-background=foo.png data-background-size=cover}




```r
plot(cars)
```

![](rmarkdowntour_files/figure-html/unnamed-chunk-6-1.png)<!-- -->

Add a new chunk by clicking the *Insert Chunk* button on the toolbar or by pressing *Cmd+Option+I*.

When you save the notebook, an HTML file containing the code and output will be saved alongside it (click the *Preview* button or press *Cmd+Shift+K* to preview the HTML file). 

The preview shows you a rendered HTML copy of the contents of the editor. Consequently, unlike *Knit*, *Preview* does not run any R code chunks. Instead, the output of the chunk when it was last run in the editor is displayed.





## R Markdown

This is an R Markdown presentation. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document.

## Slide with Bullets

- Bullet 1
- Bullet 2
- Bullet 3

## Slide with R Output


```r
summary(cars)
```

```
##      speed           dist       
##  Min.   : 4.0   Min.   :  2.00  
##  1st Qu.:12.0   1st Qu.: 26.00  
##  Median :15.0   Median : 36.00  
##  Mean   :15.4   Mean   : 42.98  
##  3rd Qu.:19.0   3rd Qu.: 56.00  
##  Max.   :25.0   Max.   :120.00
```

## Slide with Plot

![](rmarkdowntour_files/figure-html/pressure-1.png)<!-- -->

