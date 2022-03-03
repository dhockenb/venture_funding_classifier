# venture_funding_classifier
This Jupyter notebook application uses supervised machine learning using neural network models to create binary classification models for success from a dataset containing more than 34,000 organizations receiving venture funding from a VC firm. Categorical features were dummy encoded using OneHot Encoder from scikit-learn, features and target sets were split into training and testing datasets using train-test-learn and scaled using the StandardScaler preprocessing class(both from scikit-learn). The Sequential class from TensorFlow and the Keras API were used to create deep neural networks for binary classification. Optimization of original model was explored by increasing the number of hidden layers from 2 to 3, changing the activation function from relu to elu, and eliminating one feature from the analysis. Loss and accuracy metrics were calculated for each model. 


## *Technologies*
This application is written using Python 3.9.7 and uses funding data for more than 34,000 organizations receiving venture funding. t

## *Installation Guide*
Install the pandas, tensorflow and sklearn libraries.

## *Usage*
Run the program from the command line as 'GC_venture_funding_with_deep_learning.ipynb'.

## *Contributors*
This program was written by David Hockenbery with the assistance of the UW FinTech class of 2021 and instructors. Contact David at dhockenb@gmail.com.

## *License*
opyright (c) [2022] [David Hockenbery]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
