# Li-datasets

## Introduction
---
This project contains the datasets for training Li potential models 
in the paper "Self-Healing Mechanism of Lithium in Lithium Metal"

These datasets contain train and test datasets. They are generated by [dpgen](https://github.com/deepmodeling/dpgen) and Vienna ab initio simulation package (VASP). The datasets can be directly used to trian a Li potential model using [DeePMD-kit](https://github.com/deepmodeling/deepmd-kit)


**See DFT calculations and datasets section in [Supplementary materials](https://onlinelibrary.wiley.com/action/downloadSupplement?doi=10.1002%2Fadvs.202105574&file=advs3655-sup-0001-SuppMat.pdf) for more information about these datasets.**


## Files

`box.npy`  contains the lattice parameters information;

`coord.npy`  contains the coordinate information;

`energy.npy` contains the calculated energy information;

`force.npy` contains the  calculated force information;

`virial.npy` contains the calculated virial information;

`type.raw` contains elements information of each atoms for all configurations in the file;

`type_map.raw` map the elements information from the number to word.


## License and Cite
This software is licensed under the GNU General Public License version 3 or any later version (GPL-3.0-or-later). If you use these datasets in any publications, please cite the paper [Self-Healing Mechanism of Lithium in Lithium Metal](https://doi.org/10.1002/advs.202105574).
