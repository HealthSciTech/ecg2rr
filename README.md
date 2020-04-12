# ecg2rr

Repository will contain code used in the following open access publication in ACM library:

> Juho Laitala, Mingzhe Jiang, Elise Syrjälä, Emad Kasaeyan Naeini, Antti Airola, Amir M. Rahmani, Nikil D. Dutt, and Pasi Liljeberg. 2020. Robust ECG R-peak Detection Using LSTM. In The 35th ACM/SIGAPP Symposium on Applied Computing (SAC ’20), March 30-April 3, 2020, Brno, Czech Republic. (accepted)

[https://dl.acm.org/doi/abs/10.1145/3341105.3373945](https://dl.acm.org/doi/abs/10.1145/3341105.3373945)

The presentation can be found at Youtube:
[https://youtu.be/OJzF1HNVopk](https://youtu.be/OJzF1HNVopk)
More functionality regarding RR intervals will be added in future, hence the name ecg2rr.

## Dependencies

Package requires python version 3.7 or higher and it has following dependecies:

* [tensorflow 2](https://www.tensorflow.org/)
* [scipy](https://www.scipy.org/)
* [wfdb-python](https://github.com/MIT-LCP/wfdb-python)

## Installation

Latest version of the package and its dependencies can be installed from github with pip:

> `pip install git+https://github.com/jtlait/ecg2rr.git#egg=ecg2rr`

Version that was used in the upcoming publication can be installed in similar fashion:

> `pip install git+https://github.com/jtlait/ecg2rr.git@v0.1.0#egg=ecg2rr`

## Usage

See `usage_example.ipynb` from the notebooks directory.


