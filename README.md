# FMNIST Classification using CNN 


* <b>Introduction</b>

  Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples.
  Each example is a 28x28 grayscale image, associated with a label from 10 classes. Zalando intends Fashion-MNIST to serve as a direct drop-in 
  replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure 
  of training and testing splits. The MNIST dataset (arguably) is the dataset most often used as a starting point for image classification learning. 
  The scientific data community likes this dataset and uses it as a benchmark to validate their algorithms. MNIST is often the first dataset that researchers try.
  
  <i>"If the algorithm cannot work with MNIST, the algorithm will not work for other data sets. If the algorithm works with MNIST, a good start, but that does not mean it can work for other data sets."</i>
  
  | Label 	| Description 	|
  |:-----:	|-------------	|
  | 0 	| T-shirt/top 	|
  | 1 	| Trouser 	|
  | 2 	| Pullover 	|
  | 3 	| Dress 	|
  | 4 	| Coat 	|
  | 5 	| Sandal 	|
  | 6 	| Shirt 	|
  | 7 	| Sneaker 	|
  | 8 	| Bag 	|
  | 9 	| Ankle Boot 	|
  
  <img src="https://github.com/zalandoresearch/fashion-mnist/blob/master/doc/img/fashion-mnist-sprite.png" alt="" style="max-width:100%;">


* <b>Content</b>

  Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total.
  Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. 
  This pixel-value is an integer between 0 and 255.The training and test data sets have 785 columns. 
  The first column consists of the class labels (see above), and represents the article of clothing.
  The rest of 784 columns (1-785) contain the pixel-values of the associated image.
  

  
  
  
  


