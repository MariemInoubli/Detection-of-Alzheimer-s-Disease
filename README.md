# Detection-of-Alzheimer-s-Disease
This project explores machine learning and deep learning models for the early detection of Alzheimer's disease using linguistic and audio data. It includes NLP and audio processing models allows users to perform detection tests privately at home.

The objective was to test various models, combine the best performing ones, and create a user-friendly iOS application that could be accessible to individuals for private use at home.

### Dataset
We utilized dataset from DementiaBank within the TalkBank database. Specifically, the Boston Cookie Theft image description task subset was selected due to its balance, consisting of 552 recordings with transcripts, all involving descriptions of the test image during clinical interviews with each participant. (Note: One transcript did not align with its corresponding audio, leaving a final total of 551 interviews.)

### Language Models
We experimented with several natural language processing models, using a mix of syntactic tagging and markup annotations. Algorithms evaluated include:

SVM
Random Forest
ULMFiT
BERT
Custom CNN

### Audio Models
The audio recordings were processed to isolate the participants' voices from those of interviewers.  Spectrograms were then generated and fed into a CNN-based model (xResNet-34) for classification.

Although we planned to build a combined classifier that uses both text and audio data, time constraints meant that only the audio model was fully developed. Integrating both audio and text remains a future goal.

### References
Becker, J. T., et al. (1994). The natural history of Alzheimer's disease: description of study cohort and accuracy of diagnosis. Archives of Neurology, 51(6), 585-594.
Devlin, J., et al. (2018). Bert: Pre-training of deep bidirectional transformers for language understanding. arXiv preprint arXiv:1810.04805.
Howard, J., & Ruder, S. (2018). Universal language model fine-tuning for text classification. arXiv preprint arXiv:1801.06146.
Hernández-Domínguez, L., et al. (2018). Computer-based evaluation of Alzheimer’s disease and mild cognitive impairment patients during a picture description task. Alzheimer's & Dementia: Diagnosis, Assessment & Disease Monitoring, 10, 260-268.
López-de-Ipiña, K., et al. (2012). New approaches for Alzheimer’s disease diagnosis based on automatic spontaneous speech analysis and emotional temperature. Ambient Assisted Living Workshop, Springer, Berlin.
TeamN. (2019). Early Detection of Alzheimer's Disease project. GitHub repository.https: //github.com/pcuenca/alzheimer
MacWhinney, B. (2000). The CHILDES Project: Tools for Analyzing Talk.
Mirheidari, B., et al. (2016). Diagnosing people with dementia using automatic conversation analysis. Proceedings of Interspeech, ISCA.
Mirheidari, B., et al. (2019). Dementia detection using automatic analysis of conversations. Computer Speech & Language, 53, 65-79.
Yancheva, M., Fraser, K., & Rudzicz, F. (2015). Using linguistic features longitudinally to predict clinical scores for Alzheimer’s disease. SLPAT Workshop on Speech and Language Processing for Assistive Technologies.
