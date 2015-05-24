# mechatronics-boards

This repository includes submodules for the following repositories:
* [FPGA1394](https://github.com/jhu-cisst/FPGA1394.git)
* [QLA](https://github.com/jhu-cisst/QLA.git)
* [FPGA1394-QLA-Test](https://github.com/jhu-cisst/FPGA1394-QLA-Test.git)

It may be easier to individually clone each of the above repositories, rather than using this
repository with submodules. To use this repository, see below:

## To clone this repository:

```
git clone https://github.com/jhu-cisst/mechatronics-boards.git --recursive
```
If you forgot to add the `--recursive` option, use the following commands to initialize the submodules:
```
git submodule init
git submodule update --recursive
```

## To update your working copy (from remote repository):
```
git pull origin master
git submodule update --recursive
```
