# autoencoder-transferlearning
Evaluating the efficacy of transfer learning autoencoder neural networks across similar IoT devices and similar malware types.

In order to replicate, please import the jupyter-notebooks into a platform of your choice and modify the variables used to write results into persistent files on disk.

Each directory consists of one notebook consisting of steps split into cells which helps review the code. The other notebooks consist of large loops designed to automatically run a complete training, testing and trasfer-learning loop across all devices and malwares without manual intervention.



# NBaIoT 
The nbaiot dataset has been used in the same format and hierarchy as persented by the original authors. This can be downloaded from the repository link https://archive.ics.uci.edu/ml/datasets/detection_of_IoT_botnet_attacks_N_BaIoT

# CIC-IDS2017
The CIC-IDS2017 consists of data sorted on a per day basis. For this research, we filtered and resorted this data on the basis of IP address and labelled traffic flows. This re-sorted data can be found at the following path CIC-IDS2017/PerIPData


