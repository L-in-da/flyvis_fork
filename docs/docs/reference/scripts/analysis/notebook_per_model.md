# Launch Notebook Per Model on Cluster

`analysis/notebook_per_model.py`

```
usage: notebook_per_model.py [-h] [--start START] [--end END] [--nP NP]
                             [--gpu GPU] [--q Q] --ensemble_id ENSEMBLE_ID
                             --task_name TASK_NAME
                             [--notebook_per_model_path NOTEBOOK_PER_MODEL_PATH]
                             [--dry]

Run a notebook for each model of an ensemble on the cluster.

optional arguments:
  -h, --help            show this help message and exit
  --start START         Start id of ensemble.
  --end END             End id of ensemble.
  --nP NP               Number of processors.
  --gpu GPU             Number of GPUs.
  --q Q                 Queue.
  --ensemble_id ENSEMBLE_ID
                        Id of the ensemble, e.g. 0045.
  --task_name TASK_NAME
                        Name given to the task, e.g., flow.
  --notebook_per_model_path NOTEBOOK_PER_MODEL_PATH
                        Path of the notebook to execute.
  --dry                 Perform a dry run without actually launching jobs.

```