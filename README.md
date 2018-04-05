## Irony Detection in English Tweets

### Installation
#### 1. Download the system

Download the system with the following command
``` https://github.com/bhanuV/textMinProj.git ```

#### 2. Install dependencies
``` pip install -r requirements.txt ```

Install other depencies if needed.
We have Preprocessed data.

Files : 
feature_extraction.py - Takes an input string and genearates all the feature required for training and testing. 
classifierSVM.p - SVM classifier which is trained by the training file is stored here 
dictionaryFileSVM.p - This is the dictionary vector object to convert from the lists of feature value to vectors to train or test
Similarl files for other algorithms are stored

#### 3. Running the Program

Approach One
```python traintestSVM.py```  // Run SVM algorithm
In the similar run other algorithms

Approach Two
```python classification.py```