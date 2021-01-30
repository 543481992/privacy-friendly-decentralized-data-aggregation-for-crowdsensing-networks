# Souce Code Description for Paper “Privacy-friendly Decentralized data Aggregation for Crowdsensing Networks”

This is a brief description for the source code of the paper “Privacy-friendly Decentralized data Aggregation for Crowdsensing Networks” which is included in IEEE globecom 2020.



## File Description
There are five executable python files in this repo, namely
- `draw4networks.py`, 
- `draw_privacy_acc_var.py`,  
- `draw_histo.py`, 
- `draw_netsz_itt_acc.py`, and 
- `draw_real_word_test.py`, 

which seperatively corresponds to: 
- **generating random geometric graphs**,
- depicting **privacy-accuracy trade-off** for the proposed algorithm and **calculating variance**,
- plotting  **histograms of empirical convergence value**, and
- showing  **accuracy, the number of iterations to reach a convergence  as a function of network size**,

with other files being the implementation of the proposed algorithm, the original  classical algorithm and some basic functions.


## Requires

- Windows or Linux is both ok (operating system-independent)
- **at least** python 3.x (please ensure the pakage [networkx](https://networkx.org/) is installed)

## How to run

With the above reqiures met, just enter the command  `python <file_name>`(replacing <file_name> with your target file name) for running the programms.