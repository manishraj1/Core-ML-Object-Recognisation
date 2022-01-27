# Core-ML-Object-Recognisation

The Smart Grocery List allows the user to upload an image and giving the task to the mobile application to predict that particular image which the user have uploaded.

Example : 1) food iteams - furits, vegitables

          2) electronins - computers etc....   
          
this app hels the user to save a lot of time when he/she has to shop gorcery for home :)

<a><img src="https://user-images.githubusercontent.com/88855727/151360755-920df208-8cd0-4844-bf6c-ba39672ea5d0.PNG" width="230"></a>
<a><img src="https://user-images.githubusercontent.com/88855727/151360781-a4507d6b-7cc3-4ab1-8fdc-dd5170dacac6.PNG" width="230"></a>
<a><img src="https://user-images.githubusercontent.com/88855727/151360772-4b8e37f8-f78b-448a-ac72-2d41ed49089e.PNG" width="230"></a>
<a><img src="https://user-images.githubusercontent.com/88855727/151360779-b44abe46-d4ee-4109-954a-c419406bdeb8.PNG" width="230"></a>  

# Core-ML Model MobileNet General

- MobileNet

Model Type Neural Network Classifier
Size 17.1 MB
Document Type Core ML Model
Availability iOS 11.0+ | macOS 10.13+ | tvOS 11.0+ | watchOS 4.0+

- Metadata

Description:
MobileNets are based on a streamlined architecture that have depth-wise separable convolutions to build light weight deep neural networks. Trained on ImageNet with categories such as trees, animals, food, vehicles, person etc. MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications https://github.com/shicai/MobileNet-Caffe

Author:
Andrew G. Howard, Menglong Zhu, Bo Chen, Dmitry Kalenichenko, Weijun Wang, Tobias Weyand, Marco Andreetto, Hartwig Adam

License: 
Apache License. Version 2.0 http://www.apache.org/licenses/LICENSE-2.0 

- Precision

Compute
Float16

Storage
Float32

# Core-ML Model MobileNet Predictions

- Input

image
Image (Color 224 × 224)
Description
Input image to be classified

- Output

classLabelProbs
Dictionary (String -> Double)
Description
Probability of each category

classLabel
String
Description
Most likely image category

# Requirements

Built in
Xcode Version 13.2.1 (13C100)
Swift 5

# License

©CopyRight
Created by Manish raj(MR)

Udacity Core ML: Machine Learning for iOS Project
