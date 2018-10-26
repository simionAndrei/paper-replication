# Paper replication

Replication of the paper Built to last or built too fast?: evaluating prediction models for build times [1].

## Data

Pull the data from [TravisTorrent](https://travistorrent.testroots.org/page_access/).
To run our experiment, download and extract to the project root the data folder from this [link](https://drive.google.com/file/d/1PFv_-HHB2aIpxm8xfqCbB9QYfhKl4zB8/view?usp=sharing).

## Project Structure
Our designed logging system creates the following folders hierarchy: *data* for storing input files, *logs* for keeping the application logs on html format, *models* for saving Keras models as h5 files, *output* for storing different plots, statistics files and other content generated by the experiment. The logger needs a configuration file, *config.txt*, where it is needed to specify the input file name and selected features list. Both of this files must be placed on *data* folder and are present in the archieved data folder from the link above.

## Environment

Run the script `replication.py` in an [Anaconda](https://www.anaconda.com/) environment with additionally [`keras`](https://pypi.org/project/Keras/) and [`scikit-learn`](https://pypi.org/project/scikit-learn/) installed.

## References

[1] Bisong, E., Tran, E. and Baysal, O., 2017, May. Built to last or built too fast?: evaluating prediction models for build times. In _Proceedings of the 14th International Conference on Mining Software Repositories_ (pp. 487-490). IEEE Press.
