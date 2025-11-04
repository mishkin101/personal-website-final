> [!abstract]- Conversational Derailment in Dispute Resolution
> - This repository contains a tailored implementation of the [Conversational Recurrent Architecture for ForecasTing (CRAFT)](https://github.com/jpwchang/CRAFT) neural model, originally introduced in the EMNLP 2019 paper [Trouble on the Horizon: Forecasting the Derailment of Online Conversations as they Develop](https://arxiv.org/abs/1909.01362) to the dispute resolution domain. We pre-train the CRAFT model architecture with a custom corpus of [CaSiNo](https://aclanthology.org/2021.naacl-main.254.pdf), [Deal no Deal](https://aclanthology.org/D17-1259/), and [KODIS](https://arxiv.org/html/2504.12723v1) dialogs and fine-tune on the **KODIS** dataset to research whether we can learn unsupervised representation of conversational dynamics in negotiation-based dialogues and exploit the structure via supervised learning for predicting for outcomes in Dispute resolution (KODIS).
> 
>  ### [Github Project](https://github.com/mishkin101/CRAFT_Disputes)
>>[!info] #PyTorch #NLP #MLFlow #RayTune 

^fb921f

>[!abstract]- CRAFT NLP Model: Evaluating Utterance Exposure and Imbalance Strategies on fine-tuning performance for derailment prediction
>  
>  - This project analyzes the model sensitivity to utterance variations and imbalance handling on **9 model variants**. We determine whether CRAFT is a good predictor of conversation-level derailment on [KODIS](https://arxiv.org/html/2504.12723v1) using [Conversations Gone Awry Dataset (CGA-WIKI)](https://convokit.cornell.edu/documentation/awry.html)as a baseline comparison. We compares variants using **standard classification metrics (F1, AUC, Calibration Curves)** at each model’s **Youden-optimized threshold** on the **same Ground test set (CGA-WIKI**), with additional diagnostics (horizons, distributions, frustration correlation, token analysis) to interpret differences.
> - ==Including the submit agreement utterance makes KODIS fine-tuned models more prone to forecasting similar derailment scores for all conversations leading to missed conversation dynamics==
>  
>  ### [Presentation](https://arxiv.org/html/2504.12723v1) | [Github](https://github.com/mishkin101/ConvoKit_Disputes)
>>[!info] #PyTorch #NLP #explainability

^beb7f8

