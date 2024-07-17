---
title: "Strong hallucinations from negation and how to fix them"
category: articles
permalink: /articles/negation/
venue: "Findings of ACL 2024"
excerpt: 'Despite great performance on many tasks, language models (LMs) still struggle with reasoning, sometimes providing responses that cannot possibly be true because they stem from logical incoherence. We call such responses strong hallucinations and prove that they follow from its computation of its internal representations for logical operators and outputs from those representations'
date: 2024-08-17
citation: 'Asher, Nicholas, and **Swarnadeep Bhar**. "Strong hallucinations from negation and how to fix them." arXiv preprint arXiv:2402.10543 (2024).'
---
<a href='https://swarnadeep8597.github.io/papers/Why_large_language_models_hallucinate.pdf'>Download PDF here</a>

Abstract: Despite great performance on many tasks, language models (LMs) still struggle with reasoning, sometimes providing responses that cannot possibly be true because they stem from logical incoherence. We call such responses strong hallucinations and prove that they follow from an LM's computation of its internal representations for logical operators and outputs from those representations. Focusing on negation, we provide a novel solution in which negation is treated not as another element of a latent representation, but as an operation over an LM's latent representations that constrains how they may evolve. We show that our approach improves model performance in cloze prompting and natural language inference tasks with negation without requiring training on sparse negative data.

BibTeX citation: @misc{asher2024stronghallucinationsnegationfix,
      title={Strong hallucinations from negation and how to fix them}, 
      author={Nicholas Asher and Swarnadeep Bhar},
      year={2024},
      eprint={2402.10543},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2402.10543}, 
}
