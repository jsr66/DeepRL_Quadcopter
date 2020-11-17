# Deep RL Quadcopter Controller

In this project, a deep RL agent is designed and trained to fly a quadcopter to accomplish a specific task, specified via the design of a specially tailored reward function. 

## Instructions for running

1. Create and activate a new environment.

```
conda create -n quadcop python=3.6 matplotlib numpy pandas
source activate quadcop
```

2. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `quadcop` environment. 
```
python -m ipykernel install --user --name quadcop --display-name "quadcop"
```

3. Open the notebook.
```
jupyter notebook Quadcopter_Project.ipynb
```

4. Before running code, change the kernel to match the `quadcop` environment by using the drop-down menu (**Kernel > Change kernel > quadcop**). Then, follow the instructions in the notebook.

## Notes
1. The environment, in which the task of landing softly is specified via a particular choice of reward function, is contained in task_new2.py

2. The DDPG agent is in agents/agent_new2.py
