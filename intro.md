# Text Analytics Workshop 2021

## Software requirements

The workshop will be using `Python 3.7` as a computing environment. In order to be able to follow you will need
a working python installation and a text editor. The presentation and exercise materials and will be distributed as [jupyter 
notebooks](https://jupyter.org/).

- IDE: you can use your editor or IDE of choice. During the online meetings I'll be using [DataSpell](https://www.jetbrains.com/dataspell/) 
  and [PyCharm](https://www.jetbrains.com/pycharm/). DataSpell is still in early preview but is usable and free to use. 
  PyCharm is a commercial product with a free evaluation option and free student subscription. Note: the author is not affiliated with
  Jetbrains.
- You need a working Python 3.7 installation. Newer version will probably also run fine.


### Setup with DataSpell/Pycharm for Windows

1. Download and install [Anaconda 3](https://www.anaconda.com/products/individual) using 
  the default installation options 
2. Download and install [git](https://git-scm.com/download/win) for Windows. Leave the options to their defaults 
3. Download and install PyCharm Communiti Edition: [https://www.jetbrains.com/pycharm/](https://www.jetbrains.com/dataspell/)
4. Open PyCharm, find the "Get from VCS" (version control) button and click on it. This will open a dialogue 
   with two fields. In the URL field, paste the link to the course github repository: [https://github.com/boyko/text-analytics-workshop-2021](https://github.com/boyko/text-analytics-workshop-2021).
   You can change the second field to a directory on your local computer where the course files will be downloaded.
   Click "OK" to start the download.
5. When the download is complete PyCharm will open the new project. Find the `File` menu at the top left part 
   of the interface and click on `Settings`. Find the `Project` section and click on `Python interpreter`.
   On the right part of the dialogue find the cog wheel icon next to the interpreter selection menu,
   click on it and choose "Add".
6. In the new dialog choose the `Conda environment` on the left. Select the `3.7` version of python and click "OK".
7. When the environment creation is finished, click on the `Terminal` button at the bottom of the interface. 
   This will open a new command line interface. Copy and run the following command there to install 
   the python packages in the conda environment.

```
conda env update --file environment.yml --prune
```
