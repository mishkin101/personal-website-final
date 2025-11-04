> [!abstract]- Multivariate Time Series Classification - Activity Data from Wireless Sensor Network
> - This project tackles human-activity recognition on the [UCI AReM wireless-sensor dataset](https://archive.ics.uci.edu/dataset/366/activity+recognition+system+based+on+multisensor+data+fusion+arem) using a classical multivariate time-series pipeline. Time-domain features are engineered per channel and within-instance dynamics are captured by segmenting each series into ℓ chunks. Models compare (i) binary bending vs. non-bending using p-value-guided RFE + logistic regression vs. L1-penalized LR, and (ii) multiclass activity recognition using multinomial LR (L1) and Naive Bayes, with a Gaussian NB + PCA variant to decorrelate features. Selection and evaluation use nested/outer CV with ROC/AUC, accuracy, and confusion matrices. 
> - ==Adding PCA to a Gaussian NB pipeline improved multiclass CV test accuracy to .84==
>  ### [**Presentation**](https://mishkin101.github.io/Multivariate-Time-Series-Classification-Human-Activity-Data-from-Wireless-Sensor-Network/) | [Github](https://github.com/mishkin101/Multivariate-Time-Series-Classification-Human-Activity-Data-from-Wireless-Sensor-Network) 
> > [!info] #timeseries #naivebayes #scikit-learn #logisticregression

^4cfb39

