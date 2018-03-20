# protein-secondary-structure-prediction
The aim of this repo is to provide implementation of BRNN model for protein secondary structure prediction. 
Long-term aim is to improve the current known accuracy for the same task.
Done by <a href="https://github.com/Udayraj123">Udayraj Deshmukh</a> and <a href="https://github.com/s1998">Sudhanshu Ranjan</a>

# Steps to run this model
1. `chmod +x dependencies_installation.sh processCB613.sh`
2. run processCB613.sh
3. run model_6.py

# Results
The model reaches an accuracy of 68.4% on test data set (CB513).

Related work : `Next-Step Conditioned Deep Convolutional Neural Networks Improve Protein Secondary Structure Prediction` (1702.03865.pdf on arxiv) has an accuracy of 70.3% and also contains comparision with previous models.
