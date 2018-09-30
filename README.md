# KARL-Fast-Kernel-Aggregation-Queries
Before you run or read our codes, please make sure you understand the concept of our paper and also read the supplementary notes (KARL_supplementary.pdf) in this github.

Please note that the folder "Publish_codes.zip" is not the library but it is only used for testing in our publication. We are still developing/ integrating the codes to the KARL library. We will release the library soon, probably before the ICDE2019 presentation, 8th April,2019. We hope to integrate more machine learning models/ more kernel functions into this library.

In our Publish_codes.zip, there are three folders which are:

"Type_I_epsilon" This one is for kernel density estimation model with relative error epsilon

"Type_I_II_tau" This one is for kernel density classification and 1-class SVM models

"Type_III_tau" This one is for 2-class SVM model

In each file, there is one shell script called "KARL_demo.sh". It will automatically run three different methods, SCAN, SOTA and KARL in one dataset. Unfortunately, the size of the datasets is large and thus, we cannot put them inside the Github. If you need the dataset, please contact me (just call me Edison) via the following email addresses "edisonchan2013928@gmail.com" or "cstnchan@comp.polyu.edu.hk" or "tnchan2@cs.hku.hk".

In the "KARL_demo.sh" of "Type_I_epsilon" folder, this includes how to use the auto-tuning method. This method can be also used for other models (e.g. "Type_I_II_tau" and "Type_III_tau").
