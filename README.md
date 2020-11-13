# voila-demos

**The goal of this project is to create a few JupyterLab Notebooks to use in testing and demoing the use of Voila.**  

The focus on the design is on creating useful output in Voila.  

Voila creates an interactive page showing all notebook outbook - without showing the code or allowing arbitrary code execution.  

Binder can be used to view either the Jupyer Lab notebook normally or using Voila.  

Instructions for viewing any .ipynb on Github using Voila and Binder can be found here: https://www.kylabendt.com/blog/binder-and-voila-to-display-jupyter-notebooks/

**Files**  
**interact_plots.ipynb** displays sin, cos and tan plots with a interactive sliders to adjust the frequency and amplitude.  It also showcases the ipywidget interact.  You can [view the Voila version on Binder](https://mybinder.org/v2/gh/KylaBendt/voila-demos/master?filepath=voila%2Frender%2Finteract_plots.ipynb).

**requirements.txt** this is used by Binder to get the needed libraries for the project.  It needs all libraries used as imports 
+ voila. 
