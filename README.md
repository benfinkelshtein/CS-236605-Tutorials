# CS236605 Tutorials

This repo contains the code and notebooks shown during course tutorials. It will be updated during the semester.

You can also view the tutorial notebooks in your browser using `nbviewer` by clicking the button below.

<a href="https://nbviewer.jupyter.org/github/benfinkelshtein/CS-236605-Tutorials/tree/master/"><img src="https://nbviewer.jupyter.org/static/img/nav_logo.svg" height="50px"/></a>

## Environment set-up

1. Install the python3 version of [miniconda](https://conda.io/miniconda.html).
   Follow the [installation instructions](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)
   for your platform.

2. Use conda to create a virtual environment.
   From the tutorial directory, run

   ```shell
   conda env create -f environment.yml
   ```

   This will install all the necessary packages into a conda virtual environment.

3. Activate the new environment by running

   ```shell
   conda activate CS-236605-Tutorials
   ```
4. Add the environment to Jupiter notebooks

   ```shell
   ipython kernel install --user --name=CS-236605-Tutorials
   ```