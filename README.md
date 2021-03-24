# clone project
> git clone https://github.com/nnluc073/my-pytorch.git
> cd my-pytorch

# clone pytorch
> git clone --recursive https://github.com/pytorch/pytorch
> cd pytorch

# if you are updating an existing checkout
> git submodule sync
> git submodule update --init --recursive

# build
> docker build -t mypytorch:0.0.2 .
