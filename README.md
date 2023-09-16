<!-- <p align="center"> 
  <img src="gif/Pacman Logo2.jpg" alt="Pacman Logo" width="80px" height="80px">
</p> -->
<h1 align="center"> Percolation </h1>
<h3 align="center"> Isfahan University of Technology <a href="https://physics.iut.ac.ir/en">Physics Department</a> Summer School (Ofoq-haye no dar physic) </h3>
<h5 align="center"> Final Project - <a href="https://english.iut.ac.ir/">Isfahan University of Technology</a> (Summer 2023) </h5>

<p align="center"> 
  <img src="images/view.png" alt="Screenshot of the land in the NetLogo simulator" height="568px" width="1128px">
</p>

<!-- TABLE OF CONTENTS -->
<h2 id="table-of-contents"> 📖 Table of Contents</h2>

<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project"> ➤ About The Project</a></li>
    <li><a href="#project-files-description"> ➤ Project Files Description</a></li>
    <li><a href="#our-work"> ➤ Our Work</a></li>
    <li><a href="#results"> ➤ Results</a></li>
    <li><a href="#references"> ➤ References</a></li>
    <li><a href="#credits"> ➤ Credits</a></li>
  </ol>
</details>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- ABOUT THE PROJECT -->
<h2 id="about-the-project"> 📝 About The Project</h2>

<p align="justify">
  Percolation theory in statistical physics describes the behavior of a network when nodes or links are added with a definite probability and we want to explore how a signal spreads through the network. We will explore phase transition in this model in what follows (In particular, site percolation in a 2D lattice).
  
  Fractal dimension is a measure of the complexity of a fractal pattern, describing how the pattern fills space at different scales. It is a way to quantify irregular or self-similar structures that exhibit intricate detail regardless of the level of magnification. The fractal dimension in this context, often denoted as $d_f$​, characterizes the behavior of the giant component's size $S$ as a function of the system size $L$. When the system is close to the percolation threshold, the relationship can be expressed as:

  $$S \propto L ^ {d_f}$$

  Where $d_f$​ is the fractal dimension we are trying to determine. This dimension captures the scaling behavior of the giant component as the system size increases.
</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- PROJECT FILES DESCRIPTION -->
<h2 id="project-files-description"> 💾 Project Files Description</h2>

<ul>
  <li>
    <b>rawgenerator.ipynb</b><span style="font-style: italic; color: #888;"> - Where all of the necessary functions reside</span>
  </li>

  <li>
  <b>Giant Component.ipynb & Population of Burned Trees.ipynb & x.ipynb & y.ipynb &  z0.ipynb</b><span style="font-style: italic; color: #888;"> - Where we generate and export data and plots through simulation</span>
  </li>

  <li>
  <b>Presentation.pptx</b><span style="font-style: italic; color: #888;"> - The slides of our final presentation</span>
  </li>

  <li>
  <b>*.csv</b><span style="font-style: italic; color: #888;"> - Exported data out of the simulation</span>
  </li>
</ul>

<!-- <h3>Some other supporting files</h3>
<ul>
  <li><b>graphicsDisplay.py</b> - Graphics for Pacman.</li>
</ul> -->

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- GETTING STARTED -->
<!-- <h2 id="getting-started"> 📖 Getting Started</h2>

<p>You are able to start the game by typing the following commands in the command line:</p>
<pre><code>$ python pacman.py</code></pre>

<p>You can see the list of all options and their default values via:</p>
<pre><code>$ python pacman.py -h</code></pre>
<i>Note that all of the commands that appear in this project also appear in <code>commands.txt</code>, for easy copying and pasting.</i>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png) -->

<!-- OUR WORK -->
<h2 id="our-work"> 💡 Our Work</h2>

<p align="justify"> 
  In this project, we simulate wildfires with various properties such as vegetation density, wind, field size, and more, using NetLogo. Our objective is to estimate a critical density at which the following ratio changes significantly:

  $$\frac{\log\left( Size\:\:of\:\:the\:\:giant\:\:component \right)}{\log\left( Side\:\:length\:\:of\:\:the\:\:square\:\:corresponding\:\:the\:\:land \right)}$$
</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


<!-- Results -->
<h2 id="results"> 🎉 Results</h2>

<p align="justify"> 
  After extracting data from the simulation, we plotted the following graphs. The first graph demonstrates that at approximately 60 percent density, the size of the giant component exhibits a higher growth rate.
</p>

<figure>
  <figcaption align="center"><i>$$\log\left( Size\:\:of\:\:the\:\:giant\:\:component \right)$$ vs. $$\log\left( Side\:\:length\:\:of\:\:the\:\:square\:\:corresponding\:\:the\:\:land \right)$$</i></figcaption>
  <p align="center"> 
    <img src="images/Giant Component.png" alt="Giant Component" height="648px" width="1102px">
  </p>
</figure>

Also, there are some other graphs as follows:
<figure>
  <figcaption align="center"><i>Population of Burned Trees</i></figcaption>
  <p align="center"> 
    <img src="images/Population of Burned Trees.png" alt="Population of Burned Trees" height="648px" width="1102px">
  </p>
</figure>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- <p>I have implemented the depth-first search (DFS) algorithm in the depthFirstSearch function in <code>search.py</code>.</p>
<p>The Pacman will quickly find a solution via running the following commands:</p>

<pre><code>$ python pacman.py -l tinyMaze -p SearchAgent</code></pre>
<pre><code>$ python pacman.py -l mediumMaze -p SearchAgent</code></pre>
<pre><code>$ python pacman.py -l bigMaze -z .5 -p SearchAgent</code></pre> -->

<!-- <p align="center"> 
<img src="gif/DFS.gif" alt="Animated gif DFS Algorithm" height="282px" width="637px">
height="382px" width="737px"
</p> -->


<!-- REFERENCES -->
<h2 id="References"> 🌏 References</h2>

[1] Wikipedia contributors. (2023, June 22). Percolation. In Wikipedia, The Free Encyclopedia. Retrieved 20:14, August 26, 2023, from https://en.wikipedia.org/w/index.php?title=Percolation&oldid=1161443767

[2] Bak, P., Tang, C., & Wiesenfeld, K. Self-organized criticality: an explanation of 1/f noise, 1987. Phys. Rev. Lett, 59, 381.

[3] Broadbent, S. R., & Hammersley, J. M. (1957, July). Percolation processes: I. Crystals and mazes. In Mathematical proceedings of the Cambridge philosophical society (Vol. 53, No. 3, pp. 629-641). Cambridge University Press.

[4] Wikipedia contributors. (2023, August 3). Percolation theory. In Wikipedia, The Free Encyclopedia. Retrieved 20:15, August 26, 2023, from https://en.wikipedia.org/w/index.php?title=Percolation_theory&oldid=1168497132

[5] Wikipedia contributors. (2023, August 22). Kolmogorov's zero–one law. In Wikipedia, The Free Encyclopedia. Retrieved 20:15, August 26, 2023, from https://en.wikipedia.org/w/index.php?title=Kolmogorov%27s_zero%E2%80%93one_law&oldid=1171645280

[6] Wikipedia contributors. (2023, July 19). Critical exponent. In Wikipedia, The Free Encyclopedia. Retrieved 20:16, August 26, 2023, from https://en.wikipedia.org/w/index.php?title=Critical_exponent&oldid=1166036689

[7] Wikipedia contributors. (2023, August 22). Percolation critical exponents. In Wikipedia, The Free Encyclopedia. Retrieved 20:16, August 26, 2023, from https://en.wikipedia.org/w/index.php?title=Percolation_critical_exponents&oldid=1171736502


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- CREDITS -->
<h2 id="Credits"> 📜 Credits</h2>

Alireza Abrehforoush

[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Alireza-Abrehforoush)
[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alireza-abrehforoush-b6815b19b/)


<a href="https://ir.linkedin.com/in/kavyan-zare-97094b210">Kavyan Zare</a>

<a href="https://ir.linkedin.com/in/ava-moknatjoo-22a60220b">Ava Moknatjoo</a>

<!-- Acknowledgements: Based on UC Berkeley's Pacman AI project, <a href="http://ai.berkeley.edu">http://ai.berkeley.edu</a> -->

