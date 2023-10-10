# NER-DocuScan-Web-App-using-NLP
Welcome to our Document Scanner Web App !!!
In this project, we have developed a customized Named Entity Recognizer. The main idea of this project is to extract entities from scanned documents like invoices, Business cards, Shipping bills, Bill of Lading documents etc. However, for the sake of data privacy, we have restricted our views to Business Card. However, this framework can be used for all kinds of financial documents. Below given is the curriculum we have followed to develop this project. 

## Computer Vision & Natural Language Processing
In Computer Vision, we have scanned the document, identified the location of text and finally extracted text from the image. Then using NLP, we extracted the entitles from the text did necessary text cleaning and parsed them.

## Python Libraries used in Computer Vision.
1. OpenCV
2. Numpy
3. Pytesseract
## Python Libraries used in Natural Language Processing
1. SpaCy
2. Pandas
3. Regular Expression
4. String

To combine two major technologies to develop the project, we have divided the architecture of this project into several stages of development.

Stage - 1: Firstly, we have set up the project by doing the necessary installations and requirements.

Installed Python
Installed Dependencies

Stage 2: Secondly, we did all the data preparation. That is we have extracted the text from images using Pytesseract and also did necessary cleaning.

Gathered Images
Extracted Text from all Images
Cleaned and Prepared text

Stage 3: Thirdly, we have labelled the NER data using BIO tagging.

We have done labelling manually with the BIO technique.
B - Beginning
I - Inside
O - Outside

Stage 4: Fourthly, we have further cleaned the text and preprocessed the data ( conversion from pickle format to spacy format ) for to train machine learning.
Prepared Training Data for Spacy
Converted data into a spacy format

Stage 5: After preprocessing the data we have trained the Named Entity Recognition model.
Configured NER Model
Trained the model

Stage 6: Finally, we have predicted the entitles using NER and model and created a data pipeline for parsing text.
Loaded Model
Rendered and Served with Display
Drew Bounding Box on Image
Parsed Entitles from Text

Finally, we have put all together and developed the Document Scanner App
