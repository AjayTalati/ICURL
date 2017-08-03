The code builds 500 different MDP models from the MIMIC-III dataset, selects the model with the highest mean state value, then tests the policy on the eICU-RI dataset.

External files and toolboxes used:

MDP toolbox: https://uk.mathworks.com/matlabcentral/fileexchange/25786-markov-decision-processes--mdp--toolbox
Fastknnsearch : https://uk.mathworks.com/matlabcentral/fileexchange/19345-efficient-k-nearest-neighbor-search-using-jit
