# Kidney Stone Treatment Effectiveness Analysis: Exploring Simpson's Paradox

## Overview

![maxresdefault (3)](https://github.com/IrfanEzani/simpson-s-paradox/assets/59435235/f59abc87-7832-4514-91c1-ade87b8b5d8d)


This project delves into a classic case study of Simpson's Paradox, a statistical phenomenon where a trend apparent in several different groups of data disappears or reverses when these groups are combined. Utilizing a dataset from a 1986 study by a group of urologists in London, we examine the effectiveness of two kidney stone treatments: Treatment A (open surgery) and Treatment B (percutaneous nephrolithotomy). This analysis reveals how subgroup analysis can lead to different conclusions about treatment effectiveness, underscoring the importance of careful data interpretation in medical research.

Original paper: Charig CR, Webb DR, Payne SR, Wickham JE. Comparison of treatment of renal calculi by open surgery, percutaneous nephrolithotomy, and extracorporeal shockwave lithotripsy. Br Med J (Clin Res Ed). 1986 Mar 29;292(6524):879-82. doi: 10.1136/bmj.292.6524.879. 

## Dataset

The dataset comprises 700 patients who underwent treatments for kidney stones. It includes the following variables:
- `Treatment`: Type of treatment (A: open surgery, B: percutaneous nephrolithotomy)
- `Stone Size`: Size of the kidney stone (large, small)
- `Success`: Outcome of the treatment (1: success, 0: failure)

## Objectives

1. To compare the overall success rates of Treatment A and Treatment B.
2. To analyze the success rates of treatments by kidney stone size.
3. To demonstrate Simpson's Paradox in the context of treatment effectiveness.

## Methodology

The analysis involves:
- Descriptive statistics to summarize the overall and subgroup success rates.
- Chi-squared tests to examine the association between treatment type and success rates.
- Logistic regression to model the probability of treatment success, considering treatment type and stone size.
- Visualizations to illustrate the distribution of treatment outcomes and the impact of Simpson's Paradox.

## Results

<img width="460" alt="simpson-1" src="https://github.com/IrfanEzani/simpson-s-paradox/assets/59435235/0ce3c68c-c498-4d6e-bb7c-1ce1832f8ec6">
<img width="754" alt="simpson-2" src="https://github.com/IrfanEzani/simpson-s-paradox/assets/59435235/6b495b7e-1a0b-4373-89d9-4461828b5223">

Our analysis confirmed the presence of Simpson's Paradox in the dataset. While Treatment B showed a higher overall success rate, subgroup analysis revealed that Treatment A was more effective for both large and small kidney stones. This paradox highlights the critical role of stone size in determining the best treatment option and the necessity of subgroup analysis in medical research.

## Conclusions

The project emphasizes the importance of careful data analysis in healthcare, particularly when making treatment decisions. It also serves as a practical example of Simpson's Paradox, illustrating how aggregated data can mask important subgroup differences. Future research should consider additional factors that may influence treatment outcomes, such as patient health status and specific treatment protocols.

## How to Run the Analysis

Code runs on R.
