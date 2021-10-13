# FedMe: Federated Learning via Model Exchange

This is the code accompanying "FedMe: Federated Learning via Model Exchange" 

# Dataset

We have three datasets, FEMNIST, CIFAR-10, and Shakespeare. You should download datasets and put them to `data` (see ReadMe in `data`).

# Code

We have prepared eight Jupyter notebook for the three datasets: 'Centralized', 'Local Data Only', 'FedAvg', 'HypCluster', 'MAAPER', 'Federated Mutual Learning', 'pFedMe', and 'FedMe'.
'FEMNIST', 'CIFAR-10', and 'Shakespeare' contain the respective codes.
Note that the hyperparameters in these codes are not tuned, so please change the value of each and run them.

# Client best model

For FedMe, we have included the results of tuning the model in 'Local Data Only' for each client in the 'client best model' folder.
If you run the codes with a different number of clients or different seed values, please create and modify the 'client best model' by yourself.

