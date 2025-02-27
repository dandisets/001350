# data_axondeepseg_stanford
This dataset contains TEM mouse samples provided by Brad Zuchero. The goal of
this project is to study unmyelinated axons, which are usually hard to see with 
traditional TEM image acquisition. The technique used to prepare the samples is 
High pressure freezing and freeze substitution. This results in very crisp high 
definition TEM samples. Imaging was done at UC Berkeley.
Original magnification: 8000x

- data was originally used in https://www.pnas.org/doi/10.1073/pnas.2307250121
- 2 groups of mice:  Wild Type (WT) or SRF conditional knockout (KO).

Note that `sub-373C_sample-0001` has 2 small annotated ROIs:
- sub-373C_sample-0001_acq-roi_chunk-01_TEM: 800,1500   1400,2100
- sub-373C_sample-0001_acq-roi_chunk-02_TEM: 2400,1300  2900,1800


BIDS version 1.7.0