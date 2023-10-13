# SSVEP Workshop

Interactive SSVEP signal processing and classification workshop using
MOABB and MNE.

Goals:

-   Learn to work with EEG data in python using MOABB and MNE.
-   Implement an EEG preprocessing pipeline.
-   Get acquainted with state-of-the-art SSVEP classification
    algorithms.

## Installation

For this workshop, you'll need a working python environment (version 3.8
or higher). Preferably, make sure you have a python environment manager
like [Anaconda](https://www.anaconda.com/products/distribution) or
[virtualenv](https://pypi.org/project/virtualenv/) installed and
[pip](https://pip.pypa.io/en/stable/) to fetch the necessary packages.

### Using conda

    conda env create ssvep_workshop_env --file environment.yml

### Using virtualenv+pip

    virtualenv .venv
    source .venv/bin/activate
    pip install -r requirements.txt

## Running the interactive notebooks

After installing the requirements, execute the following:

    jupyter notebook

and open the interactive notebooks in your favorite web browser.

## Useful resources

-   MNE documentation: https://mne.tools/stable/index.html
-   MOABB documentation: https://neurotechx.github.io/moabb/index.html
-   pyRiemann documentation:
    https://pyriemann.readthedocs.io/en/latest/index.html
-   MOABB minischool by Sylvain Chevalier:
    https://github.com/sylvchev/moabb_minischool
-   Mike X Cohen's Analyzing Neural Time Series videos:
    https://www.youtube.com/channel/UCUR_LsXk7IYyueSnXcNextQ/playlists?view=50&sort=dd&shelf_id=1
