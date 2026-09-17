# sign_language_CNN

Comparing two convolutional neural network (CNN) models for classifying sign language hand images representing digits from 0 to 9. 
A baseline CNN model was first implemented using a simple architecture with a single convolutional layer. While this model was
able to learn basic visual patterns, its performance was limited by overfitting and reduced generalization on unseen data.

To address these limitations, an advanced CNN model was developed using transfer learning with a
pretrained VGG16 network. The convolutional base of VGG16 was combined with data augmentation,
dropout, and L2 regularization to improve robustness and reduce overfitting. Both models were
trained and evaluated using separate training, validation, and test datasets.

The results show a clear improvement in performance when using the advanced model. The baseline
CNN achieved a test accuracy of 77%, whereas the advanced model achieved a significantly higher test
accuracy of 95.47%.


