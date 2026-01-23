---
title: 🚀 Another new preprint!
author: jochen-weile
tags: publication
image: images/news/20260122_publication.png
---

Today we share another [new preprint publication](https://www.medrxiv.org/content/10.64898/2026.01.19.26344287v1). In this paper, we compared LLM-based information extraction tools with respect to how suitable they are for extracting data from clinical documents. 

We hope this work will empower researchers to make available the valuable data locked away in PDF documents and hardcopies still prevalent in health care. 

We evaluated the tools in terms of usability, accuracy, robustness, and privacy. We found local multimodal LLMs like Gemma3 and NuExtract to be the best options.

{%
  include figure.html
  image="images/news/20260122_benchmark.png"
  caption="Benchmark results for the tested tools. A) The proportion of interpretable JSON outputs for each tested tool. B) Mean F<sub>1</sub> scores of tools split by prompt and input modality. Error bars indicate standard error. Brackets indicate Mann-Whitney-U tests, where *** represents p < 0.001$ NuExtract and GliNER are color-coded as zero-shot here although they do not technically receive natural language prompts. C) Differences in mean F<sub>1</sub> between zero-shot and one-shot prompts (left) and OCR-derived text and direct image input, respectively, for each applicable tool. D) Distributions of F<sub>1</sub> scores for tested models by input modality (image vs OCR-derived text) and input quality (clean PDF vs fax-simulated)."
  height="300px"
%} 

Special thanks goes to [Aaron Yu](/members/aaron-yu.html), who worked on this project as a summer student last year.
