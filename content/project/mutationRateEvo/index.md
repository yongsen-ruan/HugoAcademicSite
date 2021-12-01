---
title: Mutation Rate Evolution
summary: Project on the evolution of mutation rate in soma and germline cell.
tags:
- mutation rate
- soma 
- germline
date: "2020-02-04T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo from the Internet
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/Yongsen_Ruan
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

---

Mutational process is fundamental to understanding many evolutionary phenomena. In a lifetime, mutation occurrence is usually treated as a simple Poisson process. This over-simplified assumption seems an inadequate foundation for realistic theories of such phenomena as the germline mutation rate (Kumar 2005; Lynch 2010; Scally and Durbin 2012; Sung, et al. 2012; Wielgoss, et al. 2013; Segurel, et al. 2014; Lynch, et al. 2016), or the evolution of sex (Charlesworth, et al. 2005).  

Mutation accumulation in the germline, like that observed in somatic tissues (Alexandrov, et al. 2015; Milholland, et al. 2015; Podolskiy, et al. 2016; Zhang, et al. 2019), is likely a time-inhomogeneous process. In particular, since some mutations are themselves mutators that increase the mutation rate, mutations should beget more mutations thus leading to runaway accumulation. While genes responsible for DNA repair are likely mutators, evidence suggests that a much larger number of mutations may increase the mutation rate in a subtle manner (Hung, et al. 2019). For example, any mutation that can influence the chromatin structure or the ion concentration can be a mutator if it can impair DNA polymerase and/or repair enzymes (Schuster-Bockler and Lehner 2012; El Meouche and Dunlop 2018). Unless held back by selection, the first mutator would start a runaway process and eventually greatly elevate the mutation rate. It will be shown that many weak mutators will trigger the runaway more quickly than a few strong ones, with the same aggregate mutation effect. 

In recent years, the accumulation of mutations in somatic tissues (including tumors) has been extensively recorded (Kandoth, et al. 2013; Lawrence, et al. 2013; Martincorena, et al. 2015; Blokzijl, et al. 2016; Ju, et al. 2017; Bae, et al. 2018; Lodato, et al. 2018; Chen, et al. 2019; Yizhak, et al. 2019). The main difference between germline and somatic mutations is that germline mutations are found in all cells of the progeny, whereas somatic mutations affect only local patches of tissues. The fitness consequences are drastically different. Indeed, somatic mutations experience such weak selection that the process is characterized as “quasi-neutral” (Chen, et al. 2019). As the runaway process is operative only when it is unchecked by natural selection, somatic mutations are ideal for such an investigation. 

In somatic cells, when the runaway mutational process is triggered, it may lead to tumorigenesis. Therefore, the end-products of runaway accumulation are different in the germline than in the soma. In the former, they are eliminated by natural selection but, in the latter, they prominently present themselves in tumors. In TCGA (The Cancer Genome Atlas) data, the mutation load varies by more than 1000-fold, even among cases of the same cancer type (Cancer Genome Atlas Research, et al. 2013; Kandoth, et al. 2013; Lawrence, et al. 2013). Hence, the distribution of the mutation load typically exhibits a very long tail (Fig. S1). This highly skewed distribution suggests something akin to a runaway process. 
 
For germline mutations, the mutation rate would be limited by natural selection due to their fitness consequences. Hence, how this limit is set has been a frequent topic in the literature (Sturtevant 1937; Kimura and Maruyama 1966; Leigh 1970; Drake 1991; Lynch 2008, 2010; Thomas, et al. 2010; Lynch 2011; Wielgoss, et al. 2013; Segurel, et al. 2014). Since the mutation rate may not stay constant in a lifetime, it might entail a low initial rate in order to reduce the likelihood of runaway accumulation. There are many evolutionary implications for avoiding the runaway process.

## ❤️ Related Research ❤️

- 👉 [**On the origin of SARS-CoV-2—The blind watchmaker argument**](https://link.springer.com/article/10.1007/s11427-021-1972-1)
- 📚 [**A theoretical exploration of the origin and early evolution of a pandemic**](https://www.sciencedirect.com/science/article/pii/S2095927320307659)
- 💬 Evidence of SARS-CoV-2 in Italy, [**November 2019**](https://wwwnc.cdc.gov/eid/article/27/2/20-4632_article) and [**September 2019**](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3883274)
- 💡 Others to be added