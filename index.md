---
layout: default
---

# About the Package

Pylj is an open-source Python library to facilitate student interaction with classical atomistic simulation. It is designed to operate within the Jupyter notebook framework, making it easy to implement in the classroom, or computer lab.

It can perform the simulation of a 2D system by molecular dynamics, with both NVE and NVT ensembles available and making use of a Velocity-Verlet integrator, as well as Metropolis Monte-Carlo simulations.

To see the package source code, you can check out the main [repository](https://github.com/arm61/pylj), also available there are some example Jupyter notebooks.
* * *
# Acessing online

Pylj can be accessed and used online through one of two methods:

## JupyterLite

JupyterLite is built on Pyodide, and allows notebooks to be run entirely in the browser, hosted as a github page. This contains the same example notebooks that are available on the main [repository](https://github.com/arm61/pylj).

The notebooks can be accessed [here](maximillian-dolan.github.io/pylj-jupyterlite), or the repository for the page can be accessed [here](https://github.com/maximillian-dolan/pylj-jupyterlite)

## Streamlit

For a less code-heavy version of Pylj simulations, you can use this [dashboard](https://pylj-online.streamlit.app/) built on Streamlit. This is run purely through using sliders to input values and utlises the plotly libray instead of matplotlib.

* * *
# Get in contact

Any issues with the package itself, please raise [here](https://github.com/arm61/pylj/issues).

For any problems with the online version, raise a new issue on the github page for either the [Streamlit](https://github.com/maximillian-dolan/pylj_streamlit/issues) or [JupyterLite](https://github.com/maximillian-dolan/pylj-jupyterlite/issues)
