# CUMUL
A simple implementation of paper 'Website Fingerprinting at Internet Scale'.
## BibTex
@inproceedings{panchenko2016website,\
  title={Website Fingerprinting at Internet Scale.},\
  author={Panchenko, Andriy and Lanze, Fabian and Pennekamp, Jan and Engel, Thomas and Zinnen, Andreas and Henze, Martin and Wehrle, Klaus},\
  booktitle={NDSS},\
  year={2016}\
}

The files for closed-world evaluation that contain the packet sizes and timestamps should be named as 1-1 (for example). The first digit indicates the class number of a website. And the second digit indicates the round the website traffic is captured.

The files for open-world evaluation are named starting at 100 (if you have 100 websites as monitored websites and the classes range from 0-99).

Sample files are given in the folder /dataset.

The grid search parameters are the same as those in the original paper in section VI, page 8.


## Requirements
numpy \
scikit-learn
