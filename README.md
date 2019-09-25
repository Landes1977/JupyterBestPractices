# JupyterBestPractices
collection of articles about maximizing jupyter notebook

## Configuring NBExtensions with Windows Anaconda Distribution

1. Anaconda ProgramData directory
  - Under Security select Users
  - Click Edit
  - Select Full control
2. Inside the Anaconda Prompt run 
```conda install -c conda-forge jupyter_nbextensions_configurator```
3. Inside the Anaconda Prompt run 
```conda install -c conda-forge jupyter_contrib_nbextensions```
4. Inside the Anaconda Prompt run
```jupyter contrib nbextension install --user```
