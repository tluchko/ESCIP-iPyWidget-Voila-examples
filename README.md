# iPyWidgets and Voilà examples

<a href="https://chemcompute.org/jupyterhub_internal/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Ftluchko%2FESCIP-iPyWidget-Voila-examples&urlpath=lab%2Ftree%2FESCIP-iPyWidget-Voila-examples%2F&branch=main" target="_blank"><img src="https://chemcompute.org/img/launch-ChemCompute-blue.svg" alt="Launch with ChemCompute"/></a>

This repository contains three examples demonstrating how to add [iPyWidgets](https://ipywidgets.readthedocs.io/en/stable/index.html) to control a simple plot in [matplotlib](https://matplotlib.org) and render a web app/dashboard with [Voilà](https://voila.readthedocs.io/en/stable/using.html). We suggest that you start by reading through the *sin-plot* example and then apply the same steps to *particle-in-a-box* or *titration-simulator* to create your own final version.

All three examples follow the same progression:

1. a static plot,
2. a plot with slider(s) and/or textbox(es) to adjust parameters and an explict 'plot' button,
3. a plot where the data is automatically replotted when the widgets are adjusted, and
4. a plot where the plot is automatically redrawn when the widgets are adjusted.

Starting from the static plot, you add code to recreate the next step.

Hint: The input widgets used in the examples are 
[`FloatSlider`](https://ipywidgets.readthedocs.io/en/stable/examples/Widget%20List.html#FloatSlider), 
[`IntSlider`](https://ipywidgets.readthedocs.io/en/stable/examples/Widget%20List.html#IntSlider), 
[`FloatBox`](https://ipywidgets.readthedocs.io/en/stable/examples/Widget%20List.html#FloatText), and 
[`BoundedFloatBox`](https://ipywidgets.readthedocs.io/en/stable/examples/Widget%20List.html#BoundedFloatText).

