# GATEdgeConv
The graph attention operator that supports edge attributes

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
