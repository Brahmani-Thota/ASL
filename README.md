# ASL

## Introduction:
American Sign Language is a natural language that serves as a sign language of deaf communities in the United States. ASL is expressed by movements of hands and face. It is completely separate and distinct from English, and has its own features of a language, like the order of the words, the pronunciation of the words and formation of the words. 

[1]Parents are often the source of a child’s early acquisition of language, but for children who are deaf, additional people may be models for language acquisition. A deaf child born to parents who are deaf and who already use ASL will begin to acquire ASL as naturally as a hearing child picks up spoken language from hearing parents. However, for a deaf child with hearing parents who have no prior experience with ASL, the language may be acquired differently. 

[2]Unfortunately, ASL is a dying form of communication at present, due to the lack of resources in education and technology. Many deaf people are adamant that sign language will always be essential, but the lack of resources is threatening to close schools that teach it. 


## Aim:
The goal of the project is to translate and recognize the signs of various alphabets and digits into the text by using the same deep learning model for training both digits and alphabets. 

## Data: 
[3]The original MNIST image dataset is made from handwritten digits and is commonly used for image-based machine learning methods. 

Sign Language MNIST is patterned to match closely with the classic MNIST.

Each training and test case represents a label (0-25) as a one-to-one map for each alphabetic letter A-Z (and no cases for 9=J or 25=Z because of gesture motions)
[4]The training data (27,455 cases) and test data (7172 cases) are approximately half the size of the standard MNIST. The dataset consists of about 100MB of space. 

The data format of the data is in the form of CSV files where the row contains the label, pixel1,pixel2….pixel784 which represent a single 28x28 pixel image with grayscale values between 0-255. 
