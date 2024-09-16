## LSMGA-MKGC
The repository for ACL 2023 paper: Multilingual Knowledge Graph Completion with Language-Sensitive Multi-Graph Attention

## Requirements
* python==3.10.14
* pytorch==2.4.0
* torch-geometric==2.6.0
* torch-cluster==1.6.3
* torch-scatter==2.1.2
* torch-sparse==0.6.18

## How to run
For DBP5L dataset
```
python run_model.py --dataset dbp5l --round 80
```
For EPKG dataset
```
python run_model.py --dataset depkg --round 50
```
