[Home](README.md) | [DevBox](devbox.md) | [Athena](athena.md) | [Supercomputing@SUTD](https://computing.sutd.edu.sg/)

# Jupyter Notebook Guide

## Starting a Notebook

1. Log into one of the two JupyterHub nodes and spawn a server.
    * [Artemis](http://10.16.74.79:30001/hub/login) or [Apollo](http://10.16.74.79:30001/hub/login)
    * **You may refer to the [user guide](bit.ly/sutddevbox) if you face issues.**
2. You will be presented with the file browser UI, from which you can upload, download, create and open files. 

## File Browser

This is the UI which you use to browse your Notebook's filesystem and interact with the files.

![browser](images/jupyter_browser.jpg)

## Notebook UI

You can create a new Jupyter Notebook with a **Python 3 kernel** by selecting 'New' > 'Python 3'. You will then be presented with the Notebook UI. 

You can run `!nvidia-smi` or `!gpustat` to check if GPUs are accesible from the notebook.

![notebook](images/jupyter_notebook.jpg)

## TensorBoard

```
TODO
```

## JupyterLab

You can use JupyterLab instead of Jupyter Notebook. Simply replace `tree?` in the URL with `lab`.

