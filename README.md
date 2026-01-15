# FedShare
This repository contains the official implementation of **FedShare: Secure Aggregation based on Additive Secret Sharing in Federated Learning**. 

The implementation is based on `Python 3.8.8` and `tensorflow 2.9.1`.

## Quick Start
There are a couple of different files named '*common.py' like 'mnistcommon.py'. These files will be used for all three algorithms, 
including FedShare, SCOTCH, and FedAvg. The default is 'mnist' dataset. But if you are interested in running the experiments on other datasets, you should replace 'import mnistcommon' with 'import emnistcommon' for example. 

For a quick start you can use:
```
git clone https://github.com/v4va/FedShare.git
```

```
chmod +x start-fedshare.sh
chmod +x start-fedavg.sh
chmod +x start-scotch.sh
```

For FedShare:
```
./start-fedshare.sh
```
For FedAvg:
```
./start-fedavg.sh
```
For SCOTCH:
```
./start-scotch.sh
```

By default `m=5` and `n=2`. If you are interested in changing these values, first change `config.py` and then change `start-*.sh` file.
For checking results and training process, check `logs` folder.

Please feel free to contact us if you are facing any difficulty or have any questions regarding this project.

## Citation

If you use this code in your research, please cite the FedShare paper:


DOI: https://dl.acm.org/doi/10.1145/3589462.3589504

BibTeX:
```
@inproceedings{fedshare2023,
  title={FedShare: Secure Aggregation based on Additive Secret Sharing in Federated Learning},
  booktitle={Proceedings of the ACM Conference ...},
  year={2023},
  doi={10.1145/3589462.3589504}
}
```
