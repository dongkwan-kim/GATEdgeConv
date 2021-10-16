# GATEdgeConv
The graph attention operator that supports edge attributes

## Notice

- 2021.09.04: The PR for this layer to PyG is now processing [#3078](https://github.com/rusty1s/pytorch_geometric/pull/3078). 
- 2021.10.12: Now it is avaialble [Docs](https://pytorch-geometric.readthedocs.io/en/latest/modules/nn.html#torch_geometric.nn.conv.GATConv). 


## Install Dependencies

````shell
CUDA=${1:-"cu102"}
TORCH=${2:-"1.9.0"}
echo "CUDA: ${CUDA} / TORCH: ${TORCH}"
pip3 install torch==${TORCH}
pip3 install torch-scatter -f https://pytorch-geometric.com/whl/torch-${TORCH}+${CUDA}.html
pip3 install torch-sparse -f https://pytorch-geometric.com/whl/torch-${TORCH}+${CUDA}.html
pip3 install torch-cluster -f https://pytorch-geometric.com/whl/torch-${TORCH}+${CUDA}.html
pip3 install torch-geometric==1.7.2
````
