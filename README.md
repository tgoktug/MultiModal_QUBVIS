# MultiModal_QUBVIS
Query based video summarization and captioning

In this study, query-based video to video summarization and captioning of these summarized videos were performed with neural models. For video to video summarization, a model training process given in the qubvis_transformer.ipynb file under the /models/ folder was performed. The json structure of the dataset is clearly seen in the data preprocessing code block of the relevant file. For video captioning, the training process in the vision_language_model.ipynb file under the /model/ folder was performed. The data structures where the developed models are loaded as objects are included in the QBSumModel2.py and VidCapModel.py files in the main directory.

The main_caption_api.py program was developed so that the inference operations of the relevant models can be presented with an API. In this API, the model files presented in the readme.txt in the /models/ folder were provided to load the trained models with the model files located in the Google Drive paths. For the use of the API, please download the model files by going to these Google Drive links. The YouTube video URL to be summarized and the Query information that the summary process should focus on should be given as parameters to the relevant API.

The index.html web interface in the /templates/ folder was developed for the testing of the developed API. The YouTube URL of the video to be summarized and the Query information that is the focus of the summary process are entered in the developed interface. Then, the query-focused summary video of this video and the captions of the summary video are displayed on the interface.
![image](https://github.com/user-attachments/assets/5d4a768a-ca17-4aa0-8a7a-bf43860ec5e8)
