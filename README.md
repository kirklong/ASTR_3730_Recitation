# ASTR_3730_Recitation
Course files/labs for ASTR 3730.

Download all the files by clicking the big green button, or for those who are command line savvy (or aspire to be command line savvy) you can do something like:

`git clone https://github.com/kirklong/ASTR_3730_Recitation.git`

However you do it, make sure you download all the files and that you preserve the directory structure wherever you put them. You can also download just the individual files for a given week from that folder, or (if going the command line route) you can just run `git pull` in the directory you originally cloned this repository into to get the most up-to-date version.

**Third lab instructions:**

Make sure you've installed the [`py_mesa`](https://github.com/wmwolf/py_mesa_reader) module, then download the files from the `MESALab3` folder. This is easy if you've already cloned the repository -- just running `git pull` should immediately get you up to date with all of the latest files here! Ask early and often if you have questions about any part of this. If you're on Windows and run into difficulty installing the module I've posted a video walkthrough of me installing it on my Windows side you can find on the Lab 3 page on Canvas. 

**1st (review) week instructions:**

If you plan to do this in Python, make sure you open the Python notebook (ignore the Julia one). You will need the random, matplotlib, numpy, pandas, csv, and scipy packages. I believe those will probably be installed by default if you go the Anaconda route, but if for some reason you're missing any of them I can show you how to install them. If you want to be exceptionally brave and try Julia then you will use the Julia one, but you need to complete the following extra steps:

1. Download and install [Julia](https://julialang.org/downloads/)

2. Follow these [instructions to make Julia work with Jupyter](https://datatofish.com/add-julia-to-jupyter/)

3. Install the DataFrames, Plots, Random, CSV, and FFTW packages. I think everything but (maybe?) FFTW should come pre-installed automatically, but you can add any if they're missing quickly/easily from a Julia session. 
