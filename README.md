# Face_Generation
 ### 
<strong> It uses Generative Adversarial Networks to generate face images. </strong>

### Dateset
* You'll be using the CelebFaces Attributes Dataset (http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) to train your adversarial networks.
* You can download the dataset from https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5be7eb6f_processed-celeba-small/processed-celeba-small.zip
### Model description
Models are described in Generator and Discriminator classes in the jupyter notebook. It is using convolutional layers to create the model.

#### Generator
* Model Structure
  - It uses 1 fully connected layer followed by 4 De Conv layers.
  - Ouput is passed to tanh.
* Loss : Binary Cross Entropy Loss.
* Optimizer : Adam Optimizer.

#### Discriminator
* Model Structure
  - It uses 4 convolutional layers followed by 1 fully connected layer.
  - Leaky ReLU is used as the activation function.
  
* Loss : Binary Cross Entropy Loss.
* Optimizer : Adam Optimizer.

### Usage
To use the code, Load samples using the Generator object to get fake faces.

      
### How to Contribute
Find any typos? Have another resource you think should be included? Contributions are welcome!

* Fork this repository.

* Clone the repository to your desktop to make changes.

      $ git clone {YOUR_REPOSITORY_CLONE_URL}

* Issue a pull request by clicking on the green pull request icon.

Instead of cloning the repository to your desktop, you can also go to README.md in your fork on GitHub.com, hit the Edit button (the button with the pencil) to edit the file in your browser, then hit the Propose file change button, and finally make a pull request.

### License
This repository has been licensed under Apache 2.0.
