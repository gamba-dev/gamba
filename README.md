# Welcome to the gamba library!
> A Python library for player behaviour tracking research



    ---------------------------------------------------------------------------

    ModuleNotFoundError                       Traceback (most recent call last)

    /tmp/ipykernel_5080/442603745.py in <module>
          1 #export
    ----> 2 from gamba.data import *
          3 from gamba.measures import *
          4 from gamba.statistics import *
          5 from gamba.labelling import *


    ~/Desktop/gamba/gamba/__init__.py in <module>
          5 # Cell
          6 from .data import *
    ----> 7 from .measures import *
          8 from .statistics import *
          9 from .labelling import *


    ~/Desktop/gamba/gamba/measures.py in <module>
        618 
        619 # Cell
    --> 620 from tqdm import tqdm
        621 import datetime, pandas as pd
        622 def calculate_labrie_measures(all_player_bets, savedir="", filename="gamba_labrie_measures.csv", loud=False, daily=True,):


    ModuleNotFoundError: No module named 'tqdm'


[![PyPI](https://img.shields.io/pypi/v/gamba?style=for-the-badge&color=blue)](https://pypi.org/project/gamba/)
[![Commit](https://img.shields.io/github/last-commit/gamba-dev/gamba?label=Last%20update&style=for-the-badge&)](https://github.com/gamba-dev/gamba/commit/main)

The gamba transaction analysis library is a collection of methods for applying analytical methods found in peer-reviewed studies. The library is 100% free and open source, and aims to be used by researchers and analysts with access to transaction data sets.

## Features

- standardise your data across game types and activities
- compute behavioural measures
- apply descriptive and comparative statistics
- run machine learning methods
- replicate full academic studies on your data in minutes

## Getting Started

Getting started using gamba in your research is super easy - the first step is to install the library using one of the commands below. From there, read through one or more of the tutorials, and once you're familiar with the typical structure of an analysis using the gamba library, look through the individual module documentation and extend one of the examples. If you get stuck, please [get in touch](https://twitter.com/ojscholten)!

## Install

To install gamba use the following pip command;

`pip install gamba`

Or if you'd like to use the development release, clone the github repository to your machine;

`git clone https://github.com/gamba-dev/gamba.git`
