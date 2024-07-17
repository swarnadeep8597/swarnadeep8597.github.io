---
title: "Analyzing semantic faithfulness of language models via input intervention on conversational question answering"
category: articles
permalink: /articles/semantic_faithfulness/
venue: "Computational Linguistics"
excerpt: 'Transformer-based language models have been shown to be highly effective for several NLP tasks. In this article, we consider three transformer models, BERT, RoBERTa, and XLNet, in both small and large versions, and investigate how faithful their representations are with respect to the semantic content of texts. We formalize a notion of semantic faithfulness, in which the semantic content of a text should causally figure in a model’s inferences in question answering'
date: 2024-03-01
citation: 'Chaturvedi, A., **Bhar, S.**, Saha, S., Garain, U., & Asher, N. (2024). Analyzing Semantic Faithfulness of Language Models via Input Intervention on Question Answering. Computational Linguistics, 50(1), 119-155.'
---
<a href='https://swarnadeep8597.github.io/papers/sem_faith.pdf'>Download PDF here</a>

Abstract: Transformer-based language models have been shown to be highly effective for several NLP tasks. In this article, we consider three transformer models, BERT, RoBERTa, and XLNet, in both small and large versions, and investigate how faithful their representations are with respect to the semantic content of texts. We formalize a notion of semantic faithfulness, in which the semantic content of a text should causally figure in a model’s inferences in question answering. We then test this notion by observing a model’s behavior on answering questions about a story after performing two novel semantic interventions—deletion intervention and negation intervention. While transformer models achieve high performance on standard question answering tasks, we show that they fail to be semantically faithful once we perform these interventions for a significant number of cases (∼ 50% for deletion intervention, and ∼ 20% drop in accuracy for negation intervention). We then propose an intervention-based training regime that can mitigate the undesirable effects for deletion intervention by a significant margin (from ∼ 50% to ∼ 6%). We analyze the inner-workings of the models to better understand the effectiveness of intervention-based training for deletion intervention. But we show that this training does not attenuate other aspects of semantic unfaithfulness such as the models’ inability to deal with negation intervention or to capture the predicate–argument structure of texts. We also test InstructGPT, via prompting, for its ability to handle the two interventions and to capture predicate–argument structure. While InstructGPT models do achieve very high performance on predicate–argument structure task, they fail to respond adequately to our deletion and negation interventions.

BibTeX citation: @misc{asher2024stronghallucinationsnegationfix,
      title={Strong hallucinations from negation and how to fix them}, 
      author={Nicholas Asher and Swarnadeep Bhar},
      year={2024},
      eprint={2402.10543},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2402.10543}, 
}
