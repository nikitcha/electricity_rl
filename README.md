# electricity_rl
## Reinforcement Learning Agent Competition Model of Power markets

### Dependencies

###### Install Python 3.7: 
https://www.python.org/downloads/release/python-370/

###### Create a virtual environment
In command prompt type: python -m venv *my_env_name*

###### Activate the environment:
In command prompt: my_env_name\Scripts\activate
<br> Install Libraries
- pip install tensorflow==2.0.0
- pip install jupyterlab
- pip install maplotlib
- pip install gym
- pip install cvxpy

##### To view the notebook:
In command prompt with activated environment type: jupyter lab
<br> Browse to Git folder and open notebook


##### How to merge Notebooks:
For convenience install the Jupyter extension: jupyter-git. This will also install 'nbdime' which is used for merging Notebooks.
<br> In the command line: nbdime config-git --enable --global
<br> Then: git mergetool --tool=nbdime
This will launch the merge tool in the browser. Once finished - close, then Git Commit and Push.


