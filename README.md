# my_rec module
BU SCC Collaboration for Intelligent Resource Prediction Framework.
## Overview

`my_rec module` is a module designed for intelligent resource prediction within collaborative environments. It provides training and prediction scripts suitable for batch job submissions on the BU SCC system.

## Features

- Data preprocessing utilities
- Regression-based prediction algorithms
- Model training and prediction tools

## Installation

On BU SCC system, first include the directory for the module and load the module.

```bash
module use /projectnb/peaclab-mon/boztop/module_files
module load my_rec/1.0.0
```
Train the model, once after module is loaded.

```bash
./train.py
```

## Usage

```bash
./rec.py path_to_your_batch_job_file
```
A new script with recommended number of processors for your batch job is created in the same directory as your batch job file.


## Support

For questions or issues, please contact [boztop@bu.edu](mailto:boztop@bu.edu).

## License

This project is licensed under the Boston University License.

