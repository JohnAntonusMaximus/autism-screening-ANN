# Austism Screening - ANN w/ F1 Scores & Classification Report

[![Tensorflow](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT7b9ZDD7lMdkByT-f_RCAqSQYqnq_CpgD16IFrwfmUwWCmdt7H)](https://www.tensorflow.org/beta/guide/effective_tf2)


[![Colab](https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/drive/1S8f4hF8THBFDhuNztAQ6vRFWqaq-IAsM?usp=sharing)

## Background

Autistic Spectrum Disorder (ASD) is a neurodevelopment  condition associated with significant healthcare costs, and early diagnosis can significantly reduce these. Unfortunately, waiting times for an ASD diagnosis are lengthy and procedures are not cost effective. The economic impact of autism and the increase in the number of ASD cases across the world reveals an urgent need for the development of easily implemented and effective screening methods.

Parents and doctors face a difficult dilemma when it comes to detecting and treating autism spectrum disorder (ASD) in children.

It’s critically important to diagnose ASD as early in a child’s development as possible. Starting treatment for ASD at an age of 18 to 24 months can increase a child’s IQ by up to 17 points—in some cases moving them into the “average” child IQ range of 90-110 (or above it)—and, in turn, significantly improving their quality of life. What’s more, early intervention can save someone with ASD up to $1.2 million in lifetime medical costs, according to Geraldine Dawson, director of the Duke Center for Autism and Brain Development.

But the current process of early screening isn’t very accurate because it relies on a questionnaire that parents answer about their child’s behavior (usually at the child’s 18 month checkup). And these questionnaires often produce false positives. In fact, of the children whose parents report early signs of ASD on the questionnaire, Dawson says only 50 percent have that diagnosis confirmed by a licensed ASD clinician. And because there are so few licensed ASD clinicians qualified to follow-up with the many parents who report suspected ASD through the questionnaire, the wait time for children to receive a diagnosis could be well after the child’s third birthday—delaying treatment past the ideal window of time to potentially improve outcomes for children with ASD.


Therefore, a time-efficient and accessible ASD screening is imminent to help health professionals and inform individuals whether they should pursue formal clinical diagnosis.  The rapid growth in the number of ASD cases worldwide necessitates datasets related to behaviour traits. However, such datasets are rare making it difficult to perform thorough analyses to improve the efficiency, sensitivity, specificity and predictive accuracy of the ASD screening process. Presently, very limited autism datasets associated with clinical or screening are available and most of them are genetic in nature. 

[![GANS Model](https://www.tutorialspoint.com/artificial_neural_network/images/model.jpg)]()

[![Amplitude](https://ars.els-cdn.com/content/image/3-s2.0-B978012817736500003X-f03-08-9780128177365.jpg?_)]()


## Approach

In this example, I use the raw data provided by Fadi Fayez Thabtah of the Department of Digital Technology at New Zealand's Manukau Institute of Technology. I preprocess the data in the notebook to transform categorical feature vectors into numerical ones, and drop redundant features that provide no additional predictability. 

At the end of the notebook, I instantiate a classification report with F1-Scores and accuracy ratings. 

The model's predictability is surprisingly accurate at 93%.


# Links

* [KaizenTek](http://www.kaizentek.io) - IT Consulting & Cloud Professional Services