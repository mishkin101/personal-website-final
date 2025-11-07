>[!abstract]- CRAFT NLP Model: Evaluating Utterance Exposure and Imbalance Strategies on fine-tuning performance for derailment prediction
>  
>  - This project analyzes the model sensitivity to utterance variations and imbalance handling on **9 model variants**. We determine whether CRAFT is a good predictor of conversation-level derailment on [KODIS](https://arxiv.org/html/2504.12723v1) using [Conversations Gone Awry Dataset (CGA-WIKI)](https://convokit.cornell.edu/documentation/awry.html)as a baseline comparison. We compares variants using **standard classification metrics (F1, AUC, Calibration Curves)** at each model’s **Youden-optimized threshold** on the **same Ground test set (CGA-WIKI**), with additional diagnostics (horizons, distributions, frustration correlation, token analysis) to interpret differences.
> - ==Including the submit agreement utterance makes KODIS fine-tuned models more prone to forecasting similar derailment scores for all conversations leading to missed conversation dynamics==
>  
>  ### [Presentation](https://mishkin101.github.io/ConvoKit_Disputes/src/fine-tuning_analysis.html) | [Github](https://github.com/mishkin101/ConvoKit_Disputes)
>>[!info] #PyTorch #NLP #explainability 
>>

^965d1e
