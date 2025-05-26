# SelfConsistency
This library contain research code for evaluating and mitigating hallucination in LLMs.  
This research project was done as a final project for Natural Language Processing (NLP) course in TLV univesity by Maor Ivgi.

Researchers: Noa Mark and Yarden Frnakel. 

## Project abstract

State of the art models in abstractive summary frequently contain hallucinations (> 30%). Defining and evaluating hallucinations is an open challenge. There is no state-of-the-art metric for evaluation, and no clear protocol or method for mitigation. Recent work has been done in improving LLM generation through self-consistency. We wish to evaluate this method as a tool for mitigating hallucination, as well as suggesting our own decoding-based strategy to reduce factual inconsistency. Our model leverages LLM paraphrasing functionality to create multiple versions of the input document, thereby creating diversity in the output signal. This new way to create a self-ensemble model is aligned with the idea that summaries should be robust to paraphrasing. We found that both self-consistency and paraphrasing significantly improve the percentage of factual errors and extrinsic hallucination in the summaries. Additionally, there is no clear advantage to paraphrasing.

For a full review of this project please refer to [this document](https://github.com/MarkNoaTAU/SelfConsistency/blob/main/SelfConsistency%20and%20beyond%20in%20the%20search%20of%20decoding%20method%20for%20mitigating%20hallucinations.pdf).

