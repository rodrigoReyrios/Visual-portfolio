Visualization Portfolio
=============

<!-- ![banner]() -->
<!-- ![badge]() -->
<!-- ![badge]() -->
Some sample visualizations from previous projects, experiments, or tutorials. Each is accompanied by some context on what the visual is supposed to convey.

Table of Contents
-----------------

-   [Perlin Noise](#perlin-noise)
-   [Discrete Fish Jumps](#discrete-fish-jumps)
-   [Signal Peak Detection](#signal-peak-detection)
-   [Crash and Barrel](#crash-and-barrel-random-walk)
-   [Author](#authors)



Perlin Noise
------------
![perlin mesh visual](/figs/PerlinNoiseInJulia.png)
Simple implementation of a Perlin noise algorithm as described in [these](https://www.cs.umd.edu/class/spring2018/cmsc425/index.shtml) course notes by Dave Mount and Roger Eastman at the University of Maryland. These notes are in turn based on Ken Perlin's improved algorithm archived [here](https://web.archive.org/web/20180418002912/http://mrl.nyu.edu/~perlin/paper445.pdf).

Discrete Fish Jumps
---------------
![discrete fish jumps](/figs/Modeling_Fish_Jumps.png)

Visual representation of modeling a fish trajectory as a discrete process. An entire fish trajectory can be taken as consequtive, discrete jumps (Left and middle panel). Then from this data distributions are constructed to predict the next burst (Right panel).

Signal Peak Detection
-----------------
![peak detect](/figs/3PanelBurstingFig.png)

Figure showing the process of detecting bust in a speed signal. First the signal is smoothed out using a gausian kernel to identify peaks in the signal (Top panel). Then the detected peaks are overlayed ontop of each other to identify an "average burst" (Bottom, Left panel). Finaly, positions in fish paths where peaks are detected are shown (Bottom right panel).

Crash and Barrel Random Walk
-------------------
![crash and barrel](/figs/crash_and_barrel.png)
Visualization of so called "crash and barrel" random walk. A particle is assigned a constant $\alpha$ which is the probability of turning randomly per unit time. The graph above is a simulation of such a particle colliding ellasticly with a box. Below is a styllized animation following the same principle.

![crash and barrel with style](/vids/ezgif-4-070dbcec9c.gif)


Authors
-------

* Rodrigo Rios [:email:](mailto:rodrigoreyrios@gmail.com)