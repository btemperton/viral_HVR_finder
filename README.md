# Viral HVR finder


##Setup

Grab the code:

```
git clone https://github.com/btemperton/viral_HVR_finder.git
cd viral_HVR_finder
```
Set up an appropriate conda environment

```
conda create -y -n find_hvrs python=3.6 pandas=0.23.4 numpy matplotlib
conda activate find_hvrs
```

## Run the code
```
python find_HVRs.py -h
```

## Test the code
```
python find_HVRs.py --coverage test/multi_sample_coverage_test.txt \
--output test_output \
--threads 4
```
