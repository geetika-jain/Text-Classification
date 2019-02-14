# Text-Classification
A MAchine Learning Project based mainly on Scikit-learn classifying text messages from multiple disaster prone areas and classifying them to many of the 42 classes in a yes/no fashion.


### Usage Guide
- Requires Python 3.6 and above
- Get all [csv data files](https://www.figure-eight.com/dataset
combined-disaster-response-data/) and place it in `data` directory.
- Install dependencies in a [`virtualenv`](https://virtualenv.pypa.io
en/latest/userguide/) using `pip install -r requirements.txt`.
- Open `notebooks/text-classification` in a jupyter notebook and run
all cells to test the bag-of-words models.
- To run the CNN classifier, run `python train_cnn.py
