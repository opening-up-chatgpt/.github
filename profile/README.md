# [![](/openchatgpt-logo-favicon-red-on-transparent.png)](https:///opening-up-chatgpt.github.io/) Opening up ChatGPT — [openness leaderboard](https://opening-up-chatgpt.github.io/) | [ repo](https://github.com/opening-up-chatgpt/opening-up-chatgpt.github.io)


**FAccT'24:** Liesenfeld, Andreas, and Mark Dingemanse. 2024. ‘Rethinking Open Source Generative AI: Open-Washing and the EU AI Act’. In _The 2024 ACM Conference on Fairness, Accountability, and Transparency_ (FAccT ’24). Rio de Janeiro, Brazil: ACM. ([PDF](https://pure.mpg.de/pubman/item/item_3588217_2/component/file_3588218/liesenfeld_dingemanse_2024_FAccT_generative_AI_open-washing_EU_AI_Act.pdf)).

>  The past year has seen a steep rise in generative AI systems that claim to be open. But how open are they really? The question of what counts as open source in generative AI is poised to take on particular importance in light of the upcoming EU AI Act that regulates open source systems differently, creating an urgent need for practical openness assessment. Here we use an evidence-based framework that distinguishes 14 dimensions of openness, from training datasets to scientific and technical documentation and from licensing to access methods. Surveying over 45 generative AI systems (both text and text-to-image), we find that while the term open source is widely used, many models are `open weight' at best and many providers seek to evade scientific, legal and regulatory scrutiny by withholding information on training and fine-tuning data. We argue that openness in generative AI is necessarily composite (consisting of multiple elements) and gradient (coming in degrees), and point out the risk of relying on single features like access or licensing to declare models open or not. Evidence-based openness assessment can help foster a generative AI landscape in which models can be effectively regulated, model providers can be held accountable, scientists can scrutinise generative AI, and end users can make informed decisions. 

**CUI'23**: Liesenfeld, Andreas, Alianda Lopez, and Mark Dingemanse. 2023. “Opening up ChatGPT: Tracking Openness, Transparency, and Accountability in Instruction-Tuned Text Generators.” In _Proceedings of the 5th International Conference on Conversational User Interfaces_. Eindhoven. doi:[10.1145/3571884.3604316](https://doi.org/10.1145/3571884.3604316). ([PDF](https://pure.mpg.de/pubman/item/item_3526897_1/component/file_3526898/Liesenfeld%20et%20al_2023_Opening%20up%20ChatGPT.pdf))

> Large language models that exhibit instruction-following behaviour represent one of the biggest recent upheavals in conversational interfaces, a trend in large part fuelled by the release of OpenAI's ChatGPT, a proprietary large language model for text generation fine-tuned through reinforcement learning from human feedback (LLM+RLHF). We review the risks of relying on proprietary software and survey the first crop of open-source projects of comparable architecture and functionality. The main contribution of this paper is to show that openness is differentiated, and to offer scientific documentation of degrees of openness in this fast-moving field. We evaluate projects in terms of openness of code, training data, model weights, reinforcement learning data, licensing, scientific documentation, and access methods. We find that while there is a fast-growing list of projects billing themselves as 'open source', many inherit undocumented data of dubious legality, few share the all-important RLHF components (a key site where human annotation labour is involved), and careful scientific documentation is exceedingly rare. Degrees of openness are relevant to fairness and accountability at all points, from data collection and curation to model architecture, and from training and fine-tuning to release and deployment. 

```bibtex

@inproceedings{liesenfeld_opening_2023,
	address = {Eindhoven},
	title = {Opening up {ChatGPT}: tracking openness, transparency, and accountability in instruction-tuned text generators},
	url = {https://opening-up-chatgpt.github.io},
	doi = {10.1145/3571884.3604316},
	booktitle = {Proceedings of the 5th {International} {Conference} on {Conversational} {User} {Interfaces}},
	publisher = {Association for Computing Machinery},
	author = {Liesenfeld, Andreas and Lopez, Alianda and Dingemanse, Mark},
	year = {2023},
	pages = {1--6},
}

```

# Guide
We have three things here:
1. A [live table](https://opening-up-chatgpt.github.io/) of open LLM+RLHF projects with fine-grained data on degrees of openness
2. A repository holding [the underlying data](https://github.com/opening-up-chatgpt/opening-up-chatgpt.github.io/tree/main/projects), in human readable yaml files open for community contributions
