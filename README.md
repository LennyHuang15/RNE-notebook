# RNE-notebook
Road Network Embedding code in python

## Requirement
numpy pandas tensorflow

## RNE model
3 training phase:
1. Hierarchical embedding
2. Vertices embedding
3. Fine-tuning (not included yet)

## Data

### 1. Road network

*.co: lng, lat of vertices

*.gr: edges and weights

Nodes_full_*_*.data: hierarchical partition

### 2. Training/Testing data

Format: (each line)

id_source_vertex id_destinate_vertex shortest-distance


Including 10^7 training samples and 10^6 testing samples in train/

You need to tar -zvxf train/test.data.tar.gz
