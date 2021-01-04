# Bayesian_Network
## AIM: To construct a Bayesian Network Considering medical data.use this model to demonstrate the diagnosis heart patient using standard heart disease dataset.
https://github.com/sahanabalappa/Bayesian_Network/blob/main/Bayesian_Network.ipynb

## Introduction: 
### Bayesian_Network is a probabilistic graphical model that represents a set of variables and conditional dependencies via a directed acyclic graph(DAG).
### bake()
#### Finalize the topology of the model.
#### Assign a numerical index to every state and create the underlying arrays corresponding to the states and edges between the states.
#### This method must be called before any of the probability-calculating methods.
### predict_proba()
#### Returns the probabilities of each variable in the graph given evidence.
#### This calculates the marginal probability distributions for each state given the evidence provided through loopy belief propagation

##### Parameters: data:dict
###### The evidence supplied to the graph. This can either be a dictionary with keys being 	state names and values being the observed values .
	
##### Returns: probabilities:array-like, shape (n_nodes)
###### An array of univariate distribution objects showing the probabilities of each 	variable.


 
