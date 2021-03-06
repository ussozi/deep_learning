# deep_learning
<p>
    Everything deep-learning
</p>

### Setting up Jupyter-notebook beyond the basic-setup:

**Note:** <br>
Do all the following in your conda base ```conda activate base``` environment assuming you have [anaconda](https://www.anaconda.org/) installed on your computer/laptop.

* Installing Jupyter themes: 
    * ```pip install jupyterthemes``` 
    * upgrade to the latest version ```pip install --upgrade jupyterthemes```
   
* Accessing conda environments within a notebook:<br>
    * Activate your environment (```conda activate <environment_name>```)
    * link your environment to jupyter with this command ```python -m ipykernel install --user --name=<environment_name>```
    * Repeat the above steps for all environments you'd want to link to jupyter so that you don't have to stop and restart jupyter everytime you want to work in a new environment.

* Adding other extensions:
    * Install nbextensions  ```pip install jupyter_contrib_nbextensions && jupyter contrib nbextension install --user```

* [Google colab](https://colab.research.google.com/) is an online notebook environment you can make use of beside a local setup. 
