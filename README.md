# DPSP: A multimodal deep learning framework for polypharmacy side effects prediction
We introduce DPSP, a Deep learning framework for Polypharmacy Side effects Prediction in two steps. In the first step, it collects a variety of drug information that may influence Drug-Drug Interactions (DDIs), i.e., mono side effects, targets, enzymes, chemical substructures, and pathways in order to construct novel features. In this stage, a feature extraction module creates feature matrix by using the Jaccard similarity and integrating five matrices with the same dimensions. In the second step, predictions of the DDIs for 65, 100, and 185 categories of DDI events in DS1, DS2, and DS3 are performed through a deep multimodal framework, respectively.
## Usage
The setup for our problem is outlined in `DPSP.py`. It uses a simple neural network with 65, 100, and 185 events. Run the code as following:

```
$ python3 DPSP.py
```
## Requirement
- numpy (==1.18.1)
- Keras (==2.2.4)
- pandas (==1.0.1)
- scikit-learn (==0.21.2)


Use the following command to install all dependencies. 
```
    pip install requirement.txt
```

Notice: Too high version of sklearn will probably not work. We use 0.21.2 for sklearn.
