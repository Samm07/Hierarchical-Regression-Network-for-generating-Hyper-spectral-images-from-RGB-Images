## Test

Please put test data in this directory first.
Note that the data should be first generated from different models (please run `test*.py`).
Then compute the average of all results by running `ensemble_track*_8methods.py`.
Finally, all the results for both tracks are saved in `./ensemble/track1` and `./ensemble/track2`.

### track 1 generation
* Run `test1.py`.
* It will output 8 results of 8 networks.

### track 1 ensemble
* Run `ensemble_track1_8methods.py`.
* It will output 1 ensemble result of 8 generated data.

### track 2 generation
* Run `test2.py`.
* It will output 8 results of 8 networks.

### track 2 ensemble
* Run `ensemble_track2_8methods.py`.
* It will output 1 ensemble result of 8 generated data.

For each track, we use the "best" epoch for ensemble.
