# Parallel Python example

To run `parallel.py` using the resources requested by `jobscript.job`, use the `sbatch` command:

``` bash
sbatch jobscript.job
```

Example output (to be found in `slurm-<jobid>.out`):

```
Non-parallel compute time: 10.018450498580933 seconds.
Parallel compute time on 96 cores: 0.3378734588623047 seconds.
```
