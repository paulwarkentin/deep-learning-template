# Deep Learning Template

*This is a template for general deep learning projects.*

## Project Structure

```
.
├─ data/
│  ├─ raw/                      <- raw datasets, e.g. downloaded archives
│  ├─ interim/                  <- extracted datasets in its raw folder structure
│  └─ processed/                <- processed, e.g. converted and filtered,
│                                  data ready for training
├─ docs/                        <- project documentation
├─ notebooks/                   <- Jupyter notebooks used for experiments
├─ models/                      <- pre-trained weights and frozen models
├─ src/
│  ├─ data/                     <- data loader and processing
│  ├─ models/                   <- model implementations
│  ├─ utils/                    <- utility functions and classes
│  └─ ...                       <- files for training, evaluation and inference etc.
├─ training/                    <- run configurations and saved checkpoints
│  └─ run_*/                       created by src/train.py
├─ LICENSE.md
└─ README.md
```

## Getting Started

*Explain here, what the first steps are to get started. This can be stuff like downloading datasets and extracting them
into the data folder.*

## Dependencies

*List here dependencies of the project, e.g.*  
The project was compiled using the following packages:
- **Matplotlib** 2.2.2 ([Information](https://matplotlib.org/))
- **NumPy** 1.14.5 ([Information](https://www.numpy.org/))

## License

*Give here information about the type of license the project is published with, e.g.*  
All python code in this repository is available under an MIT license.
