# MSDK BLE CI PER Test Tools

This repository provides some tools for the MSDK BLE CI PER tests.

## Plot the PER figures from the test results
Example:
```
conda activate py3_10
chmod u+x plot_per_results.py
./plot_per_results.py 2023-01-30_15-45-25_max32665.csv desc basename
```

Note:
The PER test results are stored on the wall-e in the folder /home/btm-ci/Workspace/ci_results/per.


