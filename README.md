[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/CalCraven/gmso_plotly_visualization/HEAD)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# GMSO Plotly Visualization
The repository contains workflows to create an interactive visualization from any General Molecular Simulation Object (GMSO).

For further information visit the `gmso` documentation at https://gmso.mosdef.org. 

### Contents:
1. [Plotly_Dash_Demo.ipynb](./notebooks/Plot_Dash_Demo.ipynb): Demos conversion to and visualization of gmso objects.
2. [demo_utils.py](./notebooks/demo_utils.py): Functions to assist in conversion to plotly dicts.

## Usage
Clone this repository and create a new conda environment from the file [environment.yml](./environment.yml) and start jupyter.

```shell script
$ git clone https://github.com/calcraven/gmso_plotly_visualization && cd gmso_plotly_visualization
$ conda env create --file environment.yml
$ jupyter notebook
```


Alternatively, you can directly launch this repository in [MyBinder](https://mybinder.org/v2/gh/CalCraven/gmso_plotly_visualization/HEAD).
