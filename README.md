# techNotes
Technical note keeping tool using binder and jupyter

Setup: (Local install of Anaconda Navigator)
1. Create a conda environment (conda create -n techNotes)
2. Copy .jupyter/jupyter_notebook_config.py to the local users jupyter directory (Typically: C:\Users\%USERNAME\.jupyter)
3. Run: pip install --user -r .requirements/requirements.txt
4. Install nodejs to build jupyter (conda install nodejs -c conda-forge)

To deal with code snippets:
1. The definitions are stored in the $JUPYTER_DATA_DIR/metadata/code-snippets directory, where $JUPYTER_DATA_DIR refers to the Jupyter data directory.
2. Find the jupyter data directory (jupyter --data-dir)
