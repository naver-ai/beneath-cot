# BeneathCoT (EMNLP 2026 Main)


[Seogyeong Jeong](https://seogyeongjeong.github.io/), [Jaehui Hwang](https://j-h-hwang.github.io/), [Dongyoon Han](https://sites.google.com/site/dyhan0920/), [Geonmo Gu](https://geonm.github.io/), [Alice Oh†](https://aliceoh9.github.io/), [Taekyung Kim†](https://taekyungkim918.github.io)

<sub> (†corresponding authors) <br>

KAIST, [NAVER AI LAB](https://naver-career.gitbook.io/en/teams/clova-cic/ai-lab)

<br>


## Abstract

> Reasoning in large language models unfolds through diverse functional operations, such as problem formulation, goal decomposition, and deduction.
> Although these operations are explicitly distinguished in text, little is known about how they are geometrically organized in representation spaces.
> To this end, we investigate whether distinct reasoning operations exhibit corresponding geometric structure in hidden representations.
> We find that operations are separable in held-out representations, with separability peaking in middle layers, and verify that this structure is not explained by lexical or positional confounds.
> Across layers, token-wise operation-alignment becomes more distributed over spans, while identical surface tokens are represented differently depending on the operation of its surrounding chunk.
> Attention-masking interventions further show that operation-aligned representations at chunk onset depend on preceding reasoning context.
> Consequently, our work demonstrates that language models maintain representational correspondence between linguistic reasoning expressions and their internal geometric structures.
  
  
## Updates
  * (08/2026) BeneathCOT is accepted at EMNLP 2026 Main


## Code
* Code, models, and additional project materials will be released here soon.


## Citation
```
@inproceedings{
Jeong2026beneath,
title={Beneath the Surface of Chains-of-Thought: A Mechanistic Interpretation of Reasoning Operations in {LLM}s},
author={Jeong, Seogyeong and Hwang, Jaehui and Han, Dongyoon and Gu, Geonmo and Oh, Alice and Kim, Taekyung},
booktitle={The 2026 Conference on Empirical Methods in Natural Language Processing},
year={2026},
}
```
