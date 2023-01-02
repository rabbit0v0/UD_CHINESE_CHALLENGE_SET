# UD_CHINESE_CHALLENGE_SET

Description: 40+40+20+40=140 sentences in four templates.

Based on the contextless syntactic ambiguity dataset of commonMT from https://github.com/tjunlp-lab/CommonMT. The sentenses have ambiguities resolved by selectional preferences and commonsense reasoning, which can be inferred from their dependency trees.

The templates include:
- [VERB][NOUN1][ATV][NOUN2]
- [NUM][CLF][NOUN1]([ADP])[ATV][NOUN2]
- [VERB][PFV][NUM][CLF][NOUN]
- [NOUN1][CCONJ][NOUN2][ATV][NOUN3] or [NOUN1][ATV][NOUN2][CCONJ][NOUN3]

In our templates, ATV is 的(de), CLF is the classifier in the quantifier phrases like 个(ge), PFV is 了(le). Reference: https://link.springer.com/article/10.1007/s10579-021-09564-2



