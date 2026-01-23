---
title: 🚀 Another new preprint!
author: jochen-weile
tags: publication
image: images/news/20260122_publication.png
---

Today we share another [new preprint publication](https://www.medrxiv.org/content/10.64898/2026.01.19.26344287v1). In this paper, we compared LLM-based information extraction tools with respect to how suitable they are for extracting data from clinical documents. 

We hope this work will empower researchers to make available the valuable data locked away in PDF documents and hardcopies still prevalent in health care. 

We evaluated the tools in terms of usability, accuracy, robustness, and privacy. 

{%
  include figure.html
  image="images/news/20260122_benchmark.png"
  caption="Benchmark results for the tested tools.
    A) The proportion of interpretable \gls{json} outputs for each tested tool. \\
    B) Mean \fscore\ scores of tools split by prompt and input modality. Error bars indicate standard error. Brackets indicate Mann-Whitney-U tests, where *** represents $p < 0.001$. NuExtract and GliNER are color-coded as zero-shot here although they do not technically receive natural language prompts.\\
    C) Differences in mean \fscore\ between zero-shot and one-shot prompts (left) and \gls{ocr}-derived text and direct image input, respectively, for each applicable tool.\\
    D) Distributions of \fscore\ scores for tested models by input modality (image vs \gls{ocr}-derived text) and input quality (clean PDF vs fax-simulated)."
  height="300px"
%} 

Special thanks goes to Aaron Yu, who worked on this project as a summer student last year.
