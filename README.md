# CNN-based Amharic OCR 
# Handwritten-OCR-for-Ancient-Geez-Numerals

In this project, we had the chance to develop a character recognition system
for ancient Geez numerals. Ethiopia’s literary wealth accumulated over the centuries and written in Geez language is at risk of loss due to the age of the manuscripts, lack of proper care and handling.
Converting these documents into a digital format can help preserve history, save
storage space and time, as well as ease retrieval of important information.
In addition to preserving Ge’ez language, we believe that building an OCR
system will increase accessibility of the language. Once we digitize the language,
we can make these documents available globally so that people can have access to
these documents from anywhere.

To develop this system, we first collected images of different hand written amharic numbers from 27
people. Each person has provided 60 characters. After we collected the images,
we pre-proccessed them in order to make the image data ready for being used
to develop the classification algorithm. We followed some pre-processing steps
to separate out individual numerals from each form represented in binary for-
mat. Algorithms were specifically selected to give good pre-processing results.A
script was also written to automatically label and classify the image dataset
into appropriate folder locations. These images were used as dataset and ap-
plied to our classification algorithm. The specific classification algorithm we
used in this project is called Convolutional Neural Network (CNN). As a future
research direction, we are planning to collect additional image data in order to
increase the classification accuracy of our model. This makes our system ca-
pable of accommodating different hand writings. Currently, we are developing
a web-based application to deploy our algorithm. Therefore, in the future we
would like to finish the application and make the system available to the users.
9

