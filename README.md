# KARL-Fast-Kernel-Aggregation-Queries
Before you run or read our codes, please make sure you understand the concept of our paper and also read the supplementary notes (KARL_supplementary.pdf) in this github.

Please note that the folder "Publish_codes.zip" is not the library but it is only used for testing in our publication. The folder "KARL_library.zip" is the library (version 0) which integrates the prediction phase of all different models. In the future, we hope to support more machine learning models/ kernel functions. Moreover, we also hope to support more interesting applications using kernel functions.

In our Publish_codes.zip, there are three folders which are:

"Type_I_epsilon" This one is for kernel density estimation model with relative error epsilon

"Type_I_II_tau" This one is for kernel density classification and 1-class SVM models

"Type_III_tau" This one is for 2-class SVM model

In each file, there is one shell script called "KARL_demo.sh". It will automatically run three different methods, SCAN, SOTA and KARL in one dataset. Unfortunately, the size of the datasets is large and thus, we cannot put them inside the Github or send these datasets via email. However, those datasets we used are from the UCI Machine learning repository and LibSVM website. Therefore, you can download the datasets from those webpages. If you have any questions, please contact me (just call me Edison) via the following email addresses "edisonchan2013928@gmail.com" or "cstnchan@comp.polyu.edu.hk" or "tnchan@cs.hku.hk" or "tnchan2@hku.hk".

In the "KARL_demo.sh" of "Type_I_epsilon" folder, this includes how to use the auto-tuning method. The similar scripts can be also used for other models (e.g. "Type_I_II_tau" and "Type_III_tau").

Please also check the webpage https://edisonchan2013928.github.io/My-homepage/ for my recent publications. We are happy that some related studies [a],[b] have been accepted in the prestigious conference and journal.

[a] Tsz Nam Chan, Reynold Cheng, Man Lung Yiu. "QUAD: Quadratic-Bound-Based Kernel Density Visualization" Proceedings of ACM Conference on Management of Data (SIGMOD), 2020. (https://edisonchan2013928.github.io/My-homepage/publication/QUAD.pdf) (Code: "https://github.com/edisonchan2013928/QUAD-for-Kernel-Density-Visualization-KDV-")

[b] Tsz Nam Chan, Leong Hou U, Reynold Cheng, Man Lung Yiu, Shivansh Mittal. "Efficient Algorithms for Kernel Aggregation Queries" IEEE Transactions on Knowledge and Data Engineering (TKDE), To appear. ("https://edisonchan2013928.github.io/My-homepage/publication/KARL_AK.pdf") (Code: "https://github.com/edisonchan2013928/Fast-Prediction-for-Additive-Kernels-Using-KARL")
