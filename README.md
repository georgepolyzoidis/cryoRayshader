# cryoRayshader

The code enables users to visualize spatial data in the cryosphere in 3D animations, including a model of the glacier as well as graphical data visualization. The code is based on the original Rayshader (https://github.com/tylermorganwall/rayshader).
Necessary input data is a DEM of the area, spatial data of the glacier surface changing in time (e.g. data retrieved from satellites or models) and data to visualize on top including glacier velocities, surface features like lakes etc.

Note that distributed glacier thickness data exists for all glaciers globally (consult: https://www.glims.org/RGI/rgi60_dl.html). 
Velocity datasets also become more and more accesible (see for example https://nsidc.org/data/golive/)

Prerequisites are a working installation of R Studio (https://rstudio.com/) as well as working packages as detailed below.

We use data from our research studies to show examples of how the model can be used below.

Visualize modelled mass loss over a clean ice and a debris-covered glacier
------
Model outputs from [Wijngaard et al. (2019)](https://www.frontiersin.org/articles/10.3389/feart.2019.00143/full) (data available on request) allows us to visualize change in space. We do that below for a clean ice (Hintereis, European Alps) and debris-covered glacier (Langtang, Himalaya).



Visualize changing pond cover on a debris-covered glacier
------
We use pond outlines from [Steiner et al. (2019)](https://www.cambridge.org/core/journals/journal-of-glaciology/article/supraglacial-ice-cliffs-and-ponds-on-debriscovered-glaciers-spatiotemporal-distribution-and-characteristics/BEE84C3FF7F8BE25709171E8AE3BED5A) (data available https://doi.pangaea.de/10.1594/PANGAEA.899171) to show the change of water surfaces on a debris-covered glacier in the Himalaya.

![](https://github.com/fidelsteiner/cryoRayshader/blob/master/exampleViz/ponds_example.gif)

