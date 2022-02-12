# Survey_slides

This repository is used to store Transformer survey slides and update the proposed modular learning slides.

## Transformer_survey.pptx
This is the main survey slides about Transformers. It includes a brief introduction of Transformer structure and four topics related to Transformers, including the adaptations of self-attention module, model compression techniques, learning paradigms in Transformers and applications of Transformers in different domains.

Since the references are too many, we omit the citation of these links. While there are three high-quality and high-level works about Transformers which guided this slides:

[A Survey of Transformers](https://arxiv.org/abs/2106.04554)

[Pre-trained Models for Natural Language Processing: A Survey](https://arxiv.org/abs/2003.08271)

[A Generalization of Transformer Networks to Graphs](https://arxiv.org/abs/2012.09699)

## Signal Decomposition and Modular Learning.pptx
This is the updated proposal about signal decomposition. These days I emailed to some authors of related works and discussed with some of them, getting many new enlightening opinions and added to the new slides.

## DeBERTa.pptx & ∞-former.pptx
These are two individual papers that interest me. The first proposed a GAN-style pretraining method that fully utilize training data, and some ideas about embedding signal disentangling are promising for our proposal. The second is about signal continurization which is beneficial when processing extremely long input data, sacrificing resolution for computational efficency.

## Pretraining with dictionaries.pptx
This is another idea that I recently came up with, while it seems no other work can be cited as reference. I would like to use dictionaries, a well-structured weakly supervising data to improve pretraining efficiency. This is similar to how we human learn a new language: to learn a new word, see its definition, syn/ant ( for better spatial representation ) and example sentences, while current pretraining methods only utilize example sentences. A related work is ConceptNet, a common sense KG aiming at improving embedding quality, while they are derived from different motivations.
