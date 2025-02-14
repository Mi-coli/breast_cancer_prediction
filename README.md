# breast_cancer_prediction
This is a sample problem used for a job interview panel presentation with the aim of explaining a technical concept to a non-technical audience. I decided to go with a breast cancer classification model since this is a good way to not only demonstrate a basic algorithm, but to also highlight the importance of understanding your results. More specifically, since no model will ever have 100% accuracy, we are always left having to make decisions of how to address the false positives and false negatives. In situations such as breast cancer identification, where the model decides which patient needs a followup with an oncologist, it is always better to have an aggressive model that will overpredict and flag patients with non-cancerous cells as needing checkups than having a model that will underpredict and not flag some patients that do have cancer. While this type of overprediction is necessary in the context of diseases, it may not be true for other applications, which is why domain knowledge is just as important as technical.


Background:

Roughly 350,000 people get diagnosed with breast cancer every year, and once the diagnosis has been made, it is critical to quickly determine whether the lump is benign (non-cancerous) or malignant (cancerous). The only way of determining this (at the time of this post) is for a biopsy to be performed, which consists of extracting a lump sample and evaluating the present cells for abnormalities. There are many factors that come into play when making a decision for whether or not the growth is cancerous or not, and time plays a huge factor in this decision because the sooner the treatment can take place, the higher the chances for survival.

This model uses the results from about 550 patients, all whom have gone through a FNA (Fine Needle Aspiration) biopsy, and uses the data from cells that were recovered from these samples to learn what features are associated with a benign versus malignant diagnosis. 

The goal of this research is to provide a more effective screening method that could assist clinicians in making a correct decision when it comes to cancer patient's treatment plans.
