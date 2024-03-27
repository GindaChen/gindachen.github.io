---
slug: launch
title: |
    Launching 🚀
draft: false
date: "2024-03-25"
description: "Hello world! Launching my first blog post (placeholder?)"
tags:
  - info
ShowToc: true
cover:
  image: images/post-cover.jpg
  caption: "\"Launch\". Taken in 2024/03/18 when SpaceX Falcon 9 rocket launches. Credit: @GindaChen"
---

## Finally started my blog!
Just a place holder here for now. I finally got the chance to start my blog. I have always wanted to write about my thoughts and experiences, but everytime I wanted to do so, I was either interrupted by work & other commitments, or simply picking the right theme for too long until I time out. This time, I'm just allocating a whole day to find somewhere to start my journey. The blog theme is going to change a lot - we will come back to those improvements later.


## First try: Hugo + PaperModX
PaperModX is a pretty nice fork from PaperMod theme. I like the simplicity and the clean design, but also the flexibility to customize it. Compared to the jekelly (which has a beautiful [`alfolio`](https://github.com/alshedivat/al-folio) theme), Hugo is generally fast to build (so I chose Hugo); and compared to other themes, the PaperMod family is simply and clean, thus allowing me to customize it easily. 

## Next Step: Enhancements
There are still a pile of todos while I'm setting up the blog:
- [ ] Text color. In dark mode, clicking "publication" in the nav bar will make the text "disappear" because the text color is black.
- [x] Search. The search function is not working. I need to figure out how to make it work.
- [ ] Theme color. Maybe find a better theme color for the webpage. Even better, we can let user tweak the variable in runtime.
- [ ] Profile page name text color. The dark / white is a little to pale. 
- [ ] Adding more color theme for papermod. I need higher constrast theme to work better.
- [ ] Version control for article. Can I have a version control system (for reader) to see how the article has changed over time? It would be sooo cool to compare what has changed (diff) and a time-machine-like feature to visualize how the article evolves.
- [ ] Profile page photo will be squashed when the width is too small. Maybe set a min width is helpful.
- [ ] Profile page layout. The layout is centralized, and the flow of text isn't that good. Maybe we can make it better.
- [x] Profile page + selected publications. 
- [ ] Adding a single script to produce publication list. I used `scholarly` to produce part of the publications, but the workflow isn't as smooth as I expected yet.
- [ ] General theme and layout. I always feel a little weird about the styling of the webpage. For example, why is there a bullt in front of the todo item? Why can't I click the todo box to mark it as done (in html)? 
- [ ] Add comment services.
- [ ] Add a "like" button for each article.
- [ ] Add a GPT to "summarize" / "shorten". Maybe we can use [MLC](https://webllm.mlc.ai/) to do the computation on browser?

## Future: What to write?

I have always imagined my blog to be a place where I can share thoughts, show some cool stuff, and some small ideas in progress to the world. 
- [ ] Write a mini LLM serving engine from scratch. Engines like [vLLM](https://vllm.ai/), [SGLang](https://lmsys.org/blog/2024-01-17-sglang/), [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) are cool but monsterous (for many). Having a mini version of it would be cool. See if we have the chance to evolve the serving sytem from static batching -> adding DP -> adding TP -> adding PP -> adding [continuous batching](https://www.anyscale.com/blog/continuous-batching-llm-inference), and finally to our [model disaggregation](https://hao-ai-lab.github.io/blogs/distserve/). Is this already a pretty standard project for LLM system course?
- [ ] Inter-galatic scale super computing as the next-level (artificial?) intelligence. We all know the energy on earth is limited, and the computation power is limited. What if we can build a super computer center on Mars, or other planets (and this idea already "seems" tractable in the near future). What if we deploy a disaggregaetd computing system on the entire solar system, and use the energy from the sun, or even the energy from the black hole, to power our computation? Further more, what if we can deploy computation across the galaxy? Now - what about inter-galatic? What will these computation become?
- [ ] After AGI. OpenAI will bring AGI into reality in 5 years!! Soon (or hopefully after the time I graduate my PhD 😭) we will enter the world where AGI becomes prevalent. Will human be liberated? Will wars continue or end permanently? If we lose our job (or if human no long need to "work"), what will human become and what do we do for a living? What is the social structure? What is the limitation of human knowledge and creativity, and how do we accept it if we can reason about it?