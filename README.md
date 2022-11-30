# Deepfake-Detection-using-Advanced-Convnets2d

Even a few decades ago, it would have been impossible to foresee the widespread use of deep learning to tackle such complex issues. It has many positive applications, but it can also be misused to cause harm to our society. One such problem is deep fakes, and now more than ever, when anyone with a smartphone app can create a fake image or video, it's crucial to take measures to authenticate content online. Visual and auditory "deepfakes" may be generated with the aid of neural networks. Deepfake mimics competing machine learning models with the help of Generative Antagonistic Networks (GANs). Many well-known people have been affected by the rapid spread of false news stories on social media platforms like Facebook, YouTube, Twitter, etc. Artificial neural network deep fakes may appear identical to authentic images or videos before being moderated, but they always leave behind telltale spatial and temporal signatures. A neural network that has been taught to specialise in Deep fake detection will be able to quickly identify these signs, even if they are not obvious to the human eye. To determine whether or not a video is a deep fake, we will be employing Residual Network and InceptionResNetV2 in this project.

### data

    Github folder Link: https://github.com/aparna1606/Deepfake-Detection-using-Advanced-Convnets2d/code
    
### code

    Github folder Link: https://github.com/aparna1606/Deepfake-Detection-using-Advanced-Convnets2d/data
    The files in this folder are:
      capture_img.ipynb → Code to capture images in videos by splitting it into frames
      deepfake_detection1.ipynb → Code to detect deepfake videos using InceptionResNetV2 algorithm
      model_play.ipynb → To load the created model

### Methodology
  A new set of challenges has been introduced by the advent of deepfakes, which are typically built using one of two methods, autoencoders or generative adversarial  networks, both of which are based on trained deep neural networks. More training data (in the form of fake photos and videos that may be obtained online) makes it possible for GANs to produce deeper fakes with a higher degree of realism. Algorithms used in deepfakes produce material that is nearly identical to the original but for a few minor details. Thus, cutting-edge strategies are urgently needed to detect and eliminate such deepfakes. This research was based on the Inception-Resnet-v2 deepfake detection network. The proposed method not only outperforms the conventional approaches in terms of efficiency and accuracy, but it also provides the highest possible resolution when taking into account the complex nature of the space and time constraints. This is because the proposed method uses an iterative approach.
