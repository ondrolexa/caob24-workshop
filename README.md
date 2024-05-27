# CAOB 2024 Conference - workshop I.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ondrolexa/caob24-workshop/main)

## Schedule

| Time | Topic | Packages |
|-------|-------|----------|
|10:00-11:30|**Introduction to Python programming**|          |
|11:30-11:45|*Break*|          |
|10:45-12:30|**Scientific Python**|Numpy, matplotlib|
|12:30-13:30|*Lunch*|          |
|13:30-16:00|**Python for structural geology**|APSG|

## Install software - JupyterLab, Python

If you want to participate actively, you must install Python and **JupyterLab** on your system. We will use the **Miniforge installer**, which allows simple and quick installation of all needed software.

​Download and execute the latest [miniforge installer](https://github.com/conda-forge/miniforge). There are known issues with using special characters and spaces in the installation location. We recommend users install in a directory without any such characters in the name e.g. `C:\Users\john\miniforge3`

## Downloading Course Materials and create environment

Download and unzip the [workshop material](https://github.com/ondrolexa/caob24-workshop/archive/refs/heads/main.zip). It is suggested to unzip it into your home directory e.g. `C:\Users\john\caob24-workshop`

From the Start menu select the **Miniforge Prompt**. Change the active working directory, where you download the workshop material, e.g `C:\Users\john\caob24-workshop`

Install all needed Python packages by executing the following command:

> mamba env create --file environment.yml

Click Enter to proceed, wait a few minutes, and installation is done.

## How to access and use JupyterLab?

​To open JupyterLab you need to activate the workshop environment and run Jupyter Lab. Open Miniforge Prompt and enter the following commands:

> mamba activate caob
> jupyter lab

​
After a successful launch, you should see the JupyterLab running in your browser.

To exit the `caob` environment, just cloas the command promt

Alternatively, if you would rather not set up a Python environment on your machine, you may run the course materials using Binder by clicking on the **launch binder** button at the top of this page.

